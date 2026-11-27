---
api_specs:
- filename: allagents-app-directory-api-openapi.yml
  format: yaml
  label: allagents Directory API
  slug: allagents-app-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allagents-app/openapi/allagents-app-directory-api-openapi.yml
- filename: allagents-app-discovery-api-openapi.yml
  format: yaml
  label: allagents Discovery API
  slug: allagents-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allagents-app/openapi/allagents-app-discovery-api-openapi.yml
- filename: allagents-app-listing-api-openapi.yml
  format: yaml
  label: allagents Listing API
  slug: allagents-app-listing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allagents-app/openapi/allagents-app-listing-api-openapi.yml
- filename: allagents-app-operator-api-openapi.yml
  format: yaml
  label: allagents Operator API
  slug: allagents-app-operator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allagents-app/openapi/allagents-app-operator-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: professional
    text: 'We store what a listing publishes: name, specialty, description, endpoints, tags, country and declared capabilities'
  - category: device
    text: with a one-day fingerprint of the sender instead of its address
  - category: communication
    text: Questions put to Ask 21 on /questions are handled the same way
  deletion:
    route: e-mail removal request
    text: A person named in a card may also ask for its removal by e-mail (contact below), no proof of endpoint control required
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention and improving operator answers
    text: We use them to prevent abuse and to improve the operator's answers.
  - purpose: answering questions via AI model provider
    text: Questions put to the operator are answered with the help of an AI model provider
  residency:
  - region: outside Switzerland
    text: which may process them outside Switzerland
  retention:
  - period: 30 days
    scope: technical logs
    text: technical logs for 30 days
  - period: 30 days
    scope: Ask 21 questions
    text: they are kept for 30 days with a one-day fingerprint instead of an address
  rights:
  - right: claim or remove card
    text: Any card can be claimed or removed by its owner, with proof.
  - right: removal by named person
    text: A person named in a card may also ask for its removal by e-mail
  role:
    text: 'Data controller: Stimhaus, Geneva, Switzerland'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We sell no data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: which may process them outside Switzerland
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: allagents
provenance_date: '2026-11-09'
provider_name: allagents
provider_slug: allagents-app
slug: allagents-app-privacy-policy
source_date: '2026-11-09'
source_filename: allagents-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://allagents.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: allagents\naid: allagents-app\nurl: https://allagents.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data controller: Stimhaus, Geneva, Switzerland'\ndata_categories:\n- category: professional\n  text: 'We store what a listing publishes: name, specialty, description, endpoints, tags, country and declared\n    capabilities'\n- category: device\n  text: with a one-day fingerprint of the sender instead of its address\n- category: communication\n  text: Questions put to Ask 21 on /questions are handled the same way\npurposes:\n- purpose: abuse prevention and improving operator answers\n\
  \  text: We use them to prevent abuse and to improve the operator's answers.\n- purpose: answering questions via AI model provider\n  text: Questions put to the operator are answered with the help of an AI model provider\nretention:\n- scope: technical logs\n  period: 30 days\n  text: technical logs for 30 days\n- scope: Ask 21 questions\n  period: 30 days\n  text: they are kept for 30 days with a one-day fingerprint instead of an address\nresidency:\n- region: outside Switzerland\n  text: which may process them outside Switzerland\ntransfers:\n- mechanism: other\n  text: which may process them outside Switzerland\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: e-mail removal request\n  text: A person named in a card may also ask for its removal by e-mail (contact below), no proof of endpoint control\n    required\nrights:\n- right: claim or remove card\n  text: Any card can be claimed or removed by its owner, with proof.\n\
  - right: removal by named person\n  text: A person named in a card may also ask for its removal by e-mail\nsale_or_sharing:\n  stance: prohibited\n  text: We sell no data.\n"
source_yaml_url: https://artifacts.apis.io/allagents-app/privacy/allagents-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from allagents's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Directory
- A2A
- Discovery
- Search
- Registry
- Switzerland
---
