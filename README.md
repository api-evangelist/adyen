# Adyen (adyen)
Adyen is a global payment company that provides businesses with a single platform to accept payments from customers worldwide. Their technology enables companies to accept a wide range of payment methods, including credit cards, digital wallets, and local payment methods, in multiple currencies and countries. Adyen also offers services such as fraud prevention, data analytics, and optimization tools to help businesses streamline their payment processes and improve their overall performance. With a focus on security, speed, and reliability, Adyen aims to simplify the payment experience for both merchants and customers, ultimately driving growth and success for businesses of all sizes.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/apis-json/artisanal/main/apis/adyen.yml)

## Scope


## Tags:

 - Payments

## Timestamps

- **Created:** 2023/11/13 
- **Modified:** 2024-12-24 

## APIs

### Adyen Accounting Notifications API
Adyen sends notifications through webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/](https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/)

**Base URL:** [https://cal-test.adyen.com](https://cal-test.adyen.com)


#### Tags:

 - Accounting, Notifications, Webhooks

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/configure-notifications/)
- [OpenAPI](properties/adyen-accounting-notifications-api-openapi.yml)
### Adyen Account API
This API is used for the classic integration. If you are just starting your implementation, refer to our new integration guide instead. The Account API provides endpoints for managing account-related entities on your platform. These related entities include account holders, accounts, bank accounts, shareholders, and verification-related documents. The management operations include actions such as creation, retrieval, updating, and deletion of them.

