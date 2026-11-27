---
api_specs:
- filename: agentanalytics-sh-api-openapi.yml
  format: yaml
  label: Agent Analytics API API
  slug: agent-analytics-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentanalytics-sh/openapi/_original/agentanalytics-sh-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: we receive your email address, display name, and avatar URL from the provider
  - category: behavioral
    text: event data (event names, properties, timestamps, optional user/session IDs)
  - category: device
    text: the tracker collects page URL, referrer, screen size, browser name, OS, device type, language, and country (derived from IP at request time)
  - category: location
    text: IP addresses are used at request time to determine visitor country (ISO country code only) but are never stored, logged, or retained.
  deletion:
    route: Dashboard or contact us
    text: You can delete your account and all associated data through the dashboard or by contacting us.
  dpa:
    available: true
    text: Our Data Processing Agreement (DPA) governs how we process data on your behalf in compliance with GDPR Article 28.
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: To provide and maintain the Agent Analytics service
  - purpose: Account authentication
    text: To authenticate you and manage your account
  - purpose: Rate limits and quotas
    text: To enforce rate limits and usage quotas
  - purpose: Payments and subscriptions
    text: To process payments and manage your subscription
  retention:
  - period: null
    scope: Account data
    text: Account data is retained as long as your account is active.
  - period: 90 days on free, 12 months on paid plans
    scope: Analytics event data
    text: Analytics event data retention depends on your plan tier (90 days on free, 12 months on paid plans).
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your account and data
  - right: Export
    text: Export your analytics data via our API
  - right: Object or restrict
    text: Object to or restrict processing of your data
  - right: Withdraw consent
    text: Withdraw consent at any time (where consent is the legal basis)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Cloudflare maintains appropriate safeguards for international data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Analytics
provenance_date: '2026-11-09'
provider_name: Agent Analytics
provider_slug: agentanalytics-sh
slug: agentanalytics-sh-privacy-policy
source_date: '2026-11-09'
source_filename: agentanalytics-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentanalytics.sh/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Analytics\naid: agentanalytics-sh\nurl: https://agentanalytics.sh/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we receive your email address, display name, and avatar URL from the provider\n- category: behavioral\n  text: event data (event names, properties, timestamps, optional user/session IDs)\n- category: device\n  text: the tracker collects page URL, referrer, screen size, browser name, OS, device type, language, and country\n    (derived from IP at request time)\n- category: location\n  text: IP addresses are used\
  \ at request time to determine visitor country (ISO country code only) but are never\n    stored, logged, or retained.\npurposes:\n- purpose: Provide and maintain service\n  text: To provide and maintain the Agent Analytics service\n- purpose: Account authentication\n  text: To authenticate you and manage your account\n- purpose: Rate limits and quotas\n  text: To enforce rate limits and usage quotas\n- purpose: Payments and subscriptions\n  text: To process payments and manage your subscription\nretention:\n- scope: Account data\n  period: null\n  text: Account data is retained as long as your account is active.\n- scope: Analytics event data\n  period: 90 days on free, 12 months on paid plans\n  text: Analytics event data retention depends on your plan tier (90 days on free, 12 months on paid plans).\nresidency: []\ntransfers:\n- mechanism: other\n  text: Cloudflare maintains appropriate safeguards for international data transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n \
  \ available: true\n  url: null\n  text: Our Data Processing Agreement (DPA) governs how we process data on your behalf in compliance with GDPR Article\n    28.\ndeletion:\n  route: Dashboard or contact us\n  text: You can delete your account and all associated data through the dashboard or by contacting us.\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your account and data\n- right: Export\n  text: Export your analytics data via our API\n- right: Object or restrict\n  text: Object to or restrict processing of your data\n- right: Withdraw consent\n  text: Withdraw consent at any time (where consent is the legal basis)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/agentanalytics-sh/privacy/agentanalytics-sh-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Agent Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Artificial Intelligence
- Web Analytics
- Open Source
- Software-as-a-Service
---
