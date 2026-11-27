---
api_specs:
- filename: atlaso-ai-openapi-generated.yml
  format: yaml
  label: Atlaso Labs Inc. API
  slug: atlaso-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlaso-ai/openapi/_ae-authored/atlaso-ai-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address and a user id
  - category: contact
    text: Your name, email address and message when you use our contact form
  - category: financial
    text: Card details, billing address, and subscription state
  - category: location
    text: an approximate city and country estimated from your IP address
  - category: behavioral
    text: Sign-up, setup and upgrade steps in the dashboard, identified by your pseudonymous user id
  - category: device
    text: A server-minted device_id
  - category: other
    text: Facts, decisions, preferences, gotchas, and auto-captured conversation snippets
  deletion:
    route: Settings > Privacy > Delete my account
    text: you can delete your Account yourself in the dashboard under Settings > Privacy > Delete my account
  dpa:
    available: true
    text: The processor/controller framing in our Data Processing Addendum (and its Standard Contractual Clauses) applies only where we process personal data on behalf of a business customer
    url: null
  purposes:
  - purpose: Provide the Service
    text: Create and manage your Account; store, sync, retrieve, and inject your Memories
  - purpose: Authentication and security
    text: Verify your identity, manage sessions and passkeys, prevent abuse and fraud
  - purpose: Product analytics
    text: Count content-free daily/monthly active usage
  residency:
  - region: United States
    text: Fireworks runs its service on servers in the United States.
  - region: India
    text: the short-lived rate-limit codes for our website's forms and Ask Atlaso are stored with Upstash in India
  retention:
  - period: life of your Account
    scope: Memory content
    text: 'Memory content: retained for the life of your Account.'
  - period: about 30 days
    scope: Search text
    text: is deleted after about 30 days, or later if the search was rated for usefulness, and in any case when your Account is deleted.
  - period: 93 days
    scope: Encrypted backups
    text: daily copies are kept for 14 days, weekly copies for 35 days and monthly copies for 93 days
  rights:
  - right: Access, rectification, erasure, restriction
    text: 'You have the right to: access your data; rectify inaccurate data; erase your data'
  - right: California know, delete, correct
    text: California residents have the right to know/access , delete , and correct personal information
  role:
    text: 'Data controller: Atlaso Labs Inc., a Delaware C-Corporation.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we do not sell your personal data
  subprocessors:
    text: For the maintained, dated list and how we tell you about changes, see our Sub-processors List
    url: null
  transfers:
  - mechanism: other
    text: We are finalizing the applicable Standard Contractual Clauses, UK Addendum, assessments and related instruments for the relevant transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atlaso Labs Inc.
provenance_date: '2026-11-09'
provider_name: Atlaso Labs Inc.
provider_slug: atlaso-ai
slug: atlaso-ai-privacy-policy
source_date: '2026-11-09'
source_filename: atlaso-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.atlaso.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atlaso Labs Inc.\naid: atlaso-ai\nurl: https://www.atlaso.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'Data controller: Atlaso Labs Inc., a Delaware C-Corporation.'\ndata_categories:\n- category: identifying\n  text: Email address and a user id\n- category: contact\n  text: Your name, email address and message when you use our contact form\n- category: financial\n  text: Card details, billing address, and subscription state\n- category: location\n  text: an approximate city and country estimated from your IP address\n- category: behavioral\n  text: Sign-up,\
  \ setup and upgrade steps in the dashboard, identified by your pseudonymous user id\n- category: device\n  text: A server-minted device_id\n- category: other\n  text: Facts, decisions, preferences, gotchas, and auto-captured conversation snippets\npurposes:\n- purpose: Provide the Service\n  text: Create and manage your Account; store, sync, retrieve, and inject your Memories\n- purpose: Authentication and security\n  text: Verify your identity, manage sessions and passkeys, prevent abuse and fraud\n- purpose: Product analytics\n  text: Count content-free daily/monthly active usage\nretention:\n- scope: Memory content\n  period: life of your Account\n  text: 'Memory content: retained for the life of your Account.'\n- scope: Search text\n  period: about 30 days\n  text: is deleted after about 30 days, or later if the search was rated for usefulness, and in any case when your\n    Account is deleted.\n- scope: Encrypted backups\n  period: 93 days\n  text: daily copies are kept for 14 days,\
  \ weekly copies for 35 days and monthly copies for 93 days\nresidency:\n- region: United States\n  text: Fireworks runs its service on servers in the United States.\n- region: India\n  text: the short-lived rate-limit codes for our website's forms and Ask Atlaso are stored with Upstash in India\ntransfers:\n- mechanism: other\n  text: We are finalizing the applicable Standard Contractual Clauses, UK Addendum, assessments and related instruments\n    for the relevant transfers.\nsubprocessors:\n  url: null\n  text: For the maintained, dated list and how we tell you about changes, see our Sub-processors List\ndpa:\n  available: true\n  url: null\n  text: The processor/controller framing in our Data Processing Addendum (and its Standard Contractual Clauses)\n    applies only where we process personal data on behalf of a business customer\ndeletion:\n  route: Settings > Privacy > Delete my account\n  text: you can delete your Account yourself in the dashboard under Settings > Privacy > Delete\
  \ my account\nrights:\n- right: Access, rectification, erasure, restriction\n  text: 'You have the right to: access your data; rectify inaccurate data; erase your data'\n- right: California know, delete, correct\n  text: California residents have the right to know/access , delete , and correct personal information\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell your personal data\n"
source_yaml_url: https://artifacts.apis.io/atlaso-ai/privacy/atlaso-ai-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Atlaso Labs Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Integration
- Platform
- Tools
---
