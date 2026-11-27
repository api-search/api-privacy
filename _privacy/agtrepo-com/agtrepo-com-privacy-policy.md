---
api_specs:
- filename: agtrepo-com-account-api-openapi.yml
  format: yaml
  label: A2A Account API
  slug: agtrepo-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-account-api-openapi.yml
- filename: agtrepo-com-auth-api-openapi.yml
  format: yaml
  label: A2A Auth API
  slug: agtrepo-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-auth-api-openapi.yml
- filename: agtrepo-com-billing-api-openapi.yml
  format: yaml
  label: A2A Billing API
  slug: agtrepo-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-billing-api-openapi.yml
- filename: agtrepo-com-discovery-api-openapi.yml
  format: yaml
  label: A2A Discovery API
  slug: agtrepo-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-discovery-api-openapi.yml
- filename: agtrepo-com-feedback-api-openapi.yml
  format: yaml
  label: A2A Feedback API
  slug: agtrepo-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-feedback-api-openapi.yml
- filename: agtrepo-com-key-requests-api-openapi.yml
  format: yaml
  label: A2A Key Requests API
  slug: agtrepo-com-key-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-key-requests-api-openapi.yml
- filename: agtrepo-com-memory-api-openapi.yml
  format: yaml
  label: A2A Memory API
  slug: agtrepo-com-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-memory-api-openapi.yml
- filename: agtrepo-com-search-api-openapi.yml
  format: yaml
  label: A2A Search API
  slug: agtrepo-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agtrepo-com/openapi/agtrepo-com-search-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Wallet addresses that interact with the Protocol (storing, reading, extending, or paying for a Memory).
  - category: financial
    text: 'Payment records — for each paid action: the paying wallet, the action, the amount, how it was paid, and the on-chain transaction hash where there is one.'
  - category: communication
    text: Feedback submissions — an optional name and your message, if you use the feedback form, API, or MCP tool.
  - category: device
    text: Standard web server logs (e.g. request IP addresses) retained temporarily for security and abuse prevention.
  - category: other
    text: Encrypted content and its metadata — ciphertext, tags, title, size, timestamps, and expiration.
  - category: other
    text: Optional public profile data — display name, bio, and links, only if you voluntarily create a profile and set it to public.
  deletion:
    route: Delete public profile from the account dashboard; other requests by contacting the listed address
    text: You may permanently delete a public profile at any time from the account dashboard — this is a hard delete, not a visibility toggle
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: security and abuse prevention
    text: Standard web server logs (e.g. request IP addresses) retained temporarily for security and abuse prevention.
  - purpose: payment facilitation
    text: Coinbase Developer Platform — facilitates and settles x402 payments on Base.
  retention:
  - period: until its time-to-live expires
    scope: Encrypted Memory content
    text: Encrypted Memory content is retained until its time-to-live expires, per the Protocol's discovery manifest , and is then deleted automatically.
  - period: null
    scope: Payment records
    text: Payment records are kept after the Memory they relate to is gone.
  - period: null
    scope: Feedback messages
    text: Feedback messages are forwarded by email and Telegram at the time of submission and are not separately stored in a database.
  - period: until you delete them
    scope: Public profiles
    text: Public profiles persist until you delete them.
  rights:
  - right: deletion of public profile
    text: You may permanently delete a public profile at any time from the account dashboard
  - right: access, correction, deletion
    text: For any other request about data we hold (access, correction, deletion), contact us using the address below.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share it for advertising purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: A2A
provenance_date: '2026-11-09'
provider_name: A2A
provider_slug: agtrepo-com
slug: agtrepo-com-privacy-policy
source_date: '2026-11-09'
source_filename: agtrepo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agtrepo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: A2A\naid: agtrepo-com\nurl: https://agtrepo.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Wallet addresses that interact with the Protocol (storing, reading, extending, or paying for a Memory).\n- category: financial\n  text: 'Payment records — for each paid action: the paying wallet, the action, the amount, how it was paid, and\n    the on-chain transaction hash where there is one.'\n- category: communication\n  text: Feedback submissions — an optional name and your message, if you use the feedback form, API, or MCP tool.\n\
  - category: device\n  text: Standard web server logs (e.g. request IP addresses) retained temporarily for security and abuse prevention.\n- category: other\n  text: Encrypted content and its metadata — ciphertext, tags, title, size, timestamps, and expiration.\n- category: other\n  text: Optional public profile data — display name, bio, and links, only if you voluntarily create a profile and\n    set it to public.\npurposes:\n- purpose: security and abuse prevention\n  text: Standard web server logs (e.g. request IP addresses) retained temporarily for security and abuse prevention.\n- purpose: payment facilitation\n  text: Coinbase Developer Platform — facilitates and settles x402 payments on Base.\nretention:\n- scope: Encrypted Memory content\n  period: until its time-to-live expires\n  text: Encrypted Memory content is retained until its time-to-live expires, per the Protocol's discovery manifest\n    , and is then deleted automatically.\n- scope: Payment records\n  period: null\n \
  \ text: Payment records are kept after the Memory they relate to is gone.\n- scope: Feedback messages\n  period: null\n  text: Feedback messages are forwarded by email and Telegram at the time of submission and are not separately stored\n    in a database.\n- scope: Public profiles\n  period: until you delete them\n  text: Public profiles persist until you delete them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete public profile from the account dashboard; other requests by contacting the listed address\n  text: You may permanently delete a public profile at any time from the account dashboard — this is a hard delete,\n    not a visibility toggle\nrights:\n- right: deletion of public profile\n  text: You may permanently delete a public profile at any time from the account dashboard\n- right: access, correction, deletion\n  text: For any other request about data we hold (access, correction,\
  \ deletion), contact us using the address below.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or share it for advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/agtrepo-com/privacy/agtrepo-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from A2A's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Persistent-Memory
- MCP
- Payments
- Encryption
- Storage
---
