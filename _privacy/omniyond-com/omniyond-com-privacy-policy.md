---
api_specs:
- filename: omniyond-com-mcp-api-openapi.yml
  format: yaml
  label: omniyond-com MCP API
  slug: omniyond-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniyond-com/openapi/omniyond-com-mcp-api-openapi.yml
- filename: omniyond-com-scheduler-api-openapi.yml
  format: yaml
  label: omniyond-com Scheduler API
  slug: omniyond-com-scheduler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniyond-com/openapi/omniyond-com-scheduler-api-openapi.yml
- filename: omniyond-com-utility-api-openapi.yml
  format: yaml
  label: omniyond-com Utility API
  slug: omniyond-com-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/omniyond-com/openapi/omniyond-com-utility-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address - Used for account authentication and communication
  - category: identifying
    text: Name - Used for personalization and identification
  - category: contact
    text: Email address - Used for account authentication and communication
  - category: financial
    text: Credit grant records - Amount and date of purchased credits
  - category: financial
    text: Wallet address - For crypto payments, the payer address that settled the transaction on-chain
  - category: device
    text: Device information - Browser type, operating system, IP address
  - category: behavioral
    text: Usage data - Features accessed, pages viewed, time spent
  - category: other
    text: Scheduled jobs - The URLs, methods, headers, payloads, and schedules you configure
  - category: other
    text: Run results - Responses retrieved by your scheduled jobs and stored for you to fetch
  deletion:
    route: Email support@omniyond.com to request account deletion
    text: You can request account deletion at any time by emailing support@omniyond.com .
  dpa:
    available: null
    text: Data processing agreements with third-party providers
    url: null
  purposes:
  - purpose: Service delivery
    text: Service delivery - To provide and maintain the Omniyond platform
  - purpose: Service functionality
    text: Service functionality - To schedule, execute, and deliver the HTTP requests you configure
  - purpose: Account management
    text: Account management - To manage your account, credits, and billing
  - purpose: Communication
    text: Communication - To send service updates, security alerts, and support responses
  - purpose: Improvement
    text: Improvement - To analyze usage patterns and improve our service
  - purpose: Legal compliance
    text: Legal compliance - To comply with legal obligations and enforce our Terms of Service
  residency:
  - region: European Union and other regions
    text: Your data is stored on Cloudflare's infrastructure, which may include servers located in the European Union and other regions.
  retention:
  - period: until account deletion is requested
    scope: Account data
    text: Account data - Retained until account deletion is requested
  - period: until you cancel or delete them, or request account deletion
    scope: Scheduled jobs and run results
    text: Scheduled jobs and run results - Retained until you cancel or delete them, or request account deletion
  - period: 7 years
    scope: Payment records
    text: Payment records - Retained for 7 years to comply with tax and accounting regulations
  - period: up to 30 days
    scope: Backup data
    text: Backup data - May be retained for up to 30 days in secure backups
  rights:
  - right: Access
    text: Right to access - Request a copy of your personal data
  - right: Rectification
    text: Right to rectification - Correct inaccurate or incomplete data
  - right: Erasure
    text: Right to erasure - Request deletion of your personal data (see Account Deletion below)
  - right: Restriction
    text: Right to restriction - Request limitation of data processing
  - right: Portability
    text: Right to data portability - Receive your data in a machine-readable format
  - right: Object
    text: Right to object - Object to certain types of data processing
  - right: Withdraw consent
    text: Right to withdraw consent - Withdraw consent for data processing at any time
  role:
    text: CraftCodely SRL ("we," "us," or "our") operates Omniyond
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: Cloudflare - Hosting provider for infrastructure, databases (D1), and file storage (R2)
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: omniyond-com
provenance_date: '2026-11-10'
provider_name: omniyond-com
provider_slug: omniyond-com
slug: omniyond-com-privacy-policy
source_date: '2026-11-10'
source_filename: omniyond-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://omniyond.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: omniyond-com\naid: omniyond-com\nurl: https://omniyond.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CraftCodely SRL (\"we,\" \"us,\" or \"our\") operates Omniyond\ndata_categories:\n- category: identifying\n  text: Email address - Used for account authentication and communication\n- category: identifying\n  text: Name - Used for personalization and identification\n- category: contact\n  text: Email address - Used for account authentication and communication\n- category: financial\n  text: Credit grant records - Amount and date of purchased credits\n- category: financial\n\
  \  text: Wallet address - For crypto payments, the payer address that settled the transaction on-chain\n- category: device\n  text: Device information - Browser type, operating system, IP address\n- category: behavioral\n  text: Usage data - Features accessed, pages viewed, time spent\n- category: other\n  text: Scheduled jobs - The URLs, methods, headers, payloads, and schedules you configure\n- category: other\n  text: Run results - Responses retrieved by your scheduled jobs and stored for you to fetch\npurposes:\n- purpose: Service delivery\n  text: Service delivery - To provide and maintain the Omniyond platform\n- purpose: Service functionality\n  text: Service functionality - To schedule, execute, and deliver the HTTP requests you configure\n- purpose: Account management\n  text: Account management - To manage your account, credits, and billing\n- purpose: Communication\n  text: Communication - To send service updates, security alerts, and support responses\n- purpose: Improvement\n\
  \  text: Improvement - To analyze usage patterns and improve our service\n- purpose: Legal compliance\n  text: Legal compliance - To comply with legal obligations and enforce our Terms of Service\nretention:\n- scope: Account data\n  period: until account deletion is requested\n  text: Account data - Retained until account deletion is requested\n- scope: Scheduled jobs and run results\n  period: until you cancel or delete them, or request account deletion\n  text: Scheduled jobs and run results - Retained until you cancel or delete them, or request account deletion\n- scope: Payment records\n  period: 7 years\n  text: Payment records - Retained for 7 years to comply with tax and accounting regulations\n- scope: Backup data\n  period: up to 30 days\n  text: Backup data - May be retained for up to 30 days in secure backups\nresidency:\n- region: European Union and other regions\n  text: Your data is stored on Cloudflare's infrastructure, which may include servers located in the European\
  \ Union\n    and other regions.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\nsubprocessors:\n  url: null\n  text: Cloudflare - Hosting provider for infrastructure, databases (D1), and file storage (R2)\ndpa:\n  available: null\n  url: null\n  text: Data processing agreements with third-party providers\ndeletion:\n  route: Email support@omniyond.com to request account deletion\n  text: You can request account deletion at any time by emailing support@omniyond.com .\nrights:\n- right: Access\n  text: Right to access - Request a copy of your personal data\n- right: Rectification\n  text: Right to rectification - Correct inaccurate or incomplete data\n- right: Erasure\n  text: Right to erasure - Request deletion of your personal data (see Account Deletion below)\n- right: Restriction\n  text: Right to restriction - Request limitation of data processing\n- right: Portability\n  text: Right to data portability - Receive your data in\
  \ a machine-readable format\n- right: Object\n  text: Right to object - Object to certain types of data processing\n- right: Withdraw consent\n  text: Right to withdraw consent - Withdraw consent for data processing at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/omniyond-com/privacy/omniyond-com-privacy-policy.yml
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
summary_line: 33 quoted statements, read from omniyond-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Pay-per-use
- Scheduling
- Automation
---
