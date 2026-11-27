---
api_specs:
- filename: hex-pm-api-keys-api-openapi.yml
  format: yaml
  label: Hex.pm API Keys API
  slug: hex-pm-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-api-keys-api-openapi.yml
- filename: hex-pm-authentication-api-openapi.yml
  format: yaml
  label: Hex.pm Authentication API
  slug: hex-pm-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-authentication-api-openapi.yml
- filename: hex-pm-documentation-api-openapi.yml
  format: yaml
  label: Hex.pm Documentation API
  slug: hex-pm-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-documentation-api-openapi.yml
- filename: hex-pm-index-api-openapi.yml
  format: yaml
  label: Hex.pm Index API
  slug: hex-pm-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-index-api-openapi.yml
- filename: hex-pm-organizations-api-openapi.yml
  format: yaml
  label: Hex.pm Organizations API
  slug: hex-pm-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-organizations-api-openapi.yml
- filename: hex-pm-package-owners-api-openapi.yml
  format: yaml
  label: Hex.pm Package Owners API
  slug: hex-pm-package-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-package-owners-api-openapi.yml
- filename: hex-pm-packages-api-openapi.yml
  format: yaml
  label: Hex.pm Packages API
  slug: hex-pm-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-packages-api-openapi.yml
- filename: hex-pm-releases-api-openapi.yml
  format: yaml
  label: Hex.pm Releases API
  slug: hex-pm-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-releases-api-openapi.yml
- filename: hex-pm-repositories-api-openapi.yml
  format: yaml
  label: Hex.pm Repositories API
  slug: hex-pm-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-repositories-api-openapi.yml
- filename: hex-pm-users-api-openapi.yml
  format: yaml
  label: Hex.pm Users API
  slug: hex-pm-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-users-api-openapi.yml
- filename: hex-pm-utilities-api-openapi.yml
  format: yaml
  label: Hex.pm Utilities API
  slug: hex-pm-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-utilities-api-openapi.yml
