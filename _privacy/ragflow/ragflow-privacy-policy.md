---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and profile information: name, email, username, authentication credentials (hashed), organization name, role/title.'
  - category: financial
    text: 'Billing and transactional information: billing contact details, invoices, subscription plan, payment method details (typically processed by a third-party payment provider).'
  - category: device
    text: 'Device and usage data: IP address, device identifiers, browser type, OS, language, referring URLs, pages viewed, timestamps, clickstream, and diagnostics.'
  - category: communication
    text: 'Support and communications: content of messages, tickets, feedback, recordings, and attachments you provide to support.'
  - category: other
    text: Documents and files you upload or connect (for example PDF, Word, spreadsheet, presentation, image, audio and web pages), together with parsed text, extracted tables, generated chunks, embeddings and metadata
  deletion:
    route: Email privacy@ragflow.io from the address associated with your account
    text: 'Delete your account and data: email privacy@ragflow.io from the address associated with your account. We verify the request and then delete or de-identify the associated Personal Data'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Services
    text: Parse and index your content, embed it, and generate answers and agent responses using the models you configure
  - purpose: Improve and protect the Services
    text: Debug, monitor performance, analyze usage, and improve features
  - purpose: Marketing
    text: Send product updates, newsletters, and promotional messages (subject to your preferences and applicable law)
  - purpose: Legal compliance
    text: Meet legal obligations and respond to lawful requests
  retention:
  - period: 30 days
    scope: Account and imported data
    text: Account and imported data are deleted within 30 days of a verified request
  - period: 90 days
    scope: Encrypted backups
    text: 'Backups: residual copies may persist in encrypted backups for up to 90 days before being deleted in the ordinary course.'
  rights:
  - right: Access, correction, deletion
    text: Access, correction, deletion
  - right: Restriction or objection
    text: Restriction or objection
  - right: Data portability
    text: Data portability
  - right: Withdraw consent
    text: Withdraw consent (where processing is based on consent)
  role:
    text: For Personal Data we collect for our own purposes (e.g., account administration, billing, website analytics), RAGFlow typically acts as a data controller (or equivalent role under applicable law).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell Personal Data, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: A current list of subprocessors for Customer Data is available in our Data Processing Agreement or on request.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use appropriate safeguards (such as Standard Contractual Clauses or equivalent transfer mechanisms)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RAGFlow
provenance_date: '2026-11-10'
provider_name: RAGFlow
provider_slug: ragflow
slug: ragflow-privacy-policy
source_date: '2026-11-10'
source_filename: ragflow-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ragflow.io/policies/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RAGFlow\naid: ragflow\nurl: https://ragflow.io/policies/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For Personal Data we collect for our own purposes (e.g., account administration, billing, website analytics),\n    RAGFlow typically acts as a data controller (or equivalent role under applicable law).\ndata_categories:\n- category: identifying\n  text: 'Account and profile information: name, email, username, authentication credentials (hashed), organization\n    name, role/title.'\n- category: financial\n  text: 'Billing and transactional information: billing contact details, invoices,\
  \ subscription plan, payment method\n    details (typically processed by a third-party payment provider).'\n- category: device\n  text: 'Device and usage data: IP address, device identifiers, browser type, OS, language, referring URLs, pages\n    viewed, timestamps, clickstream, and diagnostics.'\n- category: communication\n  text: 'Support and communications: content of messages, tickets, feedback, recordings, and attachments you provide\n    to support.'\n- category: other\n  text: Documents and files you upload or connect (for example PDF, Word, spreadsheet, presentation, image, audio\n    and web pages), together with parsed text, extracted tables, generated chunks, embeddings and metadata\npurposes:\n- purpose: Provide and operate the Services\n  text: Parse and index your content, embed it, and generate answers and agent responses using the models you configure\n- purpose: Improve and protect the Services\n  text: Debug, monitor performance, analyze usage, and improve features\n\
  - purpose: Marketing\n  text: Send product updates, newsletters, and promotional messages (subject to your preferences and applicable\n    law)\n- purpose: Legal compliance\n  text: Meet legal obligations and respond to lawful requests\nretention:\n- scope: Account and imported data\n  period: 30 days\n  text: Account and imported data are deleted within 30 days of a verified request\n- scope: Encrypted backups\n  period: 90 days\n  text: 'Backups: residual copies may persist in encrypted backups for up to 90 days before being deleted in the\n    ordinary course.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we use appropriate safeguards (such as Standard Contractual Clauses or equivalent transfer\n    mechanisms)\nsubprocessors:\n  url: null\n  text: A current list of subprocessors for Customer Data is available in our Data Processing Agreement or on request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@ragflow.io from\
  \ the address associated with your account\n  text: 'Delete your account and data: email privacy@ragflow.io from the address associated with your account. We\n    verify the request and then delete or de-identify the associated Personal Data'\nrights:\n- right: Access, correction, deletion\n  text: Access, correction, deletion\n- right: Restriction or objection\n  text: Restriction or objection\n- right: Data portability\n  text: Data portability\n- right: Withdraw consent\n  text: Withdraw consent (where processing is based on consent)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell Personal Data, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/ragflow/privacy/ragflow-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from RAGFlow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- RAG
- Search
- Vector Search
- Document Processing
- Knowledge Management
- Agents
- Open Source
- LLM
- MCP
---
