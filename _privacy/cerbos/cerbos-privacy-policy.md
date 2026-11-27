---
api_specs:
- filename: cerbos-admin-audit-api-openapi.yml
  format: yaml
  label: Cerbos Admin Audit API
  slug: cerbos-admin-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-audit-api-openapi.yml
- filename: cerbos-admin-policies-api-openapi.yml
  format: yaml
  label: Cerbos Admin Policies API
  slug: cerbos-admin-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-policies-api-openapi.yml
- filename: cerbos-admin-schemas-api-openapi.yml
  format: yaml
  label: Cerbos Admin Schemas API
  slug: cerbos-admin-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-schemas-api-openapi.yml
- filename: cerbos-admin-store-api-openapi.yml
  format: yaml
  label: Cerbos Admin Store API
  slug: cerbos-admin-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-admin-store-api-openapi.yml
- filename: cerbos-check-api-openapi.yml
  format: yaml
  label: Cerbos Check API
  slug: cerbos-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-check-api-openapi.yml
- filename: cerbos-plan-api-openapi.yml
  format: yaml
  label: Cerbos Plan API
  slug: cerbos-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-plan-api-openapi.yml
- filename: cerbos-server-api-openapi.yml
  format: yaml
  label: Cerbos Server API
  slug: cerbos-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-server-api-openapi.yml
- filename: cerbos-auth-zen-api-openapi.yml
  format: yaml
  label: Cerbos Auth ZEN API
  slug: cerbos-auth-zen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cerbos/openapi/cerbos-auth-zen-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, last name, email address, phone number, contact data, device's ID, your user preferences
  - category: device
    text: date and time of access, name website, IP address, referrer URL
  - category: location
    text: In case geo-location is opt-in by you, please be aware we may have access to your geo-location data
  deletion:
    route: email request
    text: To make a request, please let us know by sending an email to info@cerbos.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: delivering services
    text: We will use information about you for delivering our Services to you under the terms of use agreed between us.
  - purpose: website optimization via cookies
    text: The information is used to optimize the users' experience by customizing our web page content based on visitors' browser type and/or other information.
  rights:
  - right: access
    text: You have the right to request a copy of the personal information we process about you and to have any inaccuracies corrected.
  - right: erasure or restriction
    text: You can ask us to restrict, stop processing, or to delete your personal data.
  - right: withdraw consent
    text: You can withdraw your consent for data processing.
  - right: portability
    text: Obtain a copy of your personal data, which you can use with another service provider
  - right: complain to supervisory authority
    text: Make a complaint to a Supervisory Authority.
  role:
    text: Where we decide the purpose or means for which personal data you supply through these Services is processed, we are the "controller".
    value: controller
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
name: Cerbos
provenance_date: '2026-11-09'
provider_name: Cerbos
provider_slug: cerbos
slug: cerbos-privacy-policy
source_date: '2026-11-09'
source_filename: cerbos-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cerbos.dev/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cerbos\naid: cerbos\nurl: https://www.cerbos.dev/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Where we decide the purpose or means for which personal data you supply through these Services is processed,\n    we are the \"controller\".\ndata_categories:\n- category: identifying\n  text: Your name, last name, email address, phone number, contact data, device's ID, your user preferences\n- category: device\n  text: date and time of access, name website, IP address, referrer URL\n- category: location\n  text: In case geo-location is opt-in by you, please be aware we may have access\
  \ to your geo-location data\npurposes:\n- purpose: delivering services\n  text: We will use information about you for delivering our Services to you under the terms of use agreed between\n    us.\n- purpose: website optimization via cookies\n  text: The information is used to optimize the users' experience by customizing our web page content based on visitors'\n    browser type and/or other information.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: To make a request, please let us know by sending an email to info@cerbos.dev .\nrights:\n- right: access\n  text: You have the right to request a copy of the personal information we process about you and to have any inaccuracies\n    corrected.\n- right: erasure or restriction\n  text: You can ask us to restrict, stop processing, or to delete your personal data.\n- right: withdraw consent\n  text: You can\
  \ withdraw your consent for data processing.\n- right: portability\n  text: Obtain a copy of your personal data, which you can use with another service provider\n- right: complain to supervisory authority\n  text: Make a complaint to a Supervisory Authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cerbos/privacy/cerbos-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- deletion
- rights
summary_line: 12 quoted statements, read from Cerbos's own page on 2026-11-09.
synthetic: false
tags:
- ABAC
- Access Control
- Authorization
- AuthZEN
- Open Source
- PBAC
- PDP
- Permissions
- Policy as Code
- RBAC
- ReBAC
- Zero Trust
---
