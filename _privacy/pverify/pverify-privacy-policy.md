---
api_specs:
- filename: pverify-authentication-api-openapi.yml
  format: yaml
  label: pVerify Authentication API
  slug: pverify-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-authentication-api-openapi.yml
- filename: pverify-eligibility-api-openapi.yml
  format: yaml
  label: pVerify Eligibility API
  slug: pverify-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-eligibility-api-openapi.yml
- filename: pverify-dental-eligibility-api-openapi.yml
  format: yaml
  label: pVerify Dental Eligibility API
  slug: pverify-dental-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-dental-eligibility-api-openapi.yml
- filename: pverify-insurance-discovery-api-openapi.yml
  format: yaml
  label: pVerify Insurance Discovery API
  slug: pverify-insurance-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-insurance-discovery-api-openapi.yml
- filename: pverify-mbi-lookup-api-openapi.yml
  format: yaml
  label: pVerify MBI Lookup API
  slug: pverify-mbi-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-mbi-lookup-api-openapi.yml
- filename: pverify-patient-demographic-validator-api-openapi.yml
  format: yaml
  label: pVerify Patient Demographic Validator API
  slug: pverify-patient-demographic-validator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-patient-demographic-validator-api-openapi.yml
- filename: pverify-claim-status-api-openapi.yml
  format: yaml
  label: pVerify Claim Status API
  slug: pverify-claim-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-claim-status-api-openapi.yml
- filename: pverify-estimation-api-openapi.yml
  format: yaml
  label: pVerify Patient Cost Estimator API
  slug: pverify-estimation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-estimation-api-openapi.yml
- filename: pverify-payers-api-openapi.yml
  format: yaml
  label: pVerify Payers API
  slug: pverify-payers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-payers-api-openapi.yml
- filename: pverify-cgx-widget-api-openapi.yml
  format: yaml
  label: pVerify CGX Widget API
  slug: pverify-cgx-widget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-cgx-widget-api-openapi.yml
- filename: pverify-same-or-similar-api-openapi.yml
  format: yaml
  label: pVerify Same or Similar API (discontinued)
  slug: pverify-same-or-similar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-same-or-similar-api-openapi.yml
- filename: pverify-cmn-api-openapi.yml
  format: yaml
  label: pVerify CMN API (discontinued)
  slug: pverify-cmn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-cmn-api-openapi.yml
- filename: pverify-snf-api-openapi.yml
  format: yaml
  label: pVerify SNF API (discontinued)
  slug: pverify-snf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pverify/openapi/pverify-snf-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, address, email address, telephone number, employer name, job title or role
  - category: device
    text: information about your computing device and Internet connection, such as your IP address, operating system, browser type, advertising ID, and device ID
  - category: behavioral
    text: information related to your interaction with our Website, Products and Services, or advertisements
  - category: communication
    text: the content of your message and our response to you
  deletion:
    route: email request
    text: You may send us an email at [email protected] to request access to, correct, or delete any Personal Information that we have collected about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide Products and Services
    text: to provide and personalize our Website and Products and Services provided
  - purpose: marketing
    text: to promote and market our Products and Services, the products and services of our affiliates, and the products and services of third party partners
  - purpose: AI model training
    text: We may use information we collect to internally refine, improve, and train the models and algorithms that support our AI features, in accordance with applicable law.
  - purpose: security
    text: to help maintain the safety, security, and integrity of our Website, Products and Services, databases and other technology assets, and business
  residency:
  - region: United States
    text: Access to and use of the Website and Products and Services is limited exclusively to users located in states within the United States.
  retention:
  - period: null
    scope: Personal Information
    text: We retain your Personal Information for as long as we continue to provide the Products or Services to you, or for a period in which we reasonably foresee continuing to provide the Products or Services.
  rights:
  - right: access
    text: to request access to, correct, or delete any Personal Information that we have collected about you
  - right: opt out of marketing emails
    text: You may opt out of such communications at any time by clicking the “unsubscribe” link at the bottom of the email.
  role:
    text: PRN Software LLC d/b/a pVerify (“ pVerify ”, “ we ”, or “ us ”) respects your privacy
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not share, trade, sell, or otherwise disclose your Personal Information for purposes other than those outlined in this Privacy Policy.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pVerify
provenance_date: '2026-11-10'
provider_name: pVerify
provider_slug: pverify
slug: pverify-privacy-policy
source_date: '2026-11-10'
source_filename: pverify-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pverify.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pVerify\naid: pverify\nurl: https://pverify.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: PRN Software LLC d/b/a pVerify (“ pVerify ”, “ we ”, or “ us ”) respects your privacy\ndata_categories:\n- category: identifying\n  text: name, address, email address, telephone number, employer name, job title or role\n- category: device\n  text: information about your computing device and Internet connection, such as your IP address, operating system,\n    browser type, advertising ID, and device ID\n- category: behavioral\n  text: information related to your interaction with our\
  \ Website, Products and Services, or advertisements\n- category: communication\n  text: the content of your message and our response to you\npurposes:\n- purpose: provide Products and Services\n  text: to provide and personalize our Website and Products and Services provided\n- purpose: marketing\n  text: to promote and market our Products and Services, the products and services of our affiliates, and the products\n    and services of third party partners\n- purpose: AI model training\n  text: We may use information we collect to internally refine, improve, and train the models and algorithms that\n    support our AI features, in accordance with applicable law.\n- purpose: security\n  text: to help maintain the safety, security, and integrity of our Website, Products and Services, databases and\n    other technology assets, and business\nretention:\n- scope: Personal Information\n  period: null\n  text: We retain your Personal Information for as long as we continue to provide the Products\
  \ or Services to you,\n    or for a period in which we reasonably foresee continuing to provide the Products or Services.\nresidency:\n- region: United States\n  text: Access to and use of the Website and Products and Services is limited exclusively to users located in states\n    within the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: You may send us an email at [email protected] to request access to, correct, or delete any Personal Information\n    that we have collected about you.\nrights:\n- right: access\n  text: to request access to, correct, or delete any Personal Information that we have collected about you\n- right: opt out of marketing emails\n  text: You may opt out of such communications at any time by clicking the “unsubscribe” link at the bottom of the\n    email.\nsale_or_sharing:\n  stance: conditional\n  text: We do not share, trade, sell, or otherwise\
  \ disclose your Personal Information for purposes other than those\n    outlined in this Privacy Policy.\n"
source_yaml_url: https://artifacts.apis.io/pverify/privacy/pverify-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from pVerify's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Insurance
- Eligibility
- Claims
- EDI
- 270/271
- 276/277
- Revenue Cycle
- Medicare
- Payers
- Insurance Discovery
- Patient Estimation
- HIPAA
- Dental
- Health Insurance
---
