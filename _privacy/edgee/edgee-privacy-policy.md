---
api_specs:
- filename: edgee-compress-api-openapi.yml
  format: yaml
  label: Edgee Compress API
  slug: edgee-compress-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-compress-api-openapi.yml
- filename: edgee-messages-api-openapi.yml
  format: yaml
  label: Edgee Messages API
  slug: edgee-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-messages-api-openapi.yml
- filename: edgee-models-api-openapi.yml
  format: yaml
  label: Edgee Models API
  slug: edgee-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-models-api-openapi.yml
- filename: edgee-responses-api-openapi.yml
  format: yaml
  label: Edgee Responses API
  slug: edgee-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-responses-api-openapi.yml
- filename: edgee-tokens-api-openapi.yml
  format: yaml
  label: Edgee Tokens API
  slug: edgee-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-tokens-api-openapi.yml
- filename: edgee-chat-completions-api-openapi.yml
  format: yaml
  label: Edgee Chat Completions API
  slug: edgee-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-chat-completions-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account registration data (e.g., name, email, company, authentication identifiers)
  - category: contact
    text: Communication data (e.g., email correspondence, support tickets)
  - category: financial
    text: Billing data (processed through our payment provider, Stripe)
  - category: device
    text: Network and client metadata (e.g., source IP address with optional truncation, user agent or client identifiers, source application identifiers)
  - category: behavioral
    text: Usage and operational metadata (e.g., token counts, model used, latency, timestamps, request/response sizes, error codes, retry and fallback events)
  - category: other
    text: Prompt Data and Completion Data (the content sent to and returned by LLM Providers), treated as opaque payload.
  deletion:
    route: null
    text: If we become aware that such information has been collected, we will delete it without delay.
  dpa:
    available: true
    text: This processing is governed by our Data Processing Addendum (DPA)
    url: null
  purposes:
  - purpose: Routing LLM requests
    text: Routing LLM requests to the LLM Providers designated by the customer's configuration
  - purpose: Token compression
    text: Applying token compression and prompt optimization when enabled by the customer
  - purpose: Observability and cost tracking
    text: Providing observability, usage reporting, and cost tracking based on operational metadata only
  - purpose: Fraud and security
    text: Prevent fraud, abuse, and ensure service security
  - purpose: Support and account administration
    text: Provide support, communicate with customers, and administer accounts
  residency:
  - region: European Union
    text: Operational data (logs, usage metadata, configuration) is processed and stored within the European Union by default.
  retention:
  - period: null
    scope: Prompts and completions (default)
    text: not stored by Edgee; processed in-memory only for the time strictly necessary to route the request and return the response
  - period: 30 days
    scope: Prompts and completions (debug mode)
    text: retained for up to 30 days, then automatically deleted
  - period: 25 months
    scope: Usage and operational metadata
    text: retained for up to 25 months
  - period: null
    scope: Account and billing records
    text: for the duration of the customer relationship, plus legal retention obligations
  rights:
  - right: Access, rectify, or erase
    text: Access, rectify, or erase your data
  - right: Object or restrict
    text: Object to processing or request restriction
  - right: Data portability
    text: Data portability
  - right: Lodge a complaint
    text: Lodge a complaint with a data protection authority
  role:
    text: we distinguish between data Edgee processes on behalf of customers (as a processor) and data processed for our own operational purposes (as a controller).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Sell or rent personal data to third parties
  subprocessors:
    text: 'Edgee currently engages the following infrastructure subprocessors to help deliver its services: AWS (Amazon Web Services) : Infrastructure hosting and computing Vercel : Front-end hosting and deployment platform ClickHouse : Analytics-oriented database'
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs) : Contractual provisions approved by the European Commission that ensure adequate data protection safeguards.'
  - mechanism: adequacy
    text: 'Adequacy decisions : Where the European Commission has determined that a non-EU country ensures an adequate level of data protection (e.g., the UK, Switzerland, or under the EU-U.S. Data Privacy Framework), we may rely on that status to facilitate compliant transfers.'
  - mechanism: DPF
    text: under the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Edgee
