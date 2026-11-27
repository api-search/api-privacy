---
api_specs:
- filename: rendry-io-accounts-api-openapi.yml
  format: yaml
  label: rendry-io Accounts API
  slug: rendry-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-accounts-api-openapi.yml
- filename: rendry-io-assets-api-openapi.yml
  format: yaml
  label: rendry-io Assets API
  slug: rendry-io-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-assets-api-openapi.yml
- filename: rendry-io-batch-tasks-api-openapi.yml
  format: yaml
  label: rendry-io Batch Tasks API
  slug: rendry-io-batch-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-batch-tasks-api-openapi.yml
- filename: rendry-io-capabilities-api-openapi.yml
  format: yaml
  label: rendry-io Capabilities API
  slug: rendry-io-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-capabilities-api-openapi.yml
- filename: rendry-io-components-api-openapi.yml
  format: yaml
  label: rendry-io Components API
  slug: rendry-io-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-components-api-openapi.yml
- filename: rendry-io-design-guide-api-openapi.yml
  format: yaml
  label: rendry-io Design Guide API
  slug: rendry-io-design-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-design-guide-api-openapi.yml
- filename: rendry-io-documents-api-openapi.yml
  format: yaml
  label: rendry-io Documents API
  slug: rendry-io-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-documents-api-openapi.yml
- filename: rendry-io-embed-api-openapi.yml
  format: yaml
  label: rendry-io Embed API
  slug: rendry-io-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-embed-api-openapi.yml
- filename: rendry-io-files-api-openapi.yml
  format: yaml
  label: rendry-io Files API
  slug: rendry-io-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-files-api-openapi.yml
- filename: rendry-io-generations-api-openapi.yml
  format: yaml
  label: rendry-io Generations API
  slug: rendry-io-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-generations-api-openapi.yml
- filename: rendry-io-images-api-openapi.yml
  format: yaml
  label: rendry-io Images API
  slug: rendry-io-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-images-api-openapi.yml
- filename: rendry-io-mcp-api-openapi.yml
  format: yaml
  label: rendry-io MCP API
  slug: rendry-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-mcp-api-openapi.yml
- filename: rendry-io-presets-api-openapi.yml
  format: yaml
  label: rendry-io Presets API
  slug: rendry-io-presets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-presets-api-openapi.yml
- filename: rendry-io-principal-api-openapi.yml
  format: yaml
  label: rendry-io Principal API
  slug: rendry-io-principal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-principal-api-openapi.yml
- filename: rendry-io-render-api-openapi.yml
  format: yaml
  label: rendry-io Render API
  slug: rendry-io-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-render-api-openapi.yml
- filename: rendry-io-rendering-api-openapi.yml
  format: yaml
  label: rendry-io Rendering API
  slug: rendry-io-rendering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-rendering-api-openapi.yml
- filename: rendry-io-templates-api-openapi.yml
  format: yaml
  label: rendry-io Templates API
  slug: rendry-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-templates-api-openapi.yml
- filename: rendry-io-u-api-openapi.yml
  format: yaml
  label: rendry-io U API
  slug: rendry-io-u-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-u-api-openapi.yml
