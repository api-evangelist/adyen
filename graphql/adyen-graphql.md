# Adyen GraphQL

## Description

Adyen is a global enterprise payment platform offering a unified solution for accepting payments worldwide. Adyen's platform supports cards, digital wallets, local payment methods, point-of-sale terminals, marketplace splits, payouts, tokenization, dispute management, and embedded finance (Issuing and Capital).

Adyen does not offer a native GraphQL endpoint. Their API surface is REST-only, documented at https://docs.adyen.com/api-explorer/. This schema is a conceptual GraphQL representation derived from Adyen's REST API types across their Checkout, Payments, Recurring, Payouts, Transfers, Management, Legal Entity, Configuration (Balance Platform), Disputes, and Notifications APIs.

## Endpoint

No live GraphQL endpoint is available. This schema is conceptual.

## Documentation

- API Explorer: https://docs.adyen.com/api-explorer/
- Developer Documentation: https://docs.adyen.com/
- Getting Started: https://docs.adyen.com/get-started-with-adyen/

## Note

This is a **conceptual schema** synthesized from Adyen's published REST OpenAPI specifications. It maps Adyen's core domain types — payments, methods, accounts, transfers, disputes, webhooks, and more — into GraphQL SDL for reference, tooling, and integration planning purposes. It does not reflect an actual Adyen GraphQL API.

Source REST APIs modeled:
- Checkout API (v71)
- Payments API
- Payouts API
- Recurring API
- Transfers API
- Configuration (Balance Platform) API
- Management API
- Legal Entity API
- Disputes API
- Funds API
- Account API
- Notification Configuration API
- Webhooks API
