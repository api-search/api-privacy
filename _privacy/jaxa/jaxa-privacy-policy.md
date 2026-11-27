---
api_specs:
- filename: jaxa-csw-api-openapi.yml
  format: yaml
  label: JAXA CSW API
  slug: jaxa-csw-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jaxa/openapi/jaxa-csw-api-openapi.yml
- filename: jaxa-wcs-api-openapi.yml
  format: yaml
  label: JAXA WCS API
  slug: jaxa-wcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jaxa/openapi/jaxa-wcs-api-openapi.yml
- filename: jaxa-wms-api-openapi.yml
  format: yaml
  label: JAXA WMS API
  slug: jaxa-wms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jaxa/openapi/jaxa-wms-api-openapi.yml
claim_count: 6
description: ''
doc:
  data_categories:
  - category: contact
    text: name, address, name of company or school, position, e-mail address, telephone number, fax number
  - category: professional
    text: personal history in case of employment application
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: mail service, publications, employment, questions
    text: when the Users register themselves for mail service, request publications or other materials, apply for employment, or ask questions
  - purpose: statistical and analytical
    text: JAXA uses the recorded access log through the Website only for statistical and analytical purposes for finding access trends and number of access or for troubleshooting when a problem arises in the JAXA server
  role:
    text: JAXA may collect and store information and data of the Users with which an individual may be identified
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: JAXA does not disclose collected information/data of the Users, especially those which an individual can be identified with to any third parties intentionally except for the following three cases.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: JAXA
provenance_date: '2026-11-09'
provider_name: JAXA
provider_slug: jaxa
slug: jaxa-privacy-policy
source_date: '2026-11-09'
source_filename: jaxa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://global.jaxa.jp/policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: JAXA\naid: jaxa\nurl: https://global.jaxa.jp/policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: JAXA may collect and store information and data of the Users with which an individual may be identified\ndata_categories:\n- category: contact\n  text: name, address, name of company or school, position, e-mail address, telephone number, fax number\n- category: professional\n  text: personal history in case of employment application\npurposes:\n- purpose: mail service, publications, employment, questions\n  text: when the Users register themselves for mail service, request publications or\
  \ other materials, apply for\n    employment, or ask questions\n- purpose: statistical and analytical\n  text: JAXA uses the recorded access log through the Website only for statistical and analytical purposes for finding\n    access trends and number of access or for troubleshooting when a problem arises in the JAXA server\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: JAXA does not disclose collected information/data of the Users, especially those which an individual can\n    be identified with to any third parties intentionally except for the following three cases.\n"
source_yaml_url: https://artifacts.apis.io/jaxa/privacy/jaxa-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- sale_or_sharing
summary_line: 6 quoted statements, read from JAXA's own page on 2026-11-09.
synthetic: false
tags:
- Space
- Satellite
- Earth Observation
- Remote Sensing
- Geospatial
- Climate
- Environment
- Precipitation
- Greenhouse Gas
- Japan
---
