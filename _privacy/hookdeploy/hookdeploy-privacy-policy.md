---
api_specs:
- filename: hookdeploy-openapi-generated.yml
  format: yaml
  label: HookDeploy API
  slug: hookdeploy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hookdeploy/openapi/_ae-authored/hookdeploy-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, and a hashed password (handled by Supabase Auth)
  - category: financial
    text: When you subscribe to a paid plan, we collect your billing address and payment method details.
  - category: device
    text: we collect your device push token (provided by Expo's push notification service)
  - category: location
    text: pages visited, referral sources, browser type, and general geographic location
  - category: communication
    text: If you contact us for support or send us email, we retain the contents of that communication
  - category: other
    text: we store the headers, query parameters, source IP address, and request body (the "Payload") of every webhook request captured by your endpoints
  deletion:
    route: Account deletion
    text: When you delete your account, we will begin deletion of your personal data within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Billing
    text: Process billing and manage your subscription via Stripe
  - purpose: Abuse and security
    text: Detect and prevent abuse, fraud, and security incidents
  - purpose: Product improvement
    text: Improve and develop the Service (using aggregated, non-identifiable usage patterns)
  residency:
  - region: United States
    text: SnapStack is based in the United States. If you access the Service from outside the United States, your personal data will be transferred to and processed in the United States and other countries where our service providers operate
  retention:
  - period: 7 / 30 / 90 / 365 days
    scope: Webhook payload data
    text: Retained for the period specified by your plan (7 / 30 / 90 / 365 days).
  - period: null
    scope: Account and profile data
    text: Deleted within 30 days of account deletion.
  - period: typically 7 years
    scope: Billing records
    text: Retained as long as required by applicable financial and tax law (typically 7 years).
  - period: up to 3 years
    scope: Support communications
    text: Retained for up to 3 years.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate or incomplete data.'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal data ("right to be forgotten"), subject to our legal retention obligations.'
  - right: Portability
    text: 'Portability: Request a machine-readable copy of the personal data you have provided to us.'
  - right: Restriction
    text: 'Restriction: Request that we restrict processing of your data in certain circumstances.'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests.'
  - right: Withdrawal of consent
    text: 'Withdrawal of Consent: Withdraw consent where processing is based on consent'
  role:
    text: SnapStack Technologies Inc. is a Delaware corporation and the data controller for personal data collected through the Service.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: We use the following third-party service providers to operate the Service. Each is bound by data processing agreements consistent with applicable law
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as Standard Contractual Clauses (SCCs) as required under applicable data protection law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HookDeploy
provenance_date: '2026-11-09'
provider_name: HookDeploy
provider_slug: hookdeploy
slug: hookdeploy-privacy-policy
source_date: '2026-11-09'
source_filename: hookdeploy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hookdeploy.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HookDeploy\naid: hookdeploy\nurl: https://hookdeploy.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: SnapStack Technologies Inc. is a Delaware corporation and the data controller for personal data collected\n    through the Service.\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, and a hashed password (handled by Supabase Auth)\n- category: financial\n  text: When you subscribe to a paid plan, we collect your billing address and payment method details.\n- category: device\n  text: we collect your device push token (provided by Expo's push notification\
  \ service)\n- category: location\n  text: pages visited, referral sources, browser type, and general geographic location\n- category: communication\n  text: If you contact us for support or send us email, we retain the contents of that communication\n- category: other\n  text: we store the headers, query parameters, source IP address, and request body (the \"Payload\") of every webhook\n    request captured by your endpoints\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service\n- purpose: Billing\n  text: Process billing and manage your subscription via Stripe\n- purpose: Abuse and security\n  text: Detect and prevent abuse, fraud, and security incidents\n- purpose: Product improvement\n  text: Improve and develop the Service (using aggregated, non-identifiable usage patterns)\nretention:\n- scope: Webhook payload data\n  period: 7 / 30 / 90 / 365 days\n  text: Retained for the period specified by your plan (7 / 30 / 90 / 365 days).\n\
  - scope: Account and profile data\n  period: null\n  text: Deleted within 30 days of account deletion.\n- scope: Billing records\n  period: typically 7 years\n  text: Retained as long as required by applicable financial and tax law (typically 7 years).\n- scope: Support communications\n  period: up to 3 years\n  text: Retained for up to 3 years.\nresidency:\n- region: United States\n  text: SnapStack is based in the United States. If you access the Service from outside the United States, your\n    personal data will be transferred to and processed in the United States and other countries where our service\n    providers operate\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as Standard Contractual Clauses (SCCs) as required under applicable\n    data protection law.\nsubprocessors:\n  url: null\n  text: We use the following third-party service providers to operate the Service. Each is bound by data processing\n    agreements consistent with applicable law\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion\n  text: When you delete your account, we will begin deletion of your personal data within 30 days.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Rectification: Request correction of inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal data (\"right to be forgotten\"), subject to our legal retention\n    obligations.'\n- right: Portability\n  text: 'Portability: Request a machine-readable copy of the personal data you have provided to us.'\n- right: Restriction\n  text: 'Restriction: Request that we restrict processing of your data in certain circumstances.'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests.'\n- right: Withdrawal of consent\n  text: 'Withdrawal of Consent: Withdraw consent where processing is based on consent'\n\
  sale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/hookdeploy/privacy/hookdeploy-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from HookDeploy's own page on 2026-11-09.
synthetic: false
tags:
- Webhook
- PrivateInfrastructure
- Security
- Integration
- Developer Tools
---
