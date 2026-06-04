# University of North Carolina at Chapel Hill (university-of-north-carolina-at-chapel-hill)

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
