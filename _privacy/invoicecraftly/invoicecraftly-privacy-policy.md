---
api_specs:
- filename: invoicecraftly-documents-api-openapi.yml
  format: yaml
  label: InvoiceCraftly Developer Document API Documents API
  slug: invoicecraftly-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicecraftly/openapi/invoicecraftly-documents-api-openapi.yml
- filename: invoicecraftly-structured-invoicing-api-openapi.yml
  format: yaml
  label: InvoiceCraftly Developer Document API Structured invoicing API
  slug: invoicecraftly-structured-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicecraftly/openapi/invoicecraftly-structured-invoicing-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: account identifier, name, email address, optional profile image, locale
  - category: contact
    text: email, category, rating, message, and consent
  - category: financial
    text: Invoice, client, line-item, payment, note, settings, and uploaded-logo data are saved on this device during ordinary editing.
  - category: device
    text: ordinary technical request, browser, device, and interaction information
  deletion:
    route: 'On-device documents: remove them from InvoiceCraftly or clear this site''s browser data; account deletion flow or privacy/data request; delete backup files from storage provider'
    text: Delete each copy where it is stored
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Personal Cloud backup
    text: When you choose Back up now , InvoiceCraftly creates a recovery copy of the current workspace and saves it to the connected provider.
  - purpose: AI extraction
    text: For pasted or typed text, the description you provide is sent to InvoiceCraftly's AI extraction service.
  - purpose: Company lookup
    text: The search value you enter is used to perform that lookup.
  - purpose: VAT number check
    text: The VAT country code and number you submit are sent to the European Commission's VIES service.
  - purpose: Analytics
    text: After consent, measurement can include page views, sanitized page paths, page categories, referral information, approved campaign labels, and product events
  retention:
  - period: up to 30 days
    scope: Sanitized raw first-party product events
    text: Sanitized raw first-party product events are intended to be retained for up to 30 days.
  - period: at least 13 months
    scope: Aggregate daily or weekly analytics counts
    text: Aggregate daily or weekly counts may be kept for at least 13 months for product and acquisition reporting.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: InvoiceCraftly Developer Document API
provenance_date: '2026-11-09'
provider_name: InvoiceCraftly Developer Document API
provider_slug: invoicecraftly
slug: invoicecraftly-privacy-policy
source_date: '2026-11-09'
source_filename: invoicecraftly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://invoicecraftly.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: InvoiceCraftly Developer Document API\naid: invoicecraftly\nurl: https://invoicecraftly.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: account identifier, name, email address, optional profile image, locale\n- category: contact\n  text: email, category, rating, message, and consent\n- category: financial\n  text: Invoice, client, line-item, payment, note, settings, and uploaded-logo data are saved on this device during\n    ordinary editing.\n- category: device\n  text: ordinary technical request, browser, device, and interaction\
  \ information\npurposes:\n- purpose: Personal Cloud backup\n  text: When you choose Back up now , InvoiceCraftly creates a recovery copy of the current workspace and saves\n    it to the connected provider.\n- purpose: AI extraction\n  text: For pasted or typed text, the description you provide is sent to InvoiceCraftly's AI extraction service.\n- purpose: Company lookup\n  text: The search value you enter is used to perform that lookup.\n- purpose: VAT number check\n  text: The VAT country code and number you submit are sent to the European Commission's VIES service.\n- purpose: Analytics\n  text: After consent, measurement can include page views, sanitized page paths, page categories, referral information,\n    approved campaign labels, and product events\nretention:\n- scope: Sanitized raw first-party product events\n  period: up to 30 days\n  text: Sanitized raw first-party product events are intended to be retained for up to 30 days.\n- scope: Aggregate daily or weekly analytics counts\n\
  \  period: at least 13 months\n  text: Aggregate daily or weekly counts may be kept for at least 13 months for product and acquisition reporting.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'On-device documents: remove them from InvoiceCraftly or clear this site''s browser data; account deletion\n    flow or privacy/data request; delete backup files from storage provider'\n  text: Delete each copy where it is stored\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/invoicecraftly/privacy/invoicecraftly-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 12 quoted statements, read from InvoiceCraftly Developer Document API's own page on 2026-11-09.
synthetic: false
tags:
- Invoicing
- Invoice Generator
- DocumentExport
- Payment QR
- CSV Import
- Company Lookup
---
