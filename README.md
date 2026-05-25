# Moovit

Moovit — public transit and Mobility-as-a-Service routing (Intel/Mobileye).

Moovit is the urban-mobility company behind the consumer transit app used by 1.5B+ riders in 3,500+ cities across 112+ countries. It was acquired by Intel in May 2020 (~$900M) and now operates inside Mobileye as the MaaS business. The commercial surface is the **Moovit Public Transit API** — a thin, HMAC-signed, metro-scoped HTTP API covering multimodal trip planning, real-time arrivals, stops, lines, service alerts, GTFS-RT feeds, and search.

## APIs

- **[Moovit Public Transit API](https://api-docs.moovit.com/api-docs/5.1/MoovitPublicTransitAPIs.html)** — six API families (Trip Plan, Nearby, Stops, Lines, Real-Time, Service Alerts) plus GTFS-Realtime and Search. HMAC-SHA256 auth with `API_KEY` and `USER_LOC` / `MOOVIT_METRO_ID` headers.

## Artifacts

- [openapi/moovit-public-transit-api-openapi.yml](openapi/moovit-public-transit-api-openapi.yml) — OpenAPI 3.0 spec covering documented operations across all eight tag families.

## Links

- Product: https://moovit.com/maas-solutions/transit-apis/
- API docs: https://api-docs.moovit.com/
- Developers page: https://moovit.com/developers/
- Parent: https://www.mobileye.com/ (Intel/Mobileye)
- GitHub org: https://github.com/Moovit
- Wikipedia: https://en.wikipedia.org/wiki/Moovit

## Notes

- No self-service developer signup. API credentials are issued by `helpdesk@moovit.com`.
- All requests must carry either a `USER_LOC` (lat, lon) or a `MOOVIT_METRO_ID` header to scope the request to a metro area.
- Pricing is per-customer and volume-metered; rate limits are not publicly documented.
