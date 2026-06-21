# Candid Health (candidhealth)

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
