# Emissary-Ingress (emissary-ingress)

Emissary-Ingress is a CNCF incubating Kubernetes-native API gateway built on the Envoy proxy. It provides ingress control, load balancing, authentication, rate limiting, and traffic management for microservices. Emissary-Ingress is configured through Kubernetes custom resources and supports canary releases, circuit breaking, and automatic retries.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/emissary-ingress/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- API Gateway
- Cloud Native
- Envoy
- Incubating
- Ingress
- Kubernetes

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### Emissary-Ingress Configuration API

Emissary-Ingress is configured through Kubernetes custom resources including Mapping for routing rules, Host for domain configuration, TLSContext for TLS termination, RateLimitService for rate limiting, and AuthService for external authentication. These CRDs provide declarative API gateway configuration within the Kubernetes ecosystem.

**Human URL:** [https://www.getambassador.io/docs/emissary/](https://www.getambassador.io/docs/emissary/)

#### Tags

- API Gateway
- Configuration
- Routing

#### Properties

- [Documentation](https://www.getambassador.io/docs/emissary/)
- [Getting Started](https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install)
- [Reference](https://www.getambassador.io/docs/emissary/latest/topics/running/)
- [Change Log](https://archive.getambassador.io/docs/emissary/3.1/release-notes/)
- [OpenAPI](openapi/emissary-ingress-openapi.yml)
- [JSONSchema](json-schema/emissary-ingress-mapping-schema.json)
- [Authentication](https://www.getambassador.io/docs/emissary/latest/topics/running/services/auth-service)
- [Quotas](https://www.getambassador.io/docs/emissary/latest/topics/running/services/rate-limit-service)

### Emissary-Ingress Gateway API

Emissary-Ingress supports a subset of the Kubernetes Gateway API standard, including GatewayClass, Gateway, and HTTPRoute resources. This enables teams to use the next-generation Kubernetes ingress standard for defining routing rules, with support for path matching, header matching, and weighted load balancing across backend services.

**Human URL:** [https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/](https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/)

#### Tags

- Gateway API
- HTTPRoute
- Kubernetes
- Routing

#### Properties

- [Documentation](https://emissary-ingress.dev/docs/3.8/topics/using/gateway-api/)

## Common Properties

- [Website](https://www.getambassador.io/products/api-gateway)
- [Documentation](https://www.getambassador.io/docs/emissary/)
- [Getting Started](https://www.getambassador.io/docs/emissary/latest/topics/install/yaml-install)
- [GitHub Organization](https://github.com/emissary-ingress)
- [GitHub Repository](https://github.com/emissary-ingress/emissary)
- [Support](https://www.getambassador.io/docs/emissary/latest/about/support)
- [Community](https://emissary-ingress.dev/docs/4.0/community/)
- [Issue Tracker](https://github.com/emissary-ingress/emissary/issues)
- [Blog](https://blog.getambassador.io/)
- [Change Log](https://archive.getambassador.io/docs/emissary/3.1/release-notes/)
- [JSON-LD](json-ld/emissary-ingress-context.jsonld)
- [JSONSchema](json-schema/emissary-ingress-mapping-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
