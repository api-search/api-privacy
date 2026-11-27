---
api_specs:
- filename: uchecker-default-api-openapi.yml
  format: yaml
  label: uChecker Аутентификация API
  slug: uchecker-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uchecker/openapi/uchecker-default-api-openapi.yml
- filename: uchecker-email-api-openapi.yml
  format: yaml
  label: uChecker Валидация Email API
  slug: uchecker-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uchecker/openapi/uchecker-email-api-openapi.yml
- filename: uchecker-esp-api-openapi.yml
  format: yaml
  label: uChecker ESP Провайдеры API
  slug: uchecker-esp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uchecker/openapi/uchecker-esp-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Telegram ID and username
  - category: contact
    text: Email address and password when registering via the web interface
  - category: behavioral
    text: Email lists uploaded by the user for validation
  - category: financial
    text: Payment history and credit balance
  - category: device
    text: 'Technical data: IP address, User-Agent, Google Tag Manager events'
  deletion:
    route: Request via support team on Telegram
    text: Requests may be submitted to the support team via Telegram @goodsam911 .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Email validation services
    text: providing email validation services
  - purpose: Credit allocation
    text: allocating credits after payment
  - purpose: Technical support
    text: providing technical support to users
  - purpose: Service improvement
    text: improving the quality of the Service
  retention:
  - period: 30 days
    scope: Uploaded email lists and validation results
    text: Uploaded email lists and validation results are retained for 30 days after the completion of a task, after which they are automatically deleted.
  - period: null
    scope: Account data
    text: Account data (Telegram ID, credit balance, payment history) is retained until the account is deleted at the user's request.
  rights:
  - right: Access information
    text: Obtain information about the processing of their personal data
  - right: Rectification, restriction, deletion
    text: Request rectification, restriction, or deletion of data
  - right: Withdraw consent
    text: Withdraw consent to the processing of personal data
  - right: Delete account
    text: Delete their account and associated data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: uChecker
provenance_date: '2026-11-10'
provider_name: uChecker
provider_slug: uchecker
slug: uchecker-privacy-policy
source_date: '2026-11-10'
source_filename: uchecker-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://uchecker.net/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: uChecker\naid: uchecker\nurl: https://uchecker.net/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Telegram ID and username\n- category: contact\n  text: Email address and password when registering via the web interface\n- category: behavioral\n  text: Email lists uploaded by the user for validation\n- category: financial\n  text: Payment history and credit balance\n- category: device\n  text: 'Technical data: IP address, User-Agent, Google Tag Manager events'\npurposes:\n- purpose: Email validation services\n  text: providing\
  \ email validation services\n- purpose: Credit allocation\n  text: allocating credits after payment\n- purpose: Technical support\n  text: providing technical support to users\n- purpose: Service improvement\n  text: improving the quality of the Service\nretention:\n- scope: Uploaded email lists and validation results\n  period: 30 days\n  text: Uploaded email lists and validation results are retained for 30 days after the completion of a task, after\n    which they are automatically deleted.\n- scope: Account data\n  period: null\n  text: Account data (Telegram ID, credit balance, payment history) is retained until the account is deleted at\n    the user's request.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via support team on Telegram\n  text: Requests may be submitted to the support team via Telegram @goodsam911 .\nrights:\n- right: Access information\n  text: Obtain information\
  \ about the processing of their personal data\n- right: Rectification, restriction, deletion\n  text: Request rectification, restriction, or deletion of data\n- right: Withdraw consent\n  text: Withdraw consent to the processing of personal data\n- right: Delete account\n  text: Delete their account and associated data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uchecker/privacy/uchecker-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from uChecker's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- Email
- SMTP
- DNS
- Deliverability
- MX
- SPF
- DKIM
- DMARC
- MCP
- Agent-Native
- Data Quality
---
