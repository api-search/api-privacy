---
api_specs:
- filename: truebiz-async-web-presence-review-api-openapi.yml
  format: yaml
  label: TrueBiz Async Web Presence Review API
  slug: truebiz-async-web-presence-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-async-web-presence-review-api-openapi.yml
- filename: truebiz-fraud-searches-api-openapi.yml
  format: yaml
  label: TrueBiz Fraud Searches API
  slug: truebiz-fraud-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-fraud-searches-api-openapi.yml
- filename: truebiz-history-api-openapi.yml
  format: yaml
  label: TrueBiz History API
  slug: truebiz-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-history-api-openapi.yml
- filename: truebiz-industry-discovery-api-openapi.yml
  format: yaml
  label: TrueBiz Industry Discovery API
  slug: truebiz-industry-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-industry-discovery-api-openapi.yml
- filename: truebiz-industry-discovery-history-api-openapi.yml
  format: yaml
  label: TrueBiz Industry Discovery History API
  slug: truebiz-industry-discovery-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-industry-discovery-history-api-openapi.yml
- filename: truebiz-monitoring-alerts-api-openapi.yml
  format: yaml
  label: TrueBiz Monitoring Alerts API
  slug: truebiz-monitoring-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-monitoring-alerts-api-openapi.yml
- filename: truebiz-monitoring-domains-api-openapi.yml
  format: yaml
  label: TrueBiz Monitoring Domains API
  slug: truebiz-monitoring-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-monitoring-domains-api-openapi.yml
- filename: truebiz-web-presence-review-api-openapi.yml
  format: yaml
  label: TrueBiz Web Presence Review API
  slug: truebiz-web-presence-review-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-web-presence-review-api-openapi.yml
- filename: truebiz-web-presence-review-blocklist-api-openapi.yml
  format: yaml
  label: TrueBiz Web Presence Review Blocklist API
  slug: truebiz-web-presence-review-blocklist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-web-presence-review-blocklist-api-openapi.yml
- filename: truebiz-web-presence-review-history-api-openapi.yml
  format: yaml
  label: TrueBiz Web Presence Review History API
  slug: truebiz-web-presence-review-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-web-presence-review-history-api-openapi.yml
- filename: truebiz-website-status-api-openapi.yml
  format: yaml
  label: TrueBiz Website Status API
  slug: truebiz-website-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truebiz/openapi/truebiz-website-status-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, physical address, phone number, etc.
  - category: contact
    text: Name, email address, physical address, phone number, etc.
  - category: professional
    text: 'Merchant Information: Data related to the merchant websites you wish to validate, including company website URLs together with any feedback on the results we return.'
  - category: financial
    text: 'Payment Information: Details necessary to process payments, stored by our payment processor.'
  - category: device
    text: 'Technical Data: IP address, browser and device characteristics, operating system, language preferences, etc.'
  - category: behavioral
    text: 'Usage Information: Information about how you interact with our Services.'
  deletion:
    route: null
    text: we will either delete or deidentify the personal data or, if this is not possible (for example, because personal data has been stored in backup archives), then we will securely store the personal data and isolate it from further processing until deletion or deidentification is possible.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide requested services
    text: provide services and information that you request
  - purpose: prevent fraud
    text: prevent fraudulent use of our Site and Service
  - purpose: analytics and research
    text: conduct research and analytics to understand our customers
  - purpose: marketing
    text: market our Service
  - purpose: targeted advertising
    text: For advertising and marketing purposes (such as retargeting ads – see below for additional details)
  retention:
  - period: null
    scope: personal information
    text: We will usually store the personal information we collect about you for as long as necessary to fulfil the purposes for which it was collected
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
name: TrueBiz
provenance_date: '2026-11-10'
provider_name: TrueBiz
provider_slug: truebiz
slug: truebiz-privacy-policy
source_date: '2026-11-10'
source_filename: truebiz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://truebiz.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TrueBiz\naid: truebiz\nurl: https://truebiz.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, physical address, phone number, etc.\n- category: contact\n  text: Name, email address, physical address, phone number, etc.\n- category: professional\n  text: 'Merchant Information: Data related to the merchant websites you wish to validate, including company website\n    URLs together with any feedback on the results we return.'\n- category: financial\n  text: 'Payment Information: Details necessary to process payments,\
  \ stored by our payment processor.'\n- category: device\n  text: 'Technical Data: IP address, browser and device characteristics, operating system, language preferences,\n    etc.'\n- category: behavioral\n  text: 'Usage Information: Information about how you interact with our Services.'\npurposes:\n- purpose: provide requested services\n  text: provide services and information that you request\n- purpose: prevent fraud\n  text: prevent fraudulent use of our Site and Service\n- purpose: analytics and research\n  text: conduct research and analytics to understand our customers\n- purpose: marketing\n  text: market our Service\n- purpose: targeted advertising\n  text: For advertising and marketing purposes (such as retargeting ads – see below for additional details)\nretention:\n- scope: personal information\n  period: null\n  text: We will usually store the personal information we collect about you for as long as necessary to fulfil the\n    purposes for which it was collected\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: we will either delete or deidentify the personal data or, if this is not possible (for example, because\n    personal data has been stored in backup archives), then we will securely store the personal data and isolate\n    it from further processing until deletion or deidentification is possible.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truebiz/privacy/truebiz-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 13 quoted statements, read from TrueBiz's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Fraud Prevention
- Business Verification
- Merchant Risk
- KYB
- Underwriting
- Payments
- Monitoring
---
