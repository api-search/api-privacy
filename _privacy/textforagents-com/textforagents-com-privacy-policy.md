---
api_specs:
- filename: textforagents-com-accounts-api-openapi.yml
  format: yaml
  label: textforagents-com Accounts API
  slug: textforagents-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-accounts-api-openapi.yml
- filename: textforagents-com-admin-api-openapi.yml
  format: yaml
  label: textforagents-com Admin API
  slug: textforagents-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-admin-api-openapi.yml
- filename: textforagents-com-auth-api-openapi.yml
  format: yaml
  label: textforagents-com Auth API
  slug: textforagents-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-auth-api-openapi.yml
- filename: textforagents-com-billing-api-openapi.yml
  format: yaml
  label: textforagents-com Billing API
  slug: textforagents-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-billing-api-openapi.yml
- filename: textforagents-com-health-api-openapi.yml
  format: yaml
  label: textforagents-com Health API
  slug: textforagents-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-health-api-openapi.yml
- filename: textforagents-com-legal-api-openapi.yml
  format: yaml
  label: textforagents-com Legal API
  slug: textforagents-com-legal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-legal-api-openapi.yml
- filename: textforagents-com-messages-api-openapi.yml
  format: yaml
  label: textforagents-com Messages API
  slug: textforagents-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-messages-api-openapi.yml
- filename: textforagents-com-support-api-openapi.yml
  format: yaml
  label: textforagents-com Support API
  slug: textforagents-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-support-api-openapi.yml
- filename: textforagents-com-wallet-creation-api-openapi.yml
  format: yaml
  label: textforagents-com Wallet Creation API
  slug: textforagents-com-wallet-creation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-wallet-creation-api-openapi.yml
- filename: textforagents-com-webhooks-api-openapi.yml
  format: yaml
  label: textforagents-com Webhooks API
  slug: textforagents-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-webhooks-api-openapi.yml
- filename: textforagents-com-x402-api-openapi.yml
  format: yaml
  label: textforagents-com X402 API
  slug: textforagents-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textforagents-com/openapi/textforagents-com-x402-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone numbers (account, provisioned, and recipient numbers), account IDs
  - category: contact
    text: Name, business (postal) address, telephone number
  - category: financial
    text: we never store full card numbers
  - category: location
    text: We do not collect precise geolocation from your device.
  - category: communication
    text: the contents of text messages
  - category: professional
    text: Legal entity name, business address, website — used for 10DLC brand registration
  - category: other
    text: MMS media attachments transmitted as message content — photographs, images, video, and audio files
  - category: other
    text: Tax ID (e.g., EIN) and similar government/registration identifiers collected for 10DLC brand registration
  deletion:
    route: email support@textforagents.com or account connection
    text: (1) Email support@textforagents.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: 'To operate the Service: provisioning numbers, registering brands and campaigns, delivering, queueing, and holding messages, enforcing opt-outs and abuse controls, billing, support, security, and legal compliance.'
  retention:
  - period: 90 days
    scope: contents of text messages and MMS media
    text: retained 90 days , then deleted.
  - period: 24 months
    scope: message metadata and network activity logs
    text: retained 24 months for billing disputes, carrier audits, debugging, and legal defense
  - period: null
    scope: account, payment and 10DLC registration records
    text: retained while the account is active and for 24 months after it closes
  - period: 24 months
    scope: support records
    text: retained 24 months
  rights:
  - right: know
    text: Right to know — request that we disclose the categories and specific pieces of personal information we collected about you
  - right: delete
    text: Right to delete — request deletion of personal information we collected from you, and direct our service providers to delete it, subject to legal exceptions.
  - right: correct
    text: Right to correct — request correction of inaccurate personal information.
  - right: limit sensitive personal information
    text: Right to limit use of sensitive personal information — direct us to limit use/disclosure of sensitive personal information to what is necessary to provide the Service
  role:
    text: For account/customer data , we are the business and you may exercise these rights directly against us as below.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information
  subprocessors:
    text: connectivity providers (currently Telnyx)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TextForAgents
provenance_date: '2026-11-10'
provider_name: TextForAgents
provider_slug: textforagents-com
slug: textforagents-com-privacy-policy
source_date: '2026-11-10'
source_filename: textforagents-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://textforagents.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TextForAgents\naid: textforagents-com\nurl: https://textforagents.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account/customer data , we are the business and you may exercise these rights directly against us as\n    below.\ndata_categories:\n- category: identifying\n  text: Name, email address, phone numbers (account, provisioned, and recipient numbers), account IDs\n- category: contact\n  text: Name, business (postal) address, telephone number\n- category: financial\n  text: we never store full card numbers\n- category: location\n  text: We do not collect precise geolocation\
  \ from your device.\n- category: communication\n  text: the contents of text messages\n- category: professional\n  text: Legal entity name, business address, website — used for 10DLC brand registration\n- category: other\n  text: MMS media attachments transmitted as message content — photographs, images, video, and audio files\n- category: other\n  text: Tax ID (e.g., EIN) and similar government/registration identifiers collected for 10DLC brand registration\npurposes:\n- purpose: operate the service\n  text: 'To operate the Service: provisioning numbers, registering brands and campaigns, delivering, queueing, and\n    holding messages, enforcing opt-outs and abuse controls, billing, support, security, and legal compliance.'\nretention:\n- scope: contents of text messages and MMS media\n  period: 90 days\n  text: retained 90 days , then deleted.\n- scope: message metadata and network activity logs\n  period: 24 months\n  text: retained 24 months for billing disputes, carrier audits, debugging,\
  \ and legal defense\n- scope: account, payment and 10DLC registration records\n  period: null\n  text: retained while the account is active and for 24 months after it closes\n- scope: support records\n  period: 24 months\n  text: retained 24 months\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: connectivity providers (currently Telnyx)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@textforagents.com or account connection\n  text: (1) Email support@textforagents.com.\nrights:\n- right: know\n  text: Right to know — request that we disclose the categories and specific pieces of personal information we collected\n    about you\n- right: delete\n  text: Right to delete — request deletion of personal information we collected from you, and direct our service\n    providers to delete it, subject to legal exceptions.\n- right: correct\n  text: Right to correct — request correction of inaccurate personal information.\n- right: limit sensitive\
  \ personal information\n  text: Right to limit use of sensitive personal information — direct us to limit use/disclosure of sensitive personal\n    information to what is necessary to provide the Service\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information\n"
source_yaml_url: https://artifacts.apis.io/textforagents-com/privacy/textforagents-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from TextForAgents's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Telephony
- SMS
- Agents
---
