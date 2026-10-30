# Moovit

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

Moovit is a Tel Aviv-founded urban mobility company acquired by Intel in May 2020 for approximately $900M and now part of Mobileye's Mobility-as-a- Service (MaaS) business. The Moovit consumer app provides public transit trip planning, real-time arrivals, and service alerts to more than 1.5 billion users across 3,500+ cities in 112+ countries, sourcing both official agency data and crowdsourced transit reports from its global community. Moovit's commercial offering is the Public Transit API suite — a thin, volume-metered HTTP API exposing six API families (Trip Plan, Nearby, Stops, Lines, Real-Time, Service Alerts) plus GTFS-Realtime feeds and a search API. The APIs power Microsoft (Azure Maps), Uber, Lyft, Cubic, and city/transit-agency MaaS deployments. Authentication is HMAC-SHA256 with a metro-scoped request header (USER_LOC or MOOVIT_METRO_ID). Pricing and rate limits are negotiated per customer; there is no self-service developer signup — credentials are issued by helpdesk@moovit.com.

**Areas:** Transit · Public Transit · Mobility · Mobility As A Service · MaaS · Trip Planning · Multimodal Routing · Real-Time · GTFS · GTFS Realtime · Service Alerts · Smart Cities

## Moovit on APIs.io

Everything profiled for Moovit is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/moovit/](https://apis.io/providers/moovit/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Moovit General API](https://apis.io/apis/moovit/moovit-general-api/) — Metro agencies and supported transit types.
- [Moovit GTFSRealtime API](https://apis.io/apis/moovit/moovit-gtfsrealtime-api/) — GTFS-RT feeds for vehicles, trip updates, and service alerts.
- [Moovit Lines API](https://apis.io/apis/moovit/moovit-lines-api/) — Line metadata, stops, geometry, schedules, and alerts.
- [Moovit Nearby API](https://apis.io/apis/moovit/moovit-nearby-api/) — Locate stops, bikes, and scooters near a coordinate.
- [Moovit RealTime API](https://apis.io/apis/moovit/moovit-realtime-api/) — Live arrival predictions for stops and lines.
- [Moovit Search API](https://apis.io/apis/moovit/moovit-search-api/) — Search stops and lines by name or number.
- [Moovit Stops API](https://apis.io/apis/moovit/moovit-stops-api/) — Stop metadata, lines served, reviews, and photos.
- [Moovit Service Alerts API](https://apis.io/apis/moovit/moovit-service-alerts-api/) — Metro service alerts and details.
- [Moovit Trip Plan API](https://apis.io/apis/moovit/moovit-trip-plan-api/) — Multimodal trip planning and itinerary details.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Moovit Agentic Access](https://apis.io/agentic-access/moovit/moovit-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [Moovit Public Transit APIs General API](https://apis.io/collections/moovit/open-moovit-general-api/)
- [Moovit Public Transit APIs General GTFSRealtime API](https://apis.io/collections/moovit/open-moovit-gtfsrealtime-api/)
- [Moovit Public Transit APIs General Lines API](https://apis.io/collections/moovit/open-moovit-lines-api/)
- [Moovit Public Transit APIs General Nearby API](https://apis.io/collections/moovit/open-moovit-nearby-api/)
- [Moovit Public Transit APIs](https://apis.io/collections/moovit/open-moovit-public-transit-api/)
- [Moovit Public Transit APIs General RealTime API](https://apis.io/collections/moovit/open-moovit-realtime-api/)
- [Moovit Public Transit APIs General Search API](https://apis.io/collections/moovit/open-moovit-search-api/)
- [Moovit Public Transit APIs General ServiceAlerts API](https://apis.io/collections/moovit/open-moovit-servicealerts-api/)
- [Moovit Public Transit APIs General Stops API](https://apis.io/collections/moovit/open-moovit-stops-api/)
- [Moovit Public Transit APIs General TripPlan API](https://apis.io/collections/moovit/open-moovit-tripplan-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Moovit Authentication](https://apis.io/security/moovit/moovit-authentication/)
- [Moovit Domain Security](https://apis.io/security/moovit/moovit-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://moovit.com)
- [Documentation](https://api-docs.moovit.com/)
- [Support](https://support.moovitapp.com/hc/en-us)
- [Blog](https://moovit.com/blog/)
- [Terms of service](https://moovit.com/legal/terms-and-conditions/)
- [Privacy policy](https://moovit.com/privacy-policy/)
- [GitHub](https://github.com/Moovit)

## API Evangelist rating

**Kin Score 26.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 67.0 |
| Contract quality | 47.8 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 38.1 |
| Access clarity | 0.0 |

**Agent readiness 20.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/moovit/](https://apis.io/providers/moovit/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Moovit: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/moovit/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
