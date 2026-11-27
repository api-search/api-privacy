---
api_specs:
- filename: deployxa-deployments-api-openapi.yml
  format: yaml
  label: Deployxa Deployments API
  slug: deployxa-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deployxa/openapi/deployxa-deployments-api-openapi.yml
- filename: deployxa-projects-api-openapi.yml
  format: yaml
  label: Deployxa Projects API
  slug: deployxa-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deployxa/openapi/deployxa-projects-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address and password (stored as a one-way hash by our authentication provider, never in plain text).
  - category: financial
    text: Your plan, subscription status, invoices, credit balance, top-ups and payment history.
  - category: location
    text: Billing name, billing address and tax identifiers where you provide them.
  - category: device
    text: Our own server logs for the dashboard and API, which record IP address, user agent, timestamps and request metadata.
  - category: behavioral
    text: product usage events tied to a random identifier
  - category: communication
    text: Messages you send to support, the content of tickets, and records of the transactional emails we send you
  deletion:
    route: Request deletion yourself under Settings, Privacy, or email [email protected]
    text: You can export your account data and request deletion yourself under Settings, Privacy, or email [email protected] .
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide the service
    text: create and secure your account, build and run your deployments, route domains and issue TLS certificates.
  - purpose: Billing
    text: process subscriptions, credit top-ups and invoices, and prevent payment fraud.
  - purpose: Security and abuse prevention
    text: detect unauthorized access, enforce the Acceptable Use Policy and investigate incidents.
  - purpose: Improve the product
    text: understand which features are used, with consent where cookies or similar technologies are involved.
  retention:
  - period: for as long as your account is open
    scope: Account and workspace data
    text: 'Account and workspace data: for as long as your account is open, then deleted after you close it, except for what we must keep by law.'
  - period: 30 days by default
    scope: Deployment and container logs
    text: 'Deployment and container logs: 30 days by default; configurable on Enterprise plans.'
  - period: 90 days
    scope: Raw analytics events
    text: 'Raw analytics events: 90 days, after which only aggregated figures are kept.'
  - period: 12 months
    scope: Cookie choice
    text: 'Cookie choice: 12 months, after which we ask again.'
  rights:
  - right: access, correct, delete or export
    text: you may have the right to access, correct, delete or export your personal data
  - right: restrict or object to processing
    text: to restrict or object to processing, and to withdraw consent
  - right: California right to know and delete
    text: California residents have the right to know, delete and correct personal information
  role:
    text: For personal data about our own customers and website visitors (for example your account and billing details), Deployxa is the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data and we do not share it for cross-context behavioural advertising.
  subprocessors:
    text: The current list is maintained in the Data Processing Agreement .
    url: null
  transfers:
  - mechanism: SCC
    text: we use an approved transfer mechanism, such as the European Commission’s Standard Contractual Clauses (and the UK Addendum), or rely on an adequacy decision.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Deployxa
provenance_date: '2026-11-09'
provider_name: Deployxa
provider_slug: deployxa
slug: deployxa-privacy-policy
source_date: '2026-11-09'
source_filename: deployxa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://deployxa.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Deployxa\naid: deployxa\nurl: https://deployxa.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For personal data about our own customers and website visitors (for example your account and billing details),\n    Deployxa is the controller.\ndata_categories:\n- category: identifying\n  text: Your name, email address and password (stored as a one-way hash by our authentication provider, never in\n    plain text).\n- category: financial\n  text: Your plan, subscription status, invoices, credit balance, top-ups and payment history.\n- category: location\n  text: Billing name, billing address\
  \ and tax identifiers where you provide them.\n- category: device\n  text: Our own server logs for the dashboard and API, which record IP address, user agent, timestamps and request\n    metadata.\n- category: behavioral\n  text: product usage events tied to a random identifier\n- category: communication\n  text: Messages you send to support, the content of tickets, and records of the transactional emails we send you\npurposes:\n- purpose: Provide the service\n  text: create and secure your account, build and run your deployments, route domains and issue TLS certificates.\n- purpose: Billing\n  text: process subscriptions, credit top-ups and invoices, and prevent payment fraud.\n- purpose: Security and abuse prevention\n  text: detect unauthorized access, enforce the Acceptable Use Policy and investigate incidents.\n- purpose: Improve the product\n  text: understand which features are used, with consent where cookies or similar technologies are involved.\nretention:\n- scope: Account and\
  \ workspace data\n  period: for as long as your account is open\n  text: 'Account and workspace data: for as long as your account is open, then deleted after you close it, except\n    for what we must keep by law.'\n- scope: Deployment and container logs\n  period: 30 days by default\n  text: 'Deployment and container logs: 30 days by default; configurable on Enterprise plans.'\n- scope: Raw analytics events\n  period: 90 days\n  text: 'Raw analytics events: 90 days, after which only aggregated figures are kept.'\n- scope: Cookie choice\n  period: 12 months\n  text: 'Cookie choice: 12 months, after which we ask again.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we use an approved transfer mechanism, such as the European Commission’s Standard Contractual Clauses (and\n    the UK Addendum), or rely on an adequacy decision.\nsubprocessors:\n  url: null\n  text: The current list is maintained in the Data Processing Agreement .\ndpa:\n  available: true\n  url: null\n  text: Data\
  \ Processing Agreement\ndeletion:\n  route: Request deletion yourself under Settings, Privacy, or email [email protected]\n  text: You can export your account data and request deletion yourself under Settings, Privacy, or email [email\n    protected] .\nrights:\n- right: access, correct, delete or export\n  text: you may have the right to access, correct, delete or export your personal data\n- right: restrict or object to processing\n  text: to restrict or object to processing, and to withdraw consent\n- right: California right to know and delete\n  text: California residents have the right to know, delete and correct personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data and we do not share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/deployxa/privacy/deployxa-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Deployxa's own page on 2026-11-09.
synthetic: false
tags:
- Platform-as-a-Service
- Cloud Deployment
- DevOps
- CI/CD
- containers-docker
- edge-hosting
- Managed Database
- AIOps
- Developer Tools
- A2A
---
