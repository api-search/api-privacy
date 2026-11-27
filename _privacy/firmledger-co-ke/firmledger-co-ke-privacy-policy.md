---
api_specs:
- filename: firmledger-co-ke-openapi-generated.yml
  format: yaml
  label: FirmLedger API
  slug: firmledger-co-ke-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firmledger-co-ke/openapi/_ae-authored/firmledger-co-ke-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your name, your email address, and a bcrypt hash of your password
  - category: contact
    text: we store the content you provide — record fields, contact details, removal-request name and email
  - category: financial
    text: 'We do store the non-sensitive billing records needed to give you what you paid for: the plan or package purchased, subscription and order identifiers, status, amounts, currency and renewal dates'
  - category: device
    text: the browser's own description of itself (user-agent), the IP address the request came from, and when the session was last active
  - category: behavioral
    text: standard access and error logs (IP address, requested URL, user-agent, timestamp, response status)
  - category: communication
    text: If you email us or use a contact form we keep the message, your address and our reply
  deletion:
    route: Delete account from the dashboard or by writing to us
    text: delete your account from the dashboard or by writing to us
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and authentication
    text: create, authenticate, secure and administer accounts
  - purpose: security and abuse prevention
    text: prevent spam, scraping, abuse, fraud and security incidents
  - purpose: billing and receipts
    text: deliver the services you request (newsletter, alerts, messaging, tickets, billing and receipts)
  - purpose: aggregate usage measurement
    text: measure aggregate, de-identified usage so the site can be fixed and scaled
  - purpose: legal compliance
    text: comply with our legal, tax and accounting obligations
  residency:
  - region: Outside Kenya (EU, UK, United States)
    text: Some of our infrastructure providers process data outside Kenya, including in the EU, the UK and the United States.
  retention:
  - period: null
    scope: Account data
    text: Account data is kept for as long as your account exists, and is erased when you delete it
  - period: 14 days
    scope: Unverified claim tokens
    text: Unverified claim tokens expire within 14 days and are purged
  - period: 90 days
    scope: Server access logs
    text: Server access logs rotate and are deleted within 90 days.
  - period: null
    scope: Session tokens
    text: Session tokens are destroyed at sign-out, on session expiry, or when a staff role changes; expired sessions are purged automatically.
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: rectify
    text: rectify inaccurate data
  - right: erase
    text: erase your account and personal data
  - right: restrict or object
    text: restrict or object to certain processing
  - right: portability
    text: port data you gave us in a structured, machine-readable format
  - right: withdraw consent
    text: withdraw consent at any time
  - right: complain to supervisory authority
    text: complain to a supervisory authority — in Kenya, the Office of the Data Protection Commissioner
  role:
    text: FirmLedger is the data controller for the personal data processed through this website and our services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent or trade personal data, and we do not share it with advertisers or data brokers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses where applicable
  - mechanism: other
    text: contractual data-processing terms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FirmLedger
provenance_date: '2026-11-09'
provider_name: FirmLedger
provider_slug: firmledger-co-ke
slug: firmledger-co-ke-privacy-policy
source_date: '2026-11-09'
source_filename: firmledger-co-ke-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://firmledger.co.ke/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FirmLedger\naid: firmledger-co-ke\nurl: https://firmledger.co.ke/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: FirmLedger is the data controller for the personal data processed through this website and our services.\ndata_categories:\n- category: identifying\n  text: we store your name, your email address, and a bcrypt hash of your password\n- category: contact\n  text: we store the content you provide — record fields, contact details, removal-request name and email\n- category: financial\n  text: 'We do store the non-sensitive billing records needed to give you what you paid for:\
  \ the plan or package\n    purchased, subscription and order identifiers, status, amounts, currency and renewal dates'\n- category: device\n  text: the browser's own description of itself (user-agent), the IP address the request came from, and when the\n    session was last active\n- category: behavioral\n  text: standard access and error logs (IP address, requested URL, user-agent, timestamp, response status)\n- category: communication\n  text: If you email us or use a contact form we keep the message, your address and our reply\npurposes:\n- purpose: account creation and authentication\n  text: create, authenticate, secure and administer accounts\n- purpose: security and abuse prevention\n  text: prevent spam, scraping, abuse, fraud and security incidents\n- purpose: billing and receipts\n  text: deliver the services you request (newsletter, alerts, messaging, tickets, billing and receipts)\n- purpose: aggregate usage measurement\n  text: measure aggregate, de-identified usage so the\
  \ site can be fixed and scaled\n- purpose: legal compliance\n  text: comply with our legal, tax and accounting obligations\nretention:\n- scope: Account data\n  period: null\n  text: Account data is kept for as long as your account exists, and is erased when you delete it\n- scope: Unverified claim tokens\n  period: 14 days\n  text: Unverified claim tokens expire within 14 days and are purged\n- scope: Server access logs\n  period: 90 days\n  text: Server access logs rotate and are deleted within 90 days.\n- scope: Session tokens\n  period: null\n  text: Session tokens are destroyed at sign-out, on session expiry, or when a staff role changes; expired sessions\n    are purged automatically.\nresidency:\n- region: Outside Kenya (EU, UK, United States)\n  text: Some of our infrastructure providers process data outside Kenya, including in the EU, the UK and the United\n    States.\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses where applicable\n- mechanism: other\n  text:\
  \ contractual data-processing terms\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account from the dashboard or by writing to us\n  text: delete your account from the dashboard or by writing to us\nrights:\n- right: access\n  text: access the personal data we hold about you\n- right: rectify\n  text: rectify inaccurate data\n- right: erase\n  text: erase your account and personal data\n- right: restrict or object\n  text: restrict or object to certain processing\n- right: portability\n  text: port data you gave us in a structured, machine-readable format\n- right: withdraw consent\n  text: withdraw consent at any time\n- right: complain to supervisory authority\n  text: complain to a supervisory authority — in Kenya, the Office of the Data Protection Commissioner\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent or trade personal data, and we do not share it with advertisers or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/firmledger-co-ke/privacy/firmledger-co-ke-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from FirmLedger's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Directory
- Business Intelligence
- Kenya
---
