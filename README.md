# Remitian

Remitian is a fintech platform providing embedded tax payment infrastructure for tax software providers and accounting firms. Often described as the "Stripe for tax," Remitian acts as a unified gateway to multiple tax authorities, enabling automated, jurisdiction-aware payment processing without manual government portal logins.

Remitian raised $7M in seed funding in March 2026 and launched its Tax Payment API to help partners embed payment initiation, validation, and confirmation directly within their platforms.

## Links

- **Website:** https://remitian.com
- **Integration Docs:** https://remitian.com/integrations/integrate-remitian
- **Help Center:** https://help.remitian.com

## APIs

### Tax Payment API
- **Base URL:** https://api.remitian.com
- **Authentication:** Bearer token (JWT)
- **Documentation:** https://remitian.com/integrations/integrate-remitian
- **OpenAPI:** [openapi/remitian-tax-payment-openapi.yml](openapi/remitian-tax-payment-openapi.yml)
- **AsyncAPI:** [asyncapi/remitian-tax-payment-asyncapi.yml](asyncapi/remitian-tax-payment-asyncapi.yml)

**Endpoints:**
- `GET/POST /v1/payments` — Payment lifecycle management
- `POST /v1/payments/{id}/validate` — Jurisdiction validation
- `POST /v1/payments/{id}/confirm` — Confirm for processing
- `POST /v1/payments/{id}/cancel` — Cancel payment
- `GET /v1/jurisdictions` — Browse supported authorities
- `GET/POST /v1/accounts` — Client account management
- `GET /v1/audit-logs` — Bank-grade audit log access
- `GET/POST/DELETE /v1/webhooks` — Webhook subscriptions

## Payment Lifecycle

```
draft → validated → confirmed → processing → completed
                              ↘ failed
```

## Authentication

```
Authorization: Bearer {api_key}
```

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/remitian-tax-payment-openapi.yml](openapi/remitian-tax-payment-openapi.yml) |
| AsyncAPI | [asyncapi/remitian-tax-payment-asyncapi.yml](asyncapi/remitian-tax-payment-asyncapi.yml) |
| JSON Schema | [json-schema/remitian-payment-schema.json](json-schema/remitian-payment-schema.json) |
| JSON Structure | [json-structure/remitian-payment-structure.json](json-structure/remitian-payment-structure.json) |
| JSON-LD Context | [json-ld/remitian-context.jsonld](json-ld/remitian-context.jsonld) |
| Spectral Rules | [rules/remitian-rules.yml](rules/remitian-rules.yml) |
| Vocabulary | [vocabulary/remitian-vocabulary.yml](vocabulary/remitian-vocabulary.yml) |

## Capabilities

| Capability | Description |
|---|---|
| [tax-payment-automation.yaml](capabilities/tax-payment-automation.yaml) | Full tax payment automation workflow |
| [shared/tax-payment.yaml](capabilities/shared/tax-payment.yaml) | Tax Payment API shared definition |

## Examples

- [Initiate Payment](examples/remitian-initiate-payment-example.json)
- [Validate Payment](examples/remitian-validate-payment-example.json)
- [List Jurisdictions](examples/remitian-list-jurisdictions-example.json)
