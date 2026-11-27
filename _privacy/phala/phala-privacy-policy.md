---
api_specs:
- filename: phala-apps-api-openapi.yml
  format: yaml
  label: Phala Network Apps API
  slug: phala-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-api-openapi.yml
- filename: phala-apps-kms-info-api-openapi.yml
  format: yaml
  label: Phala Network Apps Kms Info API
  slug: phala-apps-kms-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-kms-info-api-openapi.yml
- filename: phala-apps-pending-updates-api-openapi.yml
  format: yaml
  label: Phala Network Apps Pending Updates API
  slug: phala-apps-pending-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-pending-updates-api-openapi.yml
- filename: phala-attestations-api-openapi.yml
  format: yaml
  label: Phala Network Attestations API
  slug: phala-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-attestations-api-openapi.yml
- filename: phala-cvms-api-openapi.yml
  format: yaml
  label: Phala Network CVMs API
  slug: phala-cvms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-cvms-api-openapi.yml
- filename: phala-cvms-network-config-api-openapi.yml
  format: yaml
  label: Phala Network Cvms Network Config API
  slug: phala-cvms-network-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-cvms-network-config-api-openapi.yml
- filename: phala-instance-types-api-openapi.yml
  format: yaml
  label: Phala Network Instance Types API
  slug: phala-instance-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-instance-types-api-openapi.yml
- filename: phala-kms-api-openapi.yml
  format: yaml
  label: Phala Network KMS API
  slug: phala-kms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-kms-api-openapi.yml
- filename: phala-ssh-keys-api-openapi.yml
  format: yaml
  label: Phala Network SSH Keys API
  slug: phala-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-ssh-keys-api-openapi.yml
- filename: phala-webhooks-api-openapi.yml
  format: yaml
  label: Phala Network Webhooks API
  slug: phala-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-webhooks-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email addresses serve as the unique identifier for user accounts.'
  - category: device
    text: Cookies to store user preferences, IP addresses, browser User Agents, and header information for anti-spam purposes (retained for six months).
  - category: financial
    text: Payments, including credit card transactions, are processed via third-party payment platforms that may uniquely identify users.
  deletion:
    route: user request or account deletion
    text: Users may request deletion of their accounts, which includes permanent deletion of TEE-stored business data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to deliver our Services, such as processing transactions, verifying identities, and facilitating user interactions.
  - purpose: Measure performance
    text: We use analytics tools to understand how our Services are used.
  - purpose: Security and fraud prevention
    text: We process information to detect, prevent, and respond to fraud, unauthorized access, security threats, and technical issues that may compromise our users or Services and comply with legal obligations.
  retention:
  - period: six months
    scope: IP logs for anti-spam
    text: 'IP logs for anti-spam purposes: Retained for six months.'
  - period: null
    scope: TEE-stored business information
    text: 'TEE-stored business information: Permanently deleted upon user request.'
  rights:
  - right: opt out of marketing
    text: Users may opt out of marketing communications.
  - right: account deletion
    text: Users may request deletion of their accounts, which includes permanent deletion of TEE-stored business data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Phala Network
provenance_date: '2026-11-10'
provider_name: Phala Network
provider_slug: phala
slug: phala-privacy-policy
source_date: '2026-11-10'
source_filename: phala-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://phala.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Phala Network\naid: phala\nurl: https://phala.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email addresses serve as the unique identifier for user accounts.'\n- category: device\n  text: Cookies to store user preferences, IP addresses, browser User Agents, and header information for anti-spam\n    purposes (retained for six months).\n- category: financial\n  text: Payments, including credit card transactions, are processed via third-party payment platforms that may uniquely\n    identify users.\npurposes:\n\
  - purpose: Provide services\n  text: We use your information to deliver our Services, such as processing transactions, verifying identities,\n    and facilitating user interactions.\n- purpose: Measure performance\n  text: We use analytics tools to understand how our Services are used.\n- purpose: Security and fraud prevention\n  text: We process information to detect, prevent, and respond to fraud, unauthorized access, security threats,\n    and technical issues that may compromise our users or Services and comply with legal obligations.\nretention:\n- scope: IP logs for anti-spam\n  period: six months\n  text: 'IP logs for anti-spam purposes: Retained for six months.'\n- scope: TEE-stored business information\n  period: null\n  text: 'TEE-stored business information: Permanently deleted upon user request.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: user request or account deletion\n\
  \  text: Users may request deletion of their accounts, which includes permanent deletion of TEE-stored business data.\nrights:\n- right: opt out of marketing\n  text: Users may opt out of marketing communications.\n- right: account deletion\n  text: Users may request deletion of their accounts, which includes permanent deletion of TEE-stored business data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phala/privacy/phala-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from Phala Network's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Confidential Computing
- Trusted Execution Environments
- Inference
- Cloud Infrastructure
- Attestation
- LLM Router
---
