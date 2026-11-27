---
api_specs:
- filename: funding-circle-decisions-api-openapi.yml
  format: yaml
  label: Funding Circle Decisions API
  slug: funding-circle-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/funding-circle/openapi/funding-circle-decisions-api-openapi.yml
- filename: funding-circle-documents-api-openapi.yml
  format: yaml
  label: Funding Circle Documents API
  slug: funding-circle-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/funding-circle/openapi/funding-circle-documents-api-openapi.yml
- filename: funding-circle-loan-applications-api-openapi.yml
  format: yaml
  label: Funding Circle Loan Applications API
  slug: funding-circle-loan-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/funding-circle/openapi/funding-circle-loan-applications-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: your personal details (including name, date of birth, current and previous postal addresses and national insurance number)
  - category: contact
    text: your contact information (including phone and e-mail details)
  - category: financial
    text: financial information (including bank or building society account details and details of debit cards used to make transfers on the Funding Circle website)
  - category: device
    text: information about your computer (including, where available, your IP address, operating system and browser type)
  - category: behavioral
    text: your interaction with our platform, and email performance data
  - category: health
    text: sensitive personal data of borrowers, investors or guarantors (such as medical information or criminal records)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: platform operation and loan matching
    text: to provide and administer our products and services
  - purpose: credit assessment
    text: to assess your creditworthiness and to make credit-related decisions
  - purpose: targeted advertising
    text: for targeted advertising through digital platforms, social media and television (this may entail profiling, data enrichment and audience segmentation)
  - purpose: fraud prevention
    text: for the prevention and detection of fraud, money laundering, or other illegal or criminal activity
  - purpose: regulatory compliance
    text: to comply with our legal and regulatory obligations
  retention:
  - period: six years
    scope: borrower and investor files
    text: retain our borrower and investor files for a period of six years after the end of the borrowing/investing relationship
  - period: six years
    scope: CRA-shared records
    text: Any records shared with CRAs will remain on file for six years after your account is closed
  rights:
  - right: access
    text: exercise your right to request access to certain personal data records we hold about you (a subject access request)
  - right: rectification
    text: request that we update and correct any out-of-date or inaccurate personal data we hold about you
  - right: objection and erasure
    text: exercise your right to object to our continued processing or your right of erasure, neither of which is a guaranteed or absolute right
  - right: marketing opt-out
    text: opt out of any marketing communications that Funding Circle may send you
  role:
    text: we mean Funding Circle Ltd and its affiliates in the United Kingdom
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we may transfer your personal data to, or your personal data may be accessible in, any location in which we do business, including those outside the EEA
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Funding Circle
provenance_date: '2026-11-09'
provider_name: Funding Circle
provider_slug: funding-circle
slug: funding-circle-privacy-policy
source_date: '2026-11-09'
source_filename: funding-circle-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fundingcircle.com/uk/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Funding Circle\naid: funding-circle\nurl: https://www.fundingcircle.com/uk/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: we mean Funding Circle Ltd and its affiliates in the United Kingdom\ndata_categories:\n- category: identifying\n  text: your personal details (including name, date of birth, current and previous postal addresses and national\n    insurance number)\n- category: contact\n  text: your contact information (including phone and e-mail details)\n- category: financial\n  text: financial information (including bank or building society account details and details\
  \ of debit cards used\n    to make transfers on the Funding Circle website)\n- category: device\n  text: information about your computer (including, where available, your IP address, operating system and browser\n    type)\n- category: behavioral\n  text: your interaction with our platform, and email performance data\n- category: health\n  text: sensitive personal data of borrowers, investors or guarantors (such as medical information or criminal records)\npurposes:\n- purpose: platform operation and loan matching\n  text: to provide and administer our products and services\n- purpose: credit assessment\n  text: to assess your creditworthiness and to make credit-related decisions\n- purpose: targeted advertising\n  text: for targeted advertising through digital platforms, social media and television (this may entail profiling,\n    data enrichment and audience segmentation)\n- purpose: fraud prevention\n  text: for the prevention and detection of fraud, money laundering, or other illegal\
  \ or criminal activity\n- purpose: regulatory compliance\n  text: to comply with our legal and regulatory obligations\nretention:\n- scope: borrower and investor files\n  period: six years\n  text: retain our borrower and investor files for a period of six years after the end of the borrowing/investing\n    relationship\n- scope: CRA-shared records\n  period: six years\n  text: Any records shared with CRAs will remain on file for six years after your account is closed\nresidency: []\ntransfers:\n- mechanism: other\n  text: we may transfer your personal data to, or your personal data may be accessible in, any location in which\n    we do business, including those outside the EEA\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: exercise your right to request access to certain personal data records we hold about you (a subject access\n    request)\n- right: rectification\n\
  \  text: request that we update and correct any out-of-date or inaccurate personal data we hold about you\n- right: objection and erasure\n  text: exercise your right to object to our continued processing or your right of erasure, neither of which is\n    a guaranteed or absolute right\n- right: marketing opt-out\n  text: opt out of any marketing communications that Funding Circle may send you\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/funding-circle/privacy/funding-circle-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- rights
summary_line: 19 quoted statements, read from Funding Circle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Lending
- Small Business
- Fintech
- Loans
- Financial Services
- Payments
---
