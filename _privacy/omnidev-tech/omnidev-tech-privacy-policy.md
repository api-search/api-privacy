---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: other
    text: API Request content (prompts, quotes) is forwarded to an upstream provider to produce the result and is not used for any other purpose.
  - category: financial
    text: Payment records (payer address, amount, transaction hash, hashed credential keys) are kept to prevent double spending and for accounting.
  - category: device
    text: Request logs hold the time, route, status and client IP address, and are used for abuse prevention and operations.
  - category: contact
    text: The contact form sends the message you type (and the optional name and reply details you add) to the operator by email.
  deletion:
    route: contact form
    text: For questions or requests about personal data, use the contact form .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: produce result
    text: is forwarded to an upstream provider to produce the result and is not used for any other purpose
  - purpose: prevent double spending and accounting
    text: Payment records (payer address, amount, transaction hash, hashed credential keys) are kept to prevent double spending and for accounting.
  - purpose: abuse prevention and operations
    text: Request logs hold the time, route, status and client IP address, and are used for abuse prevention and operations.
  - purpose: answer contact messages
    text: It is used only to answer you.
  retention:
  - period: limited time
    scope: completed result
    text: A completed result is stored for a limited time so that the paying client can retrieve it again with the same credential and nonce.
  - period: 14 days
    scope: undelivered contact form message
    text: If email delivery is temporarily unavailable, the message is held for up to 14 days and then deleted.
  rights:
  - right: questions or requests about personal data
    text: For questions or requests about personal data, use the contact form .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Data is not sold.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: omnidev-tech
provenance_date: '2026-11-10'
provider_name: omnidev-tech
provider_slug: omnidev-tech
slug: omnidev-tech-privacy-policy
source_date: '2026-11-10'
source_filename: omnidev-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://provider.omnidev.tech/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: omnidev-tech\naid: omnidev-tech\nurl: https://provider.omnidev.tech/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: API Request content (prompts, quotes) is forwarded to an upstream provider to produce the result and is\n    not used for any other purpose.\n- category: financial\n  text: Payment records (payer address, amount, transaction hash, hashed credential keys) are kept to prevent double\n    spending and for accounting.\n- category: device\n  text: Request logs hold the time, route, status and client IP address, and are used for\
  \ abuse prevention and operations.\n- category: contact\n  text: The contact form sends the message you type (and the optional name and reply details you add) to the operator\n    by email.\npurposes:\n- purpose: produce result\n  text: is forwarded to an upstream provider to produce the result and is not used for any other purpose\n- purpose: prevent double spending and accounting\n  text: Payment records (payer address, amount, transaction hash, hashed credential keys) are kept to prevent double\n    spending and for accounting.\n- purpose: abuse prevention and operations\n  text: Request logs hold the time, route, status and client IP address, and are used for abuse prevention and operations.\n- purpose: answer contact messages\n  text: It is used only to answer you.\nretention:\n- scope: completed result\n  period: limited time\n  text: A completed result is stored for a limited time so that the paying client can retrieve it again with the\n    same credential and nonce.\n- scope:\
  \ undelivered contact form message\n  period: 14 days\n  text: If email delivery is temporarily unavailable, the message is held for up to 14 days and then deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact form\n  text: For questions or requests about personal data, use the contact form .\nrights:\n- right: questions or requests about personal data\n  text: For questions or requests about personal data, use the contact form .\nsale_or_sharing:\n  stance: prohibited\n  text: Data is not sold.\n"
source_yaml_url: https://artifacts.apis.io/omnidev-tech/privacy/omnidev-tech-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from omnidev-tech's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Pay-per-call
- Company
---
