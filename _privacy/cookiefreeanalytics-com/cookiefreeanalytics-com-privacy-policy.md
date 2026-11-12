---
api_specs:
- filename: cookiefreeanalytics-com-sites-api-openapi.yml
  format: yaml
  label: Cookie Free Analytics Sites API
  slug: cookiefreeanalytics-com-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cookiefreeanalytics-com/openapi/cookiefreeanalytics-com-sites-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: location
    text: a coarse country, region code, and city name from the edge
  - category: device
    text: a browser family
  - category: identifying
    text: No coordinates, no postal code, no IP on the row.
  - category: contact
    text: An account is a name, email, and a password hash
  - category: financial
    text: we read successful charges and Checkout metadata you already stored (read-only)
  - category: behavioral
    text: which site, which path (query stripped except five UTM tags), which referrer (origin + path, no query)
  deletion:
    route: Export and delete are on /app/account
    text: Export and delete are on /app/account .
  dpa:
    available: true
    text: The processing agreement for your visitors is the DPA .
    url: null
  purposes:
  - purpose: counting visitors once per day
    text: To count one person once per day we briefly use the IP address, HMAC it with a server pepper and a daily salt we then delete
  - purpose: product email
    text: We email about the product, not about your visitors.
  - purpose: dashboard display of Search Console data
    text: That is shown to you on /app , next to your own pageviews.
  residency:
  - region: EU
    text: Beacons hit Frankfurt; pageviews sit in Ireland Postgres.
  - region: Ireland
    text: The note is stored in Ireland.
  retention:
  - period: 7 days
    scope: Watch raw checks
    text: Raw checks are kept 7 days, then rolled up.
  - period: until deleted
    scope: Site Check shared findings
    text: 'Findings are kept until deleted: email hello@cookiefreeanalytics.com to ask.'
  rights:
  - right: export and delete account data
    text: Export and delete are on /app/account .
  role:
    text: For your customer account (name, email, password hash, billing), the controller is Prestons Creek Capital
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell traffic data and we do not send it to an ads company.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Vercel is a US company.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cookie Free Analytics
provenance_date: '2026-11-09'
provider_name: Cookie Free Analytics
provider_slug: cookiefreeanalytics-com
slug: cookiefreeanalytics-com-privacy-policy
source_date: '2026-11-09'
source_filename: cookiefreeanalytics-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cookiefreeanalytics.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cookie Free Analytics\naid: cookiefreeanalytics-com\nurl: https://www.cookiefreeanalytics.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your customer account (name, email, password hash, billing), the controller is Prestons Creek Capital\ndata_categories:\n- category: location\n  text: a coarse country, region code, and city name from the edge\n- category: device\n  text: a browser family\n- category: identifying\n  text: No coordinates, no postal code, no IP on the row.\n- category: contact\n  text: An account is a name, email, and a password hash\n- category: financial\n  text:\
  \ we read successful charges and Checkout metadata you already stored (read-only)\n- category: behavioral\n  text: which site, which path (query stripped except five UTM tags), which referrer (origin + path, no query)\npurposes:\n- purpose: counting visitors once per day\n  text: To count one person once per day we briefly use the IP address, HMAC it with a server pepper and a daily\n    salt we then delete\n- purpose: product email\n  text: We email about the product, not about your visitors.\n- purpose: dashboard display of Search Console data\n  text: That is shown to you on /app , next to your own pageviews.\nretention:\n- scope: Watch raw checks\n  period: 7 days\n  text: Raw checks are kept 7 days, then rolled up.\n- scope: Site Check shared findings\n  period: until deleted\n  text: 'Findings are kept until deleted: email hello@cookiefreeanalytics.com to ask.'\nresidency:\n- region: EU\n  text: Beacons hit Frankfurt; pageviews sit in Ireland Postgres.\n- region: Ireland\n  text:\
  \ The note is stored in Ireland.\ntransfers:\n- mechanism: other\n  text: Vercel is a US company.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: The processing agreement for your visitors is the DPA .\ndeletion:\n  route: Export and delete are on /app/account\n  text: Export and delete are on /app/account .\nrights:\n- right: export and delete account data\n  text: Export and delete are on /app/account .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell traffic data and we do not send it to an ads company.\n"
source_yaml_url: https://artifacts.apis.io/cookiefreeanalytics-com/privacy/cookiefreeanalytics-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Cookie Free Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Web Analytics
- Privacy
- Cookieless
- GDPR
- MCP
- Uptime Monitoring
---
