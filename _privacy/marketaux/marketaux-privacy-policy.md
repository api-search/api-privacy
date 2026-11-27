---
api_specs:
- filename: marketaux-entities-api-openapi.yml
  format: yaml
  label: MarketAux Entities API
  slug: marketaux-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketaux/openapi/marketaux-entities-api-openapi.yml
- filename: marketaux-news-api-openapi.yml
  format: yaml
  label: MarketAux News API
  slug: marketaux-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketaux/openapi/marketaux-news-api-openapi.yml
- filename: marketaux-sources-api-openapi.yml
  format: yaml
  label: MarketAux Sources API
  slug: marketaux-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketaux/openapi/marketaux-sources-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect your first and last name, email address, postal address, phone number, and other similar contact data.
  - category: identifying
    text: Credentials. We collect passwords, password hints, and similar security information used for authentication and account access.
  - category: financial
    text: Payment Data. We collect data necessary to process your payment if you make purchases, such as your payment instrument number (such as a credit card number), and the security code associated with your payment instrument.
  - category: device
    text: device and usage information, such as your IP address, browser and device characteristics, operating system, language preferences, referring URLs, device name, country, location
  - category: behavioral
    text: information about how and when you use our Sites and other technical information
  deletion:
    route: Request via account dashboard or contact email
    text: 'To request to review, update, or delete your personal information, please visit: https://www.marketaux.com/account/dashboard .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and logon
    text: To facilitate account creation and logon process.
  - purpose: marketing communications
    text: To send you marketing and promotional communications.
  - purpose: fulfill orders
    text: Fulfill and manage your orders.
  - purpose: testimonials
    text: To post testimonials.
  - purpose: legal requests and harm prevention
    text: To respond to legal requests and prevent harm.
  - purpose: analytics and improvement
    text: For other Business Purposes. We may use your information for other Business Purposes, such as data analysis, identifying usage trends, determining the effectiveness of our promotional campaigns and to evaluate and improve our Sites , products, services, marketing and your experience.
  retention:
  - period: null
    scope: personal information
    text: We will only keep your personal information for as long as it is necessary for the purposes set out in this privacy policy, unless a longer retention period is required or permitted by law (such as tax, accounting or other legal requirements).
  - period: null
    scope: account data
    text: No purpose in this policy will require us keeping your personal information for longer than the period of time in which users have an account with us .
  rights:
  - right: access
    text: to request access and obtain a copy of your personal information
  - right: rectification or erasure
    text: to request rectification or erasure;
  - right: restriction
    text: to restrict the processing of your personal information
  - right: portability
    text: if applicable, to data portability
  - right: objection
    text: the right to object to the processing of your personal information
  - right: withdraw consent
    text: you have the right to withdraw your consent at any time
  - right: complain to supervisory authority
    text: you also have the right to complain to your local data protection supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Unless described in this Policy, we do not share, sell, rent or trade any of your information with third parties for their promotional purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MarketAux
provenance_date: '2026-11-10'
provider_name: MarketAux
provider_slug: marketaux
slug: marketaux-privacy-policy
source_date: '2026-11-10'
source_filename: marketaux-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.marketaux.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MarketAux\naid: marketaux\nurl: https://www.marketaux.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We collect your first and last name, email address, postal address, phone number, and other similar contact\n    data.\n- category: identifying\n  text: Credentials. We collect passwords, password hints, and similar security information used for authentication\n    and account access.\n- category: financial\n  text: Payment Data. We collect data necessary to process your payment if you make purchases, such as your payment\n    instrument\
  \ number (such as a credit card number), and the security code associated with your payment instrument.\n- category: device\n  text: device and usage information, such as your IP address, browser and device characteristics, operating system,\n    language preferences, referring URLs, device name, country, location\n- category: behavioral\n  text: information about how and when you use our Sites and other technical information\npurposes:\n- purpose: account creation and logon\n  text: To facilitate account creation and logon process.\n- purpose: marketing communications\n  text: To send you marketing and promotional communications.\n- purpose: fulfill orders\n  text: Fulfill and manage your orders.\n- purpose: testimonials\n  text: To post testimonials.\n- purpose: legal requests and harm prevention\n  text: To respond to legal requests and prevent harm.\n- purpose: analytics and improvement\n  text: For other Business Purposes. We may use your information for other Business Purposes, such\
  \ as data analysis,\n    identifying usage trends, determining the effectiveness of our promotional campaigns and to evaluate and improve\n    our Sites , products, services, marketing and your experience.\nretention:\n- scope: personal information\n  period: null\n  text: We will only keep your personal information for as long as it is necessary for the purposes set out in this\n    privacy policy, unless a longer retention period is required or permitted by law (such as tax, accounting or\n    other legal requirements).\n- scope: account data\n  period: null\n  text: No purpose in this policy will require us keeping your personal information for longer than the period of\n    time in which users have an account with us .\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via account dashboard or contact email\n  text: 'To request to review, update, or delete your personal information,\
  \ please visit: https://www.marketaux.com/account/dashboard\n    .'\nrights:\n- right: access\n  text: to request access and obtain a copy of your personal information\n- right: rectification or erasure\n  text: to request rectification or erasure;\n- right: restriction\n  text: to restrict the processing of your personal information\n- right: portability\n  text: if applicable, to data portability\n- right: objection\n  text: the right to object to the processing of your personal information\n- right: withdraw consent\n  text: you have the right to withdraw your consent at any time\n- right: complain to supervisory authority\n  text: you also have the right to complain to your local data protection supervisory authority\nsale_or_sharing:\n  stance: conditional\n  text: Unless described in this Policy, we do not share, sell, rent or trade any of your information with third\n    parties for their promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/marketaux/privacy/marketaux-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from MarketAux's own page on 2026-11-10.
synthetic: false
tags:
- News
- Financial News
- Stock Market
- Sentiment Analysis
- Market Data
- Entity Recognition
- Public APIs
---
