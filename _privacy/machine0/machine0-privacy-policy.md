---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, display name, profile image
  - category: contact
    text: Email address, display name, profile image
  - category: financial
    text: Stripe customer ID, wallet transactions, bandwidth measurements
  - category: location
    text: VM IP addresses, names, regions, sizes
  - category: behavioral
    text: User actions, IP address, page views (via PostHog, EU-hosted)
  - category: device
    text: Session tokens (with IP address and user agent), OAuth tokens, hashed passwords, API keys
  deletion:
    route: Contact email
    text: Contact [email protected] to exercise any of these rights.
  dpa:
    available: true
    text: Our Data Processing Agreement is available for review.
    url: null
  purposes:
  - purpose: Provide and improve service
    text: To provide, maintain, and improve the machine0 service
  - purpose: Authentication and security
    text: To authenticate you and secure your account
  - purpose: Billing
    text: To bill you accurately for resource usage
  - purpose: Abuse and fraud prevention
    text: To detect and prevent abuse, fraud, and security incidents
  - purpose: Legal compliance
    text: To comply with legal obligations (tax, accounting)
  residency:
  - region: United States
    text: Account data (email, billing, sessions, SSH keys) is hosted on Railway infrastructure in the United States.
  - region: Region selected by user
    text: VM data resides in the region you select when creating a VM.
  retention:
  - period: Duration of account + 30 days after deletion
    scope: Account identity
    text: Duration of account + 30 days after deletion
  - period: 10 years
    scope: Transaction records
    text: 'Transaction records: 10 years.'
  - period: 90 days
    scope: Request logs
    text: Request logs HTTP method, path, status code, response duration, user ID, IP address Legitimate interest (Art. 6(1)(f)), security and abuse prevention 90 days
  - period: Duration of resource existence + 90 days after destruction
    scope: Infrastructure metadata
    text: Duration of resource existence + 90 days after destruction
  rights:
  - right: Access
    text: Access your personal data
  - right: Rectify
    text: Rectify inaccurate data
  - right: Erase
    text: Erase your data (right to be forgotten)
  - right: Restrict processing
    text: Restrict processing
  - right: Portability
    text: Data portability (receive your data in a machine-readable format)
  - right: Object
    text: Object to processing based on legitimate interest
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: Complain
    text: Lodge a complaint with the CNIL (Commission Nationale de l'Informatique et des Libertés) or your local supervisory authority
  role:
    text: 'machine0 as data controller: We are the data controller for the personal data you provide to create and manage your machine0 account'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We share personal data with the following sub-processors: Processor Purpose Location Railway Application hosting, database, cache US'
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers to the United States rely on sub-processor data processing agreements incorporating Standard Contractual Clauses (SCCs) or applicable adequacy decisions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Machine0
provenance_date: '2026-11-10'
provider_name: Machine0
provider_slug: machine0
slug: machine0-privacy-policy
source_date: '2026-11-10'
source_filename: machine0-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://machine0.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Machine0\naid: machine0\nurl: https://machine0.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'machine0 as data controller: We are the data controller for the personal data you provide to create and\n    manage your machine0 account'\ndata_categories:\n- category: identifying\n  text: Email address, display name, profile image\n- category: contact\n  text: Email address, display name, profile image\n- category: financial\n  text: Stripe customer ID, wallet transactions, bandwidth measurements\n- category: location\n  text: VM IP addresses, names, regions, sizes\n- category: behavioral\n\
  \  text: User actions, IP address, page views (via PostHog, EU-hosted)\n- category: device\n  text: Session tokens (with IP address and user agent), OAuth tokens, hashed passwords, API keys\npurposes:\n- purpose: Provide and improve service\n  text: To provide, maintain, and improve the machine0 service\n- purpose: Authentication and security\n  text: To authenticate you and secure your account\n- purpose: Billing\n  text: To bill you accurately for resource usage\n- purpose: Abuse and fraud prevention\n  text: To detect and prevent abuse, fraud, and security incidents\n- purpose: Legal compliance\n  text: To comply with legal obligations (tax, accounting)\nretention:\n- scope: Account identity\n  period: Duration of account + 30 days after deletion\n  text: Duration of account + 30 days after deletion\n- scope: Transaction records\n  period: 10 years\n  text: 'Transaction records: 10 years.'\n- scope: Request logs\n  period: 90 days\n  text: Request logs HTTP method, path, status code,\
  \ response duration, user ID, IP address Legitimate interest\n    (Art. 6(1)(f)), security and abuse prevention 90 days\n- scope: Infrastructure metadata\n  period: Duration of resource existence + 90 days after destruction\n  text: Duration of resource existence + 90 days after destruction\nresidency:\n- region: United States\n  text: Account data (email, billing, sessions, SSH keys) is hosted on Railway infrastructure in the United States.\n- region: Region selected by user\n  text: VM data resides in the region you select when creating a VM.\ntransfers:\n- mechanism: SCC\n  text: Transfers to the United States rely on sub-processor data processing agreements incorporating Standard Contractual\n    Clauses (SCCs) or applicable adequacy decisions.\nsubprocessors:\n  url: null\n  text: 'We share personal data with the following sub-processors: Processor Purpose Location Railway Application\n    hosting, database, cache US'\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing\
  \ Agreement is available for review.\ndeletion:\n  route: Contact email\n  text: Contact [email protected] to exercise any of these rights.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Erase\n  text: Erase your data (right to be forgotten)\n- right: Restrict processing\n  text: Restrict processing\n- right: Portability\n  text: Data portability (receive your data in a machine-readable format)\n- right: Object\n  text: Object to processing based on legitimate interest\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent\n- right: Complain\n  text: Lodge a complaint with the CNIL (Commission Nationale de l'Informatique et des Libertés) or your local supervisory\n    authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/machine0/privacy/machine0-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Machine0's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Infrastructure
- Virtual Machines
- AI Agents
- Developer Tools
- CLI
- MCP
---
