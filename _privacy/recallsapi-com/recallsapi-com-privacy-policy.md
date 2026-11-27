---
api_specs:
- filename: recallsapi-com-account-api-openapi.yml
  format: yaml
  label: recallsapi-com Account API
  slug: recallsapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-account-api-openapi.yml
- filename: recallsapi-com-alerts-api-openapi.yml
  format: yaml
  label: recallsapi-com Alerts API
  slug: recallsapi-com-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-alerts-api-openapi.yml
- filename: recallsapi-com-billing-api-openapi.yml
  format: yaml
  label: recallsapi-com Billing API
  slug: recallsapi-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-billing-api-openapi.yml
- filename: recallsapi-com-catalogs-api-openapi.yml
  format: yaml
  label: recallsapi-com Catalogs API
  slug: recallsapi-com-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-catalogs-api-openapi.yml
- filename: recallsapi-com-check-api-openapi.yml
  format: yaml
  label: recallsapi-com Check API
  slug: recallsapi-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-check-api-openapi.yml
- filename: recallsapi-com-credits-api-openapi.yml
  format: yaml
  label: recallsapi-com Credits API
  slug: recallsapi-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-credits-api-openapi.yml
- filename: recallsapi-com-health-api-openapi.yml
  format: yaml
  label: recallsapi-com Health API
  slug: recallsapi-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-health-api-openapi.yml
- filename: recallsapi-com-keys-api-openapi.yml
  format: yaml
  label: recallsapi-com Keys API
  slug: recallsapi-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-keys-api-openapi.yml
- filename: recallsapi-com-mcp-api-openapi.yml
  format: yaml
  label: recallsapi-com MCP API
  slug: recallsapi-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-mcp-api-openapi.yml
- filename: recallsapi-com-recalls-api-openapi.yml
  format: yaml
  label: recallsapi-com Recalls API
  slug: recallsapi-com-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-recalls-api-openapi.yml
- filename: recallsapi-com-receipts-api-openapi.yml
  format: yaml
  label: recallsapi-com Receipts API
  slug: recallsapi-com-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-receipts-api-openapi.yml
- filename: recallsapi-com-signals-api-openapi.yml
  format: yaml
  label: recallsapi-com Signals API
  slug: recallsapi-com-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-signals-api-openapi.yml
- filename: recallsapi-com-vehicles-api-openapi.yml
  format: yaml
  label: recallsapi-com Vehicles API
  slug: recallsapi-com-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-vehicles-api-openapi.yml
- filename: recallsapi-com-well-known-api-openapi.yml
  format: yaml
  label: recallsapi-com .well Known API
  slug: recallsapi-com-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recallsapi-com/openapi/recallsapi-com-well-known-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your email address, a normalized form of it (lowercase, without a +tag)'
  - category: contact
    text: 'Account: your email address, a normalized form of it (lowercase, without a +tag)'
  - category: financial
    text: 'Billing: for paid plans, the Stripe customer and subscription identifiers'
  - category: financial
    text: for each payment we keep the on-chain transaction hash, amount, network, the paying wallet address, the API route and the time
  - category: device
    text: the browser, operating system and device type
  - category: behavioral
    text: a small Cloudflare script reports the page address, the referring page, page load times
  - category: location
    text: Cloudflare adds the visitor's country
  - category: communication
    text: 'Alert log: for each alert, the channel (email or webhook), the number of matches, whether it was sent and any error.'
  deletion:
    route: Email hello@recallsapi.com from the account's email address, or call DELETE /v1/catalogs/{id} for a catalog
    text: To delete your account and its data, or to get a copy of it, email hello@recallsapi.com from the account's email address.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service (sending your API key by email, matching, alerts, quotas and billing)
  - purpose: Security and abuse prevention
    text: to secure it and prevent abuse
  - purpose: Support requests
    text: to answer support requests
  - purpose: Account change notices
    text: to tell you about changes that affect your account
  residency:
  - region: United States
    text: 'Where data lives: on Cloudflare''s network, with the database stored in the western United States.'
  retention:
  - period: while your account exists, and deleted within 30 days of a deletion request or of the account being closed
    scope: Account, catalog and usage data
    text: 'Account, catalog and usage data: kept while your account exists, and deleted within 30 days of a deletion request or of the account being closed.'
  - period: 400 days
    scope: Check receipts
    text: 'Check receipts (the dated record of a check you request with receipt=1 ): 400 days, then deleted.'
  - period: 180 days
    scope: Crawler counters
    text: these totals are deleted after 180 days.
  - period: 12 months
    scope: Alert delivery log entries
    text: 'Alert delivery log entries: 12 months.'
  - period: 13 months
    scope: Daily call counts
    text: 'Daily call counts: 13 months, so you can compare a year.'
  - period: 90 days
    scope: Signup throttle rows
    text: 'Signup throttle rows (salted hashes, dated): deleted after 90 days.'
  - period: 7 years
    scope: Billing records
    text: 'Billing records held by Stripe and in our accounts, including renewal agreement records: 7 years, as tax law requires.'
  rights:
  - right: Access
    text: you can ask us to show you the personal data we hold about you
  - right: Correction
    text: correct it, delete it, give you a copy in a machine-readable form, or stop a particular use of it
  - right: Deletion
    text: correct it, delete it, give you a copy in a machine-readable form, or stop a particular use of it
  - right: Portability
    text: give you a copy in a machine-readable form
  - right: Objection to particular use
    text: stop a particular use of it
  - right: Complaint to authority
    text: If you are in a jurisdiction with a data protection authority, you can also complain to it.
  role:
    text: recallsapi.com is operated by PrimeZen LLC, 7601 Boulevard 26, OFC 10, North Richland Hills, TX 76180, United States ("we").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share it for advertising.
  subprocessors:
    text: Cloudflare hosts this website, the API, the MCP server and the database, delivers the emails we send (API keys and alerts), and counts website visits in aggregate (Cloudflare Web Analytics).
    url: null
  transfers:
  - mechanism: other
    text: If you use the service from outside the United States, your data is transferred to and processed in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: recallsapi-com
