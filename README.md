# Moovit (moovit)

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
