---
api_specs:
- filename: meal-planner-online.openapi.json
  format: json
  label: Meal Planner Read-only API
  slug: meal-planner-read-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meal-planner-online/openapi/meal-planner-online.openapi.json
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details such as name, email address, login credentials, and subscription status.
  - category: contact
    text: delivery email addresses
  - category: financial
    text: Payment identifiers from Stripe, such as customer and subscription IDs, but not full card details.
  - category: behavioral
    text: Recipient addresses, message content, delivery/bounce events and operational message identifiers.
  - category: device
    text: Hosting logs can include IP address, browser information, request time and referrer.
  - category: health
    text: Do not enter medical diagnoses, medication instructions, detailed health history, or other sensitive information that is not needed for dinner planning.
  deletion:
    route: Account deletion in the Recipe Book / account settings, plus support contact for queued cleanup confirmation
    text: Account deletion removes your active account, saved recipes and drafts, family preferences, household delivery settings and sharing links, private plans and API/MCP connections.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and meal planning
    text: Create and manage accounts. Generate weekly dinner plans, recipes, and grocery lists.
  - purpose: Email delivery
    text: Deliver account emails, weekly meal plan emails, support replies, and subscribed newsletter messages.
  - purpose: Billing
    text: Process subscription status and billing access through Stripe.
  - purpose: Security
    text: Maintain site security, troubleshoot errors, and prevent misuse.
  residency:
  - region: United States
    text: DreamHost Website/database hosting and support mailbox; US hosting.
  - region: Outside Québec and Canada
    text: Processing may occur outside Québec and Canada.
  retention:
  - period: null
    scope: Recipe Book content
    text: The Book retains the transcription, source evidence and capture details, and the recipe text you confirm until you delete the recipe or account.
  - period: null
    scope: Uploaded original files
    text: Normal processing deletes them when the request finishes.
  - period: six years
    scope: Billing and refund transaction records
    text: Minimal billing and refund transaction records legally required for accounting may remain for six years from the end of the relevant tax year, or longer where a legal dispute requires it.
  - period: 30 days
    scope: App-managed database and upload backups
    text: App-managed database and upload backups expire within 30 days.
  - period: 30 days
    scope: Anthropic API inputs and outputs
    text: Anthropic normally deletes API inputs and outputs within 30 days, with exceptions for legal obligations, usage-policy enforcement or other applicable retention arrangements.
  - period: 30 days
    scope: Resolved support requests
    text: resolved requests become eligible for permanent removal after 30 days by scheduled daily cleanup.
  rights:
  - right: access
    text: You can ask to access or correct personal information, obtain a copy or a portable format where applicable, withdraw consent for optional uses, request deletion, or raise a privacy complaint.
  - right: withdraw optional consent
    text: withdraw consent for optional uses
  - right: complaint
    text: You can contact the Commission d’accès à l’information du Québec or another competent privacy authority if your concern remains unresolved.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell household profile information, place third-party ads inside subscriber plans or the Recipe Book, or use that content for cross-company advertising tracking.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We do not claim that using a named provider establishes a certification or guarantees Canadian-only storage.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: meal-planner-online
provenance_date: '2026-11-10'
provider_name: meal-planner-online
provider_slug: meal-planner-online
slug: meal-planner-online-privacy-policy
source_date: '2026-11-10'
source_filename: meal-planner-online-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.meal-planner.online/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: meal-planner-online\naid: meal-planner-online\nurl: https://www.meal-planner.online/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account details such as name, email address, login credentials, and subscription status.\n- category: contact\n  text: delivery email addresses\n- category: financial\n  text: Payment identifiers from Stripe, such as customer and subscription IDs, but not full card details.\n- category: behavioral\n  text: Recipient addresses, message content, delivery/bounce events and operational message identifiers.\n\
  - category: device\n  text: Hosting logs can include IP address, browser information, request time and referrer.\n- category: health\n  text: Do not enter medical diagnoses, medication instructions, detailed health history, or other sensitive information\n    that is not needed for dinner planning.\npurposes:\n- purpose: Account and meal planning\n  text: Create and manage accounts. Generate weekly dinner plans, recipes, and grocery lists.\n- purpose: Email delivery\n  text: Deliver account emails, weekly meal plan emails, support replies, and subscribed newsletter messages.\n- purpose: Billing\n  text: Process subscription status and billing access through Stripe.\n- purpose: Security\n  text: Maintain site security, troubleshoot errors, and prevent misuse.\nretention:\n- scope: Recipe Book content\n  period: null\n  text: The Book retains the transcription, source evidence and capture details, and the recipe text you confirm\n    until you delete the recipe or account.\n- scope: Uploaded\
  \ original files\n  period: null\n  text: Normal processing deletes them when the request finishes.\n- scope: Billing and refund transaction records\n  period: six years\n  text: Minimal billing and refund transaction records legally required for accounting may remain for six years\n    from the end of the relevant tax year, or longer where a legal dispute requires it.\n- scope: App-managed database and upload backups\n  period: 30 days\n  text: App-managed database and upload backups expire within 30 days.\n- scope: Anthropic API inputs and outputs\n  period: 30 days\n  text: Anthropic normally deletes API inputs and outputs within 30 days, with exceptions for legal obligations,\n    usage-policy enforcement or other applicable retention arrangements.\n- scope: Resolved support requests\n  period: 30 days\n  text: resolved requests become eligible for permanent removal after 30 days by scheduled daily cleanup.\nresidency:\n- region: United States\n  text: DreamHost Website/database hosting\
  \ and support mailbox; US hosting.\n- region: Outside Québec and Canada\n  text: Processing may occur outside Québec and Canada.\ntransfers:\n- mechanism: other\n  text: We do not claim that using a named provider establishes a certification or guarantees Canadian-only storage.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in the Recipe Book / account settings, plus support contact for queued cleanup confirmation\n  text: Account deletion removes your active account, saved recipes and drafts, family preferences, household delivery\n    settings and sharing links, private plans and API/MCP connections.\nrights:\n- right: access\n  text: You can ask to access or correct personal information, obtain a copy or a portable format where applicable,\n    withdraw consent for optional uses, request deletion, or raise a privacy complaint.\n- right: withdraw optional consent\n  text: withdraw consent for optional\
  \ uses\n- right: complaint\n  text: You can contact the Commission d’accès à l’information du Québec or another competent privacy authority\n    if your concern remains unresolved.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell household profile information, place third-party ads inside subscriber plans or the Recipe\n    Book, or use that content for cross-company advertising tracking.\n"
source_yaml_url: https://artifacts.apis.io/meal-planner-online/privacy/meal-planner-online-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from meal-planner-online's own page on 2026-11-10.
synthetic: false
tags:
- Meal Planning
- Family
- Canada
- Subscription
- Cooking
---
