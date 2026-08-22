# Adyen (adyen)

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

Adyen is a global payment company that provides businesses with a single platform to accept payments from customers worldwide. Their technology enables companies to accept a wide range of payment methods, including credit cards, digital wallets, and local payment methods, in multiple currencies and countries. Adyen also offers services such as fraud prevention, data analytics, and optimization tools to help businesses streamline their payment processes and improve their overall performance.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/apis.yml)

## Tags

- Payments
- Financial Services
- Fintech

## Timestamps

- **Created:** 2023-11-13
- **Modified:** 2026-05-30

## APIs

### Adyen Accounting Notifications API

Adyen sends notifications through webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/](https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Accounting
- Notifications
- Webhooks

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/)
- [OpenAPI](openapi/accounting-notifications-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Account API

This API is used for the classic integration. The Account API provides endpoints for managing account-related entities on your platform. These related entities include account holders, accounts, bank accounts, shareholders, and verification-related documents. The management operations include actions such as creation, retrieval, updating, and deletion of them.

- **Human URL:** [https://docs.adyen.com/api-explorer/Account/6/overview](https://docs.adyen.com/api-explorer/Account/6/overview)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Account
- Accounts
- Bank
- Holders
- Shareholders
- Verification

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/Account/6/overview)
- [OpenAPI](openapi/accounts-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Authentication Webhooks API

Adyen sends webhooks to inform your system about events related to cardholder authentication.

- **Human URL:** [https://docs.adyen.com/development-resources/webhooks/](https://docs.adyen.com/development-resources/webhooks/)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Authentication
- Webhooks
- 3D Secure

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/webhooks/)
- [OpenAPI](openapi/authentication-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Balance Control API

The Balance Control API lets you transfer funds between merchant accounts that belong to the same legal entity and are under the same company account.

- **Human URL:** [https://docs.adyen.com/api-explorer/BalanceControl/1/overview](https://docs.adyen.com/api-explorer/BalanceControl/1/overview)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Balance
- Transfers
- Merchants

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/BalanceControl/1/overview)
- [OpenAPI](openapi/balance-control-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen BinLookup API

The BIN Lookup API provides endpoints for retrieving information, such as cost estimates, and 3D Secure supported version based on a given BIN.

- **Human URL:** [https://docs.adyen.com/api-explorer/BinLookup/52/overview](https://docs.adyen.com/api-explorer/BinLookup/52/overview)
- **Base URL:** `https://pal-test.adyen.com`

#### Tags

- BIN
- Card
- 3D Secure
- Cost Estimation

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/BinLookup/52/overview)
- [OpenAPI](openapi/binlookup-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Checkout API

The Checkout API provides a powerful, PCI-compliant way to accept payments online. It supports a broad range of payment methods, including cards, wallets, and local payment methods, with built-in 3D Secure and fraud detection.

- **Human URL:** [https://docs.adyen.com/api-explorer/Checkout/71/overview](https://docs.adyen.com/api-explorer/Checkout/71/overview)
- **Base URL:** `https://checkout-test.adyen.com`

#### Tags

- Checkout
- Payments
- Sessions
- Orders
- Refunds

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/Checkout/71/overview)
- [OpenAPI](openapi/checkout-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Configuration API

The Configuration API enables you to create a platform where you can onboard your users as account holders and create balance accounts, cards, and business accounts.

- **Human URL:** [https://docs.adyen.com/api-explorer/balanceplatform/2/overview](https://docs.adyen.com/api-explorer/balanceplatform/2/overview)
- **Base URL:** `https://balanceplatform-api-test.adyen.com`

#### Tags

- Configuration
- Balance Platform
- Account Holders
- Balance Accounts
- Cards

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/balanceplatform/2/overview)
- [OpenAPI](openapi/configuration-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Configuration Webhooks API

Adyen sends webhooks to inform your system about events that occur in your platform. These events include, for example, when an account holders capabilities are updated, or when a sweep configuration is created or updated.

- **Human URL:** [https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview](https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview)
- **Base URL:** `https://balanceplatform-api-test.adyen.com`

#### Tags

- Configuration
- Webhooks
- Balance Platform

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview)
- [OpenAPI](openapi/configuration-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Data Protection API

Adyen Data Protection API provides a way for you to process Subject Erasure Requests as mandated in GDPR. Use our API to submit a request to delete shopper's data, including payment details and other related information.

- **Human URL:** [https://docs.adyen.com/development-resources/data-protection-api/](https://docs.adyen.com/development-resources/data-protection-api/)
- **Base URL:** `https://ca-test.adyen.com`

#### Tags

- Data Protection
- GDPR
- Privacy
- Erasure

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/data-protection-api/)
- [OpenAPI](openapi/data-protection-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Disputes API

You can use the Disputes API to automate the dispute handling process so that you can respond to disputes and chargebacks as soon as they are initiated. The Disputes API lets you retrieve defense reasons, supply and delete defense documents, and accept or defend disputes.

- **Human URL:** [https://docs.adyen.com/risk-management/disputes-api](https://docs.adyen.com/risk-management/disputes-api)
- **Base URL:** `https://ca-test.adyen.com`

#### Tags

- Disputes
- Chargebacks
- Risk Management

#### Properties

- [Documentation](https://docs.adyen.com/risk-management/disputes-api)
- [OpenAPI](openapi/disputes-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Funds API

The Fund API provides endpoints for managing the funds in the accounts on your platform. These management operations include, for example, the transfer of funds from one account to another, the payout of funds to an account holder, and the retrieval of balances in an account.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/](https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Funds
- Transfers
- Marketplaces
- Payouts

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/)
- [OpenAPI](openapi/funds-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Hosted Onboarding API

The Hosted Onboarding API provides endpoints for managing the hosted onboarding experience for account holders, allowing you to collect verification details through Adyen's hosted pages.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/](https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Onboarding
- Verification
- Marketplaces
- KYC

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/)
- [OpenAPI](openapi/hosted-onboarding-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Legal Entity API

The Legal Entity Management API enables you to manage legal entities that contain information required for verification.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/](https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/)
- **Base URL:** `https://kyc-test.adyen.com`

#### Tags

- Legal Entity
- Verification
- KYC
- Compliance

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/)
- [OpenAPI](openapi/legal-entity-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Management API

Configure and manage your Adyen company and merchant accounts, stores, and payment terminals.

- **Human URL:** [https://docs.adyen.com/api-explorer/Management/3/overview](https://docs.adyen.com/api-explorer/Management/3/overview)
- **Base URL:** `https://management-test.adyen.com`

#### Tags

- Management
- Merchants
- Terminals
- Configuration

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/Management/3/overview)
- [OpenAPI](openapi/management-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Management Webhooks API

Adyen uses webhooks to inform your system about events that happen with your Adyen company and merchant accounts, stores, payment terminals, and payment methods when using Management API.

- **Human URL:** [https://docs.adyen.com/api-explorer/management-webhooks/3/overview](https://docs.adyen.com/api-explorer/management-webhooks/3/overview)
- **Base URL:** `https://management-test.adyen.com`

#### Tags

- Management
- Webhooks
- Merchants
- Terminals

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/management-webhooks/3/overview)
- [OpenAPI](openapi/management-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Notification Configuration API

The Notification Configuration API is used for the classic integration to configure notification subscriptions, endpoints, and settings.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/notifications](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Notifications
- Configuration
- Webhooks
- Marketplaces

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)
- [OpenAPI](openapi/notification-configurations-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Notification Webhooks API

Adyen sends notifications through webhooks to inform your system about events that occur in the balance platform. These events include, for example, a card user making a payment, or a merchant starting a refund.

- **Human URL:** [https://docs.adyen.com/point-of-sale/design-your-integration/notifications/](https://docs.adyen.com/point-of-sale/design-your-integration/notifications/)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Notifications
- Webhooks
- Point of Sale

#### Properties

- [Documentation](https://docs.adyen.com/point-of-sale/design-your-integration/notifications/)
- [OpenAPI](openapi/notification-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Notifications API

The Notification API sends notifications to the endpoints specified in a given subscription. Subscriptions are managed through the Notification Configuration API.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/notifications](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)
- **Base URL:** `https://cal-test.adyen.com`

#### Tags

- Notifications
- Webhooks
- Marketplaces

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)
- [OpenAPI](openapi/notifications-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Payments API

A set of API endpoints that allow you to initiate, settle, and modify payments on the Adyen payments platform. You can use the API to accept card payments (including One-Click and 3D Secure), bank transfers, ewallets, and many other payment methods.

- **Human URL:** [https://docs.adyen.com/online-payments/](https://docs.adyen.com/online-payments/)
- **Base URL:** `https://pal-test.adyen.com`

#### Tags

- Payments
- Cards
- 3D Secure
- Tokenization

#### Properties

- [Documentation](https://docs.adyen.com/online-payments/)
- [OpenAPI](openapi/payments-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Payouts API

A set of API endpoints that allow you to store payout details, confirm, or decline a payout. For more information, refer to Online payouts.

- **Human URL:** [https://docs.adyen.com/online-payments/online-payouts](https://docs.adyen.com/online-payments/online-payouts)
- **Base URL:** `https://pal-test.adyen.com`

#### Tags

- Payouts
- Transfers
- Online Payments

#### Properties

- [Documentation](https://docs.adyen.com/online-payments/online-payouts)
- [OpenAPI](openapi/payouts-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen POS Terminal API

This API provides endpoints for managing your point-of-sale (POS) payment terminals. You can use the API to obtain information about a specific terminal, retrieve overviews of your terminals and stores, and assign terminals to a merchant account or store.

- **Human URL:** [https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/)
- **Base URL:** `https://management-test.adyen.com`

#### Tags

- Point of Sale
- Terminals
- In-Person Payments

#### Properties

- [Documentation](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/)
- [OpenAPI](openapi/pos-terminal-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Recurring API

The Recurring APIs allow you to manage and remove your tokens or saved payment details. Tokens should be created with validation during a payment request.

- **Human URL:** [https://docs.adyen.com/online-payments/tokenization](https://docs.adyen.com/online-payments/tokenization)
- **Base URL:** `https://pal-test.adyen.com`

#### Tags

- Recurring
- Tokenization
- Stored Payment Methods

#### Properties

- [Documentation](https://docs.adyen.com/online-payments/tokenization)
- [OpenAPI](openapi/recurring-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Report Webhooks API

Adyen sends webhooks to inform your system that reports were generated and are ready to be downloaded. You can download reports programmatically by making an HTTP GET request.

- **Human URL:** [https://docs.adyen.com/api-explorer/report-webhooks/1/overview](https://docs.adyen.com/api-explorer/report-webhooks/1/overview)
- **Base URL:** `https://balanceplatform-api-test.adyen.com`

#### Tags

- Reports
- Webhooks
- Balance Platform

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/report-webhooks/1/overview)
- [OpenAPI](openapi/report-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Stored Value API

A set of API endpoints to manage stored value products.

- **Human URL:** [https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/](https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/)
- **Base URL:** `https://pal-test.adyen.com`

#### Tags

- Stored Value
- Gift Cards
- Loyalty

#### Properties

- [Documentation](https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/)
- [OpenAPI](openapi/stored-value-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Terminal API

The Adyen Terminal API lets you make payments, issue refunds, collect shopper information, and perform other shopper-terminal interactions using a payment terminal supplied by Adyen.

- **Human URL:** [https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/)
- **Base URL:** `https://terminal-api-test.adyen.com`

#### Tags

- Terminal
- Point of Sale
- In-Person Payments

#### Properties

- [Documentation](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/)
- [OpenAPI](openapi/terminal-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Test Cards API

The Test Cards API provides endpoints for generating custom test card numbers. For more information, refer to Custom test cards documentation.

- **Human URL:** [https://docs.adyen.com/development-resources/testing/create-test-cards](https://docs.adyen.com/development-resources/testing/create-test-cards)
- **Base URL:** `https://ca-test.adyen.com`

#### Tags

- Testing
- Test Cards
- Development

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/testing/create-test-cards)
- [OpenAPI](openapi/test-cards-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Transaction Webhooks API

Adyen sends webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/)
- **Base URL:** `https://balanceplatform-api-test.adyen.com`

#### Tags

- Transactions
- Webhooks
- Marketplaces
- Business Accounts

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/)
- [OpenAPI](openapi/transaction-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Transfer Webhooks API

Adyen sends webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

- **Human URL:** [https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview](https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview)
- **Base URL:** `https://balanceplatform-api-test.adyen.com`

#### Tags

- Transfers
- Webhooks
- Balance Platform

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview)
- [OpenAPI](openapi/transfer-webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Transfers API

This API provides endpoints that you can use to transfer funds, whether when paying out to a transfer instrument, sending funds to third parties for users with business bank accounts, or to request a payout for a grant offer.

- **Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts)
- **Base URL:** `https://balanceplatform-api-test.adyen.com`

#### Tags

- Transfers
- Payouts
- Balance Platform
- Marketplaces

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts)
- [OpenAPI](openapi/transfers-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Adyen Webhooks API

We use webhooks to send you updates about payment status updates, newly available reports, and other events that you can subscribe to.

- **Human URL:** [https://docs.adyen.com/development-resources/webhooks](https://docs.adyen.com/development-resources/webhooks)
- **Base URL:** `https://pal-test.adyen.com`

#### Tags

- Webhooks
- Notifications
- Events

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/webhooks)
- [OpenAPI](openapi/webhooks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/adyen-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/adyen)
- [Terms of Service](https://www.adyen.com/legal/terms-and-conditions)
- [Privacy Policy](https://www.adyen.com/policies-and-disclaimer/privacy-policy)
- [Authentication](https://docs.adyen.com/development-resources/api-credentials)
- [Pricing](https://www.adyen.com/pricing)
- [Documentation](https://docs.adyen.com/)
- [Getting Started](https://docs.adyen.com/get-started-with-adyen/)
- [Blog](https://www.adyen.com/knowledge-hub)
- [Login](https://authn-live.adyen.com/authn/ui/login)
- [Sandbox](https://ca-test.adyen.com)
- [Support](https://help.adyen.com/en_US)
- [Contact](https://help.adyen.com/en_US/contact)
- [Webinars](https://help.adyen.com/en_US/academy/webinars)
- [Status Page](https://status.adyen.com)
- [Release Notes](https://docs.adyen.com/development-resources/release-notes)
- [GitHub Organization](https://github.com/Adyen)
- [GitHub Repository](https://github.com/Adyen/adyen-openapi)
- [Newsletter](https://www.adyen.com/newsletter)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/adyen)
- [SDK](https://github.com/Adyen/adyen-web)
- [SDK](https://github.com/Adyen/adyen-ios)
- [SDK](https://github.com/Adyen/adyen-android)
- [SDK](https://github.com/Adyen/adyen-react-native)
- [SDK](https://github.com/Adyen/adyen-flutter)
- [SDK](https://github.com/Adyen/adyen-php-api-library)
- [SDK](https://github.com/Adyen/adyen-java-api-library)
- [SDK](https://github.com/Adyen/adyen-node-api-library)
- [SDK](https://github.com/Adyen/adyen-dotnet-api-library)
- [SDK](https://github.com/Adyen/adyen-go-api-library)
- [SDK](https://github.com/Adyen/adyen-python-api-library)
- [SDK](https://github.com/Adyen/adyen-ruby-api-library)
- [SDK](https://github.com/Adyen/adyen-apex-api-library)
- [Tools](https://github.com/Adyen/adyen-mcp)
- [Tools](https://github.com/Adyen/adyen-postman)
- [Features](undefined)
- [Use Cases](undefined)
- [Spectral Rules](rules/adyen-spectral-rules.yml)
- [Vocabulary](vocabulary/adyen-vocabulary.yaml)
- [Integrations](undefined)
- [M C P Server](https://github.com/Adyen/adyen-mcp)
- [L L Ms Txt](https://docs.adyen.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** http://apievangelist.com
