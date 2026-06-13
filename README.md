# Survicate

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
