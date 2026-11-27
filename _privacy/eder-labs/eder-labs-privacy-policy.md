---
api_specs:
- filename: eder-labs-ingestion-api-openapi.yml
  format: yaml
  label: Eder Labs Ingestion API
  slug: eder-labs-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-ingestion-api-openapi.yml
- filename: eder-labs-meta-api-openapi.yml
  format: yaml
  label: Eder Labs Meta API
  slug: eder-labs-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-meta-api-openapi.yml
- filename: eder-labs-query-api-openapi.yml
  format: yaml
  label: Eder Labs Query API
  slug: eder-labs-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-query-api-openapi.yml
- filename: eder-labs-users-api-openapi.yml
  format: yaml
  label: Eder Labs Users API
  slug: eder-labs-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-users-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: email address, first and last name, phone number, address (country, state, province, ZIP/Postal code, city)
  - category: device
    text: IP address, browser type and version, pages visited, time and date of visit, time spent on pages, unique device identifiers
  - category: behavioral
    text: We use cookies and similar tracking technologies (beacons, tags, scripts) to track activity and hold certain information.
  - category: demographic
    text: sex, age, date/place of birth, passport details, citizenship
  - category: financial
    text: compensation
  deletion:
    route: Email hello@eder.io
    text: Users can change personal information by emailing hello@eder.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain our Service.
  - purpose: Marketing communications
    text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials, and other information of interest.
  - purpose: Behavioral remarketing
    text: We may use remarketing services to advertise after you visit our Service.
  - purpose: Analytics and improvement
    text: Gather analysis or valuable information to improve the Service.
  retention:
  - period: null
    scope: Personal Data
    text: Personal Data is retained only as long as necessary for purposes set out in this policy and to comply with legal obligations, resolve disputes, and enforce agreements.
  - period: null
    scope: Usage Data
    text: Usage Data is retained for shorter periods unless needed for security or functionality improvements or if law requires longer retention.
  rights:
  - right: access
    text: 'If you are in the EU/EEA, you may request: access, update, deletion, rectification, objection to processing, restriction, data portability, and withdrawal of consent.'
  - right: deletion (CCPA)
    text: deletion of personal information
  - right: opt out of sale
    text: cessation of “selling” personal information (we do not sell for monetary consideration).
  role:
    text: Eder Labs is the Data Controller for your data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: we do not sell for monetary consideration
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: By submitting data, you consent to transfer to the US and processing there.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Eder Labs
provenance_date: '2026-11-09'
provider_name: Eder Labs
provider_slug: eder-labs
slug: eder-labs-privacy-policy
source_date: '2026-11-09'
source_filename: eder-labs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.eder.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Eder Labs\naid: eder-labs\nurl: https://www.eder.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Eder Labs is the Data Controller for your data.\ndata_categories:\n- category: contact\n  text: email address, first and last name, phone number, address (country, state, province, ZIP/Postal code, city)\n- category: device\n  text: IP address, browser type and version, pages visited, time and date of visit, time spent on pages, unique\n    device identifiers\n- category: behavioral\n  text: We use cookies and similar tracking technologies (beacons, tags, scripts) to track activity and\
  \ hold certain\n    information.\n- category: demographic\n  text: sex, age, date/place of birth, passport details, citizenship\n- category: financial\n  text: compensation\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain our Service.\n- purpose: Marketing communications\n  text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials, and other\n    information of interest.\n- purpose: Behavioral remarketing\n  text: We may use remarketing services to advertise after you visit our Service.\n- purpose: Analytics and improvement\n  text: Gather analysis or valuable information to improve the Service.\nretention:\n- scope: Personal Data\n  period: null\n  text: Personal Data is retained only as long as necessary for purposes set out in this policy and to comply with\n    legal obligations, resolve disputes, and enforce agreements.\n- scope: Usage Data\n  period: null\n  text: Usage Data is retained for shorter\
  \ periods unless needed for security or functionality improvements or if\n    law requires longer retention.\nresidency: []\ntransfers:\n- mechanism: other\n  text: By submitting data, you consent to transfer to the US and processing there.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@eder.io\n  text: Users can change personal information by emailing hello@eder.io.\nrights:\n- right: access\n  text: 'If you are in the EU/EEA, you may request: access, update, deletion, rectification, objection to processing,\n    restriction, data portability, and withdrawal of consent.'\n- right: deletion (CCPA)\n  text: deletion of personal information\n- right: opt out of sale\n  text: cessation of “selling” personal information (we do not sell for monetary consideration).\nsale_or_sharing:\n  stance: unstated\n  text: we do not sell for monetary consideration\n"
source_yaml_url: https://artifacts.apis.io/eder-labs/privacy/eder-labs-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from Eder Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- AI Agents
- Memory
- Knowledge Graph
- Personalization
- Privacy
- Open Source
- Developer Tools
- RAG
---
