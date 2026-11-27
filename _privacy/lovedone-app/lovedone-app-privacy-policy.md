---
api_specs:
- filename: lovedone-app-content-api-openapi.yml
  format: yaml
  label: lovedone-app Content API
  slug: lovedone-app-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lovedone-app/openapi/lovedone-app-content-api-openapi.yml
- filename: lovedone-app-discovery-api-openapi.yml
  format: yaml
  label: lovedone-app Discovery API
  slug: lovedone-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lovedone-app/openapi/lovedone-app-discovery-api-openapi.yml
- filename: lovedone-app-mcp-api-openapi.yml
  format: yaml
  label: lovedone-app MCP API
  slug: lovedone-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lovedone-app/openapi/lovedone-app-mcp-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we may collect your name, email address, and password.
  - category: device
    text: pages visited, device type, browser type, IP address, and referring URL
  - category: communication
    text: Messages sent to your loved one's @lovedone.app address, including attachments, are stored to provide the shared family inbox.
  deletion:
    route: Delete account
    text: If you delete your account, we will remove your personal data within 30 days, except where required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Transactional communications
    text: Send transactional communications
  - purpose: Analytics to improve features
    text: Analyze usage to improve features
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud or abuse
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: United States
    text: Your data is stored using Google Cloud Platform (Firebase / Firestore) in the United States.
  retention:
  - period: null
    scope: Account data
    text: We retain your personal information for as long as your account is active or as needed to provide the Service.
  - period: 30 days
    scope: Deleted account data
    text: If you delete your account, we will remove your personal data within 30 days, except where required by law.
  rights:
  - right: Access, correct, delete, object, port
    text: You may have the right to access, correct, delete, object to, or port your data.
  - right: CCPA right to know and request deletion
    text: California residents have additional rights under CCPA, including the right to know what we collect and to request deletion.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'Service Providers: Hosting (Vercel), analytics, email delivery (Resend), subject to confidentiality.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: lovedone-app
provenance_date: '2026-11-09'
provider_name: lovedone-app
provider_slug: lovedone-app
slug: lovedone-app-privacy-policy
source_date: '2026-11-09'
source_filename: lovedone-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lovedone.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: lovedone-app\naid: lovedone-app\nurl: https://lovedone.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we may collect your name, email address, and password.\n- category: device\n  text: pages visited, device type, browser type, IP address, and referring URL\n- category: communication\n  text: Messages sent to your loved one's @lovedone.app address, including attachments, are stored to provide the\n    shared family inbox.\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate,\
  \ and maintain the Service\n- purpose: Transactional communications\n  text: Send transactional communications\n- purpose: Analytics to improve features\n  text: Analyze usage to improve features\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud or abuse\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account data\n  period: null\n  text: We retain your personal information for as long as your account is active or as needed to provide the Service.\n- scope: Deleted account data\n  period: 30 days\n  text: If you delete your account, we will remove your personal data within 30 days, except where required by law.\nresidency:\n- region: United States\n  text: Your data is stored using Google Cloud Platform (Firebase / Firestore) in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service Providers: Hosting (Vercel), analytics, email delivery (Resend), subject to confidentiality.'\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Delete account\n  text: If you delete your account, we will remove your personal data within 30 days, except where required by law.\nrights:\n- right: Access, correct, delete, object, port\n  text: You may have the right to access, correct, delete, object to, or port your data.\n- right: CCPA right to know and request deletion\n  text: California residents have additional rights under CCPA, including the right to know what we collect and\n    to request deletion.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/lovedone-app/privacy/lovedone-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from lovedone-app's own page on 2026-11-09.
synthetic: false
tags:
- Family Care
- Inbox
- Healthcare
- Communications
- Privacy
---
