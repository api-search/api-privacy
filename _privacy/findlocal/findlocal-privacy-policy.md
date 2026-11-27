---
api_specs:
- filename: findlocal-events-api-openapi.yml
  format: yaml
  label: FindLocal Events API
  slug: findlocal-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findlocal/openapi/findlocal-events-api-openapi.yml
- filename: findlocal-venues-api-openapi.yml
  format: yaml
  label: FindLocal Venues API
  slug: findlocal-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findlocal/openapi/findlocal-venues-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: device
    text: Your chosen city (a cookie named fl_city ) and any events you save are stored on your device using cookies and browser storage.
  - category: behavioral
    text: we set a cookie named fl_src holding the page you landed on, the website that referred you (its domain only) and any campaign tags in the link ( utm_* )
  - category: location
    text: '"Use my location" asks your browser for your position only when you press it, and sends it rounded to about 100 m as part of the search.'
  - category: device
    text: Our hosting provider (Cloudflare) automatically records standard technical information for security and reliability when you access the Service, such as IP address, browser type and pages requested.
  - category: communication
    text: If you email us, we receive whatever you choose to send.
  deletion:
    route: Delete developer account from dashboard
    text: 'If you hold a developer account you can delete it yourself, at any time, from your dashboard : that erases your email, sign-in methods, sessions, API keys and their usage history, and cancels any subscription.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: To provide, operate and maintain the Service (for example, showing events for your chosen city).
  - purpose: Security and reliability
    text: To keep the Service secure and reliable.
  - purpose: Aggregate usage understanding
    text: To understand aggregate usage (for example, page views by country) and improve the Service.
  - purpose: Account emails
    text: To email developer-account holders. Account emails (sign-in links, plan and billing changes) are part of the service.
  retention:
  - period: up to 90 days
    scope: API usage log
    text: This usage log is kept for up to 90 days.
  - period: up to 90 days
    scope: Widget usage data
    text: it is kept for up to 90 days.
  - period: 90 days and 1 day
    scope: First-party attribution cookies
    text: They expire after 90 days and 1 day
  - period: null
    scope: Stripe invoices
    text: Stripe retains past invoices for as long as tax law requires.
  rights:
  - right: Access, correct, delete, port, object or restrict
    text: Residents of California (CCPA) and data subjects in the European Economic Area (GDPR) have rights to access, correct, delete and port personal data, and to object to or restrict certain processing.
  - right: Clear cookies
    text: clear your browser's cookies and site data for findlocal.community to remove them.
  - right: Unsubscribe from optional emails
    text: Every optional email has an unsubscribe link, and both can be switched off on your account page .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FindLocal
provenance_date: '2026-11-09'
provider_name: FindLocal
provider_slug: findlocal
slug: findlocal-privacy-policy
source_date: '2026-11-09'
source_filename: findlocal-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://findlocal.community/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FindLocal\naid: findlocal\nurl: https://findlocal.community/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Your chosen city (a cookie named fl_city ) and any events you save are stored on your device using cookies\n    and browser storage.\n- category: behavioral\n  text: we set a cookie named fl_src holding the page you landed on, the website that referred you (its domain only)\n    and any campaign tags in the link ( utm_* )\n- category: location\n  text: '\"Use my location\" asks your browser for your position only when you press\
  \ it, and sends it rounded to about\n    100 m as part of the search.'\n- category: device\n  text: Our hosting provider (Cloudflare) automatically records standard technical information for security and\n    reliability when you access the Service, such as IP address, browser type and pages requested.\n- category: communication\n  text: If you email us, we receive whatever you choose to send.\npurposes:\n- purpose: Provide and operate the Service\n  text: To provide, operate and maintain the Service (for example, showing events for your chosen city).\n- purpose: Security and reliability\n  text: To keep the Service secure and reliable.\n- purpose: Aggregate usage understanding\n  text: To understand aggregate usage (for example, page views by country) and improve the Service.\n- purpose: Account emails\n  text: To email developer-account holders. Account emails (sign-in links, plan and billing changes) are part of\n    the service.\nretention:\n- scope: API usage log\n  period: up to\
  \ 90 days\n  text: This usage log is kept for up to 90 days.\n- scope: Widget usage data\n  period: up to 90 days\n  text: it is kept for up to 90 days.\n- scope: First-party attribution cookies\n  period: 90 days and 1 day\n  text: They expire after 90 days and 1 day\n- scope: Stripe invoices\n  period: null\n  text: Stripe retains past invoices for as long as tax law requires.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete developer account from dashboard\n  text: 'If you hold a developer account you can delete it yourself, at any time, from your dashboard : that erases\n    your email, sign-in methods, sessions, API keys and their usage history, and cancels any subscription.'\nrights:\n- right: Access, correct, delete, port, object or restrict\n  text: Residents of California (CCPA) and data subjects in the European Economic Area (GDPR) have rights to access,\n    correct, delete\
  \ and port personal data, and to object to or restrict certain processing.\n- right: Clear cookies\n  text: clear your browser's cookies and site data for findlocal.community to remove them.\n- right: Unsubscribe from optional emails\n  text: Every optional email has an unsubscribe link, and both can be switched off on your account page .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/findlocal/privacy/findlocal-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from FindLocal's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Hyperlocal
- Community
- Data
- Open Data
---
