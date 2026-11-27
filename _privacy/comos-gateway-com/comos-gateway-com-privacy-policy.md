---
api_specs:
- filename: comos-gateway-com-actions-api-openapi.yml
  format: yaml
  label: comos-gateway-com Actions API
  slug: comos-gateway-com-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comos-gateway-com/openapi/comos-gateway-com-actions-api-openapi.yml
- filename: comos-gateway-com-tools-api-openapi.yml
  format: yaml
  label: comos-gateway-com Tools API
  slug: comos-gateway-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comos-gateway-com/openapi/comos-gateway-com-tools-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone number
  - category: contact
    text: Business name and address
  - category: financial
    text: Billing information and payment details
  - category: behavioral
    text: Pages visited and features used
  - category: device
    text: IP address and approximate location
  - category: communication
    text: Support requests and correspondence
  deletion:
    route: Email support@comos-federation.com or request deletion of account and data
    text: Request deletion of your account and data
  dpa:
    available: true
    text: Our [Data Processing Agreement](https://comos-federation.com/dpa) ("DPA") is **incorporated by reference into the [Terms of Service](https://comos-federation.com/terms) and applies automatically**
    url: https://comos-federation.com/dpa
  purposes:
  - purpose: Provide the service
    text: Create and manage your account
  - purpose: Security and fraud prevention
    text: Detect and prevent fraud and abuse
  - purpose: Marketing communications
    text: Marketing communications (with consent)
  - purpose: In-platform AI features
    text: Power in-Platform AI features (search, recommendations, automation, brand voice, policy enforcement)
  residency:
  - region: United States
    text: Tenant data is stored in Google Cloud and MongoDB Atlas in the United States.
  retention:
  - period: 90 days
    scope: MCP audit logs
    text: MCP audit logs are retained for **90 days**, then automatically deleted by a database time-to-live (TTL) policy.
  - period: 30 days
    scope: After account termination - export
    text: '**30 days**: Data available for export'
  - period: 90 days
    scope: After account termination - production deletion
    text: '**90 days**: Data deleted from production systems'
  - period: 1 year
    scope: After account termination - backups
    text: '**1 year**: Data purged from backups'
  rights:
  - right: Access
    text: Access your data through the Platform dashboard
  - right: Portability
    text: Export your data in standard formats (CSV, JSON)
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your account and data
  - right: Opt-out of marketing
    text: Opt out of marketing emails via unsubscribe link
  - right: Withdraw consent (GDPR)
    text: Withdraw consent at any time
  - right: Object (GDPR)
    text: Object to processing based on legitimate interests
  role:
    text: '**ComOS is the Data Processor**.'
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: This is the complete list of ComOS sub-processors, and it is identical to Appendix A of the [Data Processing Agreement](https://comos-federation.com/dpa), which also gives each one's location.
    url: https://comos-federation.com/dpa
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses approved by the European Commission to protect EEA/UK/Swiss personal data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: comos-gateway-com
provenance_date: '2026-11-09'
provider_name: comos-gateway-com
provider_slug: comos-gateway-com
slug: comos-gateway-com-privacy-policy
source_date: '2026-11-09'
source_filename: comos-gateway-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://comos-gateway.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: comos-gateway-com\naid: comos-gateway-com\nurl: https://comos-gateway.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: '**ComOS is the Data Processor**.'\ndata_categories:\n- category: identifying\n  text: Name, email address, phone number\n- category: contact\n  text: Business name and address\n- category: financial\n  text: Billing information and payment details\n- category: behavioral\n  text: Pages visited and features used\n- category: device\n  text: IP address and approximate location\n- category: communication\n  text: Support requests and correspondence\npurposes:\n- purpose:\
  \ Provide the service\n  text: Create and manage your account\n- purpose: Security and fraud prevention\n  text: Detect and prevent fraud and abuse\n- purpose: Marketing communications\n  text: Marketing communications (with consent)\n- purpose: In-platform AI features\n  text: Power in-Platform AI features (search, recommendations, automation, brand voice, policy enforcement)\nretention:\n- scope: MCP audit logs\n  period: 90 days\n  text: MCP audit logs are retained for **90 days**, then automatically deleted by a database time-to-live (TTL)\n    policy.\n- scope: After account termination - export\n  period: 30 days\n  text: '**30 days**: Data available for export'\n- scope: After account termination - production deletion\n  period: 90 days\n  text: '**90 days**: Data deleted from production systems'\n- scope: After account termination - backups\n  period: 1 year\n  text: '**1 year**: Data purged from backups'\nresidency:\n- region: United States\n  text: Tenant data is stored in Google\
  \ Cloud and MongoDB Atlas in the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses approved by the European Commission to protect EEA/UK/Swiss personal\n    data.\nsubprocessors:\n  url: https://comos-federation.com/dpa\n  text: This is the complete list of ComOS sub-processors, and it is identical to Appendix A of the [Data Processing\n    Agreement](https://comos-federation.com/dpa), which also gives each one's location.\ndpa:\n  available: true\n  url: https://comos-federation.com/dpa\n  text: Our [Data Processing Agreement](https://comos-federation.com/dpa) (\"DPA\") is **incorporated by reference\n    into the [Terms of Service](https://comos-federation.com/terms) and applies automatically**\ndeletion:\n  route: Email support@comos-federation.com or request deletion of account and data\n  text: Request deletion of your account and data\nrights:\n- right: Access\n  text: Access your data through the Platform dashboard\n- right: Portability\n\
  \  text: Export your data in standard formats (CSV, JSON)\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your account and data\n- right: Opt-out of marketing\n  text: Opt out of marketing emails via unsubscribe link\n- right: Withdraw consent (GDPR)\n  text: Withdraw consent at any time\n- right: Object (GDPR)\n  text: Object to processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/comos-gateway-com/privacy/comos-gateway-com-privacy-policy.yml
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
summary_line: 28 quoted statements, read from comos-gateway-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Federation
- On-Premises
- Commerce
---
