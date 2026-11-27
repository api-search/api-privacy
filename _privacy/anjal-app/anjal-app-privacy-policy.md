---
api_specs:
- filename: anjal-app-addresses-api-openapi.yml
  format: yaml
  label: Anjal Addresses API
  slug: anjal-app-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-addresses-api-openapi.yml
- filename: anjal-app-cadences-api-openapi.yml
  format: yaml
  label: Anjal Cadences API
  slug: anjal-app-cadences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-cadences-api-openapi.yml
- filename: anjal-app-domains-api-openapi.yml
  format: yaml
  label: Anjal Domains API
  slug: anjal-app-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-domains-api-openapi.yml
- filename: anjal-app-drafts-api-openapi.yml
  format: yaml
  label: Anjal Drafts API
  slug: anjal-app-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-drafts-api-openapi.yml
- filename: anjal-app-inboxes-api-openapi.yml
  format: yaml
  label: Anjal Inboxes API
  slug: anjal-app-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-inboxes-api-openapi.yml
- filename: anjal-app-linkedin-outreach-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Outreach API
  slug: anjal-app-linkedin-outreach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-outreach-api-openapi.yml
- filename: anjal-app-linkedin-posts-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Posts API
  slug: anjal-app-linkedin-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-posts-api-openapi.yml
- filename: anjal-app-linkedin-searches-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Searches API
  slug: anjal-app-linkedin-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-searches-api-openapi.yml
- filename: anjal-app-linkedin-sessions-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Sessions API
  slug: anjal-app-linkedin-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-sessions-api-openapi.yml
- filename: anjal-app-linkedin-signals-api-openapi.yml
  format: yaml
  label: Anjal LinkedIn — Signals API
  slug: anjal-app-linkedin-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-linkedin-signals-api-openapi.yml
- filename: anjal-app-lists-api-openapi.yml
  format: yaml
  label: Anjal Lists API
  slug: anjal-app-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-lists-api-openapi.yml
- filename: anjal-app-messages-api-openapi.yml
  format: yaml
  label: Anjal Messages API
  slug: anjal-app-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-messages-api-openapi.yml
- filename: anjal-app-metrics-api-openapi.yml
  format: yaml
  label: Anjal Metrics API
  slug: anjal-app-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-metrics-api-openapi.yml
- filename: anjal-app-tenants-api-openapi.yml
  format: yaml
  label: Anjal Tenants API
  slug: anjal-app-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-tenants-api-openapi.yml
- filename: anjal-app-webhooks-api-openapi.yml
  format: yaml
  label: Anjal Webhooks API
  slug: anjal-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-webhooks-api-openapi.yml
- filename: anjal-app-websocket-api-openapi.yml
  format: yaml
  label: Anjal WebSocket API
  slug: anjal-app-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-websocket-api-openapi.yml
- filename: anjal-app-workspaces-api-openapi.yml
  format: yaml
  label: Anjal Workspaces API
  slug: anjal-app-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anjal-app/openapi/anjal-app-workspaces-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name, authentication tokens (via Clerk)
  - category: communication
    text: Email bodies, headers, attachments sent/received via the Service
  - category: behavioral
    text: Page views, CTA clicks, signup funnel events, first-API-call timestamp
  - category: financial
    text: Payment data Processed by Stripe — we do not store card numbers
  deletion:
    route: account deletion
    text: Upon account deletion, all email and LinkedIn data is permanently deleted within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: Provide the Service — sending and receiving emails, performing LinkedIn actions on your behalf
  - purpose: Deliverability and quotas
    text: Maintain deliverability and quotas — monitoring bounce/complaint rates, enforcing sending and action limits
  - purpose: Billing
    text: Billing — tracking usage against plan limits
  - purpose: Security
    text: Security — detecting abuse, preventing unauthorized access
  - purpose: Support
    text: Support — responding to your inquiries
  residency:
  - region: EU
    text: Data is stored in encrypted databases on infrastructure hosted in the EU (Hetzner, Germany)
  retention:
  - period: as long as your account is active
    scope: Email content
    text: Email content is retained as long as your account is active
  - period: up to 12 months
    scope: LinkedIn session metadata and action logs
    text: LinkedIn session metadata and action logs are retained for up to 12 months for abuse investigation and billing
  - period: up to 90 days
    scope: Usage logs and analytics
    text: Usage logs and analytics are retained for up to 90 days
  - period: within 30 days
    scope: Account deletion
    text: Upon account deletion, all email and LinkedIn data is permanently deleted within 30 days
  rights:
  - right: Access
    text: Access your data via the API or dashboard
  - right: Export
    text: Export your emails and data at any time
  - right: Delete
    text: Delete your account and all associated data
  - right: Correct
    text: Correct inaccurate information in your account
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your data with third parties for marketing purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anjal
provenance_date: '2026-11-09'
provider_name: Anjal
provider_slug: anjal-app
slug: anjal-app-privacy-policy
source_date: '2026-11-09'
source_filename: anjal-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anjal.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anjal\naid: anjal-app\nurl: https://anjal.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, name, authentication tokens (via Clerk)\n- category: communication\n  text: Email bodies, headers, attachments sent/received via the Service\n- category: behavioral\n  text: Page views, CTA clicks, signup funnel events, first-API-call timestamp\n- category: financial\n  text: Payment data Processed by Stripe — we do not store card numbers\npurposes:\n- purpose: Provide the Service\n  text: Provide the Service — sending and\
  \ receiving emails, performing LinkedIn actions on your behalf\n- purpose: Deliverability and quotas\n  text: Maintain deliverability and quotas — monitoring bounce/complaint rates, enforcing sending and action limits\n- purpose: Billing\n  text: Billing — tracking usage against plan limits\n- purpose: Security\n  text: Security — detecting abuse, preventing unauthorized access\n- purpose: Support\n  text: Support — responding to your inquiries\nretention:\n- scope: Email content\n  period: as long as your account is active\n  text: Email content is retained as long as your account is active\n- scope: LinkedIn session metadata and action logs\n  period: up to 12 months\n  text: LinkedIn session metadata and action logs are retained for up to 12 months for abuse investigation and billing\n- scope: Usage logs and analytics\n  period: up to 90 days\n  text: Usage logs and analytics are retained for up to 90 days\n- scope: Account deletion\n  period: within 30 days\n  text: Upon account deletion,\
  \ all email and LinkedIn data is permanently deleted within 30 days\nresidency:\n- region: EU\n  text: Data is stored in encrypted databases on infrastructure hosted in the EU (Hetzner, Germany)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion\n  text: Upon account deletion, all email and LinkedIn data is permanently deleted within 30 days\nrights:\n- right: Access\n  text: Access your data via the API or dashboard\n- right: Export\n  text: Export your emails and data at any time\n- right: Delete\n  text: Delete your account and all associated data\n- right: Correct\n  text: Correct inaccurate information in your account\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/anjal-app/privacy/anjal-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Anjal's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Artificial Intelligence
- Agents
- Software-as-a-Service
- Email API
---
