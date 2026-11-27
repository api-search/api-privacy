---
api_specs:
- filename: diagram-la-diagrams-api-openapi.yml
  format: yaml
  label: Diagram Diagrams API
  slug: diagram-la-diagrams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diagram-la/openapi/diagram-la-diagrams-api-openapi.yml
- filename: diagram-la-projects-api-openapi.yml
  format: yaml
  label: Diagram Projects API
  slug: diagram-la-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diagram-la/openapi/diagram-la-projects-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: your email address, a user ID, and (if you sign in with Google) your Google account''s name.'
  - category: financial
    text: if you upgrade, Stripe handles payment; we keep your plan and a Stripe customer ID, never your card number.
  - category: device
    text: 'Technical logs: our hosting keeps standard request logs (IP address, time, page requested) for security and debugging.'
  - category: behavioral
    text: Diagram records page views, clicks, how pages are scrolled and used (including recordings of sessions on our pages),
  - category: other
    text: the diagrams you publish (their HTML, title, and every version), projects, orgs, and who you add to them.
  deletion:
    route: Delete account on your Account page
    text: To delete your account and everything in it, use Delete account on your Account page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running the service
    text: signing you in, emailing you about your account and when someone adds you to a project or org (never marketing)
  - purpose: No AI training on diagrams
    text: We don't use your diagrams to train AI models
  - purpose: Google user data limits
    text: We don't use Google user data for advertising, to train or improve AI models
  retention:
  - period: null
    scope: Content
    text: Your content stays until you delete it.
  - period: own schedule
    scope: Backups and logs
    text: Backups and logs age out on their own schedule.
  rights:
  - right: See and change content
    text: You can see and change your content in the app at any time
  - right: Copy or deletion of data
    text: ask for a copy of your data or its deletion
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we don't sell or rent personal information
  subprocessors:
    text: 'We use a few providers to run the service, each only for its job:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Diagram
provenance_date: '2026-11-09'
provider_name: Diagram
provider_slug: diagram-la
slug: diagram-la-privacy-policy
source_date: '2026-11-09'
source_filename: diagram-la-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://diagram.la/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Diagram\naid: diagram-la\nurl: https://diagram.la/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Your account: your email address, a user ID, and (if you sign in with Google) your Google account''s name.'\n- category: financial\n  text: if you upgrade, Stripe handles payment; we keep your plan and a Stripe customer ID, never your card number.\n- category: device\n  text: 'Technical logs: our hosting keeps standard request logs (IP address, time, page requested) for security\n    and debugging.'\n- category: behavioral\n  text:\
  \ Diagram records page views, clicks, how pages are scrolled and used (including recordings of sessions on\n    our pages),\n- category: other\n  text: the diagrams you publish (their HTML, title, and every version), projects, orgs, and who you add to them.\npurposes:\n- purpose: Running the service\n  text: signing you in, emailing you about your account and when someone adds you to a project or org (never marketing)\n- purpose: No AI training on diagrams\n  text: We don't use your diagrams to train AI models\n- purpose: Google user data limits\n  text: We don't use Google user data for advertising, to train or improve AI models\nretention:\n- scope: Content\n  period: null\n  text: Your content stays until you delete it.\n- scope: Backups and logs\n  period: own schedule\n  text: Backups and logs age out on their own schedule.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use a few providers to run the service, each only for its job:'\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Delete account on your Account page\n  text: To delete your account and everything in it, use Delete account on your Account page\nrights:\n- right: See and change content\n  text: You can see and change your content in the app at any time\n- right: Copy or deletion of data\n  text: ask for a copy of your data or its deletion\nsale_or_sharing:\n  stance: prohibited\n  text: we don't sell or rent personal information\n"
source_yaml_url: https://artifacts.apis.io/diagram-la/privacy/diagram-la-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Diagram's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Diagramming
- Visualization
- Artificial Intelligence
- MCP
- Collaboration
- Developer Tools
---
