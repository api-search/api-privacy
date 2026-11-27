---
api_specs:
- filename: terminal-3-did-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 DID V1 API
  slug: terminal-3-did-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-did-v1-api-openapi.yml
- filename: terminal-3-openid-connect-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 OpenID Connect V1 API
  slug: terminal-3-openid-connect-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-openid-connect-v1-api-openapi.yml
- filename: terminal-3-openid-connect-v2-api-openapi.yml
  format: yaml
  label: Terminal 3 OpenID Connect V2 API
  slug: terminal-3-openid-connect-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-openid-connect-v2-api-openapi.yml
- filename: terminal-3-sub-client-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 Sub Client V1 API
  slug: terminal-3-sub-client-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-sub-client-v1-api-openapi.yml
- filename: terminal-3-transactional-email-template-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 Transactional Email Template V1 API
  slug: terminal-3-transactional-email-template-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-transactional-email-template-v1-api-openapi.yml
- filename: terminal-3-user-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 User V1 API
  slug: terminal-3-user-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-user-v1-api-openapi.yml
- filename: terminal-3-vc-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 VC V1 API
  slug: terminal-3-vc-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-vc-v1-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers — such as your name, email address, date of birth, sex or gender, nationality, identity document details, and national or document identification numbers
  - category: biometric
    text: Identity verification data — images of your identity document, a facial image, and the result of a liveness check.
  - category: professional
    text: Business contact data — such as your name, job title, employer, business email address and telephone number, and our correspondence with you
  - category: device
    text: Website and device data — such as your IP address, the region or general location from which you access the internet, browser type, operating system
  - category: behavioral
    text: information about your use of our website
  deletion:
    route: Contact privacy@terminal3.io
    text: You may request deletion of your Private User Data at any time, subject to legally required retention of Regulated User Data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Verify identity
    text: Verify your identity against your identity document
  - purpose: Marketing
    text: Send you marketing, where you have asked for it
  - purpose: Website analytics
    text: Website analytics and improvement
  - purpose: Legal retention
    text: Retain identity verification and screening records
  residency:
  - region: Hong Kong
    text: Terminal 3 HK Limited is established in Hong Kong.
  - region: Pinnable jurisdictions
    text: Personal data can be pinned to a specific jurisdiction (for example, the EU, APAC, or North America)
  retention:
  - period: until that document expires
    scope: Credentials derived from identity documents
    text: it remains valid until that document expires, unless you delete it or ask us to delete it sooner.
  rights:
  - right: Right of access
    text: Right of access — to confirm whether we are processing your personal data and to obtain a copy of it.
  - right: Right to erasure
    text: Right to erasure — to request deletion of your personal data, subject to certain exceptions, including legally required retention of Regulated User Data.
  - right: Right to object
    text: Right to object — to object to processing based on our legitimate interests, and to direct marketing at any time.
  - right: Right to data portability
    text: Right to data portability — to receive your data in a portable format or have it transferred where technically feasible.
  role:
    text: For your Account, Terminal 3 is a controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: The current providers in each category are listed in our Trust Center at https://trust.terminal3.io
    url: https://trust.terminal3.io
  transfers:
  - mechanism: SCC
    text: the Standard Contractual Clauses approved by the European Commission together with the UK International Data Transfer Addendum
  - mechanism: adequacy
    text: that may be an adequacy decision covering the destination
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Terminal 3
provenance_date: '2026-11-10'
provider_name: Terminal 3
provider_slug: terminal-3
slug: terminal-3-privacy-policy
source_date: '2026-11-10'
source_filename: terminal-3-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://terminal3.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Terminal 3\naid: terminal-3\nurl: https://terminal3.io/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your Account, Terminal 3 is a controller.\ndata_categories:\n- category: identifying\n  text: Identifiers — such as your name, email address, date of birth, sex or gender, nationality, identity document\n    details, and national or document identification numbers\n- category: biometric\n  text: Identity verification data — images of your identity document, a facial image, and the result of a liveness\n    check.\n- category: professional\n  text: Business contact data — such\
  \ as your name, job title, employer, business email address and telephone number,\n    and our correspondence with you\n- category: device\n  text: Website and device data — such as your IP address, the region or general location from which you access\n    the internet, browser type, operating system\n- category: behavioral\n  text: information about your use of our website\npurposes:\n- purpose: Verify identity\n  text: Verify your identity against your identity document\n- purpose: Marketing\n  text: Send you marketing, where you have asked for it\n- purpose: Website analytics\n  text: Website analytics and improvement\n- purpose: Legal retention\n  text: Retain identity verification and screening records\nretention:\n- scope: Credentials derived from identity documents\n  period: until that document expires\n  text: it remains valid until that document expires, unless you delete it or ask us to delete it sooner.\nresidency:\n- region: Hong Kong\n  text: Terminal 3 HK Limited is established\
  \ in Hong Kong.\n- region: Pinnable jurisdictions\n  text: Personal data can be pinned to a specific jurisdiction (for example, the EU, APAC, or North America)\ntransfers:\n- mechanism: SCC\n  text: the Standard Contractual Clauses approved by the European Commission together with the UK International\n    Data Transfer Addendum\n- mechanism: adequacy\n  text: that may be an adequacy decision covering the destination\nsubprocessors:\n  url: https://trust.terminal3.io\n  text: The current providers in each category are listed in our Trust Center at https://trust.terminal3.io\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@terminal3.io\n  text: You may request deletion of your Private User Data at any time, subject to legally required retention of\n    Regulated User Data.\nrights:\n- right: Right of access\n  text: Right of access — to confirm whether we are processing your personal data and to obtain a copy of it.\n- right: Right to erasure\n  text:\
  \ Right to erasure — to request deletion of your personal data, subject to certain exceptions, including legally\n    required retention of Regulated User Data.\n- right: Right to object\n  text: Right to object — to object to processing based on our legitimate interests, and to direct marketing at\n    any time.\n- right: Right to data portability\n  text: Right to data portability — to receive your data in a portable format or have it transferred where technically\n    feasible.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/terminal-3/privacy/terminal-3-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Terminal 3's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Decentralized Identity
- Verifiable Credentials
- OpenID Connect
- KYC
- AML
- Confidential Computing
- AI Agents
- Privacy
- Web3
- DID
---
