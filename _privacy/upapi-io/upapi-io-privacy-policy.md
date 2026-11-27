---
api_specs:
- filename: upapi-io-communication-api-openapi.yml
  format: yaml
  label: upapi-io Communication API
  slug: upapi-io-communication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-communication-api-openapi.yml
- filename: upapi-io-data-api-openapi.yml
  format: yaml
  label: upapi-io Data API
  slug: upapi-io-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-data-api-openapi.yml
- filename: upapi-io-developer-tools-api-openapi.yml
  format: yaml
  label: upapi-io Developer Tools API
  slug: upapi-io-developer-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-developer-tools-api-openapi.yml
- filename: upapi-io-finance-api-openapi.yml
  format: yaml
  label: upapi-io Finance API
  slug: upapi-io-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-finance-api-openapi.yml
- filename: upapi-io-maps-api-openapi.yml
  format: yaml
  label: upapi-io Maps API
  slug: upapi-io-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-maps-api-openapi.yml
- filename: upapi-io-media-api-openapi.yml
  format: yaml
  label: upapi-io Media API
  slug: upapi-io-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-media-api-openapi.yml
- filename: upapi-io-search-api-openapi.yml
  format: yaml
  label: upapi-io Search API
  slug: upapi-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-search-api-openapi.yml
- filename: upapi-io-seo-tools-api-openapi.yml
  format: yaml
  label: upapi-io SEO tools API
  slug: upapi-io-seo-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-seo-tools-api-openapi.yml
- filename: upapi-io-social-media-api-openapi.yml
  format: yaml
  label: upapi-io Social Media API
  slug: upapi-io-social-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-social-media-api-openapi.yml
- filename: upapi-io-tools-api-openapi.yml
  format: yaml
  label: upapi-io Tools API
  slug: upapi-io-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-tools-api-openapi.yml
- filename: upapi-io-utility-api-openapi.yml
  format: yaml
  label: upapi-io Utility API
  slug: upapi-io-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upapi-io/openapi/upapi-io-utility-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile data — your name and email when you sign up.
  - category: contact
    text: your email, username, and avatar
  - category: financial
    text: We receive limited billing details such as your plan, status, and the last four digits of a card — never full card numbers.
  - category: device
    text: your IP address, and device and browser information
  - category: behavioral
    text: Session replay — a sample, and only if you accept.
  - category: communication
    text: Support communications — records of your correspondence with us.
  deletion:
    route: Self-serve deletion of organization in dashboard settings (Danger zone); or email support@upapi.io
    text: Deletion is self-serve and immediate — you do not have to email anyone and wait.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate and maintain the gateway and account
    text: Provide, operate, secure, and maintain the gateway and your account.
  - purpose: Metering and billing
    text: Meter usage, enforce rate limits and plan quotas, and bill paid plans.
  - purpose: Fraud and security
    text: Detect, prevent, and address fraud, abuse, and security incidents.
  - purpose: Product improvement via aggregate analytics
    text: Monitor and improve performance, investigate errors, and develop new features, including through aggregate analytics.
  retention:
  - period: for the life of your account
    scope: Account data
    text: account data for the life of your account
  - period: 30 days
    scope: Gateway call records
    text: gateway call records (operation, key, user and organization identifiers, time, status, latency and sizes) are deleted automatically once they are 30 days old
  - period: up to 90 days
    scope: Server and network logs
    text: server and network logs, which can contain IP addresses, are kept for up to 90 days
  rights:
  - right: Access
    text: Access — ask what personal data we hold about you.
  - right: Correction
    text: Correction — ask us to fix inaccurate or incomplete data.
  - right: Deletion
    text: Deletion — erase your account and its data yourself, in one action, from the dashboard.
  - right: Portability
    text: Portability — receive a copy of the data you provided in a portable format.
  - right: Restriction and objection
    text: Restriction and objection — ask us to limit or stop certain processing.
  - right: Withdraw consent
    text: Withdraw consent — where we rely on consent, withdraw it at any time without affecting prior processing.
  role:
    text: This policy applies where upAPI acts as a controller of personal data
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: such as the European Commission's Standard Contractual Clauses or reliance on an adequacy decision
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: upapi-io
provenance_date: '2026-11-10'
provider_name: upapi-io
provider_slug: upapi-io
slug: upapi-io-privacy-policy
source_date: '2026-11-10'
source_filename: upapi-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://upapi.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: upapi-io\naid: upapi-io\nurl: https://upapi.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This policy applies where upAPI acts as a controller of personal data\ndata_categories:\n- category: identifying\n  text: Account and profile data — your name and email when you sign up.\n- category: contact\n  text: your email, username, and avatar\n- category: financial\n  text: We receive limited billing details such as your plan, status, and the last four digits of a card — never\n    full card numbers.\n- category: device\n  text: your IP address, and device and browser information\n- category:\
  \ behavioral\n  text: Session replay — a sample, and only if you accept.\n- category: communication\n  text: Support communications — records of your correspondence with us.\npurposes:\n- purpose: Provide, operate and maintain the gateway and account\n  text: Provide, operate, secure, and maintain the gateway and your account.\n- purpose: Metering and billing\n  text: Meter usage, enforce rate limits and plan quotas, and bill paid plans.\n- purpose: Fraud and security\n  text: Detect, prevent, and address fraud, abuse, and security incidents.\n- purpose: Product improvement via aggregate analytics\n  text: Monitor and improve performance, investigate errors, and develop new features, including through aggregate\n    analytics.\nretention:\n- scope: Account data\n  period: for the life of your account\n  text: account data for the life of your account\n- scope: Gateway call records\n  period: 30 days\n  text: gateway call records (operation, key, user and organization identifiers, time,\
  \ status, latency and sizes)\n    are deleted automatically once they are 30 days old\n- scope: Server and network logs\n  period: up to 90 days\n  text: server and network logs, which can contain IP addresses, are kept for up to 90 days\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: such as the European Commission's Standard Contractual Clauses or reliance on an adequacy decision\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-serve deletion of organization in dashboard settings (Danger zone); or email support@upapi.io\n  text: Deletion is self-serve and immediate — you do not have to email anyone and wait.\nrights:\n- right: Access\n  text: Access — ask what personal data we hold about you.\n- right: Correction\n  text: Correction — ask us to fix inaccurate or incomplete data.\n- right: Deletion\n  text: Deletion — erase your account and its data yourself, in one action, from the dashboard.\n- right: Portability\n\
  \  text: Portability — receive a copy of the data you provided in a portable format.\n- right: Restriction and objection\n  text: Restriction and objection — ask us to limit or stop certain processing.\n- right: Withdraw consent\n  text: Withdraw consent — where we rely on consent, withdraw it at any time without affecting prior processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/upapi-io/privacy/upapi-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from upapi-io's own page on 2026-11-10.
synthetic: false
tags:
- API Marketplace
- Developer Tools
- Data
- Automation
- Integration
---
