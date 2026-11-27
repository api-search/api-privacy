---
api_specs:
- filename: fundz-acquisitions-api-openapi.yml
  format: yaml
  label: Fundz Acquisitions API
  slug: fundz-acquisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-acquisitions-api-openapi.yml
- filename: fundz-agreements-api-openapi.yml
  format: yaml
  label: Fundz Agreements API
  slug: fundz-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-agreements-api-openapi.yml
- filename: fundz-crowdfundings-api-openapi.yml
  format: yaml
  label: Fundz Crowdfundings API
  slug: fundz-crowdfundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-crowdfundings-api-openapi.yml
- filename: fundz-executives-api-openapi.yml
  format: yaml
  label: Fundz Executives API
  slug: fundz-executives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-executives-api-openapi.yml
- filename: fundz-fundings-api-openapi.yml
  format: yaml
  label: Fundz Fundings API
  slug: fundz-fundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-fundings-api-openapi.yml
- filename: fundz-products-api-openapi.yml
  format: yaml
  label: Fundz Products API
  slug: fundz-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-products-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may collect your name, email address, company name, billing information, login credentials, phone number, and IP address.
  - category: device
    text: device information such as browser type and operating system.
  - category: behavioral
    text: information about your preferences, activity data within the application, cookies and analytics data
  - category: financial
    text: Your credit card information is transmitted directly to Braintree using SSL encryption and is never stored on Fundz servers.
  deletion:
    route: contact support@fundz.net or john@fundz.net for API records
    text: To ask what we hold for your key, to have per-call records deleted before the 400 days elapse, or to have a key revoked, contact john@fundz.net .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve service
    text: We use your information to provide and improve the Fundz service, process payments, analyze usage patterns, and maintain the security and integrity of our platform.
  - purpose: metering and billing (API)
    text: 'We use these records for two purposes and no others: metering and billing'
  - purpose: abuse prevention (API)
    text: abuse prevention and service reliability , meaning rate limits, allowance enforcement, and investigating a key that is degrading the service for other customers.
  residency:
  - region: United States
    text: Fundz is operated in the United States.
  retention:
  - period: 400 days
    scope: API per-call records
    text: Per-call records are deleted automatically after 400 days, a full annual billing cycle plus a period for billing disputes.
  - period: one hour
    scope: API rate-limiting counters
    text: Rate-limiting counters are deleted after one hour.
  - period: null
    scope: API monthly billing totals
    text: We keep the monthly billing totals where required for accounting purposes.
  rights:
  - right: access
    text: You have the right to access, correct, delete, and port your personal data.
  - right: correction
    text: You have the right to access, correct, delete, and port your personal data.
  - right: deletion
    text: You have the right to access, correct, delete, and port your personal data.
  - right: portability
    text: You have the right to access, correct, delete, and port your personal data.
  - right: opt out of certain processing
    text: You may also opt out of certain data processing activities.
  role:
    text: This Privacy Policy explains how Fundz, LLC collects, uses, and shares information when you access and use our website or the Fundz software application.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Fundz does not sell, rent, or trade your personal information to third parties for their marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use Standard Contractual Clauses and other appropriate safeguards to ensure an adequate level of data protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fundz
provenance_date: '2026-11-09'
provider_name: Fundz
provider_slug: fundz
slug: fundz-privacy-policy
source_date: '2026-11-09'
source_filename: fundz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fundz.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fundz\naid: fundz\nurl: https://www.fundz.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy explains how Fundz, LLC collects, uses, and shares information when you access and use\n    our website or the Fundz software application.\ndata_categories:\n- category: identifying\n  text: we may collect your name, email address, company name, billing information, login credentials, phone number,\n    and IP address.\n- category: device\n  text: device information such as browser type and operating system.\n- category: behavioral\n  text: information about your preferences,\
  \ activity data within the application, cookies and analytics data\n- category: financial\n  text: Your credit card information is transmitted directly to Braintree using SSL encryption and is never stored\n    on Fundz servers.\npurposes:\n- purpose: provide and improve service\n  text: We use your information to provide and improve the Fundz service, process payments, analyze usage patterns,\n    and maintain the security and integrity of our platform.\n- purpose: metering and billing (API)\n  text: 'We use these records for two purposes and no others: metering and billing'\n- purpose: abuse prevention (API)\n  text: abuse prevention and service reliability , meaning rate limits, allowance enforcement, and investigating\n    a key that is degrading the service for other customers.\nretention:\n- scope: API per-call records\n  period: 400 days\n  text: Per-call records are deleted automatically after 400 days, a full annual billing cycle plus a period for\n    billing disputes.\n- scope:\
  \ API rate-limiting counters\n  period: one hour\n  text: Rate-limiting counters are deleted after one hour.\n- scope: API monthly billing totals\n  period: null\n  text: We keep the monthly billing totals where required for accounting purposes.\nresidency:\n- region: United States\n  text: Fundz is operated in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we use Standard Contractual Clauses and other appropriate safeguards to ensure an adequate\n    level of data protection.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support@fundz.net or john@fundz.net for API records\n  text: To ask what we hold for your key, to have per-call records deleted before the 400 days elapse, or to have\n    a key revoked, contact john@fundz.net .\nrights:\n- right: access\n  text: You have the right to access, correct, delete, and port your personal data.\n- right: correction\n  text: You have the right\
  \ to access, correct, delete, and port your personal data.\n- right: deletion\n  text: You have the right to access, correct, delete, and port your personal data.\n- right: portability\n  text: You have the right to access, correct, delete, and port your personal data.\n- right: opt out of certain processing\n  text: You may also opt out of certain data processing activities.\nsale_or_sharing:\n  stance: prohibited\n  text: Fundz does not sell, rent, or trade your personal information to third parties for their marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/fundz/privacy/fundz-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Fundz's own page on 2026-11-09.
synthetic: false
tags:
- Business Intelligence
- Funding
- Private Markets
- Mergers and Acquisitions
- SEC Filings
- Signals
- Sales Intelligence
- MCP
- Agents
---
