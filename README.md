# Prolific (prolific-research)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
