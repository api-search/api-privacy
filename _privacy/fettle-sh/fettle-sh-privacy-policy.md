---
api_specs:
- filename: fettle-sh-api-openapi.json
  format: json
  label: fettle.sh Api API
  slug: fettle-sh-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fettle-sh/openapi/_original/fettle-sh-api-openapi.json
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your name, email address and password'
  - category: contact
    text: 'Sign-in providers: account information received from sign-in providers you choose (Google, GitHub) — your name, email address and the provider''s account identifier.'
  - category: other
    text: 'Service data: the monitors, heartbeats and status pages you configure, check results and incident history, and the alert channels you connect.'
  - category: financial
    text: 'Billing: payments are processed by our merchant of record; we store your subscription state, never your card details.'
  - category: device
    text: 'Operational logs: request metadata such as IP address and user agent, kept briefly for security, debugging and rate limiting.'
  deletion:
    route: settings page, or email support@fettle.sh
    text: You can edit your profile and delete your account directly from the settings page, unless the account is suspended
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To run your checks and deliver alerts, to render uptime history and status pages, to maintain your subscription
  - purpose: Abuse prevention
    text: to prevent abuse of the service and of promotions
  - purpose: Transactional email
    text: to send transactional email (verification, password reset, alerts)
  retention:
  - period: 180 days
    scope: Promo code redemption IP and email domain
    text: we keep the IP address and the email domain of the redemption for 180 days
  - period: no time limit
    scope: Promo code email hash
    text: we keep a keyed hash of your email address with no time limit, also after erasure
  - period: null
    scope: Account data
    text: Account data is kept while your account is active.
  - period: currently between 7 and 365 days
    scope: Check and incident history
    text: Your plan sets how much check and incident history you can view (currently between 7 and 365 days).
  rights:
  - right: access, correct, export and erase
    text: you have the right to access, correct, export and erase your personal data
  - right: object to or restrict processing
    text: and to object to or restrict its processing
  role:
    text: The data controller for your account data is D-1 Digital Solutions Pte. Ltd.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data, and we do not use it for advertising.
  subprocessors:
    text: 'We use a small number of service providers to operate Fettle: infrastructure hosting, network and security services (including a bot check on sign-in forms), a payment processor acting as merchant of record, and an email delivery provider.'
    url: null
  transfers:
  - mechanism: other
    text: where personal data is transferred internationally, we use providers offering appropriate safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fettle-sh
provenance_date: '2026-11-09'
provider_name: fettle-sh
provider_slug: fettle-sh
slug: fettle-sh-privacy-policy
source_date: '2026-11-09'
source_filename: fettle-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fettle.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fettle-sh\naid: fettle-sh\nurl: https://fettle.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for your account data is D-1 Digital Solutions Pte. Ltd.\ndata_categories:\n- category: identifying\n  text: 'Account data: your name, email address and password'\n- category: contact\n  text: 'Sign-in providers: account information received from sign-in providers you choose (Google, GitHub) — your\n    name, email address and the provider''s account identifier.'\n- category: other\n  text: 'Service data: the monitors, heartbeats and status pages you configure, check\
  \ results and incident history,\n    and the alert channels you connect.'\n- category: financial\n  text: 'Billing: payments are processed by our merchant of record; we store your subscription state, never your\n    card details.'\n- category: device\n  text: 'Operational logs: request metadata such as IP address and user agent, kept briefly for security, debugging\n    and rate limiting.'\npurposes:\n- purpose: Service delivery\n  text: To run your checks and deliver alerts, to render uptime history and status pages, to maintain your subscription\n- purpose: Abuse prevention\n  text: to prevent abuse of the service and of promotions\n- purpose: Transactional email\n  text: to send transactional email (verification, password reset, alerts)\nretention:\n- scope: Promo code redemption IP and email domain\n  period: 180 days\n  text: we keep the IP address and the email domain of the redemption for 180 days\n- scope: Promo code email hash\n  period: no time limit\n  text: we keep a keyed\
  \ hash of your email address with no time limit, also after erasure\n- scope: Account data\n  period: null\n  text: Account data is kept while your account is active.\n- scope: Check and incident history\n  period: currently between 7 and 365 days\n  text: Your plan sets how much check and incident history you can view (currently between 7 and 365 days).\nresidency: []\ntransfers:\n- mechanism: other\n  text: where personal data is transferred internationally, we use providers offering appropriate safeguards\nsubprocessors:\n  url: null\n  text: 'We use a small number of service providers to operate Fettle: infrastructure hosting, network and security\n    services (including a bot check on sign-in forms), a payment processor acting as merchant of record, and an\n    email delivery provider.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: settings page, or email support@fettle.sh\n  text: You can edit your profile and delete your account directly from the settings\
  \ page, unless the account is\n    suspended\nrights:\n- right: access, correct, export and erase\n  text: you have the right to access, correct, export and erase your personal data\n- right: object to or restrict processing\n  text: and to object to or restrict its processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your data, and we do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/fettle-sh/privacy/fettle-sh-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from fettle-sh's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Uptime
- Developers
- AI Agents
---
