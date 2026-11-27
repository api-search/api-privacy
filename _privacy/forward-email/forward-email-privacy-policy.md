---
api_specs:
- filename: forward-email-account-api-openapi.yml
  format: yaml
  label: Forward Email Account API
  slug: forward-email-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-account-api-openapi.yml
- filename: forward-email-aliases-api-openapi.yml
  format: yaml
  label: Forward Email Aliases API
  slug: forward-email-aliases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-aliases-api-openapi.yml
- filename: forward-email-calendar-events-api-openapi.yml
  format: yaml
  label: Forward Email Calendar Events API
  slug: forward-email-calendar-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-calendar-events-api-openapi.yml
- filename: forward-email-calendars-api-openapi.yml
  format: yaml
  label: Forward Email Calendars API
  slug: forward-email-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-calendars-api-openapi.yml
- filename: forward-email-contacts-api-openapi.yml
  format: yaml
  label: Forward Email Contacts API
  slug: forward-email-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-contacts-api-openapi.yml
- filename: forward-email-domains-api-openapi.yml
  format: yaml
  label: Forward Email Domains API
  slug: forward-email-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-domains-api-openapi.yml
- filename: forward-email-emails-api-openapi.yml
  format: yaml
  label: Forward Email Emails API
  slug: forward-email-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-emails-api-openapi.yml
- filename: forward-email-encrypt-api-openapi.yml
  format: yaml
  label: Forward Email Encrypt API
  slug: forward-email-encrypt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-encrypt-api-openapi.yml
- filename: forward-email-folders-api-openapi.yml
  format: yaml
  label: Forward Email Folders API
  slug: forward-email-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-folders-api-openapi.yml
- filename: forward-email-invites-api-openapi.yml
  format: yaml
  label: Forward Email Invites API
  slug: forward-email-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-invites-api-openapi.yml
- filename: forward-email-logs-api-openapi.yml
  format: yaml
  label: Forward Email Logs API
  slug: forward-email-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-logs-api-openapi.yml
- filename: forward-email-members-api-openapi.yml
  format: yaml
  label: Forward Email Members API
  slug: forward-email-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-members-api-openapi.yml
- filename: forward-email-messages-api-openapi.yml
  format: yaml
  label: Forward Email Messages API
  slug: forward-email-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-messages-api-openapi.yml
- filename: forward-email-push-tokens-api-openapi.yml
  format: yaml
  label: Forward Email Push Tokens API
  slug: forward-email-push-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-push-tokens-api-openapi.yml
- filename: forward-email-sieve-scripts-api-openapi.yml
  format: yaml
  label: Forward Email Sieve Scripts API
  slug: forward-email-sieve-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-sieve-scripts-api-openapi.yml
- filename: forward-email-websockets-api-openapi.yml
  format: yaml
  label: Forward Email WebSockets API
  slug: forward-email-websockets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forward-email/openapi/forward-email-websockets-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: We store your email address that you provide us with.
  - category: identifying
    text: We store your domain names, aliases, and configurations that you provide us with.
  - category: device
    text: Browser and operating system type and version (parsed from user agent, raw data discarded)
  - category: location
    text: the IP address of the client that sent it (over SMTP or the API)
  - category: communication
    text: We store outbound SMTP emails for ~30 days.
  deletion:
    route: My Account > Security and click "Delete Account"
    text: go to My Account > Security and click "Delete Account".
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: functionality and service improvement
    text: Strictly for functionality and to improve our service, we collect and store securely the following information
  - purpose: abuse prevention
    text: We use these logs to find and fix problems and to stop abuse, and we keep them for up to 30 days.
  - purpose: analytics
    text: We use our own privacy-focused analytics system to understand how our services are used.
  retention:
  - period: 7 days
    scope: Error logs
    text: We store 4xx and 5xx SMTP response code error logs for 7 days.
  - period: up to 30 days
    scope: Server logs
    text: we keep them for up to 30 days.
  - period: ~30 days
    scope: Outbound SMTP emails
    text: We store outbound SMTP emails for ~30 days.
  - period: 30 days
    scope: Analytics events
    text: Analytics events are automatically deleted after 30 days
  - period: up to one year
    scope: Push tokens
    text: We keep a push token for up to one year after its last use.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Forward Email
provenance_date: '2026-11-09'
provider_name: Forward Email
provider_slug: forward-email
slug: forward-email-privacy-policy
source_date: '2026-11-09'
source_filename: forward-email-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://forwardemail.net/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Forward Email\naid: forward-email\nurl: https://forwardemail.net/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We store your email address that you provide us with.\n- category: identifying\n  text: We store your domain names, aliases, and configurations that you provide us with.\n- category: device\n  text: Browser and operating system type and version (parsed from user agent, raw data discarded)\n- category: location\n  text: the IP address of the client that sent it (over SMTP or the API)\n- category: communication\n  text:\
  \ We store outbound SMTP emails for ~30 days.\npurposes:\n- purpose: functionality and service improvement\n  text: Strictly for functionality and to improve our service, we collect and store securely the following information\n- purpose: abuse prevention\n  text: We use these logs to find and fix problems and to stop abuse, and we keep them for up to 30 days.\n- purpose: analytics\n  text: We use our own privacy-focused analytics system to understand how our services are used.\nretention:\n- scope: Error logs\n  period: 7 days\n  text: We store 4xx and 5xx SMTP response code error logs for 7 days.\n- scope: Server logs\n  period: up to 30 days\n  text: we keep them for up to 30 days.\n- scope: Outbound SMTP emails\n  period: ~30 days\n  text: We store outbound SMTP emails for ~30 days.\n- scope: Analytics events\n  period: 30 days\n  text: Analytics events are automatically deleted after 30 days\n- scope: Push tokens\n  period: up to one year\n  text: We keep a push token for up to one\
  \ year after its last use.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: My Account > Security and click \"Delete Account\"\n  text: go to My Account > Security and click \"Delete Account\".\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/forward-email/privacy/forward-email-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 14 quoted statements, read from Forward Email's own page on 2026-11-09.
synthetic: false
tags:
- Email Forwarding
- Email Hosting
- Open Source
- Secure Email
---
