---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address, username, and authentication identifiers (managed via Clerk)
  - category: financial
    text: subscription tier, transaction history, and billing details. Card data is collected and stored by Stripe; we do not store full card numbers.
  - category: behavioral
    text: prompts, files, URLs, simulation inputs/outputs, personas, campaigns, audits, and chat messages you create, plus feature-usage and quota metrics
  - category: device
    text: IP address, device/browser information, log data, and approximate location derived from IP
  - category: professional
    text: company name, job title, and preferences you provide
  - category: communication
    text: messages you send to support, sales, or via forms
  deletion:
    route: Email contact@aetherya.ai to exercise erasure rights
    text: Erasure — request deletion (“right to be forgotten”) where applicable
  dpa:
    available: true
    text: our Data Processing Agreement (Art. 28 GDPR), available on request at contact@aetherya.ai
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Provide, operate and maintain the Services; deliver simulations and AI outputs you request
  - purpose: Account management and billing
    text: Account management, authentication, billing and payment processing
  - purpose: Security and fraud prevention
    text: Securing the Services, preventing fraud and abuse, debugging
  - purpose: Improving features
    text: Improving and developing features using aggregated/de-identified data
  residency:
  - region: EU/EEA
    text: We aim to host and process personal data within the EU/EEA.
  retention:
  - period: within 30 days
    scope: Account and content data
    text: Account and content data are deleted or anonymized within a reasonable period after account closure (typically within 30 days, subject to legal retention requirements and backup cycles).
  - period: indefinitely
    scope: Aggregated or de-identified data
    text: Aggregated or de-identified data may be retained indefinitely.
  rights:
  - right: Access
    text: Access — obtain confirmation and a copy of your personal data
  - right: Rectification
    text: Rectification — correct inaccurate or incomplete data
  - right: Erasure
    text: Erasure — request deletion (“right to be forgotten”) where applicable
  - right: Restriction
    text: Restriction — limit processing in certain circumstances
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format
  - right: Object
    text: Object — object to processing based on legitimate interests and to direct marketing at any time
  - right: Withdraw consent
    text: Withdraw consent — at any time, without affecting prior lawful processing
  - right: Complain
    text: Complain to a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data and we do not “share” it for cross-context behavioural advertising
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: primarily the European Commission’s Standard Contractual Clauses (SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aetherya
provenance_date: '2026-11-09'
provider_name: Aetherya
provider_slug: aetherya-ai
slug: aetherya-ai-privacy-policy
source_date: '2026-11-09'
source_filename: aetherya-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aetherya.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aetherya\naid: aetherya-ai\nurl: https://www.aetherya.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name, email address, username, and authentication identifiers (managed via Clerk)\n- category: financial\n  text: subscription tier, transaction history, and billing details. Card data is collected and stored by Stripe;\n    we do not store full card numbers.\n- category: behavioral\n  text: prompts, files, URLs, simulation inputs/outputs, personas, campaigns, audits, and chat messages you create,\n    plus feature-usage and\
  \ quota metrics\n- category: device\n  text: IP address, device/browser information, log data, and approximate location derived from IP\n- category: professional\n  text: company name, job title, and preferences you provide\n- category: communication\n  text: messages you send to support, sales, or via forms\npurposes:\n- purpose: Provide and operate the Services\n  text: Provide, operate and maintain the Services; deliver simulations and AI outputs you request\n- purpose: Account management and billing\n  text: Account management, authentication, billing and payment processing\n- purpose: Security and fraud prevention\n  text: Securing the Services, preventing fraud and abuse, debugging\n- purpose: Improving features\n  text: Improving and developing features using aggregated/de-identified data\nretention:\n- scope: Account and content data\n  period: within 30 days\n  text: Account and content data are deleted or anonymized within a reasonable period after account closure (typically\n\
  \    within 30 days, subject to legal retention requirements and backup cycles).\n- scope: Aggregated or de-identified data\n  period: indefinitely\n  text: Aggregated or de-identified data may be retained indefinitely.\nresidency:\n- region: EU/EEA\n  text: We aim to host and process personal data within the EU/EEA.\ntransfers:\n- mechanism: SCC\n  text: primarily the European Commission’s Standard Contractual Clauses (SCCs)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: our Data Processing Agreement (Art. 28 GDPR), available on request at contact@aetherya.ai\ndeletion:\n  route: Email contact@aetherya.ai to exercise erasure rights\n  text: Erasure — request deletion (“right to be forgotten”) where applicable\nrights:\n- right: Access\n  text: Access — obtain confirmation and a copy of your personal data\n- right: Rectification\n  text: Rectification — correct inaccurate or incomplete data\n- right: Erasure\n  text: Erasure — request deletion\
  \ (“right to be forgotten”) where applicable\n- right: Restriction\n  text: Restriction — limit processing in certain circumstances\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format\n- right: Object\n  text: Object — object to processing based on legitimate interests and to direct marketing at any time\n- right: Withdraw consent\n  text: Withdraw consent — at any time, without affecting prior lawful processing\n- right: Complain\n  text: Complain to a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data and we do not “share” it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/aetherya-ai/privacy/aetherya-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Aetherya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Simulation
- Research
- Enterprise
- Platform
---
