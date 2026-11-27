---
api_specs:
- filename: mattercatalog-openapi-generated.yml
  format: yaml
  label: MatterCatalog API
  slug: mattercatalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattercatalog/openapi/_ae-authored/mattercatalog-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: If you enter your email address in a "Stay updated" form, we store that address, the page you signed up from and the date
  - category: identifying
    text: your name, email address and password are handled by Google Firebase Authentication
  - category: behavioral
    text: which pages are viewed and which retailer links are clicked
  - category: device
    text: the standard device and browser information Google Analytics collects
  - category: communication
    text: If you email us, we receive your email address and whatever you include in your message.
  deletion:
    route: Email team@mattercatalog.com
    text: To stop email updates or to ask us to delete your email address, account or price alerts, email team@mattercatalog.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Send email updates
    text: To send the email updates you asked for.
  - purpose: Run accounts, saved devices and price alerts
    text: To run accounts, saved devices and price alerts.
  - purpose: Understand page and link usefulness
    text: To understand which pages and links are useful, so we can improve the catalog.
  - purpose: Errors and abuse prevention
    text: To find and fix errors, and to prevent abuse.
  retention:
  - period: 30 days
    scope: Server logs for AI assistant connector
    text: Both logs are kept for 30 days.
  - period: up to 10 minutes
    scope: Requesting address in connector memory
    text: the connector keeps the requesting address in memory for up to 10 minutes and never writes it to its own log
  rights:
  - right: Opt out of Google Analytics
    text: You can block or delete cookies in your browser, or use the Google Analytics opt-out add-on.
  - right: Delete price alerts
    text: You can delete an alert at any time from your account.
  - right: Clear local browser data
    text: You can remove it at any time by clearing your browser's site data for mattercatalog.com.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not give your email address or account details to advertisers or retailers. We do not show display ads, and we do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MatterCatalog
provenance_date: '2026-11-10'
provider_name: MatterCatalog
provider_slug: mattercatalog
slug: mattercatalog-privacy-policy
source_date: '2026-11-10'
source_filename: mattercatalog-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mattercatalog.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MatterCatalog\naid: mattercatalog\nurl: https://mattercatalog.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: If you enter your email address in a \"Stay updated\" form, we store that address, the page you signed up\n    from and the date\n- category: identifying\n  text: your name, email address and password are handled by Google Firebase Authentication\n- category: behavioral\n  text: which pages are viewed and which retailer links are clicked\n- category: device\n  text: the standard device and browser information Google Analytics\
  \ collects\n- category: communication\n  text: If you email us, we receive your email address and whatever you include in your message.\npurposes:\n- purpose: Send email updates\n  text: To send the email updates you asked for.\n- purpose: Run accounts, saved devices and price alerts\n  text: To run accounts, saved devices and price alerts.\n- purpose: Understand page and link usefulness\n  text: To understand which pages and links are useful, so we can improve the catalog.\n- purpose: Errors and abuse prevention\n  text: To find and fix errors, and to prevent abuse.\nretention:\n- scope: Server logs for AI assistant connector\n  period: 30 days\n  text: Both logs are kept for 30 days.\n- scope: Requesting address in connector memory\n  period: up to 10 minutes\n  text: the connector keeps the requesting address in memory for up to 10 minutes and never writes it to its own\n    log\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: Email team@mattercatalog.com\n  text: To stop email updates or to ask us to delete your email address, account or price alerts, email team@mattercatalog.com.\nrights:\n- right: Opt out of Google Analytics\n  text: You can block or delete cookies in your browser, or use the Google Analytics opt-out add-on.\n- right: Delete price alerts\n  text: You can delete an alert at any time from your account.\n- right: Clear local browser data\n  text: You can remove it at any time by clearing your browser's site data for mattercatalog.com.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not give your email address or account details to advertisers or retailers. We do not show display\n    ads, and we do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/mattercatalog/privacy/mattercatalog-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from MatterCatalog's own page on 2026-11-10.
synthetic: false
tags:
- Matter
- Smart Home
- IoT
- Certification
- Directory
---
