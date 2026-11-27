---
api_specs:
- filename: ofx-authorization-code-api-openapi.yml
  format: yaml
  label: OFX Authorization Code API
  slug: ofx-authorization-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-authorization-code-api-openapi.yml
- filename: ofx-authorize-api-openapi.yml
  format: yaml
  label: OFX Authorize API
  slug: ofx-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-authorize-api-openapi.yml
- filename: ofx-business-api-openapi.yml
  format: yaml
  label: OFX Business API
  slug: ofx-business-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-business-api-openapi.yml
- filename: ofx-oauth-api-openapi.yml
  format: yaml
  label: OFX OAuth API
  slug: ofx-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-oauth-api-openapi.yml
- filename: ofx-ofxrates-api-openapi.yml
  format: yaml
  label: OFX Ofxrates API
  slug: ofx-ofxrates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-ofxrates-api-openapi.yml
- filename: ofx-open-banking-api-openapi.yml
  format: yaml
  label: OFX Open Banking API
  slug: ofx-open-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-open-banking-api-openapi.yml
- filename: ofx-refresh-token-api-openapi.yml
  format: yaml
  label: OFX Refresh Token API
  slug: ofx-refresh-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-refresh-token-api-openapi.yml
- filename: ofx-token-api-openapi.yml
  format: yaml
  label: OFX Token API
  slug: ofx-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ofx/openapi/ofx-token-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: We may collect some or all of the following information, such as your name, date of birth, title, gender, mailing address, phone number, email address, nationality, occupation and social security number or other tax identification number.
  - category: financial
    text: we may collect financial information such as bank account details (e.g. account number, routing number), credit or debit card numbers, transaction data
  - category: biometric
    text: We also may provide you with the option of using identification verification technologies that analyse your facial imagery or other biometric information.
  - category: location
    text: we may collect information about your approximate location as determined by data such as your IP address.
  - category: device
    text: We may obtain information about the devices you use to access our Online Channels such as the device type, operating systems and versions
  - category: behavioral
    text: We collect information about how you interact with the Online Channels and how you use our Online Channels, such as your user preferences and other settings selected by you.
  deletion:
    route: Contact privacy@ofx.com
    text: If you want to access a copy of the Personal Information we hold about you, you can contact us at privacy@ofx.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: To provide or improve our services
  - purpose: Verify identity and prevent fraud
    text: To conduct manual or automated monitoring to protect against fraud, money laundering and other crimes and harmful activities.
  - purpose: Comply with legal obligations
    text: To comply with laws, regulations, codes of conduct, stock exchange rules, payment network/card scheme rules, binding determinations or to respond to legal process or government authorities.
  - purpose: Marketing and advertising
    text: To deliver promotional offers, incentives, and targeted or personalised marketing in a variety of ways such as via email, SMS, push notifications, telephone, social media or online (e.g. display ads, search engine marketing, retargeting).
  retention:
  - period: 7 years
    scope: AML/CTF records
    text: Under relevant AML/CTF Laws we need to keep your Personal Information and information about your transactions for up to 7 years from the end of your relationship with us.
  - period: 7 years from account closure
    scope: US state residents
    text: We retain your Personal Information for 7 years from account closure.
  rights:
  - right: Access
    text: You have the right to ask us for copies of your Personal Information.
  - right: Rectification
    text: You have the right to ask us to rectify Personal Information you think is inaccurate or is incomplete.
  - right: Erasure
    text: You have the right to ask us to erase your Personal Information in certain circumstances.
  - right: Restriction of processing
    text: You have the right to ask us to restrict the processing of your Personal Information in certain circumstances.
  - right: Object to processing
    text: You have the right to object to the processing of your Personal Information in certain circumstances.
  - right: Data portability
    text: You have the right to ask that we transfer the Personal Information you gave us to another organisation, or to you, in certain circumstances.
  - right: Opt-out of sale or sharing (US)
    text: You can opt-out of the sharing of your Personal Information for cross-contextual behavioral advertising purposes and/or from the sale of your Personal Information for monetary or other valuable consideration.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Our use of the behavioral advertising services described above may constitute ‘sharing’ of your Personal Information with our advertising partners from which you have the right to opt out.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we will take all reasonable steps to ensure that appropriate safeguards, including the use of standard contractual data protection clauses which have been approved by the European Commission, are in place.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OFX
