---
api_specs:
- filename: markovo-net-openapi.yml
  format: yaml
  label: Markovo Conversion API
  slug: markovo-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/markovo-net/openapi/markovo-net-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: authentication identifiers from Google or GitHub when you choose social sign-in
  - category: contact
    text: A feedback report includes the email address and problem description you enter
  - category: financial
    text: When you create or complete a payment, Markovo shares only the minimum necessary billing identifiers, subscription and refund events, amounts, currency, and your account email
  - category: behavioral
    text: It may record page views, clicks, scrolling, mouse movement, browser and device information, approximate region, and the name of a file you pick in a page's upload control.
  - category: device
    text: Google Analytics may process the page path and title, time of visit, referrer, browser and device information, language, and approximate region
  - category: other
    text: the files you submit for conversion
  deletion:
    route: in-app deletion of conversion jobs
    text: You can delete an owned job earlier from the app.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account authentication and service delivery
    text: We use data to authenticate accounts, deliver conversions, prevent abuse, meter Credits, provide support, secure the service, and understand aggregate product reliability.
  - purpose: website analytics
    text: We use Cloudflare Web Analytics and Google Analytics 4 to understand visits and improve the website.
  - purpose: checkout recovery
    text: We share your account email with Creem at checkout so it can send reminders that return you to an unfinished Checkout.
  retention:
  - period: 1 hour
    scope: conversion results for anonymous and Free use
    text: Conversion results expire after 1 hour for anonymous and Free use, 7 days for Starter, and 30 days for Pro.
  - period: 7 days
    scope: conversion results for Starter
    text: Conversion results expire after 1 hour for anonymous and Free use, 7 days for Starter, and 30 days for Pro.
  - period: 30 days
    scope: conversion results for Pro
    text: Conversion results expire after 1 hour for anonymous and Free use, 7 days for Starter, and 30 days for Pro.
  - period: 90 days
    scope: feedback reports and screenshots
    text: Feedback reports and optional screenshots are kept for up to 90 days so we can investigate the report; you may request earlier deletion.
  - period: null
    scope: working copies of source files
    text: Working copies of source files are used for the requested conversion and deleted after processing.
  rights:
  - right: access, correction, export, or deletion
    text: request access, correction, export, or deletion of account data
  - right: opt out of checkout recovery reminders
    text: Checkout recovery reminders are sent only after an unfinished signed-in checkout; you may ignore or delete them, or contact support to opt out.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare provides edge compute, storage, queues, databases, aggregate web analytics, and Workers AI.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: markovo-net
provenance_date: '2026-11-10'
provider_name: markovo-net
provider_slug: markovo-net
slug: markovo-net-privacy-policy
source_date: '2026-11-10'
source_filename: markovo-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://markovo.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: markovo-net\naid: markovo-net\nurl: https://markovo.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: authentication identifiers from Google or GitHub when you choose social sign-in\n- category: contact\n  text: A feedback report includes the email address and problem description you enter\n- category: financial\n  text: When you create or complete a payment, Markovo shares only the minimum necessary billing identifiers, subscription\n    and refund events, amounts, currency, and your account email\n- category: behavioral\n  text:\
  \ It may record page views, clicks, scrolling, mouse movement, browser and device information, approximate\n    region, and the name of a file you pick in a page's upload control.\n- category: device\n  text: Google Analytics may process the page path and title, time of visit, referrer, browser and device information,\n    language, and approximate region\n- category: other\n  text: the files you submit for conversion\npurposes:\n- purpose: account authentication and service delivery\n  text: We use data to authenticate accounts, deliver conversions, prevent abuse, meter Credits, provide support,\n    secure the service, and understand aggregate product reliability.\n- purpose: website analytics\n  text: We use Cloudflare Web Analytics and Google Analytics 4 to understand visits and improve the website.\n- purpose: checkout recovery\n  text: We share your account email with Creem at checkout so it can send reminders that return you to an unfinished\n    Checkout.\nretention:\n- scope:\
  \ conversion results for anonymous and Free use\n  period: 1 hour\n  text: Conversion results expire after 1 hour for anonymous and Free use, 7 days for Starter, and 30 days for Pro.\n- scope: conversion results for Starter\n  period: 7 days\n  text: Conversion results expire after 1 hour for anonymous and Free use, 7 days for Starter, and 30 days for Pro.\n- scope: conversion results for Pro\n  period: 30 days\n  text: Conversion results expire after 1 hour for anonymous and Free use, 7 days for Starter, and 30 days for Pro.\n- scope: feedback reports and screenshots\n  period: 90 days\n  text: Feedback reports and optional screenshots are kept for up to 90 days so we can investigate the report; you\n    may request earlier deletion.\n- scope: working copies of source files\n  period: null\n  text: Working copies of source files are used for the requested conversion and deleted after processing.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare provides edge\
  \ compute, storage, queues, databases, aggregate web analytics, and Workers AI.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app deletion of conversion jobs\n  text: You can delete an owned job earlier from the app.\nrights:\n- right: access, correction, export, or deletion\n  text: request access, correction, export, or deletion of account data\n- right: opt out of checkout recovery reminders\n  text: Checkout recovery reminders are sent only after an unfinished signed-in checkout; you may ignore or delete\n    them, or contact support to opt out.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/markovo-net/privacy/markovo-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from markovo-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- File Conversion
- Text Processing
- Software-as-a-Service
- Productivity
---
