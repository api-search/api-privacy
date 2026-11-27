---
api_specs:
- filename: gov-uk-pay-agreements-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Agreements API
  slug: gov-uk-pay-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-agreements-api-openapi.yml
- filename: gov-uk-pay-authorise-card-payments-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Authorise card payments API
  slug: gov-uk-pay-authorise-card-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-authorise-card-payments-api-openapi.yml
- filename: gov-uk-pay-card-payments-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Card payments API
  slug: gov-uk-pay-card-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-card-payments-api-openapi.yml
- filename: gov-uk-pay-disputes-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Disputes API
  slug: gov-uk-pay-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-disputes-api-openapi.yml
- filename: gov-uk-pay-refunding-card-payments-api-openapi.yml
  format: yaml
  label: GOV.UK Pay Refunding card payments API
  slug: gov-uk-pay-refunding-card-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gov-uk-pay/openapi/gov-uk-pay-refunding-card-payments-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: 'We will collect personal data that includes your: names email addresses billing addresses'
  - category: financial
    text: credit or debit card number - we will only keep the first 6 and last 4 digits for our records once the payment is made
  - category: financial
    text: payment amounts and frequencies including dates payment statuses payment descriptions
  - category: device
    text: IP address of devices used to make payments
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Taking payments
    text: We use your data to process the payment you have requested.
  - purpose: Fraud monitoring
    text: to monitor our service to protect against fraud and errors
  - purpose: Public sector payment management
    text: The public sector organisation who requested your payment will have access to information about these payments through GOV.UK Pay.
  - purpose: Legal obligations
    text: 'legal obligation: we process personal data where this is necessary to meet legal, financial, audit, fraud prevention or reporting duties'
  retention:
  - period: null
    scope: Personal data
    text: we will only hold your personal data for a minimum of 1 year and a maximum of 7 years
  - period: null
    scope: Security code
    text: credit or debit card security code - this is not kept after the payment is processed
  rights:
  - right: access
    text: information about how your personal data is processed a copy of that personal data
  - right: rectification
    text: anything inaccurate in your personal data is corrected immediately
  - right: objection
    text: raise an objection about how your personal data is processed
  - right: erasure
    text: request that your personal data is erased if there is no longer a justification for it
  - right: restriction
    text: ask that the processing of your personal data is restricted in certain circumstances
  role:
    text: acting as a data processor on behalf of these organisations. The organisations using GOV.UK Pay are the data controllers
    value: both
  sale_or_sharing:
    stance: prohibited
    text: 'We will not: sell or rent your data to third parties share your data with third parties for marketing purposes'
  subprocessors:
    text: We use payment providers to process your payment.
    url: null
  transfers:
  - mechanism: other
    text: Your personal data may, throughout the course of its processing at GDS, be transferred outside the UK. Where this is the case all appropriate technical and legal safeguards will be put in place
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GOV.UK Pay
provenance_date: '2026-11-09'
provider_name: GOV.UK Pay
provider_slug: gov-uk-pay
slug: gov-uk-pay-privacy-policy
source_date: '2026-11-09'
source_filename: gov-uk-pay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.payments.service.gov.uk/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GOV.UK Pay\naid: gov-uk-pay\nurl: https://www.payments.service.gov.uk/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: acting as a data processor on behalf of these organisations. The organisations using GOV.UK Pay are the\n    data controllers\ndata_categories:\n- category: contact\n  text: 'We will collect personal data that includes your: names email addresses billing addresses'\n- category: financial\n  text: credit or debit card number - we will only keep the first 6 and last 4 digits for our records once the payment\n    is made\n- category: financial\n  text: payment amounts and frequencies\
  \ including dates payment statuses payment descriptions\n- category: device\n  text: IP address of devices used to make payments\npurposes:\n- purpose: Taking payments\n  text: We use your data to process the payment you have requested.\n- purpose: Fraud monitoring\n  text: to monitor our service to protect against fraud and errors\n- purpose: Public sector payment management\n  text: The public sector organisation who requested your payment will have access to information about these payments\n    through GOV.UK Pay.\n- purpose: Legal obligations\n  text: 'legal obligation: we process personal data where this is necessary to meet legal, financial, audit, fraud\n    prevention or reporting duties'\nretention:\n- scope: Personal data\n  period: null\n  text: we will only hold your personal data for a minimum of 1 year and a maximum of 7 years\n- scope: Security code\n  period: null\n  text: credit or debit card security code - this is not kept after the payment is processed\nresidency:\
  \ []\ntransfers:\n- mechanism: other\n  text: Your personal data may, throughout the course of its processing at GDS, be transferred outside the UK. Where\n    this is the case all appropriate technical and legal safeguards will be put in place\nsubprocessors:\n  url: null\n  text: We use payment providers to process your payment.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: information about how your personal data is processed a copy of that personal data\n- right: rectification\n  text: anything inaccurate in your personal data is corrected immediately\n- right: objection\n  text: raise an objection about how your personal data is processed\n- right: erasure\n  text: request that your personal data is erased if there is no longer a justification for it\n- right: restriction\n  text: ask that the processing of your personal data is restricted in certain circumstances\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: 'We will not: sell or rent your data to third parties share your data with third parties for marketing purposes'\n"
source_yaml_url: https://artifacts.apis.io/gov-uk-pay/privacy/gov-uk-pay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from GOV.UK Pay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Government
- United Kingdom
- Public Sector
- REST
- PCI DSS
- Refunds
- Recurring Payments
- Webhook
---
