---
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address.
  - category: identifying
    text: Display name if you set one.
  - category: financial
    text: Stripe shares the last 4 digits, brand, country of issuance, and a customer ID.
  - category: device
    text: The IP address and User-Agent string.
  - category: behavioral
    text: Endpoint, HTTP status, response size, timestamp.
  - category: communication
    text: Emails and Telegram messages are retained for three years after your last interaction, then deleted.
  deletion:
    route: Email emma@redditapis.com
    text: You can request access, correction, deletion, or export at any time by emailing emma@redditapis.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service: authentication, request routing, session management, rate limiting.'
  - purpose: Billing
    text: 'To bill you: Stripe customer record, invoice generation, tax compliance.'
  - purpose: Security
    text: 'To secure the service: detect abuse, block credential stuffing, investigate incidents, comply with lawful requests.'
  - purpose: Communications
    text: 'To communicate with you: service notices, security advisories, billing receipts.'
  residency:
  - region: EU (Frankfurt)
    text: Primary hosting and database are in the EU (Frankfurt) .
  - region: US
    text: Payment processing is in the US.
  retention:
  - period: Until you close your account, plus 30 days
    scope: Account data
    text: Until you close your account, plus 30 days
  - period: 7 years (tax compliance)
    scope: Billing records
    text: 7 years (tax compliance)
  - period: Until revoked or expired
    scope: Reddit session tokens
    text: Until revoked or expired
  - period: 90 days hot, 12 months cold
    scope: API usage logs
    text: 90 days hot, 12 months cold
  - period: 3 years from last interaction
    scope: Support correspondence
    text: 3 years from last interaction
  rights:
  - right: Access
    text: Access , get a copy of the personal data we hold.
  - right: Correct
    text: Correct data that is inaccurate or incomplete.
  - right: Delete
    text: Delete , subject to legal retention obligations.
  - right: Restrict
    text: Restrict , limit how we use your data while we investigate a dispute.
  - right: Port
    text: Port , JSON or CSV.
  - right: Object
    text: Object to legitimate-interest processing.
  - right: Withdraw consent
    text: Withdraw consent at any time.
  role:
    text: The data controller for redditapis.com is the redditapis.com team.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Stripe Payment processing Cloudflare DDoS and edge protection Hetzner Cloud Compute and hosting Supabase Database, auth, encrypted session storage
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers out of the EEA/UK we rely on the European Commission's Standard Contractual Clauses (2021/914) and supplementary measures including encryption-in-transit and at-rest.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: redditapis-com
provenance_date: '2026-11-10'
provider_name: redditapis-com
provider_slug: redditapis-com
slug: redditapis-com-privacy-policy
source_date: '2026-11-10'
source_filename: redditapis-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.redditapis.com/privacy-and-data-handling
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: redditapis-com\naid: redditapis-com\nurl: https://www.redditapis.com/privacy-and-data-handling\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for redditapis.com is the redditapis.com team.\ndata_categories:\n- category: contact\n  text: Email address.\n- category: identifying\n  text: Display name if you set one.\n- category: financial\n  text: Stripe shares the last 4 digits, brand, country of issuance, and a customer ID.\n- category: device\n  text: The IP address and User-Agent string.\n- category: behavioral\n  text: Endpoint, HTTP status, response size, timestamp.\n\
  - category: communication\n  text: Emails and Telegram messages are retained for three years after your last interaction, then deleted.\npurposes:\n- purpose: Run the service\n  text: 'To run the service: authentication, request routing, session management, rate limiting.'\n- purpose: Billing\n  text: 'To bill you: Stripe customer record, invoice generation, tax compliance.'\n- purpose: Security\n  text: 'To secure the service: detect abuse, block credential stuffing, investigate incidents, comply with lawful\n    requests.'\n- purpose: Communications\n  text: 'To communicate with you: service notices, security advisories, billing receipts.'\nretention:\n- scope: Account data\n  period: Until you close your account, plus 30 days\n  text: Until you close your account, plus 30 days\n- scope: Billing records\n  period: 7 years (tax compliance)\n  text: 7 years (tax compliance)\n- scope: Reddit session tokens\n  period: Until revoked or expired\n  text: Until revoked or expired\n- scope: API\
  \ usage logs\n  period: 90 days hot, 12 months cold\n  text: 90 days hot, 12 months cold\n- scope: Support correspondence\n  period: 3 years from last interaction\n  text: 3 years from last interaction\nresidency:\n- region: EU (Frankfurt)\n  text: Primary hosting and database are in the EU (Frankfurt) .\n- region: US\n  text: Payment processing is in the US.\ntransfers:\n- mechanism: SCC\n  text: For transfers out of the EEA/UK we rely on the European Commission's Standard Contractual Clauses (2021/914)\n    and supplementary measures including encryption-in-transit and at-rest.\nsubprocessors:\n  url: null\n  text: Stripe Payment processing Cloudflare DDoS and edge protection Hetzner Cloud Compute and hosting Supabase\n    Database, auth, encrypted session storage\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email emma@redditapis.com\n  text: You can request access, correction, deletion, or export at any time by emailing emma@redditapis.com .\nrights:\n- right:\
  \ Access\n  text: Access , get a copy of the personal data we hold.\n- right: Correct\n  text: Correct data that is inaccurate or incomplete.\n- right: Delete\n  text: Delete , subject to legal retention obligations.\n- right: Restrict\n  text: Restrict , limit how we use your data while we investigate a dispute.\n- right: Port\n  text: Port , JSON or CSV.\n- right: Object\n  text: Object to legitimate-interest processing.\n- right: Withdraw consent\n  text: Withdraw consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/redditapis-com/privacy/redditapis-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from redditapis-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Reddit
- Pay-per-call
- Artificial Intelligence
---
