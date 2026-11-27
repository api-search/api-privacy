---
api_specs:
- filename: agent-api.yaml
  format: yaml
  label: callagent.pro Agent API
  slug: agent-api
  spec_type: OpenAPI
  url: https://www.callagent.pro/openapi/agent-api.yaml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and contact information (email address, phone number)
  - category: contact
    text: Caller phone numbers
  - category: financial
    text: Payment and billing information
  - category: communication
    text: Call recordings and transcripts
  - category: device
    text: IP address and device information
  - category: behavioral
    text: Usage patterns and preferences
  deletion:
    route: Request deletion via privacy@callagent.pro
    text: 'Deletion: Request deletion of your personal information'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve service
    text: Provide, maintain, and improve our AI phone assistant service
  - purpose: Customer support
    text: Provide customer support and respond to inquiries
  - purpose: Legal compliance
    text: Comply with legal obligations and enforce our terms
  - purpose: Fraud prevention
    text: Prevent fraud and ensure service security
  retention:
  - period: 90 days
    scope: Call recordings and transcripts
    text: Call recordings and transcripts are typically retained for 90 days unless you configure different retention settings.
  - period: null
    scope: Account information
    text: Account information is retained until you request account deletion.
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal information'
  - right: Correction
    text: 'Correction: Request correction of inaccurate information'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal information'
  - right: Portability
    text: 'Portability: Request transfer of your data to another service'
  - right: Objection
    text: 'Objection: Object to certain processing of your information'
  - right: Withdrawal
    text: 'Withdrawal: Withdraw consent at any time'
  role:
    text: callagent.pro ("we," "our," or "us") is committed to protecting your privacy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: callagent.pro
provenance_date: '2026-11-09'
provider_name: callagent.pro
provider_slug: callagentpro
slug: callagentpro-privacy-policy
source_date: '2026-11-09'
source_filename: callagentpro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.callagent.pro/policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: callagent.pro\naid: callagentpro\nurl: https://www.callagent.pro/policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: callagent.pro (\"we,\" \"our,\" or \"us\") is committed to protecting your privacy.\ndata_categories:\n- category: identifying\n  text: Name and contact information (email address, phone number)\n- category: contact\n  text: Caller phone numbers\n- category: financial\n  text: Payment and billing information\n- category: communication\n  text: Call recordings and transcripts\n- category: device\n  text: IP address and device information\n- category: behavioral\n  text: Usage\
  \ patterns and preferences\npurposes:\n- purpose: Provide and improve service\n  text: Provide, maintain, and improve our AI phone assistant service\n- purpose: Customer support\n  text: Provide customer support and respond to inquiries\n- purpose: Legal compliance\n  text: Comply with legal obligations and enforce our terms\n- purpose: Fraud prevention\n  text: Prevent fraud and ensure service security\nretention:\n- scope: Call recordings and transcripts\n  period: 90 days\n  text: Call recordings and transcripts are typically retained for 90 days unless you configure different retention\n    settings.\n- scope: Account information\n  period: null\n  text: Account information is retained until you request account deletion.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via privacy@callagent.pro\n  text: 'Deletion: Request deletion of your personal information'\nrights:\n\
  - right: Access\n  text: 'Access: Request a copy of your personal information'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal information'\n- right: Portability\n  text: 'Portability: Request transfer of your data to another service'\n- right: Objection\n  text: 'Objection: Object to certain processing of your information'\n- right: Withdrawal\n  text: 'Withdrawal: Withdraw consent at any time'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/callagentpro/privacy/callagentpro-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from callagent.pro's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Voice
- Telephony
- Phone Agents
- SIP
- x402
- Call Automation
---
