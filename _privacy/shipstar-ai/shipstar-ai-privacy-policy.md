---
api_specs:
- filename: shipstar-ai-authentication-api-openapi.yml
  format: yaml
  label: shipstar-ai Authentication API
  slug: shipstar-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-authentication-api-openapi.yml
- filename: shipstar-ai-banner-api-openapi.yml
  format: yaml
  label: shipstar-ai Banner API
  slug: shipstar-ai-banner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-banner-api-openapi.yml
- filename: shipstar-ai-blog-api-openapi.yml
  format: yaml
  label: shipstar-ai Blog API
  slug: shipstar-ai-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-blog-api-openapi.yml
- filename: shipstar-ai-changelog-api-openapi.yml
  format: yaml
  label: shipstar-ai Changelog API
  slug: shipstar-ai-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-changelog-api-openapi.yml
- filename: shipstar-ai-changelog-subscriptions-api-openapi.yml
  format: yaml
  label: shipstar-ai Changelog Subscriptions API
  slug: shipstar-ai-changelog-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-changelog-subscriptions-api-openapi.yml
- filename: shipstar-ai-health-api-openapi.yml
  format: yaml
  label: shipstar-ai Health API
  slug: shipstar-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-health-api-openapi.yml
- filename: shipstar-ai-kb-api-openapi.yml
  format: yaml
  label: shipstar-ai Kb API
  slug: shipstar-ai-kb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-kb-api-openapi.yml
- filename: shipstar-ai-mailing-lists-api-openapi.yml
  format: yaml
  label: shipstar-ai Mailing Lists API
  slug: shipstar-ai-mailing-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-mailing-lists-api-openapi.yml
- filename: shipstar-ai-team-invitations-api-openapi.yml
  format: yaml
  label: shipstar-ai Team Invitations API
  slug: shipstar-ai-team-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipstar-ai/openapi/shipstar-ai-team-invitations-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, job title, password (stored only as a hash)
  - category: financial
    text: Card details are collected and stored by Stripe; we never see the full card number.
  - category: device
    text: IP address, browser and device type, sign-in history, API request logs
  - category: behavioral
    text: the pages and features you use, and errors you run into
  - category: communication
    text: messages you send to support or through the in-app help widget
  - category: professional
    text: repository names and commit metadata (message, author name, date and SHA)
  deletion:
    route: Download your data or delete your account under Account → Data & privacy
    text: Download your data or delete your account under Account → Data & privacy .
  dpa:
    available: null
    text: under the data processing terms in our Terms of Service
    url: null
  purposes:
  - purpose: Create and run account, generate and publish content, provide support
    text: Create and run your account, generate and publish content, deliver to the destinations you connect, and provide support
  - purpose: Product improvement and error tracking
    text: Understand how the dashboard and API are used, find errors and improve the product (PostHog, server-side, and error tracking)
  - purpose: Advertising and analytics cookies
    text: Analytics and advertising cookies on our website and dashboard (Google Analytics, PostHog in the browser, Ahrefs, Google advertising signals)
  residency:
  - region: United States
    text: Shipstar is run from the United States and our vendors mostly process data there.
  retention:
  - period: Until you delete your account or the content
    scope: Account, team and content data
    text: Account, team and content data Until you delete your account or the content.
  - period: 90 days
    scope: IP address and browser on API requests and sign-ins
    text: IP address and browser on API requests and sign-ins 90 days, then cleared
  - period: 90 days
    scope: Prompts sent to the AI model
    text: Prompts sent to the AI model (they quote commit authors and messages) 90 days, then cleared; the draft stays
  - period: typically 7 years
    scope: Billing records and invoices
    text: As long as tax and accounting law requires, typically 7 years
  - period: 2 years
    scope: Records of staff access to accounts
    text: Records of staff access to accounts 2 years
  rights:
  - right: Access
    text: Access your personal information and get a copy of it
  - right: Portability
    text: 'Port it: receive it in a machine-readable format'
  - right: Correction
    text: Correct it if it is inaccurate or incomplete
  - right: Deletion
    text: Delete it
  - right: Restriction
    text: Restrict how we use it while a concern is resolved
  - right: Objection
    text: Object to uses based on legitimate interests, and to direct marketing at any time
  - right: Withdraw consent
    text: Withdraw consent at any time, without affecting what we did before you withdrew it
  - right: Complain to authority
    text: Complain to a data protection authority
  role:
    text: For your account and our website we are the controller of your personal information. For the audiences our customers reach through Shipstar (their changelog subscribers and mailing-list recipients) and for the commit data in their repositories, the customer is the controller and we act as their processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information , and we do not let anyone use it for their own marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (Decision 2021/914) and, for the UK, the International Data Transfer Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: shipstar-ai
