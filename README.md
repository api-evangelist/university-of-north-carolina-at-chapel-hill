# University of North Carolina at Chapel Hill (university-of-north-carolina-at-chapel-hill)

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

The University of North Carolina at Chapel Hill is a leading public research university in Chapel Hill, North Carolina, United States, ranked #155 in the QS World University Rankings 2025. Its public developer and API footprint is decentralized, centered on research data and open-data infrastructure (UNC Dataverse, the campus ArcGIS Hub open-data site, and the UNC Libraries open-source software organization) rather than a single unified developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-north-carolina-at-chapel-hill/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-north-carolina-at-chapel-hill-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Data, Geospatial, Digital Library, United States, North Carolina

## APIs

- **UNC Dataverse API** — Native REST API for the UNC research data repository (live, Dataverse 6.8). Docs: https://guides.dataverse.org/en/latest/api/ | Base: https://dataverse.unc.edu/api
- **UNC GIS Open Data Hub** — ArcGIS Hub geospatial open data via DCAT-US feeds and ArcGIS REST services. Docs: https://gisdata-uncadmin.opendata.arcgis.com/
- **UNC Libraries Digital Collections Repository (box-c)** — Open-source digital collections platform. Site: https://dc.lib.unc.edu/ | Source: https://github.com/UNC-Libraries/box-c
- **Facilities SPOTS REST API** — Space Planning and Occupancy Tracking System API (Onyen-gated). Docs: https://facilities.unc.edu/resources/mapping-and-space/spots-rest-api/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-north-carolina-at-chapel-hill-plans-pricing.yml](plans/university-of-north-carolina-at-chapel-hill-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-north-carolina-at-chapel-hill-rate-limits.yml](rate-limits/university-of-north-carolina-at-chapel-hill-rate-limits.yml)
- FinOps: [finops/university-of-north-carolina-at-chapel-hill-finops.yml](finops/university-of-north-carolina-at-chapel-hill-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.unc.edu/
- GitHub: https://github.com/unc-libraries
- LinkedIn: https://www.linkedin.com/school/unc-chapel-hill/
- Authentication: https://sso.unc.edu/ (Onyen / Shibboleth single sign-on)
- Review: [review.yml](review.yml)

## Notes

- Verification caveats: The UNC Dataverse native API and the ArcGIS Hub DCAT-US feed were both confirmed live (HTTP 200) on 2026-06-03; the Dataverse instance reported version 6.8.
- The UNC Libraries GitHub organization is real (84 public repositories) and includes box-c, the Digital Collections Repository application.
- The Facilities SPOTS REST API documentation is Onyen-gated and not publicly accessible.
- The OIRA "UNC-Chapel Hill API List" page resolves but does not publish actual API specifications.
- No single unified public developer portal was found; no endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
