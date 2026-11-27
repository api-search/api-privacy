---
api_specs:
- filename: audioscrape-com-account-api-openapi.yml
  format: yaml
  label: Audioscrape Account API
  slug: audioscrape-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-account-api-openapi.yml
- filename: audioscrape-com-agent-rail-api-openapi.yml
  format: yaml
  label: Audioscrape Agent rail API
  slug: audioscrape-com-agent-rail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-agent-rail-api-openapi.yml
- filename: audioscrape-com-api-keys-api-openapi.yml
  format: yaml
  label: Audioscrape API Keys API
  slug: audioscrape-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-api-keys-api-openapi.yml
- filename: audioscrape-com-charts-api-openapi.yml
  format: yaml
  label: Audioscrape Charts API
  slug: audioscrape-com-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-charts-api-openapi.yml
- filename: audioscrape-com-data-export-api-openapi.yml
  format: yaml
  label: Audioscrape Data Export API
  slug: audioscrape-com-data-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-data-export-api-openapi.yml
- filename: audioscrape-com-episodes-api-openapi.yml
  format: yaml
  label: Audioscrape Episodes API
  slug: audioscrape-com-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-episodes-api-openapi.yml
- filename: audioscrape-com-items-api-openapi.yml
  format: yaml
  label: Audioscrape Items API
  slug: audioscrape-com-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-items-api-openapi.yml
- filename: audioscrape-com-knowledge-graph-api-openapi.yml
  format: yaml
  label: Audioscrape Knowledge Graph API
  slug: audioscrape-com-knowledge-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-knowledge-graph-api-openapi.yml
- filename: audioscrape-com-libraries-api-openapi.yml
  format: yaml
  label: Audioscrape Libraries API
  slug: audioscrape-com-libraries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-libraries-api-openapi.yml
- filename: audioscrape-com-persons-api-openapi.yml
  format: yaml
  label: Audioscrape Persons API
  slug: audioscrape-com-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-persons-api-openapi.yml
- filename: audioscrape-com-podcasts-api-openapi.yml
  format: yaml
  label: Audioscrape Podcasts API
  slug: audioscrape-com-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-podcasts-api-openapi.yml
- filename: audioscrape-com-search-api-openapi.yml
  format: yaml
  label: Audioscrape Search API
  slug: audioscrape-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-search-api-openapi.yml
- filename: audioscrape-com-system-api-openapi.yml
  format: yaml
  label: Audioscrape System API
  slug: audioscrape-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-system-api-openapi.yml
- filename: audioscrape-com-workspaces-api-openapi.yml
  format: yaml
  label: Audioscrape Workspaces API
  slug: audioscrape-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audioscrape-com/openapi/audioscrape-com-workspaces-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (name, email address) when you sign up via Google OAuth
  - category: financial
    text: Payment information when you subscribe (processed securely through Stripe)
  - category: location
    text: IP address and approximate location
  - category: device
    text: Device information (browser type, operating system)
  - category: behavioral
    text: Usage data (pages visited, features used, search queries)
  - category: communication
    text: Communications you send to us (support requests, feedback)
  deletion:
    route: Account › Close account
    text: Close your account yourself under Account › Close account — your recordings, transcripts, sign-in and keys are deleted at once — or ask us to do it
  dpa:
    available: true
    text: customers under a Data Processing Agreement are notified by email in advance of any subprocessor change.
    url: null
  purposes:
  - purpose: Provide and maintain services
    text: Provide and maintain our services
  - purpose: Process transactions and manage subscriptions
    text: Process your transactions and manage subscriptions
  - purpose: Analyze usage patterns
    text: Analyze usage patterns and optimize our platform
  - purpose: Comply with legal obligations
    text: Comply with legal obligations
  residency:
  - region: EU/EEA
    text: Infrastructure providers — Hetzner Online GmbH (Germany and Finland) and NexGen Cloud Ltd / Hyperstack (Norway) Hosting, compute, storage, and backups EU/EEA, no third-country transfer
  - region: United States
    text: OpenAI, LLC AI processing for transcript-derived features; training on customer data is disabled United States, EU–US Data Privacy Framework
  retention:
  - period: immediately
    scope: Account closure data
    text: When you close your account, your recordings, transcripts, sign-in details, keys and connected apps are deleted immediately.
  - period: within 30 days
    scope: Backups
    text: Deleted data leaves our backups as they rotate, within 30 days.
  - period: the period tax law requires
    scope: Invoices and payment records
    text: Invoices and payment records are kept for the period tax law requires.
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate data'
  - right: Erasure
    text: 'Erasure: Close your account yourself under Account › Close account'
  - right: Portability
    text: 'Portability: Receive your data in a structured format'
  - right: Objection
    text: 'Objection: Object to certain types of processing'
  - right: Restriction
    text: 'Restriction: Request limited processing of your data'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: We keep a current list of subprocessors — including their processing locations, transfer mechanisms, and scope — which enterprise customers can request at any time
    url: null
  transfers:
  - mechanism: DPF
    text: United States, EU–US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Audioscrape
