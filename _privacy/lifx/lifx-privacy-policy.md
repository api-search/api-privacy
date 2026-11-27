---
api_specs:
- filename: lifx-color-api-openapi.yml
  format: yaml
  label: LIFX Color API
  slug: lifx-color-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifx/openapi/lifx-color-api-openapi.yml
- filename: lifx-lights-api-openapi.yml
  format: yaml
  label: LIFX Lights API
  slug: lifx-lights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifx/openapi/lifx-lights-api-openapi.yml
- filename: lifx-scenes-api-openapi.yml
  format: yaml
  label: LIFX Scenes API
  slug: lifx-scenes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifx/openapi/lifx-scenes-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact details including name, postal address (billing and shipping), email address, and telephone number.
  - category: financial
    text: Financial information , such as payment card number, expiration date, CVV, and billing address.
  - category: location
    text: Location data , which includes approximate location inferred from IP address.
  - category: behavioral
    text: Usage data , including pages visited, links clicked, search queries entered on our sites, time and duration of visits, referrer URLs, and shopping cart activity.
  - category: device
    text: Device information including information about your electronic device, browser, or network connection, your IP address, and other unique identifiers.
  - category: communication
    text: Communications with Feit , including contents of messages, emails, chat logs, and support tickets you send to us.
  - category: identifying
    text: Account credentials including username, passwords, and security question responses.
  deletion:
    route: request to contact the company using the details in Section 10
    text: You may have a right to request that we delete personal information we maintain about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: order fulfilment and payments
    text: fulfilling orders and processing payments
  - purpose: personalized advertising
    text: displaying personalized advertisements on our websites and on third-party platforms based on your activity and preferences
  - purpose: security and fraud prevention
    text: detecting, investigating, and preventing fraudulent transactions and unauthorized access
  retention:
  - period: null
    scope: general
    text: How long we retain your personal information depends on different factors, such as whether we need the information to maintain your account, to provide you with Services, comply with legal obligations, resolve disputes or enforce other applicable contracts and policies.
  rights:
  - right: access / know
    text: You may have a right to request access to personal information that we hold about you.
  - right: delete
    text: You may have a right to request that we delete personal information we maintain about you.
  - right: correct
    text: You may have a right to request that we correct inaccurate personal information we maintain about you.
  - right: portability
    text: You may have a right to receive a copy of the personal information we hold about you
  - right: opt out of sale, sharing or targeted advertising
    text: You can exercise your rights to opt out of those uses here
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: You can exercise your rights to opt out of those uses here
  subprocessors:
    text: 'We engage vendors and contractors who process personal information on our behalf, including: e-commerce and payment processing (Shopify, Stripe); cloud storage and hosting (Amazon Web Services, Google Cloud, Tuya Smart for IoT infrastructure)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LIFX
provenance_date: '2026-11-09'
provider_name: LIFX
provider_slug: lifx
slug: lifx-privacy-policy
source_date: '2026-11-09'
source_filename: lifx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.lifx.com/policies/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LIFX\naid: lifx\nurl: https://www.lifx.com/policies/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact details including name, postal address (billing and shipping), email address, and telephone number.\n- category: financial\n  text: Financial information , such as payment card number, expiration date, CVV, and billing address.\n- category: location\n  text: Location data , which includes approximate location inferred from IP address.\n- category: behavioral\n  text: Usage data , including pages visited, links clicked,\
  \ search queries entered on our sites, time and duration\n    of visits, referrer URLs, and shopping cart activity.\n- category: device\n  text: Device information including information about your electronic device, browser, or network connection, your\n    IP address, and other unique identifiers.\n- category: communication\n  text: Communications with Feit , including contents of messages, emails, chat logs, and support tickets you send\n    to us.\n- category: identifying\n  text: Account credentials including username, passwords, and security question responses.\npurposes:\n- purpose: order fulfilment and payments\n  text: fulfilling orders and processing payments\n- purpose: personalized advertising\n  text: displaying personalized advertisements on our websites and on third-party platforms based on your activity\n    and preferences\n- purpose: security and fraud prevention\n  text: detecting, investigating, and preventing fraudulent transactions and unauthorized access\nretention:\n\
  - scope: general\n  period: null\n  text: How long we retain your personal information depends on different factors, such as whether we need the information\n    to maintain your account, to provide you with Services, comply with legal obligations, resolve disputes or enforce\n    other applicable contracts and policies.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We engage vendors and contractors who process personal information on our behalf, including: e-commerce\n    and payment processing (Shopify, Stripe); cloud storage and hosting (Amazon Web Services, Google Cloud, Tuya\n    Smart for IoT infrastructure)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to contact the company using the details in Section 10\n  text: You may have a right to request that we delete personal information we maintain about you.\nrights:\n- right: access / know\n  text: You may have a right to request access to personal information that we hold\
  \ about you.\n- right: delete\n  text: You may have a right to request that we delete personal information we maintain about you.\n- right: correct\n  text: You may have a right to request that we correct inaccurate personal information we maintain about you.\n- right: portability\n  text: You may have a right to receive a copy of the personal information we hold about you\n- right: opt out of sale, sharing or targeted advertising\n  text: You can exercise your rights to opt out of those uses here\nsale_or_sharing:\n  stance: conditional\n  text: You can exercise your rights to opt out of those uses here\n"
source_yaml_url: https://artifacts.apis.io/lifx/privacy/lifx-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from LIFX's own page on 2026-11-09.
synthetic: false
tags:
- Smart Lighting
- Wi‑Fi Bulbs
- Home Automation
- Lighting Fixtures
---
