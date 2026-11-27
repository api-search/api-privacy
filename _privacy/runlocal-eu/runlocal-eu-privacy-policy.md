---
claim_count: 12
description: ''
doc:
  data_categories:
  - category: other
    text: Runlocal does not collect personal data.
  - category: behavioral
    text: Your HTTP traffic is forwarded in real time through a WebSocket connection and is never persisted
  - category: other
    text: Standard server logs (timestamps, paths, status codes) exist only in ephemeral container output
  deletion:
    route: null
    text: Since we don't collect or store personal data, there is no personal data to access, rectify, or delete.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Forward traffic
    text: HTTP requests arrive, get forwarded to your CLI via WebSocket, and the response comes back.
  - purpose: Assign subdomains
    text: a random adjective-animal pair is generated in memory and forgotten when you disconnect
  residency:
  - region: Germany
    text: Hosting netcup GmbH, Nuremberg, Germany
  - region: EEA
    text: We do not transfer data outside the EU/EEA.
  retention:
  - period: null
    scope: HTTP requests and responses
    text: HTTP requests and responses are proxied in real time and never written to disk
  - period: null
    scope: Standard server logs
    text: These are ephemeral container logs, not persisted to any database or log aggregation service.
  role:
    text: '1. Data Controller Whitenoise AS Org.nr: 821 244 722 Oslo, Norway support@runlater.eu'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 5. Sub-processors Company Purpose Location netcup GmbH Infrastructure hosting Nuremberg, Germany
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: runlocal-eu
provenance_date: '2026-11-10'
provider_name: runlocal-eu
provider_slug: runlocal-eu
slug: runlocal-eu-privacy-policy
source_date: '2026-11-10'
source_filename: runlocal-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://runlocal.eu/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: runlocal-eu\naid: runlocal-eu\nurl: https://runlocal.eu/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: '1. Data Controller Whitenoise AS Org.nr: 821 244 722 Oslo, Norway support@runlater.eu'\ndata_categories:\n- category: other\n  text: Runlocal does not collect personal data.\n- category: behavioral\n  text: Your HTTP traffic is forwarded in real time through a WebSocket connection and is never persisted\n- category: other\n  text: Standard server logs (timestamps, paths, status codes) exist only in ephemeral container output\npurposes:\n- purpose: Forward traffic\n  text: HTTP requests\
  \ arrive, get forwarded to your CLI via WebSocket, and the response comes back.\n- purpose: Assign subdomains\n  text: a random adjective-animal pair is generated in memory and forgotten when you disconnect\nretention:\n- scope: HTTP requests and responses\n  period: null\n  text: HTTP requests and responses are proxied in real time and never written to disk\n- scope: Standard server logs\n  period: null\n  text: These are ephemeral container logs, not persisted to any database or log aggregation service.\nresidency:\n- region: Germany\n  text: Hosting netcup GmbH, Nuremberg, Germany\n- region: EEA\n  text: We do not transfer data outside the EU/EEA.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 5. Sub-processors Company Purpose Location netcup GmbH Infrastructure hosting Nuremberg, Germany\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Since we don't collect or store personal data, there is no personal data to access, rectify, or delete.\n\
  rights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runlocal-eu/privacy/runlocal-eu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
summary_line: 12 quoted statements, read from runlocal-eu's own page on 2026-11-10.
synthetic: false
tags:
- Developer Tools
- Networking
- Security
- Privacy
- EU
---
