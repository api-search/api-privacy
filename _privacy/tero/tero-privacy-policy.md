---
api_specs:
- filename: tero-openapi-generated.yml
  format: yaml
  label: Tero API
  slug: tero-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tero/openapi/_ae-authored/tero-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect personal information such as name, email address, and company details provided during registration or communication.
  - category: device
    text: We may also collect limited usage data to monitor and secure the platform, including IP address, browser type, login timestamps, and general metadata about how users interact with the application.
  - category: financial
    text: If applicable, we may collect billing and subscription information for payment and invoicing.
  deletion:
    route: request deletion of stored data
    text: You may request deletion of any stored data associated with your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and improve the Service
    text: We use the collected data to operate and improve the Service.
  - purpose: build and maintain pattern index
    text: Build and maintain the pattern index
  - purpose: support and important updates
    text: Provide support and communicate important updates
  retention:
  - period: null
    scope: full telemetry data
    text: We do not store or back up your full telemetry data.
  - period: as long as necessary
    scope: stored patterns, metadata, samples
    text: Stored patterns, metadata, and samples are retained only as long as necessary to deliver the Service.
  - period: 30 days
    scope: retained data after account termination
    text: We delete all retained data within 30 days of account termination unless otherwise required by law.
  rights:
  - right: access and correction
    text: you may request access to or correction of your data
  - right: deletion
    text: request deletion of your stored data
  - right: objection or restriction
    text: object to or restrict processing
  - right: portability
    text: request data portability
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not sell or share your data with third parties for marketing purposes.
  subprocessors:
    text: We may share limited data with subprocessors under strict confidentiality.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tero
provenance_date: '2026-11-10'
provider_name: Tero
provider_slug: tero
slug: tero-privacy-policy
source_date: '2026-11-10'
source_filename: tero-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://usetero.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tero\naid: tero\nurl: https://usetero.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect personal information such as name, email address, and company details provided during registration\n    or communication.\n- category: device\n  text: We may also collect limited usage data to monitor and secure the platform, including IP address, browser\n    type, login timestamps, and general metadata about how users interact with the application.\n- category: financial\n  text: If applicable, we may collect billing and subscription\
  \ information for payment and invoicing.\npurposes:\n- purpose: operate and improve the Service\n  text: We use the collected data to operate and improve the Service.\n- purpose: build and maintain pattern index\n  text: Build and maintain the pattern index\n- purpose: support and important updates\n  text: Provide support and communicate important updates\nretention:\n- scope: full telemetry data\n  period: null\n  text: We do not store or back up your full telemetry data.\n- scope: stored patterns, metadata, samples\n  period: as long as necessary\n  text: Stored patterns, metadata, and samples are retained only as long as necessary to deliver the Service.\n- scope: retained data after account termination\n  period: 30 days\n  text: We delete all retained data within 30 days of account termination unless otherwise required by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We may share limited data with subprocessors under strict confidentiality.\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: request deletion of stored data\n  text: You may request deletion of any stored data associated with your account.\nrights:\n- right: access and correction\n  text: you may request access to or correction of your data\n- right: deletion\n  text: request deletion of your stored data\n- right: objection or restriction\n  text: object to or restrict processing\n- right: portability\n  text: request data portability\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell or share your data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/tero/privacy/tero-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 15 quoted statements, read from Tero's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Observability
- Telemetry
- Cost-Reduction
- Compliance
- Reliability
---
