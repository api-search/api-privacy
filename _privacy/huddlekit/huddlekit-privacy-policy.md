---
api_specs:
- filename: huddlekit-account-api-openapi.yml
  format: yaml
  label: Huddlekit Account API
  slug: huddlekit-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huddlekit/openapi/huddlekit-account-api-openapi.yml
- filename: huddlekit-comments-api-openapi.yml
  format: yaml
  label: Huddlekit Comments API
  slug: huddlekit-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huddlekit/openapi/huddlekit-comments-api-openapi.yml
- filename: huddlekit-events-api-openapi.yml
  format: yaml
  label: Huddlekit Events API
  slug: huddlekit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huddlekit/openapi/huddlekit-events-api-openapi.yml
- filename: huddlekit-projects-api-openapi.yml
  format: yaml
  label: Huddlekit Projects API
  slug: huddlekit-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huddlekit/openapi/huddlekit-projects-api-openapi.yml
- filename: huddlekit-webhook-events-api-openapi.yml
  format: yaml
  label: Huddlekit Webhook events API
  slug: huddlekit-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huddlekit/openapi/huddlekit-webhook-events-api-openapi.yml
- filename: huddlekit-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Huddlekit Webhook subscriptions API
  slug: huddlekit-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huddlekit/openapi/huddlekit-webhook-subscriptions-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information such as your name, email address, and password when you register
  - category: financial
    text: Billing and payment information when you purchase a subscription (processed by Stripe, our third-party payment provider)
  - category: location
    text: IP address, browser type, operating system, and referring URLs
  - category: behavioral
    text: Usage data such as features accessed, pages viewed, and interaction patterns
  - category: device
    text: Technical data related to your feedback, including page URLs, viewport dimensions, device type, and browser information
  - category: communication
    text: Communications you send to us, such as support requests
  deletion:
    route: Contact support@huddlekit.com
    text: To exercise any of these rights, please contact us at support@huddlekit.com.
  dpa:
    available: true
    text: Each acts under a Data Processing Agreement and only processes data as necessary to provide services on our behalf
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: Provide, operate, maintain, and improve the Service
  - purpose: Process transactions
    text: Process transactions and manage your subscription
  - purpose: Security and fraud
    text: Detect, prevent, and address technical issues, fraud, or security concerns
  - purpose: Analytics
    text: Generate aggregate, anonymized data for analytics and product development
  residency:
  - region: European Union
    text: Our primary data stores (Supabase database and file storage) and product analytics (PostHog) are hosted in the European Union.
  retention:
  - period: null
    scope: Account data
    text: When you delete your account, we will delete or anonymize your personal information within a reasonable period, unless retention is required by law or for legitimate business purposes such as resolving disputes.
  - period: null
    scope: User content
    text: User Content associated with active workspaces may be retained until the workspace owner deletes it or the workspace is terminated.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal information we hold about you'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete information'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal information, subject to legal obligations'
  - right: Data portability
    text: 'Data portability: Request a copy of your data in a structured, commonly used format'
  - right: Restriction
    text: 'Restriction: Request that we restrict the processing of your information'
  - right: Objection
    text: 'Objection: Object to our processing of your personal information'
  role:
    text: Everace AB is the data controller (personuppgiftsansvarig) for personal data processed through the Service.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: We rely on the following sub-processors to operate the Service.
    url: null
  transfers:
  - mechanism: SCC
    text: including the European Commission's Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: and, where applicable, the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Huddlekit
provenance_date: '2026-11-09'
provider_name: Huddlekit
provider_slug: huddlekit
slug: huddlekit-privacy-policy
source_date: '2026-11-09'
source_filename: huddlekit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://huddlekit.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Huddlekit\naid: huddlekit\nurl: https://huddlekit.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Everace AB is the data controller (personuppgiftsansvarig) for personal data processed through the Service.\ndata_categories:\n- category: identifying\n  text: Account information such as your name, email address, and password when you register\n- category: financial\n  text: Billing and payment information when you purchase a subscription (processed by Stripe, our third-party payment\n    provider)\n- category: location\n  text: IP address, browser type, operating system, and referring\
  \ URLs\n- category: behavioral\n  text: Usage data such as features accessed, pages viewed, and interaction patterns\n- category: device\n  text: Technical data related to your feedback, including page URLs, viewport dimensions, device type, and browser\n    information\n- category: communication\n  text: Communications you send to us, such as support requests\npurposes:\n- purpose: Provide and improve the Service\n  text: Provide, operate, maintain, and improve the Service\n- purpose: Process transactions\n  text: Process transactions and manage your subscription\n- purpose: Security and fraud\n  text: Detect, prevent, and address technical issues, fraud, or security concerns\n- purpose: Analytics\n  text: Generate aggregate, anonymized data for analytics and product development\nretention:\n- scope: Account data\n  period: null\n  text: When you delete your account, we will delete or anonymize your personal information within a reasonable\n    period, unless retention is required by\
  \ law or for legitimate business purposes such as resolving disputes.\n- scope: User content\n  period: null\n  text: User Content associated with active workspaces may be retained until the workspace owner deletes it or the\n    workspace is terminated.\nresidency:\n- region: European Union\n  text: Our primary data stores (Supabase database and file storage) and product analytics (PostHog) are hosted\n    in the European Union.\ntransfers:\n- mechanism: SCC\n  text: including the European Commission's Standard Contractual Clauses (SCCs)\n- mechanism: DPF\n  text: and, where applicable, the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: We rely on the following sub-processors to operate the Service.\ndpa:\n  available: true\n  url: null\n  text: Each acts under a Data Processing Agreement and only processes data as necessary to provide services on\n    our behalf\ndeletion:\n  route: Contact support@huddlekit.com\n  text: To exercise any of these rights, please contact\
  \ us at support@huddlekit.com.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal information we hold about you'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal information, subject to legal obligations'\n- right: Data portability\n  text: 'Data portability: Request a copy of your data in a structured, commonly used format'\n- right: Restriction\n  text: 'Restriction: Request that we restrict the processing of your information'\n- right: Objection\n  text: 'Objection: Object to our processing of your personal information'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/huddlekit/privacy/huddlekit-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Huddlekit's own page on 2026-11-09.
synthetic: false
tags:
- Visual Annotation
- Website Feedback
- Developer Tools
- AI Integration
---
