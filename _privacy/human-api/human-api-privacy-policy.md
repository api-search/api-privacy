---
api_specs:
- filename: human-api-admin-api-openapi.yml
  format: yaml
  label: Human API Admin API
  slug: human-api-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-admin-api-openapi.yml
- filename: human-api-connect-api-openapi.yml
  format: yaml
  label: Human API Connect API
  slug: human-api-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-connect-api-openapi.yml
- filename: human-api-orders-api-openapi.yml
  format: yaml
  label: Human API Orders API
  slug: human-api-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-orders-api-openapi.yml
- filename: human-api-reports-api-openapi.yml
  format: yaml
  label: Human API Reports API
  slug: human-api-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-reports-api-openapi.yml
- filename: human-api-resources-api-openapi.yml
  format: yaml
  label: Human API Resources API
  slug: human-api-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-resources-api-openapi.yml
- filename: human-api-subscriptions-api-openapi.yml
  format: yaml
  label: Human API Subscriptions API
  slug: human-api-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-subscriptions-api-openapi.yml
- filename: human-api-users-api-openapi.yml
  format: yaml
  label: Human API Users API
  slug: human-api-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/human-api/openapi/human-api-users-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal identifiers such as a real name, alias, postal address, telephone or mobile contact number, unique personal identifier, email address, account name, and other similar identifiers
  - category: health
    text: Individual health conditions, treatment, diseases, or diagnosis
  - category: health
    text: Genetic data
  - category: biometric
    text: Biometric data
  - category: health
    text: Reproductive or sexual health information
  deletion:
    route: Contact via details in Contact section
    text: You have the right to ask that we delete your personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your personal information to provide our services to you including to support life insurance underwriting, if applicable, for statistical purposes, and to improve our products and services.
  - purpose: Life insurance underwriting
    text: if you are utilizing Human API for the purposes of life insurance underwriting, your personal information may be transferred to our affiliate LexisNexis Risk Solutions Inc.
  retention:
  - period: null
    scope: Personal information
    text: We retain your personal information for as long as necessary to provide our services and fulfill the transactions you have requested
  rights:
  - right: Access
    text: Right to Access — You have the right to ask whether we are processing your personal information, access a copy of that data, and learn how we use it.
  - right: Delete
    text: Right to Delete — You have the right to ask that we delete your personal information.
  - right: Correction
    text: Right of Correction — You have the right to ask that we fix any errors in the personal information that we collect.
  - right: Withdraw consent
    text: Right to Withdraw Consent — If we are processing your personal information with your consent, you have the right to withdraw that consent.
  - right: Appeal
    text: If we refuse to act on your request within a reasonable period after you have received notice of the refusal you have the right to file an appeal.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information within the scope of the application of the U.S. Privacy Laws.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Human API
provenance_date: '2026-11-09'
provider_name: Human API
provider_slug: human-api
slug: human-api-privacy-policy
source_date: '2026-11-09'
source_filename: human-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://my.humanapi.co/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Human API\naid: human-api\nurl: https://my.humanapi.co/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personal identifiers such as a real name, alias, postal address, telephone or mobile contact number, unique\n    personal identifier, email address, account name, and other similar identifiers\n- category: health\n  text: Individual health conditions, treatment, diseases, or diagnosis\n- category: health\n  text: Genetic data\n- category: biometric\n  text: Biometric data\n- category: health\n  text: Reproductive or sexual\
  \ health information\npurposes:\n- purpose: Provide services\n  text: We use your personal information to provide our services to you including to support life insurance underwriting,\n    if applicable, for statistical purposes, and to improve our products and services.\n- purpose: Life insurance underwriting\n  text: if you are utilizing Human API for the purposes of life insurance underwriting, your personal information\n    may be transferred to our affiliate LexisNexis Risk Solutions Inc.\nretention:\n- scope: Personal information\n  period: null\n  text: We retain your personal information for as long as necessary to provide our services and fulfill the transactions\n    you have requested\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact via details in Contact section\n  text: You have the right to ask that we delete your personal information.\nrights:\n- right: Access\n  text:\
  \ Right to Access — You have the right to ask whether we are processing your personal information, access\n    a copy of that data, and learn how we use it.\n- right: Delete\n  text: Right to Delete — You have the right to ask that we delete your personal information.\n- right: Correction\n  text: Right of Correction — You have the right to ask that we fix any errors in the personal information that\n    we collect.\n- right: Withdraw consent\n  text: Right to Withdraw Consent — If we are processing your personal information with your consent, you have the\n    right to withdraw that consent.\n- right: Appeal\n  text: If we refuse to act on your request within a reasonable period after you have received notice of the refusal\n    you have the right to file an appeal.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information within the scope of the application of the U.S. Privacy Laws.\n"
source_yaml_url: https://artifacts.apis.io/human-api/privacy/human-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Human API's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- United States
- Health Data
- Electronic Health Records
- Interoperability
- Remote Monitoring
- Wearables
- Life Insurance
- Clinical Data
- Health API
---
