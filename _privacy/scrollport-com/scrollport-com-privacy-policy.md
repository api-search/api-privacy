---
api_specs:
- filename: scrollport-com-openapi-generated.yml
  format: yaml
  label: scrollport-com API
  slug: scrollport-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrollport-com/openapi/_ae-authored/scrollport-com-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, plus a provider identifier when you sign in with Google.
  - category: financial
    text: An append-only ledger of top-ups, holds, charges and refunds.
  - category: behavioral
    text: 'For each call: which capability, the input you sent, the result, the estimated and final cost, and timing.'
  - category: communication
    text: If you use our support form, we send your name, reply email, subject and message to our support inbox through Resend.
  - category: other
    text: Files a run produces (audio, images, datasets), in object storage, reachable only through expiring signed links.
  deletion:
    route: account deletion request or workspace closure
    text: You can ask us to delete your account and its data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver calls to capability providers
    text: To run a capability we must send your input to the provider that performs it
  - purpose: usage log and failed-run explanation
    text: We keep inputs and results so the usage log can show them back to you and so a failed run can be explained.
  - purpose: product analytics
    text: we use PostHog's EU service for bounded browser statistics such as page class and app-connection intent.
  residency:
  - region: European Union
    text: Our database and storage run in the European Union.
  retention:
  - period: while your account is open
    scope: Non-Google run records and ledger entries
    text: Non-Google run records and ledger entries are kept while your account is open.
  - period: 30 days
    scope: Google Workspace run content
    text: Raw Google Workspace run inputs, results and provider error content are retained for no more than 30 days.
  - period: 7 days
    scope: Private Google artifacts
    text: Private Google artifacts are retained for no more than 7 days.
  - period: null
    scope: Support messages
    text: Support messages remain in our support inbox only while needed to reply, resolve the request, prevent abuse or meet legal obligations.
  - period: 30 days
    scope: Analytics browser identifier
    text: A random first-party browser identifier is stored for up to 30 days so repeat visits can be counted consistently.
  rights:
  - right: access, correct, export or delete
    text: you may have the right to access, correct, export or delete your personal data
  - right: object to certain processing
    text: to object to certain processing
  - right: complain to data protection authority
    text: If you are in the EU or UK you may also complain to your data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share it for advertising.
  subprocessors:
    text: Requested Google data passes through Nango (OAuth token management), Railway (application hosting), Google Cloud Model Armor (security screening) and Supabase (EU database and private artifact storage)
    url: null
  transfers:
  - mechanism: other
    text: Capability providers operate in their own regions, so running a capability may send your input outside the EU
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: scrollport-com
provenance_date: '2026-11-10'
provider_name: scrollport-com
provider_slug: scrollport-com
slug: scrollport-com-privacy-policy
source_date: '2026-11-10'
source_filename: scrollport-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scrollport.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: scrollport-com\naid: scrollport-com\nurl: https://scrollport.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, plus a provider identifier when you sign in with Google.\n- category: financial\n  text: An append-only ledger of top-ups, holds, charges and refunds.\n- category: behavioral\n  text: 'For each call: which capability, the input you sent, the result, the estimated and final cost, and timing.'\n- category: communication\n  text: If you use our support form, we send your name, reply email, subject and\
  \ message to our support inbox through\n    Resend.\n- category: other\n  text: Files a run produces (audio, images, datasets), in object storage, reachable only through expiring signed\n    links.\npurposes:\n- purpose: deliver calls to capability providers\n  text: To run a capability we must send your input to the provider that performs it\n- purpose: usage log and failed-run explanation\n  text: We keep inputs and results so the usage log can show them back to you and so a failed run can be explained.\n- purpose: product analytics\n  text: we use PostHog's EU service for bounded browser statistics such as page class and app-connection intent.\nretention:\n- scope: Non-Google run records and ledger entries\n  period: while your account is open\n  text: Non-Google run records and ledger entries are kept while your account is open.\n- scope: Google Workspace run content\n  period: 30 days\n  text: Raw Google Workspace run inputs, results and provider error content are retained for no\
  \ more than 30 days.\n- scope: Private Google artifacts\n  period: 7 days\n  text: Private Google artifacts are retained for no more than 7 days.\n- scope: Support messages\n  period: null\n  text: Support messages remain in our support inbox only while needed to reply, resolve the request, prevent abuse\n    or meet legal obligations.\n- scope: Analytics browser identifier\n  period: 30 days\n  text: A random first-party browser identifier is stored for up to 30 days so repeat visits can be counted consistently.\nresidency:\n- region: European Union\n  text: Our database and storage run in the European Union.\ntransfers:\n- mechanism: other\n  text: Capability providers operate in their own regions, so running a capability may send your input outside the\n    EU\nsubprocessors:\n  url: null\n  text: Requested Google data passes through Nango (OAuth token management), Railway (application hosting), Google\n    Cloud Model Armor (security screening) and Supabase (EU database and private\
  \ artifact storage)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request or workspace closure\n  text: You can ask us to delete your account and its data.\nrights:\n- right: access, correct, export or delete\n  text: you may have the right to access, correct, export or delete your personal data\n- right: object to certain processing\n  text: to object to certain processing\n- right: complain to data protection authority\n  text: If you are in the EU or UK you may also complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/scrollport-com/privacy/scrollport-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from scrollport-com's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- API Tools
- Pay-per-use
- Search
- Web Scraping
---
