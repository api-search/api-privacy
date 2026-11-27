---
api_specs:
- filename: jithox-com-iban-api-openapi.yml
  format: yaml
  label: jithox-com Iban API
  slug: jithox-com-iban-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-iban-api-openapi.yml
- filename: jithox-com-invoice-api-openapi.yml
  format: yaml
  label: jithox-com Invoice API
  slug: jithox-com-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-invoice-api-openapi.yml
- filename: jithox-com-payment-api-openapi.yml
  format: yaml
  label: jithox-com Payment API
  slug: jithox-com-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-payment-api-openapi.yml
- filename: jithox-com-peppol-api-openapi.yml
  format: yaml
  label: jithox-com Peppol API
  slug: jithox-com-peppol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-peppol-api-openapi.yml
- filename: jithox-com-vat-api-openapi.yml
  format: yaml
  label: jithox-com Vat API
  slug: jithox-com-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jithox-com/openapi/jithox-com-vat-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Business identifiers, IBANs, names and invoice text can be personal data.
  - category: financial
    text: Your business details (name, VAT number, address, IBAN) that you enter once for your invoices.
  - category: device
    text: To count them we take your IP address and keep the first 16 characters of its SHA-256 hash, with a counter.
  - category: communication
    text: The messages you paste or forward, and the invoices, drafts and questions prepared from them.
  deletion:
    route: email request to info.jithox@gmail.com
    text: You can ask us to delete data via info.jithox@gmail.com; we assess each request per data category.
  dpa:
    available: true
    text: The data processing agreement names every sub-processor and is signed on request.
    url: null
  purposes:
  - purpose: answer read-only checks
    text: It processes the business identifiers a call submits — VAT numbers, Peppol participant ids, invoice documents — to answer that call.
  - purpose: limit abuse
    text: To limit abuse, each caller may send up to 30 requests per minute.
  - purpose: count usage
    text: We use it to count how often the entrance is used and with which kind of client; we do not combine it into profiles.
  residency:
  - region: Frankfurt
    text: Vercel compute is configured for Frankfurt.
  retention:
  - period: 60 seconds
    scope: rate-limit hash and counter
    text: The counter and hash apply to a window of 60 seconds.
  - period: 30 days
    scope: hosting access and error logs at Vercel
    text: for our plan, Vercel's documentation gives a retention of at most 30 days for these logs
  - period: 30 days
    scope: first-party funnel rows
    text: 'First-party funnel rows: the sweep selects rows older than 30 days.'
  - period: 90 days
    scope: missed-call rows
    text: 'Missed-call rows: the sweep selects rows older than 90 days.'
  - period: null
    scope: accounts, usage, payment metadata, invoices, approval records
    text: 'Accounts, credentials, usage, payment metadata, invoices and approval/receipt records: we have no fixed retention period.'
  rights:
  - right: deletion
    text: You can ask us to delete data via info.jithox@gmail.com
  - right: access
    text: For questions, access or deletion, write to info.jithox@gmail.com; a person reads every message and we answer within 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No selling of your data, and no advertising network embedded.
  subprocessors:
    text: The data processing agreement names every sub-processor and is signed on request.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: jithox-com
provenance_date: '2026-11-09'
provider_name: jithox-com
provider_slug: jithox-com
slug: jithox-com-privacy-policy
source_date: '2026-11-09'
source_filename: jithox-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jithox.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: jithox-com\naid: jithox-com\nurl: https://jithox.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Business identifiers, IBANs, names and invoice text can be personal data.\n- category: financial\n  text: Your business details (name, VAT number, address, IBAN) that you enter once for your invoices.\n- category: device\n  text: To count them we take your IP address and keep the first 16 characters of its SHA-256 hash, with a counter.\n- category: communication\n  text: The messages you paste or forward, and the invoices, drafts\
  \ and questions prepared from them.\npurposes:\n- purpose: answer read-only checks\n  text: It processes the business identifiers a call submits — VAT numbers, Peppol participant ids, invoice documents\n    — to answer that call.\n- purpose: limit abuse\n  text: To limit abuse, each caller may send up to 30 requests per minute.\n- purpose: count usage\n  text: We use it to count how often the entrance is used and with which kind of client; we do not combine it into\n    profiles.\nretention:\n- scope: rate-limit hash and counter\n  period: 60 seconds\n  text: The counter and hash apply to a window of 60 seconds.\n- scope: hosting access and error logs at Vercel\n  period: 30 days\n  text: for our plan, Vercel's documentation gives a retention of at most 30 days for these logs\n- scope: first-party funnel rows\n  period: 30 days\n  text: 'First-party funnel rows: the sweep selects rows older than 30 days.'\n- scope: missed-call rows\n  period: 90 days\n  text: 'Missed-call rows: the sweep\
  \ selects rows older than 90 days.'\n- scope: accounts, usage, payment metadata, invoices, approval records\n  period: null\n  text: 'Accounts, credentials, usage, payment metadata, invoices and approval/receipt records: we have no fixed\n    retention period.'\nresidency:\n- region: Frankfurt\n  text: Vercel compute is configured for Frankfurt.\ntransfers: []\nsubprocessors:\n  url: null\n  text: The data processing agreement names every sub-processor and is signed on request.\ndpa:\n  available: true\n  url: null\n  text: The data processing agreement names every sub-processor and is signed on request.\ndeletion:\n  route: email request to info.jithox@gmail.com\n  text: You can ask us to delete data via info.jithox@gmail.com; we assess each request per data category.\nrights:\n- right: deletion\n  text: You can ask us to delete data via info.jithox@gmail.com\n- right: access\n  text: For questions, access or deletion, write to info.jithox@gmail.com; a person reads every message and we\
  \ answer\n    within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: No selling of your data, and no advertising network embedded.\n"
source_yaml_url: https://artifacts.apis.io/jithox-com/privacy/jithox-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from jithox-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Back Office
- Tools
---
