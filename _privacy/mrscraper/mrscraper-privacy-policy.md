---
api_specs:
- filename: mrscraper-analytic-api-openapi.yml
  format: yaml
  label: MrScraper Analytic API
  slug: mrscraper-analytic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-analytic-api-openapi.yml
- filename: mrscraper-auth-api-openapi.yml
  format: yaml
  label: MrScraper Auth API
  slug: mrscraper-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-auth-api-openapi.yml
- filename: mrscraper-gateway-api-openapi.yml
  format: yaml
  label: MrScraper Gateway API
  slug: mrscraper-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-gateway-api-openapi.yml
- filename: mrscraper-jobs-api-openapi.yml
  format: yaml
  label: MrScraper Jobs API
  slug: mrscraper-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-jobs-api-openapi.yml
- filename: mrscraper-proxies-api-openapi.yml
  format: yaml
  label: MrScraper Proxies API
  slug: mrscraper-proxies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-proxies-api-openapi.yml
- filename: mrscraper-results-api-openapi.yml
  format: yaml
  label: MrScraper Results API
  slug: mrscraper-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-results-api-openapi.yml
- filename: mrscraper-storage-api-openapi.yml
  format: yaml
  label: MrScraper Storage API
  slug: mrscraper-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-storage-api-openapi.yml
- filename: mrscraper-tasks-api-openapi.yml
  format: yaml
  label: MrScraper Tasks API
  slug: mrscraper-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mrscraper/openapi/mrscraper-tasks-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may require you to provide us with certain personally identifiable information, including but not limited to your name and email
  - category: behavioral
    text: the time spent on those pages, and other statistics
  - category: financial
    text: We also process account verification, subscription, and token-usage information to authenticate connections and report usage.
  - category: other
    text: URLs, search queries, extraction instructions, output schemas, request settings, saved scraper/result identifiers and filters, and retrieved content, including HTML and extracted records. These may contain personal information.
  deletion:
    route: support request to support@mrscraper.com
    text: Retention and permanent-deletion workflows are supported on request through our support team at support@mrscraper.com , rather than through the dashboard.
  dpa:
    available: null
    text: Where the Data Protection Policy applies, it sets out our contractual processing, return/deletion, and data-subject-request obligations.
    url: null
  purposes:
  - purpose: providing and improving the Service
    text: The Personal Information that we collect are used for providing and improving the Service.
  - purpose: fetching, search, extraction and result retrieval
    text: We use this information to perform the requested fetching, search, extraction, saved-scraper reruns, and result retrieval.
  - purpose: service operations and troubleshooting
    text: we process the account, requested domain, operation, time, and request outcome to calculate usage, troubleshoot errors, and improve our platform.
  - purpose: support requests
    text: Information you send to support is used to handle your request.
  retention:
  - period: up to 180 days
    scope: cookie consent preference
    text: The Cookie Policy describes these technologies and the consent preference retained for up to 180 days.
  - period: null
    scope: saved scrapers and results
    text: MrScraper stores saved scraper configurations and results, which can include HTML, so you can retrieve and reuse them.
  rights:
  - right: access, correction, deletion
    text: For access, correction, or deletion requests concerning your personal information, or assistance deleting your account, contact support@mrscraper.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MrScraper
provenance_date: '2026-11-10'
provider_name: MrScraper
provider_slug: mrscraper
slug: mrscraper-privacy-policy
source_date: '2026-11-10'
source_filename: mrscraper-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mrscraper.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MrScraper\naid: mrscraper\nurl: https://mrscraper.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we may require you to provide us with certain personally identifiable information, including but not limited\n    to your name and email\n- category: behavioral\n  text: the time spent on those pages, and other statistics\n- category: financial\n  text: We also process account verification, subscription, and token-usage information to authenticate connections\n    and report usage.\n- category: other\n  text: URLs, search\
  \ queries, extraction instructions, output schemas, request settings, saved scraper/result identifiers\n    and filters, and retrieved content, including HTML and extracted records. These may contain personal information.\npurposes:\n- purpose: providing and improving the Service\n  text: The Personal Information that we collect are used for providing and improving the Service.\n- purpose: fetching, search, extraction and result retrieval\n  text: We use this information to perform the requested fetching, search, extraction, saved-scraper reruns, and\n    result retrieval.\n- purpose: service operations and troubleshooting\n  text: we process the account, requested domain, operation, time, and request outcome to calculate usage, troubleshoot\n    errors, and improve our platform.\n- purpose: support requests\n  text: Information you send to support is used to handle your request.\nretention:\n- scope: cookie consent preference\n  period: up to 180 days\n  text: The Cookie Policy describes\
  \ these technologies and the consent preference retained for up to 180 days.\n- scope: saved scrapers and results\n  period: null\n  text: MrScraper stores saved scraper configurations and results, which can include HTML, so you can retrieve and\n    reuse them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Where the Data Protection Policy applies, it sets out our contractual processing, return/deletion, and data-subject-request\n    obligations.\ndeletion:\n  route: support request to support@mrscraper.com\n  text: Retention and permanent-deletion workflows are supported on request through our support team at support@mrscraper.com\n    , rather than through the dashboard.\nrights:\n- right: access, correction, deletion\n  text: For access, correction, or deletion requests concerning your personal information, or assistance deleting\n    your account, contact support@mrscraper.com .\nsale_or_sharing:\n  stance: unstated\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/mrscraper/privacy/mrscraper-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
summary_line: 13 quoted statements, read from MrScraper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- Proxies
- AI Agents
- MCP
- Search
- Browser Automation
---
