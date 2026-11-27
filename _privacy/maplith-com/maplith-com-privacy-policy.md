---
api_specs:
- filename: maplith-com-openapi-generated.yml
  format: yaml
  label: maplith-com API
  slug: maplith-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maplith-com/openapi/_ae-authored/maplith-com-openapi-generated.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address, name, the identity provider''s user identifier if you sign in with Google, Microsoft or GitHub'
  - category: contact
    text: 'Sales contacts: your name, company, role and contact details, and notes from our conversations about your company possibly becoming a customer'
  - category: financial
    text: 'Payment and billing data (not live): billing identity, invoices, payment status'
  - category: behavioral
    text: the pages you view, how you arrived (the referring site and the campaign tags on the link you followed)
  - category: device
    text: technical details of your browser and device (such as their type and version, language, time zone and screen size)
  - category: communication
    text: 'Correspondence: what you write to frp@maplith.com and Maplith''s other addresses, and what we reply'
  - category: other
    text: 'Operational logs: request metadata and IP addresses at the edge and in the application'
  deletion:
    route: email request to frp@maplith.com
    text: 'Deleting your account or your organisation is not yet self-service: write to frp@maplith.com, and Maplith''s operator carries it out within 30 days and confirms in writing.'
  dpa:
    available: true
    text: the Data Processing Agreement and the Processing and security description apply
    url: null
  purposes:
  - purpose: account sign-in and workspace membership
    text: Sign-in (one-time links or single sign-on), workspace membership, roles and grants
  - purpose: security, abuse prevention and product use
    text: Security, abuse prevention, fair-use caps, audit of agent actions on the customer's behalf, and understanding how the product is used
  - purpose: following up possible customers
    text: Following up a possible customer relationship
  - purpose: Maplith Bridge updates
    text: Sending security notices and release news about Maplith Bridge to the people who asked for them
  residency:
  - region: EU (hosting, database, file storage)
    text: 'Hosting, database and file storage run in the EU: Supabase (Frankfurt) and Railway (EU West, Amsterdam)'
  - region: United States (AI model inference)
    text: model inference runs in the United States
  retention:
  - period: While your account exists
    scope: account data
    text: While your account exists.
  - period: 12 months
    scope: funnel events, agent-key and MCP usage, assistant usage, agent-action audit rows
    text: 12 months from the event, or until the workspace is deleted, whichever is earlier
  - period: 2 years
    scope: Maplith Bridge consent proof
    text: keeps a proof of your consent for 2 years
  - period: 12 months
    scope: questions to the demo company
    text: One usage row per question (time, model, tokens, cost) and a daily count of the demo's calls, 12 months each
  - period: At most 13 months
    scope: website analytics with consent
    text: 'At most 13 months: Maplith deletes them at least once a year.'
  - period: 24 months after the last contact or change to the record
    scope: sales contacts
    text: 24 months after the last contact or change to the record
  - period: 5 years after the end of the financial year
    scope: billing data
    text: 5 years after the end of the financial year, as the Danish Bookkeeping Act requires
  rights:
  - right: access
    text: you can ask Maplith for access to your personal data
  - right: correction, deletion, restriction
    text: for correction, for deletion, for restriction of processing
  - right: portability
    text: for a copy of the data you gave us in a machine-readable form (portability)
  - right: objection
    text: you can object to processing based on legitimate interest, including at any time to direct marketing
  - right: complaint
    text: You can complain to Datatilsynet, the Danish supervisory authority
  role:
    text: 'Data controller: Maplith ApS, CVR 46843290, Ørnekulsvej 15, 2920 Charlottenlund, Denmark.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data.
  subprocessors:
    text: The sub-processor list lists every provider, what it receives, where it processes it and on what basis.
    url: null
  transfers:
  - mechanism: SCC
    text: under its data processing addendum with the standard contractual clauses
  - mechanism: DPF
    text: Cal.com, Inc. processes in the United States and states that it relies on the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: maplith-com
