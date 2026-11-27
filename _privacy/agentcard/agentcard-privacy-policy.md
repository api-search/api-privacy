---
api_specs:
- filename: agentcard-authentication-api-openapi.yml
  format: yaml
  label: Agentcard Authentication API
  slug: agentcard-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-authentication-api-openapi.yml
- filename: agentcard-connect-api-openapi.yml
  format: yaml
  label: Agentcard Connect API
  slug: agentcard-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-connect-api-openapi.yml
- filename: agentcard-identity-verification-api-openapi.yml
  format: yaml
  label: Agentcard Identity verification API
  slug: agentcard-identity-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-identity-verification-api-openapi.yml
- filename: agentcard-member-cards-api-openapi.yml
  format: yaml
  label: Agentcard Member cards API
  slug: agentcard-member-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-member-cards-api-openapi.yml
- filename: agentcard-purchase-api-openapi.yml
  format: yaml
  label: Agentcard Purchase API
  slug: agentcard-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcard/openapi/agentcard-purchase-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account information: name, email address, and phone number when you create an account.'
  - category: financial
    text: 'Payment information: wallet funding details processed through our payment providers'
  - category: financial
    text: 'Card usage data: card names, labels, funding amounts, and transaction history associated with your virtual cards'
  - category: identifying
    text: 'Log data: IP address, browser type, operating system, referring URLs, pages visited, and timestamps'
  - category: device
    text: 'Device information: device type, unique device identifiers, and mobile network information'
  - category: behavioral
    text: 'Usage data: how you interact with the Site and services, including API and MCP tool usage patterns, and recordings of your sessions on the Site and in our dashboard'
  - category: communication
    text: 'Support communications: messages you send through our support chat or email'
  deletion:
    route: Contact support email
    text: Contact us at support@agentcard.sh .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve the Site and services
  - purpose: Process transactions
    text: Process transactions and send related information
  - purpose: Fraud prevention
    text: Detect, investigate, and prevent fraudulent transactions
  - purpose: Legal compliance
    text: Comply with legal obligations
  retention:
  - period: null
    scope: Personal information
    text: We retain your personal information for as long as your account is active or as needed to provide services, comply with legal obligations, resolve disputes, and enforce our agreements.
  rights:
  - right: access, correct, delete, port
    text: Depending on your jurisdiction, you may have rights to access, correct, delete, or port your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to servers located outside your jurisdiction. By using the Site, you consent to the transfer of your information to the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentcard
provenance_date: '2026-11-09'
provider_name: Agentcard
provider_slug: agentcard
slug: agentcard-privacy-policy
source_date: '2026-11-09'
source_filename: agentcard-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentcard.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentcard\naid: agentcard\nurl: https://agentcard.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account information: name, email address, and phone number when you create an account.'\n- category: financial\n  text: 'Payment information: wallet funding details processed through our payment providers'\n- category: financial\n  text: 'Card usage data: card names, labels, funding amounts, and transaction history associated with your virtual\n    cards'\n- category: identifying\n  text: 'Log data: IP address, browser type, operating\
  \ system, referring URLs, pages visited, and timestamps'\n- category: device\n  text: 'Device information: device type, unique device identifiers, and mobile network information'\n- category: behavioral\n  text: 'Usage data: how you interact with the Site and services, including API and MCP tool usage patterns, and\n    recordings of your sessions on the Site and in our dashboard'\n- category: communication\n  text: 'Support communications: messages you send through our support chat or email'\npurposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve the Site and services\n- purpose: Process transactions\n  text: Process transactions and send related information\n- purpose: Fraud prevention\n  text: Detect, investigate, and prevent fraudulent transactions\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Personal information\n  period: null\n  text: We retain your personal information for as long as your account is\
  \ active or as needed to provide services,\n    comply with legal obligations, resolve disputes, and enforce our agreements.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to servers located outside your jurisdiction. By using the Site, you\n    consent to the transfer of your information to the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support email\n  text: Contact us at support@agentcard.sh .\nrights:\n- right: access, correct, delete, port\n  text: Depending on your jurisdiction, you may have rights to access, correct, delete, or port your data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/agentcard/privacy/agentcard-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Agentcard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Virtual Cards
- Card Issuing
- AI Agents
- Agentic Commerce
- MCP
- Fintech
- Wallets
- Visa
- A2A
---
