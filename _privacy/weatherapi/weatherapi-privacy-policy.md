---
api_specs:
- filename: weatherapi-alerts-api-openapi.yml
  format: yaml
  label: WeatherAPI Alerts API
  slug: weatherapi-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-alerts-api-openapi.yml
- filename: weatherapi-future-api-openapi.yml
  format: yaml
  label: WeatherAPI Future API
  slug: weatherapi-future-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-future-api-openapi.yml
- filename: weatherapi-geo-api-openapi.yml
  format: yaml
  label: WeatherAPI Geo API
  slug: weatherapi-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-geo-api-openapi.yml
- filename: weatherapi-history-api-openapi.yml
  format: yaml
  label: WeatherAPI History API
  slug: weatherapi-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-history-api-openapi.yml
- filename: weatherapi-marine-api-openapi.yml
  format: yaml
  label: WeatherAPI Marine API
  slug: weatherapi-marine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-marine-api-openapi.yml
- filename: weatherapi-sports-api-openapi.yml
  format: yaml
  label: WeatherAPI Sports API
  slug: weatherapi-sports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-sports-api-openapi.yml
- filename: weatherapi-weather-api-openapi.yml
  format: yaml
  label: WeatherAPI Weather API
  slug: weatherapi-weather-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-weather-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, password (stored only as a secure hash), name, and any profile details you add
  - category: contact
    text: 'Team details : the email addresses of people you invite to your account, and their role.'
  - category: financial
    text: company name, billing address, VAT number, purchase order numbers, invoices and payment history
  - category: device
    text: IP address, browser and device information, and the pages you request on our website and dashboard, recorded in server logs and used for security
  - category: communication
    text: emails and messages you send to support, and records of the emails we send you (for example whether they were delivered)
  - category: other
    text: locations (for example coordinates) and IP addresses that relate to your own users
  deletion:
    route: Email support@weatherapi.com
    text: Requests are free and we answer within one month. Email support@weatherapi.com
  dpa:
    available: true
    text: You can sign a copy of the DPA in your dashboard under My Account, DPA .
    url: null
  purposes:
  - purpose: provide account and API
    text: 'To provide your account and the API, including authentication, usage limits and support: performance of our contract with you.'
  - purpose: billing and legal records
    text: 'To bill you, collect payments, keep accounting and tax records: contract and legal obligation .'
  - purpose: security and fraud prevention
    text: 'To keep our website and API secure, prevent fraud and abuse, and fix faults: legitimate interests .'
  - purpose: marketing
    text: 'To send product news and offers to customers: legitimate interests , and you can unsubscribe at any time using the link in each email'
  - purpose: analytics
    text: 'To understand how the dashboard is used so we can improve it (Google Analytics): consent where required by law.'
  residency:
  - region: United Kingdom and Finland
    text: Our servers are in the United Kingdom and Finland.
  retention:
  - period: While your account is open; deleted within 30 days after you close it
    scope: Account, team and API key details
    text: While your account is open; deleted within 30 days after you close it
  - period: 6 years after the end of the financial year they relate to
    scope: Invoices, payment and tax records
    text: 6 years after the end of the financial year they relate to, as UK tax law requires
  - period: 30 days
    scope: Web server, load balancer and CDN logs
    text: Web server, load balancer and CDN logs 30 days
  - period: 12 months
    scope: Support emails
    text: Support emails 12 months
  - period: 30 days
    scope: Backups
    text: Backups 30 days
  rights:
  - right: access
    text: access your personal data
  - right: correction
    text: have inaccurate data corrected
  - right: deletion
    text: have your data deleted
  - right: restriction or objection
    text: restrict or object to our processing (including at any time to direct marketing)
  - right: portability
    text: receive your data in a portable format
  - right: withdraw consent
    text: withdraw consent where we rely on it
  role:
    text: We are the controller of the personal data described in this policy
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data
  subprocessors:
    text: We use the following service providers, each under a written contract that requires them to protect your data and use it only on our instructions
    url: null
  transfers:
  - mechanism: adequacy
    text: we rely on an adequacy decision (including the UK-US data bridge for certified US companies)
  - mechanism: other
    text: the UK International Data Transfer Agreement or Addendum and the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WeatherAPI
