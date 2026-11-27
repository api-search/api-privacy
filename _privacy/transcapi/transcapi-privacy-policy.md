---
api_specs:
- filename: transcapi-airports-api-openapi.yml
  format: yaml
  label: TransCAPI Airports API
  slug: transcapi-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-airports-api-openapi.yml
- filename: transcapi-alerts-api-openapi.yml
  format: yaml
  label: TransCAPI Alerts API
  slug: transcapi-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-alerts-api-openapi.yml
- filename: transcapi-bus-api-openapi.yml
  format: yaml
  label: TransCAPI Bus API
  slug: transcapi-bus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-bus-api-openapi.yml
- filename: transcapi-disruptions-api-openapi.yml
  format: yaml
  label: TransCAPI Disruptions API
  slug: transcapi-disruptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-disruptions-api-openapi.yml
- filename: transcapi-journey-api-openapi.yml
  format: yaml
  label: TransCAPI Journey API
  slug: transcapi-journey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-journey-api-openapi.yml
- filename: transcapi-places-api-openapi.yml
  format: yaml
  label: TransCAPI Places API
  slug: transcapi-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-places-api-openapi.yml
- filename: transcapi-rail-api-openapi.yml
  format: yaml
  label: TransCAPI Rail API
  slug: transcapi-rail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-rail-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email address, password (stored only as a secure hash), sign-up and confirmation dates, plan'
  - category: contact
    text: 'News email list: your email address, where you signed up, and when you confirmed or left'
  - category: financial
    text: 'Billing: your Stripe customer reference, subscription and renewal date. We never see or store card details'
  - category: device
    text: 'Web server logs: IP address, browser, page requested, time'
  - category: behavioral
    text: 'API request logs: which key, endpoint and parameters (which can include coordinates, stops or places you look up), response code and time'
  - category: communication
    text: 'Chats: your name, what you and we write in the chat on this site, the page you started it on, and your email address if you give it (or your account, if you''re logged in)'
  deletion:
    route: Self-service deletion from Settings in dashboard
    text: or delete your account and everything tied to it, yourself from Settings in your dashboard
  dpa:
    available: null
    text: They act on our instructions under contracts that protect your data, except Stripe for payment data as noted.
    url: null
  purposes:
  - purpose: Run account and send account emails
    text: 'To run your account and send the emails it needs: confirmation, password resets, plan changes, security notices'
  - purpose: Authenticate API requests and apply plan limits
    text: To authenticate requests and apply your plan's limits
  - purpose: Show usage, investigate problems and abuse, improve service
    text: To show your usage in the dashboard, investigate problems and abuse, and improve the service
  - purpose: Send news emails
    text: To send the occasional news email you asked for
  - purpose: Answer chat questions
    text: To answer your questions, and to email you the reply if you've left the page
  residency:
  - region: Germany
    text: 'Hosting: the servers the website, API and database run on Germany'
  retention:
  - period: 30 days
    scope: Account data
    text: While your account is open; deleted within 30 days of closing it
  - period: 90 days
    scope: API request logs
    text: 90 days, then deleted automatically
  - period: 14 days
    scope: Web server logs
    text: 14 days
  - period: 2 years
    scope: Chats
    text: As long as needed to deal with your request, and no more than 2 years
  - period: null
    scope: Billing records
    text: as long afterwards as tax and accounting law requires
  rights:
  - right: Access
    text: You can ask us to give you a copy of your data
  - right: Rectification
    text: correct it
  - right: Erasure
    text: delete it
  - right: Restriction and objection
    text: restrict or object to how we use it
  - right: Portability
    text: give it to you in a portable form
  - right: Complaint
    text: you can complain to the Information Commissioner's Office at ico.org.uk
  role:
    text: TransCAPI, Edinburgh, is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data, and we only share it with anyone else where the law requires it.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Where data goes outside the UK, it is to countries the UK recognises as adequate, such as EU countries
  - mechanism: other
    text: under the UK's approved safeguards for transfers, such as the International Data Transfer Agreement or the UK Extension to the EU–US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TransCAPI
provenance_date: '2026-11-10'
provider_name: TransCAPI
provider_slug: transcapi
slug: transcapi-privacy-policy
source_date: '2026-11-10'
source_filename: transcapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.transcapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TransCAPI\naid: transcapi\nurl: https://www.transcapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: TransCAPI, Edinburgh, is the controller of the personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Account: email address, password (stored only as a secure hash), sign-up and confirmation dates, plan'\n- category: contact\n  text: 'News email list: your email address, where you signed up, and when you confirmed or left'\n- category: financial\n  text: 'Billing: your Stripe customer reference, subscription and renewal date. We never see or store card\
  \ details'\n- category: device\n  text: 'Web server logs: IP address, browser, page requested, time'\n- category: behavioral\n  text: 'API request logs: which key, endpoint and parameters (which can include coordinates, stops or places you\n    look up), response code and time'\n- category: communication\n  text: 'Chats: your name, what you and we write in the chat on this site, the page you started it on, and your\n    email address if you give it (or your account, if you''re logged in)'\npurposes:\n- purpose: Run account and send account emails\n  text: 'To run your account and send the emails it needs: confirmation, password resets, plan changes, security\n    notices'\n- purpose: Authenticate API requests and apply plan limits\n  text: To authenticate requests and apply your plan's limits\n- purpose: Show usage, investigate problems and abuse, improve service\n  text: To show your usage in the dashboard, investigate problems and abuse, and improve the service\n- purpose: Send news\
  \ emails\n  text: To send the occasional news email you asked for\n- purpose: Answer chat questions\n  text: To answer your questions, and to email you the reply if you've left the page\nretention:\n- scope: Account data\n  period: 30 days\n  text: While your account is open; deleted within 30 days of closing it\n- scope: API request logs\n  period: 90 days\n  text: 90 days, then deleted automatically\n- scope: Web server logs\n  period: 14 days\n  text: 14 days\n- scope: Chats\n  period: 2 years\n  text: As long as needed to deal with your request, and no more than 2 years\n- scope: Billing records\n  period: null\n  text: as long afterwards as tax and accounting law requires\nresidency:\n- region: Germany\n  text: 'Hosting: the servers the website, API and database run on Germany'\ntransfers:\n- mechanism: adequacy\n  text: Where data goes outside the UK, it is to countries the UK recognises as adequate, such as EU countries\n- mechanism: other\n  text: under the UK's approved safeguards\
  \ for transfers, such as the International Data Transfer Agreement or the\n    UK Extension to the EU–US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: They act on our instructions under contracts that protect your data, except Stripe for payment data as noted.\ndeletion:\n  route: Self-service deletion from Settings in dashboard\n  text: or delete your account and everything tied to it, yourself from Settings in your dashboard\nrights:\n- right: Access\n  text: You can ask us to give you a copy of your data\n- right: Rectification\n  text: correct it\n- right: Erasure\n  text: delete it\n- right: Restriction and objection\n  text: restrict or object to how we use it\n- right: Portability\n  text: give it to you in a portable form\n- right: Complaint\n  text: you can complain to the Information Commissioner's Office at ico.org.uk\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data, and we only share\
  \ it with anyone else where the law requires it.\n"
source_yaml_url: https://artifacts.apis.io/transcapi/privacy/transcapi-privacy-policy.yml
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
summary_line: 29 quoted statements, read from TransCAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Transport
- United Kingdom
- Ireland
---
