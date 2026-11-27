---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, address, phone number, email address, and other personal, professional, demographic and business information that you provide
  - category: financial
    text: we may also collect your credit card information
  - category: device
    text: your computer's or mobile device’s Internet Protocol (IP) address, your operating system, the browser type
  - category: behavioral
    text: your activity on Lawtrades
  - category: communication
    text: 'User Content: prompts, contracts, playbooks, and other materials you upload.'
  - category: communication
    text: Your phone number. Your explicit consent to receive SMS messages from us.
  deletion:
    route: Contact help@lawtrades.com, close account, or use Lawtrades conversation controls and Gmail controls
    text: For access, correction or deletion of other stored records, contact help@lawtrades.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate services
    text: to facilitate your use of Lawtrades, to process your requests or transactions, to provide you with information, products and services you request
  - purpose: marketing communications
    text: to communicate any promotions to you by email, calls, texts
  - purpose: Lawtrades AI operation
    text: Provide, operate, and improve Lawtrades AI for you.
  - purpose: Gmail user-facing features
    text: We use Gmail data for the user-facing features you authorize, not advertising, sale to data brokers, credit decisions or general-purpose AI model training.
  residency:
  - region: United States
    text: The connector is hosted on Google Cloud Platform in the United States (us-central1).
  - region: United States
    text: Production conversation objects are stored in Google Cloud's US-CENTRAL1 region
  retention:
  - period: 1 hour
    scope: MCP access tokens
    text: Access tokens expire 1 hour after issuance
  - period: 30 days
    scope: MCP refresh tokens
    text: refresh tokens expire after 30 days and are rotated on each use
  - period: 730 days
    scope: MCP audit-log metadata
    text: Audit-log metadata is retained for 730 days (24 months).
  - period: 30 days
    scope: Gmail production conversation objects
    text: deletion scheduled at 30 days of object age, followed by a seven-day soft-delete retention period
  rights:
  - right: access, correction and deletion
    text: you wish to verify, correct or delete any personal information we have collected, please contact us at help@lawtrades.com
  - right: opt out of SMS
    text: You can opt out of SMS communications at any time by following the instructions provided in the messages or contacting us at help@lawtrades.com .
  - right: opt out of advertising
    text: You may opt out of receiving this advertising by visiting https://app.retention.com/optout
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell, share, or rent any personal information we collect from you through Lawtrades in ways different from what is disclosed in this Policy
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LawTrades
provenance_date: '2026-11-09'
provider_name: LawTrades
provider_slug: lawtrades
slug: lawtrades-privacy-policy
source_date: '2026-11-09'
source_filename: lawtrades-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lawtrades.com/disclaimers-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LawTrades\naid: lawtrades\nurl: https://www.lawtrades.com/disclaimers-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, address, phone number, email address, and other personal, professional, demographic and business\n    information that you provide\n- category: financial\n  text: we may also collect your credit card information\n- category: device\n  text: your computer's or mobile device’s Internet Protocol (IP) address, your operating system, the browser type\n- category: behavioral\n  text: your activity on Lawtrades\n\
  - category: communication\n  text: 'User Content: prompts, contracts, playbooks, and other materials you upload.'\n- category: communication\n  text: Your phone number. Your explicit consent to receive SMS messages from us.\npurposes:\n- purpose: provide and operate services\n  text: to facilitate your use of Lawtrades, to process your requests or transactions, to provide you with information,\n    products and services you request\n- purpose: marketing communications\n  text: to communicate any promotions to you by email, calls, texts\n- purpose: Lawtrades AI operation\n  text: Provide, operate, and improve Lawtrades AI for you.\n- purpose: Gmail user-facing features\n  text: We use Gmail data for the user-facing features you authorize, not advertising, sale to data brokers, credit\n    decisions or general-purpose AI model training.\nretention:\n- scope: MCP access tokens\n  period: 1 hour\n  text: Access tokens expire 1 hour after issuance\n- scope: MCP refresh tokens\n  period: 30\
  \ days\n  text: refresh tokens expire after 30 days and are rotated on each use\n- scope: MCP audit-log metadata\n  period: 730 days\n  text: Audit-log metadata is retained for 730 days (24 months).\n- scope: Gmail production conversation objects\n  period: 30 days\n  text: deletion scheduled at 30 days of object age, followed by a seven-day soft-delete retention period\nresidency:\n- region: United States\n  text: The connector is hosted on Google Cloud Platform in the United States (us-central1).\n- region: United States\n  text: Production conversation objects are stored in Google Cloud's US-CENTRAL1 region\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact help@lawtrades.com, close account, or use Lawtrades conversation controls and Gmail controls\n  text: For access, correction or deletion of other stored records, contact help@lawtrades.com .\nrights:\n- right: access, correction and deletion\n\
  \  text: you wish to verify, correct or delete any personal information we have collected, please contact us at help@lawtrades.com\n- right: opt out of SMS\n  text: You can opt out of SMS communications at any time by following the instructions provided in the messages\n    or contacting us at help@lawtrades.com .\n- right: opt out of advertising\n  text: You may opt out of receiving this advertising by visiting https://app.retention.com/optout\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell, share, or rent any personal information we collect from you through Lawtrades in ways different\n    from what is disclosed in this Policy\n"
source_yaml_url: https://artifacts.apis.io/lawtrades/privacy/lawtrades-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from LawTrades's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Services
- Legal Operations
- Marketplace
- Talent Marketplace
- Contracts
- Compliance
- Professional Services
- Artificial Intelligence
---
