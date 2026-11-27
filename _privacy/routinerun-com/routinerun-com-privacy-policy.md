---
api_specs:
- filename: routinerun-com-events-api-openapi.yml
  format: yaml
  label: routinerun-com Events API
  slug: routinerun-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-events-api-openapi.yml
- filename: routinerun-com-runs-api-openapi.yml
  format: yaml
  label: routinerun-com Runs API
  slug: routinerun-com-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-runs-api-openapi.yml
- filename: routinerun-com-commands-api-openapi.yml
  format: yaml
  label: routinerun-com Commands API
  slug: routinerun-com-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-commands-api-openapi.yml
- filename: routinerun-com-history-api-openapi.yml
  format: yaml
  label: routinerun-com History API
  slug: routinerun-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-history-api-openapi.yml
- filename: routinerun-com-pagerduty-api-openapi.yml
  format: yaml
  label: routinerun-com Pagerduty API
  slug: routinerun-com-pagerduty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-pagerduty-api-openapi.yml
- filename: routinerun-com-routines-api-openapi.yml
  format: yaml
  label: routinerun-com Routines API
  slug: routinerun-com-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routinerun-com/openapi/routinerun-com-routines-api-openapi.yml
claim_count: 7
description: ''
doc:
  data_categories:
  - category: device
    text: a token Apple gives us for sending to your phone
  - category: communication
    text: What we can see is a routine you chose to publish and the addresses you made for connections.
  deletion:
    route: email support@routinerun.com
    text: We will delete a published routine if you send us its code.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: relay connection delivery
    text: What the other system sends is passed to your phone and not kept
  retention:
  - period: until you press Unpublish
    scope: published routine
    text: and stays there until you press Unpublish.
  - period: an hour later for a run and a day for anything else
    scope: relay waiting item
    text: if it never does, it is deleted when the request expires, an hour later for a run and a day for anything else.
  - period: a day at most
    scope: connection messages on relay
    text: we hold it only until Apple has accepted it for delivery, and Apple holds it until your phone is reachable, for a day at most.
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
name: routinerun-com
provenance_date: '2026-11-10'
provider_name: routinerun-com
provider_slug: routinerun-com
slug: routinerun-com-privacy-policy
source_date: '2026-11-10'
source_filename: routinerun-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://routinerun.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: routinerun-com\naid: routinerun-com\nurl: https://routinerun.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: a token Apple gives us for sending to your phone\n- category: communication\n  text: What we can see is a routine you chose to publish and the addresses you made for connections.\npurposes:\n- purpose: relay connection delivery\n  text: What the other system sends is passed to your phone and not kept\nretention:\n- scope: published routine\n  period: until you press Unpublish\n  text: and stays there until you press Unpublish.\n\
  - scope: relay waiting item\n  period: an hour later for a run and a day for anything else\n  text: if it never does, it is deleted when the request expires, an hour later for a run and a day for anything\n    else.\n- scope: connection messages on relay\n  period: a day at most\n  text: we hold it only until Apple has accepted it for delivery, and Apple holds it until your phone is reachable,\n    for a day at most.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@routinerun.com\n  text: We will delete a published routine if you send us its code.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/routinerun-com/privacy/routinerun-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 7 quoted statements, read from routinerun-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Automation
- Productivity
- Task Management
- No-Code
---
