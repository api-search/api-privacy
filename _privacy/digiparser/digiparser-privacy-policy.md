---
api_specs:
- filename: digiparser-document-processing-api-openapi.yml
  format: yaml
  label: DigiParser Document processing API
  slug: digiparser-document-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digiparser/openapi/digiparser-document-processing-api-openapi.yml
- filename: digiparser-mcp-api-openapi.yml
  format: yaml
  label: DigiParser MCP API
  slug: digiparser-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digiparser/openapi/digiparser-mcp-api-openapi.yml
- filename: digiparser-parsers-api-openapi.yml
  format: yaml
  label: DigiParser Parsers API
  slug: digiparser-parsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digiparser/openapi/digiparser-parsers-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: identifying
    text: First name and last name
  - category: professional
    text: Company information (if provided)
  - category: other
    text: Documents and files you upload for processing (invoices, receipts, forms, bank statements, etc.)
  - category: financial
    text: Billing information including payment details (processed securely by our payment provider, not stored by us)
  - category: device
    text: Your Device's Internet Protocol address (e.g. IP address), browser type, browser version, the pages of our Service that You visit, the time and date of Your visit, the time spent on those pages, unique device identifiers and other diagnostic data.
  - category: behavioral
    text: 'Analytics Cookies Type: Persistent Cookies Administered by: Third party (PostHog)'
  deletion:
    route: Delete account or contact us; account settings
    text: You may update, amend, or delete Your information at any time by signing in to Your Account, if you have one, and visiting the account settings section
  dpa:
    available: true
    text: For more information about our data processing practices, see our Data Processing Agreement and GDPR Compliance pages.
    url: null
  purposes:
  - purpose: provide and maintain the Service
    text: To provide and maintain our Service , including to monitor the usage of our Service.
  - purpose: manage user account
    text: 'To manage Your Account: to manage Your registration as a user of the Service.'
  - purpose: contact users
    text: 'To contact You: To contact You by email, telephone calls, SMS, or other equivalent forms of electronic communication'
  - purpose: analytics and improvement
    text: 'For other purposes : We may use Your information for other purposes, such as data analysis, identifying usage trends, determining the effectiveness of our promotional campaigns and to evaluate and improve our Service, products, services, marketing and your experience.'
  residency:
  - region: United States
    text: By default, your data is stored in secure cloud infrastructure located in the United States.
  - region: European Union
    text: Optional European Union (EU) data residency is available for enterprise customers upon request and must be agreed before the enterprise environment is provisioned.
  retention:
  - period: null
    scope: active accounts
    text: 'Active Accounts: We retain your data for as long as your account is active and you are using our services.'
  - period: 30-90 days
    scope: backup data
    text: Backups are retained for a limited period (typically 30-90 days) for disaster recovery purposes.
  rights:
  - right: Access
    text: 'Access : Request access to the personal data we hold about you'
  - right: Rectification
    text: 'Rectification : Correct inaccurate or incomplete data'
  - right: Erasure
    text: 'Erasure : Request deletion of your personal data'
  - right: Data Portability
    text: 'Data Portability : Export your data in a machine-readable format'
  - right: Object to Processing
    text: 'Object to Processing : Object to certain types of data processing'
  - right: Restrict Processing
    text: 'Restrict Processing : Request that we limit how we process your data'
  - right: Withdraw Consent
    text: 'Withdraw Consent : Withdraw consent where processing is based on consent'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: For a complete list of our service providers, see our Third Party Subprocessors page.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DigiParser
provenance_date: '2026-11-09'
provider_name: DigiParser
provider_slug: digiparser
slug: digiparser-privacy-policy
source_date: '2026-11-09'
source_filename: digiparser-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.digiparser.com/docs/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DigiParser\naid: digiparser\nurl: https://www.digiparser.com/docs/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address\n- category: identifying\n  text: First name and last name\n- category: professional\n  text: Company information (if provided)\n- category: other\n  text: Documents and files you upload for processing (invoices, receipts, forms, bank statements, etc.)\n- category: financial\n  text: Billing information including payment details (processed securely by our payment provider, not stored by\n    us)\n\
  - category: device\n  text: Your Device's Internet Protocol address (e.g. IP address), browser type, browser version, the pages of our\n    Service that You visit, the time and date of Your visit, the time spent on those pages, unique device identifiers\n    and other diagnostic data.\n- category: behavioral\n  text: 'Analytics Cookies Type: Persistent Cookies Administered by: Third party (PostHog)'\npurposes:\n- purpose: provide and maintain the Service\n  text: To provide and maintain our Service , including to monitor the usage of our Service.\n- purpose: manage user account\n  text: 'To manage Your Account: to manage Your registration as a user of the Service.'\n- purpose: contact users\n  text: 'To contact You: To contact You by email, telephone calls, SMS, or other equivalent forms of electronic\n    communication'\n- purpose: analytics and improvement\n  text: 'For other purposes : We may use Your information for other purposes, such as data analysis, identifying\n    usage trends,\
  \ determining the effectiveness of our promotional campaigns and to evaluate and improve our Service,\n    products, services, marketing and your experience.'\nretention:\n- scope: active accounts\n  period: null\n  text: 'Active Accounts: We retain your data for as long as your account is active and you are using our services.'\n- scope: backup data\n  period: 30-90 days\n  text: Backups are retained for a limited period (typically 30-90 days) for disaster recovery purposes.\nresidency:\n- region: United States\n  text: By default, your data is stored in secure cloud infrastructure located in the United States.\n- region: European Union\n  text: Optional European Union (EU) data residency is available for enterprise customers upon request and must\n    be agreed before the enterprise environment is provisioned.\ntransfers: []\nsubprocessors:\n  url: null\n  text: For a complete list of our service providers, see our Third Party Subprocessors page.\ndpa:\n  available: true\n  url: null\n\
  \  text: For more information about our data processing practices, see our Data Processing Agreement and GDPR Compliance\n    pages.\ndeletion:\n  route: Delete account or contact us; account settings\n  text: You may update, amend, or delete Your information at any time by signing in to Your Account, if you have\n    one, and visiting the account settings section\nrights:\n- right: Access\n  text: 'Access : Request access to the personal data we hold about you'\n- right: Rectification\n  text: 'Rectification : Correct inaccurate or incomplete data'\n- right: Erasure\n  text: 'Erasure : Request deletion of your personal data'\n- right: Data Portability\n  text: 'Data Portability : Export your data in a machine-readable format'\n- right: Object to Processing\n  text: 'Object to Processing : Object to certain types of data processing'\n- right: Restrict Processing\n  text: 'Restrict Processing : Request that we limit how we process your data'\n- right: Withdraw Consent\n  text: 'Withdraw\
  \ Consent : Withdraw consent where processing is based on consent'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/digiparser/privacy/digiparser-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from DigiParser's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Document Processing
- Automation
- Data Extraction
- Artificial Intelligence
---
