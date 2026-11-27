---
api_specs:
- filename: concentrate-decisions-api-openapi.yml
  format: yaml
  label: Concentrate Decisions API
  slug: concentrate-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-decisions-api-openapi.yml
- filename: concentrate-messages-api-openapi.yml
  format: yaml
  label: Concentrate Messages API
  slug: concentrate-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-messages-api-openapi.yml
- filename: concentrate-models-api-openapi.yml
  format: yaml
  label: Concentrate Models API
  slug: concentrate-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-models-api-openapi.yml
- filename: concentrate-responses-api-openapi.yml
  format: yaml
  label: Concentrate Responses API
  slug: concentrate-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-responses-api-openapi.yml
- filename: concentrate-systemone-api-openapi.yml
  format: yaml
  label: Concentrate Systemone API
  slug: concentrate-systemone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-systemone-api-openapi.yml
- filename: concentrate-chat-completions-api-openapi.yml
  format: yaml
  label: Concentrate Chat Completions API
  slug: concentrate-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/concentrate/openapi/concentrate-chat-completions-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email, organization, role, login identifiers.
  - category: device
    text: IP address, device/browser type, timestamps, API call metrics, features used, error logs.
  - category: financial
    text: Billing contacts, company address, tax/VAT IDs, transaction IDs.
  - category: communication
    text: Messages you send to support@…, attachments, screenshots.
  - category: other
    text: prompt text; identifiers of end users; documents; API payloads; model outputs; metadata about which model was used.
  deletion:
    route: Written request through an authenticated admin for Controller deletion of Customer Data
    text: If you are the Controller and you ask us (in writing, through an authenticated admin) to delete Customer Data sooner, we will follow your instruction unless we are legally required to keep it.
  dpa:
    available: true
    text: This is the behavior described in our DPA and is consistent with GDPR Articles 28–32.
    url: null
  purposes:
  - purpose: provide, maintain and improve Services
    text: provide, maintain, and improve the Services; secure and monitor the platform; detect, prevent, and investigate fraud or abuse
  - purpose: billing and tax compliance
    text: to process payments and meet tax/audit obligations.
  residency:
  - region: United States
    text: We operate from the United States and may process data there.
  retention:
  - period: typically deleted within 90 days of termination
    scope: Customer Data (processor)
    text: 'Customer Data (processor): kept for the duration of the Services and typically deleted within 90 days of termination, unless a shorter period is agreed or longer retention is required by law or to resolve a dispute.'
  - period: up to 7 years
    scope: Account, billing, and contract records
    text: 'Account, billing, and contract records (controller): kept for up to 7 years to meet tax, accounting, and audit requirements.'
  - period: up to 12 months
    scope: Security and system logs
    text: 'Security and system logs: typically kept for up to 12 months for forensic, security, and continuity purposes, then deleted or anonymized.'
  rights:
  - right: access
    text: You may request confirmation of whether we process your Personal Data and obtain a copy of it.
  - right: correction
    text: You may request correction of inaccurate or incomplete Personal Data.
  - right: deletion
    text: You may request deletion of Personal Data we hold about you.
  - right: restriction of processing
    text: You may request that we restrict processing of your Personal Data in situations allowed under the GDPR
  - right: portability
    text: You may request a copy of Personal Data you provided to us in a structured, commonly used, machine-readable format.
  - right: object
    text: you may object to processing based on our legitimate interests or for research/statistical purposes.
  - right: appeal
    text: If we decline a request, you may appeal our decision within the timeframe required by applicable state law.
  role:
    text: For any data that your organization sends to or through the Services, you (the customer) are the data controller/business. Concentrate processes that data only on your documented instructions. Where we collect data for our own business purposes (like billing, sales, security, or website analytics), we act as the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share Personal Data as those terms are defined under the CPRA.
  subprocessors:
    text: we will post changes at a dedicated URL (e.g. concentrate.ai/subprocessors)
    url: concentrate.ai/subprocessors
  transfers:
  - mechanism: SCC
    text: EU Standard Contractual Clauses (SCCs); UK IDTA / UK Addendum for UK data;
  - mechanism: DPF
    text: Concentrate AI, Inc. complies with the EU–U.S. Data Privacy Framework ("EU–U.S. DPF"), the UK Extension to the EU–U.S. DPF, and the Swiss–U.S. Data Privacy Framework ("Swiss–U.S. DPF") as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Concentrate
