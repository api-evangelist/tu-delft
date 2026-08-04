# Delft University of Technology (tu-delft)

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

Delft University of Technology (TU Delft) is the largest and oldest public technical university in the Netherlands, ranked #51 in the QS World University Rankings 2025. This repository catalogs TU Delft's public developer and API footprint as an [APIs.json](http://apisjson.org) provider profile. TU Delft's public API surface centers on research-data and library infrastructure — the 4TU.ResearchData REST API and OAI-PMH, the TU Delft Repository's OAI-PMH metadata, and a NetID/OAuth2 identity service — rather than a single unified developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/tu-delft/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tu-delft-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Open Access, Library, Open Data, Netherlands, Europe

## APIs

- **4TU.ResearchData API** — Public REST API (v2/v3) for the 4TU.ResearchData repository TU Delft leads. Docs: https://djehuty.4tu.nl/ — Base: https://data.4tu.nl/v2
- **4TU.ResearchData OAI-PMH** — Metadata harvesting for datasets/software. Docs: https://djehuty.4tu.nl/
- **TU Delft Repository (OAI-PMH)** — Institutional repository of open-access theses and research output, CC0 metadata. Docs: https://www.tudelft.nl/en/library/collections/resources-and-collections/access-academic-work-from-the-tu-delft-repository
- **TU Delft NetID / OAuth2 SSO** — Single sign-on and OAuth2 authorization service. Docs: https://www.tudelft.nl/en/it-manuals/netid
- **TU Delft API Platform (legacy / suspended)** — General campus/courses/education/organisation API at api.tudelft.nl, OAuth2-secured, publicly announced as being suspended. Docs: https://apidoc.tudelft.nl/

## Plans

- [plans/tu-delft-plans-pricing.yml](plans/tu-delft-plans-pricing.yml)

## Rate Limits

- [rate-limits/tu-delft-rate-limits.yml](rate-limits/tu-delft-rate-limits.yml)

## FinOps

- [finops/tu-delft-finops.yml](finops/tu-delft-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tudelft.nl/
- GitHub: https://github.com/4TUResearchData
- LinkedIn: https://www.linkedin.com/school/tu-delft/
- Developer Portal: https://djehuty.4tu.nl/
- Authentication: https://login.tudelft.nl/
- Source Code: https://github.com/4TUResearchData/djehuty

## Notes

Verification caveats (probed 2026-06-03): data.4tu.nl (v2/v3), djehuty.4tu.nl, repository.tudelft.nl, login.tudelft.nl and www.tudelft.nl all resolved live (HTTP 200). The legacy institutional API (api.tudelft.nl, apidoc.tudelft.nl) did not resolve from the cataloging environment (status 0) and has been publicly announced as being suspended with no new client registrations accepted; it is cataloged as legacy/gated, not as a live endpoint. The LinkedIn school page returns 999 (bot-block), which is expected. TU Delft has no single official institution-wide GitHub organization; research-data code lives under the 4TUResearchData org. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
