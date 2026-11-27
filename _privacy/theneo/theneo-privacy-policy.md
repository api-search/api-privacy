---
api_specs:
- filename: theneo-import-api-openapi.yml
  format: yaml
  label: Theneo Import API
  slug: theneo-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/theneo/openapi/theneo-import-api-openapi.yml
- filename: theneo-projects-api-openapi.yml
  format: yaml
  label: Theneo Projects API
  slug: theneo-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/theneo/openapi/theneo-projects-api-openapi.yml
- filename: theneo-publishing-api-openapi.yml
  format: yaml
  label: Theneo Publishing API
  slug: theneo-publishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/theneo/openapi/theneo-publishing-api-openapi.yml
- filename: theneo-users-api-openapi.yml
  format: yaml
  label: Theneo Users API
  slug: theneo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/theneo/openapi/theneo-users-api-openapi.yml
- filename: theneo-workspaces-api-openapi.yml
  format: yaml
  label: Theneo Workspaces API
  slug: theneo-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/theneo/openapi/theneo-workspaces-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, and password
  - category: financial
    text: we do not store or have access to your full payment card details
  - category: device
    text: IP address, browser and device information, referring URLs, timestamps, and activity/audit logs
  - category: behavioral
    text: Cookies and similar technologies
  - category: communication
    text: information you provide when you contact us or use our in-app support channels
  deletion:
    route: Request via hello@theneo.io or account/workspace deletion
    text: You may request deletion of Your workspace, projects, or account at any time.
  dpa:
    available: true
    text: which is available on our website and is hereby incorporated into these Terms by reference
    url: null
  purposes:
  - purpose: Provide, operate, secure the Platform
    text: 'We use the information we collect to: provide, operate, and secure the Platform'
  - purpose: Fraud and misuse prevention
    text: prevent fraud and misuse
  residency:
  - region: United States
    text: Theneo Inc. is established in the United States and our Services are hosted there.
  retention:
  - period: 30 days
    scope: Account data
    text: 'Account data: retained while your account is active; deletion requests are completed within 30 days of verification'
  - period: 30 days
    scope: Customer Content
    text: content is deleted on your request or account deletion, within 30 days.
  rights:
  - right: Access, correction, deletion
    text: You have the right to access, correct, and delete your personal data, and not to be discriminated against for exercising these rights
  - right: Data portability
    text: 'Right to data portability: to receive the personal data you have provided to us in a structured, commonly used, and machine-readable format'
  - right: Object
    text: Where we process your personal data on the basis of our legitimate interests, you may object at any time on grounds relating to your particular situation.
  - right: Withdraw consent
    text: 'Right to withdraw consent: where we rely on your consent, you may withdraw it at any time.'
  role:
    text: For the personal data described in this Policy — account, billing, technical, support, and marketing data — Theneo Inc. acts as the data controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: listed in Annex III of our Data Processing Agreement
    url: null
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards, including the European Commission's Standard Contractual Clauses and, where applicable, the UK International Data Transfer Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Theneo
provenance_date: '2026-11-10'
provider_name: Theneo
provider_slug: theneo
slug: theneo-privacy-policy
source_date: '2026-11-10'
source_filename: theneo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.theneo.io/privacy-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Theneo\naid: theneo\nurl: https://www.theneo.io/privacy-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: For the personal data described in this Policy — account, billing, technical, support, and marketing data\n    — Theneo Inc. acts as the data controller.\ndata_categories:\n- category: identifying\n  text: your name, email address, and password\n- category: financial\n  text: we do not store or have access to your full payment card details\n- category: device\n  text: IP address, browser and device information, referring URLs, timestamps, and activity/audit logs\n- category:\
  \ behavioral\n  text: Cookies and similar technologies\n- category: communication\n  text: information you provide when you contact us or use our in-app support channels\npurposes:\n- purpose: Provide, operate, secure the Platform\n  text: 'We use the information we collect to: provide, operate, and secure the Platform'\n- purpose: Fraud and misuse prevention\n  text: prevent fraud and misuse\nretention:\n- scope: Account data\n  period: 30 days\n  text: 'Account data: retained while your account is active; deletion requests are completed within 30 days of\n    verification'\n- scope: Customer Content\n  period: 30 days\n  text: content is deleted on your request or account deletion, within 30 days.\nresidency:\n- region: United States\n  text: Theneo Inc. is established in the United States and our Services are hosted there.\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards, including the European Commission's Standard Contractual Clauses and, where\n    applicable,\
  \ the UK International Data Transfer Addendum.\nsubprocessors:\n  url: null\n  text: listed in Annex III of our Data Processing Agreement\ndpa:\n  available: true\n  url: null\n  text: which is available on our website and is hereby incorporated into these Terms by reference\ndeletion:\n  route: Request via hello@theneo.io or account/workspace deletion\n  text: You may request deletion of Your workspace, projects, or account at any time.\nrights:\n- right: Access, correction, deletion\n  text: You have the right to access, correct, and delete your personal data, and not to be discriminated against\n    for exercising these rights\n- right: Data portability\n  text: 'Right to data portability: to receive the personal data you have provided to us in a structured, commonly\n    used, and machine-readable format'\n- right: Object\n  text: Where we process your personal data on the basis of our legitimate interests, you may object at any time\n    on grounds relating to your particular situation.\n\
  - right: Withdraw consent\n  text: 'Right to withdraw consent: where we rely on your consent, you may withdraw it at any time.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/theneo/privacy/theneo-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Theneo's own page on 2026-11-10.
synthetic: false
tags:
- API Documentation
- Developer Portal
- Developer Tools
- Documentation Platform
- Artificial Intelligence
- AI Copilot
- MCP
- Platform
---
