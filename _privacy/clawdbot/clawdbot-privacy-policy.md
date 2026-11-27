---
api_specs:
- filename: clawdbot-clawdbot-api-api-openapi.yml
  format: yaml
  label: Clawdbot Clawdbot API
  slug: clawdbot-clawdbot-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-clawdbot-api-api-openapi.yml
- filename: clawdbot-npm-api-openapi.yml
  format: yaml
  label: Clawdbot Npm API
  slug: clawdbot-npm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-npm-api-openapi.yml
- filename: clawdbot-packages-api-openapi.yml
  format: yaml
  label: Clawdbot Packages API
  slug: clawdbot-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-packages-api-openapi.yml
- filename: clawdbot-plugins-api-openapi.yml
  format: yaml
  label: Clawdbot Plugins API
  slug: clawdbot-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-plugins-api-openapi.yml
- filename: clawdbot-skills-api-openapi.yml
  format: yaml
  label: Clawdbot Skills API
  slug: clawdbot-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-skills-api-openapi.yml
- filename: clawdbot-transfers-api-openapi.yml
  format: yaml
  label: Clawdbot Transfers API
  slug: clawdbot-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-transfers-api-openapi.yml
- filename: clawdbot-users-api-openapi.yml
  format: yaml
  label: Clawdbot Users API
  slug: clawdbot-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdbot/openapi/clawdbot-users-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: device
    text: Connection and setup data, such as gateway host/port, tokens, passwords, TLS fingerprints, pairing state, local display name, wake-word settings, feature toggles, local discovery state, and push or notification tokens on supported platforms.
  - category: location
    text: Location data if you enable location sharing.
  - category: contact
    text: Contacts if you enable contact search or contact creation.
  - category: communication
    text: Microphone audio if you use voice transcription, talk mode, voice wake, or audio capture.
  - category: behavioral
    text: Motion sensor data if you enable activity or pedometer features.
  deletion:
    route: disconnect from gateway, clear app storage, or uninstall
    text: You can disconnect from a gateway, clear app storage, or uninstall the app or extension.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: gateway delivery
    text: OpenClaw sends commands, content, and device capability data to the gateway you configure.
  retention:
  - period: until you remove it
    scope: data stored on your device
    text: Data stored on your device generally remains there until you remove it, clear app data, or uninstall the app.
  rights:
  - right: deny or revoke permissions
    text: You can deny or revoke iOS or Android permissions at any time in system settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clawdbot
provenance_date: '2026-11-09'
provider_name: Clawdbot
provider_slug: clawdbot
slug: clawdbot-privacy-policy
source_date: '2026-11-09'
source_filename: clawdbot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openclaw.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clawdbot\naid: clawdbot\nurl: https://openclaw.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Connection and setup data, such as gateway host/port, tokens, passwords, TLS fingerprints, pairing state,\n    local display name, wake-word settings, feature toggles, local discovery state, and push or notification tokens\n    on supported platforms.\n- category: location\n  text: Location data if you enable location sharing.\n- category: contact\n  text: Contacts if you enable contact search or contact creation.\n- category: communication\n\
  \  text: Microphone audio if you use voice transcription, talk mode, voice wake, or audio capture.\n- category: behavioral\n  text: Motion sensor data if you enable activity or pedometer features.\npurposes:\n- purpose: gateway delivery\n  text: OpenClaw sends commands, content, and device capability data to the gateway you configure.\nretention:\n- scope: data stored on your device\n  period: until you remove it\n  text: Data stored on your device generally remains there until you remove it, clear app data, or uninstall the\n    app.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: disconnect from gateway, clear app storage, or uninstall\n  text: You can disconnect from a gateway, clear app storage, or uninstall the app or extension.\nrights:\n- right: deny or revoke permissions\n  text: You can deny or revoke iOS or Android permissions at any time in system settings.\nsale_or_sharing:\n \
  \ stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/clawdbot/privacy/clawdbot-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Clawdbot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Open Source
- Personal Assistant
- Automation
---