provenance_date: '2026-11-10'
provider_name: WeatherAPI
provider_slug: weatherapi
slug: weatherapi-privacy-policy
source_date: '2026-11-10'
source_filename: weatherapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.weatherapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WeatherAPI\naid: weatherapi\nurl: https://www.weatherapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of the personal data described in this policy\ndata_categories:\n- category: identifying\n  text: your email address, password (stored only as a secure hash), name, and any profile details you add\n- category: contact\n  text: 'Team details : the email addresses of people you invite to your account, and their role.'\n- category: financial\n  text: company name, billing address, VAT number, purchase order numbers, invoices and payment history\n- category: device\n\
  \  text: IP address, browser and device information, and the pages you request on our website and dashboard, recorded\n    in server logs and used for security\n- category: communication\n  text: emails and messages you send to support, and records of the emails we send you (for example whether they\n    were delivered)\n- category: other\n  text: locations (for example coordinates) and IP addresses that relate to your own users\npurposes:\n- purpose: provide account and API\n  text: 'To provide your account and the API, including authentication, usage limits and support: performance of\n    our contract with you.'\n- purpose: billing and legal records\n  text: 'To bill you, collect payments, keep accounting and tax records: contract and legal obligation .'\n- purpose: security and fraud prevention\n  text: 'To keep our website and API secure, prevent fraud and abuse, and fix faults: legitimate interests .'\n- purpose: marketing\n  text: 'To send product news and offers to customers: legitimate\
  \ interests , and you can unsubscribe at any time\n    using the link in each email'\n- purpose: analytics\n  text: 'To understand how the dashboard is used so we can improve it (Google Analytics): consent where required\n    by law.'\nretention:\n- scope: Account, team and API key details\n  period: While your account is open; deleted within 30 days after you close it\n  text: While your account is open; deleted within 30 days after you close it\n- scope: Invoices, payment and tax records\n  period: 6 years after the end of the financial year they relate to\n  text: 6 years after the end of the financial year they relate to, as UK tax law requires\n- scope: Web server, load balancer and CDN logs\n  period: 30 days\n  text: Web server, load balancer and CDN logs 30 days\n- scope: Support emails\n  period: 12 months\n  text: Support emails 12 months\n- scope: Backups\n  period: 30 days\n  text: Backups 30 days\nresidency:\n- region: United Kingdom and Finland\n  text: Our servers are in\
  \ the United Kingdom and Finland.\ntransfers:\n- mechanism: adequacy\n  text: we rely on an adequacy decision (including the UK-US data bridge for certified US companies)\n- mechanism: other\n  text: the UK International Data Transfer Agreement or Addendum and the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: We use the following service providers, each under a written contract that requires them to protect your\n    data and use it only on our instructions\ndpa:\n  available: true\n  url: null\n  text: You can sign a copy of the DPA in your dashboard under My Account, DPA .\ndeletion:\n  route: Email support@weatherapi.com\n  text: Requests are free and we answer within one month. Email support@weatherapi.com\nrights:\n- right: access\n  text: access your personal data\n- right: correction\n  text: have inaccurate data corrected\n- right: deletion\n  text: have your data deleted\n- right: restriction or objection\n  text: restrict or object to our processing (including\
  \ at any time to direct marketing)\n- right: portability\n  text: receive your data in a portable format\n- right: withdraw consent\n  text: withdraw consent where we rely on it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data\n"
source_yaml_url: https://artifacts.apis.io/weatherapi/privacy/weatherapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from WeatherAPI's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Forecast
- History
- Marine
- Astronomy
- Geolocation
- Sports
- Alerts
- Public APIs
---
