---
api_specs:
- filename: due-account-api-openapi.yml
  format: yaml
  label: Due Account API
  slug: due-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-account-api-openapi.yml
- filename: due-account-wallets-api-openapi.yml
  format: yaml
  label: Due Account Wallets API
  slug: due-account-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-account-wallets-api-openapi.yml
- filename: due-blockchain-transfers-api-openapi.yml
  format: yaml
  label: Due Blockchain Transfers API
  slug: due-blockchain-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-blockchain-transfers-api-openapi.yml
- filename: due-channels-api-openapi.yml
  format: yaml
  label: Due Channels API
  slug: due-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-channels-api-openapi.yml
- filename: due-financial-institutions-api-openapi.yml
  format: yaml
  label: Due Financial Institutions API
  slug: due-financial-institutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-financial-institutions-api-openapi.yml
- filename: due-kyc-api-openapi.yml
  format: yaml
  label: Due KYC API
  slug: due-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-kyc-api-openapi.yml
- filename: due-markets-api-openapi.yml
  format: yaml
  label: Due Markets API
  slug: due-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-markets-api-openapi.yml
- filename: due-quote-api-openapi.yml
  format: yaml
  label: Due Quote API
  slug: due-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-quote-api-openapi.yml
- filename: due-recipients-api-openapi.yml
  format: yaml
  label: Due Recipients API
  slug: due-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-recipients-api-openapi.yml
- filename: due-simulate-pay-in-api-openapi.yml
  format: yaml
  label: Due Simulate pay-in API
  slug: due-simulate-pay-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-simulate-pay-in-api-openapi.yml
- filename: due-tos-api-openapi.yml
  format: yaml
  label: Due TOS API
  slug: due-tos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-tos-api-openapi.yml
- filename: due-transfers-api-openapi.yml
  format: yaml
  label: Due Transfers API
  slug: due-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-transfers-api-openapi.yml
- filename: due-usage-api-openapi.yml
  format: yaml
  label: Due Usage API
  slug: due-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-usage-api-openapi.yml
- filename: due-vaults-api-openapi.yml
  format: yaml
  label: Due Vaults API
  slug: due-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-vaults-api-openapi.yml
- filename: due-virtual-accounts-api-openapi.yml
  format: yaml
  label: Due Virtual Accounts API
  slug: due-virtual-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-virtual-accounts-api-openapi.yml
- filename: due-wallets-api-openapi.yml
  format: yaml
  label: Due Wallets API
  slug: due-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-wallets-api-openapi.yml
- filename: due-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Due Webhook Endpoints API
  slug: due-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-webhook-endpoints-api-openapi.yml
- filename: due-webhooks-api-openapi.yml
  format: yaml
  label: Due Webhooks API
  slug: due-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/due/openapi/due-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: full name; identity document number; identity document expiry date
  - category: contact
    text: Contact details, including postal/shipping address, billing address, email address and telephone number
  - category: financial
    text: 'Transaction data, including: transaction date(s); transaction amount; transaction currency'
  - category: biometric
    text: Facial biometric data/attributes extracted from selfies/videos for liveness verification and face matching
  - category: location
    text: geolocation and user interaction data
  - category: device
    text: access logs, IP addresses, technical identifiers and security events
  deletion:
    route: Contact the Data Protection Officer at dpo@due.network
    text: You have the right to request that we delete your personal data in certain circumstances.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Identity verification and KYC/KYB
    text: Identity verification and KYC/KYB, including sanctions screening, beneficial owner verification and identity document checks
  - purpose: Transaction monitoring and fraud prevention
    text: Transaction monitoring, wallet verification and fraud prevention, including automated analysis
  - purpose: Performance of the contract
    text: Performance of the contract, including onboarding, payment processing and customer service
  - purpose: Marketing communications
    text: Marketing communications
  residency:
  - region: EEA and UK
    text: Personal data is mainly stored and processed within the European Economic Area (EEA) and the United Kingdom.
  retention:
  - period: 10 years
    scope: KYC/AML records
    text: 'KYC/AML records and due diligence evidence: 10 years from the end of the business relationship or the execution of an occasional transaction'
  - period: up to 2 years
    scope: Security and anti-fraud records
    text: 'Security and anti-fraud records: retained for a limited period based on proportionality and security needs (generally up to 2 years)'
  - period: 5 years
    scope: Claims and litigation
    text: 'Claims and litigation: retained for the applicable limitation period (generally 5 years under Spanish civil law'
  rights:
  - right: access
    text: the right to obtain information about the processing of your personal data and to access the personal data we hold about you
  - right: rectification
    text: the right to request that we rectify your personal data if it is inaccurate or incomplete
  - right: erasure
    text: You have the right to request that we delete your personal data in certain circumstances.
  - right: objection and restriction
    text: the right to object and the right to request that we restrict the processing of your personal data in certain circumstances
  - right: portability
    text: the right to receive certain personal data in a structured, commonly used and machine-readable format
  - right: withdraw consent
    text: the right to withdraw your consent at any time
  - right: automated decisions
    text: the right not to be subject to a decision based solely on automated processing, including profiling
  role:
    text: we act as the controller of your personal data
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers to Due Payments Inc. we use standard contractual clauses (SCCs) approved by the European Commission
  - mechanism: adequacy
    text: 'Argentina: recognised as an adequate country by the European Commission.'
  - mechanism: BCR
    text: 'Intra-group transfers: may be based on binding corporate rules (BCRs) where applicable.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Due
