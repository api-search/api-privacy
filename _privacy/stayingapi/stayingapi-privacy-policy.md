---
api_specs:
- filename: stayingapi-account-api-openapi.yml
  format: yaml
  label: StayingAPI Account API
  slug: stayingapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-account-api-openapi.yml
- filename: stayingapi-data-api-openapi.yml
  format: yaml
  label: StayingAPI Data API
  slug: stayingapi-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-data-api-openapi.yml
- filename: stayingapi-jobs-api-openapi.yml
  format: yaml
  label: StayingAPI Jobs API
  slug: stayingapi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-jobs-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name (optional), email address, and any identity returned by a sign-in provider (Google or GitHub) when you use social sign-in.
  - category: financial
    text: Your subscription and top-up records and a Stripe customer identifier.
  - category: device
    text: the request’s IP address and user-agent
  - category: communication
    text: Messages you send us and their contents.
  - category: other
    text: Reviewer public display names and the free text of public reviews.
  - category: location
    text: approximate location derived from the IP address
  - category: behavioral
    text: Pages viewed, referrer, browser and device type
  deletion:
    route: email hello@stayingapi.com
    text: To exercise any of these, email hello@stayingapi.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide and operate the service — authenticate requests, run and normalize queries, meter credits, and return results.
  - purpose: Billing
    text: Billing — manage subscriptions, top-ups and the credit ledger through Stripe.
  - purpose: Security and abuse prevention
    text: Security, abuse prevention & reliability — verify email before live credits are usable, detect free-tier farming and leaked keys, enforce rate limits, and monitor for anomalies.
  - purpose: Legal compliance
    text: Legal compliance — respond to lawful requests, takedown notices and data-subject requests, and keep required financial records.
  residency:
  - region: EU
    text: EU data-residency for the data store is available as an Enterprise option.
  retention:
  - period: For the life of your account
    scope: Account data
    text: For the life of your account, then deleted on request
  - period: 90 days
    scope: Request IP and user-agent
    text: Identifiable for 90 days for security/abuse analytics.
  - period: 24 hours
    scope: Raw source payloads
    text: auto-expired within 24 hours
  - period: 30 minutes to 24 hours
    scope: Normalized cached results
    text: Short per-endpoint TTLs (30 minutes to 24 hours), then hard-expired
  rights:
  - right: access, rectify, erase, restrict, object, portability, withdraw consent
    text: you may have the right to access , rectify , erase (“be forgotten”), restrict or object to our processing, to data portability , and to withdraw consent.
  - right: complain to supervisory authority
    text: You also have the right to complain to your local supervisory authority.
  role:
    text: which is the controller of the personal data described in this policy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: We share it only with the service providers (“sub-processors”) below, each bound by a data-processing agreement
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the EU Standard Contractual Clauses (SCCs) and equivalent UK/Swiss transfer mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: StayingAPI
provenance_date: '2026-11-10'
provider_name: StayingAPI
provider_slug: stayingapi
slug: stayingapi-privacy-policy
source_date: '2026-11-10'
source_filename: stayingapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://stayingapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: StayingAPI\naid: stayingapi\nurl: https://stayingapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: which is the controller of the personal data described in this policy\ndata_categories:\n- category: identifying\n  text: Your name (optional), email address, and any identity returned by a sign-in provider (Google or GitHub)\n    when you use social sign-in.\n- category: financial\n  text: Your subscription and top-up records and a Stripe customer identifier.\n- category: device\n  text: the request’s IP address and user-agent\n- category: communication\n  text: Messages you send\
  \ us and their contents.\n- category: other\n  text: Reviewer public display names and the free text of public reviews.\n- category: location\n  text: approximate location derived from the IP address\n- category: behavioral\n  text: Pages viewed, referrer, browser and device type\npurposes:\n- purpose: Provide and operate the service\n  text: Provide and operate the service — authenticate requests, run and normalize queries, meter credits, and return\n    results.\n- purpose: Billing\n  text: Billing — manage subscriptions, top-ups and the credit ledger through Stripe.\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention & reliability — verify email before live credits are usable, detect free-tier\n    farming and leaked keys, enforce rate limits, and monitor for anomalies.\n- purpose: Legal compliance\n  text: Legal compliance — respond to lawful requests, takedown notices and data-subject requests, and keep required\n    financial records.\nretention:\n- scope:\
  \ Account data\n  period: For the life of your account\n  text: For the life of your account, then deleted on request\n- scope: Request IP and user-agent\n  period: 90 days\n  text: Identifiable for 90 days for security/abuse analytics.\n- scope: Raw source payloads\n  period: 24 hours\n  text: auto-expired within 24 hours\n- scope: Normalized cached results\n  period: 30 minutes to 24 hours\n  text: Short per-endpoint TTLs (30 minutes to 24 hours), then hard-expired\nresidency:\n- region: EU\n  text: EU data-residency for the data store is available as an Enterprise option.\ntransfers:\n- mechanism: SCC\n  text: we rely on the EU Standard Contractual Clauses (SCCs) and equivalent UK/Swiss transfer mechanisms\nsubprocessors:\n  url: null\n  text: We share it only with the service providers (“sub-processors”) below, each bound by a data-processing agreement\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@stayingapi.com\n  text: To exercise any of these,\
  \ email hello@stayingapi.com\nrights:\n- right: access, rectify, erase, restrict, object, portability, withdraw consent\n  text: you may have the right to access , rectify , erase (“be forgotten”), restrict or object to our processing,\n    to data portability , and to withdraw consent.\n- right: complain to supervisory authority\n  text: You also have the right to complain to your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/stayingapi/privacy/stayingapi-privacy-policy.yml
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
summary_line: 23 quoted statements, read from StayingAPI's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Hospitality
- accommodation-data
- hotel-api
- Vacation Rentals
- Short-Term Rental
- Airbnb
- Booking.com
- Vrbo
- google-hotels
- cross-ota-price-comparison
- Availability
- Reviews
- REST
- MCP
- Agent-Native
- OpenAPI
---
