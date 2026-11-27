---
api_specs:
- filename: envoisms-ma-api-openapi.json
  format: json
  label: EnvoiSMS API API
  slug: envoisms-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/envoisms-ma/openapi/_original/envoisms-ma-api-openapi.json
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Last name, first name, business email, company, telephone
  - category: financial
    text: Payment method (processed by Stripe, never stored by us), billing address, purchase history
  - category: communication
    text: Recipient telephone numbers, content of messages sent, send logs, delivery statuses (DLR)
  - category: device
    text: IP address, browser type, pages visited, cookies
  - category: communication
    text: Exchanges with support, tickets, call recordings where applicable
  deletion:
    route: Deletion or anonymisation after account closure
    text: Deletion or anonymisation within 30 days, unless a legal obligation requires longer retention
  dpa:
    available: true
    text: View official DPA
    url: https://envoisms.ma/en/legal/dpa/
  purposes:
  - purpose: Provide, operate and secure the Service
    text: Provide, operate and secure the Service (message sending, API, dashboard)
  - purpose: Billing and account management
    text: Bill and manage your customer account
  - purpose: Technical and commercial support
    text: Provide technical and commercial support
  - purpose: Legal and regulatory compliance
    text: Comply with our legal and regulatory obligations (accounting, anti-fraud, judicial requisitions)
  - purpose: Service improvement and measurement
    text: Improve our Services and measure their performance (aggregated and anonymised statistics)
  retention:
  - period: For the entire duration of the contractual relationship
    scope: Active account data
    text: Active account data For the entire duration of the contractual relationship
  - period: 12 months
    scope: SMS/WhatsApp send logs
    text: SMS/WhatsApp send logs (content, DLR) 12 months, for delivery-proof and support purposes
  - period: 10 years
    scope: Billing data
    text: Billing data 10 years (accounting obligations)
  - period: 30 days
    scope: Data after account closure
    text: Deletion or anonymisation within 30 days, unless a legal obligation requires longer retention
  rights:
  - right: Access
    text: 'Right of access : obtain a copy of the data we hold about you'
  - right: Rectification
    text: 'Right of rectification : correct inaccurate data'
  - right: Objection
    text: 'Right to object : object to a processing operation, subject to legitimate grounds'
  - right: Erasure
    text: 'Right to erasure : request the deletion of your data, subject to our legal retention obligations'
  - right: Withdraw consent
    text: Right to withdraw consent, where the processing is based on it
  role:
    text: 'Data Controller : ALLNOACROBÁTICO - CONSULTORIA DE ANÁLISE DADOS, UNIPESSOAL LDA'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell, rent or share your data with third parties for commercial purposes.
  subprocessors:
    text: 'full list: https://envoisms.ma/en/legal/subprocessors/'
    url: https://envoisms.ma/en/legal/subprocessors/
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: envoisms-ma
provenance_date: '2026-11-09'
provider_name: envoisms-ma
provider_slug: envoisms-ma
slug: envoisms-ma-privacy-policy
source_date: '2026-11-09'
source_filename: envoisms-ma-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://envoisms.ma/en/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: envoisms-ma\naid: envoisms-ma\nurl: https://envoisms.ma/en/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Data Controller : ALLNOACROBÁTICO - CONSULTORIA DE ANÁLISE DADOS, UNIPESSOAL LDA'\ndata_categories:\n- category: identifying\n  text: Last name, first name, business email, company, telephone\n- category: financial\n  text: Payment method (processed by Stripe, never stored by us), billing address, purchase history\n- category: communication\n  text: Recipient telephone numbers, content of messages sent, send logs, delivery statuses (DLR)\n- category: device\n  text: IP address,\
  \ browser type, pages visited, cookies\n- category: communication\n  text: Exchanges with support, tickets, call recordings where applicable\npurposes:\n- purpose: Provide, operate and secure the Service\n  text: Provide, operate and secure the Service (message sending, API, dashboard)\n- purpose: Billing and account management\n  text: Bill and manage your customer account\n- purpose: Technical and commercial support\n  text: Provide technical and commercial support\n- purpose: Legal and regulatory compliance\n  text: Comply with our legal and regulatory obligations (accounting, anti-fraud, judicial requisitions)\n- purpose: Service improvement and measurement\n  text: Improve our Services and measure their performance (aggregated and anonymised statistics)\nretention:\n- scope: Active account data\n  period: For the entire duration of the contractual relationship\n  text: Active account data For the entire duration of the contractual relationship\n- scope: SMS/WhatsApp send logs\n  period:\
  \ 12 months\n  text: SMS/WhatsApp send logs (content, DLR) 12 months, for delivery-proof and support purposes\n- scope: Billing data\n  period: 10 years\n  text: Billing data 10 years (accounting obligations)\n- scope: Data after account closure\n  period: 30 days\n  text: Deletion or anonymisation within 30 days, unless a legal obligation requires longer retention\nresidency: []\ntransfers: []\nsubprocessors:\n  url: https://envoisms.ma/en/legal/subprocessors/\n  text: 'full list: https://envoisms.ma/en/legal/subprocessors/'\ndpa:\n  available: true\n  url: https://envoisms.ma/en/legal/dpa/\n  text: View official DPA\ndeletion:\n  route: Deletion or anonymisation after account closure\n  text: Deletion or anonymisation within 30 days, unless a legal obligation requires longer retention\nrights:\n- right: Access\n  text: 'Right of access : obtain a copy of the data we hold about you'\n- right: Rectification\n  text: 'Right of rectification : correct inaccurate data'\n- right: Objection\n\
  \  text: 'Right to object : object to a processing operation, subject to legitimate grounds'\n- right: Erasure\n  text: 'Right to erasure : request the deletion of your data, subject to our legal retention obligations'\n- right: Withdraw consent\n  text: Right to withdraw consent, where the processing is based on it\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell, rent or share your data with third parties for commercial purposes.\n"
source_yaml_url: https://artifacts.apis.io/envoisms-ma/privacy/envoisms-ma-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from envoisms-ma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- WhatsApp
- Messaging
- Morocco
- CPaaS
---
