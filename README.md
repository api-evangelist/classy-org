# Classy (classy-org)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Classy is an online fundraising platform for nonprofits - donation forms, peer-to-peer campaigns, crowdfunding, and event/ticketing pages - built around Organizations, Campaigns, Fundraising Pages, Fundraising Teams, Transactions, Recurring Donation Plans, Members, Supporters, and Designations. GoFundMe acquired Classy in 2022 and announced in 2025 that the Classy product and brand are being folded into GoFundMe Pro; the Classy name is being retired through 2026 while the underlying software, the `api.classy.org/2.0` REST API, and the developer docs (developers.classy.org, now redirecting to developers.gofundme.com/pro) continue to operate under the GoFundMe Pro banner.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/classy-org/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/classy-org/refs/heads/main/apis.yml)

## Tags

- Nonprofit
- Fundraising
- Donations
- Peer to Peer
- Philanthropy
- Payments
- GoFundMe Pro

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Classy Organizations API

Retrieve nonprofit organization records and their nested collections - campaigns, designations, fundraising pages, fundraising teams, supporters, transactions, recurring donation plans, credential sets, and integrations - plus organization-level settings such as branding and engagement configuration.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Organizations
- Nonprofits
- Accounts

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Campaigns API

Create, retrieve, and update campaigns - the donation forms, peer-to-peer drives, crowdfunding pages, and ticketed events nonprofits run on Classy - plus publish/unpublish/deactivate lifecycle actions and nested collections (fundraising pages, fundraising teams, designations, transactions, updates, stories, promo codes, ticket types).

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Campaigns
- Donation Forms
- Peer to Peer

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Fundraising Pages API

Retrieve, update, and delete individual peer-to-peer fundraising pages created under a campaign, including their overview/progress stats, posts, updates, stories, feed items, and soft credits.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Fundraising Pages
- Personal Pages
- Peer to Peer

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Fundraising Teams API

Manage fundraising teams and subteams under a campaign - retrieve, update, and delete teams, list member fundraising pages and subteams, and pull team-level overview/progress stats and activity feeds.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Fundraising Teams
- Peer to Peer
- Groups

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Transactions API

Fetch individual transactions (donations, ticket and merchandise orders) with their line items, source tracking codes, and acknowledgements, list transactions scoped to an organization/campaign/recurring donation plan, and post offline/bulk donation transactions against a campaign.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Transactions
- Donations
- Payments

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Recurring Donation Plans API

Retrieve and update recurring (sustainer) donation plans and list the individual transactions a plan has generated over its billing history.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Recurring Donations
- Subscriptions
- Sustainers

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Members API

Retrieve a Classy member (the account behind a fundraiser or admin user) and list the organizations, fundraising teams, fundraising pages, and recurring donation plans associated with that member.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Members
- Fundraisers
- Accounts

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Supporters API

Retrieve and update supporter records - the donor/CRM profile Classy maintains per organization - and trigger Mailchimp subscribe actions for a supporter.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Supporters
- Donors
- CRM

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Classy Designations API

Retrieve and update designations - the funds/programs an organization or campaign lets donors direct their gift toward - and list an organization's designations or a campaign's unassigned designations.

- **Human URL:** [https://developers.gofundme.com/pro/docs](https://developers.gofundme.com/pro/docs)
- **Base URL:** `https://api.classy.org/2.0`

#### Tags

- Designations
- Funds
- Restricted Giving

#### Properties

- [Documentation](https://developers.gofundme.com/pro/docs)
- [API Reference](https://developers.gofundme.com/pro/api-docs/overview.html)
- [OpenAPI](openapi/classy-org-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/classy-org.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/classy-org.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/classy-org)
- [LinkedIn](https://www.linkedin.com/company/stayclassy)
- [Website](https://www.classy.org)
- [Documentation](https://developers.gofundme.com/pro/docs)
- [Plans](plans/classy-org-plans-pricing.yml)
- [Rate Limits](rate-limits/classy-org-rate-limits.yml)
- [Fin Ops](finops/classy-org-finops.yml)

## Review

[Does Classy expose a documented public WebSocket API?](review.yml) — No. Classy's public API (`api.classy.org/2.0`) is request/response REST authenticated with OAuth2 client credentials; no WebSocket or public webhooks/event-subscription resource is documented.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
