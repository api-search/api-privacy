---
api_specs:
- filename: curviate-com-openapi.json
  format: json
  label: Curviate API
  slug: curviate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curviate-com/openapi/curviate-com-openapi.json
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account identity (name, email, sign-in method)
  - category: contact
    text: personal contact details from profiles, such as email addresses and phone numbers
  - category: financial
    text: Billing details
  - category: behavioral
    text: Website analytics, only if you opt in
  - category: device
    text: Usage and security logs
  - category: communication
    text: Chats and messages from your connected accounts' personal LinkedIn inboxes
  deletion:
    route: Self-service deletion in dashboard Settings, or email privacy@curviate.com
    text: You can delete your account yourself, from Settings in your dashboard . It takes effect immediately and it cannot be undone.
  dpa:
    available: true
    text: A data processing agreement under Article 28 of the GDPR is available to business customers on request.
    url: null
  purposes:
  - purpose: Operate requested actions
    text: Operate the actions you request
  - purpose: Billing and tax
    text: Charge you correctly and meet our tax obligations
  - purpose: Service reliability and security
    text: Keep the service reliable and abuse-free
  - purpose: Campaign measurement
    text: so we can measure which campaigns bring in customers
  residency:
  - region: EU
    text: Our infrastructure runs in the EU.
  - region: EU
    text: All customer LinkedIn data, account data, and telemetry are processed and stored exclusively in EU regions of our sub-processors.
  retention:
  - period: While your account is active
    scope: Account and workspace data
    text: Account and workspace data While your account is active
  - period: As required by German tax law, currently up to 10 years
    scope: Billing records
    text: Billing records As required by German tax law, currently up to 10 years
  - period: A short operational window
    scope: Logs
    text: Logs A short operational window; metadata only, never message content
  - period: 90 days
    scope: Security log
    text: A security log of which requests were made, kept for 90 days and then removed automatically.
  rights:
  - right: Access, correction, deletion, restriction, objection, portability
    text: You can access, correct, delete, restrict, or object to your data, port it elsewhere, and withdraw consent at any time
  - right: Complaint to supervisory authority
    text: You can also complain to a supervisory authority
  - right: No automated decisions
    text: We don't make automated decisions about you that have a legal or similarly significant effect.
  role:
    text: For that data, we are the controller . When you use Curviate to act on your own connected LinkedIn account, viewing profiles, sending messages, managing engagement, that content and those contacts belong to that account and its people. You are the controller of that data; we are the processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data or use it to train models.
  subprocessors:
    text: 'We give the current, named list of every provider above to any customer who asks: security@curviate.com .'
    url: null
  transfers:
  - mechanism: SCC
    text: typically the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: curviate-com
provenance_date: '2026-11-09'
provider_name: curviate-com
provider_slug: curviate-com
slug: curviate-com-privacy-policy
source_date: '2026-11-09'
source_filename: curviate-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://curviate.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: curviate-com\naid: curviate-com\nurl: https://curviate.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For that data, we are the controller . When you use Curviate to act on your own connected LinkedIn account,\n    viewing profiles, sending messages, managing engagement, that content and those contacts belong to that account\n    and its people. You are the controller of that data; we are the processor\ndata_categories:\n- category: identifying\n  text: Account identity (name, email, sign-in method)\n- category: contact\n  text: personal contact details from profiles, such as email addresses\
  \ and phone numbers\n- category: financial\n  text: Billing details\n- category: behavioral\n  text: Website analytics, only if you opt in\n- category: device\n  text: Usage and security logs\n- category: communication\n  text: Chats and messages from your connected accounts' personal LinkedIn inboxes\npurposes:\n- purpose: Operate requested actions\n  text: Operate the actions you request\n- purpose: Billing and tax\n  text: Charge you correctly and meet our tax obligations\n- purpose: Service reliability and security\n  text: Keep the service reliable and abuse-free\n- purpose: Campaign measurement\n  text: so we can measure which campaigns bring in customers\nretention:\n- scope: Account and workspace data\n  period: While your account is active\n  text: Account and workspace data While your account is active\n- scope: Billing records\n  period: As required by German tax law, currently up to 10 years\n  text: Billing records As required by German tax law, currently up to 10 years\n\
  - scope: Logs\n  period: A short operational window\n  text: Logs A short operational window; metadata only, never message content\n- scope: Security log\n  period: 90 days\n  text: A security log of which requests were made, kept for 90 days and then removed automatically.\nresidency:\n- region: EU\n  text: Our infrastructure runs in the EU.\n- region: EU\n  text: All customer LinkedIn data, account data, and telemetry are processed and stored exclusively in EU regions\n    of our sub-processors.\ntransfers:\n- mechanism: SCC\n  text: typically the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: 'We give the current, named list of every provider above to any customer who asks: security@curviate.com\n    .'\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement under Article 28 of the GDPR is available to business customers on request.\ndeletion:\n  route: Self-service deletion in dashboard Settings, or email privacy@curviate.com\n  text: You can\
  \ delete your account yourself, from Settings in your dashboard . It takes effect immediately and\n    it cannot be undone.\nrights:\n- right: Access, correction, deletion, restriction, objection, portability\n  text: You can access, correct, delete, restrict, or object to your data, port it elsewhere, and withdraw consent\n    at any time\n- right: Complaint to supervisory authority\n  text: You can also complain to a supervisory authority\n- right: No automated decisions\n  text: We don't make automated decisions about you that have a legal or similarly significant effect.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data or use it to train models.\n"
source_yaml_url: https://artifacts.apis.io/curviate-com/privacy/curviate-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from curviate-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LinkedIn
- Automation
- Agents
---
