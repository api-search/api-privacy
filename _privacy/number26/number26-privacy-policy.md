---
api_specs:
- filename: number26-default-api-openapi.yml
  format: yaml
  label: Number26 Default API
  slug: number26-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/number26/openapi/number26-default-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name and surname
  - category: contact
    text: Mobile telephone number
  - category: financial
    text: Data concerning your economic situation and your N26 products and services usage history which are your IBAN
  - category: location
    text: we will need access to your geolocation from your mobile device
  - category: behavioral
    text: we analyze your user behavior
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fraud prevention
    text: Fraud prevention, based on the legitimate interest of N26 not to contract or provide services to any potential customer related to fraud
  retention:
  - period: 5 years
    scope: Wise transfer data
    text: Wise will retain your data for 5 years after the date of the respective transfer
  rights:
  - right: withdraw consent
    text: Your consent is revocable at any time
  - right: object
    text: You can object to the processing of your personal data to receive informational emails
  role:
    text: 'The responsible entity for the collection, processing and use of your personal data is:'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Our list of processors includes pure data processors, meaning technical service providers
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Number26
provenance_date: '2026-11-10'
provider_name: Number26
provider_slug: number26
slug: number26-privacy-policy
source_date: '2026-11-10'
source_filename: number26-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.n26.com/legal/06+EU/03+Privacy%20Policy/en/01privacy-policy-en.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Number26\naid: number26\nurl: https://docs.n26.com/legal/06+EU/03+Privacy%20Policy/en/01privacy-policy-en.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'The responsible entity for the collection, processing and use of your personal data is:'\ndata_categories:\n- category: identifying\n  text: First name and surname\n- category: contact\n  text: Mobile telephone number\n- category: financial\n  text: Data concerning your economic situation and your N26 products and services usage history which are your\n    IBAN\n- category: location\n  text: we will need access to your\
  \ geolocation from your mobile device\n- category: behavioral\n  text: we analyze your user behavior\npurposes:\n- purpose: Fraud prevention\n  text: Fraud prevention, based on the legitimate interest of N26 not to contract or provide services to any potential\n    customer related to fraud\nretention:\n- scope: Wise transfer data\n  period: 5 years\n  text: Wise will retain your data for 5 years after the date of the respective transfer\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Our list of processors includes pure data processors, meaning technical service providers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: withdraw consent\n  text: Your consent is revocable at any time\n- right: object\n  text: You can object to the processing of your personal data to receive informational emails\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/number26/privacy/number26-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- rights
summary_line: 11 quoted statements, read from Number26's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Neobank
- Mobile Banking
- Payments
- Europe
- Germany
---
