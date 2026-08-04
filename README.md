# Emissary-Ingress (emissary-ingress)

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

Emissary-Ingress is a CNCF incubating Kubernetes-native API gateway built on the Envoy proxy. It provides ingress control, load balancing, authentication, rate limiting, and traffic management for microservices. Emissary-Ingress is configured through Kubernetes custom resources and supports canary releases, circuit breaking, and automatic retries.

**APIs.json:** [https://www.getambassador.io/products/api-gateway](https://www.getambassador.io/products/api-gateway)

## Scope

- **Type:** Index

## Tags

- API Gateway
- Cloud Native
- Envoy
- Incubating
- Ingress
- Kubernetes

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Emissary-Ingress Configuration API

Emissary-Ingress is configured through Kubernetes custom resources including Mapping for routing rules, Host for domain configuration, TLSContext for TLS termination, RateLimitService for rate limiting, and AuthService for external authentication. These CRDs provide declarative API gateway configuration within the Kubernetes ecosystem.

- **Human URL:** [https://www.getambassador.io/docs/emissary/](https://www.getambassador.io/docs/emissary/)

#### Tags

- API Gateway
- Configuration
- Routing

#### Properties

- [Documentation](https://www.getambassador.io/docs/emissary/)
- [Getting Started](https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install)
- [Reference](https://www.getambassador.io/docs/emissary/latest/topics/running/)
- [Changelog](https://archive.getambassador.io/docs/emissary/3.1/release-notes/)
- [OpenAPI](openapi/emissary-ingress-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/emissary-ingress.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/emissary-ingress.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/emissary-ingress-mapping-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://www.getambassador.io/docs/emissary/latest/topics/running/services/auth-service)
- [Quotas](https://www.getambassador.io/docs/emissary/latest/topics/running/services/rate-limit-service)

### Emissary-Ingress Gateway API

Emissary-Ingress supports a subset of the Kubernetes Gateway API standard, including GatewayClass, Gateway, and HTTPRoute resources. This enables teams to use the next-generation Kubernetes ingress standard for defining routing rules, with support for path matching, header matching, and weighted load balancing across backend services.

- **Human URL:** [https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/](https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/)

#### Tags

- Gateway API
- HTTPRoute
- Kubernetes
- Routing

#### Properties

- [Documentation](https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/)
- [Postman Collection](collections/emissary-ingress.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/emissary-ingress.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.getambassador.io/products/api-gateway)
- [Documentation](https://www.getambassador.io/docs/emissary/)
- [Getting Started](https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install)
- [GitHub Organization](https://github.com/emissary-ingress)
- [GitHub Repository](https://github.com/emissary-ingress/emissary)
- [Support](https://www.getambassador.io/docs/emissary/latest/about/support)
- [Community](https://emissary-ingress.dev/docs/4.0/community/)
- [Issue  Tracker](https://github.com/emissary-ingress/emissary/issues)
- [Blog](https://blog.getambassador.io/)
- [Changelog](https://archive.getambassador.io/docs/emissary/3.1/release-notes/)
- [JSON-LD](json-ld/emissary-ingress-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/emissary-ingress-mapping-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
