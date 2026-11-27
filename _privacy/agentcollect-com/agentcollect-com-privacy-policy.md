---
api_specs:
- filename: agentcollect-com-openapi-generated.yml
  format: yaml
  label: AgentCollect API
  slug: agentcollect-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcollect-com/openapi/_ae-authored/agentcollect-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account registration data (name, email, company name, phone number)
  - category: financial
    text: Billing and payment information (processed via Stripe; we do not store full card numbers)
  - category: device
    text: Device and browser information (IP address, browser type, operating system)
  - category: behavioral
    text: Usage data (pages visited, features used, session duration)
  - category: communication
    text: Communications with our support team
  deletion:
    route: Email privacy@agentcollect.com to exercise any right, including deletion
    text: Request deletion of your data (subject to legal retention requirements)
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide and operate platform
    text: Provide, operate, and maintain our AI-powered recovery platform
  - purpose: Transactions and notices
    text: Process transactions and send related information
  - purpose: Fraud and abuse prevention
    text: Detect, investigate, and prevent fraudulent transactions and abuse
  - purpose: Analytics
    text: Monitor and analyze trends, usage, and activities
  residency:
  - region: United States
    text: Your data may be transferred to and processed in the United States, where our servers and certain subprocessors are located.
  retention:
  - period: 90 days
    scope: Account data
    text: Account data is deleted within 90 days of account closure.
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your data (subject to legal retention requirements)
  - right: Opt out of marketing
    text: Opt out of marketing communications
  - right: CCPA right to opt out of sale or sharing
    text: Right to opt out of the sale or sharing of personal information
  - right: GDPR portability
    text: Right of access, rectification, erasure, and data portability
  - right: Object to processing
    text: Right to restrict or object to processing
  - right: Complaint
    text: Right to lodge a complaint with a supervisory authority
  role:
    text: For data about your own account and your use of our website , AgentCollect is the controller and this policy applies directly. For the debtor and invoice data you upload to run collections, you are the controller and AgentCollect is your processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: a current list of subprocessors is available to customers on request, as described in our Data Processing Addendum
    url: null
  transfers:
  - mechanism: SCC
    text: For personal data subject to the EU or UK GDPR, these transfers are governed by the European Commission's Standard Contractual Clauses (and the UK Addendum where applicable)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentCollect
provenance_date: '2026-11-09'
provider_name: AgentCollect
provider_slug: agentcollect-com
slug: agentcollect-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentcollect-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agentcollect.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentCollect\naid: agentcollect-com\nurl: https://www.agentcollect.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For data about your own account and your use of our website , AgentCollect is the controller and this policy\n    applies directly. For the debtor and invoice data you upload to run collections, you are the controller and\n    AgentCollect is your processor\ndata_categories:\n- category: identifying\n  text: Account registration data (name, email, company name, phone number)\n- category: financial\n  text: Billing and payment information (processed via Stripe; we do not store\
  \ full card numbers)\n- category: device\n  text: Device and browser information (IP address, browser type, operating system)\n- category: behavioral\n  text: Usage data (pages visited, features used, session duration)\n- category: communication\n  text: Communications with our support team\npurposes:\n- purpose: Provide and operate platform\n  text: Provide, operate, and maintain our AI-powered recovery platform\n- purpose: Transactions and notices\n  text: Process transactions and send related information\n- purpose: Fraud and abuse prevention\n  text: Detect, investigate, and prevent fraudulent transactions and abuse\n- purpose: Analytics\n  text: Monitor and analyze trends, usage, and activities\nretention:\n- scope: Account data\n  period: 90 days\n  text: Account data is deleted within 90 days of account closure.\nresidency:\n- region: United States\n  text: Your data may be transferred to and processed in the United States, where our servers and certain subprocessors\n    are located.\n\
  transfers:\n- mechanism: SCC\n  text: For personal data subject to the EU or UK GDPR, these transfers are governed by the European Commission's\n    Standard Contractual Clauses (and the UK Addendum where applicable)\nsubprocessors:\n  url: null\n  text: a current list of subprocessors is available to customers on request, as described in our Data Processing\n    Addendum\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: Email privacy@agentcollect.com to exercise any right, including deletion\n  text: Request deletion of your data (subject to legal retention requirements)\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your data (subject to legal retention requirements)\n- right: Opt out of marketing\n  text: Opt out of marketing communications\n- right: CCPA right to opt out of sale or sharing\n  text:\
  \ Right to opt out of the sale or sharing of personal information\n- right: GDPR portability\n  text: Right of access, rectification, erasure, and data portability\n- right: Object to processing\n  text: Right to restrict or object to processing\n- right: Complaint\n  text: Right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/agentcollect-com/privacy/agentcollect-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from AgentCollect's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Artificial Intelligence
- Billing
- Payments
- Software-as-a-Service
- Company
---
