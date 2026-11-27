---
api_specs:
- filename: b-well-users-api-openapi.yml
  format: yaml
  label: b.well Users API
  slug: b-well-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b-well/openapi/b-well-users-api-openapi.yml
- filename: b-well-webhook-api-openapi.yml
  format: yaml
  label: b.well Webhook API
  slug: b-well-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/b-well/openapi/b-well-webhook-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Data You Enter Directly. Any information you share with the b.well application through your b.well account. This can include demographic information, and other self-reported data that you enter manually
  - category: device
    text: Passive Data. Any information that the b.well application collects passively from your device or browser or your interactions with the application.
  - category: health
    text: ePHR Data. Any copy of Health Data that is available for you to access under your direction through a Health Data Connection (defined below).
  deletion:
    route: In-app PHR deletion or account closure
    text: You can permanently delete your PHR at any time and for any reason without closing your b.well account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Personal health record management
    text: The b.well application collects your Personal Data so we can help you build and manage a summary of your health history
  - purpose: Personalized insights
    text: We also build personalized insights and tools on top of your Personal Data to deliver more personalized assistance related to your health and healthcare needs.
  - purpose: Marketing and communications
    text: send you communications
  - purpose: Sale of data
    text: By accepting this Privacy Policy and using the b.well application, you are not giving default consent for b.well to sell or trade in your Personal Data or Non-Personal Data.
  residency:
  - region: United States
    text: The b.well application is hosted in the United States and does not transfer your Personal Data to regions outside the United States.
  retention:
  - period: 10 years
    scope: Dormant accounts
    text: We follow an established data retention policy for deleting the Personal Data of dormant accounts after 10 years and closed accounts after 30 days.
  - period: 30 days
    scope: Closed accounts
    text: We delete the Personal Data of permanently disabled (closed) accounts after 30 days.
  rights:
  - right: Data correction
    text: You can contact Support if you discover an error in your Personal Data.
  - right: Consent revocation
    text: The b.well application includes tools that help you view, change and revoke consents.
  role:
    text: This Privacy Policy describes the privacy commitments and data practices for the applications and digital experiences that b.well Connected Health, Inc. makes available under the b.well brand.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: By accepting this Privacy Policy and using the b.well application, you are not giving default consent for b.well to sell or trade in your Personal Data or Non-Personal Data.
  subprocessors:
    text: We publish a list of current list of these vendors on our website at https://www.icanbwell.com/sub-processors .
    url: https://www.icanbwell.com/sub-processors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: b.well
provenance_date: '2026-11-09'
provider_name: b.well
provider_slug: b-well
slug: b-well-privacy-policy
source_date: '2026-11-09'
source_filename: b-well-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.icanbwell.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: b.well\naid: b-well\nurl: https://www.icanbwell.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy describes the privacy commitments and data practices for the applications and digital\n    experiences that b.well Connected Health, Inc. makes available under the b.well brand.\ndata_categories:\n- category: identifying\n  text: Data You Enter Directly. Any information you share with the b.well application through your b.well account.\n    This can include demographic information, and other self-reported data that you enter manually\n- category: device\n\
  \  text: Passive Data. Any information that the b.well application collects passively from your device or browser\n    or your interactions with the application.\n- category: health\n  text: ePHR Data. Any copy of Health Data that is available for you to access under your direction through a Health\n    Data Connection (defined below).\npurposes:\n- purpose: Personal health record management\n  text: The b.well application collects your Personal Data so we can help you build and manage a summary of your\n    health history\n- purpose: Personalized insights\n  text: We also build personalized insights and tools on top of your Personal Data to deliver more personalized\n    assistance related to your health and healthcare needs.\n- purpose: Marketing and communications\n  text: send you communications\n- purpose: Sale of data\n  text: By accepting this Privacy Policy and using the b.well application, you are not giving default consent for\n    b.well to sell or trade in your Personal Data\
  \ or Non-Personal Data.\nretention:\n- scope: Dormant accounts\n  period: 10 years\n  text: We follow an established data retention policy for deleting the Personal Data of dormant accounts after\n    10 years and closed accounts after 30 days.\n- scope: Closed accounts\n  period: 30 days\n  text: We delete the Personal Data of permanently disabled (closed) accounts after 30 days.\nresidency:\n- region: United States\n  text: The b.well application is hosted in the United States and does not transfer your Personal Data to regions\n    outside the United States.\ntransfers: []\nsubprocessors:\n  url: https://www.icanbwell.com/sub-processors\n  text: We publish a list of current list of these vendors on our website at https://www.icanbwell.com/sub-processors\n    .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app PHR deletion or account closure\n  text: You can permanently delete your PHR at any time and for any reason without closing your b.well account.\n\
  rights:\n- right: Data correction\n  text: You can contact Support if you discover an error in your Personal Data.\n- right: Consent revocation\n  text: The b.well application includes tools that help you view, change and revoke consents.\nsale_or_sharing:\n  stance: prohibited\n  text: By accepting this Privacy Policy and using the b.well application, you are not giving default consent for\n    b.well to sell or trade in your Personal Data or Non-Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/b-well/privacy/b-well-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from b.well's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- FHIR
- Health Data
- Interoperability
- Patient Access
- Health Records
- MCP
---
