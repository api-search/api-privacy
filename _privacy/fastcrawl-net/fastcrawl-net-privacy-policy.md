---
api_specs:
- filename: fastcrawl-net-batch-api-openapi.yml
  format: yaml
  label: fastcrawl-net Batch API
  slug: fastcrawl-net-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-batch-api-openapi.yml
- filename: fastcrawl-net-crawl-api-openapi.yml
  format: yaml
  label: fastcrawl-net Crawl API
  slug: fastcrawl-net-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-crawl-api-openapi.yml
- filename: fastcrawl-net-email-api-openapi.yml
  format: yaml
  label: fastcrawl-net Email API
  slug: fastcrawl-net-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-email-api-openapi.yml
- filename: fastcrawl-net-extract-api-openapi.yml
  format: yaml
  label: fastcrawl-net Extract API
  slug: fastcrawl-net-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-extract-api-openapi.yml
- filename: fastcrawl-net-health-api-openapi.yml
  format: yaml
  label: fastcrawl-net Health API
  slug: fastcrawl-net-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-health-api-openapi.yml
- filename: fastcrawl-net-image-api-openapi.yml
  format: yaml
  label: fastcrawl-net Image API
  slug: fastcrawl-net-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-image-api-openapi.yml
- filename: fastcrawl-net-map-api-openapi.yml
  format: yaml
  label: fastcrawl-net Map API
  slug: fastcrawl-net-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-map-api-openapi.yml
- filename: fastcrawl-net-me-api-openapi.yml
  format: yaml
  label: fastcrawl-net Me API
  slug: fastcrawl-net-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-me-api-openapi.yml
- filename: fastcrawl-net-monitors-api-openapi.yml
  format: yaml
  label: fastcrawl-net Monitors API
  slug: fastcrawl-net-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-monitors-api-openapi.yml
- filename: fastcrawl-net-parse-api-openapi.yml
  format: yaml
  label: fastcrawl-net Parse API
  slug: fastcrawl-net-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-parse-api-openapi.yml
- filename: fastcrawl-net-pdf-api-openapi.yml
  format: yaml
  label: fastcrawl-net PDF API
  slug: fastcrawl-net-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-pdf-api-openapi.yml
- filename: fastcrawl-net-scrape-api-openapi.yml
  format: yaml
  label: fastcrawl-net Scrape API
  slug: fastcrawl-net-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-scrape-api-openapi.yml
- filename: fastcrawl-net-screenshot-api-openapi.yml
  format: yaml
  label: fastcrawl-net Screenshot API
  slug: fastcrawl-net-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-screenshot-api-openapi.yml
- filename: fastcrawl-net-search-api-openapi.yml
  format: yaml
  label: fastcrawl-net Search API
  slug: fastcrawl-net-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-search-api-openapi.yml
- filename: fastcrawl-net-usage-api-openapi.yml
  format: yaml
  label: fastcrawl-net Usage API
  slug: fastcrawl-net-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-usage-api-openapi.yml
- filename: fastcrawl-net-webhooks-api-openapi.yml
  format: yaml
  label: fastcrawl-net Webhooks API
  slug: fastcrawl-net-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrawl-net/openapi/fastcrawl-net-webhooks-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, and — if you sign in with Google — your Google display name.
  - category: contact
    text: Truncated IP address. We store your client IP with the last part removed
  - category: device
    text: your user agent, and a request identifier
  - category: financial
    text: Your subscription status, plan, and metered usage counts.
  - category: behavioral
    text: the target URL you asked us to fetch, the duration, the error code if the call failed, whether the response came from cache, which engine path served it, the request mode
  deletion:
    route: email
    text: Email us and we will delete your account and revoke your keys for you
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: To provide the service — serving your requests, caching responses, and returning results (performance of our contract with you).
  - purpose: meter and bill
    text: To meter and bill — counting billable requests so your invoice is correct.
  - purpose: keep service working and safe
    text: To keep it working and safe — diagnosing failures, spotting abuse, and preventing it (our legitimate interests).
  - purpose: legal obligations
    text: To meet legal obligations — tax and accounting records.
  retention:
  - period: indefinite
    scope: request logs
    text: We do not currently run an automatic expiry on this table, so treat the retention as indefinite for now
  - period: 48 hours
    scope: cached content
    text: The default cache lifetime is 48 hours
  - period: null
    scope: billing records
    text: Billing records are kept as long as tax law requires.
  rights:
  - right: access, correct, export, delete
    text: you may have the right to access, correct, export, or delete your personal data
  - right: object or restrict processing
    text: to object to or restrict certain processing
  - right: complain to authority
    text: to complain to your local data-protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, and we do not share it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Our providers operate globally, so your data may be processed outside your country, including in the United States, under the safeguards those providers offer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fastcrawl-net
provenance_date: '2026-11-09'
provider_name: fastcrawl-net
provider_slug: fastcrawl-net
slug: fastcrawl-net-privacy-policy
source_date: '2026-11-09'
source_filename: fastcrawl-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fastcrawl.net/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fastcrawl-net\naid: fastcrawl-net\nurl: https://fastcrawl.net/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, and — if you sign in with Google — your Google display name.\n- category: contact\n  text: Truncated IP address. We store your client IP with the last part removed\n- category: device\n  text: your user agent, and a request identifier\n- category: financial\n  text: Your subscription status, plan, and metered usage counts.\n- category: behavioral\n  text: the target URL you asked us to fetch, the duration,\
  \ the error code if the call failed, whether the response\n    came from cache, which engine path served it, the request mode\npurposes:\n- purpose: provide the service\n  text: To provide the service — serving your requests, caching responses, and returning results (performance of\n    our contract with you).\n- purpose: meter and bill\n  text: To meter and bill — counting billable requests so your invoice is correct.\n- purpose: keep service working and safe\n  text: To keep it working and safe — diagnosing failures, spotting abuse, and preventing it (our legitimate interests).\n- purpose: legal obligations\n  text: To meet legal obligations — tax and accounting records.\nretention:\n- scope: request logs\n  period: indefinite\n  text: We do not currently run an automatic expiry on this table, so treat the retention as indefinite for now\n- scope: cached content\n  period: 48 hours\n  text: The default cache lifetime is 48 hours\n- scope: billing records\n  period: null\n  text: Billing\
  \ records are kept as long as tax law requires.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our providers operate globally, so your data may be processed outside your country, including in the United\n    States, under the safeguards those providers offer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: Email us and we will delete your account and revoke your keys for you\nrights:\n- right: access, correct, export, delete\n  text: you may have the right to access, correct, export, or delete your personal data\n- right: object or restrict processing\n  text: to object to or restrict certain processing\n- right: complain to authority\n  text: to complain to your local data-protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, and we do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/fastcrawl-net/privacy/fastcrawl-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from fastcrawl-net's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Artificial Intelligence
- Content Extraction
- REST API
- MCP
---
