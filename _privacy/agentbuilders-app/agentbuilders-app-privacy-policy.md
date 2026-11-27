---
api_specs:
- filename: agentbuilders-app-openapi-generated.yml
  format: yaml
  label: AgentBuilders API
  slug: agentbuilders-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbuilders-app/openapi/_ae-authored/agentbuilders-app-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account information: email address, display name, and authentication credentials when you register.'
  - category: behavioral
    text: 'Usage data: deploy frequency, API call patterns, resource consumption, and feature usage.'
  - category: device
    text: 'Device and access data: IP address, browser type, operating system, and referral URLs collected automatically on each request.'
  - category: financial
    text: 'Payment information: billing details processed securely by Stripe.'
  - category: other
    text: 'Application data: source code, files, database records, and configuration you deploy to the platform.'
  deletion:
    route: Contact privacy@agentbuilders.app
    text: To request deletion of your data, contact us at privacy@agentbuilders.app .
  dpa:
    available: null
    text: All third-party processors are bound by data processing agreements.
    url: null
  purposes:
  - purpose: Operate and improve platform
    text: To operate, maintain, and improve the AgentBuilders platform.
  - purpose: Abuse and fraud prevention
    text: To detect and prevent abuse, fraud, and security threats.
  - purpose: Account communications
    text: To communicate with you about your account, billing, and service updates.
  - purpose: Aggregated analytics
    text: To generate aggregated, anonymized analytics to improve the Service.
  retention:
  - period: 30 days
    scope: Account data
    text: Upon account deletion request, account data is removed within 30 days.
  - period: 90 days
    scope: Usage logs
    text: 'Usage logs: server logs, API call records, and access logs are retained for 90 days, then permanently deleted.'
  - period: 30 days
    scope: Backups
    text: 'Backups: backup copies of your data are purged within 30 days after an account deletion request is processed.'
  - period: 7 years
    scope: Payment records
    text: 'Payment records: billing and transaction records are retained as required by applicable law, typically 7 years for tax and accounting purposes.'
  - period: 90 days
    scope: Analytics data
    text: 'Analytics data: raw analytics data is aggregated and anonymized after 90 days.'
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correction
    text: Request correction of inaccurate data.
  - right: Deletion
    text: Request deletion of your data (subject to legal retention requirements).
  - right: Portability
    text: Export your data in a portable format.
  - right: Objection or restriction
    text: Object to or restrict certain processing of your data.
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  role:
    text: The data controller for AgentBuilders.app is Vonkra Ltd .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'Cloudflare: Data Processing Addendum with Standard Contractual Clauses (SCCs).'
  - mechanism: DPF
    text: 'Stripe: EU-US Data Privacy Framework certified; SCCs in place.'
  - mechanism: SCC
    text: 'Sentry: SCCs and data processing agreement.'
  - mechanism: SCC
    text: 'Resend: Data processing agreement with SCCs.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentBuilders
provenance_date: '2026-11-09'
provider_name: AgentBuilders
provider_slug: agentbuilders-app
slug: agentbuilders-app-privacy-policy
source_date: '2026-11-09'
source_filename: agentbuilders-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentbuilders.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentBuilders\naid: agentbuilders-app\nurl: https://agentbuilders.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for AgentBuilders.app is Vonkra Ltd .\ndata_categories:\n- category: contact\n  text: 'Account information: email address, display name, and authentication credentials when you register.'\n- category: behavioral\n  text: 'Usage data: deploy frequency, API call patterns, resource consumption, and feature usage.'\n- category: device\n  text: 'Device and access data: IP address, browser type, operating system, and referral URLs collected automatically\n\
  \    on each request.'\n- category: financial\n  text: 'Payment information: billing details processed securely by Stripe.'\n- category: other\n  text: 'Application data: source code, files, database records, and configuration you deploy to the platform.'\npurposes:\n- purpose: Operate and improve platform\n  text: To operate, maintain, and improve the AgentBuilders platform.\n- purpose: Abuse and fraud prevention\n  text: To detect and prevent abuse, fraud, and security threats.\n- purpose: Account communications\n  text: To communicate with you about your account, billing, and service updates.\n- purpose: Aggregated analytics\n  text: To generate aggregated, anonymized analytics to improve the Service.\nretention:\n- scope: Account data\n  period: 30 days\n  text: Upon account deletion request, account data is removed within 30 days.\n- scope: Usage logs\n  period: 90 days\n  text: 'Usage logs: server logs, API call records, and access logs are retained for 90 days, then permanently\
  \ deleted.'\n- scope: Backups\n  period: 30 days\n  text: 'Backups: backup copies of your data are purged within 30 days after an account deletion request is processed.'\n- scope: Payment records\n  period: 7 years\n  text: 'Payment records: billing and transaction records are retained as required by applicable law, typically\n    7 years for tax and accounting purposes.'\n- scope: Analytics data\n  period: 90 days\n  text: 'Analytics data: raw analytics data is aggregated and anonymized after 90 days.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: 'Cloudflare: Data Processing Addendum with Standard Contractual Clauses (SCCs).'\n- mechanism: DPF\n  text: 'Stripe: EU-US Data Privacy Framework certified; SCCs in place.'\n- mechanism: SCC\n  text: 'Sentry: SCCs and data processing agreement.'\n- mechanism: SCC\n  text: 'Resend: Data processing agreement with SCCs.'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: All third-party processors\
  \ are bound by data processing agreements.\ndeletion:\n  route: Contact privacy@agentbuilders.app\n  text: To request deletion of your data, contact us at privacy@agentbuilders.app .\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correction\n  text: Request correction of inaccurate data.\n- right: Deletion\n  text: Request deletion of your data (subject to legal retention requirements).\n- right: Portability\n  text: Export your data in a portable format.\n- right: Objection or restriction\n  text: Object to or restrict certain processing of your data.\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/agentbuilders-app/privacy/agentbuilders-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from AgentBuilders's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Deployment
- Agents
- Automation
- Company
---
