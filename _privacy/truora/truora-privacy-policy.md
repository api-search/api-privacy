---
api_specs:
- filename: truora-account-api-openapi.yml
  format: yaml
  label: Truora Account API
  slug: truora-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-account-api-openapi.yml
- filename: truora-checks-api-openapi.yml
  format: yaml
  label: Truora Checks API
  slug: truora-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-checks-api-openapi.yml
- filename: truora-continuous-monitoring-api-openapi.yml
  format: yaml
  label: Truora Continuous Monitoring API
  slug: truora-continuous-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-continuous-monitoring-api-openapi.yml
- filename: truora-digital-identity-api-openapi.yml
  format: yaml
  label: Truora Digital Identity API
  slug: truora-digital-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-digital-identity-api-openapi.yml
- filename: truora-validators-api-openapi.yml
  format: yaml
  label: Truora Validators API
  slug: truora-validators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truora/openapi/truora-validators-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and surnames
  - category: contact
    text: Email address
  - category: demographic
    text: Date and place of birth
  - category: identifying
    text: Official Identification
  - category: biometric
    text: Biometric Data
  - category: demographic
    text: Sex
  - category: financial
    text: Bank accounts
  deletion:
    route: Request the deletion of personal data via the privacy contact privacy@Truora.com
    text: Request the deletion of personal data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract execution
    text: The proper execution of the contract formalized between the Data Subject and Truora.
  - purpose: Identity verification
    text: Identity verification with any valid official document that serves to prove identity.
  - purpose: Marketing communications
    text: Sending information or text messages to the provided cell phone number, email, about new services, service changes and fees, payment reminders, promotions, events, and information of interest to Data Subjects in general.
  - purpose: Fraud prevention
    text: Fraud detection and security matters review.
  - purpose: Billing
    text: Billing and other tax purposes.
  retention:
  - period: during the active life of the account
    scope: Truora Pass account data
    text: Such data will be retained during the active life of the account
  - period: null
    scope: Electronic signature evidence
    text: Truora will retain the associated evidence (such as authentication records, time stamps, and audit trails) for the time necessary to preserve the legal validity and integrity of signed documents
  rights:
  - right: access
    text: (a) access; (b) rectification; (c) erasure ("right to be forgotten"), with legal exceptions
  - right: portability
    text: The right to portability of their Personal Data, under the terms and limits provided in applicable regulations
  - right: withdraw consent
    text: (h) withdraw consent at any time, without affecting the lawfulness of prior processing
  - right: objection
    text: (f) objection, including objection to direct marketing
  - right: human review of automated decisions
    text: The right to request human review of decisions that affect them and that have been made based solely on automated processing
  role:
    text: in events where it is considered as "Controller" and/or "Processor" of the Processing of such Personal Data
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers of Personal Data of EU/EEA data subjects to countries outside the EEA — including Colombia, Brazil, Mexico, Chile, and the United States — will be carried out based on the adequate safeguards of Chapter V of the GDPR, in particular, where applicable, the Standard Contractual Clauses approved by Commission Implementing Decision (EU) 2021/914.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Truora
provenance_date: '2026-11-10'
provider_name: Truora
provider_slug: truora
slug: truora-privacy-policy
source_date: '2026-11-10'
source_filename: truora-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.truora.com/en/integral-privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Truora\naid: truora\nurl: https://www.truora.com/en/integral-privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: in events where it is considered as \"Controller\" and/or \"Processor\" of the Processing of such Personal Data\ndata_categories:\n- category: identifying\n  text: Name and surnames\n- category: contact\n  text: Email address\n- category: demographic\n  text: Date and place of birth\n- category: identifying\n  text: Official Identification\n- category: biometric\n  text: Biometric Data\n- category: demographic\n  text: Sex\n- category: financial\n  text: Bank accounts\npurposes:\n\
  - purpose: Contract execution\n  text: The proper execution of the contract formalized between the Data Subject and Truora.\n- purpose: Identity verification\n  text: Identity verification with any valid official document that serves to prove identity.\n- purpose: Marketing communications\n  text: Sending information or text messages to the provided cell phone number, email, about new services, service\n    changes and fees, payment reminders, promotions, events, and information of interest to Data Subjects in general.\n- purpose: Fraud prevention\n  text: Fraud detection and security matters review.\n- purpose: Billing\n  text: Billing and other tax purposes.\nretention:\n- scope: Truora Pass account data\n  period: during the active life of the account\n  text: Such data will be retained during the active life of the account\n- scope: Electronic signature evidence\n  period: null\n  text: Truora will retain the associated evidence (such as authentication records, time stamps, and audit\
  \ trails)\n    for the time necessary to preserve the legal validity and integrity of signed documents\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Transfers of Personal Data of EU/EEA data subjects to countries outside the EEA — including Colombia, Brazil,\n    Mexico, Chile, and the United States — will be carried out based on the adequate safeguards of Chapter V of\n    the GDPR, in particular, where applicable, the Standard Contractual Clauses approved by Commission Implementing\n    Decision (EU) 2021/914.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request the deletion of personal data via the privacy contact privacy@Truora.com\n  text: Request the deletion of personal data\nrights:\n- right: access\n  text: (a) access; (b) rectification; (c) erasure (\"right to be forgotten\"), with legal exceptions\n- right: portability\n  text: The right to portability of their Personal Data, under the terms and limits\
  \ provided in applicable regulations\n- right: withdraw consent\n  text: (h) withdraw consent at any time, without affecting the lawfulness of prior processing\n- right: objection\n  text: (f) objection, including objection to direct marketing\n- right: human review of automated decisions\n  text: The right to request human review of decisions that affect them and that have been made based solely on\n    automated processing\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truora/privacy/truora-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from Truora's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- KYC
- Background Checks
- Fraud Prevention
- Latin America
- WhatsApp
---