- filename: hex-pm-oauth-api-openapi.yml
  format: yaml
  label: Hex.pm O Auth API
  slug: hex-pm-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hex-pm/openapi/hex-pm-oauth-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: To register you have to provide a username and an email address, and a password unless you sign up with GitHub
  - category: contact
    text: your email address, which is shown by default and which you can hide in your dashboard
  - category: financial
    text: Organizations with a paid subscription provide billing details such as the billing name, address and VAT number.
  - category: location
    text: We also record the IP address the payment details were entered from and the country it resolves to
  - category: device
    text: Requests to the hex.pm website and API are logged with the client IP address, user agent and referrer
  - category: communication
    text: Emails to @hex.pm addresses are stored, including the sender's address and the contents.
  deletion:
    route: dashboard
    text: You can delete your account in the dashboard.
  dpa:
    available: true
    text: The organization is the controller of this content and we process it under the Data Processing Agreement
    url: null
  purposes:
  - purpose: operate account and deliver service
    text: We process account data to operate your account and deliver the service, so the legal basis is our contract with you.
  - purpose: security and abuse investigation
    text: We use them for security, for investigating abuse and to compute the aggregate download counts shown on hex.pm.
  - purpose: billing and tax records
    text: The legal bases are our contract with the organization, for charging for the service, and legal obligation
  - purpose: coordinated vulnerability handling
    text: The legal basis for the disclosure is our legitimate interest, shared with the ecosystem, in coordinated handling of security vulnerabilities.
  residency:
  - region: United States
    text: Account and package data is stored in the United States on Google Cloud Platform and Amazon AWS servers.
  retention:
  - period: as long as your account exists
    scope: account data
    text: We keep it for as long as your account exists.
  - period: indefinitely
    scope: published public packages
    text: Published packages stay available indefinitely, including after the publisher deletes their account, unless removed under our policies.
  - period: 90 days
    scope: organization private content after subscription ends
    text: When a subscription or a free trial ends we keep the organization's content for 90 days so the organization can retrieve it
  - period: three years
    scope: request logs for public packages
    text: Entries for public packages and documentation keep the IP address and the key or token for three years
  - period: ten years
    scope: hex.pm website and API request logs
    text: We keep these logs for ten years.
  - period: indefinitely
    scope: audit log entries
    text: We keep audit log entries indefinitely, because their purpose is to be a permanent record of what changed.
  - period: as long as that law requires
    scope: billing and tax records
    text: We keep those records for as long as that law requires.
  rights:
  - right: access
    text: You can ask us for access to the personal data we hold about you
  - right: rectification, erasure, restriction
    text: for rectification, erasure, restriction of processing, or a copy of the data you provided in a portable format
  - right: portability
    text: a copy of the data you provided in a portable format
  - right: objection
    text: You can object to any processing we base on legitimate interests.
  - right: withdraw consent
    text: Where processing is based on consent, you can withdraw it at any time without affecting what was done before.
  - right: complaint to supervisory authority
    text: If you believe we're processing your personal data unlawfully you can lodge a complaint with a supervisory authority.
  role:
    text: We're the data controller for the processing described in this policy.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The third party providers we use to operate the service process personal data on our behalf and are listed on the Subprocessors page.
    url: null
  transfers:
  - mechanism: DPF
    text: the European Commission's adequacy decision for the EU-US Data Privacy Framework, where that provider is certified
  - mechanism: SCC
    text: the Standard Contractual Clauses adopted by the European Commission, together with the UK Addendum and the Swiss amendments where those apply
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hex.pm
provenance_date: '2026-11-09'
provider_name: Hex.pm
provider_slug: hex-pm
slug: hex-pm-privacy-policy
source_date: '2026-11-09'
source_filename: hex-pm-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hex.pm/policies/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hex.pm\naid: hex-pm\nurl: https://hex.pm/policies/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We're the data controller for the processing described in this policy.\ndata_categories:\n- category: identifying\n  text: To register you have to provide a username and an email address, and a password unless you sign up with\n    GitHub\n- category: contact\n  text: your email address, which is shown by default and which you can hide in your dashboard\n- category: financial\n  text: Organizations with a paid subscription provide billing details such as the billing name, address and VAT\n  \
  \  number.\n- category: location\n  text: We also record the IP address the payment details were entered from and the country it resolves to\n- category: device\n  text: Requests to the hex.pm website and API are logged with the client IP address, user agent and referrer\n- category: communication\n  text: Emails to @hex.pm addresses are stored, including the sender's address and the contents.\npurposes:\n- purpose: operate account and deliver service\n  text: We process account data to operate your account and deliver the service, so the legal basis is our contract\n    with you.\n- purpose: security and abuse investigation\n  text: We use them for security, for investigating abuse and to compute the aggregate download counts shown on\n    hex.pm.\n- purpose: billing and tax records\n  text: The legal bases are our contract with the organization, for charging for the service, and legal obligation\n- purpose: coordinated vulnerability handling\n  text: The legal basis for the disclosure\
  \ is our legitimate interest, shared with the ecosystem, in coordinated\n    handling of security vulnerabilities.\nretention:\n- scope: account data\n  period: as long as your account exists\n  text: We keep it for as long as your account exists.\n- scope: published public packages\n  period: indefinitely\n  text: Published packages stay available indefinitely, including after the publisher deletes their account, unless\n    removed under our policies.\n- scope: organization private content after subscription ends\n  period: 90 days\n  text: When a subscription or a free trial ends we keep the organization's content for 90 days so the organization\n    can retrieve it\n- scope: request logs for public packages\n  period: three years\n  text: Entries for public packages and documentation keep the IP address and the key or token for three years\n- scope: hex.pm website and API request logs\n  period: ten years\n  text: We keep these logs for ten years.\n- scope: audit log entries\n  period:\
  \ indefinitely\n  text: We keep audit log entries indefinitely, because their purpose is to be a permanent record of what changed.\n- scope: billing and tax records\n  period: as long as that law requires\n  text: We keep those records for as long as that law requires.\nresidency:\n- region: United States\n  text: Account and package data is stored in the United States on Google Cloud Platform and Amazon AWS servers.\ntransfers:\n- mechanism: DPF\n  text: the European Commission's adequacy decision for the EU-US Data Privacy Framework, where that provider is\n    certified\n- mechanism: SCC\n  text: the Standard Contractual Clauses adopted by the European Commission, together with the UK Addendum and the\n    Swiss amendments where those apply\nsubprocessors:\n  url: null\n  text: The third party providers we use to operate the service process personal data on our behalf and are listed\n    on the Subprocessors page.\ndpa:\n  available: true\n  url: null\n  text: The organization is the\
  \ controller of this content and we process it under the Data Processing Agreement\ndeletion:\n  route: dashboard\n  text: You can delete your account in the dashboard.\nrights:\n- right: access\n  text: You can ask us for access to the personal data we hold about you\n- right: rectification, erasure, restriction\n  text: for rectification, erasure, restriction of processing, or a copy of the data you provided in a portable\n    format\n- right: portability\n  text: a copy of the data you provided in a portable format\n- right: objection\n  text: You can object to any processing we base on legitimate interests.\n- right: withdraw consent\n  text: Where processing is based on consent, you can withdraw it at any time without affecting what was done before.\n- right: complaint to supervisory authority\n  text: If you believe we're processing your personal data unlawfully you can lodge a complaint with a supervisory\n    authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hex-pm/privacy/hex-pm-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 30 quoted statements, read from Hex.pm's own page on 2026-11-09.
synthetic: false
tags:
- Package Registry
- Erlang
- Elixir
- Gleam
- BEAM
- Open Source
- Package Manager
---
