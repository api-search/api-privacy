---
api_specs:
- filename: speko-agents-api-openapi.yml
  format: yaml
  label: Speko Agents API
  slug: speko-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-agents-api-openapi.yml
- filename: speko-providers-api-openapi.yml
  format: yaml
  label: Speko Providers API
  slug: speko-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-providers-api-openapi.yml
- filename: speko-telephony-api-openapi.yml
  format: yaml
  label: Speko Telephony API
  slug: speko-telephony-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-telephony-api-openapi.yml
- filename: speko-voice-api-openapi.yml
  format: yaml
  label: Speko Voice API
  slug: speko-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/speko/openapi/speko-voice-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, organization, authentication identifiers, role, workspace membership, and security settings.
  - category: communication
    text: Audio, transcripts, generated responses, tool inputs and outputs, session recordings, phone numbers, request metadata, latency, routing decisions, logs, and usage data generated when you or your users use Speko.
  - category: financial
    text: Billing contact details, subscription status, usage credits, invoices, and payment processing records handled by our payment providers.
  - category: device
    text: IP address, browser and device metadata, pages visited, referral source, diagnostics, cookies or similar technologies, support messages, and feedback.
  - category: contact
    text: Information from third-party services you connect, such as account identifiers, access tokens, calendars, events, availability, messages, files, or other data exposed by the scopes you approve.
  deletion:
    route: Contact Speko to request account or data deletion
    text: You may request deletion of your account or certain data by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide platform and support
    text: provide the Speko platform, APIs, SDKs, demos, integrations, and support
  - purpose: Route AI requests to providers
    text: route voice and AI requests to selected providers, perform failover, return transcripts, play generated audio, execute configured tools, and show operational logs
  - purpose: Billing and abuse prevention
    text: measure usage, manage billing, enforce limits, detect abuse, and prevent fraud
  - purpose: Improve services
    text: debug, maintain, secure, and improve Speko services
  residency:
  - region: United States
    text: Speko is operated from the United States and may process information in the United States and other countries where we or our subprocessors operate.
  retention:
  - period: 30 days
    scope: Session recordings
    text: Session recordings are generally retained for 30 days after a session ends, then deleted by lifecycle policy
  - period: null
    scope: General information
    text: We retain information for as long as needed to provide Speko, comply with legal obligations, resolve disputes, maintain security, and enforce agreements.
  rights:
  - right: Access, correct, delete, export, object
    text: you may have rights to access, correct, delete, export, or object to certain processing of your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: Customers are responsible for reviewing the third-party providers they configure, including any provider-specific privacy, security, retention, and compliance terms.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Speko
provenance_date: '2026-11-10'
provider_name: Speko
provider_slug: speko
slug: speko-privacy-policy
source_date: '2026-11-10'
source_filename: speko-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://speko.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Speko\naid: speko\nurl: https://speko.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, organization, authentication identifiers, role, workspace membership, and security\n    settings.\n- category: communication\n  text: Audio, transcripts, generated responses, tool inputs and outputs, session recordings, phone numbers, request\n    metadata, latency, routing decisions, logs, and usage data generated when you or your users use Speko.\n- category: financial\n  text: Billing contact details, subscription\
  \ status, usage credits, invoices, and payment processing records handled\n    by our payment providers.\n- category: device\n  text: IP address, browser and device metadata, pages visited, referral source, diagnostics, cookies or similar\n    technologies, support messages, and feedback.\n- category: contact\n  text: Information from third-party services you connect, such as account identifiers, access tokens, calendars,\n    events, availability, messages, files, or other data exposed by the scopes you approve.\npurposes:\n- purpose: Provide platform and support\n  text: provide the Speko platform, APIs, SDKs, demos, integrations, and support\n- purpose: Route AI requests to providers\n  text: route voice and AI requests to selected providers, perform failover, return transcripts, play generated\n    audio, execute configured tools, and show operational logs\n- purpose: Billing and abuse prevention\n  text: measure usage, manage billing, enforce limits, detect abuse, and prevent fraud\n\
  - purpose: Improve services\n  text: debug, maintain, secure, and improve Speko services\nretention:\n- scope: Session recordings\n  period: 30 days\n  text: Session recordings are generally retained for 30 days after a session ends, then deleted by lifecycle policy\n- scope: General information\n  period: null\n  text: We retain information for as long as needed to provide Speko, comply with legal obligations, resolve disputes,\n    maintain security, and enforce agreements.\nresidency:\n- region: United States\n  text: Speko is operated from the United States and may process information in the United States and other countries\n    where we or our subprocessors operate.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Customers are responsible for reviewing the third-party providers they configure, including any provider-specific\n    privacy, security, retention, and compliance terms.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Speko to request\
  \ account or data deletion\n  text: You may request deletion of your account or certain data by contacting us.\nrights:\n- right: Access, correct, delete, export, object\n  text: you may have rights to access, correct, delete, export, or object to certain processing of your personal\n    information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/speko/privacy/speko-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Speko's own page on 2026-11-10.
synthetic: false
tags:
- Voice
- Voice AI
- Speech-to-Text
- Text-to-Speech
- LLM
- Telephony
- API Gateway
- Conversational AI
- Developer Tools
- AI Infrastructure
---
