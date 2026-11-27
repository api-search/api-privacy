---
api_specs:
- filename: blinkinbox-club-account-api-openapi.yml
  format: yaml
  label: blinkinbox-club Account API
  slug: blinkinbox-club-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-account-api-openapi.yml
- filename: blinkinbox-club-domains-api-openapi.yml
  format: yaml
  label: blinkinbox-club Domains API
  slug: blinkinbox-club-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-domains-api-openapi.yml
- filename: blinkinbox-club-inboxes-api-openapi.yml
  format: yaml
  label: blinkinbox-club Inboxes API
  slug: blinkinbox-club-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-inboxes-api-openapi.yml
- filename: blinkinbox-club-messages-api-openapi.yml
  format: yaml
  label: blinkinbox-club Messages API
  slug: blinkinbox-club-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-messages-api-openapi.yml
- filename: blinkinbox-club-webhooks-api-openapi.yml
  format: yaml
  label: blinkinbox-club Webhooks API
  slug: blinkinbox-club-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blinkinbox-club/openapi/blinkinbox-club-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: communication
    text: 'Mail sent to your inbox : sender, subject, body and attachments, plus the codes and links we extract from them.'
  - category: contact
    text: 'Accounts (developers only): email address, a hashed password and hashed API keys.'
  - category: identifying
    text: 'Connected apps : when you approve an AI client over OAuth, we store its name, redirect address, the scopes you granted and hashed tokens.'
  - category: device
    text: 'Operational logs : IP address and request metadata, used for rate limiting and abuse prevention.'
  - category: behavioral
    text: Google Analytics, with advertising features disabled, to see which pages are used.
  deletion:
    route: Delete messages or whole inboxes at any time; contact for deletion requests
    text: You can delete messages or whole inboxes earlier at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Rate limiting and abuse prevention
    text: 'Operational logs : IP address and request metadata, used for rate limiting and abuse prevention.'
  - purpose: Enforce inbox limit
    text: For browser inboxes we also keep a keyed hash of your IP address (never the IP itself) to enforce the 3-per-day limit.
  - purpose: Site analytics
    text: We use Google Analytics, with advertising features disabled, to see which pages are used.
  - purpose: Developer sign-in and account
    text: a code to confirm your email address when you sign up, a code each time you sign in, and a password reset link when you ask for one.
  retention:
  - period: 24 hours
    scope: Inboxes, IP hash and all mail
    text: Inboxes, the IP hash and all mail are deleted automatically 24 hours after the inbox expires.
  rights:
  - right: Revoke connected app
    text: Revoke it from the dashboard at any time.
  - right: Change analytics choice
    text: Change your choice at any time with Cookie settings at the bottom of every page; turning analytics off removes its cookies.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Sell or share the content of your mail.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: blinkinbox-club
provenance_date: '2026-11-09'
provider_name: blinkinbox-club
provider_slug: blinkinbox-club
slug: blinkinbox-club-privacy-policy
source_date: '2026-11-09'
source_filename: blinkinbox-club-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blinkinbox.club/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: blinkinbox-club\naid: blinkinbox-club\nurl: https://blinkinbox.club/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: communication\n  text: 'Mail sent to your inbox : sender, subject, body and attachments, plus the codes and links we extract from\n    them.'\n- category: contact\n  text: 'Accounts (developers only): email address, a hashed password and hashed API keys.'\n- category: identifying\n  text: 'Connected apps : when you approve an AI client over OAuth, we store its name, redirect address, the scopes\n    you granted and hashed tokens.'\n- category:\
  \ device\n  text: 'Operational logs : IP address and request metadata, used for rate limiting and abuse prevention.'\n- category: behavioral\n  text: Google Analytics, with advertising features disabled, to see which pages are used.\npurposes:\n- purpose: Rate limiting and abuse prevention\n  text: 'Operational logs : IP address and request metadata, used for rate limiting and abuse prevention.'\n- purpose: Enforce inbox limit\n  text: For browser inboxes we also keep a keyed hash of your IP address (never the IP itself) to enforce the 3-per-day\n    limit.\n- purpose: Site analytics\n  text: We use Google Analytics, with advertising features disabled, to see which pages are used.\n- purpose: Developer sign-in and account\n  text: a code to confirm your email address when you sign up, a code each time you sign in, and a password reset\n    link when you ask for one.\nretention:\n- scope: Inboxes, IP hash and all mail\n  period: 24 hours\n  text: Inboxes, the IP hash and all mail are deleted\
  \ automatically 24 hours after the inbox expires.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete messages or whole inboxes at any time; contact for deletion requests\n  text: You can delete messages or whole inboxes earlier at any time.\nrights:\n- right: Revoke connected app\n  text: Revoke it from the dashboard at any time.\n- right: Change analytics choice\n  text: Change your choice at any time with Cookie settings at the bottom of every page; turning analytics off removes\n    its cookies.\nsale_or_sharing:\n  stance: prohibited\n  text: Sell or share the content of your mail.\n"
source_yaml_url: https://artifacts.apis.io/blinkinbox-club/privacy/blinkinbox-club-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from blinkinbox-club's own page on 2026-11-09.
synthetic: false
tags:
- Email
- MCP
- Developer Tools
- Disposable
---
