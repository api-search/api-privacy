---
api_specs:
- filename: postzen-dev-accounts-api-openapi.yml
  format: yaml
  label: postzen-dev Accounts API
  slug: postzen-dev-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-accounts-api-openapi.yml
- filename: postzen-dev-analytics-api-openapi.yml
  format: yaml
  label: postzen-dev Analytics API
  slug: postzen-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-analytics-api-openapi.yml
- filename: postzen-dev-api-keys-api-openapi.yml
  format: yaml
  label: postzen-dev API Keys API
  slug: postzen-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-api-keys-api-openapi.yml
- filename: postzen-dev-comment-automations-api-openapi.yml
  format: yaml
  label: postzen-dev Comment Automations API
  slug: postzen-dev-comment-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-comment-automations-api-openapi.yml
- filename: postzen-dev-connect-api-openapi.yml
  format: yaml
  label: postzen-dev Connect API
  slug: postzen-dev-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-connect-api-openapi.yml
- filename: postzen-dev-contacts-api-openapi.yml
  format: yaml
  label: postzen-dev Contacts API
  slug: postzen-dev-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-contacts-api-openapi.yml
- filename: postzen-dev-inbox-api-openapi.yml
  format: yaml
  label: postzen-dev Inbox API
  slug: postzen-dev-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-inbox-api-openapi.yml
- filename: postzen-dev-media-api-openapi.yml
  format: yaml
  label: postzen-dev Media API
  slug: postzen-dev-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-media-api-openapi.yml
- filename: postzen-dev-posts-api-openapi.yml
  format: yaml
  label: postzen-dev Posts API
  slug: postzen-dev-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-posts-api-openapi.yml
- filename: postzen-dev-profiles-api-openapi.yml
  format: yaml
  label: postzen-dev Profiles API
  slug: postzen-dev-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-profiles-api-openapi.yml
- filename: postzen-dev-queues-api-openapi.yml
  format: yaml
  label: postzen-dev Queues API
  slug: postzen-dev-queues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-queues-api-openapi.yml
- filename: postzen-dev-webhook-events-api-openapi.yml
  format: yaml
  label: postzen-dev Webhook Events API
  slug: postzen-dev-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-webhook-events-api-openapi.yml
- filename: postzen-dev-webhooks-api-openapi.yml
  format: yaml
  label: postzen-dev Webhooks API
  slug: postzen-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postzen-dev/openapi/postzen-dev-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information, such as your name, email address, sign-in provider, verification emails, password reset activity, and workspace profile names.
  - category: financial
    text: Billing and payment information needed to manage paid plans. Card details are processed by Stripe; we do not store full card numbers.
  - category: communication
    text: Inbox messages and contacts, when you connect a Facebook Page or Instagram professional account and use the inbox.
  - category: device
    text: Basic technical data, such as session cookies, authentication state, security logs, device/browser details, and product usage events needed to operate and secure the service.
  deletion:
    route: Email privacy@updates.postzen.dev with the subject "Data deletion request"
    text: To request deletion of your personal information, Google user data, YouTube account data, Meta Platform Data, or other connected-platform data, email privacy@updates.postzen.dev with the subject "Data deletion request"
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: To create accounts, authenticate users, secure sessions, and prevent unauthorized access.
  - purpose: Connecting and publishing to social accounts
    text: To connect social accounts, refresh tokens, validate permissions, display selectable accounts or Pages, publish or schedule content, read analytics where you authorize it, and show connection health.
  - purpose: Inbox and comment automations
    text: To show inbox conversations in your PostZen inbox, let you (or your API key or MCP client) read and reply to them, and run comment automations you set up.
  - purpose: Legal compliance
    text: To comply with legal obligations and enforce our agreements.
  residency:
  - region: Outside Alberta or Canada
    text: Because we use cloud providers and connected platforms, information may be processed outside Alberta or Canada.
  retention:
  - period: 30 days
    scope: Account and workspace data
    text: 'Account and workspace data: kept for the life of your account, then deleted or de-identified within 30 days of account deletion.'
  - period: 14 days
    scope: Raw webhook payloads from Meta
    text: 'Raw webhook payloads from Meta: kept for up to 14 days for troubleshooting, then deleted.'
  - period: 90 days
    scope: Server, security, and technical logs
    text: 'Server, security, and technical logs: retained for up to 90 days.'
  - period: 35 days
    scope: Backups
    text: 'Backups: retained on a rolling basis for up to 35 days, after which deleted data ages out.'
  - period: 7 years
    scope: Billing and tax records
    text: 'Billing and tax records: retained for up to 7 years where required by law.'
  rights:
  - right: Access, correction, deletion, portability
    text: You can request access, correction, deletion, or portability of your personal information, subject to legal limits.
  - right: Opt out of non-essential communications
    text: You can opt out of non-essential communications.
  - right: Revoke connected platform access
    text: You can revoke PostZen access from a connected social platform, including from Google account security permissions for YouTube, disconnect accounts in PostZen, remove API keys, delete supported content, delete inbox contacts in the app or through the API, and cancel scheduled posts where those controls are available.
  role:
    text: PostZen is operated by Dead Unicorn Inc., a company located in Alberta, Canada.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use it for cross-site advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: postzen-dev
