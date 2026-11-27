---
api_specs:
- filename: insforge-admin-api-openapi.yml
  format: yaml
  label: Insforge Admin API
  slug: insforge-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-admin-api-openapi.yml
- filename: insforge-channels-api-openapi.yml
  format: yaml
  label: Insforge Channels API
  slug: insforge-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-channels-api-openapi.yml
- filename: insforge-client-api-openapi.yml
  format: yaml
  label: Insforge Client API
  slug: insforge-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-client-api-openapi.yml
- filename: insforge-configuration-api-openapi.yml
  format: yaml
  label: Insforge Configuration API
  slug: insforge-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-configuration-api-openapi.yml
- filename: insforge-messages-api-openapi.yml
  format: yaml
  label: Insforge Messages API
  slug: insforge-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-messages-api-openapi.yml
- filename: insforge-payment-webhooks-api-openapi.yml
  format: yaml
  label: Insforge Payment Webhooks API
  slug: insforge-payment-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-payment-webhooks-api-openapi.yml
- filename: insforge-permissions-api-openapi.yml
  format: yaml
  label: Insforge Permissions API
  slug: insforge-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-permissions-api-openapi.yml
- filename: insforge-razorpay-payments-api-openapi.yml
  format: yaml
  label: Insforge Razorpay Payments API
  slug: insforge-razorpay-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-razorpay-payments-api-openapi.yml
- filename: insforge-s3-access-keys-api-openapi.yml
  format: yaml
  label: Insforge S3 Access Keys API
  slug: insforge-s3-access-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-s3-access-keys-api-openapi.yml
- filename: insforge-s3-protocol-api-openapi.yml
  format: yaml
  label: Insforge S3 Protocol API
  slug: insforge-s3-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-s3-protocol-api-openapi.yml
