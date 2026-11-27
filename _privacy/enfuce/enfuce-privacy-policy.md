---
api_specs:
- filename: enfuce-authorisation-request-api-api-openapi.yml
  format: yaml
  label: Enfuce Authorisation Request API
  slug: enfuce-authorisation-request-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-authorisation-request-api-api-openapi.yml
- filename: enfuce-create-card-api-openapi.yml
  format: yaml
  label: Enfuce Create Card API
  slug: enfuce-create-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-create-card-api-openapi.yml
- filename: enfuce-create-pin-control-access-token-api-openapi.yml
  format: yaml
  label: Enfuce Create PIN Control access token API
  slug: enfuce-create-pin-control-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-create-pin-control-access-token-api-openapi.yml
- filename: enfuce-get-card-api-openapi.yml
  format: yaml
  label: Enfuce Get card API
  slug: enfuce-get-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-get-card-api-openapi.yml
- filename: enfuce-get-card-payment-info-api-openapi.yml
  format: yaml
  label: Enfuce Get Card Payment Info API
  slug: enfuce-get-card-payment-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-get-card-payment-info-api-openapi.yml
- filename: enfuce-get-plastic-manufacturing-history-api-openapi.yml
  format: yaml
  label: Enfuce Get plastic manufacturing history API
  slug: enfuce-get-plastic-manufacturing-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-get-plastic-manufacturing-history-api-openapi.yml
