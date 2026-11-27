---
api_specs:
- filename: evari-quotes-api-openapi.yml
  format: yaml
  label: Evari Quotes API
  slug: evari-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evari/openapi/evari-quotes-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address
  - category: contact
    text: Phone number (optional)
  - category: behavioral
    text: Pages visited, time spent, click patterns, device type, browser, IP address (anonymized)
  - category: communication
    text: Message content
  - category: professional
    text: Company information (if applicable)
  - category: other
    text: Text, documents, and files you upload
  deletion:
    route: Request via privacy@evari.tech
    text: You can request deletion of your data at any time (except where we're legally required to retain it). Contact privacy@evari.tech.
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide services
    text: Process your requests, run AI agents, and deliver platform functionality
  - purpose: Service improvement
    text: Analyze usage patterns to improve our platform and develop new features
  - purpose: Security monitoring
    text: Detect and prevent fraud, abuse, and security threats
  - purpose: Communication
    text: Send service updates, security notices, and support messages
  residency:
  - region: UK
    text: Contact data is processed in the UK on Google Cloud Platform (GCP).
  retention:
  - period: Until you delete or cancel account + 48 hours
    scope: Service Content
    text: Until you delete or cancel account + 48 hours
  - period: Until account deletion + 30 days
    scope: Account Data
    text: Until account deletion + 30 days
  - period: 3 years
    scope: Contact Form Submissions
    text: Contact inquiries are retained for 3 years to maintain business records, then securely deleted.
  - period: 6 years
    scope: Payment/Billing Records
    text: Payment/Billing Records 6 years Tax/legal compliance (UK requirement)
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal data'
  - right: Portability
    text: 'Portability: Receive your data in a portable format'
  - right: Rectification
    text: 'Rectification: Correct inaccurate personal data'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests'
  - right: Restriction
    text: 'Restriction: Restrict certain processing activities'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal data and only share it as described in this policy.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When we transfer data internationally, we implement appropriate safeguards including Standard Contractual Clauses as described in our Data Processing Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Evari
provenance_date: '2026-11-09'
provider_name: Evari
provider_slug: evari
slug: evari-privacy-policy
source_date: '2026-11-09'
source_filename: evari-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.evari.tech/legal#privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Evari\naid: evari\nurl: https://www.evari.tech/legal#privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and email address\n- category: contact\n  text: Phone number (optional)\n- category: behavioral\n  text: Pages visited, time spent, click patterns, device type, browser, IP address (anonymized)\n- category: communication\n  text: Message content\n- category: professional\n  text: Company information (if applicable)\n- category: other\n  text: Text, documents, and files you upload\npurposes:\n- purpose: Provide services\n  text:\
  \ Process your requests, run AI agents, and deliver platform functionality\n- purpose: Service improvement\n  text: Analyze usage patterns to improve our platform and develop new features\n- purpose: Security monitoring\n  text: Detect and prevent fraud, abuse, and security threats\n- purpose: Communication\n  text: Send service updates, security notices, and support messages\nretention:\n- scope: Service Content\n  period: Until you delete or cancel account + 48 hours\n  text: Until you delete or cancel account + 48 hours\n- scope: Account Data\n  period: Until account deletion + 30 days\n  text: Until account deletion + 30 days\n- scope: Contact Form Submissions\n  period: 3 years\n  text: Contact inquiries are retained for 3 years to maintain business records, then securely deleted.\n- scope: Payment/Billing Records\n  period: 6 years\n  text: Payment/Billing Records 6 years Tax/legal compliance (UK requirement)\nresidency:\n- region: UK\n  text: Contact data is processed in the UK\
  \ on Google Cloud Platform (GCP).\ntransfers:\n- mechanism: SCC\n  text: When we transfer data internationally, we implement appropriate safeguards including Standard Contractual\n    Clauses as described in our Data Processing Addendum.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: Request via privacy@evari.tech\n  text: You can request deletion of your data at any time (except where we're legally required to retain it). Contact\n    privacy@evari.tech.\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal data'\n- right: Portability\n  text: 'Portability: Receive your data in a portable format'\n- right: Rectification\n  text: 'Rectification: Correct inaccurate personal data'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests'\n- right: Restriction\n  text:\
  \ 'Restriction: Restrict certain processing activities'\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal data and only share it as described in this policy.\n"
source_yaml_url: https://artifacts.apis.io/evari/privacy/evari-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Evari's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Australia
- Insurtech
- Policy Administration
- Core Systems
- Property and Casualty
- Underwriting
- Claims
- Brokerage
- MGA
- Artificial Intelligence
- Quoting
- Endorsements
---
