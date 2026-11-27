---
api_specs:
- filename: avian-openapi-generated.yml
  format: yaml
  label: Avian.io API
  slug: avian-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avian/openapi/_ae-authored/avian-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: Name, email address, and password when you create an account.'
  - category: financial
    text: 'Payment information: Billing details processed through our payment provider, Paddle. We do not directly store your credit card numbers.'
  - category: communication
    text: 'Communications: Information you provide when contacting us for support or other inquiries.'
  - category: device
    text: 'Device and log data: IP address, browser type, operating system, and referring URLs.'
  - category: behavioral
    text: 'Usage data: API request metadata such as timestamps, model selected, and token counts.'
  deletion:
    route: Request account deletion
    text: If you request account deletion, we will remove your personal data within 30 days, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate services
    text: Provide, operate, and maintain the Services.
  - purpose: Billing
    text: Process transactions and send related billing information.
  - purpose: Service monitoring and abuse prevention
    text: Monitor usage patterns and API request metadata (not content) to maintain service quality, prevent abuse, and improve performance.
  - purpose: Legal compliance
    text: Comply with legal obligations.
  residency:
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: null
    scope: Prompts and completions
    text: Zero data retention. Prompt and completion data is processed in memory and not written to persistent storage.
  - period: null
    scope: Account information
    text: We retain your account information for as long as your account is active or as needed to provide the Services.
  - period: null
    scope: API request metadata
    text: API request metadata is retained for billing and service monitoring purposes and is periodically purged in accordance with our data management practices.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correct
    text: Correct inaccurate or incomplete data.
  - right: Delete
    text: Delete your personal data.
  - right: Port
    text: Port your data to another service.
  - right: Object or restrict
    text: Object to or restrict certain processing.
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  role:
    text: Avian Data Inc. ("Avian", "we", "our", or "us") with respect to personal information we collect when you access our website at avian.io
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We use appropriate safeguards, including Standard Contractual Clauses where applicable, to ensure your data is protected in accordance with this Policy.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Avian.io
provenance_date: '2026-11-09'
provider_name: Avian.io
provider_slug: avian
slug: avian-privacy-policy
source_date: '2026-11-09'
source_filename: avian-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://avian.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Avian.io\naid: avian\nurl: https://avian.io/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Avian Data Inc. (\"Avian\", \"we\", \"our\", or \"us\") with respect to personal information we collect when you\n    access our website at avian.io\ndata_categories:\n- category: identifying\n  text: 'Account information: Name, email address, and password when you create an account.'\n- category: financial\n  text: 'Payment information: Billing details processed through our payment provider, Paddle. We do not directly\n    store your credit card numbers.'\n- category: communication\n  text:\
  \ 'Communications: Information you provide when contacting us for support or other inquiries.'\n- category: device\n  text: 'Device and log data: IP address, browser type, operating system, and referring URLs.'\n- category: behavioral\n  text: 'Usage data: API request metadata such as timestamps, model selected, and token counts.'\npurposes:\n- purpose: Provide and operate services\n  text: Provide, operate, and maintain the Services.\n- purpose: Billing\n  text: Process transactions and send related billing information.\n- purpose: Service monitoring and abuse prevention\n  text: Monitor usage patterns and API request metadata (not content) to maintain service quality, prevent abuse,\n    and improve performance.\n- purpose: Legal compliance\n  text: Comply with legal obligations.\nretention:\n- scope: Prompts and completions\n  period: null\n  text: Zero data retention. Prompt and completion data is processed in memory and not written to persistent storage.\n- scope: Account information\n\
  \  period: null\n  text: We retain your account information for as long as your account is active or as needed to provide the Services.\n- scope: API request metadata\n  period: null\n  text: API request metadata is retained for billing and service monitoring purposes and is periodically purged\n    in accordance with our data management practices.\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\ntransfers:\n- mechanism: SCC\n  text: We use appropriate safeguards, including Standard Contractual Clauses where applicable, to ensure your data\n    is protected in accordance with this Policy.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account deletion\n  text: If you request account deletion, we will remove your personal data within 30 days, except where retention\n    is required by law.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n\
  - right: Correct\n  text: Correct inaccurate or incomplete data.\n- right: Delete\n  text: Delete your personal data.\n- right: Port\n  text: Port your data to another service.\n- right: Object or restrict\n  text: Object to or restrict certain processing.\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/avian/privacy/avian-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Avian.io's own page on 2026-11-09.
synthetic: false
tags:
- Inference
- Compute
- OpenAI Compatibility
- GPU Compute
- Enterprise Security
---
