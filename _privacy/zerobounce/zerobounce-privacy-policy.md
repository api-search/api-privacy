---
api_specs:
- filename: zerobounce-validation-api-openapi.yml
  format: yaml
  label: ZeroBounce Validation API
  slug: zerobounce-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerobounce/openapi/zerobounce-validation-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Your full name, email address, the password You select, phone number, company industry
  - category: financial
    text: Your credit card/debit card number and related billing information will also be collected.
  - category: behavioral
    text: behavioral data like opens and clicks
  - category: device
    text: type of computer or device accessing the Site
  - category: location
    text: Your geographic region based on Your IP address
  deletion:
    route: contact ZeroBounce via website
    text: Have us delete any data we have about You
  dpa:
    available: true
    text: we incorporate a data processing addendum and the EU standard contractual clauses.
    url: null
  purposes:
  - purpose: respond to inquiries and fulfill service requests
    text: ZeroBounce may use your Personal Information to Respond to Your inquiries and fulfill Your requests for Services
  - purpose: marketing communications
    text: Send You marketing communications that we believe may be of interest to You, including via third party platforms
  - purpose: payment processing
    text: Complete and fulfill Your purchase, for example, to process Your payments
  - purpose: fraud monitoring and prevention
    text: Conduct data analysis, audits, fraud monitoring and prevention
  residency:
  - region: EU
    text: However, in all other instances, ZeroBounce processes and stores Personal Information in the EU.
  - region: United States
    text: 'For customers that specifically elect to utilize ZeroBounce''s API server in the United States: ZeroBounce will process Personal Information in the United States.'
  retention:
  - period: thirty (30) days
    scope: uploaded files and submitted data
    text: may be stored encrypted with a password for a period of thirty (30) days
  - period: as long as needed to provide the Services
    scope: Personal Information
    text: We will retain Your Personal Information for as long as needed to provide the Services, unless a longer retention period is required or permitted by law.
  rights:
  - right: access
    text: Request access to Your Personal Information
  - right: correct
    text: Change/correct any data we have about You
  - right: delete
    text: Have us delete any data we have about You
  - right: opt-out of sharing with third party partners
    text: You may opt-out of our sharing of Your Personal Information with our third party partners
  - right: limit use and disclosure
    text: To request to limit the use and disclosure of Your personal information, please submit a written request
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: will not sell or rent Personal Information to anyone
  subprocessors:
    text: To support our Services (email validation, list cleaning, customer support, payments, analytics, infrastructure), we may disclose your personal information
    url: null
  transfers:
  - mechanism: DPF
    text: ZeroBounce complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)
  - mechanism: SCC
    text: where transfers are made by ZeroBounce customers in the EU, we incorporate a data processing addendum and the EU standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ZeroBounce
provenance_date: '2026-11-10'
provider_name: ZeroBounce
provider_slug: zerobounce
slug: zerobounce-privacy-policy
source_date: '2026-11-10'
source_filename: zerobounce-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zerobounce.net/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ZeroBounce\naid: zerobounce\nurl: https://www.zerobounce.net/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your full name, email address, the password You select, phone number, company industry\n- category: financial\n  text: Your credit card/debit card number and related billing information will also be collected.\n- category: behavioral\n  text: behavioral data like opens and clicks\n- category: device\n  text: type of computer or device accessing the Site\n- category: location\n  text: Your geographic region based on Your\
  \ IP address\npurposes:\n- purpose: respond to inquiries and fulfill service requests\n  text: ZeroBounce may use your Personal Information to Respond to Your inquiries and fulfill Your requests for\n    Services\n- purpose: marketing communications\n  text: Send You marketing communications that we believe may be of interest to You, including via third party platforms\n- purpose: payment processing\n  text: Complete and fulfill Your purchase, for example, to process Your payments\n- purpose: fraud monitoring and prevention\n  text: Conduct data analysis, audits, fraud monitoring and prevention\nretention:\n- scope: uploaded files and submitted data\n  period: thirty (30) days\n  text: may be stored encrypted with a password for a period of thirty (30) days\n- scope: Personal Information\n  period: as long as needed to provide the Services\n  text: We will retain Your Personal Information for as long as needed to provide the Services, unless a longer\n    retention period is required or\
  \ permitted by law.\nresidency:\n- region: EU\n  text: However, in all other instances, ZeroBounce processes and stores Personal Information in the EU.\n- region: United States\n  text: 'For customers that specifically elect to utilize ZeroBounce''s API server in the United States: ZeroBounce\n    will process Personal Information in the United States.'\ntransfers:\n- mechanism: DPF\n  text: ZeroBounce complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)\n- mechanism: SCC\n  text: where transfers are made by ZeroBounce customers in the EU, we incorporate a data processing addendum and\n    the EU standard contractual clauses.\nsubprocessors:\n  url: null\n  text: To support our Services (email validation, list cleaning, customer support, payments, analytics, infrastructure),\n    we may disclose your personal information\ndpa:\n  available: true\n  url: null\n  text: we incorporate\
  \ a data processing addendum and the EU standard contractual clauses.\ndeletion:\n  route: contact ZeroBounce via website\n  text: Have us delete any data we have about You\nrights:\n- right: access\n  text: Request access to Your Personal Information\n- right: correct\n  text: Change/correct any data we have about You\n- right: delete\n  text: Have us delete any data we have about You\n- right: opt-out of sharing with third party partners\n  text: You may opt-out of our sharing of Your Personal Information with our third party partners\n- right: limit use and disclosure\n  text: To request to limit the use and disclosure of Your personal information, please submit a written request\nsale_or_sharing:\n  stance: prohibited\n  text: will not sell or rent Personal Information to anyone\n"
source_yaml_url: https://artifacts.apis.io/zerobounce/privacy/zerobounce-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ZeroBounce's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- Email Deliverability
- Marketing
- Lead Scoring
- Anti-Spam
- Data Quality
- Email Finder
- Deliverability Monitoring
- DMARC
- Email
---
