---
api_specs:
- filename: archome-ai-openapi-generated.yml
  format: yaml
  label: Archome AI API
  slug: archome-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archome-ai/openapi/_ae-authored/archome-ai-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account info: Full name, email address, password (stored hashed).'
  - category: behavioral
    text: 'Usage data: Images you generate, projects, credit transactions, render history.'
  - category: financial
    text: 'Payment data: Payment processing happens through Dodo Payments infrastructure.'
  - category: device
    text: 'Technical data: IP address, browser type, operating system, visit date and time, log records.'
  - category: other
    text: content you submit (photos, sketches, text instructions)
  deletion:
    route: Settings or email to info@archome.store
    text: download your data or delete your account at any time in Settings
  dpa:
    available: true
    text: These providers operate under data processing agreements.
    url: null
  purposes:
  - purpose: account, service, payments, security and improvement
    text: We use collected data to create and manage your account, deliver the AI rendering service, complete payment transactions, secure the platform (bot and fraud detection), fulfill legal obligations, and improve service quality.
  - purpose: no AI training on uploads
    text: We do not use your uploads to train AI models.
  residency:
  - region: outside Türkiye and EU/EEA
    text: Several of these providers are located, or process data, outside Türkiye and the EU/EEA (for example in the United States).
  retention:
  - period: as long as your account is active
    scope: account data
    text: We retain your account data as long as your account is active.
  - period: within 30 days
    scope: deleted account data
    text: When you delete your account, your personal data, uploads and renders are deleted or anonymized within 30 days
  - period: 30 days
    scope: gallery items in trash
    text: items you delete from your gallery are removed after 30 days in trash
  - period: up to 90 days
    scope: hashed email
    text: a hashed (non-readable) form of your email address may be kept for up to 90 days to prevent abuse
  - period: 10 years
    scope: payment records
    text: payment records are retained as required by law (10 years under the Turkish Commercial Code)
  rights:
  - right: access and portability
    text: access your data and receive a copy, including in a structured, machine-readable format (portability)
  - right: correction
    text: request correction of incomplete or incorrect data
  - right: deletion
    text: request deletion or destruction
  - right: restriction
    text: request restriction of processing
  - right: objection
    text: object to processing based on legitimate interests and to results obtained through automated analysis
  - right: withdraw consent
    text: withdraw your consent at any time, without affecting earlier processing
  - right: complaint
    text: You may also lodge a complaint with a supervisory authority
  role:
    text: This platform is operated by Archome AI.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Supabase (database and authentication); Vercel (hosting and Vercel Analytics); Cloudflare R2 (file storage for uploads and renders)
    url: null
  transfers:
  - mechanism: SCC
    text: For these transfers we rely on Standard Contractual Clauses or equivalent safeguards
  - mechanism: other
    text: on the standard contracts required by KVKK Article 9
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Archome AI
provenance_date: '2026-11-09'
provider_name: Archome AI
provider_slug: archome-ai
slug: archome-ai-privacy-policy
source_date: '2026-11-09'
source_filename: archome-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://archome.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Archome AI\naid: archome-ai\nurl: https://archome.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This platform is operated by Archome AI.\ndata_categories:\n- category: identifying\n  text: 'Account info: Full name, email address, password (stored hashed).'\n- category: behavioral\n  text: 'Usage data: Images you generate, projects, credit transactions, render history.'\n- category: financial\n  text: 'Payment data: Payment processing happens through Dodo Payments infrastructure.'\n- category: device\n  text: 'Technical data: IP address, browser type, operating system, visit\
  \ date and time, log records.'\n- category: other\n  text: content you submit (photos, sketches, text instructions)\npurposes:\n- purpose: account, service, payments, security and improvement\n  text: We use collected data to create and manage your account, deliver the AI rendering service, complete payment\n    transactions, secure the platform (bot and fraud detection), fulfill legal obligations, and improve service\n    quality.\n- purpose: no AI training on uploads\n  text: We do not use your uploads to train AI models.\nretention:\n- scope: account data\n  period: as long as your account is active\n  text: We retain your account data as long as your account is active.\n- scope: deleted account data\n  period: within 30 days\n  text: When you delete your account, your personal data, uploads and renders are deleted or anonymized within 30\n    days\n- scope: gallery items in trash\n  period: 30 days\n  text: items you delete from your gallery are removed after 30 days in trash\n- scope:\
  \ hashed email\n  period: up to 90 days\n  text: a hashed (non-readable) form of your email address may be kept for up to 90 days to prevent abuse\n- scope: payment records\n  period: 10 years\n  text: payment records are retained as required by law (10 years under the Turkish Commercial Code)\nresidency:\n- region: outside Türkiye and EU/EEA\n  text: Several of these providers are located, or process data, outside Türkiye and the EU/EEA (for example in\n    the United States).\ntransfers:\n- mechanism: SCC\n  text: For these transfers we rely on Standard Contractual Clauses or equivalent safeguards\n- mechanism: other\n  text: on the standard contracts required by KVKK Article 9\nsubprocessors:\n  url: null\n  text: Supabase (database and authentication); Vercel (hosting and Vercel Analytics); Cloudflare R2 (file storage\n    for uploads and renders)\ndpa:\n  available: true\n  url: null\n  text: These providers operate under data processing agreements.\ndeletion:\n  route: Settings or\
  \ email to info@archome.store\n  text: download your data or delete your account at any time in Settings\nrights:\n- right: access and portability\n  text: access your data and receive a copy, including in a structured, machine-readable format (portability)\n- right: correction\n  text: request correction of incomplete or incorrect data\n- right: deletion\n  text: request deletion or destruction\n- right: restriction\n  text: request restriction of processing\n- right: objection\n  text: object to processing based on legitimate interests and to results obtained through automated analysis\n- right: withdraw consent\n  text: withdraw your consent at any time, without affecting earlier processing\n- right: complaint\n  text: You may also lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/archome-ai/privacy/archome-ai-privacy-policy.yml
stated_fields:
- role
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
summary_line: 27 quoted statements, read from Archome AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Virtual Staging
- Architectural Rendering
- Design Tools
- Software-as-a-Service
---
