---
api_specs:
- filename: slng-account-api-openapi.yml
  format: yaml
  label: SLNG Account API
  slug: slng-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-account-api-openapi.yml
- filename: slng-agents-api-openapi.yml
  format: yaml
  label: SLNG Agents API
  slug: slng-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-agents-api-openapi.yml
- filename: slng-calls-api-openapi.yml
  format: yaml
  label: SLNG Calls API
  slug: slng-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-calls-api-openapi.yml
- filename: slng-catalog-api-openapi.yml
  format: yaml
  label: SLNG Catalog API
  slug: slng-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-catalog-api-openapi.yml
- filename: slng-deepgram-aura-2-api-openapi.yml
  format: yaml
  label: SLNG Deepgram Aura 2 API
  slug: slng-deepgram-aura-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-deepgram-aura-2-api-openapi.yml
- filename: slng-deepgram-nova-3-api-openapi.yml
  format: yaml
  label: SLNG Deepgram Nova 3 API
  slug: slng-deepgram-nova-3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-deepgram-nova-3-api-openapi.yml
- filename: slng-inworld-max-1-5-api-openapi.yml
  format: yaml
  label: SLNG Inworld Max 1.5 API
  slug: slng-inworld-max-1-5-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-inworld-max-1-5-api-openapi.yml
- filename: slng-orpheus-english-api-openapi.yml
  format: yaml
  label: SLNG Orpheus English API
  slug: slng-orpheus-english-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-orpheus-english-api-openapi.yml
- filename: slng-pronunciation-dictionaries-api-openapi.yml
  format: yaml
  label: SLNG Pronunciation dictionaries API
  slug: slng-pronunciation-dictionaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-pronunciation-dictionaries-api-openapi.yml
- filename: slng-rime-arcana-v2-api-openapi.yml
  format: yaml
  label: SLNG Rime Arcana v2 API
  slug: slng-rime-arcana-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-rime-arcana-v2-api-openapi.yml
- filename: slng-rime-arcana-v3-api-openapi.yml
  format: yaml
  label: SLNG Rime Arcana v3 API
  slug: slng-rime-arcana-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-rime-arcana-v3-api-openapi.yml
- filename: slng-rime-coda-api-openapi.yml
  format: yaml
  label: SLNG Rime Coda API
  slug: slng-rime-coda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-rime-coda-api-openapi.yml
- filename: slng-sessions-api-openapi.yml
  format: yaml
  label: SLNG Sessions API
  slug: slng-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-sessions-api-openapi.yml
- filename: slng-speechmatics-api-openapi.yml
  format: yaml
  label: SLNG Speechmatics API
  slug: slng-speechmatics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-speechmatics-api-openapi.yml
- filename: slng-whisper-large-v3-api-openapi.yml
  format: yaml
  label: SLNG Whisper Large v3 API
  slug: slng-whisper-large-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/slng/openapi/slng-whisper-large-v3-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (name, email address, billing details)
  - category: contact
    text: Contact information for customer support
  - category: financial
    text: Payment and billing information
  - category: communication
    text: Audio files uploaded for processing
  - category: behavioral
    text: Usage analytics and service performance data
  - category: device
    text: IP addresses and device information
  deletion:
    route: Account settings or request to delete account
    text: Delete your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: Processing audio and text through our AI models
  - purpose: Account and billing
    text: Managing your account and billing
  - purpose: Service improvement
    text: Analyzing usage patterns to improve our AI models
  - purpose: Security
    text: Ensuring security and preventing abuse
  residency:
  - region: USA
    text: 'USA: Data processed in US data centers, subject to US privacy laws'
  - region: UK
    text: 'UK: Data processed in UK data centers, subject to UK GDPR'
  - region: EU
    text: 'EU: Data processed in EU data centers, subject to EU GDPR'
  - region: UAE
    text: 'UAE: Data processed in UAE data centers, subject to UAE data protection laws'
  - region: Singapore
    text: 'Singapore: Data processed in Singapore data centers, subject to Singapore PDPA'
  rights:
  - right: Access
    text: Access your personal information
  - right: Correction
    text: Correct inaccurate information
  - right: Deletion
    text: Delete your account and associated data
  - right: Portability
    text: Export your data in a portable format
  - right: Restrict or object
    text: Restrict or object to certain processing activities
  - right: Complaint
    text: the right to lodge a complaint with a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloud infrastructure providers (AWS, Google Cloud, Azure) in your selected region
    url: null
  transfers:
  - mechanism: other
    text: We do not transfer your audio or text data outside your selected region without your explicit consent, except as required by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SLNG
provenance_date: '2026-11-10'
provider_name: SLNG
provider_slug: slng
slug: slng-privacy-policy
source_date: '2026-11-10'
source_filename: slng-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://slng.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SLNG\naid: slng\nurl: https://slng.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (name, email address, billing details)\n- category: contact\n  text: Contact information for customer support\n- category: financial\n  text: Payment and billing information\n- category: communication\n  text: Audio files uploaded for processing\n- category: behavioral\n  text: Usage analytics and service performance data\n- category: device\n  text: IP addresses and device information\npurposes:\n- purpose: Service\
  \ provision\n  text: Processing audio and text through our AI models\n- purpose: Account and billing\n  text: Managing your account and billing\n- purpose: Service improvement\n  text: Analyzing usage patterns to improve our AI models\n- purpose: Security\n  text: Ensuring security and preventing abuse\nretention: []\nresidency:\n- region: USA\n  text: 'USA: Data processed in US data centers, subject to US privacy laws'\n- region: UK\n  text: 'UK: Data processed in UK data centers, subject to UK GDPR'\n- region: EU\n  text: 'EU: Data processed in EU data centers, subject to EU GDPR'\n- region: UAE\n  text: 'UAE: Data processed in UAE data centers, subject to UAE data protection laws'\n- region: Singapore\n  text: 'Singapore: Data processed in Singapore data centers, subject to Singapore PDPA'\ntransfers:\n- mechanism: other\n  text: We do not transfer your audio or text data outside your selected region without your explicit consent, except\n    as required by law.\nsubprocessors:\n  url:\
  \ null\n  text: Cloud infrastructure providers (AWS, Google Cloud, Azure) in your selected region\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or request to delete account\n  text: Delete your account and associated data\nrights:\n- right: Access\n  text: Access your personal information\n- right: Correction\n  text: Correct inaccurate information\n- right: Deletion\n  text: Delete your account and associated data\n- right: Portability\n  text: Export your data in a portable format\n- right: Restrict or object\n  text: Restrict or object to certain processing activities\n- right: Complaint\n  text: the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/slng/privacy/slng-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 24 quoted statements, read from SLNG's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Speech
- Voice
- Speech-to-Text
- Text-to-Speech
- Voice AI
- Voice Agents
- Transcription
- Speech Recognition
- Artificial Intelligence
- API Gateway
- Real-Time
---
