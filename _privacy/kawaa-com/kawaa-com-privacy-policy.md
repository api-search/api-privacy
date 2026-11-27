---
api_specs:
- filename: kawaa-com-account-api-openapi.yml
  format: yaml
  label: kawaa-com Account API
  slug: kawaa-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-account-api-openapi.yml
- filename: kawaa-com-activity-api-openapi.yml
  format: yaml
  label: kawaa-com Activity API
  slug: kawaa-com-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-activity-api-openapi.yml
- filename: kawaa-com-api-keys-api-openapi.yml
  format: yaml
  label: kawaa-com API keys API
  slug: kawaa-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-api-keys-api-openapi.yml
- filename: kawaa-com-catalogue-api-openapi.yml
  format: yaml
  label: kawaa-com Catalogue API
  slug: kawaa-com-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-catalogue-api-openapi.yml
- filename: kawaa-com-deliverability-api-openapi.yml
  format: yaml
  label: kawaa-com Deliverability API
  slug: kawaa-com-deliverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-deliverability-api-openapi.yml
- filename: kawaa-com-exports-api-openapi.yml
  format: yaml
  label: kawaa-com Exports API
  slug: kawaa-com-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-exports-api-openapi.yml
- filename: kawaa-com-health-api-openapi.yml
  format: yaml
  label: kawaa-com Health API
  slug: kawaa-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-health-api-openapi.yml
- filename: kawaa-com-jobs-api-openapi.yml
  format: yaml
  label: kawaa-com Jobs API
  slug: kawaa-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-jobs-api-openapi.yml
- filename: kawaa-com-search-api-openapi.yml
  format: yaml
  label: kawaa-com Search API
  slug: kawaa-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-search-api-openapi.yml
- filename: kawaa-com-verification-api-openapi.yml
  format: yaml
  label: kawaa-com Verification API
  slug: kawaa-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-verification-api-openapi.yml
- filename: kawaa-com-webhooks-api-openapi.yml
  format: yaml
  label: kawaa-com Webhooks API
  slug: kawaa-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kawaa-com/openapi/kawaa-com-webhooks-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: identifying
    text: Name (optional)
  - category: financial
    text: Kawaa plans and credit packs are sold through Link, LLC ("Link"), a Stripe company, and payments are processed by Stripe. We do not store card numbers.
  - category: device
    text: IP addresses, for rate limiting and security.
  - category: behavioral
    text: 'Website analytics: the pages you open on kawaa.com and app.kawaa.com, the page title, time on page, scroll depth, the site that linked you to us and any campaign tags on that link.'
  deletion:
    route: Account deletion request by email confirmation; contact privacy@kawaa.com
    text: You may request deletion of your account and associated data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: Provide and maintain our service
  - purpose: Process transactions
    text: Process transactions and send billing notifications
  - purpose: Security alerts and updates
    text: Send service updates and security alerts
  - purpose: Improve service
    text: Improve our service and develop new features
  - purpose: Prevent fraud and abuse
    text: Prevent fraud and abuse
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: United States
    text: Your data may be processed in the United States where our servers are located.
  retention:
  - period: 30 days
    scope: Account information
    text: If an account's email address is never verified, we begin deleting the account and its sign-up data 30 days after sign-up
  - period: 2 days
    scope: Rate-limit counters
    text: 'rate-limit counters: up to 2 days'
  - period: 7 days
    scope: Signed-in session
    text: 'a signed-in session: 7 days'
  - period: 30 days
    scope: Service logs (IP addresses)
    text: 'our service logs, which record the IP address each request came from: up to 30 days'
  - period: 90 days
    scope: Sign-in history and security events
    text: 'sign-in history and security events: 90 days'
  - period: 7 days
    scope: Free email checker results
    text: The result of a check made with the free email checker without an account is retained for 7 days and then deleted automatically
  - period: 35 days
    scope: Backups
    text: copies of it can remain in these backups for up to 35 days after it was deleted
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your data
  - right: Export
    text: Export your data
  - right: Withdraw consent
    text: Withdraw consent
  - right: Lodge complaint
    text: Lodge a complaint with a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for international transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: kawaa-com
provenance_date: '2026-11-09'
provider_name: kawaa-com
provider_slug: kawaa-com
slug: kawaa-com-privacy-policy
source_date: '2026-11-09'
source_filename: kawaa-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kawaa.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: kawaa-com\naid: kawaa-com\nurl: https://kawaa.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address\n- category: identifying\n  text: Name (optional)\n- category: financial\n  text: Kawaa plans and credit packs are sold through Link, LLC (\"Link\"), a Stripe company, and payments are processed\n    by Stripe. We do not store card numbers.\n- category: device\n  text: IP addresses, for rate limiting and security.\n- category: behavioral\n  text: 'Website analytics: the pages you open on kawaa.com and app.kawaa.com, the page\
  \ title, time on page, scroll\n    depth, the site that linked you to us and any campaign tags on that link.'\npurposes:\n- purpose: Provide and maintain service\n  text: Provide and maintain our service\n- purpose: Process transactions\n  text: Process transactions and send billing notifications\n- purpose: Security alerts and updates\n  text: Send service updates and security alerts\n- purpose: Improve service\n  text: Improve our service and develop new features\n- purpose: Prevent fraud and abuse\n  text: Prevent fraud and abuse\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account information\n  period: 30 days\n  text: If an account's email address is never verified, we begin deleting the account and its sign-up data 30 days\n    after sign-up\n- scope: Rate-limit counters\n  period: 2 days\n  text: 'rate-limit counters: up to 2 days'\n- scope: Signed-in session\n  period: 7 days\n  text: 'a signed-in session: 7 days'\n- scope: Service\
  \ logs (IP addresses)\n  period: 30 days\n  text: 'our service logs, which record the IP address each request came from: up to 30 days'\n- scope: Sign-in history and security events\n  period: 90 days\n  text: 'sign-in history and security events: 90 days'\n- scope: Free email checker results\n  period: 7 days\n  text: The result of a check made with the free email checker without an account is retained for 7 days and then\n    deleted automatically\n- scope: Backups\n  period: 35 days\n  text: copies of it can remain in these backups for up to 35 days after it was deleted\nresidency:\n- region: United States\n  text: Your data may be processed in the United States where our servers are located.\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place for international transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion request by email confirmation; contact privacy@kawaa.com\n\
  \  text: You may request deletion of your account and associated data at any time.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your data\n- right: Export\n  text: Export your data\n- right: Withdraw consent\n  text: Withdraw consent\n- right: Lodge complaint\n  text: Lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/kawaa-com/privacy/kawaa-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from kawaa-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- Software-as-a-Service
- Marketing
---
