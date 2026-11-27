---
api_specs:
- filename: createmod-com-analytics-api-openapi.yml
  format: yaml
  label: CreateMod.com Analytics API
  slug: createmod-com-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createmod-com/openapi/createmod-com-analytics-api-openapi.yml
- filename: createmod-com-mod-integration-api-openapi.yml
  format: yaml
  label: CreateMod.com Mod Integration API
  slug: createmod-com-mod-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createmod-com/openapi/createmod-com-mod-integration-api-openapi.yml
- filename: createmod-com-schematics-api-openapi.yml
  format: yaml
  label: CreateMod.com Schematics API
  slug: createmod-com-schematics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createmod-com/openapi/createmod-com-schematics-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register, we collect your username, email address and password (stored only as a secure hash).
  - category: financial
    text: 'We receive and keep only what we need to run your membership: your Stripe customer and subscription IDs, the plan, its status and renewal dates, and records of refunds and disputes.'
  - category: device
    text: Like most websites, we and our providers process your IP address, browser and device details, the pages you visit and when.
  - category: communication
    text: Messages you exchange with moderators about your content are visible only to you and the moderators.
  deletion:
    route: Contact by email for rights requests
    text: To exercise any of these rights, please contact us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the Site and membership
    text: Provide, maintain, and improve the Site, including your account and membership (to perform our contract with you).
  - purpose: Safety and fraud prevention
    text: 'Keep the Site and its users safe: moderating content, preventing spam, scraping and fraud (our legitimate interest).'
  - purpose: Emails you request or account notices
    text: Send the emails you ask for, such as notifications, and important messages about your account or membership.
  residency:
  - region: European Union
    text: Your personal data is stored and processed mainly within the European Union.
  - region: Germany
    text: 'Hosted in: Germany'
  retention:
  - period: while your account exists
    scope: Account data
    text: We keep your account data while your account exists.
  - period: as long as accounting and tax law requires
    scope: Membership and payment records
    text: Membership and payment records are kept as long as accounting and tax law requires.
  - period: 90 days
    scope: Modpack search lists
    text: it is deleted after 90 days without use.
  rights:
  - right: Access, correction, deletion
    text: The right to access, correct, or delete your personal data.
  - right: Objection, restriction, consent withdrawal
    text: The right to object to or restrict the processing of your personal data, and to withdraw consent at any time.
  - right: Data portability
    text: The right to data portability.
  - right: Complaint to supervisory authority
    text: The right to lodge a complaint with a supervisory authority, such as the Swedish Authority for Privacy Protection (IMY).
  role:
    text: 'Data Controller: CreateMod.com'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information to third parties.
  subprocessors:
    text: Hetzner, our hosting provider in Germany, which runs the Site and its database.
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission's standard contractual clauses
  - mechanism: DPF
    text: the EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CreateMod.com
provenance_date: '2026-11-09'
provider_name: CreateMod.com
provider_slug: createmod-com
slug: createmod-com-privacy-policy
source_date: '2026-11-09'
source_filename: createmod-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://createmod.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CreateMod.com\naid: createmod-com\nurl: https://createmod.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller: CreateMod.com'\ndata_categories:\n- category: identifying\n  text: When you register, we collect your username, email address and password (stored only as a secure hash).\n- category: financial\n  text: 'We receive and keep only what we need to run your membership: your Stripe customer and subscription IDs,\n    the plan, its status and renewal dates, and records of refunds and disputes.'\n- category: device\n  text: Like most websites, we and our providers\
  \ process your IP address, browser and device details, the pages\n    you visit and when.\n- category: communication\n  text: Messages you exchange with moderators about your content are visible only to you and the moderators.\npurposes:\n- purpose: Provide and improve the Site and membership\n  text: Provide, maintain, and improve the Site, including your account and membership (to perform our contract\n    with you).\n- purpose: Safety and fraud prevention\n  text: 'Keep the Site and its users safe: moderating content, preventing spam, scraping and fraud (our legitimate\n    interest).'\n- purpose: Emails you request or account notices\n  text: Send the emails you ask for, such as notifications, and important messages about your account or membership.\nretention:\n- scope: Account data\n  period: while your account exists\n  text: We keep your account data while your account exists.\n- scope: Membership and payment records\n  period: as long as accounting and tax law requires\n  text:\
  \ Membership and payment records are kept as long as accounting and tax law requires.\n- scope: Modpack search lists\n  period: 90 days\n  text: it is deleted after 90 days without use.\nresidency:\n- region: European Union\n  text: Your personal data is stored and processed mainly within the European Union.\n- region: Germany\n  text: 'Hosted in: Germany'\ntransfers:\n- mechanism: SCC\n  text: the European Commission's standard contractual clauses\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: Hetzner, our hosting provider in Germany, which runs the Site and its database.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact by email for rights requests\n  text: To exercise any of these rights, please contact us at [email protected] .\nrights:\n- right: Access, correction, deletion\n  text: The right to access, correct, or delete your personal data.\n- right: Objection, restriction, consent withdrawal\n  text:\
  \ The right to object to or restrict the processing of your personal data, and to withdraw consent at any\n    time.\n- right: Data portability\n  text: The right to data portability.\n- right: Complaint to supervisory authority\n  text: The right to lodge a complaint with a supervisory authority, such as the Swedish Authority for Privacy Protection\n    (IMY).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/createmod-com/privacy/createmod-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from CreateMod.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Minecraft
- Gaming
- Schematics
- Create Mod
- Community
- User Generated Content
- REST API
---
