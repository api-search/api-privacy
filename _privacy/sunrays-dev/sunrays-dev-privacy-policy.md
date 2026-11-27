---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: caller_id — your email address or OAuth identity, used as a Stripe customer key.
  - category: location
    text: Booking details — service category, zip code, requested datetime, issue description.
  - category: financial
    text: Payment method — stored securely by Stripe as a SetupIntent . Sunrays stores only the Stripe PaymentMethod ID and Customer ID reference, not card numbers.
  - category: behavioral
    text: Setup-card page analytics — time on page, completion vs abandonment, agent attribution.
  - category: device
    text: Web server logs — standard HTTP access logs (IP, user agent, path, response code). Retained 30 days.
  deletion:
    route: Email help@sunrays.dev
    text: 'Email help@sunrays.dev to: Access the data we hold about you. Delete your account and booking history (subject to legal retention requirements). Request deletion of your Stripe payment method.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Execute and confirm bookings
    text: Execute and confirm your booking (dispatch a tradesperson, send a receipt).
  - purpose: Payment processing
    text: Process payment via Stripe Connect (auth on booking, capture on dispatch confirmation, refund if needed).
  - purpose: Product improvement
    text: Improve the product using aggregate, anonymized telemetry (tool-selection patterns, abandonment rates, geographic demand).
  - purpose: Legal and insurance obligations
    text: Meet legal and insurance obligations.
  retention:
  - period: 7 years
    scope: Booking records
    text: 'Booking records: retained for 7 years (tax and insurance compliance).'
  - period: null
    scope: Stripe payment methods
    text: 'Stripe payment methods: retained until you request deletion or we are required to delete.'
  - period: 30 days
    scope: Web server logs
    text: 'Web server logs: 30 days.'
  rights:
  - right: Access
    text: Access the data we hold about you.
  - right: Deletion
    text: Delete your account and booking history (subject to legal retention requirements).
  - right: Correction
    text: Correct inaccurate data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: sunrays-dev
provenance_date: '2026-11-10'
provider_name: sunrays-dev
provider_slug: sunrays-dev
slug: sunrays-dev-privacy-policy
source_date: '2026-11-10'
source_filename: sunrays-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sunrays.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sunrays-dev\naid: sunrays-dev\nurl: https://sunrays.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: caller_id — your email address or OAuth identity, used as a Stripe customer key.\n- category: location\n  text: Booking details — service category, zip code, requested datetime, issue description.\n- category: financial\n  text: Payment method — stored securely by Stripe as a SetupIntent . Sunrays stores only the Stripe PaymentMethod\n    ID and Customer ID reference, not card numbers.\n- category: behavioral\n  text: Setup-card\
  \ page analytics — time on page, completion vs abandonment, agent attribution.\n- category: device\n  text: Web server logs — standard HTTP access logs (IP, user agent, path, response code). Retained 30 days.\npurposes:\n- purpose: Execute and confirm bookings\n  text: Execute and confirm your booking (dispatch a tradesperson, send a receipt).\n- purpose: Payment processing\n  text: Process payment via Stripe Connect (auth on booking, capture on dispatch confirmation, refund if needed).\n- purpose: Product improvement\n  text: Improve the product using aggregate, anonymized telemetry (tool-selection patterns, abandonment rates, geographic\n    demand).\n- purpose: Legal and insurance obligations\n  text: Meet legal and insurance obligations.\nretention:\n- scope: Booking records\n  period: 7 years\n  text: 'Booking records: retained for 7 years (tax and insurance compliance).'\n- scope: Stripe payment methods\n  period: null\n  text: 'Stripe payment methods: retained until you request\
  \ deletion or we are required to delete.'\n- scope: Web server logs\n  period: 30 days\n  text: 'Web server logs: 30 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email help@sunrays.dev\n  text: 'Email help@sunrays.dev to: Access the data we hold about you. Delete your account and booking history (subject\n    to legal retention requirements). Request deletion of your Stripe payment method.'\nrights:\n- right: Access\n  text: Access the data we hold about you.\n- right: Deletion\n  text: Delete your account and booking history (subject to legal retention requirements).\n- right: Correction\n  text: Correct inaccurate data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/sunrays-dev/privacy/sunrays-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from sunrays-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Booking
- Local Services
- MCP
- Agent-Callable
---
