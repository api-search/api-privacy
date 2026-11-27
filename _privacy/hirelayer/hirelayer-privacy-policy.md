---
api_specs:
- filename: hirelayer-hirelayer-api-api-openapi.yml
  format: yaml
  label: HireLayer HireLayer API
  slug: hirelayer-hirelayer-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hirelayer/openapi/hirelayer-hirelayer-api-api-openapi.yml
- filename: hirelayer-jobs-api-openapi.yml
  format: yaml
  label: HireLayer Jobs API
  slug: hirelayer-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hirelayer/openapi/hirelayer-jobs-api-openapi.yml
- filename: hirelayer-matching-api-openapi.yml
  format: yaml
  label: HireLayer Matching API
  slug: hirelayer-matching-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hirelayer/openapi/hirelayer-matching-api-openapi.yml
- filename: hirelayer-parser-api-openapi.yml
  format: yaml
  label: HireLayer Parser API
  slug: hirelayer-parser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hirelayer/openapi/hirelayer-parser-api-openapi.yml
- filename: hirelayer-skills-api-openapi.yml
  format: yaml
  label: HireLayer Skills API
  slug: hirelayer-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hirelayer/openapi/hirelayer-skills-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and authentication data, such as your name, email address, and account identifiers
  - category: financial
    text: Billing and subscription records, including Stripe customer and transaction identifiers
  - category: professional
    text: resumes, job descriptions and candidate information you submit
  - category: device
    text: Technical information generated when you use the Site or Service, such as IP address, timestamps, request metadata, and browser or device information
  - category: behavioral
    text: the actions you take on them (for example a click on a sign-up or demo button)
  - category: communication
    text: Support messages and information you choose to include in them
  deletion:
    route: Email contact@hirelayer.co to object or have a resume erased
    text: You may object to this processing or have a resume erased at any time by writing to contact@hirelayer.co
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: Create and manage accounts and authenticate users
  - purpose: Subscriptions, payments and support
    text: Manage subscriptions, payments, and customer support
  - purpose: Prospecting for HireLayer
    text: 'prospect for HireLayer: each resume is analyzed to tell whether the person or their employer may be interested in HireLayer'
  - purpose: Audience measurement
    text: These data are used only to produce statistics for the Provider
  residency:
  - region: European Union
    text: an analytics tool it runs on its own server in the European Union.
  - region: Paris, France
    text: The files are stored with Amazon Web Services in Paris, France
  retention:
  - period: 12 months
    scope: Resumes uploaded without an account
    text: They are kept for 12 months from the upload, then erased with the data extracted from them.
  - period: 25 months
    scope: Audience measurement data
    text: They are kept for at most 25 months.
  - period: null
    scope: Account, subscription, usage, and billing records
    text: are kept for as long as needed to provide the Service and manage the account
  rights:
  - right: Access, rectification and erasure
    text: Right of access, rectification, and erasure of data (articles 15, 16, and 17 of the GDPR);
  - right: Data portability
    text: Right to data portability (article 20 of the GDPR);
  - right: Restriction and objection
    text: Right to restriction (article 18 of the GDPR) and opposition to data processing (article 21 of the GDPR);
  - right: Complaint to supervisory authority
    text: Right to file a complaint with the competent supervisory authority (article 77 of the GDPR).
  role:
    text: the data controller is Louis Desclous , operating HireLayer (formerly OnlineResumeParser)
    value: both
  sale_or_sharing:
    stance: conditional
    text: They are not sold or shared with third parties for their own purposes.
  subprocessors:
    text: 'Payments: Stripe. Transactional email: Resend. Sign-in and analytics: Google, when those features are enabled or used.'
    url: null
  transfers:
  - mechanism: other
    text: Where a transfer outside the EEA takes place, the Provider applies a transfer mechanism and safeguards required by applicable data protection law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HireLayer
provenance_date: '2026-11-09'
provider_name: HireLayer
provider_slug: hirelayer
slug: hirelayer-privacy-policy
source_date: '2026-11-09'
source_filename: hirelayer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hirelayer.co/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HireLayer\naid: hirelayer\nurl: https://hirelayer.co/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: the data controller is Louis Desclous , operating HireLayer (formerly OnlineResumeParser)\ndata_categories:\n- category: identifying\n  text: Account and authentication data, such as your name, email address, and account identifiers\n- category: financial\n  text: Billing and subscription records, including Stripe customer and transaction identifiers\n- category: professional\n  text: resumes, job descriptions and candidate information you submit\n- category: device\n  text: Technical\
  \ information generated when you use the Site or Service, such as IP address, timestamps, request\n    metadata, and browser or device information\n- category: behavioral\n  text: the actions you take on them (for example a click on a sign-up or demo button)\n- category: communication\n  text: Support messages and information you choose to include in them\npurposes:\n- purpose: Account creation and authentication\n  text: Create and manage accounts and authenticate users\n- purpose: Subscriptions, payments and support\n  text: Manage subscriptions, payments, and customer support\n- purpose: Prospecting for HireLayer\n  text: 'prospect for HireLayer: each resume is analyzed to tell whether the person or their employer may be interested\n    in HireLayer'\n- purpose: Audience measurement\n  text: These data are used only to produce statistics for the Provider\nretention:\n- scope: Resumes uploaded without an account\n  period: 12 months\n  text: They are kept for 12 months from the upload,\
  \ then erased with the data extracted from them.\n- scope: Audience measurement data\n  period: 25 months\n  text: They are kept for at most 25 months.\n- scope: Account, subscription, usage, and billing records\n  period: null\n  text: are kept for as long as needed to provide the Service and manage the account\nresidency:\n- region: European Union\n  text: an analytics tool it runs on its own server in the European Union.\n- region: Paris, France\n  text: The files are stored with Amazon Web Services in Paris, France\ntransfers:\n- mechanism: other\n  text: Where a transfer outside the EEA takes place, the Provider applies a transfer mechanism and safeguards required\n    by applicable data protection law.\nsubprocessors:\n  url: null\n  text: 'Payments: Stripe. Transactional email: Resend. Sign-in and analytics: Google, when those features are enabled\n    or used.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@hirelayer.co to object or have\
  \ a resume erased\n  text: You may object to this processing or have a resume erased at any time by writing to contact@hirelayer.co\nrights:\n- right: Access, rectification and erasure\n  text: Right of access, rectification, and erasure of data (articles 15, 16, and 17 of the GDPR);\n- right: Data portability\n  text: Right to data portability (article 20 of the GDPR);\n- right: Restriction and objection\n  text: Right to restriction (article 18 of the GDPR) and opposition to data processing (article 21 of the GDPR);\n- right: Complaint to supervisory authority\n  text: Right to file a complaint with the competent supervisory authority (article 77 of the GDPR).\nsale_or_sharing:\n  stance: conditional\n  text: They are not sold or shared with third parties for their own purposes.\n"
source_yaml_url: https://artifacts.apis.io/hirelayer/privacy/hirelayer-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from HireLayer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Resume Parsing
- CandidateMatching
---
