---
api_specs:
- filename: arvx-ai-readings-api-openapi.yml
  format: yaml
  label: ARVX Readings API
  slug: arvx-ai-readings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arvx-ai/openapi/arvx-ai-readings-api-openapi.yml
- filename: arvx-ai-records-api-openapi.yml
  format: yaml
  label: ARVX Records API
  slug: arvx-ai-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arvx-ai/openapi/arvx-ai-records-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, and your company's name.
  - category: financial
    text: We receive the card's brand, type (credit, debit or prepaid), last four digits, expiry date, country and billing address, never the full number.
  - category: identifying
    text: 'We receive the result and the details Stripe confirms: your verified name, address, email, phone number, and your document''s type and issuing country.'
  - category: device
    text: Network addresses, kept with sign-in, signup and card-page attempts and in account activity records, to detect misuse.
  - category: behavioral
    text: 'Usage records: your account, key, the time of each request, the service used, its size and its cost.'
  - category: communication
    text: Your emails to us at help@arvx.ai.
  deletion:
    route: Email help@arvx.ai from your account's email address, or close your account and say you want your information deleted.
    text: To ask for deletion, email help@arvx.ai from your account's email address, or close your account and say you want your information deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run your account
    text: 'To run your account: signing you in, issuing keys, and keeping your balance.'
  - purpose: Take payment
    text: 'To take payment: charging your card, issuing receipts and refunds, working out sales tax, and keeping the records tax law requires.'
  - purpose: Verify identity
    text: 'To verify who you are: confirming you are a real person before your first paid Reading, and preventing fraud.'
  - purpose: Protect the service
    text: 'To protect the service: detecting misuse, giving free Readings only once per card, and enforcing the developer terms.'
  - purpose: Contact you
    text: 'To contact you: receipts, security notices, changes to our terms or prices, and replies to your messages.'
  - purpose: Legal duties
    text: 'To meet legal duties: answering lawful requests and keeping records the law requires.'
  residency:
  - region: United States
    text: Account records are stored in Google Cloud's United States regions.
  - region: Global
    text: Service logs, which include network addresses, are kept for 30 days in Google's global log storage, which is not limited to the United States.
  retention:
  - period: 3 years
    scope: Account details and statements of intended use
    text: While your account is open, then 3 years
  - period: 7 years
    scope: Billing and tax records
    text: Billing and tax records 7 years from the transaction
  - period: 24 months
    scope: Usage records
    text: Usage records 24 months from the request
  - period: 90 days
    scope: Network addresses
    text: Network addresses, wherever we keep them 90 days
  - period: 45 days
    scope: Postmark email contents
    text: Postmark keeps the contents of our emails to you for 45 days.
  rights:
  - right: Deletion
    text: To ask for deletion, email help@arvx.ai from your account's email address, or close your account and say you want your information deleted.
  - right: Access
    text: You can also ask what personal information we hold about you, for a copy of it, or for a correction, the same way.
  - right: Correction
    text: You can also ask what personal information we hold about you, for a copy of it, or for a correction, the same way.
  - right: Non-discrimination
    text: We never treat you differently for making a request.
  - right: Authorized agent
    text: You may act through an agent you authorize.
  role:
    text: This policy explains how Centric AI, Incorporated, d/b/a ARVX ("we") handles personal information about the people who hold ARVX for Developers accounts.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your personal information for advertising, and we never use it to train any AI model.
  subprocessors:
    text: Each handles your information only to provide its service to us, under a contract.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ARVX
provenance_date: '2026-11-09'
provider_name: ARVX
provider_slug: arvx-ai
slug: arvx-ai-privacy-policy
source_date: '2026-11-09'
source_filename: arvx-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://developer.arvx.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ARVX\naid: arvx-ai\nurl: https://developer.arvx.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This policy explains how Centric AI, Incorporated, d/b/a ARVX (\"we\") handles personal information about\n    the people who hold ARVX for Developers accounts.\ndata_categories:\n- category: identifying\n  text: Your name, email address, and your company's name.\n- category: financial\n  text: We receive the card's brand, type (credit, debit or prepaid), last four digits, expiry date, country and\n    billing address, never the full number.\n- category: identifying\n  text: 'We receive\
  \ the result and the details Stripe confirms: your verified name, address, email, phone number,\n    and your document''s type and issuing country.'\n- category: device\n  text: Network addresses, kept with sign-in, signup and card-page attempts and in account activity records, to\n    detect misuse.\n- category: behavioral\n  text: 'Usage records: your account, key, the time of each request, the service used, its size and its cost.'\n- category: communication\n  text: Your emails to us at help@arvx.ai.\npurposes:\n- purpose: Run your account\n  text: 'To run your account: signing you in, issuing keys, and keeping your balance.'\n- purpose: Take payment\n  text: 'To take payment: charging your card, issuing receipts and refunds, working out sales tax, and keeping the\n    records tax law requires.'\n- purpose: Verify identity\n  text: 'To verify who you are: confirming you are a real person before your first paid Reading, and preventing\n    fraud.'\n- purpose: Protect the service\n  text:\
  \ 'To protect the service: detecting misuse, giving free Readings only once per card, and enforcing the developer\n    terms.'\n- purpose: Contact you\n  text: 'To contact you: receipts, security notices, changes to our terms or prices, and replies to your messages.'\n- purpose: Legal duties\n  text: 'To meet legal duties: answering lawful requests and keeping records the law requires.'\nretention:\n- scope: Account details and statements of intended use\n  period: 3 years\n  text: While your account is open, then 3 years\n- scope: Billing and tax records\n  period: 7 years\n  text: Billing and tax records 7 years from the transaction\n- scope: Usage records\n  period: 24 months\n  text: Usage records 24 months from the request\n- scope: Network addresses\n  period: 90 days\n  text: Network addresses, wherever we keep them 90 days\n- scope: Postmark email contents\n  period: 45 days\n  text: Postmark keeps the contents of our emails to you for 45 days.\nresidency:\n- region: United States\n\
  \  text: Account records are stored in Google Cloud's United States regions.\n- region: Global\n  text: Service logs, which include network addresses, are kept for 30 days in Google's global log storage, which\n    is not limited to the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Each handles your information only to provide its service to us, under a contract.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email help@arvx.ai from your account's email address, or close your account and say you want your information\n    deleted.\n  text: To ask for deletion, email help@arvx.ai from your account's email address, or close your account and say\n    you want your information deleted.\nrights:\n- right: Deletion\n  text: To ask for deletion, email help@arvx.ai from your account's email address, or close your account and say\n    you want your information deleted.\n- right: Access\n  text: You can also ask what personal information we hold about\
  \ you, for a copy of it, or for a correction, the\n    same way.\n- right: Correction\n  text: You can also ask what personal information we hold about you, for a copy of it, or for a correction, the\n    same way.\n- right: Non-discrimination\n  text: We never treat you differently for making a request.\n- right: Authorized agent\n  text: You may act through an agent you authorize.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your personal information for advertising, and we never use it to train any AI model.\n"
source_yaml_url: https://artifacts.apis.io/arvx-ai/privacy/arvx-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from ARVX's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
