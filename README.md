# Adyen (adyen)
End-to-end payments, data, and financial management in a single solution. Meet the financial technology platform that helps you realize your ambitions faster.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-search/payments/main/_apis/adyen/apis.md)

## Scope


## Tags

- Payments

## Timestamps

- **Created:** 2024/04/14 
- **Modified:** 2024-12-10 

## APIs

### Adyen Accounting Notifications API
Adyen sends notifications through webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.


#### Tags

### Adyen Account API
This API is used for the classic integration. If you are just starting your implementation, refer to our new integration guide instead. The Account API provides endpoints for managing account-related entities on your platform. These related entities include account holders, accounts, bank accounts, shareholders, and verification-related documents. The management operations include actions such as creation, retrieval, updating, and deletion of them.


#### Tags

- Accounts
- Arrangements
- Bank
- Close
- Documents
- Forms
- Holders
- Legal
- Methods
- Payouts
- Processing
- Shareholders
- Signatories
- States
- Stores
- Suspend
- Taxes
- Triggers
- Unsuspend
- Uploaded
- Uploads
- Verification
### Adyen Authentication Webhooks API
Adyen sends webhooks to inform your system about events related to cardholder authentication.


#### Tags

### Adyen Balance Control API
The Balance Control API lets you transfer funds between merchant accounts that belong to the same legal entity and are under the same company account.


#### Tags

- Balance
- Transfers
### Adyen BinLookup API
The BIN Lookup API provides endpoints for retrieving information, such as cost estimates, and 3D Secure supported version based on a given BIN.


#### Tags

- Availability
- Available
- Checks
- Cost
- Estimates
- Fees
- If
- Is
- Secure
### Adyen Checkout API
Adyen Checkout API provides a simple and flexible way to initiate and authorise online payments. You can use the same integration for payments made with cards (including 3D Secure), mobile wallets, and local payment methods (for example, iDEAL and Sofort).

