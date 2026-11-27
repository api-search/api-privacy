---
api_specs:
- filename: betterimage-io-openapi-generated.yml
  format: yaml
  label: BetterImage.io API
  slug: betterimage-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterimage-io/openapi/_ae-authored/betterimage-io-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your email address
  - category: identifying
    text: Your IP address is used to limit how many requests one visitor can make.
  - category: behavioral
    text: We count downloads (with the time, the kind of download, the layout and the size) and MCP connections and tool calls (with the tool name, the outcome and how long it took).
  - category: device
    text: Cloudflare gives us aggregate visit statistics (page views, referrers, countries, browser and device types)
  - category: financial
    text: If you subscribe, the Stripe customer and subscription identifiers, the plan and its status.
  deletion:
    route: Account settings
    text: From your settings you can change your email or password and delete the account yourself.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the requested service
    text: 'To provide what you asked for (performance of a contract): your account, templates, renders, purchases, API keys and subscriptions, connected apps, and the emails needed to run them.'
  - purpose: Security and operation
    text: 'To keep the service secure and working (our legitimate interest, which we believe does not override yours): rate limiting, Turnstile, usage counts, Cloudflare''s aggregate statistics, and periodic cleanup.'
  - purpose: Legal obligations
    text: 'To meet legal obligations: keeping payment records for tax and accounting purposes.'
  residency:
  - region: Germany
    text: Hetzner (the server in Germany that runs the application and its database)
  - region: European Union
    text: Our Sentry project runs in Sentry's EU region, so error reports stay in the European Union.
  retention:
  - period: until you delete the account, or until we close it for abuse
    scope: Account data, templates, API keys, usage counts and connected apps
    text: 'Account data, templates, API keys, usage counts and connected apps: until you delete the account, or until we close it for abuse.'
  - period: 14 days
    scope: Sign-in sessions
    text: 'Sign-in sessions: 14 days; app sign-ins until their tokens expire.'
  - period: 90 days
    scope: MCP usage entries
    text: 'MCP usage entries: 90 days.'
  - period: never stored
    scope: IP address
    text: 'Your IP address: never stored.'
  - period: as long as tax and accounting rules require
    scope: Payment records
    text: the payment record for as long as tax and accounting rules require
  rights:
  - right: Access
    text: you can ask for access to the personal data we hold about you
  - right: Portability
    text: receive a copy in a portable format
  role:
    text: betterimage.io is run by its operator, based in Poland, who is the data controller for everything described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we never sell or share your data
  subprocessors:
    text: Each provider works for us for one purpose only
    url: null
  transfers:
  - mechanism: DPF
    text: the EU-US Data Privacy Framework where the provider is certified
  - mechanism: SCC
    text: the European Commission's standard contractual clauses otherwise
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BetterImage.io
provenance_date: '2026-11-09'
provider_name: BetterImage.io
provider_slug: betterimage-io
slug: betterimage-io-privacy-policy
source_date: '2026-11-09'
source_filename: betterimage-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://betterimage.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BetterImage.io\naid: betterimage-io\nurl: https://betterimage.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: betterimage.io is run by its operator, based in Poland, who is the data controller for everything described\n    here.\ndata_categories:\n- category: contact\n  text: we store your email address\n- category: identifying\n  text: Your IP address is used to limit how many requests one visitor can make.\n- category: behavioral\n  text: We count downloads (with the time, the kind of download, the layout and the size) and MCP connections and\n    tool calls (with the tool name,\
  \ the outcome and how long it took).\n- category: device\n  text: Cloudflare gives us aggregate visit statistics (page views, referrers, countries, browser and device types)\n- category: financial\n  text: If you subscribe, the Stripe customer and subscription identifiers, the plan and its status.\npurposes:\n- purpose: Provide the requested service\n  text: 'To provide what you asked for (performance of a contract): your account, templates, renders, purchases,\n    API keys and subscriptions, connected apps, and the emails needed to run them.'\n- purpose: Security and operation\n  text: 'To keep the service secure and working (our legitimate interest, which we believe does not override yours):\n    rate limiting, Turnstile, usage counts, Cloudflare''s aggregate statistics, and periodic cleanup.'\n- purpose: Legal obligations\n  text: 'To meet legal obligations: keeping payment records for tax and accounting purposes.'\nretention:\n- scope: Account data, templates, API keys, usage counts\
  \ and connected apps\n  period: until you delete the account, or until we close it for abuse\n  text: 'Account data, templates, API keys, usage counts and connected apps: until you delete the account, or until\n    we close it for abuse.'\n- scope: Sign-in sessions\n  period: 14 days\n  text: 'Sign-in sessions: 14 days; app sign-ins until their tokens expire.'\n- scope: MCP usage entries\n  period: 90 days\n  text: 'MCP usage entries: 90 days.'\n- scope: IP address\n  period: never stored\n  text: 'Your IP address: never stored.'\n- scope: Payment records\n  period: as long as tax and accounting rules require\n  text: the payment record for as long as tax and accounting rules require\nresidency:\n- region: Germany\n  text: Hetzner (the server in Germany that runs the application and its database)\n- region: European Union\n  text: Our Sentry project runs in Sentry's EU region, so error reports stay in the European Union.\ntransfers:\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework\
  \ where the provider is certified\n- mechanism: SCC\n  text: the European Commission's standard contractual clauses otherwise\nsubprocessors:\n  url: null\n  text: Each provider works for us for one purpose only\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings\n  text: From your settings you can change your email or password and delete the account yourself.\nrights:\n- right: Access\n  text: you can ask for access to the personal data we hold about you\n- right: Portability\n  text: receive a copy in a portable format\nsale_or_sharing:\n  stance: prohibited\n  text: we never sell or share your data\n"
source_yaml_url: https://artifacts.apis.io/betterimage-io/privacy/betterimage-io-privacy-policy.yml
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
summary_line: 23 quoted statements, read from BetterImage.io's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Image Generation
---
