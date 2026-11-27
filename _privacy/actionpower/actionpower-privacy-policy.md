---
api_specs:
- filename: actionpower-nlp-api-openapi.yml
  format: yaml
  label: Actionpower NLP API
  slug: actionpower-nlp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionpower/openapi/actionpower-nlp-api-openapi.yml
- filename: actionpower-stt-api-openapi.yml
  format: yaml
  label: Actionpower STT API
  slug: actionpower-stt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionpower/openapi/actionpower-stt-api-openapi.yml
- filename: actionpower-tts-api-openapi.yml
  format: yaml
  label: Actionpower TTS API
  slug: actionpower-tts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionpower/openapi/actionpower-tts-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, ID, password, email address, date of birth, gender (Required)
  - category: contact
    text: ID, mobile phone number, email address, telephone number, address (Required)
  - category: financial
    text: payment information, bank account information
  - category: behavioral
    text: Advertising identifiers, service usage records, cookies (Optional)
  - category: communication
    text: Voice and video files, call recording files, transcription results, edited text, patterns of interaction with the service (Optional)
  - category: device
    text: IP address, smartphone device information (device model, OS, mobile carrier, device ID)
  - category: demographic
    text: Gender, age group, occupation, purpose of use, expected features
  deletion:
    route: Edit Information on the daglo site, or written or email request
    text: where requested by email or in writing, the Company will process the viewing, correction, and deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Identity verification, SSO integration
    text: Identity verification, SSO integration
  - purpose: Marketing and promotion
    text: The Company uses personal information for marketing and promotional purposes, such as providing event information and participation opportunities and providing promotional information.
  - purpose: Service analysis and customized services
    text: The Company uses personal information for analysis of service usage records and access frequency, statistics on service use, service analysis using user behavior analysis tools
  residency:
  - region: United States
    text: Google transmits the information collected through cookies to and stores it on Google servers located in the United States.
  retention:
  - period: at least 2 years
    scope: Dormant accounts
    text: A dormant account is an account that has not been used even once for at least 2 years.
  - period: 3 months
    scope: Log records and IP addresses under Protection of Communications Secrets Act
    text: Log records, IP addresses, etc. — 3 months
  - period: Retained during the service provision period
    scope: Overseas trustee retention
    text: Retained during the service provision period
  rights:
  - right: View and correct
    text: Users may view and correct their personal information at any time through
  - right: Suspend processing
    text: Users may request the suspension of processing of their personal information on the daglo site at any time.
  - right: Withdraw consent
    text: Users may withdraw at any time the consent they have given to the collection, use, and provision of personal information through membership registration, etc.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The Company outsources work as follows in connection with the processing of personal information
    url: null
  transfers:
  - mechanism: other
    text: For smooth personal information processing, the Company outsources to overseas entities as follows.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Actionpower
provenance_date: '2026-11-09'
provider_name: Actionpower
provider_slug: actionpower
slug: actionpower-privacy-policy
source_date: '2026-11-09'
source_filename: actionpower-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://daglo.ai/d/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Actionpower\naid: actionpower\nurl: https://daglo.ai/d/en/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, ID, password, email address, date of birth, gender (Required)\n- category: contact\n  text: ID, mobile phone number, email address, telephone number, address (Required)\n- category: financial\n  text: payment information, bank account information\n- category: behavioral\n  text: Advertising identifiers, service usage records, cookies (Optional)\n- category: communication\n  text: Voice and video files, call recording\
  \ files, transcription results, edited text, patterns of interaction\n    with the service (Optional)\n- category: device\n  text: IP address, smartphone device information (device model, OS, mobile carrier, device ID)\n- category: demographic\n  text: Gender, age group, occupation, purpose of use, expected features\npurposes:\n- purpose: Identity verification, SSO integration\n  text: Identity verification, SSO integration\n- purpose: Marketing and promotion\n  text: The Company uses personal information for marketing and promotional purposes, such as providing event information\n    and participation opportunities and providing promotional information.\n- purpose: Service analysis and customized services\n  text: The Company uses personal information for analysis of service usage records and access frequency, statistics\n    on service use, service analysis using user behavior analysis tools\nretention:\n- scope: Dormant accounts\n  period: at least 2 years\n  text: A dormant account\
  \ is an account that has not been used even once for at least 2 years.\n- scope: Log records and IP addresses under Protection of Communications Secrets Act\n  period: 3 months\n  text: Log records, IP addresses, etc. — 3 months\n- scope: Overseas trustee retention\n  period: Retained during the service provision period\n  text: Retained during the service provision period\nresidency:\n- region: United States\n  text: Google transmits the information collected through cookies to and stores it on Google servers located in\n    the United States.\ntransfers:\n- mechanism: other\n  text: For smooth personal information processing, the Company outsources to overseas entities as follows.\nsubprocessors:\n  url: null\n  text: The Company outsources work as follows in connection with the processing of personal information\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Edit Information on the daglo site, or written or email request\n  text: where requested by email or\
  \ in writing, the Company will process the viewing, correction, and deletion.\nrights:\n- right: View and correct\n  text: Users may view and correct their personal information at any time through\n- right: Suspend processing\n  text: Users may request the suspension of processing of their personal information on the daglo site at any time.\n- right: Withdraw consent\n  text: Users may withdraw at any time the consent they have given to the collection, use, and provision of personal\n    information through membership registration, etc.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/actionpower/privacy/actionpower-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 20 quoted statements, read from Actionpower's own page on 2026-11-09.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Text-to-Speech
- Natural Language Processing
- Artificial Intelligence
- Transcription
- Voice
- Meeting Intelligence
- gRPC
- South Korea
---
