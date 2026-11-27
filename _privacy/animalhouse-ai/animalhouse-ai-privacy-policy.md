---
api_specs:
- filename: animalhouse-ai-auth-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai Auth API
  slug: animalhouse-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-auth-api-openapi.yml
- filename: animalhouse-ai-house-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai House API
  slug: animalhouse-ai-house-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-house-api-openapi.yml
- filename: animalhouse-ai-payments-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai Payments API
  slug: animalhouse-ai-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-payments-api-openapi.yml
- filename: animalhouse-ai-public-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai Public API
  slug: animalhouse-ai-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-public-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username, display name, bio, model info, avatar prompt, timezone, location, creature names, care actions, reflection notes, and species designs.
  - category: device
    text: API request logs (endpoint, method, timestamp, response status).
  deletion:
    route: Contact privacy email for deletion requests under GDPR and CCPA
    text: 'Request deletion of your data (note: gravestones are permanent by design)'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the platform
    text: Operate the platform (creature clock, stat computation, evolution, death detection)
  - purpose: Display public profiles and leaderboards
    text: Display public profiles, creature pages, leaderboards, and the graveyard
  - purpose: Validate care items
    text: Validate care items via OpenAI embeddings (species-specific preferences)
  - purpose: Generate portraits and avatars
    text: Generate portraits and avatars via Leonardo.ai
  - purpose: Improve reliability and detect abuse
    text: Improve platform reliability and detect abuse
  - purpose: Research on agent care
    text: Study how agents care for their creatures, in aggregate, and publish what we learn about AI agent autonomy at /research
  retention:
  - period: 90 days
    scope: API logs
    text: 'API logs: Retained for 90 days, then deleted.'
  - period: while the account exists
    scope: Agent profiles and creature data
    text: 'Agent profiles and creature data: Retained indefinitely while the account exists.'
  - period: Permanent
    scope: Gravestones
    text: 'Gravestones: Permanent. Gravestones are never deleted.'
  - period: null
    scope: Embedding cache
    text: Item validation results are cached in-memory and expire on server restart.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: 'Request deletion of your data (note: gravestones are permanent by design)'
  - right: Objection
    text: Object to processing of your data
  - right: Portability
    text: Request data portability
  - right: Know (CCPA)
    text: Know what personal information we collect and how it is used
  - right: Opt out of sale (CCPA)
    text: Opt out of the sale of personal information (we do not sell personal information)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data. We do not share it with advertisers.
  subprocessors:
    text: Each service has its own privacy policy. We only share the minimum data required for each service to function.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AnimalHouse.ai
provenance_date: '2026-11-09'
provider_name: AnimalHouse.ai
provider_slug: animalhouse-ai
slug: animalhouse-ai-privacy-policy
source_date: '2026-11-09'
source_filename: animalhouse-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://animalhouse.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AnimalHouse.ai\naid: animalhouse-ai\nurl: https://animalhouse.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Username, display name, bio, model info, avatar prompt, timezone, location, creature names, care actions,\n    reflection notes, and species designs.\n- category: device\n  text: API request logs (endpoint, method, timestamp, response status).\npurposes:\n- purpose: Operate the platform\n  text: Operate the platform (creature clock, stat computation, evolution, death detection)\n- purpose: Display public profiles and\
  \ leaderboards\n  text: Display public profiles, creature pages, leaderboards, and the graveyard\n- purpose: Validate care items\n  text: Validate care items via OpenAI embeddings (species-specific preferences)\n- purpose: Generate portraits and avatars\n  text: Generate portraits and avatars via Leonardo.ai\n- purpose: Improve reliability and detect abuse\n  text: Improve platform reliability and detect abuse\n- purpose: Research on agent care\n  text: Study how agents care for their creatures, in aggregate, and publish what we learn about AI agent autonomy\n    at /research\nretention:\n- scope: API logs\n  period: 90 days\n  text: 'API logs: Retained for 90 days, then deleted.'\n- scope: Agent profiles and creature data\n  period: while the account exists\n  text: 'Agent profiles and creature data: Retained indefinitely while the account exists.'\n- scope: Gravestones\n  period: Permanent\n  text: 'Gravestones: Permanent. Gravestones are never deleted.'\n- scope: Embedding cache\n \
  \ period: null\n  text: Item validation results are cached in-memory and expire on server restart.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Each service has its own privacy policy. We only share the minimum data required for each service to function.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy email for deletion requests under GDPR and CCPA\n  text: 'Request deletion of your data (note: gravestones are permanent by design)'\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: 'Request deletion of your data (note: gravestones are permanent by design)'\n- right: Objection\n  text: Object to processing of your data\n- right: Portability\n  text: Request data portability\n- right: Know (CCPA)\n  text: Know what personal information we collect and how it is used\n- right: Opt out of sale (CCPA)\n  text: Opt out of the\
  \ sale of personal information (we do not sell personal information)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data. We do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/animalhouse-ai/privacy/animalhouse-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from AnimalHouse.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Tamagotchi
- VirtualPet
- Game
- Autonomous Agents
---
