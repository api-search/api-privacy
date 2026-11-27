---
api_specs:
- filename: abundanceapis-com-cors-proxy-api-openapi.yml
  format: yaml
  label: abundanceapis-com CORS Proxy API
  slug: abundanceapis-com-cors-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abundanceapis-com/openapi/abundanceapis-com-cors-proxy-api-openapi.yml
- filename: abundanceapis-com-system-api-openapi.yml
  format: yaml
  label: abundanceapis-com System API
  slug: abundanceapis-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abundanceapis-com/openapi/abundanceapis-com-system-api-openapi.yml
- filename: abundanceapis-com-tools-api-openapi.yml
  format: yaml
  label: abundanceapis-com Tools API
  slug: abundanceapis-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abundanceapis-com/openapi/abundanceapis-com-tools-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: other
    text: Request payloads (text, images, PDFs, URLs, coordinates) are processed in memory and are not written to disk or stored after the response is sent.
  - category: identifying
    text: For marketplace traffic we record the RapidAPI subscriber identifier supplied by the gateway.
  - category: device
    text: timestamp, endpoint path, HTTP status, response latency, and the request source category
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operations and abuse prevention
    text: For operations and abuse prevention we keep minimal request metadata
  - purpose: rate limiting
    text: Tool requests are rate-limited per visitor IP; the IP is used in memory for rate limiting and is not retained in analytics.
  retention:
  - period: null
    scope: request payloads
    text: are processed in memory and are not written to disk or stored after the response is sent.
  - period: null
    scope: encryption keys and plaintexts
    text: Keys and plaintexts exist only for the lifetime of the request and are never stored.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, share, or monetize any data from API requests.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: abundanceapis-com
provenance_date: '2026-11-09'
provider_name: abundanceapis-com
provider_slug: abundanceapis-com
slug: abundanceapis-com-privacy-policy
source_date: '2026-11-09'
source_filename: abundanceapis-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://abundanceapis.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: abundanceapis-com\naid: abundanceapis-com\nurl: https://abundanceapis.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: Request payloads (text, images, PDFs, URLs, coordinates) are processed in memory and are not written to\n    disk or stored after the response is sent.\n- category: identifying\n  text: For marketplace traffic we record the RapidAPI subscriber identifier supplied by the gateway.\n- category: device\n  text: timestamp, endpoint path, HTTP status, response latency, and the request source category\npurposes:\n- purpose:\
  \ operations and abuse prevention\n  text: For operations and abuse prevention we keep minimal request metadata\n- purpose: rate limiting\n  text: Tool requests are rate-limited per visitor IP; the IP is used in memory for rate limiting and is not retained\n    in analytics.\nretention:\n- scope: request payloads\n  period: null\n  text: are processed in memory and are not written to disk or stored after the response is sent.\n- scope: encryption keys and plaintexts\n  period: null\n  text: Keys and plaintexts exist only for the lifetime of the request and are never stored.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, share, or monetize any data from API requests.\n"
source_yaml_url: https://artifacts.apis.io/abundanceapis-com/privacy/abundanceapis-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 8 quoted statements, read from abundanceapis-com's own page on 2026-11-09.
synthetic: false
tags:
- Developer Tools
- Data Validation
- Geolocation
- Finance
- Utilities
---
