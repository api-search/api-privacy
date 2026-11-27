---
api_specs:
- filename: wyndpath-com-account-api-openapi.yml
  format: yaml
  label: wyndpath-com Account API
  slug: wyndpath-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-account-api-openapi.yml
- filename: wyndpath-com-charge-api-openapi.yml
  format: yaml
  label: wyndpath-com Charge API
  slug: wyndpath-com-charge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-charge-api-openapi.yml
- filename: wyndpath-com-estimate-api-openapi.yml
  format: yaml
  label: wyndpath-com Estimate API
  slug: wyndpath-com-estimate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-estimate-api-openapi.yml
- filename: wyndpath-com-geo-api-openapi.yml
  format: yaml
  label: wyndpath-com Geo API
  slug: wyndpath-com-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-geo-api-openapi.yml
- filename: wyndpath-com-healthz-api-openapi.yml
  format: yaml
  label: wyndpath-com Healthz API
  slug: wyndpath-com-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-healthz-api-openapi.yml
- filename: wyndpath-com-internal-api-openapi.yml
  format: yaml
  label: wyndpath-com Internal API
  slug: wyndpath-com-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-internal-api-openapi.yml
- filename: wyndpath-com-profiles-api-openapi.yml
  format: yaml
  label: wyndpath-com Profiles API
  slug: wyndpath-com-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-profiles-api-openapi.yml
- filename: wyndpath-com-requests-api-openapi.yml
  format: yaml
  label: wyndpath-com Requests API
  slug: wyndpath-com-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-requests-api-openapi.yml
- filename: wyndpath-com-stats-api-openapi.yml
  format: yaml
  label: wyndpath-com Stats API
  slug: wyndpath-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-stats-api-openapi.yml
- filename: wyndpath-com-target-api-openapi.yml
  format: yaml
  label: wyndpath-com Target API
  slug: wyndpath-com-target-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-target-api-openapi.yml
- filename: wyndpath-com-wyndpath-api-openapi.yml
  format: yaml
  label: wyndpath-com Wynd Path API
  slug: wyndpath-com-wyndpath-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-wyndpath-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account : email address, first name, last name, company (optional), password (stored hashed, never in plain text).'
  - category: device
    text: a device identifier stored via cookie to limit abuse
  - category: behavioral
    text: 'Audience measurement : anonymized browsing statistics on the public pages.'
  - category: communication
    text: one-time codes (OTP) sent by email
  deletion:
    route: account deletion
    text: When the account is deleted, personal data is erased or anonymized.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide console and API, manage account
    text: 'Provide the console and the API, manage your account: performance of the contract .'
  - purpose: Secure access
    text: 'Secure access (anti-bot, rate limiting, logs): legitimate interest .'
  - purpose: Audience measurement
    text: 'Measure audience and improve the site: legitimate interest / consent depending on the context.'
  residency:
  - region: Germany / European Union
    text: Hetzner (hosting, Germany / European Union).
  retention:
  - period: for as long as the account is active
    scope: Account data
    text: Account data is kept for as long as the account is active.
  - period: a limited period necessary for security and billing
    scope: Technical logs
    text: Technical logs are kept for a limited period necessary for security and billing.
  rights:
  - right: access, rectification, erasure, restriction, objection, portability
    text: You have a right of access, rectification, erasure, restriction, objection and portability over your data.
  - right: complaint to CNIL
    text: You may also lodge a complaint with the CNIL (the French data protection authority).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any data.
  subprocessors:
    text: 'We rely on subprocessors to run the service: Hetzner (hosting, Germany / European Union).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: wyndpath-com
provenance_date: '2026-11-10'
provider_name: wyndpath-com
provider_slug: wyndpath-com
slug: wyndpath-com-privacy-policy
source_date: '2026-11-10'
source_filename: wyndpath-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.wyndpath.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: wyndpath-com\naid: wyndpath-com\nurl: https://www.wyndpath.com/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account : email address, first name, last name, company (optional), password (stored hashed, never in plain\n    text).'\n- category: device\n  text: a device identifier stored via cookie to limit abuse\n- category: behavioral\n  text: 'Audience measurement : anonymized browsing statistics on the public pages.'\n- category: communication\n  text: one-time codes (OTP) sent by email\npurposes:\n- purpose: Provide console\
  \ and API, manage account\n  text: 'Provide the console and the API, manage your account: performance of the contract .'\n- purpose: Secure access\n  text: 'Secure access (anti-bot, rate limiting, logs): legitimate interest .'\n- purpose: Audience measurement\n  text: 'Measure audience and improve the site: legitimate interest / consent depending on the context.'\nretention:\n- scope: Account data\n  period: for as long as the account is active\n  text: Account data is kept for as long as the account is active.\n- scope: Technical logs\n  period: a limited period necessary for security and billing\n  text: Technical logs are kept for a limited period necessary for security and billing.\nresidency:\n- region: Germany / European Union\n  text: Hetzner (hosting, Germany / European Union).\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We rely on subprocessors to run the service: Hetzner (hosting, Germany / European Union).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: account deletion\n  text: When the account is deleted, personal data is erased or anonymized.\nrights:\n- right: access, rectification, erasure, restriction, objection, portability\n  text: You have a right of access, rectification, erasure, restriction, objection and portability over your data.\n- right: complaint to CNIL\n  text: You may also lodge a complaint with the CNIL (the French data protection authority).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any data.\n"
source_yaml_url: https://artifacts.apis.io/wyndpath-com/privacy/wyndpath-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from wyndpath-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data
- Automation
- Web
---
