---
api_specs:
- filename: igaming-tools-demand-api-openapi.yml
  format: yaml
  label: iGaming Tools Demand API
  slug: igaming-tools-demand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-demand-api-openapi.yml
- filename: igaming-tools-features-api-openapi.yml
  format: yaml
  label: iGaming Tools Features API
  slug: igaming-tools-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-features-api-openapi.yml
- filename: igaming-tools-jobs-api-openapi.yml
  format: yaml
  label: iGaming Tools Jobs API
  slug: igaming-tools-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-jobs-api-openapi.yml
- filename: igaming-tools-news-api-openapi.yml
  format: yaml
  label: iGaming Tools News API
  slug: igaming-tools-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-news-api-openapi.yml
- filename: igaming-tools-providers-api-openapi.yml
  format: yaml
  label: iGaming Tools Providers API
  slug: igaming-tools-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-providers-api-openapi.yml
- filename: igaming-tools-regulators-api-openapi.yml
  format: yaml
  label: iGaming Tools Regulators API
  slug: igaming-tools-regulators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-regulators-api-openapi.yml
- filename: igaming-tools-series-api-openapi.yml
  format: yaml
  label: iGaming Tools Series API
  slug: igaming-tools-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-series-api-openapi.yml
- filename: igaming-tools-slots-api-openapi.yml
  format: yaml
  label: iGaming Tools Slots API
  slug: igaming-tools-slots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-slots-api-openapi.yml
- filename: igaming-tools-sources-api-openapi.yml
  format: yaml
  label: iGaming Tools Sources API
  slug: igaming-tools-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-sources-api-openapi.yml
- filename: igaming-tools-stats-api-openapi.yml
  format: yaml
  label: iGaming Tools Stats API
  slug: igaming-tools-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-stats-api-openapi.yml
- filename: igaming-tools-themes-api-openapi.yml
  format: yaml
  label: iGaming Tools Themes API
  slug: igaming-tools-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/igaming-tools/openapi/igaming-tools-themes-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (which is also your username).
  - category: device
    text: IP address (stored in full, but masked to /24 in our admin interface) and a short user-agent string.
  - category: communication
    text: Email-confirmation status and the time it was confirmed.
  deletion:
    route: email request to the Data Protection Contact
    text: We do not provide self-service tools for these; instead, email [email protected] and we will respond within the statutory time limits (normally one month).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and API access
    text: 'Account creation, authentication and API access: performance of a contract.'
  - purpose: security and abuse prevention
    text: 'Security, abuse and brute-force prevention, rate limiting and audit logging: legitimate interests.'
  residency:
  - region: EU (Germany)
    text: Our servers are in the EU (Germany, via Hetzner)
  retention:
  - period: 365 days
    scope: Audit logs
    text: 'Audit logs: 365 days, then automatically deleted.'
  - period: for as long as your account exists
    scope: Account data
    text: 'Account data: for as long as your account exists.'
  - period: until you revoke them
    scope: API tokens
    text: 'API tokens: until you revoke them.'
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: You have the right to access, rectification, erasure, restriction, data portability and objection.
  - right: complain to the ICO
    text: You also have the right to complain to the ICO (ico.org.uk).
  role:
    text: The team, acting through the Data Protection Contact, is the data controller for the purposes of UK GDPR and the Data Protection Act 2018.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not carry out advertising or profiling, and we do not sell your data.
  subprocessors:
    text: Cloudflare, for Turnstile bot protection and R2 storage.
    url: null
  transfers:
  - mechanism: adequacy
    text: Where personal data is transferred outside the UK, we rely on UK adequacy regulations where they apply.
  - mechanism: SCC
    text: the UK Addendum to the EU Standard Contractual Clauses
  - mechanism: DPF
    text: the UK extension to the EU–US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: iGaming Tools
provenance_date: '2026-11-09'
provider_name: iGaming Tools
provider_slug: igaming-tools
slug: igaming-tools-privacy-policy
source_date: '2026-11-09'
source_filename: igaming-tools-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://i-gaming.tools/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: iGaming Tools\naid: igaming-tools\nurl: https://i-gaming.tools/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The team, acting through the Data Protection Contact, is the data controller for the purposes of UK GDPR\n    and the Data Protection Act 2018.\ndata_categories:\n- category: identifying\n  text: Email address (which is also your username).\n- category: device\n  text: IP address (stored in full, but masked to /24 in our admin interface) and a short user-agent string.\n- category: communication\n  text: Email-confirmation status and the time it was confirmed.\npurposes:\n\
  - purpose: account and API access\n  text: 'Account creation, authentication and API access: performance of a contract.'\n- purpose: security and abuse prevention\n  text: 'Security, abuse and brute-force prevention, rate limiting and audit logging: legitimate interests.'\nretention:\n- scope: Audit logs\n  period: 365 days\n  text: 'Audit logs: 365 days, then automatically deleted.'\n- scope: Account data\n  period: for as long as your account exists\n  text: 'Account data: for as long as your account exists.'\n- scope: API tokens\n  period: until you revoke them\n  text: 'API tokens: until you revoke them.'\nresidency:\n- region: EU (Germany)\n  text: Our servers are in the EU (Germany, via Hetzner)\ntransfers:\n- mechanism: adequacy\n  text: Where personal data is transferred outside the UK, we rely on UK adequacy regulations where they apply.\n- mechanism: SCC\n  text: the UK Addendum to the EU Standard Contractual Clauses\n- mechanism: DPF\n  text: the UK extension to the EU–US Data\
  \ Privacy Framework.\nsubprocessors:\n  url: null\n  text: Cloudflare, for Turnstile bot protection and R2 storage.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to the Data Protection Contact\n  text: We do not provide self-service tools for these; instead, email [email protected] and we will respond within\n    the statutory time limits (normally one month).\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: You have the right to access, rectification, erasure, restriction, data portability and objection.\n- right: complain to the ICO\n  text: You also have the right to complain to the ICO (ico.org.uk).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not carry out advertising or profiling, and we do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/igaming-tools/privacy/igaming-tools-privacy-policy.yml
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
summary_line: 18 quoted statements, read from iGaming Tools's own page on 2026-11-09.
synthetic: false
tags:
- iGaming
- Online Casino
- Gambling
- slot games
- slot metadata
- gambling regulation
- Industry News
- Job
- market demand
- Analytics
- REST API
- OpenAPI
- MCP Server
- Llms.txt
- LLM Tooling
- slot RTP
- paytable data
- search demand
- iGaming jobs
- agent-ready API
- read-only API
---
