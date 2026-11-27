---
api_specs:
- filename: allratestoday-com-authentication-api-openapi.yml
  format: yaml
  label: allratestoday-com Authentication API
  slug: allratestoday-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-authentication-api-openapi.yml
- filename: allratestoday-com-central-bank-rates-api-openapi.yml
  format: yaml
  label: allratestoday-com Central Bank Rates API
  slug: allratestoday-com-central-bank-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-central-bank-rates-api-openapi.yml
- filename: allratestoday-com-compatibility-api-openapi.yml
  format: yaml
  label: allratestoday-com Compatibility API
  slug: allratestoday-com-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-compatibility-api-openapi.yml
- filename: allratestoday-com-market-rates-api-openapi.yml
  format: yaml
  label: allratestoday-com Market Rates API
  slug: allratestoday-com-market-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-market-rates-api-openapi.yml
- filename: allratestoday-com-open-endpoints-api-openapi.yml
  format: yaml
  label: allratestoday-com Open Endpoints API
  slug: allratestoday-com-open-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-open-endpoints-api-openapi.yml
- filename: allratestoday-com-reference-rate-api-openapi.yml
  format: yaml
  label: allratestoday-com Reference Rate API
  slug: allratestoday-com-reference-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allratestoday-com/openapi/allratestoday-com-reference-rate-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your name, email address, sign-in details, API key, plan and usage counts
  - category: identifying
    text: 'Identity : name, email address and, for email sign-up, a password hash.'
  - category: financial
    text: We store your Stripe customer and subscription IDs, plan, billing interval, subscription status and dates
  - category: device
    text: the calling client's user-agent string (first 120 characters) and the country derived from the IP address
  - category: behavioral
    text: Clarity also records clicks and scrolling to show how pages are used.
  - category: location
    text: approximate location and referring site
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: running the service and fixing errors
    text: 'Purpose: running the service, fixing errors and counting usage.'
  - purpose: providing account and API, billing, security
    text: 'Purposes: providing the account and API, enforcing plan limits, billing, security and preventing abusive sign-ups'
  - purpose: analytics
    text: 'Analytics : Google Analytics (Google) and Microsoft Clarity (Microsoft) record pages visited, time on page, device and browser type, approximate location and referring site.'
  retention:
  - period: until you delete your account
    scope: account data
    text: 'Account data: until you delete your account.'
  - period: 90 days
    scope: API usage counters (daily)
    text: 'API usage counters: 90 days (daily) and 62 days (monthly).'
  - period: up to 7 days
    scope: MCP and API request logs
    text: 'MCP and API request logs, including over-quota events: up to 7 days.'
  - period: 6 months
    scope: contact-form messages
    text: Messages sent through our contact form are stored with your name, email address and IP address for 6 months.
  - period: 30 days
    scope: sessions
    text: 'Sessions: 30 days.'
  rights:
  - right: access, correct, export or delete
    text: you may also have the right to access, correct, export or delete your data
  - right: object or restrict processing
    text: to object to or restrict processing
  - right: withdraw consent
    text: and to withdraw consent
  - right: complain to regulator
    text: You may also complain to the UK Information Commissioner's Office (ico.org.uk) or your local data protection authority.
  role:
    text: The data controller is AllRatesToday.com, Luton, United Kingdom (LU1 5EG).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share it for advertising.
  subprocessors:
    text: 'We use these processors, each only for the purpose shown: Cloudflare : hosting, databases, request logs, email sending and Turnstile. Stripe : payments and subscriptions.'
    url: null
  transfers:
  - mechanism: other
    text: Our processors may handle data outside the UK, including in the United States, under safeguards such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: allratestoday-com
provenance_date: '2026-11-09'
provider_name: allratestoday-com
provider_slug: allratestoday-com
slug: allratestoday-com-privacy-policy
source_date: '2026-11-09'
source_filename: allratestoday-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://allratestoday.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: allratestoday-com\naid: allratestoday-com\nurl: https://allratestoday.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is AllRatesToday.com, Luton, United Kingdom (LU1 5EG).\ndata_categories:\n- category: contact\n  text: we store your name, email address, sign-in details, API key, plan and usage counts\n- category: identifying\n  text: 'Identity : name, email address and, for email sign-up, a password hash.'\n- category: financial\n  text: We store your Stripe customer and subscription IDs, plan, billing interval, subscription status and dates\n- category:\
  \ device\n  text: the calling client's user-agent string (first 120 characters) and the country derived from the IP address\n- category: behavioral\n  text: Clarity also records clicks and scrolling to show how pages are used.\n- category: location\n  text: approximate location and referring site\npurposes:\n- purpose: running the service and fixing errors\n  text: 'Purpose: running the service, fixing errors and counting usage.'\n- purpose: providing account and API, billing, security\n  text: 'Purposes: providing the account and API, enforcing plan limits, billing, security and preventing abusive\n    sign-ups'\n- purpose: analytics\n  text: 'Analytics : Google Analytics (Google) and Microsoft Clarity (Microsoft) record pages visited, time on page,\n    device and browser type, approximate location and referring site.'\nretention:\n- scope: account data\n  period: until you delete your account\n  text: 'Account data: until you delete your account.'\n- scope: API usage counters (daily)\n\
  \  period: 90 days\n  text: 'API usage counters: 90 days (daily) and 62 days (monthly).'\n- scope: MCP and API request logs\n  period: up to 7 days\n  text: 'MCP and API request logs, including over-quota events: up to 7 days.'\n- scope: contact-form messages\n  period: 6 months\n  text: Messages sent through our contact form are stored with your name, email address and IP address for 6 months.\n- scope: sessions\n  period: 30 days\n  text: 'Sessions: 30 days.'\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our processors may handle data outside the UK, including in the United States, under safeguards such as\n    standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'We use these processors, each only for the purpose shown: Cloudflare : hosting, databases, request logs,\n    email sending and Turnstile. Stripe : payments and subscriptions.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correct,\
  \ export or delete\n  text: you may also have the right to access, correct, export or delete your data\n- right: object or restrict processing\n  text: to object to or restrict processing\n- right: withdraw consent\n  text: and to withdraw consent\n- right: complain to regulator\n  text: You may also complain to the UK Information Commissioner's Office (ico.org.uk) or your local data protection\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/allratestoday-com/privacy/allratestoday-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from allratestoday-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Exchange Rates
- Data
---
