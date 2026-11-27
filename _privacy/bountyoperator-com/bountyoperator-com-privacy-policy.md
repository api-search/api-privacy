---
api_specs:
- filename: bountyoperator-com-openapi-generated.yml
  format: yaml
  label: Bounty Operator API
  slug: bountyoperator-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bountyoperator-com/openapi/_ae-authored/bountyoperator-com-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Sign-up asks for no password and no email address.
  - category: financial
    text: Stripe collects your email, card and billing details at checkout.
  - category: behavioral
    text: For each hosted review we store the account identifier, the status (running, completed or failed), the review profile, the channel (web or MCP) and the timestamps.
  deletion:
    route: account panel
    text: Download your account data or delete the account from the account panel.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: enforce usage limits
    text: These rows enforce the daily allowance and the concurrency limit.
  - purpose: abuse limits
    text: Abuse limits use a keyed hash of your IP address that expires within a day.
  retention:
  - period: seven days
    scope: usage records
    text: They are deleted after seven days.
  - period: within a day
    scope: IP hash for abuse limits
    text: Abuse limits use a keyed hash of your IP address that expires within a day.
  - period: 30 days
    scope: request metadata
    text: Request metadata is deleted after 30 days.
  - period: 30 days
    scope: Stripe webhook event IDs
    text: webhook event IDs for 30 days
  - period: 30 days
    scope: session cookie
    text: It lasts up to 30 days.
  - period: 400 days
    scope: page counters
    text: Counters older than 400 days are deleted.
  rights:
  - right: access and export
    text: Download your account data or delete the account from the account panel.
  role:
    text: Operated by Vaytric, which is responsible for the data described here.
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Model processing may take place outside your country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bounty Operator
provenance_date: '2026-11-09'
provider_name: Bounty Operator
provider_slug: bountyoperator-com
slug: bountyoperator-com-privacy-policy
source_date: '2026-11-09'
source_filename: bountyoperator-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bountyoperator.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bounty Operator\naid: bountyoperator-com\nurl: https://bountyoperator.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: Operated by Vaytric, which is responsible for the data described here.\ndata_categories:\n- category: identifying\n  text: Sign-up asks for no password and no email address.\n- category: financial\n  text: Stripe collects your email, card and billing details at checkout.\n- category: behavioral\n  text: For each hosted review we store the account identifier, the status (running, completed or failed), the review\n    profile, the channel (web or MCP) and the timestamps.\n\
  purposes:\n- purpose: enforce usage limits\n  text: These rows enforce the daily allowance and the concurrency limit.\n- purpose: abuse limits\n  text: Abuse limits use a keyed hash of your IP address that expires within a day.\nretention:\n- scope: usage records\n  period: seven days\n  text: They are deleted after seven days.\n- scope: IP hash for abuse limits\n  period: within a day\n  text: Abuse limits use a keyed hash of your IP address that expires within a day.\n- scope: request metadata\n  period: 30 days\n  text: Request metadata is deleted after 30 days.\n- scope: Stripe webhook event IDs\n  period: 30 days\n  text: webhook event IDs for 30 days\n- scope: session cookie\n  period: 30 days\n  text: It lasts up to 30 days.\n- scope: page counters\n  period: 400 days\n  text: Counters older than 400 days are deleted.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Model processing may take place outside your country.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: account panel\n  text: Download your account data or delete the account from the account panel.\nrights:\n- right: access and export\n  text: Download your account data or delete the account from the account panel.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bountyoperator-com/privacy/bountyoperator-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 15 quoted statements, read from Bounty Operator's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Bug Bounty
- Review
- Artificial Intelligence
---
