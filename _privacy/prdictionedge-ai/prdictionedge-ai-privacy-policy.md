---
api_specs:
- filename: prdictionedge-ai-certification-attempts-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge Certification Attempts API
  slug: prdictionedge-ai-certification-attempts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-certification-attempts-api-openapi.yml
- filename: prdictionedge-ai-certification-handoffs-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge Certification Handoffs API
  slug: prdictionedge-ai-certification-handoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-certification-handoffs-api-openapi.yml
- filename: prdictionedge-ai-certification-profiles-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge Certification Profiles API
  slug: prdictionedge-ai-certification-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-certification-profiles-api-openapi.yml
- filename: prdictionedge-ai-certification-requirements-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge Certification Requirements API
  slug: prdictionedge-ai-certification-requirements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-certification-requirements-api-openapi.yml
- filename: prdictionedge-ai-certifications-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge Certifications API
  slug: prdictionedge-ai-certifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-certifications-api-openapi.yml
- filename: prdictionedge-ai-evidence-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge Evidence API
  slug: prdictionedge-ai-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-evidence-api-openapi.yml
- filename: prdictionedge-ai-well-known-api-openapi.yml
  format: yaml
  label: AUX by PrdictionEdge .well Known API
  slug: prdictionedge-ai-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prdictionedge-ai/openapi/prdictionedge-ai-well-known-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect your name, email address, company name, role, and subscription status to provide GovEdge and RegWatch.
  - category: professional
    text: For GovEdge, we may also collect NAICS codes, CAGE code, and clearance level information you choose to provide to improve opportunity matching.
  - category: behavioral
    text: For RegWatch, we may collect agency and regulation domain preferences you configure.
  deletion:
    route: Request by contacting us
    text: You may request deletion at any time by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and matching
    text: We use your information to provide the Services, match you to relevant opportunities or regulatory notices, process billing, send notifications you opt into, and improve the platform.
  retention:
  - period: null
    scope: Active account data
    text: We retain your account data while your subscription is active.
  - period: a reasonable period
    scope: Post-cancellation data
    text: Upon cancellation, we retain data for a reasonable period to support billing history and reactivation, after which it may be deleted.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: We use Supabase for authentication and database hosting, Stripe for payment processing, Anthropic for AI-assisted classification and scoring, Resend for transactional email, and Vercel for application hosting.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AUX by PrdictionEdge
provenance_date: '2026-11-10'
provider_name: AUX by PrdictionEdge
provider_slug: prdictionedge-ai
slug: prdictionedge-ai-privacy-policy
source_date: '2026-11-10'
source_filename: prdictionedge-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aux.prdictionedge.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AUX by PrdictionEdge\naid: prdictionedge-ai\nurl: https://aux.prdictionedge.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect your name, email address, company name, role, and subscription status to provide GovEdge and\n    RegWatch.\n- category: professional\n  text: For GovEdge, we may also collect NAICS codes, CAGE code, and clearance level information you choose to provide\n    to improve opportunity matching.\n- category: behavioral\n  text: For RegWatch, we may collect agency and regulation domain preferences you\
  \ configure.\npurposes:\n- purpose: Provide services and matching\n  text: We use your information to provide the Services, match you to relevant opportunities or regulatory notices,\n    process billing, send notifications you opt into, and improve the platform.\nretention:\n- scope: Active account data\n  period: null\n  text: We retain your account data while your subscription is active.\n- scope: Post-cancellation data\n  period: a reasonable period\n  text: Upon cancellation, we retain data for a reasonable period to support billing history and reactivation, after\n    which it may be deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use Supabase for authentication and database hosting, Stripe for payment processing, Anthropic for AI-assisted\n    classification and scoring, Resend for transactional email, and Vercel for application hosting.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request by contacting us\n  text: You\
  \ may request deletion at any time by contacting us.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/prdictionedge-ai/privacy/prdictionedge-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 9 quoted statements, read from AUX by PrdictionEdge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Counterparty Verification
- Sanctions Screening
- Legal Entity Identifier
- KYB
- Agent Infrastructure
- Trust and Safety
- Signed Receipts
- Agentic Payments
- A2A
- Agent-Native
---
