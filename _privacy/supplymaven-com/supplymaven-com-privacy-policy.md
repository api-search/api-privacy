---
api_specs:
- filename: supplymaven-com-openapi-generated.yml
  format: yaml
  label: supplymaven-com API
  slug: supplymaven-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supplymaven-com/openapi/_ae-authored/supplymaven-com-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, company name, job title, and password when you register'
  - category: financial
    text: 'Billing Information: Payment card details, billing address, and transaction history'
  - category: device
    text: 'Device Information: Browser type, operating system, device type, screen resolution, and unique device identifiers'
  - category: location
    text: 'Location Data: General geographic location derived from IP address (we do not collect precise GPS location)'
  - category: behavioral
    text: 'Usage Data: Features accessed, pages viewed, time spent on platform, click patterns, and interaction with risk scores and recommendations'
  - category: communication
    text: 'Communications: Messages, feedback, support requests, and any other information you provide when contacting us'
  deletion:
    route: Request deletion via privacy@supplymaven.com
    text: 'Deletion: Request deletion of your personal data, subject to legal retention requirements'
  dpa:
    available: null
    text: Data Processing Agreements with all service providers
    url: null
  purposes:
  - purpose: Service delivery
    text: Provide, operate, and maintain the SupplyMaven platform and features
  - purpose: Analytics
    text: Understand usage patterns, measure performance, and improve our Service
  - purpose: Marketing communications
    text: Send transactional emails, service updates, security alerts, and (with consent) marketing materials
  - purpose: Security
    text: Detect, prevent, and respond to fraud, abuse, and security incidents
  residency:
  - region: United States
    text: SupplyMaven is based in the United States. If you access our Service from outside the United States, your information will be transferred to, stored, and processed in the United States
  retention:
  - period: 90 days after deletion request
    scope: Account data
    text: Retained while your account is active and for 90 days after deletion request to allow for recovery
  - period: 7 years
    scope: Billing records
    text: 'Billing Records: Retained for 7 years as required for tax and accounting purposes'
  - period: 12 months
    scope: Usage logs
    text: 'Usage Logs: Retained for 12 months for analytics and security purposes'
  - period: 3 years
    scope: Support communications
    text: 'Support Communications: Retained for 3 years to provide context for future inquiries'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal information we hold about you'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete data'
  - right: Portability
    text: 'Portability: Receive your data in a structured, machine-readable format'
  - right: Restriction
    text: 'Restriction: Request restriction of processing in certain circumstances'
  - right: Objection
    text: 'Objection: Object to processing based on legitimate interests'
  - right: Lodge complaint
    text: 'Lodge Complaint: File a complaint with your local Data Protection Authority'
  role:
    text: We operate as a Data Controller under applicable data protection laws
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'Our current service providers include: Clerk (authentication), Convex (database), Vercel (hosting), and Polar (payment processing).'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: supplymaven-com
provenance_date: '2026-11-10'
provider_name: supplymaven-com
provider_slug: supplymaven-com
slug: supplymaven-com-privacy-policy
source_date: '2026-11-10'
source_filename: supplymaven-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://supplymaven.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: supplymaven-com\naid: supplymaven-com\nurl: https://supplymaven.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We operate as a Data Controller under applicable data protection laws\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, company name, job title, and password when you register'\n- category: financial\n  text: 'Billing Information: Payment card details, billing address, and transaction history'\n- category: device\n  text: 'Device Information: Browser type, operating system, device type, screen resolution, and unique device identifiers'\n\
  - category: location\n  text: 'Location Data: General geographic location derived from IP address (we do not collect precise GPS location)'\n- category: behavioral\n  text: 'Usage Data: Features accessed, pages viewed, time spent on platform, click patterns, and interaction with\n    risk scores and recommendations'\n- category: communication\n  text: 'Communications: Messages, feedback, support requests, and any other information you provide when contacting\n    us'\npurposes:\n- purpose: Service delivery\n  text: Provide, operate, and maintain the SupplyMaven platform and features\n- purpose: Analytics\n  text: Understand usage patterns, measure performance, and improve our Service\n- purpose: Marketing communications\n  text: Send transactional emails, service updates, security alerts, and (with consent) marketing materials\n- purpose: Security\n  text: Detect, prevent, and respond to fraud, abuse, and security incidents\nretention:\n- scope: Account data\n  period: 90 days after deletion\
  \ request\n  text: Retained while your account is active and for 90 days after deletion request to allow for recovery\n- scope: Billing records\n  period: 7 years\n  text: 'Billing Records: Retained for 7 years as required for tax and accounting purposes'\n- scope: Usage logs\n  period: 12 months\n  text: 'Usage Logs: Retained for 12 months for analytics and security purposes'\n- scope: Support communications\n  period: 3 years\n  text: 'Support Communications: Retained for 3 years to provide context for future inquiries'\nresidency:\n- region: United States\n  text: SupplyMaven is based in the United States. If you access our Service from outside the United States, your\n    information will be transferred to, stored, and processed in the United States\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission\nsubprocessors:\n  url: null\n  text: 'Our current service providers include: Clerk (authentication), Convex (database), Vercel\
  \ (hosting), and\n    Polar (payment processing).'\ndpa:\n  available: null\n  url: null\n  text: Data Processing Agreements with all service providers\ndeletion:\n  route: Request deletion via privacy@supplymaven.com\n  text: 'Deletion: Request deletion of your personal data, subject to legal retention requirements'\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal information we hold about you'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete data'\n- right: Portability\n  text: 'Portability: Receive your data in a structured, machine-readable format'\n- right: Restriction\n  text: 'Restriction: Request restriction of processing in certain circumstances'\n- right: Objection\n  text: 'Objection: Object to processing based on legitimate interests'\n- right: Lodge complaint\n  text: 'Lodge Complaint: File a complaint with your local Data Protection Authority'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell\
  \ your personal information.\n"
source_yaml_url: https://artifacts.apis.io/supplymaven-com/privacy/supplymaven-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from supplymaven-com's own page on 2026-11-10.
synthetic: false
tags:
- Supply Chain
- Risk Intelligence
- Data Platform
- Analytics
- Logistics
---
