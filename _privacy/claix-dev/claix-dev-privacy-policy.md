---
api_specs:
- filename: claix-dev-documento-a-json-api-openapi.yml
  format: yaml
  label: Claix Documento a JSON API
  slug: claix-dev-documento-a-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-documento-a-json-api-openapi.yml
- filename: claix-dev-espacios-de-conocimiento-api-openapi.yml
  format: yaml
  label: Claix Espacios de Conocimiento API
  slug: claix-dev-espacios-de-conocimiento-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-espacios-de-conocimiento-api-openapi.yml
- filename: claix-dev-excel-a-json-api-openapi.yml
  format: yaml
  label: Claix Excel a JSON API
  slug: claix-dev-excel-a-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-excel-a-json-api-openapi.yml
- filename: claix-dev-imagen-a-json-api-openapi.yml
  format: yaml
  label: Claix Imagen a JSON API
  slug: claix-dev-imagen-a-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-imagen-a-json-api-openapi.yml
- filename: claix-dev-json-a-excel-api-openapi.yml
  format: yaml
  label: Claix JSON a Excel API
  slug: claix-dev-json-a-excel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-json-a-excel-api-openapi.yml
- filename: claix-dev-modo-agente-api-openapi.yml
  format: yaml
  label: Claix Modo Agente API
  slug: claix-dev-modo-agente-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-modo-agente-api-openapi.yml
- filename: claix-dev-pdf-a-json-api-openapi.yml
  format: yaml
  label: Claix PDF a JSON API
  slug: claix-dev-pdf-a-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-pdf-a-json-api-openapi.yml
- filename: claix-dev-schemas-api-openapi.yml
  format: yaml
  label: Claix Schemas API
  slug: claix-dev-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-schemas-api-openapi.yml
- filename: claix-dev-texto-a-json-api-openapi.yml
  format: yaml
  label: Claix Texto a JSON API
  slug: claix-dev-texto-a-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-texto-a-json-api-openapi.yml
- filename: claix-dev-ventana-de-contexto-api-openapi.yml
  format: yaml
  label: Claix Ventana de Contexto API
  slug: claix-dev-ventana-de-contexto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-ventana-de-contexto-api-openapi.yml
- filename: claix-dev-audio-a-json-api-openapi.yml
  format: yaml
  label: Claix Audio a JSON API
  slug: claix-dev-audio-a-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-audio-a-json-api-openapi.yml
- filename: claix-dev-markdown-api-openapi.yml
  format: yaml
  label: Claix Markdown API
  slug: claix-dev-markdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claix-dev/openapi/claix-dev-markdown-api-openapi.yml
