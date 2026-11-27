---
api_specs:
- filename: tl-dv-meetings-api-openapi.yml
  format: yaml
  label: tl;dv Meetings API
  slug: tl-dv-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-meetings-api-openapi.yml
- filename: tl-dv-notes-api-openapi.yml
  format: yaml
  label: tl;dv Notes API
  slug: tl-dv-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-notes-api-openapi.yml
- filename: tl-dv-system-api-openapi.yml
  format: yaml
  label: tl;dv System API
  slug: tl-dv-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-system-api-openapi.yml
- filename: tl-dv-transcripts-api-openapi.yml
  format: yaml
  label: tl;dv Transcripts API
  slug: tl-dv-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-transcripts-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name and profile image URL
  - category: location
    text: 'Metadata: IP address, your geographic location.'
  - category: financial
    text: Information relating to credit card, billing email, banking info, transaction location and/or billing address
  - category: communication
    text: Video and audio recording, written transcriptions
  - category: device
    text: devices used to access the Services, including device type, operating system used, device settings, application identifiers, unique device identifiers and crash data.
  - category: behavioral
    text: pages viewed and navigation paths on the website, the frequency and pattern of your service use.
  deletion:
    route: Account deletion or data deletion request
    text: For 5 years or upon deletion request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision of the main service
    text: Provision of the main service, sharing and collaboration
  - purpose: Security and fraud prevention
    text: Security and fraud prevention, adapted pricing, security monitoring.
  - purpose: Product analysis and improvement
    text: Product analysis and improvement, marketing and attribution, incident management
  - purpose: Billing
    text: Billing
  residency:
  - region: European Economic Area
    text: All personal data collected through our platform is primarily processed and stored in facilities located in the European Economic Area (EEA)
  retention:
  - period: 3 months
    scope: Free user recordings and transcriptions
    text: 'Free user: 3 months'
  - period: until account deletion
    scope: Paying user recordings and transcriptions
    text: 'Paying user: until account deletion'
  - period: 10 days
    scope: Logs
    text: Logs Automatic Fraud detection and prevention, legal compliance, internal audit, performance analysis, product optimization, customer support, infrastructure monitoring 10 days
  - period: Until consent withdrawal
    scope: Newsletter email address
    text: Newsletter Until consent withdrawal
  rights:
  - right: Access
    text: 'Right of access: you can request a copy of the data that personally concerns you'
  - right: Rectification
    text: 'Right of rectification: you can modify data that would be inaccurate concerning you'
  - right: Erasure
    text: 'Right to erasure: you can ask us to erase the data concerning you'
  - right: Portability
    text: Right to portability.
  - right: Objection
    text: 'Right of opposition: you can oppose our processing of your data'
  - right: Limitation
    text: Right to limitation of processing.
  - right: Withdraw consent
    text: when you give your consent to the processing of your personal data, you have the possibility to withdraw it at any time
  role:
    text: This policy applies when we act as a Data Controller with respect to the personal data of users of our services
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We will not sell the collected data to other companies .
  subprocessors:
    text: Hosting/infrastructure/storage providers Google Cloud, Hetzner, Wasabi
    url: null
  transfers:
  - mechanism: SCC
    text: We have ensured that appropriate guarantees are in place for these transfers, namely the use of standard data protection clauses adopted or approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tl;dv
provenance_date: '2026-11-10'
provider_name: tl;dv
provider_slug: tl-dv
slug: tl-dv-privacy-policy
source_date: '2026-11-10'
source_filename: tl-dv-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tldv.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tl;dv\naid: tl-dv\nurl: https://tldv.io/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This policy applies when we act as a Data Controller with respect to the personal data of users of our services\ndata_categories:\n- category: identifying\n  text: Email address, name and profile image URL\n- category: location\n  text: 'Metadata: IP address, your geographic location.'\n- category: financial\n  text: Information relating to credit card, billing email, banking info, transaction location and/or billing address\n- category: communication\n  text: Video and audio recording, written\
  \ transcriptions\n- category: device\n  text: devices used to access the Services, including device type, operating system used, device settings, application\n    identifiers, unique device identifiers and crash data.\n- category: behavioral\n  text: pages viewed and navigation paths on the website, the frequency and pattern of your service use.\npurposes:\n- purpose: Provision of the main service\n  text: Provision of the main service, sharing and collaboration\n- purpose: Security and fraud prevention\n  text: Security and fraud prevention, adapted pricing, security monitoring.\n- purpose: Product analysis and improvement\n  text: Product analysis and improvement, marketing and attribution, incident management\n- purpose: Billing\n  text: Billing\nretention:\n- scope: Free user recordings and transcriptions\n  period: 3 months\n  text: 'Free user: 3 months'\n- scope: Paying user recordings and transcriptions\n  period: until account deletion\n  text: 'Paying user: until account deletion'\n\
  - scope: Logs\n  period: 10 days\n  text: Logs Automatic Fraud detection and prevention, legal compliance, internal audit, performance analysis, product\n    optimization, customer support, infrastructure monitoring 10 days\n- scope: Newsletter email address\n  period: Until consent withdrawal\n  text: Newsletter Until consent withdrawal\nresidency:\n- region: European Economic Area\n  text: All personal data collected through our platform is primarily processed and stored in facilities located\n    in the European Economic Area (EEA)\ntransfers:\n- mechanism: SCC\n  text: We have ensured that appropriate guarantees are in place for these transfers, namely the use of standard\n    data protection clauses adopted or approved by the European Commission.\nsubprocessors:\n  url: null\n  text: Hosting/infrastructure/storage providers Google Cloud, Hetzner, Wasabi\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or data deletion request\n  text: For 5\
  \ years or upon deletion request\nrights:\n- right: Access\n  text: 'Right of access: you can request a copy of the data that personally concerns you'\n- right: Rectification\n  text: 'Right of rectification: you can modify data that would be inaccurate concerning you'\n- right: Erasure\n  text: 'Right to erasure: you can ask us to erase the data concerning you'\n- right: Portability\n  text: Right to portability.\n- right: Objection\n  text: 'Right of opposition: you can oppose our processing of your data'\n- right: Limitation\n  text: Right to limitation of processing.\n- right: Withdraw consent\n  text: when you give your consent to the processing of your personal data, you have the possibility to withdraw\n    it at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell the collected data to other companies .\n"
source_yaml_url: https://artifacts.apis.io/tl-dv/privacy/tl-dv-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from tl;dv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Meetings
- Transcription
- Note Taking
- Conversation Intelligence
- Productivity
- Video
- Webhook
---
