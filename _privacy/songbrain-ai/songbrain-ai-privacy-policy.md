---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your email address and authentication credentials via Supabase Auth
  - category: financial
    text: We do not store credit card numbers or full payment details on our servers — only the transaction reference, the product purchased, the credit amount or subscription status, and a timestamp received via webhook.
  - category: behavioral
    text: we record product usage events on our own servers to understand and improve how Songbrain is used
  - category: device
    text: your browser's user-agent string
  - category: communication
    text: a copy of each message you send (your display name or e-mail address and the message text) is also posted to our internal team chat (Slack, section 5)
  deletion:
    route: Settings → Danger Zone → Delete account, or email info [at] songbrain [dot] ai
    text: You can delete your account and all associated data yourself at any time in Settings → Danger Zone → "Delete account".
  dpa:
    available: true
    text: under the data processing agreement at songbrain.ai/dpa , which applies to every API account automatically.
    url: songbrain.ai/dpa
  purposes:
  - purpose: provide analysis service
    text: We process personal data only to the extent necessary to provide and improve our service.
  - purpose: model calibration
    text: To calibrate and improve our Virality Score model we continuously collect publicly available metadata about released music from third-party platforms.
  residency:
  - region: Switzerland/EU
    text: Hetzner Online GmbH (Germany, EU) — Server hosting and infrastructure.
  - region: EU
    text: Data is stored in Supabase's EU region.
  retention:
  - period: within 24 hours
    scope: Uploaded audio files
    text: The original upload is deleted within 24 hours (section 6).
  - period: 400 days
    scope: Product usage events
    text: Usage events are deleted after 400 days (about 13 months; section 6).
  - period: 12 months
    scope: E-mails sorting record
    text: We keep a record of sender, subject, date, category and summary (not the e-mail text) for 12 months.
  - period: 10 years
    scope: Payment records
    text: Retained for the legally required period (10 years under Art. 958f of the Swiss Code of Obligations — retention of business records).
  rights:
  - right: access
    text: Right of access (Art. 15) — Request a copy of all personal data we hold about you.
  - right: erasure
    text: Right to erasure (Art. 17) — Request deletion of your personal data ("right to be forgotten").
  - right: object
    text: Right to object (Art. 21) — Object to processing based on legitimate interest.
  - right: withdraw consent
    text: Right to withdraw consent (Art. 7(3)) — Withdraw any previously given consent at any time.
  role:
    text: We process personal data in accordance with the Swiss Federal Act on Data Protection (FADP / revDSG) and — where it applies to users in the EU/EEA — the GDPR.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: The current list of sub-processors is at songbrain.ai/security .
    url: songbrain.ai/security
  transfers:
  - mechanism: DPF
    text: EU-U.S. and Swiss-U.S. Data Privacy Framework (DPF) where the recipient is certified
  - mechanism: SCC
    text: by the EU Standard Contractual Clauses (SCCs) under Commission Implementing Decision (EU) 2021/914
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: songbrain-ai
provenance_date: '2026-11-10'
provider_name: songbrain-ai
provider_slug: songbrain-ai
slug: songbrain-ai-privacy-policy
source_date: '2026-11-10'
source_filename: songbrain-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.songbrain.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: songbrain-ai\naid: songbrain-ai\nurl: https://www.songbrain.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We process personal data in accordance with the Swiss Federal Act on Data Protection (FADP / revDSG) and\n    — where it applies to users in the EU/EEA — the GDPR.\ndata_categories:\n- category: identifying\n  text: we store your email address and authentication credentials via Supabase Auth\n- category: financial\n  text: We do not store credit card numbers or full payment details on our servers — only the transaction reference,\n    the product purchased, the credit amount\
  \ or subscription status, and a timestamp received via webhook.\n- category: behavioral\n  text: we record product usage events on our own servers to understand and improve how Songbrain is used\n- category: device\n  text: your browser's user-agent string\n- category: communication\n  text: a copy of each message you send (your display name or e-mail address and the message text) is also posted\n    to our internal team chat (Slack, section 5)\npurposes:\n- purpose: provide analysis service\n  text: We process personal data only to the extent necessary to provide and improve our service.\n- purpose: model calibration\n  text: To calibrate and improve our Virality Score model we continuously collect publicly available metadata about\n    released music from third-party platforms.\nretention:\n- scope: Uploaded audio files\n  period: within 24 hours\n  text: The original upload is deleted within 24 hours (section 6).\n- scope: Product usage events\n  period: 400 days\n  text: Usage events\
  \ are deleted after 400 days (about 13 months; section 6).\n- scope: E-mails sorting record\n  period: 12 months\n  text: We keep a record of sender, subject, date, category and summary (not the e-mail text) for 12 months.\n- scope: Payment records\n  period: 10 years\n  text: Retained for the legally required period (10 years under Art. 958f of the Swiss Code of Obligations — retention\n    of business records).\nresidency:\n- region: Switzerland/EU\n  text: Hetzner Online GmbH (Germany, EU) — Server hosting and infrastructure.\n- region: EU\n  text: Data is stored in Supabase's EU region.\ntransfers:\n- mechanism: DPF\n  text: EU-U.S. and Swiss-U.S. Data Privacy Framework (DPF) where the recipient is certified\n- mechanism: SCC\n  text: by the EU Standard Contractual Clauses (SCCs) under Commission Implementing Decision (EU) 2021/914\nsubprocessors:\n  url: songbrain.ai/security\n  text: The current list of sub-processors is at songbrain.ai/security .\ndpa:\n  available: true\n  url:\
  \ songbrain.ai/dpa\n  text: under the data processing agreement at songbrain.ai/dpa , which applies to every API account automatically.\ndeletion:\n  route: Settings → Danger Zone → Delete account, or email info [at] songbrain [dot] ai\n  text: You can delete your account and all associated data yourself at any time in Settings → Danger Zone → \"Delete\n    account\".\nrights:\n- right: access\n  text: Right of access (Art. 15) — Request a copy of all personal data we hold about you.\n- right: erasure\n  text: Right to erasure (Art. 17) — Request deletion of your personal data (\"right to be forgotten\").\n- right: object\n  text: Right to object (Art. 21) — Object to processing based on legitimate interest.\n- right: withdraw consent\n  text: Right to withdraw consent (Art. 7(3)) — Withdraw any previously given consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/songbrain-ai/privacy/songbrain-ai-privacy-policy.yml
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
summary_line: 24 quoted statements, read from songbrain-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Music
- Video
---
