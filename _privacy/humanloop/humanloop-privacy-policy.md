---
api_specs:
- filename: humanloop-datasets-api-openapi.yml
  format: yaml
  label: Humanloop Datasets API
  slug: humanloop-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-datasets-api-openapi.yml
- filename: humanloop-evaluators-api-openapi.yml
  format: yaml
  label: Humanloop Evaluators API
  slug: humanloop-evaluators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-evaluators-api-openapi.yml
- filename: humanloop-logs-api-openapi.yml
  format: yaml
  label: Humanloop Logs API
  slug: humanloop-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-logs-api-openapi.yml
- filename: humanloop-prompts-api-openapi.yml
  format: yaml
  label: Humanloop Prompts API
  slug: humanloop-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-prompts-api-openapi.yml
- filename: humanloop-sessions-api-openapi.yml
  format: yaml
  label: Humanloop Sessions API
  slug: humanloop-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-sessions-api-openapi.yml
- filename: humanloop-tools-api-openapi.yml
  format: yaml
  label: Humanloop Tools API
  slug: humanloop-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-tools-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: To facilitate the account creation and logon process we collect your name and email address.
  - category: contact
    text: When you contact us either by phone, email, via our 'contact us' page or via social media, we will usually collect your name, social media handle and contact details
  - category: device
    text: we will collect information about how you use our website including your device type, operating system, browser type, browser settings, IP address, language settings
  - category: behavioral
    text: browsing behaviour and links clicked
  deletion:
    route: email privacy@humanloop.com or verifiable request
    text: You have the right to request that we delete any of your personal information, subject to the following exceptions
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: account creation and service provision
    text: allow us to provide our services, including to fulfil your orders and requests, and to facilitate payments
  - purpose: fraud monitoring
    text: This includes monitoring payments and purchases for fraud.
  - purpose: marketing updates
    text: to provide you with our updates in line with any preferences you have told us about
  - purpose: website improvement
    text: We use this information to improve our website and to better understand how people use it.
  residency:
  - region: United States of America and United Kingdom
    text: We store your data in United States of America and United Kingdom.
  retention:
  - period: null
    scope: personal information
    text: We will only retain your personal information for as long as we need it.
  - period: indefinitely
    scope: anonymised data
    text: we can use it indefinitely without notifying you
  rights:
  - right: access
    text: Access your personal data (also known as a “subject access request”)
  - right: erasure
    text: Ask us to erase the personal data we hold about you
  - right: correction
    text: Correct incomplete or inaccurate data we hold about you
  - right: objection
    text: Object to how we are using your personal data
  - right: portability
    text: Ask us to transfer your personal data to a third party
  - right: restriction
    text: Ask us to restrict our handling of your personal data
  - right: withdraw consent
    text: Withdraw your consent to us handling your personal data
  role:
    text: Our full company name is Humanloop Limited.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold personal information that is subject to the CCPA’s sale limitations.
  subprocessors:
    text: List of Subprocessors
    url: null
  transfers:
  - mechanism: other
    text: Whenever we transfer your personal information outside of the UK and the EU, we ensure it receives additional protection as required by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Humanloop
provenance_date: '2026-11-09'
provider_name: Humanloop
provider_slug: humanloop
slug: humanloop-privacy-policy
source_date: '2026-11-09'
source_filename: humanloop-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://humanloop.com/policies/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Humanloop\naid: humanloop\nurl: https://humanloop.com/policies/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Our full company name is Humanloop Limited.\ndata_categories:\n- category: identifying\n  text: To facilitate the account creation and logon process we collect your name and email address.\n- category: contact\n  text: When you contact us either by phone, email, via our 'contact us' page or via social media, we will usually\n    collect your name, social media handle and contact details\n- category: device\n  text: we will collect information about how you use our website\
  \ including your device type, operating system,\n    browser type, browser settings, IP address, language settings\n- category: behavioral\n  text: browsing behaviour and links clicked\npurposes:\n- purpose: account creation and service provision\n  text: allow us to provide our services, including to fulfil your orders and requests, and to facilitate payments\n- purpose: fraud monitoring\n  text: This includes monitoring payments and purchases for fraud.\n- purpose: marketing updates\n  text: to provide you with our updates in line with any preferences you have told us about\n- purpose: website improvement\n  text: We use this information to improve our website and to better understand how people use it.\nretention:\n- scope: personal information\n  period: null\n  text: We will only retain your personal information for as long as we need it.\n- scope: anonymised data\n  period: indefinitely\n  text: we can use it indefinitely without notifying you\nresidency:\n- region: United States\
  \ of America and United Kingdom\n  text: We store your data in United States of America and United Kingdom.\ntransfers:\n- mechanism: other\n  text: Whenever we transfer your personal information outside of the UK and the EU, we ensure it receives additional\n    protection as required by law.\nsubprocessors:\n  url: null\n  text: List of Subprocessors\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: email privacy@humanloop.com or verifiable request\n  text: You have the right to request that we delete any of your personal information, subject to the following\n    exceptions\nrights:\n- right: access\n  text: Access your personal data (also known as a “subject access request”)\n- right: erasure\n  text: Ask us to erase the personal data we hold about you\n- right: correction\n  text: Correct incomplete or inaccurate data we hold about you\n- right: objection\n  text: Object to how we are using your personal data\n- right: portability\n  text:\
  \ Ask us to transfer your personal data to a third party\n- right: restriction\n  text: Ask us to restrict our handling of your personal data\n- right: withdraw consent\n  text: Withdraw your consent to us handling your personal data\nsale_or_sharing:\n  stance: unstated\n  text: We have not sold personal information that is subject to the CCPA’s sale limitations.\n"
source_yaml_url: https://artifacts.apis.io/humanloop/privacy/humanloop-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Humanloop's own page on 2026-11-09.
synthetic: false
tags:
- LLM Platform
- Prompt Management
- Evaluation
- LLMOps
- Observability
- Datasets
- Prompts
- Tools
- Logs
- Multi-Provider
- Sunsetting
- Acquired
---
