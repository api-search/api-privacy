---
api_specs:
- filename: bankbridge-money-openapi-generated.yml
  format: yaml
  label: BankBridge API
  slug: bankbridge-money-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankbridge-money/openapi/_ae-authored/bankbridge-money-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: your email address, your Stripe customer and subscription IDs, your plan (monthly or annual), and your referral code.'
  - category: identifying
    text: 'Sign in with Google (optional): if you choose “Continue with Google”, Google shares your name, email address, whether Google has verified that email, and your profile photo URL.'
  - category: financial
    text: 'Bank connections: an access token for each bank you link (encrypted with AES-256-GCM), plus the bank’s name and connection status.'
  - category: device
    text: 'Usage log: for each request to the MCP server, the tool name, time, calling app and version, user agent, IP address, response status, and response time.'
  - category: communication
    text: 'Email and feedback records: which account emails we sent you and when, your email preferences, and any answers you give in the cancellation survey.'
  - category: device
    text: 'Website data: web server logs (IP address, page requested, browser type), kept 14 days for security.'
  deletion:
    route: Delete your account from Settings
    text: Delete your account from Settings. This cancels your subscription, revokes every bank connection, and deletes your account details, usage log, and email and feedback records right away.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign in and billing
    text: Used to sign you in, bill you, and send account email.
  - purpose: Fetch data when agent asks
    text: Used only to fetch your data when your agent asks.
  - purpose: Check requests come from you
    text: Used to check that a request really comes from you.
  - purpose: Show agent activity, debug, stop abuse
    text: Used to show you your agent’s activity, debug problems, and stop abuse.
  - purpose: Avoid duplicate emails and improve BankBridge
    text: Used to avoid duplicate emails and improve BankBridge.
  - purpose: Billing and tax records
    text: Used for billing and tax records.
  residency:
  - region: United States
    text: DigitalOcean hosts our servers in the United States.
  retention:
  - period: until you delete your account
    scope: Account details
    text: Kept until you delete your account.
  - period: within a day after your subscription ends
    scope: Bank connections
    text: Deleted when you disconnect that bank, delete your account, or within a day after your subscription ends.
  - period: 30 days
    scope: Usage log
    text: Deleted after 30 days.
  - period: 7 years
    scope: Billing audit records
    text: Kept up to 7 years.
  - period: 14 days
    scope: Website web server logs
    text: web server logs (IP address, page requested, browser type), kept 14 days for security.
  - period: 30 days
    scope: Guest connections
    text: a guest connection not used for 30 days is deleted automatically.
  rights:
  - right: Access or copy of data
    text: Email hello@greatwork.company to get a copy of your data or to ask any privacy question.
  - right: Deletion of account
    text: Delete your account from Settings.
  - right: Withdraw analytics consent / block cookies
    text: Block or clear analytics cookies in your browser.
  - right: Unsubscribe from optional emails
    text: Turn off optional emails with the unsubscribe link in any of them.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your data, share it with advertisers, or use it to train AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BankBridge
provenance_date: '2026-11-09'
provider_name: BankBridge
provider_slug: bankbridge-money
slug: bankbridge-money-privacy-policy
source_date: '2026-11-09'
source_filename: bankbridge-money-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bankbridge.money/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BankBridge\naid: bankbridge-money\nurl: https://bankbridge.money/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account details: your email address, your Stripe customer and subscription IDs, your plan (monthly or annual),\n    and your referral code.'\n- category: identifying\n  text: 'Sign in with Google (optional): if you choose “Continue with Google”, Google shares your name, email address,\n    whether Google has verified that email, and your profile photo URL.'\n- category: financial\n  text: 'Bank connections: an access\
  \ token for each bank you link (encrypted with AES-256-GCM), plus the bank’s\n    name and connection status.'\n- category: device\n  text: 'Usage log: for each request to the MCP server, the tool name, time, calling app and version, user agent,\n    IP address, response status, and response time.'\n- category: communication\n  text: 'Email and feedback records: which account emails we sent you and when, your email preferences, and any\n    answers you give in the cancellation survey.'\n- category: device\n  text: 'Website data: web server logs (IP address, page requested, browser type), kept 14 days for security.'\npurposes:\n- purpose: Sign in and billing\n  text: Used to sign you in, bill you, and send account email.\n- purpose: Fetch data when agent asks\n  text: Used only to fetch your data when your agent asks.\n- purpose: Check requests come from you\n  text: Used to check that a request really comes from you.\n- purpose: Show agent activity, debug, stop abuse\n  text: Used to show\
  \ you your agent’s activity, debug problems, and stop abuse.\n- purpose: Avoid duplicate emails and improve BankBridge\n  text: Used to avoid duplicate emails and improve BankBridge.\n- purpose: Billing and tax records\n  text: Used for billing and tax records.\nretention:\n- scope: Account details\n  period: until you delete your account\n  text: Kept until you delete your account.\n- scope: Bank connections\n  period: within a day after your subscription ends\n  text: Deleted when you disconnect that bank, delete your account, or within a day after your subscription ends.\n- scope: Usage log\n  period: 30 days\n  text: Deleted after 30 days.\n- scope: Billing audit records\n  period: 7 years\n  text: Kept up to 7 years.\n- scope: Website web server logs\n  period: 14 days\n  text: web server logs (IP address, page requested, browser type), kept 14 days for security.\n- scope: Guest connections\n  period: 30 days\n  text: a guest connection not used for 30 days is deleted automatically.\n\
  residency:\n- region: United States\n  text: DigitalOcean hosts our servers in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account from Settings\n  text: Delete your account from Settings. This cancels your subscription, revokes every bank connection, and deletes\n    your account details, usage log, and email and feedback records right away.\nrights:\n- right: Access or copy of data\n  text: Email hello@greatwork.company to get a copy of your data or to ask any privacy question.\n- right: Deletion of account\n  text: Delete your account from Settings.\n- right: Withdraw analytics consent / block cookies\n  text: Block or clear analytics cookies in your browser.\n- right: Unsubscribe from optional emails\n  text: Turn off optional emails with the unsubscribe link in any of them.\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your data, share it with advertisers,\
  \ or use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/bankbridge-money/privacy/bankbridge-money-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from BankBridge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- MCP
- Banking
---