- filename: insforge-stripe-payments-api-openapi.yml
  format: yaml
  label: Insforge Stripe Payments API
  slug: insforge-stripe-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insforge/openapi/insforge-stripe-payments-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: including your name, email address, GitHub username, and organization details
  - category: financial
    text: We collect transactional information for subscriptions and usage-based billing.
  - category: device
    text: IP address, browser type, operating system, device identifiers, access times, pages viewed, links clicked, and referring URLs
  - category: location
    text: Mobile device identifiers and location information (where permitted)
  - category: communication
    text: When you communicate with us, we collect your contact information and communication contents
  - category: behavioral
    text: 'AI Agent Interaction Data: We collect metadata about AI agent interactions with our Service, including API call patterns, performance metrics, and error logs'
  deletion:
    route: Email support@insforge.dev with the subject line "Data Deletion Request"
    text: Send an email to support@insforge.dev with the subject line "Data Deletion Request."
  dpa:
    available: true
    text: We maintain data processing agreements with all sub-processors that include appropriate data transfer mechanisms and security obligations.
    url: null
  purposes:
  - purpose: administer account and provide services
    text: We use this information to administer your account, provide services, and communicate with you.
  - purpose: product analytics
    text: 'Analytics: Mixpanel and PostHog for product analytics and usage monitoring'
  - purpose: AI-powered features
    text: We may share data with AI service providers (such as OpenAI, Anthropic, or other AI model providers) solely to provide AI-powered features of our Service
  residency:
  - region: United States
    text: Our Services are primarily hosted in and provided from the United States.
  retention:
  - period: as long as your account is active
    scope: Account information
    text: We retain your account information for as long as your account is active.
  - period: 30 days
    scope: User Content and AI-Generated Data
    text: Upon account deletion, User Content is deleted within 30 days from our active systems.
  - period: 7 years
    scope: Payment records
    text: typically 7 years from the date of the transaction
  - period: 24 months
    scope: Usage and analytics data
    text: Retained in identifiable form for up to 24 months, after which it is aggregated or anonymized.
  - period: 12 months
    scope: AI agent interaction logs
    text: Retained for up to 12 months for service quality and debugging purposes
  rights:
  - right: access
    text: 'Right of Access: You may request confirmation of whether we process your personal information'
  - right: rectification
    text: 'Right to Rectification: You may request correction of inaccurate or incomplete personal information without undue delay.'
  - right: erasure
    text: 'Right to Erasure (Right to Delete): You may request that we delete your personal information where continued processing is no longer justified.'
  - right: portability
    text: 'Right to Data Portability: You may request to receive a copy of the personal information you have provided to us'
  - right: restriction
    text: 'Right to Restriction of Processing: You may request that we limit the processing of your personal information in certain circumstances'
  - right: object
    text: 'Right to Object: You may object to processing of your personal information based on our legitimate interests.'
  - right: withdraw consent
    text: 'Right to Withdraw Consent: Where we rely on your consent to process personal information, you may withdraw your consent at any time.'
  - right: complain
    text: 'Right to Lodge a Complaint: You have the right to lodge a complaint with your local data protection authority'
  role:
    text: We are the data controller of your personal information when we use it as described in this Privacy Notice
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): We use SCCs approved by the European Commission and the UK Information Commissioner''s Office'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Insforge
provenance_date: '2026-11-09'
provider_name: Insforge
provider_slug: insforge
slug: insforge-privacy-policy
source_date: '2026-11-09'
source_filename: insforge-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://insforge.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Insforge\naid: insforge\nurl: https://insforge.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the data controller of your personal information when we use it as described in this Privacy Notice\ndata_categories:\n- category: identifying\n  text: including your name, email address, GitHub username, and organization details\n- category: financial\n  text: We collect transactional information for subscriptions and usage-based billing.\n- category: device\n  text: IP address, browser type, operating system, device identifiers, access times, pages viewed, links clicked,\n    and referring\
  \ URLs\n- category: location\n  text: Mobile device identifiers and location information (where permitted)\n- category: communication\n  text: When you communicate with us, we collect your contact information and communication contents\n- category: behavioral\n  text: 'AI Agent Interaction Data: We collect metadata about AI agent interactions with our Service, including\n    API call patterns, performance metrics, and error logs'\npurposes:\n- purpose: administer account and provide services\n  text: We use this information to administer your account, provide services, and communicate with you.\n- purpose: product analytics\n  text: 'Analytics: Mixpanel and PostHog for product analytics and usage monitoring'\n- purpose: AI-powered features\n  text: We may share data with AI service providers (such as OpenAI, Anthropic, or other AI model providers) solely\n    to provide AI-powered features of our Service\nretention:\n- scope: Account information\n  period: as long as your account is active\n\
  \  text: We retain your account information for as long as your account is active.\n- scope: User Content and AI-Generated Data\n  period: 30 days\n  text: Upon account deletion, User Content is deleted within 30 days from our active systems.\n- scope: Payment records\n  period: 7 years\n  text: typically 7 years from the date of the transaction\n- scope: Usage and analytics data\n  period: 24 months\n  text: Retained in identifiable form for up to 24 months, after which it is aggregated or anonymized.\n- scope: AI agent interaction logs\n  period: 12 months\n  text: Retained for up to 12 months for service quality and debugging purposes\nresidency:\n- region: United States\n  text: Our Services are primarily hosted in and provided from the United States.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): We use SCCs approved by the European Commission and the UK Information\n    Commissioner''s Office'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ true\n  url: null\n  text: We maintain data processing agreements with all sub-processors that include appropriate data transfer mechanisms\n    and security obligations.\ndeletion:\n  route: Email support@insforge.dev with the subject line \"Data Deletion Request\"\n  text: Send an email to support@insforge.dev with the subject line \"Data Deletion Request.\"\nrights:\n- right: access\n  text: 'Right of Access: You may request confirmation of whether we process your personal information'\n- right: rectification\n  text: 'Right to Rectification: You may request correction of inaccurate or incomplete personal information without\n    undue delay.'\n- right: erasure\n  text: 'Right to Erasure (Right to Delete): You may request that we delete your personal information where continued\n    processing is no longer justified.'\n- right: portability\n  text: 'Right to Data Portability: You may request to receive a copy of the personal information you have provided\n    to us'\n- right: restriction\n\
  \  text: 'Right to Restriction of Processing: You may request that we limit the processing of your personal information\n    in certain circumstances'\n- right: object\n  text: 'Right to Object: You may object to processing of your personal information based on our legitimate interests.'\n- right: withdraw consent\n  text: 'Right to Withdraw Consent: Where we rely on your consent to process personal information, you may withdraw\n    your consent at any time.'\n- right: complain\n  text: 'Right to Lodge a Complaint: You have the right to lodge a complaint with your local data protection authority'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/insforge/privacy/insforge-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Insforge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Backend-as-a-Service
- Agent-Native
- Cloud Infrastructure
- Database
- Authentication
- Storage
- Serverless
- Edge Functions
- AI Gateway
- Payments
- Real-Time
- Open Source
- Y Combinator
---
