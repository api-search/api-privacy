---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details (email, and any name you provide)
  - category: financial
    text: Payment metadata (via Coinbase / x402 or a card processor)
  - category: device
    text: API and request logs (request id, timestamp, endpoint, status, coarse IP/rate-limit signal)
  - category: financial
    text: 'x402 gauntlet receipts per settled POST /x402/v1/gauntlet payment: the payment nonce, paying wallet address, transaction id, input digest and cached response.'
  deletion:
    route: email hello@alphaassay.com to exercise erasure right
    text: To exercise any of these, email hello@alphaassay.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: create and secure account
    text: create and secure your account, send service messages
  - purpose: take payment and prevent abuse
    text: take payment and prevent abuse — we do not store card numbers
  - purpose: run the API and audit trail
    text: run the API, debug, enforce rate limits, keep an audit trail
  residency:
  - region: European Union (Germany)
    text: The Service runs on servers located in the European Union (Germany) .
  retention:
  - period: about 90 days
    scope: API and request logs
    text: Operational API and request logs are retained for about 90 days , then deleted or aggregated.
  - period: null
    scope: Account data
    text: Account data is kept while your account exists and for as long as needed to meet legal obligations.
  - period: null
    scope: Submitted signals and backtests
    text: 'retained per trial: a one-way fingerprint, the verdict with failure codes, summary statistics'
  rights:
  - right: access
    text: you can request access to your data
  - right: rectification
    text: rectification
  - right: erasure
    text: erasure
  - right: restriction
    text: restriction
  - right: portability
    text: portability
  - right: object
    text: you can object to processing based on legitimate interests
  - right: complain to supervisory authority
    text: lodge a complaint with a supervisory authority
  role:
    text: The controller is AlphaAssay , 6403 Küssnacht am Rigi, Switzerland
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data and do not share it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AlphaAssay
provenance_date: '2026-11-09'
provider_name: AlphaAssay
provider_slug: alphaassay-com
slug: alphaassay-com-privacy-policy
source_date: '2026-11-09'
source_filename: alphaassay-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alphaassay.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AlphaAssay\naid: alphaassay-com\nurl: https://alphaassay.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is AlphaAssay , 6403 Küssnacht am Rigi, Switzerland\ndata_categories:\n- category: identifying\n  text: Account details (email, and any name you provide)\n- category: financial\n  text: Payment metadata (via Coinbase / x402 or a card processor)\n- category: device\n  text: API and request logs (request id, timestamp, endpoint, status, coarse IP/rate-limit signal)\n- category: financial\n  text: 'x402 gauntlet receipts per settled POST /x402/v1/gauntlet payment:\
  \ the payment nonce, paying wallet address,\n    transaction id, input digest and cached response.'\npurposes:\n- purpose: create and secure account\n  text: create and secure your account, send service messages\n- purpose: take payment and prevent abuse\n  text: take payment and prevent abuse — we do not store card numbers\n- purpose: run the API and audit trail\n  text: run the API, debug, enforce rate limits, keep an audit trail\nretention:\n- scope: API and request logs\n  period: about 90 days\n  text: Operational API and request logs are retained for about 90 days , then deleted or aggregated.\n- scope: Account data\n  period: null\n  text: Account data is kept while your account exists and for as long as needed to meet legal obligations.\n- scope: Submitted signals and backtests\n  period: null\n  text: 'retained per trial: a one-way fingerprint, the verdict with failure codes, summary statistics'\nresidency:\n- region: European Union (Germany)\n  text: The Service runs on servers\
  \ located in the European Union (Germany) .\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@alphaassay.com to exercise erasure right\n  text: To exercise any of these, email hello@alphaassay.com .\nrights:\n- right: access\n  text: you can request access to your data\n- right: rectification\n  text: rectification\n- right: erasure\n  text: erasure\n- right: restriction\n  text: restriction\n- right: portability\n  text: portability\n- right: object\n  text: you can object to processing based on legitimate interests\n- right: complain to supervisory authority\n  text: lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data and do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/alphaassay-com/privacy/alphaassay-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from AlphaAssay's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Artificial Intelligence
- Validation
---
