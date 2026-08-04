# Domino's Pizza (dominos-pizza)

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

Domino's Pizza is a major US quick-service restaurant corporation and Fortune 1000 company. Domino's does NOT publish an official public developer API or a developer portal. Its digital ordering surface is delivered through consumer channels - the dominos.com website, the Domino's mobile apps, and the "AnyWare" ordering platform (text, voice, smart TV, Amazon Echo, Google Home, and more), including the "Dom" virtual voice ordering assistant. The undocumented HTTP endpoints behind these first-party apps have been reverse-engineered by the developer community into well-known UNOFFICIAL wrapper libraries (the npm "dominos" / node-dominos-pizza-api package and the Python "pizzapi" / "dominos" packages). These community libraries are not endorsed, supported, or warranted by Domino's. Domino's does expose APIs to select delivery-marketplace partners (e.g. Uber Eats, Just Eat) through direct partnership and a private Postman workspace, but these are not publicly available. No official API specification, pricing, or rate-limit policy is published.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dominos-pizza/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Food Service, Restaurants, QSR, Online Ordering

## Timestamps

- **Created:** 2026-04-19
- **Modified:** 2026-06-02

## Common Properties

- [Website](https://www.dominos.com)
- [Domino's AnyWare Ordering Platform](https://anyware.dominos.com/)
- [Domino's Engineering / Tech Blog (UK)](https://tech.dominos.co.uk/)
- [GitHubOrganization](https://github.com/dominos-pizza)
- [LinkedIn](https://www.linkedin.com/company/dominos-pizza-inc)
- [node-dominos-pizza-api (Unofficial Community Wrapper)](https://github.com/RIAEvangelist/node-dominos-pizza-api)
- [dominos (Unofficial Node.js Community Library)](https://www.npmjs.com/package/dominos)
- [pizzapi (Unofficial Python Community Wrapper)](https://github.com/ggrammar/pizzapi)
- [dominos (Unofficial Python Community Library)](https://pypi.org/project/dominos/)

## Commercial Profile

> Note: Domino's has no official public API. The files below document the *absence* of a commercial API surface and the unofficial community-discovered access, with `reconciled: false`. No artifacts (OpenAPI, AsyncAPI, JSON Schema, capabilities, vocabulary) are generated because there is no official API to describe.

- [Plans & Pricing](plans/dominos-pizza-plans-pricing.yml) — API Commons Plans 0.1 (no commercial plans; unofficial access only)
- [Rate Limits](rate-limits/dominos-pizza-rate-limits.yml) — API Commons Rate Limits 0.1 (no published limits)
- [FinOps](finops/dominos-pizza-finops.yml) — FinOps Framework / FOCUS alignment (no API billing relationship)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
