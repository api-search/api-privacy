---
api_specs:
- filename: markifact-com-connections-api-openapi.yml
  format: yaml
  label: markifact-com Connections API
  slug: markifact-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markifact-com/openapi/markifact-com-connections-api-openapi.yml
- filename: markifact-com-credits-api-openapi.yml
  format: yaml
  label: markifact-com Credits API
  slug: markifact-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markifact-com/openapi/markifact-com-credits-api-openapi.yml
- filename: markifact-com-logs-api-openapi.yml
  format: yaml
  label: markifact-com Logs API
  slug: markifact-com-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markifact-com/openapi/markifact-com-logs-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create a Markifact account, we collect your name, email address, and profile photo URL (if available from your authentication provider).
  - category: financial
    text: If you choose to subscribe to our paid plans, we collect billing information such as your address.
  - category: behavioral
    text: Our servers automatically collect certain information including IP addresses, browser types, Internet Service Provider (ISP), timestamps, page references/exit pages, and number of clicks.
  - category: device
    text: This includes log data, device information, and other data related to your activities within our Service.
  deletion:
    route: Self-service deletion from account Settings, or email contact@markifact.com with subject 'Data Deletion Request'
    text: You can delete your Markifact account and all associated data yourself at any time from your account Settings, as long as you do not have an active subscription.
  dpa:
    available: true
    text: Our Data Processing Agreement (DPA) applies automatically to every Markifact customer and is incorporated into these terms by reference.
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: We use your information to deliver the services you request, maintain your Markifact account, and continuously enhance your experience with our platform.
  - purpose: Analytics and monitoring
    text: We utilize analytics tools to understand how users interact with our platform, track service performance, and make data-driven improvements to enhance your experience.
  - purpose: Security and compliance
    text: We process your information to protect against fraudulent activities, maintain platform security, comply with legal obligations, and prevent unauthorized access to your account and data.
  residency:
  - region: EU
    text: Markifact's core application infrastructure and production database are configured in EU regions where applicable.
  retention:
  - period: 7-30 days
    scope: Execution logs
    text: These are available in your account for 7-30 days depending on your subscription plan.
  - period: up to 90 days
    scope: Expired execution logs for security
    text: including expired execution logs kept for up to 90 days for security and incident investigation before permanent deletion.
  - period: typically within 30 days
    scope: Data deletion requests
    text: we will delete or anonymize your data within a reasonable timeframe (typically within 30 days).
  rights:
  - right: Access
    text: 'Right to Access : Request a copy of the personal data we hold about you'
  - right: Rectification
    text: 'Right to Rectification : Request correction of inaccurate or incomplete data'
  - right: Deletion
    text: 'Right to Deletion : Request deletion of your personal data'
  - right: Portability
    text: 'Right to Data Portability : Request an export of your data in a portable format'
  - right: Object
    text: 'Right to Object : Object to certain types of processing'
  - right: Restrict processing
    text: 'Right to Restrict Processing : Request that we limit how we use your data'
  - right: Opt-out of sale (CCPA)
    text: 'Right to Opt-Out of Sale : We do not sell your personal information as defined under CCPA'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Markifact does not sell, rent, or trade your personal information to third parties for monetary or other valuable consideration.
  subprocessors:
    text: Some subprocessors, including providers for application hosting, email delivery, payments, analytics, AI services, and support infrastructure, may process limited data outside the EU under appropriate safeguards, as described in our DPA and Subprocessor list.
    url: null
  transfers:
  - mechanism: SCC
    text: For Customer Personal Data originating from the EEA, UK, or Switzerland, Markifact relies on applicable transfer mechanisms, including the EU Standard Contractual Clauses and any required UK or Swiss transfer addenda where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: markifact-com
