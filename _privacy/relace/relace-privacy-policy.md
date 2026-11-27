---
api_specs:
- filename: relace-code-api-openapi.yml
  format: yaml
  label: Relace Code API
  slug: relace-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relace/openapi/relace-code-api-openapi.yml
- filename: relace-repo-api-openapi.yml
  format: yaml
  label: Relace Repo API
  slug: relace-repo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relace/openapi/relace-repo-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, email address, physical address, telephone number, social security number
  - category: financial
    text: payment information
  - category: location
    text: geolocation data
  - category: behavioral
    text: internet browsing history, geolocation data, information regarding interaction with a website
  - category: device
    text: unique Device identifiers, the location of your Device
  - category: communication
    text: Support Information. Information you provide to us when you contact us for technical, operational, or other support
  - category: professional
    text: professional information
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Recommendations and personalization
    text: We use your Personal Information to recommend features, products, and services that might be of interest to you
  - purpose: Fraud prevention and credit risk
    text: We use Personal Information to verify your identity, prevent and detect fraud and abuse
  - purpose: AI model training
    text: we use data provided to us to train, evaluate and improve our AI models
  - purpose: Legal compliance
    text: In certain cases, we collect and use your Personal Information to comply with laws.
  - purpose: Communication
    text: We use your Personal Information to communicate with you in relation to the Services via different channels
  retention:
  - period: null
    scope: API platform prompts, source code and outputs
    text: are not retained; they are held only transiently in memory while a request is processed
  - period: 30 days
    scope: Google user data
    text: Upon disconnection or account deletion, Google user data (including OAuth tokens and cached calendar data) is deleted from our active systems within 30 days, except where retention is required by law.
  - period: null
    scope: All other Information
    text: we retain your Information for as long as it is needed to provide you with Services, or for other purposes described in this Privacy Policy, and for as long as legally required.
  rights:
  - right: Access, correct, update, delete
    text: We strive to provide you with the ability to access, review, correct, update, suppress, delete, or otherwise limit our use of the Information you have previously provided directly to us
  - right: Opt out of AI training
    text: You may request that we do not use your Personal Information for purposes of training, evaluating and improving our AI models.
  - right: Opt out of third-party marketing disclosure
    text: You may request that we do not disclose your Personal Information on a going-forward basis with third parties for their direct marketing purposes
  - right: Nondiscrimination (CCPA)
    text: we will not discriminate against you for exercising any of your rights under the CCPA
  role:
    text: Squack, Inc. (“Relace”, “we”, “us” or “our”) respects your privacy and is committed to protecting it.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Personal Information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Relace
provenance_date: '2026-11-10'
provider_name: Relace
provider_slug: relace
slug: relace-privacy-policy
source_date: '2026-11-10'
source_filename: relace-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://relace.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Relace\naid: relace\nurl: https://relace.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Squack, Inc. (“Relace”, “we”, “us” or “our”) respects your privacy and is committed to protecting it.\ndata_categories:\n- category: identifying\n  text: such as your name, email address, physical address, telephone number, social security number\n- category: financial\n  text: payment information\n- category: location\n  text: geolocation data\n- category: behavioral\n  text: internet browsing history, geolocation data, information regarding interaction with a website\n- category:\
  \ device\n  text: unique Device identifiers, the location of your Device\n- category: communication\n  text: Support Information. Information you provide to us when you contact us for technical, operational, or other\n    support\n- category: professional\n  text: professional information\npurposes:\n- purpose: Recommendations and personalization\n  text: We use your Personal Information to recommend features, products, and services that might be of interest\n    to you\n- purpose: Fraud prevention and credit risk\n  text: We use Personal Information to verify your identity, prevent and detect fraud and abuse\n- purpose: AI model training\n  text: we use data provided to us to train, evaluate and improve our AI models\n- purpose: Legal compliance\n  text: In certain cases, we collect and use your Personal Information to comply with laws.\n- purpose: Communication\n  text: We use your Personal Information to communicate with you in relation to the Services via different channels\nretention:\n\
  - scope: API platform prompts, source code and outputs\n  period: null\n  text: are not retained; they are held only transiently in memory while a request is processed\n- scope: Google user data\n  period: 30 days\n  text: Upon disconnection or account deletion, Google user data (including OAuth tokens and cached calendar data)\n    is deleted from our active systems within 30 days, except where retention is required by law.\n- scope: All other Information\n  period: null\n  text: we retain your Information for as long as it is needed to provide you with Services, or for other purposes\n    described in this Privacy Policy, and for as long as legally required.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access, correct, update, delete\n  text: We strive to provide you with the ability to access, review, correct, update, suppress, delete, or otherwise\n\
  \    limit our use of the Information you have previously provided directly to us\n- right: Opt out of AI training\n  text: You may request that we do not use your Personal Information for purposes of training, evaluating and improving\n    our AI models.\n- right: Opt out of third-party marketing disclosure\n  text: You may request that we do not disclose your Personal Information on a going-forward basis with third parties\n    for their direct marketing purposes\n- right: Nondiscrimination (CCPA)\n  text: we will not discriminate against you for exercising any of your rights under the CCPA\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your Personal Information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/relace/privacy/relace-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Relace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Coding Agents
- Code Generation
- Developer Tools
- Machine Learning
- Code Search
- LLM
- Foundation Models
---
