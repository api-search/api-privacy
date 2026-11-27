---
api_specs:
- filename: luno-streaming-asyncapi.yml
  format: yaml
  label: Luno API
  slug: luno-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/luno/asyncapi/luno-streaming-asyncapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: First, last and any middle names; date of birth; nationality; gender; email address; cell phone number
  - category: financial
    text: Source of funds; nature and purpose of business relationship; bank account details; masked PAN debit, credit or other payment card number
  - category: biometric
    text: Typically a scan of your face taken from a photo or video selfie to compare with the photograph of you on the copy of your identity document that you submit
  - category: location
    text: Information that identifies your location in a reasonably specific way based on an IP address or GSM, GPS and/or WiFi.
  - category: device
    text: IP and MAC address; device IMEI number; mobile network information
  - category: behavioral
    text: Information about your visit and use of our services including what you viewed and what you clicked on
  - category: communication
    text: Correspondence between Luno and you as a customer, including call recordings and call/chat transcripts, emails, feedback and survey responses
  deletion:
    route: Request deletion via rights
    text: You may ask us to delete personal data in certain circumstances. For more information please see the section “Your rights” below.
  dpa:
    available: true
    text: When data processing is carried out on our behalf, we conclude a separate agreement with service providers, called a data processing agreement
    url: null
  purposes:
  - purpose: Open and maintain account
    text: In order to open and to maintain your Luno account
  - purpose: Legal and regulatory compliance
    text: To comply with our legal obligations
  - purpose: Marketing
    text: To market our products and services that might be of interest to you
  - purpose: Security
    text: To maintain the quality, integrity and security of our services including our website and app
  retention:
  - period: null
    scope: Customer personal data
    text: We will typically retain personal data for the duration of your relationship with us, and afterwards for such period as may be necessary for our legitimate business purposes
  rights:
  - right: Access
    text: Ask us to give you access to personal data.
  - right: Erasure
    text: Ask to have personal data erased.
  - right: Object
    text: Object to our processing of personal data.
  - right: Restriction
    text: Ask for processing to be restricted.
  - right: Rectification
    text: Ask for personal data to be corrected or updated.
  - right: Portability
    text: Ask us to transfer (or “port”) personal data to you or to a third party.
  - right: Complaint
    text: Make a complaint to a supervisory authority.
  role:
    text: If you are the account owner, the Luno entity providing the services is the data controller.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We will only transfer personal data where permitted by local law and with appropriate safeguards such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Luno
provenance_date: '2026-11-10'
provider_name: Luno
provider_slug: luno
slug: luno-privacy-policy
source_date: '2026-11-10'
source_filename: luno-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.luno.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Luno\naid: luno\nurl: https://www.luno.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: If you are the account owner, the Luno entity providing the services is the data controller.\ndata_categories:\n- category: identifying\n  text: First, last and any middle names; date of birth; nationality; gender; email address; cell phone number\n- category: financial\n  text: Source of funds; nature and purpose of business relationship; bank account details; masked PAN debit, credit\n    or other payment card number\n- category: biometric\n  text: Typically a scan of your face taken from\
  \ a photo or video selfie to compare with the photograph of you on\n    the copy of your identity document that you submit\n- category: location\n  text: Information that identifies your location in a reasonably specific way based on an IP address or GSM, GPS\n    and/or WiFi.\n- category: device\n  text: IP and MAC address; device IMEI number; mobile network information\n- category: behavioral\n  text: Information about your visit and use of our services including what you viewed and what you clicked on\n- category: communication\n  text: Correspondence between Luno and you as a customer, including call recordings and call/chat transcripts,\n    emails, feedback and survey responses\npurposes:\n- purpose: Open and maintain account\n  text: In order to open and to maintain your Luno account\n- purpose: Legal and regulatory compliance\n  text: To comply with our legal obligations\n- purpose: Marketing\n  text: To market our products and services that might be of interest to you\n- purpose:\
  \ Security\n  text: To maintain the quality, integrity and security of our services including our website and app\nretention:\n- scope: Customer personal data\n  period: null\n  text: We will typically retain personal data for the duration of your relationship with us, and afterwards for\n    such period as may be necessary for our legitimate business purposes\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: We will only transfer personal data where permitted by local law and with appropriate safeguards such as\n    standard contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: When data processing is carried out on our behalf, we conclude a separate agreement with service providers,\n    called a data processing agreement\ndeletion:\n  route: Request deletion via rights\n  text: You may ask us to delete personal data in certain circumstances. For more information please see the section\n    “Your rights” below.\nrights:\n-\
  \ right: Access\n  text: Ask us to give you access to personal data.\n- right: Erasure\n  text: Ask to have personal data erased.\n- right: Object\n  text: Object to our processing of personal data.\n- right: Restriction\n  text: Ask for processing to be restricted.\n- right: Rectification\n  text: Ask for personal data to be corrected or updated.\n- right: Portability\n  text: Ask us to transfer (or “port”) personal data to you or to a third party.\n- right: Complaint\n  text: Make a complaint to a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/luno/privacy/luno-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 23 quoted statements, read from Luno's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Bitcoin
- Ethereum
- Trading
- Fintech
- Wallets
- Blockchain
- Financial Services
- Real-Time
---
