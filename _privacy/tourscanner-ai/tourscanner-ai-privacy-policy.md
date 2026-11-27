---
api_specs:
- filename: tourscanner-ai-tourscanner-api-openapi.yml
  format: yaml
  label: TourScanner API
  slug: tourscanner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tourscanner-ai/openapi/tourscanner-ai-tourscanner-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Traveller name, email address, phone number, party details, the activity, date and time, and any answers the supplier asks for.
  - category: financial
    text: We receive the payment status, amount, currency and a reference.
  - category: location
    text: If you share a location, we resolve it to the nearest city and round it to about 1 km before it is logged.
  - category: behavioral
    text: Pages viewed, clicks, device and browser data, and session recordings and heatmaps.
  - category: communication
    text: Messages you send to our AI agent, the tool calls it makes and its replies.
  - category: identifying
    text: Email address and sign-in data. You can sign in with an emailed magic link or with Google.
  deletion:
    route: email request to the privacy contact in section 7
    text: Under the GDPR and similar laws you can ask to access, correct, delete or export your data, restrict or object to some processing, and withdraw consent at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and API keys
    text: Used to run your account and API keys.
  - purpose: security, rate limiting, billing
    text: Used for security, rate limiting, debugging and billing.
  - purpose: booking management
    text: Used to hold, confirm, amend or cancel the booking and to send vouchers.
  - purpose: AI agent replies and improvement
    text: Used to answer you, to debug and to improve the agent.
  - purpose: site analytics
    text: Used to understand and improve the site.
  retention:
  - period: while your account is active
    scope: account data
    text: 'Account data: while your account is active, then deleted or anonymised on request or after it closes, except what we must keep.'
  - period: as long as tax, accounting and dispute rules require
    scope: booking and payment records
    text: 'Booking and payment records: as long as tax, accounting and dispute rules require.'
  - period: only as long as needed for security, debugging and improvement
    scope: logs and AI conversations
    text: 'Logs and AI conversations: only as long as needed for security, debugging and improvement, then deleted or aggregated.'
  rights:
  - right: access, correction, deletion, export
    text: Under the GDPR and similar laws you can ask to access, correct, delete or export your data, restrict or object to some processing, and withdraw consent at any time.
  - right: complain to authority
    text: You can also complain to your local data protection authority.
  role:
    text: 'Website, accounts and API access: we are the controller of the data described below.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use it for third-party advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Where data leaves the EEA, we rely on an adequacy decision or on standard contractual clauses.
  - mechanism: SCC
    text: Where data leaves the EEA, we rely on an adequacy decision or on standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TourScanner AI
provenance_date: '2026-11-10'
provider_name: TourScanner AI
provider_slug: tourscanner-ai
slug: tourscanner-ai-privacy-policy
source_date: '2026-11-10'
source_filename: tourscanner-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tourscanner.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TourScanner AI\naid: tourscanner-ai\nurl: https://tourscanner.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Website, accounts and API access: we are the controller of the data described below.'\ndata_categories:\n- category: contact\n  text: Traveller name, email address, phone number, party details, the activity, date and time, and any answers\n    the supplier asks for.\n- category: financial\n  text: We receive the payment status, amount, currency and a reference.\n- category: location\n  text: If you share a location, we resolve it to the nearest city and round it to about\
  \ 1 km before it is logged.\n- category: behavioral\n  text: Pages viewed, clicks, device and browser data, and session recordings and heatmaps.\n- category: communication\n  text: Messages you send to our AI agent, the tool calls it makes and its replies.\n- category: identifying\n  text: Email address and sign-in data. You can sign in with an emailed magic link or with Google.\npurposes:\n- purpose: account and API keys\n  text: Used to run your account and API keys.\n- purpose: security, rate limiting, billing\n  text: Used for security, rate limiting, debugging and billing.\n- purpose: booking management\n  text: Used to hold, confirm, amend or cancel the booking and to send vouchers.\n- purpose: AI agent replies and improvement\n  text: Used to answer you, to debug and to improve the agent.\n- purpose: site analytics\n  text: Used to understand and improve the site.\nretention:\n- scope: account data\n  period: while your account is active\n  text: 'Account data: while your account\
  \ is active, then deleted or anonymised on request or after it closes, except\n    what we must keep.'\n- scope: booking and payment records\n  period: as long as tax, accounting and dispute rules require\n  text: 'Booking and payment records: as long as tax, accounting and dispute rules require.'\n- scope: logs and AI conversations\n  period: only as long as needed for security, debugging and improvement\n  text: 'Logs and AI conversations: only as long as needed for security, debugging and improvement, then deleted\n    or aggregated.'\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where data leaves the EEA, we rely on an adequacy decision or on standard contractual clauses.\n- mechanism: SCC\n  text: Where data leaves the EEA, we rely on an adequacy decision or on standard contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to the privacy contact in section 7\n  text: Under\
  \ the GDPR and similar laws you can ask to access, correct, delete or export your data, restrict or\n    object to some processing, and withdraw consent at any time.\nrights:\n- right: access, correction, deletion, export\n  text: Under the GDPR and similar laws you can ask to access, correct, delete or export your data, restrict or\n    object to some processing, and withdraw consent at any time.\n- right: complain to authority\n  text: You can also complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not use it for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/tourscanner-ai/privacy/tourscanner-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from TourScanner AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tours
- Activities
- Booking
---
