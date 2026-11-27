---
api_specs:
- filename: buggazi-com-openapi-generated.yml
  format: yaml
  label: Buggazi API
  slug: buggazi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buggazi-com/openapi/_ae-authored/buggazi-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name and display name
  - category: contact
    text: Email address
  - category: financial
    text: Payment card details (processed and stored securely by our payment processor, Stripe ; Buggazi does not store full card numbers on our servers)
  - category: device
    text: IP address
  - category: behavioral
    text: Feature usage patterns and frequency
  - category: communication
    text: Customer support inquiries and correspondence
  - category: professional
    text: Organisation or project name
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and maintaining services
    text: Creating and managing your Buggazi account and API keys
  - purpose: Improving platform
    text: Analysing usage patterns to improve features, user experience, and platform performance
  - purpose: Communications
    text: Sending marketing communications about new features, updates, and offers (with your consent, where required)
  - purpose: Security and fraud
    text: Detecting, preventing, and addressing fraud, abuse, and security incidents
  - purpose: Legal compliance
    text: Complying with applicable laws, regulations, and legal processes
  retention:
  - period: up to 12 months
    scope: Log data
    text: Server logs, API request logs, and technical data are typically retained for up to 12 months for security, debugging, and analytical purposes
  - period: a minimum of 6 years
    scope: Transaction records
    text: We retain transaction and billing data for a minimum of 6 years from the date of the transaction
  - period: within 30 days
    scope: Deleted Tenant accounts
    text: When a Tenant deletes their account, we will permanently delete their personal data and project data (including bugs, features, sprints, and uploaded screenshots) within 30 days, except where retention is required for legal compliance.
  rights:
  - right: Access
    text: 'Right of Access: You have the right to request a copy of the personal data we hold about you, along with information about how we process it.'
  - right: Rectification
    text: 'Right to Rectification: You have the right to request the correction of inaccurate or incomplete personal data we hold about you.'
  - right: Erasure
    text: 'Right to Erasure ("Right to Be Forgotten"): You have the right to request the deletion of your personal data in certain circumstances'
  - right: Portability
    text: 'Right to Data Portability: You have the right to receive your personal data in a structured, commonly used, and machine-readable format'
  - right: Object
    text: 'Right to Object: You have the right to object to the processing of your personal data based on our legitimate interests or for direct marketing purposes.'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: Where processing is based on your consent, you have the right to withdraw your consent at any time'
  role:
    text: Buggazi acts as the data controller for personal data that we collect directly from you in connection with your use of our platform.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We use the European Commission's Standard Contractual Clauses and the UK International Data Transfer Agreement (IDTA) or UK Addendum to the EU SCCs, as applicable, when transferring personal data to service providers or other recipients outside the UK/EEA.
  - mechanism: adequacy
    text: Where the European Commission or the UK Secretary of State has determined that a country provides an adequate level of data protection, we may rely on such adequacy decisions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Buggazi
provenance_date: '2026-11-09'
provider_name: Buggazi
provider_slug: buggazi-com
slug: buggazi-com-privacy-policy
source_date: '2026-11-09'
source_filename: buggazi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buggazi.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Buggazi\naid: buggazi-com\nurl: https://buggazi.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Buggazi acts as the data controller for personal data that we collect directly from you in connection with\n    your use of our platform.\ndata_categories:\n- category: identifying\n  text: Full name and display name\n- category: contact\n  text: Email address\n- category: financial\n  text: Payment card details (processed and stored securely by our payment processor, Stripe ; Buggazi does not\n    store full card numbers on our servers)\n- category: device\n  text: IP address\n- category:\
  \ behavioral\n  text: Feature usage patterns and frequency\n- category: communication\n  text: Customer support inquiries and correspondence\n- category: professional\n  text: Organisation or project name\npurposes:\n- purpose: Providing and maintaining services\n  text: Creating and managing your Buggazi account and API keys\n- purpose: Improving platform\n  text: Analysing usage patterns to improve features, user experience, and platform performance\n- purpose: Communications\n  text: Sending marketing communications about new features, updates, and offers (with your consent, where required)\n- purpose: Security and fraud\n  text: Detecting, preventing, and addressing fraud, abuse, and security incidents\n- purpose: Legal compliance\n  text: Complying with applicable laws, regulations, and legal processes\nretention:\n- scope: Log data\n  period: up to 12 months\n  text: Server logs, API request logs, and technical data are typically retained for up to 12 months for security,\n    debugging,\
  \ and analytical purposes\n- scope: Transaction records\n  period: a minimum of 6 years\n  text: We retain transaction and billing data for a minimum of 6 years from the date of the transaction\n- scope: Deleted Tenant accounts\n  period: within 30 days\n  text: When a Tenant deletes their account, we will permanently delete their personal data and project data (including\n    bugs, features, sprints, and uploaded screenshots) within 30 days, except where retention is required for legal\n    compliance.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: We use the European Commission's Standard Contractual Clauses and the UK International Data Transfer Agreement\n    (IDTA) or UK Addendum to the EU SCCs, as applicable, when transferring personal data to service providers or\n    other recipients outside the UK/EEA.\n- mechanism: adequacy\n  text: Where the European Commission or the UK Secretary of State has determined that a country provides an adequate\n    level of data protection,\
  \ we may rely on such adequacy decisions.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: 'Right of Access: You have the right to request a copy of the personal data we hold about you, along with\n    information about how we process it.'\n- right: Rectification\n  text: 'Right to Rectification: You have the right to request the correction of inaccurate or incomplete personal\n    data we hold about you.'\n- right: Erasure\n  text: 'Right to Erasure (\"Right to Be Forgotten\"): You have the right to request the deletion of your personal\n    data in certain circumstances'\n- right: Portability\n  text: 'Right to Data Portability: You have the right to receive your personal data in a structured, commonly used,\n    and machine-readable format'\n- right: Object\n  text: 'Right to Object: You have the right to object to the processing of your personal data based on our\
  \ legitimate\n    interests or for direct marketing purposes.'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent: Where processing is based on your consent, you have the right to withdraw your\n    consent at any time'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/buggazi-com/privacy/buggazi-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Buggazi's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Bug Tracking
- Sprint Planning
- AI Coding Agents
- Collaboration
---
