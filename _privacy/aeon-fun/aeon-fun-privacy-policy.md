---
api_specs:
- filename: aeon-fun-api-openapi.json
  format: json
  label: aeon agent-facing API API
  slug: aeon-agent-facing-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeon-fun/openapi/_original/aeon-fun-api-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We keep your GitHub username, avatar, and GitHub sign-in token in a server-side session.
  - category: contact
    text: Wallet and auth (Privy and its wallet partners)
  - category: behavioral
    text: 'PostHog also records browsing sessions on this site: the pages you move through, clicks, scrolling, and console errors.'
  - category: device
    text: which capture usage events and basic device/browser information and help us catch errors
  - category: financial
    text: Onchain transactions are, by nature, public and permanent on the Base blockchain.
  deletion:
    route: email request to aaron@aeon.fun
    text: Request access to or deletion of any personal data we hold by emailing aaron@aeon.fun .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: improve the site
    text: We use these signals in aggregate to improve the site, not to identify you individually.
  - purpose: run Aeon Connect
    text: Connect reads and writes the repo you picked through the GitHub App
  - purpose: find broken flows
    text: we use them to find broken flows and dead ends rather than to watch individual people
  retention:
  - period: 30 days
    scope: session recordings
    text: Recordings are deleted automatically after 30 days
  - period: 14 months
    scope: analytics events
    text: 'Analytics events (Umami, PostHog, Google Analytics): kept for up to 14 months, then deleted.'
  - period: 7 days without use
    scope: Aeon Connect sign-in sessions
    text: 'Aeon Connect sign-in sessions: deleted on log out, or after 7 days without use.'
  - period: 12 months
    scope: emails
    text: 'Emails you send us: kept as long as needed to answer you, then deleted within 12 months.'
  rights:
  - right: access and deletion
    text: Request access to or deletion of any personal data we hold by emailing aaron@aeon.fun .
  role:
    text: The data controller for aeon.fun, Aeon Connect, and the aeon plugin is Aeon Inc .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share it for advertising.
  subprocessors:
    text: Who receives data Data you share with the site may be processed by the providers that power these features - website hosting (Vercel), Aeon Connect session storage (Upstash), GitHub (where your agent and its secrets live), analytics and session recording (Umami, PostHog, Google Analytics), wallet and auth (Privy and its wallet partners), and swap routing (0x).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aeon
provenance_date: '2026-11-09'
provider_name: Aeon
provider_slug: aeon-fun
slug: aeon-fun-privacy-policy
source_date: '2026-11-09'
source_filename: aeon-fun-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aeon.fun/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aeon\naid: aeon-fun\nurl: https://www.aeon.fun/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for aeon.fun, Aeon Connect, and the aeon plugin is Aeon Inc .\ndata_categories:\n- category: identifying\n  text: We keep your GitHub username, avatar, and GitHub sign-in token in a server-side session.\n- category: contact\n  text: Wallet and auth (Privy and its wallet partners)\n- category: behavioral\n  text: 'PostHog also records browsing sessions on this site: the pages you move through, clicks, scrolling, and\n    console errors.'\n- category: device\n  text: which\
  \ capture usage events and basic device/browser information and help us catch errors\n- category: financial\n  text: Onchain transactions are, by nature, public and permanent on the Base blockchain.\npurposes:\n- purpose: improve the site\n  text: We use these signals in aggregate to improve the site, not to identify you individually.\n- purpose: run Aeon Connect\n  text: Connect reads and writes the repo you picked through the GitHub App\n- purpose: find broken flows\n  text: we use them to find broken flows and dead ends rather than to watch individual people\nretention:\n- scope: session recordings\n  period: 30 days\n  text: Recordings are deleted automatically after 30 days\n- scope: analytics events\n  period: 14 months\n  text: 'Analytics events (Umami, PostHog, Google Analytics): kept for up to 14 months, then deleted.'\n- scope: Aeon Connect sign-in sessions\n  period: 7 days without use\n  text: 'Aeon Connect sign-in sessions: deleted on log out, or after 7 days without use.'\n\
  - scope: emails\n  period: 12 months\n  text: 'Emails you send us: kept as long as needed to answer you, then deleted within 12 months.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who receives data Data you share with the site may be processed by the providers that power these features\n    - website hosting (Vercel), Aeon Connect session storage (Upstash), GitHub (where your agent and its secrets\n    live), analytics and session recording (Umami, PostHog, Google Analytics), wallet and auth (Privy and its wallet\n    partners), and swap routing (0x).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to aaron@aeon.fun\n  text: Request access to or deletion of any personal data we hold by emailing aaron@aeon.fun .\nrights:\n- right: access and deletion\n  text: Request access to or deletion of any personal data we hold by emailing aaron@aeon.fun .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or\
  \ share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/aeon-fun/privacy/aeon-fun-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Aeon's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Open Source
- Framework
- Enterprise
---
