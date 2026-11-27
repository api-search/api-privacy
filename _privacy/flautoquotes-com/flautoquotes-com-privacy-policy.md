---
api_specs:
- filename: flautoquotes-com-eligibility-api-openapi.yml
  format: yaml
  label: flautoquotes-com Eligibility API
  slug: flautoquotes-com-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flautoquotes-com/openapi/flautoquotes-com-eligibility-api-openapi.yml
- filename: flautoquotes-com-quotes-api-openapi.yml
  format: yaml
  label: flautoquotes-com Quotes API
  slug: flautoquotes-com-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flautoquotes-com/openapi/flautoquotes-com-quotes-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: other
    text: We Request garaging zip date of birth vehicle coverage wanted mileage violations prior insurance
  - category: contact
    text: We Then Request ["name","phone number","email (optional)","street address (optional, for a firm quote)"]
  deletion:
    route: POST https://flautoquotes.com/forget
    text: 'Revocation POST https://flautoquotes.com/forget with {"id": "<request id or lead id>"}, or https://flautoquotes.com/forget in a browser.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: indicative pricing
    text: You send the facts. We return indicative prices where licensed.
  - purpose: connecting consumer with licensed agents
    text: Contact details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.
  retention:
  - period: 30 days
    scope: facts
    text: 'Facts: 30 days.'
  - period: 365 days
    scope: leads
    text: 'Leads: until revoked or 365 days.'
  - period: 180 days
    scope: sighting logs
    text: 'Sighting logs: 180 days, no personal data.'
  rights:
  - right: withdraw consent
    text: Withdraw at any time at /forget .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Sold To Third Parties Only under sell_identity, only with that consent.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: flautoquotes-com
provenance_date: '2026-11-09'
provider_name: flautoquotes-com
provider_slug: flautoquotes-com
slug: flautoquotes-com-privacy-policy
source_date: '2026-11-09'
source_filename: flautoquotes-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flautoquotes.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: flautoquotes-com\naid: flautoquotes-com\nurl: https://flautoquotes.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: We Request garaging zip date of birth vehicle coverage wanted mileage violations prior insurance\n- category: contact\n  text: We Then Request [\"name\",\"phone number\",\"email (optional)\",\"street address (optional, for a firm quote)\"]\npurposes:\n- purpose: indicative pricing\n  text: You send the facts. We return indicative prices where licensed.\n- purpose: connecting consumer with licensed agents\n  text: Contact\
  \ details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.\nretention:\n- scope: facts\n  period: 30 days\n  text: 'Facts: 30 days.'\n- scope: leads\n  period: 365 days\n  text: 'Leads: until revoked or 365 days.'\n- scope: sighting logs\n  period: 180 days\n  text: 'Sighting logs: 180 days, no personal data.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: POST https://flautoquotes.com/forget\n  text: 'Revocation POST https://flautoquotes.com/forget with {\"id\": \"<request id or lead id>\"}, or https://flautoquotes.com/forget\n    in a browser.'\nrights:\n- right: withdraw consent\n  text: Withdraw at any time at /forget .\nsale_or_sharing:\n  stance: conditional\n  text: Sold To Third Parties Only under sell_identity, only with that consent.\n"
source_yaml_url: https://artifacts.apis.io/flautoquotes-com/privacy/flautoquotes-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from flautoquotes-com's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Auto
- Quotes
- Florida
- Marketplace
---
