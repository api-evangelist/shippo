# Shippo (shippo)

Shippo's robust shipping API architecture helps you drive efficiency at scale. We have you covered from pre-purchase to returns.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/shippo/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Ecommerce, Labels, Logistics, Returns, Shipping, Tracking

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-02

## APIs

### Shippo API

Shippo is a multi-carrier shipping API that enables developers to add complete shipping functionality to their applications. The API supports address validation, carrier rate comparison across USPS, UPS, FedEx, DHL, and 80+ other carriers, label generation, package tracking, returns management, and webhook notifications.

**Human URL:** [https://docs.goshippo.com/](https://docs.goshippo.com/)

#### Tags

- Ecommerce, Labels, Logistics, Shipping, Tracking

#### Properties

- [Documentation](https://docs.goshippo.com/)
- [OpenAPI](openapi/shippo-openapi.yml)
- [OpenAPI](https://docs.goshippo.com/spec/shippoapi/public-api.yaml)
- [SDK](https://github.com/goshippo/shippo-python-sdk)
- [SDK](https://github.com/goshippo/shippo-javascript-sdk)
- [SDK](https://github.com/goshippo/shippo-php-client)
- [SDK](https://github.com/goshippo/shippo-java-client)
- [SDK](https://github.com/goshippo/shippo-ruby-client)
- [SDK](https://github.com/goshippo/shippo-node-client)
- [JSONSchema](json-schema/shippo-shipment-schema.json)
- [JSONSchema](json-schema/shippo-transaction-schema.json)
- [JSONLD](json-ld/shippo-context.jsonld)
- [SpectralRules](rules/shippo-rules.yml)
- [NaftikoCapabilities](capabilities/shipping-fulfillment.yaml)
- [Vocabulary](vocabulary/shippo-vocabulary.yml)

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/shippo.yaml](capabilities/shared/shippo.yaml) | Shippo API — addresses, shipments, rates, transactions, tracking, refunds |

### Workflow Capabilities

| Capability | Description | Tools |
|---|---|---|
| [shipping-fulfillment.yaml](capabilities/shipping-fulfillment.yaml) | End-to-end shipping from address validation through label purchase and tracking | 10 tools |

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/shippo-openapi.yml](openapi/shippo-openapi.yml) |
| JSON Schema | [json-schema/shippo-shipment-schema.json](json-schema/shippo-shipment-schema.json) |
| JSON Schema | [json-schema/shippo-transaction-schema.json](json-schema/shippo-transaction-schema.json) |
| JSON Structure | [json-structure/shippo-shipment-structure.json](json-structure/shippo-shipment-structure.json) |
| JSON-LD | [json-ld/shippo-context.jsonld](json-ld/shippo-context.jsonld) |
| Examples | [examples/shippo-create-shipment-example.json](examples/shippo-create-shipment-example.json) |
| Examples | [examples/shippo-purchase-label-example.json](examples/shippo-purchase-label-example.json) |
| Spectral Rules | [rules/shippo-rules.yml](rules/shippo-rules.yml) |
| Vocabulary | [vocabulary/shippo-vocabulary.yml](vocabulary/shippo-vocabulary.yml) |

## Common Properties

- [Documentation](https://docs.goshippo.com/)
- [API Reference](https://docs.goshippo.com/shippoapi/public-api)
- [SDKs](https://docs.goshippo.com/docs/guides_general/clientlibraries)
- [Getting Started](https://support.goshippo.com/hc/en-us/articles/4404415886491-Shippo-API-Quick-Start-Guide)
- [Pricing](https://goshippo.com/pricing/api)
- [GitHub Organization](https://github.com/goshippo)
- [Developer Portal](https://goshippo.com/products/api)
- [Website](https://goshippo.com)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
