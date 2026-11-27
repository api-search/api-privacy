---
api_specs:
- filename: eurocomply-app-mcp-tools.json
  format: json
  label: EuroComply MCP API
  slug: eurocomply-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eurocomply-app/openapi/eurocomply-app-mcp-tools.json
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Email, name
  - category: identifying
    text: Google Account Data (email, name, profile picture)
  - category: behavioral
    text: Anonymised usage statistics
  - category: communication
    text: Chat messages
  deletion:
    route: Settings → Data or privacy@eurocomply.app
    text: Erasure (Art. 17) — request deletion. Available in Settings → Data.
  dpa:
    available: true
    text: A DPA incorporating the standard EU SCCs (controller-to-processor) is available on request at privacy@eurocomply.app at no cost for all paid-tier customers.
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: Account creation, authentication, transactional emails
  - purpose: Regulatory newsletter
    text: Regulatory intelligence newsletter
  - purpose: Sovereignty scoring
    text: Sovereignty scoring, EU alternative recommendations
  residency:
  - region: EU / EEA
    text: We seek to keep all personal data within the EEA or in countries with an EU adequacy decision.
  retention:
  - period: Duration of account + 30 days after deletion
    scope: Account data
    text: Account data (name, email) Duration of account + 30 days after deletion
  - period: 12 months
    scope: Chat messages
    text: Chat messages 12 months, then automatically deleted
  - period: 10 years from transaction date
    scope: Billing transaction records
    text: Billing transaction records 10 years from transaction date
  - period: within 90 days
    scope: Database backups
    text: Database backups containing personal data are purged within 90 days.
  rights:
  - right: Access
    text: Access (Art. 15) — obtain confirmation of processing and a copy of your data.
  - right: Rectification
    text: Rectification (Art. 16) — correct inaccurate data.
  - right: Portability
    text: Data portability (Art. 20) — receive your data in a machine-readable format (JSON).
  - right: Objection
    text: Objection (Art. 21) — object to processing based on legitimate interest (including analytics).
  role:
    text: Brevio Ventures is the data controller within the meaning of Article 4(7) GDPR.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A current sub-processor list is available on request at privacy@eurocomply.app .
    url: null
  transfers:
  - mechanism: SCC
    text: Where sub-processors are incorporated in third countries, we rely on Standard Contractual Clauses (SCCs) approved by the European Commission under Art. 46(2)(c) GDPR
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EuroComply
provenance_date: '2026-11-09'
provider_name: EuroComply
provider_slug: eurocomply-app
slug: eurocomply-app-privacy-policy
source_date: '2026-11-09'
source_filename: eurocomply-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eurocomply.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EuroComply\naid: eurocomply-app\nurl: https://eurocomply.app/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Brevio Ventures is the data controller within the meaning of Article 4(7) GDPR.\ndata_categories:\n- category: contact\n  text: Email, name\n- category: identifying\n  text: Google Account Data (email, name, profile picture)\n- category: behavioral\n  text: Anonymised usage statistics\n- category: communication\n  text: Chat messages\npurposes:\n- purpose: Account creation and authentication\n  text: Account creation, authentication, transactional emails\n- purpose: Regulatory\
  \ newsletter\n  text: Regulatory intelligence newsletter\n- purpose: Sovereignty scoring\n  text: Sovereignty scoring, EU alternative recommendations\nretention:\n- scope: Account data\n  period: Duration of account + 30 days after deletion\n  text: Account data (name, email) Duration of account + 30 days after deletion\n- scope: Chat messages\n  period: 12 months\n  text: Chat messages 12 months, then automatically deleted\n- scope: Billing transaction records\n  period: 10 years from transaction date\n  text: Billing transaction records 10 years from transaction date\n- scope: Database backups\n  period: within 90 days\n  text: Database backups containing personal data are purged within 90 days.\nresidency:\n- region: EU / EEA\n  text: We seek to keep all personal data within the EEA or in countries with an EU adequacy decision.\ntransfers:\n- mechanism: SCC\n  text: Where sub-processors are incorporated in third countries, we rely on Standard Contractual Clauses (SCCs)\n    approved\
  \ by the European Commission under Art. 46(2)(c) GDPR\nsubprocessors:\n  url: null\n  text: A current sub-processor list is available on request at privacy@eurocomply.app .\ndpa:\n  available: true\n  url: null\n  text: A DPA incorporating the standard EU SCCs (controller-to-processor) is available on request at privacy@eurocomply.app\n    at no cost for all paid-tier customers.\ndeletion:\n  route: Settings → Data or privacy@eurocomply.app\n  text: Erasure (Art. 17) — request deletion. Available in Settings → Data.\nrights:\n- right: Access\n  text: Access (Art. 15) — obtain confirmation of processing and a copy of your data.\n- right: Rectification\n  text: Rectification (Art. 16) — correct inaccurate data.\n- right: Portability\n  text: Data portability (Art. 20) — receive your data in a machine-readable format (JSON).\n- right: Objection\n  text: Objection (Art. 21) — object to processing based on legitimate interest (including analytics).\nsale_or_sharing:\n  stance: unstated\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/eurocomply-app/privacy/eurocomply-app-privacy-policy.yml
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
summary_line: 21 quoted statements, read from EuroComply's own page on 2026-11-09.
synthetic: false
tags:
- AI Act
- GDPR
- NIS2
- DORA
- RegTech
---
