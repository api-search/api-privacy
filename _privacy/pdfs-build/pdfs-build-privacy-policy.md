---
api_specs:
- filename: pdfs-build-delegated-agents-api-openapi.yml
  format: yaml
  label: pdfs-build Delegated agents API
  slug: pdfs-build-delegated-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-delegated-agents-api-openapi.yml
- filename: pdfs-build-embedded-editor-api-openapi.yml
  format: yaml
  label: pdfs-build Embedded editor API
  slug: pdfs-build-embedded-editor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-embedded-editor-api-openapi.yml
- filename: pdfs-build-legacy-v1-api-openapi.yml
  format: yaml
  label: pdfs-build Legacy v1 API
  slug: pdfs-build-legacy-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-legacy-v1-api-openapi.yml
- filename: pdfs-build-render-jobs-api-openapi.yml
  format: yaml
  label: pdfs-build Render jobs API
  slug: pdfs-build-render-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-render-jobs-api-openapi.yml
- filename: pdfs-build-render-logs-api-openapi.yml
  format: yaml
  label: pdfs-build Render logs API
  slug: pdfs-build-render-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-render-logs-api-openapi.yml
- filename: pdfs-build-rendering-api-openapi.yml
  format: yaml
  label: pdfs-build Rendering API
  slug: pdfs-build-rendering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-rendering-api-openapi.yml
- filename: pdfs-build-template-gallery-api-openapi.yml
  format: yaml
  label: pdfs-build Template gallery API
  slug: pdfs-build-template-gallery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-template-gallery-api-openapi.yml
- filename: pdfs-build-templates-api-openapi.yml
  format: yaml
  label: pdfs-build Templates API
  slug: pdfs-build-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-templates-api-openapi.yml
- filename: pdfs-build-webhooks-api-openapi.yml
  format: yaml
  label: pdfs-build Webhooks API
  slug: pdfs-build-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pdfs-build/openapi/pdfs-build-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and identity data: name, email, password hash, organization and membership details, invitations, authentication provider identifiers, sessions, IP address, user agent'
  - category: contact
    text: 'Communications: support, privacy, security, and other messages you send us.'
  - category: financial
    text: 'Billing data: customer and subscription identifiers, plan, status, country, invoices, transactions, and metered usage.'
  - category: behavioral
    text: 'Website data: pages, features, and referrers measured through Google Analytics when enabled.'
  - category: device
    text: 'Product and technical data: features used, render and AI usage, API-key identifiers, request and error logs, device/browser details, diagnostic context, and security events.'
  - category: other
    text: 'Customer Content: templates, source code, schemas, sample or form data, prompts and chat history, uploaded and generated images, fonts, imports, and rendered documents.'
  deletion:
    route: Deletion by an authorized user or account closure; request via hello@pdfs.build
    text: until it is deleted by an authorized user or the account is closed.
  dpa:
    available: true
    text: we act as its processor under our Data Processing Addendum
    url: https://pdfs.build/dpa/
  purposes:
  - purpose: Account and service provision
    text: 'Contract: create and secure accounts; provide editing, rendering, AI, sharing, billing, support, and requested integrations.'
  - purpose: Legitimate interests
    text: 'Legitimate interests: operate, troubleshoot, and improve the Service; understand aggregate usage; prevent fraud and abuse; and protect users and our systems.'
  - purpose: Legal obligations
    text: 'Legal obligations: maintain tax and transaction records and comply with valid legal requests.'
  retention:
  - period: null
    scope: Account and Customer Content
    text: We keep account and Customer Content while the account or workspace is active and until it is deleted by an authorized user or the account is closed.
  - period: null
    scope: Operational and security logs
    text: We keep operational and security logs only for the period needed to troubleshoot, secure, and operate the Service.
  - period: null
    scope: Billing, tax, dispute, and legal records
    text: Billing, tax, dispute, and legal records are retained for the period required by applicable law.
  rights:
  - right: access
    text: you may have rights to access, correct, delete, restrict or object to processing, receive a portable copy, and withdraw consent.
  - right: complaint to authority
    text: You may also complain to the data-protection authority where you live or work.
  role:
    text: We are a controller for account, website, security, product-usage, and commercial data we determine how to use.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioural advertising.
  subprocessors:
    text: infrastructure, storage, email, monitoring, AI, search, identity, and billing providers described in our Subprocessor List
    url: https://pdfs.build/subprocessors/
  transfers:
  - mechanism: adequacy
    text: Where required, we use an adequacy decision or contractual safeguards such as the European Commission's Standard Contractual Clauses and the UK International Data Transfer Addendum
  - mechanism: SCC
    text: such as the European Commission's Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pdfs-build
