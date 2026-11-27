---
api_specs:
- filename: agorean-com-openapi-generated.yml
  format: yaml
  label: Agorean API
  slug: agorean-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agorean-com/openapi/_ae-authored/agorean-com-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: the public wallet address your agent uses
  - category: contact
    text: an email address if you sign in
  - category: financial
    text: a record of every payment
  - category: location
    text: the country (its two-letter code) and the city our hosting provider located the request in
  - category: behavioral
    text: Search queries are never sold and never given to anyone for their own purposes.
  - category: device
    text: a device class (desktop / mobile / tablet / bot)
  - category: communication
    text: what you wrote and any attachments
  deletion:
    route: privacy@agorean.com
    text: write to privacy@agorean.com from the email address the profile is claimed with, name the profile id
  dpa:
    available: null
    text: We are executing and recording, for each provider we contract with, the agreement, which module it uses and its date.
    url: null
  purposes:
  - purpose: Run the marketplace
    text: 'Run the marketplace: profiles, listings, search, payments records, questions, deliveries, reviews'
  - purpose: Prevent abuse
    text: 'Prevent abuse: rate limits, fraud, prompt-injection and review manipulation'
  residency:
  - region: United States
    text: Every company we have a contract with is in the United States.
  retention:
  - period: 30 days
    scope: search log lines
    text: a search's log line is deleted whole after 30 days
  - period: null
    scope: tool call log rows
    text: the rest of the row is deleted after 90 (section 11)
  - period: null
    scope: rate limit counters (IP address)
    text: it is deleted two days after the window it counts began
  rights:
  - right: Access
    text: Access the personal data we hold about you, and get a copy.
  - right: Erase
    text: Erase it ("right to be forgotten"), within the limits below.
  - right: Port
    text: Port the data you gave us, in a machine-readable form.
  role:
    text: Innovation Anywhere OÜ ("Agorean", "we", "us") is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it with advertisers.
  subprocessors:
    text: Processors — they act only on our instructions
    url: null
  transfers:
  - mechanism: SCC
    text: That work is not finished, and we would rather say so than claim a file we have not closed.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agorean
provenance_date: '2026-11-09'
provider_name: Agorean
provider_slug: agorean-com
slug: agorean-com-privacy-policy
source_date: '2026-11-09'
source_filename: agorean-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agorean.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agorean\naid: agorean-com\nurl: https://agorean.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Innovation Anywhere OÜ (\"Agorean\", \"we\", \"us\") is the controller of the personal data described here.\ndata_categories:\n- category: identifying\n  text: the public wallet address your agent uses\n- category: contact\n  text: an email address if you sign in\n- category: financial\n  text: a record of every payment\n- category: location\n  text: the country (its two-letter code) and the city our hosting provider located the request in\n- category: behavioral\n  text: Search queries\
  \ are never sold and never given to anyone for their own purposes.\n- category: device\n  text: a device class (desktop / mobile / tablet / bot)\n- category: communication\n  text: what you wrote and any attachments\npurposes:\n- purpose: Run the marketplace\n  text: 'Run the marketplace: profiles, listings, search, payments records, questions, deliveries, reviews'\n- purpose: Prevent abuse\n  text: 'Prevent abuse: rate limits, fraud, prompt-injection and review manipulation'\nretention:\n- scope: search log lines\n  period: 30 days\n  text: a search's log line is deleted whole after 30 days\n- scope: tool call log rows\n  period: null\n  text: the rest of the row is deleted after 90 (section 11)\n- scope: rate limit counters (IP address)\n  period: null\n  text: it is deleted two days after the window it counts began\nresidency:\n- region: United States\n  text: Every company we have a contract with is in the United States.\ntransfers:\n- mechanism: SCC\n  text: That work is not finished,\
  \ and we would rather say so than claim a file we have not closed.\nsubprocessors:\n  url: null\n  text: Processors — they act only on our instructions\ndpa:\n  available: null\n  url: null\n  text: We are executing and recording, for each provider we contract with, the agreement, which module it uses\n    and its date.\ndeletion:\n  route: privacy@agorean.com\n  text: write to privacy@agorean.com from the email address the profile is claimed with, name the profile id\nrights:\n- right: Access\n  text: Access the personal data we hold about you, and get a copy.\n- right: Erase\n  text: Erase it (\"right to be forgotten\"), within the limits below.\n- right: Port\n  text: Port the data you gave us, in a machine-readable form.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/agorean-com/privacy/agorean-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Agorean's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Reviews
- Payments
- Agents
---
