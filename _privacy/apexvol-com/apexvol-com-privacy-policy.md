---
api_specs:
- filename: apexvol-com-account-and-index-api-openapi.yml
  format: yaml
  label: ApexVol Account and index API
  slug: apexvol-com-account-and-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-account-and-index-api-openapi.yml
- filename: apexvol-com-earnings-and-expected-move-api-openapi.yml
  format: yaml
  label: ApexVol Earnings and expected move API
  slug: apexvol-com-earnings-and-expected-move-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-earnings-and-expected-move-api-openapi.yml
- filename: apexvol-com-events-and-calendars-api-openapi.yml
  format: yaml
  label: ApexVol Events and calendars API
  slug: apexvol-com-events-and-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-events-and-calendars-api-openapi.yml
- filename: apexvol-com-gamma-exposure-api-openapi.yml
  format: yaml
  label: ApexVol Gamma exposure API
  slug: apexvol-com-gamma-exposure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-gamma-exposure-api-openapi.yml
- filename: apexvol-com-implied-volatility-api-openapi.yml
  format: yaml
  label: ApexVol Implied volatility API
  slug: apexvol-com-implied-volatility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-implied-volatility-api-openapi.yml
- filename: apexvol-com-options-chain-api-openapi.yml
  format: yaml
  label: ApexVol Options chain API
  slug: apexvol-com-options-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-options-chain-api-openapi.yml
- filename: apexvol-com-options-flow-api-openapi.yml
  format: yaml
  label: ApexVol Options flow API
  slug: apexvol-com-options-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-options-flow-api-openapi.yml
- filename: apexvol-com-options-greeks-api-openapi.yml
  format: yaml
  label: ApexVol Options Greeks API
  slug: apexvol-com-options-greeks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-options-greeks-api-openapi.yml
- filename: apexvol-com-portfolio-risk-api-openapi.yml
  format: yaml
  label: ApexVol Portfolio risk API
  slug: apexvol-com-portfolio-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-portfolio-risk-api-openapi.yml
- filename: apexvol-com-screeners-api-openapi.yml
  format: yaml
  label: ApexVol Screeners API
  slug: apexvol-com-screeners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-screeners-api-openapi.yml
- filename: apexvol-com-stock-analytics-api-openapi.yml
  format: yaml
  label: ApexVol Stock analytics API
  slug: apexvol-com-stock-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-stock-analytics-api-openapi.yml