provenance_date: '2026-11-10'
provider_name: pdfs-build
provider_slug: pdfs-build
slug: pdfs-build-privacy-policy
source_date: '2026-11-10'
source_filename: pdfs-build-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pdfs.build/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pdfs-build\naid: pdfs-build\nurl: https://pdfs.build/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are a controller for account, website, security, product-usage, and commercial data we determine how\n    to use.\ndata_categories:\n- category: identifying\n  text: 'Account and identity data: name, email, password hash, organization and membership details, invitations,\n    authentication provider identifiers, sessions, IP address, user agent'\n- category: contact\n  text: 'Communications: support, privacy, security, and other messages you send us.'\n- category: financial\n  text: 'Billing\
  \ data: customer and subscription identifiers, plan, status, country, invoices, transactions, and\n    metered usage.'\n- category: behavioral\n  text: 'Website data: pages, features, and referrers measured through Google Analytics when enabled.'\n- category: device\n  text: 'Product and technical data: features used, render and AI usage, API-key identifiers, request and error\n    logs, device/browser details, diagnostic context, and security events.'\n- category: other\n  text: 'Customer Content: templates, source code, schemas, sample or form data, prompts and chat history, uploaded\n    and generated images, fonts, imports, and rendered documents.'\npurposes:\n- purpose: Account and service provision\n  text: 'Contract: create and secure accounts; provide editing, rendering, AI, sharing, billing, support, and requested\n    integrations.'\n- purpose: Legitimate interests\n  text: 'Legitimate interests: operate, troubleshoot, and improve the Service; understand aggregate usage; prevent\n\
  \    fraud and abuse; and protect users and our systems.'\n- purpose: Legal obligations\n  text: 'Legal obligations: maintain tax and transaction records and comply with valid legal requests.'\nretention:\n- scope: Account and Customer Content\n  period: null\n  text: We keep account and Customer Content while the account or workspace is active and until it is deleted by\n    an authorized user or the account is closed.\n- scope: Operational and security logs\n  period: null\n  text: We keep operational and security logs only for the period needed to troubleshoot, secure, and operate the\n    Service.\n- scope: Billing, tax, dispute, and legal records\n  period: null\n  text: Billing, tax, dispute, and legal records are retained for the period required by applicable law.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where required, we use an adequacy decision or contractual safeguards such as the European Commission's\n    Standard Contractual Clauses and the UK International\
  \ Data Transfer Addendum\n- mechanism: SCC\n  text: such as the European Commission's Standard Contractual Clauses\nsubprocessors:\n  url: https://pdfs.build/subprocessors/\n  text: infrastructure, storage, email, monitoring, AI, search, identity, and billing providers described in our\n    Subprocessor List\ndpa:\n  available: true\n  url: https://pdfs.build/dpa/\n  text: we act as its processor under our Data Processing Addendum\ndeletion:\n  route: Deletion by an authorized user or account closure; request via hello@pdfs.build\n  text: until it is deleted by an authorized user or the account is closed.\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, restrict or object to processing, receive a portable copy,\n    and withdraw consent.\n- right: complaint to authority\n  text: You may also complain to the data-protection authority where you live or work.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it\
  \ for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/pdfs-build/privacy/pdfs-build-privacy-policy.yml
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
summary_line: 21 quoted statements, read from pdfs-build's own page on 2026-11-10.
synthetic: false
tags:
- PDF
- Template Engine
- Rendering
- Software-as-a-Service
- Document Generation
---