**Human URL:** [https://docs.adyen.com/api-explorer/Account/6/overview](https://docs.adyen.com/api-explorer/Account/6/overview)

**Base URL:** [https://cal-test.adyen.com](https://cal-test.adyen.com)


#### Tags:

 - Checks, Accounts, Holders, Close, Stores, Account, Bank, Legal, Arrangements, Methods, Shareholders, Signatories, Tax, Forms, Uploaded, Documents, Suspend, State, Uploads

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/Account/6/overview)
- [OpenAPI](properties/adyen-account-api-openapi.yml)
### Adyen Authentication Webhooks API
Adyen sends webhooks to inform your system about events related to cardholder authentication.

**Human URL:** [https://docs.adyen.com/development-resources/webhooks/](https://docs.adyen.com/development-resources/webhooks/)

**Base URL:** [https://cal-test.adyen.com](https://cal-test.adyen.com)


#### Tags:

 - Authentication, Webhooks

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/webhooks/)
- [OpenAPI](openapi/authentication-webhooks-openapi-original.yml)
### Adyen Balance Control API
The Balance Control API lets you transfer funds between merchant accounts that belong to the same legal entity and are under the same company account.

**Human URL:** [https://docs.adyen.com/api-explorer/BalanceControl/1/overview](https://docs.adyen.com/api-explorer/BalanceControl/1/overview)

**Base URL:** [https://cal-test.adyen.com](https://cal-test.adyen.com)


#### Tags:

 - Balance, Transfers

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/BalanceControl/1/overview)
- [OpenAPI](properties/adyen-balance-control-api-openapi.yml)
### Adyen BinLookup API
The BIN Lookup API provides endpoints for retrieving information, such as cost estimates, and 3D Secure supported version based on a given BIN.

**Human URL:** [https://docs.adyen.com/api-explorer/BinLookup/52/overview](https://docs.adyen.com/api-explorer/BinLookup/52/overview)

**Base URL:** [https://pal-test.adyen.com](https://pal-test.adyen.com)


#### Tags:

 - Availability, Cost, Estimates

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/BinLookup/52/overview)
- [OpenAPI](properties/adyen-binlookup-api-openapi.yml)
### Adyen Checkout API
This is the description of your API.

**Human URL:** [https://docs.adyen.com/api-explorer/Checkout/71/overview](https://docs.adyen.com/api-explorer/Checkout/71/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - Apple, Pay, Sessions, Cancels, Card, Donations, Orders, Origin, Keys, Payments, Links, Methods, Balance, Session, Results, Psp, References, Amount, Captures, Refunds, Reversals, Stored, Method

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/Checkout/71/overview)
- [OpenAPI](properties/adyen-checkout-api-openapi.yml)
### Adyen Configuration API
The Configuration API enables you to create a platform where you can onboard your users as account holders and create balance accounts, cards, and business accounts.

**Human URL:** [https://docs.adyen.com/api-explorer/balanceplatform/2/overview](https://docs.adyen.com/api-explorer/balanceplatform/2/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - Accounts, Holders, Balance, Tax, Forms, Sweeps, Sweep, Payment, Instruments, Platforms, Account, Card Orders, Items, Offers, Offer, Networks, Tokens, Token, Payments, Transaction, Rules, Network, Reveal, Pins, Changes, Public, Keys, Transfers, Routes, Calculate, Validate, Bank, Identification

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/balanceplatform/2/overview)
- [OpenAPI](properties/adyen-configuration-api-openapi.yml)
### Adyen Configuration Webhooks API
Adyen sends webhooks to inform your system about events that occur in your platform. These events include, for example, when an account holders capabilities are updated, or when a sweep configuration is created or updated. When an event occurs, Adyen makes an HTTP POST request to a URL on your server and includes the details of the event in the request body. You can use these webhooks to build your implementation.

**Human URL:** [https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview](https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - Configuraton, Webhooks

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/balanceplatform-webhooks/1/overview)
- [OpenAPI](openapi/configuration-webhooks-openapi-original.yml)
### Adyen Data Protection API
Adyen Data Protection API provides a way for you to process [Subject Erasure Requests](https://gdpr-info.eu/art-17-gdpr/) as mandated in GDPR. Use our API to submit a request to delete shopper''s data, including payment details and other related information (for example, delivery address or shopper email).

**Human URL:** [https://gdpr-info.eu/art-17-gdpr/](https://gdpr-info.eu/art-17-gdpr/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 -  Subjects,  Erasure

#### Properties

- [Documentation](https://gdpr-info.eu/art-17-gdpr/)
- [OpenAPI](properties/adyen-data-protection-api-openapi.yml)
### Adyen Disputes API
You can use the Disputes API to automate the dispute handling process so that you can respond to disputes and chargebacks as soon as they are initiated. The Disputes API lets you retrieve defense reasons, supply and delete defense documents, and accept or defend disputes.

**Human URL:** [https://docs.adyen.com/risk-management/disputes-api](https://docs.adyen.com/risk-management/disputes-api)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/risk-management/disputes-api)
- [OpenAPI](openapi/disputes-openapi-original.yml)
### Adyen Funds API
The Fund API provides endpoints for managing the funds in the accounts on your platform. These management operations include, for example, the transfer of funds from one account to another, the payout of funds to an account holder, and the retrieval of balances in an account.

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/](https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/fund-transfer/)
- [OpenAPI](openapi/funds-openapi-original.yml)
### Adyen Hosted Onboarding API
The Fund API provides endpoints for managing the funds in the accounts on your platform. These management operations include, for example, the transfer of funds from one account to another, the payout of funds to an account holder, and the retrieval of balances in an account.

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/](https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/collect-verification-details/hosted/)
- [OpenAPI](openapi/hosted-onboarding-openapi-original.yml)
### Adyen Legal Entity API
The Legal Entity Management API enables you to manage legal entities that contain information required for verification.

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/](https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/)
- [OpenAPI](openapi/legal-entity-openapi-original.yml)
### Adyen Legal Entity API
The Legal Entity Management API enables you to manage legal entities that contain information required for verification.

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/](https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/legal-entity-management-api/)
- [OpenAPI](openapi/legal-entity-openapi-original.yml)
### Adyen Management API
Configure and manage your Adyen company and merchant accounts, stores, and payment terminals.

**Human URL:** [https://docs.adyen.com/api-explorer/Management/3/overview](https://docs.adyen.com/api-explorer/Management/3/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/Management/3/overview)
- [OpenAPI](openapi/management-openapi-original.yml)
### Adyen Management Webhooks API
Adyen uses webhooks to inform your system about events that happen with your Adyen company and merchant accounts, stores, payment terminals, and payment methods when using [Management API](https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview). When a and includes the details of the event in the request body. See [Webhooks](https://docs.adyen.com/development-resources/webhooks) for more information.

**Human URL:** [https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview](https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview)
- [OpenAPI](openapi/management-webhooks-openapi-original.yml)
### Adyen Notification Configuration API
This API is used for the classic integration. If you are just starting your implementation, refer to our [new integration guide](https://docs.adyen.com/marketplaces-and-platforms) instead.\n\nThe Notification Configuration API provides endpoints for setting up and testing notifications that inform you of events on your platform, for example when a verification check or a payout has been completed.\n\nFor more information, refer to our [documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications).

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/notifications](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)
- [OpenAPI](openapi/notification-configurations-openapi-original.yml)
### Adyen Notification Webhooks API
Adyen sends notifications through webhooks to inform your system about events that occur in the balance platform. These events include, for example, a card user making a payment, or a merchant starting a refund. When an event occurs, Adyen makes an HTTP POST request to a URL on your server and includes the details of the event in the request body. You can use the webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

**Human URL:** [https://docs.adyen.com/point-of-sale/design-your-integration/notifications/](https://docs.adyen.com/point-of-sale/design-your-integration/notifications/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/point-of-sale/design-your-integration/notifications/)
- [OpenAPI](openapi/notification-webhooks-openapi-original.yml)
### Adyen Notifications API
The Notification API sends notifications to the endpoints specified in a given subscription. Subscriptions are managed through the Notification Configuration API. The API specifications listed here detail the format of each notification. For more information, refer to our [documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications).

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/classic/notifications](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications)
- [OpenAPI](openapi/notifications-openapi-original.yml)
### Adyen Payments API
A set of API endpoints that allow you to initiate, settle, and modify payments on the Adyen payments platform. You can use the API to accept card payments (including One-Click and 3D Secure), bank transfers, ewallets, and many other payment methods.

**Human URL:** [https://docs.adyen.com/online-payments/](https://docs.adyen.com/online-payments/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/online-payments/)
- [OpenAPI](openapi/payments-openapi-original.yml)
### Adyen Payouts API
A set of API endpoints that allow you to store payout details, confirm, or decline a payout.\n\nFor more information, refer to [Online payouts](https://docs.adyen.com/online-payments/online-payouts).

**Human URL:** [https://docs.adyen.com/online-payments/online-payouts](https://docs.adyen.com/online-payments/online-payouts)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/online-payments/online-payouts)
- [OpenAPI](openapi/payouts-openapi-original.yml)
### Adyen POS Terminal API
This API provides endpoints for managing your point-of-sale (POS) payment terminals. You can use the API to obtain information about a specific terminal, retrieve overviews of your terminals and stores, and assign terminals to a merchant account or store.

**Human URL:** [https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/)
- [OpenAPI](openapi/pos-terminal-openapi-original.yml)
### Adyen Recurring API
The Recurring APIs allow you to manage and remove your tokens or saved payment details. Tokens should be created with validation during a payment request. For more information, refer to our [Tokenization documentation](https://docs.adyen.com/online-payments/tokenization).

**Human URL:** [https://docs.adyen.com/online-payments/tokenization](https://docs.adyen.com/online-payments/tokenization)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/online-payments/tokenization)
- [OpenAPI](openapi/recurring-openapi-original.yml)
### Adyen Report Webhooks API
Adyen sends webhooks to inform your system that reports were generated and are ready to be downloaded. You can download reports programmatically by making an HTTP GET request, or manually from your [Balance Platform Customer Area](https://balanceplatform-test.adyen.com/balanceplatform).

**Human URL:** [https://docs.adyen.com/api-explorer/report-webhooks/1/overview](https://docs.adyen.com/api-explorer/report-webhooks/1/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/report-webhooks/1/overview)
- [OpenAPI](openapi/report-webhooks-openapi-original.yml)
### Adyen Stored Value API
A set of API endpoints to manage stored value products.

**Human URL:** [https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/](https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/payment-methods/gift-cards/stored-value-api/)
- [OpenAPI](openapi/stored-value-openapi-original.yml)
### Adyen Terminal API
The Adyen Terminal API lets you make payments, issue refunds, collect shopper information, and perform other shopper-terminal interactions using a payment terminal supplied by Adyen.

**Human URL:** [https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/point-of-sale/design-your-integration/terminal-api/terminal-api-reference/)
- [OpenAPI](openapi/terminal-openapi-original.yml)
### Adyen Test Cards API
The Test Cards API provides endpoints for generating custom test card numbers. For more information, refer to [Custom test cards](https://docs.adyen.com/development-resources/testing/create-test-cards) documentation.

**Human URL:** [https://docs.adyen.com/development-resources/testing/create-test-cards](https://docs.adyen.com/development-resources/testing/create-test-cards)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/testing/create-test-cards)
- [OpenAPI](openapi/test-cards-openapi-original.yml)
### Adyen Transaction Webhooks API
Adyen sends webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions/transaction-webhooks/)
- [OpenAPI](openapi/transaction-webhooks-openapi-original.yml)
### Adyen Transfer Webhooks API
Adyen sends webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.

**Human URL:** [https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview](https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/api-explorer/transfer-webhooks/3/overview)
- [OpenAPI](openapi/transfer-webhooks-openapi-original.yml)
### Adyen Transfers API
This API provides endpoints that you can use to transfer funds, whether when [paying out to a transfer instrument](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts), [sending funds to third parties](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/send-receive-funds) for users with business bank accounts, or to [request a payout for a grant offer](https://docs.adyen.com/marketplaces-and-platforms/capital). The API also supports use cases for [getting transactions for business bank accounts](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions-api) and getting [grants and its outstanding balances](https://docs.adyen.com/marketplaces-and-platforms/capital#get-balances).

**Human URL:** [https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts)
- [OpenAPI](openapi/transfers-openapi-original.yml)
### Adyen Webhooks API
We use webhooks to send you updates about payment status updates, newly available reports, and other events that you can subscribe to. For more information, refer to our [documentation](https://docs.adyen.com/development-resources/webhooks).

**Human URL:** [https://docs.adyen.com/development-resources/webhooks](https://docs.adyen.com/development-resources/webhooks)

**Base URL:** [https://api.example.com](https://api.example.com)


#### Tags:

 - No Tags

#### Properties

- [Documentation](https://docs.adyen.com/development-resources/webhooks)
- [OpenAPI](openapi/webhooks-openapi-original.yml)

## Common Properties

- [Terms of Service](https://www.adyen.com/legal/terms-and-conditions)
- [Authentication](https://www.adyen.com/authentication-3d-secure)
- [Plans](https://www.adyen.com/pricing)
- [Documentation](https://docs.adyen.com/)
- [Newsletter](https://www.adyen.com/newsletter)
- [Knowledge](https://www.adyen.com/knowledge-hub)
- [Login](https://authn-live.adyen.com/authn/ui/login)
- [Support](https://help.adyen.com/en_US)
- [Contact](https://help.adyen.com/en_US/contact)
- [Webinars](https://help.adyen.com/en_US/academy/webinars)
- [Privacy](https://www.adyen.com/policies-and-disclaimer/privacy-policy)
- [OpenAPI](https://github.com/Adyen/adyen-openapi)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com