claim_count: 45
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address; encrypted or hashed authentication credentials, where applicable; name, company name, trade name, or legal entity name
  - category: contact
    text: email address
  - category: financial
    text: tax identification number, billing address, and billing details, where applicable
  - category: device
    text: IP address; browser, device, and operating-system information; HTTP headers
  - category: location
    text: approximate location inferred from IP address
  - category: behavioral
    text: API request metadata; API key or token usage metadata; authentication events
  - category: communication
    text: support communications and support ticket information
  - category: other
    text: 'Customer Content may include: files such as Excel, CSV, PDF, Word, text, Markdown, RTF, or image files'
  - category: identifying
    source: https://www.claix.dev/dpa
    text: identity and contact information
  - category: financial
    source: https://www.claix.dev/dpa
    text: account, contract, purchase, invoice, payment, transaction, and tax-related information
  - category: communication
    source: https://www.claix.dev/dpa
    text: communications and correspondence
  - category: device
    source: https://www.claix.dev/dpa
    text: technical and usage data
  deletion:
    route: Contact info@claix.dev or delete via Dashboard retention settings
    text: Upon termination of the Service or at the customer’s request, Claix will delete or return Customer Content in accordance with the DPA, applicable product settings, and applicable law, unless retention is required by law.
  dpa:
    available: true
    text: The Claix DPA, which forms part of the applicable contractual documentation where accepted or incorporated by reference, governs such processing.
    url: null
  purposes:
  - purpose: Account and workspace management
    text: create and manage accounts and workspaces
  - purpose: Authentication and security
    text: authenticate users and secure access to the Service
  - purpose: Billing
    text: manage subscriptions, billing, invoices, and payment-related obligations
  - purpose: Customer support
    text: provide customer support
  - purpose: Fraud and abuse prevention
    text: prevent fraud, abuse, unauthorized access, and misuse of the Service
  - purpose: Legal compliance
    text: comply with legal, accounting, tax, and regulatory obligations
  - purpose: Provide the Service
    source: https://www.claix.dev/dpa
    text: Claix processes Personal Data only to provide the Service to the Customer
  - purpose: AI processing selected by customer
    source: https://www.claix.dev/dpa
    text: providing Claix Managed AI or BYOK processing selected by the Customer
  - purpose: Security and operations
    source: https://www.claix.dev/dpa
    text: maintaining Service security, reliability, performance, logging, troubleshooting, support, abuse prevention, and incident response
  residency:
  - region: EEA
    text: The relevant Claix Supabase project may be configured in the European Economic Area, including Stockholm, Sweden, depending on the service and configuration in use.
  - region: EEA
    text: Claix is established in Spain and seeks to operate its core application infrastructure within the European Economic Area where possible.
  - region: EEA
    source: https://www.claix.dev/dpa
    text: Claix seeks to operate relevant core application infrastructure within the European Economic Area where possible.
  retention:
  - period: null
    scope: Account, billing, and contractual data
    text: Account, billing, tax, contractual-acceptance, and related business records are retained for the duration of the customer relationship and thereafter for the periods required by applicable tax, accounting, legal, dispute-resolution, fraud-prevention, or regulatory obligations.
  - period: null
    scope: Customer Content without context persistence
    text: Claix processes Customer Content for the duration necessary to complete the requested API or Dashboard operation and does not intentionally retain it as a persistent document/context record after processing is complete.
  - period: null
    scope: Customer Content with persistent context enabled
    text: Where a customer enables persistent document/context retention, Customer Content and associated context may be retained until the customer deletes the relevant document, disables or changes the retention configuration, closes the account, or otherwise requests deletion
  - period: null
    scope: Query results
    text: Query results are generally processed to provide the requested response and are not intentionally retained as persistent business records unless required by a selected feature, customer configuration, legal obligation, security requirement, or applicable retention policy.
  - period: null
    scope: Database Credentials
    source: https://www.claix.dev/dpa
    text: Database Credentials are retained in encrypted form only while the relevant Database Connection remains active or until the Customer replaces, updates, disables, deletes, or requests deletion of the connection
  rights:
  - right: access
    text: access to your personal data
  - right: rectification
    text: rectification of inaccurate or incomplete data
  - right: erasure
    text: erasure of personal data
  - right: restriction
    text: restriction of processing
  - right: objection
    text: objection to processing based on legitimate interests
  - right: portability
    text: portability of personal data in a structured, commonly used, machine-readable format
  - right: withdraw consent
    text: withdrawal of consent where processing is based on consent
  role:
    text: Where Claix processes personal data contained in Customer Content on behalf of a business customer, Claix generally acts as a processor and the customer acts as controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Claix does not sell Customer Content.
  subprocessors:
    text: 'Examples of providers that may be involved depending on the selected product configuration include: Google, including Gemini services; OpenAI; Anthropic; xAI; Supabase; Amazon Web Services'
    url: null
  transfers:
  - mechanism: SCC
    text: such as the European Commission’s Standard Contractual Clauses, an adequacy decision, the EU–U.S. Data Privacy Framework where applicable, or another lawful transfer mechanism
  - mechanism: DPF
    text: the EU–U.S. Data Privacy Framework where applicable
  - mechanism: DPF
    source: https://www.claix.dev/dpa
    text: the EU–U.S. Data Privacy Framework, where applicable
  - mechanism: BCR
    source: https://www.claix.dev/dpa
    text: Binding Corporate Rules
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Claix
provenance_date: '2026-11-09'
provider_name: Claix
provider_slug: claix-dev
slug: claix-dev-privacy-policy
source_date: '2026-11-09'
source_filename: claix-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.claix.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Claix\naid: claix-dev\nurl: https://www.claix.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.claix.dev/dpa\n  - https://www.claix.dev/privacy\nrole:\n  value: both\n  text: Where Claix processes personal data contained in Customer Content on behalf of a business customer, Claix\n    generally acts as a processor and the customer acts as controller\ndata_categories:\n- category: identifying\n  text: email address; encrypted or hashed authentication credentials, where applicable; name, company name, trade\n    name, or legal entity name\n- category: contact\n  text: email address\n- category:\
  \ financial\n  text: tax identification number, billing address, and billing details, where applicable\n- category: device\n  text: IP address; browser, device, and operating-system information; HTTP headers\n- category: location\n  text: approximate location inferred from IP address\n- category: behavioral\n  text: API request metadata; API key or token usage metadata; authentication events\n- category: communication\n  text: support communications and support ticket information\n- category: other\n  text: 'Customer Content may include: files such as Excel, CSV, PDF, Word, text, Markdown, RTF, or image files'\n- category: identifying\n  text: identity and contact information\n  source: https://www.claix.dev/dpa\n- category: financial\n  text: account, contract, purchase, invoice, payment, transaction, and tax-related information\n  source: https://www.claix.dev/dpa\n- category: communication\n  text: communications and correspondence\n  source: https://www.claix.dev/dpa\n- category: device\n\
  \  text: technical and usage data\n  source: https://www.claix.dev/dpa\npurposes:\n- purpose: Account and workspace management\n  text: create and manage accounts and workspaces\n- purpose: Authentication and security\n  text: authenticate users and secure access to the Service\n- purpose: Billing\n  text: manage subscriptions, billing, invoices, and payment-related obligations\n- purpose: Customer support\n  text: provide customer support\n- purpose: Fraud and abuse prevention\n  text: prevent fraud, abuse, unauthorized access, and misuse of the Service\n- purpose: Legal compliance\n  text: comply with legal, accounting, tax, and regulatory obligations\n- purpose: Provide the Service\n  text: Claix processes Personal Data only to provide the Service to the Customer\n  source: https://www.claix.dev/dpa\n- purpose: AI processing selected by customer\n  text: providing Claix Managed AI or BYOK processing selected by the Customer\n  source: https://www.claix.dev/dpa\n- purpose: Security and\
  \ operations\n  text: maintaining Service security, reliability, performance, logging, troubleshooting, support, abuse prevention,\n    and incident response\n  source: https://www.claix.dev/dpa\nretention:\n- scope: Account, billing, and contractual data\n  period: null\n  text: Account, billing, tax, contractual-acceptance, and related business records are retained for the duration\n    of the customer relationship and thereafter for the periods required by applicable tax, accounting, legal, dispute-resolution,\n    fraud-prevention, or regulatory obligations.\n- scope: Customer Content without context persistence\n  period: null\n  text: Claix processes Customer Content for the duration necessary to complete the requested API or Dashboard operation\n    and does not intentionally retain it as a persistent document/context record after processing is complete.\n- scope: Customer Content with persistent context enabled\n  period: null\n  text: Where a customer enables persistent document/context\
  \ retention, Customer Content and associated context\n    may be retained until the customer deletes the relevant document, disables or changes the retention configuration,\n    closes the account, or otherwise requests deletion\n- scope: Query results\n  period: null\n  text: Query results are generally processed to provide the requested response and are not intentionally retained\n    as persistent business records unless required by a selected feature, customer configuration, legal obligation,\n    security requirement, or applicable retention policy.\n- scope: Database Credentials\n  period: null\n  text: Database Credentials are retained in encrypted form only while the relevant Database Connection remains\n    active or until the Customer replaces, updates, disables, deletes, or requests deletion of the connection\n  source: https://www.claix.dev/dpa\nresidency:\n- region: EEA\n  text: The relevant Claix Supabase project may be configured in the European Economic Area, including\
  \ Stockholm,\n    Sweden, depending on the service and configuration in use.\n- region: EEA\n  text: Claix is established in Spain and seeks to operate its core application infrastructure within the European\n    Economic Area where possible.\n- region: EEA\n  text: Claix seeks to operate relevant core application infrastructure within the European Economic Area where\n    possible.\n  source: https://www.claix.dev/dpa\ntransfers:\n- mechanism: SCC\n  text: such as the European Commission’s Standard Contractual Clauses, an adequacy decision, the EU–U.S. Data Privacy\n    Framework where applicable, or another lawful transfer mechanism\n- mechanism: DPF\n  text: the EU–U.S. Data Privacy Framework where applicable\n- mechanism: DPF\n  text: the EU–U.S. Data Privacy Framework, where applicable\n  source: https://www.claix.dev/dpa\n- mechanism: BCR\n  text: Binding Corporate Rules\n  source: https://www.claix.dev/dpa\nsubprocessors:\n  url: null\n  text: 'Examples of providers that may be\
  \ involved depending on the selected product configuration include: Google,\n    including Gemini services; OpenAI; Anthropic; xAI; Supabase; Amazon Web Services'\ndpa:\n  available: true\n  url: null\n  text: The Claix DPA, which forms part of the applicable contractual documentation where accepted or incorporated\n    by reference, governs such processing.\ndeletion:\n  route: Contact info@claix.dev or delete via Dashboard retention settings\n  text: Upon termination of the Service or at the customer’s request, Claix will delete or return Customer Content\n    in accordance with the DPA, applicable product settings, and applicable law, unless retention is required by\n    law.\nrights:\n- right: access\n  text: access to your personal data\n- right: rectification\n  text: rectification of inaccurate or incomplete data\n- right: erasure\n  text: erasure of personal data\n- right: restriction\n  text: restriction of processing\n- right: objection\n  text: objection to processing based\
  \ on legitimate interests\n- right: portability\n  text: portability of personal data in a structured, commonly used, machine-readable format\n- right: withdraw consent\n  text: withdrawal of consent where processing is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: Claix does not sell Customer Content.\n"
source_yaml_url: https://artifacts.apis.io/claix-dev/privacy/claix-dev-privacy-policy.yml
stated_fields:
- role
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
summary_line: 45 quoted statements, read from Claix's own page on 2026-11-09.
synthetic: false
tags:
- Document Processing
- Data Extraction
- Document Intelligence
- PDF
- Excel
- OCR
- Structured Data
- AI Agents
- MCP
- A2A
- Spain
- Company
---
