---
api_specs:
- filename: attestwire-com-billing-api-openapi.yml
  format: yaml
  label: Attestwire Billing API
  slug: attestwire-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-billing-api-openapi.yml
- filename: attestwire-com-diagnose-api-openapi.yml
  format: yaml
  label: Attestwire Diagnose API
  slug: attestwire-com-diagnose-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-diagnose-api-openapi.yml
- filename: attestwire-com-invoices-api-openapi.yml
  format: yaml
  label: Attestwire Invoices API
  slug: attestwire-com-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-invoices-api-openapi.yml
- filename: attestwire-com-keys-api-openapi.yml
  format: yaml
  label: Attestwire Keys API
  slug: attestwire-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-keys-api-openapi.yml
- filename: attestwire-com-meta-api-openapi.yml
  format: yaml
  label: Attestwire Meta API
  slug: attestwire-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-meta-api-openapi.yml
- filename: attestwire-com-peppol-api-openapi.yml
  format: yaml
  label: Attestwire Peppol API
  slug: attestwire-com-peppol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-peppol-api-openapi.yml
- filename: attestwire-com-recipient-api-openapi.yml
  format: yaml
  label: Attestwire Recipient API
  slug: attestwire-com-recipient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-recipient-api-openapi.yml
- filename: attestwire-com-records-api-openapi.yml
  format: yaml
  label: Attestwire Records API
  slug: attestwire-com-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-records-api-openapi.yml
- filename: attestwire-com-vat-api-openapi.yml
  format: yaml
  label: Attestwire Vat API
  slug: attestwire-com-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-vat-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: the address, the tier, and the SHA-256 hash of the key
  - category: contact
    text: Email address Lowercased, and used as the storage key, so a second submission updates nothing rather than creating a duplicate.
  - category: financial
    text: the billing email, address and any tax ID you give at checkout are held by Paddle
  - category: device
    text: Which assistant software connected, and its version, as it names itself (for example claude-code/2.1 ).
  - category: behavioral
    text: Which endpoint and method you called, and the HTTP status of the answer.
  deletion:
    route: Email hello@attestwire.com
    text: Email hello@attestwire.com from the address you signed up with, or just tell us which address to look for. We delete it and confirm.
  dpa:
    available: true
    text: 'If you need a GDPR Article 28 processor agreement, one is written: the data processing addendum .'
    url: null
  purposes:
  - purpose: Service usage understanding
    text: We read them ourselves, as totals and per key, to find the calls that fail and fix what makes them fail.
  - purpose: Replying to requests
    text: To reply to you about the thing you asked about, and nothing else.
  retention:
  - period: null
    scope: Invoice payloads sent to the API
    text: An invoice you send to api.attestwire.com is processed in memory and never stored .
  - period: 365 days
    scope: Validation records
    text: Records are deleted automatically 365 days after they are made.
  - period: three months
    scope: Usage entries and MCP feedback
    text: Usage entries and feedback are stored in Cloudflare Workers Analytics Engine , in the same Cloudflare account that runs the API, and are deleted automatically after three months .
  - period: null
    scope: Email alert records
    text: Until you ask us to remove it, or until the list has served its purpose and we delete the whole store, whichever comes first.
  rights:
  - right: access
    text: The GDPR also gives you the right to access the data we hold, correct it, object to the processing, receive it in a portable form, and lodge a complaint with your national supervisory authority.
  - right: erasure
    text: Until you ask us to remove it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, share or trade email addresses, and we send them to no marketing, CRM or advertising service.
  subprocessors:
    text: The full list, with what each one touches, is the subprocessor table on the security page .
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Attestwire
provenance_date: '2026-11-09'
provider_name: Attestwire
provider_slug: attestwire-com
slug: attestwire-com-privacy-policy
source_date: '2026-11-09'
source_filename: attestwire-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://attestwire.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Attestwire\naid: attestwire-com\nurl: https://attestwire.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the address, the tier, and the SHA-256 hash of the key\n- category: contact\n  text: Email address Lowercased, and used as the storage key, so a second submission updates nothing rather than\n    creating a duplicate.\n- category: financial\n  text: the billing email, address and any tax ID you give at checkout are held by Paddle\n- category: device\n  text: Which assistant software connected, and its version, as it names\
  \ itself (for example claude-code/2.1 ).\n- category: behavioral\n  text: Which endpoint and method you called, and the HTTP status of the answer.\npurposes:\n- purpose: Service usage understanding\n  text: We read them ourselves, as totals and per key, to find the calls that fail and fix what makes them fail.\n- purpose: Replying to requests\n  text: To reply to you about the thing you asked about, and nothing else.\nretention:\n- scope: Invoice payloads sent to the API\n  period: null\n  text: An invoice you send to api.attestwire.com is processed in memory and never stored .\n- scope: Validation records\n  period: 365 days\n  text: Records are deleted automatically 365 days after they are made.\n- scope: Usage entries and MCP feedback\n  period: three months\n  text: Usage entries and feedback are stored in Cloudflare Workers Analytics Engine , in the same Cloudflare account\n    that runs the API, and are deleted automatically after three months .\n- scope: Email alert records\n  period:\
  \ null\n  text: Until you ask us to remove it, or until the list has served its purpose and we delete the whole store, whichever\n    comes first.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The full list, with what each one touches, is the subprocessor table on the security page .\ndpa:\n  available: true\n  url: null\n  text: 'If you need a GDPR Article 28 processor agreement, one is written: the data processing addendum .'\ndeletion:\n  route: Email hello@attestwire.com\n  text: Email hello@attestwire.com from the address you signed up with, or just tell us which address to look for.\n    We delete it and confirm.\nrights:\n- right: access\n  text: The GDPR also gives you the right to access the data we hold, correct it, object to the processing, receive\n    it in a portable form, and lodge a complaint with your national supervisory authority.\n- right: erasure\n  text: Until you ask us to remove it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not\
  \ sell, rent, share or trade email addresses, and we send them to no marketing, CRM or advertising\n    service.\n"
source_yaml_url: https://artifacts.apis.io/attestwire-com/privacy/attestwire-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Attestwire's own page on 2026-11-09.
synthetic: false
tags:
- Attestwire
- e-invoice
- Validation
- XRechnung
- Peppol
- MCP
---
