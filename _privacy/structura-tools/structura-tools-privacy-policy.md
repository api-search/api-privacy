---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — name, email, organisation, authentication identifiers, and (for paid tiers) billing details processed by our payment provider.
  - category: behavioral
    text: Operational data — request logs (timestamp, tool or endpoint, account id, outcome, IP, user-agent) for security, debugging, abuse prevention and service metering.
  - category: other
    text: Model content submitted through the connector — domain-model or text your MCP client or agent sends to the connector's tools.
  deletion:
    route: Web app or connector delete_project tool; or email support@structura.tools
    text: Models and projects — until you delete them (in the web app or via the connector's delete_project tool).
  dpa:
    available: null
    text: We use service providers to run Structura, under data-processing agreements and instructions
    url: null
  purposes:
  - purpose: Provide service and perform contract
    text: To provide the Service and perform our contract with you — performance of a contract .
  - purpose: Security, abuse prevention, metering and debugging
    text: To secure the Service, prevent abuse, meter usage and debug — legitimate interests .
  - purpose: Service improvement
    text: To improve the Service using aggregated, de-identified statistics — legitimate interests .
  - purpose: Billing and tax records
    text: For billing and tax records (paid tiers) — legal obligation / contract .
  retention:
  - period: 12 months
    scope: Account data
    text: Account data — for the life of the account, then deleted or anonymised within 12 months , except records we must keep for legal reasons (e.g. invoices).
  - period: 3 months
    scope: Generation artifacts
    text: Generation artifacts — while the job record exists, then removed within 3 months .
  - period: 12 months
    scope: Operational logs
    text: Operational logs — 12 months .
  rights:
  - right: access
    text: you may request access, rectification, erasure, restriction, portability, and object to processing based on legitimate interests
  - right: withdraw consent
    text: and withdraw consent where processing is consent-based.
  - right: complain to authority
    text: You may also lodge a complaint with the Spanish Data Protection Agency (AEPD, www.aepd.es ) or your local authority.
  role:
    text: The controller of your personal data is Metadev S.L. , Bormujos, Sevilla, Spain .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: A current list is available on request at support@structura.tools .
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a provider processes data outside the EEA (European Economic Area), we rely on an adequacy decision or on Standard Contractual Clauses with appropriate safeguards.
  - mechanism: SCC
    text: Where a provider processes data outside the EEA (European Economic Area), we rely on an adequacy decision or on Standard Contractual Clauses with appropriate safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Structura
provenance_date: '2026-11-10'
provider_name: Structura
provider_slug: structura-tools
slug: structura-tools-privacy-policy
source_date: '2026-11-10'
source_filename: structura-tools-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://structura.tools/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Structura\naid: structura-tools\nurl: https://structura.tools/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is Metadev S.L. , Bormujos, Sevilla, Spain .\ndata_categories:\n- category: identifying\n  text: Account data — name, email, organisation, authentication identifiers, and (for paid tiers) billing details\n    processed by our payment provider.\n- category: behavioral\n  text: Operational data — request logs (timestamp, tool or endpoint, account id, outcome, IP, user-agent) for security,\n    debugging, abuse prevention and service metering.\n\
  - category: other\n  text: Model content submitted through the connector — domain-model or text your MCP client or agent sends to the\n    connector's tools.\npurposes:\n- purpose: Provide service and perform contract\n  text: To provide the Service and perform our contract with you — performance of a contract .\n- purpose: Security, abuse prevention, metering and debugging\n  text: To secure the Service, prevent abuse, meter usage and debug — legitimate interests .\n- purpose: Service improvement\n  text: To improve the Service using aggregated, de-identified statistics — legitimate interests .\n- purpose: Billing and tax records\n  text: For billing and tax records (paid tiers) — legal obligation / contract .\nretention:\n- scope: Account data\n  period: 12 months\n  text: Account data — for the life of the account, then deleted or anonymised within 12 months , except records\n    we must keep for legal reasons (e.g. invoices).\n- scope: Generation artifacts\n  period: 3 months\n  text:\
  \ Generation artifacts — while the job record exists, then removed within 3 months .\n- scope: Operational logs\n  period: 12 months\n  text: Operational logs — 12 months .\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where a provider processes data outside the EEA (European Economic Area), we rely on an adequacy decision\n    or on Standard Contractual Clauses with appropriate safeguards.\n- mechanism: SCC\n  text: Where a provider processes data outside the EEA (European Economic Area), we rely on an adequacy decision\n    or on Standard Contractual Clauses with appropriate safeguards.\nsubprocessors:\n  url: null\n  text: A current list is available on request at support@structura.tools .\ndpa:\n  available: null\n  url: null\n  text: We use service providers to run Structura, under data-processing agreements and instructions\ndeletion:\n  route: Web app or connector delete_project tool; or email support@structura.tools\n  text: Models and projects — until you delete them\
  \ (in the web app or via the connector's delete_project tool).\nrights:\n- right: access\n  text: you may request access, rectification, erasure, restriction, portability, and object to processing based\n    on legitimate interests\n- right: withdraw consent\n  text: and withdraw consent where processing is consent-based.\n- right: complain to authority\n  text: You may also lodge a complaint with the Spanish Data Protection Agency (AEPD, www.aepd.es ) or your local\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/structura-tools/privacy/structura-tools-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Structura's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Code Generation
- Domain Modeling
- UML
- Software Architecture
- Low-Code
- Compliance
- MCP
---
