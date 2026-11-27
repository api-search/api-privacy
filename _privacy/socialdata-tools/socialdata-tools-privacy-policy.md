---
api_specs:
- filename: socialdata-tools-data-api-api-openapi.yml
  format: yaml
  label: socialdata-tools Data API
  slug: socialdata-tools-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-data-api-api-openapi.yml
- filename: socialdata-tools-monitoring-api-api-openapi.yml
  format: yaml
  label: socialdata-tools Monitoring API
  slug: socialdata-tools-monitoring-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-monitoring-api-api-openapi.yml
- filename: socialdata-tools-social-actions-api-api-openapi.yml
  format: yaml
  label: socialdata-tools Social Actions API
  slug: socialdata-tools-social-actions-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-social-actions-api-api-openapi.yml
- filename: socialdata-tools-socialdata-account-management-api-openapi.yml
  format: yaml
  label: socialdata-tools SocialData Account Management API
  slug: socialdata-tools-socialdata-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-socialdata-account-management-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: This includes your name, e-mail address, payment information and more.
  - category: behavioral
    text: We also collect data based on your usage of our platform with our optional cookies.
  deletion:
    route: Explicit request to delete information
    text: when you explicitly request us to delete it
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide access to platform features
    text: Provide you with access to all of SocialData.Tools features
  - purpose: Process payments
    text: Process your payments
  - purpose: Improve services via usage analysis
    text: We use anonymous usage data to analyze the use of our platform by our users so we can improve our services.
  retention:
  - period: 14 days
    scope: Personal identifiable information after deletion request
    text: Once your request has been submitted and confirmed, your information will be deleted within 14 days.
  rights:
  - right: Access
    text: 'Right of access: You are entitled to receiving a copy of all personally identifiable information related to you and your person that we have processed'
  - right: Rectification
    text: 'Right to rectification: You are entitled to have any personally identifiable information you have provided to us corrected or adjusted in the case the information is not correct'
  - right: Erasure
    text: 'Right to erasure: You are entitled to having some or all personally identifiable information we have gathered be erased at your request'
  - right: Restriction of processing
    text: 'Right to restriction of processing: You are entitled to us stopping the processing of relevant personally identifiable information'
  - right: Portability
    text: 'Right to data portability: You have the right to transfer personally identifiable information we have processed to another party'
  - right: Object to direct marketing
    text: you have the right to object to us processing your personally identifiable information for direct marketing purposes.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: This data will always be made fully anonymous before it’s shared.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: socialdata-tools
provenance_date: '2026-11-10'
provider_name: socialdata-tools
provider_slug: socialdata-tools
slug: socialdata-tools-privacy-policy
source_date: '2026-11-10'
source_filename: socialdata-tools-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://socialdata.tools/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: socialdata-tools\naid: socialdata-tools\nurl: https://socialdata.tools/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: This includes your name, e-mail address, payment information and more.\n- category: behavioral\n  text: We also collect data based on your usage of our platform with our optional cookies.\npurposes:\n- purpose: Provide access to platform features\n  text: Provide you with access to all of SocialData.Tools features\n- purpose: Process payments\n  text: Process your payments\n- purpose: Improve services\
  \ via usage analysis\n  text: We use anonymous usage data to analyze the use of our platform by our users so we can improve our services.\nretention:\n- scope: Personal identifiable information after deletion request\n  period: 14 days\n  text: Once your request has been submitted and confirmed, your information will be deleted within 14 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Explicit request to delete information\n  text: when you explicitly request us to delete it\nrights:\n- right: Access\n  text: 'Right of access: You are entitled to receiving a copy of all personally identifiable information related\n    to you and your person that we have processed'\n- right: Rectification\n  text: 'Right to rectification: You are entitled to have any personally identifiable information you have provided\n    to us corrected or adjusted in the case the information is not correct'\n- right:\
  \ Erasure\n  text: 'Right to erasure: You are entitled to having some or all personally identifiable information we have gathered\n    be erased at your request'\n- right: Restriction of processing\n  text: 'Right to restriction of processing: You are entitled to us stopping the processing of relevant personally\n    identifiable information'\n- right: Portability\n  text: 'Right to data portability: You have the right to transfer personally identifiable information we have processed\n    to another party'\n- right: Object to direct marketing\n  text: you have the right to object to us processing your personally identifiable information for direct marketing\n    purposes.\nsale_or_sharing:\n  stance: conditional\n  text: This data will always be made fully anonymous before it’s shared.\n"
source_yaml_url: https://artifacts.apis.io/socialdata-tools/privacy/socialdata-tools-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from socialdata-tools's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Data
- Public APIs
---