provenance_date: '2026-11-10'
provider_name: OFX
provider_slug: ofx
slug: ofx-privacy-policy
source_date: '2026-11-10'
source_filename: ofx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ofx.com/en-us/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OFX\naid: ofx\nurl: https://www.ofx.com/en-us/legal/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We may collect some or all of the following information, such as your name, date of birth, title, gender,\n    mailing address, phone number, email address, nationality, occupation and social security number or other tax\n    identification number.\n- category: financial\n  text: we may collect financial information such as bank account details (e.g. account number, routing number),\n    credit or debit\
  \ card numbers, transaction data\n- category: biometric\n  text: We also may provide you with the option of using identification verification technologies that analyse your\n    facial imagery or other biometric information.\n- category: location\n  text: we may collect information about your approximate location as determined by data such as your IP address.\n- category: device\n  text: We may obtain information about the devices you use to access our Online Channels such as the device type,\n    operating systems and versions\n- category: behavioral\n  text: We collect information about how you interact with the Online Channels and how you use our Online Channels,\n    such as your user preferences and other settings selected by you.\npurposes:\n- purpose: Provide and improve services\n  text: To provide or improve our services\n- purpose: Verify identity and prevent fraud\n  text: To conduct manual or automated monitoring to protect against fraud, money laundering and other crimes and\n\
  \    harmful activities.\n- purpose: Comply with legal obligations\n  text: To comply with laws, regulations, codes of conduct, stock exchange rules, payment network/card scheme rules,\n    binding determinations or to respond to legal process or government authorities.\n- purpose: Marketing and advertising\n  text: To deliver promotional offers, incentives, and targeted or personalised marketing in a variety of ways such\n    as via email, SMS, push notifications, telephone, social media or online (e.g. display ads, search engine marketing,\n    retargeting).\nretention:\n- scope: AML/CTF records\n  period: 7 years\n  text: Under relevant AML/CTF Laws we need to keep your Personal Information and information about your transactions\n    for up to 7 years from the end of your relationship with us.\n- scope: US state residents\n  period: 7 years from account closure\n  text: We retain your Personal Information for 7 years from account closure.\nresidency: []\ntransfers:\n- mechanism: SCC\n\
  \  text: we will take all reasonable steps to ensure that appropriate safeguards, including the use of standard contractual\n    data protection clauses which have been approved by the European Commission, are in place.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@ofx.com\n  text: If you want to access a copy of the Personal Information we hold about you, you can contact us at privacy@ofx.com\nrights:\n- right: Access\n  text: You have the right to ask us for copies of your Personal Information.\n- right: Rectification\n  text: You have the right to ask us to rectify Personal Information you think is inaccurate or is incomplete.\n- right: Erasure\n  text: You have the right to ask us to erase your Personal Information in certain circumstances.\n- right: Restriction of processing\n  text: You have the right to ask us to restrict the processing of your Personal Information in certain circumstances.\n-\
  \ right: Object to processing\n  text: You have the right to object to the processing of your Personal Information in certain circumstances.\n- right: Data portability\n  text: You have the right to ask that we transfer the Personal Information you gave us to another organisation,\n    or to you, in certain circumstances.\n- right: Opt-out of sale or sharing (US)\n  text: You can opt-out of the sharing of your Personal Information for cross-contextual behavioral advertising\n    purposes and/or from the sale of your Personal Information for monetary or other valuable consideration.\nsale_or_sharing:\n  stance: conditional\n  text: Our use of the behavioral advertising services described above may constitute ‘sharing’ of your Personal\n    Information with our advertising partners from which you have the right to opt out.\n"
source_yaml_url: https://artifacts.apis.io/ofx/privacy/ofx-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from OFX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Money Transfer
- Fintech
- Banking
---
