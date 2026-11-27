---
api_specs:
- filename: rybbit-analytics-api-openapi.yml
  format: yaml
  label: Rybbit Analytics API
  slug: rybbit-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-analytics-api-openapi.yml
- filename: rybbit-event-tracking-api-openapi.yml
  format: yaml
  label: Rybbit Event Tracking API
  slug: rybbit-event-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-event-tracking-api-openapi.yml
- filename: rybbit-sessions-api-openapi.yml
  format: yaml
  label: Rybbit Sessions API
  slug: rybbit-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rybbit/openapi/rybbit-sessions-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: behavioral
    text: 'Page data: URLs visited, page titles, referrers, and query parameters'
  - category: device
    text: 'Device information: Browser type and version, operating system, screen resolution, device type'
  - category: location
    text: 'Location data: Country and region (derived from IP address, which is not stored)'
  - category: behavioral
    text: 'Marketing data: UTM parameters (source, medium, campaign)'
  - category: other
    text: 'Custom events: If configured by the website owner'
  deletion:
    route: Automatic deletion after retention period
    text: Once the applicable retention period is reached, data is automatically deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Visitor statistics
    text: Provide website owners with anonymous, aggregated statistics about their visitors
  - purpose: Marketing campaign performance
    text: Track marketing campaign performance
  retention:
  - period: 3 years
    scope: Standard cloud plans
    text: Standard plans retain analytics data for 3 years
  - period: 5 years
    scope: Pro cloud plans
    text: Pro plans retain it for 5 years
  - period: indefinitely
    scope: Enterprise cloud plans
    text: Enterprise plans retain data indefinitely
  - period: null
    scope: Self-hosted instances
    text: data retention is configurable by the administrator
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't share or sell your analytics data
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rybbit
provenance_date: '2026-11-10'
provider_name: Rybbit
provider_slug: rybbit
slug: rybbit-privacy-policy
source_date: '2026-11-10'
source_filename: rybbit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rybbit.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rybbit\naid: rybbit\nurl: https://rybbit.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: 'Page data: URLs visited, page titles, referrers, and query parameters'\n- category: device\n  text: 'Device information: Browser type and version, operating system, screen resolution, device type'\n- category: location\n  text: 'Location data: Country and region (derived from IP address, which is not stored)'\n- category: behavioral\n  text: 'Marketing data: UTM parameters (source, medium, campaign)'\n- category: other\n  text: 'Custom events:\
  \ If configured by the website owner'\npurposes:\n- purpose: Visitor statistics\n  text: Provide website owners with anonymous, aggregated statistics about their visitors\n- purpose: Marketing campaign performance\n  text: Track marketing campaign performance\nretention:\n- scope: Standard cloud plans\n  period: 3 years\n  text: Standard plans retain analytics data for 3 years\n- scope: Pro cloud plans\n  period: 5 years\n  text: Pro plans retain it for 5 years\n- scope: Enterprise cloud plans\n  period: indefinitely\n  text: Enterprise plans retain data indefinitely\n- scope: Self-hosted instances\n  period: null\n  text: data retention is configurable by the administrator\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Automatic deletion after retention period\n  text: Once the applicable retention period is reached, data is automatically deleted.\nrights: []\nsale_or_sharing:\n  stance:\
  \ prohibited\n  text: We don't share or sell your analytics data\n"
source_yaml_url: https://artifacts.apis.io/rybbit/privacy/rybbit-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 13 quoted statements, read from Rybbit's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Product Analytics
- Privacy
- Open Source
- Cookieless
---
