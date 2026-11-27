---
api_specs:
- filename: engagespark-balance-api-openapi.yml
  format: yaml
  label: engageSPARK Balance API
  slug: engagespark-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-balance-api-openapi.yml
- filename: engagespark-campaigns-api-openapi.yml
  format: yaml
  label: engageSPARK Campaigns API
  slug: engagespark-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-campaigns-api-openapi.yml
- filename: engagespark-contacts-api-openapi.yml
  format: yaml
  label: engageSPARK Contacts API
  slug: engagespark-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-contacts-api-openapi.yml
- filename: engagespark-files-api-openapi.yml
  format: yaml
  label: engageSPARK Files API
  slug: engagespark-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-files-api-openapi.yml
- filename: engagespark-sms-api-openapi.yml
  format: yaml
  label: engageSPARK SMS API
  slug: engagespark-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-sms-api-openapi.yml
- filename: engagespark-top-up-api-openapi.yml
  format: yaml
  label: engageSPARK Top-Up API
  slug: engagespark-top-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-top-up-api-openapi.yml
- filename: engagespark-whats-app-api-openapi.yml
  format: yaml
  label: engageSPARK Whats App API
  slug: engagespark-whats-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-whats-app-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identifying information: name, email address, phone number, physical address'
  - category: financial
    text: Your credit card information (processed by our payment processor; we do not store full card numbers)
  - category: location
    text: Location, when received in form of a WhatsApp Location message or similar
  - category: behavioral
    text: 'Internet or other electronic activity: browser type, pages viewed, referring URL, interaction with our Website.'
  - category: communication
    text: Message content (SMS, voice, WhatsApp, and other channels)
  - category: device
    text: Device type, browser type, plugin details
  - category: professional
    text: Your organization name and your role within it
  deletion:
    route: Delete specific Contacts through the Service; account closure triggers deletion per DPA process
    text: You may also delete specific Contacts through the Service at any time.
  dpa:
    available: true
    text: The complete contractual terms governing engageSPARK’s processing of Content — including Article 28 GDPR processor obligations, Standard Contractual Clauses for international transfers, security measures, subprocessor terms, breach notification, audit rights, and return/deletion at end — are set out in our Data Processing Agreement (DPA)
    url: https://www.engagespark.com/legal/data-processing-agreement/
  purposes:
  - purpose: Provide and support the Service
    text: 'Provide and support the Service (basis: contract)'
  - purpose: Billing and payments
    text: 'Bill you and collect payments, including via third-party payment processors (basis: contract / legal obligation)'
  - purpose: Fraud and abuse detection
    text: 'Detect and prevent fraud, abuse, and security incidents (basis: legitimate interests / legal obligation)'
  - purpose: Aggregated analytics
    text: 'Generate aggregated, anonymized analytics about the Service (basis: legitimate interests)'
  residency:
  - region: Germany / European Economic Area
    text: Your account, billing, and support data are primarily processed in the European Economic Area (our servers are in Germany).
  retention:
  - period: six (6) years after closure
    scope: Account data
    text: 'Account data (name, email, organization): for the lifetime of your account, plus up to six (6) years after closure for legal and tax reasons.'
  - period: fifteen (15) years
    scope: Support communications
    text: 'Support communications: up to fifteen (15) years.'
  - period: thirty (30) day cycle
    scope: Backups
    text: 'Backups: purged on a rolling thirty (30) day cycle.'
  rights:
  - right: Access
    text: 'Right of access: request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Right of rectification: correct inaccurate or incomplete data.'
  - right: Erasure
    text: 'Right of erasure: request deletion, subject to applicable retention obligations.'
  - right: Restriction
    text: 'Right to restrict processing: limit how we process your data under certain conditions.'
  - right: Objection
    text: 'Right to object: object to processing based on legitimate interests'
  - right: Portability
    text: 'Right to data portability: receive your data in a structured, commonly used format.'
  - right: Withdraw consent
    text: 'Right to withdraw consent: withdraw any consent at any time, without affecting prior processing.'
  role:
    text: you are the data controller of your Contacts’ data and engageSPARK is your data processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your personal information as those terms are defined under the CCPA, CPRA, or any other US state privacy law.
  subprocessors:
    text: A current list is published at https://www.engagespark.com/legal/subprocessors.
    url: https://www.engagespark.com/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses adopted by the European Commission (Decision 2021/914) for transfers from the EEA;
  - mechanism: other
    text: The UK International Data Transfer Addendum (UK IDTA) for transfers from the UK;
  - mechanism: DPF
    text: The EU-US Data Privacy Framework (and its UK Extension and Swiss-US DPF) for transfers to certified US recipients, where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: engageSPARK
