---
api_specs:
- filename: tsb-bank-atm-api-openapi.yml
  format: yaml
  label: TSB Bank ATM API
  slug: tsb-bank-atm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-atm-api-openapi.yml
- filename: tsb-bank-authorization-server-apis-api-openapi.yml
  format: yaml
  label: TSB Bank Authorization Server APIs API
  slug: tsb-bank-authorization-server-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-authorization-server-apis-api-openapi.yml
- filename: tsb-bank-bca-api-openapi.yml
  format: yaml
  label: TSB Bank BCA API
  slug: tsb-bank-bca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-bca-api-openapi.yml
- filename: tsb-bank-branch-api-openapi.yml
  format: yaml
  label: TSB Bank Branch API
  slug: tsb-bank-branch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-branch-api-openapi.yml
- filename: tsb-bank-ccc-api-openapi.yml
  format: yaml
  label: TSB Bank CCC API
  slug: tsb-bank-ccc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-ccc-api-openapi.yml
- filename: tsb-bank-pca-api-openapi.yml
  format: yaml
  label: TSB Bank PCA API
  slug: tsb-bank-pca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-pca-api-openapi.yml
- filename: tsb-bank-resource-server-apis-api-openapi.yml
  format: yaml
  label: TSB Bank Resource Server APIs API
  slug: tsb-bank-resource-server-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-resource-server-apis-api-openapi.yml
- filename: tsb-bank-sme-api-openapi.yml
  format: yaml
  label: TSB Bank SME API
  slug: tsb-bank-sme-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-sme-api-openapi.yml
- filename: tsb-bank-token-server-apis-api-openapi.yml
  format: yaml
  label: TSB Bank Token Server APIs API
  slug: tsb-bank-token-server-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tsb-bank/openapi/tsb-bank-token-server-apis-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Data confirming your identity.
  - category: contact
    text: Contact information we hold for you
  - category: financial
    text: Data relating to credit history and status of you or any associated person.
  - category: behavioral
    text: We monitor how you use the TSB App.
  - category: device
    text: We also collect information on all the other apps installed on your device
  - category: biometric
    text: We use biometric data analysis to combat fraudsters.
  - category: health
    text: such as details about your health or ethnicity
  - category: communication
    text: Phone call recordings
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing products and services
    text: providing you with products and services
  - purpose: Determine eligibility
    text: we’ll compare this against different metrics to determine whether you meet the eligibility criteria for an account.
  - purpose: Improve security and combat fraud
    text: We use biometric data analysis to combat fraudsters.
  - purpose: Using CCTV
    text: We use CCTV Systems (comprising static cameras and body worn video (BWV)) to record images to keep our customers, employees and property safe.
  - purpose: Direct marketing
    text: We’ll only send direct marketing to TSB customers in this way if you’ve consented to receive it.
  - purpose: Comply with legal obligations
    text: This might include providing information to HMRC, preventing fraud and money laundering and doing what our Regulators require.
  retention:
  - period: null
    scope: Special category and criminal offence information
    text: We only keep special category and criminal offence information for as long as we need it
  - period: null
    scope: CCTV
    text: Will only hold your information in this way for as long as is needed.
  rights:
  - right: access
    text: Yes, you have a right to request a copy of your personal data that we process.
  - right: object to processing (CCTV)
    text: You have the right to object to us processing your information in this way.
  - right: withdraw consent
    text: You can withdraw this consent at any time.
  - right: contest automated decision
    text: we’ll always allow you to contest the decision
  - right: opt out of marketing
    text: You have the right to opt out of this marketing at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TSB Bank
provenance_date: '2026-11-10'
provider_name: TSB Bank
provider_slug: tsb-bank
slug: tsb-bank-privacy-policy
source_date: '2026-11-10'
source_filename: tsb-bank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tsb.co.uk/help-and-support/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TSB Bank\naid: tsb-bank\nurl: https://www.tsb.co.uk/help-and-support/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Data confirming your identity.\n- category: contact\n  text: Contact information we hold for you\n- category: financial\n  text: Data relating to credit history and status of you or any associated person.\n- category: behavioral\n  text: We monitor how you use the TSB App.\n- category: device\n  text: We also collect information on all the other apps installed on your device\n- category: biometric\n\
  \  text: We use biometric data analysis to combat fraudsters.\n- category: health\n  text: such as details about your health or ethnicity\n- category: communication\n  text: Phone call recordings\npurposes:\n- purpose: Providing products and services\n  text: providing you with products and services\n- purpose: Determine eligibility\n  text: we’ll compare this against different metrics to determine whether you meet the eligibility criteria for\n    an account.\n- purpose: Improve security and combat fraud\n  text: We use biometric data analysis to combat fraudsters.\n- purpose: Using CCTV\n  text: We use CCTV Systems (comprising static cameras and body worn video (BWV)) to record images to keep our customers,\n    employees and property safe.\n- purpose: Direct marketing\n  text: We’ll only send direct marketing to TSB customers in this way if you’ve consented to receive it.\n- purpose: Comply with legal obligations\n  text: This might include providing information to HMRC, preventing\
  \ fraud and money laundering and doing what our\n    Regulators require.\nretention:\n- scope: Special category and criminal offence information\n  period: null\n  text: We only keep special category and criminal offence information for as long as we need it\n- scope: CCTV\n  period: null\n  text: Will only hold your information in this way for as long as is needed.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: Yes, you have a right to request a copy of your personal data that we process.\n- right: object to processing (CCTV)\n  text: You have the right to object to us processing your information in this way.\n- right: withdraw consent\n  text: You can withdraw this consent at any time.\n- right: contest automated decision\n  text: we’ll always allow you to contest the decision\n- right: opt out of marketing\n  text: You have the right\
  \ to opt out of this marketing at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tsb-bank/privacy/tsb-bank-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 21 quoted statements, read from TSB Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Payments
- Account Information
- FAPI
- Fintech
---
