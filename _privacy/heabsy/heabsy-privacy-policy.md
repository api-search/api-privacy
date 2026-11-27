---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'When you sign in: email, name, profile picture (via Google or your organisation''s single sign-on)'
  - category: contact
    text: 'When you use the Heabsy Platform API: organisation name, contact email, API key identifiers (keys are stored hashed)'
  - category: behavioral
    text: Pages visited, time spent, referrer
  - category: device
    text: Browser type, operating system, device type
  - category: location
    text: IP address (via Cloudflare logs)
  - category: communication
    text: 'When you use chat: conversation content'
  - category: financial
    text: Accounting & tax Financial records
  deletion:
    route: Email privacy@heabsy.com to exercise erasure rights
    text: To exercise these rights, email privacy@heabsy.com
  dpa:
    available: true
    text: Our processing of that content is governed by our Data Processing Addendum (GDPR Art. 28)
    url: null
  purposes:
  - purpose: Provide the Service (incl. inference)
    text: Provide the Service (incl. inference) Account and usage metadata Art. 6(1)(b) — contract
  - purpose: Security monitoring and abuse prevention
    text: Security monitoring & abuse prevention IP, User-Agent, access logs
  - purpose: Advertising measurement and remarketing
    text: Advertising measurement, remarketing and session analytics (Google Ads, Microsoft Advertising, Microsoft Clarity, Meta, Reddit)
  - purpose: Training on customer prompts and completions
    text: We do not use prompts or completions processed on Heabsy infrastructure to train, fine-tune, or improve models.
  residency:
  - region: EEA or United States
    text: Inference on models served on Heabsy infrastructure runs in data centres in the European Economic Area or the United States.
  - region: EEA (EU-only setting)
    text: If you set your organisation or API key to EU-only processing (data region "EEA"), we process those requests only in data centres within the EEA
  retention:
  - period: Not persisted
    scope: Prompt / completion content (Heabsy-served models)
    text: Not persisted — processed in memory only for the duration of the request
  - period: 10 years
    scope: Usage metadata and financial records
    text: Usage metadata & financial records 10 years (Slovak accounting/tax law)
  - period: 30 days
    scope: Application logs
    text: Application logs 30 days
  - period: 1 year
    scope: Security audit logs
    text: Security audit logs 1 year
  - period: Until you delete the account
    scope: Account
    text: Account Until you delete the account
  rights:
  - right: access
    text: you have the right to access, rectify, erase, restrict, port, and object to processing of your data
  - right: withdraw consent
    text: and to withdraw consent where consent is the basis
  - right: complaint
    text: You may also lodge a complaint with the Office for Personal Data Protection of the Slovak Republic (dataprotection.gov.sk) or with your local supervisory authority.
  role:
    text: For the heabsy.com website and account sign-in , we act as a data controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data.
  subprocessors:
    text: A current list of sub-processors is available on request.
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers to data centres in the United States rely on the EU-US Data Privacy Framework or Standard Contractual Clauses with a transfer-impact assessment.
  - mechanism: SCC
    text: Transfers to data centres in the United States rely on the EU-US Data Privacy Framework or Standard Contractual Clauses with a transfer-impact assessment.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Heabsy
provenance_date: '2026-11-09'
provider_name: Heabsy
provider_slug: heabsy
slug: heabsy-privacy-policy
source_date: '2026-11-09'
source_filename: heabsy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://heabsy.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Heabsy\naid: heabsy\nurl: https://heabsy.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the heabsy.com website and account sign-in , we act as a data controller\ndata_categories:\n- category: identifying\n  text: 'When you sign in: email, name, profile picture (via Google or your organisation''s single sign-on)'\n- category: contact\n  text: 'When you use the Heabsy Platform API: organisation name, contact email, API key identifiers (keys are stored\n    hashed)'\n- category: behavioral\n  text: Pages visited, time spent, referrer\n- category: device\n  text: Browser type, operating\
  \ system, device type\n- category: location\n  text: IP address (via Cloudflare logs)\n- category: communication\n  text: 'When you use chat: conversation content'\n- category: financial\n  text: Accounting & tax Financial records\npurposes:\n- purpose: Provide the Service (incl. inference)\n  text: Provide the Service (incl. inference) Account and usage metadata Art. 6(1)(b) — contract\n- purpose: Security monitoring and abuse prevention\n  text: Security monitoring & abuse prevention IP, User-Agent, access logs\n- purpose: Advertising measurement and remarketing\n  text: Advertising measurement, remarketing and session analytics (Google Ads, Microsoft Advertising, Microsoft\n    Clarity, Meta, Reddit)\n- purpose: Training on customer prompts and completions\n  text: We do not use prompts or completions processed on Heabsy infrastructure to train, fine-tune, or improve\n    models.\nretention:\n- scope: Prompt / completion content (Heabsy-served models)\n  period: Not persisted\n  text:\
  \ Not persisted — processed in memory only for the duration of the request\n- scope: Usage metadata and financial records\n  period: 10 years\n  text: Usage metadata & financial records 10 years (Slovak accounting/tax law)\n- scope: Application logs\n  period: 30 days\n  text: Application logs 30 days\n- scope: Security audit logs\n  period: 1 year\n  text: Security audit logs 1 year\n- scope: Account\n  period: Until you delete the account\n  text: Account Until you delete the account\nresidency:\n- region: EEA or United States\n  text: Inference on models served on Heabsy infrastructure runs in data centres in the European Economic Area or\n    the United States.\n- region: EEA (EU-only setting)\n  text: If you set your organisation or API key to EU-only processing (data region \"EEA\"), we process those requests\n    only in data centres within the EEA\ntransfers:\n- mechanism: DPF\n  text: Transfers to data centres in the United States rely on the EU-US Data Privacy Framework or Standard\
  \ Contractual\n    Clauses with a transfer-impact assessment.\n- mechanism: SCC\n  text: Transfers to data centres in the United States rely on the EU-US Data Privacy Framework or Standard Contractual\n    Clauses with a transfer-impact assessment.\nsubprocessors:\n  url: null\n  text: A current list of sub-processors is available on request.\ndpa:\n  available: true\n  url: null\n  text: Our processing of that content is governed by our Data Processing Addendum (GDPR Art. 28)\ndeletion:\n  route: Email privacy@heabsy.com to exercise erasure rights\n  text: To exercise these rights, email privacy@heabsy.com\nrights:\n- right: access\n  text: you have the right to access, rectify, erase, restrict, port, and object to processing of your data\n- right: withdraw consent\n  text: and to withdraw consent where consent is the basis\n- right: complaint\n  text: You may also lodge a complaint with the Office for Personal Data Protection of the Slovak Republic (dataprotection.gov.sk)\n    or with\
  \ your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data.\n"
source_yaml_url: https://artifacts.apis.io/heabsy/privacy/heabsy-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Heabsy's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Inference
- OpenAI-Compatible
- EU-regulated
- Software-as-a-Service
---
