---
api_specs:
- filename: adrcourses-co-uk-enquiry-api-openapi.yml
  format: yaml
  label: ADR Courses Enquiry API
  slug: adrcourses-co-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adrcourses-co-uk/openapi/adrcourses-co-uk-enquiry-api-openapi.yml
- filename: adrcourses-co-uk-mcp-api-openapi.yml
  format: yaml
  label: ADR Courses MCP API
  slug: adrcourses-co-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adrcourses-co-uk/openapi/adrcourses-co-uk-mcp-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when
  - category: behavioral
    text: We measure pages, referrers, device class and tool usage server-side
  deletion:
    route: email quotes@adrcourses.co.uk
    text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email quotes@adrcourses.co.uk with the address you used.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: enquiry handling
    text: to answer it and, where you ask us to, to pass it to a relevant provider
  - purpose: email updates
    text: We email you only about what that sentence names.
  - purpose: analytics
    text: We measure pages, referrers, device class and tool usage server-side; no cookies are set for measurement
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
  - period: 30 days
    scope: unconfirmed sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: 6 years
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
  - right: complaint to ICO
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell data, run third-party advertising, or load third-party scripts on this site.
  subprocessors:
    text: We use service providers to host and store this site and its data, to route email, and to help us read and answer enquiries, including AI tools.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ADR Courses
provenance_date: '2026-11-09'
provider_name: ADR Courses
provider_slug: adrcourses-co-uk
slug: adrcourses-co-uk-privacy-policy
source_date: '2026-11-09'
source_filename: adrcourses-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adrcourses.co.uk/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ADR Courses\naid: adrcourses-co-uk\nurl: https://adrcourses.co.uk/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House), 14 Warfield Crescent, Waterlooville, England, PO7 7JP.\ndata_categories:\n- category: contact\n  text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when\n- category: behavioral\n  text: We measure pages, referrers, device class and tool usage server-side\npurposes:\n-\
  \ purpose: enquiry handling\n  text: to answer it and, where you ask us to, to pass it to a relevant provider\n- purpose: email updates\n  text: We email you only about what that sentence names.\n- purpose: analytics\n  text: We measure pages, referrers, device class and tool usage server-side; no cookies are set for measurement\nretention:\n- scope: enquiries\n  period: 24 months\n  text: 'Enquiries: 24 months from when you send them, then deleted.'\n- scope: raw inbound email\n  period: 12 months\n  text: 'Raw inbound email: 12 months, then deleted.'\n- scope: unconfirmed sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: consent records\n  period: 6 years\n  text: 'Consent records (which form, the wording you agreed to, and when): kept for 6 years after the enquiry is\n    deleted, as evidence of the lawful basis, then deleted.'\n- scope: aggregate anonymous analytics\n  period: indefinitely\n  text: 'Aggregate, anonymous analytics: kept\
  \ indefinitely (they identify no one).'\nresidency:\n- region: EU\n  text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use service providers to host and store this site and its data, to route email, and to help us read and\n    answer enquiries, including AI tools.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email quotes@adrcourses.co.uk\n  text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email quotes@adrcourses.co.uk\n    with the address you used.'\nrights:\n- right: access\n  text: You can ask for a copy of your data\n- right: rectification\n  text: ask us to correct it\n- right: erasure\n  text: ask us to delete it\n- right: complaint to ICO\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell data, run third-party\
  \ advertising, or load third-party scripts on this site.\n"
source_yaml_url: https://artifacts.apis.io/adrcourses-co-uk/privacy/adrcourses-co-uk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from ADR Courses's own page on 2026-11-09.
synthetic: false
tags:
- ADR
- Training
- United Kingdom
- Transportation
- Safety
---
