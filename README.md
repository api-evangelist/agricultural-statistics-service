# Agricultural Statistics Service (agricultural-statistics-service)

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

The National Agricultural Statistics Service (NASS) is an agency of the United States Department of Agriculture (USDA) whose mission is to support the United States, its agricultural sector, and rural communities by providing accurate, objective, and meaningful statistical information and services. NASS operates the QuickStats API for programmatic access to agricultural survey and census data, as well as geospatial APIs for cropland data, vegetation conditions, and crop moisture monitoring covering the continental United States.

**URL:** [https://www.nass.usda.gov/](https://www.nass.usda.gov/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agriculture, Federal Government, Statistics, Open Data, Geospatial

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-04-19

## APIs

### USDA NASS QuickStats API
The QuickStats API provides direct programmatic access to the statistical information contained in the NASS Quick Stats database, covering official published aggregate estimates related to U.S. agricultural production from NASS surveys and the Census of Agriculture. Supports filtering by commodity, location, and time with comparison operators. Returns data in JSON, XML, or CSV format.

**Human URL:** [https://quickstats.nass.usda.gov/api](https://quickstats.nass.usda.gov/api)

#### Tags:

 - Agricultural Statistics, Crop Data, Livestock Data, Census Of Agriculture, Open Data

#### Properties

- [Documentation](https://quickstats.nass.usda.gov/api)
- [API Reference](https://quickstats.nass.usda.gov/api/#param_define)
- [Authentication](https://quickstats.nass.usda.gov/api)
- [OpenAPI](openapi/agricultural-statistics-service-quickstats-api.yaml)
- [Statistics Record Schema](json-schema/quickstats-api-statistics-record-schema.json)
- [Statistics Response Schema](json-schema/quickstats-api-statistics-response-schema.json)
- [Count Response Schema](json-schema/quickstats-api-count-response-schema.json)
- [Statistics Record Structure](json-structure/quickstats-api-statistics-record-structure.json)
- [JSON-LD Context](json-ld/agricultural-statistics-service-quickstats-api-context.jsonld)

### USDA NASS CroplandCROS API
The CroplandCROS API provides access to the Cropland Data Layer (CDL), a crop-specific land cover data layer with 30-meter spatial resolution covering the continental United States. Historical CDL data is available back to 1997 for select states.

**Human URL:** [https://www.nass.usda.gov/developer/index.php](https://www.nass.usda.gov/developer/index.php)

#### Tags:

 - Cropland, Geospatial, Remote Sensing, Land Cover

#### Properties

- [Documentation](https://www.nass.usda.gov/developer/index.php)
- [Data API](https://nassgeodata.gmu.edu/CropScapeService)

### USDA NASS VegScape API
The VegScape API delivers vegetation condition indices at 250-meter spatial resolution covering the continental United States. Data includes daily and weekly vegetation index composites available since 2000.

**Human URL:** [https://www.nass.usda.gov/developer/index.php](https://www.nass.usda.gov/developer/index.php)

#### Tags:

 - Vegetation, Geospatial, Crop Monitoring, Remote Sensing

#### Properties

- [Documentation](https://www.nass.usda.gov/developer/index.php)
- [Data API](https://nassgeodata.gmu.edu/VegScape)

### USDA NASS Crop CASMA API
The Crop CASMA API provides programmatic access to crop vegetation and soil moisture conditions using NASA SMAP and MODIS satellite data for agricultural drought monitoring and crop condition analysis.

**Human URL:** [https://www.nass.usda.gov/developer/index.php](https://www.nass.usda.gov/developer/index.php)

#### Tags:

 - Soil Moisture, Crop Condition, Geospatial, Drought Monitoring

#### Properties

- [Documentation](https://www.nass.usda.gov/developer/index.php)
- [Data API](https://nassgeodata.gmu.edu/CropCASMA)

## Common Properties

- [Website](https://www.nass.usda.gov/)
- [Developer Portal](https://www.nass.usda.gov/developer/index.php)
- [GitHub Organization](https://github.com/usda)
- [Terms of Service](https://www.usda.gov/policies-and-links)
- [Privacy Policy](https://www.usda.gov/privacy-policy)

## Features

| Name | Description |
|------|-------------|
| API Key Authentication | All API access requires registration and an API key obtained by agreeing to NASS Terms of Service. |
| Multiple Output Formats | The QuickStats API supports JSON, XML, and CSV response formats with optional JSONP callback support. |
| Rich Query Operators | Support for comparison operators including GE, LE, GT, LT, NE, LIKE, and NOT_LIKE for flexible data filtering. |
| Agricultural Census Data | Access to the complete Census of Agriculture and annual survey estimates covering all major commodity types. |
| Geospatial Data Coverage | Geospatial APIs provide 30-meter and 250-meter resolution data layers covering the entire continental United States. |
| Historical Time Series | Access to historical agricultural statistics and cropland data extending back to 1997 for select states. |

## Use Cases

| Name | Description |
|------|-------------|
| Crop Production Analysis | Query crop production estimates by commodity, year, and location for market analysis and supply forecasting. |
| Livestock Population Monitoring | Access livestock inventory and production statistics at state and county levels for supply chain planning. |
| Geospatial Cropland Mapping | Use the CroplandCROS API to integrate 30-meter resolution cropland data into GIS applications and land use analysis. |
| Agricultural Drought Monitoring | Monitor crop condition and soil moisture via the Crop CASMA API to assess drought impacts on agricultural production. |
| Agricultural Research | Access the full Quick Stats database for academic research on agricultural trends, productivity, and policy analysis. |
| Food Security Assessment | Combine crop production, livestock, and vegetation data to assess regional and national food security conditions. |

## Integrations

| Name | Description |
|------|-------------|
| R Package rnassqs | Open-source R package for accessing NASS QuickStats API data directly within R statistical computing environments. |
| Python Package usdarnass | Python package providing programmatic access to the USDA NASS QuickStats API for data analysis workflows. |
| data.gov Catalog | NASS Quick Stats datasets are cataloged on catalog.data.gov for broader federal data discovery. |
| NASA SMAP | Crop CASMA integrates NASA SMAP satellite data for soil moisture monitoring. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [USDA NASS QuickStats API](openapi/agricultural-statistics-service-quickstats-api.yaml)

### JSON Schema

- [Statistics Record Schema](json-schema/quickstats-api-statistics-record-schema.json)
- [Statistics Response Schema](json-schema/quickstats-api-statistics-response-schema.json)
- [Parameter Values Response Schema](json-schema/quickstats-api-param-values-response-schema.json)
- [Count Response Schema](json-schema/quickstats-api-count-response-schema.json)
- [Error Response Schema](json-schema/quickstats-api-error-response-schema.json)

### JSON Structure

- [Statistics Record Structure](json-structure/quickstats-api-statistics-record-structure.json)
- [Statistics Response Structure](json-structure/quickstats-api-statistics-response-structure.json)
- [Count Response Structure](json-structure/quickstats-api-count-response-structure.json)

### JSON-LD

- [QuickStats API Context](json-ld/agricultural-statistics-service-quickstats-api-context.jsonld)

## Vocabulary

- [Agricultural Statistics Service Vocabulary](vocabulary/agricultural-statistics-service-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 1 action, 0 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Agricultural Statistics Service Spectral Rules](rules/agricultural-statistics-service-spectral-rules.yml) — 22 rules across 9 categories enforcing USDA NASS API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