- filename: enfuce-update-card-api-openapi.yml
  format: yaml
  label: Enfuce Update card API
  slug: enfuce-update-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enfuce/openapi/enfuce-update-card-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact data : first and last name, email address, phone number, physical address'
  - category: identifying
    text: 'Identification data : full name, physical address, phone number, email address, personal ID number, date of birth, nationality, national identification / social security number (SSN), signature, photo'
  - category: financial
    text: 'Payment transaction data : date, amount, currency, name of the merchant, creditor or supplier, transaction location'
  - category: financial
    text: 'Payment card data : card number (PAN), card name, expiry date, CVV code, card PIN block, service code'
  - category: device
    text: 'Technical data : such as data on system logs, IP address, device information, cryptographic data'
  - category: behavioral
    text: 'Web analytics data : data related to e.g. page visits, time spent on pages, links clicked, accessed content, device used'
  - category: professional
    text: 'Recruitment and qualification data : information related to your education, previous work experience, certifications, training records'
  deletion:
    route: Contact privacy(at)enfuce.com to exercise rights
    text: We will delete your personal data unless we have a legal obligation or other overriding reason to retain your data.
  dpa:
    available: null
    text: Such processing is always regulated by data processing agreements in order to ensure that all our service providers keep your personal data safe
    url: null
  purposes:
  - purpose: Provide and manage card services and payment transactions
    text: Processing your payment transactions, including authorization, clearing and settlement
  - purpose: Anti-money laundering and terrorism financing compliance
    text: Prevent, reveal and/or resolve issues related to money laundering and terrorism financing
  - purpose: Recruitment
    text: Recruitment, including screening, evaluating, interviewing and selecting potential employee candidates
  - purpose: Security of systems
    text: Ensuring and developing security of our systems with technical means, such as with data encryption, access controls, log management and auditing
  residency:
  - region: EEA
    text: We store your personal data in servers located in the European Economic Area (EEA), but we may use service providers that are based elsewhere in limited occasions.
  retention:
  - period: Six years
    scope: Cardholder identification and identity verification
    text: Six years after the end of the customer relationship, based on anti-money laundering legislation
  - period: Six years
    scope: Payment transaction-related data
    text: Six years after the end of the customer relationship or after an occasional transaction, based on anti-money laundering legislation
  - period: 18 months
    scope: Data used for recruitment purposes
    text: 18 months, unless you request a deletion or to store it for longer
  - period: up to five years
    scope: Whistleblowing-related data
    text: Generally, personal data is retained up to five years, unless obligatory to be stored for longer
  rights:
  - right: Access
    text: 'Right of access: You have the right to know whether we process your personal data and to know what personal data about you we process.'
  - right: Rectification
    text: 'Right to rectification: You have the right to correct and update your personal data'
  - right: Erasure
    text: 'Right to erasure (“Right to be forgotten”): You have the right to request us to delete your personal data.'
  - right: Restriction
    text: 'Right to restriction of processing: You can, under certain limited circumstances, ask us to restrict how we use your personal data'
  - right: Objection
    text: 'Right to objection: You can object to us processing your personal data'
  - right: Portability
    text: 'Right to data portability: You can ask us to send you or another organisation an electronic copy of your personal data'
  - right: Complaint
    text: you always have the right to complain to a data protection supervisory authority
  role:
    text: Enfuce is the data controller of your personal data as described in this notice
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Enfuce does not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: European Commission’s Standard Contractual Clauses for international transfers of personal data
  - mechanism: adequacy
    text: adequacy decisions adopted by the European Commission concerning a specific country
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Enfuce
provenance_date: '2026-11-09'
provider_name: Enfuce
provider_slug: enfuce
slug: enfuce-privacy-policy
source_date: '2026-11-09'
source_filename: enfuce-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://enfuce.com/privacy-and-data-protection
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Enfuce\naid: enfuce\nurl: https://enfuce.com/privacy-and-data-protection\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Enfuce is the data controller of your personal data as described in this notice\ndata_categories:\n- category: contact\n  text: 'Contact data : first and last name, email address, phone number, physical address'\n- category: identifying\n  text: 'Identification data : full name, physical address, phone number, email address, personal ID number, date\n    of birth, nationality, national identification / social security number (SSN), signature, photo'\n- category: financial\n\
  \  text: 'Payment transaction data : date, amount, currency, name of the merchant, creditor or supplier, transaction\n    location'\n- category: financial\n  text: 'Payment card data : card number (PAN), card name, expiry date, CVV code, card PIN block, service code'\n- category: device\n  text: 'Technical data : such as data on system logs, IP address, device information, cryptographic data'\n- category: behavioral\n  text: 'Web analytics data : data related to e.g. page visits, time spent on pages, links clicked, accessed content,\n    device used'\n- category: professional\n  text: 'Recruitment and qualification data : information related to your education, previous work experience, certifications,\n    training records'\npurposes:\n- purpose: Provide and manage card services and payment transactions\n  text: Processing your payment transactions, including authorization, clearing and settlement\n- purpose: Anti-money laundering and terrorism financing compliance\n  text: Prevent, reveal\
  \ and/or resolve issues related to money laundering and terrorism financing\n- purpose: Recruitment\n  text: Recruitment, including screening, evaluating, interviewing and selecting potential employee candidates\n- purpose: Security of systems\n  text: Ensuring and developing security of our systems with technical means, such as with data encryption, access\n    controls, log management and auditing\nretention:\n- scope: Cardholder identification and identity verification\n  period: Six years\n  text: Six years after the end of the customer relationship, based on anti-money laundering legislation\n- scope: Payment transaction-related data\n  period: Six years\n  text: Six years after the end of the customer relationship or after an occasional transaction, based on anti-money\n    laundering legislation\n- scope: Data used for recruitment purposes\n  period: 18 months\n  text: 18 months, unless you request a deletion or to store it for longer\n- scope: Whistleblowing-related data\n  period:\
  \ up to five years\n  text: Generally, personal data is retained up to five years, unless obligatory to be stored for longer\nresidency:\n- region: EEA\n  text: We store your personal data in servers located in the European Economic Area (EEA), but we may use service\n    providers that are based elsewhere in limited occasions.\ntransfers:\n- mechanism: SCC\n  text: European Commission’s Standard Contractual Clauses for international transfers of personal data\n- mechanism: adequacy\n  text: adequacy decisions adopted by the European Commission concerning a specific country\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Such processing is always regulated by data processing agreements in order to ensure that all our service\n    providers keep your personal data safe\ndeletion:\n  route: Contact privacy(at)enfuce.com to exercise rights\n  text: We will delete your personal data unless we have a legal obligation or other overriding reason to retain\n\
  \    your data.\nrights:\n- right: Access\n  text: 'Right of access: You have the right to know whether we process your personal data and to know what personal\n    data about you we process.'\n- right: Rectification\n  text: 'Right to rectification: You have the right to correct and update your personal data'\n- right: Erasure\n  text: 'Right to erasure (“Right to be forgotten”): You have the right to request us to delete your personal data.'\n- right: Restriction\n  text: 'Right to restriction of processing: You can, under certain limited circumstances, ask us to restrict how\n    we use your personal data'\n- right: Objection\n  text: 'Right to objection: You can object to us processing your personal data'\n- right: Portability\n  text: 'Right to data portability: You can ask us to send you or another organisation an electronic copy of your\n    personal data'\n- right: Complaint\n  text: you always have the right to complain to a data protection supervisory authority\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: Enfuce does not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/enfuce/privacy/enfuce-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Enfuce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Card Issuing
- Fintech
- API Platform
- A2A
---
