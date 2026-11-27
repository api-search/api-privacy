---
api_specs:
- filename: vidplate-app-account-api-openapi.yml
  format: yaml
  label: VidPlate Account API
  slug: vidplate-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-account-api-openapi.yml
- filename: vidplate-app-render-nodes-api-openapi.yml
  format: yaml
  label: VidPlate Render nodes API
  slug: vidplate-app-render-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-render-nodes-api-openapi.yml
- filename: vidplate-app-render-presets-api-openapi.yml
  format: yaml
  label: VidPlate Render presets API
  slug: vidplate-app-render-presets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-render-presets-api-openapi.yml
- filename: vidplate-app-renders-api-openapi.yml
  format: yaml
  label: VidPlate Renders API
  slug: vidplate-app-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-renders-api-openapi.yml
- filename: vidplate-app-storage-destinations-api-openapi.yml
  format: yaml
  label: VidPlate Storage destinations API
  slug: vidplate-app-storage-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-storage-destinations-api-openapi.yml
- filename: vidplate-app-templates-api-openapi.yml
  format: yaml
  label: VidPlate Templates API
  slug: vidplate-app-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-templates-api-openapi.yml
- filename: vidplate-app-uploads-api-openapi.yml
  format: yaml
  label: VidPlate Uploads API
  slug: vidplate-app-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-uploads-api-openapi.yml
- filename: vidplate-app-webhook-endpoints-api-openapi.yml
  format: yaml
  label: VidPlate Webhook endpoints API
  slug: vidplate-app-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vidplate-app/openapi/vidplate-app-webhook-endpoints-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: full name, email address, and password when you register
  - category: contact
    text: we may receive names, business email addresses, job titles, employer and company details, business locations
  - category: behavioral
    text: actions performed on the platform such as clicks, page views, and time spent
  - category: device
    text: IP address, browser type, operating system, device information
  - category: financial
    text: we receive from Stripe and store a card fingerprint
  - category: communication
    text: feedback, support queries, and other correspondence
  - category: biometric
    text: A voice recording identifies the person who spoke it, and in some jurisdictions is treated as biometric data.
  deletion:
    route: account deletion request or account closure
    text: If you ask us to delete it, or your VidPlate account closes, we delete it straight away.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver and operate VidPlate and its features
    text: Deliver and operate VidPlate and its features.
  - purpose: Improve and develop product using anonymized data
    text: Improve and develop our product using anonymized data.
  retention:
  - period: seven days
    scope: Free Trial attempt records
    text: Attempt records expire after seven days.
  - period: twelve (12) months
    scope: Free Trial activation records
    text: The records are deleted automatically twelve (12) months after they are recorded.
  - period: 30 days
    scope: YouTube statistics
    text: Statistics read from YouTube are deleted or refreshed within 30 days
  rights:
  - right: access, correction, objection and erasure
    text: Access/export, correction, objection and erasure requests can be made to [email protected] or the responsible sender.
  role:
    text: VidPlate Ltd is the controller of your VidPlate account details and of the details of your own LinkedIn connections.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell this data or repurpose it beyond the functionality described in this Privacy Policy.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: VidPlate
provenance_date: '2026-11-10'
provider_name: VidPlate
provider_slug: vidplate-app
slug: vidplate-app-privacy-policy
source_date: '2026-11-10'
source_filename: vidplate-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vidplate.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: VidPlate\naid: vidplate-app\nurl: https://vidplate.app/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: VidPlate Ltd is the controller of your VidPlate account details and of the details of your own LinkedIn\n    connections.\ndata_categories:\n- category: identifying\n  text: full name, email address, and password when you register\n- category: contact\n  text: we may receive names, business email addresses, job titles, employer and company details, business locations\n- category: behavioral\n  text: actions performed on the platform such as clicks, page views, and\
  \ time spent\n- category: device\n  text: IP address, browser type, operating system, device information\n- category: financial\n  text: we receive from Stripe and store a card fingerprint\n- category: communication\n  text: feedback, support queries, and other correspondence\n- category: biometric\n  text: A voice recording identifies the person who spoke it, and in some jurisdictions is treated as biometric\n    data.\npurposes:\n- purpose: Deliver and operate VidPlate and its features\n  text: Deliver and operate VidPlate and its features.\n- purpose: Improve and develop product using anonymized data\n  text: Improve and develop our product using anonymized data.\nretention:\n- scope: Free Trial attempt records\n  period: seven days\n  text: Attempt records expire after seven days.\n- scope: Free Trial activation records\n  period: twelve (12) months\n  text: The records are deleted automatically twelve (12) months after they are recorded.\n- scope: YouTube statistics\n  period: 30\
  \ days\n  text: Statistics read from YouTube are deleted or refreshed within 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request or account closure\n  text: If you ask us to delete it, or your VidPlate account closes, we delete it straight away.\nrights:\n- right: access, correction, objection and erasure\n  text: Access/export, correction, objection and erasure requests can be made to [email protected] or the responsible\n    sender.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell this data or repurpose it beyond the functionality described in this Privacy Policy.\n"
source_yaml_url: https://artifacts.apis.io/vidplate-app/privacy/vidplate-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from VidPlate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Rendering
- 3D
- Templates
---
