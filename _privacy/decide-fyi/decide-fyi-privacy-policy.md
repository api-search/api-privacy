---
api_specs:
- filename: decide-fyi-action-execution-api-openapi.yml
  format: yaml
  label: decide-fyi Action Execution API
  slug: decide-fyi-action-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-action-execution-api-openapi.yml
- filename: decide-fyi-anomalies-api-openapi.yml
  format: yaml
  label: decide-fyi Anomalies API
  slug: decide-fyi-anomalies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-anomalies-api-openapi.yml
- filename: decide-fyi-audit-chain-api-openapi.yml
  format: yaml
  label: decide-fyi Audit Chain API
  slug: decide-fyi-audit-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-audit-chain-api-openapi.yml
- filename: decide-fyi-benchmarks-api-openapi.yml
  format: yaml
  label: decide-fyi Benchmarks API
  slug: decide-fyi-benchmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-benchmarks-api-openapi.yml
- filename: decide-fyi-confidence-api-openapi.yml
  format: yaml
  label: decide-fyi Confidence API
  slug: decide-fyi-confidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-confidence-api-openapi.yml
- filename: decide-fyi-counterfactuals-api-openapi.yml
  format: yaml
  label: decide-fyi Counterfactuals API
  slug: decide-fyi-counterfactuals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-counterfactuals-api-openapi.yml
- filename: decide-fyi-crm-sync-api-openapi.yml
  format: yaml
  label: decide-fyi CRM Sync API
  slug: decide-fyi-crm-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-crm-sync-api-openapi.yml
- filename: decide-fyi-decision-packets-api-openapi.yml
  format: yaml
  label: decide-fyi Decision Packets API
  slug: decide-fyi-decision-packets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-decision-packets-api-openapi.yml
- filename: decide-fyi-decision-protocol-api-openapi.yml
  format: yaml
  label: decide-fyi Decision Protocol API
  slug: decide-fyi-decision-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-decision-protocol-api-openapi.yml
- filename: decide-fyi-effectiveness-api-openapi.yml
  format: yaml
  label: decide-fyi Effectiveness API
  slug: decide-fyi-effectiveness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-effectiveness-api-openapi.yml
- filename: decide-fyi-outcome-tracking-api-openapi.yml
  format: yaml
  label: decide-fyi Outcome Tracking API
  slug: decide-fyi-outcome-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-outcome-tracking-api-openapi.yml
- filename: decide-fyi-policy-patterns-api-openapi.yml
  format: yaml
  label: decide-fyi Policy Patterns API
  slug: decide-fyi-policy-patterns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-policy-patterns-api-openapi.yml
- filename: decide-fyi-registries-api-openapi.yml
  format: yaml
  label: decide-fyi Registries API
  slug: decide-fyi-registries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-registries-api-openapi.yml
- filename: decide-fyi-verification-api-openapi.yml
  format: yaml
  label: decide-fyi Verification API
  slug: decide-fyi-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decide-fyi/openapi/decide-fyi-verification-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Contact and account information: name, email, company, role, sign-in identifiers, support messages, and API access requests you submit.'
  - category: financial
    text: 'Payment and plan metadata: checkout status, customer identifiers, billing/work email, plan, subscription, and invoice-related metadata.'
  - category: device
    text: 'Local browser data: sandbox history, saved demo cases, monitor preferences, and similar settings may be stored in your browser unless you clear them.'
  - category: behavioral
    text: 'Operational logs: limited metadata such as timestamp, route, status, latency, IP-derived rate-limit data, hashed identifiers, and error details for security, debugging, abuse prevention, and reliability.'
  - category: other
    text: 'API and runtime information: request inputs, context fields, verdicts, evidence codes, policy versions, decision IDs, request IDs, record hashes, replay metadata, latency, status, route, and usage counters needed to operate the API.'
  deletion:
    route: Email support@decide.fyi
    text: To request deletion, export, or correction of account or support data, email support@decide.fyi .
  dpa:
    available: null
    text: If a signed order, data processing addendum, or enterprise agreement applies to your use, that written agreement controls where it conflicts with this public policy.
    url: null
  purposes:
  - purpose: API operation and security
    text: Provide and secure the Decision API, reference applications, account access, checkout, API key provisioning, and support workflows.
  - purpose: Decision record replay
    text: Generate and replay Decision Record v1 outputs when your integration calls the API.
  - purpose: Abuse and quota enforcement
    text: Enforce API keys, quotas, rate limits, billing state, and abuse controls.
  - purpose: Support and reliability
    text: Improve reliability, diagnose incidents, and maintain public status, trust, and source-alert surfaces.
  retention:
  - period: null
    scope: General information
    text: We keep information for as long as needed to operate the service, provide support, meet billing or security obligations, resolve disputes, and maintain auditability.
  - period: 90 elapsed days
    scope: Business prepaid full decision records
    text: For the separately selected business prepaid Runtime package, full completed decision records are available for 90 elapsed days from their signed creation timestamp.
  - period: 12 calendar months
    scope: Prepaid purchase redemption
    text: Each purchase has 12 calendar months of redemption availability; unused credit remains refundable afterward.
  rights:
  - right: Deletion, export or correction
    text: Contact support@decide.fyi for an account export, correction or deletion request.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use customer prompts or decision inputs to train public AI models.
  subprocessors:
    text: Visible providers may include Clerk for authentication and Stripe for payment processing. Other infrastructure providers may support hosting, storage, logs, email, metrics, and alerting.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: decide-fyi
