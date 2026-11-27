---
api_specs:
- filename: login-gov-authentication-api-openapi.yml
  format: yaml
  label: Login.gov Authentication API
  slug: login-gov-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-authentication-api-openapi.yml
- filename: login-gov-authorization-api-openapi.yml
  format: yaml
  label: Login.gov Authorization API
  slug: login-gov-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-authorization-api-openapi.yml
- filename: login-gov-discovery-api-openapi.yml
  format: yaml
  label: Login.gov Discovery API
  slug: login-gov-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-discovery-api-openapi.yml
- filename: login-gov-logout-api-openapi.yml
  format: yaml
  label: Login.gov Logout API
  slug: login-gov-logout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-logout-api-openapi.yml
- filename: login-gov-metadata-api-openapi.yml
  format: yaml
  label: Login.gov Metadata API
  slug: login-gov-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-metadata-api-openapi.yml
- filename: login-gov-token-api-openapi.yml
  format: yaml
  label: Login.gov Token API
  slug: login-gov-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-token-api-openapi.yml
- filename: login-gov-user-info-api-openapi.yml
  format: yaml
  label: Login.gov User Info API
  slug: login-gov-user-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/login-gov/openapi/login-gov-user-info-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: For authentication to establish a secure account, we need your name, email address, and an authentication method.
  - category: identifying
    text: Identity proofing requires more sensitive information such as a social security number, address, phone number, and a U.S. based federal or state ID.
  - category: demographic
    text: A self-photograph is needed in cases where partners require verification through biometric comparison as further proof of your identity.
  - category: device
    text: To prevent it, we look at the device you’re using, how you interact with the page, and the information you provide during identity verification.
  - category: behavioral
    text: We aggregate the pages visited, web browser type and version, and the length of the session to help us improve the Login.gov experience.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Identity verification and account access
    text: The information that you submit is used to create or update your Login.gov account and give you access to Login.gov’s partner agencies.
  - purpose: Fraud prevention
    text: We ask for information to authenticate your account, prove your identity, and protect against fraud.
  - purpose: Service improvement
    text: We aggregate the pages visited, web browser type and version, and the length of the session to help us improve the Login.gov experience.
  retention:
  - period: up to one year
    scope: Attempt information
    text: We keep attempt information decryptable by Login for up to one year, and the encrypted documents for partner agencies longer because identity theft is often discovered later, when a victim or an agency reports it.
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
name: Login.gov
provenance_date: '2026-11-09'
provider_name: Login.gov
provider_slug: login-gov
slug: login-gov-privacy-policy
source_date: '2026-11-09'
source_filename: login-gov-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.login.gov/policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Login.gov\naid: login-gov\nurl: https://www.login.gov/policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: For authentication to establish a secure account, we need your name, email address, and an authentication\n    method.\n- category: identifying\n  text: Identity proofing requires more sensitive information such as a social security number, address, phone number,\n    and a U.S. based federal or state ID.\n- category: demographic\n  text: A self-photograph is needed in cases where partners require verification through biometric\
  \ comparison as\n    further proof of your identity.\n- category: device\n  text: To prevent it, we look at the device you’re using, how you interact with the page, and the information you\n    provide during identity verification.\n- category: behavioral\n  text: We aggregate the pages visited, web browser type and version, and the length of the session to help us improve\n    the Login.gov experience.\npurposes:\n- purpose: Identity verification and account access\n  text: The information that you submit is used to create or update your Login.gov account and give you access to\n    Login.gov’s partner agencies.\n- purpose: Fraud prevention\n  text: We ask for information to authenticate your account, prove your identity, and protect against fraud.\n- purpose: Service improvement\n  text: We aggregate the pages visited, web browser type and version, and the length of the session to help us improve\n    the Login.gov experience.\nretention:\n- scope: Attempt information\n  period: up to\
  \ one year\n  text: We keep attempt information decryptable by Login for up to one year, and the encrypted documents for partner\n    agencies longer because identity theft is often discovered later, when a victim or an agency reports it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/login-gov/privacy/login-gov-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 9 quoted statements, read from Login.gov's own page on 2026-11-09.
synthetic: false
tags:
- Government
- Federal
- GSA
- Identity
- Authentication
- SSO
- OpenID Connect
- SAML
- IAL2
- AAL2
- Identity Federation
---
