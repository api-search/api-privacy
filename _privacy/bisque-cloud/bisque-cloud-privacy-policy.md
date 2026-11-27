---
api_specs:
- filename: bisque-cloud-api-openapi.json
  format: json
  label: Bisque API API
  slug: bisque-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bisque-cloud/openapi/_original/bisque-cloud-api-openapi.json
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in with Google, we receive your email address, name, and basic profile from your Google account.
  - category: financial
    text: We receive limited billing details — such as your subscription status, what you bought, and the brand and last four digits of your card — but not your full card number.
  - category: device
    text: Information such as your IP address, browser or app version, and device type.
  - category: behavioral
    text: How you interact with the Service — features used, events, and aggregate metrics — collected with Google Analytics and stored in BigQuery.
  - category: communication
    text: the Artifacts you or your agent publish
  deletion:
    route: Account-deletion option in the app or email to hello@bisque.today; verified requests actioned within 30 days
    text: To delete your account and content, use the account-deletion option in the app or email hello@bisque.today ; we action verified requests within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service, including generating and storing your presentations
  - purpose: Process subscriptions and purchases
    text: Process your subscription and purchases, calculate and remit sales tax, and pay sellers
  - purpose: Improve the product
    text: Understand how the Service is used and improve the product
  - purpose: Security and fraud prevention
    text: Detect, prevent, and address security issues, abuse, and fraud
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: United States and other countries
    text: We operate on Google Cloud infrastructure and may process and store information in the United States and other countries whose data-protection laws differ from those where you live.
  retention:
  - period: null
    scope: Account and content
    text: We keep your account and content for as long as your account is active or as needed to provide the Service.
  - period: 90 days
    scope: Presentations and inputs after deletion
    text: After deletion, your presentations and inputs are removed from our active systems and purged from backups within 90 days.
  rights:
  - right: Access, correct, delete, export, object or restrict
    text: you may have the right to access, correct, delete, export, or object to or restrict our processing of your personal information
  - right: Lodge a complaint
    text: and to lodge a complaint with your local data-protection authority
  - right: Opt out of non-essential emails
    text: You can also opt out of non-essential emails at any time.
  role:
    text: The data controller is Bisque ( hello@bisque.today ).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses (and the UK Addendum)
  - mechanism: DPF
    text: our providers’ certification under the EU-U.S. Data Privacy Framework where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bisque
provenance_date: '2026-11-09'
provider_name: Bisque
provider_slug: bisque-cloud
slug: bisque-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: bisque-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bisque.today/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bisque\naid: bisque-cloud\nurl: https://bisque.today/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Bisque ( hello@bisque.today ).\ndata_categories:\n- category: identifying\n  text: When you sign in with Google, we receive your email address, name, and basic profile from your Google account.\n- category: financial\n  text: We receive limited billing details — such as your subscription status, what you bought, and the brand and\n    last four digits of your card — but not your full card number.\n- category: device\n  text: Information such as your IP address,\
  \ browser or app version, and device type.\n- category: behavioral\n  text: How you interact with the Service — features used, events, and aggregate metrics — collected with Google\n    Analytics and stored in BigQuery.\n- category: communication\n  text: the Artifacts you or your agent publish\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service, including generating and storing your presentations\n- purpose: Process subscriptions and purchases\n  text: Process your subscription and purchases, calculate and remit sales tax, and pay sellers\n- purpose: Improve the product\n  text: Understand how the Service is used and improve the product\n- purpose: Security and fraud prevention\n  text: Detect, prevent, and address security issues, abuse, and fraud\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account and content\n  period: null\n  text: We keep your account and content for as long as your\
  \ account is active or as needed to provide the Service.\n- scope: Presentations and inputs after deletion\n  period: 90 days\n  text: After deletion, your presentations and inputs are removed from our active systems and purged from backups\n    within 90 days.\nresidency:\n- region: United States and other countries\n  text: We operate on Google Cloud infrastructure and may process and store information in the United States and\n    other countries whose data-protection laws differ from those where you live.\ntransfers:\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses (and the UK Addendum)\n- mechanism: DPF\n  text: our providers’ certification under the EU-U.S. Data Privacy Framework where applicable\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account-deletion option in the app or email to hello@bisque.today; verified requests actioned within 30\n    days\n  text: To delete your account\
  \ and content, use the account-deletion option in the app or email hello@bisque.today\n    ; we action verified requests within 30 days.\nrights:\n- right: Access, correct, delete, export, object or restrict\n  text: you may have the right to access, correct, delete, export, or object to or restrict our processing of your\n    personal information\n- right: Lodge a complaint\n  text: and to lodge a complaint with your local data-protection authority\n- right: Opt out of non-essential emails\n  text: You can also opt out of non-essential emails at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/bisque-cloud/privacy/bisque-cloud-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Bisque's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Code Presentation
---