**Human URL:** [https://docs.adyen.com/api-explorer/Checkout/latest/overview](https://docs.adyen.com/api-explorer/Checkout/latest/overview)
r

#### Tags

- Checkout
- Payments
### Adyen Configuration API
The Configuration API enables you to create a platform where you can onboard your users as account holders and create balance accounts, cards, and business accounts.


#### Tags

- Configurations
- Cards
- Balance Accounts
- Business Accounts
- Accounts
### Adyen Configuration Webhooks API
Adyen sends webhooks to inform your system about events that occur in your platform. These events include, for example, when an account holders capabilities are updated, or when a sweep configuration is created or updated. When an event occurs, Adyen makes an HTTP POST request to a URL on your server and includes the details of the event in the request body. You can use these webhooks to build your implementation.


#### Tags

### Adyen Data Protection API
Adyen Data Protection API provides a way for you to process [Subject Erasure Requests](https://gdpr-info.eu/art-17-gdpr/) as mandated in GDPR. Use our API to submit a request to delete shopper''s data, including payment details and other related information (for example, delivery address or shopper email).


#### Tags

- Erasure
- Subjects
- Submit
### Adyen Disputes API
You can use the Disputes API to automate the dispute handling process so that you can respond to disputes and chargebacks as soon as they are initiated. The Disputes API lets you retrieve defense reasons, supply and delete defense documents, and accept or defend disputes.


#### Tags

- Accept
- Applicable
- Defend
- Defense
- Disputes
- Documents
- Reasons
- Supply
### Adyen Funds API
The Fund API provides endpoints for managing the funds in the accounts on your platform. These management operations include, for example, the transfer of funds from one account to another, the payout of funds to an account holder, and the retrieval of balances in an account.


#### Tags

- Accounts
- Balance
- Balances
- Benefactor's
- Beneficiary
- Between
- Current
- Debit
- Designate
- Direct
- Funds
- Holders
- Most
- Out
- Paid
- Pay
- Payouts
- Platforms
- Recent
- Refunds
- Send
- Since
- The
- Transactions
- Transfers
### Adyen Hosted Onboarding API
The Fund API provides endpoints for managing the funds in the accounts on your platform. These management operations include, for example, the transfer of funds from one account to another, the payout of funds to an account holder, and the retrieval of balances in an account.


#### Tags

- Adyen-hosted
- Compliance
- Link
- Onboarding
- PCI
- Page
- Questionnaires
- URL
### Adyen Legal Entity API
The Legal Entity Management API enables you to manage legal entities that contain information required for verification.


#### Tags

- Accept
- Acceptance
- Adyen-hosted
- Business
- Checks
- Confirm
- Data
- Details
- Documents
- Entities
- Errors
- Generate
- Hosted
- Information
- Instruments
- Legal
- Line
- Lines
- Link
- Links
- Onboarding
- PCI
- Page
- Pciid
- Questionnaires
- Reviews
- Services
- Sign
- Status
- Templates
- Terms
- Terms Of Service Documents
- Theme
- Themes
- Transfers
- Under
- Uploads
- Verification
### Adyen Legal Entity API
The Legal Entity Management API enables you to manage legal entities that contain information required for verification.


#### Tags

- Accept
- Acceptance
- Adyen-hosted
- Business
- Checks
- Confirm
- Data
- Details
- Documents
- Entities
- Errors
- Generate
- Hosted
- Information
- Instruments
- Legal
- Line
- Lines
- Link
- Links
- Onboarding
- PCI
- Page
- Pciid
- Questionnaires
- Reviews
- Services
- Sign
- Status
- Templates
- Terms
- Terms Of Service Documents
- Theme
- Themes
- Transfers
- Under
- Uploads
- Verification
### Adyen Management API
Configure and manage your Adyen company and merchant accounts, stores, and payment terminals.


#### Tags

- Accounts
- Actions
- Activate
- Allowed
- Android
- Apple
- Applications
- Billing
- Cancel
- Certificates
- Clients
- Companies
- Conditions
- Configurations
- Credentials
- Descriptions
- Details
- Domains
- Entities
- Generate
- HMAC
- Keys
- Locations
- Logic
- Logo
- Logos
- Me
- Merchants
- Methods
- Models
- Orders
- Origin
- Origins
- Pay
- Payments
- Payouts
- Products
- Reassign
- References
- Removes
- Rules
- Sets
- Settings
- Shipping
- Split
- Store
- Stores
- Terminal
- Terminals
- Tests
- The
- Up
- Uploads
- Users
- Webhooks
### Adyen Management Webhooks API
Adyen uses webhooks to inform your system about events that happen with your Adyen company and merchant accounts, stores, payment terminals, and payment methods when using [Management API](https://docs.adyen.com/api-explorer/#/ManagementService/latest/overview). When a and includes the details of the event in the request body. See [Webhooks](https://docs.adyen.com/development-resources/webhooks) for more information.


#### Tags

### Adyen Notification Configuration API
This API is used for the classic integration. If you are just starting your implementation, refer to our [new integration guide](https://docs.adyen.com/marketplaces-and-platforms) instead.\n\nThe Notification Configuration API provides endpoints for setting up and testing notifications that inform you of events on your platform, for example when a verification check or a payout has been completed.\n\nFor more information, refer to our [documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications).


#### Tags

- Configurations
- Notifications
- Subscribe
- Subscriptions
- Tests
### Adyen Notification Webhooks API
Adyen sends notifications through webhooks to inform your system about events that occur in the balance platform. These events include, for example, a card user making a payment, or a merchant starting a refund. When an event occurs, Adyen makes an HTTP POST request to a URL on your server and includes the details of the event in the request body. You can use the webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.


#### Tags

### Adyen Notifications API
The Notification API sends notifications to the endpoints specified in a given subscription. Subscriptions are managed through the Notification Configuration API. The API specifications listed here detail the format of each notification. For more information, refer to our [documentation](https://docs.adyen.com/marketplaces-and-platforms/classic/notifications).


#### Tags

### Adyen Payments API
A set of API endpoints that allow you to initiate, settle, and modify payments on the Adyen payments platform. You can use the API to accept card payments (including One-Click and 3D Secure), bank transfers, ewallets, and many other payment methods.


#### Tags

- Amount
- Authentication
- Authorised
- Authorization
- Cancel
- Capture
- Captured
- Change
- Complete
- Donate
- Donations
- In-person
- Payments
- Pending
- References
- Refunds
- Results
- The
- Using
- Your
- ~!
### Adyen Payouts API
A set of API endpoints that allow you to store payout details, confirm, or decline a payout.\n\nFor more information, refer to [Online payouts](https://docs.adyen.com/online-payments/online-payouts).


#### Tags

- Cancel
- Cards
- Confirm
- Detail
- Details
- Instant
- Make
- Party
- Payouts
- Store
- Submit
- Third
### Adyen POS Terminal API
This API provides endpoints for managing your point-of-sale (POS) payment terminals. You can use the API to obtain information about a specific terminal, retrieve overviews of your terminals and stores, and assign terminals to a merchant account or store.


#### Tags

- Accounts
- Assign
- Details
- Store
- Stores
- Terminal
- Terminals
- The
- Under
### Adyen Recurring API
The Recurring APIs allow you to manage and remove your tokens or saved payment details. Tokens should be created with validation during a payment request. For more information, refer to our [Tokenization documentation](https://docs.adyen.com/online-payments/tokenization).


#### Tags

- Accounts
- Ask
- Contracts
- Details
- Disable
- Existing
- Issuer
- Linked
- Notify
- Payments
- Permits
- Recurring
- Running
- Schedules
- Shopper
- Stored
- The
### Adyen Report Webhooks API
Adyen sends webhooks to inform your system that reports were generated and are ready to be downloaded. You can download reports programmatically by making an HTTP GET request, or manually from your [Balance Platform Customer Area](https://balanceplatform-test.adyen.com/balanceplatform).


#### Tags

### Adyen Stored Value API
A set of API endpoints to manage stored value products.


#### Tags

- Balance
- Cards
- Change
- Changes
- Checks
- Issues
- Load
- Loads
- Merge
- Methods
- Payments
- Status
- The
- Transactions
- Voids
### Adyen Terminal API
The Adyen Terminal API lets you make payments, issue refunds, collect shopper information, and perform other shopper-terminal interactions using a payment terminal supplied by Adyen.


#### Tags

- Acquisition
- Administrative
- Balance
- Balance Inquiry
- Card Acquisitions
- Card Reader Applications
- Cards
- Diagnosis
- Display
- Enable
- Enable Service
- Gettotals
- Inputs
- Inquiries
- Login
- Logout
- Loyalty
- Payments
- Print
- Readers
- Reconciliation
- Reversals
- Services
- Status
- Stored
- Stored Values
- Totals
- Transaction Status
- Transactions
- Value
### Adyen Test Cards API
The Test Cards API provides endpoints for generating custom test card numbers. For more information, refer to [Custom test cards](https://docs.adyen.com/development-resources/testing/create-test-cards) documentation.


#### Tags

- Cards
- Creates
- More
- One
- Ranges
- Tests
### Adyen Transaction Webhooks API
Adyen sends webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.


#### Tags

### Adyen Transfer Webhooks API
Adyen sends webhooks to inform your system about incoming and outgoing transfers in your platform. You can use these webhooks to build your implementation. For example, you can use this information to update balances in your own dashboards or to keep track of incoming funds.


#### Tags

### Adyen Transfers API
This API provides endpoints that you can use to transfer funds, whether when [paying out to a transfer instrument](https://docs.adyen.com/marketplaces-and-platforms/payout-to-users/on-demand-payouts), [sending funds to third parties](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/send-receive-funds) for users with business bank accounts, or to [request a payout for a grant offer](https://docs.adyen.com/marketplaces-and-platforms/capital). The API also supports use cases for [getting transactions for business bank accounts](https://docs.adyen.com/marketplaces-and-platforms/business-accounts/transactions-api) and getting [grants and its outstanding balances](https://docs.adyen.com/marketplaces-and-platforms/capital#get-balances).


#### Tags

- Accounts
- Capital
- Details
- Funds
- Grants
- Grants""
- Payouts
- References
- Returns
- Transactions
- Transfers
### Adyen Webhooks API
We use webhooks to send you updates about payment status updates, newly available reports, and other events that you can subscribe to. For more information, refer to our [documentation](https://docs.adyen.com/development-resources/webhooks).


#### Tags


## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com

