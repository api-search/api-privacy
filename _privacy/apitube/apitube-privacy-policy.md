---
api_specs:
- filename: apitube-news-api-openapi.yml
  format: yaml
  label: APITube News API
  slug: apitube-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-news-api-openapi.yml
- filename: apitube-account-api-openapi.yml
  format: yaml
  label: APITube Account API
  slug: apitube-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-account-api-openapi.yml
- filename: apitube-fact-check-api-openapi.yml
  format: yaml
  label: APITube Fact Check API
  slug: apitube-fact-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-fact-check-api-openapi.yml
- filename: apitube-reference-api-openapi.yml
  format: yaml
  label: APITube Reference API
  slug: apitube-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-reference-api-openapi.yml
- filename: apitube-suggest-api-openapi.yml
  format: yaml
  label: APITube Suggest API
  slug: apitube-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-suggest-api-openapi.yml
- filename: apitube-system-api-openapi.yml
  format: yaml
  label: APITube System API
  slug: apitube-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-system-api-openapi.yml
- filename: apitube-utilities-api-openapi.yml
  format: yaml
  label: APITube Utilities API
  slug: apitube-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apitube/openapi/apitube-utilities-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: device
    text: 'Among the types of Personal Data that this Application collects, by itself or through third parties, there are: Cookies and Usage Data.'
  - category: other
    text: System logs and maintenance For operation and maintenance purposes, this Application and any third party services may collect files that record interaction with this Application (System logs) or use for this purpose other Personal Data (such as IP Address).
  deletion:
    route: user request to Data Controller
    text: the User can always request that the Data Controller suspend or remove the data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Analytics
    text: 'The Data concerning the User is collected to allow the Owner to provide its services, as well as for the following purposes: Analytics.'
  - purpose: Legal action
    text: The User's Personal Data may be used for legal purposes by the Data Controller, in Court or in the stages leading to possible legal action arising from improper use of this Application or the related services.
  residency:
  - region: unspecified
    text: The Data is processed at the Data Controller's operating offices and in any other places where the parties involved with the processing are located.
  retention:
  - period: null
    scope: Personal Data
    text: The Data is kept for the time necessary to provide the service requested by the User, or stated by the purposes outlined in this document
  rights:
  - right: access, correction, deletion, restriction
    text: to know whether their Personal Data has been stored and can consult the Data Controller to learn about their contents and origin, to verify their accuracy or to ask for them to be supplemented, cancelled, updated or corrected
  - right: object to processing
    text: as well as to oppose their treatment for any and all legitimate reasons.
  role:
    text: The Data Controller, unless otherwise specified, is the Owner of this Application.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The updated list of these parties may be requested from the Data Controller at any time.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: APITube
provenance_date: '2026-11-09'
provider_name: APITube
provider_slug: apitube
slug: apitube-privacy-policy
source_date: '2026-11-09'
source_filename: apitube-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apitube.io/terms/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: APITube\naid: apitube\nurl: https://apitube.io/terms/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Data Controller, unless otherwise specified, is the Owner of this Application.\ndata_categories:\n- category: device\n  text: 'Among the types of Personal Data that this Application collects, by itself or through third parties, there\n    are: Cookies and Usage Data.'\n- category: other\n  text: System logs and maintenance For operation and maintenance purposes, this Application and any third party\n    services may collect files that record interaction with this Application\
  \ (System logs) or use for this purpose\n    other Personal Data (such as IP Address).\npurposes:\n- purpose: Analytics\n  text: 'The Data concerning the User is collected to allow the Owner to provide its services, as well as for the\n    following purposes: Analytics.'\n- purpose: Legal action\n  text: The User's Personal Data may be used for legal purposes by the Data Controller, in Court or in the stages\n    leading to possible legal action arising from improper use of this Application or the related services.\nretention:\n- scope: Personal Data\n  period: null\n  text: The Data is kept for the time necessary to provide the service requested by the User, or stated by the purposes\n    outlined in this document\nresidency:\n- region: unspecified\n  text: The Data is processed at the Data Controller's operating offices and in any other places where the parties\n    involved with the processing are located.\ntransfers: []\nsubprocessors:\n  url: null\n  text: The updated list of these\
  \ parties may be requested from the Data Controller at any time.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: user request to Data Controller\n  text: the User can always request that the Data Controller suspend or remove the data.\nrights:\n- right: access, correction, deletion, restriction\n  text: to know whether their Personal Data has been stored and can consult the Data Controller to learn about their\n    contents and origin, to verify their accuracy or to ask for them to be supplemented, cancelled, updated or corrected\n- right: object to processing\n  text: as well as to oppose their treatment for any and all legitimate reasons.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apitube/privacy/apitube-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 11 quoted statements, read from APITube's own page on 2026-11-09.
synthetic: false
tags:
- News
- Media Monitoring
- News API
- Fact Check
- Journalists
---
