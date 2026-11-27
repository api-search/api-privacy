---
api_specs:
- filename: authelia-authentication-api-openapi.yml
  format: yaml
  label: Authelia Authentication API
  slug: authelia-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-authentication-api-openapi.yml
- filename: authelia-authorization-api-openapi.yml
  format: yaml
  label: Authelia Authorization API
  slug: authelia-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-authorization-api-openapi.yml
- filename: authelia-first-factor-api-openapi.yml
  format: yaml
  label: Authelia First Factor API
  slug: authelia-first-factor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-first-factor-api-openapi.yml
- filename: authelia-oauth-2-0-api-openapi.yml
  format: yaml
  label: Authelia OAuth 2.0 API
  slug: authelia-oauth-2-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-oauth-2-0-api-openapi.yml
- filename: authelia-openid-connect-1-0-api-openapi.yml
  format: yaml
  label: Authelia OpenID Connect 1.0 API
  slug: authelia-openid-connect-1-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-openid-connect-1-0-api-openapi.yml
- filename: authelia-password-change-api-openapi.yml
  format: yaml
  label: Authelia Password Change API
  slug: authelia-password-change-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-password-change-api-openapi.yml
- filename: authelia-password-reset-api-openapi.yml
  format: yaml
  label: Authelia Password Reset API
  slug: authelia-password-reset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-password-reset-api-openapi.yml
- filename: authelia-second-factor-api-openapi.yml
  format: yaml
  label: Authelia Second Factor API
  slug: authelia-second-factor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-second-factor-api-openapi.yml
- filename: authelia-state-api-openapi.yml
  format: yaml
  label: Authelia State API
  slug: authelia-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-state-api-openapi.yml
- filename: authelia-user-elevation-api-openapi.yml
  format: yaml
  label: Authelia User Elevation API
  slug: authelia-user-elevation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-user-elevation-api-openapi.yml
- filename: authelia-user-information-api-openapi.yml
  format: yaml
  label: Authelia User Information API
  slug: authelia-user-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-user-information-api-openapi.yml
- filename: authelia-utilities-api-openapi.yml
  format: yaml
  label: Authelia Utilities API
  slug: authelia-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authelia/openapi/authelia-utilities-api-openapi.yml
claim_count: 5
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username and IP address are recorded and logged for security related events for auditing purposes.
  - category: device
    text: 'Cookies: A session cookie necessary for the application to operate.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: security auditing
    text: Username and IP address are recorded and logged for security related events for auditing purposes.
  - purpose: application operation
    text: 'Local Storage: A language preference necessary for the application to operate.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No information is shared with, sent to or sold to third-parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Authelia
provenance_date: '2026-11-09'
provider_name: Authelia
provider_slug: authelia
slug: authelia-privacy-policy
source_date: '2026-11-09'
source_filename: authelia-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.authelia.com/policies/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Authelia\naid: authelia\nurl: https://www.authelia.com/policies/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Username and IP address are recorded and logged for security related events for auditing purposes.\n- category: device\n  text: 'Cookies: A session cookie necessary for the application to operate.'\npurposes:\n- purpose: security auditing\n  text: Username and IP address are recorded and logged for security related events for auditing purposes.\n- purpose: application operation\n  text: 'Local Storage: A language preference\
  \ necessary for the application to operate.'\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No information is shared with, sent to or sold to third-parties.\n"
source_yaml_url: https://artifacts.apis.io/authelia/privacy/authelia-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- sale_or_sharing
summary_line: 5 quoted statements, read from Authelia's own page on 2026-11-09.
synthetic: false
tags:
- Authentication
- Authorization
- LDAP
- MFA
- Open Source
- OpenID Connect
- Self-Hosted
- SSO
- Identity Federation
---
