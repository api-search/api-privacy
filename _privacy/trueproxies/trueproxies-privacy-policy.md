---
api_specs:
- filename: trueproxies-analytics-api-openapi.yml
  format: yaml
  label: TrueProxies Analytics API
  slug: trueproxies-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-analytics-api-openapi.yml
- filename: trueproxies-catalog-api-openapi.yml
  format: yaml
  label: TrueProxies Catalog API
  slug: trueproxies-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-catalog-api-openapi.yml
- filename: trueproxies-invoices-api-openapi.yml
  format: yaml
  label: TrueProxies Invoices API
  slug: trueproxies-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-invoices-api-openapi.yml
- filename: trueproxies-me-api-openapi.yml
  format: yaml
  label: TrueProxies Me API
  slug: trueproxies-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-me-api-openapi.yml
- filename: trueproxies-services-api-openapi.yml
  format: yaml
  label: TrueProxies Services API
  slug: trueproxies-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trueproxies/openapi/trueproxies-services-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address (required for registration)
  - category: identifying
    text: Name or company name (if provided)
  - category: financial
    text: Payment information (processed by third-party payment providers — we do not store full card details)
  - category: behavioral
    text: Pages visited, referral source, browser type, device type
  - category: location
    text: your approximate city and country, derived from your IP address
  - category: communication
    text: the messages and files you send
  - category: device
    text: Dashboard login activity (timestamps, IP addresses)
  deletion:
    route: Account deletion
    text: When your account is deleted, we also delete your Support chat contact and conversations in Intercom.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Services
    text: Provide and maintain the Services (account management, billing, support)
  - purpose: Fraud prevention and payments
    text: Process payments and prevent fraud
  - purpose: Improve the Services
    text: Improve the Services based on aggregated, anonymized usage patterns
  - purpose: Campaign measurement
    text: Measure campaign visits, account creation, and confirmed payments using browser analytics and server-side events
  residency:
  - region: United States
    text: Intercom stores Support chat data in the United States.
  retention:
  - period: 12 months after deletion
    scope: Account data
    text: Account data is retained for the duration of your account plus 12 months after deletion
  - period: 24 months
    scope: Support communication
    text: Support communication is retained for 24 months after the last interaction
  - period: 365 days
    scope: Reseller application answers
    text: Reseller program application answers are redacted 365 days after the application is declined, withdrawn or revoked
  - period: up to 30 days
    scope: Browser referral data
    text: browser referral data for up to 30 days
  - period: 15 minutes
    scope: Rate-limit windows and in-memory proxy lines
    text: A finished, failed, or cancelled job is scheduled to expire from the isolated checker's process memory after 15 minutes
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correct
    text: Correct inaccurate or incomplete information
  - right: Delete
    text: Delete your personal information (subject to legal retention requirements)
  - right: Export
    text: Export your data in a portable format
  - right: Withdraw consent
    text: Withdraw consent for optional data processing
  - right: Object or restrict
    text: You also have the right to object to or request restriction of certain processing
  role:
    text: The data controller for personal information processed under this policy is TrueProxies, LLC, a Delaware limited liability company
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information for money. Advertising measurement tags on our website send information about your visit to our advertising partners
  subprocessors:
    text: Intercom uses its own sub-processors, including the AI model providers named in section 1
    url: null
  transfers:
  - mechanism: DPF
    text: Intercom relies on its certification under the EU-US Data Privacy Framework, the UK Extension to it and the Swiss-US Data Privacy Framework
  - mechanism: SCC
    text: with standard contractual clauses as the fallback
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TrueProxies
provenance_date: '2026-11-10'
provider_name: TrueProxies
provider_slug: trueproxies
slug: trueproxies-privacy-policy
source_date: '2026-11-10'
source_filename: trueproxies-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://trueproxies.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TrueProxies\naid: trueproxies\nurl: https://trueproxies.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for personal information processed under this policy is TrueProxies, LLC, a Delaware\n    limited liability company\ndata_categories:\n- category: contact\n  text: Email address (required for registration)\n- category: identifying\n  text: Name or company name (if provided)\n- category: financial\n  text: Payment information (processed by third-party payment providers — we do not store full card details)\n- category: behavioral\n  text: Pages visited, referral\
  \ source, browser type, device type\n- category: location\n  text: your approximate city and country, derived from your IP address\n- category: communication\n  text: the messages and files you send\n- category: device\n  text: Dashboard login activity (timestamps, IP addresses)\npurposes:\n- purpose: Provide and maintain the Services\n  text: Provide and maintain the Services (account management, billing, support)\n- purpose: Fraud prevention and payments\n  text: Process payments and prevent fraud\n- purpose: Improve the Services\n  text: Improve the Services based on aggregated, anonymized usage patterns\n- purpose: Campaign measurement\n  text: Measure campaign visits, account creation, and confirmed payments using browser analytics and server-side\n    events\nretention:\n- scope: Account data\n  period: 12 months after deletion\n  text: Account data is retained for the duration of your account plus 12 months after deletion\n- scope: Support communication\n  period: 24 months\n  text:\
  \ Support communication is retained for 24 months after the last interaction\n- scope: Reseller application answers\n  period: 365 days\n  text: Reseller program application answers are redacted 365 days after the application is declined, withdrawn\n    or revoked\n- scope: Browser referral data\n  period: up to 30 days\n  text: browser referral data for up to 30 days\n- scope: Rate-limit windows and in-memory proxy lines\n  period: 15 minutes\n  text: A finished, failed, or cancelled job is scheduled to expire from the isolated checker's process memory after\n    15 minutes\nresidency:\n- region: United States\n  text: Intercom stores Support chat data in the United States.\ntransfers:\n- mechanism: DPF\n  text: Intercom relies on its certification under the EU-US Data Privacy Framework, the UK Extension to it and\n    the Swiss-US Data Privacy Framework\n- mechanism: SCC\n  text: with standard contractual clauses as the fallback\nsubprocessors:\n  url: null\n  text: Intercom uses its\
  \ own sub-processors, including the AI model providers named in section 1\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion\n  text: When your account is deleted, we also delete your Support chat contact and conversations in Intercom.\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correct\n  text: Correct inaccurate or incomplete information\n- right: Delete\n  text: Delete your personal information (subject to legal retention requirements)\n- right: Export\n  text: Export your data in a portable format\n- right: Withdraw consent\n  text: Withdraw consent for optional data processing\n- right: Object or restrict\n  text: You also have the right to object to or request restriction of certain processing\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information for money. Advertising measurement tags on our website send information\n    about your visit to our advertising\
  \ partners\n"
source_yaml_url: https://artifacts.apis.io/trueproxies/privacy/trueproxies-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from TrueProxies's own page on 2026-11-10.
synthetic: false
tags:
- Proxies
- Residential Proxies
- Datacenter Proxies
- Web Scraping
- Networking
- IPv6
- SOCKS5
- Data Collection
---
