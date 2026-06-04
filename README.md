# Delft University of Technology (tu-delft)

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
