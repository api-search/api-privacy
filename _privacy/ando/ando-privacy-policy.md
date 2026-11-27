---
api_specs:
- filename: ando-calls-api-openapi.yml
  format: yaml
  label: Ando Calls API
  slug: ando-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-calls-api-openapi.yml
- filename: ando-members-api-openapi.yml
  format: yaml
  label: Ando Members API
  slug: ando-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-members-api-openapi.yml
- filename: ando-messages-api-openapi.yml
  format: yaml
  label: Ando Messages API
  slug: ando-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-messages-api-openapi.yml
- filename: ando-realtime-api-openapi.yml
  format: yaml
  label: Ando Realtime API
  slug: ando-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-realtime-api-openapi.yml
- filename: ando-search-api-openapi.yml
  format: yaml
  label: Ando Search API
  slug: ando-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-search-api-openapi.yml
- filename: ando-webhooks-api-openapi.yml
  format: yaml
  label: Ando Webhooks API
  slug: ando-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-webhooks-api-openapi.yml
- filename: ando-agents-api-openapi.yml
  format: yaml
  label: Ando Agents API
  slug: ando-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-agents-api-openapi.yml
- filename: ando-api-keys-api-openapi.yml
  format: yaml
  label: Ando API Keys API
  slug: ando-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-api-keys-api-openapi.yml
- filename: ando-conversations-api-openapi.yml
  format: yaml
  label: Ando Conversations API
  slug: ando-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-conversations-api-openapi.yml
- filename: ando-files-api-openapi.yml
  format: yaml
  label: Ando Files API
  slug: ando-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-files-api-openapi.yml
- filename: ando-imports-api-openapi.yml
  format: yaml
  label: Ando Imports API
  slug: ando-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-imports-api-openapi.yml
- filename: ando-webhook-sources-api-openapi.yml
  format: yaml
  label: Ando Webhook sources API
  slug: ando-webhook-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ando/openapi/ando-webhook-sources-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your name, email address, and organization details.
  - category: device
    text: We collect device type, operating system, browser type, and IP address.
  - category: behavioral
    text: We automatically collect information about how you interact with our services, including pages visited, features used, and timestamps.
  - category: communication
    text: We process messages, files, and other content you transmit through our platform to provide and improve our services.
  deletion:
    route: Email hello@ando.so
    text: You can request deletion of your account and associated data by contacting us at hello@ando.so.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: To provide, maintain, and improve our services
  - purpose: Process transactions
    text: To process transactions and send related information
  - purpose: Personalization
    text: To personalize your experience and deliver relevant content
  - purpose: Abuse and technical issue detection
    text: To detect, prevent, and address technical issues and abuse
  - purpose: Legal compliance
    text: To comply with legal obligations
  retention:
  - period: null
    scope: Account information
    text: We retain your information for as long as your account is active or as needed to provide you services.
  rights:
  - right: Access and portability
    text: You may request a copy of the personal data we hold about you in a portable format
  - right: Correction
    text: You may request that we correct inaccurate or incomplete information.
  - right: Deletion
    text: You may request deletion of your personal data, subject to certain legal exceptions.
  - right: Opt-out of marketing
    text: You may opt out of marketing communications at any time by following the unsubscribe instructions in our emails.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ando
provenance_date: '2026-11-09'
provider_name: Ando
provider_slug: ando
slug: ando-privacy-policy
source_date: '2026-11-09'
source_filename: ando-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ando.so/security/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ando\naid: ando\nurl: https://www.ando.so/security/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your name, email address, and organization details.\n- category: device\n  text: We collect device type, operating system, browser type, and IP address.\n- category: behavioral\n  text: We automatically collect information about how you interact with our services, including pages visited,\n    features used, and timestamps.\n- category: communication\n  text: We process messages, files,\
  \ and other content you transmit through our platform to provide and improve our\n    services.\npurposes:\n- purpose: Provide and improve services\n  text: To provide, maintain, and improve our services\n- purpose: Process transactions\n  text: To process transactions and send related information\n- purpose: Personalization\n  text: To personalize your experience and deliver relevant content\n- purpose: Abuse and technical issue detection\n  text: To detect, prevent, and address technical issues and abuse\n- purpose: Legal compliance\n  text: To comply with legal obligations\nretention:\n- scope: Account information\n  period: null\n  text: We retain your information for as long as your account is active or as needed to provide you services.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@ando.so\n  text: You can request deletion of your account and associated data by contacting\
  \ us at hello@ando.so.\nrights:\n- right: Access and portability\n  text: You may request a copy of the personal data we hold about you in a portable format\n- right: Correction\n  text: You may request that we correct inaccurate or incomplete information.\n- right: Deletion\n  text: You may request deletion of your personal data, subject to certain legal exceptions.\n- right: Opt-out of marketing\n  text: You may opt out of marketing communications at any time by following the unsubscribe instructions in our\n    emails.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/ando/privacy/ando-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Ando's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Business Applications
- Messaging
- Team Collaboration
- AI Agents
- Agents
- Developer Tools
- MCP
- Webhook
- Productivity
---
