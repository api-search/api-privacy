---
api_specs:
- filename: openapi.json
  format: json
  label: three.ws API
  slug: main-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/three-ws/openapi.json
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account identifiers Wallet address, email (optional), username, display name
  - category: contact
    text: Email (if provided) Email address for transactional messages
  - category: biometric
    text: we do not derive or store a face template or any other biometric identifier from them
  - category: location
    text: IP address (hashed), user agent
  - category: device
    text: Usage data API calls, widget load events (no IPs, no fingerprints)
  - category: financial
    text: USDC payment tx hashes
  - category: communication
    text: Legal acceptance records Terms of Service version accepted, Risk Disclosure version accepted, timestamp, IP address, user agent, which flow recorded it
  deletion:
    route: Email privacy@three.ws or sign a message with your wallet address to request deletion
    text: Requests to delete your account will remove all content stored on our servers, except records we must keep (Section 5)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and session management
    text: To authenticate you and maintain your session.
  - purpose: Content delivery
    text: To store and serve your 3D content via our CDN.
  - purpose: Transactional email
    text: To send transactional emails (welcome, subscription receipts, security alerts).
  - purpose: Quotas and rate limits
    text: To enforce plan quotas and rate limits.
  - purpose: Abuse and security
    text: To detect and prevent abuse, fraud, and security incidents.
  - purpose: Aggregate analytics
    text: To improve the Service using aggregate, anonymized analytics.
  residency:
  - region: United States
    text: data is processed on infrastructure located in the United States
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your account data for as long as your account is active.
  - period: 30 days
    scope: Deleted accounts
    text: Deleted accounts are soft-deleted for 30 days (for recovery), then permanently purged.
  - period: 30 days
    scope: Session tokens
    text: Session tokens expire after 30 days.
  - period: 90 days
    scope: Usage events
    text: Usage events are retained for 90 days for quota and abuse analysis, then deleted.
  - period: 12 months
    scope: Widget view events
    text: Widget view events (no personal data) are retained for 12 months.
  - period: 365 days
    scope: Security audit logs
    text: Security audit logs are retained for 365 days.
  - period: null
    scope: Legal acceptance records
    text: Legal acceptance records (your acceptance of the Terms of Service and Risk Disclosure) are retained for the life of your account and afterward for as long as needed to establish or defend legal claims.
  rights:
  - right: access
    text: you may have rights to access, correct, delete, or export your personal data
  - right: object or restrict
    text: and to object to or restrict certain processing
  - right: know and port (California)
    text: You have the rights to know, access, correct, delete, and port your personal information
  - right: non-discrimination
    text: We will never discriminate against you for exercising a privacy right.
  - right: complaint to supervisory authority
    text: You have the right to lodge a complaint with your local supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: 'Infrastructure providers: Google Cloud Platform (hosting and compute), Neon (database), Cloudflare (storage and CDN), Resend (transactional email), and Privy (optional sign-in).'
    url: null
  transfers:
  - mechanism: SCC
    text: Where GDPR applies, transfers to our processors rely on their standard contractual clauses or an applicable adequacy framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: three-ws
provenance_date: '2026-11-10'
provider_name: three-ws
provider_slug: three-ws
slug: three-ws-privacy-policy
source_date: '2026-11-10'
source_filename: three-ws-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://three.ws/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: three-ws\naid: three-ws\nurl: https://three.ws/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account identifiers Wallet address, email (optional), username, display name\n- category: contact\n  text: Email (if provided) Email address for transactional messages\n- category: biometric\n  text: we do not derive or store a face template or any other biometric identifier from them\n- category: location\n  text: IP address (hashed), user agent\n- category: device\n  text: Usage data API calls, widget load events (no IPs, no fingerprints)\n\
  - category: financial\n  text: USDC payment tx hashes\n- category: communication\n  text: Legal acceptance records Terms of Service version accepted, Risk Disclosure version accepted, timestamp,\n    IP address, user agent, which flow recorded it\npurposes:\n- purpose: Authentication and session management\n  text: To authenticate you and maintain your session.\n- purpose: Content delivery\n  text: To store and serve your 3D content via our CDN.\n- purpose: Transactional email\n  text: To send transactional emails (welcome, subscription receipts, security alerts).\n- purpose: Quotas and rate limits\n  text: To enforce plan quotas and rate limits.\n- purpose: Abuse and security\n  text: To detect and prevent abuse, fraud, and security incidents.\n- purpose: Aggregate analytics\n  text: To improve the Service using aggregate, anonymized analytics.\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your account data for as long as your account\
  \ is active.\n- scope: Deleted accounts\n  period: 30 days\n  text: Deleted accounts are soft-deleted for 30 days (for recovery), then permanently purged.\n- scope: Session tokens\n  period: 30 days\n  text: Session tokens expire after 30 days.\n- scope: Usage events\n  period: 90 days\n  text: Usage events are retained for 90 days for quota and abuse analysis, then deleted.\n- scope: Widget view events\n  period: 12 months\n  text: Widget view events (no personal data) are retained for 12 months.\n- scope: Security audit logs\n  period: 365 days\n  text: Security audit logs are retained for 365 days.\n- scope: Legal acceptance records\n  period: null\n  text: Legal acceptance records (your acceptance of the Terms of Service and Risk Disclosure) are retained for\n    the life of your account and afterward for as long as needed to establish or defend legal claims.\nresidency:\n- region: United States\n  text: data is processed on infrastructure located in the United States\ntransfers:\n\
  - mechanism: SCC\n  text: Where GDPR applies, transfers to our processors rely on their standard contractual clauses or an applicable\n    adequacy framework.\nsubprocessors:\n  url: null\n  text: 'Infrastructure providers: Google Cloud Platform (hosting and compute), Neon (database), Cloudflare (storage\n    and CDN), Resend (transactional email), and Privy (optional sign-in).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@three.ws or sign a message with your wallet address to request deletion\n  text: Requests to delete your account will remove all content stored on our servers, except records we must keep\n    (Section 5)\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, or export your personal data\n- right: object or restrict\n  text: and to object to or restrict certain processing\n- right: know and port (California)\n  text: You have the rights to know, access, correct, delete, and port your personal information\n\
  - right: non-discrimination\n  text: We will never discriminate against you for exercising a privacy right.\n- right: complaint to supervisory authority\n  text: You have the right to lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/three-ws/privacy/three-ws-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from three-ws's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- 3D
- Agents
- Web3
---