provenance_date: '2026-11-10'
provider_name: maplith-com
provider_slug: maplith-com
slug: maplith-com-privacy-policy
source_date: '2026-11-10'
source_filename: maplith-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://maplith.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: maplith-com\naid: maplith-com\nurl: https://maplith.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Data controller: Maplith ApS, CVR 46843290, Ørnekulsvej 15, 2920 Charlottenlund, Denmark.'\ndata_categories:\n- category: identifying\n  text: 'Account data: email address, name, the identity provider''s user identifier if you sign in with Google,\n    Microsoft or GitHub'\n- category: contact\n  text: 'Sales contacts: your name, company, role and contact details, and notes from our conversations about your\n    company possibly becoming a customer'\n- category: financial\n  text: 'Payment\
  \ and billing data (not live): billing identity, invoices, payment status'\n- category: behavioral\n  text: the pages you view, how you arrived (the referring site and the campaign tags on the link you followed)\n- category: device\n  text: technical details of your browser and device (such as their type and version, language, time zone and screen\n    size)\n- category: communication\n  text: 'Correspondence: what you write to frp@maplith.com and Maplith''s other addresses, and what we reply'\n- category: other\n  text: 'Operational logs: request metadata and IP addresses at the edge and in the application'\npurposes:\n- purpose: account sign-in and workspace membership\n  text: Sign-in (one-time links or single sign-on), workspace membership, roles and grants\n- purpose: security, abuse prevention and product use\n  text: Security, abuse prevention, fair-use caps, audit of agent actions on the customer's behalf, and understanding\n    how the product is used\n- purpose: following up\
  \ possible customers\n  text: Following up a possible customer relationship\n- purpose: Maplith Bridge updates\n  text: Sending security notices and release news about Maplith Bridge to the people who asked for them\nretention:\n- scope: account data\n  period: While your account exists\n  text: While your account exists.\n- scope: funnel events, agent-key and MCP usage, assistant usage, agent-action audit rows\n  period: 12 months\n  text: 12 months from the event, or until the workspace is deleted, whichever is earlier\n- scope: Maplith Bridge consent proof\n  period: 2 years\n  text: keeps a proof of your consent for 2 years\n- scope: questions to the demo company\n  period: 12 months\n  text: One usage row per question (time, model, tokens, cost) and a daily count of the demo's calls, 12 months\n    each\n- scope: website analytics with consent\n  period: At most 13 months\n  text: 'At most 13 months: Maplith deletes them at least once a year.'\n- scope: sales contacts\n  period: 24\
  \ months after the last contact or change to the record\n  text: 24 months after the last contact or change to the record\n- scope: billing data\n  period: 5 years after the end of the financial year\n  text: 5 years after the end of the financial year, as the Danish Bookkeeping Act requires\nresidency:\n- region: EU (hosting, database, file storage)\n  text: 'Hosting, database and file storage run in the EU: Supabase (Frankfurt) and Railway (EU West, Amsterdam)'\n- region: United States (AI model inference)\n  text: model inference runs in the United States\ntransfers:\n- mechanism: SCC\n  text: under its data processing addendum with the standard contractual clauses\n- mechanism: DPF\n  text: Cal.com, Inc. processes in the United States and states that it relies on the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: The sub-processor list lists every provider, what it receives, where it processes it and on what basis.\ndpa:\n  available: true\n  url: null\n  text:\
  \ the Data Processing Agreement and the Processing and security description apply\ndeletion:\n  route: email request to frp@maplith.com\n  text: 'Deleting your account or your organisation is not yet self-service: write to frp@maplith.com, and Maplith''s\n    operator carries it out within 30 days and confirms in writing.'\nrights:\n- right: access\n  text: you can ask Maplith for access to your personal data\n- right: correction, deletion, restriction\n  text: for correction, for deletion, for restriction of processing\n- right: portability\n  text: for a copy of the data you gave us in a machine-readable form (portability)\n- right: objection\n  text: you can object to processing based on legitimate interest, including at any time to direct marketing\n- right: complaint\n  text: You can complain to Datatilsynet, the Danish supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data.\n"
source_yaml_url: https://artifacts.apis.io/maplith-com/privacy/maplith-com-privacy-policy.yml
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
summary_line: 32 quoted statements, read from maplith-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Data Integration
- Knowledge Graph
- Platform
---
