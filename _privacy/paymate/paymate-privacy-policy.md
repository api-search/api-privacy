---
api_specs:
- filename: paymate-businesses-api-openapi.yml
  format: yaml
  label: PayMate Businesses API
  slug: paymate-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-businesses-api-openapi.yml
- filename: paymate-cards-api-openapi.yml
  format: yaml
  label: PayMate Cards API
  slug: paymate-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-cards-api-openapi.yml
- filename: paymate-collections-api-openapi.yml
  format: yaml
  label: PayMate Collections API
  slug: paymate-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-collections-api-openapi.yml
- filename: paymate-contacts-api-openapi.yml
  format: yaml
  label: PayMate Contacts API
  slug: paymate-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-contacts-api-openapi.yml
- filename: paymate-payments-api-openapi.yml
  format: yaml
  label: PayMate Payments API
  slug: paymate-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-payments-api-openapi.yml
- filename: paymate-reference-api-openapi.yml
  format: yaml
  label: PayMate Reference API
  slug: paymate-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymate/openapi/paymate-reference-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, postal address, age, mobile/telephone phone number, email address, Aadhaar issued by Unique Identification Authority of India and masked as per applicable laws, Permanent Account Number (‘PAN’) issued by the Income Tax Department
  - category: financial
    text: financial information like bank account details, shipping, billing or communication address of the customer
  - category: device
    text: device ID for mapping the application to the device on which it is registered
  - category: location
    text: Geolocation Information
  - category: behavioral
    text: analysis of the User behaviour on the Sites
  - category: communication
    text: SMS for entering the activation code directly in the application during the activation
  deletion:
    route: Withdrawal of consent by email
    text: 'You may choose not to provide Your SPDI, at any time while availing the Services or otherwise, or withdraw Your consent provided to Us earlier, in writing to our email ID: support@paymate.co.in'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Payment aggregation, payouts and verification services
    text: For providing payment aggregation, payouts and verification services to our merchants, business partners and end-customers.
  - purpose: Compliance with screening requirements
    text: to comply with screening requirements as per Applicable Laws.
  - purpose: Targeted advertisements
    text: We may collect Your device information in order to gain insights about Your use of Our website or Services, to provide a customized experience, and to show targeted advertisements.
  - purpose: Fraud detection
    text: to detect and protect us against error, fraud and other criminal activity
  retention:
  - period: null
    scope: Account closed data
    text: If your Account is closed, we may take steps to mask Data and other information, but PayMate reserves our ability to retain and access the data for so long as required to comply with applicable laws.
  rights:
  - right: Review SPDI
    text: You may review the SPDI provided by You and any SPDI found to be inaccurate or deficient will be corrected or amended by Us, as feasible.
  - right: Withdraw consent
    text: 'withdraw Your consent provided to Us earlier, in writing to our email ID: support@paymate.co.in'
  - right: Opt out of promotional communications
    text: We provide all Users with the opportunity to opt-out of receiving non-essential (promotional, marketing-related) communications from us
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: PayMate shall not sell or rent a User's personal information to third parties for their marketing purposes without his explicit consent.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PayMate
provenance_date: '2026-11-10'
provider_name: PayMate
provider_slug: paymate
slug: paymate-privacy-policy
source_date: '2026-11-10'
source_filename: paymate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://paymate.in/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PayMate\naid: paymate\nurl: https://paymate.in/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, postal address, age, mobile/telephone phone number, email address, Aadhaar issued by Unique Identification\n    Authority of India and masked as per applicable laws, Permanent Account Number (‘PAN’) issued by the Income\n    Tax Department\n- category: financial\n  text: financial information like bank account details, shipping, billing or communication address of the customer\n- category: device\n  text: device ID for mapping\
  \ the application to the device on which it is registered\n- category: location\n  text: Geolocation Information\n- category: behavioral\n  text: analysis of the User behaviour on the Sites\n- category: communication\n  text: SMS for entering the activation code directly in the application during the activation\npurposes:\n- purpose: Payment aggregation, payouts and verification services\n  text: For providing payment aggregation, payouts and verification services to our merchants, business partners\n    and end-customers.\n- purpose: Compliance with screening requirements\n  text: to comply with screening requirements as per Applicable Laws.\n- purpose: Targeted advertisements\n  text: We may collect Your device information in order to gain insights about Your use of Our website or Services,\n    to provide a customized experience, and to show targeted advertisements.\n- purpose: Fraud detection\n  text: to detect and protect us against error, fraud and other criminal activity\nretention:\n\
  - scope: Account closed data\n  period: null\n  text: If your Account is closed, we may take steps to mask Data and other information, but PayMate reserves our\n    ability to retain and access the data for so long as required to comply with applicable laws.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Withdrawal of consent by email\n  text: 'You may choose not to provide Your SPDI, at any time while availing the Services or otherwise, or withdraw\n    Your consent provided to Us earlier, in writing to our email ID: support@paymate.co.in'\nrights:\n- right: Review SPDI\n  text: You may review the SPDI provided by You and any SPDI found to be inaccurate or deficient will be corrected\n    or amended by Us, as feasible.\n- right: Withdraw consent\n  text: 'withdraw Your consent provided to Us earlier, in writing to our email ID: support@paymate.co.in'\n- right: Opt out of promotional communications\n\
  \  text: We provide all Users with the opportunity to opt-out of receiving non-essential (promotional, marketing-related)\n    communications from us\nsale_or_sharing:\n  stance: conditional\n  text: PayMate shall not sell or rent a User's personal information to third parties for their marketing purposes\n    without his explicit consent.\n"
source_yaml_url: https://artifacts.apis.io/paymate/privacy/paymate-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from PayMate's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- B2B Payments
- Accounts Payable
- Accounts Receivable
- Supply Chain Finance
- Invoice Discounting
- Working Capital
- Commercial Cards
- Financial Services
- India
- Fintech
- Company
---
