---
api_specs:
- filename: teamohana-discovery-api-openapi.yml
  format: yaml
  label: TeamOhana Discovery API
  slug: teamohana-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-discovery-api-openapi.yml
- filename: teamohana-headcount-api-openapi.yml
  format: yaml
  label: TeamOhana Headcount API
  slug: teamohana-headcount-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-headcount-api-openapi.yml
- filename: teamohana-scenario-api-openapi.yml
  format: yaml
  label: TeamOhana Scenario API
  slug: teamohana-scenario-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-scenario-api-openapi.yml
- filename: teamohana-scim-api-openapi.yml
  format: yaml
  label: TeamOhana SCIM API
  slug: teamohana-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamohana/openapi/teamohana-scim-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Name Required
  - category: contact
    text: Work email, Telephone number Email required, phone optional
  - category: demographic
    text: Gender, Ethnicity Optional
  - category: location
    text: Address (city, region, country) Required
  - category: professional
    text: Employment type (contractor/full-time), Employment status (active/terminated), Department/sub-department, Reporting manager Required
  - category: financial
    text: Compensation Salary information Required, for budgeting and reporting
  - category: identifying
    text: Image Photograph Optional
  - category: device
    text: your IP address, your browser type, your operating system, your access times
  deletion:
    route: Written request to security@teamohana.com
    text: Customers may request deletion of their data by making a request in writing to security@teamohana.com
  dpa:
    available: true
    text: the Data Processing Agreement between TeamOhana and each customer applies in addition to this Privacy Policy
    url: null
  purposes:
  - purpose: Workforce planning and management
    text: real-time headcount planning, approval, and tracking
  - purpose: Compensation and budget management
    text: budget forecasting and cost tracking
  - purpose: Workforce analytics
    text: organizational insights, including diversity and inclusion planning where the customer has enabled it
  - purpose: Marketing to website contacts
    text: Send you advertising and marketing materials about our products, services and promotions
  residency:
  - region: United States
    text: Personal data processed on behalf of our customers is stored and processed in the United States (AWS us-west-2, Oregon, with backup replication to AWS us-east-1, Virginia).
  retention:
  - period: 90 days
    scope: Analytics data in PostHog
    text: Analytics data held in PostHog is retained for no more than 90 days.
  - period: 30 days
    scope: Controller contact-form submissions
    text: Other personal data we collect as Data Controller, such as contact-form submissions, is retained for no more than 30 days, unless a longer period is required by law.
  - period: duration of the customer relationship
    scope: Customer personal data
    text: Personal data processed on behalf of a customer is retained for the duration of the customer relationship.
  rights:
  - right: Access, correction, deletion, objection (website visitors)
    text: you may request access to, correction of, or deletion of your personal data, object to our processing of it, or ask us to stop contacting you, by emailing security@teamohana.com
  - right: California right to know, delete, correct, opt out
    text: California residents have the right to know what personal information we collect, use, and disclose; to request deletion or correction of their personal information; to opt out of the sale or sharing of their personal information
  - right: Withdraw consent (EEA/UK)
    text: you may also withdraw any consent you have given at any time
  role:
    text: TeamOhana as Data Processor for personal data about our customers’ employees, contractors, and job applicants which we process strictly on that customer’s instructions; and TeamOhana as Data Controller for personal data about visitors to our website and business contacts
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not use Customer Workforce and Applicant Data for our own marketing or advertising, and we do not sell it or share it with advertisers, ad networks, or data brokers.
  subprocessors:
    text: A current, detailed sub-processor list is maintained at https://trust.teamohana.com/subprocessors .
    url: https://trust.teamohana.com/subprocessors
  transfers:
  - mechanism: DPF
    text: TeamOhana, Inc. complies with the EU–U.S. Data Privacy Framework
  - mechanism: SCC
    text: Standard Contractual Clauses incorporated into our Data Processing Agreements
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TeamOhana
provenance_date: '2026-11-10'
provider_name: TeamOhana
provider_slug: teamohana
slug: teamohana-privacy-policy
source_date: '2026-11-10'
source_filename: teamohana-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.teamohana.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TeamOhana\naid: teamohana\nurl: https://www.teamohana.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: TeamOhana as Data Processor for personal data about our customers’ employees, contractors, and job applicants\n    which we process strictly on that customer’s instructions; and TeamOhana as Data Controller for personal data\n    about visitors to our website and business contacts\ndata_categories:\n- category: identifying\n  text: Identity Name Required\n- category: contact\n  text: Work email, Telephone number Email required, phone optional\n- category: demographic\n  text: Gender,\
  \ Ethnicity Optional\n- category: location\n  text: Address (city, region, country) Required\n- category: professional\n  text: Employment type (contractor/full-time), Employment status (active/terminated), Department/sub-department,\n    Reporting manager Required\n- category: financial\n  text: Compensation Salary information Required, for budgeting and reporting\n- category: identifying\n  text: Image Photograph Optional\n- category: device\n  text: your IP address, your browser type, your operating system, your access times\npurposes:\n- purpose: Workforce planning and management\n  text: real-time headcount planning, approval, and tracking\n- purpose: Compensation and budget management\n  text: budget forecasting and cost tracking\n- purpose: Workforce analytics\n  text: organizational insights, including diversity and inclusion planning where the customer has enabled it\n- purpose: Marketing to website contacts\n  text: Send you advertising and marketing materials about our products,\
  \ services and promotions\nretention:\n- scope: Analytics data in PostHog\n  period: 90 days\n  text: Analytics data held in PostHog is retained for no more than 90 days.\n- scope: Controller contact-form submissions\n  period: 30 days\n  text: Other personal data we collect as Data Controller, such as contact-form submissions, is retained for no\n    more than 30 days, unless a longer period is required by law.\n- scope: Customer personal data\n  period: duration of the customer relationship\n  text: Personal data processed on behalf of a customer is retained for the duration of the customer relationship.\nresidency:\n- region: United States\n  text: Personal data processed on behalf of our customers is stored and processed in the United States (AWS us-west-2,\n    Oregon, with backup replication to AWS us-east-1, Virginia).\ntransfers:\n- mechanism: DPF\n  text: TeamOhana, Inc. complies with the EU–U.S. Data Privacy Framework\n- mechanism: SCC\n  text: Standard Contractual Clauses incorporated\
  \ into our Data Processing Agreements\nsubprocessors:\n  url: https://trust.teamohana.com/subprocessors\n  text: A current, detailed sub-processor list is maintained at https://trust.teamohana.com/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: the Data Processing Agreement between TeamOhana and each customer applies in addition to this Privacy Policy\ndeletion:\n  route: Written request to security@teamohana.com\n  text: Customers may request deletion of their data by making a request in writing to security@teamohana.com\nrights:\n- right: Access, correction, deletion, objection (website visitors)\n  text: you may request access to, correction of, or deletion of your personal data, object to our processing of\n    it, or ask us to stop contacting you, by emailing security@teamohana.com\n- right: California right to know, delete, correct, opt out\n  text: California residents have the right to know what personal information we collect, use, and disclose; to\n    request\
  \ deletion or correction of their personal information; to opt out of the sale or sharing of their personal\n    information\n- right: Withdraw consent (EEA/UK)\n  text: you may also withdraw any consent you have given at any time\nsale_or_sharing:\n  stance: conditional\n  text: We do not use Customer Workforce and Applicant Data for our own marketing or advertising, and we do not\n    sell it or share it with advertisers, ad networks, or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/teamohana/privacy/teamohana-privacy-policy.yml
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
- sale_or_sharing
summary_line: 26 quoted statements, read from TeamOhana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Headcount Management
- Headcount Planning
- Workforce Planning
- Talent Acquisition
- Finance
- SCIM
- Software-as-a-Service
---
