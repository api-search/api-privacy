---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Aqta API keys are stored only as one-way hashes.
  - category: contact
    text: 'Accounts on app.aqta.ai: email address, organisation name and, if you use one, your Auth0, Google or GitHub account identifier'
  - category: behavioral
    text: 'Declared intent: for agent sessions, the intent your agent declares when the session opens, in plain text, with the session.'
  - category: device
    text: the IP address and user agent of the system that called Seal
  - category: financial
    text: billing records, if you pay
  - category: communication
    text: what you type, such as email, name, company and message, and your IP address to limit abuse
  deletion:
    route: Email hello@aqta.ai with subject Data protection request
    text: 'Data-protection requests: hello@aqta.ai , subject Data protection request .'
  dpa:
    available: true
    text: under a data processing agreement, available on request.
    url: null
  purposes:
  - purpose: Security and abuse prevention
    text: To keep the service secure and prevent abuse (legitimate interest)
  - purpose: Billing records
    text: To keep billing records (legal obligation)
  - purpose: Replying to enquiries
    text: To reply to enquiries and form requests (legitimate interest), and to send the blog (consent)
  residency:
  - region: Belgium
    text: Seal and our database run in Belgium, and our website functions in Dublin.
  - region: Ireland
    text: 'Amazon Web Services (Ireland): a database from before August 2026 that we can no longer reach'
  retention:
  - period: 30 days on starter
    scope: Operational metadata
    text: deleted automatically after the period for your plan (7 days for evaluation access, 30 days on starter, 365 days on pro)
  - period: null
    scope: Signed and agent-action records
    text: 'No expiry set yet, under review: sessions opened by registering an intent, threat patterns, and signed and agent-action records, which are not deleted automatically (section 3).'
  - period: null
    scope: Account and billing records
    text: billing records for as long as Irish tax law requires. No automatic deletion yet.
  - period: 12 months
    scope: Working paper PDF requests
    text: 'Working paper PDF requests: 12 months after your last request, then deleted automatically, or sooner if you ask.'
  - period: up to 30 days
    scope: Server logs
    text: 'Server logs: up to 30 days on Google Cloud'
  rights:
  - right: access
    text: You can ask for access to your personal data, its correction or deletion, a restriction of its use or a portable copy, object to its use, and withdraw consent at any time.
  - right: object
    text: You can object at any time to our use of your data on the basis of legitimate interest
  - right: complain
    text: You can also complain to the Data Protection Commission (dataprotection.ie).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, use it for advertising, or use request content to train models.
  subprocessors:
    text: The same list, with roles, is on /trust .
    url: https://aqta.ai/trust
  transfers:
  - mechanism: other
    text: We are reviewing the safeguards for each of these transfers; ask us for the current position.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aqta
provenance_date: '2026-11-09'
provider_name: Aqta
provider_slug: aqta-ai
slug: aqta-ai-privacy-policy
source_date: '2026-11-09'
source_filename: aqta-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aqta.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aqta\naid: aqta-ai\nurl: https://aqta.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Aqta API keys are stored only as one-way hashes.\n- category: contact\n  text: 'Accounts on app.aqta.ai: email address, organisation name and, if you use one, your Auth0, Google or GitHub\n    account identifier'\n- category: behavioral\n  text: 'Declared intent: for agent sessions, the intent your agent declares when the session opens, in plain text,\n    with the session.'\n- category: device\n  text: the IP address and user agent of the system\
  \ that called Seal\n- category: financial\n  text: billing records, if you pay\n- category: communication\n  text: what you type, such as email, name, company and message, and your IP address to limit abuse\npurposes:\n- purpose: Security and abuse prevention\n  text: To keep the service secure and prevent abuse (legitimate interest)\n- purpose: Billing records\n  text: To keep billing records (legal obligation)\n- purpose: Replying to enquiries\n  text: To reply to enquiries and form requests (legitimate interest), and to send the blog (consent)\nretention:\n- scope: Operational metadata\n  period: 30 days on starter\n  text: deleted automatically after the period for your plan (7 days for evaluation access, 30 days on starter,\n    365 days on pro)\n- scope: Signed and agent-action records\n  period: null\n  text: 'No expiry set yet, under review: sessions opened by registering an intent, threat patterns, and signed\n    and agent-action records, which are not deleted automatically (section\
  \ 3).'\n- scope: Account and billing records\n  period: null\n  text: billing records for as long as Irish tax law requires. No automatic deletion yet.\n- scope: Working paper PDF requests\n  period: 12 months\n  text: 'Working paper PDF requests: 12 months after your last request, then deleted automatically, or sooner if\n    you ask.'\n- scope: Server logs\n  period: up to 30 days\n  text: 'Server logs: up to 30 days on Google Cloud'\nresidency:\n- region: Belgium\n  text: Seal and our database run in Belgium, and our website functions in Dublin.\n- region: Ireland\n  text: 'Amazon Web Services (Ireland): a database from before August 2026 that we can no longer reach'\ntransfers:\n- mechanism: other\n  text: We are reviewing the safeguards for each of these transfers; ask us for the current position.\nsubprocessors:\n  url: https://aqta.ai/trust\n  text: The same list, with roles, is on /trust .\ndpa:\n  available: true\n  url: null\n  text: under a data processing agreement, available\
  \ on request.\ndeletion:\n  route: Email hello@aqta.ai with subject Data protection request\n  text: 'Data-protection requests: hello@aqta.ai , subject Data protection request .'\nrights:\n- right: access\n  text: You can ask for access to your personal data, its correction or deletion, a restriction of its use or a\n    portable copy, object to its use, and withdraw consent at any time.\n- right: object\n  text: You can object at any time to our use of your data on the basis of legitimate interest\n- right: complain\n  text: You can also complain to the Data Protection Commission (dataprotection.ie).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, use it for advertising, or use request content to train models.\n"
source_yaml_url: https://artifacts.apis.io/aqta-ai/privacy/aqta-ai-privacy-policy.yml
stated_fields:
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
summary_line: 24 quoted statements, read from Aqta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Verification
- Transparency
- Dublin
- Startups
---
