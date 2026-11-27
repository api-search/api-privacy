---
api_specs:
- filename: rdapapi-io-asn-api-openapi.yml
  format: yaml
  label: rdapapi-io ASN API
  slug: rdapapi-io-asn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-asn-api-openapi.yml
- filename: rdapapi-io-domain-api-openapi.yml
  format: yaml
  label: rdapapi-io Domain API
  slug: rdapapi-io-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-domain-api-openapi.yml
- filename: rdapapi-io-entity-api-openapi.yml
  format: yaml
  label: rdapapi-io Entity API
  slug: rdapapi-io-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-entity-api-openapi.yml
- filename: rdapapi-io-health-api-openapi.yml
  format: yaml
  label: rdapapi-io Health API
  slug: rdapapi-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-health-api-openapi.yml
- filename: rdapapi-io-ip-api-openapi.yml
  format: yaml
  label: rdapapi-io IP API
  slug: rdapapi-io-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-ip-api-openapi.yml
- filename: rdapapi-io-nameserver-api-openapi.yml
  format: yaml
  label: rdapapi-io Nameserver API
  slug: rdapapi-io-nameserver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-nameserver-api-openapi.yml
- filename: rdapapi-io-tlds-api-openapi.yml
  format: yaml
  label: rdapapi-io TLDs API
  slug: rdapapi-io-tlds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-tlds-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address (provided during registration)
  - category: financial
    text: 'the billing details you enter for invoices: name, address, country and VAT number'
  - category: financial
    text: Payment information is processed and stored by Stripe .
  - category: behavioral
    text: 'API request logs: query type, queried domain, response time, cache status, and timestamp.'
  - category: device
    text: The IP addresses your account connects from when you register, log in, or call the API or MCP server
  deletion:
    route: Settings page in dashboard
    text: You may delete your account at any time from the Settings page in your dashboard.
  dpa:
    available: true
    text: Business customers subject to GDPR Article 28 may rely on our Data Processing Agreement
    url: null
  purposes:
  - purpose: provide and maintain the Service
    text: To provide and maintain the Service.
  - purpose: enforce rate limits and usage quotas
    text: To enforce rate limits and usage quotas.
  - purpose: process payments and manage subscriptions
    text: To process payments and manage subscriptions.
  - purpose: detect and prevent abuse
    text: To detect and prevent abuse.
  residency:
  - region: EU
    text: All production data is stored in the European Union.
  retention:
  - period: while your account is active
    scope: account data
    text: Account data is retained while your account is active.
  - period: 400 days
    scope: API request logs
    text: API request logs are retained, linked to your user identifier, for 400 days.
  - period: 12 months
    scope: account IP addresses
    text: Account IP addresses are deleted 12 months after they were last seen, or with your account.
  - period: 10 years
    scope: accounting records
    text: Accounting records (invoices, payment history) are retained for 10 years, as required by French commercial law.
  rights:
  - right: access, correct, or delete
    text: Access, correct, or delete your personal data.
  - right: export
    text: Export your data in a portable format.
  - right: restrict or object
    text: Restrict or object to processing.
  - right: withdraw consent
    text: Withdraw consent for data processing at any time.
  - right: lodge complaint
    text: Lodge a complaint with a supervisory authority.
  role:
    text: The data controller is FEELTECH , a French SARL
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'We use the subprocessors listed below, each bound by a data processing agreement and appropriate security commitments:'
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers to subprocessors outside the EU (Cloudflare, Backblaze, Mailgun) are governed by the European Commission Standard Contractual Clauses (SCCs, 2021/914).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: rdapapi-io
provenance_date: '2026-11-10'
provider_name: rdapapi-io
provider_slug: rdapapi-io
slug: rdapapi-io-privacy-policy
source_date: '2026-11-10'
source_filename: rdapapi-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rdapapi.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rdapapi-io\naid: rdapapi-io\nurl: https://rdapapi.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is FEELTECH , a French SARL\ndata_categories:\n- category: identifying\n  text: Name and email address (provided during registration)\n- category: financial\n  text: 'the billing details you enter for invoices: name, address, country and VAT number'\n- category: financial\n  text: Payment information is processed and stored by Stripe .\n- category: behavioral\n  text: 'API request logs: query type, queried domain, response time, cache status, and timestamp.'\n- category:\
  \ device\n  text: The IP addresses your account connects from when you register, log in, or call the API or MCP server\npurposes:\n- purpose: provide and maintain the Service\n  text: To provide and maintain the Service.\n- purpose: enforce rate limits and usage quotas\n  text: To enforce rate limits and usage quotas.\n- purpose: process payments and manage subscriptions\n  text: To process payments and manage subscriptions.\n- purpose: detect and prevent abuse\n  text: To detect and prevent abuse.\nretention:\n- scope: account data\n  period: while your account is active\n  text: Account data is retained while your account is active.\n- scope: API request logs\n  period: 400 days\n  text: API request logs are retained, linked to your user identifier, for 400 days.\n- scope: account IP addresses\n  period: 12 months\n  text: Account IP addresses are deleted 12 months after they were last seen, or with your account.\n- scope: accounting records\n  period: 10 years\n  text: Accounting records\
  \ (invoices, payment history) are retained for 10 years, as required by French commercial\n    law.\nresidency:\n- region: EU\n  text: All production data is stored in the European Union.\ntransfers:\n- mechanism: SCC\n  text: Transfers to subprocessors outside the EU (Cloudflare, Backblaze, Mailgun) are governed by the European\n    Commission Standard Contractual Clauses (SCCs, 2021/914).\nsubprocessors:\n  url: null\n  text: 'We use the subprocessors listed below, each bound by a data processing agreement and appropriate security\n    commitments:'\ndpa:\n  available: true\n  url: null\n  text: Business customers subject to GDPR Article 28 may rely on our Data Processing Agreement\ndeletion:\n  route: Settings page in dashboard\n  text: You may delete your account at any time from the Settings page in your dashboard.\nrights:\n- right: access, correct, or delete\n  text: Access, correct, or delete your personal data.\n- right: export\n  text: Export your data in a portable format.\n\
  - right: restrict or object\n  text: Restrict or object to processing.\n- right: withdraw consent\n  text: Withdraw consent for data processing at any time.\n- right: lodge complaint\n  text: Lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/rdapapi-io/privacy/rdapapi-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from rdapapi-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- RDAP
- Domain
- WHOIS
---