- filename: apexvol-com-strategies-api-openapi.yml
  format: yaml
  label: ApexVol Strategies API
  slug: apexvol-com-strategies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexvol-com/openapi/apexvol-com-strategies-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account Information Name, email address, password (encrypted), username
  - category: financial
    text: Billing Information Payment card details (processed by Stripe), billing address, transaction history
  - category: device
    text: Device Information IP address, browser type, operating system, device identifiers
  - category: behavioral
    text: Usage Data Pages visited, features used, timestamps, session duration
  - category: communication
    text: Communications Support requests, feedback, survey responses
  - category: location
    text: 'Geolocation Data: Approximate location based on IP address'
  deletion:
    route: Data Rights Portal, email, or Account Settings
    text: 'To exercise any of these rights, please: Visit our Data Rights Portal Email: [email protected] Use the data management options in your Account Settings'
  dpa:
    available: true
    text: All service providers are bound by Data Processing Agreements (DPAs) requiring them to protect your data and use it only for the specified purposes.
    url: null
  purposes:
  - purpose: Service delivery
    text: To provide, maintain, and improve our options analytics platform
  - purpose: Payment processing
    text: To process payments and prevent fraudulent transactions
  - purpose: Analytics
    text: To understand usage patterns and improve user experience
  - purpose: Security
    text: To detect, prevent, and address fraud, abuse, and security issues
  retention:
  - period: Duration of account + 2 years after deletion request
    scope: Account Data
    text: Duration of account + 2 years after deletion request
  - period: 7 years
    scope: Billing & Transaction Records
    text: 7 years (UK tax/accounting requirements)
  - period: Up to 90 days
    scope: Server Logs
    text: Up to 90 days (requests, errors and security events, for security & debugging purposes)
  - period: Up to 2 years
    scope: Usage Records
    text: Up to 2 years (pages viewed, features used, searches and Connector requests, for security, analytics and improving the Services)
  - period: 3 years after resolution
    scope: Support Communications
    text: Support Communications 3 years after resolution
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you
  - right: Erasure
    text: Request deletion of your data ("right to be forgotten")
  - right: Portability
    text: Receive your data in a structured, machine-readable format
  - right: Objection
    text: Object to processing based on legitimate interests or for marketing
  - right: Opt-out of sale/sharing
    text: Opt out of the sale or sharing of your personal information for cross-context behavioral advertising
  role:
    text: ApexVol Ltd. is the data controller responsible for your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: 'Adequacy Decisions: Transfers to countries deemed adequate by the UK Government'
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): UK-approved contractual protections with recipients'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ApexVol
provenance_date: '2026-11-09'
provider_name: ApexVol
provider_slug: apexvol-com
slug: apexvol-com-privacy-policy
source_date: '2026-11-09'
source_filename: apexvol-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apexvol.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ApexVol\naid: apexvol-com\nurl: https://apexvol.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ApexVol Ltd. is the data controller responsible for your personal data.\ndata_categories:\n- category: identifying\n  text: Account Information Name, email address, password (encrypted), username\n- category: financial\n  text: Billing Information Payment card details (processed by Stripe), billing address, transaction history\n- category: device\n  text: Device Information IP address, browser type, operating system, device identifiers\n- category: behavioral\n  text: Usage Data\
  \ Pages visited, features used, timestamps, session duration\n- category: communication\n  text: Communications Support requests, feedback, survey responses\n- category: location\n  text: 'Geolocation Data: Approximate location based on IP address'\npurposes:\n- purpose: Service delivery\n  text: To provide, maintain, and improve our options analytics platform\n- purpose: Payment processing\n  text: To process payments and prevent fraudulent transactions\n- purpose: Analytics\n  text: To understand usage patterns and improve user experience\n- purpose: Security\n  text: To detect, prevent, and address fraud, abuse, and security issues\nretention:\n- scope: Account Data\n  period: Duration of account + 2 years after deletion request\n  text: Duration of account + 2 years after deletion request\n- scope: Billing & Transaction Records\n  period: 7 years\n  text: 7 years (UK tax/accounting requirements)\n- scope: Server Logs\n  period: Up to 90 days\n  text: Up to 90 days (requests, errors\
  \ and security events, for security & debugging purposes)\n- scope: Usage Records\n  period: Up to 2 years\n  text: Up to 2 years (pages viewed, features used, searches and Connector requests, for security, analytics and\n    improving the Services)\n- scope: Support Communications\n  period: 3 years after resolution\n  text: Support Communications 3 years after resolution\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: 'Adequacy Decisions: Transfers to countries deemed adequate by the UK Government'\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): UK-approved contractual protections with recipients'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: All service providers are bound by Data Processing Agreements (DPAs) requiring them to protect your data\n    and use it only for the specified purposes.\ndeletion:\n  route: Data Rights Portal, email, or Account Settings\n  text: 'To exercise any of these rights, please: Visit\
  \ our Data Rights Portal Email: [email protected] Use the\n    data management options in your Account Settings'\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you\n- right: Erasure\n  text: Request deletion of your data (\"right to be forgotten\")\n- right: Portability\n  text: Receive your data in a structured, machine-readable format\n- right: Objection\n  text: Object to processing based on legitimate interests or for marketing\n- right: Opt-out of sale/sharing\n  text: Opt out of the sale or sharing of your personal information for cross-context behavioral advertising\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/apexvol-com/privacy/apexvol-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from ApexVol's own page on 2026-11-09.
synthetic: false
tags:
- Options
- Analytics
- Trading
- Finance
- Terminal
---
