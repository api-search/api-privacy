---
api_specs:
- filename: datakoot-com-base-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Base Intel API
  slug: datakoot-com-base-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-base-intel-api-openapi.yml
- filename: datakoot-com-domain-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Domain Intel API
  slug: datakoot-com-domain-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-domain-intel-api-openapi.yml
- filename: datakoot-com-economy-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Economy Intel API
  slug: datakoot-com-economy-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-economy-intel-api-openapi.yml
- filename: datakoot-com-filings-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Filings Intel API
  slug: datakoot-com-filings-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-filings-intel-api-openapi.yml
- filename: datakoot-com-koot-api-openapi.yml
  format: yaml
  label: datakoot-com Koot API
  slug: datakoot-com-koot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-koot-api-openapi.yml
- filename: datakoot-com-market-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Market Intel API
  slug: datakoot-com-market-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-market-intel-api-openapi.yml
- filename: datakoot-com-package-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Package Intel API
  slug: datakoot-com-package-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-package-intel-api-openapi.yml
- filename: datakoot-com-regulatory-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Regulatory Intel API
  slug: datakoot-com-regulatory-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-regulatory-intel-api-openapi.yml
- filename: datakoot-com-security-intel-api-openapi.yml
  format: yaml
  label: datakoot-com Security Intel API
  slug: datakoot-com-security-intel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-security-intel-api-openapi.yml
- filename: datakoot-com-weather-geo-api-openapi.yml
  format: yaml
  label: datakoot-com Weather & Geo API
  slug: datakoot-com-weather-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datakoot-com/openapi/datakoot-com-weather-geo-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: we take the network address your request arrives from, prepend a fixed secret string, run it through SHA-256, and keep the first 12 bytes
  - category: contact
    text: Email us at hello@datakoot.com and we will of course have your email address, and whatever you put in the message.
  - category: financial
    text: When you subscribe, Polar collects and holds your name, email address, billing location and payment details
  - category: behavioral
    text: We use Cloudflare Web Analytics to see which pages get read.
  - category: device
    text: 'What we see is aggregate: page paths, referrers, country, browser and device class, and load-performance numbers.'
  deletion:
    route: email hello@datakoot.com
    text: To make a request, email hello@datakoot.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: enforce free allowance and meter paid plans
    text: The servers need to count calls to enforce the free allowance and to meter paid plans.
  - purpose: keep free tier fair
    text: To keep the free tier fair we count calls against a one-way hash of your network address
  - purpose: prevent abuse and understand site usage
    text: legitimate interest (keeping a free service available and preventing abuse, and understanding aggregate site usage)
  - purpose: answer email enquiries
    text: We use it to answer you.
  residency:
  - region: North America
    text: The call-counter database is a single Cloudflare D1 database placed in North America.
  retention:
  - period: 90 days
    scope: call counters
    text: Deleted no later than 90 days after your last call.
  - period: one hour
    scope: licence-key validation cache
    text: Held for at most one hour, then expires on its own.
  - period: 7 days
    scope: application logs
    text: Retained by Cloudflare on its own schedule, currently no more than 7 days.
  - period: seven years
    scope: metering ledger
    text: so we keep it for seven years
  - period: three days
    scope: gateway logs of pay-per-call payments
    text: Our gateway logs of them are kept for three days.
  rights:
  - right: access, correct, delete, export
    text: you may have the right to access, correct, delete, or export your personal data
  - right: object or restrict processing
    text: to object to or restrict its processing
  - right: non-discrimination
    text: to be free from discrimination for exercising those rights
  - right: complaint to supervisory authority
    text: You may lodge a complaint with your local supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we never will.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: datakoot-com
provenance_date: '2026-11-09'
provider_name: datakoot-com
provider_slug: datakoot-com
slug: datakoot-com-privacy-policy
source_date: '2026-11-09'
source_filename: datakoot-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://datakoot.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: datakoot-com\naid: datakoot-com\nurl: https://datakoot.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we take the network address your request arrives from, prepend a fixed secret string, run it through SHA-256,\n    and keep the first 12 bytes\n- category: contact\n  text: Email us at hello@datakoot.com and we will of course have your email address, and whatever you put in the\n    message.\n- category: financial\n  text: When you subscribe, Polar collects and holds your name, email address, billing location and payment details\n\
  - category: behavioral\n  text: We use Cloudflare Web Analytics to see which pages get read.\n- category: device\n  text: 'What we see is aggregate: page paths, referrers, country, browser and device class, and load-performance\n    numbers.'\npurposes:\n- purpose: enforce free allowance and meter paid plans\n  text: The servers need to count calls to enforce the free allowance and to meter paid plans.\n- purpose: keep free tier fair\n  text: To keep the free tier fair we count calls against a one-way hash of your network address\n- purpose: prevent abuse and understand site usage\n  text: legitimate interest (keeping a free service available and preventing abuse, and understanding aggregate\n    site usage)\n- purpose: answer email enquiries\n  text: We use it to answer you.\nretention:\n- scope: call counters\n  period: 90 days\n  text: Deleted no later than 90 days after your last call.\n- scope: licence-key validation cache\n  period: one hour\n  text: Held for at most one hour, then\
  \ expires on its own.\n- scope: application logs\n  period: 7 days\n  text: Retained by Cloudflare on its own schedule, currently no more than 7 days.\n- scope: metering ledger\n  period: seven years\n  text: so we keep it for seven years\n- scope: gateway logs of pay-per-call payments\n  period: three days\n  text: Our gateway logs of them are kept for three days.\nresidency:\n- region: North America\n  text: The call-counter database is a single Cloudflare D1 database placed in North America.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@datakoot.com\n  text: To make a request, email hello@datakoot.com\nrights:\n- right: access, correct, delete, export\n  text: you may have the right to access, correct, delete, or export your personal data\n- right: object or restrict processing\n  text: to object to or restrict its processing\n- right: non-discrimination\n  text: to be free from discrimination\
  \ for exercising those rights\n- right: complaint to supervisory authority\n  text: You may lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we never will.\n"
source_yaml_url: https://artifacts.apis.io/datakoot-com/privacy/datakoot-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from datakoot-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Artificial Intelligence
- Real-Time
- MCP
- Security
---
