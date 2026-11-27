---
api_specs:
- filename: crawlora-net-openapi-generated.yml
  format: yaml
  label: crawlora-net API
  slug: crawlora-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlora-net/openapi/_ae-authored/crawlora-net-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, username, organization name, account ID, and the profile your Google or GitHub account shares when you sign in with it.
  - category: financial
    text: Plan, subscription status, invoice status, billing email, Stripe or payment provider customer ID, tax metadata, failed payment status.
  - category: location
    text: approximate location from IP
  - category: device
    text: IP address, browser type, device info, session cookie, security events, referrer, approximate location from IP.
  - category: behavioral
    text: page views, traffic source, docs and Playground interactions, and recorded browsing sessions (clicks, scrolling, and page interactions, with on-page text and form inputs masked).
  - category: communication
    text: Messages, screenshots, attachments, logs shared by user, support ticket content.
  deletion:
    route: Account settings in the console; or written request to privacy mailbox
    text: You can ask for your account to be deleted from Account settings in the console.
  dpa:
    available: true
    text: If your organization needs a data processing agreement, request one from the Legal mailbox below.
    url: null
  purposes:
  - purpose: Account creation and service delivery
    text: Account creation and service delivery Legal basis Contract necessity.
  - purpose: Security and abuse prevention
    text: Apply rate limits, detect abuse, prevent fraud, and protect infrastructure.
  - purpose: Billing and invoices
    text: Process billing, subscriptions, invoices, payment status, and tax metadata.
  - purpose: Product analytics
    text: Product analytics and session replay (Google Analytics, Microsoft Clarity) Legal basis Consent, given through the cookie prompt.
  - purpose: Marketing emails
    text: Marketing emails Legal basis Consent or legitimate interests depending on jurisdiction.
  retention:
  - period: 14 days
    scope: Raw request logs
    text: Raw request logs are deleted after 14 days.
  - period: Retained while the account is active and for a reasonable period afterward where needed.
    scope: Account data
    text: Retained while the account is active and for a reasonable period afterward where needed.
  - period: Retained as required for tax, accounting, audit, and legal obligations.
    scope: Billing records
    text: Retained as required for tax, accounting, audit, and legal obligations.
  - period: Retained until overwritten or deleted through normal backup rotation.
    scope: Backups
    text: Retained until overwritten or deleted through normal backup rotation.
  rights:
  - right: access
    text: you may have rights to access data, correct data, delete data, export or receive a copy of data, object to processing, restrict processing, withdraw consent
  - right: opt out of sale, sharing, or targeted advertising
    text: opt out of sale, sharing, or targeted advertising where applicable
  - right: complaint
    text: lodge a complaint with a privacy authority
  role:
    text: For certain Customer Data processed on behalf of a business customer through the API, Crawlora may act as a processor or service provider
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information for money.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where required, Crawlora uses appropriate safeguards for international transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crawlora-net
provenance_date: '2026-11-09'
provider_name: crawlora-net
provider_slug: crawlora-net
slug: crawlora-net-privacy-policy
source_date: '2026-11-09'
source_filename: crawlora-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crawlora.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crawlora-net\naid: crawlora-net\nurl: https://crawlora.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For certain Customer Data processed on behalf of a business customer through the API, Crawlora may act as\n    a processor or service provider\ndata_categories:\n- category: identifying\n  text: Name, email, username, organization name, account ID, and the profile your Google or GitHub account shares\n    when you sign in with it.\n- category: financial\n  text: Plan, subscription status, invoice status, billing email, Stripe or payment provider customer ID, tax metadata,\n    failed\
  \ payment status.\n- category: location\n  text: approximate location from IP\n- category: device\n  text: IP address, browser type, device info, session cookie, security events, referrer, approximate location from\n    IP.\n- category: behavioral\n  text: page views, traffic source, docs and Playground interactions, and recorded browsing sessions (clicks, scrolling,\n    and page interactions, with on-page text and form inputs masked).\n- category: communication\n  text: Messages, screenshots, attachments, logs shared by user, support ticket content.\npurposes:\n- purpose: Account creation and service delivery\n  text: Account creation and service delivery Legal basis Contract necessity.\n- purpose: Security and abuse prevention\n  text: Apply rate limits, detect abuse, prevent fraud, and protect infrastructure.\n- purpose: Billing and invoices\n  text: Process billing, subscriptions, invoices, payment status, and tax metadata.\n- purpose: Product analytics\n  text: Product analytics\
  \ and session replay (Google Analytics, Microsoft Clarity) Legal basis Consent, given through\n    the cookie prompt.\n- purpose: Marketing emails\n  text: Marketing emails Legal basis Consent or legitimate interests depending on jurisdiction.\nretention:\n- scope: Raw request logs\n  period: 14 days\n  text: Raw request logs are deleted after 14 days.\n- scope: Account data\n  period: Retained while the account is active and for a reasonable period afterward where needed.\n  text: Retained while the account is active and for a reasonable period afterward where needed.\n- scope: Billing records\n  period: Retained as required for tax, accounting, audit, and legal obligations.\n  text: Retained as required for tax, accounting, audit, and legal obligations.\n- scope: Backups\n  period: Retained until overwritten or deleted through normal backup rotation.\n  text: Retained until overwritten or deleted through normal backup rotation.\nresidency: []\ntransfers:\n- mechanism: other\n  text:\
  \ Where required, Crawlora uses appropriate safeguards for international transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: If your organization needs a data processing agreement, request one from the Legal mailbox below.\ndeletion:\n  route: Account settings in the console; or written request to privacy mailbox\n  text: You can ask for your account to be deleted from Account settings in the console.\nrights:\n- right: access\n  text: you may have rights to access data, correct data, delete data, export or receive a copy of data, object\n    to processing, restrict processing, withdraw consent\n- right: opt out of sale, sharing, or targeted advertising\n  text: opt out of sale, sharing, or targeted advertising where applicable\n- right: complaint\n  text: lodge a complaint with a privacy authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information for money.\n"
source_yaml_url: https://artifacts.apis.io/crawlora-net/privacy/crawlora-net-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from crawlora-net's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Scraping
- Artificial Intelligence
- Data
- MCP
---