provenance_date: '2026-11-09'
provider_name: Edgee
provider_slug: edgee
slug: edgee-privacy-policy
source_date: '2026-11-09'
source_filename: edgee-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.edgee.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Edgee\naid: edgee\nurl: https://www.edgee.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we distinguish between data Edgee processes on behalf of customers (as a processor) and data processed for\n    our own operational purposes (as a controller).\ndata_categories:\n- category: identifying\n  text: Account registration data (e.g., name, email, company, authentication identifiers)\n- category: contact\n  text: Communication data (e.g., email correspondence, support tickets)\n- category: financial\n  text: Billing data (processed through our payment provider, Stripe)\n- category: device\n\
  \  text: Network and client metadata (e.g., source IP address with optional truncation, user agent or client identifiers,\n    source application identifiers)\n- category: behavioral\n  text: Usage and operational metadata (e.g., token counts, model used, latency, timestamps, request/response sizes,\n    error codes, retry and fallback events)\n- category: other\n  text: Prompt Data and Completion Data (the content sent to and returned by LLM Providers), treated as opaque payload.\npurposes:\n- purpose: Routing LLM requests\n  text: Routing LLM requests to the LLM Providers designated by the customer's configuration\n- purpose: Token compression\n  text: Applying token compression and prompt optimization when enabled by the customer\n- purpose: Observability and cost tracking\n  text: Providing observability, usage reporting, and cost tracking based on operational metadata only\n- purpose: Fraud and security\n  text: Prevent fraud, abuse, and ensure service security\n- purpose: Support\
  \ and account administration\n  text: Provide support, communicate with customers, and administer accounts\nretention:\n- scope: Prompts and completions (default)\n  period: null\n  text: not stored by Edgee; processed in-memory only for the time strictly necessary to route the request and return\n    the response\n- scope: Prompts and completions (debug mode)\n  period: 30 days\n  text: retained for up to 30 days, then automatically deleted\n- scope: Usage and operational metadata\n  period: 25 months\n  text: retained for up to 25 months\n- scope: Account and billing records\n  period: null\n  text: for the duration of the customer relationship, plus legal retention obligations\nresidency:\n- region: European Union\n  text: Operational data (logs, usage metadata, configuration) is processed and stored within the European Union\n    by default.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs) : Contractual provisions approved by the European Commission that\
  \ ensure\n    adequate data protection safeguards.'\n- mechanism: adequacy\n  text: 'Adequacy decisions : Where the European Commission has determined that a non-EU country ensures an adequate\n    level of data protection (e.g., the UK, Switzerland, or under the EU-U.S. Data Privacy Framework), we may rely\n    on that status to facilitate compliant transfers.'\n- mechanism: DPF\n  text: under the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: 'Edgee currently engages the following infrastructure subprocessors to help deliver its services: AWS (Amazon\n    Web Services) : Infrastructure hosting and computing Vercel : Front-end hosting and deployment platform ClickHouse\n    : Analytics-oriented database'\ndpa:\n  available: true\n  url: null\n  text: This processing is governed by our Data Processing Addendum (DPA)\ndeletion:\n  route: null\n  text: If we become aware that such information has been collected, we will delete it without delay.\nrights:\n- right: Access,\
  \ rectify, or erase\n  text: Access, rectify, or erase your data\n- right: Object or restrict\n  text: Object to processing or request restriction\n- right: Data portability\n  text: Data portability\n- right: Lodge a complaint\n  text: Lodge a complaint with a data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: Sell or rent personal data to third parties\n"
source_yaml_url: https://artifacts.apis.io/edgee/privacy/edgee-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Edgee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- AI Gateway
- Agents
- Developer Tools
- Observability
- FinOps
- Edge Computing
- Cost Management
---
