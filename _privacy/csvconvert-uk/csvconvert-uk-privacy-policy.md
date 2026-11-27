---
api_specs:
- filename: csvconvert-uk-enquiry-api-openapi.yml
  format: yaml
  label: CSV Convert Enquiry API
  slug: csvconvert-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/csvconvert-uk/openapi/csvconvert-uk-enquiry-api-openapi.yml
- filename: csvconvert-uk-guide-api-openapi.yml
  format: yaml
  label: CSV Convert Guide API
  slug: csvconvert-uk-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/csvconvert-uk/openapi/csvconvert-uk-guide-api-openapi.yml
- filename: csvconvert-uk-mcp-api-openapi.yml
  format: yaml
  label: CSV Convert MCP API
  slug: csvconvert-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/csvconvert-uk/openapi/csvconvert-uk-mcp-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when.
  - category: communication
    text: replies to enquiries are stored with the enquiry.
  - category: behavioral
    text: We measure pages, referrers, device class and tool usage server-side
  deletion:
    route: email request to hello@csvconvert.uk
    text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email hello@csvconvert.uk with the address you used.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer enquiries and pass them to a provider
    text: we store the details you enter (with a timestamp and the page you sent it from) to answer it and, where you ask us to, to pass it to a relevant provider.
  - purpose: aggregate analytics
    text: 'Analytics : first-party, cookieless and aggregate.'
  - purpose: email updates
    text: We email you only about what that sentence names.
  residency:
  - region: EU
    text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).
  retention:
  - period: 24 months
    scope: enquiries
    text: 'Enquiries: 24 months from when you send them, then deleted.'
  - period: 12 months
    scope: raw inbound email
    text: 'Raw inbound email: 12 months, then deleted.'
  - period: null
    scope: email updates
    text: 'Email updates: kept while you are subscribed.'
  - period: 30 days
    scope: unconfirmed sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: null
    scope: consent records
    text: 'Consent records (which form, the wording you agreed to, and when): kept for 6 years after the enquiry is deleted, as evidence of the lawful basis, then deleted.'
  - period: indefinitely
    scope: aggregate anonymous analytics
    text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'
  rights:
  - right: access
    text: You can ask for a copy of your data
  - right: rectification
    text: ask us to correct it
  - right: erasure
    text: ask us to delete it
  - right: complain to ICO
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell data, run third-party advertising, or load third-party scripts on this site.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CSV Convert
provenance_date: '2026-11-09'
provider_name: CSV Convert
provider_slug: csvconvert-uk
slug: csvconvert-uk-privacy-policy
source_date: '2026-11-09'
source_filename: csvconvert-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://csvconvert.uk/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CSV Convert\naid: csvconvert-uk\nurl: https://csvconvert.uk/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.\ndata_categories:\n- category: contact\n  text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when.\n- category: communication\n  text: replies to enquiries are stored with the enquiry.\n- category: behavioral\n  text: We\
  \ measure pages, referrers, device class and tool usage server-side\npurposes:\n- purpose: answer enquiries and pass them to a provider\n  text: we store the details you enter (with a timestamp and the page you sent it from) to answer it and, where\n    you ask us to, to pass it to a relevant provider.\n- purpose: aggregate analytics\n  text: 'Analytics : first-party, cookieless and aggregate.'\n- purpose: email updates\n  text: We email you only about what that sentence names.\nretention:\n- scope: enquiries\n  period: 24 months\n  text: 'Enquiries: 24 months from when you send them, then deleted.'\n- scope: raw inbound email\n  period: 12 months\n  text: 'Raw inbound email: 12 months, then deleted.'\n- scope: email updates\n  period: null\n  text: 'Email updates: kept while you are subscribed.'\n- scope: unconfirmed sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: consent records\n  period: null\n  text: 'Consent records (which form, the\
  \ wording you agreed to, and when): kept for 6 years after the enquiry is\n    deleted, as evidence of the lawful basis, then deleted.'\n- scope: aggregate anonymous analytics\n  period: indefinitely\n  text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'\nresidency:\n- region: EU\n  text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to hello@csvconvert.uk\n  text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email hello@csvconvert.uk\n    with the address you used.'\nrights:\n- right: access\n  text: You can ask for a copy of your data\n- right: rectification\n  text: ask us to correct it\n- right: erasure\n  text: ask us to delete it\n- right: complain to ICO\n  text: You can complain to the Information Commissioner's Office (ico.org.uk)\
  \ in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell data, run third-party advertising, or load third-party scripts on this site.\n"
source_yaml_url: https://artifacts.apis.io/csvconvert-uk/privacy/csvconvert-uk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from CSV Convert's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CSV
- PDF
- Data Conversion
- Data Extraction
- OCR
- United Kingdom
- Data Protection
---
