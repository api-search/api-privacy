---
api_specs:
- filename: everpop-app-campaigns-api-openapi.yml
  format: yaml
  label: Everpop Campaigns API
  slug: everpop-app-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-campaigns-api-openapi.yml
- filename: everpop-app-clip-api-openapi.yml
  format: yaml
  label: Everpop Clip API
  slug: everpop-app-clip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-clip-api-openapi.yml
- filename: everpop-app-generate-api-openapi.yml
  format: yaml
  label: Everpop Generate API
  slug: everpop-app-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-generate-api-openapi.yml
- filename: everpop-app-jobs-api-openapi.yml
  format: yaml
  label: Everpop Jobs API
  slug: everpop-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-jobs-api-openapi.yml
- filename: everpop-app-posts-api-openapi.yml
  format: yaml
  label: Everpop Posts API
  slug: everpop-app-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-posts-api-openapi.yml
- filename: everpop-app-publish-api-openapi.yml
  format: yaml
  label: Everpop Publish API
  slug: everpop-app-publish-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-publish-api-openapi.yml
- filename: everpop-app-receipts-api-openapi.yml
  format: yaml
  label: Everpop Receipts API
  slug: everpop-app-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-receipts-api-openapi.yml
- filename: everpop-app-usage-api-openapi.yml
  format: yaml
  label: Everpop Usage API
  slug: everpop-app-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-usage-api-openapi.yml
