---
api_specs:
- filename: karmacheck-authentication-api-openapi.yml
  format: yaml
  label: KarmaCheck Authentication API
  slug: karmacheck-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-authentication-api-openapi.yml
- filename: karmacheck-candidate-onboarding-api-openapi.yml
  format: yaml
  label: KarmaCheck Candidate onboarding API
  slug: karmacheck-candidate-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-candidate-onboarding-api-openapi.yml
- filename: karmacheck-case-api-openapi.yml
  format: yaml
  label: KarmaCheck Case API
  slug: karmacheck-case-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-case-api-openapi.yml
- filename: karmacheck-cases-api-openapi.yml
  format: yaml
  label: KarmaCheck Cases API
  slug: karmacheck-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-cases-api-openapi.yml
- filename: karmacheck-packages-api-openapi.yml
  format: yaml
  label: KarmaCheck Packages API
  slug: karmacheck-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-packages-api-openapi.yml
- filename: karmacheck-secure-documents-api-openapi.yml
  format: yaml
  label: KarmaCheck Secure documents API
  slug: karmacheck-secure-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-secure-documents-api-openapi.yml
- filename: karmacheck-services-api-openapi.yml
  format: yaml
  label: KarmaCheck Services API
  slug: karmacheck-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-services-api-openapi.yml
- filename: karmacheck-users-api-openapi.yml
  format: yaml
  label: KarmaCheck Users API
  slug: karmacheck-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-users-api-openapi.yml
- filename: karmacheck-verification-book-api-openapi.yml
  format: yaml
  label: KarmaCheck Verification Book API
  slug: karmacheck-verification-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karmacheck/openapi/karmacheck-verification-book-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, address, or IP address
  - category: contact
    text: email address, phone number
  - category: identifying
    text: social security number (SSN), DOB, password
  - category: financial
    text: credit card details and billing address
  - category: biometric
    text: images of the identity documents and Live Selfies used to conduct digital identity verification
  - category: behavioral
    text: behavioral metrics, heatmaps, and session replay
  - category: device
    text: operating system, screen settings, Web browser software, and referring website
  deletion:
    route: email or toll-free phone request
    text: 'To exercise your rights please submit a request to the following email: privacy@karmacheck.com or call the following toll-free phone number: 877-732-2129.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Conduct background checks
    text: Conduct background checks and pre-fill background check information as requested by KarmaCheck's customers
  retention:
  - period: a minimum of five years
    scope: Background screening data under FCRA
    text: Personal information collected for background screening purposes subject to the Fair Credit Reporting Act will be retained for a minimum of five years.
  - period: null
    scope: Other personal information
    text: KarmaCheck will retain all other personal information as allowed by law.
  rights:
  - right: Right to know
    text: You have the right to request that KarmaCheck disclose certain information to you about our collection, use, disclosure and sale of your personal information over the past twelve (12) months.
  - right: Deletion
    text: You have the right to request that KarmaCheck delete any of your personal information that we have collected from you and maintain, subject to certain exceptions.
  - right: Non-discrimination
    text: KarmaCheck will not discriminate against you for exercising any of your CCPA rights.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: KarmaCheck does not sell any personal information for marketing purposes. Your phone number will not be shared with third parties or affiliates for marketing/promotional purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: KarmaCheck
provenance_date: '2026-11-09'
provider_name: KarmaCheck
provider_slug: karmacheck
slug: karmacheck-privacy-policy
source_date: '2026-11-09'
source_filename: karmacheck-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.karmacheck.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: KarmaCheck\naid: karmacheck\nurl: https://www.karmacheck.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name, address, or IP address\n- category: contact\n  text: email address, phone number\n- category: identifying\n  text: social security number (SSN), DOB, password\n- category: financial\n  text: credit card details and billing address\n- category: biometric\n  text: images of the identity documents and Live Selfies used to conduct digital identity verification\n- category: behavioral\n  text: behavioral metrics,\
  \ heatmaps, and session replay\n- category: device\n  text: operating system, screen settings, Web browser software, and referring website\npurposes:\n- purpose: Conduct background checks\n  text: Conduct background checks and pre-fill background check information as requested by KarmaCheck's customers\nretention:\n- scope: Background screening data under FCRA\n  period: a minimum of five years\n  text: Personal information collected for background screening purposes subject to the Fair Credit Reporting Act\n    will be retained for a minimum of five years.\n- scope: Other personal information\n  period: null\n  text: KarmaCheck will retain all other personal information as allowed by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email or toll-free phone request\n  text: 'To exercise your rights please submit a request to the following email: privacy@karmacheck.com or call\n    the\
  \ following toll-free phone number: 877-732-2129.'\nrights:\n- right: Right to know\n  text: You have the right to request that KarmaCheck disclose certain information to you about our collection,\n    use, disclosure and sale of your personal information over the past twelve (12) months.\n- right: Deletion\n  text: You have the right to request that KarmaCheck delete any of your personal information that we have collected\n    from you and maintain, subject to certain exceptions.\n- right: Non-discrimination\n  text: KarmaCheck will not discriminate against you for exercising any of your CCPA rights.\nsale_or_sharing:\n  stance: conditional\n  text: KarmaCheck does not sell any personal information for marketing purposes. Your phone number will not be\n    shared with third parties or affiliates for marketing/promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/karmacheck/privacy/karmacheck-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from KarmaCheck's own page on 2026-11-09.
synthetic: false
tags:
- Background Checks
- Employment Screening
- Identity Verification
- Credential Verification
- Motor Vehicle Records
- Occupational Health Screening
- Drug Screening
- Human Resources
- Staffing
- Healthcare
- Compliance
- FCRA
- Adjudication
- Webhook
- MCP Server
- Agent-Native
---
