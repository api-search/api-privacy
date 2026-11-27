---
api_specs:
- filename: voicedock-api-openapi-generated.yml
  format: yaml
  label: VoiceDock api API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voicedock/openapi/_ae-authored/voicedock-api-openapi-generated.yml
- filename: voicedock-reference-openapi-generated.yml
  format: yaml
  label: VoiceDock reference API
  slug: reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voicedock/openapi/_ae-authored/voicedock-reference-openapi-generated.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, organisation
  - category: financial
    text: Billing address, VAT details
  - category: financial
    text: Payment details
  - category: device
    text: Browser and device information
  deletion:
    route: Callers contact the company whose assistant they spoke with; account and controller data requests go to privacy@flireo.com
    text: If you are a caller and want access to, or deletion of, a conversation, contact the company you called.
  dpa:
    available: true
    text: Under a Data Processing Agreement
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: Creating and authenticating your account, service notifications
  - purpose: Invoicing and tax compliance
    text: Invoicing and tax compliance
  - purpose: Securing the platform and preventing abuse
    text: Securing the platform, detecting and preventing abuse
  - purpose: Advertising measurement on website
    text: Measuring which of our ads work
  residency:
  - region: Germany
    text: Germany (Frankfurt, eu-central-1)
  - region: Finland and Germany
    text: Germany (Nuremberg, with a standby in Falkenstein) for real-time media and orchestration; Finland (Helsinki) for the VoiceDock voice
  - region: EU (error monitoring)
    text: whose storage region is set to the European Union
  retention:
  - period: 2 years
    scope: Account data
    text: Duration of the account, then 2 years
  - period: 7 years
    scope: Billing address and VAT details
    text: 7 years (Dutch statutory retention for accounting records)
  - period: Up to 30 days
    scope: IP address in server logs
    text: Up to 30 days in server logs
  - period: 30 days
    scope: Application error reports
    text: 30 days
  - period: 24 months
    scope: Trust Centre data
    text: 24 months from the decision
  - period: Up to 90 days
    scope: Google Ads cookies
    text: Cookies up to 90 days
  rights:
  - right: Access (Art. 15)
    text: Obtain a copy of the personal data we hold about you
  - right: Rectification (Art. 16)
    text: Have inaccurate or incomplete data corrected
  - right: Erasure (Art. 17)
    text: Have your data deleted, where no legal obligation requires us to keep it
  - right: Restriction (Art. 18)
    text: Have processing limited while a dispute is resolved
  - right: Portability (Art. 20)
    text: Receive data you provided to us in a machine-readable format
  - right: Objection (Art. 21)
    text: Object to processing based on legitimate interest, including anything in Sections 3.2 and 3.3
  - right: Withdraw consent (Art. 7(3))
    text: Where processing rests on consent, withdraw it at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: This is the single canonical list, maintained in one place, which every other document references.
    url: null
  transfers:
  - mechanism: SCC
    text: EU SCCs 2021/914, completed in Schedule 2 of the executed DPA
  - mechanism: DPF
    text: Primary mechanism is the EU-US Data Privacy Framework, to which Google LLC has certified; EU SCCs (2021/914) apply as the fallback.
  - mechanism: other
    text: Every such transfer takes place under an adequacy decision (Art. 45 GDPR), the EU-US Data Privacy Framework where the provider is certified, or the EU Standard Contractual Clauses adopted by Commission Implementing Decision (EU) 2021/914 (Art. 46 GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: VoiceDock
provenance_date: '2026-11-10'
provider_name: VoiceDock
provider_slug: voicedock
slug: voicedock-privacy-policy
source_date: '2026-11-10'
source_filename: voicedock-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://trust.voicedock.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: VoiceDock\naid: voicedock\nurl: https://trust.voicedock.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, organisation\n- category: financial\n  text: Billing address, VAT details\n- category: financial\n  text: Payment details\n- category: device\n  text: Browser and device information\npurposes:\n- purpose: Account creation and authentication\n  text: Creating and authenticating your account, service notifications\n- purpose: Invoicing and tax compliance\n  text: Invoicing and tax compliance\n\
  - purpose: Securing the platform and preventing abuse\n  text: Securing the platform, detecting and preventing abuse\n- purpose: Advertising measurement on website\n  text: Measuring which of our ads work\nretention:\n- scope: Account data\n  period: 2 years\n  text: Duration of the account, then 2 years\n- scope: Billing address and VAT details\n  period: 7 years\n  text: 7 years (Dutch statutory retention for accounting records)\n- scope: IP address in server logs\n  period: Up to 30 days\n  text: Up to 30 days in server logs\n- scope: Application error reports\n  period: 30 days\n  text: 30 days\n- scope: Trust Centre data\n  period: 24 months\n  text: 24 months from the decision\n- scope: Google Ads cookies\n  period: Up to 90 days\n  text: Cookies up to 90 days\nresidency:\n- region: Germany\n  text: Germany (Frankfurt, eu-central-1)\n- region: Finland and Germany\n  text: Germany (Nuremberg, with a standby in Falkenstein) for real-time media and orchestration; Finland (Helsinki)\n\
  \    for the VoiceDock voice\n- region: EU (error monitoring)\n  text: whose storage region is set to the European Union\ntransfers:\n- mechanism: SCC\n  text: EU SCCs 2021/914, completed in Schedule 2 of the executed DPA\n- mechanism: DPF\n  text: Primary mechanism is the EU-US Data Privacy Framework, to which Google LLC has certified; EU SCCs (2021/914)\n    apply as the fallback.\n- mechanism: other\n  text: Every such transfer takes place under an adequacy decision (Art. 45 GDPR), the EU-US Data Privacy Framework\n    where the provider is certified, or the EU Standard Contractual Clauses adopted by Commission Implementing Decision\n    (EU) 2021/914 (Art. 46 GDPR).\nsubprocessors:\n  url: null\n  text: This is the single canonical list, maintained in one place, which every other document references.\ndpa:\n  available: true\n  url: null\n  text: Under a Data Processing Agreement\ndeletion:\n  route: Callers contact the company whose assistant they spoke with; account and controller\
  \ data requests go to\n    privacy@flireo.com\n  text: If you are a caller and want access to, or deletion of, a conversation, contact the company you called.\nrights:\n- right: Access (Art. 15)\n  text: Obtain a copy of the personal data we hold about you\n- right: Rectification (Art. 16)\n  text: Have inaccurate or incomplete data corrected\n- right: Erasure (Art. 17)\n  text: Have your data deleted, where no legal obligation requires us to keep it\n- right: Restriction (Art. 18)\n  text: Have processing limited while a dispute is resolved\n- right: Portability (Art. 20)\n  text: Receive data you provided to us in a machine-readable format\n- right: Objection (Art. 21)\n  text: Object to processing based on legitimate interest, including anything in Sections 3.2 and 3.3\n- right: Withdraw consent (Art. 7(3))\n  text: Where processing rests on consent, withdraw it at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/voicedock/privacy/voicedock-privacy-policy.yml
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
summary_line: 31 quoted statements, read from VoiceDock's own page on 2026-11-10.
synthetic: false
tags:
- Voice AI
- Telephony
- Communications
- Platform
- EU-Sovereign
- On-Premises
---
