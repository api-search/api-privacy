---
api_specs:
- filename: nsgoods-org-health-api-openapi.yml
  format: yaml
  label: nsgoods-org Health API
  slug: nsgoods-org-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nsgoods-org/openapi/nsgoods-org-health-api-openapi.yml
- filename: nsgoods-org-payable-api-openapi.yml
  format: yaml
  label: nsgoods-org Payable API
  slug: nsgoods-org-payable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nsgoods-org/openapi/nsgoods-org-payable-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Our web server access logs record the caller IP address, user agent, referring page, and the request path and query string.
  - category: communication
    text: if you email us, we keep the correspondence.
  - category: financial
    text: Our revenue watcher stores on-chain payment records only, which are public blockchain data such as payer address, amount and transaction hash.
  - category: device
    text: The free /feedback endpoint stores the message you send, your user agent and a daily keyed hash of your IP
  deletion:
    route: scheduled removal of older entries
    text: Entries written before 26 September 2026 that fall outside these limits, including Workbench tool log records in an earlier fuller format, are removed by 26 October 2026.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate, secure and rate limit the services
    text: We use all of the above only to operate, secure and rate limit the services.
  retention:
  - period: 90 daily rotations
    scope: web server access logs
    text: Logs are rotated daily and we keep 90 daily rotations, compressed.
  - period: about 24 hours
    scope: web server error logs
    text: so they stay in the raw log for at most about 24 hours.
  - period: 30 days
    scope: payment proxy access log
    text: It is rotated daily and kept for 30 days.
  - period: 30 days
    scope: Workbench MCP logs
    text: both are deleted after 30 days.
  - period: 90 days
    scope: screening audit log
    text: It is rotated daily and kept for 90 days.
  - period: 90 days
    scope: settlement and screening verification log
    text: It is rotated daily and kept for 90 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share any data with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: nsgoods-org
provenance_date: '2026-11-10'
provider_name: nsgoods-org
provider_slug: nsgoods-org
slug: nsgoods-org-privacy-policy
source_date: '2026-11-10'
source_filename: nsgoods-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://x402.nsgoods.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: nsgoods-org\naid: nsgoods-org\nurl: https://x402.nsgoods.org/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Our web server access logs record the caller IP address, user agent, referring page, and the request path\n    and query string.\n- category: communication\n  text: if you email us, we keep the correspondence.\n- category: financial\n  text: Our revenue watcher stores on-chain payment records only, which are public blockchain data such as payer\n    address, amount and transaction hash.\n- category: device\n  text: The free\
  \ /feedback endpoint stores the message you send, your user agent and a daily keyed hash of your\n    IP\npurposes:\n- purpose: operate, secure and rate limit the services\n  text: We use all of the above only to operate, secure and rate limit the services.\nretention:\n- scope: web server access logs\n  period: 90 daily rotations\n  text: Logs are rotated daily and we keep 90 daily rotations, compressed.\n- scope: web server error logs\n  period: about 24 hours\n  text: so they stay in the raw log for at most about 24 hours.\n- scope: payment proxy access log\n  period: 30 days\n  text: It is rotated daily and kept for 30 days.\n- scope: Workbench MCP logs\n  period: 30 days\n  text: both are deleted after 30 days.\n- scope: screening audit log\n  period: 90 days\n  text: It is rotated daily and kept for 90 days.\n- scope: settlement and screening verification log\n  period: 90 days\n  text: It is rotated daily and kept for 90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: scheduled removal of older entries\n  text: Entries written before 26 September 2026 that fall outside these limits, including Workbench tool log records\n    in an earlier fuller format, are removed by 26 October 2026.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share any data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/nsgoods-org/privacy/nsgoods-org-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 13 quoted statements, read from nsgoods-org's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Blockchain
- Data
- Services
- Company
---
