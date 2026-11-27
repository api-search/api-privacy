---
api_specs:
- filename: agentkey-openapi-generated.yml
  format: yaml
  label: AgentKey API
  slug: agentkey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentkey/openapi/_ae-authored/agentkey-openapi-generated.yml
- filename: agentkey-install-api-openapi.yml
  format: yaml
  label: AgentKey (Data API Layer) Install API
  slug: agentkey-install-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentkey/openapi/agentkey-install-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in, we collect your email address, profile image, and a unique identifier issued by our authentication provider.
  - category: financial
    text: We receive only a customer reference, the amount paid, and the transaction status — never card numbers or CVCs.
  - category: behavioral
    text: Usage logs. For each API request routed through AgentKey, we record the timestamp, endpoint path, HTTP status, response latency, credit cost, and the API key that made the call.
  - category: device
    text: When you install our CLI or skill plugin, we may receive an anonymous installation identifier and basic telemetry (CLI version, install method)
  - category: communication
    text: If you contact us by email or community channel, we retain the content of that exchange to respond to and resolve your inquiry.
  deletion:
    route: Dashboard or support@agentkey.app
    text: delete your account and its associated personal data directly from your dashboard at any time.
  dpa:
    available: null
    text: Each handles a narrow function, processes data on our behalf under a data processing agreement
    url: null
  purposes:
  - purpose: Authenticate and authorize access
    text: Authenticate you and authorize your access to the Service;
  - purpose: Route API requests
    text: Route your API requests to the appropriate Third-Party Provider and return responses;
  - purpose: Metering and billing
    text: Meter and bill your usage of credits;
  - purpose: Abuse and security
    text: Detect, prevent, and investigate abuse, fraud, and security incidents;
  - purpose: Product improvement
    text: Maintain, debug, and improve the Service;
  residency:
  - region: Data-residency restricted sources
    text: Where a source may only be provided from within a specific jurisdiction, we route those requests through infrastructure in that region
  retention:
  - period: null
    scope: Account data
    text: Account data is retained while your account is active.
  - period: null
    scope: API key hashes
    text: API key hashes are retained until you revoke the key, plus a short window for audit.
  - period: twelve (12) months
    scope: Usage logs
    text: Usage logs are retained for operational and billing reconciliation purposes, typically up to twelve (12) months, then aggregated or deleted.
  - period: twelve (12) months
    scope: Email open and click records
    text: Email open and click records are retained for up to twelve (12) months, then deleted.
  - period: thirty (30) days
    scope: Account deletion
    text: When you delete your account, we delete or anonymize personal data within thirty (30) days, except where retention is required by law or necessary to resolve a dispute.
  rights:
  - right: Access
    text: Access the personal data we hold about you;
  - right: Correct
    text: Correct inaccurate or incomplete personal data;
  - right: Delete
    text: Delete your personal data, subject to legal retention obligations;
  - right: Portability
    text: Receive a copy of your data in a portable format;
  - right: Object or restrict
    text: Restrict or object to certain processing;
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent;
  role:
    text: AgentKey acts as a routing layer.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data or use it to train AI models.
  subprocessors:
    text: Clerk (clerk.com) — sign-in, session management, and identity.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate legal mechanisms (such as Standard Contractual Clauses or equivalent safeguards) where required by applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentKey (Data API Layer)
provenance_date: '2026-11-09'
provider_name: AgentKey (Data API Layer)
provider_slug: agentkey
slug: agentkey-privacy-policy
source_date: '2026-11-09'
source_filename: agentkey-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentkey.app/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentKey (Data API Layer)\naid: agentkey\nurl: https://agentkey.app/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AgentKey acts as a routing layer.\ndata_categories:\n- category: identifying\n  text: When you sign in, we collect your email address, profile image, and a unique identifier issued by our authentication\n    provider.\n- category: financial\n  text: We receive only a customer reference, the amount paid, and the transaction status — never card numbers or\n    CVCs.\n- category: behavioral\n  text: Usage logs. For each API request routed through AgentKey, we record\
  \ the timestamp, endpoint path, HTTP status,\n    response latency, credit cost, and the API key that made the call.\n- category: device\n  text: When you install our CLI or skill plugin, we may receive an anonymous installation identifier and basic\n    telemetry (CLI version, install method)\n- category: communication\n  text: If you contact us by email or community channel, we retain the content of that exchange to respond to and\n    resolve your inquiry.\npurposes:\n- purpose: Authenticate and authorize access\n  text: Authenticate you and authorize your access to the Service;\n- purpose: Route API requests\n  text: Route your API requests to the appropriate Third-Party Provider and return responses;\n- purpose: Metering and billing\n  text: Meter and bill your usage of credits;\n- purpose: Abuse and security\n  text: Detect, prevent, and investigate abuse, fraud, and security incidents;\n- purpose: Product improvement\n  text: Maintain, debug, and improve the Service;\nretention:\n\
  - scope: Account data\n  period: null\n  text: Account data is retained while your account is active.\n- scope: API key hashes\n  period: null\n  text: API key hashes are retained until you revoke the key, plus a short window for audit.\n- scope: Usage logs\n  period: twelve (12) months\n  text: Usage logs are retained for operational and billing reconciliation purposes, typically up to twelve (12)\n    months, then aggregated or deleted.\n- scope: Email open and click records\n  period: twelve (12) months\n  text: Email open and click records are retained for up to twelve (12) months, then deleted.\n- scope: Account deletion\n  period: thirty (30) days\n  text: When you delete your account, we delete or anonymize personal data within thirty (30) days, except where\n    retention is required by law or necessary to resolve a dispute.\nresidency:\n- region: Data-residency restricted sources\n  text: Where a source may only be provided from within a specific jurisdiction, we route those requests\
  \ through\n    infrastructure in that region\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate legal mechanisms (such as Standard Contractual Clauses or equivalent safeguards)\n    where required by applicable law.\nsubprocessors:\n  url: null\n  text: Clerk (clerk.com) — sign-in, session management, and identity.\ndpa:\n  available: null\n  url: null\n  text: Each handles a narrow function, processes data on our behalf under a data processing agreement\ndeletion:\n  route: Dashboard or support@agentkey.app\n  text: delete your account and its associated personal data directly from your dashboard at any time.\nrights:\n- right: Access\n  text: Access the personal data we hold about you;\n- right: Correct\n  text: Correct inaccurate or incomplete personal data;\n- right: Delete\n  text: Delete your personal data, subject to legal retention obligations;\n- right: Portability\n  text: Receive a copy of your data in a portable format;\n- right: Object or restrict\n  text: Restrict\
  \ or object to certain processing;\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent;\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/agentkey/privacy/agentkey-privacy-policy.yml
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
summary_line: 28 quoted statements, read from AgentKey (Data API Layer)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Integration
- Artificial Intelligence
- Automation
---
