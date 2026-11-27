---
api_specs:
- filename: beliefstate-ai-access-api-openapi.yml
  format: yaml
  label: BeliefState Access API
  slug: beliefstate-ai-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-access-api-openapi.yml
- filename: beliefstate-ai-beliefs-api-openapi.yml
  format: yaml
  label: BeliefState Beliefs API
  slug: beliefstate-ai-beliefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-beliefs-api-openapi.yml
- filename: beliefstate-ai-brief-api-openapi.yml
  format: yaml
  label: BeliefState Brief API
  slug: beliefstate-ai-brief-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-brief-api-openapi.yml
- filename: beliefstate-ai-research-api-openapi.yml
  format: yaml
  label: BeliefState Research API
  slug: beliefstate-ai-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-research-api-openapi.yml
- filename: beliefstate-ai-research-payments-api-openapi.yml
  format: yaml
  label: BeliefState Research payments API
  slug: beliefstate-ai-research-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-research-payments-api-openapi.yml
- filename: beliefstate-ai-sources-api-openapi.yml
  format: yaml
  label: BeliefState Sources API
  slug: beliefstate-ai-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-sources-api-openapi.yml
- filename: beliefstate-ai-tickers-api-openapi.yml
  format: yaml
  label: BeliefState Tickers API
  slug: beliefstate-ai-tickers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beliefstate-ai/openapi/beliefstate-ai-tickers-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information, including your name, email address, authentication identifiers, workspace, access role, API key metadata, and connected AI grants.
  - category: communication
    text: Research content you submit or select for processing, plus source records, annotations, reviews, thesis events, and audit history created through your use of the service.
  - category: device
    text: Technical information such as device and browser details, IP address, timestamps, REST and MCP request metadata, usage and cost records, documentation search terms and usefulness feedback, error data, and security events.
  - category: financial
    text: Prepaid credit, billing, and transaction details. Payment card information is processed by our payment provider and is not stored by BeliefState.
  deletion:
    route: Request account deletion, connected data deletion, or an export by contacting the privacy email address
    text: You may request account deletion, connected data deletion, or an export by contacting [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate users and API clients
    text: We use information to authenticate users and API clients, deliver analyst belief data through the website, REST API, and MCP, meter usage, enforce access
  - purpose: Process payments
    text: process payments, improve documentation, comply with law, and improve reliability.
  - purpose: Analytics
    text: We use PostHog to understand website and connected AI use, including pages viewed, referring sites, device and browser details, automation signals, page exits, conversion actions, and completed payments.
  - purpose: Ad measurement
    text: It is used to measure advertising results.
  retention:
  - period: null
    scope: General records
    text: We retain information only while needed to provide the service, satisfy legal and security obligations, resolve disputes, and preserve required audit records.
  - period: null
    scope: Discord API data
    text: Discord API data is retained only while needed for BeliefState’s stated Discord features or as required by law.
  rights:
  - right: Access, correct, delete, or obtain a copy
    text: Depending on your location, you may have rights to access, correct, delete, or obtain a copy of personal information and to appeal a denied request.
  - right: Opt out of marketing email
    text: You may disconnect providers, stop using the service, or opt out of marketing email at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BeliefState
provenance_date: '2026-11-09'
provider_name: BeliefState
provider_slug: beliefstate-ai
slug: beliefstate-ai-privacy-policy
source_date: '2026-11-09'
source_filename: beliefstate-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://beliefstate.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BeliefState\naid: beliefstate-ai\nurl: https://beliefstate.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information, including your name, email address, authentication identifiers, workspace, access role,\n    API key metadata, and connected AI grants.\n- category: communication\n  text: Research content you submit or select for processing, plus source records, annotations, reviews, thesis\n    events, and audit history created through your use of the service.\n- category: device\n  text: Technical information such\
  \ as device and browser details, IP address, timestamps, REST and MCP request metadata,\n    usage and cost records, documentation search terms and usefulness feedback, error data, and security events.\n- category: financial\n  text: Prepaid credit, billing, and transaction details. Payment card information is processed by our payment provider\n    and is not stored by BeliefState.\npurposes:\n- purpose: Authenticate users and API clients\n  text: We use information to authenticate users and API clients, deliver analyst belief data through the website,\n    REST API, and MCP, meter usage, enforce access\n- purpose: Process payments\n  text: process payments, improve documentation, comply with law, and improve reliability.\n- purpose: Analytics\n  text: We use PostHog to understand website and connected AI use, including pages viewed, referring sites, device\n    and browser details, automation signals, page exits, conversion actions, and completed payments.\n- purpose: Ad measurement\n\
  \  text: It is used to measure advertising results.\nretention:\n- scope: General records\n  period: null\n  text: We retain information only while needed to provide the service, satisfy legal and security obligations,\n    resolve disputes, and preserve required audit records.\n- scope: Discord API data\n  period: null\n  text: Discord API data is retained only while needed for BeliefState’s stated Discord features or as required\n    by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account deletion, connected data deletion, or an export by contacting the privacy email address\n  text: You may request account deletion, connected data deletion, or an export by contacting [email protected]\n    .\nrights:\n- right: Access, correct, delete, or obtain a copy\n  text: Depending on your location, you may have rights to access, correct, delete, or obtain a copy of personal\n    information\
  \ and to appeal a denied request.\n- right: Opt out of marketing email\n  text: You may disconnect providers, stop using the service, or opt out of marketing email at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/beliefstate-ai/privacy/beliefstate-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from BeliefState's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Research
- Analytics
- Platform
---
