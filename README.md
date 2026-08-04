# Exodigo

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

Exodigo is a subsurface intelligence company that maps what is underground and above ground without
digging. Founded in 2021 and headquartered in the San Francisco Bay Area, it fuses ground-penetrating
radar, electromagnetic (TDEM/FDEM), magnetic gradiometry and electrical sensing with GPS-RTK
positioning, then processes the combined signal with AI to produce geolocated 3D maps of buried
utilities, foundations and geotechnical conditions.

- Website: https://www.exodigo.com/
- Insights / press: https://www.exodigo.com/insights
- Contact: https://www.exodigo.com/connect

## API surface

**No public API.** A full contract-discovery pass on 2026-08-04 found no developer portal, no API
documentation, no OpenAPI/Swagger/AsyncAPI/GraphQL specification, no SDK on any public package
registry, no MCP server and no A2A agent card. Exodigo delivers its output as GIS and CAD artifacts
(Esri ArcGIS, AutoCAD, BIM) and through a private client portal. The one machine-readable document it
publishes for agents is `/llms.txt`, captured verbatim in `llms/`.

See `well-known/exodigo-well-known.yml` for the full probe record, including the
`learn.exodigo.com` SPA catch-all that answers 200 for every path and was rejected as a false positive.
