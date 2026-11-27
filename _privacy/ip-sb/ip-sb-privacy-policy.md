---
api_specs:
- filename: ip-sb-openapi-generated.yml
  format: yaml
  label: IP.SB API
  slug: ip-sb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ip-sb/openapi/_ae-authored/ip-sb-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you visit, we receive your IP address and standard request metadata (user agent, referring page, requested URL).
  - category: location
    text: your IP address and its geolocation are displayed back to you
  - category: behavioral
    text: Cached results are keyed by the queried resource, not by who asked.
  deletion:
    route: contact email
    text: for any request, contact [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: render the page and keep the service healthy
    text: 'We use it to render the page (your IP address and its geolocation are displayed back to you) and to keep the Service healthy: rate limiting, abuse prevention, and short-lived operational logs.'
  - purpose: answer lookup queries
    text: The IP addresses, network blocks, ASNs, and domain names you look up are processed to answer the query and cached briefly
  retention:
  - period: minutes to a few hours
    scope: lookup query caches
    text: cached briefly (typically minutes to a few hours)
  - period: up to a day
    scope: reverse DNS caches
    text: Results are cached for up to a day.
  - period: two minutes
    scope: DNS leak test records
    text: These records are deleted after two minutes.
  - period: minutes to hours
    scope: rate-limit counters
    text: Rate-limit counters expire within minutes to hours.
  - period: null
    scope: operational logs
    text: Operational logs are kept only as long as needed for debugging and abuse handling, then rotated out.
  rights:
  - right: access
    text: you may have rights to access, correct, or delete personal data, and to object to processing
  - right: correct
    text: you may have rights to access, correct, or delete personal data
  - right: delete
    text: you may have rights to access, correct, or delete personal data
  - right: object
    text: and to object to processing
  role:
    text: The Service is operated by Show Corporation .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No sale, rental, or trade of personal data. Ever.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IP.SB
provenance_date: '2026-11-09'
provider_name: IP.SB
provider_slug: ip-sb
slug: ip-sb-privacy-policy
source_date: '2026-11-09'
source_filename: ip-sb-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ip.sb/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IP.SB\naid: ip-sb\nurl: https://ip.sb/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Service is operated by Show Corporation .\ndata_categories:\n- category: identifying\n  text: When you visit, we receive your IP address and standard request metadata (user agent, referring page, requested\n    URL).\n- category: location\n  text: your IP address and its geolocation are displayed back to you\n- category: behavioral\n  text: Cached results are keyed by the queried resource, not by who asked.\npurposes:\n- purpose: render the page and keep the service healthy\n  text: 'We\
  \ use it to render the page (your IP address and its geolocation are displayed back to you) and to keep\n    the Service healthy: rate limiting, abuse prevention, and short-lived operational logs.'\n- purpose: answer lookup queries\n  text: The IP addresses, network blocks, ASNs, and domain names you look up are processed to answer the query and\n    cached briefly\nretention:\n- scope: lookup query caches\n  period: minutes to a few hours\n  text: cached briefly (typically minutes to a few hours)\n- scope: reverse DNS caches\n  period: up to a day\n  text: Results are cached for up to a day.\n- scope: DNS leak test records\n  period: two minutes\n  text: These records are deleted after two minutes.\n- scope: rate-limit counters\n  period: minutes to hours\n  text: Rate-limit counters expire within minutes to hours.\n- scope: operational logs\n  period: null\n  text: Operational logs are kept only as long as needed for debugging and abuse handling, then rotated out.\nresidency: []\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact email\n  text: for any request, contact [email protected] .\nrights:\n- right: access\n  text: you may have rights to access, correct, or delete personal data, and to object to processing\n- right: correct\n  text: you may have rights to access, correct, or delete personal data\n- right: delete\n  text: you may have rights to access, correct, or delete personal data\n- right: object\n  text: and to object to processing\nsale_or_sharing:\n  stance: prohibited\n  text: No sale, rental, or trade of personal data. Ever.\n"
source_yaml_url: https://artifacts.apis.io/ip-sb/privacy/ip-sb-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from IP.SB's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IP
- GeoIP
- DNS
---
