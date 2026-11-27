---
api_specs:
- filename: texasautoquotes-com-agency-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Agency API
  slug: texasautoquotes-com-agency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-agency-api-openapi.yml
- filename: texasautoquotes-com-benchmark-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Benchmark API
  slug: texasautoquotes-com-benchmark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-benchmark-api-openapi.yml
- filename: texasautoquotes-com-consent-record-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Consent Record API
  slug: texasautoquotes-com-consent-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-consent-record-api-openapi.yml
- filename: texasautoquotes-com-contact-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Contact API
  slug: texasautoquotes-com-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-contact-api-openapi.yml
- filename: texasautoquotes-com-dataset-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Dataset API
  slug: texasautoquotes-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-dataset-api-openapi.yml
- filename: texasautoquotes-com-eligibility-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Eligibility API
  slug: texasautoquotes-com-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-eligibility-api-openapi.yml
- filename: texasautoquotes-com-forget-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Forget API
  slug: texasautoquotes-com-forget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-forget-api-openapi.yml
- filename: texasautoquotes-com-join-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Join API
  slug: texasautoquotes-com-join-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-join-api-openapi.yml
- filename: texasautoquotes-com-prices-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Prices API
  slug: texasautoquotes-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-prices-api-openapi.yml
- filename: texasautoquotes-com-pull-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Pull API
  slug: texasautoquotes-com-pull-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-pull-api-openapi.yml
- filename: texasautoquotes-com-quotes-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Quotes API
  slug: texasautoquotes-com-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-quotes-api-openapi.yml
- filename: texasautoquotes-com-terms-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Terms API
  slug: texasautoquotes-com-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-terms-api-openapi.yml
- filename: texasautoquotes-com-verify-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Verify API
  slug: texasautoquotes-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-verify-api-openapi.yml
- filename: texasautoquotes-com-top-up-api-openapi.yml
  format: yaml
  label: texasautoquotes-com Top Up API
  slug: texasautoquotes-com-top-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/texasautoquotes-com/openapi/texasautoquotes-com-top-up-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: demographic
    text: We Request garaging zip date of birth vehicle coverage wanted mileage violations prior insurance
  - category: contact
    text: We Then Request ["name","phone number","email (optional)","street address (optional, for a firm quote)"]
  deletion:
    route: POST https://texasautoquotes.com/forget
    text: 'Revocation POST https://texasautoquotes.com/forget with {"id": "<request id or lead id>"}, or https://texasautoquotes.com/forget in a browser.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: indicative prices
    text: You send the facts. We return indicative prices where licensed.
  - purpose: licensed agent contact
    text: Contact details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.
  retention:
  - period: 30 days
    scope: facts
    text: 'Facts: 30 days.'
  - period: until revoked or 365 days
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
name: texasautoquotes-com
provenance_date: '2026-11-10'
provider_name: texasautoquotes-com
provider_slug: texasautoquotes-com
slug: texasautoquotes-com-privacy-policy
source_date: '2026-11-10'
source_filename: texasautoquotes-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://texasautoquotes.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: texasautoquotes-com\naid: texasautoquotes-com\nurl: https://texasautoquotes.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: demographic\n  text: We Request garaging zip date of birth vehicle coverage wanted mileage violations prior insurance\n- category: contact\n  text: We Then Request [\"name\",\"phone number\",\"email (optional)\",\"street address (optional, for a firm quote)\"]\npurposes:\n- purpose: indicative prices\n  text: You send the facts. We return indicative prices where licensed.\n- purpose: licensed agent contact\n  text: Contact\
  \ details leave only with the consumer's explicit consent, to licensed agents, in the scope granted.\nretention:\n- scope: facts\n  period: 30 days\n  text: 'Facts: 30 days.'\n- scope: leads\n  period: until revoked or 365 days\n  text: 'Leads: until revoked or 365 days.'\n- scope: sighting logs\n  period: 180 days\n  text: 'Sighting logs: 180 days, no personal data.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: POST https://texasautoquotes.com/forget\n  text: 'Revocation POST https://texasautoquotes.com/forget with {\"id\": \"<request id or lead id>\"}, or https://texasautoquotes.com/forget\n    in a browser.'\nrights:\n- right: withdraw consent\n  text: Withdraw at any time at /forget .\nsale_or_sharing:\n  stance: conditional\n  text: Sold To Third Parties Only under sell_identity, only with that consent.\n"
source_yaml_url: https://artifacts.apis.io/texasautoquotes-com/privacy/texasautoquotes-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from texasautoquotes-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Auto
- Texas
- Quotes
- Marketplace
---
