---
api_specs:
- filename: githunt-ai-briefs-api-openapi.yml
  format: yaml
  label: githunt-ai Briefs API
  slug: githunt-ai-briefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-briefs-api-openapi.yml
- filename: githunt-ai-lists-api-openapi.yml
  format: yaml
  label: githunt-ai Lists API
  slug: githunt-ai-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-lists-api-openapi.yml
- filename: githunt-ai-profile-api-openapi.yml
  format: yaml
  label: githunt-ai Profile API
  slug: githunt-ai-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-profile-api-openapi.yml
- filename: githunt-ai-search-api-openapi.yml
  format: yaml
  label: githunt-ai Search API
  slug: githunt-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-search-api-openapi.yml
- filename: githunt-ai-users-api-openapi.yml
  format: yaml
  label: githunt-ai Users API
  slug: githunt-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/githunt-ai/openapi/githunt-ai-users-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name, and password for account creation.
  - category: contact
    text: Name, email address, and message content via our contact form
  - category: financial
    text: Account data includes plan status, usage counts, and credit balance.
  - category: behavioral
    text: Through Google Analytics, we collect anonymized data about your visit including pages viewed, time spent, browser type, and referring website
  - category: device
    text: 'Technical Data: IP address (anonymized), device information, and browser type'
  deletion:
    route: email privacy@githunt.ai
    text: To exercise these rights, please contact us at privacy@githunt.ai
  dpa:
    available: true
    text: AWS data centers with GDPR-compliant data processing agreements
    url: null
  purposes:
  - purpose: service delivery
    text: To search GitHub and generate developer talent reports based on your criteria
  - purpose: payment processing
    text: To process your payments securely through Stripe
  - purpose: analytics
    text: To understand how users interact with our website and improve our services
  retention:
  - period: null
    scope: search queries
    text: Not permanently stored; processed in real-time
  - period: 30 days
    scope: generated reports
    text: Stored for 30 days for re-download, then permanently deleted
  - period: 7 years
    scope: purchase records
    text: Retained for accounting and legal compliance (7 years)
  - period: 7 years after account deletion
    scope: account data
    text: are retained while the account is active and for 7 years after account deletion for legal compliance
  rights:
  - right: access
    text: 'Right to Access: Request a copy of your personal data'
  - right: erasure
    text: 'Right to Erasure: Request deletion of your data'
  - right: objection
    text: 'Right to Object: Object to processing based on legitimate interests'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) for data transfers
  - mechanism: DPF
    text: Service providers certified under EU-U.S. Data Privacy Framework where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: githunt-ai
provenance_date: '2026-11-09'
provider_name: githunt-ai
provider_slug: githunt-ai
slug: githunt-ai-privacy-policy
source_date: '2026-11-09'
source_filename: githunt-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://githunt.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: githunt-ai\naid: githunt-ai\nurl: https://githunt.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, name, and password for account creation.\n- category: contact\n  text: Name, email address, and message content via our contact form\n- category: financial\n  text: Account data includes plan status, usage counts, and credit balance.\n- category: behavioral\n  text: Through Google Analytics, we collect anonymized data about your visit including pages viewed, time spent,\n    browser type, and referring website\n- category:\
  \ device\n  text: 'Technical Data: IP address (anonymized), device information, and browser type'\npurposes:\n- purpose: service delivery\n  text: To search GitHub and generate developer talent reports based on your criteria\n- purpose: payment processing\n  text: To process your payments securely through Stripe\n- purpose: analytics\n  text: To understand how users interact with our website and improve our services\nretention:\n- scope: search queries\n  period: null\n  text: Not permanently stored; processed in real-time\n- scope: generated reports\n  period: 30 days\n  text: Stored for 30 days for re-download, then permanently deleted\n- scope: purchase records\n  period: 7 years\n  text: Retained for accounting and legal compliance (7 years)\n- scope: account data\n  period: 7 years after account deletion\n  text: are retained while the account is active and for 7 years after account deletion for legal compliance\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual\
  \ Clauses (SCCs) for data transfers\n- mechanism: DPF\n  text: Service providers certified under EU-U.S. Data Privacy Framework where applicable\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: AWS data centers with GDPR-compliant data processing agreements\ndeletion:\n  route: email privacy@githunt.ai\n  text: To exercise these rights, please contact us at privacy@githunt.ai\nrights:\n- right: access\n  text: 'Right to Access: Request a copy of your personal data'\n- right: erasure\n  text: 'Right to Erasure: Request deletion of your data'\n- right: objection\n  text: 'Right to Object: Object to processing based on legitimate interests'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/githunt-ai/privacy/githunt-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from githunt-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Talent
- Recruiting
- Developers
---
