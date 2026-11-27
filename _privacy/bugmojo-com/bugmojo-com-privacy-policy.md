---
api_specs:
- filename: bugmojo-com-openapi-generated.yml
  format: yaml
  label: BugMojo API
  slug: bugmojo-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bugmojo-com/openapi/_ae-authored/bugmojo-com-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data. When you create an account we collect your name, email, and authentication credentials, plus workspace, project, and team membership.
  - category: device
    text: environment details (browser, OS, viewport, page URL)
  - category: behavioral
    text: a DOM session replay (via rrweb), console logs, network request metadata (never request or response bodies), screenshots
  - category: communication
    text: If you turn them on for a capture, we also collect a tab video and a voice note.
  - category: behavioral
    text: Google Analytics counts visits and tells us which pages and sources (search engines, AI assistants, other sites) bring people to the site.
  deletion:
    route: In-app deletion of captures, issues, or account
    text: You can delete individual captures, issues, or your entire account at any time; deletion removes the associated stored artifacts.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: store and display captured bugs, power session replay, route issues to people or AI agents, and sync with your connected tools'
  - purpose: Secure, maintain, improve product
    text: To secure, maintain, and improve the product, and to communicate with you about your account.
  retention:
  - period: 7 days
    scope: Quick Capture anonymous captures
    text: anonymous captures after 7 days
  - period: 30 days
    scope: Quick Capture free-tier captures
    text: free-tier captures after 30 days
  - period: null
    scope: Account and workspace data
    text: Account and workspace data is retained while your account is active.
  rights:
  - right: access, export, correct, delete
    text: You can access, export, correct, or delete your data.
  - right: additional rights under GDPR or CCPA
    text: Depending on where you live, you may have additional rights under laws such as the GDPR or CCPA.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use bug capture content for advertising.
  subprocessors:
    text: 'We share data only with infrastructure providers that help us run the service, under contract: app hosting (Vercel), the database (Neon), object storage (AWS S3)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BugMojo
provenance_date: '2026-11-09'
provider_name: BugMojo
provider_slug: bugmojo-com
slug: bugmojo-com-privacy-policy
source_date: '2026-11-09'
source_filename: bugmojo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bugmojo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BugMojo\naid: bugmojo-com\nurl: https://www.bugmojo.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data. When you create an account we collect your name, email, and authentication credentials, plus\n    workspace, project, and team membership.\n- category: device\n  text: environment details (browser, OS, viewport, page URL)\n- category: behavioral\n  text: a DOM session replay (via rrweb), console logs, network request metadata (never request or response bodies),\n    screenshots\n- category: communication\n  text:\
  \ If you turn them on for a capture, we also collect a tab video and a voice note.\n- category: behavioral\n  text: Google Analytics counts visits and tells us which pages and sources (search engines, AI assistants, other\n    sites) bring people to the site.\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: store and display captured bugs, power session replay, route issues to people or\n    AI agents, and sync with your connected tools'\n- purpose: Secure, maintain, improve product\n  text: To secure, maintain, and improve the product, and to communicate with you about your account.\nretention:\n- scope: Quick Capture anonymous captures\n  period: 7 days\n  text: anonymous captures after 7 days\n- scope: Quick Capture free-tier captures\n  period: 30 days\n  text: free-tier captures after 30 days\n- scope: Account and workspace data\n  period: null\n  text: Account and workspace data is retained while your account is active.\nresidency: []\ntransfers: []\n\
  subprocessors:\n  url: null\n  text: 'We share data only with infrastructure providers that help us run the service, under contract: app hosting\n    (Vercel), the database (Neon), object storage (AWS S3)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app deletion of captures, issues, or account\n  text: You can delete individual captures, issues, or your entire account at any time; deletion removes the associated\n    stored artifacts.\nrights:\n- right: access, export, correct, delete\n  text: You can access, export, correct, or delete your data.\n- right: additional rights under GDPR or CCPA\n  text: Depending on where you live, you may have additional rights under laws such as the GDPR or CCPA.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use bug capture content for advertising.\n"
source_yaml_url: https://artifacts.apis.io/bugmojo-com/privacy/bugmojo-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from BugMojo's own page on 2026-11-09.
synthetic: false
tags:
- Bug Tracking
- Artificial Intelligence
- Developer Tools
- Session Replay
- Open Source
---
