---
api_specs:
- filename: cleolm-com-tools-api-openapi.yml
  format: yaml
  label: CleoLM Tools API
  slug: cleolm-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleolm-com/openapi/cleolm-com-tools-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address - Required for account creation and authentication
  - category: contact
    text: Email address - Required for account creation and authentication
  - category: financial
    text: Billing history - Record of payments and invoices
  - category: device
    text: Device information - Device type, browser type, operating system
  - category: location
    text: IP address - Used for rate limiting and security
  - category: behavioral
    text: Feature usage - Which features you use and how often
  - category: communication
    text: Chat conversations - Questions you ask and AI responses about your content
  deletion:
    route: Request deletion of your account via contact email
    text: Delete your account - Request deletion of your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service
    text: Create and manage your account
  - purpose: Billing and payments
    text: Process subscription payments through Stripe
  - purpose: Service improvement
    text: Analyze usage patterns to improve features
  - purpose: Security and compliance
    text: Prevent fraud, abuse, and unauthorized access
  - purpose: Communication
    text: Respond to your inquiries and support requests
  residency:
  - region: United States
    text: CleoLM operates in the United States.
  retention:
  - period: Until you delete your account
    scope: Account information
    text: Account information Until you delete your account
  - period: Until you delete items or your account
    scope: Chat conversations
    text: Chat conversations Until you delete items or your account
  - period: 7 years
    scope: Payment records
    text: Payment records 7 years (legal/tax requirements)
  - period: 90 days
    scope: Technical/error logs
    text: Technical/error logs 90 days
  - period: 2 years
    scope: Agent/API usage and credit records
    text: Agent/API usage and credit records 2 years
  rights:
  - right: Access
    text: Access your data - View the personal information we hold about you
  - right: Delete account
    text: Delete your account - Request deletion of your account and associated data
  - right: Export data
    text: Export your data - Download your transcripts and processing history
  - right: Rectification
    text: Update your information - Correct inaccurate account information
  - right: Erasure (GDPR)
    text: Right to Erasure - Request deletion of your personal data ("right to be forgotten")
  - right: Portability (GDPR)
    text: Right to Data Portability - Receive your personal data in a structured, machine-readable format
  - right: Object (GDPR)
    text: Right to Object - Object to processing based on legitimate interests
  role:
    text: 'Data Controller: CleoLM'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal information to third parties for their marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CleoLM
provenance_date: '2026-11-09'
provider_name: CleoLM
provider_slug: cleolm-com
slug: cleolm-com-privacy-policy
source_date: '2026-11-09'
source_filename: cleolm-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cleolm.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CleoLM\naid: cleolm-com\nurl: https://cleolm.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller: CleoLM'\ndata_categories:\n- category: identifying\n  text: Email address - Required for account creation and authentication\n- category: contact\n  text: Email address - Required for account creation and authentication\n- category: financial\n  text: Billing history - Record of payments and invoices\n- category: device\n  text: Device information - Device type, browser type, operating system\n- category: location\n  text: IP address - Used for rate limiting and security\n\
  - category: behavioral\n  text: Feature usage - Which features you use and how often\n- category: communication\n  text: Chat conversations - Questions you ask and AI responses about your content\npurposes:\n- purpose: Providing the service\n  text: Create and manage your account\n- purpose: Billing and payments\n  text: Process subscription payments through Stripe\n- purpose: Service improvement\n  text: Analyze usage patterns to improve features\n- purpose: Security and compliance\n  text: Prevent fraud, abuse, and unauthorized access\n- purpose: Communication\n  text: Respond to your inquiries and support requests\nretention:\n- scope: Account information\n  period: Until you delete your account\n  text: Account information Until you delete your account\n- scope: Chat conversations\n  period: Until you delete items or your account\n  text: Chat conversations Until you delete items or your account\n- scope: Payment records\n  period: 7 years\n  text: Payment records 7 years (legal/tax\
  \ requirements)\n- scope: Technical/error logs\n  period: 90 days\n  text: Technical/error logs 90 days\n- scope: Agent/API usage and credit records\n  period: 2 years\n  text: Agent/API usage and credit records 2 years\nresidency:\n- region: United States\n  text: CleoLM operates in the United States.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of your account via contact email\n  text: Delete your account - Request deletion of your account and associated data\nrights:\n- right: Access\n  text: Access your data - View the personal information we hold about you\n- right: Delete account\n  text: Delete your account - Request deletion of your account and associated data\n- right: Export data\n  text: Export your data - Download your transcripts and processing history\n- right: Rectification\n  text:\
  \ Update your information - Correct inaccurate account information\n- right: Erasure (GDPR)\n  text: Right to Erasure - Request deletion of your personal data (\"right to be forgotten\")\n- right: Portability (GDPR)\n  text: Right to Data Portability - Receive your personal data in a structured, machine-readable format\n- right: Object (GDPR)\n  text: Right to Object - Object to processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal information to third parties for their marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/cleolm-com/privacy/cleolm-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from CleoLM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Transcription
- Podcasts
- YouTube
- Search
- MCP
- Video
---
