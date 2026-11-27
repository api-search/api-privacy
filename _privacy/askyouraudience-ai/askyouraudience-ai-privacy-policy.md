---
api_specs:
- filename: askyouraudience-ai-openapi-generated.yml
  format: yaml
  label: Ask Your Audience API
  slug: askyouraudience-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askyouraudience-ai/openapi/_ae-authored/askyouraudience-ai-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address, authentication records, workspace, role and preferences.'
  - category: location
    text: 'Website and device data: pages visited, approximate location derived from IP address, browser, device, referrer and performance information.'
  - category: financial
    text: 'Commercial data: plan, transaction status, invoices and limited payment metadata.'
  - category: communication
    text: 'Communications: support requests, feedback and other messages you send us.'
  - category: behavioral
    text: With analytics consent, we record approved campaign tags, the referring-site origin, a privacy-safe landing path and visit times against a random first-party browser identifier.
  deletion:
    route: email privacy@askyouraudience.ai
    text: You can ask about a specific record or request deletion at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Snapshot and platform services
    text: Provide Snapshot and platform services Questions, account and research content Contract, or steps requested before a contract
  - purpose: Improve product performance
    text: Improve product performance Consented analytics and feedback Consent for non-essential storage; legitimate interests where no storage/access rule applies
  retention:
  - period: short-lived or removed when the flow completes
    scope: Snapshot recovery and creator-claim values in browser
    text: Snapshot recovery and creator-claim values stored in your browser are short-lived or removed when the flow completes.
  - period: while the account is active and for a limited period afterwards
    scope: Account and workspace data
    text: Account and workspace data is generally kept while the account is active and for a limited period afterwards where needed for recovery, security or legal claims.
  - period: period required by tax and accounting law
    scope: Billing records
    text: Billing records may be kept for the period required by tax and accounting law.
  rights:
  - right: access, correct, delete, restrict or transfer
    text: you may ask us to access, correct, delete, restrict or transfer your personal data
  - right: object to processing
    text: object to processing
  - right: withdraw consent
    text: withdraw consent
  - right: complain to supervisory authority
    text: complain to a supervisory authority
  role:
    text: AYA is the controller for website, account, billing, security and direct customer-relationship data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use advertising trackers on the AYA public website.
  subprocessors:
    text: 'Our principal service categories include: Supabase for authentication, databases, storage and realtime infrastructure;'
    url: null
  transfers:
  - mechanism: adequacy
    text: we use an adequacy decision
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses
  - mechanism: other
    text: the UK International Data Transfer Addendum, or another valid safeguard
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ask Your Audience
provenance_date: '2026-11-09'
provider_name: Ask Your Audience
provider_slug: askyouraudience-ai
slug: askyouraudience-ai-privacy-policy
source_date: '2026-11-09'
source_filename: askyouraudience-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.askyouraudience.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ask Your Audience\naid: askyouraudience-ai\nurl: https://www.askyouraudience.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: AYA is the controller for website, account, billing, security and direct customer-relationship data.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address, authentication records, workspace, role and preferences.'\n- category: location\n  text: 'Website and device data: pages visited, approximate location derived from IP address, browser, device,\n    referrer and performance information.'\n- category: financial\n  text: 'Commercial\
  \ data: plan, transaction status, invoices and limited payment metadata.'\n- category: communication\n  text: 'Communications: support requests, feedback and other messages you send us.'\n- category: behavioral\n  text: With analytics consent, we record approved campaign tags, the referring-site origin, a privacy-safe landing\n    path and visit times against a random first-party browser identifier.\npurposes:\n- purpose: Provide Snapshot and platform services\n  text: Provide Snapshot and platform services Questions, account and research content Contract, or steps requested\n    before a contract\n- purpose: Improve product performance\n  text: Improve product performance Consented analytics and feedback Consent for non-essential storage; legitimate\n    interests where no storage/access rule applies\nretention:\n- scope: Snapshot recovery and creator-claim values in browser\n  period: short-lived or removed when the flow completes\n  text: Snapshot recovery and creator-claim values stored\
  \ in your browser are short-lived or removed when the flow\n    completes.\n- scope: Account and workspace data\n  period: while the account is active and for a limited period afterwards\n  text: Account and workspace data is generally kept while the account is active and for a limited period afterwards\n    where needed for recovery, security or legal claims.\n- scope: Billing records\n  period: period required by tax and accounting law\n  text: Billing records may be kept for the period required by tax and accounting law.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: we use an adequacy decision\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses\n- mechanism: other\n  text: the UK International Data Transfer Addendum, or another valid safeguard\nsubprocessors:\n  url: null\n  text: 'Our principal service categories include: Supabase for authentication, databases, storage and realtime\n    infrastructure;'\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: email privacy@askyouraudience.ai\n  text: You can ask about a specific record or request deletion at any time.\nrights:\n- right: access, correct, delete, restrict or transfer\n  text: you may ask us to access, correct, delete, restrict or transfer your personal data\n- right: object to processing\n  text: object to processing\n- right: withdraw consent\n  text: withdraw consent\n- right: complain to supervisory authority\n  text: complain to a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use advertising trackers on the AYA public website.\n"
source_yaml_url: https://artifacts.apis.io/askyouraudience-ai/privacy/askyouraudience-ai-privacy-policy.yml
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
summary_line: 21 quoted statements, read from Ask Your Audience's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- AudienceResearch
- MarketTesting
- Digital Twin
---
