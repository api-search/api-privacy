---
api_specs:
- filename: careranks-com-openapi-generated.yml
  format: yaml
  label: CareRanks API
  slug: careranks-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/careranks-com/openapi/_ae-authored/careranks-com-openapi-generated.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: Standard server access logs (IP address, timestamp, page requested, user-agent) are retained for 30 days for operational and security purposes.
  - category: behavioral
    text: For each page view we record the page address, the country and region the request came from, the referring site, and whether the request appears to come from a person's browser or from an automated crawler.
  - category: device
    text: Cloudflare Web Analytics is a separate service run by Cloudflare; it reports aggregate statistics such as browser, operating system, and device type, and Cloudflare's own privacy policy applies to it.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: site operations and security
    text: Standard server access logs (IP address, timestamp, page requested, user-agent) are retained for 30 days for operational and security purposes.
  - purpose: site improvement
    text: we use them only to understand and improve the site
  retention:
  - period: 30 days
    scope: server access logs
    text: Standard server access logs (IP address, timestamp, page requested, user-agent) are retained for 30 days for operational and security purposes.
  - period: about three months
    scope: analytics events
    text: Analytics events stay in our analytics service for about three months.
  - period: indefinitely
    scope: event-level analytics records
    text: We also keep these event-level records indefinitely, in private storage, so we can study how the site is used over time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not use advertising networks and do not sell or share analytics data for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CareRanks
provenance_date: '2026-11-09'
provider_name: CareRanks
provider_slug: careranks-com
slug: careranks-com-privacy-policy
source_date: '2026-11-09'
source_filename: careranks-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://careranks.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CareRanks\naid: careranks-com\nurl: https://careranks.com/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Standard server access logs (IP address, timestamp, page requested, user-agent) are retained for 30 days\n    for operational and security purposes.\n- category: behavioral\n  text: For each page view we record the page address, the country and region the request came from, the referring\n    site, and whether the request appears to come from a person's browser or from an automated crawler.\n- category: device\n  text:\
  \ Cloudflare Web Analytics is a separate service run by Cloudflare; it reports aggregate statistics such as\n    browser, operating system, and device type, and Cloudflare's own privacy policy applies to it.\npurposes:\n- purpose: site operations and security\n  text: Standard server access logs (IP address, timestamp, page requested, user-agent) are retained for 30 days\n    for operational and security purposes.\n- purpose: site improvement\n  text: we use them only to understand and improve the site\nretention:\n- scope: server access logs\n  period: 30 days\n  text: Standard server access logs (IP address, timestamp, page requested, user-agent) are retained for 30 days\n    for operational and security purposes.\n- scope: analytics events\n  period: about three months\n  text: Analytics events stay in our analytics service for about three months.\n- scope: event-level analytics records\n  period: indefinitely\n  text: We also keep these event-level records indefinitely, in private\
  \ storage, so we can study how the site is\n    used over time.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use advertising networks and do not sell or share analytics data for advertising.\n"
source_yaml_url: https://artifacts.apis.io/careranks-com/privacy/careranks-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 9 quoted statements, read from CareRanks's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Transparency
- Data
- Hospitals
- Pricing
---
