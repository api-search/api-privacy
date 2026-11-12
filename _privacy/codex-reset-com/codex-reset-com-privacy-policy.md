---
api_specs:
- filename: codex-reset-com-data-api-openapi.yml
  format: yaml
  label: Codex Reset Data API
  slug: codex-reset-com-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-data-api-openapi.yml
- filename: codex-reset-com-effort-evidence-api-openapi.yml
  format: yaml
  label: Codex Reset Effort Evidence API
  slug: codex-reset-com-effort-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-effort-evidence-api-openapi.yml
- filename: codex-reset-com-feed-api-openapi.yml
  format: yaml
  label: Codex Reset Feed API
  slug: codex-reset-com-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-feed-api-openapi.yml
- filename: codex-reset-com-feed-xml-api-openapi.yml
  format: yaml
  label: Codex Reset Feed.xml API
  slug: codex-reset-com-feed-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-feed-xml-api-openapi.yml
- filename: codex-reset-com-forecast-api-openapi.yml
  format: yaml
  label: Codex Reset Forecast API
  slug: codex-reset-com-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-forecast-api-openapi.yml
- filename: codex-reset-com-health-api-openapi.yml
  format: yaml
  label: Codex Reset Health API
  slug: codex-reset-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-health-api-openapi.yml
- filename: codex-reset-com-juice-api-openapi.yml
  format: yaml
  label: Codex Reset Juice API
  slug: codex-reset-com-juice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-juice-api-openapi.yml
- filename: codex-reset-com-push-api-openapi.yml
  format: yaml
  label: Codex Reset Push API
  slug: codex-reset-com-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-push-api-openapi.yml
- filename: codex-reset-com-reset-poll-api-openapi.yml
  format: yaml
  label: Codex Reset Reset Poll API
  slug: codex-reset-com-reset-poll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-reset-poll-api-openapi.yml
- filename: codex-reset-com-status-api-openapi.yml
  format: yaml
  label: Codex Reset Status API
  slug: codex-reset-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-status-api-openapi.yml
- filename: codex-reset-com-status-history-api-openapi.yml
  format: yaml
  label: Codex Reset Status History API
  slug: codex-reset-com-status-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-status-history-api-openapi.yml
- filename: codex-reset-com-timeline-api-openapi.yml
  format: yaml
  label: Codex Reset Timeline API
  slug: codex-reset-com-timeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-timeline-api-openapi.yml
- filename: codex-reset-com-usage-reference-api-openapi.yml
  format: yaml
  label: Codex Reset Usage Reference API
  slug: codex-reset-com-usage-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codex-reset-com/openapi/codex-reset-com-usage-reference-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: device
    text: Reset times and notification preferences are saved under the codexreset.v1 localStorage key.
  - category: identifying
    text: your generated pilgrim name — is saved under codexreset.v1:pray
  - category: device
    text: the subscription endpoint URL it issues, the time you subscribed, your page language, and whether the active Service Worker can safely render the full alert scope
  - category: contact
    text: An address is HMAC-hashed for private lookup and encrypted with AES-GCM only while the request is pending or active
  - category: location
    text: a coarse location (country and, when available, city from Cloudflare's edge metadata) on the public vigil wall
  deletion:
    route: open an issue via the contact line in the footer
    text: 'Questions or removal requests: open an issue via the contact line in the footer.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: aggregate site analytics
    text: It loads Cloudflare Web Analytics and Google Analytics 4 to understand aggregate site use.
  - purpose: enforce one prayer per person per reset cycle
    text: The /api/pray endpoint accepts one prayer per person per reset cycle.
  - purpose: reset calibration
    text: These observations are shadow data only and do not confirm or change a reset, forecast, alert, or public counter.
  - purpose: serve and protect the site
    text: Cloudflare processes standard request metadata (IP, user agent) to serve and protect the site.
  retention:
  - period: up to 45 days
    scope: salted hash of request IP
    text: the Worker stores a salted one-way hash of the request IP for up to 45 days
  - period: 14 days
    scope: stored calibration sample
    text: The stored sample contains only that 15-minute bucket and coarse range and expires after 14 days.
  rights:
  - right: removal request
    text: 'Questions or removal requests: open an issue via the contact line in the footer.'
  - right: block or clear analytics cookies
    text: You can block or clear analytics cookies through your browser.
  role:
    text: null
    value: unstated
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
name: Codex Reset
provenance_date: '2026-11-09'
provider_name: Codex Reset
provider_slug: codex-reset-com
slug: codex-reset-com-privacy-policy
source_date: '2026-11-09'
source_filename: codex-reset-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codex-reset.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Codex Reset\naid: codex-reset-com\nurl: https://codex-reset.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Reset times and notification preferences are saved under the codexreset.v1 localStorage key.\n- category: identifying\n  text: your generated pilgrim name — is saved under codexreset.v1:pray\n- category: device\n  text: the subscription endpoint URL it issues, the time you subscribed, your page language, and whether the active\n    Service Worker can safely render the full alert scope\n- category: contact\n  text: An address\
  \ is HMAC-hashed for private lookup and encrypted with AES-GCM only while the request is pending\n    or active\n- category: location\n  text: a coarse location (country and, when available, city from Cloudflare's edge metadata) on the public vigil\n    wall\npurposes:\n- purpose: aggregate site analytics\n  text: It loads Cloudflare Web Analytics and Google Analytics 4 to understand aggregate site use.\n- purpose: enforce one prayer per person per reset cycle\n  text: The /api/pray endpoint accepts one prayer per person per reset cycle.\n- purpose: reset calibration\n  text: These observations are shadow data only and do not confirm or change a reset, forecast, alert, or public\n    counter.\n- purpose: serve and protect the site\n  text: Cloudflare processes standard request metadata (IP, user agent) to serve and protect the site.\nretention:\n- scope: salted hash of request IP\n  period: up to 45 days\n  text: the Worker stores a salted one-way hash of the request IP for up to 45 days\n\
  - scope: stored calibration sample\n  period: 14 days\n  text: The stored sample contains only that 15-minute bucket and coarse range and expires after 14 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: open an issue via the contact line in the footer\n  text: 'Questions or removal requests: open an issue via the contact line in the footer.'\nrights:\n- right: removal request\n  text: 'Questions or removal requests: open an issue via the contact line in the footer.'\n- right: block or clear analytics cookies\n  text: You can block or clear analytics cookies through your browser.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/codex-reset-com/privacy/codex-reset-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from Codex Reset's own page on 2026-11-09.
synthetic: false
tags:
- Company
- OpenAI Codex
- Usage Limits
- Forecasting
- Alerts
- MCP
- Open Data
- Developer Tools
---
