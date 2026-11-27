---
api_specs:
- filename: nrouter-openapi-generated.yml
  format: yaml
  label: CloudAct API
  slug: nrouter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nrouter/openapi/_ae-authored/nrouter-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity: email address, full name, avatar URL'
  - category: contact
    text: 'Signup metadata: phone number, country code'
  - category: financial
    text: 'Financial: credit amounts, transaction types, timestamps (no payment card data stored — Stripe handles PCI)'
  - category: behavioral
    text: 'Request content: prompts and completions sent through our API'
  - category: device
    text: 'Request metadata: model, token counts, cost, latency, timestamps'
  deletion:
    route: Organization Settings > Danger Zone > Delete Organization
    text: Request deletion of your account and all associated data. Available via Organization Settings > Danger Zone > Delete Organization .
  dpa:
    available: true
    text: A pre-signed DPA is available for organizations that require one under GDPR Art. 28.
    url: nrouter.ai /legal/dpa
  purposes:
  - purpose: Route LLM requests and track usage costs
    text: Route LLM requests to providers and track usage costs
  - purpose: Process payments
    text: Process payments and manage credit balances via Stripe
  - purpose: Security and compliance audit logs
    text: Maintain audit logs for security and compliance (SOC 2-aligned)
  residency:
  - region: US
    text: Our application compute infrastructure is hosted in the US (Microsoft Azure Container Apps, East US) and our managed database infrastructure is hosted in the US (Supabase, Oregon).
  - region: EU
    text: EU data residency options (European Union (Netherlands) and EU North (Stockholm)) are available for organizations that require data to remain within the EEA.
  retention:
  - period: Zero data retention
    scope: LLM request & response content
    text: Zero data retention (never written to disk or database; processed ephemerally in memory only)
  - period: Until account deletion + 30-day grace
    scope: Account data
    text: Until account deletion + 30-day grace
  - period: 7 years
    scope: Credit transactions
    text: Credit transactions 7 years
  - period: 30 days after expiration (auto-purged)
    scope: Invitations
    text: 30 days after expiration (auto-purged)
  rights:
  - right: Access
    text: 'Right of access (Art. 15): Request a copy of all personal data we hold about you.'
  - right: Rectification
    text: 'Right to rectification (Art. 16): Update your name, email, or other account details from your profile settings.'
  - right: Erasure
    text: 'Right to erasure (Art. 17): Request deletion of your account and all associated data.'
  - right: Portability
    text: 'Right to data portability (Art. 20): Export your data in a structured, machine-readable format (JSON).'
  - right: Restriction
    text: 'Right to restrict processing (Art. 18): Request that we limit how we process your data while a dispute is resolved.'
  - right: Object
    text: 'Right to object (Art. 21): Object to processing based on legitimate interest.'
  - right: Complaint
    text: 'Right to lodge a complaint: You may file a complaint with your local supervisory authority'
  role:
    text: We act as the Data Controller for account, billing, and operational data, and as a Data Processor for LLM request content submitted through our API.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not use your LLM request content to train models, serve advertisements, or share with third parties beyond the sub-processors listed below.
  subprocessors:
    text: The current sub-processor register is available upon request at privacy@nrouter.ai .
    url: null
  transfers:
  - mechanism: DPF
    text: The EU-US Data Privacy Framework (DPF) for certified sub-processors
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) adopted by the European Commission (Commission Implementing Decision (EU) 2021/914)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CloudAct
provenance_date: '2026-11-10'
provider_name: CloudAct
provider_slug: nrouter
slug: nrouter-privacy-policy
source_date: '2026-11-10'
source_filename: nrouter-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nrouter.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CloudAct\naid: nrouter\nurl: https://nrouter.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as the Data Controller for account, billing, and operational data, and as a Data Processor for LLM\n    request content submitted through our API.\ndata_categories:\n- category: identifying\n  text: 'Identity: email address, full name, avatar URL'\n- category: contact\n  text: 'Signup metadata: phone number, country code'\n- category: financial\n  text: 'Financial: credit amounts, transaction types, timestamps (no payment card data stored — Stripe handles\n    PCI)'\n- category: behavioral\n\
  \  text: 'Request content: prompts and completions sent through our API'\n- category: device\n  text: 'Request metadata: model, token counts, cost, latency, timestamps'\npurposes:\n- purpose: Route LLM requests and track usage costs\n  text: Route LLM requests to providers and track usage costs\n- purpose: Process payments\n  text: Process payments and manage credit balances via Stripe\n- purpose: Security and compliance audit logs\n  text: Maintain audit logs for security and compliance (SOC 2-aligned)\nretention:\n- scope: LLM request & response content\n  period: Zero data retention\n  text: Zero data retention (never written to disk or database; processed ephemerally in memory only)\n- scope: Account data\n  period: Until account deletion + 30-day grace\n  text: Until account deletion + 30-day grace\n- scope: Credit transactions\n  period: 7 years\n  text: Credit transactions 7 years\n- scope: Invitations\n  period: 30 days after expiration (auto-purged)\n  text: 30 days after expiration\
  \ (auto-purged)\nresidency:\n- region: US\n  text: Our application compute infrastructure is hosted in the US (Microsoft Azure Container Apps, East US) and\n    our managed database infrastructure is hosted in the US (Supabase, Oregon).\n- region: EU\n  text: EU data residency options (European Union (Netherlands) and EU North (Stockholm)) are available for organizations\n    that require data to remain within the EEA.\ntransfers:\n- mechanism: DPF\n  text: The EU-US Data Privacy Framework (DPF) for certified sub-processors\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) adopted by the European Commission (Commission Implementing Decision\n    (EU) 2021/914)\nsubprocessors:\n  url: null\n  text: The current sub-processor register is available upon request at privacy@nrouter.ai .\ndpa:\n  available: true\n  url: nrouter.ai /legal/dpa\n  text: A pre-signed DPA is available for organizations that require one under GDPR Art. 28.\ndeletion:\n  route: Organization Settings > Danger\
  \ Zone > Delete Organization\n  text: Request deletion of your account and all associated data. Available via Organization Settings > Danger Zone\n    > Delete Organization .\nrights:\n- right: Access\n  text: 'Right of access (Art. 15): Request a copy of all personal data we hold about you.'\n- right: Rectification\n  text: 'Right to rectification (Art. 16): Update your name, email, or other account details from your profile settings.'\n- right: Erasure\n  text: 'Right to erasure (Art. 17): Request deletion of your account and all associated data.'\n- right: Portability\n  text: 'Right to data portability (Art. 20): Export your data in a structured, machine-readable format (JSON).'\n- right: Restriction\n  text: 'Right to restrict processing (Art. 18): Request that we limit how we process your data while a dispute\n    is resolved.'\n- right: Object\n  text: 'Right to object (Art. 21): Object to processing based on legitimate interest.'\n- right: Complaint\n  text: 'Right to lodge a complaint:\
  \ You may file a complaint with your local supervisory authority'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use your LLM request content to train models, serve advertisements, or share with third parties\n    beyond the sub-processors listed below.\n"
source_yaml_url: https://artifacts.apis.io/nrouter/privacy/nrouter-privacy-policy.yml
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
summary_line: 28 quoted statements, read from CloudAct's own page on 2026-11-10.
synthetic: false
tags:
- Company
- LLM Gateway
- AI Infrastructure
- Smart Routing
- Token Management
---
