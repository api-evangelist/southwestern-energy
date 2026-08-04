# Southwestern Energy

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

Southwestern Energy Company (SWN) is one of the largest producers of natural gas in the United States, with exploration and production operations focused primarily on the Marcellus and Haynesville shales. In October 2024, Southwestern Energy completed a merger with Expand Energy Corporation (formerly Chesapeake Energy), though the SWN brand and investor relations infrastructure continues to operate under swn.com. As a Fortune 500 energy company, SWN focuses on responsible development of natural gas resources in the Appalachian Basin and Gulf Coast regions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/southwestern-energy/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Fortune 500
- Natural Gas
- Energy
- Oil And Gas

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-02

## APIs

### Southwestern Energy Investor Relations API

The Southwestern Energy investor relations portal provides financial data, shareholder information, earnings summaries, SEC filings, and corporate governance information. The investor relations infrastructure continues to operate at ir.swn.com following the merger with Expand Energy Corporation.

- [Investor Relations Portal](https://ir.swn.com/CorporateProfile/default.aspx)
- [Investor FAQ](https://ir.swn.com/resources/investor-faq/default.aspx)
- [Shareholder Information](https://www.swn.com/investors/shareholder-information/)
- [JSON Schema - Production](https://raw.githubusercontent.com/api-evangelist/southwestern-energy/refs/heads/main/json-schema/southwestern-energy-production-schema.json)

### Expand Energy Investor Relations API

Following the merger, Expand Energy Corporation's investor relations portal provides access to combined company financial data, earnings releases, SEC filings, and investor presentations for the merged natural gas production company.

- [Investor Relations](https://investors.expandenergy.com/)
- [Annual Report](https://investors.expandenergy.com/static-files/e946a7e5-4ef1-4e8b-ba7b-f51506895db0)

## Common Properties

- [Website](https://www.swn.com)
- [Investor Relations](https://ir.swn.com/)
- [Expand Energy](https://www.expandenergy.com/)
- [LinkedIn](https://www.linkedin.com/company/southwestern-energy)
- [X (Twitter)](https://twitter.com/SWNenergy)

## Artifacts

### JSON Schemas

| Schema | Description |
|---|---|
| [southwestern-energy-production-schema.json](json-schema/southwestern-energy-production-schema.json) | Natural gas production data for SWN operating areas and shale plays |

### JSON Structure

| Structure | Description |
|---|---|
| [southwestern-energy-production-structure.json](json-structure/southwestern-energy-production-structure.json) | Hierarchical structure of operating areas, production records, and wells |

### JSON-LD Context

| Context | Description |
|---|---|
| [southwestern-energy-context.jsonld](json-ld/southwestern-energy-context.jsonld) | Linked data context mapping SWN vocabulary to schema.org |

### Examples

| Example | Description |
|---|---|
| [southwestern-energy-production-example.json](examples/southwestern-energy-production-example.json) | Sample Q3 2025 Marcellus shale production report |

### Vocabulary

| Vocabulary | Description |
|---|---|
| [southwestern-energy-vocabulary.yml](vocabulary/southwestern-energy-vocabulary.yml) | Domain vocabulary for natural gas E&P operations and shale terminology |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