provenance_date: '2026-11-09'
provider_name: engageSPARK
provider_slug: engagespark
slug: engagespark-privacy-policy
source_date: '2026-11-09'
source_filename: engagespark-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.engagespark.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: engageSPARK\naid: engagespark\nurl: https://www.engagespark.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: you are the data controller of your Contacts’ data and engageSPARK is your data processor\ndata_categories:\n- category: identifying\n  text: 'Identifying information: name, email address, phone number, physical address'\n- category: financial\n  text: Your credit card information (processed by our payment processor; we do not store full card numbers)\n- category: location\n  text: Location, when received in form of a WhatsApp Location message or similar\n- category:\
  \ behavioral\n  text: 'Internet or other electronic activity: browser type, pages viewed, referring URL, interaction with our\n    Website.'\n- category: communication\n  text: Message content (SMS, voice, WhatsApp, and other channels)\n- category: device\n  text: Device type, browser type, plugin details\n- category: professional\n  text: Your organization name and your role within it\npurposes:\n- purpose: Provide and support the Service\n  text: 'Provide and support the Service (basis: contract)'\n- purpose: Billing and payments\n  text: 'Bill you and collect payments, including via third-party payment processors (basis: contract / legal obligation)'\n- purpose: Fraud and abuse detection\n  text: 'Detect and prevent fraud, abuse, and security incidents (basis: legitimate interests / legal obligation)'\n- purpose: Aggregated analytics\n  text: 'Generate aggregated, anonymized analytics about the Service (basis: legitimate interests)'\nretention:\n- scope: Account data\n  period: six\
  \ (6) years after closure\n  text: 'Account data (name, email, organization): for the lifetime of your account, plus up to six (6) years after\n    closure for legal and tax reasons.'\n- scope: Support communications\n  period: fifteen (15) years\n  text: 'Support communications: up to fifteen (15) years.'\n- scope: Backups\n  period: thirty (30) day cycle\n  text: 'Backups: purged on a rolling thirty (30) day cycle.'\nresidency:\n- region: Germany / European Economic Area\n  text: Your account, billing, and support data are primarily processed in the European Economic Area (our servers\n    are in Germany).\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses adopted by the European Commission (Decision 2021/914) for transfers from the\n    EEA;\n- mechanism: other\n  text: The UK International Data Transfer Addendum (UK IDTA) for transfers from the UK;\n- mechanism: DPF\n  text: The EU-US Data Privacy Framework (and its UK Extension and Swiss-US DPF) for transfers to certified\
  \ US recipients,\n    where applicable.\nsubprocessors:\n  url: https://www.engagespark.com/legal/subprocessors\n  text: A current list is published at https://www.engagespark.com/legal/subprocessors.\ndpa:\n  available: true\n  url: https://www.engagespark.com/legal/data-processing-agreement/\n  text: The complete contractual terms governing engageSPARK’s processing of Content — including Article 28 GDPR\n    processor obligations, Standard Contractual Clauses for international transfers, security measures, subprocessor\n    terms, breach notification, audit rights, and return/deletion at end — are set out in our Data Processing Agreement\n    (DPA)\ndeletion:\n  route: Delete specific Contacts through the Service; account closure triggers deletion per DPA process\n  text: You may also delete specific Contacts through the Service at any time.\nrights:\n- right: Access\n  text: 'Right of access: request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Right\
  \ of rectification: correct inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Right of erasure: request deletion, subject to applicable retention obligations.'\n- right: Restriction\n  text: 'Right to restrict processing: limit how we process your data under certain conditions.'\n- right: Objection\n  text: 'Right to object: object to processing based on legitimate interests'\n- right: Portability\n  text: 'Right to data portability: receive your data in a structured, commonly used format.'\n- right: Withdraw consent\n  text: 'Right to withdraw consent: withdraw any consent at any time, without affecting prior processing.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your personal information as those terms are defined under the CCPA, CPRA, or any\n    other US state privacy law.\n"
source_yaml_url: https://artifacts.apis.io/engagespark/privacy/engagespark-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from engageSPARK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Messaging
- SMS
- Voice
- WhatsApp
- Airtime
- Communications
- CPaaS
- Surveys
- International Development
---
