---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email, display name, avatar URL, preferred language
  - category: device
    text: Hashed IP (SHA-256), user-agent summary, language preference
  - category: communication
    text: Forum posts, questions, replies, chat messages you send
  - category: financial
    text: Email, payment info (when you pay)
  - category: location
    text: Street and house number, city, postcode and country (NL) of the building site
  deletion:
    route: POST /api/user/delete
    text: POST /api/user/delete — delete account and anonymize content
  dpa:
    available: null
    text: Data processing agreements (DPAs) with the processors listed here are being put in place.
    url: null
  purposes:
  - purpose: service provision
    text: to provide the coordination service you requested (account, posting, matching).
  - purpose: fraud prevention and observability
    text: fraud prevention (hashed IPs), service observability (brain events).
  residency:
  - region: Netherlands (Amsterdam)
    text: All personal data is stored on servers in Amsterdam, Netherlands (DigitalOcean AMS3 data center).
  retention:
  - period: 30 days
    scope: server logs (IP-anonymized)
    text: 'Server logs (IP-anonymized): 30 days, then automatic deletion.'
  - period: until you delete your account
    scope: account data
    text: 'Account data: until you delete your account.'
  - period: 30 days
    scope: chat messages
    text: 'Chat messages: hot storage 30 days, then compressed archive accessible only to you.'
  - period: 7 years
    scope: financial records
    text: 'Financial records (invoices, payment proofs): 7 years per Dutch law (BW 2:10).'
  - period: 90 days
    scope: brain events
    text: 'Brain events (observability): actor field contains only hashed IDs, purged after 90 days.'
  rights:
  - right: access
    text: Access — request a copy of all your data (Art. 15)
  - right: rectification
    text: Rectify — correct wrong information (Art. 16)
  - right: erasure
    text: Erase — delete your account and content (Art. 17, "right to be forgotten")
  - right: portability
    text: Portability — receive your data in JSON format (Art. 20)
  - right: objection
    text: Object — refuse processing based on legitimate interest (Art. 21)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'Safeguard: being put in place (EU standard contractual clauses in a processing agreement).'
  - mechanism: DPF
    text: 'Safeguard: certified under the EU-U.S. Data Privacy Framework.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: astranl-com
provenance_date: '2026-11-09'
provider_name: astranl-com
provider_slug: astranl-com
slug: astranl-com-privacy-policy
source_date: '2026-11-09'
source_filename: astranl-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astranl.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: astranl-com\naid: astranl-com\nurl: https://astranl.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email, display name, avatar URL, preferred language\n- category: device\n  text: Hashed IP (SHA-256), user-agent summary, language preference\n- category: communication\n  text: Forum posts, questions, replies, chat messages you send\n- category: financial\n  text: Email, payment info (when you pay)\n- category: location\n  text: Street and house number, city, postcode and country (NL) of the building site\npurposes:\n- purpose:\
  \ service provision\n  text: to provide the coordination service you requested (account, posting, matching).\n- purpose: fraud prevention and observability\n  text: fraud prevention (hashed IPs), service observability (brain events).\nretention:\n- scope: server logs (IP-anonymized)\n  period: 30 days\n  text: 'Server logs (IP-anonymized): 30 days, then automatic deletion.'\n- scope: account data\n  period: until you delete your account\n  text: 'Account data: until you delete your account.'\n- scope: chat messages\n  period: 30 days\n  text: 'Chat messages: hot storage 30 days, then compressed archive accessible only to you.'\n- scope: financial records\n  period: 7 years\n  text: 'Financial records (invoices, payment proofs): 7 years per Dutch law (BW 2:10).'\n- scope: brain events\n  period: 90 days\n  text: 'Brain events (observability): actor field contains only hashed IDs, purged after 90 days.'\nresidency:\n- region: Netherlands (Amsterdam)\n  text: All personal data is stored on\
  \ servers in Amsterdam, Netherlands (DigitalOcean AMS3 data center).\ntransfers:\n- mechanism: SCC\n  text: 'Safeguard: being put in place (EU standard contractual clauses in a processing agreement).'\n- mechanism: DPF\n  text: 'Safeguard: certified under the EU-U.S. Data Privacy Framework.'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Data processing agreements (DPAs) with the processors listed here are being put in place.\ndeletion:\n  route: POST /api/user/delete\n  text: POST /api/user/delete — delete account and anonymize content\nrights:\n- right: access\n  text: Access — request a copy of all your data (Art. 15)\n- right: rectification\n  text: Rectify — correct wrong information (Art. 16)\n- right: erasure\n  text: Erase — delete your account and content (Art. 17, \"right to be forgotten\")\n- right: portability\n  text: Portability — receive your data in JSON format (Art. 20)\n- right: objection\n  text: Object — refuse processing based\
  \ on legitimate interest (Art. 21)\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data.\n"
source_yaml_url: https://artifacts.apis.io/astranl-com/privacy/astranl-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from astranl-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coordination
- Payments
- Platform
- NL
---
