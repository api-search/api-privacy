---
api_specs:
- filename: layercall-com-ai-agents-api-openapi.yml
  format: yaml
  label: layercall-com AI agents API
  slug: layercall-com-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-ai-agents-api-openapi.yml
- filename: layercall-com-batch-api-openapi.yml
  format: yaml
  label: layercall-com Batch API
  slug: layercall-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-batch-api-openapi.yml
- filename: layercall-com-device-api-openapi.yml
  format: yaml
  label: layercall-com Device API
  slug: layercall-com-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-device-api-openapi.yml
- filename: layercall-com-reputation-api-openapi.yml
  format: yaml
  label: layercall-com Reputation API
  slug: layercall-com-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-reputation-api-openapi.yml
- filename: layercall-com-rules-api-openapi.yml
  format: yaml
  label: layercall-com Rules API
  slug: layercall-com-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-rules-api-openapi.yml
- filename: layercall-com-scoring-api-openapi.yml
  format: yaml
  label: layercall-com Scoring API
  slug: layercall-com-scoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-scoring-api-openapi.yml
- filename: layercall-com-unified-api-openapi.yml
  format: yaml
  label: layercall-com Unified API
  slug: layercall-com-unified-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-unified-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up, we store your email address and, if you use Google sign-in, the basic profile information Google provides (name, email).
  - category: device
    text: For each API request we record metadata such as the endpoint called, timestamp, whether the result was cached, and which API key was used
  - category: contact
    text: To score a lookup, you send us values such as an IP address, email, phone number, or domain.
  - category: behavioral
    text: We keep the resulting score, the verdict, and the names of the signals that fired.
  deletion:
    route: Email support@layercall.com or request deletion of account; reputation digests deleted by naming the value
    text: You can request deletion of your account and associated data at any time (see "Your rights" below).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, secure and improve the Service
    text: To provide, secure, and improve the Service.
  - purpose: Authentication and account protection
    text: To authenticate you and protect your account.
  - purpose: Usage metering and billing
    text: To meter usage, enforce plan limits, and process billing.
  - purpose: Abuse detection
    text: To detect abuse of the Service itself and maintain our fraud-signal accuracy.
  - purpose: Fraud prevention on signup
    text: Our lawful basis is legitimate interest in preventing abuse of our own free tier
  residency:
  - region: India
    text: LayerCall is operated from India and uses providers that may process data in other countries.
  retention:
  - period: null
    scope: Account and usage data
    text: We keep account and usage data for as long as your account is active and as needed to provide the Service, comply with legal obligations, and resolve disputes.
  - period: null
    scope: Reputation-network digests
    text: Reputation-network digests are kept for as long as they remain useful as a fraud signal.
  rights:
  - right: access, correct, export, delete
    text: you may have the right to access, correct, export, or delete your personal data, and to object to certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not use the raw values you submit to build advertising profiles or sell them.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where required, we rely on appropriate safeguards for international transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: layercall-com
provenance_date: '2026-11-09'
provider_name: layercall-com
provider_slug: layercall-com
slug: layercall-com-privacy-policy
source_date: '2026-11-09'
source_filename: layercall-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.layercall.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: layercall-com\naid: layercall-com\nurl: https://www.layercall.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up, we store your email address and, if you use Google sign-in, the basic profile information\n    Google provides (name, email).\n- category: device\n  text: For each API request we record metadata such as the endpoint called, timestamp, whether the result was cached,\n    and which API key was used\n- category: contact\n  text: To score a lookup, you send us values such as an IP address, email, phone\
  \ number, or domain.\n- category: behavioral\n  text: We keep the resulting score, the verdict, and the names of the signals that fired.\npurposes:\n- purpose: Provide, secure and improve the Service\n  text: To provide, secure, and improve the Service.\n- purpose: Authentication and account protection\n  text: To authenticate you and protect your account.\n- purpose: Usage metering and billing\n  text: To meter usage, enforce plan limits, and process billing.\n- purpose: Abuse detection\n  text: To detect abuse of the Service itself and maintain our fraud-signal accuracy.\n- purpose: Fraud prevention on signup\n  text: Our lawful basis is legitimate interest in preventing abuse of our own free tier\nretention:\n- scope: Account and usage data\n  period: null\n  text: We keep account and usage data for as long as your account is active and as needed to provide the Service,\n    comply with legal obligations, and resolve disputes.\n- scope: Reputation-network digests\n  period: null\n \
  \ text: Reputation-network digests are kept for as long as they remain useful as a fraud signal.\nresidency:\n- region: India\n  text: LayerCall is operated from India and uses providers that may process data in other countries.\ntransfers:\n- mechanism: other\n  text: Where required, we rely on appropriate safeguards for international transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@layercall.com or request deletion of account; reputation digests deleted by naming the value\n  text: You can request deletion of your account and associated data at any time (see \"Your rights\" below).\nrights:\n- right: access, correct, export, delete\n  text: you may have the right to access, correct, export, or delete your personal data, and to object to certain\n    processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use the raw values you submit to build advertising profiles or sell them.\n"
source_yaml_url: https://artifacts.apis.io/layercall-com/privacy/layercall-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from layercall-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fraud Prevention
- TrustIntelligence
- Security
---
