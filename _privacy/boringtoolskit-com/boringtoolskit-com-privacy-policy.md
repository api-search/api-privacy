---
api_specs:
- filename: boringtoolskit-com-privacy-region-api-openapi.yml
  format: yaml
  label: BoringToolsKit Privacy region API
  slug: boringtoolskit-com-privacy-region-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boringtoolskit-com/openapi/boringtoolskit-com-privacy-region-api-openapi.yml
- filename: boringtoolskit-com-usage-events-api-openapi.yml
  format: yaml
  label: BoringToolsKit Usage events API
  slug: boringtoolskit-com-usage-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/boringtoolskit-com/openapi/boringtoolskit-com-usage-events-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: device
    text: Your theme preference may be stored locally in your browser.
  - category: behavioral
    text: It contains only an allowed event name, canonical pathname, controlled source category, and a coarse local new-or-returning flag.
  deletion:
    route: Browser site-data controls or Clear all BoringToolsKit browser storage button; no user database to delete from
    text: Because we do not store personal calculation data, there is no user database to delete from.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Local preferences and navigation
    text: 'Purpose: theme, scenery, and interface choices.'
  - purpose: Aggregate tool completion measurement
    text: measure aggregate tool completion and next actions
  - purpose: Advertising
    text: third-party vendors may use cookies or similar technologies to serve and measure ads.
  retention:
  - period: until changed or cleared
    scope: Essential preferences
    text: 'Retention: until changed or cleared.'
  - period: 30 days
    scope: Raw outcome events
    text: each raw event expires after 30 days.
  - period: 395 days
    scope: Daily aggregate counts
    text: Daily aggregate counts retain only day, event, canonical path, count, and bounded timestamps for 395 days
  rights:
  - right: Opt out of personalized advertising
    text: You may opt out of personalized advertising by visiting Google Ads Settings .
  - right: Disable aggregate outcome measurement
    text: Disable aggregate outcome measurement on this device.
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
name: BoringToolsKit
provenance_date: '2026-11-09'
provider_name: BoringToolsKit
provider_slug: boringtoolskit-com
slug: boringtoolskit-com-privacy-policy
source_date: '2026-11-09'
source_filename: boringtoolskit-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://boringtoolskit.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BoringToolsKit\naid: boringtoolskit-com\nurl: https://boringtoolskit.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Your theme preference may be stored locally in your browser.\n- category: behavioral\n  text: It contains only an allowed event name, canonical pathname, controlled source category, and a coarse local\n    new-or-returning flag.\npurposes:\n- purpose: Local preferences and navigation\n  text: 'Purpose: theme, scenery, and interface choices.'\n- purpose: Aggregate tool completion measurement\n  text: measure aggregate\
  \ tool completion and next actions\n- purpose: Advertising\n  text: third-party vendors may use cookies or similar technologies to serve and measure ads.\nretention:\n- scope: Essential preferences\n  period: until changed or cleared\n  text: 'Retention: until changed or cleared.'\n- scope: Raw outcome events\n  period: 30 days\n  text: each raw event expires after 30 days.\n- scope: Daily aggregate counts\n  period: 395 days\n  text: Daily aggregate counts retain only day, event, canonical path, count, and bounded timestamps for 395 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Browser site-data controls or Clear all BoringToolsKit browser storage button; no user database to delete\n    from\n  text: Because we do not store personal calculation data, there is no user database to delete from.\nrights:\n- right: Opt out of personalized advertising\n  text: You may opt out of personalized\
  \ advertising by visiting Google Ads Settings .\n- right: Disable aggregate outcome measurement\n  text: Disable aggregate outcome measurement on this device.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boringtoolskit-com/privacy/boringtoolskit-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from BoringToolsKit's own page on 2026-11-09.
synthetic: false
tags:
- Tools
- Finance
- Health
- Education
- Construction
- Free
---
