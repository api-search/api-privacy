---
api_specs:
- filename: politecnico-di-milano-catalog-api-openapi.yml
  format: yaml
  label: Politecnico di Milano Catalog API
  slug: politecnico-di-milano-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/politecnico-di-milano/openapi/politecnico-di-milano-catalog-api-openapi.yml
- filename: politecnico-di-milano-distributions-api-openapi.yml
  format: yaml
  label: Politecnico di Milano Distributions API
  slug: politecnico-di-milano-distributions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/politecnico-di-milano/openapi/politecnico-di-milano-distributions-api-openapi.yml
- filename: politecnico-di-milano-federation-api-openapi.yml
  format: yaml
  label: Politecnico di Milano Federation API
  slug: politecnico-di-milano-federation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/politecnico-di-milano/openapi/politecnico-di-milano-federation-api-openapi.yml
- filename: politecnico-di-milano-harvesting-api-openapi.yml
  format: yaml
  label: Politecnico di Milano Harvesting API
  slug: politecnico-di-milano-harvesting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/politecnico-di-milano/openapi/politecnico-di-milano-harvesting-api-openapi.yml
claim_count: 12
description: ''
doc:
  deletion:
    route: Request to the data controller for cancellation, subject to storage obligations
    text: Cancellation is not allowed for data included in documents that must be stored by the University
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 'Legal basis: public interest'
    text: Article 6 letter e) of EU regulation 2016/679 (data processing for reasons of public interest)
  - purpose: Statistical surveys and evaluation of teaching
    text: Data processing for statistical surveys and evaluation of teaching
  - purpose: Internship activity
    text: Data processing for internship activity
  - purpose: Libraries
    text: Data processing for libraries
  retention:
  - period: the time established by current legislation or by the University regulations
    scope: General personal data
    text: The data collected will be kept for the time established by current legislation or by the University regulations.
  - period: indefinitely
    scope: University career data
    text: personal data concerning the university career will be kept indefinitely
  rights:
  - right: Access, correction, cancellation, limitation or objection
    text: To ask the data controller, pursuant to Article 16, 17, 18, 19 and 21 of Regulation (EU) 2016/679, the access to their personal data and correction or their cancellation or limitation of the data processing that concern him/her or to object to their processing.
  - right: Complaint to supervisory authority
    text: To submit a complaint to a supervisory authority.
  role:
    text: 'The Data controller of Politecnico di Milano is the General Manager upon authorization of the pro-tempore Rector – contact: dirgen@polimi.it'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The University is supported by external service providers for technical-administrative management, which could be made aware of the personal data of students, for the sole purpose of the service required and which would be previously authorized as external data processors.
    url: null
  transfers:
  - mechanism: other
    text: Personal data for research and teaching activities may be transferred abroad to other university and research institutions, or in the context of international mobility projects.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Politecnico di Milano
provenance_date: '2026-11-10'
provider_name: Politecnico di Milano
provider_slug: politecnico-di-milano
slug: politecnico-di-milano-privacy-policy
source_date: '2026-11-10'
source_filename: politecnico-di-milano-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.polimi.it/en/the-politecnico/communication/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Politecnico di Milano\naid: politecnico-di-milano\nurl: https://www.polimi.it/en/the-politecnico/communication/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The Data controller of Politecnico di Milano is the General Manager upon authorization of the pro-tempore\n    Rector – contact: dirgen@polimi.it'\ndata_categories: []\npurposes:\n- purpose: 'Legal basis: public interest'\n  text: Article 6 letter e) of EU regulation 2016/679 (data processing for reasons of public interest)\n- purpose: Statistical surveys and evaluation of teaching\n  text: Data processing for statistical surveys\
  \ and evaluation of teaching\n- purpose: Internship activity\n  text: Data processing for internship activity\n- purpose: Libraries\n  text: Data processing for libraries\nretention:\n- scope: General personal data\n  period: the time established by current legislation or by the University regulations\n  text: The data collected will be kept for the time established by current legislation or by the University regulations.\n- scope: University career data\n  period: indefinitely\n  text: personal data concerning the university career will be kept indefinitely\nresidency: []\ntransfers:\n- mechanism: other\n  text: Personal data for research and teaching activities may be transferred abroad to other university and research\n    institutions, or in the context of international mobility projects.\nsubprocessors:\n  url: null\n  text: The University is supported by external service providers for technical-administrative management, which\n    could be made aware of the personal data of students,\
  \ for the sole purpose of the service required and which\n    would be previously authorized as external data processors.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to the data controller for cancellation, subject to storage obligations\n  text: Cancellation is not allowed for data included in documents that must be stored by the University\nrights:\n- right: Access, correction, cancellation, limitation or objection\n  text: To ask the data controller, pursuant to Article 16, 17, 18, 19 and 21 of Regulation (EU) 2016/679, the access\n    to their personal data and correction or their cancellation or limitation of the data processing that concern\n    him/her or to object to their processing.\n- right: Complaint to supervisory authority\n  text: To submit a complaint to a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/politecnico-di-milano/privacy/politecnico-di-milano-privacy-policy.yml
stated_fields:
- role
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 12 quoted statements, read from Politecnico di Milano's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Technical University
- Research
- Open Data
- Research Repository
- Course Catalog
- Identity Federation
- OAI-PMH
- Shibboleth
- DCAT
- Italy
- Europe
---
