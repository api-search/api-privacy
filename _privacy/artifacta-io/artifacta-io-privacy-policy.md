---
api_specs:
- filename: artifacta-io-openapi.json
  format: json
  label: Artifacta API
  slug: artifacta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifacta-io/openapi/artifacta-io-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address and hashed password (managed by Supabase Auth).
  - category: contact
    text: Email address, optional display name
  - category: financial
    text: Stripe customer ID, subscription status, and payment-failure timestamps.
  - category: device
    text: Standard request logs (IP address, user agent, endpoint, status code, timestamp) retained for operations and abuse prevention.
  - category: behavioral
    text: Usage telemetry. Request counts, storage consumed, download link activity, and rate-limit state
  deletion:
    route: Delete artifacts via CLI or dashboard; account-level erasure by contacting privacy@artifacta.io
    text: for account-level export or erasure, contact us at §10.
  dpa:
    available: false
    text: We do not currently offer a self-serve clickwrap DPA ; enterprise customers may request a DPA as we formalize that program.
    url: null
  purposes:
  - purpose: Run the product
    text: 'We use your data to run the product: authenticate you, verify agent signups, store and retrieve artifacts, enforce plan limits, bill subscriptions, fix bugs, and investigate abuse.'
  - purpose: No AI training
    text: We do not train AI models on your artifacts, sell your data, or share it with advertisers.
  retention:
  - period: 30 days
    scope: Deleted artifacts
    text: hard-deleted from R2 by a background job after 30 days
  - period: 7 days
    scope: Deleted accounts
    text: after 7 days, the account, artifacts, and API keys are permanently removed (subject to legal holds)
  - period: 90 days
    scope: Server logs
    text: Server logs are retained for up to 90 days for operational and security purposes unless a longer hold is required.
  rights:
  - right: access, correct, export, delete
    text: you may have rights to access, correct, export, or delete personal data, and to object to or restrict certain processing.
  role:
    text: Account, billing, and service operation. Artifacta Inc. decides how we use personal information needed to run accounts, authentication, billing, security, and support. In GDPR terms, we act as a controller for that processing (where the GDPR applies).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not “sell” or “share” personal information for cross-context behavioral advertising as defined under the CCPA/CPRA
  subprocessors:
    text: We may publish a dedicated sub-processor list page; this table should stay in sync with that list.
    url: null
  transfers:
  - mechanism: SCC
    text: we intend to rely on appropriate safeguards such as the EU Standard Contractual Clauses (and UK Addendum where applicable).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Artifacta
provenance_date: '2026-11-09'
provider_name: Artifacta
provider_slug: artifacta-io
slug: artifacta-io-privacy-policy
source_date: '2026-11-09'
source_filename: artifacta-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://artifacta.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Artifacta\naid: artifacta-io\nurl: https://artifacta.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Account, billing, and service operation. Artifacta Inc. decides how we use personal information needed to\n    run accounts, authentication, billing, security, and support. In GDPR terms, we act as a controller for that\n    processing (where the GDPR applies).\ndata_categories:\n- category: identifying\n  text: Email address and hashed password (managed by Supabase Auth).\n- category: contact\n  text: Email address, optional display name\n- category: financial\n  text: Stripe customer\
  \ ID, subscription status, and payment-failure timestamps.\n- category: device\n  text: Standard request logs (IP address, user agent, endpoint, status code, timestamp) retained for operations\n    and abuse prevention.\n- category: behavioral\n  text: Usage telemetry. Request counts, storage consumed, download link activity, and rate-limit state\npurposes:\n- purpose: Run the product\n  text: 'We use your data to run the product: authenticate you, verify agent signups, store and retrieve artifacts,\n    enforce plan limits, bill subscriptions, fix bugs, and investigate abuse.'\n- purpose: No AI training\n  text: We do not train AI models on your artifacts, sell your data, or share it with advertisers.\nretention:\n- scope: Deleted artifacts\n  period: 30 days\n  text: hard-deleted from R2 by a background job after 30 days\n- scope: Deleted accounts\n  period: 7 days\n  text: after 7 days, the account, artifacts, and API keys are permanently removed (subject to legal holds)\n- scope: Server\
  \ logs\n  period: 90 days\n  text: Server logs are retained for up to 90 days for operational and security purposes unless a longer hold is\n    required.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we intend to rely on appropriate safeguards such as the EU Standard Contractual Clauses (and UK Addendum\n    where applicable).\nsubprocessors:\n  url: null\n  text: We may publish a dedicated sub-processor list page; this table should stay in sync with that list.\ndpa:\n  available: false\n  url: null\n  text: We do not currently offer a self-serve clickwrap DPA ; enterprise customers may request a DPA as we formalize\n    that program.\ndeletion:\n  route: Delete artifacts via CLI or dashboard; account-level erasure by contacting privacy@artifacta.io\n  text: for account-level export or erasure, contact us at §10.\nrights:\n- right: access, correct, export, delete\n  text: you may have rights to access, correct, export, or delete personal data, and to object to or restrict certain\n\
  \    processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not “sell” or “share” personal information for cross-context behavioral advertising as defined under\n    the CCPA/CPRA\n"
source_yaml_url: https://artifacts.apis.io/artifacta-io/privacy/artifacta-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Artifacta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Storage
- Artifact
- MCP
- Open Source
---
