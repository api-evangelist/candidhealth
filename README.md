# Candid Health (candidhealth)

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

Candid Health is an autonomous medical-billing and revenue-cycle management platform. Its REST API lets digital health providers submit encounters and claims, run real-time eligibility checks, capture charges, look up payers and fee schedules, reconcile remits/ERAs, and subscribe to billing events end-to-end.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/candidhealth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/candidhealth/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Medical Billing
- Revenue Cycle
- Claims
- Eligibility

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Candid Health Encounters & Claims API

Submit professional encounters that Candid uses to generate and track insurance claims end-to-end, with service lines, diagnoses, providers, and claim status surfaced through the Encounters V4 endpoints.

- **Human URL:** [https://docs.joincandidhealth.com/api-reference/encounters/v-4/get-all](https://docs.joincandidhealth.com/api-reference/encounters/v-4/get-all)
- **Base URL:** `https://api.joincandidhealth.com/api`

#### Tags

- Encounters
- Claims
- Billing

#### Properties

- [Documentation](https://docs.joincandidhealth.com/api-reference/encounters/v-4/get-all)
- [API Reference](https://docs.joincandidhealth.com/api-reference/encounters/v-4/create)
- [OpenAPI](openapi/candidhealth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candidhealth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candidhealth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Health Eligibility API

Run real-time and batch eligibility checks to confirm active medical coverage and patient benefits (co-pays, deductibles) before and after appointments.

- **Human URL:** [https://docs.joincandidhealth.com/api-reference/eligibility/v-2/submit-eligibility-check](https://docs.joincandidhealth.com/api-reference/eligibility/v-2/submit-eligibility-check)
- **Base URL:** `https://api.joincandidhealth.com/api`

#### Tags

- Eligibility
- Coverage
- Benefits

#### Properties

- [Documentation](https://docs.joincandidhealth.com/api-reference/eligibility/v-2/submit-eligibility-check)
- [API Reference](https://docs.joincandidhealth.com/api-reference/pre-encounter/coverages/v-1/check-eligibility)
- [OpenAPI](openapi/candidhealth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candidhealth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candidhealth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Health Charge Capture API

Capture charges and service-line detail that bundle into encounters, decoupling clinical charge entry from final claim assembly and coding.

- **Human URL:** [https://docs.joincandidhealth.com/api-reference/charge-capture/v-1/create](https://docs.joincandidhealth.com/api-reference/charge-capture/v-1/create)
- **Base URL:** `https://api.joincandidhealth.com/api`

#### Tags

- Charge Capture
- Service Lines
- Coding

#### Properties

- [Documentation](https://docs.joincandidhealth.com/api-reference/charge-capture/v-1/create)
- [OpenAPI](openapi/candidhealth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candidhealth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candidhealth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Health Payers & Fee Schedules API

Look up payers and resolve contracted rates for service lines against configured fee schedules, including rate matching, history, and payer thresholds.

- **Human URL:** [https://docs.joincandidhealth.com/api-reference/payers/v-3/get](https://docs.joincandidhealth.com/api-reference/payers/v-3/get)
- **Base URL:** `https://api.joincandidhealth.com/api`

#### Tags

- Payers
- Fee Schedules
- Rates

#### Properties

- [Documentation](https://docs.joincandidhealth.com/api-reference/payers/v-3/get)
- [API Reference](https://docs.joincandidhealth.com/api-reference/fee-schedules/v-3/get-match)
- [OpenAPI](openapi/candidhealth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candidhealth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candidhealth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Health Remits & ERAs API

Retrieve insurance adjudications (ERA / 835 remittance detail) and reconcile payer payments, refunds, and write-offs against submitted claims.

- **Human URL:** [https://docs.joincandidhealth.com/api-reference/insurance-adjudications/v-1/get](https://docs.joincandidhealth.com/api-reference/insurance-adjudications/v-1/get)
- **Base URL:** `https://api.joincandidhealth.com/api`

#### Tags

- Remits
- ERA
- Adjudications

#### Properties

- [Documentation](https://docs.joincandidhealth.com/api-reference/insurance-adjudications/v-1/get)
- [OpenAPI](openapi/candidhealth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candidhealth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candidhealth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Candid Health Webhooks & Events API

Scan and retrieve billing lifecycle events used to drive webhook-style notifications as encounters, claims, and remits change state.

- **Human URL:** [https://docs.joincandidhealth.com/api-reference/events/v-1/get](https://docs.joincandidhealth.com/api-reference/events/v-1/get)
- **Base URL:** `https://api.joincandidhealth.com/api`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.joincandidhealth.com/api-reference/events/v-1/get)
- [OpenAPI](openapi/candidhealth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/candidhealth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/candidhealth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/candidhealth)
- [LinkedIn](https://www.linkedin.com/company/candidhealth)
- [Website](https://www.joincandidhealth.com)
- [Documentation](https://docs.joincandidhealth.com)
- [Plans](plans/candidhealth-plans-pricing.yml)
- [Rate Limits](rate-limits/candidhealth-rate-limits.yml)
- [Fin Ops](finops/candidhealth-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
