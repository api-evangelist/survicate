# Survicate

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

Survicate is a customer feedback and survey platform that enables teams to collect, analyze, and act on feedback across web, mobile, email, and in-product channels. The platform provides a REST Data Export API, JavaScript SDK, Mobile SDKs (iOS, Android, React Native, Flutter, Unity), and Webhooks for integrating survey feedback into CRM, analytics, and data warehouse solutions.

## API Products

- **Data Export API (v2)** — REST API for retrieving surveys, responses, respondents, and personal data. Authenticated via Basic auth with workspace API keys.
- **JavaScript SDK** — Client-side SDK for embedding and controlling surveys on websites and web apps. Provides methods for visitor targeting, event triggering, and programmatic survey control.
- **Mobile SDKs** — Native survey SDKs for iOS, Android, React Native, Flutter, and Unity with integrations for Segment, UXCam, and FullStory.
- **Webhooks** — Event-driven integrations that subscribe to survey events such as new responses and completions.

## Developer Resources

- Developer Portal: https://developers.survicate.com/
- Data Export API Docs: https://developers.survicate.com/data-export/
- JavaScript API Methods: https://developers.survicate.com/javascript/methods/
- GitHub Organization: https://github.com/Survicate
- Status Page: https://status.survicate.com/

## Pricing

Survicate offers four paid tiers: Starter, Growth ($114/mo annually), Pro ($349/mo), and Enterprise ($569/mo). All plans include Webhooks and the Data Export API. Plans differ by monthly response caps (500 to custom), active survey limits, data retention (6 months to 5+ years), and integration count (25+ to 40+).

Full pricing: https://survicate.com/pricing/

## Rate Limits (Data Export API)

- Maximum 5 concurrent simultaneous requests per workspace
- Maximum 1000 requests per minute per workspace
- Exceeded limits return HTTP 429 Too Many Requests

## Links

- Website: https://survicate.com/
- Blog: https://survicate.com/blog/
- LinkedIn: https://www.linkedin.com/products/survicate/
- X: https://x.com/Survicate
- Pricing: https://survicate.com/pricing/
- Status: https://status.survicate.com/

## APIs.json

This repository contains an APIs.json index conforming to specification version 0.19 that catalogs Survicate's API surface including plans, rate limits, and FinOps guidance.
