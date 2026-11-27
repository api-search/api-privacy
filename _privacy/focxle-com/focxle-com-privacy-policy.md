---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: financial
    text: Transaction hashes, amounts, assets and settlement status for payments we process, kept as receipts so both sides can audit what happened.
  - category: identifying
    text: Public wallet addresses , including the address paying us.
  - category: identifying
    text: IP addresses , used as short-lived rate-limiting keys and to cap self-registration attempts.
  - category: device
    text: User-Agent strings , in two forms.
  - category: contact
    text: Email address , if you register an agent through the human-facing flow, which sends a sign-in link to verify you.
  - category: communication
    text: Anything you send us in a support message.
  deletion:
    route: Email mrinal@focxle.com to exercise rights
    text: 'Erasure : have off-chain data deleted, subject to records we must retain for legal or anti-fraud reasons.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sanctions screening
    text: We screen wallet addresses against public sanctions lists, including the US Treasury OFAC list.
  - purpose: Security and abuse prevention
    text: the interest is keeping a payment system available and resistant to abuse
  - purpose: Reputation and credit scoring
    text: We compute reputation scores and on-chain risk assessments, and these can affect whether an agent is extended credit, asked to prepay, or flagged to a counterparty.
  retention:
  - period: 35 days
    scope: Daily operational counters
    text: 'Daily operational counters : 35 days, then deleted automatically.'
  - period: one year
    scope: Lookup records
    text: 'Lookup records (who asked about which wallet): one year from the last time that pair occurred, then deleted automatically.'
  - period: up to one hour
    scope: Rate-limiting and registration-throttle keys
    text: 'Rate-limiting and registration-throttle keys : up to one hour.'
  - period: indefinitely
    scope: Aggregate all-time counters
    text: 'Aggregate all-time counters : kept indefinitely.'
  - period: for as long as the agent exists on the platform
    scope: Settlement receipts, agent records and reputation history
    text: 'Settlement receipts, agent records and reputation history : kept for as long as the agent exists on the platform'
  rights:
  - right: Access and portability
    text: 'Access and portability : request a copy of the off-chain data we hold that relates to you or your agent.'
  - right: Correction
    text: 'Correction : have inaccurate data corrected, including a disputed automated assessment.'
  - right: Objection and restriction
    text: 'Objection and restriction : object to processing based on legitimate interest.'
  - right: Complaint
    text: 'Complaint : raise the matter with your local data protection authority.'
  role:
    text: Focxle is the data controller for the data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for cross-context behavioural advertising, so there is nothing to opt out of.
  subprocessors:
    text: Our hosting and infrastructure providers , who run the application and store its server logs and databases.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, transfers rely on standard contractual clauses or an equivalent mechanism offered by the provider.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: focxle-com
provenance_date: '2026-11-09'
provider_name: focxle-com
provider_slug: focxle-com
slug: focxle-com-privacy-policy
source_date: '2026-11-09'
source_filename: focxle-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://focxle.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: focxle-com\naid: focxle-com\nurl: https://focxle.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Focxle is the data controller for the data described here.\ndata_categories:\n- category: financial\n  text: Transaction hashes, amounts, assets and settlement status for payments we process, kept as receipts so both\n    sides can audit what happened.\n- category: identifying\n  text: Public wallet addresses , including the address paying us.\n- category: identifying\n  text: IP addresses , used as short-lived rate-limiting keys and to cap self-registration attempts.\n- category: device\n\
  \  text: User-Agent strings , in two forms.\n- category: contact\n  text: Email address , if you register an agent through the human-facing flow, which sends a sign-in link to verify\n    you.\n- category: communication\n  text: Anything you send us in a support message.\npurposes:\n- purpose: Sanctions screening\n  text: We screen wallet addresses against public sanctions lists, including the US Treasury OFAC list.\n- purpose: Security and abuse prevention\n  text: the interest is keeping a payment system available and resistant to abuse\n- purpose: Reputation and credit scoring\n  text: We compute reputation scores and on-chain risk assessments, and these can affect whether an agent is extended\n    credit, asked to prepay, or flagged to a counterparty.\nretention:\n- scope: Daily operational counters\n  period: 35 days\n  text: 'Daily operational counters : 35 days, then deleted automatically.'\n- scope: Lookup records\n  period: one year\n  text: 'Lookup records (who asked about which\
  \ wallet): one year from the last time that pair occurred, then deleted\n    automatically.'\n- scope: Rate-limiting and registration-throttle keys\n  period: up to one hour\n  text: 'Rate-limiting and registration-throttle keys : up to one hour.'\n- scope: Aggregate all-time counters\n  period: indefinitely\n  text: 'Aggregate all-time counters : kept indefinitely.'\n- scope: Settlement receipts, agent records and reputation history\n  period: for as long as the agent exists on the platform\n  text: 'Settlement receipts, agent records and reputation history : kept for as long as the agent exists on the\n    platform'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, transfers rely on standard contractual clauses or an equivalent mechanism offered by the\n    provider.\nsubprocessors:\n  url: null\n  text: Our hosting and infrastructure providers , who run the application and store its server logs and databases.\ndpa:\n  available: null\n  url: null\n  text: null\n\
  deletion:\n  route: Email mrinal@focxle.com to exercise rights\n  text: 'Erasure : have off-chain data deleted, subject to records we must retain for legal or anti-fraud reasons.'\nrights:\n- right: Access and portability\n  text: 'Access and portability : request a copy of the off-chain data we hold that relates to you or your agent.'\n- right: Correction\n  text: 'Correction : have inaccurate data corrected, including a disputed automated assessment.'\n- right: Objection and restriction\n  text: 'Objection and restriction : object to processing based on legitimate interest.'\n- right: Complaint\n  text: 'Complaint : raise the matter with your local data protection authority.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for cross-context behavioural advertising, so there is nothing\n    to opt out of.\n"
source_yaml_url: https://artifacts.apis.io/focxle-com/privacy/focxle-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from focxle-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Governance
- Payments
- B2B
- Autonomous Agents
---
