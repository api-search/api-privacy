---
api_specs:
- filename: bassethound-ai-openapi-generated.yml
  format: yaml
  label: Bassethound API
  slug: bassethound-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bassethound-ai/openapi/_ae-authored/bassethound-ai-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: your account identity, and the IP the request came from
  - category: device
    text: Standard server logs (IP address, timestamp, and the requested operation)
  - category: other
    text: Authentication token. If you connect with a Bearer token, we process a one-way hash of it to identify your plan and apply your rate limit.
  deletion:
    route: contact email privacy@bassethound.ai
    text: Contact us to ask what request metadata we hold about your IP or token, or to request deletion, at the address below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate service
    text: Operate the service and return your dossier.
  - purpose: rate limiting and abuse prevention
    text: Enforce rate limits and prevent abuse.
  - purpose: reliability and detection quality
    text: Maintain and improve reliability and detection quality.
  retention:
  - period: up to 24 hours
    scope: result cache
    text: dossiers are cached for a short, time-limited window (up to 24 hours) and then evicted.
  - period: up to 30 days
    scope: server logs
    text: 'Server logs: retained for up to 30 days for security and operations, then deleted.'
  - period: indefinitely
    scope: analysis results
    text: 'Analysis results: retained indefinitely, including your account identity and the request IP stored alongside the dossier.'
  rights:
  - right: deletion request
    text: or to request deletion, at the address below
  - right: access to request metadata
    text: Contact us to ask what request metadata we hold about your IP or token
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or rent data to third parties.
  subprocessors:
    text: Amazon Web Services for cloud infrastructure and hosting.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bassethound
provenance_date: '2026-11-09'
provider_name: Bassethound
provider_slug: bassethound-ai
slug: bassethound-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bassethound-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bassethound.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bassethound\naid: bassethound-ai\nurl: https://bassethound.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your account identity, and the IP the request came from\n- category: device\n  text: Standard server logs (IP address, timestamp, and the requested operation)\n- category: other\n  text: Authentication token. If you connect with a Bearer token, we process a one-way hash of it to identify your\n    plan and apply your rate limit.\npurposes:\n- purpose: operate service\n  text: Operate the service and return your dossier.\n\
  - purpose: rate limiting and abuse prevention\n  text: Enforce rate limits and prevent abuse.\n- purpose: reliability and detection quality\n  text: Maintain and improve reliability and detection quality.\nretention:\n- scope: result cache\n  period: up to 24 hours\n  text: dossiers are cached for a short, time-limited window (up to 24 hours) and then evicted.\n- scope: server logs\n  period: up to 30 days\n  text: 'Server logs: retained for up to 30 days for security and operations, then deleted.'\n- scope: analysis results\n  period: indefinitely\n  text: 'Analysis results: retained indefinitely, including your account identity and the request IP stored alongside\n    the dossier.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Amazon Web Services for cloud infrastructure and hosting.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact email privacy@bassethound.ai\n  text: Contact us to ask what request metadata we hold about your IP\
  \ or token, or to request deletion, at the address\n    below.\nrights:\n- right: deletion request\n  text: or to request deletion, at the address below\n- right: access to request metadata\n  text: Contact us to ask what request metadata we hold about your IP or token\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or rent data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/bassethound-ai/privacy/bassethound-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Bassethound's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Intelligence
- MCP
- Company Intelligence
---