provenance_date: '2026-11-10'
provider_name: markifact-com
provider_slug: markifact-com
slug: markifact-com-privacy-policy
source_date: '2026-11-10'
source_filename: markifact-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.markifact.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: markifact-com\naid: markifact-com\nurl: https://www.markifact.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create a Markifact account, we collect your name, email address, and profile photo URL (if available\n    from your authentication provider).\n- category: financial\n  text: If you choose to subscribe to our paid plans, we collect billing information such as your address.\n- category: behavioral\n  text: Our servers automatically collect certain information including IP addresses, browser types, Internet\
  \ Service\n    Provider (ISP), timestamps, page references/exit pages, and number of clicks.\n- category: device\n  text: This includes log data, device information, and other data related to your activities within our Service.\npurposes:\n- purpose: Provide and improve the Service\n  text: We use your information to deliver the services you request, maintain your Markifact account, and continuously\n    enhance your experience with our platform.\n- purpose: Analytics and monitoring\n  text: We utilize analytics tools to understand how users interact with our platform, track service performance,\n    and make data-driven improvements to enhance your experience.\n- purpose: Security and compliance\n  text: We process your information to protect against fraudulent activities, maintain platform security, comply\n    with legal obligations, and prevent unauthorized access to your account and data.\nretention:\n- scope: Execution logs\n  period: 7-30 days\n  text: These are available in your\
  \ account for 7-30 days depending on your subscription plan.\n- scope: Expired execution logs for security\n  period: up to 90 days\n  text: including expired execution logs kept for up to 90 days for security and incident investigation before permanent\n    deletion.\n- scope: Data deletion requests\n  period: typically within 30 days\n  text: we will delete or anonymize your data within a reasonable timeframe (typically within 30 days).\nresidency:\n- region: EU\n  text: Markifact's core application infrastructure and production database are configured in EU regions where applicable.\ntransfers:\n- mechanism: SCC\n  text: For Customer Personal Data originating from the EEA, UK, or Switzerland, Markifact relies on applicable\n    transfer mechanisms, including the EU Standard Contractual Clauses and any required UK or Swiss transfer addenda\n    where applicable.\nsubprocessors:\n  url: null\n  text: Some subprocessors, including providers for application hosting, email delivery, payments,\
  \ analytics, AI\n    services, and support infrastructure, may process limited data outside the EU under appropriate safeguards,\n    as described in our DPA and Subprocessor list.\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing Agreement (DPA) applies automatically to every Markifact customer and is incorporated\n    into these terms by reference.\ndeletion:\n  route: Self-service deletion from account Settings, or email contact@markifact.com with subject 'Data Deletion\n    Request'\n  text: You can delete your Markifact account and all associated data yourself at any time from your account Settings,\n    as long as you do not have an active subscription.\nrights:\n- right: Access\n  text: 'Right to Access : Request a copy of the personal data we hold about you'\n- right: Rectification\n  text: 'Right to Rectification : Request correction of inaccurate or incomplete data'\n- right: Deletion\n  text: 'Right to Deletion : Request deletion of your personal data'\n- right:\
  \ Portability\n  text: 'Right to Data Portability : Request an export of your data in a portable format'\n- right: Object\n  text: 'Right to Object : Object to certain types of processing'\n- right: Restrict processing\n  text: 'Right to Restrict Processing : Request that we limit how we use your data'\n- right: Opt-out of sale (CCPA)\n  text: 'Right to Opt-Out of Sale : We do not sell your personal information as defined under CCPA'\nsale_or_sharing:\n  stance: prohibited\n  text: Markifact does not sell, rent, or trade your personal information to third parties for monetary or other\n    valuable consideration.\n"
source_yaml_url: https://artifacts.apis.io/markifact-com/privacy/markifact-com-privacy-policy.yml
stated_fields:
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
summary_line: 23 quoted statements, read from markifact-com's own page on 2026-11-10.
synthetic: false
tags:
- AI Marketing Automation
- Ad Management
- Reporting
- Workflow Automation
- Marketing Operations
- Data Integration
---
