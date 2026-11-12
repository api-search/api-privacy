---
api_specs:
- filename: clicon-app-openapi-generated.yml
  format: yaml
  label: Clicon Lotus Bot Tracking API
  slug: clicon-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clicon-app/openapi/_ae-authored/clicon-app-openapi-generated.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: behavioral
    text: It collects aggregated metrics (pages visited, referrers and device type), with no tracking cookies and no personal identification.
  - category: contact
    text: The form asks for name, email and message.
  - category: device
    text: AI crawler log When an identified AI crawler (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, Bingbot, Applebot-Extended, Meta-ExternalAgent, Bytespider or CCBot) visits the site, the middleware sends a record to lotus.clicon.app that includes the domain, the bot name and the accessed path.
  deletion:
    route: email request to martin@clicon.app
    text: You can request deletion of your data by writing to martin@clicon.app.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: measure site traffic
    text: We use Vercel Analytics to measure site traffic.
  - purpose: remember language
    text: that only remembers the language you chose (Spanish or English).
  - purpose: reply to contact form messages
    text: That data is emailed to martin@clicon.app via Resend and used only to reply to you.
  retention:
  - period: null
    scope: contact form data
    text: It is not stored in a database or shared with third parties.
  rights:
  - right: deletion
    text: You can request deletion of your data by writing to martin@clicon.app.
  role:
    text: Clicon is Martín Endara's studio, based in the City of Buenos Aires, Argentina.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clicon
provenance_date: '2026-11-09'
provider_name: Clicon
provider_slug: clicon-app
slug: clicon-app-privacy-policy
source_date: '2026-11-09'
source_filename: clicon-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clicon.app/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clicon\naid: clicon-app\nurl: https://clicon.app/en/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Clicon is Martín Endara's studio, based in the City of Buenos Aires, Argentina.\ndata_categories:\n- category: behavioral\n  text: It collects aggregated metrics (pages visited, referrers and device type), with no tracking cookies and\n    no personal identification.\n- category: contact\n  text: The form asks for name, email and message.\n- category: device\n  text: AI crawler log When an identified AI crawler (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, Bingbot,\n    Applebot-Extended,\
  \ Meta-ExternalAgent, Bytespider or CCBot) visits the site, the middleware sends a record to\n    lotus.clicon.app that includes the domain, the bot name and the accessed path.\npurposes:\n- purpose: measure site traffic\n  text: We use Vercel Analytics to measure site traffic.\n- purpose: remember language\n  text: that only remembers the language you chose (Spanish or English).\n- purpose: reply to contact form messages\n  text: That data is emailed to martin@clicon.app via Resend and used only to reply to you.\nretention:\n- scope: contact form data\n  period: null\n  text: It is not stored in a database or shared with third parties.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to martin@clicon.app\n  text: You can request deletion of your data by writing to martin@clicon.app.\nrights:\n- right: deletion\n  text: You can request deletion of your data by writing to martin@clicon.app.\n\
  sale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clicon-app/privacy/clicon-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 10 quoted statements, read from Clicon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative Engine Optimization
- MCP
- AI Crawlers
- Analytics
- Business Tools
- SEO
---
