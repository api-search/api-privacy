---
api_specs:
- filename: scrapingbot-io-openapi-generated.yml
  format: yaml
  label: scrapingbot-io API
  slug: scrapingbot-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingbot-io/openapi/_ae-authored/scrapingbot-io-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address you give us when you sign up
  - category: financial
    text: We keep the card brand, last four digits and expiry date Stripe gives us
  - category: location
    text: We store your approximate location (city, region, country) worked out from your IP address, not the address itself.
  - category: behavioral
    text: Our pages record page views, clicks, scrolling, performance timings and errors
  - category: device
    text: your IP address and browser user agent at sign-up
  - category: communication
    text: If you write to us by email or through the chat on the site, we keep the conversation so we can help you.
  deletion:
    route: Email from your account's email address
    text: to close your account and delete it
  dpa:
    available: true
    text: If you need a data processing agreement for that role, email us.
    url: null
  purposes:
  - purpose: run account and API
    text: To run the API, the dashboard and your account, and to charge the right amount.
  - purpose: security and fraud prevention
    text: To keep the service secure and stop fraud and abuse.
  - purpose: analytics and improvement
    text: To understand which pages, ads and features work, and to fix what doesn’t.
  residency:
  - region: United States and other countries
    text: We and our providers may process data in the United States and other countries
  retention:
  - period: 400 days
    scope: API usage logs
    text: 'API usage logs: 400 days.'
  - period: 24 hours
    scope: Request results
    text: 'Request results: 24 hours.'
  - period: 14 days
    scope: Session recordings
    text: 'Session recordings: 14 days.'
  - period: 180 days
    scope: Website analytics events
    text: 'Website analytics events: 180 days.'
  - period: 1 day (sign-ups) or 7 days (free tools)
    scope: Hashed IP addresses
    text: 'Hashed IP addresses: 1 day (sign-ups) or 7 days (free tools).'
  rights:
  - right: access and copy
    text: to ask for a copy of your data, to correct it, or to close your account and delete it
  - right: object or restrict processing
    text: such as to object to or restrict some processing
  - right: complain to authority
    text: or to complain to your data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal information
  subprocessors:
    text: Stripe , for payments and invoices.
    url: null
  transfers:
  - mechanism: SCC
    text: where the law requires, transfers rely on safeguards such as the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: scrapingbot-io
provenance_date: '2026-11-10'
provider_name: scrapingbot-io
provider_slug: scrapingbot-io
slug: scrapingbot-io-privacy-policy
source_date: '2026-11-10'
source_filename: scrapingbot-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scrapingbot.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: scrapingbot-io\naid: scrapingbot-io\nurl: https://scrapingbot.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and email address you give us when you sign up\n- category: financial\n  text: We keep the card brand, last four digits and expiry date Stripe gives us\n- category: location\n  text: We store your approximate location (city, region, country) worked out from your IP address, not the address\n    itself.\n- category: behavioral\n  text: Our pages record page views, clicks, scrolling, performance timings and errors\n\
  - category: device\n  text: your IP address and browser user agent at sign-up\n- category: communication\n  text: If you write to us by email or through the chat on the site, we keep the conversation so we can help you.\npurposes:\n- purpose: run account and API\n  text: To run the API, the dashboard and your account, and to charge the right amount.\n- purpose: security and fraud prevention\n  text: To keep the service secure and stop fraud and abuse.\n- purpose: analytics and improvement\n  text: To understand which pages, ads and features work, and to fix what doesn’t.\nretention:\n- scope: API usage logs\n  period: 400 days\n  text: 'API usage logs: 400 days.'\n- scope: Request results\n  period: 24 hours\n  text: 'Request results: 24 hours.'\n- scope: Session recordings\n  period: 14 days\n  text: 'Session recordings: 14 days.'\n- scope: Website analytics events\n  period: 180 days\n  text: 'Website analytics events: 180 days.'\n- scope: Hashed IP addresses\n  period: 1 day (sign-ups)\
  \ or 7 days (free tools)\n  text: 'Hashed IP addresses: 1 day (sign-ups) or 7 days (free tools).'\nresidency:\n- region: United States and other countries\n  text: We and our providers may process data in the United States and other countries\ntransfers:\n- mechanism: SCC\n  text: where the law requires, transfers rely on safeguards such as the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: Stripe , for payments and invoices.\ndpa:\n  available: true\n  url: null\n  text: If you need a data processing agreement for that role, email us.\ndeletion:\n  route: Email from your account's email address\n  text: to close your account and delete it\nrights:\n- right: access and copy\n  text: to ask for a copy of your data, to correct it, or to close your account and delete it\n- right: object or restrict processing\n  text: such as to object to or restrict some processing\n- right: complain to authority\n  text: or to complain to your data protection authority\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We don’t sell personal information\n"
source_yaml_url: https://artifacts.apis.io/scrapingbot-io/privacy/scrapingbot-io-privacy-policy.yml
stated_fields:
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
summary_line: 23 quoted statements, read from scrapingbot-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Artificial Intelligence
- Data Extraction
- Automation
---
