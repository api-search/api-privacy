---
api_specs:
- filename: pred-authentication-api-openapi.yml
  format: yaml
  label: Pred Authentication API
  slug: pred-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-authentication-api-openapi.yml
- filename: pred-market-discovery-api-openapi.yml
  format: yaml
  label: Pred Market Discovery API
  slug: pred-market-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-market-discovery-api-openapi.yml
- filename: pred-orders-api-openapi.yml
  format: yaml
  label: Pred Orders API
  slug: pred-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-orders-api-openapi.yml
- filename: pred-overview-api-openapi.yml
  format: yaml
  label: Pred Overview API
  slug: pred-overview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-overview-api-openapi.yml
- filename: pred-portfolio-api-openapi.yml
  format: yaml
  label: Pred Portfolio API
  slug: pred-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-portfolio-api-openapi.yml
- filename: pred-user-api-openapi.yml
  format: yaml
  label: Pred User API
  slug: pred-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-user-api-openapi.yml
- filename: pred-websocket-api-openapi.yml
  format: yaml
  label: Pred WebSocket API
  slug: pred-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-websocket-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact Information: Includes your e-mail address, telephone number, discord handle, telegram username, postal address, and any other contact details you provide when signing up for alerts or support.'
  - category: identifying
    text: 'Identity & KYC Information: Includes your full legal name, date of birth, gender, nationality, hometown, government-issued identification details'
  - category: biometric
    text: biometric data (such as a live photograph or "selfie") used strictly for identity verification and fraud prevention.
  - category: financial
    text: This category also includes billing address and source of funds declarations.
  - category: behavioral
    text: Includes information about how you use our Website, products, and services
  - category: location
    text: Includes precise or approximate location data determined from your IP address, GPS, Wi-Fi, or cell-site triangulation.
  - category: device
    text: Includes your internet protocol (IP) address, browser type and version, time zone setting and location, browser plug-in types and versions, operating system and platform, device attributes (fingerprinting), and other technology on the devices you use to access this Website.
  - category: communication
    text: 'Correspondence Data: Includes records of your communications with our customer support team, feedback, and responses to surveys.'
  - category: other
    text: Includes your public Digital Wallet address (e.g., Ethereum or Polygon address), your transaction history on the Blockchain (including deposits, withdrawals, token swaps, Information Contracts purchased, and market resolutions), account balances, token holdings
  deletion:
    route: Email support@pred.app with subject line "Erasure / Personal Data Deletion"
    text: If you should wish to cease use of our Services and have your Personal Data deleted, then you may submit a request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account registration and management
    text: To register you as a new customer; to manage your account
  - purpose: identity verification and fraud prevention
    text: To verify your identity; to prevent fraud, money laundering, and terrorist financing
  - purpose: analytics and improvement
    text: To use data analytics to improve our website, products/services, marketing, customer relationships and experiences
  - purpose: customer support
    text: To provide customer support; to resolve disputes regarding market resolutions; and to respond to inquiries.
  residency:
  - region: Panama
    text: The Services, including the Interface, are made available by us from the Republic of Panama
  retention:
  - period: null
    scope: general personal data
    text: The Company retains your Personal Data for as long as necessary to provide the access to and use of the Website, to fulfil the purposes described above, or for other essential purposes such as complying with our legal obligations, resolving disputes, and enforcing our agreements.
  - period: 5 to 7 years
    scope: KYC data
    text: We are often legally required to retain identity verification data for a period of 5 to 7 years after the closure of your account to comply with AML/CFT laws.
  - period: indefinitely
    scope: blockchain data
    text: may be retained indefinitely by the nature of the distributed ledger technology
  rights:
  - right: access
    text: You have the right to access, update or to delete the information we have on you
  - right: correction
    text: You have the right to have your information rectified if that information is inaccurate or incomplete.
  - right: object
    text: You have the right to object to our processing of your Personal Data.
  - right: restriction
    text: You have the right to request that we restrict the processing of your Personal Data.
  - right: portability
    text: You have the right to be provided with a copy of your Personal Data in a structured, machine-readable and commonly used format.
  - right: withdraw consent
    text: You have the right to withdraw your consent at any time where we rely on your consent to process your Personal Data.
  role:
    text: This Notice is issued on behalf of the Company as the Controller.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: You may be entitled to prevent us from sharing and/or licensing your personal information to other companies under applicable law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: 'Adequacy Decisions: We will only transfer your Personal Data to countries that have been deemed to provide an adequate level of protection for Personal Data by the European Commission.'
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): Where we use certain service providers, we may use specific contracts approved by the European Commission which give Personal Data the same protection it has within the EEA.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Pred
provenance_date: '2026-11-10'
provider_name: Pred
provider_slug: pred
slug: pred-privacy-policy
source_date: '2026-11-10'
source_filename: pred-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.pred.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Pred\naid: pred\nurl: https://www.pred.app/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Notice is issued on behalf of the Company as the Controller.\ndata_categories:\n- category: contact\n  text: 'Contact Information: Includes your e-mail address, telephone number, discord handle, telegram username,\n    postal address, and any other contact details you provide when signing up for alerts or support.'\n- category: identifying\n  text: 'Identity & KYC Information: Includes your full legal name, date of birth, gender, nationality, hometown,\n    government-issued identification\
  \ details'\n- category: biometric\n  text: biometric data (such as a live photograph or \"selfie\") used strictly for identity verification and fraud\n    prevention.\n- category: financial\n  text: This category also includes billing address and source of funds declarations.\n- category: behavioral\n  text: Includes information about how you use our Website, products, and services\n- category: location\n  text: Includes precise or approximate location data determined from your IP address, GPS, Wi-Fi, or cell-site\n    triangulation.\n- category: device\n  text: Includes your internet protocol (IP) address, browser type and version, time zone setting and location,\n    browser plug-in types and versions, operating system and platform, device attributes (fingerprinting), and other\n    technology on the devices you use to access this Website.\n- category: communication\n  text: 'Correspondence Data: Includes records of your communications with our customer support team, feedback,\n    and\
  \ responses to surveys.'\n- category: other\n  text: Includes your public Digital Wallet address (e.g., Ethereum or Polygon address), your transaction history\n    on the Blockchain (including deposits, withdrawals, token swaps, Information Contracts purchased, and market\n    resolutions), account balances, token holdings\npurposes:\n- purpose: account registration and management\n  text: To register you as a new customer; to manage your account\n- purpose: identity verification and fraud prevention\n  text: To verify your identity; to prevent fraud, money laundering, and terrorist financing\n- purpose: analytics and improvement\n  text: To use data analytics to improve our website, products/services, marketing, customer relationships and experiences\n- purpose: customer support\n  text: To provide customer support; to resolve disputes regarding market resolutions; and to respond to inquiries.\nretention:\n- scope: general personal data\n  period: null\n  text: The Company retains your\
  \ Personal Data for as long as necessary to provide the access to and use of the\n    Website, to fulfil the purposes described above, or for other essential purposes such as complying with our\n    legal obligations, resolving disputes, and enforcing our agreements.\n- scope: KYC data\n  period: 5 to 7 years\n  text: We are often legally required to retain identity verification data for a period of 5 to 7 years after the\n    closure of your account to comply with AML/CFT laws.\n- scope: blockchain data\n  period: indefinitely\n  text: may be retained indefinitely by the nature of the distributed ledger technology\nresidency:\n- region: Panama\n  text: The Services, including the Interface, are made available by us from the Republic of Panama\ntransfers:\n- mechanism: adequacy\n  text: 'Adequacy Decisions: We will only transfer your Personal Data to countries that have been deemed to provide\n    an adequate level of protection for Personal Data by the European Commission.'\n- mechanism:\
  \ SCC\n  text: 'Standard Contractual Clauses (SCCs): Where we use certain service providers, we may use specific contracts\n    approved by the European Commission which give Personal Data the same protection it has within the EEA.'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@pred.app with subject line \"Erasure / Personal Data Deletion\"\n  text: If you should wish to cease use of our Services and have your Personal Data deleted, then you may submit\n    a request.\nrights:\n- right: access\n  text: You have the right to access, update or to delete the information we have on you\n- right: correction\n  text: You have the right to have your information rectified if that information is inaccurate or incomplete.\n- right: object\n  text: You have the right to object to our processing of your Personal Data.\n- right: restriction\n  text: You have the right to request that we restrict the processing of your\
  \ Personal Data.\n- right: portability\n  text: You have the right to be provided with a copy of your Personal Data in a structured, machine-readable and\n    commonly used format.\n- right: withdraw consent\n  text: You have the right to withdraw your consent at any time where we rely on your consent to process your Personal\n    Data.\nsale_or_sharing:\n  stance: conditional\n  text: You may be entitled to prevent us from sharing and/or licensing your personal information to other companies\n    under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/pred/privacy/pred-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Pred's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Prediction Markets
- Sports
- Trading
- Exchange
- Web3
- Blockchain
- Base
- USDC
- Real-Time
---
