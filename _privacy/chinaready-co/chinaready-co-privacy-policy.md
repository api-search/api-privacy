---
api_specs:
- filename: chinaready-co-assistant-api-openapi.yml
  format: yaml
  label: Chinaready Assistant API
  slug: chinaready-co-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-assistant-api-openapi.yml
- filename: chinaready-co-contact-api-openapi.yml
  format: yaml
  label: Chinaready Contact API
  slug: chinaready-co-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-contact-api-openapi.yml
- filename: chinaready-co-intake-api-openapi.yml
  format: yaml
  label: Chinaready Intake API
  slug: chinaready-co-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-intake-api-openapi.yml
- filename: chinaready-co-search-api-openapi.yml
  format: yaml
  label: Chinaready Search API
  slug: chinaready-co-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chinaready-co/openapi/chinaready-co-search-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact details and product information you submit through forms
  - category: behavioral
    text: basic analytics on site usage
  - category: identifying
    text: Name and email are collected only if you send the assistant contact form
  - category: identifying
    text: the app sends your email address, the one-time code, and your display name to wb.chinaready.co over HTTPS
  deletion:
    route: email request
    text: To close your Workbench account or have your data deleted, contact [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond to inquiries and deliver services
    text: To respond to your inquiry, run your assessment, and deliver contracted services.
  - purpose: site assistant answers
    text: Questions and retrieved page excerpts are sent to DeepSeek to produce an answer.
  residency:
  - region: China
    text: Diagnostic execution data is processed on launchready.cn under the same policy.
  - region: unstated
    text: Form data is processed on Cloudflare infrastructure.
  retention:
  - period: null
    scope: site assistant transcript
    text: We do not keep a chat account or store the transcript in our case database unless you send the form.
  rights:
  - right: access, correction, or deletion
    text: Request access, correction, or deletion of your data at any time via [email protected] .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your data with third parties for marketing.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chinaready
provenance_date: '2026-11-09'
provider_name: Chinaready
provider_slug: chinaready-co
slug: chinaready-co-privacy-policy
source_date: '2026-11-09'
source_filename: chinaready-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chinaready.co/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chinaready\naid: chinaready-co\nurl: https://chinaready.co/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact details and product information you submit through forms\n- category: behavioral\n  text: basic analytics on site usage\n- category: identifying\n  text: Name and email are collected only if you send the assistant contact form\n- category: identifying\n  text: the app sends your email address, the one-time code, and your display name to wb.chinaready.co over HTTPS\npurposes:\n- purpose: respond to inquiries and deliver\
  \ services\n  text: To respond to your inquiry, run your assessment, and deliver contracted services.\n- purpose: site assistant answers\n  text: Questions and retrieved page excerpts are sent to DeepSeek to produce an answer.\nretention:\n- scope: site assistant transcript\n  period: null\n  text: We do not keep a chat account or store the transcript in our case database unless you send the form.\nresidency:\n- region: China\n  text: Diagnostic execution data is processed on launchready.cn under the same policy.\n- region: unstated\n  text: Form data is processed on Cloudflare infrastructure.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: To close your Workbench account or have your data deleted, contact [email protected] .\nrights:\n- right: access, correction, or deletion\n  text: Request access, correction, or deletion of your data at any time via [email protected] .\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell or share your data with third parties for marketing.\n"
source_yaml_url: https://artifacts.apis.io/chinaready-co/privacy/chinaready-co-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from Chinaready's own page on 2026-11-09.
synthetic: false
tags:
- Company
- China
- Market Entry
- Content Delivery
- Hosting
- Compliance
- Mobile App Distribution
- Network Diagnostics
- MCP
---