provenance_date: '2026-11-10'
provider_name: postzen-dev
provider_slug: postzen-dev
slug: postzen-dev-privacy-policy
source_date: '2026-11-10'
source_filename: postzen-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.postzen.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: postzen-dev\naid: postzen-dev\nurl: https://www.postzen.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: PostZen is operated by Dead Unicorn Inc., a company located in Alberta, Canada.\ndata_categories:\n- category: identifying\n  text: Account information, such as your name, email address, sign-in provider, verification emails, password reset\n    activity, and workspace profile names.\n- category: financial\n  text: Billing and payment information needed to manage paid plans. Card details are processed by Stripe; we do\n    not store full card numbers.\n- category: communication\n\
  \  text: Inbox messages and contacts, when you connect a Facebook Page or Instagram professional account and use\n    the inbox.\n- category: device\n  text: Basic technical data, such as session cookies, authentication state, security logs, device/browser details,\n    and product usage events needed to operate and secure the service.\npurposes:\n- purpose: Account creation and security\n  text: To create accounts, authenticate users, secure sessions, and prevent unauthorized access.\n- purpose: Connecting and publishing to social accounts\n  text: To connect social accounts, refresh tokens, validate permissions, display selectable accounts or Pages,\n    publish or schedule content, read analytics where you authorize it, and show connection health.\n- purpose: Inbox and comment automations\n  text: To show inbox conversations in your PostZen inbox, let you (or your API key or MCP client) read and reply\n    to them, and run comment automations you set up.\n- purpose: Legal compliance\n\
  \  text: To comply with legal obligations and enforce our agreements.\nretention:\n- scope: Account and workspace data\n  period: 30 days\n  text: 'Account and workspace data: kept for the life of your account, then deleted or de-identified within 30\n    days of account deletion.'\n- scope: Raw webhook payloads from Meta\n  period: 14 days\n  text: 'Raw webhook payloads from Meta: kept for up to 14 days for troubleshooting, then deleted.'\n- scope: Server, security, and technical logs\n  period: 90 days\n  text: 'Server, security, and technical logs: retained for up to 90 days.'\n- scope: Backups\n  period: 35 days\n  text: 'Backups: retained on a rolling basis for up to 35 days, after which deleted data ages out.'\n- scope: Billing and tax records\n  period: 7 years\n  text: 'Billing and tax records: retained for up to 7 years where required by law.'\nresidency:\n- region: Outside Alberta or Canada\n  text: Because we use cloud providers and connected platforms, information may be processed\
  \ outside Alberta or\n    Canada.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@updates.postzen.dev with the subject \"Data deletion request\"\n  text: To request deletion of your personal information, Google user data, YouTube account data, Meta Platform\n    Data, or other connected-platform data, email privacy@updates.postzen.dev with the subject \"Data deletion request\"\nrights:\n- right: Access, correction, deletion, portability\n  text: You can request access, correction, deletion, or portability of your personal information, subject to legal\n    limits.\n- right: Opt out of non-essential communications\n  text: You can opt out of non-essential communications.\n- right: Revoke connected platform access\n  text: You can revoke PostZen access from a connected social platform, including from Google account security permissions\n    for YouTube, disconnect accounts in PostZen, remove\
  \ API keys, delete supported content, delete inbox contacts\n    in the app or through the API, and cancel scheduled posts where those controls are available.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use it for cross-site advertising.\n"
source_yaml_url: https://artifacts.apis.io/postzen-dev/privacy/postzen-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from postzen-dev's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Developer Tools
- AI Agents
- Automation
---
