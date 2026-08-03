# 46elks (46elks)

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

46elks is a Swedish communications platform as a service (CPaaS) offering a simple HTTP REST API for sending and receiving SMS and MMS, making and receiving voice calls with programmable call actions, provisioning virtual phone numbers, and handling media and recordings. The API uses HTTP Basic authentication with an API username and password, and is billed pay-as-you-go.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/46elks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/46elks/refs/heads/main/apis.yml)

## Tags

- CPaaS
- SMS
- MMS
- Voice
- Messaging
- Phone Numbers
- Communications

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### 46elks SMS API

Send and receive text messages worldwide. POST to /sms with from, to, and message, with support for delivery reports (whendelivered webhook), dry runs, flash SMS, and alphanumeric sender IDs. GET /sms and /sms/{id} retrieve message history.

- **Human URL:** [https://46elks.com/docs/send-sms](https://46elks.com/docs/send-sms)
- **Base URL:** `https://api.46elks.com/a1`

#### Tags

- SMS
- Messaging
- Text

#### Properties

- [Documentation](https://46elks.com/docs/send-sms)
- [API Reference](https://46elks.com/docs)
- [OpenAPI](openapi/46elks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/46elks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/46elks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 46elks MMS API

Send picture messages (MMS) to mobile phones. POST to /mms with from, to, message, and image data, and GET /mms and /mms/{id} to retrieve MMS history.

- **Human URL:** [https://46elks.com/docs/send-mms](https://46elks.com/docs/send-mms)
- **Base URL:** `https://api.46elks.com/a1`

#### Tags

- MMS
- Messaging
- Media

#### Properties

- [Documentation](https://46elks.com/docs/send-mms)
- [API Reference](https://46elks.com/docs)
- [OpenAPI](openapi/46elks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/46elks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/46elks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 46elks Voice Calls API

Make and receive programmable voice calls. POST to /calls with from, to, and voice_start driving JSON call actions (connect, play, ivr, record, hangup) delivered via webhook, plus whenhangup callbacks. GET /calls and /calls/{id} retrieve call history.

- **Human URL:** [https://46elks.com/docs/make-call](https://46elks.com/docs/make-call)
- **Base URL:** `https://api.46elks.com/a1`

#### Tags

- Voice
- Calls
- IVR

#### Properties

- [Documentation](https://46elks.com/docs/make-call)
- [API Reference](https://46elks.com/docs)
- [OpenAPI](openapi/46elks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/46elks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/46elks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 46elks Phone Numbers API

Allocate, configure, and deallocate virtual phone numbers. POST to /numbers to rent a number and set sms_url / voice_start handlers, GET /numbers to list, and POST or DELETE /numbers/{id} to reconfigure or release a number.

- **Human URL:** [https://46elks.com/docs/allocate-phone-number](https://46elks.com/docs/allocate-phone-number)
- **Base URL:** `https://api.46elks.com/a1`

#### Tags

- Phone Numbers
- Provisioning
- Virtual Numbers

#### Properties

- [Documentation](https://46elks.com/docs/allocate-phone-number)
- [API Reference](https://46elks.com/docs)
- [OpenAPI](openapi/46elks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/46elks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/46elks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 46elks Media API

Access media generated by the platform - GET /recordings for call recordings and GET /images for MMS image history - for archiving, transcription, and playback workflows.

- **Human URL:** [https://46elks.com/docs/recordings](https://46elks.com/docs/recordings)
- **Base URL:** `https://api.46elks.com/a1`

#### Tags

- Media
- Recordings
- Images

#### Properties

- [Documentation](https://46elks.com/docs/recordings)
- [API Reference](https://46elks.com/docs)
- [OpenAPI](openapi/46elks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/46elks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/46elks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### 46elks Verification API

Phone number verification and one-time passcodes (OTP / 2FA) built on the SMS and voice call primitives - generate a code, deliver it via POST /sms or a spoken IVR POST /calls, and confirm the user-entered value in your application.

- **Human URL:** [https://46elks.com/kb/verify-phone-number](https://46elks.com/kb/verify-phone-number)
- **Base URL:** `https://api.46elks.com/a1`

#### Tags

- Verification
- OTP
- Two-Factor

#### Properties

- [Documentation](https://46elks.com/kb/verify-phone-number)
- [API Reference](https://46elks.com/docs)
- [OpenAPI](openapi/46elks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/46elks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/46elks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/46elks)
- [LinkedIn](https://www.linkedin.com/company/46elks)
- [Website](https://46elks.com/)
- [Documentation](https://46elks.com/docs)
- [Plans](plans/46elks-plans-pricing.yml)
- [Rate Limits](rate-limits/46elks-rate-limits.yml)
- [Fin Ops](finops/46elks-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
