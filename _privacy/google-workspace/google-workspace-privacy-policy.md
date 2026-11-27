---
api_specs:
- filename: google-workspace-allowlisteddomains-api-openapi.yml
  format: yaml
  label: Google Workspace Allowlisted Domains API
  slug: google-workspace-allowlisteddomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-allowlisteddomains-api-openapi.yml
- filename: google-workspace-customerlicense-api-openapi.yml
  format: yaml
  label: Google Workspace Customer License API
  slug: google-workspace-customerlicense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-customerlicense-api-openapi.yml
- filename: google-workspace-customers-api-openapi.yml
  format: yaml
  label: Google Workspace Customers API
  slug: google-workspace-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-customers-api-openapi.yml
- filename: google-workspace-devices-api-openapi.yml
  format: yaml
  label: Google Workspace Devices API
  slug: google-workspace-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-devices-api-openapi.yml
- filename: google-workspace-groups-api-openapi.yml
  format: yaml
  label: Google Workspace Groups API
  slug: google-workspace-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-groups-api-openapi.yml
- filename: google-workspace-inboundoidcssoprofiles-api-openapi.yml
  format: yaml
  label: Google Workspace Inbound Oidc SSO Profiles API
  slug: google-workspace-inboundoidcssoprofiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-inboundoidcssoprofiles-api-openapi.yml
- filename: google-workspace-inboundsamlssoprofiles-api-openapi.yml
  format: yaml
  label: Google Workspace Inbound Saml SSO Profiles API
  slug: google-workspace-inboundsamlssoprofiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-inboundsamlssoprofiles-api-openapi.yml
- filename: google-workspace-inboundssoassignments-api-openapi.yml
  format: yaml
  label: Google Workspace Inbound SSO Assignments API
  slug: google-workspace-inboundssoassignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-inboundssoassignments-api-openapi.yml
- filename: google-workspace-operations-api-openapi.yml
  format: yaml
  label: Google Workspace Operations API
  slug: google-workspace-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-operations-api-openapi.yml
- filename: google-workspace-policies-api-openapi.yml
  format: yaml
  label: Google Workspace Policies API
  slug: google-workspace-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-policies-api-openapi.yml
- filename: google-workspace-subscriptions-api-openapi.yml
  format: yaml
  label: Google Workspace Subscriptions API
  slug: google-workspace-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-subscriptions-api-openapi.yml
- filename: google-workspace-userlicense-api-openapi.yml
  format: yaml
  label: Google Workspace User License API
  slug: google-workspace-userlicense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-workspace/openapi/google-workspace-userlicense-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers and similar information such as your name and password, phone number, and address, as well as unique identifiers tied to the browser, application, or device you’re using.
  - category: location
    text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around your device
  - category: health
    text: Health information if you choose to provide it, such as your medical history, vital signs and health metrics (like blood glucose levels)
  - category: biometric
    text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development studies.
  deletion:
    route: Delete your information from your Google Account at any time
    text: You can export a copy of your information or delete it from your Google Account at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our services
  - purpose: Measure performance
    text: We use data for analytics and measurement to understand how our services are used.
  - purpose: Advertising
    text: Google processes information to provide advertising, including online identifiers, browsing and search activity, and information about your location and interactions with advertisements.
  residency:
  - region: Global
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: Advertising data in server logs
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  rights:
  - right: Access, correct and delete
    text: U.S. state privacy laws also provide the right to request information about how Google collects, uses, and discloses your information.
  - right: Opt out of targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Google does not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Google Workspace
provenance_date: '2026-11-09'
provider_name: Google Workspace
provider_slug: google-workspace
slug: google-workspace-privacy-policy
source_date: '2026-11-09'
source_filename: google-workspace-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Workspace\naid: google-workspace\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: location\n  text: Geolocation data , such as may be determined by GPS, IP address, and other data from sensors on or around\n    your device\n- category: health\n  text: Health information if\
  \ you choose to provide it, such as your medical history, vital signs and health metrics\n    (like blood glucose levels)\n- category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\npurposes:\n- purpose: Provide services\n  text: We use your information to deliver our services\n- purpose: Measure performance\n  text: We use data for analytics and measurement to understand how our services are used.\n- purpose: Advertising\n  text: Google processes information to provide advertising, including online identifiers, browsing and search activity,\n    and information about your location and interactions with advertisements.\nretention:\n- scope: Advertising data in server logs\n  period: null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\nresidency:\n- region: Global\n  text: We maintain servers around the world and\
  \ your information may be processed on servers located outside of\n    the country where you live.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your information from your Google Account at any time\n  text: You can export a copy of your information or delete it from your Google Account at any time\nrights:\n- right: Access, correct and delete\n  text: U.S. state privacy laws also provide the right to request information about how Google collects, uses, and\n    discloses your information.\n- right: Opt out of targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\nsale_or_sharing:\n  stance: prohibited\n  text: Google does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/google-workspace/privacy/google-workspace-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Google Workspace's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Collaboration
- Email
- Productivity
- Storage
- Video Conferencing
- Google Workspace
---
