---
api_specs:
- filename: agentbookable-com-availability-api-openapi.yml
  format: yaml
  label: Agentbookable Availability API
  slug: agentbookable-com-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-availability-api-openapi.yml
- filename: agentbookable-com-bookings-api-openapi.yml
  format: yaml
  label: Agentbookable Bookings API
  slug: agentbookable-com-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-bookings-api-openapi.yml
- filename: agentbookable-com-discovery-api-openapi.yml
  format: yaml
  label: Agentbookable Discovery API
  slug: agentbookable-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-discovery-api-openapi.yml
- filename: agentbookable-com-mandates-api-openapi.yml
  format: yaml
  label: Agentbookable Mandates API
  slug: agentbookable-com-mandates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-mandates-api-openapi.yml
- filename: agentbookable-com-services-api-openapi.yml
  format: yaml
  label: Agentbookable Services API
  slug: agentbookable-com-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-services-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: typically name and email; phone when the service requires or allows it
  - category: behavioral
    text: search queries and business/service metadata from our public registry
  - category: identifying
    text: identifiers clients send (e.g. actorRef)
  - category: device
    text: standard request logs for rate limits, abuse prevention, and audit
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate limits and abuse prevention
    text: standard request logs for rate limits, abuse prevention, and audit
  - purpose: operate service, disputes, legal obligations
    text: Booking records and audit/consent logs are kept as needed to operate the service, handle disputes, and meet legal obligations.
  retention:
  - period: ~15 minutes
    scope: drafts and mandates
    text: Drafts and mandates are short-lived (slots ~60s TTL; mandates ~15 minutes, single-use).
  - period: briefly
    scope: request logs
    text: Request logs may be retained briefly for security and rate limiting.
  rights:
  - right: decline consent
    text: Do not consent → we do not create a booking.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentbookable
provenance_date: '2026-11-09'
provider_name: Agentbookable
provider_slug: agentbookable-com
slug: agentbookable-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentbookable-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentbookable.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentbookable\naid: agentbookable-com\nurl: https://agentbookable.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: typically name and email; phone when the service requires or allows it\n- category: behavioral\n  text: search queries and business/service metadata from our public registry\n- category: identifying\n  text: identifiers clients send (e.g. actorRef)\n- category: device\n  text: standard request logs for rate limits, abuse prevention, and audit\npurposes:\n- purpose: rate limits and abuse prevention\n  text: standard request\
  \ logs for rate limits, abuse prevention, and audit\n- purpose: operate service, disputes, legal obligations\n  text: Booking records and audit/consent logs are kept as needed to operate the service, handle disputes, and meet\n    legal obligations.\nretention:\n- scope: drafts and mandates\n  period: ~15 minutes\n  text: Drafts and mandates are short-lived (slots ~60s TTL; mandates ~15 minutes, single-use).\n- scope: request logs\n  period: briefly\n  text: Request logs may be retained briefly for security and rate limiting.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: decline consent\n  text: Do not consent → we do not create a booking.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentbookable-com/privacy/agentbookable-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Agentbookable's own page on 2026-11-09.
synthetic: false
tags:
- Booking
- Artificial Intelligence
- Scheduling
- Integration
- Automation
- Company
---
