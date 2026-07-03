# Classy (classy-org)

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
