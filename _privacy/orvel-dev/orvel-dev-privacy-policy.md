---
api_specs:
- filename: orvel-dev-e-invoicing-api-openapi.yml
  format: yaml
  label: orvel-dev E Invoicing API
  slug: orvel-dev-e-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orvel-dev/openapi/orvel-dev-e-invoicing-api-openapi.yml
- filename: orvel-dev-verification-api-openapi.yml
  format: yaml
  label: orvel-dev Verification API
  slug: orvel-dev-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orvel-dev/openapi/orvel-dev-verification-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Optional identifiers are pseudonymised separately for each product; they do not contain your email.
  - category: contact
    text: we process your email to respond and keep the correspondence as needed to handle your request
  - category: device
    text: Access logs (time, path, status, IP) may be retained up to 30 days for security and abuse prevention (legitimate interest).
  deletion:
    route: Contact privacy@orvel.dev about these records.
    text: Contact privacy@orvel.dev about these records.
  dpa:
    available: true
    text: under its DPA with EU standard contractual clauses
    url: null
  purposes:
  - purpose: operational statistics
    text: Orvel records operational events such as sign-in outcomes, completed operations, checkout progress, safe error categories and response times in its private product dashboard.
  - purpose: language selection
    text: A NEXT_LOCALE cookie remembers your language.
  - purpose: authentication
    text: Owner access uses a secure session cookie, orvel_admin_session, with a maximum duration of 30 days that can be renewed during use.
  - purpose: security and abuse prevention
    text: Access logs (time, path, status, IP) may be retained up to 30 days for security and abuse prevention (legitimate interest).
  residency:
  - region: Europe West (Amsterdam)
    text: Europe West region (Amsterdam)
  retention:
  - period: up to 90 days
    scope: operational statistics events
    text: These events are kept for up to 90 days, with scheduled deletion.
  - period: up to 30 days
    scope: access logs
    text: Access logs (time, path, status, IP) may be retained up to 30 days for security and abuse prevention (legitimate interest).
  - period: 30 days
    scope: owner session cookie
    text: with a maximum duration of 30 days that can be renewed during use
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: 'Access, rectification, erasure, restriction, portability, objection: write to hello@orvel.dev.'
  - right: complain to supervisory authority
    text: You may complain to the CNIL (cnil.fr).
  role:
    text: This policy describes how Orvel (“we”) processes personal data on orvel.dev.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data and we do not use it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: under its DPA with EU standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: orvel-dev
provenance_date: '2026-11-10'
provider_name: orvel-dev
provider_slug: orvel-dev
slug: orvel-dev-privacy-policy
source_date: '2026-11-10'
source_filename: orvel-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://orvel.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: orvel-dev\naid: orvel-dev\nurl: https://orvel.dev/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This policy describes how Orvel (“we”) processes personal data on orvel.dev.\ndata_categories:\n- category: identifying\n  text: Optional identifiers are pseudonymised separately for each product; they do not contain your email.\n- category: contact\n  text: we process your email to respond and keep the correspondence as needed to handle your request\n- category: device\n  text: Access logs (time, path, status, IP) may be retained up to 30 days for security and abuse prevention (legitimate\n\
  \    interest).\npurposes:\n- purpose: operational statistics\n  text: Orvel records operational events such as sign-in outcomes, completed operations, checkout progress, safe\n    error categories and response times in its private product dashboard.\n- purpose: language selection\n  text: A NEXT_LOCALE cookie remembers your language.\n- purpose: authentication\n  text: Owner access uses a secure session cookie, orvel_admin_session, with a maximum duration of 30 days that\n    can be renewed during use.\n- purpose: security and abuse prevention\n  text: Access logs (time, path, status, IP) may be retained up to 30 days for security and abuse prevention (legitimate\n    interest).\nretention:\n- scope: operational statistics events\n  period: up to 90 days\n  text: These events are kept for up to 90 days, with scheduled deletion.\n- scope: access logs\n  period: up to 30 days\n  text: Access logs (time, path, status, IP) may be retained up to 30 days for security and abuse prevention (legitimate\n\
  \    interest).\n- scope: owner session cookie\n  period: 30 days\n  text: with a maximum duration of 30 days that can be renewed during use\nresidency:\n- region: Europe West (Amsterdam)\n  text: Europe West region (Amsterdam)\ntransfers:\n- mechanism: SCC\n  text: under its DPA with EU standard contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: under its DPA with EU standard contractual clauses\ndeletion:\n  route: Contact privacy@orvel.dev about these records.\n  text: Contact privacy@orvel.dev about these records.\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: 'Access, rectification, erasure, restriction, portability, objection: write to hello@orvel.dev.'\n- right: complain to supervisory authority\n  text: You may complain to the CNIL (cnil.fr).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data and we do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/orvel-dev/privacy/orvel-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from orvel-dev's own page on 2026-11-10.
synthetic: false
tags:
- E-Invoicing
- Accessibility
- France
- EU
---