provenance_date: '2026-11-09'
provider_name: Due
provider_slug: due
slug: due-privacy-policy
source_date: '2026-11-09'
source_filename: due-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.opendue.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Due\naid: due\nurl: https://www.opendue.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: we act as the controller of your personal data\ndata_categories:\n- category: identifying\n  text: full name; identity document number; identity document expiry date\n- category: contact\n  text: Contact details, including postal/shipping address, billing address, email address and telephone number\n- category: financial\n  text: 'Transaction data, including: transaction date(s); transaction amount; transaction currency'\n- category: biometric\n  text: Facial biometric data/attributes\
  \ extracted from selfies/videos for liveness verification and face matching\n- category: location\n  text: geolocation and user interaction data\n- category: device\n  text: access logs, IP addresses, technical identifiers and security events\npurposes:\n- purpose: Identity verification and KYC/KYB\n  text: Identity verification and KYC/KYB, including sanctions screening, beneficial owner verification and identity\n    document checks\n- purpose: Transaction monitoring and fraud prevention\n  text: Transaction monitoring, wallet verification and fraud prevention, including automated analysis\n- purpose: Performance of the contract\n  text: Performance of the contract, including onboarding, payment processing and customer service\n- purpose: Marketing communications\n  text: Marketing communications\nretention:\n- scope: KYC/AML records\n  period: 10 years\n  text: 'KYC/AML records and due diligence evidence: 10 years from the end of the business relationship or the execution\n    of an\
  \ occasional transaction'\n- scope: Security and anti-fraud records\n  period: up to 2 years\n  text: 'Security and anti-fraud records: retained for a limited period based on proportionality and security needs\n    (generally up to 2 years)'\n- scope: Claims and litigation\n  period: 5 years\n  text: 'Claims and litigation: retained for the applicable limitation period (generally 5 years under Spanish civil\n    law'\nresidency:\n- region: EEA and UK\n  text: Personal data is mainly stored and processed within the European Economic Area (EEA) and the United Kingdom.\ntransfers:\n- mechanism: SCC\n  text: For transfers to Due Payments Inc. we use standard contractual clauses (SCCs) approved by the European Commission\n- mechanism: adequacy\n  text: 'Argentina: recognised as an adequate country by the European Commission.'\n- mechanism: BCR\n  text: 'Intra-group transfers: may be based on binding corporate rules (BCRs) where applicable.'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the Data Protection Officer at dpo@due.network\n  text: You have the right to request that we delete your personal data in certain circumstances.\nrights:\n- right: access\n  text: the right to obtain information about the processing of your personal data and to access the personal data\n    we hold about you\n- right: rectification\n  text: the right to request that we rectify your personal data if it is inaccurate or incomplete\n- right: erasure\n  text: You have the right to request that we delete your personal data in certain circumstances.\n- right: objection and restriction\n  text: the right to object and the right to request that we restrict the processing of your personal data in certain\n    circumstances\n- right: portability\n  text: the right to receive certain personal data in a structured, commonly used and machine-readable format\n- right: withdraw consent\n  text: the right to withdraw your consent\
  \ at any time\n- right: automated decisions\n  text: the right not to be subject to a decision based solely on automated processing, including profiling\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/due/privacy/due-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 26 quoted statements, read from Due's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Cross-Border Payments
- Stablecoins
- Fintech
- Virtual Accounts
- Foreign Exchange
- KYC
- Wallets
---
