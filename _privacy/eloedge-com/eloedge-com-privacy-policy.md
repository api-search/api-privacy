---
api_specs:
- filename: eloedge-com-openapi-generated.yml
  format: yaml
  label: eloedge-com API
  slug: eloedge-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eloedge-com/openapi/_ae-authored/eloedge-com-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, confirmed email address and profile picture, the identifier your chosen provider uses for your account, and its sign-in tokens.
  - category: financial
    text: We receive and keep only your Stripe customer ID, your plan (including a Lifetime purchase), whether you pay monthly or yearly, your subscription status, when your current period ends, and whether you've scheduled a cancellation.
  - category: location
    text: Your IP address, approximate country (derived from the IP), the date and time, the page or endpoint requested including its full address, the response status, and your browser or client's user-agent.
  - category: communication
    text: If you write to [email protected] , we keep your message, your email address and our reply in our email, so we can answer and follow up.
  - category: behavioral
    text: a count of requests per day
  - category: device
    text: your browser's user-agent
  deletion:
    route: Account page self-service deletion
    text: You can delete your account yourself, any time, from your account page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign in and run account
    text: 'Only to: sign you in and run your account; provide the Service, including the website, API, MCP servers and data store'
  - purpose: Payments and subscription
    text: process payments and manage your subscription
  - purpose: Security and abuse prevention
    text: enforce plan limits and our Terms , and prevent fraud, abuse and security incidents
  - purpose: Legal and accounting
    text: meet legal, tax and accounting obligations
  residency:
  - region: United States
    text: The Service runs in the United States , and your information is stored on servers in Virginia.
  retention:
  - period: Until you delete your account
    scope: Account and API key records
    text: Account and API key records Until you delete your account
  - period: 30 days
    scope: Server logs
    text: Server logs 30 days, unless needed longer for an active security investigation
  - period: Up to 2 years
    scope: Support emails and feedback
    text: Support emails and feedback Up to 2 years
  - period: generally 7 years
    scope: Billing and tax records
    text: Billing and tax records As long as the law requires — generally 7 years, even after you delete your account
  rights:
  - right: access
    text: email [email protected] to ask for a copy of your data, to correct it, or to delete it
  - right: correct
    text: email [email protected] to ask for a copy of your data, to correct it, or to delete it
  - right: delete
    text: delete your account yourself from the account page
  - right: restrict, port and object (GDPR)
    text: You have rights to access, correct, delete, restrict, port and object, and to complain to your local data protection authority.
  role:
    text: We are responsible for the personal information described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your personal information or share it for targeted advertising , and we haven't in the past 12 months.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: eloedge-com
provenance_date: '2026-11-09'
provider_name: eloedge-com
provider_slug: eloedge-com
slug: eloedge-com-privacy-policy
source_date: '2026-11-09'
source_filename: eloedge-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eloedge.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: eloedge-com\naid: eloedge-com\nurl: https://eloedge.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for the personal information described here.\ndata_categories:\n- category: identifying\n  text: Your name, confirmed email address and profile picture, the identifier your chosen provider uses for your\n    account, and its sign-in tokens.\n- category: financial\n  text: We receive and keep only your Stripe customer ID, your plan (including a Lifetime purchase), whether you\n    pay monthly or yearly, your subscription status, when your current period ends, and\
  \ whether you've scheduled\n    a cancellation.\n- category: location\n  text: Your IP address, approximate country (derived from the IP), the date and time, the page or endpoint requested\n    including its full address, the response status, and your browser or client's user-agent.\n- category: communication\n  text: If you write to [email protected] , we keep your message, your email address and our reply in our email,\n    so we can answer and follow up.\n- category: behavioral\n  text: a count of requests per day\n- category: device\n  text: your browser's user-agent\npurposes:\n- purpose: Sign in and run account\n  text: 'Only to: sign you in and run your account; provide the Service, including the website, API, MCP servers\n    and data store'\n- purpose: Payments and subscription\n  text: process payments and manage your subscription\n- purpose: Security and abuse prevention\n  text: enforce plan limits and our Terms , and prevent fraud, abuse and security incidents\n- purpose:\
  \ Legal and accounting\n  text: meet legal, tax and accounting obligations\nretention:\n- scope: Account and API key records\n  period: Until you delete your account\n  text: Account and API key records Until you delete your account\n- scope: Server logs\n  period: 30 days\n  text: Server logs 30 days, unless needed longer for an active security investigation\n- scope: Support emails and feedback\n  period: Up to 2 years\n  text: Support emails and feedback Up to 2 years\n- scope: Billing and tax records\n  period: generally 7 years\n  text: Billing and tax records As long as the law requires — generally 7 years, even after you delete your account\nresidency:\n- region: United States\n  text: The Service runs in the United States , and your information is stored on servers in Virginia.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page self-service deletion\n  text: You can delete your account\
  \ yourself, any time, from your account page.\nrights:\n- right: access\n  text: email [email protected] to ask for a copy of your data, to correct it, or to delete it\n- right: correct\n  text: email [email protected] to ask for a copy of your data, to correct it, or to delete it\n- right: delete\n  text: delete your account yourself from the account page\n- right: restrict, port and object (GDPR)\n  text: You have rights to access, correct, delete, restrict, port and object, and to complain to your local data\n    protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your personal information or share it for targeted advertising , and we haven't in the past\n    12 months.\n"
source_yaml_url: https://artifacts.apis.io/eloedge-com/privacy/eloedge-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from eloedge-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Prediction-Market
- Trading-Agent
- MCP
- Data Feed
- Platform
---
