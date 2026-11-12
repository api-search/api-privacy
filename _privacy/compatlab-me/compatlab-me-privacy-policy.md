---
api_specs:
- filename: compatlab-me-packages-api-openapi.yml
  format: yaml
  label: CompatLab Packages API
  slug: compatlab-me-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-packages-api-openapi.yml
- filename: compatlab-me-reports-api-openapi.yml
  format: yaml
  label: CompatLab Reports API
  slug: compatlab-me-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-reports-api-openapi.yml
- filename: compatlab-me-scans-api-openapi.yml
  format: yaml
  label: CompatLab Scans API
  slug: compatlab-me-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-scans-api-openapi.yml
- filename: compatlab-me-search-api-openapi.yml
  format: yaml
  label: CompatLab Search API
  slug: compatlab-me-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compatlab-me/openapi/compatlab-me-search-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: device
    text: The ingress uses your network address to limit abuse.
  - category: behavioral
    text: For successful package-version lookups, we retain the public package name, exact version, UTC day and whether current, earlier or no eligible evidence was available.
  deletion:
    route: repository issue
    text: For an incorrect report or public content removal request, open a repository issue with the report URL and reason.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse limiting
    text: The ingress uses your network address to limit abuse.
  retention:
  - period: seven days
    scope: keyed network identifier
    text: Admission stores a keyed identifier that rotates daily, groups IPv6 addresses by /64, and is removed after seven days.
  - period: 14 days
    scope: service and audit logs
    text: Service logs are retained for 14 days; operator and security audit events for 180 days.
  - period: seven days
    scope: encrypted database backups
    text: Encrypted database backups are retained for seven days.
  - period: 30 UTC days
    scope: package/version lookup counts
    text: Collection is best effort, capped at 1,000 package/version/availability rows per day, and expires after 30 UTC days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The control service may send fixed operational error names to an operator-configured Sentry endpoint.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CompatLab
provenance_date: '2026-11-09'
provider_name: CompatLab
provider_slug: compatlab-me
slug: compatlab-me-privacy-policy
source_date: '2026-11-09'
source_filename: compatlab-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://compatlab.me/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CompatLab\naid: compatlab-me\nurl: https://compatlab.me/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: The ingress uses your network address to limit abuse.\n- category: behavioral\n  text: For successful package-version lookups, we retain the public package name, exact version, UTC day and whether\n    current, earlier or no eligible evidence was available.\npurposes:\n- purpose: abuse limiting\n  text: The ingress uses your network address to limit abuse.\nretention:\n- scope: keyed network identifier\n  period: seven days\n  text:\
  \ Admission stores a keyed identifier that rotates daily, groups IPv6 addresses by /64, and is removed after\n    seven days.\n- scope: service and audit logs\n  period: 14 days\n  text: Service logs are retained for 14 days; operator and security audit events for 180 days.\n- scope: encrypted database backups\n  period: seven days\n  text: Encrypted database backups are retained for seven days.\n- scope: package/version lookup counts\n  period: 30 UTC days\n  text: Collection is best effort, capped at 1,000 package/version/availability rows per day, and expires after\n    30 UTC days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The control service may send fixed operational error names to an operator-configured Sentry endpoint.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: repository issue\n  text: For an incorrect report or public content removal request, open a repository issue with the report URL and\n    reason.\nrights: []\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/compatlab-me/privacy/compatlab-me-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
summary_line: 9 quoted statements, read from CompatLab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- npm
- JavaScript
- Node.js
- Bun
- Deno
- Compatibility Testing
- Developer Tools
- Open Source
- MCP
---
