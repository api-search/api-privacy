---
api_specs:
- filename: clubgrants-co-uk-enquiry-api-openapi.yml
  format: yaml
  label: Club Grants Enquiry API
  slug: clubgrants-co-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clubgrants-co-uk/openapi/clubgrants-co-uk-enquiry-api-openapi.yml
- filename: clubgrants-co-uk-guide-api-openapi.yml
  format: yaml
  label: Club Grants Guide API
  slug: clubgrants-co-uk-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clubgrants-co-uk/openapi/clubgrants-co-uk-guide-api-openapi.yml
- filename: clubgrants-co-uk-mcp-api-openapi.yml
  format: yaml
  label: Club Grants MCP API
  slug: clubgrants-co-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clubgrants-co-uk/openapi/clubgrants-co-uk-mcp-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Enquiry forms : if you send an enquiry, we store the details you enter (with a timestamp and the page you sent it from) to answer it'
  - category: contact
    text: 'Email updates : If you sign up for updates from this site (the box at the foot of a page, or the tick on an enquiry form), we store your email address'
  - category: device
    text: We measure pages, referrers, device class and tool usage server-side; no cookies are set for measurement, no identifiers are stored
  deletion:
    route: Email contact@clubgrants.co.uk with the address you used
    text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email contact@clubgrants.co.uk with the address you used.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Answering enquiries
    text: we store the details you enter (with a timestamp and the page you sent it from) to answer it
  - purpose: Passing enquiry to relevant provider
    text: where you ask us to, to pass it to a relevant provider
  - purpose: Email updates
    text: We email you only about what that sentence names.
  - purpose: Aggregate analytics
    text: We measure pages, referrers, device class and tool usage server-side
  residency:
  - region: EU
    text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).
  retention:
  - period: 24 months
    scope: Enquiries
    text: 'Enquiries: 24 months from when you send them, then deleted.'
  - period: 12 months
    scope: Raw inbound email
    text: 'Raw inbound email: 12 months, then deleted.'
  - period: 30 days
    scope: Unconfirmed email sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: 6 years
    scope: Consent records
    text: 'Consent records (which form, the wording you agreed to, and when): kept for 6 years after the enquiry is deleted'
  - period: indefinitely
    scope: Aggregate analytics
    text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'
  rights:
  - right: Access
    text: You can ask for a copy of your data
  - right: Rectification
    text: ask us to correct it
  - right: Erasure
    text: ask us to delete it, at any time
  - right: Complaint to ICO
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House)
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
name: Club Grants
provenance_date: '2026-11-09'
provider_name: Club Grants
provider_slug: clubgrants-co-uk
slug: clubgrants-co-uk-privacy-policy
source_date: '2026-11-09'
source_filename: clubgrants-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clubgrants.co.uk/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Club Grants\naid: clubgrants-co-uk\nurl: https://clubgrants.co.uk/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House)\ndata_categories:\n- category: contact\n  text: 'Enquiry forms : if you send an enquiry, we store the details you enter (with a timestamp and the page you\n    sent it from) to answer it'\n- category: contact\n  text: 'Email updates : If you sign up for updates from this site (the box at the foot of a page, or the tick on\n  \
  \  an enquiry form), we store your email address'\n- category: device\n  text: We measure pages, referrers, device class and tool usage server-side; no cookies are set for measurement,\n    no identifiers are stored\npurposes:\n- purpose: Answering enquiries\n  text: we store the details you enter (with a timestamp and the page you sent it from) to answer it\n- purpose: Passing enquiry to relevant provider\n  text: where you ask us to, to pass it to a relevant provider\n- purpose: Email updates\n  text: We email you only about what that sentence names.\n- purpose: Aggregate analytics\n  text: We measure pages, referrers, device class and tool usage server-side\nretention:\n- scope: Enquiries\n  period: 24 months\n  text: 'Enquiries: 24 months from when you send them, then deleted.'\n- scope: Raw inbound email\n  period: 12 months\n  text: 'Raw inbound email: 12 months, then deleted.'\n- scope: Unconfirmed email sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after\
  \ 30 days.\n- scope: Consent records\n  period: 6 years\n  text: 'Consent records (which form, the wording you agreed to, and when): kept for 6 years after the enquiry is\n    deleted'\n- scope: Aggregate analytics\n  period: indefinitely\n  text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'\nresidency:\n- region: EU\n  text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@clubgrants.co.uk with the address you used\n  text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email contact@clubgrants.co.uk\n    with the address you used.'\nrights:\n- right: Access\n  text: You can ask for a copy of your data\n- right: Rectification\n  text: ask us to correct it\n- right: Erasure\n  text: ask us to delete it, at any time\n- right: Complaint to\
  \ ICO\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell data, run third-party advertising, or load third-party scripts on this site.\n"
source_yaml_url: https://artifacts.apis.io/clubgrants-co-uk/privacy/clubgrants-co-uk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Club Grants's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grants
- Funding
- Sports
- Nonprofit
- Open Data
- United Kingdom
- MCP
---
