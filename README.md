# Centers for Medicare and Medicaid Services (centers-for-medicare-and-medicaid-services)

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

The Centers for Medicare and Medicaid Services (CMS) is the federal agency that provides health coverage to more than 160 million Americans through Medicare, Medicaid, the Children's Health Insurance Program (CHIP), and the Health Insurance Marketplace. CMS operates one of the largest public API programs in the U.S. government, including the FHIR-based Blue Button 2.0, Beneficiary Claims Data API (BCDA), and Data at the Point of Care (DPC); the data.cms.gov Socrata Open Data API covering Medicare claims, provider, and enrollment datasets; the Medicare Provider Data Catalog (Hospital Compare, Nursing Home Compare); the Healthcare.gov Marketplace API; NPPES and NPI Registry APIs; the QPP Measures API; and Medicaid Transformed Medicaid Statistical Information System (T-MSIS) resources.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/centers-for-medicare-and-medicaid-services/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/centers-for-medicare-and-medicaid-services/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- BCDA
- Blue Button
- CMS
- Claims
- DPC
- FHIR
- Federal Government
- Healthcare
- Interoperability
- Marketplace
- Medicaid
- Medicare
- Open Data
- Provider Data
- Socrata

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### CMS Blue Button 2.0 API

Blue Button 2.0 is a standards-based HL7 FHIR R4 API that delivers Medicare Part A, B, and D claims data for over 60 million beneficiaries to registered third-party applications, authorized by the beneficiary through OAuth 2.0. It anchors CMS's Patient Access API program under the 21st Century Cures Act.

