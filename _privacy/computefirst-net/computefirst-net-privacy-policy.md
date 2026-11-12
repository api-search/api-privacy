---
api_specs:
- filename: computefirst-net-account-api-openapi.yml
  format: yaml
  label: ComputeFirst Account API
  slug: computefirst-net-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-account-api-openapi.yml
- filename: computefirst-net-discovery-api-openapi.yml
  format: yaml
  label: ComputeFirst Discovery API
  slug: computefirst-net-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-discovery-api-openapi.yml
- filename: computefirst-net-execution-api-openapi.yml
  format: yaml
  label: ComputeFirst Execution API
  slug: computefirst-net-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-execution-api-openapi.yml
- filename: computefirst-net-feedback-api-openapi.yml
  format: yaml
  label: ComputeFirst Feedback API
  slug: computefirst-net-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-feedback-api-openapi.yml
- filename: computefirst-net-mcp-api-openapi.yml
  format: yaml
  label: ComputeFirst MCP API
  slug: computefirst-net-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-mcp-api-openapi.yml
- filename: computefirst-net-newsletter-api-openapi.yml
  format: yaml
  label: ComputeFirst Newsletter API
  slug: computefirst-net-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-newsletter-api-openapi.yml
- filename: computefirst-net-savings-api-openapi.yml
  format: yaml
  label: ComputeFirst Savings API
  slug: computefirst-net-savings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-savings-api-openapi.yml
- filename: computefirst-net-service-api-openapi.yml
  format: yaml
  label: ComputeFirst Service API
  slug: computefirst-net-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computefirst-net/openapi/computefirst-net-service-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username, display name, optional contact email (not verified), your passkey's public key, and the policy version you accepted and when.
  - category: contact
    text: 'Emails to us: your address and whatever you write.'
  - category: device
    text: calling software and version, country (from your IP address, via Cloudflare), referring host
  - category: behavioral
    text: 'Search record: the search text (cut to 256 bytes), a language guess, the search method, the tools returned, the top match score'
  - category: communication
    text: 'Tool requests: your description (up to 4 KB) and optional example input and output'
  deletion:
    route: Email idan.roth.ai@gmail.com with the subject "Privacy request"
    text: To withdraw consent for a tool-request email, or to delete your profile or an email sign-in account, email us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run tools and searches
    text: 'Run tools and searches: inputs (in memory only) and search text [legitimate interests; contract for profile holders].'
  - purpose: Security, limits and abuse prevention
    text: 'Security, limits, abuse prevention and fixing errors: usage records, request log, hashed IPs, hosting logs [legitimate interests].'
  - purpose: Newsletter and tool-ready emails
    text: 'Newsletter and "your tool is ready" emails: email address [consent].'
  - purpose: Website analytics
    text: 'Website analytics: Google Analytics data [consent].'
  residency:
  - region: Israel
    text: Idan Roth is in Israel, which the European Commission and the UK recognise as adequate
  retention:
  - period: 180 days
    scope: Usage and search records
    text: 'Usage and search records: 180 days.'
  - period: 30 days
    scope: Request log, execution records, limit counters, feedback, recorded content
    text: 'Request log, execution records, limit counters and search rerank records, feedback, individual savings reports and recorded content: 30 days.'
  - period: 7 days
    scope: Browser sessions
    text: 'Browser sessions: 7 days.'
  - period: no more than 14 months
    scope: Google Analytics data
    text: 'Google Analytics data: no more than 14 months.'
  rights:
  - right: Inspect personal data
    text: you can inspect the personal data we hold about you
  - right: Correct or delete
    text: ask us to correct or delete data that is wrong, incomplete, unclear or out of date
  - right: Portability
    text: you can also get a portable copy of your data, have it erased, restrict processing, object to processing based on legitimate interests
  - right: Withdraw consent
    text: withdraw consent at any time
  role:
    text: ComputeFirst is run by Idan Roth , a private individual in Israel, who is responsible for your personal data (the "controller").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data or build advertising profiles
  subprocessors:
    text: Cloudflare, Inc. hosts the service, its network, database and logs. Google provides Google Analytics (only with your consent) and Gmail
    url: null
  transfers:
  - mechanism: SCC
    text: with the EU Standard Contractual Clauses where they apply
  - mechanism: DPF
    text: certified providers' EU-U.S. Data Privacy Framework certification, with its UK and Swiss extensions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ComputeFirst
