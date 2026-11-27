---
api_specs:
- filename: openserp-docs-api-openapi.yml
  format: yaml
  label: OpenSERP Docs API
  slug: openserp-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-docs-api-openapi.yml
- filename: openserp-health-api-openapi.yml
  format: yaml
  label: OpenSERP Health API
  slug: openserp-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-health-api-openapi.yml
- filename: openserp-mega-api-openapi.yml
  format: yaml
  label: OpenSERP Mega API
  slug: openserp-mega-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-mega-api-openapi.yml
- filename: openserp-search-api-openapi.yml
  format: yaml
  label: OpenSERP Search API
  slug: openserp-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-search-api-openapi.yml
- filename: openserp-stats-api-openapi.yml
  format: yaml
  label: OpenSERP Stats API
  slug: openserp-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openserp/openapi/openserp-stats-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (provided at registration)
  - category: contact
    text: Email address (provided at registration)
  - category: financial
    text: Transaction records (amounts, dates, payment references)
  - category: behavioral
    text: 'API request records: timestamp, endpoint, account or API key identifiers, response status, credits used, and limited request parameters such as query text or an extraction URL'
  - category: device
    text: IP address (used for rate limiting, security, and network logs)
  - category: device
    text: Browser user agent (when accessing the website)
  - category: communication
    text: Email address and optional use case description (if you signed up for early access)
  deletion:
    route: Contact us to exercise rights, including erasure
    text: To exercise any of these rights, contact us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: To provide and maintain the Service
  - purpose: Process payments and maintain account balance
    text: To process payments and maintain your account balance
  - purpose: Enforce rate limits and prevent abuse
    text: To enforce rate limits and prevent abuse
  - purpose: Communicate service updates
    text: To communicate service updates and important notices
  - purpose: Comply with legal obligations
    text: To comply with legal obligations
  retention:
  - period: null
    scope: Account data
    text: 'Account data: retained while your account is active, then deleted or anonymized unless a longer period is needed for legal claims, security, or compliance'
  - period: up to 12 months
    scope: API usage records
    text: 'API usage records, including limited request parameters: retained for up to 12 months for billing accuracy, support, security, and dispute resolution'
  - period: up to 6 years
    scope: Billing and transaction records
    text: 'Billing and transaction records: retained for up to 6 years, or longer where tax, accounting, fraud prevention, or legal-claim requirements apply'
  - period: null
    scope: Waitlist data
    text: 'Waitlist data: retained until the waitlist program ends, unless you request deletion earlier'
  rights:
  - right: Access
    text: Access your personal data
  - right: Rectify
    text: Rectify inaccurate data
  - right: Erase
    text: Erase your data ("right to be forgotten")
  - right: Port
    text: Port your data to another service
  - right: Restrict or object
    text: Restrict or object to certain processing
  - right: Withdraw consent
    text: Withdraw consent at any time
  role:
    text: TATLAB LTD is the data controller for personal data processed through the Service.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell, rent, or trade your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where applicable, we rely on UK adequacy regulations or approved contractual safeguards and supplementary measures.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OpenSERP
provenance_date: '2026-11-10'
provider_name: OpenSERP
provider_slug: openserp
slug: openserp-privacy-policy
source_date: '2026-11-10'
source_filename: openserp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openserp.org/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OpenSERP\naid: openserp\nurl: https://openserp.org/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: TATLAB LTD is the data controller for personal data processed through the Service.\ndata_categories:\n- category: identifying\n  text: Email address (provided at registration)\n- category: contact\n  text: Email address (provided at registration)\n- category: financial\n  text: Transaction records (amounts, dates, payment references)\n- category: behavioral\n  text: 'API request records: timestamp, endpoint, account or API key identifiers, response status, credits used,\n    and limited\
  \ request parameters such as query text or an extraction URL'\n- category: device\n  text: IP address (used for rate limiting, security, and network logs)\n- category: device\n  text: Browser user agent (when accessing the website)\n- category: communication\n  text: Email address and optional use case description (if you signed up for early access)\npurposes:\n- purpose: Provide and maintain the Service\n  text: To provide and maintain the Service\n- purpose: Process payments and maintain account balance\n  text: To process payments and maintain your account balance\n- purpose: Enforce rate limits and prevent abuse\n  text: To enforce rate limits and prevent abuse\n- purpose: Communicate service updates\n  text: To communicate service updates and important notices\n- purpose: Comply with legal obligations\n  text: To comply with legal obligations\nretention:\n- scope: Account data\n  period: null\n  text: 'Account data: retained while your account is active, then deleted or anonymized\
  \ unless a longer period\n    is needed for legal claims, security, or compliance'\n- scope: API usage records\n  period: up to 12 months\n  text: 'API usage records, including limited request parameters: retained for up to 12 months for billing accuracy,\n    support, security, and dispute resolution'\n- scope: Billing and transaction records\n  period: up to 6 years\n  text: 'Billing and transaction records: retained for up to 6 years, or longer where tax, accounting, fraud prevention,\n    or legal-claim requirements apply'\n- scope: Waitlist data\n  period: null\n  text: 'Waitlist data: retained until the waitlist program ends, unless you request deletion earlier'\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where applicable, we rely on UK adequacy regulations or approved contractual safeguards and supplementary\n    measures.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us to exercise rights,\
  \ including erasure\n  text: To exercise any of these rights, contact us at [email protected] .\nrights:\n- right: Access\n  text: Access your personal data\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Erase\n  text: Erase your data (\"right to be forgotten\")\n- right: Port\n  text: Port your data to another service\n- right: Restrict or object\n  text: Restrict or object to certain processing\n- right: Withdraw consent\n  text: Withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell, rent, or trade your personal data.\n"
source_yaml_url: https://artifacts.apis.io/openserp/privacy/openserp-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from OpenSERP's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Search
- SERP
- Web Scraping
- Content Extraction
- AI Grounding
- Rank Tracking
- Open Source
- Developer Tools
---
