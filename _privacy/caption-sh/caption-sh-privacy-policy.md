---
api_specs:
- filename: caption-sh-antigravity-md-api-openapi.yml
  format: yaml
  label: caption-sh Antigravity.md API
  slug: caption-sh-antigravity-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-antigravity-md-api-openapi.yml
- filename: caption-sh-chatgpt-md-api-openapi.yml
  format: yaml
  label: caption-sh Chatgpt.md API
  slug: caption-sh-chatgpt-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-chatgpt-md-api-openapi.yml
- filename: caption-sh-claude-md-api-openapi.yml
  format: yaml
  label: caption-sh Claude.md API
  slug: caption-sh-claude-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-claude-md-api-openapi.yml
- filename: caption-sh-codex-md-api-openapi.yml
  format: yaml
  label: caption-sh Codex.md API
  slug: caption-sh-codex-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-codex-md-api-openapi.yml
- filename: caption-sh-cursor-md-api-openapi.yml
  format: yaml
  label: caption-sh Cursor.md API
  slug: caption-sh-cursor-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-cursor-md-api-openapi.yml
- filename: caption-sh-index-md-api-openapi.yml
  format: yaml
  label: caption-sh Index.md API
  slug: caption-sh-index-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-index-md-api-openapi.yml
- filename: caption-sh-install-sh-api-openapi.yml
  format: yaml
  label: caption-sh Install.sh API
  slug: caption-sh-install-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-install-sh-api-openapi.yml
- filename: caption-sh-mcp-api-openapi.yml
  format: yaml
  label: caption-sh MCP API
  slug: caption-sh-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-mcp-api-openapi.yml
- filename: caption-sh-pricing-md-api-openapi.yml
  format: yaml
  label: caption-sh Pricing.md API
  slug: caption-sh-pricing-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-pricing-md-api-openapi.yml
- filename: caption-sh-use-lazyweb-md-api-openapi.yml
  format: yaml
  label: caption-sh Use Lazyweb.md API
  slug: caption-sh-use-lazyweb-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-use-lazyweb-md-api-openapi.yml
- filename: caption-sh-well-known-api-openapi.yml
  format: yaml
  label: caption-sh .well Known API
  slug: caption-sh-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caption-sh/openapi/caption-sh-well-known-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: your email address and sign-in identifiers'
  - category: financial
    text: 'Billing information: payments are processed by Stripe.'
  - category: other
    text: 'Your content: videos you upload for captioning'
  - category: device
    text: IP address, browser and device type, and request and error logs
  - category: communication
    text: 'Communications: messages you send us, such as support emails.'
  deletion:
    route: delete account
    text: When you delete your account, we delete or anonymize your personal information within a reasonable time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, maintain, and improve the Service
    text: provide, maintain, and improve the Service
  - purpose: transcribe and render videos
    text: transcribe and render your videos
  - purpose: process payments
    text: process payments and manage your credit balance
  - purpose: prevent fraud and abuse
    text: prevent fraud, abuse, and security incidents
  retention:
  - period: 24 hours after a job finishes
    scope: Rendered results
    text: Rendered results are deleted 24 hours after a job finishes
  - period: 30 days
    scope: Uploaded source videos
    text: uploaded source videos are deleted automatically within 30 days
  - period: null
    scope: Account data on deletion
    text: When you delete your account, we delete or anonymize your personal information within a reasonable time
  rights:
  - right: access, correction, deletion, portability
    text: to access, correct, delete, or receive a copy of your personal information
  - right: object or restrict processing
    text: to object to or restrict certain processing
  - right: opt out of sale or sharing
    text: to opt out of the sale or sharing of personal information
  - right: complaint
    text: You may also complain to your local data protection authority.
  role:
    text: Canna Holdings is the controller of the personal information described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information
  subprocessors:
    text: Clerk (authentication), Neon (database hosting), Stripe (payments), Cloudflare (hosting, storage, queues, and video rendering), Deepgram (speech-to-text, with model training on customer audio disabled), and our transactional email provider.
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses
  - mechanism: other
    text: our providers' certifications to protect information transferred from the EEA, UK, or Switzerland
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: caption-sh
provenance_date: '2026-11-09'
provider_name: caption-sh
provider_slug: caption-sh
slug: caption-sh-privacy-policy
source_date: '2026-11-09'
source_filename: caption-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://caption.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: caption-sh\naid: caption-sh\nurl: https://caption.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Canna Holdings is the controller of the personal information described here.\ndata_categories:\n- category: identifying\n  text: 'Account information: your email address and sign-in identifiers'\n- category: financial\n  text: 'Billing information: payments are processed by Stripe.'\n- category: other\n  text: 'Your content: videos you upload for captioning'\n- category: device\n  text: IP address, browser and device type, and request and error logs\n- category: communication\n  text:\
  \ 'Communications: messages you send us, such as support emails.'\npurposes:\n- purpose: provide, maintain, and improve the Service\n  text: provide, maintain, and improve the Service\n- purpose: transcribe and render videos\n  text: transcribe and render your videos\n- purpose: process payments\n  text: process payments and manage your credit balance\n- purpose: prevent fraud and abuse\n  text: prevent fraud, abuse, and security incidents\nretention:\n- scope: Rendered results\n  period: 24 hours after a job finishes\n  text: Rendered results are deleted 24 hours after a job finishes\n- scope: Uploaded source videos\n  period: 30 days\n  text: uploaded source videos are deleted automatically within 30 days\n- scope: Account data on deletion\n  period: null\n  text: When you delete your account, we delete or anonymize your personal information within a reasonable time\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses\n- mechanism:\
  \ other\n  text: our providers' certifications to protect information transferred from the EEA, UK, or Switzerland\nsubprocessors:\n  url: null\n  text: Clerk (authentication), Neon (database hosting), Stripe (payments), Cloudflare (hosting, storage, queues,\n    and video rendering), Deepgram (speech-to-text, with model training on customer audio disabled), and our transactional\n    email provider.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account\n  text: When you delete your account, we delete or anonymize your personal information within a reasonable time\nrights:\n- right: access, correction, deletion, portability\n  text: to access, correct, delete, or receive a copy of your personal information\n- right: object or restrict processing\n  text: to object to or restrict certain processing\n- right: opt out of sale or sharing\n  text: to opt out of the sale or sharing of personal information\n- right: complaint\n  text: You may also complain to\
  \ your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information\n"
source_yaml_url: https://artifacts.apis.io/caption-sh/privacy/caption-sh-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from caption-sh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Captions
- Automation
---