provenance_date: '2026-11-09'
provider_name: Audioscrape
provider_slug: audioscrape-com
slug: audioscrape-com-privacy-policy
source_date: '2026-11-09'
source_filename: audioscrape-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.audioscrape.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Audioscrape\naid: audioscrape-com\nurl: https://www.audioscrape.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (name, email address) when you sign up via Google OAuth\n- category: financial\n  text: Payment information when you subscribe (processed securely through Stripe)\n- category: location\n  text: IP address and approximate location\n- category: device\n  text: Device information (browser type, operating system)\n- category: behavioral\n  text: Usage data (pages visited, features used, search\
  \ queries)\n- category: communication\n  text: Communications you send to us (support requests, feedback)\npurposes:\n- purpose: Provide and maintain services\n  text: Provide and maintain our services\n- purpose: Process transactions and manage subscriptions\n  text: Process your transactions and manage subscriptions\n- purpose: Analyze usage patterns\n  text: Analyze usage patterns and optimize our platform\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations\nretention:\n- scope: Account closure data\n  period: immediately\n  text: When you close your account, your recordings, transcripts, sign-in details, keys and connected apps are\n    deleted immediately.\n- scope: Backups\n  period: within 30 days\n  text: Deleted data leaves our backups as they rotate, within 30 days.\n- scope: Invoices and payment records\n  period: the period tax law requires\n  text: Invoices and payment records are kept for the period tax law requires.\nresidency:\n- region: EU/EEA\n\
  \  text: Infrastructure providers — Hetzner Online GmbH (Germany and Finland) and NexGen Cloud Ltd / Hyperstack (Norway)\n    Hosting, compute, storage, and backups EU/EEA, no third-country transfer\n- region: United States\n  text: OpenAI, LLC AI processing for transcript-derived features; training on customer data is disabled United\n    States, EU–US Data Privacy Framework\ntransfers:\n- mechanism: DPF\n  text: United States, EU–US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: We keep a current list of subprocessors — including their processing locations, transfer mechanisms, and\n    scope — which enterprise customers can request at any time\ndpa:\n  available: true\n  url: null\n  text: customers under a Data Processing Agreement are notified by email in advance of any subprocessor change.\ndeletion:\n  route: Account › Close account\n  text: Close your account yourself under Account › Close account — your recordings, transcripts, sign-in and keys\n    are deleted at\
  \ once — or ask us to do it\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Rectification: Request correction of inaccurate data'\n- right: Erasure\n  text: 'Erasure: Close your account yourself under Account › Close account'\n- right: Portability\n  text: 'Portability: Receive your data in a structured format'\n- right: Objection\n  text: 'Objection: Object to certain types of processing'\n- right: Restriction\n  text: 'Restriction: Request limited processing of your data'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/audioscrape-com/privacy/audioscrape-com-privacy-policy.yml
stated_fields:
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
summary_line: 26 quoted statements, read from Audioscrape's own page on 2026-11-09.
synthetic: false
tags:
- Audio
- Artificial Intelligence
- Transcription
- Search
- MCP
---