- **Human URL:** [https://bluebutton.cms.gov/](https://bluebutton.cms.gov/)
- **Base URL:** `https://api.bluebutton.cms.gov/v2/fhir/`

#### Tags

- Blue Button
- Claims
- FHIR
- Medicare
- OAuth 2.0
- Patient Access

#### Properties

- [Website](https://bluebutton.cms.gov/)
- [Developer](https://bluebutton.cms.gov/developers/)
- [Documentation](https://bluebutton.cms.gov/api-documentation/)
- [Sandbox](https://sandbox.bluebutton.cms.gov/)
- [Resources](https://bluebutton.cms.gov/resources/)
- [OpenAPI](openapi/centers-for-medicare-and-medicaid-services-cms-blue-button-2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CMS Beneficiary Claims Data API (BCDA)

The Beneficiary Claims Data API (BCDA) is a Bulk FHIR API that delivers Medicare Part A, B, and D claims data to Medicare Shared Savings Program ACOs, ACO REACH participants, and other Alternative Payment Model participants for their attributed and assignable beneficiaries.

- **Human URL:** [https://bcda.cms.gov/](https://bcda.cms.gov/)
- **Base URL:** `https://api.bcda.cms.gov/api/v2/`

#### Tags

- ACO
- BCDA
- Bulk FHIR
- Claims
- Medicare
- Shared Savings

#### Properties

- [Website](https://bcda.cms.gov/)
- [Documentation](https://bcda.cms.gov/guide.html)
- [Sandbox](https://sandbox.bcda.cms.gov/)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CMS Data at the Point of Care (DPC) API

Data at the Point of Care is a FHIR Bulk Data API that delivers Original Medicare claims data to fee-for-service providers for the patients currently under their care, enabling clinicians to see a patient's full Medicare history at the point of care.

- **Human URL:** [https://dpc.cms.gov/](https://dpc.cms.gov/)
- **Base URL:** `https://api.dpc.cms.gov/api/v1/`

#### Tags

- Bulk FHIR
- Claims
- FFS
- Point of Care
- Providers

#### Properties

- [Website](https://dpc.cms.gov/)
- [Documentation](https://dpc.cms.gov/docs)
- [Sandbox](https://sandbox.dpc.cms.gov/)
- [F A Q](https://dpc.cms.gov/faq)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CMS Socrata Open Data API (data.cms.gov)

data.cms.gov hosts hundreds of CMS datasets including Medicare Fee-for-Service utilization and payment data, Provider of Services files, Medicare Part B/D Prescriber summaries, Marketplace open enrollment data, and COVID-19 nursing home data, available via the data.cms.gov Data API (JSON) and the CMS Provider Data Catalog Socrata-compatible endpoints.

- **Human URL:** [https://data.cms.gov/](https://data.cms.gov/)
- **Base URL:** `https://data.cms.gov/data.json`

#### Tags

- Datasets
- Medicare
- Open Data
- Provider Data
- SODA
- Socrata

#### Properties

- [Website](https://data.cms.gov/)
- [Documentation](https://data.cms.gov/provider-data/docs)
- [Developer](https://developer.cms.gov/data-cms/)
- [Data A P I](https://data.cms.gov/data-api)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CMS Provider Data Catalog API (Care Compare)

The Provider Data Catalog API (formerly Hospital Compare) exposes the Medicare.gov Care Compare datasets including Hospital, Nursing Home, Home Health, Hospice, Physician, Long-Term Care Hospital, Inpatient Rehab, and Dialysis Facility quality measures as DCAT-based datasets with Datastore query endpoints.

- **Human URL:** [https://data.cms.gov/provider-data/](https://data.cms.gov/provider-data/)
- **Base URL:** `https://data.cms.gov/provider-data/api/1/`

#### Tags

- Care Compare
- Dialysis Compare
- Hospital Compare
- Nursing Home Compare
- Provider Data
- Quality

#### Properties

- [Website](https://data.cms.gov/provider-data/)
- [Documentation](https://data.cms.gov/provider-data/docs)
- [Metastore](https://data.cms.gov/provider-data/api/1/metastore/schemas/dataset/items)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NPPES NPI Registry API

The NPPES NPI Registry API provides free public access to look up active National Provider Identifier records for individual and organizational healthcare providers, supporting FHIR-compatible JSON responses used widely in credentialing, directory, and claims validation workflows.

- **Human URL:** [https://npiregistry.cms.hhs.gov/](https://npiregistry.cms.hhs.gov/)
- **Base URL:** `https://npiregistry.cms.hhs.gov/api/`

#### Tags

- Credentialing
- NPI
- NPPES
- Provider Identifier
- Provider Registry

#### Properties

- [Website](https://npiregistry.cms.hhs.gov/)
- [Documentation](https://npiregistry.cms.hhs.gov/api-page)
- [Help](https://npiregistry.cms.hhs.gov/help-api/)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Healthcare.gov Marketplace API

The Healthcare.gov Marketplace API and accompanying Open Data Plan Finder exposes Qualified Health Plan (QHP) details, plan attributes, provider networks, and formularies for the Federally-Facilitated Marketplace states, enabling third-party plan comparison and enrollment experiences.

- **Human URL:** [https://www.healthcare.gov/developers/](https://www.healthcare.gov/developers/)
- **Base URL:** `https://marketplace.api.healthcare.gov/api/v1/`

#### Tags

- ACA
- Exchange
- Marketplace
- Plan Finder
- QHP

#### Properties

- [Developer](https://www.healthcare.gov/developers/)
- [Examples](https://github.com/CMSgov/marketplace-api-examples)
- [Open Data](https://data.healthcare.gov/)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CMS Quality Payment Program (QPP) Measures API

The Quality Payment Program Measures Data repository and REST API publish machine-readable specifications of MIPS quality, promoting interoperability, improvement activities, and cost measures for each performance year, supporting vendor QPP submissions and analytics.

- **Human URL:** [https://qpp.cms.gov/](https://qpp.cms.gov/)

#### Tags

- MIPS
- Measures
- Quality
- QPP
- Value-Based

#### Properties

- [Website](https://qpp.cms.gov/)
- [Documentation](https://cmsgov.github.io/qpp-measures-data/)
- [Source Code](https://github.com/CMSgov/qpp-measures-data)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Medicare Coverage Database (MCD) API

The Medicare Coverage Database publishes National Coverage Determinations (NCDs), Local Coverage Determinations (LCDs), articles, and coding guidance used to determine Medicare coverage and reimbursement policies, distributed via downloadable datasets and JSON/CSV query endpoints.

- **Human URL:** [https://www.cms.gov/medicare-coverage-database/](https://www.cms.gov/medicare-coverage-database/)

#### Tags

- Coverage
- LCD
- MAC
- NCD
- Policy

#### Properties

- [Website](https://www.cms.gov/medicare-coverage-database/)
- [Downloads](https://www.cms.gov/medicare-coverage-database/downloads/downloads.aspx)
- [Postman Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centers-for-medicare-and-medicaid-services-cms-blue-button-2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.cms.gov/)
- [Developer](https://developer.cms.gov/)
- [Open Data](https://data.cms.gov/)
- [Provider Data](https://data.cms.gov/provider-data/)
- [Blue Button](https://bluebutton.cms.gov/)
- [B C D A](https://bcda.cms.gov/)
- [D P C](https://dpc.cms.gov/)
- [N P P E S](https://npiregistry.cms.hhs.gov/)
- [Marketplace](https://www.healthcare.gov/developers/)
- [Q P P](https://qpp.cms.gov/)
- [GitHub Organization](https://github.com/CMSgov)
- [Privacy Policy](https://www.cms.gov/privacy)
- [Integrations](https://www.cms.gov/marketplace/in-person-assisters/information-partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
