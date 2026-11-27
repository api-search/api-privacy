---
api_specs:
- filename: sendbridge-com-account-api-openapi.yml
  format: yaml
  label: SendBridge Account API
  slug: sendbridge-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-account-api-openapi.yml
- filename: sendbridge-com-dmarc-api-openapi.yml
  format: yaml
  label: SendBridge DMARC API
  slug: sendbridge-com-dmarc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-dmarc-api-openapi.yml
- filename: sendbridge-com-mail-tester-api-openapi.yml
  format: yaml
  label: SendBridge Mail Tester API
  slug: sendbridge-com-mail-tester-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-mail-tester-api-openapi.yml
- filename: sendbridge-com-validation-api-openapi.yml
  format: yaml
  label: SendBridge Validation API
  slug: sendbridge-com-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-validation-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name, date of birth, email address, gender, occupation, or other demographic information
  - category: contact
    text: such as your name, email address, address or telephone number
  - category: financial
    text: such as your credit card details and billing address
  - category: device
    text: such as your IP address, your operating system, your browser ID, and other information about your system and connection
  - category: behavioral
    text: your browsing activities (such as what portions of the Services are used)
  - category: location
    text: location (such as city and state)
  deletion:
    route: contact form
    text: You may contact us directly at any time about accessing, correcting, updating or deleting your Personal Information, or altering your data, by contacting us via contact form .
  dpa:
    available: true
    text: offering our Members a Data Processing Agreement
    url: null
  purposes:
  - purpose: billing and collection
    text: To bill and collect money owed to us by you.
  - purpose: provide, support and improve the Services
    text: To provide, support and improve the Services.
  - purpose: data analytics projects
    text: For our data analytics projects.
  - purpose: legal compliance
    text: To meet legal requirements
  - purpose: advertising and targeting
    text: or for advertising or targeting purposes in accordance with this privacy policy
  residency:
  - region: Germany and Czech Republic
    text: Our servers are located in Germany and offices are located in the Czech Republic, so your information may be transferred to, stored, or processed in the Germany and/or Czech Republic.
  - region: United States
    text: Our servers are located in the United States.
  retention:
  - period: null
    scope: Personal Information generally
    text: We retain Personal Information where we have an ongoing legitimate business or legal need to do so.
  rights:
  - right: access, correct, update or delete
    text: To access, correct, update or request deletion of Personal Information.
  - right: object, restrict, portability (EEA)
    text: individuals who are residents of the EEA can object to processing of their Personal Information, ask to restrict processing of their Personal Information or request portability of their Personal Information.
  - right: withdraw consent
    text: if Personal Information is collected or processed on the basis of consent, the data subject can withdraw their consent at any time.
  - right: complain to data protection authority
    text: The right to complain to a data protection authority about the collection and use of Personal Information.
  role:
    text: we act as a processor on behalf of our Members
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not, under any circumstances, sell your Distribution Lists.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we take many steps to protect your privacy, including offering our Members a Data Processing Agreement
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SendBridge
provenance_date: '2026-11-10'
provider_name: SendBridge
provider_slug: sendbridge-com
slug: sendbridge-com-privacy-policy
source_date: '2026-11-10'
source_filename: sendbridge-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sendbridge.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SendBridge\naid: sendbridge-com\nurl: https://sendbridge.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a processor on behalf of our Members\ndata_categories:\n- category: identifying\n  text: first and last name, date of birth, email address, gender, occupation, or other demographic information\n- category: contact\n  text: such as your name, email address, address or telephone number\n- category: financial\n  text: such as your credit card details and billing address\n- category: device\n  text: such as your IP address, your operating system, your browser ID, and other\
  \ information about your system\n    and connection\n- category: behavioral\n  text: your browsing activities (such as what portions of the Services are used)\n- category: location\n  text: location (such as city and state)\npurposes:\n- purpose: billing and collection\n  text: To bill and collect money owed to us by you.\n- purpose: provide, support and improve the Services\n  text: To provide, support and improve the Services.\n- purpose: data analytics projects\n  text: For our data analytics projects.\n- purpose: legal compliance\n  text: To meet legal requirements\n- purpose: advertising and targeting\n  text: or for advertising or targeting purposes in accordance with this privacy policy\nretention:\n- scope: Personal Information generally\n  period: null\n  text: We retain Personal Information where we have an ongoing legitimate business or legal need to do so.\nresidency:\n- region: Germany and Czech Republic\n  text: Our servers are located in Germany and offices are located in\
  \ the Czech Republic, so your information may\n    be transferred to, stored, or processed in the Germany and/or Czech Republic.\n- region: United States\n  text: Our servers are located in the United States.\ntransfers:\n- mechanism: other\n  text: we take many steps to protect your privacy, including offering our Members a Data Processing Agreement\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: offering our Members a Data Processing Agreement\ndeletion:\n  route: contact form\n  text: You may contact us directly at any time about accessing, correcting, updating or deleting your Personal\n    Information, or altering your data, by contacting us via contact form .\nrights:\n- right: access, correct, update or delete\n  text: To access, correct, update or request deletion of Personal Information.\n- right: object, restrict, portability (EEA)\n  text: individuals who are residents of the EEA can object to processing of their Personal Information,\
  \ ask to\n    restrict processing of their Personal Information or request portability of their Personal Information.\n- right: withdraw consent\n  text: if Personal Information is collected or processed on the basis of consent, the data subject can withdraw\n    their consent at any time.\n- right: complain to data protection authority\n  text: The right to complain to a data protection authority about the collection and use of Personal Information.\nsale_or_sharing:\n  stance: conditional\n  text: We do not, under any circumstances, sell your Distribution Lists.\n"
source_yaml_url: https://artifacts.apis.io/sendbridge-com/privacy/sendbridge-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from SendBridge's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Verification
- Deliverability
- Validation
- Marketing
- Services
---
