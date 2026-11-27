---
api_specs:
- filename: anteproof-com-account-api-openapi.yml
  format: yaml
  label: Anteproof Account API
  slug: anteproof-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-account-api-openapi.yml
- filename: anteproof-com-anchor-api-openapi.yml
  format: yaml
  label: Anteproof Anchor API
  slug: anteproof-com-anchor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-anchor-api-openapi.yml
- filename: anteproof-com-billing-api-openapi.yml
  format: yaml
  label: Anteproof Billing API
  slug: anteproof-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-billing-api-openapi.yml
- filename: anteproof-com-calibration-api-openapi.yml
  format: yaml
  label: Anteproof Calibration API
  slug: anteproof-com-calibration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-calibration-api-openapi.yml
- filename: anteproof-com-chain-api-openapi.yml
  format: yaml
  label: Anteproof Chain API
  slug: anteproof-com-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-chain-api-openapi.yml
- filename: anteproof-com-coverage-preview-api-openapi.yml
  format: yaml
  label: Anteproof Coverage Preview API
  slug: anteproof-com-coverage-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-coverage-preview-api-openapi.yml
- filename: anteproof-com-digest-api-openapi.yml
  format: yaml
  label: Anteproof Digest API
  slug: anteproof-com-digest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-digest-api-openapi.yml
- filename: anteproof-com-entities-api-openapi.yml
  format: yaml
  label: Anteproof Entities API
  slug: anteproof-com-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-entities-api-openapi.yml
- filename: anteproof-com-forecasts-api-openapi.yml
  format: yaml
  label: Anteproof Forecasts API
  slug: anteproof-com-forecasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-forecasts-api-openapi.yml
- filename: anteproof-com-freshness-api-openapi.yml
  format: yaml
  label: Anteproof Freshness API
  slug: anteproof-com-freshness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-freshness-api-openapi.yml
- filename: anteproof-com-me-api-openapi.yml
  format: yaml
  label: Anteproof Me API
  slug: anteproof-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-me-api-openapi.yml
- filename: anteproof-com-proof-api-openapi.yml
  format: yaml
  label: Anteproof Proof API
  slug: anteproof-com-proof-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-proof-api-openapi.yml
- filename: anteproof-com-questions-api-openapi.yml
  format: yaml
  label: Anteproof Questions API
  slug: anteproof-com-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-questions-api-openapi.yml
- filename: anteproof-com-risk-api-openapi.yml
  format: yaml
  label: Anteproof Risk API
  slug: anteproof-com-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-risk-api-openapi.yml
- filename: anteproof-com-stats-api-openapi.yml
  format: yaml
  label: Anteproof Stats API
  slug: anteproof-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-stats-api-openapi.yml
