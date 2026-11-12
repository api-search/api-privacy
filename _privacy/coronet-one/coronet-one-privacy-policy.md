---
api_specs:
- filename: coronet-one-confirm-checkout-api-openapi.yml
  format: yaml
  label: Coronet Arcade Confirm Checkout API
  slug: coronet-one-confirm-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coronet-one/openapi/coronet-one-confirm-checkout-api-openapi.yml
- filename: coronet-one-create-checkout-api-openapi.yml
  format: yaml
  label: Coronet Arcade Create Checkout API
  slug: coronet-one-create-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coronet-one/openapi/coronet-one-create-checkout-api-openapi.yml
- filename: coronet-one-mcp-api-openapi.yml
  format: yaml
  label: Coronet Arcade MCP API
  slug: coronet-one-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coronet-one/openapi/coronet-one-mcp-api-openapi.yml
- filename: coronet-one-restore-purchase-api-openapi.yml
  format: yaml
  label: Coronet Arcade Restore Purchase API
  slug: coronet-one-restore-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coronet-one/openapi/coronet-one-restore-purchase-api-openapi.yml
- filename: coronet-one-site-api-openapi.yml
  format: yaml
  label: Coronet Arcade Site API
  slug: coronet-one-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coronet-one/openapi/coronet-one-site-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Email — to send a magic-link sign-in (and email-change confirmation).
  - category: identifying
    text: Display name — optional, only if you join public daily leaderboards.
  - category: behavioral
    text: Finished dailies — the puzzle, time, and hints for each daily you finish, saved so that daily reopens solved on another browser.
  - category: device
    text: Device slot ids — anonymous browser ids so Arcade Pass can restore on up to 3 browsers.
  - category: financial
    text: We store the checkout session id, receipt email, amount, and which browsers you’ve restored so we can honor the pass.
  - category: behavioral
    text: Cloudflare Analytics Engine records anonymous game events (open, win, share).
  deletion:
    route: Settings → Account → Delete account
    text: Delete account — Settings → Account → Delete account. That deletes the account, finished dailies stored on it, leaderboard scores, and sessions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sign-in
    text: to send a magic-link sign-in
  - purpose: cross-browser restore
    text: saved so that daily reopens solved on another browser
  - purpose: honor Arcade Pass
    text: so we can honor the pass
  retention:
  - period: until you delete the account
    scope: account rows
    text: Account rows stay until you delete the account.
  - period: as long as we need them to restore a purchase or meet bookkeeping rules
    scope: payment ledger
    text: Payment ledger rows stay as long as we need them to restore a purchase or meet bookkeeping rules.
  - period: expire
    scope: magic-link tokens
    text: Magic-link tokens expire.
  rights:
  - right: opt out of public leaderboards
    text: Opting out hides you from listings.
  - right: delete account
    text: Delete account — Settings → Account → Delete account.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coronet Arcade
provenance_date: '2026-11-09'
provider_name: Coronet Arcade
provider_slug: coronet-one
slug: coronet-one-privacy-policy
source_date: '2026-11-09'
source_filename: coronet-one-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coronet.one/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coronet Arcade\naid: coronet-one\nurl: https://coronet.one/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email — to send a magic-link sign-in (and email-change confirmation).\n- category: identifying\n  text: Display name — optional, only if you join public daily leaderboards.\n- category: behavioral\n  text: Finished dailies — the puzzle, time, and hints for each daily you finish, saved so that daily reopens solved\n    on another browser.\n- category: device\n  text: Device slot ids — anonymous browser ids so Arcade Pass can\
  \ restore on up to 3 browsers.\n- category: financial\n  text: We store the checkout session id, receipt email, amount, and which browsers you’ve restored so we can honor\n    the pass.\n- category: behavioral\n  text: Cloudflare Analytics Engine records anonymous game events (open, win, share).\npurposes:\n- purpose: sign-in\n  text: to send a magic-link sign-in\n- purpose: cross-browser restore\n  text: saved so that daily reopens solved on another browser\n- purpose: honor Arcade Pass\n  text: so we can honor the pass\nretention:\n- scope: account rows\n  period: until you delete the account\n  text: Account rows stay until you delete the account.\n- scope: payment ledger\n  period: as long as we need them to restore a purchase or meet bookkeeping rules\n  text: Payment ledger rows stay as long as we need them to restore a purchase or meet bookkeeping rules.\n- scope: magic-link tokens\n  period: expire\n  text: Magic-link tokens expire.\nresidency: []\ntransfers: []\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Account → Delete account\n  text: Delete account — Settings → Account → Delete account. That deletes the account, finished dailies stored\n    on it, leaderboard scores, and sessions.\nrights:\n- right: opt out of public leaderboards\n  text: Opting out hides you from listings.\n- right: delete account\n  text: Delete account — Settings → Account → Delete account.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/coronet-one/privacy/coronet-one-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Coronet Arcade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Games
- Puzzles
- Word Games
- Logic Puzzles
- MCP
- AI Agents
---
