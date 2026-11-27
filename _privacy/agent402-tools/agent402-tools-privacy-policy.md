---
api_specs:
- filename: agent402-tools-api-openapi.json
  format: json
  label: 'Agent402: 500+ pay-per-call tools for AI agents over x402 + MPP Api API'
  slug: agent402-500-pay-per-call-tools-for-ai-agents-over-x402-mpp-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent402-tools/openapi/_original/agent402-tools-api-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP addresses. Used for rate limiting and in standard operational logs (request path, status code) for abuse prevention and debugging.
  - category: contact
    text: Stripe gives us the email address you entered, a customer and session id, and the payment status.
  - category: financial
    text: we keep a sales ledger of settled payments (wallet address, amount, chain, transaction id)
  - category: behavioral
    text: It records page views, page leaves (time on the page and how far you scrolled)
  - category: device
    text: your browser, user agent string, operating system, device type, screen and window size, browser language and time zone
  deletion:
    route: email request to the address below
    text: You can ask us at the address below to delete your email from our alert, follow-up and subscription records
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention and debugging
    text: for abuse prevention and debugging
  - purpose: deliver purchases
    text: We use the email to deliver what you bought
  residency:
  - region: United States
    text: The service is operated from the United States, and the data described here is processed and stored there.
  retention:
  - period: hosting platform's default log retention
    scope: operational logs
    text: Operational logs are kept for our hosting platform's default log retention.
  - period: null
    scope: memory tool data
    text: Memory-tool data persists until deleted by its owner or TTL expiry.
  - period: until you unsubscribe
    scope: free-alert email
    text: Free-alert records keep your email until you unsubscribe, when the address is removed
  - period: 14 days
    scope: backups
    text: each copy is deleted after 14 days
  rights:
  - right: access, correction, erasure, portability, objection, withdraw consent
    text: You have the right to ask for access to your data, to have it corrected or erased, to receive it in a portable form, to object to processing based on our legitimate interest, to withdraw consent
  - right: complain to supervisory authority
    text: and to complain to your supervisory authority
  role:
    text: the controller of the data described on this page is Cardhavok LLC
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell or share data with anyone for advertising, or for any purpose beyond what this list describes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent402 Tools
provenance_date: '2026-11-09'
provider_name: Agent402 Tools
provider_slug: agent402-tools
slug: agent402-tools-privacy-policy
source_date: '2026-11-09'
source_filename: agent402-tools-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agent402.tools/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent402 Tools\naid: agent402-tools\nurl: https://agent402.tools/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the controller of the data described on this page is Cardhavok LLC\ndata_categories:\n- category: identifying\n  text: IP addresses. Used for rate limiting and in standard operational logs (request path, status code) for abuse\n    prevention and debugging.\n- category: contact\n  text: Stripe gives us the email address you entered, a customer and session id, and the payment status.\n- category: financial\n  text: we keep a sales ledger of settled payments (wallet address,\
  \ amount, chain, transaction id)\n- category: behavioral\n  text: It records page views, page leaves (time on the page and how far you scrolled)\n- category: device\n  text: your browser, user agent string, operating system, device type, screen and window size, browser language\n    and time zone\npurposes:\n- purpose: abuse prevention and debugging\n  text: for abuse prevention and debugging\n- purpose: deliver purchases\n  text: We use the email to deliver what you bought\nretention:\n- scope: operational logs\n  period: hosting platform's default log retention\n  text: Operational logs are kept for our hosting platform's default log retention.\n- scope: memory tool data\n  period: null\n  text: Memory-tool data persists until deleted by its owner or TTL expiry.\n- scope: free-alert email\n  period: until you unsubscribe\n  text: Free-alert records keep your email until you unsubscribe, when the address is removed\n- scope: backups\n  period: 14 days\n  text: each copy is deleted after\
  \ 14 days\nresidency:\n- region: United States\n  text: The service is operated from the United States, and the data described here is processed and stored there.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to the address below\n  text: You can ask us at the address below to delete your email from our alert, follow-up and subscription records\nrights:\n- right: access, correction, erasure, portability, objection, withdraw consent\n  text: You have the right to ask for access to your data, to have it corrected or erased, to receive it in a portable\n    form, to object to processing based on our legitimate interest, to withdraw consent\n- right: complain to supervisory authority\n  text: and to complain to your supervisory authority\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell or share data with anyone for advertising, or for any purpose beyond what this list describes.\n"
source_yaml_url: https://artifacts.apis.io/agent402-tools/privacy/agent402-tools-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Agent402 Tools's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Tools
- Pay-per-call
- Integration
---
