---
api_specs:
- filename: xproapi-default-api-openapi.yml
  format: yaml
  label: Xproapi Default API
  slug: xproapi-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-default-api-openapi.yml
- filename: xproapi-follow-followings-api-openapi.yml
  format: yaml
  label: Xproapi Follow, Followings API
  slug: xproapi-follow-followings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-follow-followings-api-openapi.yml
- filename: xproapi-tweet-activity-api-openapi.yml
  format: yaml
  label: Xproapi Tweet Activity API
  slug: xproapi-tweet-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-tweet-activity-api-openapi.yml
- filename: xproapi-tweets-api-openapi.yml
  format: yaml
  label: Xproapi Tweets API
  slug: xproapi-tweets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-tweets-api-openapi.yml
- filename: xproapi-users-api-openapi.yml
  format: yaml
  label: Xproapi Users API
  slug: xproapi-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-users-api-openapi.yml
- filename: xproapi-followers-api-openapi.yml
  format: yaml
  label: Xproapi Followers API
  slug: xproapi-followers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-followers-api-openapi.yml
- filename: xproapi-following-api-openapi.yml
  format: yaml
  label: Xproapi Following API
  slug: xproapi-following-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-following-api-openapi.yml
- filename: xproapi-mentions-api-openapi.yml
  format: yaml
  label: Xproapi Mentions API
  slug: xproapi-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xproapi/openapi/xproapi-mentions-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: Email address, password hash, company name, primary use case, and selected timezone.'
  - category: communication
    text: 'Alert Configurations: Telegram chat IDs (linked via our official bot) and Discord webhook URLs provided for notification delivery.'
  - category: financial
    text: 'Payment Evidence: Cryptocurrency transaction hashes and screenshot uploads submitted to verify credit recharge requests.'
  - category: device
    text: 'HTTP & Activity Logs: IP addresses, browser user agent, requested URLs, request timestamps, and response status codes.'
  - category: behavioral
    text: 'Usage Metrics: Number of daily requests made to our API, credit consumption history, and active monitored accounts.'
  deletion:
    route: Contact support to request full account deletion
    text: Request full deletion of your account and associated tracked watchlists by contacting support.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain account access
    text: Provide, authenticate, and maintain your account access.
  - purpose: Deliver alerts and digests
    text: Deliver real-time follow alerts and periodic summary digests to your configured channels.
  - purpose: Validate and credit top-ups
    text: Validate and credit your account for USDT top-up requests.
  - purpose: Abuse and fraud prevention
    text: Detect abuse, prevent fraudulent account creation, and protect the stability of our platform.
  - purpose: Customer support
    text: Provide prompt technical and customer support.
  retention:
  - period: 14 days
    scope: HTTP request logs
    text: Detailed server request logs are retained for 14 days for security and debugging, after which they are automatically pruned.
  - period: 90 days
    scope: Admin and security activity
    text: Login records and account audit entries are kept for 90 days .
  - period: null
    scope: Payment and credit history
    text: Transaction logs and approved top-up records are retained for financial accounting consistency.
  rights:
  - right: Access
    text: Access and review the personal data associated with your account.
  - right: Update
    text: Update your profile, timezone, and alert notification destinations at any time.
  - right: Deletion
    text: Request full deletion of your account and associated tracked watchlists by contacting support.
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
name: Xproapi
provenance_date: '2026-11-10'
provider_name: Xproapi
provider_slug: xproapi
slug: xproapi-privacy-policy
source_date: '2026-11-10'
source_filename: xproapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://xproapi.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Xproapi\naid: xproapi\nurl: https://xproapi.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Data: Email address, password hash, company name, primary use case, and selected timezone.'\n- category: communication\n  text: 'Alert Configurations: Telegram chat IDs (linked via our official bot) and Discord webhook URLs provided\n    for notification delivery.'\n- category: financial\n  text: 'Payment Evidence: Cryptocurrency transaction hashes and screenshot uploads submitted to verify credit recharge\n    requests.'\n\
  - category: device\n  text: 'HTTP & Activity Logs: IP addresses, browser user agent, requested URLs, request timestamps, and response\n    status codes.'\n- category: behavioral\n  text: 'Usage Metrics: Number of daily requests made to our API, credit consumption history, and active monitored\n    accounts.'\npurposes:\n- purpose: Provide and maintain account access\n  text: Provide, authenticate, and maintain your account access.\n- purpose: Deliver alerts and digests\n  text: Deliver real-time follow alerts and periodic summary digests to your configured channels.\n- purpose: Validate and credit top-ups\n  text: Validate and credit your account for USDT top-up requests.\n- purpose: Abuse and fraud prevention\n  text: Detect abuse, prevent fraudulent account creation, and protect the stability of our platform.\n- purpose: Customer support\n  text: Provide prompt technical and customer support.\nretention:\n- scope: HTTP request logs\n  period: 14 days\n  text: Detailed server request\
  \ logs are retained for 14 days for security and debugging, after which they are automatically\n    pruned.\n- scope: Admin and security activity\n  period: 90 days\n  text: Login records and account audit entries are kept for 90 days .\n- scope: Payment and credit history\n  period: null\n  text: Transaction logs and approved top-up records are retained for financial accounting consistency.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support to request full account deletion\n  text: Request full deletion of your account and associated tracked watchlists by contacting support.\nrights:\n- right: Access\n  text: Access and review the personal data associated with your account.\n- right: Update\n  text: Update your profile, timezone, and alert notification destinations at any time.\n- right: Deletion\n  text: Request full deletion of your account and associated tracked watchlists\
  \ by contacting support.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xproapi/privacy/xproapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from Xproapi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- X
- Social
- Monitoring
- Data
---
