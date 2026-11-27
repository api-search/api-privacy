---
api_specs:
- filename: hypr-analytics-api-openapi.yml
  format: yaml
  label: HYPR Analytics API
  slug: hypr-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-analytics-api-openapi.yml
- filename: hypr-control-center-api-openapi.yml
  format: yaml
  label: HYPR Control Center API
  slug: hypr-control-center-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-control-center-api-openapi.yml
- filename: hypr-fido-api-api-openapi.yml
  format: yaml
  label: HYPR FIDO API
  slug: hypr-fido-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-fido-api-api-openapi.yml
- filename: hypr-fido2-rp-api-api-openapi.yml
  format: yaml
  label: HYPR FIDO2 RP API
  slug: hypr-fido2-rp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-fido2-rp-api-api-openapi.yml
- filename: hypr-radius-api-openapi.yml
  format: yaml
  label: HYPR RADIUS API
  slug: hypr-radius-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-radius-api-openapi.yml
- filename: hypr-rp-applications-api-openapi.yml
  format: yaml
  label: HYPR RP Applications API
  slug: hypr-rp-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hypr/openapi/hypr-rp-applications-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: Typically, contact data includes your name and contact methods, such as telephone number, email address, and mailing address
  - category: biometric
    text: Face geometry, Voice print, voice match, and Video and audio footage to verify customer biometric data.
  - category: device
    text: operating system name and version, device identifier, browser type, browser language, geolocation, and IP address
  - category: financial
    text: payment card details, in connection with our Services
  - category: demographic
    text: racial or ethnic origin, or other such Personal Data in connection with your job application
  deletion:
    route: Request by emailing legal@hypr.com
    text: You also have a right to request that we delete your Personal Data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and promote the Services
    text: We use Personal Data to provide and promote the Services and respond to your requests
  - purpose: Fraud detection and authentication
    text: Perform fraud detection and authentication.
  - purpose: Verify identity for Affirm customers
    text: Verify your identity for companies which have implemented the Affirm Services.
  - purpose: Marketing
    text: Promote the Services or send you other HYPR marketing information (if you opt-in to receive marketing communications when creating an account or afterwards).
  retention:
  - period: null
    scope: Personal Data generally
    text: We will retain your Personal Data for a period of time that is consistent with the original purpose of the data collection, or as necessary to comply with our legal obligations, resolve disputes, and enforce our agreements.
  rights:
  - right: Access
    text: Access . You have the right to request information about how we process your Personal Data and to obtain a copy of that Personal Data.
  - right: Rectification
    text: Rectification. You have the right to request the rectification of inaccurate information about you
  - right: Erasure
    text: Erasure. You have the right to request the erasure of your Personal Data (subject to certain conditions).
  - right: Portability
    text: Portability. You have the right to receive your Personal Data, which you have provided to us, in a structured, commonly used and machine-readable format
  - right: Objection
    text: Objection. You have the right to object to the processing of your Personal Data, which is based on our legitimate interests (as described above).
  role:
    text: HYPR is the controller of your Personal Data, as described in this Privacy Policy, unless otherwise stated.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses for the transfer of data as approved by the European Commission or UK Secretary of State
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HYPR
provenance_date: '2026-11-09'
provider_name: HYPR
provider_slug: hypr
slug: hypr-privacy-policy
source_date: '2026-11-09'
source_filename: hypr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.hypr.com/trust-center/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HYPR\naid: hypr\nurl: https://www.hypr.com/trust-center/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: HYPR is the controller of your Personal Data, as described in this Privacy Policy, unless otherwise stated.\ndata_categories:\n- category: contact\n  text: Typically, contact data includes your name and contact methods, such as telephone number, email address,\n    and mailing address\n- category: biometric\n  text: Face geometry, Voice print, voice match, and Video and audio footage to verify customer biometric data.\n- category: device\n  text: operating system name and version,\
  \ device identifier, browser type, browser language, geolocation, and IP\n    address\n- category: financial\n  text: payment card details, in connection with our Services\n- category: demographic\n  text: racial or ethnic origin, or other such Personal Data in connection with your job application\npurposes:\n- purpose: Provide and promote the Services\n  text: We use Personal Data to provide and promote the Services and respond to your requests\n- purpose: Fraud detection and authentication\n  text: Perform fraud detection and authentication.\n- purpose: Verify identity for Affirm customers\n  text: Verify your identity for companies which have implemented the Affirm Services.\n- purpose: Marketing\n  text: Promote the Services or send you other HYPR marketing information (if you opt-in to receive marketing communications\n    when creating an account or afterwards).\nretention:\n- scope: Personal Data generally\n  period: null\n  text: We will retain your Personal Data for a period of\
  \ time that is consistent with the original purpose of the\n    data collection, or as necessary to comply with our legal obligations, resolve disputes, and enforce our agreements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses for the transfer of data as approved by the European Commission or UK Secretary\n    of State\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request by emailing legal@hypr.com\n  text: You also have a right to request that we delete your Personal Data.\nrights:\n- right: Access\n  text: Access . You have the right to request information about how we process your Personal Data and to obtain\n    a copy of that Personal Data.\n- right: Rectification\n  text: Rectification. You have the right to request the rectification of inaccurate information about you\n- right: Erasure\n  text: Erasure. You have the right to request the erasure of your Personal Data (subject\
  \ to certain conditions).\n- right: Portability\n  text: Portability. You have the right to receive your Personal Data, which you have provided to us, in a structured,\n    commonly used and machine-readable format\n- right: Objection\n  text: Objection. You have the right to object to the processing of your Personal Data, which is based on our legitimate\n    interests (as described above).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hypr/privacy/hypr-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from HYPR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Passwordless
- Authentication
- FIDO
- Security
---
