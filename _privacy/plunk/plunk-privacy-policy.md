---
api_specs:
- filename: plunk-campaigns-api-openapi.yml
  format: yaml
  label: Plunk Campaigns API
  slug: plunk-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-campaigns-api-openapi.yml
- filename: plunk-contacts-api-openapi.yml
  format: yaml
  label: Plunk Contacts API
  slug: plunk-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-contacts-api-openapi.yml
- filename: plunk-events-api-openapi.yml
  format: yaml
  label: Plunk Events API
  slug: plunk-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-events-api-openapi.yml
- filename: plunk-transactional-api-openapi.yml
  format: yaml
  label: Plunk Transactional API
  slug: plunk-transactional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-transactional-api-openapi.yml
- filename: plunk-public-api-api-openapi.yml
  format: yaml
  label: Plunk Public API
  slug: plunk-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-public-api-api-openapi.yml
- filename: plunk-segments-api-openapi.yml
  format: yaml
  label: Plunk Segments API
  slug: plunk-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-segments-api-openapi.yml
- filename: plunk-templates-api-openapi.yml
  format: yaml
  label: Plunk Templates API
  slug: plunk-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plunk/openapi/plunk-templates-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (required for login and notifications)
  - category: contact
    text: Contact email addresses
  - category: behavioral
    text: Open count and click count (aggregated)
  - category: device
    text: IP address and user-agent
  - category: financial
    text: Billing email, usage amounts, transaction history
  deletion:
    route: Dashboard > Settings > Delete Account, or email legal@useplunk.com
    text: Immediate and permanent deletion (no grace period)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: 'We use your data to: Authenticate you and maintain your session (JWT tokens) Send emails on your behalf via AWS SES'
  - purpose: Billing and payments
    text: Process payments via Stripe
  - purpose: Security and compliance
    text: Suspicious login attempts
  residency:
  - region: EU/EEA
    text: All data is stored in the European Union / European Economic Area
  retention:
  - period: Until you delete your account
    scope: Account data
    text: 'Retained: Until you delete your account'
  - period: Until you delete contacts or your account
    scope: Contact data
    text: 'Retained: Until you delete contacts or your account'
  - period: Indefinitely
    scope: Email activity data
    text: 'Retained: Indefinitely (for analytics and deliverability tracking)'
  - period: 30 days
    scope: API request logs
    text: 'Retained: 30 days (automatic deletion)'
  rights:
  - right: Access
    text: Request a copy of all personal data we hold about you
  - right: Rectification
    text: Correct inaccurate or incomplete data
  - right: Erasure
    text: Delete your account and all associated data
  - right: Portability
    text: Export your data in JSON format
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Restrict processing
    text: Temporarily limit how we process your data
  - right: Lodge a complaint
    text: File a complaint with your data protection authority
  role:
    text: 'Data Controller: For your account data (email, password, billing) Data Processor: For your contact data (we process on your behalf)'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We DO NOT sell your data. Ever.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Protected by Data Processing Agreements (DPA) and Standard Contractual Clauses (SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Plunk
provenance_date: '2026-11-10'
provider_name: Plunk
provider_slug: plunk
slug: plunk-privacy-policy
source_date: '2026-11-10'
source_filename: plunk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.useplunk.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Plunk\naid: plunk\nurl: https://www.useplunk.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Data Controller: For your account data (email, password, billing) Data Processor: For your contact data\n    (we process on your behalf)'\ndata_categories:\n- category: identifying\n  text: Email address (required for login and notifications)\n- category: contact\n  text: Contact email addresses\n- category: behavioral\n  text: Open count and click count (aggregated)\n- category: device\n  text: IP address and user-agent\n- category: financial\n  text: Billing email, usage amounts, transaction\
  \ history\npurposes:\n- purpose: Service delivery\n  text: 'We use your data to: Authenticate you and maintain your session (JWT tokens) Send emails on your behalf\n    via AWS SES'\n- purpose: Billing and payments\n  text: Process payments via Stripe\n- purpose: Security and compliance\n  text: Suspicious login attempts\nretention:\n- scope: Account data\n  period: Until you delete your account\n  text: 'Retained: Until you delete your account'\n- scope: Contact data\n  period: Until you delete contacts or your account\n  text: 'Retained: Until you delete contacts or your account'\n- scope: Email activity data\n  period: Indefinitely\n  text: 'Retained: Indefinitely (for analytics and deliverability tracking)'\n- scope: API request logs\n  period: 30 days\n  text: 'Retained: 30 days (automatic deletion)'\nresidency:\n- region: EU/EEA\n  text: All data is stored in the European Union / European Economic Area\ntransfers:\n- mechanism: SCC\n  text: Protected by Data Processing Agreements\
  \ (DPA) and Standard Contractual Clauses (SCCs)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard > Settings > Delete Account, or email legal@useplunk.com\n  text: Immediate and permanent deletion (no grace period)\nrights:\n- right: Access\n  text: Request a copy of all personal data we hold about you\n- right: Rectification\n  text: Correct inaccurate or incomplete data\n- right: Erasure\n  text: Delete your account and all associated data\n- right: Portability\n  text: Export your data in JSON format\n- right: Object\n  text: Object to processing based on legitimate interests\n- right: Restrict processing\n  text: Temporarily limit how we process your data\n- right: Lodge a complaint\n  text: File a complaint with your data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We DO NOT sell your data. Ever.\n"
source_yaml_url: https://artifacts.apis.io/plunk/privacy/plunk-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Plunk's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Transactional Email
- Marketing
- Automation
- Open Source
- Software-as-a-Service
- Email API
- Webhook
- Segmentation
- Workflow Automation
- Self-Hosted
- Developer Tools
---
