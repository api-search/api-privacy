---
api_specs:
- filename: scratchpay-borrower-application-api-openapi.yml
  format: yaml
  label: Scratchpay Borrower application API
  slug: scratchpay-borrower-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scratchpay/openapi/scratchpay-borrower-application-api-openapi.yml
- filename: scratchpay-borrower-application-result-api-openapi.yml
  format: yaml
  label: Scratchpay Borrower application result API
  slug: scratchpay-borrower-application-result-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scratchpay/openapi/scratchpay-borrower-application-result-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name User name Phone number Date of birth Address Email address Social security number
  - category: financial
    text: We may also collect your income, bank account online login information, bank account numbers, bank account details including transaction history, routing numbers and/or debit card numbers and credit card numbers
  - category: location
    text: We may also collect your general geographic location based on IP address when you use the Services
  - category: behavioral
    text: In some cases, we may collect click or touch stream data, movement, scroll, keystroke activity and third-party sites or services you were using before and after interacting with the Services.
  - category: device
    text: device information including but not limited to identifier, name and type, operating system, location, mobile network information
  - category: professional
    text: We collect information about your current employer and your employment history.
  deletion:
    route: Request account closure by contacting us; CCPA-style access/deletion requests via form
    text: You can also request to close your account if you do not have an active loan by contacting us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services or complete a transaction
    text: Provide the Services or complete a transaction
  - purpose: Personalized advertising
    text: Allow us and our advertising partners to personalize content and advertising that you may see on the Services and on third-party platforms
  - purpose: Fraud prevention and security
    text: Prevent fraud, unauthorized access/use of the Services, breaches of terms and policies, or other wrongful behavior
  - purpose: Background and screening
    text: We use this information to conduct background and other screening activities, and to promote our services to others.
  retention:
  - period: null
    scope: General customer information
    text: We will retain your information for as long as necessary to provide the Services and for the other purposes set out in this Privacy Policy.
  - period: null
    scope: Closed accounts
    text: If you close your Scratch Financial account, we will mark your account in our database as "Closed," but will keep your account information in our database to comply with our legal obligations.
  rights:
  - right: access
    text: confirm whether or not we are processing your information and provide access to and/or a copy of certain information we hold about you
  - right: correction
    text: correct information which is incorrect
  - right: deletion
    text: delete certain information which we are holding about you
  - right: opt out of sales and targeted advertising
    text: You may also have the right to opt out of the “sales” of personal information and targeted advertising
  role:
    text: THIS POLICY DESCRIBES THE WAYS SCRATCH FINANCIAL, INC. AND ANY OF OUR AFFILIATES ("Company", "we", "us", "our") COLLECT, PROTECT, USE AND STORE YOUR PERSONAL INFORMATION.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We will not sell or share your mobile phone number or consent with third parties for their promotional or marketing purposes
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Scratchpay
provenance_date: '2026-11-10'
provider_name: Scratchpay
provider_slug: scratchpay
slug: scratchpay-privacy-policy
source_date: '2026-11-10'
source_filename: scratchpay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scratchpay.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Scratchpay\naid: scratchpay\nurl: https://scratchpay.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: THIS POLICY DESCRIBES THE WAYS SCRATCH FINANCIAL, INC. AND ANY OF OUR AFFILIATES (\"Company\", \"we\", \"us\",\n    \"our\") COLLECT, PROTECT, USE AND STORE YOUR PERSONAL INFORMATION.\ndata_categories:\n- category: identifying\n  text: Name User name Phone number Date of birth Address Email address Social security number\n- category: financial\n  text: We may also collect your income, bank account online login information, bank account numbers, bank account\n    details including\
  \ transaction history, routing numbers and/or debit card numbers and credit card numbers\n- category: location\n  text: We may also collect your general geographic location based on IP address when you use the Services\n- category: behavioral\n  text: In some cases, we may collect click or touch stream data, movement, scroll, keystroke activity and third-party\n    sites or services you were using before and after interacting with the Services.\n- category: device\n  text: device information including but not limited to identifier, name and type, operating system, location, mobile\n    network information\n- category: professional\n  text: We collect information about your current employer and your employment history.\npurposes:\n- purpose: Provide the Services or complete a transaction\n  text: Provide the Services or complete a transaction\n- purpose: Personalized advertising\n  text: Allow us and our advertising partners to personalize content and advertising that you may see on the\
  \ Services\n    and on third-party platforms\n- purpose: Fraud prevention and security\n  text: Prevent fraud, unauthorized access/use of the Services, breaches of terms and policies, or other wrongful\n    behavior\n- purpose: Background and screening\n  text: We use this information to conduct background and other screening activities, and to promote our services\n    to others.\nretention:\n- scope: General customer information\n  period: null\n  text: We will retain your information for as long as necessary to provide the Services and for the other purposes\n    set out in this Privacy Policy.\n- scope: Closed accounts\n  period: null\n  text: If you close your Scratch Financial account, we will mark your account in our database as \"Closed,\" but\n    will keep your account information in our database to comply with our legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ Request account closure by contacting us; CCPA-style access/deletion requests via form\n  text: You can also request to close your account if you do not have an active loan by contacting us at [email\n    protected] .\nrights:\n- right: access\n  text: confirm whether or not we are processing your information and provide access to and/or a copy of certain\n    information we hold about you\n- right: correction\n  text: correct information which is incorrect\n- right: deletion\n  text: delete certain information which we are holding about you\n- right: opt out of sales and targeted advertising\n  text: You may also have the right to opt out of the “sales” of personal information and targeted advertising\nsale_or_sharing:\n  stance: conditional\n  text: We will not sell or share your mobile phone number or consent with third parties for their promotional or\n    marketing purposes\n"
source_yaml_url: https://artifacts.apis.io/scratchpay/privacy/scratchpay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Scratchpay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financing
- Payments
- Lending
- Veterinary
- Healthcare
- Fintech
- Buy Now Pay Later
- Point-of-Sale
---
