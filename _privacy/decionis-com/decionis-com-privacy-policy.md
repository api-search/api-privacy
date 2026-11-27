---
api_specs:
- filename: decionis-com-well-known-openapi.json
  format: json
  label: Decionis Policy Evaluation API .well-known API
  slug: decionis-policy-evaluation-api-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decionis-com/openapi/_original/decionis-com-well-known-openapi.json
- filename: decionis-com-openapi-openapi.yml
  format: yaml
  label: Decionis Vertex Extension Verify API Openapi API
  slug: decionis-vertex-extension-verify-api-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decionis-com/openapi/_original/decionis-com-openapi-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: User identifiers provided by the platform (e.g., SAP User ID, Microsoft personId, Webex orgId), names, and corporate email addresses.
  - category: financial
    text: 'Operational Transaction Metadata: Contextual payload parameters required to evaluate an execution rule (e.g., transaction amounts, system change requests, or routing instructions)'
  - category: device
    text: 'System Diagnostics: Cryptographic logs, performance metadata, and audit logs of the policy evaluation engine to ensure execution uptime.'
  - category: contact
    text: 'Account Credentials: Email addresses, workspace IDs, and authentication tokens required to securely link Decionis to your corporate tech stack.'
  deletion:
    route: Enterprise client request
    text: Enterprise clients maintain the complete authority to request total data deletion or specify custom retention windows.
  dpa:
    available: null
    text: Enterprise clients maintain the complete authority to request total data deletion or specify custom retention windows.
    url: null
  purposes:
  - purpose: Evaluate execution constraints
    text: Evaluate execution constraints against live, real-time enterprise rules.
  - purpose: Generate signed Decision Dossiers
    text: Generate, cryptographically sign, and deliver immutable Decision Dossiers.
  - purpose: Audit trail
    text: Provide an audit trail for your organization's risk, GRC, and finance teams.
  retention:
  - period: null
    scope: Customer data
    text: We retain data only as long as specified by our Data Processing Agreement (DPA) with your organization, or as necessary to comply with legal audit obligations.
  rights:
  - right: Access, correct, restrict, or delete
    text: Depending on your jurisdiction, you may have rights to access, correct, restrict, or delete your personal data.
  role:
    text: Decionis acts strictly as the Data Processor (processing data solely on behalf of, and under the strict instruction of, our enterprise customers).
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or monetize enterprise operational data or personal metadata under any circumstances.
  subprocessors:
    text: To deliver our cloud services, Decionis runs on Microsoft Azure (Central US region), a tier-one infrastructure provider
    url: null
  transfers:
  - mechanism: SCC
    text: Where data transfers cross European Economic Area (EEA) boundaries, we utilize Standard Contractual Clauses (SCCs) approved by the European Commission, combined with strict technical safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: decionis-com
provenance_date: '2026-11-09'
provider_name: decionis-com
provider_slug: decionis-com
slug: decionis-com-privacy-policy
source_date: '2026-11-09'
source_filename: decionis-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://decionis.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: decionis-com\naid: decionis-com\nurl: https://decionis.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Decionis acts strictly as the Data Processor (processing data solely on behalf of, and under the strict\n    instruction of, our enterprise customers).\ndata_categories:\n- category: identifying\n  text: User identifiers provided by the platform (e.g., SAP User ID, Microsoft personId, Webex orgId), names, and\n    corporate email addresses.\n- category: financial\n  text: 'Operational Transaction Metadata: Contextual payload parameters required to evaluate an execution rule\n  \
  \  (e.g., transaction amounts, system change requests, or routing instructions)'\n- category: device\n  text: 'System Diagnostics: Cryptographic logs, performance metadata, and audit logs of the policy evaluation engine\n    to ensure execution uptime.'\n- category: contact\n  text: 'Account Credentials: Email addresses, workspace IDs, and authentication tokens required to securely link\n    Decionis to your corporate tech stack.'\npurposes:\n- purpose: Evaluate execution constraints\n  text: Evaluate execution constraints against live, real-time enterprise rules.\n- purpose: Generate signed Decision Dossiers\n  text: Generate, cryptographically sign, and deliver immutable Decision Dossiers.\n- purpose: Audit trail\n  text: Provide an audit trail for your organization's risk, GRC, and finance teams.\nretention:\n- scope: Customer data\n  period: null\n  text: We retain data only as long as specified by our Data Processing Agreement (DPA) with your organization,\n    or as necessary to\
  \ comply with legal audit obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where data transfers cross European Economic Area (EEA) boundaries, we utilize Standard Contractual Clauses\n    (SCCs) approved by the European Commission, combined with strict technical safeguards.\nsubprocessors:\n  url: null\n  text: To deliver our cloud services, Decionis runs on Microsoft Azure (Central US region), a tier-one infrastructure\n    provider\ndpa:\n  available: null\n  url: null\n  text: Enterprise clients maintain the complete authority to request total data deletion or specify custom retention\n    windows.\ndeletion:\n  route: Enterprise client request\n  text: Enterprise clients maintain the complete authority to request total data deletion or specify custom retention\n    windows.\nrights:\n- right: Access, correct, restrict, or delete\n  text: Depending on your jurisdiction, you may have rights to access, correct, restrict, or delete your personal\n    data.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell, rent, or monetize enterprise operational data or personal metadata under any circumstances.\n"
source_yaml_url: https://artifacts.apis.io/decionis-com/privacy/decionis-com-privacy-policy.yml
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
summary_line: 15 quoted statements, read from decionis-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Decision-Making
- Enterprise
- Automation
- Finance
---
