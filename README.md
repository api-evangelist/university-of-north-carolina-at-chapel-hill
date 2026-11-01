# University of North Carolina at Chapel Hill

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

The University of North Carolina at Chapel Hill is a public research university in Chapel Hill, North Carolina, a member of the Association of American Universities and the flagship of the seventeen-campus University of North Carolina System. It operates no central developer portal, no API gateway, and publishes no OpenAPI of its own — but it does run several genuinely institution-engineered machine-readable surfaces. The strongest is the Carolina Digital Repository services API at dcr.lib.unc.edu, including IIIF Presentation 3.0 and Image 3.0 endpoints, served by box-c, a repository application UNC Libraries writes and maintains in the open on GitHub. Alongside it are two Blacklight JSON search APIs on UNC's own hardware (the TRLN Discovery library catalog and the Wilson Library finding aids), an OAI-PMH 2.0 archive on UNC Dataverse advertising DataCite metadata, and UNC's own Shibboleth/InCommon SAML 2.0 metadata. The rest of the programmable footprint is tenant relationships rather than UNC engineering: the UNC Dataverse native REST API is the Dataverse product's contract, the course-catalog search API is Leepfrog CourseLeaf's, the GIS open-data hub is Esri ArcGIS Hub's, and the Digital Collections search at dc.lib.unc.edu is OCLC CONTENTdm. The Facilities SPOTS REST API is institution-operated but its documentation is entirely Onyen-gated and could not be read.

**Areas:** Education · Higher Education · University · Public Research University · United States · North Carolina · University of North Carolina System · Association of American Universities · Research Data · Open Data · Digital Library · Library

## University of North Carolina at Chapel Hill on APIs.io

Everything profiled for University of North Carolina at Chapel Hill is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-north-carolina-at-chapel-hill/](https://apis.io/providers/university-of-north-carolina-at-chapel-hill/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Carolina Digital Repository Services API (box-c)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/cdr-services-api/) — Public, keyless JSON API behind the Carolina Digital Repository, UNC Libraries' institutional repository for digitized special collections, theses,…
- [UNC Libraries Catalog Search API (TRLN Discovery / Blacklight)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/library-catalog-search/) — The UNC University Library catalog answers machine-readable search over its full bibliographic index at /catalog.json, the Blacklight JSON response format,…
- [UNC Finding Aids Search API (Blacklight JSON:API)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/finding-aids-search/) — Machine-readable search across the finding aids of the Wilson Special Collections Library, served at /catalog.json in Blacklight's JSON:API form — a `links`…
- [UNC Dataverse OAI-PMH Archive](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/dataverse-oai-pmh/) — OAI-PMH 2.0 harvesting endpoint for the UNC Dataverse research data repository, operated by the Odum Institute / Institute for Research in Social Science.…
- [UNC Shibboleth Identity Provider (SAML 2.0 / InCommon)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/shibboleth-idp/) — UNC's Onyen single sign-on is a Shibboleth Identity Provider that publishes SAML 2.0 metadata at its canonical /idp/shibboleth location — an…
- [Facilities SPOTS REST API](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/facilities-spots/) — REST API for the Space Planning and Occupancy Tracking System run by UNC Facilities Services, the campus system of record for building and room space data.…
- [UNC Dataverse Native REST API (Dataverse deployment)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/dataverse-native-api/) — UNC Dataverse, the Odum Institute's research data repository, runs Dataverse 6.8 and exposes the Dataverse Native REST API at /api. GET /api/info/version is…
- [UNC Catalog Course Search API (CourseLeaf)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/course-catalog-search/) — The University Catalog exposes a keyless JSON course-search API at /course-search/api/?page=fose&route=search. A POST carrying a criteria array returns…
- [UNC GIS Open Data Hub (ArcGIS Hub DCAT-US)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/gis-opendata/) — UNC-Chapel Hill's campus open-data site for geospatial and institutional datasets, published through ArcGIS Hub. The DCAT-US 1.1 catalog feed at…
- [UNC Digital Collections Search (OCLC CONTENTdm)](https://apis.io/apis/university-of-north-carolina-at-chapel-hill/digital-collections/) — "Search the Special Collections", UNC University Library's discovery layer over its digitized special collections. A WordPress front at the root fronts an…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [UNC Dataverse API Vocabulary](https://apis.io/vocabularies/university-of-north-carolina-at-chapel-hill/university-of-north-carolina-at-chapel-hill-vocabulary/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [University Of North Carolina At Chapel Hill Domain Security](https://apis.io/security/university-of-north-carolina-at-chapel-hill/university-of-north-carolina-at-chapel-hill-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of North Carolina At Chapel Hill Plans Pricing](https://apis.io/plans/university-of-north-carolina-at-chapel-hill/university-of-north-carolina-at-chapel-hill-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of North Carolina At Chapel Hill Rate Limits](https://apis.io/rate-limits/university-of-north-carolina-at-chapel-hill/university-of-north-carolina-at-chapel-hill-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of North Carolina At Chapel Hill Finops](https://apis.io/finops/university-of-north-carolina-at-chapel-hill/university-of-north-carolina-at-chapel-hill-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.unc.edu/)
- [Documentation](https://github.com/UNC-Libraries/box-c)
- [Support](https://help.unc.edu/)
- [Blog](https://www.unc.edu/feed/)
- [Terms of service](https://policies.unc.edu/)
- [Privacy policy](https://www.unc.edu/about/privacy-statement/)
- [GitHub](https://github.com/UNC-Libraries)

## API Evangelist rating

**Kin Score 19.3** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 4.4 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 26.3 |

**Agent readiness 3.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-north-carolina-at-chapel-hill/](https://apis.io/providers/university-of-north-carolina-at-chapel-hill/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of North Carolina at Chapel Hill: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-north-carolina-at-chapel-hill/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
