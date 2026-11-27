---
api_specs:
- filename: sarvam-pronunciationdictionary-api-openapi.yml
  format: yaml
  label: Sarvam Pronunciation Dictionary API
  slug: sarvam-pronunciationdictionary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-pronunciationdictionary-api-openapi.yml
- filename: sarvam-speechtotextjob-api-openapi.yml
  format: yaml
  label: Sarvam Speech To Text Job API
  slug: sarvam-speechtotextjob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-speechtotextjob-api-openapi.yml
- filename: sarvam-speechtotexttranslatejob-api-openapi.yml
  format: yaml
  label: Sarvam Speech To Text Translate Job API
  slug: sarvam-speechtotexttranslatejob-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-speechtotexttranslatejob-api-openapi.yml
- filename: sarvam-text-api-openapi.yml
  format: yaml
  label: Sarvam Text API
  slug: sarvam-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-text-api-openapi.yml
- filename: sarvam-chat-completions-api-openapi.yml
  format: yaml
  label: Sarvam Chat Completions API
  slug: sarvam-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-chat-completions-api-openapi.yml
- filename: sarvam-document-intelligence-api-openapi.yml
  format: yaml
  label: Sarvam Document Intelligence API
  slug: sarvam-document-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-document-intelligence-api-openapi.yml
- filename: sarvam-speech-to-text-api-openapi.yml
  format: yaml
  label: Sarvam Speech To Text API
  slug: sarvam-speech-to-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-speech-to-text-api-openapi.yml
- filename: sarvam-text-to-speech-api-openapi.yml
  format: yaml
  label: Sarvam Text To Speech API
  slug: sarvam-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sarvam/openapi/sarvam-text-to-speech-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your first and last names, location (unless disabled by accessing the Device settings
  - category: contact
    text: email address, residential and/or work place address, mobile number, postal code
  - category: financial
    text: Financial transaction data (processed by certified payment gateways, not stored by us).
  - category: behavioral
    text: standard usage logs, through the web server, cookies, standard web log data, traffic to and from our Services
  - category: device
    text: an IP address, assigned to the Device used by the User; type of browser used by the User
  - category: location
    text: automatically receive, collect and analyze your location data which may be accessed through a variety of methods including, inter alia, GPS, Internet Protocol address, and cell tower/Device location
  - category: biometric
    text: Voice biometric data for Content Studio (with explicit consent and additional safeguards);
  - category: communication
    text: 'Communication & support data: name, contact details, and contents of messages you send us'
  deletion:
    route: Account Settings or email to the privacy contact with subject "Data Deletion Request"
    text: 'We will delete data within 30 days of request verification, except where:'
  dpa:
    available: true
    text: Data processing agreements with all international vendors
    url: null
  purposes:
  - purpose: Model training and service improvement
    text: We use Your content (including inputs, uploads, prompts, or generated outputs) to train, fine-tune, and/ or improve our AI models unless you explicitly opt-out through your account settings
  - purpose: Providing and generating outputs
    text: To process your requests and generate outputs (transcription, synthesized speech, translations, digitized documents)
  - purpose: Marketing communications
    text: to communicate special offers and general information about our products, services and events
  - purpose: Security and fraud prevention
    text: To monitor, secure and maintain the platform, prevent abuse and fraud, enforce rate limits, troubleshoot and improve reliability
  residency:
  - region: India
    text: Sensitive personal data of Indian users is stored in India where feasible
  - region: India
    text: 'Payment data: Stored in India per RBI Payment System Data guidelines'
  retention:
  - period: Duration of account + 90 days post-termination
    scope: Account & profile data
    text: Duration of account + 90 days post-termination unless early deletion is requested in writing
  - period: 1 year from collection
    scope: Usage logs & technical data
    text: 1 year from collection and such additional period as may be prescribed DPDP Rules 2025, Rule 6 (mandatory minimum)
  - period: 30 days after last access
    scope: Your content (inputs/outputs)
    text: 'User-configurable (default: 30 days after last access)'
  - period: Until consent withdrawal + 30 days
    scope: Voice samples & models
    text: Voice Samples & Models Until consent withdrawal + 30 days
  - period: 2 years from last interaction
    scope: Support communications
    text: Support Communications 2 years from last interaction
  - period: 7 years from incident
    scope: Security incident logs
    text: Security Incident Logs 7 years from incident
  rights:
  - right: Access
    text: Confirmation of whether we are processing your personal data. Summary of personal data being processed.
  - right: Correction and erasure
    text: Correction of inaccurate, incomplete, or out-of-date personal data.
  - right: Grievance redressal
    text: You may lodge complaints about data processing activities with our Data Protection Officer
  - right: Nominate
    text: You may nominate another individual to exercise your rights in case of death or incapacity.
  - right: Consent withdrawal
    text: You may withdraw consent at any time with the same ease as giving consent.
  role:
    text: Axonwise Private Limited (doing business as Sarvam AI) is the Data Fiduciary under the Digital Personal Data Protection Act, 2023
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we do not sell your data to any third party under any circumstance
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs):EU Commission-approved SCCs for GDPR transfers.
  - mechanism: other
    text: 'Contractual Obligations: Data processing agreements with all international vendors'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sarvam
