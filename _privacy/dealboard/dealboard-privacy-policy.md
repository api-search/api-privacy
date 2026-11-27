---
api_specs:
- filename: dealboard-deals-api-openapi.yml
  format: yaml
  label: Dealboard Deals API
  slug: dealboard-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-deals-api-openapi.yml
- filename: dealboard-reports-api-openapi.yml
  format: yaml
  label: Dealboard Reports API
  slug: dealboard-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-reports-api-openapi.yml
- filename: dealboard-templates-api-openapi.yml
  format: yaml
  label: Dealboard Templates API
  slug: dealboard-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-templates-api-openapi.yml
- filename: dealboard-auth-api-openapi.yml
  format: yaml
  label: Dealboard Auth API
  slug: dealboard-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-auth-api-openapi.yml
- filename: dealboard-boards-api-openapi.yml
  format: yaml
  label: Dealboard Boards API
  slug: dealboard-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-boards-api-openapi.yml
- filename: dealboard-dealboard-api-api-openapi.yml
  format: yaml
  label: Dealboard Dealboard API
  slug: dealboard-dealboard-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-dealboard-api-api-openapi.yml
- filename: dealboard-leads-api-openapi.yml
  format: yaml
  label: Dealboard Leads API
  slug: dealboard-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-leads-api-openapi.yml
- filename: dealboard-match-api-openapi.yml
  format: yaml
  label: Dealboard Match API
  slug: dealboard-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-match-api-openapi.yml
- filename: dealboard-notes-api-openapi.yml
  format: yaml
  label: Dealboard Notes API
  slug: dealboard-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-notes-api-openapi.yml
- filename: dealboard-webhooks-api-openapi.yml
  format: yaml
  label: Dealboard Webhooks API
  slug: dealboard-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email, profile photo (from Google OAuth or uploaded by you), and a hashed credential if you sign in with a password.
  - category: financial
    text: Dealboard receives a card brand, last four digits, and a Stripe customer ID — never your full card number.
  - category: behavioral
    text: Pages visited inside the app, feature clicks, error events, and approximate session duration.
  - category: device
    text: IP address, browser type, operating system, and timestamps.
  - category: communication
    text: the contents of forms submitted to your boards or emails sent to your inbound address
  deletion:
    route: account deletion in the app
    text: 'When you delete your account: We mark it for deletion immediately.'
  dpa:
    available: true
    text: Higher-volume customers who require it can request our standard Data Processing Addendum at support@getdealboard.com .
    url: null
  purposes:
  - purpose: Operate, secure, and improve the Service
    text: Operate, secure, and improve the Service.
  - purpose: Account authentication and protection
    text: Authenticate you and protect your account.
  - purpose: Product news and onboarding tips
    text: Send occasional product news and onboarding tips (lifecycle).
  - purpose: Security and debugging
    text: Used for security (rate limiting, anomaly detection) and debugging.
  residency:
  - region: United States
    text: Dealboard's servers are located in the United States and personal information is processed in the United States.
  retention:
  - period: for as long as your account is active
    scope: customer content
    text: We retain your customer content for as long as your account is active.
  - period: approximately 30 days
    scope: deleted account grace period
    text: You can typically sign back in within approximately 30 days to restore it
  - period: for the period required by law
    scope: billing record
    text: We retain a minimal billing record (Stripe customer ID, invoices, tax records) for the period required by law.
  rights:
  - right: Know
    text: Request the categories and specific pieces of personal information we've collected about you
  - right: Delete
    text: Request that we delete the personal information we've collected from you.
  - right: Correct
    text: Request that we correct inaccurate personal information.
  - right: Access, rectify, erase, restrict, port, object (EEA/UK)
    text: you have the rights to access, rectify, erase, restrict, port, and object to processing of your personal data
  role:
    text: Dealboard acts strictly as a data processor (under GDPR and UK GDPR)
    value: both
  sale_or_sharing:
    stance: conditional
    text: You can opt out two ways
  subprocessors:
    text: Higher-volume customers can request a current subprocessor list at any time at support@getdealboard.com .
    url: null
  transfers:
  - mechanism: SCC
    text: such as the European Commission's Standard Contractual Clauses and the UK Addendum, as applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dealboard
provenance_date: '2026-11-09'
provider_name: Dealboard
provider_slug: dealboard
slug: dealboard-privacy-policy
source_date: '2026-11-09'
source_filename: dealboard-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://getdealboard.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dealboard\naid: dealboard\nurl: https://getdealboard.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Dealboard acts strictly as a data processor (under GDPR and UK GDPR)\ndata_categories:\n- category: identifying\n  text: Your name, email, profile photo (from Google OAuth or uploaded by you), and a hashed credential if you sign\n    in with a password.\n- category: financial\n  text: Dealboard receives a card brand, last four digits, and a Stripe customer ID — never your full card number.\n- category: behavioral\n  text: Pages visited inside the app, feature clicks, error events, and\
  \ approximate session duration.\n- category: device\n  text: IP address, browser type, operating system, and timestamps.\n- category: communication\n  text: the contents of forms submitted to your boards or emails sent to your inbound address\npurposes:\n- purpose: Operate, secure, and improve the Service\n  text: Operate, secure, and improve the Service.\n- purpose: Account authentication and protection\n  text: Authenticate you and protect your account.\n- purpose: Product news and onboarding tips\n  text: Send occasional product news and onboarding tips (lifecycle).\n- purpose: Security and debugging\n  text: Used for security (rate limiting, anomaly detection) and debugging.\nretention:\n- scope: customer content\n  period: for as long as your account is active\n  text: We retain your customer content for as long as your account is active.\n- scope: deleted account grace period\n  period: approximately 30 days\n  text: You can typically sign back in within approximately 30 days to\
  \ restore it\n- scope: billing record\n  period: for the period required by law\n  text: We retain a minimal billing record (Stripe customer ID, invoices, tax records) for the period required by\n    law.\nresidency:\n- region: United States\n  text: Dealboard's servers are located in the United States and personal information is processed in the United\n    States.\ntransfers:\n- mechanism: SCC\n  text: such as the European Commission's Standard Contractual Clauses and the UK Addendum, as applicable\nsubprocessors:\n  url: null\n  text: Higher-volume customers can request a current subprocessor list at any time at support@getdealboard.com\n    .\ndpa:\n  available: true\n  url: null\n  text: Higher-volume customers who require it can request our standard Data Processing Addendum at support@getdealboard.com\n    .\ndeletion:\n  route: account deletion in the app\n  text: 'When you delete your account: We mark it for deletion immediately.'\nrights:\n- right: Know\n  text: Request the categories\
  \ and specific pieces of personal information we've collected about you\n- right: Delete\n  text: Request that we delete the personal information we've collected from you.\n- right: Correct\n  text: Request that we correct inaccurate personal information.\n- right: Access, rectify, erase, restrict, port, object (EEA/UK)\n  text: you have the rights to access, rectify, erase, restrict, port, and object to processing of your personal\n    data\nsale_or_sharing:\n  stance: conditional\n  text: You can opt out two ways\n"
source_yaml_url: https://artifacts.apis.io/dealboard/privacy/dealboard-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Dealboard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Sales
- Artificial Intelligence
- Integration
---
