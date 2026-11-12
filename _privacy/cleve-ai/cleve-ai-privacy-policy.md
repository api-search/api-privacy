---
api_specs:
- filename: cleve-ai-folders-api-openapi.yml
  format: yaml
  label: Cleve Folders API
  slug: cleve-ai-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-folders-api-openapi.yml
- filename: cleve-ai-notes-api-openapi.yml
  format: yaml
  label: Cleve Notes API
  slug: cleve-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleve-ai/openapi/cleve-ai-notes-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : email address, name, authentication credentials, and subscription status.'
  - category: contact
    text: email address, name, authentication credentials, and subscription status
  - category: financial
    text: 'Payment data : billing metadata (plan, renewal date, payment status).'
  - category: communication
    text: 'Content data : notes, documents, chats, files, and other material you create or upload in Cleve.'
  - category: device
    text: 'Technical data : IP address (approximate location), browser type, and device information.'
  - category: behavioral
    text: 'Usage data : feature interactions, page views, performance metrics, and crash reports.'
  deletion:
    route: Close account; export data before closing
    text: 'When you close your account: Content and personal data is deleted within 30 days.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve features
    text: Provide and improve the features you use (AI writing, search, collaboration).
  - purpose: Authentication and security
    text: Authenticate your account and keep it secure.
  - purpose: Payments
    text: Process payments and manage subscriptions.
  - purpose: Abuse monitoring
    text: Monitor for abuse, errors, and performance issues.
  - purpose: Legal obligations
    text: Comply with legal obligations.
  residency:
  - region: United States
    text: Data is stored in the United States by default.
  - region: EU
    text: EU data residency is available for enterprise customers.
  retention:
  - period: 30 days
    scope: Content and personal data after account closure
    text: Content and personal data is deleted within 30 days.
  - period: 30 to 90 days
    scope: Backups
    text: Backups are purged on a rolling basis (typically 30 to 90 days).
  - period: null
    scope: Billing records
    text: Billing records may be retained longer where required by law.
  rights:
  - right: Access
    text: 'Access : request a copy of the data we hold about you.'
  - right: Correction
    text: 'Correction : update inaccurate or incomplete data.'
  - right: Deletion
    text: 'Deletion : request deletion of your personal data (subject to legal retention requirements).'
  - right: Portability
    text: 'Portability : receive your data in a machine-readable format.'
  - right: Objection / Restriction
    text: 'Objection / Restriction : object to or restrict certain types of processing (EU/UK).'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your content, share it for advertising, or use it to train AI models.
  subprocessors:
    text: A full list of subprocessors is available on our security page .
    url: https://www.cleve.ai/security
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards including Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: EU-US Data Privacy Framework certified providers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cleve
provenance_date: '2026-11-09'
provider_name: Cleve
provider_slug: cleve-ai
slug: cleve-ai-privacy-policy
source_date: '2026-11-09'
source_filename: cleve-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cleve.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cleve\naid: cleve-ai\nurl: https://www.cleve.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data : email address, name, authentication credentials, and subscription status.'\n- category: contact\n  text: email address, name, authentication credentials, and subscription status\n- category: financial\n  text: 'Payment data : billing metadata (plan, renewal date, payment status).'\n- category: communication\n  text: 'Content data : notes, documents, chats, files, and other material you create or upload in Cleve.'\n- category:\
  \ device\n  text: 'Technical data : IP address (approximate location), browser type, and device information.'\n- category: behavioral\n  text: 'Usage data : feature interactions, page views, performance metrics, and crash reports.'\npurposes:\n- purpose: Provide and improve features\n  text: Provide and improve the features you use (AI writing, search, collaboration).\n- purpose: Authentication and security\n  text: Authenticate your account and keep it secure.\n- purpose: Payments\n  text: Process payments and manage subscriptions.\n- purpose: Abuse monitoring\n  text: Monitor for abuse, errors, and performance issues.\n- purpose: Legal obligations\n  text: Comply with legal obligations.\nretention:\n- scope: Content and personal data after account closure\n  period: 30 days\n  text: Content and personal data is deleted within 30 days.\n- scope: Backups\n  period: 30 to 90 days\n  text: Backups are purged on a rolling basis (typically 30 to 90 days).\n- scope: Billing records\n  period:\
  \ null\n  text: Billing records may be retained longer where required by law.\nresidency:\n- region: United States\n  text: Data is stored in the United States by default.\n- region: EU\n  text: EU data residency is available for enterprise customers.\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards including Standard Contractual Clauses (SCCs)\n- mechanism: DPF\n  text: EU-US Data Privacy Framework certified providers\nsubprocessors:\n  url: https://www.cleve.ai/security\n  text: A full list of subprocessors is available on our security page .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Close account; export data before closing\n  text: 'When you close your account: Content and personal data is deleted within 30 days.'\nrights:\n- right: Access\n  text: 'Access : request a copy of the data we hold about you.'\n- right: Correction\n  text: 'Correction : update inaccurate or incomplete data.'\n- right: Deletion\n  text: 'Deletion : request\
  \ deletion of your personal data (subject to legal retention requirements).'\n- right: Portability\n  text: 'Portability : receive your data in a machine-readable format.'\n- right: Objection / Restriction\n  text: 'Objection / Restriction : object to or restrict certain types of processing (EU/UK).'\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your content, share it for advertising, or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/cleve-ai/privacy/cleve-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Cleve's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Writing
- Knowledge Management
- Note Taking
- Collaboration
- Model Context Protocol
- Productivity
---
