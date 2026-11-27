---
api_specs:
- filename: payplug-cards-api-openapi.yml
  format: yaml
  label: PayPlug Cards API
  slug: payplug-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payplug/openapi/payplug-cards-api-openapi.yml
- filename: payplug-installment-plans-api-openapi.yml
  format: yaml
  label: PayPlug Installment Plans API
  slug: payplug-installment-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payplug/openapi/payplug-installment-plans-api-openapi.yml
- filename: payplug-payments-api-openapi.yml
  format: yaml
  label: PayPlug Payments API
  slug: payplug-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payplug/openapi/payplug-payments-api-openapi.yml
- filename: payplug-payplug-api-api-openapi.yml
  format: yaml
  label: PayPlug PayPlug API
  slug: payplug-payplug-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payplug/openapi/payplug-payplug-api-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Surname, first name, postal address, telephone number, email address, date of birth, nationality, bank details, proof of identity and/or address, commercial register number.
  - category: financial
    text: bank card data (PAN, CVV, expiry date), transaction date and time, transaction amount
  - category: location
    text: location data (postcode, IP country, card country)
  - category: device
    text: connection data (IP address)
  - category: behavioral
    text: IP address, language preferences and other data relating to the consultation of our sites, date and time of last connection, number of connections.
  deletion:
    route: Request by email or post to the data protection officer
    text: You can request the deletion of your personal data;
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Developing client base
    text: We may contact professionals who might be interested in our payment solution in order to present them with our services.
  - purpose: Anti-money laundering and terrorist financing
    text: As a payment institution, Payplug is required to implement measures to combat money laundering and the financing of terrorism
  - purpose: Fraud prevention
    text: we are required to implement processes to detect attempted fraud ( 3D Secure )
  - purpose: Recruitment management
    text: We collect and process the personal data of our candidates.
  - purpose: Website navigation and cookies
    text: Payplug may collect personal data via cookies in order to ensure the smooth operation of the site and to improve the user experience
  retention:
  - period: 5 years
    scope: Clients
    text: 5 years from the end of the business relationship with the client.
  - period: 3 years
    scope: Prospects
    text: 3 years from the date of collection of the prospect's information or the last contact from them.
  - period: 5 years
    scope: Fraud files
    text: 5 years from the closure of the fraud file, where applicable.
  - period: 2 years
    scope: Unsuccessful candidates
    text: 2 years after the last contact with an unsuccessful candidate.
  - period: 6 months
    scope: Cookies requiring consent
    text: 'Cookies requiring user consent: 6 months.'
  - period: 13 months
    scope: Audience measurement cookies
    text: 'Audience measurement cookies: 13 months.'
  - period: 3 years
    scope: Contact form data
    text: 'Personal data collected via the contact form: 3 years.'
  rights:
  - right: Access
    text: 'Access to your personal data: you can obtain information about the processing of your personal data and a copy of it.'
  - right: Rectification
    text: 'Rectify, update your personal data: if you consider that your personal data is inaccurate or incomplete'
  - right: Erasure
    text: 'Deletion: you can request the deletion of your personal data;'
  - right: Restriction
    text: Request a restriction on the processing of your personal data by us;
  - right: Portability
    text: Request portability of your personal data
  - right: Withdraw consent
    text: Withdraw your consent at any time for the processing of your personal data subject to your consent;
  - right: Objection
    text: To object to the processing of your personal data
  - right: Complaint
    text: To file a complaint with a control authority (in France, the CNIL (new tab) ).
  role:
    text: Payplug Enterprise SAS, acting as data controller, processes and protects your personal data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: adequacy decision or standard contractual data protection clauses adopted by the European Commission
  - mechanism: SCC
    text: adequacy decision or standard contractual data protection clauses adopted by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PayPlug
provenance_date: '2026-11-10'
provider_name: PayPlug
provider_slug: payplug
slug: payplug-privacy-policy
source_date: '2026-11-10'
source_filename: payplug-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.payplug.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PayPlug\naid: payplug\nurl: https://www.payplug.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Payplug Enterprise SAS, acting as data controller, processes and protects your personal data.\ndata_categories:\n- category: identifying\n  text: Surname, first name, postal address, telephone number, email address, date of birth, nationality, bank details,\n    proof of identity and/or address, commercial register number.\n- category: financial\n  text: bank card data (PAN, CVV, expiry date), transaction date and time, transaction amount\n- category: location\n  text: location\
  \ data (postcode, IP country, card country)\n- category: device\n  text: connection data (IP address)\n- category: behavioral\n  text: IP address, language preferences and other data relating to the consultation of our sites, date and time\n    of last connection, number of connections.\npurposes:\n- purpose: Developing client base\n  text: We may contact professionals who might be interested in our payment solution in order to present them with\n    our services.\n- purpose: Anti-money laundering and terrorist financing\n  text: As a payment institution, Payplug is required to implement measures to combat money laundering and the financing\n    of terrorism\n- purpose: Fraud prevention\n  text: we are required to implement processes to detect attempted fraud ( 3D Secure )\n- purpose: Recruitment management\n  text: We collect and process the personal data of our candidates.\n- purpose: Website navigation and cookies\n  text: Payplug may collect personal data via cookies in order to ensure\
  \ the smooth operation of the site and to\n    improve the user experience\nretention:\n- scope: Clients\n  period: 5 years\n  text: 5 years from the end of the business relationship with the client.\n- scope: Prospects\n  period: 3 years\n  text: 3 years from the date of collection of the prospect's information or the last contact from them.\n- scope: Fraud files\n  period: 5 years\n  text: 5 years from the closure of the fraud file, where applicable.\n- scope: Unsuccessful candidates\n  period: 2 years\n  text: 2 years after the last contact with an unsuccessful candidate.\n- scope: Cookies requiring consent\n  period: 6 months\n  text: 'Cookies requiring user consent: 6 months.'\n- scope: Audience measurement cookies\n  period: 13 months\n  text: 'Audience measurement cookies: 13 months.'\n- scope: Contact form data\n  period: 3 years\n  text: 'Personal data collected via the contact form: 3 years.'\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: adequacy decision or standard\
  \ contractual data protection clauses adopted by the European Commission\n- mechanism: SCC\n  text: adequacy decision or standard contractual data protection clauses adopted by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request by email or post to the data protection officer\n  text: You can request the deletion of your personal data;\nrights:\n- right: Access\n  text: 'Access to your personal data: you can obtain information about the processing of your personal data and\n    a copy of it.'\n- right: Rectification\n  text: 'Rectify, update your personal data: if you consider that your personal data is inaccurate or incomplete'\n- right: Erasure\n  text: 'Deletion: you can request the deletion of your personal data;'\n- right: Restriction\n  text: Request a restriction on the processing of your personal data by us;\n- right: Portability\n  text: Request portability of your personal data\n-\
  \ right: Withdraw consent\n  text: Withdraw your consent at any time for the processing of your personal data subject to your consent;\n- right: Objection\n  text: To object to the processing of your personal data\n- right: Complaint\n  text: To file a complaint with a control authority (in France, the CNIL (new tab) ).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payplug/privacy/payplug-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 29 quoted statements, read from PayPlug's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
