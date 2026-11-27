---
api_specs:
- filename: youscan-data-import-api-openapi.yml
  format: yaml
  label: YouScan Data Import API
  slug: youscan-data-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-data-import-api-openapi.yml
- filename: youscan-history-api-openapi.yml
  format: yaml
  label: YouScan History API
  slug: youscan-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-history-api-openapi.yml
- filename: youscan-mentions-api-openapi.yml
  format: yaml
  label: YouScan Mentions API
  slug: youscan-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-mentions-api-openapi.yml
- filename: youscan-spaces-api-openapi.yml
  format: yaml
  label: YouScan Spaces API
  slug: youscan-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-spaces-api-openapi.yml
- filename: youscan-statistics-api-openapi.yml
  format: yaml
  label: YouScan Statistics API
  slug: youscan-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-statistics-api-openapi.yml
- filename: youscan-tags-api-openapi.yml
  format: yaml
  label: YouScan Tags API
  slug: youscan-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-tags-api-openapi.yml
- filename: youscan-topics-api-openapi.yml
  format: yaml
  label: YouScan Topics API
  slug: youscan-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-topics-api-openapi.yml
- filename: youscan-webhook-api-openapi.yml
  format: yaml
  label: YouScan Webhook API
  slug: youscan-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/youscan/openapi/youscan-webhook-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Your contact details (such as first and last name, address, e-mail address, phone number)
  - category: identifying
    text: Identification numbers (such as social security number, tax number, tax ID, passport or ID card number, insurance numbers)
  - category: financial
    text: Payment data (such as bank account number, credit card number, financial institution)
  - category: device
    text: Online identifiers (such as cookie IDs, IP addresses, advertising IDs)
  - category: behavioral
    text: Log files with information about your visit to our website
  - category: communication
    text: Your correspondence with us
  deletion:
    route: Data Subject Access/Opt-Out Request Form or email to privacy@youscan.io
    text: You may file your request (revoke your consent, etc.) via Data Subject Access/Opt-Out Request Form available at https://youscan.io/gdpr-request/ or by sending email to privacy@youscan.io
  dpa:
    available: true
    text: Our Data Processing Addendum (available at https://youscan.io/data-processing-addendum/ ) sets out our data-protection obligations to customers.
    url: https://youscan.io/data-processing-addendum/
  purposes:
  - purpose: providing the Services
    text: providing the Services, including technical support
  - purpose: billing
    text: billing
  - purpose: marketing and advertising
    text: as well as marketing and advertising
  - purpose: market research and business development
    text: market research and business development
  retention:
  - period: null
    scope: controller personal data
    text: We retain personal data that we process as a controller only for as long as necessary for the purposes described in this policy and permitted by applicable law.
  rights:
  - right: access
    text: To request information about the processing of your data, as well as to receive a copy of your personal data.
  - right: portability
    text: To receive personal data relating to you in a structured, common and machine-readable format or to transfer it to another person in charge;
  - right: rectification
    text: To correct your data.
  - right: erasure
    text: To have your data deleted or blocked;
  - right: restriction
    text: To have the processing restricted;
  - right: objection
    text: To object to the processing of your data;
  - right: withdraw consent
    text: To revoke your consent to the processing of your data for the future; and
  - right: complaint
    text: To complain to the responsible supervisory authority about unauthorised data processing.
  role:
    text: we act as a processor or sub-processor for that activity
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We maintain information about our subprocessors in our Trust Center (available at https://trust.youscan.io/ ).
    url: https://trust.youscan.io/
  transfers:
  - mechanism: SCC
    text: European Commission-approved standard contractual clauses
  - mechanism: adequacy
    text: Where a transfer is covered by an applicable European Commission adequacy decision, we may rely on that decision.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: YouScan
provenance_date: '2026-11-10'
provider_name: YouScan
provider_slug: youscan
slug: youscan-privacy-policy
source_date: '2026-11-10'
source_filename: youscan-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://youscan.io/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: YouScan\naid: youscan\nurl: https://youscan.io/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a processor or sub-processor for that activity\ndata_categories:\n- category: contact\n  text: Your contact details (such as first and last name, address, e-mail address, phone number)\n- category: identifying\n  text: Identification numbers (such as social security number, tax number, tax ID, passport or ID card number,\n    insurance numbers)\n- category: financial\n  text: Payment data (such as bank account number, credit card number, financial institution)\n- category: device\n\
  \  text: Online identifiers (such as cookie IDs, IP addresses, advertising IDs)\n- category: behavioral\n  text: Log files with information about your visit to our website\n- category: communication\n  text: Your correspondence with us\npurposes:\n- purpose: providing the Services\n  text: providing the Services, including technical support\n- purpose: billing\n  text: billing\n- purpose: marketing and advertising\n  text: as well as marketing and advertising\n- purpose: market research and business development\n  text: market research and business development\nretention:\n- scope: controller personal data\n  period: null\n  text: We retain personal data that we process as a controller only for as long as necessary for the purposes described\n    in this policy and permitted by applicable law.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: European Commission-approved standard contractual clauses\n- mechanism: adequacy\n  text: Where a transfer is covered by an applicable European\
  \ Commission adequacy decision, we may rely on that\n    decision.\nsubprocessors:\n  url: https://trust.youscan.io/\n  text: We maintain information about our subprocessors in our Trust Center (available at https://trust.youscan.io/\n    ).\ndpa:\n  available: true\n  url: https://youscan.io/data-processing-addendum/\n  text: Our Data Processing Addendum (available at https://youscan.io/data-processing-addendum/ ) sets out our data-protection\n    obligations to customers.\ndeletion:\n  route: Data Subject Access/Opt-Out Request Form or email to privacy@youscan.io\n  text: You may file your request (revoke your consent, etc.) via Data Subject Access/Opt-Out Request Form available\n    at https://youscan.io/gdpr-request/ or by sending email to privacy@youscan.io\nrights:\n- right: access\n  text: To request information about the processing of your data, as well as to receive a copy of your personal\n    data.\n- right: portability\n  text: To receive personal data relating to you in a\
  \ structured, common and machine-readable format or to transfer\n    it to another person in charge;\n- right: rectification\n  text: To correct your data.\n- right: erasure\n  text: To have your data deleted or blocked;\n- right: restriction\n  text: To have the processing restricted;\n- right: objection\n  text: To object to the processing of your data;\n- right: withdraw consent\n  text: To revoke your consent to the processing of your data for the future; and\n- right: complaint\n  text: To complain to the responsible supervisory authority about unauthorised data processing.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/youscan/privacy/youscan-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from YouScan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media Listening
- Social Intelligence
- Consumer Insights
- Sentiment Analysis
- Media Monitoring
- Analytics
- Artificial Intelligence
---
