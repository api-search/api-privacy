---
api_specs:
- filename: tracetail-io-identification-api-openapi.yml
  format: yaml
  label: tracetail-io Identification API
  slug: tracetail-io-identification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-identification-api-openapi.yml
- filename: tracetail-io-server-api-api-openapi.yml
  format: yaml
  label: tracetail-io Server API
  slug: tracetail-io-server-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-server-api-api-openapi.yml
- filename: tracetail-io-service-api-openapi.yml
  format: yaml
  label: tracetail-io Service API
  slug: tracetail-io-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-service-api-openapi.yml
- filename: tracetail-io-setup-links-api-openapi.yml
  format: yaml
  label: tracetail-io Setup links API
  slug: tracetail-io-setup-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tracetail-io/openapi/tracetail-io-setup-links-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: device
    text: the SDK reads characteristics of your browser and device
  - category: identifying
    text: Our servers also record your IP address and your browser's user agent.
  - category: contact
    text: we collect your email address and use it to send you sign-in codes and service emails
  - category: financial
    text: we keep your Stripe customer ID, your subscription status and records of your usage and charges
  - category: behavioral
    text: Clarity records page views, clicks, scrolling and mouse movement
  deletion:
    route: Account Settings, or contact the website operator for visitor data
    text: You can delete your account, with its API keys, visitor data and request history, from Settings at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fraud and abuse prevention for operator
    text: which they typically use to prevent fraud and abuse
  - purpose: Billing
    text: to bill them for usage
  - purpose: Website analytics
    text: to understand how people use the TraceTail website
  - purpose: Service protection
    text: to protect the service from abuse
  retention:
  - period: 180 days
    scope: Visitor record
    text: Your visitor record (the visitor ID, the characteristics, your IP address and user agent) is deleted 180 days after your last visit to that website.
  - period: 90 days
    scope: API request logs
    text: Logs of individual API requests are deleted after 90 days.
  - period: while your account is open
    scope: Account data
    text: We keep account data while your account is open.
  - period: as long as tax and accounting law requires
    scope: Stripe invoices
    text: Stripe keeps invoices for as long as tax and accounting law requires.
  rights:
  - right: Access, correction and deletion
    text: you may have the right to access, correct or delete your personal data
  - right: Withdraw consent
    text: to withdraw consent at any time
  - right: Complain to authority
    text: You also have the right to complain to your local data protection authority.
  role:
    text: TraceTail processes the data on their behalf as their processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information.
  subprocessors:
    text: Who processes data for us
    url: null
  transfers:
  - mechanism: other
    text: Our providers operate worldwide, so your data may be processed outside your country, including in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tracetail-io
provenance_date: '2026-11-10'
provider_name: tracetail-io
provider_slug: tracetail-io
slug: tracetail-io-privacy-policy
source_date: '2026-11-10'
source_filename: tracetail-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tracetail.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tracetail-io\naid: tracetail-io\nurl: https://tracetail.io/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: TraceTail processes the data on their behalf as their processor\ndata_categories:\n- category: device\n  text: the SDK reads characteristics of your browser and device\n- category: identifying\n  text: Our servers also record your IP address and your browser's user agent.\n- category: contact\n  text: we collect your email address and use it to send you sign-in codes and service emails\n- category: financial\n  text: we keep your Stripe customer ID, your subscription status and\
  \ records of your usage and charges\n- category: behavioral\n  text: Clarity records page views, clicks, scrolling and mouse movement\npurposes:\n- purpose: Fraud and abuse prevention for operator\n  text: which they typically use to prevent fraud and abuse\n- purpose: Billing\n  text: to bill them for usage\n- purpose: Website analytics\n  text: to understand how people use the TraceTail website\n- purpose: Service protection\n  text: to protect the service from abuse\nretention:\n- scope: Visitor record\n  period: 180 days\n  text: Your visitor record (the visitor ID, the characteristics, your IP address and user agent) is deleted 180\n    days after your last visit to that website.\n- scope: API request logs\n  period: 90 days\n  text: Logs of individual API requests are deleted after 90 days.\n- scope: Account data\n  period: while your account is open\n  text: We keep account data while your account is open.\n- scope: Stripe invoices\n  period: as long as tax and accounting law requires\n\
  \  text: Stripe keeps invoices for as long as tax and accounting law requires.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our providers operate worldwide, so your data may be processed outside your country, including in the United\n    States.\nsubprocessors:\n  url: null\n  text: Who processes data for us\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account Settings, or contact the website operator for visitor data\n  text: You can delete your account, with its API keys, visitor data and request history, from Settings at any time.\nrights:\n- right: Access, correction and deletion\n  text: you may have the right to access, correct or delete your personal data\n- right: Withdraw consent\n  text: to withdraw consent at any time\n- right: Complain to authority\n  text: You also have the right to complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/tracetail-io/privacy/tracetail-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from tracetail-io's own page on 2026-11-10.
synthetic: false
tags:
- Browser Fingerprinting
- Privacy
- Analytics
- Device Identification
---
