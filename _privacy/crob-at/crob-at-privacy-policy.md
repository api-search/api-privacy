---
api_specs:
- filename: crob-at-account-api-openapi.yml
  format: yaml
  label: crob.at Account API
  slug: crob-at-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crob-at/openapi/crob-at-account-api-openapi.yml
- filename: crob-at-feedback-api-openapi.yml
  format: yaml
  label: crob.at Feedback API
  slug: crob-at-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crob-at/openapi/crob-at-feedback-api-openapi.yml
- filename: crob-at-generation-api-openapi.yml
  format: yaml
  label: crob.at Generation API
  slug: crob-at-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crob-at/openapi/crob-at-generation-api-openapi.yml
- filename: crob-at-reference-api-openapi.yml
  format: yaml
  label: crob.at Reference API
  slug: crob-at-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crob-at/openapi/crob-at-reference-api-openapi.yml
- filename: crob-at-teams-api-openapi.yml
  format: yaml
  label: crob.at Teams API
  slug: crob-at-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crob-at/openapi/crob-at-teams-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your crob.at handle, email address, password hash, email-verification status, and session token
  - category: location
    text: operational logs may retain a country code
  - category: device
    text: Those logs contain a route pattern, response status, timing, country code, browser family, full user-agent string, and coarse referral class.
  - category: behavioral
    text: Journey events contain only an allowlisted event name, a broad surface such as Teams or Pokédex, a broad source class, a bounded page type
  - category: other
    text: the team data (Pokémon, movesets, items, EVs) is stored on our server so the link works when someone opens it
  deletion:
    route: contact us
    text: You can request deletion by contacting us .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: aggregate usage measurement
    text: We use self-hosted Plausible to understand aggregate page and feature usage without analytics cookies or account identifiers.
  - purpose: security and abuse prevention
    text: We keep short-lived operational request logs for security, reliability, and abuse prevention.
  - purpose: account features
    text: we record a small first-party activity ledger for signup, visits, team creation, reopening, saving, copying, editing, and Pokémon Showdown clone outcomes
  - purpose: advertising
    text: Some pages use Journey by Mediavine to fund the site.
  retention:
  - period: 30 days
    scope: operational request logs
    text: Operational request logs are retained for no more than 30 days under normal operation.
  - period: 90 days
    scope: raw browser journey events and random code
    text: Raw browser journey events, daily browser records, and the random code stored in your browser expire after 90 days.
  - period: null
    scope: account activity ledger
    text: The account activity ledger may be retained until the account is deleted or a shorter policy replaces this rule.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crob.at
provenance_date: '2026-11-09'
provider_name: crob.at
provider_slug: crob-at
slug: crob-at-privacy-policy
source_date: '2026-11-09'
source_filename: crob-at-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crob.at/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crob.at\naid: crob-at\nurl: https://crob.at/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we store your crob.at handle, email address, password hash, email-verification status, and session token\n- category: location\n  text: operational logs may retain a country code\n- category: device\n  text: Those logs contain a route pattern, response status, timing, country code, browser family, full user-agent\n    string, and coarse referral class.\n- category: behavioral\n  text: Journey events contain only an allowlisted event name,\
  \ a broad surface such as Teams or Pokédex, a broad\n    source class, a bounded page type\n- category: other\n  text: the team data (Pokémon, movesets, items, EVs) is stored on our server so the link works when someone opens\n    it\npurposes:\n- purpose: aggregate usage measurement\n  text: We use self-hosted Plausible to understand aggregate page and feature usage without analytics cookies or\n    account identifiers.\n- purpose: security and abuse prevention\n  text: We keep short-lived operational request logs for security, reliability, and abuse prevention.\n- purpose: account features\n  text: we record a small first-party activity ledger for signup, visits, team creation, reopening, saving, copying,\n    editing, and Pokémon Showdown clone outcomes\n- purpose: advertising\n  text: Some pages use Journey by Mediavine to fund the site.\nretention:\n- scope: operational request logs\n  period: 30 days\n  text: Operational request logs are retained for no more than 30 days under normal\
  \ operation.\n- scope: raw browser journey events and random code\n  period: 90 days\n  text: Raw browser journey events, daily browser records, and the random code stored in your browser expire after\n    90 days.\n- scope: account activity ledger\n  period: null\n  text: The account activity ledger may be retained until the account is deleted or a shorter policy replaces this\n    rule.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us\n  text: You can request deletion by contacting us .\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/crob-at/privacy/crob-at-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 14 quoted statements, read from crob.at's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Esports
- Pokemon
- Pokemon Showdown
- Team Building
- Content Rendering
- Developer Tools
- REST API
---
