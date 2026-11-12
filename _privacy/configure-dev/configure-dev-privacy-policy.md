---
api_specs:
- filename: configure-dev-auth-api-openapi.yml
  format: yaml
  label: Configure Auth API
  slug: configure-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-auth-api-openapi.yml
- filename: configure-dev-connectors-api-openapi.yml
  format: yaml
  label: Configure Connectors API
  slug: configure-dev-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-connectors-api-openapi.yml
- filename: configure-dev-files-api-openapi.yml
  format: yaml
  label: Configure Files API
  slug: configure-dev-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-files-api-openapi.yml
- filename: configure-dev-import-api-openapi.yml
  format: yaml
  label: Configure Import API
  slug: configure-dev-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-import-api-openapi.yml
- filename: configure-dev-profile-api-openapi.yml
  format: yaml
  label: Configure Profile API
  slug: configure-dev-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-profile-api-openapi.yml
- filename: configure-dev-web-api-openapi.yml
  format: yaml
  label: Configure Web API
  slug: configure-dev-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-web-api-openapi.yml
- filename: configure-dev-webhooks-api-openapi.yml
  format: yaml
  label: Configure Webhooks API
  slug: configure-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect and store identity information (such as name, email, bio, occupation, interests, and location)
  - category: identifying
    text: Your phone number is stored as an irreversible cryptographic hash, together with its last four digits so that you can recognise your account.
  - category: communication
    text: Gmail — account information, senders and recipients, subjects, dates, labels, and selected message snippets or bodies.
  - category: device
    text: we also record your browser's user-agent string and a hashed form of it, together with a hashed form of your IP address.
  - category: financial
    text: For developers using the Configure API or SDK, we collect API keys, agent configurations, and usage metrics.
  deletion:
    route: Deletion controls in the service or by contacting privacy@configure.dev
    text: Configure provides deletion controls for stored profile information and chat history; you can also contact us to request erasure
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: identity verification
    text: Verify your identity via phone OTP
  - purpose: profile building
    text: Build and maintain your persistent user profile across agents and applications
  - purpose: AI extraction
    text: Use AI to extract facts, preferences, and context from conversations, authorized connected tools, and what you and your assistants explicitly send
  - purpose: security
    text: We use these records only to detect suspicious sign-in activity on your account.
  residency:
  - region: United States
    text: Your data is processed and stored in the US.
  retention:
  - period: null
    scope: profile data
    text: Profile data is retained for as long as your account exists, or until you request deletion
  - period: up to 90 days
    scope: server logs
    text: Server logs are retained for up to 90 days
  rights:
  - right: Access
    text: Access your personal data and obtain a copy of the information we hold about you
  - right: Rectify
    text: Rectify inaccurate or incomplete data
  - right: Erase
    text: Erase your data ("right to be forgotten")
  - right: Port
    text: Port your data to another service in a structured, machine-readable format
  - right: Restrict processing
    text: Restrict processing of your data in certain circumstances
  - right: Object
    text: Object to processing based on legitimate interest
  - right: Withdraw consent
    text: Withdraw consent at any time, without affecting the lawfulness of processing carried out before withdrawal
  role:
    text: 'When you integrate the Configure SDK or API into your application: You act as a data controller for your end users. Configure processes data on your behalf as a data processor .'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: You must not sell, license, sublicense, rent, lease, or trade user profile data.
  subprocessors:
    text: We use third-party service providers for identity verification, AI model inference, application hosting, OAuth integration management, caching, and static site delivery.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses (SCCs) approved by the European Commission to provide adequate safeguards for international data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Configure
provenance_date: '2026-11-09'
provider_name: Configure
provider_slug: configure-dev
slug: configure-dev-privacy-policy
source_date: '2026-11-09'
source_filename: configure-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://configure.dev/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Configure\naid: configure-dev\nurl: https://configure.dev/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'When you integrate the Configure SDK or API into your application: You act as a data controller for your\n    end users. Configure processes data on your behalf as a data processor .'\ndata_categories:\n- category: contact\n  text: we collect and store identity information (such as name, email, bio, occupation, interests, and location)\n- category: identifying\n  text: Your phone number is stored as an irreversible cryptographic hash, together with its last four digits so\n    that\
  \ you can recognise your account.\n- category: communication\n  text: Gmail — account information, senders and recipients, subjects, dates, labels, and selected message snippets\n    or bodies.\n- category: device\n  text: we also record your browser's user-agent string and a hashed form of it, together with a hashed form of\n    your IP address.\n- category: financial\n  text: For developers using the Configure API or SDK, we collect API keys, agent configurations, and usage metrics.\npurposes:\n- purpose: identity verification\n  text: Verify your identity via phone OTP\n- purpose: profile building\n  text: Build and maintain your persistent user profile across agents and applications\n- purpose: AI extraction\n  text: Use AI to extract facts, preferences, and context from conversations, authorized connected tools, and what\n    you and your assistants explicitly send\n- purpose: security\n  text: We use these records only to detect suspicious sign-in activity on your account.\nretention:\n\
  - scope: profile data\n  period: null\n  text: Profile data is retained for as long as your account exists, or until you request deletion\n- scope: server logs\n  period: up to 90 days\n  text: Server logs are retained for up to 90 days\nresidency:\n- region: United States\n  text: Your data is processed and stored in the US.\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses (SCCs) approved by the European Commission to provide adequate safeguards\n    for international data transfers.\nsubprocessors:\n  url: null\n  text: We use third-party service providers for identity verification, AI model inference, application hosting,\n    OAuth integration management, caching, and static site delivery.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deletion controls in the service or by contacting privacy@configure.dev\n  text: Configure provides deletion controls for stored profile information and chat history; you can also contact\n    us\
  \ to request erasure\nrights:\n- right: Access\n  text: Access your personal data and obtain a copy of the information we hold about you\n- right: Rectify\n  text: Rectify inaccurate or incomplete data\n- right: Erase\n  text: Erase your data (\"right to be forgotten\")\n- right: Port\n  text: Port your data to another service in a structured, machine-readable format\n- right: Restrict processing\n  text: Restrict processing of your data in certain circumstances\n- right: Object\n  text: Object to processing based on legitimate interest\n- right: Withdraw consent\n  text: Withdraw consent at any time, without affecting the lawfulness of processing carried out before withdrawal\nsale_or_sharing:\n  stance: prohibited\n  text: You must not sell, license, sublicense, rent, lease, or trade user profile data.\n"
source_yaml_url: https://artifacts.apis.io/configure-dev/privacy/configure-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Configure's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Memory
- Personalization
- User Context
- MCP
---
