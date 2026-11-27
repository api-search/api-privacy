---
api_specs:
- filename: sitey-my-check-api-openapi.yml
  format: yaml
  label: sitey-my Check API
  slug: sitey-my-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitey-my/openapi/sitey-my-check-api-openapi.yml
- filename: sitey-my-domains-api-openapi.yml
  format: yaml
  label: sitey-my Domains API
  slug: sitey-my-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitey-my/openapi/sitey-my-domains-api-openapi.yml
- filename: sitey-my-subdomains-api-openapi.yml
  format: yaml
  label: sitey-my Subdomains API
  slug: sitey-my-subdomains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sitey-my/openapi/sitey-my-subdomains-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Google account identifier Display name and profile picture URL
  - category: contact
    text: Email address Google account identifier Display name and profile picture URL Time of sign-up
  - category: device
    text: the creator's IP address
  - category: behavioral
    text: The subject making the request — an account, or an anonymous identifier
  - category: communication
    text: Which kind of message was sent and when, and a hash of the recipient address
  deletion:
    route: Email ljj5256@gmail.com; delete subdomain records from the dashboard
    text: You can also delete your subdomain records yourself from the dashboard at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Signing you in
    text: Identifying you, signing you in
  - purpose: Providing the DNS service
    text: Subdomain records Providing the DNS service
  - purpose: Establishing ownership, preventing abuse
    text: IP on account-less records Establishing ownership, preventing abuse
  - purpose: Diagnosing faults and preventing abuse
    text: Server logs Diagnosing faults, preventing abuse, improving the service
  - purpose: Sending expiry notices
    text: Email address Sending expiry notices
  residency:
  - region: Outside Korea
    text: data is stored on servers outside Korea
  retention:
  - period: null
    scope: Account details
    text: Account details — erased without delay when you ask us to close your account
  - period: null
    scope: Subdomain records
    text: Subdomain records — until the record is deleted or reclaimed at expiry
  - period: null
    scope: API keys
    text: API keys — until you delete them
  - period: null
    scope: Sessions
    text: Sessions — invalid once expired, and removed periodically
  - period: null
    scope: Server logs
    text: Server logs — kept for as long as fault diagnosis and abuse assessment require, then deleted oldest first
  rights:
  - right: Access
    text: You may ask us to show you the personal data we hold
  - right: Correction
    text: correct it
  - right: Erasure
    text: erase it
  - right: Restriction of processing
    text: or stop processing it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not pass it to anyone else.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: All four processors are outside Korea, and data is stored on servers outside Korea.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: sitey-my
provenance_date: '2026-11-10'
provider_name: sitey-my
provider_slug: sitey-my
slug: sitey-my-privacy-policy
source_date: '2026-11-10'
source_filename: sitey-my-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sitey.my/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sitey-my\naid: sitey-my\nurl: https://sitey.my/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Google account identifier Display name and profile picture URL\n- category: contact\n  text: Email address Google account identifier Display name and profile picture URL Time of sign-up\n- category: device\n  text: the creator's IP address\n- category: behavioral\n  text: The subject making the request — an account, or an anonymous identifier\n- category: communication\n  text: Which kind of message was sent and when, and a hash of the\
  \ recipient address\npurposes:\n- purpose: Signing you in\n  text: Identifying you, signing you in\n- purpose: Providing the DNS service\n  text: Subdomain records Providing the DNS service\n- purpose: Establishing ownership, preventing abuse\n  text: IP on account-less records Establishing ownership, preventing abuse\n- purpose: Diagnosing faults and preventing abuse\n  text: Server logs Diagnosing faults, preventing abuse, improving the service\n- purpose: Sending expiry notices\n  text: Email address Sending expiry notices\nretention:\n- scope: Account details\n  period: null\n  text: Account details — erased without delay when you ask us to close your account\n- scope: Subdomain records\n  period: null\n  text: Subdomain records — until the record is deleted or reclaimed at expiry\n- scope: API keys\n  period: null\n  text: API keys — until you delete them\n- scope: Sessions\n  period: null\n  text: Sessions — invalid once expired, and removed periodically\n- scope: Server logs\n \
  \ period: null\n  text: Server logs — kept for as long as fault diagnosis and abuse assessment require, then deleted oldest first\nresidency:\n- region: Outside Korea\n  text: data is stored on servers outside Korea\ntransfers:\n- mechanism: other\n  text: All four processors are outside Korea, and data is stored on servers outside Korea.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email ljj5256@gmail.com; delete subdomain records from the dashboard\n  text: You can also delete your subdomain records yourself from the dashboard at any time.\nrights:\n- right: Access\n  text: You may ask us to show you the personal data we hold\n- right: Correction\n  text: correct it\n- right: Erasure\n  text: erase it\n- right: Restriction of processing\n  text: or stop processing it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not pass it to anyone else.\n"
source_yaml_url: https://artifacts.apis.io/sitey-my/privacy/sitey-my-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from sitey-my's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Website Builder
- Sub Domain
- MCP
---
