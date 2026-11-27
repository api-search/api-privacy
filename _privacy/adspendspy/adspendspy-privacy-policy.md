---
api_specs:
- filename: adspendspy-api-openapi.json
  format: json
  label: Meta Ad Library Spend API by AdSpendSpy API
  slug: meta-ad-library-spend-api-by-adspendspy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adspendspy/openapi/_original/adspendspy-api-openapi.json
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, password, and profile picture when you create an account'
  - category: financial
    text: 'Payment Information: Billing details and payment method information processed securely through Stripe'
  - category: behavioral
    text: 'Usage Data: Information about how you interact with our service, including tracked brands, favorite ads, and search queries'
  - category: device
    text: 'Technical Data: IP address, browser type, device information, and cookies to improve your experience'
  - category: communication
    text: 'Communications: Any messages, feedback, or support requests you send to us'
  deletion:
    route: Settings, Delete your account on the website, or Me, Delete account in the app
    text: You can delete your account and personal data yourself, on the website under Settings, Delete your account, or in the mobile app under Me, Delete account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve our services
  - purpose: Process transactions
    text: Process your transactions and send you related information
  - purpose: Marketing communications
    text: Communicate with you about products, services, offers, and promotions
  - purpose: Fraud detection
    text: Detect, prevent, and address technical issues and fraudulent activities
  - purpose: Personalization
    text: Personalize your experience and provide content recommendations
  retention:
  - period: 14 days
    scope: Account deletion
    text: hold the account frozen for 14 days, so you can still change your mind. After that the deletion is permanent.
  - period: null
    scope: Invoices and payment records
    text: Invoices, payment and subscription records and affiliate settlements are kept without your personal details, because tax law requires us to retain them.
  - period: 30-day period
    scope: Automation delivery content
    text: The content of each delivery is cleared after a 30-day period.
  rights:
  - right: Access and update
    text: 'Access and Update: You can access and update your account information through your settings page'
  - right: Delete
    text: 'Delete: You can delete your account and personal data yourself'
  - right: Opt-out of marketing
    text: 'Opt-Out: You can opt out of marketing communications by following the unsubscribe link in our emails'
  - right: Data portability
    text: 'Data Portability: You can request a copy of your personal data in a structured format'
  role:
    text: 'The controller responsible for processing your personal data is: Eastbound Sp. z o.o.'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information to third parties for their marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the transfer is covered by the EU standard contractual clauses
  - mechanism: other
    text: data may be processed in the United States, see International Data Transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AdSpendSpy (Meta Ad Library Spend API)
provenance_date: '2026-11-09'
provider_name: AdSpendSpy (Meta Ad Library Spend API)
provider_slug: adspendspy
slug: adspendspy-privacy-policy
source_date: '2026-11-09'
source_filename: adspendspy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.adspendspy.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AdSpendSpy (Meta Ad Library Spend API)\naid: adspendspy\nurl: https://www.adspendspy.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller responsible for processing your personal data is: Eastbound Sp. z o.o.'\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, password, and profile picture when you create an account'\n- category: financial\n  text: 'Payment Information: Billing details and payment method information processed securely through Stripe'\n- category: behavioral\n  text: 'Usage Data: Information about how you interact\
  \ with our service, including tracked brands, favorite ads,\n    and search queries'\n- category: device\n  text: 'Technical Data: IP address, browser type, device information, and cookies to improve your experience'\n- category: communication\n  text: 'Communications: Any messages, feedback, or support requests you send to us'\npurposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve our services\n- purpose: Process transactions\n  text: Process your transactions and send you related information\n- purpose: Marketing communications\n  text: Communicate with you about products, services, offers, and promotions\n- purpose: Fraud detection\n  text: Detect, prevent, and address technical issues and fraudulent activities\n- purpose: Personalization\n  text: Personalize your experience and provide content recommendations\nretention:\n- scope: Account deletion\n  period: 14 days\n  text: hold the account frozen for 14 days, so you can still change your mind.\
  \ After that the deletion is permanent.\n- scope: Invoices and payment records\n  period: null\n  text: Invoices, payment and subscription records and affiliate settlements are kept without your personal details,\n    because tax law requires us to retain them.\n- scope: Automation delivery content\n  period: 30-day period\n  text: The content of each delivery is cleared after a 30-day period.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: the transfer is covered by the EU standard contractual clauses\n- mechanism: other\n  text: data may be processed in the United States, see International Data Transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings, Delete your account on the website, or Me, Delete account in the app\n  text: You can delete your account and personal data yourself, on the website under Settings, Delete your account,\n    or in the mobile app under Me, Delete account.\nrights:\n- right:\
  \ Access and update\n  text: 'Access and Update: You can access and update your account information through your settings page'\n- right: Delete\n  text: 'Delete: You can delete your account and personal data yourself'\n- right: Opt-out of marketing\n  text: 'Opt-Out: You can opt out of marketing communications by following the unsubscribe link in our emails'\n- right: Data portability\n  text: 'Data Portability: You can request a copy of your personal data in a structured format'\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information to third parties for their marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/adspendspy/privacy/adspendspy-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from AdSpendSpy (Meta Ad Library Spend API)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Analytics
- Meta
---
