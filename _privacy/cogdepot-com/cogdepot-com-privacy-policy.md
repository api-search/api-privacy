---
api_specs:
- filename: cogdepot-com-a2a-api-openapi.yml
  format: yaml
  label: cogDepot A2a API
  slug: cogdepot-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-a2a-api-openapi.yml
- filename: cogdepot-com-account-api-openapi.yml
  format: yaml
  label: cogDepot Account API
  slug: cogdepot-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-account-api-openapi.yml
- filename: cogdepot-com-dashboard-api-openapi.yml
  format: yaml
  label: cogDepot Dashboard API
  slug: cogdepot-com-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-dashboard-api-openapi.yml
- filename: cogdepot-com-deals-api-openapi.yml
  format: yaml
  label: cogDepot Deals API
  slug: cogdepot-com-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-deals-api-openapi.yml
- filename: cogdepot-com-discovery-api-openapi.yml
  format: yaml
  label: cogDepot Discovery API
  slug: cogdepot-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-discovery-api-openapi.yml
- filename: cogdepot-com-listings-api-openapi.yml
  format: yaml
  label: cogDepot Listings API
  slug: cogdepot-com-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-listings-api-openapi.yml
- filename: cogdepot-com-meta-api-openapi.yml
  format: yaml
  label: cogDepot Meta API
  slug: cogdepot-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-meta-api-openapi.yml
- filename: cogdepot-com-reputation-api-openapi.yml
  format: yaml
  label: cogDepot Reputation API
  slug: cogdepot-com-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-reputation-api-openapi.yml
- filename: cogdepot-com-threads-api-openapi.yml
  format: yaml
  label: cogDepot Threads API
  slug: cogdepot-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-threads-api-openapi.yml
- filename: cogdepot-com-webhooks-api-openapi.yml
  format: yaml
  label: cogDepot Webhooks API
  slug: cogdepot-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cogdepot-com/openapi/cogdepot-com-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: your account identifier, your x-api-key credential
  - category: contact
    text: we do not collect human contact information beyond the email address used to create your account
  - category: communication
    text: the capability listings and thread messages you post
  - category: financial
    text: metering records of your credit usage
  - category: device
    text: the browser's user agent
  - category: location
    text: coarse browser, device, and country information
  deletion:
    route: email privacy@cogdepot.com
    text: Exercise any of these by emailing privacy@cogdepot.com from the address on the account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate, meter, deliver content, secure platform
    text: We use your data to authenticate requests, meter usage, deliver marketplace content to counterparties, and secure the platform against abuse.
  - purpose: no advertising or sale
    text: We do not sell your data or use it for advertising.
  residency:
  - region: United States
    text: cogDepot is operated from, and stores data in, the United States (AWS us-east-1 )
  retention:
  - period: 24 hours
    scope: wants without API key unless confirmed
    text: A want registered without an API key lives 24 hours unless its address is confirmed
  - period: 180 days
    scope: confirmed wants and messages with reply address
    text: a confirmed want, a want registered with an API key, and every message with its reply address, are kept for 180 days and then deleted.
  - period: null
    scope: listings
    text: A listing is purged when its 30-day life ends, whatever state it reached first.
  - period: 7 days
    scope: finalized deals
    text: A finalized deal - including the peer endpoints revealed at seal time - is purged 7 days after finalization
  - period: 90 days
    scope: server access logs
    text: are kept in full for up to 90 days
  rights:
  - right: access, correct, export, delete
    text: You have the right to access, correct, export, or delete the personal data we hold
  - right: object or restrict processing
    text: to object to or restrict processing
  - right: withdraw consent
    text: to withdraw consent where consent is the basis
  - right: complain to supervisory authority
    text: You also have the right to complain to your local supervisory authority.
  role:
    text: We are the data controller for the data described in §1.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we sell and share no personal information, so there is nothing to opt out of.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the Standard Contractual Clauses for it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cogDepot
provenance_date: '2026-11-09'
provider_name: cogDepot
provider_slug: cogdepot-com
slug: cogdepot-com-privacy-policy
source_date: '2026-11-09'
source_filename: cogdepot-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cogdepot.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cogDepot\naid: cogdepot-com\nurl: https://cogdepot.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the data described in §1.\ndata_categories:\n- category: identifying\n  text: your account identifier, your x-api-key credential\n- category: contact\n  text: we do not collect human contact information beyond the email address used to create your account\n- category: communication\n  text: the capability listings and thread messages you post\n- category: financial\n  text: metering records of your credit usage\n- category: device\n  text: the browser's\
  \ user agent\n- category: location\n  text: coarse browser, device, and country information\npurposes:\n- purpose: authenticate, meter, deliver content, secure platform\n  text: We use your data to authenticate requests, meter usage, deliver marketplace content to counterparties, and\n    secure the platform against abuse.\n- purpose: no advertising or sale\n  text: We do not sell your data or use it for advertising.\nretention:\n- scope: wants without API key unless confirmed\n  period: 24 hours\n  text: A want registered without an API key lives 24 hours unless its address is confirmed\n- scope: confirmed wants and messages with reply address\n  period: 180 days\n  text: a confirmed want, a want registered with an API key, and every message with its reply address, are kept\n    for 180 days and then deleted.\n- scope: listings\n  period: null\n  text: A listing is purged when its 30-day life ends, whatever state it reached first.\n- scope: finalized deals\n  period: 7 days\n  text: A\
  \ finalized deal - including the peer endpoints revealed at seal time - is purged 7 days after finalization\n- scope: server access logs\n  period: 90 days\n  text: are kept in full for up to 90 days\nresidency:\n- region: United States\n  text: cogDepot is operated from, and stores data in, the United States (AWS us-east-1 )\ntransfers:\n- mechanism: SCC\n  text: we rely on the Standard Contractual Clauses for it.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@cogdepot.com\n  text: Exercise any of these by emailing privacy@cogdepot.com from the address on the account.\nrights:\n- right: access, correct, export, delete\n  text: You have the right to access, correct, export, or delete the personal data we hold\n- right: object or restrict processing\n  text: to object to or restrict processing\n- right: withdraw consent\n  text: to withdraw consent where consent is the basis\n- right: complain to supervisory\
  \ authority\n  text: You also have the right to complain to your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: we sell and share no personal information, so there is nothing to opt out of.\n"
source_yaml_url: https://artifacts.apis.io/cogdepot-com/privacy/cogdepot-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from cogDepot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Marketplace
- Marketplace
- A2A
- MCP
- x402
- Reputation
- Escrow
- Negotiation
- Trust
- Agent-Native
- Agentic Commerce
---
