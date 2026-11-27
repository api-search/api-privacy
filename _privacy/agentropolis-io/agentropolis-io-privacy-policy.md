---
api_specs:
- filename: agentropolis-io-badge-api-openapi.yml
  format: yaml
  label: Agentropolis Badge API
  slug: agentropolis-io-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-badge-api-openapi.yml
- filename: agentropolis-io-badges-api-openapi.yml
  format: yaml
  label: Agentropolis Badges API
  slug: agentropolis-io-badges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-badges-api-openapi.yml
- filename: agentropolis-io-business-model-api-openapi.yml
  format: yaml
  label: Agentropolis Business Model API
  slug: agentropolis-io-business-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-business-model-api-openapi.yml
- filename: agentropolis-io-buyers-api-openapi.yml
  format: yaml
  label: Agentropolis Buyers API
  slug: agentropolis-io-buyers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-buyers-api-openapi.yml
- filename: agentropolis-io-call-api-openapi.yml
  format: yaml
  label: Agentropolis Call API
  slug: agentropolis-io-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-call-api-openapi.yml
- filename: agentropolis-io-categories-api-openapi.yml
  format: yaml
  label: Agentropolis Categories API
  slug: agentropolis-io-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-categories-api-openapi.yml
- filename: agentropolis-io-go-api-openapi.yml
  format: yaml
  label: Agentropolis Go API
  slug: agentropolis-io-go-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-go-api-openapi.yml
- filename: agentropolis-io-listings-api-openapi.yml
  format: yaml
  label: Agentropolis Listings API
  slug: agentropolis-io-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-listings-api-openapi.yml
- filename: agentropolis-io-market-api-openapi.yml
  format: yaml
  label: Agentropolis Market API
  slug: agentropolis-io-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-market-api-openapi.yml
- filename: agentropolis-io-reports-api-openapi.yml
  format: yaml
  label: Agentropolis Reports API
  slug: agentropolis-io-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-reports-api-openapi.yml
- filename: agentropolis-io-roadmap-api-openapi.yml
  format: yaml
  label: Agentropolis Roadmap API
  slug: agentropolis-io-roadmap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-roadmap-api-openapi.yml
- filename: agentropolis-io-search-api-openapi.yml
  format: yaml
  label: Agentropolis Search API
  slug: agentropolis-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-search-api-openapi.yml
- filename: agentropolis-io-sellers-api-openapi.yml
  format: yaml
  label: Agentropolis Sellers API
  slug: agentropolis-io-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-sellers-api-openapi.yml
- filename: agentropolis-io-sources-api-openapi.yml
  format: yaml
  label: Agentropolis Sources API
  slug: agentropolis-io-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-sources-api-openapi.yml
- filename: agentropolis-io-sponsored-api-openapi.yml
  format: yaml
  label: Agentropolis Sponsored API
  slug: agentropolis-io-sponsored-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-sponsored-api-openapi.yml
- filename: agentropolis-io-stats-api-openapi.yml
  format: yaml
  label: Agentropolis Stats API
  slug: agentropolis-io-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-stats-api-openapi.yml
- filename: agentropolis-io-tools-api-openapi.yml
  format: yaml
  label: Agentropolis Tools API
  slug: agentropolis-io-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-tools-api-openapi.yml
- filename: agentropolis-io-trust-api-openapi.yml
  format: yaml
  label: Agentropolis Trust API
  slug: agentropolis-io-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentropolis-io/openapi/agentropolis-io-trust-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: behavioral
    text: the query text (first 200 characters), filters, which listings were shown and in what position, which listing was opened
  - category: device
    text: the user-agent string and a coarse agent type (e.g. "browser", "mcp_client"), and a timestamp
  - category: contact
    text: your email (for sign-in links you request)
  - category: financial
    text: whether a payment was attached and settled, amount, network, asset, payTo, payer address and transaction hash from the x402 headers
  - category: communication
    text: received through Resend and forwarded to the Agentropolis team. We keep the message in Resend plus a log row (message id, sender, subject, forward status)
  deletion:
    route: email hello@agentropolis.io
    text: 'Questions or deletion requests: hello@agentropolis.io .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse and rate limiting
    text: We store only a salted, truncated hash of the IP that changes every day, used for abuse and rate limiting.
  - purpose: seller statistics and traffic classification
    text: Each event also gets a traffic class (e.g. our own tests, declared crawler, likely human) computed from the user agent and standard browser headers, so our numbers can exclude bots.
  - purpose: sign-in emails
    text: We send only the sign-in emails you ask for.
  retention:
  - period: 90 days
    scope: search, click, page-view and MCP-session events
    text: search, click, page-view and MCP-session events are deleted after 90 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No marketing, no sharing or selling of personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentropolis
provenance_date: '2026-11-09'
provider_name: Agentropolis
provider_slug: agentropolis-io
slug: agentropolis-io-privacy-policy
source_date: '2026-11-09'
source_filename: agentropolis-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentropolis.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentropolis\naid: agentropolis-io\nurl: https://agentropolis.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: the query text (first 200 characters), filters, which listings were shown and in what position, which listing\n    was opened\n- category: device\n  text: the user-agent string and a coarse agent type (e.g. \"browser\", \"mcp_client\"), and a timestamp\n- category: contact\n  text: your email (for sign-in links you request)\n- category: financial\n  text: whether a payment was attached and settled, amount, network, asset,\
  \ payTo, payer address and transaction\n    hash from the x402 headers\n- category: communication\n  text: received through Resend and forwarded to the Agentropolis team. We keep the message in Resend plus a log\n    row (message id, sender, subject, forward status)\npurposes:\n- purpose: abuse and rate limiting\n  text: We store only a salted, truncated hash of the IP that changes every day, used for abuse and rate limiting.\n- purpose: seller statistics and traffic classification\n  text: Each event also gets a traffic class (e.g. our own tests, declared crawler, likely human) computed from\n    the user agent and standard browser headers, so our numbers can exclude bots.\n- purpose: sign-in emails\n  text: We send only the sign-in emails you ask for.\nretention:\n- scope: search, click, page-view and MCP-session events\n  period: 90 days\n  text: search, click, page-view and MCP-session events are deleted after 90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text:\
  \ null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@agentropolis.io\n  text: 'Questions or deletion requests: hello@agentropolis.io .'\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No marketing, no sharing or selling of personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentropolis-io/privacy/agentropolis-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from Agentropolis's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Marketplace
- Search
- Tools
---
