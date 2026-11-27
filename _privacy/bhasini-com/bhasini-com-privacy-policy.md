---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and the name you entered
  - category: contact
    text: Your email address and the name you entered , to identify your account and contact you about it.
  - category: financial
    text: 'Payment records from Razorpay: order and payment ids, pack, amount and date.'
  - category: device
    text: your IP address (in ChatGPT this is usually an OpenAI server address rather than your own), the time, the URL path, the HTTP method, the response status and size, and standard headers such as the user agent.
  - category: behavioral
    text: 'Your credit balance and daily usage : the number of characters and requests per day.'
  - category: communication
    text: Razorpay shares a record of the payment with us (amount, date, transaction reference and the contact details you entered, such as name, email or phone).
  deletion:
    route: Email us to close your account or request deletion
    text: To close your account and delete its data, write to us from your account's email address.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Rate limiting and service operation
    text: These are used only to rate-limit and to keep the service running
  - purpose: Translation API account management
    text: to identify your account and contact you about it
  - purpose: Payment confirmation and accounting
    text: We use this record only to confirm the payment, to reply to you and to meet accounting and tax obligations.
  - purpose: Security and fault finding
    text: We use them only to find faults and abuse.
  residency:
  - region: United States and India
    text: connection data may be processed in countries other than your own, including the United States and India.
  retention:
  - period: null
    scope: Tool input and output text
    text: Not kept. Discarded when the request ends.
  - period: 60 seconds
    scope: IP address in the rate-limit counter
    text: IP address in the rate-limit counter 60 seconds
  - period: within 7 days
    scope: Cloudflare Workers operational logs
    text: Deleted automatically within 7 days
  - period: null
    scope: Translation API account
    text: Until you ask us to close the account, then deleted within 30 days (payment records are kept as above)
  - period: up to 8 years
    scope: Sponsorship and API payment records
    text: As long as Indian accounting and tax law requires (currently up to 8 years)
  rights:
  - right: Access, correction and deletion
    text: email us to ask what data we hold about you, or to ask us to correct or delete it.
  - right: Complaint to data protection authority
    text: including the right to complain to a data protection authority.
  - right: Disconnect plugin
    text: disconnect or remove Bhasini in ChatGPT's settings (Apps or Plugins) at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it for advertising or profiling.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bhasini
provenance_date: '2026-11-09'
provider_name: Bhasini
provider_slug: bhasini-com
slug: bhasini-com-privacy-policy
source_date: '2026-11-09'
source_filename: bhasini-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bhasini.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bhasini\naid: bhasini-com\nurl: https://bhasini.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address and the name you entered\n- category: contact\n  text: Your email address and the name you entered , to identify your account and contact you about it.\n- category: financial\n  text: 'Payment records from Razorpay: order and payment ids, pack, amount and date.'\n- category: device\n  text: your IP address (in ChatGPT this is usually an OpenAI server address rather than your own), the time, the\n    URL path,\
  \ the HTTP method, the response status and size, and standard headers such as the user agent.\n- category: behavioral\n  text: 'Your credit balance and daily usage : the number of characters and requests per day.'\n- category: communication\n  text: Razorpay shares a record of the payment with us (amount, date, transaction reference and the contact details\n    you entered, such as name, email or phone).\npurposes:\n- purpose: Rate limiting and service operation\n  text: These are used only to rate-limit and to keep the service running\n- purpose: Translation API account management\n  text: to identify your account and contact you about it\n- purpose: Payment confirmation and accounting\n  text: We use this record only to confirm the payment, to reply to you and to meet accounting and tax obligations.\n- purpose: Security and fault finding\n  text: We use them only to find faults and abuse.\nretention:\n- scope: Tool input and output text\n  period: null\n  text: Not kept. Discarded when\
  \ the request ends.\n- scope: IP address in the rate-limit counter\n  period: 60 seconds\n  text: IP address in the rate-limit counter 60 seconds\n- scope: Cloudflare Workers operational logs\n  period: within 7 days\n  text: Deleted automatically within 7 days\n- scope: Translation API account\n  period: null\n  text: Until you ask us to close the account, then deleted within 30 days (payment records are kept as above)\n- scope: Sponsorship and API payment records\n  period: up to 8 years\n  text: As long as Indian accounting and tax law requires (currently up to 8 years)\nresidency:\n- region: United States and India\n  text: connection data may be processed in countries other than your own, including the United States and India.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email us to close your account or request deletion\n  text: To close your account and delete its data, write to us from your account's\
  \ email address.\nrights:\n- right: Access, correction and deletion\n  text: email us to ask what data we hold about you, or to ask us to correct or delete it.\n- right: Complaint to data protection authority\n  text: including the right to complain to a data protection authority.\n- right: Disconnect plugin\n  text: disconnect or remove Bhasini in ChatGPT's settings (Apps or Plugins) at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it for advertising or profiling.\n"
source_yaml_url: https://artifacts.apis.io/bhasini-com/privacy/bhasini-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Bhasini's own page on 2026-11-09.
synthetic: false
tags:
- Typing
- Indian Languages
- Free
- Web App
- Utility
---
