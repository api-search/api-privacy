---
api_specs:
- filename: paytabs-payments-api-openapi.yml
  format: yaml
  label: PayTabs Payments API
  slug: paytabs-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paytabs/openapi/paytabs-payments-api-openapi.yml
- filename: paytabs-transactions-api-openapi.yml
  format: yaml
  label: PayTabs Transactions API
  slug: paytabs-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paytabs/openapi/paytabs-transactions-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: full name, email address, date of birth, home address, proof of address, phone number
  - category: financial
    text: Financial information which is provided by you and/or your customers while using payment gateway for payment processing.
  - category: financial
    text: credit card number, payment information, including credit card and bank account information
  - category: device
    text: IP address, browser type and version
  - category: behavioral
    text: Information collected by cookies and other tracking technologies while using PayTabs website.
  deletion:
    route: null
    text: 'Request to erase the Personal Information: you reserve the right to request to remove any personal information except personal information is required to comply with the applicable data protection laws and regulations'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process transactions and services
    text: to provide and deliver PayTabs services and process transactions related to PayTabs services, products
  - purpose: marketing
    text: 'For marketing purposes: we may use your personal information if you have “Opt in” for promotional activities'
  - purpose: fraud prevention
    text: To identify and reduce fraudulent activity
  - purpose: legal compliance
    text: 'To comply with the law: we may use your information when it is required to comply with legal obligations'
  retention:
  - period: null
    scope: personal information
    text: PayTabs securely retains personal information in an identifiable format for the duration required by applicable laws.
  - period: null
    scope: after account closure
    text: we may need to keep certain information for an additional period of time for legal and legitimate business purposes.
  rights:
  - right: erasure
    text: Request to erase the Personal Information
  - right: portability
    text: 'Request for personal information transfer: you have the right to request to export your information to a third-party where technically and legally feasible.'
  - right: correction
    text: 'Request correction: you reserve the right to request to correct any information held by us'
  - right: access
    text: 'Right to access your personal information: you have the right to receive a copy of your personal information that we hold'
  - right: object to direct marketing
    text: 'Right to object to direct marketing: you have the right to object processing of your personal information for direct marketing purposes.'
  - right: withdraw consent
    text: 'Right to withdraw consent: where we rely on your consent to process personal data, you may withdraw it at any time'
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
    text: PayTabs applies appropriate safeguards in accordance with applicable data protection laws, including the use of EU Standard Contractual Clauses (SCCs) or equivalent mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PayTabs
provenance_date: '2026-11-10'
provider_name: PayTabs
provider_slug: paytabs
slug: paytabs-privacy-policy
source_date: '2026-11-10'
source_filename: paytabs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ai.paytabs.com/en/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PayTabs\naid: paytabs\nurl: https://ai.paytabs.com/en/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: full name, email address, date of birth, home address, proof of address, phone number\n- category: financial\n  text: Financial information which is provided by you and/or your customers while using payment gateway for payment\n    processing.\n- category: financial\n  text: credit card number, payment information, including credit card and bank account information\n- category: device\n  text: IP address, browser type and\
  \ version\n- category: behavioral\n  text: Information collected by cookies and other tracking technologies while using PayTabs website.\npurposes:\n- purpose: process transactions and services\n  text: to provide and deliver PayTabs services and process transactions related to PayTabs services, products\n- purpose: marketing\n  text: 'For marketing purposes: we may use your personal information if you have “Opt in” for promotional activities'\n- purpose: fraud prevention\n  text: To identify and reduce fraudulent activity\n- purpose: legal compliance\n  text: 'To comply with the law: we may use your information when it is required to comply with legal obligations'\nretention:\n- scope: personal information\n  period: null\n  text: PayTabs securely retains personal information in an identifiable format for the duration required by applicable\n    laws.\n- scope: after account closure\n  period: null\n  text: we may need to keep certain information for an additional period of time for legal\
  \ and legitimate business\n    purposes.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: PayTabs applies appropriate safeguards in accordance with applicable data protection laws, including the\n    use of EU Standard Contractual Clauses (SCCs) or equivalent mechanisms\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: 'Request to erase the Personal Information: you reserve the right to request to remove any personal information\n    except personal information is required to comply with the applicable data protection laws and regulations'\nrights:\n- right: erasure\n  text: Request to erase the Personal Information\n- right: portability\n  text: 'Request for personal information transfer: you have the right to request to export your information to\n    a third-party where technically and legally feasible.'\n- right: correction\n  text: 'Request correction: you reserve the right to request to correct any\
  \ information held by us'\n- right: access\n  text: 'Right to access your personal information: you have the right to receive a copy of your personal information\n    that we hold'\n- right: object to direct marketing\n  text: 'Right to object to direct marketing: you have the right to object processing of your personal information\n    for direct marketing purposes.'\n- right: withdraw consent\n  text: 'Right to withdraw consent: where we rely on your consent to process personal data, you may withdraw it\n    at any time'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paytabs/privacy/paytabs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 19 quoted statements, read from PayTabs's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- MENA
- Saudi Arabia
- Cards
- mada
---
