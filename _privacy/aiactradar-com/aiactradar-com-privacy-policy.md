---
api_specs:
- filename: aiactradar-com-events-api-openapi.yml
  format: yaml
  label: AI Act Radar Events API
  slug: aiactradar-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-events-api-openapi.yml
- filename: aiactradar-com-health-api-openapi.yml
  format: yaml
  label: AI Act Radar Health API
  slug: aiactradar-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-health-api-openapi.yml
- filename: aiactradar-com-sources-api-openapi.yml
  format: yaml
  label: AI Act Radar Sources API
  slug: aiactradar-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-sources-api-openapi.yml
- filename: aiactradar-com-topics-api-openapi.yml
  format: yaml
  label: AI Act Radar Topics API
  slug: aiactradar-com-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiactradar-com/openapi/aiactradar-com-topics-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: email, company name, encrypted API keys.'
  - category: financial
    text: 'Billing data: processed by Stripe Inc.'
  - category: device
    text: 'Server logs: IP, user agent, request path.'
  - category: other
    text: 'Webhook URLs: stored to deliver events to your endpoint.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver events to endpoint
    text: 'Webhook URLs: stored to deliver events to your endpoint.'
  - purpose: LLM enrichment of public regulatory content
    text: Anthropic — LLM enrichment of public regulatory content only; no customer data is sent to Anthropic.
  retention:
  - period: 30 days
    scope: server logs
    text: 'Server logs: IP, user agent, request path. Retained 30 days.'
  rights:
  - right: access
    text: Access, rectification, erasure, restriction, portability, objection.
  - right: objection
    text: Access, rectification, erasure, restriction, portability, objection.
  role:
    text: Controller ligea GmbH, Hardtstr. 37a, 76185 Karlsruhe, Germany.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Processors Cloudflare — hosting, edge compute, WAF. Stripe — payment processing. Resend / Postmark — transactional email. Anthropic — LLM enrichment of public regulatory content only; no customer data is sent to Anthropic.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Act Radar
provenance_date: '2026-11-09'
provider_name: AI Act Radar
provider_slug: aiactradar-com
slug: aiactradar-com-privacy-policy
source_date: '2026-11-09'
source_filename: aiactradar-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aiactradar.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Act Radar\naid: aiactradar-com\nurl: https://aiactradar.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller ligea GmbH, Hardtstr. 37a, 76185 Karlsruhe, Germany.\ndata_categories:\n- category: contact\n  text: 'Account data: email, company name, encrypted API keys.'\n- category: financial\n  text: 'Billing data: processed by Stripe Inc.'\n- category: device\n  text: 'Server logs: IP, user agent, request path.'\n- category: other\n  text: 'Webhook URLs: stored to deliver events to your endpoint.'\npurposes:\n- purpose: deliver events to endpoint\n  text: 'Webhook URLs:\
  \ stored to deliver events to your endpoint.'\n- purpose: LLM enrichment of public regulatory content\n  text: Anthropic — LLM enrichment of public regulatory content only; no customer data is sent to Anthropic.\nretention:\n- scope: server logs\n  period: 30 days\n  text: 'Server logs: IP, user agent, request path. Retained 30 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors Cloudflare — hosting, edge compute, WAF. Stripe — payment processing. Resend / Postmark — transactional\n    email. Anthropic — LLM enrichment of public regulatory content only; no customer data is sent to Anthropic.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: Access, rectification, erasure, restriction, portability, objection.\n- right: objection\n  text: Access, rectification, erasure, restriction, portability, objection.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiactradar-com/privacy/aiactradar-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- rights
summary_line: 11 quoted statements, read from AI Act Radar's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Regulations
- EU
- Webhook
- Compliance
---
