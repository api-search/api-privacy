---
api_specs:
- filename: heard-dev-openapi-generated.yml
  format: yaml
  label: heard-dev API
  slug: heard-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/heard-dev/openapi/_ae-authored/heard-dev-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, used for account identification and sign in codes.
  - category: device
    text: A SHA 256 hash of each device session token. We do not store the live bearer token.
  - category: financial
    text: Stripe customer and subscription identifiers. Payments are entered on Stripe hosted pages; Heard does not store full card numbers.
  - category: behavioral
    text: PostHog receives an anonymous install ID or signed in account ID, app and plan information, macOS version, processor architecture, locale, and categorical product events.
  - category: location
    text: On your first visit, heard.dev stores a first party cookie (heard_ft, 90 days) with the referring site, any campaign (utm) or ref link parameters, the page you landed on, and the time.
  deletion:
    route: Email request or in-app Delete what I've shared
    text: You can request access to, correction of, or deletion of your account data by emailing [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account identification and sign in
    text: Email address, used for account identification and sign in codes.
  - purpose: Help improve Heard models
    text: Heard can share masked usage data with us so we can train and improve Heard's models, including how Parrot decides what to say, when to speak, and how to answer what you ask.
  - purpose: Product analytics
    text: heard.dev uses PostHog product analytics (page views and download or sign up clicks), sent first party through heard.dev with no advertising and no session recording.
  retention:
  - period: while the account exists
    scope: Account records
    text: Account records are kept while the account exists and deleted on request.
  - period: 10 minutes
    scope: Pending signup codes
    text: Pending signup codes expire after 10 minutes and are then pruned.
  - period: 14 days
    scope: Stripe webhook logs
    text: Stripe webhook logs are retained for 14 days.
  - period: null
    scope: Narration text, generated audio, hosted rewrite text
    text: Heard does not retain narration text, generated audio, or hosted rewrite text after completing the request.
  - period: 7 days
    scope: Cloud agent reports
    text: Cloud agent reports are deleted after 7 days.
  - period: 30 days
    scope: Messages to agents
    text: Messages to agents expire after 7 days if the agent never picks them up and are deleted after 30 days either way.
  rights:
  - right: Access, correction, deletion
    text: You can request access to, correction of, or deletion of your account data by emailing [email protected] .
  - right: GDPR and CCPA rights
    text: Residents of the EU, UK, and California have additional rights under GDPR and CCPA.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, and we do not give it to other companies to train their models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: heard-dev
provenance_date: '2026-11-09'
provider_name: heard-dev
provider_slug: heard-dev
slug: heard-dev-privacy-policy
source_date: '2026-11-09'
source_filename: heard-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://heard.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: heard-dev\naid: heard-dev\nurl: https://heard.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, used for account identification and sign in codes.\n- category: device\n  text: A SHA 256 hash of each device session token. We do not store the live bearer token.\n- category: financial\n  text: Stripe customer and subscription identifiers. Payments are entered on Stripe hosted pages; Heard does not\n    store full card numbers.\n- category: behavioral\n  text: PostHog receives an anonymous install ID or signed in account\
  \ ID, app and plan information, macOS version,\n    processor architecture, locale, and categorical product events.\n- category: location\n  text: On your first visit, heard.dev stores a first party cookie (heard_ft, 90 days) with the referring site,\n    any campaign (utm) or ref link parameters, the page you landed on, and the time.\npurposes:\n- purpose: Account identification and sign in\n  text: Email address, used for account identification and sign in codes.\n- purpose: Help improve Heard models\n  text: Heard can share masked usage data with us so we can train and improve Heard's models, including how Parrot\n    decides what to say, when to speak, and how to answer what you ask.\n- purpose: Product analytics\n  text: heard.dev uses PostHog product analytics (page views and download or sign up clicks), sent first party through\n    heard.dev with no advertising and no session recording.\nretention:\n- scope: Account records\n  period: while the account exists\n  text: Account records\
  \ are kept while the account exists and deleted on request.\n- scope: Pending signup codes\n  period: 10 minutes\n  text: Pending signup codes expire after 10 minutes and are then pruned.\n- scope: Stripe webhook logs\n  period: 14 days\n  text: Stripe webhook logs are retained for 14 days.\n- scope: Narration text, generated audio, hosted rewrite text\n  period: null\n  text: Heard does not retain narration text, generated audio, or hosted rewrite text after completing the request.\n- scope: Cloud agent reports\n  period: 7 days\n  text: Cloud agent reports are deleted after 7 days.\n- scope: Messages to agents\n  period: 30 days\n  text: Messages to agents expire after 7 days if the agent never picks them up and are deleted after 30 days either\n    way.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request or in-app Delete what I've shared\n  text: You can request access to, correction\
  \ of, or deletion of your account data by emailing [email protected]\n    .\nrights:\n- right: Access, correction, deletion\n  text: You can request access to, correction of, or deletion of your account data by emailing [email protected]\n    .\n- right: GDPR and CCPA rights\n  text: Residents of the EU, UK, and California have additional rights under GDPR and CCPA.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, and we do not give it to other companies to train their models.\n"
source_yaml_url: https://artifacts.apis.io/heard-dev/privacy/heard-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from heard-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice
- macOS
- Developer Tools
---
