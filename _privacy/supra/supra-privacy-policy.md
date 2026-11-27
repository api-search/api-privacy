---
api_specs:
- filename: supra-accounts-api-openapi.yml
  format: yaml
  label: Supra Accounts API
  slug: supra-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-accounts-api-openapi.yml
- filename: supra-block-api-openapi.yml
  format: yaml
  label: Supra Block API
  slug: supra-block-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-block-api-openapi.yml
- filename: supra-consensus-api-openapi.yml
  format: yaml
  label: Supra Consensus API
  slug: supra-consensus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-consensus-api-openapi.yml
- filename: supra-events-api-openapi.yml
  format: yaml
  label: Supra Events API
  slug: supra-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-events-api-openapi.yml
- filename: supra-faucet-api-openapi.yml
  format: yaml
  label: Supra Faucet API
  slug: supra-faucet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-faucet-api-openapi.yml
- filename: supra-proofs-api-openapi.yml
  format: yaml
  label: Supra Proofs API
  slug: supra-proofs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-proofs-api-openapi.yml
- filename: supra-tables-api-openapi.yml
  format: yaml
  label: Supra Tables API
  slug: supra-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-tables-api-openapi.yml
- filename: supra-transactions-api-openapi.yml
  format: yaml
  label: Supra Transactions API
  slug: supra-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-transactions-api-openapi.yml
- filename: supra-version-api-openapi.yml
  format: yaml
  label: Supra Version API
  slug: supra-version-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-version-api-openapi.yml
- filename: supra-view-api-openapi.yml
  format: yaml
  label: Supra View API
  slug: supra-view-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-view-api-openapi.yml
- filename: supra-websocket-api-openapi.yml
  format: yaml
  label: Supra Web Socket API
  slug: supra-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supra/openapi/supra-websocket-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers, such as name, mailing address, e-mail address, or any other information that the Services collect
  - category: financial
    text: Financial Data includes bank account, wallet IDs and payment card details.
  - category: biometric
    text: Information required to verify your identity (which we will do through our service provider Zyphe), including your Biometric Information
  - category: device
    text: Information about the device you use to access the Services, and its characteristics and functionality
  - category: location
    text: We may also receive location data passed to us from third-party services or GPS-enabled devices that you have set up
  - category: behavioral
    text: Your browsing history, including the areas within our Services that you visit and your activities there
  deletion:
    route: Email the company to delete or deactivate an account
    text: If you wish to delete or deactivate your account, please email us at [email protected] , or opt-out on our Services, but note that we may retain certain information as required by law or for legitimate business purposes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve Services
    text: To provide, maintain and improve the Services;
  - purpose: Behavioral tracking and advertising
    text: For behavioral tracking, profiling and advertising;
  - purpose: Identity verification and fraud prevention
    text: To verify your identity and prevent fraud
  - purpose: Marketing
    text: To contact you about our own and third-parties’ goods and services that we think may be of interest to you;
  retention:
  - period: null
    scope: Personal data generally
    text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it for, including for the purposes of satisfying any legal, accounting, or reporting requirements.
  - period: a brief period of time
    scope: Website log data
    text: we maintain website log data for a brief period of time
  rights:
  - right: Access
    text: Request access to your personal data (commonly known as a “data subject access request”).
  - right: Correction
    text: Request correction of the personal data that we hold about you.
  - right: Erasure
    text: Request erasure of your personal data.
  - right: Objection
    text: Object to processing of your personal data where we are relying on a legitimate interest
  - right: Opt out of sale
    text: You have the right to request that your Personal Information not be sold to third parties.
  role:
    text: 'Entropy Foundation, (Switzerland: CHE.383.364.961) is the controller and responsible for your personal data.'
    value: controller
  sale_or_sharing:
    stance: allowed
    text: We sell Personal Information, as the term “sale” is defined pursuant to the CCPA, but not in exchange for monetary compensation.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where we use certain service providers, we may use specific contracts approved by the European Commission which give personal data the same protection it has in Europe.
  - mechanism: adequacy
    text: We will only transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data by the European Commission or other applicable regulatory body
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Supra
provenance_date: '2026-11-10'
provider_name: Supra
provider_slug: supra
slug: supra-privacy-policy
source_date: '2026-11-10'
source_filename: supra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://supra.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Supra\naid: supra\nurl: https://supra.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'Entropy Foundation, (Switzerland: CHE.383.364.961) is the controller and responsible for your personal\n    data.'\ndata_categories:\n- category: identifying\n  text: Identifiers, such as name, mailing address, e-mail address, or any other information that the Services collect\n- category: financial\n  text: Financial Data includes bank account, wallet IDs and payment card details.\n- category: biometric\n  text: Information required to verify your identity (which we\
  \ will do through our service provider Zyphe), including\n    your Biometric Information\n- category: device\n  text: Information about the device you use to access the Services, and its characteristics and functionality\n- category: location\n  text: We may also receive location data passed to us from third-party services or GPS-enabled devices that you\n    have set up\n- category: behavioral\n  text: Your browsing history, including the areas within our Services that you visit and your activities there\npurposes:\n- purpose: Provide and improve Services\n  text: To provide, maintain and improve the Services;\n- purpose: Behavioral tracking and advertising\n  text: For behavioral tracking, profiling and advertising;\n- purpose: Identity verification and fraud prevention\n  text: To verify your identity and prevent fraud\n- purpose: Marketing\n  text: To contact you about our own and third-parties’ goods and services that we think may be of interest to you;\nretention:\n- scope: Personal\
  \ data generally\n  period: null\n  text: We will only retain your personal data for as long as necessary to fulfill the purposes we collected it\n    for, including for the purposes of satisfying any legal, accounting, or reporting requirements.\n- scope: Website log data\n  period: a brief period of time\n  text: we maintain website log data for a brief period of time\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where we use certain service providers, we may use specific contracts approved by the European Commission\n    which give personal data the same protection it has in Europe.\n- mechanism: adequacy\n  text: We will only transfer your personal data to countries that have been deemed to provide an adequate level\n    of protection for personal data by the European Commission or other applicable regulatory body\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the company to delete or deactivate an account\n\
  \  text: If you wish to delete or deactivate your account, please email us at [email protected] , or opt-out on our\n    Services, but note that we may retain certain information as required by law or for legitimate business purposes.\nrights:\n- right: Access\n  text: Request access to your personal data (commonly known as a “data subject access request”).\n- right: Correction\n  text: Request correction of the personal data that we hold about you.\n- right: Erasure\n  text: Request erasure of your personal data.\n- right: Objection\n  text: Object to processing of your personal data where we are relying on a legitimate interest\n- right: Opt out of sale\n  text: You have the right to request that your Personal Information not be sold to third parties.\nsale_or_sharing:\n  stance: allowed\n  text: We sell Personal Information, as the term “sale” is defined pursuant to the CCPA, but not in exchange for\n    monetary compensation.\n"
source_yaml_url: https://artifacts.apis.io/supra/privacy/supra-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Supra's own page on 2026-11-10.
synthetic: false
tags:
- Blockchain
- Layer 1
- Oracle
- Web3
- Market Data
- Smart Contracts
- Verifiable Randomness
- Cross-Chain Bridge
- Automation
- Move
- Cryptocurrency
- DeFi
---
