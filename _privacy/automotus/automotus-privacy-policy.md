---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: License plate information is the only form of personally identifiable information (PII) we collect
  - category: behavioral
    text: de-identified traffic and curb activity data to inform smarter policies
  - category: other
    text: de-identified sample image data to train our technology
  deletion:
    route: null
    text: all images are deleted immediately once the payment or citation is resolved
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: parking payment and enforcement
    text: we never capture or share this information for any purpose other than to facilitate payment and enforcement of parking regulations, or to train machine learning models
  - purpose: model training
    text: sample image data of vehicles and vehicle activity for the purpose of validating system performance and training the computer vision algorithms on our sensors
  - purpose: city traffic policy metadata
    text: We use this metadata to deliver aggregate statistics and insights to city transportation agencies
  retention:
  - period: null
    scope: traffic and curb activity metadata source video
    text: We capture de-identified traffic and curb activity data, often referred to as metadata, from video streams processed in real time and deleted instantly.
  - period: null
    scope: license plate payment and enforcement images
    text: all images are deleted immediately once the payment or citation is resolved
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No, we never sell any data to any third party.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Automotus
provenance_date: '2026-11-09'
provider_name: Automotus
provider_slug: automotus
slug: automotus-privacy-policy
source_date: '2026-11-09'
source_filename: automotus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.automotus.ai/privacypolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Automotus\naid: automotus\nurl: https://www.automotus.ai/privacypolicy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: License plate information is the only form of personally identifiable information (PII) we collect\n- category: behavioral\n  text: de-identified traffic and curb activity data to inform smarter policies\n- category: other\n  text: de-identified sample image data to train our technology\npurposes:\n- purpose: parking payment and enforcement\n  text: we never capture or share this information for any purpose other than to\
  \ facilitate payment and enforcement\n    of parking regulations, or to train machine learning models\n- purpose: model training\n  text: sample image data of vehicles and vehicle activity for the purpose of validating system performance and\n    training the computer vision algorithms on our sensors\n- purpose: city traffic policy metadata\n  text: We use this metadata to deliver aggregate statistics and insights to city transportation agencies\nretention:\n- scope: traffic and curb activity metadata source video\n  period: null\n  text: We capture de-identified traffic and curb activity data, often referred to as metadata, from video streams\n    processed in real time and deleted instantly.\n- scope: license plate payment and enforcement images\n  period: null\n  text: all images are deleted immediately once the payment or citation is resolved\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ null\n  text: all images are deleted immediately once the payment or citation is resolved\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No, we never sell any data to any third party.\n"
source_yaml_url: https://artifacts.apis.io/automotus/privacy/automotus-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from Automotus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Smart Cities
- Urban Mobility
- Curb Management
- Computer Vision
- Transportation
- Parking
- Enforcement
---
