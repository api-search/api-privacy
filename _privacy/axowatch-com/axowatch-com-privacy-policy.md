---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: When an account is created we store your name, email address and password.
  - category: financial
    text: Your name, email address, billing address and card details. The card goes to Stripe directly, and we never see its full number.
  - category: location
    text: approximate location (country and city, worked out from the IP address)
  - category: device
    text: their device, browser and approximate location
  - category: behavioral
    text: which pages they open, where they came from, their device, browser and approximate location
  - category: communication
    text: messages you write in the flow chat
  deletion:
    route: Ask by email, or delete flows, checks and projects in the app
    text: You can ask us for a copy of your data or to delete it at any time.
  dpa:
    available: true
    text: If you need a data processing agreement, write to us.
    url: null
  purposes:
  - purpose: Provide the service
    text: to run your checks and flows, show you the results, alert you when something breaks, help you fix it, take payments, keep your account secure, and answer you when you write to us
  - purpose: Advertising measurement
    text: Meta Pixel (Facebook and Instagram) to measure which of our ads lead to sign-ups and purchases
  - purpose: Website analytics
    text: Google Analytics to understand how people find and use our website
  residency:
  - region: United States and other countries
    text: the services above store and process data in the United States and other countries
  retention:
  - period: Until you delete them in the app or ask us to delete your account
    scope: Account, projects and checks
    text: Until you delete them in the app or ask us to delete your account
  - period: 30 days by default
    scope: Raw uptime results
    text: Raw uptime results 30 days by default; you can choose 7, 90 or 400 days
  - period: 30 days
    scope: Error reports
    text: Error reports 30 days, deleted in weekly batches, so at most 37
  - period: 14 months
    scope: Google Analytics data
    text: Google Analytics data 14 months
  - period: 6 years
    scope: Payment records and invoices
    text: As long as tax and accounting law requires (in Canada, 6 years)
  rights:
  - right: Access
    text: Ask us at privacy@axowatch.com for a copy of your data
  - right: Correction
    text: to correct it
  - right: Objection
    text: or to object to how we use it
  - right: Complaint
    text: you can complain to the Office of the Privacy Commissioner of Canada
  role:
    text: We are responsible for the personal data described here.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do this only if you accept advertising cookies, and you can opt out at any time under Cookie settings or with Global Privacy Control.
  subprocessors:
    text: We use a small number of services to run AxoWatch. Each gets only what its job needs
    url: null
  transfers:
  - mechanism: other
    text: Data processed there is protected by our agreements with these services, but it is subject to the laws of those countries
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AxoWatch
provenance_date: '2026-11-09'
provider_name: AxoWatch
provider_slug: axowatch-com
slug: axowatch-com-privacy-policy
source_date: '2026-11-09'
source_filename: axowatch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://axowatch.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AxoWatch\naid: axowatch-com\nurl: https://axowatch.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are responsible for the personal data described here.\ndata_categories:\n- category: identifying\n  text: When an account is created we store your name, email address and password.\n- category: financial\n  text: Your name, email address, billing address and card details. The card goes to Stripe directly, and we never\n    see its full number.\n- category: location\n  text: approximate location (country and city, worked out from the IP address)\n- category: device\n  text: their device,\
  \ browser and approximate location\n- category: behavioral\n  text: which pages they open, where they came from, their device, browser and approximate location\n- category: communication\n  text: messages you write in the flow chat\npurposes:\n- purpose: Provide the service\n  text: to run your checks and flows, show you the results, alert you when something breaks, help you fix it, take\n    payments, keep your account secure, and answer you when you write to us\n- purpose: Advertising measurement\n  text: Meta Pixel (Facebook and Instagram) to measure which of our ads lead to sign-ups and purchases\n- purpose: Website analytics\n  text: Google Analytics to understand how people find and use our website\nretention:\n- scope: Account, projects and checks\n  period: Until you delete them in the app or ask us to delete your account\n  text: Until you delete them in the app or ask us to delete your account\n- scope: Raw uptime results\n  period: 30 days by default\n  text: Raw uptime results\
  \ 30 days by default; you can choose 7, 90 or 400 days\n- scope: Error reports\n  period: 30 days\n  text: Error reports 30 days, deleted in weekly batches, so at most 37\n- scope: Google Analytics data\n  period: 14 months\n  text: Google Analytics data 14 months\n- scope: Payment records and invoices\n  period: 6 years\n  text: As long as tax and accounting law requires (in Canada, 6 years)\nresidency:\n- region: United States and other countries\n  text: the services above store and process data in the United States and other countries\ntransfers:\n- mechanism: other\n  text: Data processed there is protected by our agreements with these services, but it is subject to the laws of\n    those countries\nsubprocessors:\n  url: null\n  text: We use a small number of services to run AxoWatch. Each gets only what its job needs\ndpa:\n  available: true\n  url: null\n  text: If you need a data processing agreement, write to us.\ndeletion:\n  route: Ask by email, or delete flows, checks and\
  \ projects in the app\n  text: You can ask us for a copy of your data or to delete it at any time.\nrights:\n- right: Access\n  text: Ask us at privacy@axowatch.com for a copy of your data\n- right: Correction\n  text: to correct it\n- right: Objection\n  text: or to object to how we use it\n- right: Complaint\n  text: you can complain to the Office of the Privacy Commissioner of Canada\nsale_or_sharing:\n  stance: conditional\n  text: We do this only if you accept advertising cookies, and you can opt out at any time under Cookie settings\n    or with Global Privacy Control.\n"
source_yaml_url: https://artifacts.apis.io/axowatch-com/privacy/axowatch-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from AxoWatch's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Uptime
- Performance
- Error Tracking
- Artificial Intelligence
- Software-as-a-Service
---
