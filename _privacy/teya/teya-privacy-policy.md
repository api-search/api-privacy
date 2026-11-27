---
api_specs:
- filename: teya-captures-api-openapi.yml
  format: yaml
  label: Teya Captures API
  slug: teya-captures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-captures-api-openapi.yml
- filename: teya-dcc-api-openapi.yml
  format: yaml
  label: Teya DCC API
  slug: teya-dcc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-dcc-api-openapi.yml
- filename: teya-epos-registration-api-openapi.yml
  format: yaml
  label: Teya ePOS Registration API
  slug: teya-epos-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-epos-registration-api-openapi.yml
- filename: teya-hosted-checkout-api-openapi.yml
  format: yaml
  label: Teya Hosted Checkout API
  slug: teya-hosted-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-hosted-checkout-api-openapi.yml
- filename: teya-internal-api-openapi.yml
  format: yaml
  label: Teya '@internal' API
  slug: teya-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-internal-api-openapi.yml
- filename: teya-pay-at-table-api-openapi.yml
  format: yaml
  label: Teya Pay at Table API
  slug: teya-pay-at-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-pay-at-table-api-openapi.yml
- filename: teya-payment-requests-api-openapi.yml
  format: yaml
  label: Teya Payment Requests API
  slug: teya-payment-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-payment-requests-api-openapi.yml
- filename: teya-print-receipts-epos-api-openapi.yml
  format: yaml
  label: Teya Print Receipts (ePOS) API
  slug: teya-print-receipts-epos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-print-receipts-epos-api-openapi.yml
- filename: teya-public-api-openapi.yml
  format: yaml
  label: Teya '@public' API
  slug: teya-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-public-api-openapi.yml
- filename: teya-refunds-api-openapi.yml
  format: yaml
  label: Teya Refunds API
  slug: teya-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-refunds-api-openapi.yml
- filename: teya-stores-api-openapi.yml
  format: yaml
  label: Teya Stores API
  slug: teya-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-stores-api-openapi.yml
- filename: teya-terminals-api-openapi.yml
  format: yaml
  label: Teya Terminals API
  slug: teya-terminals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-terminals-api-openapi.yml
- filename: teya-tokens-api-openapi.yml
  format: yaml
  label: Teya Tokens API
  slug: teya-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-tokens-api-openapi.yml
- filename: teya-transactions-api-openapi.yml
  format: yaml
  label: Teya Transactions API
  slug: teya-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-transactions-api-openapi.yml
- filename: teya-pay-by-link-api-openapi.yml
  format: yaml
  label: Teya Pay by Link API
  slug: teya-pay-by-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-pay-by-link-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: biometric
    text: '" Biometric Data " includes your image in photo or video form, likeness data, facial scan data and voice data.'
  deletion:
    route: contact form
    text: Request erasure of your personal data. This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and manage account
    text: To register you as a new customer.
  - purpose: Fraud and crime prevention
    text: To investigate, detect and prevent fraud or crime.
  - purpose: Marketing
    text: To make suggestions and recommendations to you about Services that may be of interest to you.
  retention:
  - period: null
    scope: personal data
    text: We will only retain your personal data for as long as necessary to fulfil the purposes we collected it for, including the purpose of satisfying any legal, accounting, or reporting requirements.
  rights:
  - right: access
    text: Request access to your personal data (commonly known as a “ data subject access request ”).
  - right: correction
    text: Request correction of the personal data that we hold about you.
  - right: erasure
    text: Request erasure of your personal data.
  - right: objection
    text: Object to processing of your personal data where we are relying on a legitimate interest (or those of a third party).
  - right: portability
    text: Request the transfer of your personal data to a third party.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: such as the Standard Contractual Clauses approved by the EU Commission or issued by the UK Information Commissioner’s Office
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Teya
provenance_date: '2026-11-10'
provider_name: Teya
provider_slug: teya
slug: teya-privacy-policy
source_date: '2026-11-10'
source_filename: teya-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.teya.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Teya\naid: teya\nurl: https://www.teya.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: biometric\n  text: '\" Biometric Data \" includes your image in photo or video form, likeness data, facial scan data and voice\n    data.'\npurposes:\n- purpose: Provide services and manage account\n  text: To register you as a new customer.\n- purpose: Fraud and crime prevention\n  text: To investigate, detect and prevent fraud or crime.\n- purpose: Marketing\n  text: To make suggestions and recommendations to you about Services that may be of interest\
  \ to you.\nretention:\n- scope: personal data\n  period: null\n  text: We will only retain your personal data for as long as necessary to fulfil the purposes we collected it for,\n    including the purpose of satisfying any legal, accounting, or reporting requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: such as the Standard Contractual Clauses approved by the EU Commission or issued by the UK Information Commissioner’s\n    Office\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact form\n  text: Request erasure of your personal data. This enables you to ask us to delete or remove personal data where\n    there is no good reason for us continuing to process it.\nrights:\n- right: access\n  text: Request access to your personal data (commonly known as a “ data subject access request ”).\n- right: correction\n  text: Request correction of the personal data that we hold about you.\n- right: erasure\n\
  \  text: Request erasure of your personal data.\n- right: objection\n  text: Object to processing of your personal data where we are relying on a legitimate interest (or those of a\n    third party).\n- right: portability\n  text: Request the transfer of your personal data to a third party.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/teya/privacy/teya-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 12 quoted statements, read from Teya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payment Processing
- Card Acquiring
- Online Payments
- Point-of-Sale
- E-Commerce
- Fintech
- Merchant Services
- Europe
- Card Machines
- Business Accounts
---
