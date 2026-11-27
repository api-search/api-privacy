---
api_specs:
- filename: weatherai-io-openapi.json
  format: json
  label: Decision API
  slug: decision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherai-io/openapi/weatherai-io-openapi.json
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account details: your email address, a securely hashed password (we cannot read your password), and the name and company you choose to give.'
  - category: financial
    text: 'Billing data: for each top-up, the amount, the date, the billing name, email and address you give on the checkout page (needed for VAT receipts)'
  - category: device
    text: 'Technical data: IP address, browser or client type, the page or endpoint requested, the response code and timing'
  - category: behavioral
    text: 'Usage data: the number of free and paid calls per day, the activities requested, your credit balance'
  - category: location
    text: 'API request data: the locations and activities sent in API requests.'
  - category: communication
    text: 'Correspondence: emails you send us and our replies.'
  deletion:
    route: Email support@weatherai.io from the email address on your account
    text: To use these rights, email support@weatherai.io from the email address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and API service
    text: Create and run your account, provide the API, show your usage and balance, and send service emails
  - purpose: Payments and tax records
    text: Take payments, add credit, issue VAT receipts and keep accounting and tax records
  - purpose: Abuse prevention and security
    text: Prevent abuse of the free allowance, fraud, spam sign-ups and attacks, and keep the Service secure
  - purpose: Website analytics
    text: Website analytics with Google Analytics (pages visited, approximate location, device and browser)
  residency:
  - region: UK or EEA
    text: We keep our servers in the UK or the European Economic Area
  retention:
  - period: 90 days
    scope: Account details, API keys and usage statistics
    text: While your account is open, then deleted or anonymised within 90 days of closure
  - period: 6 years
    scope: Billing data and VAT receipts
    text: 6 years from the end of the financial year of the payment
  - period: 14 days
    scope: Web server and API logs
    text: Web server and API logs 14 days
  - period: about 10 minutes
    scope: Locations and activities sent to the API
    text: Not stored, except in a short-lived cache of about 10 minutes
  - period: 3 years
    scope: Correspondence
    text: Correspondence 3 years from our last contact
  rights:
  - right: access
    text: get a copy of your personal data (access)
  - right: correction
    text: have inaccurate data corrected
  - right: erasure
    text: have your data deleted, where we no longer need it or have no lawful basis to keep it
  - right: restriction or objection
    text: restrict how we use your data, or object to our use of it based on legitimate interests
  - right: portability
    text: receive the data you gave us in a machine-readable format (portability)
  - right: withdraw consent
    text: withdraw any consent you have given, at any time
  role:
    text: The controller of your personal data is Zoomash Ltd, a company registered in England and Wales with company number 07838145
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data and do not use it for advertising.
  subprocessors:
    text: 'Processors acting for us under written contracts that require them to protect your data and use it only on our instructions: UpCloud Ltd (Finland), cloud servers in London, UK'
    url: null
  transfers:
  - mechanism: DPF
    text: the UK Extension to the EU-US Data Privacy Framework where the recipient is certified
  - mechanism: other
    text: the International Data Transfer Agreement or the UK Addendum to the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: weatherAI.io
provenance_date: '2026-11-10'
provider_name: weatherAI.io
provider_slug: weatherai-io
slug: weatherai-io-privacy-policy
source_date: '2026-11-10'
source_filename: weatherai-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.weatherai.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: weatherAI.io\naid: weatherai-io\nurl: https://www.weatherai.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is Zoomash Ltd, a company registered in England and Wales with company\n    number 07838145\ndata_categories:\n- category: contact\n  text: 'Account details: your email address, a securely hashed password (we cannot read your password), and the\n    name and company you choose to give.'\n- category: financial\n  text: 'Billing data: for each top-up, the amount, the date, the billing name, email and address you give on the\n    checkout page\
  \ (needed for VAT receipts)'\n- category: device\n  text: 'Technical data: IP address, browser or client type, the page or endpoint requested, the response code and\n    timing'\n- category: behavioral\n  text: 'Usage data: the number of free and paid calls per day, the activities requested, your credit balance'\n- category: location\n  text: 'API request data: the locations and activities sent in API requests.'\n- category: communication\n  text: 'Correspondence: emails you send us and our replies.'\npurposes:\n- purpose: Account and API service\n  text: Create and run your account, provide the API, show your usage and balance, and send service emails\n- purpose: Payments and tax records\n  text: Take payments, add credit, issue VAT receipts and keep accounting and tax records\n- purpose: Abuse prevention and security\n  text: Prevent abuse of the free allowance, fraud, spam sign-ups and attacks, and keep the Service secure\n- purpose: Website analytics\n  text: Website analytics with\
  \ Google Analytics (pages visited, approximate location, device and browser)\nretention:\n- scope: Account details, API keys and usage statistics\n  period: 90 days\n  text: While your account is open, then deleted or anonymised within 90 days of closure\n- scope: Billing data and VAT receipts\n  period: 6 years\n  text: 6 years from the end of the financial year of the payment\n- scope: Web server and API logs\n  period: 14 days\n  text: Web server and API logs 14 days\n- scope: Locations and activities sent to the API\n  period: about 10 minutes\n  text: Not stored, except in a short-lived cache of about 10 minutes\n- scope: Correspondence\n  period: 3 years\n  text: Correspondence 3 years from our last contact\nresidency:\n- region: UK or EEA\n  text: We keep our servers in the UK or the European Economic Area\ntransfers:\n- mechanism: DPF\n  text: the UK Extension to the EU-US Data Privacy Framework where the recipient is certified\n- mechanism: other\n  text: the International Data\
  \ Transfer Agreement or the UK Addendum to the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: 'Processors acting for us under written contracts that require them to protect your data and use it only\n    on our instructions: UpCloud Ltd (Finland), cloud servers in London, UK'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@weatherai.io from the email address on your account\n  text: To use these rights, email support@weatherai.io from the email address on your account.\nrights:\n- right: access\n  text: get a copy of your personal data (access)\n- right: correction\n  text: have inaccurate data corrected\n- right: erasure\n  text: have your data deleted, where we no longer need it or have no lawful basis to keep it\n- right: restriction or objection\n  text: restrict how we use your data, or object to our use of it based on legitimate interests\n- right: portability\n  text: receive the data you gave us in a machine-readable\
  \ format (portability)\n- right: withdraw consent\n  text: withdraw any consent you have given, at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data and do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/weatherai-io/privacy/weatherai-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from weatherAI.io's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Artificial Intelligence
- Decisions
- Forecast
---
