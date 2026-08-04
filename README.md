# Owner.com (owner-com)

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

Owner.com is an all-in-one, done-for-you digital platform for independent restaurants. A single per-location subscription bundles an AI-built restaurant website with SEO, commission-free online and direct ordering, a branded mobile app, email/SMS and push marketing with automated campaigns, a loyalty and rewards program, delivery and catering management, and reporting and analytics. The company (Palo Alto, CA; founded 2018 as ProfitBoss, rebranded to Owner.com in 2021) positions itself as the platform independent restaurants use to win online and reduce dependence on third-party delivery marketplaces.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/owner-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/owner-com/refs/heads/main/apis.yml)

## API Access Model

**Owner.com does not expose a public or partner developer API.** It is a closed, managed SaaS product built for non-technical restaurant operators as a fully done-for-you service. There is:

- No developer portal, API reference, or published OpenAPI/GraphQL/AsyncAPI specification.
- No self-serve API keys, OAuth application registration, or webhook subscription surface for third parties.
- No public SDK or CLI.

Owner.com markets **POS integrations** (Toast, Clover, Square) and **payment integrations** (Stripe, Apple Pay, Google Pay), but these are provisioned and configured by Owner.com's own onboarding/support team rather than offered as documented, programmatic endpoints that outside developers can call. Prospective integrators are directed to Owner.com support (`support@owner.com`, 1-844-246-9637) or the "Partner with Owner" channel, not to API documentation.

This repository is therefore an **honest stub**: it documents Owner.com as a real, notable provider in the restaurant technology space that currently has **no public API surface to catalog**. The `apis.yml` intentionally lists no `apis:` entries. If Owner.com later publishes a developer API, this entry should be revisited and expanded with real, sourced endpoints.

## Tags

- Restaurants
- Online Ordering
- Restaurant Marketing
- Loyalty
- Website Builder
- Food and Beverage
- SMB
- SaaS
- No Public API

## Timestamps

- **Created:** 2026-07-04
- **Modified:** 2026-07-04

## Pricing (Platform Subscription, not API)

Owner.com is sold as a month-to-month per-location subscription (no long-term contract). Publicly reported plans as of mid-2026:

- **Flex Plan** — ~$249/month plus a ~5% per-order fee.
- **Flat-Rate Plan** — ~$499/month with no per-order commission.
- **Setup/implementation** — ~$1,000 one-time; ~$299 for each additional location.
- **Guest order support fee** — ~5% charged to the guest on direct orders.
- **Delivery** — zero-commission model, flat ~$7 per delivery passed to the restaurant.

These are platform/subscription plans, not API access plans. See [plans/owner-com-plans-pricing.yml](plans/owner-com-plans-pricing.yml). Verify current rates on the [Owner.com pricing page](https://www.owner.com/pricing) during reconciliation.

## Common Properties

- [Website](https://www.owner.com)
- [LinkedIn](https://www.linkedin.com/company/owner-com)
- [Documentation / Help Center](https://help.owner.com)
- [Pricing](https://www.owner.com/pricing)
- [Plans](plans/owner-com-plans-pricing.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
