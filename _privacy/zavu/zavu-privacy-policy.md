---
api_specs:
- filename: zavu-10dlc-api-openapi.yml
  format: yaml
  label: Zavu 10DLC API
  slug: zavu-10dlc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-10dlc-api-openapi.yml
- filename: zavu-account-api-openapi.yml
  format: yaml
  label: Zavu Account API
  slug: zavu-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-account-api-openapi.yml
- filename: zavu-agent-flows-api-openapi.yml
  format: yaml
  label: Zavu Agent Flows API
  slug: zavu-agent-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-agent-flows-api-openapi.yml
- filename: zavu-agent-knowledge-bases-api-openapi.yml
  format: yaml
  label: Zavu Agent Knowledge Bases API
  slug: zavu-agent-knowledge-bases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-agent-knowledge-bases-api-openapi.yml
- filename: zavu-agent-tools-api-openapi.yml
  format: yaml
  label: Zavu Agent Tools API
  slug: zavu-agent-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-agent-tools-api-openapi.yml
- filename: zavu-agents-api-openapi.yml
  format: yaml
  label: Zavu Agents API
  slug: zavu-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-agents-api-openapi.yml
- filename: zavu-balance-api-openapi.yml
  format: yaml
  label: Zavu Balance API
  slug: zavu-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-balance-api-openapi.yml
- filename: zavu-broadcasts-api-openapi.yml
  format: yaml
  label: Zavu Broadcasts API
  slug: zavu-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-broadcasts-api-openapi.yml
- filename: zavu-contacts-api-openapi.yml
  format: yaml
  label: Zavu Contacts API
  slug: zavu-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-contacts-api-openapi.yml
- filename: zavu-functions-api-openapi.yml
  format: yaml
  label: Zavu Functions API
  slug: zavu-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-functions-api-openapi.yml
- filename: zavu-introspect-api-openapi.yml
  format: yaml
  label: Zavu Introspect API
  slug: zavu-introspect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-introspect-api-openapi.yml
- filename: zavu-invitations-api-openapi.yml
  format: yaml
  label: Zavu Invitations API
  slug: zavu-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-invitations-api-openapi.yml
- filename: zavu-messages-api-openapi.yml
  format: yaml
  label: Zavu Messages API
  slug: zavu-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-messages-api-openapi.yml
- filename: zavu-phone-numbers-api-openapi.yml
  format: yaml
  label: Zavu Phone Numbers API
  slug: zavu-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-phone-numbers-api-openapi.yml
- filename: zavu-regulatory-api-openapi.yml
  format: yaml
  label: Zavu Regulatory API
  slug: zavu-regulatory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-regulatory-api-openapi.yml
- filename: zavu-senders-api-openapi.yml
  format: yaml
  label: Zavu Senders API
  slug: zavu-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-senders-api-openapi.yml
- filename: zavu-templates-api-openapi.yml
  format: yaml
  label: Zavu Templates API
  slug: zavu-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-templates-api-openapi.yml
- filename: zavu-url-verification-api-openapi.yml
  format: yaml
  label: Zavu URL Verification API
  slug: zavu-url-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-url-verification-api-openapi.yml
- filename: zavu-whatsapp-alternative-api-openapi.yml
  format: yaml
  label: Zavu WhatsApp Alternative API
  slug: zavu-whatsapp-alternative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-whatsapp-alternative-api-openapi.yml
- filename: zavu-whatsapp-sync-api-openapi.yml
  format: yaml
  label: Zavu WhatsApp Sync API
  slug: zavu-whatsapp-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-whatsapp-sync-api-openapi.yml
- filename: zavu-subaccounts-api-openapi.yml
  format: yaml
  label: Zavu Subaccounts API
  slug: zavu-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zavu/openapi/zavu-subaccounts-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and billing information (via Clerk and Stripe)
  - category: communication
    text: Messages sent through the platform
  - category: device
    text: Device information and IP addresses
  - category: behavioral
    text: Webhooks, logs, and usage metadata
  - category: other
    text: Communication preferences and settings
  deletion:
    route: Deleting a contact removes the contact and its channels
    text: Deleting a contact removes the contact and its channels; its conversations and messages are deleted when their retention period ends.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver and maintain services
    text: To deliver and maintain the Services
  - purpose: analytics and service improvement
    text: For analytics and service improvement
  - purpose: billing and payment processing
    text: For billing and payment processing
  - purpose: legal compliance and fraud prevention
    text: For legal compliance and fraud prevention
  - purpose: account communication
    text: To communicate with you about your account
  retention:
  - period: 90 days
    scope: message content
    text: 'Message content: 90 days (default, configurable by Customer)'
  - period: null
    scope: metadata
    text: 'Metadata: Retained for billing, compliance, and operational purposes'
  rights:
  - right: access
    text: 'Access: Request access to your personal data'
  - right: rectification
    text: 'Rectification: Request correction of inaccurate data'
  - right: erasure
    text: 'Erasure: Request deletion of your personal data'
  - right: restriction
    text: 'Restriction: Request restriction of processing'
  - right: portability
    text: 'Portability: Request transfer of your data'
  - right: objection
    text: 'Objection: Object to processing of your data'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Clerk: Authentication and user management'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zavu
provenance_date: '2026-11-10'
provider_name: Zavu
provider_slug: zavu
slug: zavu-privacy-policy
source_date: '2026-11-10'
source_filename: zavu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zavu.dev/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zavu\naid: zavu\nurl: https://www.zavu.dev/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and billing information (via Clerk and Stripe)\n- category: communication\n  text: Messages sent through the platform\n- category: device\n  text: Device information and IP addresses\n- category: behavioral\n  text: Webhooks, logs, and usage metadata\n- category: other\n  text: Communication preferences and settings\npurposes:\n- purpose: deliver and maintain services\n  text: To deliver and maintain the Services\n- purpose: analytics\
  \ and service improvement\n  text: For analytics and service improvement\n- purpose: billing and payment processing\n  text: For billing and payment processing\n- purpose: legal compliance and fraud prevention\n  text: For legal compliance and fraud prevention\n- purpose: account communication\n  text: To communicate with you about your account\nretention:\n- scope: message content\n  period: 90 days\n  text: 'Message content: 90 days (default, configurable by Customer)'\n- scope: metadata\n  period: null\n  text: 'Metadata: Retained for billing, compliance, and operational purposes'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: 'Clerk: Authentication and user management'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deleting a contact removes the contact and its channels\n  text: Deleting a contact removes the contact and its channels; its conversations\
  \ and messages are deleted when\n    their retention period ends.\nrights:\n- right: access\n  text: 'Access: Request access to your personal data'\n- right: rectification\n  text: 'Rectification: Request correction of inaccurate data'\n- right: erasure\n  text: 'Erasure: Request deletion of your personal data'\n- right: restriction\n  text: 'Restriction: Request restriction of processing'\n- right: portability\n  text: 'Portability: Request transfer of your data'\n- right: objection\n  text: 'Objection: Object to processing of your data'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zavu/privacy/zavu-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 21 quoted statements, read from Zavu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Messaging
- SMS
- WhatsApp
- Email
- Voice
- Communications
- CPaaS
- Webhook
- AI Agents
---
