---
api_specs:
- filename: firecrawl-account-api-openapi.yml
  format: yaml
  label: Firecrawl Account API
  slug: firecrawl-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-account-api-openapi.yml
- filename: firecrawl-agent-api-openapi.yml
  format: yaml
  label: Firecrawl Agent API
  slug: firecrawl-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-agent-api-openapi.yml
- filename: firecrawl-billing-api-openapi.yml
  format: yaml
  label: Firecrawl Billing API
  slug: firecrawl-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-billing-api-openapi.yml
- filename: firecrawl-browser-api-openapi.yml
  format: yaml
  label: Firecrawl Browser API
  slug: firecrawl-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-browser-api-openapi.yml
- filename: firecrawl-crawling-api-openapi.yml
  format: yaml
  label: Firecrawl Crawling API
  slug: firecrawl-crawling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-crawling-api-openapi.yml
- filename: firecrawl-extraction-api-openapi.yml
  format: yaml
  label: Firecrawl Extraction API
  slug: firecrawl-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-extraction-api-openapi.yml
- filename: firecrawl-mapping-api-openapi.yml
  format: yaml
  label: Firecrawl Mapping API
  slug: firecrawl-mapping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-mapping-api-openapi.yml
- filename: firecrawl-miscellaneous-api-openapi.yml
  format: yaml
  label: Firecrawl Miscellaneous API
  slug: firecrawl-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-miscellaneous-api-openapi.yml
- filename: firecrawl-scraping-api-openapi.yml
  format: yaml
  label: Firecrawl Scraping API
  slug: firecrawl-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-scraping-api-openapi.yml
- filename: firecrawl-search-api-openapi.yml
  format: yaml
  label: Firecrawl Search API
  slug: firecrawl-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firecrawl/openapi/firecrawl-search-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: name email address payment information, including credit card information company Information
  - category: device
    text: IP addresses browser information timestamps page views, load times referrers device type and browser information
  - category: behavioral
    text: We use cookies to track unauthenticated user activity on our site
  - category: contact
    text: names, emails, and phone numbers if provided by users
  - category: location
    text: location data (based on IP)
  deletion:
    route: written request to help@firecrawl.com
    text: Upon your written request, and absent a legal need under to retain such information, we will delete your personal information we have collected.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services
    text: To provide you our services; Caching and indexing
  - purpose: payments
    text: To process payments
  - purpose: communication
    text: To contact you via email to inform you of service issues, new features, updates, offers, and billing issues
  - purpose: analytics
    text: This is for product and marketing analytics.
  - purpose: advertising
    text: For advertising purposes.
  residency:
  - region: United States
    text: Our servers are located in the United States and this is where your data and information will be stored.
  retention:
  - period: null
    scope: personally identifiable information
    text: We will retain your personally identifiable information until you request in writing that we delete or otherwise remove your personally identifiable information as part of our normal business processes.
  rights:
  - right: access
    text: Have access to their data;
  - right: correction
    text: Correct any errors in their data;
  - right: erasure
    text: Erase data from our records;
  - right: objection
    text: Object to the use of their data, including for the purpose of automated profiling and direct marketing;
  - right: portability
    text: Data portability;
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
name: Firecrawl
provenance_date: '2026-11-09'
provider_name: Firecrawl
provider_slug: firecrawl
slug: firecrawl-privacy-policy
source_date: '2026-11-09'
source_filename: firecrawl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.firecrawl.dev/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Firecrawl\naid: firecrawl\nurl: https://www.firecrawl.dev/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name email address payment information, including credit card information company Information\n- category: device\n  text: IP addresses browser information timestamps page views, load times referrers device type and browser information\n- category: behavioral\n  text: We use cookies to track unauthenticated user activity on our site\n- category: contact\n  text: names, emails, and phone numbers if provided by users\n\
  - category: location\n  text: location data (based on IP)\npurposes:\n- purpose: provide services\n  text: To provide you our services; Caching and indexing\n- purpose: payments\n  text: To process payments\n- purpose: communication\n  text: To contact you via email to inform you of service issues, new features, updates, offers, and billing issues\n- purpose: analytics\n  text: This is for product and marketing analytics.\n- purpose: advertising\n  text: For advertising purposes.\nretention:\n- scope: personally identifiable information\n  period: null\n  text: We will retain your personally identifiable information until you request in writing that we delete or otherwise\n    remove your personally identifiable information as part of our normal business processes.\nresidency:\n- region: United States\n  text: Our servers are located in the United States and this is where your data and information will be stored.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: written request to help@firecrawl.com\n  text: Upon your written request, and absent a legal need under to retain such information, we will delete your\n    personal information we have collected.\nrights:\n- right: access\n  text: Have access to their data;\n- right: correction\n  text: Correct any errors in their data;\n- right: erasure\n  text: Erase data from our records;\n- right: objection\n  text: Object to the use of their data, including for the purpose of automated profiling and direct marketing;\n- right: portability\n  text: Data portability;\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firecrawl/privacy/firecrawl-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 18 quoted statements, read from Firecrawl's own page on 2026-11-09.
synthetic: false
tags:
- Crawling
- Data Extraction
- Web Scraping
- URLs
- Artificial Intelligence
- Markdown
---
