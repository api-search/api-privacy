---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile information, including your name, email address, profile image, plan, account status, and preferences.
  - category: financial
    text: Billing and subscription records, including provider customer, subscription, order, transaction, and invoice identifiers
  - category: communication
    text: Support communications and attachments that you choose to send us.
  - category: device
    text: Operational data, including feature usage counts, request timestamps, IP address and server logs, browser or device information, error diagnostics, and security events
  - category: behavioral
    text: Website analytics and cookie information, where enabled, as described in the Cookies section below.
  deletion:
    route: Account deletion request or in-app deletion of supported records
    text: You can delete supported records or request account deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate and synchronize account
    text: Authenticate you and synchronize your account, plan, settings, usage limits, and entitlements across PrompTessor products.
  - purpose: Provide requested prompt features
    text: Provide user-requested prompt generation, analysis, optimization, refinement, reverse prompting, direct insertion, history, and Prompt Library features.
  - purpose: Billing and subscriptions
    text: Create checkouts and authenticated Polar Customer Portal sessions using an external customer identifier
  - purpose: Security and abuse prevention
    text: Measure feature reliability and aggregate usage, enforce usage limits, troubleshoot errors, secure accounts, and prevent fraud or abuse.
  retention:
  - period: null
    scope: Account and workflow records
    text: Account, prompt, workflow history, library, and attachment records are retained while your account or the related record remains active so you can reopen, version, save, and reuse them.
  - period: 90 days
    scope: Developer API operation records
    text: API and MCP operation records are retained for 90 days
  - period: 30 days
    scope: Webhook delivery payloads and logs
    text: webhook delivery payloads and logs are retained for 30 days
  - period: 24 hours
    scope: Unconsumed temporary uploads
    text: Unconsumed temporary uploads are retained for up to 24 hours
  - period: 365 days
    scope: Sponsor visitor cookie
    text: The first-party HttpOnly cookie sponsor_visitor contains a random identifier for up to 365 days.
  rights:
  - right: Access and copy
    text: Access, correct, or obtain a copy of your personal information.
  - right: Deletion
    text: Delete supported prompt and workflow records or request deletion of your account and associated data.
  - right: Opt out of marketing
    text: Opt out of marketing communications while continuing to receive necessary service and security messages.
  - right: Object or restrict
    text: Object to or restrict certain processing and request data portability where applicable.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: PrompTessor and its service providers may process data in countries other than your own. Where required, we use appropriate safeguards for international transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PrompTessor
provenance_date: '2026-11-10'
provider_name: PrompTessor
provider_slug: promptessor
slug: promptessor-privacy-policy
source_date: '2026-11-10'
source_filename: promptessor-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://promptessor.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PrompTessor\naid: promptessor\nurl: https://promptessor.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and profile information, including your name, email address, profile image, plan, account status,\n    and preferences.\n- category: financial\n  text: Billing and subscription records, including provider customer, subscription, order, transaction, and invoice\n    identifiers\n- category: communication\n  text: Support communications and attachments that you choose to send us.\n- category: device\n  text: Operational\
  \ data, including feature usage counts, request timestamps, IP address and server logs, browser\n    or device information, error diagnostics, and security events\n- category: behavioral\n  text: Website analytics and cookie information, where enabled, as described in the Cookies section below.\npurposes:\n- purpose: Authenticate and synchronize account\n  text: Authenticate you and synchronize your account, plan, settings, usage limits, and entitlements across PrompTessor\n    products.\n- purpose: Provide requested prompt features\n  text: Provide user-requested prompt generation, analysis, optimization, refinement, reverse prompting, direct\n    insertion, history, and Prompt Library features.\n- purpose: Billing and subscriptions\n  text: Create checkouts and authenticated Polar Customer Portal sessions using an external customer identifier\n- purpose: Security and abuse prevention\n  text: Measure feature reliability and aggregate usage, enforce usage limits, troubleshoot errors,\
  \ secure accounts,\n    and prevent fraud or abuse.\nretention:\n- scope: Account and workflow records\n  period: null\n  text: Account, prompt, workflow history, library, and attachment records are retained while your account or the\n    related record remains active so you can reopen, version, save, and reuse them.\n- scope: Developer API operation records\n  period: 90 days\n  text: API and MCP operation records are retained for 90 days\n- scope: Webhook delivery payloads and logs\n  period: 30 days\n  text: webhook delivery payloads and logs are retained for 30 days\n- scope: Unconsumed temporary uploads\n  period: 24 hours\n  text: Unconsumed temporary uploads are retained for up to 24 hours\n- scope: Sponsor visitor cookie\n  period: 365 days\n  text: The first-party HttpOnly cookie sponsor_visitor contains a random identifier for up to 365 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: PrompTessor and its service providers may process data in countries other than\
  \ your own. Where required,\n    we use appropriate safeguards for international transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion request or in-app deletion of supported records\n  text: You can delete supported records or request account deletion.\nrights:\n- right: Access and copy\n  text: Access, correct, or obtain a copy of your personal information.\n- right: Deletion\n  text: Delete supported prompt and workflow records or request deletion of your account and associated data.\n- right: Opt out of marketing\n  text: Opt out of marketing communications while continuing to receive necessary service and security messages.\n- right: Object or restrict\n  text: Object to or restrict certain processing and request data portability where applicable.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/promptessor/privacy/promptessor-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from PrompTessor's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Prompt Engineering
- Platform
- Documentation
- Community
---
