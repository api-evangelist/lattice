# Lattice GraphQL Schema

## Overview

This document describes a conceptual GraphQL schema for the Lattice people success platform. Lattice publicly exposes REST APIs (Talent API v1 and HRIS API v2), but the types defined here model the full domain of Lattice's product surface — performance management, OKRs, goal tracking, continuous feedback, engagement surveys, compensation, HRIS, and integrations — as a unified GraphQL type system.

The schema is derived from Lattice's public developer documentation at https://developers.lattice.com, the API reference at https://help.lattice.com/hc/en-us/articles/360026264713-API-Overview, and Lattice's published product capabilities.

## Schema Source

- **Provider:** Lattice (latticehq.com)
- **Schema type:** Conceptual (REST-derived, not a native GraphQL endpoint)
- **Derived from:** Lattice Talent API v1, Lattice HRIS API v2
- **Base URLs:** https://api.latticehq.com/v1 (Talent), https://api.latticehq.com/v2 (HRIS)
- **Authentication:** API key (header: `Authorization: Bearer <key>`)
- **Schema file:** lattice-schema.graphql

## Domain Coverage

| Domain | Types |
|---|---|
| People & Org | Employee, EmployeeProfile, Manager, DirectReport, Team, Department |
| Goals & OKRs | OKR, Objective, KeyResult, Goal, GoalUpdate |
| Performance | Review, ReviewCycle, ReviewQuestion, ReviewAnswer, ReviewRequest, CheckIn, OneOnOne |
| Feedback | Feedback, PublicFeedback, PrivateFeedback, RequestedFeedback, Praise |
| Nominations | Nomination, NominationRound |
| Engagement | EngagementSurvey, SurveyQuestion, SurveyResponse, PulseCheck |
| Development | GrowthArea, DevelopmentPlan, Achievement, Badge |
| Collaboration | CommentThread, Comment, Notification |
| Compensation | Compensation, CompensationBand, Market, Range |
| Platform | User, Permission, Admin, APIKey, Webhook, Integration, HRIS, Slack, Calendar |

## Type Count

55 named types (excluding scalars and enums).

## Key Relationships

- An `Employee` belongs to one `Department` and may have one `Manager`.
- A `ReviewCycle` contains many `Review` records, each linked to an `Employee`.
- `Objective` records aggregate `KeyResult` records into an `OKR`.
- `Goal` records have ordered `GoalUpdate` entries tracking progress over time.
- `EngagementSurvey` contains `SurveyQuestion` records; each `Employee` produces a `SurveyResponse`.
- `Feedback` is polymorphic: subtypes `PublicFeedback`, `PrivateFeedback`, and `RequestedFeedback` extend the base interface.
- `Compensation` links to `CompensationBand`, `Market`, and `Range` for total-rewards modeling.
- `Integration` is the base type for `HRIS`, `Slack`, and `Calendar` integration records.

## Usage Notes

- All list fields support cursor-based pagination via `after: String` and `first: Int` arguments, matching the Lattice REST API convention.
- Mutations follow the Relay mutation convention: each mutation takes a single `input` argument and returns a payload type.
- Enum values (ReviewStatus, GoalStatus, SurveyStatus, etc.) are defined inline in the schema file.
- The `ID` scalar maps to Lattice's string-based UUID identifiers.
