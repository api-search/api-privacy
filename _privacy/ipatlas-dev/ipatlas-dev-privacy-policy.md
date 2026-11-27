---
api_specs:
- filename: ipatlas-dev-openapi-generated.yml
  format: yaml
  label: ipatlas-dev API
  slug: ipatlas-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipatlas-dev/openapi/_ae-authored/ipatlas-dev-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: financial
    text: Stripe customer identifier
  - category: behavioral
    text: Per-key request counts (daily and monthly)
  - category: device
    text: a SHA-256 hash of your browser's user-agent string
  - category: location
    text: the first two octets of your IPv4 (e.g. 203.0 — a /16 prefix; for IPv6, the first three groups — a /48)
  - category: other
    text: SHA-256 hash of the cookie
  deletion:
    route: email support@ip-atlas.io
    text: Request deletion of your account (we delete your email, key, and usage history subject to the retention limits above).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate requests and enforce quotas
    text: To authenticate requests and enforce plan quotas;
  - purpose: billing
    text: To bill you correctly, including overage, and send receipts;
  - purpose: abuse and security investigation
    text: To investigate abuse or security incidents.
  residency:
  - region: United States
    text: IP-Atlas is hosted in the United States.
  retention:
  - period: 6 months
    scope: Account email, password hash and API key hashes
    text: retained while the account is active, plus 6 months after deletion for fraud and audit purposes, then permanently removed.
  - period: rolling 13-month retention
    scope: Per-key request counts
    text: rolling 13-month retention for historical billing inquiries, then aggregated and per-key detail deleted.
  - period: 7 days idle
    scope: Sessions
    text: deleted when the session expires (7 days idle), the user signs out, or the user explicitly revokes all sessions.
  - period: 90 days
    scope: Account security audit log
    text: 'Account security audit log : 90 days.'
  - period: ≤30 days
    scope: Server access logs
    text: 'Server access logs : ≤30 days.'
  - period: 7 years
    scope: Billing records
    text: 'Billing records : retained 7 years for US tax compliance.'
  rights:
  - right: access
    text: Request a copy of the data we hold associated with your email address;
  - right: correction
    text: Request correction of inaccurate data
  - right: deletion
    text: Request deletion of your account
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, rent it, or share it with advertising networks.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses with our subprocessors where applicable.
  - mechanism: other
    text: If you access the Service from outside the United States you consent to your data being processed in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ipatlas-dev
provenance_date: '2026-11-09'
provider_name: ipatlas-dev
provider_slug: ipatlas-dev
slug: ipatlas-dev-privacy-policy
source_date: '2026-11-09'
source_filename: ipatlas-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ip-atlas.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ipatlas-dev\naid: ipatlas-dev\nurl: https://ip-atlas.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address\n- category: financial\n  text: Stripe customer identifier\n- category: behavioral\n  text: Per-key request counts (daily and monthly)\n- category: device\n  text: a SHA-256 hash of your browser's user-agent string\n- category: location\n  text: the first two octets of your IPv4 (e.g. 203.0 — a /16 prefix; for IPv6, the first three groups — a /48)\n- category: other\n  text: SHA-256 hash of the cookie\npurposes:\n- purpose:\
  \ authenticate requests and enforce quotas\n  text: To authenticate requests and enforce plan quotas;\n- purpose: billing\n  text: To bill you correctly, including overage, and send receipts;\n- purpose: abuse and security investigation\n  text: To investigate abuse or security incidents.\nretention:\n- scope: Account email, password hash and API key hashes\n  period: 6 months\n  text: retained while the account is active, plus 6 months after deletion for fraud and audit purposes, then permanently\n    removed.\n- scope: Per-key request counts\n  period: rolling 13-month retention\n  text: rolling 13-month retention for historical billing inquiries, then aggregated and per-key detail deleted.\n- scope: Sessions\n  period: 7 days idle\n  text: deleted when the session expires (7 days idle), the user signs out, or the user explicitly revokes all sessions.\n- scope: Account security audit log\n  period: 90 days\n  text: 'Account security audit log : 90 days.'\n- scope: Server access logs\n\
  \  period: ≤30 days\n  text: 'Server access logs : ≤30 days.'\n- scope: Billing records\n  period: 7 years\n  text: 'Billing records : retained 7 years for US tax compliance.'\nresidency:\n- region: United States\n  text: IP-Atlas is hosted in the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses with our subprocessors where applicable.\n- mechanism: other\n  text: If you access the Service from outside the United States you consent to your data being processed in the\n    United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@ip-atlas.io\n  text: Request deletion of your account (we delete your email, key, and usage history subject to the retention\n    limits above).\nrights:\n- right: access\n  text: Request a copy of the data we hold associated with your email address;\n- right: correction\n  text: Request correction of inaccurate data\n- right: deletion\n\
  \  text: Request deletion of your account\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, rent it, or share it with advertising networks.\n"
source_yaml_url: https://artifacts.apis.io/ipatlas-dev/privacy/ipatlas-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from ipatlas-dev's own page on 2026-11-09.
synthetic: false
tags:
- IP
- Geolocation
- ASN
- VPN
- Data
---
