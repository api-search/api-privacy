---
api_specs:
- filename: tessio-eu-age-verification-api-openapi.yml
  format: yaml
  label: tessio-eu Age Verification API
  slug: tessio-eu-age-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessio-eu/openapi/tessio-eu-age-verification-api-openapi.yml
- filename: tessio-eu-stats-api-openapi.yml
  format: yaml
  label: tessio-eu Stats API
  slug: tessio-eu-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessio-eu/openapi/tessio-eu-stats-api-openapi.yml
- filename: tessio-eu-webhooks-api-openapi.yml
  format: yaml
  label: tessio-eu Webhooks API
  slug: tessio-eu-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessio-eu/openapi/tessio-eu-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: we process your email address and password (stored as an Argon2id hash; we never see the plaintext)
  - category: financial
    text: If your organisation is billed, we also hold its billing details (legal name, address, VAT and registration numbers, billing email and any purchase reference) to invoice it.
  - category: behavioral
    text: aggregate page statistics and does not build visitor profiles, use cookies or share data with third parties
  - category: device
    text: the browser family rather than the full browser string
  - category: communication
    text: If you email us, we keep the correspondence for as long as the conversation is relevant.
  - category: identifying
    text: we received no name, no date of birth, no document number and no photo
  deletion:
    route: Write to hello@tessio.eu
    text: If you ask us to delete your data, we do, and the deletion reaches backups as they expire.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website analytics
    text: Our websites use self hosted, cookieless analytics (Umami, running on our own EU infrastructure).
  - purpose: Contract performance for dashboard accounts
    text: 'Legal basis: performance of the contract with you or your employer.'
  - purpose: Abuse prevention
    text: To limit abuse, the pages and endpoints a check uses count requests per network address (an IPv6 address by its /64 block).
  residency:
  - region: Finland
    text: Everything runs on servers in Helsinki, Finland (Hetzner), inside the EU, over TLS.
  retention:
  - period: as long as the account
    scope: Account data
    text: Account data lives as long as the account.
  - period: 30 days
    scope: Check records on Free and Starter
    text: 30 days on Free and Starter, 90 days on Growth and a year on Platform and on Self host where we host it, counted from the check.
  - period: a day
    scope: Demo checks
    text: Demo checks are deleted a day later.
  - period: an hour after the last request
    scope: Network address counters
    text: is deleted an hour after the last request
  - period: within 25 days in normal operation
    scope: Backups
    text: Backup copies, and the storage snapshots that hold them, are deleted on a rolling schedule, within 25 days in normal operation.
  rights:
  - right: access, correction, deletion, restriction, portability
    text: Under the GDPR you can ask for access, correction, deletion, restriction and portability
  - right: object
    text: you can object to processing based on legitimate interest
  - right: complain to supervisory authority
    text: You can also complain to the Swedish supervisory authority, Integritetsskyddsmyndigheten (imy.se), or to your local authority.
  role:
    text: We are the data controller for the processing described on this page.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal data with anyone for their own purposes.
  subprocessors:
    text: We list the few external services we use, and the conditions, on the subprocessors page.
    url: https://tessio.eu/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tessio-eu
provenance_date: '2026-11-10'
provider_name: tessio-eu
provider_slug: tessio-eu
slug: tessio-eu-privacy-policy
source_date: '2026-11-10'
source_filename: tessio-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tessio.eu/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tessio-eu\naid: tessio-eu\nurl: https://tessio.eu/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the processing described on this page.\ndata_categories:\n- category: contact\n  text: we process your email address and password (stored as an Argon2id hash; we never see the plaintext)\n- category: financial\n  text: If your organisation is billed, we also hold its billing details (legal name, address, VAT and registration\n    numbers, billing email and any purchase reference) to invoice it.\n- category: behavioral\n  text: aggregate page statistics and\
  \ does not build visitor profiles, use cookies or share data with third parties\n- category: device\n  text: the browser family rather than the full browser string\n- category: communication\n  text: If you email us, we keep the correspondence for as long as the conversation is relevant.\n- category: identifying\n  text: we received no name, no date of birth, no document number and no photo\npurposes:\n- purpose: Website analytics\n  text: Our websites use self hosted, cookieless analytics (Umami, running on our own EU infrastructure).\n- purpose: Contract performance for dashboard accounts\n  text: 'Legal basis: performance of the contract with you or your employer.'\n- purpose: Abuse prevention\n  text: To limit abuse, the pages and endpoints a check uses count requests per network address (an IPv6 address\n    by its /64 block).\nretention:\n- scope: Account data\n  period: as long as the account\n  text: Account data lives as long as the account.\n- scope: Check records on Free and\
  \ Starter\n  period: 30 days\n  text: 30 days on Free and Starter, 90 days on Growth and a year on Platform and on Self host where we host it,\n    counted from the check.\n- scope: Demo checks\n  period: a day\n  text: Demo checks are deleted a day later.\n- scope: Network address counters\n  period: an hour after the last request\n  text: is deleted an hour after the last request\n- scope: Backups\n  period: within 25 days in normal operation\n  text: Backup copies, and the storage snapshots that hold them, are deleted on a rolling schedule, within 25 days\n    in normal operation.\nresidency:\n- region: Finland\n  text: Everything runs on servers in Helsinki, Finland (Hetzner), inside the EU, over TLS.\ntransfers: []\nsubprocessors:\n  url: https://tessio.eu/subprocessors\n  text: We list the few external services we use, and the conditions, on the subprocessors page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@tessio.eu\n  text: If you ask\
  \ us to delete your data, we do, and the deletion reaches backups as they expire.\nrights:\n- right: access, correction, deletion, restriction, portability\n  text: Under the GDPR you can ask for access, correction, deletion, restriction and portability\n- right: object\n  text: you can object to processing based on legitimate interest\n- right: complain to supervisory authority\n  text: You can also complain to the Swedish supervisory authority, Integritetsskyddsmyndigheten (imy.se), or to\n    your local authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal data with anyone for their own purposes.\n"
source_yaml_url: https://artifacts.apis.io/tessio-eu/privacy/tessio-eu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from tessio-eu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Age Verification
- EU
- Identity
---
