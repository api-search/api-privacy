---
api_specs:
- filename: payjoy-carts-api-openapi.yml
  format: yaml
  label: PayJoy Carts API
  slug: payjoy-carts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-carts-api-openapi.yml
- filename: payjoy-down-payments-api-openapi.yml
  format: yaml
  label: PayJoy Down Payments API
  slug: payjoy-down-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-down-payments-api-openapi.yml
- filename: payjoy-merchants-api-openapi.yml
  format: yaml
  label: PayJoy Merchants API
  slug: payjoy-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-merchants-api-openapi.yml
- filename: payjoy-reconciliation-api-openapi.yml
  format: yaml
  label: PayJoy Reconciliation API
  slug: payjoy-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-reconciliation-api-openapi.yml
- filename: payjoy-repayments-api-openapi.yml
  format: yaml
  label: PayJoy Repayments API
  slug: payjoy-repayments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-repayments-api-openapi.yml
- filename: payjoy-salesclerks-api-openapi.yml
  format: yaml
  label: PayJoy SalesClerks API
  slug: payjoy-salesclerks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-salesclerks-api-openapi.yml
- filename: payjoy-status-api-openapi.yml
  format: yaml
  label: PayJoy Status API
  slug: payjoy-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-status-api-openapi.yml
- filename: payjoy-vouchers-api-openapi.yml
  format: yaml
  label: PayJoy Vouchers API
  slug: payjoy-vouchers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-vouchers-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identification Data: name, government ID, e-mail, telephone number, your photograph.'
  - category: financial
    text: 'Payment Information: information about how you pay your obligation with PayJoy'
  - category: device
    text: Information Concerning Your Mobile Device Including but not limited to information regarding the device, operating system, device identifier, SIM information, applications list, internet connection state, application foreground state, etc.
  - category: communication
    text: If you provide specific authorization, we may collect and process information from your mobile device related but not limited to call logs and SMS messages.
  - category: professional
    text: requested copies of your credit history which may contain professional and financial information about you
  deletion:
    route: Request to the data protection officer via privacy@payjoy.com
    text: Right to Erasure You have the right to request that the Company erase your personal data, under certain conditions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate identity and assess risk of repayment
    text: When you contract PayJoy Services, we need to process your Information to authenticate your identity and assess risk of repayment.
  - purpose: fraud prevention
    text: We process and store some of your Information for fraud prevention
  - purpose: manage payment collection
    text: We also process your Information to manage your payment obligations for payment collection purposes.
  retention:
  - period: null
    scope: Information generally
    text: The criteria considered to determine the retention period include the duration of your relationship with the Company, legal retention periods applicable, and legal prescriptions
  rights:
  - right: Access
    text: Right to Access You have the right to request access to or solicit a copy of any of your personal information that the Company may hold.
  - right: Rectification
    text: Right to Rectification You have the right to request that the Company correct any information you believe is inaccurate.
  - right: Erasure
    text: Right to Erasure You have the right to request that the Company erase your personal data, under certain conditions.
  - right: Restrict processing
    text: Right to Restrict Processing You have the right to request that the Company restrict the processing of your personal data, under certain conditions.
  - right: Portability
    text: Right to Data Portability You have the right to request that the Company transfer the data that we have collected to another organization, or directly to you, under certain conditions.
  - right: Withdraw consent
    text: Right to Withdraw Consent Where the Company has relied on your consent to process particular information
  - right: Lodge complaint
    text: Right to Lodge a Complaint You have a right to bring a claim to the competent data protection authority.
  role:
    text: The Company
    value: controller
  sale_or_sharing:
    stance: conditional
    text: your Information may be sold or transferred as part of such a transaction as permitted by applicable law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may transfer the personal information we collect about you to recipients in countries other than the country in which the information was originally collected.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PayJoy
provenance_date: '2026-11-10'
provider_name: PayJoy
provider_slug: payjoy
slug: payjoy-privacy-policy
source_date: '2026-11-10'
source_filename: payjoy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.payjoy.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PayJoy\naid: payjoy\nurl: https://www.payjoy.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Company\ndata_categories:\n- category: identifying\n  text: 'Identification Data: name, government ID, e-mail, telephone number, your photograph.'\n- category: financial\n  text: 'Payment Information: information about how you pay your obligation with PayJoy'\n- category: device\n  text: Information Concerning Your Mobile Device Including but not limited to information regarding the device,\n    operating system, device identifier, SIM information, applications list, internet\
  \ connection state, application\n    foreground state, etc.\n- category: communication\n  text: If you provide specific authorization, we may collect and process information from your mobile device related\n    but not limited to call logs and SMS messages.\n- category: professional\n  text: requested copies of your credit history which may contain professional and financial information about you\npurposes:\n- purpose: authenticate identity and assess risk of repayment\n  text: When you contract PayJoy Services, we need to process your Information to authenticate your identity and\n    assess risk of repayment.\n- purpose: fraud prevention\n  text: We process and store some of your Information for fraud prevention\n- purpose: manage payment collection\n  text: We also process your Information to manage your payment obligations for payment collection purposes.\nretention:\n- scope: Information generally\n  period: null\n  text: The criteria considered to determine the retention period include\
  \ the duration of your relationship with\n    the Company, legal retention periods applicable, and legal prescriptions\nresidency: []\ntransfers:\n- mechanism: other\n  text: We may transfer the personal information we collect about you to recipients in countries other than the\n    country in which the information was originally collected.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to the data protection officer via privacy@payjoy.com\n  text: Right to Erasure You have the right to request that the Company erase your personal data, under certain\n    conditions.\nrights:\n- right: Access\n  text: Right to Access You have the right to request access to or solicit a copy of any of your personal information\n    that the Company may hold.\n- right: Rectification\n  text: Right to Rectification You have the right to request that the Company correct any information you believe\n    is inaccurate.\n- right: Erasure\n\
  \  text: Right to Erasure You have the right to request that the Company erase your personal data, under certain\n    conditions.\n- right: Restrict processing\n  text: Right to Restrict Processing You have the right to request that the Company restrict the processing of your\n    personal data, under certain conditions.\n- right: Portability\n  text: Right to Data Portability You have the right to request that the Company transfer the data that we have\n    collected to another organization, or directly to you, under certain conditions.\n- right: Withdraw consent\n  text: Right to Withdraw Consent Where the Company has relied on your consent to process particular information\n- right: Lodge complaint\n  text: Right to Lodge a Complaint You have a right to bring a claim to the competent data protection authority.\nsale_or_sharing:\n  stance: conditional\n  text: your Information may be sold or transferred as part of such a transaction as permitted by applicable law.\n"
source_yaml_url: https://artifacts.apis.io/payjoy/privacy/payjoy-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from PayJoy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Lending
- Buy Now Pay Later
- Point-of-Sale
- Emerging Markets
- Financial Inclusion
- Partner API
---