provenance_date: '2026-11-10'
provider_name: shipstar-ai
provider_slug: shipstar-ai
slug: shipstar-ai-privacy-policy
source_date: '2026-11-10'
source_filename: shipstar-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shipstar.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: shipstar-ai\naid: shipstar-ai\nurl: https://shipstar.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your account and our website we are the controller of your personal information. For the audiences our\n    customers reach through Shipstar (their changelog subscribers and mailing-list recipients) and for the commit\n    data in their repositories, the customer is the controller and we act as their processor\ndata_categories:\n- category: identifying\n  text: Name, email address, job title, password (stored only as a hash)\n- category: financial\n  text: Card details are collected\
  \ and stored by Stripe; we never see the full card number.\n- category: device\n  text: IP address, browser and device type, sign-in history, API request logs\n- category: behavioral\n  text: the pages and features you use, and errors you run into\n- category: communication\n  text: messages you send to support or through the in-app help widget\n- category: professional\n  text: repository names and commit metadata (message, author name, date and SHA)\npurposes:\n- purpose: Create and run account, generate and publish content, provide support\n  text: Create and run your account, generate and publish content, deliver to the destinations you connect, and\n    provide support\n- purpose: Product improvement and error tracking\n  text: Understand how the dashboard and API are used, find errors and improve the product (PostHog, server-side,\n    and error tracking)\n- purpose: Advertising and analytics cookies\n  text: Analytics and advertising cookies on our website and dashboard (Google\
  \ Analytics, PostHog in the browser,\n    Ahrefs, Google advertising signals)\nretention:\n- scope: Account, team and content data\n  period: Until you delete your account or the content\n  text: Account, team and content data Until you delete your account or the content.\n- scope: IP address and browser on API requests and sign-ins\n  period: 90 days\n  text: IP address and browser on API requests and sign-ins 90 days, then cleared\n- scope: Prompts sent to the AI model\n  period: 90 days\n  text: Prompts sent to the AI model (they quote commit authors and messages) 90 days, then cleared; the draft stays\n- scope: Billing records and invoices\n  period: typically 7 years\n  text: As long as tax and accounting law requires, typically 7 years\n- scope: Records of staff access to accounts\n  period: 2 years\n  text: Records of staff access to accounts 2 years\nresidency:\n- region: United States\n  text: Shipstar is run from the United States and our vendors mostly process data there.\n\
  transfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (Decision 2021/914) and, for the UK, the\n    International Data Transfer Addendum\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: under the data processing terms in our Terms of Service\ndeletion:\n  route: Download your data or delete your account under Account → Data & privacy\n  text: Download your data or delete your account under Account → Data & privacy .\nrights:\n- right: Access\n  text: Access your personal information and get a copy of it\n- right: Portability\n  text: 'Port it: receive it in a machine-readable format'\n- right: Correction\n  text: Correct it if it is inaccurate or incomplete\n- right: Deletion\n  text: Delete it\n- right: Restriction\n  text: Restrict how we use it while a concern is resolved\n- right: Objection\n  text: Object to uses based on legitimate interests, and to direct marketing at any time\n- right: Withdraw\
  \ consent\n  text: Withdraw consent at any time, without affecting what we did before you withdrew it\n- right: Complain to authority\n  text: Complain to a data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information , and we do not let anyone use it for their own marketing.\n"
source_yaml_url: https://artifacts.apis.io/shipstar-ai/privacy/shipstar-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from shipstar-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Developer Tools
- Automation
- Open Source
---
