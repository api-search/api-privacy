---
api_specs:
- filename: tunova-ai-generation-api-openapi.yml
  format: yaml
  label: tunova-ai Generation API
  slug: tunova-ai-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tunova-ai/openapi/tunova-ai-generation-api-openapi.yml
- filename: tunova-ai-jobs-api-openapi.yml
  format: yaml
  label: tunova-ai Jobs API
  slug: tunova-ai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tunova-ai/openapi/tunova-ai-jobs-api-openapi.yml
- filename: tunova-ai-utility-api-openapi.yml
  format: yaml
  label: tunova-ai Utility API
  slug: tunova-ai-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tunova-ai/openapi/tunova-ai-utility-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and sign-in state, handled by our authentication provider, Clerk.
  - category: behavioral
    text: Prompts you submit, job metadata (timing, status, model), URLs of generated tracks, and your token ledger — every charge, refund, and top-up.
  - category: financial
    text: We receive the payment status and amount; we never see your wallet keys.
  deletion:
    route: Email a deletion request to the contact address on the page
    text: You can request an export of your data or deletion of your account by emailing [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authentication
    text: Clerk — authentication (email, sessions).
  - purpose: crypto payments
    text: OxaPay — crypto payments (payment status, amounts).
  - purpose: music generation
    text: Suno — generation.
  retention:
  - period: null
    scope: account data
    text: We keep account data while your account is active, and afterwards only as required (for example, accounting records).
  - period: null
    scope: usage ledger
    text: The usage ledger is kept for billing integrity — it is the record that proves what you were and weren't charged for.
  rights:
  - right: export
    text: You can request an export of your data
  - right: deletion
    text: or deletion of your account by emailing [email protected] .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data.
  subprocessors:
    text: Clerk — authentication (email, sessions). OxaPay — crypto payments (payment status, amounts). Cloudflare — infrastructure the service runs on. Linode (Akamai) — servers parts of the service run on. Suno — generation.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tunova-ai
provenance_date: '2026-11-10'
provider_name: tunova-ai
provider_slug: tunova-ai
slug: tunova-ai-privacy-policy
source_date: '2026-11-10'
source_filename: tunova-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tunova.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tunova-ai\naid: tunova-ai\nurl: https://tunova.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address and sign-in state, handled by our authentication provider, Clerk.\n- category: behavioral\n  text: Prompts you submit, job metadata (timing, status, model), URLs of generated tracks, and your token ledger\n    — every charge, refund, and top-up.\n- category: financial\n  text: We receive the payment status and amount; we never see your wallet keys.\npurposes:\n- purpose: authentication\n  text: Clerk — authentication\
  \ (email, sessions).\n- purpose: crypto payments\n  text: OxaPay — crypto payments (payment status, amounts).\n- purpose: music generation\n  text: Suno — generation.\nretention:\n- scope: account data\n  period: null\n  text: We keep account data while your account is active, and afterwards only as required (for example, accounting\n    records).\n- scope: usage ledger\n  period: null\n  text: The usage ledger is kept for billing integrity — it is the record that proves what you were and weren't\n    charged for.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Clerk — authentication (email, sessions). OxaPay — crypto payments (payment status, amounts). Cloudflare\n    — infrastructure the service runs on. Linode (Akamai) — servers parts of the service run on. Suno — generation.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email a deletion request to the contact address on the page\n  text: You can request an export of your data or deletion\
  \ of your account by emailing [email protected] .\nrights:\n- right: export\n  text: You can request an export of your data\n- right: deletion\n  text: or deletion of your account by emailing [email protected] .\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data.\n"
source_yaml_url: https://artifacts.apis.io/tunova-ai/privacy/tunova-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from tunova-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Music
- Audio
- Suno
- TokenizedAPI
- REST
- MCP
---
