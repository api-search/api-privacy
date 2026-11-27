---
api_specs:
- filename: cheapestinference-com-api-openapi-generated.yml
  format: yaml
  label: cheapestinference-com api API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cheapestinference-com/openapi/_ae-authored/cheapestinference-com-api-openapi-generated.yml
- filename: cheapestinference-com-core-openapi-generated.yml
  format: yaml
  label: cheapestinference-com core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cheapestinference-com/openapi/_ae-authored/cheapestinference-com-core-openapi-generated.yml
- filename: cheapestinference-com-guides-openapi-generated.yml
  format: yaml
  label: cheapestinference-com guides API
  slug: guides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cheapestinference-com/openapi/_ae-authored/cheapestinference-com-guides-openapi-generated.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — email, subscription status, and API key metadata (name, plan, rate limits).
  - category: financial
    text: Payment information — card payments are processed by Stripe; USDC payments are verified on-chain (Base L2).
  - category: behavioral
    text: Usage metadata — request counts, token counts, and cost per key.
  deletion:
    route: email privacy@cheapestinference.com
    text: To exercise these rights, email privacy@cheapestinference.com from the address associated with your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing and analytics
    text: Usage metadata — retained for billing and analytics; aggregated and anonymized after 90 days.
  retention:
  - period: 30 days
    scope: Account data
    text: Account data — retained while your account is active; deleted within 30 days of account deletion.
  - period: 90 days
    scope: Usage metadata
    text: Usage metadata — retained for billing and analytics; aggregated and anonymized after 90 days.
  - period: null
    scope: Inference data (prompts/completions)
    text: Inference data (prompts/completions) — not retained; processed in memory only.
  rights:
  - right: access
    text: EU/EEA users may request access to, export of, or deletion of their personal data.
  - right: deletion
    text: EU/EEA users may request access to, export of, or deletion of their personal data.
  - right: export
    text: EU/EEA users may request access to, export of, or deletion of their personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cheapestinference-com
provenance_date: '2026-11-09'
provider_name: cheapestinference-com
provider_slug: cheapestinference-com
slug: cheapestinference-com-privacy-policy
source_date: '2026-11-09'
source_filename: cheapestinference-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cheapestinference.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cheapestinference-com\naid: cheapestinference-com\nurl: https://cheapestinference.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — email, subscription status, and API key metadata (name, plan, rate limits).\n- category: financial\n  text: Payment information — card payments are processed by Stripe; USDC payments are verified on-chain (Base L2).\n- category: behavioral\n  text: Usage metadata — request counts, token counts, and cost per key.\npurposes:\n- purpose: billing and analytics\n  text: Usage metadata —\
  \ retained for billing and analytics; aggregated and anonymized after 90 days.\nretention:\n- scope: Account data\n  period: 30 days\n  text: Account data — retained while your account is active; deleted within 30 days of account deletion.\n- scope: Usage metadata\n  period: 90 days\n  text: Usage metadata — retained for billing and analytics; aggregated and anonymized after 90 days.\n- scope: Inference data (prompts/completions)\n  period: null\n  text: Inference data (prompts/completions) — not retained; processed in memory only.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@cheapestinference.com\n  text: To exercise these rights, email privacy@cheapestinference.com from the address associated with your account.\nrights:\n- right: access\n  text: EU/EEA users may request access to, export of, or deletion of their personal data.\n- right: deletion\n  text: EU/EEA users may\
  \ request access to, export of, or deletion of their personal data.\n- right: export\n  text: EU/EEA users may request access to, export of, or deletion of their personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cheapestinference-com/privacy/cheapestinference-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from cheapestinference-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Inference
- LLM
- Flat-rate
- Software-as-a-Service
---
