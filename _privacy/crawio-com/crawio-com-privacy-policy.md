---
api_specs:
- filename: crawio-com-openapi-generated.yml
  format: yaml
  label: crawio-com API
  slug: crawio-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawio-com/openapi/_ae-authored/crawio-com-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : email address, optional company/project name, and a hashed password'
  - category: device
    text: 'Security logs : IP addresses and rate-limit counters for abuse prevention, kept short-term.'
  - category: behavioral
    text: 'Website analytics : Cloudflare Web Analytics counts page views and page load times on our website, without cookies and without tracking you across sites.'
  - category: communication
    text: 'Support data : tickets you open, including messages and images you attach.'
  - category: financial
    text: 'Billing data : handled by Paddle.com, our merchant of record, when you buy a paid plan; we never see or store full card numbers.'
  deletion:
    route: Delete your account from the Account tab in the dashboard
    text: delete your account from the Account tab.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service
    text: 'To provide the Service you signed up for: accounts, dashboards, quota, and support (contract).'
  - purpose: security and abuse prevention
    text: To secure the platform and prevent abuse (legitimate interest).
  - purpose: transactional email
    text: 'To send transactional email: verification, password resets, quota alerts, ticket replies (contract).'
  - purpose: legal obligations
    text: To meet legal obligations, such as tax and accounting rules (legal obligation).
  retention:
  - period: for as long as your account exists
    scope: Account and usage data
    text: 'Account and usage data: for as long as your account exists.'
  - period: short-term, rolling
    scope: Security logs
    text: 'Security logs: short-term, rolling.'
  rights:
  - right: access and export
    text: You can access and export your usage data (CSV) and change your email or password in the dashboard
  - right: correct, delete, restrict, port
    text: Under GDPR/UK GDPR you also have the rights to access, correct, delete, restrict, and port your personal data, to object to processing, and to complain to your supervisory authority.
  role:
    text: you are the data controller and we act as your processor on your instructions
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not run ads.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crawio-com
provenance_date: '2026-11-09'
provider_name: crawio-com
provider_slug: crawio-com
slug: crawio-com-privacy-policy
source_date: '2026-11-09'
source_filename: crawio-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crawio.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crawio-com\naid: crawio-com\nurl: https://crawio.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: you are the data controller and we act as your processor on your instructions\ndata_categories:\n- category: identifying\n  text: 'Account data : email address, optional company/project name, and a hashed password'\n- category: device\n  text: 'Security logs : IP addresses and rate-limit counters for abuse prevention, kept short-term.'\n- category: behavioral\n  text: 'Website analytics : Cloudflare Web Analytics counts page views and page load times on our website, without\n    cookies and\
  \ without tracking you across sites.'\n- category: communication\n  text: 'Support data : tickets you open, including messages and images you attach.'\n- category: financial\n  text: 'Billing data : handled by Paddle.com, our merchant of record, when you buy a paid plan; we never see or\n    store full card numbers.'\npurposes:\n- purpose: provide the Service\n  text: 'To provide the Service you signed up for: accounts, dashboards, quota, and support (contract).'\n- purpose: security and abuse prevention\n  text: To secure the platform and prevent abuse (legitimate interest).\n- purpose: transactional email\n  text: 'To send transactional email: verification, password resets, quota alerts, ticket replies (contract).'\n- purpose: legal obligations\n  text: To meet legal obligations, such as tax and accounting rules (legal obligation).\nretention:\n- scope: Account and usage data\n  period: for as long as your account exists\n  text: 'Account and usage data: for as long as your account exists.'\n\
  - scope: Security logs\n  period: short-term, rolling\n  text: 'Security logs: short-term, rolling.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account from the Account tab in the dashboard\n  text: delete your account from the Account tab.\nrights:\n- right: access and export\n  text: You can access and export your usage data (CSV) and change your email or password in the dashboard\n- right: correct, delete, restrict, port\n  text: Under GDPR/UK GDPR you also have the rights to access, correct, delete, restrict, and port your personal\n    data, to object to processing, and to complain to your supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not run ads.\n"
source_yaml_url: https://artifacts.apis.io/crawio-com/privacy/crawio-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from crawio-com's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Proxy
- Anti-Bot
- Data Extraction
---
