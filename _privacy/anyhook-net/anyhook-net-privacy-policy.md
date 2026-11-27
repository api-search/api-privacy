---
api_specs:
- filename: anyhook-net-anyhook-api-api-openapi.yml
  format: yaml
  label: AnyHook AnyHook API
  slug: anyhook-net-anyhook-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-anyhook-api-api-openapi.yml
- filename: anyhook-net-api-keys-api-openapi.yml
  format: yaml
  label: AnyHook Api Keys API
  slug: anyhook-net-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-api-keys-api-openapi.yml
- filename: anyhook-net-apps-api-openapi.yml
  format: yaml
  label: AnyHook Apps API
  slug: anyhook-net-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-apps-api-openapi.yml
- filename: anyhook-net-claim-api-openapi.yml
  format: yaml
  label: AnyHook Claim API
  slug: anyhook-net-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-claim-api-openapi.yml
- filename: anyhook-net-connect-api-openapi.yml
  format: yaml
  label: AnyHook Connect API
  slug: anyhook-net-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-connect-api-openapi.yml
- filename: anyhook-net-events-api-openapi.yml
  format: yaml
  label: AnyHook Events API
  slug: anyhook-net-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-events-api-openapi.yml
- filename: anyhook-net-quickstart-api-openapi.yml
  format: yaml
  label: AnyHook Quickstart API
  slug: anyhook-net-quickstart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-quickstart-api-openapi.yml
- filename: anyhook-net-usage-api-openapi.yml
  format: yaml
  label: AnyHook Usage API
  slug: anyhook-net-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anyhook-net/openapi/anyhook-net-usage-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up, we collect your name, email address, and, if you sign in via Google OAuth, your Google profile information.
  - category: financial
    text: Payment details (credit card, billing address) are collected directly by Stripe and are never stored on our servers.
  - category: communication
    text: 'we receive and store the full HTTP request: headers, body, IP address, and timestamp.'
  - category: behavioral
    text: We collect metadata about how you use the dashboard (pages visited, actions taken, error events)
  deletion:
    route: Email hello@anyhook.net, or dashboard for archived events
    text: 'Erasure : request deletion of your account and associated personal data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate account and manage subscription
    text: To authenticate your account and manage your subscription.
  - purpose: Deliver webhook events
    text: To receive, queue, deliver, and log webhook events on your behalf.
  - purpose: No ML training or ad profiles
    text: We do not use your webhook payload data to train machine learning models, build advertising profiles, or share with any party other than those necessary to deliver the service.
  residency:
  - region: global
    text: AnyHook operates globally. Your data may be processed in countries outside your own, including the United States.
  retention:
  - period: 3 days
    scope: Free webhook events
    text: on Free, deleted 3 days after we receive them.
  - period: 1 or 7 years
    scope: Pro and Scale webhook events
    text: then kept as a read-only encrypted archive (Cloudflare R2) until 1 or 7 years after receipt, then deleted.
  - period: 30 days
    scope: Account data
    text: Deleted within 30 days of a verified account deletion request.
  - period: 7 years
    scope: Billing records
    text: 'Billing records: retained for 7 years to comply with financial regulations, even after account deletion.'
  - period: indefinitely
    scope: Non-content metadata
    text: 'Non-content metadata: retained indefinitely.'
  rights:
  - right: Access
    text: 'Access : request a copy of your personal data.'
  - right: Erasure
    text: 'Erasure : request deletion of your account and associated personal data.'
  - right: Portability
    text: 'Portability : receive your data in a machine-readable format.'
  role:
    text: For webhook payloads we handle on your behalf, you are the controller and AnyHook is your processor.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: 'Opt-out of sale (CCPA) : we do not sell personal data.'
  subprocessors:
    text: We engage the following sub-processors to operate AnyHook.
    url: null
  transfers:
  - mechanism: SCC
    text: Where we transfer data from the EEA to third countries, we rely on Standard Contractual Clauses or equivalent safeguards as approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AnyHook
provenance_date: '2026-11-09'
provider_name: AnyHook
provider_slug: anyhook-net
slug: anyhook-net-privacy-policy
source_date: '2026-11-09'
source_filename: anyhook-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anyhook.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AnyHook\naid: anyhook-net\nurl: https://anyhook.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For webhook payloads we handle on your behalf, you are the controller and AnyHook is your processor.\ndata_categories:\n- category: identifying\n  text: When you sign up, we collect your name, email address, and, if you sign in via Google OAuth, your Google\n    profile information.\n- category: financial\n  text: Payment details (credit card, billing address) are collected directly by Stripe and are never stored on\n    our servers.\n- category: communication\n  text: 'we receive and store\
  \ the full HTTP request: headers, body, IP address, and timestamp.'\n- category: behavioral\n  text: We collect metadata about how you use the dashboard (pages visited, actions taken, error events)\npurposes:\n- purpose: Authenticate account and manage subscription\n  text: To authenticate your account and manage your subscription.\n- purpose: Deliver webhook events\n  text: To receive, queue, deliver, and log webhook events on your behalf.\n- purpose: No ML training or ad profiles\n  text: We do not use your webhook payload data to train machine learning models, build advertising profiles, or\n    share with any party other than those necessary to deliver the service.\nretention:\n- scope: Free webhook events\n  period: 3 days\n  text: on Free, deleted 3 days after we receive them.\n- scope: Pro and Scale webhook events\n  period: 1 or 7 years\n  text: then kept as a read-only encrypted archive (Cloudflare R2) until 1 or 7 years after receipt, then deleted.\n- scope: Account data\n  period:\
  \ 30 days\n  text: Deleted within 30 days of a verified account deletion request.\n- scope: Billing records\n  period: 7 years\n  text: 'Billing records: retained for 7 years to comply with financial regulations, even after account deletion.'\n- scope: Non-content metadata\n  period: indefinitely\n  text: 'Non-content metadata: retained indefinitely.'\nresidency:\n- region: global\n  text: AnyHook operates globally. Your data may be processed in countries outside your own, including the United\n    States.\ntransfers:\n- mechanism: SCC\n  text: Where we transfer data from the EEA to third countries, we rely on Standard Contractual Clauses or equivalent\n    safeguards as approved by the European Commission.\nsubprocessors:\n  url: null\n  text: We engage the following sub-processors to operate AnyHook.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@anyhook.net, or dashboard for archived events\n  text: 'Erasure : request deletion of your account and\
  \ associated personal data.'\nrights:\n- right: Access\n  text: 'Access : request a copy of your personal data.'\n- right: Erasure\n  text: 'Erasure : request deletion of your account and associated personal data.'\n- right: Portability\n  text: 'Portability : receive your data in a machine-readable format.'\nsale_or_sharing:\n  stance: prohibited\n  text: 'Opt-out of sale (CCPA) : we do not sell personal data.'\n"
source_yaml_url: https://artifacts.apis.io/anyhook-net/privacy/anyhook-net-privacy-policy.yml
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
summary_line: 21 quoted statements, read from AnyHook's own page on 2026-11-09.
synthetic: false
tags:
- Webhook
- Integration
- Reliability
- Developer Tools
- event-replay
---