provenance_date: '2026-11-09'
provider_name: decide-fyi
provider_slug: decide-fyi
slug: decide-fyi-privacy-policy
source_date: '2026-11-09'
source_filename: decide-fyi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.decide.fyi/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: decide-fyi\naid: decide-fyi\nurl: https://www.decide.fyi/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Contact and account information: name, email, company, role, sign-in identifiers, support messages, and\n    API access requests you submit.'\n- category: financial\n  text: 'Payment and plan metadata: checkout status, customer identifiers, billing/work email, plan, subscription,\n    and invoice-related metadata.'\n- category: device\n  text: 'Local browser data: sandbox history, saved demo cases, monitor preferences, and similar\
  \ settings may be\n    stored in your browser unless you clear them.'\n- category: behavioral\n  text: 'Operational logs: limited metadata such as timestamp, route, status, latency, IP-derived rate-limit data,\n    hashed identifiers, and error details for security, debugging, abuse prevention, and reliability.'\n- category: other\n  text: 'API and runtime information: request inputs, context fields, verdicts, evidence codes, policy versions,\n    decision IDs, request IDs, record hashes, replay metadata, latency, status, route, and usage counters needed\n    to operate the API.'\npurposes:\n- purpose: API operation and security\n  text: Provide and secure the Decision API, reference applications, account access, checkout, API key provisioning,\n    and support workflows.\n- purpose: Decision record replay\n  text: Generate and replay Decision Record v1 outputs when your integration calls the API.\n- purpose: Abuse and quota enforcement\n  text: Enforce API keys, quotas, rate limits, billing\
  \ state, and abuse controls.\n- purpose: Support and reliability\n  text: Improve reliability, diagnose incidents, and maintain public status, trust, and source-alert surfaces.\nretention:\n- scope: General information\n  period: null\n  text: We keep information for as long as needed to operate the service, provide support, meet billing or security\n    obligations, resolve disputes, and maintain auditability.\n- scope: Business prepaid full decision records\n  period: 90 elapsed days\n  text: For the separately selected business prepaid Runtime package, full completed decision records are available\n    for 90 elapsed days from their signed creation timestamp.\n- scope: Prepaid purchase redemption\n  period: 12 calendar months\n  text: Each purchase has 12 calendar months of redemption availability; unused credit remains refundable afterward.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Visible providers may include Clerk for authentication and Stripe for payment\
  \ processing. Other infrastructure\n    providers may support hosting, storage, logs, email, metrics, and alerting.\ndpa:\n  available: null\n  url: null\n  text: If a signed order, data processing addendum, or enterprise agreement applies to your use, that written agreement\n    controls where it conflicts with this public policy.\ndeletion:\n  route: Email support@decide.fyi\n  text: To request deletion, export, or correction of account or support data, email support@decide.fyi .\nrights:\n- right: Deletion, export or correction\n  text: Contact support@decide.fyi for an account export, correction or deletion request.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not use customer prompts or decision inputs to train public AI models.\n"
source_yaml_url: https://artifacts.apis.io/decide-fyi/privacy/decide-fyi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from decide-fyi's own page on 2026-11-09.
synthetic: false
tags:
- Decision API
- Rule Engine
- Software-as-a-Service
- Automation
- Runtime
---
