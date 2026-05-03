# Southwest Gas

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
