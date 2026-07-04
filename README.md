# Prolific (prolific-research)

Prolific is an online research participant recruitment platform that connects researchers and AI teams with a large, vetted pool of human participants for surveys, experiments, and data annotation. The Prolific API is a versioned REST interface (`https://api.prolific.com/api/v1`) authenticated with an API token that lets researchers programmatically create and publish studies, review and approve submissions, manage participant groups, projects and workspaces, apply demographic filters and requirements, pay bonuses, message participants, and subscribe to event webhooks (hooks).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/prolific-research/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/prolific-research/refs/heads/main/apis.yml)

## Tags

- Research
- Participant Recruitment
- Surveys
- Human Data
- Crowdsourcing
- Data Annotation
- AI Training

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## Authentication

All requests require an `Authorization` header with the value `Token <your token>`. Create an API token in your Prolific account settings. The base URL is `https://api.prolific.com/api/v1`.

## APIs

### Prolific Studies API

Create draft studies, list and retrieve studies (optionally by project), update, delete, calculate and show cost, duplicate, and transition study status (publish, start, pause, stop) to recruit participants for a survey or task.

- **Human URL:** [https://docs.prolific.com/api-reference/studies](https://docs.prolific.com/api-reference/studies)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Studies
- Recruitment
- Publishing

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/studies)
- [API Reference](https://docs.prolific.com/api-reference/studies/get-studies)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Submissions API

List submissions for a study, retrieve a submission, transition a submission (approve or reject), request that a participant return their submission, and bulk approve submissions once a participant has completed a study.

- **Human URL:** [https://docs.prolific.com/api-reference/submissions](https://docs.prolific.com/api-reference/submissions)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Submissions
- Approvals
- Reviews

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/submissions)
- [API Reference](https://docs.prolific.com/api-reference/submissions/get-submissions)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Participant Groups API

Create and manage saved, dynamic groups of participant IDs so you can re-contact the same participants across studies - list, get, update, and delete groups, and add or remove participants used as allowlist or blocklist filters.

- **Human URL:** [https://docs.prolific.com/api-reference/participant-groups](https://docs.prolific.com/api-reference/participant-groups)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Participant Groups
- Allowlist
- Panels

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/participant-groups)
- [API Reference](https://docs.prolific.com/api-reference/participant-groups/get-participant-groups)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Projects API

Organize studies within a workspace by project - list all projects in a workspace, create a project, retrieve a project, and update a project, including managing project members and access.

- **Human URL:** [https://docs.prolific.com/api-reference/projects/get-projects](https://docs.prolific.com/api-reference/projects/get-projects)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Projects
- Organization

#### Properties

- [API Reference](https://docs.prolific.com/api-reference/projects/get-projects)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Workspaces API

List and create workspaces, retrieve and update a workspace, and read a workspace's wallet balance and cost breakdown - the top-level container that holds projects, funds studies, and scopes team collaboration.

- **Human URL:** [https://docs.prolific.com/api-reference/workspaces/get-workspace](https://docs.prolific.com/api-reference/workspaces/get-workspace)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Workspaces
- Balance
- Billing

#### Properties

- [API Reference](https://docs.prolific.com/api-reference/workspaces/get-workspace)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Messages API

Retrieve messages between you and participants, send a message to an individual participant, send to multiple participants or to a participant group, and retrieve unread messages to send reminders, thank participants, or answer questions.

- **Human URL:** [https://docs.prolific.com/api-reference/messages](https://docs.prolific.com/api-reference/messages)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Messages
- Communication

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/messages)
- [API Reference](https://docs.prolific.com/api-reference/messages/get-messages)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Hooks (Webhooks) API

Subscribe to Prolific events (such as submission.status.change and study.status.change) instead of polling - list subscribable event types, manage signing secrets, create, retrieve, confirm, update, and delete subscriptions, and read delivered events. Hook deliveries are HMAC-SHA256 signed via `X-Prolific-Request-Signature`.

- **Human URL:** [https://docs.prolific.com/api-reference/webhooks](https://docs.prolific.com/api-reference/webhooks)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Webhooks
- Hooks
- Events

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/webhooks)
- [API Reference](https://docs.prolific.com/api-reference/webhooks/verifying)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Requirements & Filters API

List all demographic and screening filters (requirements) that can be applied to a study or filter set, read a filter's distribution, and count how many eligible participants match a set of filters before publishing a study.

- **Human URL:** [https://docs.prolific.com/api-reference/filters/filters-overview](https://docs.prolific.com/api-reference/filters/filters-overview)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Filters
- Requirements
- Prescreening

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/filters/filters-overview)
- [API Reference](https://docs.prolific.com/api-reference/filters/get-filters)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Bonuses API

Reward exceptional or follow-up work with bonus payments - set up bulk bonus payments for a study from CSV of participant/submission IDs and amounts (up to 200 participants per request), then pay them asynchronously against your workspace balance.

- **Human URL:** [https://docs.prolific.com/api-reference/bonuses](https://docs.prolific.com/api-reference/bonuses)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Bonuses
- Payments

#### Properties

- [Documentation](https://docs.prolific.com/api-reference/bonuses)
- [API Reference](https://docs.prolific.com/api-reference/bonuses/pay-bonus-payments)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Prolific Users API

Retrieve the authenticated researcher account (users/me) with ID and email, retrieve a user, and read user identity information used to scope workspaces, projects, and API token access.

- **Human URL:** [https://docs.prolific.com/api-reference/users/get-user](https://docs.prolific.com/api-reference/users/get-user)
- **Base URL:** `https://api.prolific.com/api/v1`

#### Tags

- Users
- Account
- Identity

#### Properties

- [API Reference](https://docs.prolific.com/api-reference/users/get-user)
- [OpenAPI](openapi/prolific-research-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/prolific-research.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/prolific-research.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/prolific-oss)
- [LinkedIn](https://www.linkedin.com/company/prolific-com)
- [Website](https://www.prolific.com)
- [Documentation](https://docs.prolific.com)
- [Plans](plans/prolific-research-plans-pricing.yml)
- [Rate Limits](rate-limits/prolific-research-rate-limits.yml)
- [Fin Ops](finops/prolific-research-finops.yml)
- [Blog](https://www.prolific.com/resources/blog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
