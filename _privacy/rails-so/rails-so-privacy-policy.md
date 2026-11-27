---
api_specs:
- filename: rails-so-api-openapi.json
  format: json
  label: Agent Rails public MCP and OAuth HTTP API API
  slug: agent-rails-public-mcp-and-oauth-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rails-so/openapi/_original/rails-so-api-openapi.json
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address or phone number, its verification time, your identity provider identifier, your name and picture if you sign in with Google
  - category: financial
    text: Rails stores purchase and payment references, the app, buyer, amount, currency, status and term information.
  - category: communication
    text: read-only access to your mail ( gmail.readonly )
  - category: device
    text: Servers process network addresses, request paths and errors to serve requests, limit abuse and diagnose faults.
  deletion:
    route: support@rails.so
    text: Write to us at the address below to delete your Google data or your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Google data features
    text: Rails uses Google data only to provide the features you turned on
  - purpose: No advertising or sale
    text: Rails uses no Google data for advertising, to build profiles for other purposes, or for credit or lending decisions, and does not sell it.
  - purpose: No AI training on Google data
    text: Rails does not use Google user data to develop, improve or train generalized AI or machine learning models
  residency:
  - region: unstated
    text: This policy does not assert a particular data region, adequacy decision or contractual safeguard that has not been verified.
  retention:
  - period: until you revoke the connection
    scope: Google calendar tokens
    text: Rails stores your Google access and refresh tokens, encrypted with AES-256-GCM under a key held outside the database, until you revoke the connection.
  - period: 730 days
    scope: Google connection receipts
    text: We keep them for 730 days, then delete them.
  - period: 30 days
    scope: Chat content holding mail results
    text: Chat content that holds mail results is kept until you delete it or your account, then purged within 30 days.
  - period: no automatic age-based expiry
    scope: Saved app records
    text: Saved app records have no automatic age-based expiry unless the feature says otherwise.
  rights:
  - right: GDPR rights
    text: In the EEA, where the GDPR applies, your rights include access, correction, erasure, restriction, portability, objection to legitimate-interest processing, and withdrawal of consent.
  - right: CCPA rights
    text: 'California residents have the rights that apply under the CCPA: know and access, correct, delete, opt out of sale or advertising sharing, and limit qualifying uses of sensitive personal information.'
  role:
    text: Alex Neyman, doing business as Agent Rails operates Rails and is responsible for the personal information covered by this policy (the data controller where that term applies).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Rails does not sell personal information or share it for cross-context behavioral advertising.
  subprocessors:
    text: Our infrastructure provider hosts the service and database.
    url: null
  transfers:
  - mechanism: other
    text: Providers can process information in countries other than yours.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: rails-so
provenance_date: '2026-11-10'
provider_name: rails-so
provider_slug: rails-so
slug: rails-so-privacy-policy
source_date: '2026-11-10'
source_filename: rails-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rails.so/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rails-so\naid: rails-so\nurl: https://rails.so/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Alex Neyman, doing business as Agent Rails operates Rails and is responsible for the personal information\n    covered by this policy (the data controller where that term applies).\ndata_categories:\n- category: identifying\n  text: Your email address or phone number, its verification time, your identity provider identifier, your name\n    and picture if you sign in with Google\n- category: financial\n  text: Rails stores purchase and payment references, the app, buyer, amount, currency, status\
  \ and term information.\n- category: communication\n  text: read-only access to your mail ( gmail.readonly )\n- category: device\n  text: Servers process network addresses, request paths and errors to serve requests, limit abuse and diagnose\n    faults.\npurposes:\n- purpose: Google data features\n  text: Rails uses Google data only to provide the features you turned on\n- purpose: No advertising or sale\n  text: Rails uses no Google data for advertising, to build profiles for other purposes, or for credit or lending\n    decisions, and does not sell it.\n- purpose: No AI training on Google data\n  text: Rails does not use Google user data to develop, improve or train generalized AI or machine learning models\nretention:\n- scope: Google calendar tokens\n  period: until you revoke the connection\n  text: Rails stores your Google access and refresh tokens, encrypted with AES-256-GCM under a key held outside\n    the database, until you revoke the connection.\n- scope: Google connection\
  \ receipts\n  period: 730 days\n  text: We keep them for 730 days, then delete them.\n- scope: Chat content holding mail results\n  period: 30 days\n  text: Chat content that holds mail results is kept until you delete it or your account, then purged within 30\n    days.\n- scope: Saved app records\n  period: no automatic age-based expiry\n  text: Saved app records have no automatic age-based expiry unless the feature says otherwise.\nresidency:\n- region: unstated\n  text: This policy does not assert a particular data region, adequacy decision or contractual safeguard that has\n    not been verified.\ntransfers:\n- mechanism: other\n  text: Providers can process information in countries other than yours.\nsubprocessors:\n  url: null\n  text: Our infrastructure provider hosts the service and database.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: support@rails.so\n  text: Write to us at the address below to delete your Google data or your account.\nrights:\n\
  - right: GDPR rights\n  text: In the EEA, where the GDPR applies, your rights include access, correction, erasure, restriction, portability,\n    objection to legitimate-interest processing, and withdrawal of consent.\n- right: CCPA rights\n  text: 'California residents have the rights that apply under the CCPA: know and access, correct, delete, opt out\n    of sale or advertising sharing, and limit qualifying uses of sensitive personal information.'\nsale_or_sharing:\n  stance: prohibited\n  text: Rails does not sell personal information or share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/rails-so/privacy/rails-so-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from rails-so's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Productivity
- Collaboration
- ChatGPT
- Claude
- Company
---