provenance_date: '2026-11-10'
provider_name: recallsapi-com
provider_slug: recallsapi-com
slug: recallsapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: recallsapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://recallsapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: recallsapi-com\naid: recallsapi-com\nurl: https://recallsapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: recallsapi.com is operated by PrimeZen LLC, 7601 Boulevard 26, OFC 10, North Richland Hills, TX 76180, United\n    States (\"we\").\ndata_categories:\n- category: identifying\n  text: 'Account: your email address, a normalized form of it (lowercase, without a +tag)'\n- category: contact\n  text: 'Account: your email address, a normalized form of it (lowercase, without a +tag)'\n- category: financial\n  text: 'Billing: for paid plans, the Stripe customer and subscription identifiers'\n\
  - category: financial\n  text: for each payment we keep the on-chain transaction hash, amount, network, the paying wallet address, the\n    API route and the time\n- category: device\n  text: the browser, operating system and device type\n- category: behavioral\n  text: a small Cloudflare script reports the page address, the referring page, page load times\n- category: location\n  text: Cloudflare adds the visitor's country\n- category: communication\n  text: 'Alert log: for each alert, the channel (email or webhook), the number of matches, whether it was sent and\n    any error.'\npurposes:\n- purpose: Provide the service\n  text: To provide the service (sending your API key by email, matching, alerts, quotas and billing)\n- purpose: Security and abuse prevention\n  text: to secure it and prevent abuse\n- purpose: Support requests\n  text: to answer support requests\n- purpose: Account change notices\n  text: to tell you about changes that affect your account\nretention:\n- scope: Account,\
  \ catalog and usage data\n  period: while your account exists, and deleted within 30 days of a deletion request or of the account being closed\n  text: 'Account, catalog and usage data: kept while your account exists, and deleted within 30 days of a deletion\n    request or of the account being closed.'\n- scope: Check receipts\n  period: 400 days\n  text: 'Check receipts (the dated record of a check you request with receipt=1 ): 400 days, then deleted.'\n- scope: Crawler counters\n  period: 180 days\n  text: these totals are deleted after 180 days.\n- scope: Alert delivery log entries\n  period: 12 months\n  text: 'Alert delivery log entries: 12 months.'\n- scope: Daily call counts\n  period: 13 months\n  text: 'Daily call counts: 13 months, so you can compare a year.'\n- scope: Signup throttle rows\n  period: 90 days\n  text: 'Signup throttle rows (salted hashes, dated): deleted after 90 days.'\n- scope: Billing records\n  period: 7 years\n  text: 'Billing records held by Stripe and\
  \ in our accounts, including renewal agreement records: 7 years, as tax\n    law requires.'\nresidency:\n- region: United States\n  text: 'Where data lives: on Cloudflare''s network, with the database stored in the western United States.'\ntransfers:\n- mechanism: other\n  text: If you use the service from outside the United States, your data is transferred to and processed in the\n    United States.\nsubprocessors:\n  url: null\n  text: Cloudflare hosts this website, the API, the MCP server and the database, delivers the emails we send (API\n    keys and alerts), and counts website visits in aggregate (Cloudflare Web Analytics).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@recallsapi.com from the account's email address, or call DELETE /v1/catalogs/{id} for a catalog\n  text: To delete your account and its data, or to get a copy of it, email hello@recallsapi.com from the account's\n    email address.\nrights:\n- right: Access\n  text: you can ask\
  \ us to show you the personal data we hold about you\n- right: Correction\n  text: correct it, delete it, give you a copy in a machine-readable form, or stop a particular use of it\n- right: Deletion\n  text: correct it, delete it, give you a copy in a machine-readable form, or stop a particular use of it\n- right: Portability\n  text: give you a copy in a machine-readable form\n- right: Objection to particular use\n  text: stop a particular use of it\n- right: Complaint to authority\n  text: If you are in a jurisdiction with a data protection authority, you can also complain to it.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/recallsapi-com/privacy/recallsapi-com-privacy-policy.yml
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
summary_line: 31 quoted statements, read from recallsapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recall
- E-Commerce
- Safety
- US-Agencies
---
