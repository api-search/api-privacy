---
api_specs:
- filename: changethisfile-com-account-api-openapi.yml
  format: yaml
  label: ChangeThisFile Account API
  slug: changethisfile-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/changethisfile-com/openapi/changethisfile-com-account-api-openapi.yml
- filename: changethisfile-com-billing-api-openapi.yml
  format: yaml
  label: ChangeThisFile Billing API
  slug: changethisfile-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/changethisfile-com/openapi/changethisfile-com-billing-api-openapi.yml
- filename: changethisfile-com-conversions-api-openapi.yml
  format: yaml
  label: ChangeThisFile Conversions API
  slug: changethisfile-com-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/changethisfile-com/openapi/changethisfile-com-conversions-api-openapi.yml
- filename: changethisfile-com-jobs-api-openapi.yml
  format: yaml
  label: ChangeThisFile Jobs API
  slug: changethisfile-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/changethisfile-com/openapi/changethisfile-com-jobs-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: behavioral
    text: We collect basic analytics (page views, conversion counts) via PostHog.
  - category: other
    text: We do not collect or store the contents of your files.
  deletion:
    route: email privacy@changethisfile.com
    text: You can request deletion of your account and associated data by emailing privacy@changethisfile.com .
  dpa:
    available: null
    text: A full subprocessor list and processing summary is on our Data Processing Addendum page .
    url: null
  purposes:
  - purpose: usage analytics
    text: Analytics cookies — understanding how users interact with our service (PostHog)
  - purpose: session management
    text: Essential cookies — session management, conversion preferences
  residency:
  - region: EU (Germany)
    text: Hetzner — conversion server hosting (Germany, EU)
  retention:
  - period: immediately after the conversion completes
    scope: conversion files
    text: 'Conversion files: deleted immediately after the conversion completes'
  - period: 24 hours
    scope: async API jobs
    text: 'async API jobs: deleted automatically within 24 hours'
  - period: 12 months
    scope: analytics data
    text: 'Analytics data: retained for 12 months.'
  - period: while account is active
    scope: account data (paid plans)
    text: 'Account data (paid plans): retained while account is active.'
  rights:
  - right: deletion
    text: You can request deletion of your account and associated data by emailing privacy@changethisfile.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A full subprocessor list and processing summary is on our Data Processing Addendum page .
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ChangeThisFile
provenance_date: '2026-11-09'
provider_name: ChangeThisFile
provider_slug: changethisfile-com
slug: changethisfile-com-privacy-policy
source_date: '2026-11-09'
source_filename: changethisfile-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://changethisfile.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChangeThisFile\naid: changethisfile-com\nurl: https://changethisfile.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: We collect basic analytics (page views, conversion counts) via PostHog.\n- category: other\n  text: We do not collect or store the contents of your files.\npurposes:\n- purpose: usage analytics\n  text: Analytics cookies — understanding how users interact with our service (PostHog)\n- purpose: session management\n  text: Essential cookies — session management, conversion preferences\nretention:\n- scope: conversion\
  \ files\n  period: immediately after the conversion completes\n  text: 'Conversion files: deleted immediately after the conversion completes'\n- scope: async API jobs\n  period: 24 hours\n  text: 'async API jobs: deleted automatically within 24 hours'\n- scope: analytics data\n  period: 12 months\n  text: 'Analytics data: retained for 12 months.'\n- scope: account data (paid plans)\n  period: while account is active\n  text: 'Account data (paid plans): retained while account is active.'\nresidency:\n- region: EU (Germany)\n  text: Hetzner — conversion server hosting (Germany, EU)\ntransfers: []\nsubprocessors:\n  url: null\n  text: A full subprocessor list and processing summary is on our Data Processing Addendum page .\ndpa:\n  available: null\n  url: null\n  text: A full subprocessor list and processing summary is on our Data Processing Addendum page .\ndeletion:\n  route: email privacy@changethisfile.com\n  text: You can request deletion of your account and associated data by emailing\
  \ privacy@changethisfile.com .\nrights:\n- right: deletion\n  text: You can request deletion of your account and associated data by emailing privacy@changethisfile.com .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/changethisfile-com/privacy/changethisfile-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 13 quoted statements, read from ChangeThisFile's own page on 2026-11-09.
synthetic: false
tags:
- File Conversion
- Free
- Privacy
- Software-as-a-Service
---
