---
api_specs:
- filename: backquant-com-api-openapi.json
  format: json
  label: BackQuant API v2 API
  slug: backquant-api-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backquant-com/openapi/_original/backquant-com-api-openapi.json
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your email address and basic profile information.
  - category: device
    text: Each event carries a timestamp, a session identifier generated in your browser, the app version, and a small set of categorical or numeric properties
  - category: financial
    text: We only receive confirmation of successful transactions, the last four digits of the card, and basic billing information.
  - category: location
    text: we automatically collect limited technical information, including your IP address and a payment-method fingerprint provided by our payment processor.
  deletion:
    route: Email admin@backquant.com
    text: Request deletion of your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and improve the service
    text: We collect anonymous usage telemetry to understand how the terminal is used in aggregate, debug failures, and prioritise what to build next.
  - purpose: Fraud prevention
    text: We use this solely to detect and prevent fraud and abuse, such as repeated free-trial signups from the same person or payment method.
  - purpose: Process transactions and manage subscription
    text: Process transactions and manage your subscription
  retention:
  - period: 365 days
    scope: Telemetry events
    text: Telemetry events are stored on BackQuant infrastructure and are automatically deleted after 365 days.
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correction
    text: Request correction of inaccurate information
  - right: Deletion
    text: Request deletion of your account and associated data
  - right: Withdraw consent
    text: Withdraw consent for optional data processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data under any circumstances.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BackQuant
provenance_date: '2026-11-09'
provider_name: BackQuant
provider_slug: backquant-com
slug: backquant-com-privacy-policy
source_date: '2026-11-09'
source_filename: backquant-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.backquant.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BackQuant\naid: backquant-com\nurl: https://www.backquant.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your email address and basic profile information.\n- category: device\n  text: Each event carries a timestamp, a session identifier generated in your browser, the app version, and a small\n    set of categorical or numeric properties\n- category: financial\n  text: We only receive confirmation of successful transactions, the last four digits of the card, and basic billing\n    information.\n\
  - category: location\n  text: we automatically collect limited technical information, including your IP address and a payment-method fingerprint\n    provided by our payment processor.\npurposes:\n- purpose: Operate and improve the service\n  text: We collect anonymous usage telemetry to understand how the terminal is used in aggregate, debug failures,\n    and prioritise what to build next.\n- purpose: Fraud prevention\n  text: We use this solely to detect and prevent fraud and abuse, such as repeated free-trial signups from the same\n    person or payment method.\n- purpose: Process transactions and manage subscription\n  text: Process transactions and manage your subscription\nretention:\n- scope: Telemetry events\n  period: 365 days\n  text: Telemetry events are stored on BackQuant infrastructure and are automatically deleted after 365 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ Email admin@backquant.com\n  text: Request deletion of your account and associated data\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correction\n  text: Request correction of inaccurate information\n- right: Deletion\n  text: Request deletion of your account and associated data\n- right: Withdraw consent\n  text: Withdraw consent for optional data processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data under any circumstances.\n"
source_yaml_url: https://artifacts.apis.io/backquant-com/privacy/backquant-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from BackQuant's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Options
- Cryptocurrency
- Analytics
---