- filename: anteproof-com-support-api-openapi.yml
  format: yaml
  label: Anteproof Support API
  slug: anteproof-com-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anteproof-com/openapi/anteproof-com-support-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in, our identity provider (Clerk) gives us your email address, a user id
  - category: device
    text: IP address, user agent, the URL requested
  - category: communication
    text: What you send us by email or through the support form on this site
  deletion:
    route: Email legal@anteproof.com, or delete watchlist entries and revoke API keys on the account page
    text: to close the account, email us.
  dpa:
    available: true
    text: the data processing addendum for business customers
    url: https://anteproof.com/dpa
  purposes:
  - purpose: Running account, watchlist, keys and subscription
    text: Running your account, watchlist, keys and subscription
  - purpose: Metering API use and enforcing plan allowances
    text: Metering API use and enforcing plan allowances
  - purpose: Security, abuse prevention and fault diagnosis
    text: Keeping the Service secure; detecting and limiting abuse; diagnosing faults
  - purpose: Product analytics and attribution
    text: Understanding how the product is used and where sign-ups come from
  - purpose: Sending the weekly digest
    text: Sending the digest you asked for
  residency:
  - region: Germany
    text: Hosting of the public serving plane, database and product-event store Germany
  - region: United States
    text: We are in the United States and the database is hosted in Germany.
  retention:
  - period: null
    scope: Account, watchlist, keys
    text: While the account exists; deleted within 30 days of a deletion request or of closing the account
  - period: 13 months
    scope: API call counts
    text: API call counts 13 months, for allowance enforcement and usage history
  - period: generally 7 years
    scope: Billing identifiers and subscription status
    text: As long as tax and accounting law requires (in the US generally 7 years)
  - period: 13 months
    scope: Product events
    text: Event-level data 13 months, then aggregated.
  - period: 90 days
    scope: Server logs
    text: At most 90 days
  - period: 3 years
    scope: Correspondence
    text: Correspondence 3 years
  rights:
  - right: Access, correction, deletion, portability, restriction, objection
    text: Wherever you are, you can ask us to tell you what we hold about you, correct it, delete it, give you a copy in a portable form, restrict how we use it, or stop a particular use.
  - right: Withdraw consent (digest)
    text: Where we rely on consent (the digest) you may withdraw it at any time by unsubscribing.
  - right: Opt out of sale or sharing (California)
    text: to opt out of sale or sharing under the CCPA/CPRA
  - right: Complain to supervisory authority
    text: the right to complain to your supervisory authority (for the UK, the Information Commissioner's Office)
  role:
    text: Recoilix LLC, a Delaware limited liability company operating from North Carolina and doing business as Anteproof ("we", "us"), is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information and do not use sensitive personal information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For those transfers we rely on the European Commission's Standard Contractual Clauses (and the UK Addendum) with each provider
  - mechanism: DPF
    text: or on the provider's certification under the EU-US Data Privacy Framework where it holds one
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anteproof
provenance_date: '2026-11-09'
provider_name: Anteproof
provider_slug: anteproof-com
slug: anteproof-com-privacy-policy
source_date: '2026-11-09'
source_filename: anteproof-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anteproof.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anteproof\naid: anteproof-com\nurl: https://anteproof.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Recoilix LLC, a Delaware limited liability company operating from North Carolina and doing business as Anteproof\n    (\"we\", \"us\"), is the controller of the personal data described here.\ndata_categories:\n- category: identifying\n  text: When you sign in, our identity provider (Clerk) gives us your email address, a user id\n- category: device\n  text: IP address, user agent, the URL requested\n- category: communication\n  text: What you send us by email or through the support\
  \ form on this site\npurposes:\n- purpose: Running account, watchlist, keys and subscription\n  text: Running your account, watchlist, keys and subscription\n- purpose: Metering API use and enforcing plan allowances\n  text: Metering API use and enforcing plan allowances\n- purpose: Security, abuse prevention and fault diagnosis\n  text: Keeping the Service secure; detecting and limiting abuse; diagnosing faults\n- purpose: Product analytics and attribution\n  text: Understanding how the product is used and where sign-ups come from\n- purpose: Sending the weekly digest\n  text: Sending the digest you asked for\nretention:\n- scope: Account, watchlist, keys\n  period: null\n  text: While the account exists; deleted within 30 days of a deletion request or of closing the account\n- scope: API call counts\n  period: 13 months\n  text: API call counts 13 months, for allowance enforcement and usage history\n- scope: Billing identifiers and subscription status\n  period: generally 7 years\n \
  \ text: As long as tax and accounting law requires (in the US generally 7 years)\n- scope: Product events\n  period: 13 months\n  text: Event-level data 13 months, then aggregated.\n- scope: Server logs\n  period: 90 days\n  text: At most 90 days\n- scope: Correspondence\n  period: 3 years\n  text: Correspondence 3 years\nresidency:\n- region: Germany\n  text: Hosting of the public serving plane, database and product-event store Germany\n- region: United States\n  text: We are in the United States and the database is hosted in Germany.\ntransfers:\n- mechanism: SCC\n  text: For those transfers we rely on the European Commission's Standard Contractual Clauses (and the UK Addendum)\n    with each provider\n- mechanism: DPF\n  text: or on the provider's certification under the EU-US Data Privacy Framework where it holds one\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://anteproof.com/dpa\n  text: the data processing addendum for business customers\ndeletion:\n\
  \  route: Email legal@anteproof.com, or delete watchlist entries and revoke API keys on the account page\n  text: to close the account, email us.\nrights:\n- right: Access, correction, deletion, portability, restriction, objection\n  text: Wherever you are, you can ask us to tell you what we hold about you, correct it, delete it, give you a copy\n    in a portable form, restrict how we use it, or stop a particular use.\n- right: Withdraw consent (digest)\n  text: Where we rely on consent (the digest) you may withdraw it at any time by unsubscribing.\n- right: Opt out of sale or sharing (California)\n  text: to opt out of sale or sharing under the CCPA/CPRA\n- right: Complain to supervisory authority\n  text: the right to complain to your supervisory authority (for the UK, the Information Commissioner's Office)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information and do not use sensitive personal information\n"
source_yaml_url: https://artifacts.apis.io/anteproof-com/privacy/anteproof-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Anteproof's own page on 2026-11-09.
synthetic: false
tags:
- Dependency
- Risk Management
- Analytics
- Open Source
- Software
---
