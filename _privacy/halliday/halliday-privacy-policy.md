---
api_specs:
- filename: halliday-assets-api-openapi.yml
  format: yaml
  label: Halliday Assets API
  slug: halliday-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-assets-api-openapi.yml
- filename: halliday-chains-api-openapi.yml
  format: yaml
  label: Halliday Chains API
  slug: halliday-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-chains-api-openapi.yml
- filename: halliday-payments-api-openapi.yml
  format: yaml
  label: Halliday Payments API
  slug: halliday-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-payments-api-openapi.yml
- filename: halliday-webhooks-api-openapi.yml
  format: yaml
  label: Halliday Webhooks API
  slug: halliday-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halliday/openapi/halliday-webhooks-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, address, date of birth, national identification numbers (such as social security number), identity documentation, email address, IP address, wallet address
  - category: device
    text: details of the devices used to access our website, such as language, unique device identifier, browser type, device type, and operating system information
  - category: location
    text: approximate geolocation
  - category: behavioral
    text: your activity while browsing the Website (e.g., whether you played a video, performed a search, downloaded a file, submitted a webform, etc.)
  deletion:
    route: email privacy@halliday.xyz
    text: Requests relating to information that Halliday collects for its own purposes (such as your email address, wallet address, or information collected through Tracking Technologies) should be directed to Halliday
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: pass-through for third party KYC/AML compliance
    text: Halliday passes this information through solely for that purpose and does not use it to improve or develop the Features or for marketing or promotional purposes.
  - purpose: combatting fraud and legal compliance
    text: for the purpose of combatting fraud, or to otherwise operate our business
  retention:
  - period: null
    scope: Pass Through Information
    text: Pass Through Information is retained by the relevant Third Party Provider and the Data Processing Vendors in accordance with their own retention policies and legal obligations.
  - period: null
    scope: Halliday own-purpose information
    text: We retain information that we collect for our own purposes for as long as necessary to provide the Features, to comply with our legal and regulatory obligations, to resolve disputes, and to enforce our agreements, after which we delete or de-identify it.
  rights:
  - right: access
    text: the right to request access to that information
  - right: correction
    text: to request that it be corrected or deleted
  - right: portability
    text: to request a copy of it in a portable format
  - right: appeal
    text: to appeal a decision we make about your request
  role:
    text: Where Halliday passes through your information to a Third Party Provider, the Third Party Provider (not Halliday) determines what categories of information are collected, the purposes for which that information is used
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Halliday does not sell personal information, and does not share personal information for cross-context behavioral advertising
  subprocessors:
    text: Our current Data Processing Vendors include SumSub and Basis Theory, among others (as integrated from time to time).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Halliday
provenance_date: '2026-11-09'
provider_name: Halliday
provider_slug: halliday
slug: halliday-privacy-policy
source_date: '2026-11-09'
source_filename: halliday-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.halliday.xyz/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Halliday\naid: halliday\nurl: https://www.halliday.xyz/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where Halliday passes through your information to a Third Party Provider, the Third Party Provider (not\n    Halliday) determines what categories of information are collected, the purposes for which that information is\n    used\ndata_categories:\n- category: identifying\n  text: name, address, date of birth, national identification numbers (such as social security number), identity\n    documentation, email address, IP address, wallet address\n- category: device\n  text: details\
  \ of the devices used to access our website, such as language, unique device identifier, browser type,\n    device type, and operating system information\n- category: location\n  text: approximate geolocation\n- category: behavioral\n  text: your activity while browsing the Website (e.g., whether you played a video, performed a search, downloaded\n    a file, submitted a webform, etc.)\npurposes:\n- purpose: pass-through for third party KYC/AML compliance\n  text: Halliday passes this information through solely for that purpose and does not use it to improve or develop\n    the Features or for marketing or promotional purposes.\n- purpose: combatting fraud and legal compliance\n  text: for the purpose of combatting fraud, or to otherwise operate our business\nretention:\n- scope: Pass Through Information\n  period: null\n  text: Pass Through Information is retained by the relevant Third Party Provider and the Data Processing Vendors\n    in accordance with their own retention policies\
  \ and legal obligations.\n- scope: Halliday own-purpose information\n  period: null\n  text: We retain information that we collect for our own purposes for as long as necessary to provide the Features,\n    to comply with our legal and regulatory obligations, to resolve disputes, and to enforce our agreements, after\n    which we delete or de-identify it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Our current Data Processing Vendors include SumSub and Basis Theory, among others (as integrated from time\n    to time).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@halliday.xyz\n  text: Requests relating to information that Halliday collects for its own purposes (such as your email address,\n    wallet address, or information collected through Tracking Technologies) should be directed to Halliday\nrights:\n- right: access\n  text: the right to request access to that information\n- right: correction\n  text: to request that\
  \ it be corrected or deleted\n- right: portability\n  text: to request a copy of it in a portable format\n- right: appeal\n  text: to appeal a decision we make about your request\nsale_or_sharing:\n  stance: prohibited\n  text: Halliday does not sell personal information, and does not share personal information for cross-context behavioral\n    advertising\n"
source_yaml_url: https://artifacts.apis.io/halliday/privacy/halliday-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Halliday's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- Blockchain
- Web3
- On-Ramp
- Swap
- DeFi
- Agentic Workflows
- Fintech
---
