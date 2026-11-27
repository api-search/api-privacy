---
api_specs:
- filename: userlens-events-api-openapi.yml
  format: yaml
  label: Userlens Events API
  slug: userlens-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/userlens/openapi/userlens-events-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Contact and account information: name, work email address, company, role, login details, and account identifiers.'
  - category: financial
    text: 'Billing and transaction information: billing contact, billing address, plan, and transaction records.'
  - category: behavioral
    text: product usage and behavioral data, such as events, sessions, feature interactions, and activity over time
  - category: device
    text: technical data, such as browser, device, IP address, log, and security information
  - category: communication
    text: 'Communications: messages, meeting details, support requests, feedback, and other information you send to us.'
  deletion:
    route: Contact us using the details below, or delete or return customer data after termination or a valid customer request
    text: We delete or return customer personal data after termination or a valid customer request, subject to legal requirements and limited backup retention.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, support, and bill for the Services
    text: Provide, operate, support, and bill for the Services
  - purpose: Analytics after consent
    text: Analyze and improve the website after you accept analytics cookies
  - purpose: Marketing
    text: Send marketing where permitted and manage your preferences
  - purpose: AI-driven personalized guidance
    text: The Services use artificial intelligence to analyze product context and behavior, identify adoption opportunities, and prepare personalized guidance.
  residency:
  - region: Frankfurt and Stockholm
    text: Our primary service infrastructure is hosted in AWS regions in Frankfurt and Stockholm.
  retention:
  - period: current rolling year and the two previous calendar years
    scope: Customer data
    text: Unless otherwise agreed, the standard service retention period covers the current rolling year and the two previous calendar years.
  - period: up to one year
    scope: PostHog analytics identifiers
    text: PostHog analytics identifiers may be stored in cookies and local storage for up to one year.
  rights:
  - right: access
    text: access personal information we hold about you
  - right: correction
    text: correct inaccurate or incomplete information
  - right: deletion or restriction
    text: request deletion or restriction of processing
  - right: objection
    text: object to processing based on legitimate interests or direct marketing
  - right: portability
    text: receive certain information in a portable format
  - right: withdraw consent
    text: withdraw consent at any time
  role:
    text: Userlens generally acts as the controller and decides why and how the information is processed. When a customer sends us information about the Accounts and People who use its product, the customer is the controller and Userlens acts as its processor.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: When required, we use recognized safeguards for international transfers, such as adequacy decisions or standard contractual clauses.
  - mechanism: SCC
    text: When required, we use recognized safeguards for international transfers, such as adequacy decisions or standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Userlens
provenance_date: '2026-11-10'
provider_name: Userlens
provider_slug: userlens
slug: userlens-privacy-policy
source_date: '2026-11-10'
source_filename: userlens-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://userlens.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Userlens\naid: userlens\nurl: https://userlens.io/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Userlens generally acts as the controller and decides why and how the information is processed. When a customer\n    sends us information about the Accounts and People who use its product, the customer is the controller and Userlens\n    acts as its processor.\ndata_categories:\n- category: identifying\n  text: 'Contact and account information: name, work email address, company, role, login details, and account identifiers.'\n- category: financial\n  text: 'Billing and transaction information:\
  \ billing contact, billing address, plan, and transaction records.'\n- category: behavioral\n  text: product usage and behavioral data, such as events, sessions, feature interactions, and activity over time\n- category: device\n  text: technical data, such as browser, device, IP address, log, and security information\n- category: communication\n  text: 'Communications: messages, meeting details, support requests, feedback, and other information you send to\n    us.'\npurposes:\n- purpose: Provide, operate, support, and bill for the Services\n  text: Provide, operate, support, and bill for the Services\n- purpose: Analytics after consent\n  text: Analyze and improve the website after you accept analytics cookies\n- purpose: Marketing\n  text: Send marketing where permitted and manage your preferences\n- purpose: AI-driven personalized guidance\n  text: The Services use artificial intelligence to analyze product context and behavior, identify adoption opportunities,\n    and prepare personalized\
  \ guidance.\nretention:\n- scope: Customer data\n  period: current rolling year and the two previous calendar years\n  text: Unless otherwise agreed, the standard service retention period covers the current rolling year and the two\n    previous calendar years.\n- scope: PostHog analytics identifiers\n  period: up to one year\n  text: PostHog analytics identifiers may be stored in cookies and local storage for up to one year.\nresidency:\n- region: Frankfurt and Stockholm\n  text: Our primary service infrastructure is hosted in AWS regions in Frankfurt and Stockholm.\ntransfers:\n- mechanism: adequacy\n  text: When required, we use recognized safeguards for international transfers, such as adequacy decisions or standard\n    contractual clauses.\n- mechanism: SCC\n  text: When required, we use recognized safeguards for international transfers, such as adequacy decisions or standard\n    contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Contact us using the details below, or delete or return customer data after termination or a valid customer\n    request\n  text: We delete or return customer personal data after termination or a valid customer request, subject to legal\n    requirements and limited backup retention.\nrights:\n- right: access\n  text: access personal information we hold about you\n- right: correction\n  text: correct inaccurate or incomplete information\n- right: deletion or restriction\n  text: request deletion or restriction of processing\n- right: objection\n  text: object to processing based on legitimate interests or direct marketing\n- right: portability\n  text: receive certain information in a portable format\n- right: withdraw consent\n  text: withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/userlens/privacy/userlens-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Userlens's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Customer Success
- Product Analytics
- AI Agents
- Churn Prediction
- Event Tracking
- B2B SaaS
- Account Intelligence
---
