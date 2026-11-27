---
api_specs:
- filename: outpost-ai-oauth-api-openapi.yml
  format: yaml
  label: Outpost OAuth API
  slug: outpost-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outpost-ai/openapi/outpost-ai-oauth-api-openapi.yml
- filename: outpost-ai-payments-api-openapi.yml
  format: yaml
  label: Outpost Payments API
  slug: outpost-ai-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outpost-ai/openapi/outpost-ai-payments-api-openapi.yml
- filename: outpost-ai-webhooks-api-openapi.yml
  format: yaml
  label: Outpost Webhooks API
  slug: outpost-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outpost-ai/openapi/outpost-ai-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Personal details: name; date of birth/age.'
  - category: contact
    text: 'Contact details: correspondence address; telephone number; email address; details of your public social media profile(s).'
  - category: financial
    text: 'Payment details: invoice records; payment records; billing address; payment method; cardholder name; payment amount; payment date; transaction identifiers.'
  - category: location
    text: 'Location data: geographic location (inferred from IP address).'
  - category: device
    text: 'Data relating to our Sites: device type; operating system; browser type and version; IP address; internet service provider; pages accessed; dates and times of Site access; referring URLs.'
  - category: demographic
    text: 'Demographic information: gender; nationality; country of residence.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision of Sites, products, and services
    text: Providing our Sites, products, or services; acting as Merchant of Record; processing transactions and issuing invoices
  - purpose: Compliance checks
    text: Fulfilling our regulatory compliance obligations as Merchant of Record
  - purpose: Fraud prevention
    text: Detecting, preventing and investigating fraud and other criminal activity; verifying identity; screening transactions.
  - purpose: Legal compliance
    text: Compliance with our legal and regulatory obligations under applicable law, including tax law, financial regulations, anti-money laundering law, and payment industry standards
  retention:
  - period: 5–10 years
    scope: Transaction records
    text: transaction records are retained for 5–10 years depending on the jurisdiction
  rights:
  - right: Access
    text: 'Right of access: the right to request access to, or copies of, your Personal Data'
  - right: Rectification
    text: 'Right to rectification: the right to request rectification of any inaccuracies in your Personal Data'
  - right: Erasure or restriction
    text: 'Right to erasure or restriction: the right to request, on legitimate grounds, erasure of your Personal Data or restriction of Processing of your Personal Data'
  - right: Objection
    text: 'Right to object: the right to object, on legitimate grounds, to the Processing of your Personal Data by us'
  - right: Portability
    text: 'Right to data portability: the right to have certain Personal Data transferred to another Controller, in a structured, commonly used and machine-readable format'
  - right: Withdraw consent
    text: 'Right to withdraw consent: where we Process your Personal Data on the basis of your consent, the right to withdraw that consent'
  - right: Complaint
    text: 'Right to lodge complaints: the right to lodge complaints regarding the Processing of your Personal Data with a Data Protection Authority.'
  role:
    text: which acts as Controller
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or otherwise disclose Personal Data for monetary or other valuable consideration.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where we transfer your Personal Data from the UK/EEA to recipients located outside the UK/EEA who are not in an Adequate Jurisdiction, we do so on the basis of Standard Contractual Clauses approved by the European Commission and/or the UK Information Commissioner’s Office (as applicable).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Outpost
provenance_date: '2026-11-10'
provider_name: Outpost
provider_slug: outpost-ai
slug: outpost-ai-privacy-policy
source_date: '2026-11-10'
source_filename: outpost-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://outpost.ai/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Outpost\naid: outpost-ai\nurl: https://outpost.ai/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: which acts as Controller\ndata_categories:\n- category: identifying\n  text: 'Personal details: name; date of birth/age.'\n- category: contact\n  text: 'Contact details: correspondence address; telephone number; email address; details of your public social\n    media profile(s).'\n- category: financial\n  text: 'Payment details: invoice records; payment records; billing address; payment method; cardholder name; payment\n    amount; payment date; transaction identifiers.'\n- category:\
  \ location\n  text: 'Location data: geographic location (inferred from IP address).'\n- category: device\n  text: 'Data relating to our Sites: device type; operating system; browser type and version; IP address; internet\n    service provider; pages accessed; dates and times of Site access; referring URLs.'\n- category: demographic\n  text: 'Demographic information: gender; nationality; country of residence.'\npurposes:\n- purpose: Provision of Sites, products, and services\n  text: Providing our Sites, products, or services; acting as Merchant of Record; processing transactions and issuing\n    invoices\n- purpose: Compliance checks\n  text: Fulfilling our regulatory compliance obligations as Merchant of Record\n- purpose: Fraud prevention\n  text: Detecting, preventing and investigating fraud and other criminal activity; verifying identity; screening\n    transactions.\n- purpose: Legal compliance\n  text: Compliance with our legal and regulatory obligations under applicable law, including\
  \ tax law, financial\n    regulations, anti-money laundering law, and payment industry standards\nretention:\n- scope: Transaction records\n  period: 5–10 years\n  text: transaction records are retained for 5–10 years depending on the jurisdiction\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where we transfer your Personal Data from the UK/EEA to recipients located outside the UK/EEA who are not\n    in an Adequate Jurisdiction, we do so on the basis of Standard Contractual Clauses approved by the European\n    Commission and/or the UK Information Commissioner’s Office (as applicable).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: 'Right of access: the right to request access to, or copies of, your Personal Data'\n- right: Rectification\n  text: 'Right to rectification: the right to request rectification of any inaccuracies in your Personal Data'\n- right:\
  \ Erasure or restriction\n  text: 'Right to erasure or restriction: the right to request, on legitimate grounds, erasure of your Personal\n    Data or restriction of Processing of your Personal Data'\n- right: Objection\n  text: 'Right to object: the right to object, on legitimate grounds, to the Processing of your Personal Data by\n    us'\n- right: Portability\n  text: 'Right to data portability: the right to have certain Personal Data transferred to another Controller, in\n    a structured, commonly used and machine-readable format'\n- right: Withdraw consent\n  text: 'Right to withdraw consent: where we Process your Personal Data on the basis of your consent, the right\n    to withdraw that consent'\n- right: Complaint\n  text: 'Right to lodge complaints: the right to lodge complaints regarding the Processing of your Personal Data\n    with a Data Protection Authority.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or otherwise disclose Personal Data for monetary\
  \ or other valuable consideration.\n"
source_yaml_url: https://artifacts.apis.io/outpost-ai/privacy/outpost-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Outpost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Tax
- Commerce
- Software-as-a-Service
---
