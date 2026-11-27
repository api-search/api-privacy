---
api_specs:
- filename: archstone-dev-capabilities-api-openapi.yml
  format: yaml
  label: Archstone Capabilities API
  slug: archstone-dev-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-capabilities-api-openapi.yml
- filename: archstone-dev-listings-api-openapi.yml
  format: yaml
  label: Archstone Listings API
  slug: archstone-dev-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-listings-api-openapi.yml
- filename: archstone-dev-pricing-api-openapi.yml
  format: yaml
  label: Archstone Pricing API
  slug: archstone-dev-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-pricing-api-openapi.yml
- filename: archstone-dev-verify-openapi-api-openapi.yml
  format: yaml
  label: Archstone Verify Openapi API
  slug: archstone-dev-verify-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-verify-openapi-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: It is your username, the address a verification link goes to, and how we reach you about the service
  - category: identifying
    text: Stored as an scrypt hash with a per-password 16-byte random salt
  - category: device
    text: IP address and user agent, per authenticated request
  - category: communication
    text: the recipient address, the workspace name, the deployment an alert came from, and the message body
  deletion:
    route: Write to gdpr@archstone.dev or ask to close the workspace
    text: Ask us to close it and the account data goes with it, subject to §5's honest limit.
  dpa:
    available: true
    text: which is what our data processing agreement exists to cover
    url: null
  purposes:
  - purpose: authentication
    text: Authentication.
  - purpose: security and account access logging
    text: so an admin in your workspace can see who reached what
  - purpose: abuse prevention
    text: Rate limiting, before any account exists to attribute the attempt to
  residency:
  - region: Finland (EU)
    text: data resident in Helsinki, Finland
  - region: United States
    text: Resend stores in the United States and offers no setting that moves stored data to the EU
  retention:
  - period: 30 days
    scope: audit records on Free
    text: the retention ladder is 30 days on Free, 90 on Starter, a year on Growth, negotiated up to seven years on Enterprise
  - period: 400 days
    scope: campaign counts
    text: Counts are deleted after 400 days.
  - period: 30 days
    scope: test call records
    text: the arguments you typed and the test's result (with any of your credentials blanked out of it) are kept for 30 days
  - period: 24 hours
    scope: OpenAPI document text
    text: discard the document text 24 hours after the fetch
  - period: 3 years
    scope: record of accepted notice versions
    text: for 3 years — the general limitation period under Romanian law — then delete it
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: Access, rectification, erasure, restriction, portability, objection, and a complaint to your supervisory authority.
  role:
    text: When you sign up for the hosted console, we decide what to collect and why.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal data, and we do not share it with anyone not named above.
  subprocessors:
    text: the first two are our customer-data sub-processors (the ones our data processing agreement covers)
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on those standard contractual clauses
  - mechanism: DPF
    text: additionally on Resend's certification under the EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Archstone
provenance_date: '2026-11-09'
provider_name: Archstone
provider_slug: archstone-dev
slug: archstone-dev-privacy-policy
source_date: '2026-11-09'
source_filename: archstone-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://console.archstone.dev/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Archstone\naid: archstone-dev\nurl: https://console.archstone.dev/privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When you sign up for the hosted console, we decide what to collect and why.\ndata_categories:\n- category: contact\n  text: It is your username, the address a verification link goes to, and how we reach you about the service\n- category: identifying\n  text: Stored as an scrypt hash with a per-password 16-byte random salt\n- category: device\n  text: IP address and user agent, per authenticated request\n- category: communication\n  text: the recipient address, the workspace\
  \ name, the deployment an alert came from, and the message body\npurposes:\n- purpose: authentication\n  text: Authentication.\n- purpose: security and account access logging\n  text: so an admin in your workspace can see who reached what\n- purpose: abuse prevention\n  text: Rate limiting, before any account exists to attribute the attempt to\nretention:\n- scope: audit records on Free\n  period: 30 days\n  text: the retention ladder is 30 days on Free, 90 on Starter, a year on Growth, negotiated up to seven years on\n    Enterprise\n- scope: campaign counts\n  period: 400 days\n  text: Counts are deleted after 400 days.\n- scope: test call records\n  period: 30 days\n  text: the arguments you typed and the test's result (with any of your credentials blanked out of it) are kept\n    for 30 days\n- scope: OpenAPI document text\n  period: 24 hours\n  text: discard the document text 24 hours after the fetch\n- scope: record of accepted notice versions\n  period: 3 years\n  text: for 3 years\
  \ — the general limitation period under Romanian law — then delete it\nresidency:\n- region: Finland (EU)\n  text: data resident in Helsinki, Finland\n- region: United States\n  text: Resend stores in the United States and offers no setting that moves stored data to the EU\ntransfers:\n- mechanism: SCC\n  text: We rely on those standard contractual clauses\n- mechanism: DPF\n  text: additionally on Resend's certification under the EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: the first two are our customer-data sub-processors (the ones our data processing agreement covers)\ndpa:\n  available: true\n  url: null\n  text: which is what our data processing agreement exists to cover\ndeletion:\n  route: Write to gdpr@archstone.dev or ask to close the workspace\n  text: Ask us to close it and the account data goes with it, subject to §5's honest limit.\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: Access, rectification, erasure,\
  \ restriction, portability, objection, and a complaint to your supervisory\n    authority.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal data, and we do not share it with anyone not named above.\n"
source_yaml_url: https://artifacts.apis.io/archstone-dev/privacy/archstone-dev-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Archstone's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Connector
- No-Code
- Pricing
- Business
---
