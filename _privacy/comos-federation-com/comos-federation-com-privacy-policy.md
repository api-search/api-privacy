---
api_specs:
- filename: comos-federation-com-openapi.yml
  format: yaml
  label: ComOS Federation Gateway
  slug: comos-federation-gateway
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comos-federation-com/openapi/comos-federation-com-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone number
  - category: financial
    text: Billing information and payment details
  - category: location
    text: IP address and approximate location
  - category: device
    text: Browser type and version
  - category: behavioral
    text: Pages visited and features used
  - category: communication
    text: Support requests and correspondence
  deletion:
    route: Email support@comos-federation.com or account deletion request
    text: Request deletion of your account and data
  dpa:
    available: true
    text: Our [Data Processing Agreement](https://comos-federation.com/dpa) ("DPA") is **incorporated by reference into the [Terms of Service](https://comos-federation.com/terms) and applies automatically**
    url: https://comos-federation.com/dpa
  purposes:
  - purpose: Provide the service
    text: Create and manage your account
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud and abuse
  - purpose: Power in-Platform AI features
    text: Power in-Platform AI features (search, recommendations, automation, brand voice, policy enforcement)
  - purpose: Marketing communications
    text: Marketing communications (with consent)
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
    text: Request a copy of personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your account and data
  - right: Portability
    text: Export your data in standard formats (CSV, JSON)
  - right: Know (California)
    text: Request the categories and specific pieces of personal information collected
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Withdraw consent
    text: Withdraw consent at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
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
name: ComOS
provenance_date: '2026-11-09'
provider_name: ComOS
provider_slug: comos-federation-com
slug: comos-federation-com-privacy-policy
source_date: '2026-11-09'
source_filename: comos-federation-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://comos-federation.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ComOS\naid: comos-federation-com\nurl: https://comos-federation.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, phone number\n- category: financial\n  text: Billing information and payment details\n- category: location\n  text: IP address and approximate location\n- category: device\n  text: Browser type and version\n- category: behavioral\n  text: Pages visited and features used\n- category: communication\n  text: Support requests and correspondence\npurposes:\n- purpose: Provide the service\n  text: Create\
  \ and manage your account\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud and abuse\n- purpose: Power in-Platform AI features\n  text: Power in-Platform AI features (search, recommendations, automation, brand voice, policy enforcement)\n- purpose: Marketing communications\n  text: Marketing communications (with consent)\nretention:\n- scope: MCP audit logs\n  period: 90 days\n  text: MCP audit logs are retained for **90 days**, then automatically deleted by a database time-to-live (TTL)\n    policy.\n- scope: After account termination - export\n  period: 30 days\n  text: '**30 days**: Data available for export'\n- scope: After account termination - production deletion\n  period: 90 days\n  text: '**90 days**: Data deleted from production systems'\n- scope: After account termination - backups\n  period: 1 year\n  text: '**1 year**: Data purged from backups'\nresidency:\n- region: United States\n  text: Tenant data is stored in Google Cloud and MongoDB Atlas in the\
  \ United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses approved by the European Commission to protect EEA/UK/Swiss personal\n    data.\nsubprocessors:\n  url: https://comos-federation.com/dpa\n  text: This is the complete list of ComOS sub-processors, and it is identical to Appendix A of the [Data Processing\n    Agreement](https://comos-federation.com/dpa), which also gives each one's location.\ndpa:\n  available: true\n  url: https://comos-federation.com/dpa\n  text: Our [Data Processing Agreement](https://comos-federation.com/dpa) (\"DPA\") is **incorporated by reference\n    into the [Terms of Service](https://comos-federation.com/terms) and applies automatically**\ndeletion:\n  route: Email support@comos-federation.com or account deletion request\n  text: Request deletion of your account and data\nrights:\n- right: Access\n  text: Request a copy of personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate\
  \ data\n- right: Deletion\n  text: Request deletion of your account and data\n- right: Portability\n  text: Export your data in standard formats (CSV, JSON)\n- right: Know (California)\n  text: Request the categories and specific pieces of personal information collected\n- right: Object\n  text: Object to processing based on legitimate interests\n- right: Withdraw consent\n  text: Withdraw consent at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/comos-federation-com/privacy/comos-federation-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 26 quoted statements, read from ComOS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- AI Agents
- MCP
- Federation
- Payments
- Self-Hosted
- Operating System
---
