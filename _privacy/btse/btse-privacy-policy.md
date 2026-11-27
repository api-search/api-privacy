---
api_specs:
- filename: btse-account-api-openapi.yml
  format: yaml
  label: BTSE Account API
  slug: btse-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-account-api-openapi.yml
- filename: btse-earn-api-openapi.yml
  format: yaml
  label: BTSE Earn API
  slug: btse-earn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-earn-api-openapi.yml
- filename: btse-markets-api-openapi.yml
  format: yaml
  label: BTSE Markets API
  slug: btse-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-markets-api-openapi.yml
- filename: btse-otc-api-openapi.yml
  format: yaml
  label: BTSE OTC API
  slug: btse-otc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-otc-api-openapi.yml
- filename: btse-trade-api-openapi.yml
  format: yaml
  label: BTSE Trade API
  slug: btse-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-trade-api-openapi.yml
- filename: btse-trade-v3-api-openapi.yml
  format: yaml
  label: BTSE Trade V3 API
  slug: btse-trade-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-trade-v3-api-openapi.yml
- filename: btse-trade-v4-api-openapi.yml
  format: yaml
  label: BTSE Trade V4 API
  slug: btse-trade-v4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-trade-v4-api-openapi.yml
- filename: btse-wallet-api-openapi.yml
  format: yaml
  label: BTSE Wallet API
  slug: btse-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btse/openapi/btse-wallet-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Such as first name, middle name, last name, username, password, date of birth, nationality, country of residence, and gender
  - category: contact
    text: Such as address, phone number, and email address
  - category: financial
    text: Such as bank account details, tax identification number, credit/debit Card details, and wallet information
  - category: location
    text: Such as GPS location, contacts, photos, and other data from your mobile device, in accordance with the permissions you have granted
  - category: behavioral
    text: Such as activity information including what you view or click on while visiting our website and app, how you use our Services
  - category: device
    text: Such as information about the device, operating system, and browser you’re using, your IP Address, plugins, and the internet network you connect to
  - category: biometric
    text: Such as photos or videos, or any other biometric data you provide during the KYC process
  - category: communication
    text: information provided to our Customer Support team (including call recordings)
  deletion:
    route: Privacy rights management portal
    text: You can exercise your privacy rights with us at our privacy right management portal.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract performance
    text: To create and maintain your BTSE account.
  - purpose: Legal compliance
    text: To verify your identity and comply with laws like anti-money laundering (“AML”) regulations, counter-terrorist financing, or sanctions and laws that mandate KYC verification.
  - purpose: Legitimate interests
    text: To improve our services and enhance your experience on our app and website.
  - purpose: Consent-based marketing
    text: To send you targeted marketing communications through email, mobile, in-app, push notifications, or SMS.
  residency:
  - region: Transfer destinations
    text: including in Australia, Canada, Hungary, Japan, Malaysia, countries in EU/EEA, Netherlands, Singapore, Taiwan, United States.
  retention:
  - period: null
    scope: General customer data
    text: We retain your personal information for as long as reasonably necessary to provide our Services to you, fulfill our legitimate business purposes, and to comply with our legal and regulatory obligations.
  rights:
  - right: Access
    text: 'Access: You have the right to request access to the personal information we hold about you.'
  - right: Rectification
    text: 'Rectification: You can request the correction of any inaccurate personal information we hold about you, ensuring your information is up-to-date.'
  - right: Erasure
    text: 'Erasure: Under certain circumstances, such as when your personal information is no longer necessary for our processing purposes or when you''ve objected to the processing, you have the right to have your personal information erased.'
  - right: Objection
    text: 'Objection: In specific situations, such as when we process your personal information for direct marketing purposes or when your legitimate interests override ours, you have the right to object to the processing.'
  - right: Data Portability
    text: 'Data Portability: If you no longer wish to use our Services, you can request the transfer of your personal information to a new service provider'
  role:
    text: BTSE and its applicable affiliates entities acting as data controllers
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: BTSE may rely on legally recognised transfer mechanisms including adequacy decisions, Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: recognised certification frameworks (such as EU-US Data Privacy Framework, where applicable)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BTSE
provenance_date: '2026-11-09'
provider_name: BTSE
provider_slug: btse
slug: btse-privacy-policy
source_date: '2026-11-09'
source_filename: btse-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.btse.com/en/privacy?anchor=personalInformation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BTSE\naid: btse\nurl: https://www.btse.com/en/privacy?anchor=personalInformation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BTSE and its applicable affiliates entities acting as data controllers\ndata_categories:\n- category: identifying\n  text: Such as first name, middle name, last name, username, password, date of birth, nationality, country of residence,\n    and gender\n- category: contact\n  text: Such as address, phone number, and email address\n- category: financial\n  text: Such as bank account details, tax identification number, credit/debit Card details, and wallet information\n\
  - category: location\n  text: Such as GPS location, contacts, photos, and other data from your mobile device, in accordance with the permissions\n    you have granted\n- category: behavioral\n  text: Such as activity information including what you view or click on while visiting our website and app, how\n    you use our Services\n- category: device\n  text: Such as information about the device, operating system, and browser you’re using, your IP Address, plugins,\n    and the internet network you connect to\n- category: biometric\n  text: Such as photos or videos, or any other biometric data you provide during the KYC process\n- category: communication\n  text: information provided to our Customer Support team (including call recordings)\npurposes:\n- purpose: Contract performance\n  text: To create and maintain your BTSE account.\n- purpose: Legal compliance\n  text: To verify your identity and comply with laws like anti-money laundering (“AML”) regulations, counter-terrorist\n    financing,\
  \ or sanctions and laws that mandate KYC verification.\n- purpose: Legitimate interests\n  text: To improve our services and enhance your experience on our app and website.\n- purpose: Consent-based marketing\n  text: To send you targeted marketing communications through email, mobile, in-app, push notifications, or SMS.\nretention:\n- scope: General customer data\n  period: null\n  text: We retain your personal information for as long as reasonably necessary to provide our Services to you,\n    fulfill our legitimate business purposes, and to comply with our legal and regulatory obligations.\nresidency:\n- region: Transfer destinations\n  text: including in Australia, Canada, Hungary, Japan, Malaysia, countries in EU/EEA, Netherlands, Singapore, Taiwan,\n    United States.\ntransfers:\n- mechanism: SCC\n  text: BTSE may rely on legally recognised transfer mechanisms including adequacy decisions, Standard Contractual\n    Clauses (SCCs)\n- mechanism: DPF\n  text: recognised certification\
  \ frameworks (such as EU-US Data Privacy Framework, where applicable)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy rights management portal\n  text: You can exercise your privacy rights with us at our privacy right management portal.\nrights:\n- right: Access\n  text: 'Access: You have the right to request access to the personal information we hold about you.'\n- right: Rectification\n  text: 'Rectification: You can request the correction of any inaccurate personal information we hold about you,\n    ensuring your information is up-to-date.'\n- right: Erasure\n  text: 'Erasure: Under certain circumstances, such as when your personal information is no longer necessary for\n    our processing purposes or when you''ve objected to the processing, you have the right to have your personal\n    information erased.'\n- right: Objection\n  text: 'Objection: In specific situations, such as when we process your personal\
  \ information for direct marketing\n    purposes or when your legitimate interests override ours, you have the right to object to the processing.'\n- right: Data Portability\n  text: 'Data Portability: If you no longer wish to use our Services, you can request the transfer of your personal\n    information to a new service provider'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/btse/privacy/btse-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 23 quoted statements, read from BTSE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Digital Assets
- Futures
- WebSocket
---
