---
api_specs:
- filename: counter-dev-account-api-openapi.yml
  format: yaml
  label: Counter Account API
  slug: counter-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counter-dev/openapi/counter-dev-account-api-openapi.yml
- filename: counter-dev-stats-api-openapi.yml
  format: yaml
  label: Counter Stats API
  slug: counter-dev-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counter-dev/openapi/counter-dev-stats-api-openapi.yml
- filename: counter-dev-tracking-api-openapi.yml
  format: yaml
  label: Counter Tracking API
  slug: counter-dev-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counter-dev/openapi/counter-dev-tracking-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your username
  - category: identifying
    text: An encrypted password
  - category: device
    text: Your browser's time zone, a preference that can be changed in the account settings.
  - category: device
    text: 'The users browser (As in: Firefox , Chrome , Microsoft Edge , ...)'
  - category: device
    text: Information on the users screen size
  - category: location
    text: A country mapped to the users IP address.
  - category: behavioral
    text: Pages visited
  - category: behavioral
    text: From which other website a visit originated.
  deletion:
    route: account settings
    text: If you do not need your data anymore, we recommend permanently deleting it in the account settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Keeping signed in
    text: 'Counter uses cookies for the following purpose: Keeping you signed in.'
  residency:
  - region: Frankfurt, Germany
    text: We use server resources and services hosted in Frankfurt, Germany.
  retention:
  - period: null
    scope: hourly, daily, weekly and monthly statistics
    text: Counter deletes hourly, daily, weekly and monthly statistics after a certain time period.
  - period: one year
    scope: inactive accounts
    text: We may delete your data automatically if you stop using the service for longer than one year.
  rights:
  - right: access
    text: The right to access - You have the right to request Counter for copies of your personal data.
  - right: rectification
    text: The right to rectification - You have the right to request that Counter correct any information you believe is inaccurate.
  - right: erasure
    text: The right to erasure - You have the right to request that Counter erase your personal data, under certain conditions.
  - right: restrict processing
    text: The right to restrict processing - You have the right to request that Counter restrict the processing of your personal data, under certain conditions.
  - right: object to processing
    text: The right to object to Counter's processing of your personal data, under certain conditions.
  - right: data portability
    text: The right to data portability - You have the right to request that Counter transfer the data that we have collected to another organization, or directly to you, under certain conditions.
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
name: Counter
provenance_date: '2026-11-09'
provider_name: Counter
provider_slug: counter-dev
slug: counter-dev-privacy-policy
source_date: '2026-11-09'
source_filename: counter-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://counter.dev/pages/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Counter\naid: counter-dev\nurl: https://counter.dev/pages/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your username\n- category: identifying\n  text: An encrypted password\n- category: device\n  text: Your browser's time zone, a preference that can be changed in the account settings.\n- category: device\n  text: 'The users browser (As in: Firefox , Chrome , Microsoft Edge , ...)'\n- category: device\n  text: Information on the users screen size\n- category: location\n  text: A country mapped to the users IP address.\n-\
  \ category: behavioral\n  text: Pages visited\n- category: behavioral\n  text: From which other website a visit originated.\npurposes:\n- purpose: Keeping signed in\n  text: 'Counter uses cookies for the following purpose: Keeping you signed in.'\nretention:\n- scope: hourly, daily, weekly and monthly statistics\n  period: null\n  text: Counter deletes hourly, daily, weekly and monthly statistics after a certain time period.\n- scope: inactive accounts\n  period: one year\n  text: We may delete your data automatically if you stop using the service for longer than one year.\nresidency:\n- region: Frankfurt, Germany\n  text: We use server resources and services hosted in Frankfurt, Germany.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings\n  text: If you do not need your data anymore, we recommend permanently deleting it in the account settings.\nrights:\n- right: access\n  text: The right\
  \ to access - You have the right to request Counter for copies of your personal data.\n- right: rectification\n  text: The right to rectification - You have the right to request that Counter correct any information you believe\n    is inaccurate.\n- right: erasure\n  text: The right to erasure - You have the right to request that Counter erase your personal data, under certain\n    conditions.\n- right: restrict processing\n  text: The right to restrict processing - You have the right to request that Counter restrict the processing of\n    your personal data, under certain conditions.\n- right: object to processing\n  text: The right to object to Counter's processing of your personal data, under certain conditions.\n- right: data portability\n  text: The right to data portability - You have the right to request that Counter transfer the data that we have\n    collected to another organization, or directly to you, under certain conditions.\nsale_or_sharing:\n  stance: unstated\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/counter-dev/privacy/counter-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 19 quoted statements, read from Counter's own page on 2026-11-09.
synthetic: false
tags:
- Web Analytics
- Privacy
- Open Source
- Tracking
- Self-Hosted
---
