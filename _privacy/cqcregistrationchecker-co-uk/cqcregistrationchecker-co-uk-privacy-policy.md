---
api_specs:
- filename: cqcregistrationchecker-co-uk-enquiry-api-openapi.yml
  format: yaml
  label: CQC Registration Checker Enquiry API
  slug: cqcregistrationchecker-co-uk-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqcregistrationchecker-co-uk/openapi/cqcregistrationchecker-co-uk-enquiry-api-openapi.yml
- filename: cqcregistrationchecker-co-uk-guide-api-openapi.yml
  format: yaml
  label: CQC Registration Checker Guide API
  slug: cqcregistrationchecker-co-uk-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqcregistrationchecker-co-uk/openapi/cqcregistrationchecker-co-uk-guide-api-openapi.yml
- filename: cqcregistrationchecker-co-uk-mcp-api-openapi.yml
  format: yaml
  label: CQC Registration Checker MCP API
  slug: cqcregistrationchecker-co-uk-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqcregistrationchecker-co-uk/openapi/cqcregistrationchecker-co-uk-mcp-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when
  - category: communication
    text: replies to enquiries are stored with the enquiry
  - category: behavioral
    text: We measure pages, referrers, device class and tool usage server-side
  deletion:
    route: email enquiries@cqcregistrationchecker.co.uk with the address you used
    text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email enquiries@cqcregistrationchecker.co.uk with the address you used.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer enquiries
    text: we store the details you enter (with a timestamp and the page you sent it from) to answer it
  - purpose: pass enquiry to a provider
    text: where you ask us to, to pass it to a relevant provider
  - purpose: email updates
    text: We email you only about what that sentence names.
  - purpose: aggregate analytics
    text: We measure pages, referrers, device class and tool usage server-side
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
  - period: null
    scope: email updates
    text: 'Email updates: kept while you are subscribed.'
  - period: 6 years after the enquiry is deleted
    scope: consent records
    text: 'Consent records (which form, the wording you agreed to, and when): kept for 6 years after the enquiry is deleted, as evidence of the lawful basis, then deleted.'
  - period: indefinitely
    scope: aggregate analytics
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
    text: The controller of the personal data on this site is Ellul Solutions Ltd
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
name: CQC Registration Checker
provenance_date: '2026-11-09'
provider_name: CQC Registration Checker
provider_slug: cqcregistrationchecker-co-uk
slug: cqcregistrationchecker-co-uk-privacy-policy
source_date: '2026-11-09'
source_filename: cqcregistrationchecker-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cqcregistrationchecker.co.uk/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CQC Registration Checker\naid: cqcregistrationchecker-co-uk\nurl: https://cqcregistrationchecker.co.uk/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd\ndata_categories:\n- category: contact\n  text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when\n- category: communication\n  text: replies to enquiries are stored with the enquiry\n- category: behavioral\n  text: We measure pages, referrers, device class and tool usage server-side\npurposes:\n- purpose:\
  \ answer enquiries\n  text: we store the details you enter (with a timestamp and the page you sent it from) to answer it\n- purpose: pass enquiry to a provider\n  text: where you ask us to, to pass it to a relevant provider\n- purpose: email updates\n  text: We email you only about what that sentence names.\n- purpose: aggregate analytics\n  text: We measure pages, referrers, device class and tool usage server-side\nretention:\n- scope: enquiries\n  period: 24 months\n  text: 'Enquiries: 24 months from when you send them, then deleted.'\n- scope: raw inbound email\n  period: 12 months\n  text: 'Raw inbound email: 12 months, then deleted.'\n- scope: unconfirmed sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: email updates\n  period: null\n  text: 'Email updates: kept while you are subscribed.'\n- scope: consent records\n  period: 6 years after the enquiry is deleted\n  text: 'Consent records (which form, the wording you agreed to, and when):\
  \ kept for 6 years after the enquiry is\n    deleted, as evidence of the lawful basis, then deleted.'\n- scope: aggregate analytics\n  period: indefinitely\n  text: 'Aggregate, anonymous analytics: kept indefinitely (they identify no one).'\nresidency:\n- region: EU\n  text: All personal data is stored in the EU (Cloudflare EU jurisdiction storage).\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use service providers to host and store this site and its data, to route email, and to help us read and\n    answer enquiries, including AI tools.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email enquiries@cqcregistrationchecker.co.uk with the address you used\n  text: 'You can ask for a copy of your data, ask us to correct it, or ask us to delete it, at any time: email enquiries@cqcregistrationchecker.co.uk\n    with the address you used.'\nrights:\n- right: access\n  text: You can ask for a copy of your data\n- right: rectification\n  text: ask us to correct\
  \ it\n- right: erasure\n  text: ask us to delete it\n- right: complaint to ICO\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell data, run third-party advertising, or load third-party scripts on this site.\n"
source_yaml_url: https://artifacts.apis.io/cqcregistrationchecker-co-uk/privacy/cqcregistrationchecker-co-uk-privacy-policy.yml
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
summary_line: 22 quoted statements, read from CQC Registration Checker's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Care Quality Commission
- Regulatory Compliance
- Social Care
- United Kingdom
- Datasets
---
