---
api_specs:
- filename: anchord-ai-dupes-api-openapi.yml
  format: yaml
  label: Anchord AI Dupes API
  slug: anchord-ai-dupes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-dupes-api-openapi.yml
- filename: anchord-ai-entities-api-openapi.yml
  format: yaml
  label: Anchord AI Entities API
  slug: anchord-ai-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-entities-api-openapi.yml
- filename: anchord-ai-guard-api-openapi.yml
  format: yaml
  label: Anchord AI Guard API
  slug: anchord-ai-guard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-guard-api-openapi.yml
- filename: anchord-ai-health-api-openapi.yml
  format: yaml
  label: Anchord AI Health API
  slug: anchord-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-health-api-openapi.yml
- filename: anchord-ai-ingest-api-openapi.yml
  format: yaml
  label: Anchord AI Ingest API
  slug: anchord-ai-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-ingest-api-openapi.yml
- filename: anchord-ai-links-api-openapi.yml
  format: yaml
  label: Anchord AI Links API
  slug: anchord-ai-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-links-api-openapi.yml
- filename: anchord-ai-resolve-api-openapi.yml
  format: yaml
  label: Anchord AI Resolve API
  slug: anchord-ai-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-resolve-api-openapi.yml
- filename: anchord-ai-sources-api-openapi.yml
  format: yaml
  label: Anchord AI Sources API
  slug: anchord-ai-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchord-ai/openapi/anchord-ai-sources-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up for Anchord, we collect your name, email address, company name, and password.
  - category: contact
    text: records you submit through the API, which may contain business contact information such as names, email addresses, domains, and external system identifiers
  - category: device
    text: We also collect standard web access logs (IP address, user agent, timestamps) for security monitoring and abuse prevention.
  deletion:
    route: account deletion or console purge
    text: You can disconnect integrations and purge associated source records at any time from the console.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide identity resolution service
    text: We use your information to provide the identity resolution service, authenticate your API requests, maintain your account, and communicate with you about the service.
  - purpose: advertising
    text: We do not sell your data or use it for advertising.
  residency:
  - region: United States
    text: Your data is stored in AWS-hosted infrastructure (US regions).
  retention:
  - period: null
    scope: account data
    text: Your data is retained for the duration of your account.
  - period: null
    scope: tenant data
    text: Upon account deletion, all tenant data including source records, entities, API keys, and integration credentials are permanently deleted.
  rights:
  - right: access, correction, deletion
    text: You may request access to, correction of, or deletion of your personal data by contacting us.
  - right: GDPR, CCPA and similar rights
    text: If you are subject to GDPR, CCPA, or similar regulations, we will honor applicable data subject rights.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anchord AI
provenance_date: '2026-11-09'
provider_name: Anchord AI
provider_slug: anchord-ai
slug: anchord-ai-privacy-policy
source_date: '2026-11-09'
source_filename: anchord-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.anchord.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anchord AI\naid: anchord-ai\nurl: https://www.anchord.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign up for Anchord, we collect your name, email address, company name, and password.\n- category: contact\n  text: records you submit through the API, which may contain business contact information such as names, email\n    addresses, domains, and external system identifiers\n- category: device\n  text: We also collect standard web access logs (IP address, user agent, timestamps) for security monitoring and\n    abuse\
  \ prevention.\npurposes:\n- purpose: provide identity resolution service\n  text: We use your information to provide the identity resolution service, authenticate your API requests, maintain\n    your account, and communicate with you about the service.\n- purpose: advertising\n  text: We do not sell your data or use it for advertising.\nretention:\n- scope: account data\n  period: null\n  text: Your data is retained for the duration of your account.\n- scope: tenant data\n  period: null\n  text: Upon account deletion, all tenant data including source records, entities, API keys, and integration credentials\n    are permanently deleted.\nresidency:\n- region: United States\n  text: Your data is stored in AWS-hosted infrastructure (US regions).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion or console purge\n  text: You can disconnect integrations and purge associated source records at any\
  \ time from the console.\nrights:\n- right: access, correction, deletion\n  text: You may request access to, correction of, or deletion of your personal data by contacting us.\n- right: GDPR, CCPA and similar rights\n  text: If you are subject to GDPR, CCPA, or similar regulations, we will honor applicable data subject rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/anchord-ai/privacy/anchord-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from Anchord AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Identity
- Trust
- Write-Guard
- Integration
---
