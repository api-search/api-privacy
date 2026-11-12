---
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address is added as a contact to our list in Resend.
  - category: identifying
    text: a daily call counter keyed by a truncated SHA-256 hash of your IP address.
  - category: financial
    text: a credit ledger with the Stripe checkout session ID, or the transaction hash for USDC on Base payments
  deletion:
    route: email
    text: To request access or deletion, email support@rendlet.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: manage subscriber list
    text: so we can manage the subscriber list
  - purpose: answer tool calls
    text: The tool arguments you send are processed to answer the call and are not stored.
  - purpose: payment processing
    text: Stripe processes the payment, so we never see your card number.
  retention:
  - period: about a day after they expire
    scope: unpaid USDC quotes
    text: Unpaid USDC quotes are deleted about a day after they expire.
  - period: null
    scope: subscriber contact
    text: When a subscription ends, the contact is removed from that list.
  - period: null
    scope: other data
    text: We haven't set automatic deletion periods for other data.
  rights:
  - right: access and deletion requests
    text: To request access or deletion, email support@rendlet.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Neon : the MCP database (rate limits, keys, credits).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CN RegWatch
provenance_date: '2026-11-09'
provider_name: CN RegWatch
provider_slug: cnregwatch-com
slug: cnregwatch-com-privacy-policy
source_date: '2026-11-09'
source_filename: cnregwatch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cnregwatch.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CN RegWatch\naid: cnregwatch-com\nurl: https://cnregwatch.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email address is added as a contact to our list in Resend.\n- category: identifying\n  text: a daily call counter keyed by a truncated SHA-256 hash of your IP address.\n- category: financial\n  text: a credit ledger with the Stripe checkout session ID, or the transaction hash for USDC on Base payments\npurposes:\n- purpose: manage subscriber list\n  text: so we can manage the subscriber list\n- purpose: answer tool calls\n\
  \  text: The tool arguments you send are processed to answer the call and are not stored.\n- purpose: payment processing\n  text: Stripe processes the payment, so we never see your card number.\nretention:\n- scope: unpaid USDC quotes\n  period: about a day after they expire\n  text: Unpaid USDC quotes are deleted about a day after they expire.\n- scope: subscriber contact\n  period: null\n  text: When a subscription ends, the contact is removed from that list.\n- scope: other data\n  period: null\n  text: We haven't set automatic deletion periods for other data.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Neon : the MCP database (rate limits, keys, credits).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: To request access or deletion, email support@rendlet.com\nrights:\n- right: access and deletion requests\n  text: To request access or deletion, email support@rendlet.com\nsale_or_sharing:\n  stance: unstated\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/cnregwatch-com/privacy/cnregwatch-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 12 quoted statements, read from CN RegWatch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- China
- Regulatory Compliance
- Regulation Monitoring
- Government Policy
- Foreign Investment
- Alerts
- MCP
---