provenance_date: '2026-11-09'
provider_name: ComputeFirst
provider_slug: computefirst-net
slug: computefirst-net-privacy-policy
source_date: '2026-11-09'
source_filename: computefirst-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://computefirst.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ComputeFirst\naid: computefirst-net\nurl: https://computefirst.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ComputeFirst is run by Idan Roth , a private individual in Israel, who is responsible for your personal\n    data (the \"controller\").\ndata_categories:\n- category: identifying\n  text: Username, display name, optional contact email (not verified), your passkey's public key, and the policy\n    version you accepted and when.\n- category: contact\n  text: 'Emails to us: your address and whatever you write.'\n- category: device\n  text: calling software and version, country\
  \ (from your IP address, via Cloudflare), referring host\n- category: behavioral\n  text: 'Search record: the search text (cut to 256 bytes), a language guess, the search method, the tools returned,\n    the top match score'\n- category: communication\n  text: 'Tool requests: your description (up to 4 KB) and optional example input and output'\npurposes:\n- purpose: Run tools and searches\n  text: 'Run tools and searches: inputs (in memory only) and search text [legitimate interests; contract for profile\n    holders].'\n- purpose: Security, limits and abuse prevention\n  text: 'Security, limits, abuse prevention and fixing errors: usage records, request log, hashed IPs, hosting logs\n    [legitimate interests].'\n- purpose: Newsletter and tool-ready emails\n  text: 'Newsletter and \"your tool is ready\" emails: email address [consent].'\n- purpose: Website analytics\n  text: 'Website analytics: Google Analytics data [consent].'\nretention:\n- scope: Usage and search records\n  period:\
  \ 180 days\n  text: 'Usage and search records: 180 days.'\n- scope: Request log, execution records, limit counters, feedback, recorded content\n  period: 30 days\n  text: 'Request log, execution records, limit counters and search rerank records, feedback, individual savings\n    reports and recorded content: 30 days.'\n- scope: Browser sessions\n  period: 7 days\n  text: 'Browser sessions: 7 days.'\n- scope: Google Analytics data\n  period: no more than 14 months\n  text: 'Google Analytics data: no more than 14 months.'\nresidency:\n- region: Israel\n  text: Idan Roth is in Israel, which the European Commission and the UK recognise as adequate\ntransfers:\n- mechanism: SCC\n  text: with the EU Standard Contractual Clauses where they apply\n- mechanism: DPF\n  text: certified providers' EU-U.S. Data Privacy Framework certification, with its UK and Swiss extensions\nsubprocessors:\n  url: null\n  text: Cloudflare, Inc. hosts the service, its network, database and logs. Google provides Google\
  \ Analytics (only\n    with your consent) and Gmail\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email idan.roth.ai@gmail.com with the subject \"Privacy request\"\n  text: To withdraw consent for a tool-request email, or to delete your profile or an email sign-in account, email\n    us.\nrights:\n- right: Inspect personal data\n  text: you can inspect the personal data we hold about you\n- right: Correct or delete\n  text: ask us to correct or delete data that is wrong, incomplete, unclear or out of date\n- right: Portability\n  text: you can also get a portable copy of your data, have it erased, restrict processing, object to processing\n    based on legitimate interests\n- right: Withdraw consent\n  text: withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data or build advertising profiles\n"
source_yaml_url: https://artifacts.apis.io/computefirst-net/privacy/computefirst-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ComputeFirst's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- Developer Tools
- Data Transformation
- CSV
- JSON
- Deterministic Tools
---