provenance_date: '2026-11-09'
provider_name: Concentrate
provider_slug: concentrate
slug: concentrate-privacy-policy
source_date: '2026-11-09'
source_filename: concentrate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://concentrate.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Concentrate\naid: concentrate\nurl: https://concentrate.ai/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For any data that your organization sends to or through the Services, you (the customer) are the data controller/business.\n    Concentrate processes that data only on your documented instructions. Where we collect data for our own business\n    purposes (like billing, sales, security, or website analytics), we act as the controller.\ndata_categories:\n- category: identifying\n  text: Name, work email, organization, role, login identifiers.\n- category: device\n  text: IP\
  \ address, device/browser type, timestamps, API call metrics, features used, error logs.\n- category: financial\n  text: Billing contacts, company address, tax/VAT IDs, transaction IDs.\n- category: communication\n  text: Messages you send to support@…, attachments, screenshots.\n- category: other\n  text: prompt text; identifiers of end users; documents; API payloads; model outputs; metadata about which model\n    was used.\npurposes:\n- purpose: provide, maintain and improve Services\n  text: provide, maintain, and improve the Services; secure and monitor the platform; detect, prevent, and investigate\n    fraud or abuse\n- purpose: billing and tax compliance\n  text: to process payments and meet tax/audit obligations.\nretention:\n- scope: Customer Data (processor)\n  period: typically deleted within 90 days of termination\n  text: 'Customer Data (processor): kept for the duration of the Services and typically deleted within 90 days of\n    termination, unless a shorter period is agreed\
  \ or longer retention is required by law or to resolve a dispute.'\n- scope: Account, billing, and contract records\n  period: up to 7 years\n  text: 'Account, billing, and contract records (controller): kept for up to 7 years to meet tax, accounting, and\n    audit requirements.'\n- scope: Security and system logs\n  period: up to 12 months\n  text: 'Security and system logs: typically kept for up to 12 months for forensic, security, and continuity purposes,\n    then deleted or anonymized.'\nresidency:\n- region: United States\n  text: We operate from the United States and may process data there.\ntransfers:\n- mechanism: SCC\n  text: EU Standard Contractual Clauses (SCCs); UK IDTA / UK Addendum for UK data;\n- mechanism: DPF\n  text: Concentrate AI, Inc. complies with the EU–U.S. Data Privacy Framework (\"EU–U.S. DPF\"), the UK Extension\n    to the EU–U.S. DPF, and the Swiss–U.S. Data Privacy Framework (\"Swiss–U.S. DPF\") as set forth by the U.S. Department\n    of Commerce.\nsubprocessors:\n\
  \  url: concentrate.ai/subprocessors\n  text: we will post changes at a dedicated URL (e.g. concentrate.ai/subprocessors)\ndpa:\n  available: true\n  url: null\n  text: This is the behavior described in our DPA and is consistent with GDPR Articles 28–32.\ndeletion:\n  route: Written request through an authenticated admin for Controller deletion of Customer Data\n  text: If you are the Controller and you ask us (in writing, through an authenticated admin) to delete Customer\n    Data sooner, we will follow your instruction unless we are legally required to keep it.\nrights:\n- right: access\n  text: You may request confirmation of whether we process your Personal Data and obtain a copy of it.\n- right: correction\n  text: You may request correction of inaccurate or incomplete Personal Data.\n- right: deletion\n  text: You may request deletion of Personal Data we hold about you.\n- right: restriction of processing\n  text: You may request that we restrict processing of your Personal Data\
  \ in situations allowed under the GDPR\n- right: portability\n  text: You may request a copy of Personal Data you provided to us in a structured, commonly used, machine-readable\n    format.\n- right: object\n  text: you may object to processing based on our legitimate interests or for research/statistical purposes.\n- right: appeal\n  text: If we decline a request, you may appeal our decision within the timeframe required by applicable state law.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share Personal Data as those terms are defined under the CPRA.\n"
source_yaml_url: https://artifacts.apis.io/concentrate/privacy/concentrate-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Concentrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Gateways
- Platform
---
