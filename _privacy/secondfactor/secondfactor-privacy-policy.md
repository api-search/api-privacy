---
api_specs:
- filename: secondfactor-openapi-generated.yml
  format: yaml
  label: SecondFactor API
  slug: secondfactor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/secondfactor/openapi/_ae-authored/secondfactor-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity and contact details: full name, email address, mobile number, password (stored hashed, never in plain text).'
  - category: financial
    text: 'Billing information: processed through our third-party payment processor, we do not store full card numbers on our own systems.'
  - category: communication
    text: The destination phone number for an OTP.
  - category: device
    text: 'Device and technical data: IP address, browser type, operating system.'
  - category: behavioral
    text: 'Usage data: pages visited on our dashboard, features used, API call metadata (endpoint, timestamp, response status).'
  deletion:
    route: contact support@secondfactor.ai to close your account
    text: you may close your account by contacting support@secondfactor.ai.
  dpa:
    available: true
    text: Our handling of End User Data on your behalf is further governed by our standard Data Processing Terms, available on request.
    url: null
  purposes:
  - purpose: Account creation, authentication, and support
    text: to create your account, verify your identity, secure your login, and respond when you contact support.
  - purpose: Fraud and abuse prevention
    text: to detect and prevent fraud, including SMS pumping and Artificially Inflated Traffic (AIT), across our platform
  - purpose: Product improvement and aggregated research
    text: to understand how our Services and PIE's routing decisions are performing
  - purpose: Marketing communications
    text: to tell you about new features, channels, or pricing changes that may interest you.
  retention:
  - period: for as long as your account is active
    scope: Account Data
    text: 'Account Data: for as long as your account is active, and for a reasonable period afterward to satisfy accounting, tax, audit, or dispute-resolution needs.'
  - period: the short window needed to complete the send/verify cycle
    scope: OTP codes themselves
    text: 'OTP codes themselves: for only the short window needed to complete the send/verify cycle, then discarded.'
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correct
    text: Correct inaccurate or incomplete personal data.
  - right: Delete
    text: Delete your personal data, subject to legal or contractual retention requirements.
  - right: Restrict or object
    text: Restrict or object to certain processing.
  - right: Port
    text: Port your data to another provider, in a structured, commonly used format.
  - right: Withdraw consent
    text: Withdraw consent at any time, where processing is based on consent
  - right: Complain
    text: Lodge a complaint with your local data protection authority.
  role:
    text: As Data Controller, for Account Data
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on an appropriate safeguard such as Standard Contractual Clauses or another lawful transfer mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SecondFactor
provenance_date: '2026-11-10'
provider_name: SecondFactor
provider_slug: secondfactor
slug: secondfactor-privacy-policy
source_date: '2026-11-10'
source_filename: secondfactor-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://secondfactor.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SecondFactor\naid: secondfactor\nurl: https://secondfactor.ai/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As Data Controller, for Account Data\ndata_categories:\n- category: identifying\n  text: 'Identity and contact details: full name, email address, mobile number, password (stored hashed, never in\n    plain text).'\n- category: financial\n  text: 'Billing information: processed through our third-party payment processor, we do not store full card numbers\n    on our own systems.'\n- category: communication\n  text: The destination phone number for an OTP.\n- category: device\n  text:\
  \ 'Device and technical data: IP address, browser type, operating system.'\n- category: behavioral\n  text: 'Usage data: pages visited on our dashboard, features used, API call metadata (endpoint, timestamp, response\n    status).'\npurposes:\n- purpose: Account creation, authentication, and support\n  text: to create your account, verify your identity, secure your login, and respond when you contact support.\n- purpose: Fraud and abuse prevention\n  text: to detect and prevent fraud, including SMS pumping and Artificially Inflated Traffic (AIT), across our platform\n- purpose: Product improvement and aggregated research\n  text: to understand how our Services and PIE's routing decisions are performing\n- purpose: Marketing communications\n  text: to tell you about new features, channels, or pricing changes that may interest you.\nretention:\n- scope: Account Data\n  period: for as long as your account is active\n  text: 'Account Data: for as long as your account is active, and for a reasonable\
  \ period afterward to satisfy accounting,\n    tax, audit, or dispute-resolution needs.'\n- scope: OTP codes themselves\n  period: the short window needed to complete the send/verify cycle\n  text: 'OTP codes themselves: for only the short window needed to complete the send/verify cycle, then discarded.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on an appropriate safeguard such as Standard Contractual Clauses or another lawful transfer mechanism\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Our handling of End User Data on your behalf is further governed by our standard Data Processing Terms,\n    available on request.\ndeletion:\n  route: contact support@secondfactor.ai to close your account\n  text: you may close your account by contacting support@secondfactor.ai.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correct\n  text: Correct inaccurate or incomplete personal data.\n- right:\
  \ Delete\n  text: Delete your personal data, subject to legal or contractual retention requirements.\n- right: Restrict or object\n  text: Restrict or object to certain processing.\n- right: Port\n  text: Port your data to another provider, in a structured, commonly used format.\n- right: Withdraw consent\n  text: Withdraw consent at any time, where processing is based on consent\n- right: Complain\n  text: Lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/secondfactor/privacy/secondfactor-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from SecondFactor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- OTP
- Authentication
- Multi-Channel
- Messaging
---
