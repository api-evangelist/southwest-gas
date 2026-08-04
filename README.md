# Southwest Gas

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

Southwest Gas Holdings is a natural gas distribution company that purchases, distributes, and transports natural gas for customers in Arizona, Nevada, and California. As a Fortune 1000 utility company headquartered in Las Vegas, Nevada, Southwest Gas serves over 2 million customers through its regulated utility segment and also operates Centuri Group, a full-service utility infrastructure services company.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/southwest-gas/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Fortune 1000
- Natural Gas
- Utility
- Energy

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-02

## APIs

### Southwest Gas My Account API

The Southwest Gas My Account API powers the online customer portal and mobile application for natural gas utility customers in Arizona, Nevada, and California. Customers can view usage history, pay bills, manage account settings, and receive outage notifications through the portal.

- [Customer Portal](https://myaccount.swgas.com/Portal/)
- [Mobile App](https://www.swgas.com/en/mobile-app)
- [JSON Schema - Account](https://raw.githubusercontent.com/api-evangelist/southwest-gas/refs/heads/main/json-schema/southwest-gas-account-schema.json)
- [JSON Schema - Usage](https://raw.githubusercontent.com/api-evangelist/southwest-gas/refs/heads/main/json-schema/southwest-gas-usage-schema.json)

### Southwest Gas Agency Portal API

The Southwest Gas Agency Portal provides access for charitable organizations and assistance agencies to look up customer accounts and submit utility assistance pledges on behalf of customers in need.

- [Agency Portal](https://agency.swgas.com/Portal/)
- [Agency Portal FAQs](https://h1www.swgas.com/en/agency-portal-faqs)

## Common Properties

- [Website](https://www.swgas.com)
- [Customer Portal](https://myaccount.swgas.com/)
- [Agency Portal](https://agency.swgas.com/Portal/)
- [Mobile App](https://www.swgas.com/en/mobile-app)
- [Investor Relations](https://investors.swgasholdings.com/)
- [LinkedIn](https://www.linkedin.com/company/southwest-gas)
- [X (Twitter)](https://twitter.com/SouthwestGas)

## Artifacts

### JSON Schemas

| Schema | Description |
|---|---|
| [southwest-gas-account-schema.json](json-schema/southwest-gas-account-schema.json) | Natural gas customer account with service address and billing data |
| [southwest-gas-usage-schema.json](json-schema/southwest-gas-usage-schema.json) | Monthly natural gas usage records in therms and CCF |

### JSON Structure

| Structure | Description |
|---|---|
| [southwest-gas-account-structure.json](json-structure/southwest-gas-account-structure.json) | Hierarchical structure of account, meter, usage, and agency pledge entities |

### JSON-LD Context

| Context | Description |
|---|---|
| [southwest-gas-context.jsonld](json-ld/southwest-gas-context.jsonld) | Linked data context mapping Southwest Gas vocabulary to schema.org |

### Examples

| Example | Description |
|---|---|
| [southwest-gas-account-example.json](examples/southwest-gas-account-example.json) | Sample Nevada residential customer account |
| [southwest-gas-usage-example.json](examples/southwest-gas-usage-example.json) | Sample monthly natural gas usage record |

### Vocabulary

| Vocabulary | Description |
|---|---|
| [southwest-gas-vocabulary.yml](vocabulary/southwest-gas-vocabulary.yml) | Domain vocabulary for Southwest Gas utility distribution operations |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
