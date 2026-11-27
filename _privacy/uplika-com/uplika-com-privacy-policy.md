---
api_specs:
- filename: uplika-com-automations-api-openapi.yml
  format: yaml
  label: Uplika Automations API
  slug: uplika-com-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-automations-api-openapi.yml
- filename: uplika-com-connecting-channels-api-openapi.yml
  format: yaml
  label: Uplika Connecting channels API
  slug: uplika-com-connecting-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-connecting-channels-api-openapi.yml
- filename: uplika-com-errors-api-openapi.yml
  format: yaml
  label: Uplika Errors API
  slug: uplika-com-errors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-errors-api-openapi.yml
- filename: uplika-com-inbox-and-contacts-api-openapi.yml
  format: yaml
  label: Uplika Inbox and contacts API
  slug: uplika-com-inbox-and-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-inbox-and-contacts-api-openapi.yml
- filename: uplika-com-media-api-openapi.yml
  format: yaml
  label: Uplika Media API
  slug: uplika-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-media-api-openapi.yml
- filename: uplika-com-platforms-api-openapi.yml
  format: yaml
  label: Uplika Platforms API
  slug: uplika-com-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-platforms-api-openapi.yml
- filename: uplika-com-posts-api-openapi.yml
  format: yaml
  label: Uplika Posts API
  slug: uplika-com-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-posts-api-openapi.yml
- filename: uplika-com-replies-and-insights-api-openapi.yml
  format: yaml
  label: Uplika Replies and insights API
  slug: uplika-com-replies-and-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-replies-and-insights-api-openapi.yml
- filename: uplika-com-troubleshooting-and-faq-api-openapi.yml
  format: yaml
  label: Uplika Troubleshooting and FAQ API
  slug: uplika-com-troubleshooting-and-faq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uplika-com/openapi/uplika-com-troubleshooting-and-faq-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email, name, profile image
  - category: device
    text: IP address, browser
  - category: communication
    text: What you send through the Contact us window in the dashboard, with any images, so we can answer it.
  deletion:
    route: Dashboard settings or the data deletion page
    text: You can delete your account yourself from the dashboard settings, and if you cannot sign in, follow the steps on the data deletion page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Session management and spotting unusual sign-ins
    text: Session management and spotting unusual sign-ins.
  retention:
  - period: Deleted the moment you delete your account
    scope: Account, sessions, workspace, identity records, channel connections, publishing history
    text: Deleted the moment you delete your account
  - period: Deleted automatically after 7 days
    scope: Request logs
    text: Deleted automatically after 7 days
  - period: 24 hours after the post settles
    scope: Images and videos attached to a post
    text: Images and videos you attach are deleted automatically 24 hours after the post settles.
  rights:
  - right: See, correct, delete or restrict processing
    text: You can ask to see, correct, delete or restrict processing of your data at any time.
  role:
    text: It is the entity that decides why and how your personal data is processed.
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
name: Uplika
provenance_date: '2026-11-10'
provider_name: Uplika
provider_slug: uplika-com
slug: uplika-com-privacy-policy
source_date: '2026-11-10'
source_filename: uplika-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://uplika.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Uplika\naid: uplika-com\nurl: https://uplika.com/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: It is the entity that decides why and how your personal data is processed.\ndata_categories:\n- category: identifying\n  text: Email, name, profile image\n- category: device\n  text: IP address, browser\n- category: communication\n  text: What you send through the Contact us window in the dashboard, with any images, so we can answer it.\npurposes:\n- purpose: Session management and spotting unusual sign-ins\n  text: Session management and spotting unusual sign-ins.\nretention:\n- scope:\
  \ Account, sessions, workspace, identity records, channel connections, publishing history\n  period: Deleted the moment you delete your account\n  text: Deleted the moment you delete your account\n- scope: Request logs\n  period: Deleted automatically after 7 days\n  text: Deleted automatically after 7 days\n- scope: Images and videos attached to a post\n  period: 24 hours after the post settles\n  text: Images and videos you attach are deleted automatically 24 hours after the post settles.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard settings or the data deletion page\n  text: You can delete your account yourself from the dashboard settings, and if you cannot sign in, follow the\n    steps on the data deletion page.\nrights:\n- right: See, correct, delete or restrict processing\n  text: You can ask to see, correct, delete or restrict processing of your data at any time.\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uplika-com/privacy/uplika-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 10 quoted statements, read from Uplika's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- AI Agents
- Multi-Channel Publishing
- Automation
- Marketing
---
