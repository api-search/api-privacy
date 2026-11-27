---
api_specs:
- filename: clawvisor-auth-api-openapi.yml
  format: yaml
  label: Clawvisor Auth API
  slug: clawvisor-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-auth-api-openapi.yml
- filename: clawvisor-catalog-api-openapi.yml
  format: yaml
  label: Clawvisor Catalog API
  slug: clawvisor-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-catalog-api-openapi.yml
- filename: clawvisor-gateway-api-openapi.yml
  format: yaml
  label: Clawvisor Gateway API
  slug: clawvisor-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-gateway-api-openapi.yml
- filename: clawvisor-tasks-api-openapi.yml
  format: yaml
  label: Clawvisor Tasks API
  slug: clawvisor-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-tasks-api-openapi.yml
- filename: clawvisor-tokens-api-openapi.yml
  format: yaml
  label: Clawvisor Tokens API
  slug: clawvisor-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawvisor/openapi/clawvisor-tokens-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address and bcrypt-hashed password for authentication.
  - category: behavioral
    text: 'Audit logs: Every gateway request is logged with the service, action, sanitized parameters, decision, and outcome.'
  - category: device
    text: 'Connection metadata: Daemon ID, Ed25519 public key, IP address, and connection/disconnection timestamps.'
  - category: device
    text: 'Device tokens: Required to deliver notifications to your mobile device.'
  deletion:
    route: email support@clawvisor.com
    text: You may request deletion at any time by contacting support@clawvisor.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and maintain the service
    text: Operate and maintain the service
  - purpose: Execute agent requests against third-party APIs
    text: Execute agent requests against third-party APIs on your behalf
  - purpose: Enforce authorization policies
    text: Enforce authorization policies (restrictions, task scopes, and approvals)
  - purpose: Generate audit logs
    text: Generate audit logs for your review
  residency:
  - region: United States
    text: The cloud service infrastructure is hosted in the United States on Google Cloud Platform.
  retention:
  - period: within thirty (30) days
    scope: Cloud account data after account deletion
    text: Upon account deletion, all associated data — including credentials, audit logs, agent configurations, and account information — is permanently purged within thirty (30) days, except where retention is required by applicable law.
  - period: lifetime of your account
    scope: Cloud audit logs
    text: Audit logs on the cloud service are retained for the lifetime of your account.
  - period: while the relay connection or push subscription is active
    scope: Relay connection metadata and device tokens
    text: Connection metadata and device tokens are retained while the relay connection or push subscription is active and are deleted upon de-registration or account removal.
  rights:
  - right: access, correction, deletion
    text: For the cloud service, you may request access to, correction of, or deletion of your personal data by emailing support@clawvisor.com.
  - right: GDPR rights for EEA/UK users
    text: including the right to access, rectify, erase, restrict processing, data portability, and object to processing of your personal data.
  role:
    text: Clawvisor, Inc., a Delaware corporation ("Clawvisor," "we," "us," or "our"), is the data controller for information collected through the cloud service and the clawvisor.com website.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it for advertising.
  subprocessors:
    text: 'The cloud service uses the following sub-processors to deliver the Service:'
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers of personal data from the EEA/UK to the United States are governed by Google's Data Processing Addendum, which incorporates Standard Contractual Clauses (SCCs) approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clawvisor
provenance_date: '2026-11-09'
provider_name: Clawvisor
provider_slug: clawvisor
slug: clawvisor-privacy-policy
source_date: '2026-11-09'
source_filename: clawvisor-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clawvisor.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clawvisor\naid: clawvisor\nurl: https://clawvisor.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Clawvisor, Inc., a Delaware corporation (\"Clawvisor,\" \"we,\" \"us,\" or \"our\"), is the data controller for\n    information collected through the cloud service and the clawvisor.com website.\ndata_categories:\n- category: contact\n  text: Email address and bcrypt-hashed password for authentication.\n- category: behavioral\n  text: 'Audit logs: Every gateway request is logged with the service, action, sanitized parameters, decision, and\n    outcome.'\n- category: device\n  text:\
  \ 'Connection metadata: Daemon ID, Ed25519 public key, IP address, and connection/disconnection timestamps.'\n- category: device\n  text: 'Device tokens: Required to deliver notifications to your mobile device.'\npurposes:\n- purpose: Operate and maintain the service\n  text: Operate and maintain the service\n- purpose: Execute agent requests against third-party APIs\n  text: Execute agent requests against third-party APIs on your behalf\n- purpose: Enforce authorization policies\n  text: Enforce authorization policies (restrictions, task scopes, and approvals)\n- purpose: Generate audit logs\n  text: Generate audit logs for your review\nretention:\n- scope: Cloud account data after account deletion\n  period: within thirty (30) days\n  text: Upon account deletion, all associated data — including credentials, audit logs, agent configurations, and\n    account information — is permanently purged within thirty (30) days, except where retention is required by applicable\n    law.\n- scope:\
  \ Cloud audit logs\n  period: lifetime of your account\n  text: Audit logs on the cloud service are retained for the lifetime of your account.\n- scope: Relay connection metadata and device tokens\n  period: while the relay connection or push subscription is active\n  text: Connection metadata and device tokens are retained while the relay connection or push subscription is active\n    and are deleted upon de-registration or account removal.\nresidency:\n- region: United States\n  text: The cloud service infrastructure is hosted in the United States on Google Cloud Platform.\ntransfers:\n- mechanism: SCC\n  text: Transfers of personal data from the EEA/UK to the United States are governed by Google's Data Processing\n    Addendum, which incorporates Standard Contractual Clauses (SCCs) approved by the European Commission.\nsubprocessors:\n  url: null\n  text: 'The cloud service uses the following sub-processors to deliver the Service:'\ndpa:\n  available: null\n  url: null\n  text: null\n\
  deletion:\n  route: email support@clawvisor.com\n  text: You may request deletion at any time by contacting support@clawvisor.com.\nrights:\n- right: access, correction, deletion\n  text: For the cloud service, you may request access to, correction of, or deletion of your personal data by emailing\n    support@clawvisor.com.\n- right: GDPR rights for EEA/UK users\n  text: including the right to access, rectify, erase, restrict processing, data portability, and object to processing\n    of your personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/clawvisor/privacy/clawvisor-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Clawvisor's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Authorization
- Security
- Identity
- Access Control
- MCP
- Credential Management
- Governance
- Developer Tools
---