- filename: rendry-io-user-api-openapi.yml
  format: yaml
  label: rendry-io User API
  slug: rendry-io-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendry-io/openapi/rendry-io-user-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect your email address, hashed password, uploaded assets, and usage analytics (render counts, API calls).
  - category: behavioral
    text: those tags and the page the link opened are recorded with your account when you sign up, so that we learn which campaigns bring people to Rendry
  deletion:
    route: Settings, Account tab, block at the bottom
    text: 'You can delete the account yourself: sign in, open Settings, the Account tab, and the block at the bottom.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation, billing, and support
    text: Your personal data is processed for service operation, billing, and support.
  - purpose: campaign attribution
    text: so that we learn which campaigns bring people to Rendry
  - purpose: AI image generation via OpenRouter
    text: OpenRouter, Inc. (USA) — making AI images — only when you run this operation.
  residency:
  - region: Netherlands (Amsterdam)
    text: Data is stored on servers operated for Rendry in the Netherlands (Amsterdam).
  retention:
  - period: 30 days
    scope: account data
    text: account data is deleted 30 days after you delete the account
  - period: 30 days
    scope: templates, uploaded files, documents and render results
    text: your templates, uploaded files, documents and render results are deleted 30 days later
  - period: 365 days
    scope: authenticated rendered files
    text: Authenticated rendered files, including test-key files, expire 365 days after completion.
  - period: 72 hours
    scope: guest files
    text: Guest files expire 72 hours after batch creation.
  - period: as long as accounting law requires
    scope: payment and credit records
    text: Payment and credit records are kept for as long as accounting law requires, without your email address or name.
  rights:
  - right: access or correction
    text: To get a copy of your data or correct it — or to delete an account you can no longer sign in to — write to us through the contact form on the home page.
  - right: complaint to data protection authority
    text: you may also complain to your local data protection authority.
  - right: withdraw consent
    text: Where consent is the basis, you may withdraw it at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No data is sold to third parties.
  subprocessors:
    text: We send data only to these recipients, only for the stated purpose and only what is listed
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: rendry-io
provenance_date: '2026-11-10'
provider_name: rendry-io
provider_slug: rendry-io
slug: rendry-io-privacy-policy
source_date: '2026-11-10'
source_filename: rendry-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rendry.io/legal#privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rendry-io\naid: rendry-io\nurl: https://rendry.io/legal#privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect your email address, hashed password, uploaded assets, and usage analytics (render counts, API\n    calls).\n- category: behavioral\n  text: those tags and the page the link opened are recorded with your account when you sign up, so that we learn\n    which campaigns bring people to Rendry\npurposes:\n- purpose: service operation, billing, and support\n  text: Your personal data is processed for service operation, billing,\
  \ and support.\n- purpose: campaign attribution\n  text: so that we learn which campaigns bring people to Rendry\n- purpose: AI image generation via OpenRouter\n  text: OpenRouter, Inc. (USA) — making AI images — only when you run this operation.\nretention:\n- scope: account data\n  period: 30 days\n  text: account data is deleted 30 days after you delete the account\n- scope: templates, uploaded files, documents and render results\n  period: 30 days\n  text: your templates, uploaded files, documents and render results are deleted 30 days later\n- scope: authenticated rendered files\n  period: 365 days\n  text: Authenticated rendered files, including test-key files, expire 365 days after completion.\n- scope: guest files\n  period: 72 hours\n  text: Guest files expire 72 hours after batch creation.\n- scope: payment and credit records\n  period: as long as accounting law requires\n  text: Payment and credit records are kept for as long as accounting law requires, without your email address\
  \ or\n    name.\nresidency:\n- region: Netherlands (Amsterdam)\n  text: Data is stored on servers operated for Rendry in the Netherlands (Amsterdam).\ntransfers: []\nsubprocessors:\n  url: null\n  text: We send data only to these recipients, only for the stated purpose and only what is listed\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings, Account tab, block at the bottom\n  text: 'You can delete the account yourself: sign in, open Settings, the Account tab, and the block at the bottom.'\nrights:\n- right: access or correction\n  text: To get a copy of your data or correct it — or to delete an account you can no longer sign in to — write\n    to us through the contact form on the home page.\n- right: complaint to data protection authority\n  text: you may also complain to your local data protection authority.\n- right: withdraw consent\n  text: Where consent is the basis, you may withdraw it at any time.\nsale_or_sharing:\n  stance: prohibited\n  text:\
  \ No data is sold to third parties.\n"
source_yaml_url: https://artifacts.apis.io/rendry-io/privacy/rendry-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from rendry-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Image Rendering
- PDF Generation
- Template Engine
- AI Integration
---