provenance_date: '2026-11-10'
provider_name: Sarvam
provider_slug: sarvam
slug: sarvam-privacy-policy
source_date: '2026-11-10'
source_filename: sarvam-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sarvam.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sarvam\naid: sarvam\nurl: https://www.sarvam.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Axonwise Private Limited (doing business as Sarvam AI) is the Data Fiduciary under the Digital Personal\n    Data Protection Act, 2023\ndata_categories:\n- category: identifying\n  text: such as your first and last names, location (unless disabled by accessing the Device settings\n- category: contact\n  text: email address, residential and/or work place address, mobile number, postal code\n- category: financial\n  text: Financial transaction data (processed by certified payment gateways,\
  \ not stored by us).\n- category: behavioral\n  text: standard usage logs, through the web server, cookies, standard web log data, traffic to and from our Services\n- category: device\n  text: an IP address, assigned to the Device used by the User; type of browser used by the User\n- category: location\n  text: automatically receive, collect and analyze your location data which may be accessed through a variety of\n    methods including, inter alia, GPS, Internet Protocol address, and cell tower/Device location\n- category: biometric\n  text: Voice biometric data for Content Studio (with explicit consent and additional safeguards);\n- category: communication\n  text: 'Communication & support data: name, contact details, and contents of messages you send us'\npurposes:\n- purpose: Model training and service improvement\n  text: We use Your content (including inputs, uploads, prompts, or generated outputs) to train, fine-tune, and/\n    or improve our AI models unless you explicitly opt-out\
  \ through your account settings\n- purpose: Providing and generating outputs\n  text: To process your requests and generate outputs (transcription, synthesized speech, translations, digitized\n    documents)\n- purpose: Marketing communications\n  text: to communicate special offers and general information about our products, services and events\n- purpose: Security and fraud prevention\n  text: To monitor, secure and maintain the platform, prevent abuse and fraud, enforce rate limits, troubleshoot\n    and improve reliability\nretention:\n- scope: Account & profile data\n  period: Duration of account + 90 days post-termination\n  text: Duration of account + 90 days post-termination unless early deletion is requested in writing\n- scope: Usage logs & technical data\n  period: 1 year from collection\n  text: 1 year from collection and such additional period as may be prescribed DPDP Rules 2025, Rule 6 (mandatory\n    minimum)\n- scope: Your content (inputs/outputs)\n  period: 30 days after\
  \ last access\n  text: 'User-configurable (default: 30 days after last access)'\n- scope: Voice samples & models\n  period: Until consent withdrawal + 30 days\n  text: Voice Samples & Models Until consent withdrawal + 30 days\n- scope: Support communications\n  period: 2 years from last interaction\n  text: Support Communications 2 years from last interaction\n- scope: Security incident logs\n  period: 7 years from incident\n  text: Security Incident Logs 7 years from incident\nresidency:\n- region: India\n  text: Sensitive personal data of Indian users is stored in India where feasible\n- region: India\n  text: 'Payment data: Stored in India per RBI Payment System Data guidelines'\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs):EU Commission-approved SCCs for GDPR transfers.\n- mechanism: other\n  text: 'Contractual Obligations: Data processing agreements with all international vendors'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url:\
  \ null\n  text: Data processing agreements with all international vendors\ndeletion:\n  route: Account Settings or email to the privacy contact with subject \"Data Deletion Request\"\n  text: 'We will delete data within 30 days of request verification, except where:'\nrights:\n- right: Access\n  text: Confirmation of whether we are processing your personal data. Summary of personal data being processed.\n- right: Correction and erasure\n  text: Correction of inaccurate, incomplete, or out-of-date personal data.\n- right: Grievance redressal\n  text: You may lodge complaints about data processing activities with our Data Protection Officer\n- right: Nominate\n  text: You may nominate another individual to exercise your rights in case of death or incapacity.\n- right: Consent withdrawal\n  text: You may withdraw consent at any time with the same ease as giving consent.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell your data to any third party under any circumstance\n"
source_yaml_url: https://artifacts.apis.io/sarvam/privacy/sarvam-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Sarvam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Speech-to-Text
- Text-to-Speech
- Translation
- LLM
- Document Intelligence
- Indian Languages
- Voice
- Real-Time
---
