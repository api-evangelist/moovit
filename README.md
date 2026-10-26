# Moovit (moovit)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/moovit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/moovit/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Transit
- Public Transit
- Mobility
- Mobility As A Service
- MaaS
- Trip Planning
- Multimodal Routing
- Real Time
- GTFS
- GTFS Realtime
- Service Alerts
- Smart Cities
- Transportation
- Mobileye
- Intel

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Moovit Public Transit API

The Moovit Public Transit API suite — a thin, volume-metered HTTP API for multimodal trip planning, nearby transit discovery, stops and lines metadata, real-time arrival predictions, service alerts, and GTFS-Realtime feeds. Auth is HMAC-SHA256 over `<timestamp>:<payload>: <nonce>` with an API_KEY header and a USER_LOC or MOOVIT_METRO_ID header that scopes the request to a metro area.

- **Human URL:** [https://api-docs.moovit.com/api-docs/5.1/MoovitPublicTransitAPIs.html](https://api-docs.moovit.com/api-docs/5.1/MoovitPublicTransitAPIs.html)
- **Base URL:** `https://app5.moovitapp.com/services-app/services/`

#### Tags

- Transit
- Trip Planning
- Real Time
- GTFS

#### Properties

- [Documentation](https://api-docs.moovit.com/api-docs/5.1/MoovitPublicTransitAPIs.html)
- [Documentation](https://moovit.com/maas-solutions/transit-apis/)
- [OpenAPI](openapi/moovit-public-transit-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/moovit-public-transit-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/moovit-public-transit-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://moovit.com)
- [Consumer App](https://moovitapp.com)
- [Portal](https://moovit.com/maas-solutions/)
- [Documentation](https://api-docs.moovit.com/)
- [Documentation](https://api-docs.moovit.com/api-docs/5.1/MoovitPublicTransitAPIs.html)
- [Developers](https://moovit.com/developers/)
- [Product Page](https://moovit.com/maas-solutions/transit-apis/)
- [Product Page](https://moovit.com/industries/private-sector/)
- [Industries](https://moovit.com/industries/)
- [About](https://company.moovit.com/)
- [Newsroom](https://moovit.com/press-releases/)
- [Blog](https://moovit.com/blog/)
- [Insights](https://moovit.com/insights/)
- [Careers](https://moovit.com/careers/)
- [Support](https://support.moovitapp.com/hc/en-us)
- [Contact Sales](https://moovit.com/contact-sales/)
- [Contact Support](mailto:support@moovitapp.com)
- [Contact Support](mailto:helpdesk@moovit.com)
- [Privacy Policy](https://moovit.com/privacy-policy/)
- [Terms of Service](https://moovit.com/legal/terms-and-conditions/)
- [Cookie Policy](https://moovit.com/cookies-policy/)
- [Accessibility](https://moovit.com/accessibility-statement/)
- [Parent Company](https://www.mobileye.com/)
- [Parent Company](https://www.intel.com/)
- [Press Release](https://www.intc.com/news-events/press-releases/detail/6/intel-acquires-moovit-to-accelerate-mobileyes)
- [GitHub Organization](https://github.com/Moovit)
- [Twitter](https://twitter.com/moovit)
- [LinkedIn](https://www.linkedin.com/company/moovit)
- [Facebook](https://www.facebook.com/moovitapp)
- [Instagram](https://www.instagram.com/moovit/)
- [YouTube](https://www.youtube.com/user/MoovitApp)
- [App Store](https://apps.apple.com/app/moovit/id498477945)
- [Play Store](https://play.google.com/store/apps/details?id=com.tranzmate)
- [Wikipedia Page](https://en.wikipedia.org/wiki/Moovit)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
