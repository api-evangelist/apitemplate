# APITemplate.io (apitemplate)

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

APITemplate.io is a templating service that auto-generates PDFs and images programmatically from HTML/CSS templates with Jinja2-style data binding. Drag-and-drop visual editor; sync and async generation with webhooks; regional endpoints in US, EU, Singapore and Australia.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **APITemplate.io REST** — `https://rest.apitemplate.io/v2` — generate PDFs (HTML, URL, visual-editor templates) and images. Bearer-token auth. SDKs for Python, JavaScript, PHP, C# and Java. [Docs](https://apitemplate.io/docs/) · [API Reference](https://apitemplate.io/api-reference/).

## OpenAPI
APITemplate.io does not currently publish a downloadable OpenAPI/Swagger document at a stable public URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
Document Generation, PDF, Images, Templates, API, Jinja2

## Common Properties
- [Website](https://apitemplate.io/) · [Docs](https://apitemplate.io/docs/) · [Pricing](https://apitemplate.io/pricing/) · [GitHub](https://github.com/apitemplateio)
- [Plans](plans/apitemplate-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/apitemplate-rate-limits.yml) — partially reconciled (per-second numeric limits not public)
- [FinOps](finops/apitemplate-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled — annual prices)
**PDF-only:**
- **Free** — 50 PDFs/mo, 3 templates.
- **PDF Basic** — $19/mo, 3,000 PDFs, 20 templates.
- **PDF Standard** — $69/mo, 12,000 PDFs, 180 templates.
- **PDF Enterprise** — $139/mo, 25,000 PDFs, unlimited templates.

**Image + PDF combined:**
- **Starter** — $29/mo, 1,500 outputs, 15 templates.
- **Standard** — $69/mo, 9,000 outputs, 150 templates.
- **Enterprise** — $139/mo, 20,000 outputs, unlimited templates.

PAYG overage available on Enterprise. Monthly billing is 15–30% more than annual.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
