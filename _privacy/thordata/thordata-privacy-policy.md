---
api_specs:
- filename: thordata-locations-api-openapi.yml
  format: yaml
  label: Thordata Locations API
  slug: thordata-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-locations-api-openapi.yml
- filename: thordata-proxy-extract-api-openapi.yml
  format: yaml
  label: Thordata Proxy IP Extract API
  slug: thordata-proxy-ip-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-proxy-extract-api-openapi.yml
- filename: thordata-account-api-openapi.yml
  format: yaml
  label: Thordata Account API
  slug: thordata-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-account-api-openapi.yml
- filename: thordata-proxy-api-openapi.yml
  format: yaml
  label: Thordata Proxy API
  slug: thordata-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-proxy-api-openapi.yml
- filename: thordata-proxy-users-api-openapi.yml
  format: yaml
  label: Thordata Proxy Users API
  slug: thordata-proxy-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-proxy-users-api-openapi.yml
- filename: thordata-serp-api-api-openapi.yml
  format: yaml
  label: Thordata SERP API
  slug: thordata-serp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-serp-api-api-openapi.yml
- filename: thordata-tasks-api-openapi.yml
  format: yaml
  label: Thordata Tasks API
  slug: thordata-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-tasks-api-openapi.yml
- filename: thordata-web-scraper-api-api-openapi.yml
  format: yaml
  label: Thordata Web Scraper API
  slug: thordata-web-scraper-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-web-scraper-api-api-openapi.yml
- filename: thordata-whitelist-api-openapi.yml
  format: yaml
  label: Thordata Whitelist API
  slug: thordata-whitelist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-whitelist-api-openapi.yml
- filename: thordata-public-api-api-openapi.yml
  format: yaml
  label: Thordata Public API
  slug: thordata-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-public-api-api-openapi.yml
- filename: thordata-universal-api-api-openapi.yml
  format: yaml
  label: Thordata Universal API
  slug: thordata-universal-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thordata/openapi/thordata-universal-api-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address, contact information such as your Phone number, device information, address, company name, industry, credit card information (credit card number last four digits)
  - category: behavioral
    text: usage data (e.g. access logs, activity history, preferences)
  deletion:
    route: contact us directly
    text: If you would like to delete or modify your personal information, you may contact us directly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide requested service and contract performance
    text: the processing of personal data is necessary for the provision of the requested service and the performance of the contractual obligations between you and Thordata
  - purpose: marketing information about services
    text: Thordata may use your personal data to inform you about our services.
  - purpose: human verification and bot abuse prevention
    text: Human verification and prevention of bot abuse, safeguarding the security of registration, login, form submission, and similar processes
  retention:
  - period: as long as necessary
    scope: personal information
    text: We will retain your personal information for as long as necessary to fulfill the purposes for which it was collected, unless a longer retention period is required or permitted by law.
  rights:
  - right: withdraw consent
    text: You have the right to withdraw your consent at any time without affecting the lawfulness of processing based on consent before the withdrawal.
  - right: access, copy, correct, delete
    text: exercise your personal information rights, including the rights to access, copy, correct, and delete
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: compliance with EU-approved data transfer mechanisms such as standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Thordata
provenance_date: '2026-11-10'
provider_name: Thordata
provider_slug: thordata
slug: thordata-privacy-policy
source_date: '2026-11-10'
source_filename: thordata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.thordata.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Thordata\naid: thordata\nurl: https://www.thordata.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name, email address, contact information such as your Phone number, device information, address, company\n    name, industry, credit card information (credit card number last four digits)\n- category: behavioral\n  text: usage data (e.g. access logs, activity history, preferences)\npurposes:\n- purpose: provide requested service and contract performance\n  text: the processing of personal data is necessary for the provision\
  \ of the requested service and the performance\n    of the contractual obligations between you and Thordata\n- purpose: marketing information about services\n  text: Thordata may use your personal data to inform you about our services.\n- purpose: human verification and bot abuse prevention\n  text: Human verification and prevention of bot abuse, safeguarding the security of registration, login, form submission,\n    and similar processes\nretention:\n- scope: personal information\n  period: as long as necessary\n  text: We will retain your personal information for as long as necessary to fulfill the purposes for which it was\n    collected, unless a longer retention period is required or permitted by law.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: compliance with EU-approved data transfer mechanisms such as standard contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us directly\n  text:\
  \ If you would like to delete or modify your personal information, you may contact us directly.\nrights:\n- right: withdraw consent\n  text: You have the right to withdraw your consent at any time without affecting the lawfulness of processing based\n    on consent before the withdrawal.\n- right: access, copy, correct, delete\n  text: exercise your personal information rights, including the rights to access, copy, correct, and delete\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thordata/privacy/thordata-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 10 quoted statements, read from Thordata's own page on 2026-11-10.
synthetic: false
tags:
- Proxy Network
- Web Scraping
- Data Extraction
- SERP
- Search data
- Web unblocking
- Residential Proxies
- Mobile Proxies
- ISP Proxies
- Datacenter Proxies
- Scraping Browser
- Data-for-AI
- RAG data pipelines
- Web Data
---