- filename: everpop-app-videos-api-openapi.yml
  format: yaml
  label: Everpop Videos API
  slug: everpop-app-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpop-app/openapi/everpop-app-videos-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email address, and password (stored hashed) when you register.'
  - category: contact
    text: email address of a person a workspace owner invites (Section 4)
  - category: financial
    text: 'Billing information: processed by our payment provider (Stripe). We do not store full card numbers.'
  - category: location
    text: 'Usage data: log data, device/browser information, IP address, and — only if you enable it — product analytics about how you interact with the Service.'
  - category: communication
    text: 'Communications and reports: messages you send to support'
  - category: behavioral
    text: 'Clip performance data: aggregate per-clip and per-channel metrics retrieved from platform analytics APIs you authorize (see Section 5). Never viewer-level data.'
  deletion:
    route: Data deletion page, or request via privacy@everpop.app
    text: You may request deletion of your account and associated personal data at any time — see our Data deletion page.
  dpa:
    available: true
    text: business customers can request the current details and DPA.
    url: null
  purposes:
  - purpose: Providing the Service
    text: To provide, operate, maintain, and improve the Service
  - purpose: Payments and subscriptions
    text: To process payments, manage subscriptions, and prevent fraud
  - purpose: Security and monitoring
    text: To monitor, secure, alert our team about, and troubleshoot the Service
  - purpose: Legal compliance
    text: To comply with legal obligations and enforce our Terms.
  residency:
  - region: Bulgaria/EU
    text: Everpop-operated render machines (Bulgaria, EU)
  retention:
  - period: no later than 30 days
    scope: Account & profile data
    text: deleted promptly when you delete your account — normally immediately and no later than 30 days
  - period: 21 days
    scope: Verify saved checks
    text: We keep your latest 20 saved checks for 21 days
  - period: up to 3 hours
    scope: Cached public video information
    text: cached public video information — up to 3 hours
  - period: up to 12 months
    scope: Audit and security logs
    text: 'Audit & security logs, server logs, and IP addresses in them: kept for fraud-prevention and security no longer than necessary for those purposes (up to 12 months)'
  rights:
  - right: access, correct, delete, port, restrict
    text: you may have the right to access, correct, delete, port, or restrict processing of your personal data
  - right: object
    text: You may object at any time to processing based on our legitimate interests, and to direct marketing
  - right: withdraw consent
    text: you may withdraw any consent you have given at any time without affecting the lawfulness of processing before the withdrawal
  - right: complain to supervisory authority
    text: You have the right to lodge a complaint with your local supervisory authority
  role:
    text: As the controller is established in Bulgaria, our lead supervisory authority is the Bulgarian Commission for Personal Data Protection (cpdp.bg).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information as defined by the CCPA/CPRA.
  subprocessors:
    text: 8. Subprocessors We use the following service providers and subprocessors to operate Everpop.
    url: https://everpop.app/privacy
  transfers:
  - mechanism: SCC
    text: For recipients outside the EEA and the UK we rely on the European Commission's Standard Contractual Clauses (Decision 2021/914)
  - mechanism: DPF
    text: or on the EU-US Data Privacy Framework (and its UK Extension) where the recipient is certified under it
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Everpop
provenance_date: '2026-11-09'
provider_name: Everpop
provider_slug: everpop-app
slug: everpop-app-privacy-policy
source_date: '2026-11-09'
source_filename: everpop-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://everpop.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Everpop\naid: everpop-app\nurl: https://everpop.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: As the controller is established in Bulgaria, our lead supervisory authority is the Bulgarian Commission\n    for Personal Data Protection (cpdp.bg).\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email address, and password (stored hashed) when you register.'\n- category: contact\n  text: email address of a person a workspace owner invites (Section 4)\n- category: financial\n  text: 'Billing information: processed by our payment provider (Stripe). We\
  \ do not store full card numbers.'\n- category: location\n  text: 'Usage data: log data, device/browser information, IP address, and — only if you enable it — product analytics\n    about how you interact with the Service.'\n- category: communication\n  text: 'Communications and reports: messages you send to support'\n- category: behavioral\n  text: 'Clip performance data: aggregate per-clip and per-channel metrics retrieved from platform analytics APIs\n    you authorize (see Section 5). Never viewer-level data.'\npurposes:\n- purpose: Providing the Service\n  text: To provide, operate, maintain, and improve the Service\n- purpose: Payments and subscriptions\n  text: To process payments, manage subscriptions, and prevent fraud\n- purpose: Security and monitoring\n  text: To monitor, secure, alert our team about, and troubleshoot the Service\n- purpose: Legal compliance\n  text: To comply with legal obligations and enforce our Terms.\nretention:\n- scope: Account & profile data\n  period:\
  \ no later than 30 days\n  text: deleted promptly when you delete your account — normally immediately and no later than 30 days\n- scope: Verify saved checks\n  period: 21 days\n  text: We keep your latest 20 saved checks for 21 days\n- scope: Cached public video information\n  period: up to 3 hours\n  text: cached public video information — up to 3 hours\n- scope: Audit and security logs\n  period: up to 12 months\n  text: 'Audit & security logs, server logs, and IP addresses in them: kept for fraud-prevention and security no\n    longer than necessary for those purposes (up to 12 months)'\nresidency:\n- region: Bulgaria/EU\n  text: Everpop-operated render machines (Bulgaria, EU)\ntransfers:\n- mechanism: SCC\n  text: For recipients outside the EEA and the UK we rely on the European Commission's Standard Contractual Clauses\n    (Decision 2021/914)\n- mechanism: DPF\n  text: or on the EU-US Data Privacy Framework (and its UK Extension) where the recipient is certified under it\nsubprocessors:\n\
  \  url: https://everpop.app/privacy\n  text: 8. Subprocessors We use the following service providers and subprocessors to operate Everpop.\ndpa:\n  available: true\n  url: null\n  text: business customers can request the current details and DPA.\ndeletion:\n  route: Data deletion page, or request via privacy@everpop.app\n  text: You may request deletion of your account and associated personal data at any time — see our Data deletion\n    page.\nrights:\n- right: access, correct, delete, port, restrict\n  text: you may have the right to access, correct, delete, port, or restrict processing of your personal data\n- right: object\n  text: You may object at any time to processing based on our legitimate interests, and to direct marketing\n- right: withdraw consent\n  text: you may withdraw any consent you have given at any time without affecting the lawfulness of processing before\n    the withdrawal\n- right: complain to supervisory authority\n  text: You have the right to lodge a complaint\
  \ with your local supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information as defined by the CCPA/CPRA.\n"
source_yaml_url: https://artifacts.apis.io/everpop-app/privacy/everpop-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Everpop's own page on 2026-11-09.
synthetic: false
tags:
- Video
- Artificial Intelligence
- Social Media
- Shorts
- Reels
---
