---
api_specs:
- filename: sovrn-account-api-openapi.yml
  format: yaml
  label: Sovrn Account API
  slug: sovrn-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-account-api-openapi.yml
- filename: sovrn-ai-orchestration-api-openapi.yml
  format: yaml
  label: Sovrn Ai Orchestration API
  slug: sovrn-ai-orchestration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-ai-orchestration-api-openapi.yml
- filename: sovrn-bid-api-openapi.yml
  format: yaml
  label: Sovrn Bid API
  slug: sovrn-bid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-bid-api-openapi.yml
- filename: sovrn-link-api-openapi.yml
  format: yaml
  label: Sovrn Link API
  slug: sovrn-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-link-api-openapi.yml
- filename: sovrn-merchant-group-summaries-api-openapi.yml
  format: yaml
  label: Sovrn Merchant Group Summaries API
  slug: sovrn-merchant-group-summaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-merchant-group-summaries-api-openapi.yml
- filename: sovrn-product-coupons-api-openapi.yml
  format: yaml
  label: Sovrn Product Coupons API
  slug: sovrn-product-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-product-coupons-api-openapi.yml
- filename: sovrn-reporting-api-openapi.yml
  format: yaml
  label: Sovrn Reporting API
  slug: sovrn-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-reporting-api-openapi.yml
- filename: sovrn-reports-api-openapi.yml
  format: yaml
  label: Sovrn Reports API
  slug: sovrn-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-reports-api-openapi.yml
- filename: sovrn-sites-api-openapi.yml
  format: yaml
  label: Sovrn Sites API
  slug: sovrn-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sovrn/openapi/sovrn-sites-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Cookie ID A unique, random identifier stored in your browser.
  - category: identifying
    text: Hashed Email A non-readable, consistent hash of an email address.
  - category: device
    text: Device Information Browser type/version, OS, device type, ad-blocker usage, etc.
  - category: behavioral
    text: Metrics on page views, time spent, scroll depth, and interactions.
  - category: contact
    text: Account-related details (e.g., upon registration to use Sovrn Services) such as name, email, company info, payment details, and website URLs
  - category: communication
    text: Voice Recordings Recorded virtual meetings or telephone conversations that assist with note taking and internal training purposes.
  deletion:
    route: Privacy Center or email privacy@sovrn[.]com
    text: 'Access, delete, or correct: Submit requests via the Privacy Center , email privacy@sovrn[.]com (include “CCPA Consumer Request” in the subject line), or call +1 (888) 280-8085.'
  dpa:
    available: true
    text: Data Processing Addendum (Sovrn as Data Importer)
    url: null
  purposes:
  - purpose: Interest-based advertising
    text: Deliver interest-based (targeted) advertising on Publisher sites.
  - purpose: Internal business operations
    text: Audit ad impressions, detect fraud, and ensure compliance with industry standards.
  - purpose: Analytics
    text: Work with analytics providers (e.g., Google Analytics) to study Site and Service usage.
  - purpose: Commercial data products
    text: Create audience segments based on browsing interests and behaviors (we do not use personally identifiable information for this).
  retention:
  - period: null
    scope: Personal information generally
    text: We keep your personal information only for as long as necessary to fulfill the purposes for which it was collected or for as long as necessary to provide services as described in Section 3.
  rights:
  - right: Access
    text: 'Access : Request confirmation of whether we process your personal data and obtain a copy, along with details about the processing.'
  - right: Erasure
    text: 'Erasure (“right to be forgotten”): Request deletion of your personal data in certain situations'
  - right: Objection
    text: 'Objection : Object to processing based on legitimate interests or direct marketing (including profiling for advertising).'
  - right: Opt-out of sale/sharing
    text: 'Right to Opt-Out of Sale/Sharing : Stop the sale or sharing of your personal information for cross-context behavioral advertising.'
  role:
    text: In most cases involving Reader data from Publisher sites, Sovrn acts as a processor, while Publishers act as controllers.
    value: both
  sale_or_sharing:
    stance: conditional
    text: Certain sharing of device identifiers qualifies as a “sale” or “sharing” under CCPA/CPRA. See Section 13.2 for your opt-out rights.
  subprocessors:
    text: See full list at sovrn.com/legal/subprocessors
    url: sovrn.com/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: We use appropriate safeguards, such as Standard Contractual Clauses (SCCs) or other approved mechanisms, to ensure an adequate level of protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sovrn
provenance_date: '2026-11-10'
provider_name: Sovrn
provider_slug: sovrn
slug: sovrn-privacy-policy
source_date: '2026-11-10'
source_filename: sovrn-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sovrn.com/privacy-policy/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sovrn\naid: sovrn\nurl: https://www.sovrn.com/privacy-policy/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In most cases involving Reader data from Publisher sites, Sovrn acts as a processor, while Publishers act\n    as controllers.\ndata_categories:\n- category: identifying\n  text: Cookie ID A unique, random identifier stored in your browser.\n- category: identifying\n  text: Hashed Email A non-readable, consistent hash of an email address.\n- category: device\n  text: Device Information Browser type/version, OS, device type, ad-blocker usage, etc.\n- category: behavioral\n \
  \ text: Metrics on page views, time spent, scroll depth, and interactions.\n- category: contact\n  text: Account-related details (e.g., upon registration to use Sovrn Services) such as name, email, company info,\n    payment details, and website URLs\n- category: communication\n  text: Voice Recordings Recorded virtual meetings or telephone conversations that assist with note taking and internal\n    training purposes.\npurposes:\n- purpose: Interest-based advertising\n  text: Deliver interest-based (targeted) advertising on Publisher sites.\n- purpose: Internal business operations\n  text: Audit ad impressions, detect fraud, and ensure compliance with industry standards.\n- purpose: Analytics\n  text: Work with analytics providers (e.g., Google Analytics) to study Site and Service usage.\n- purpose: Commercial data products\n  text: Create audience segments based on browsing interests and behaviors (we do not use personally identifiable\n    information for this).\nretention:\n- scope:\
  \ Personal information generally\n  period: null\n  text: We keep your personal information only for as long as necessary to fulfill the purposes for which it was\n    collected or for as long as necessary to provide services as described in Section 3.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: We use appropriate safeguards, such as Standard Contractual Clauses (SCCs) or other approved mechanisms,\n    to ensure an adequate level of protection.\nsubprocessors:\n  url: sovrn.com/legal/subprocessors\n  text: See full list at sovrn.com/legal/subprocessors\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum (Sovrn as Data Importer)\ndeletion:\n  route: Privacy Center or email privacy@sovrn[.]com\n  text: 'Access, delete, or correct: Submit requests via the Privacy Center , email privacy@sovrn[.]com (include\n    “CCPA Consumer Request” in the subject line), or call +1 (888) 280-8085.'\nrights:\n- right: Access\n  text: 'Access : Request confirmation of whether\
  \ we process your personal data and obtain a copy, along with details\n    about the processing.'\n- right: Erasure\n  text: 'Erasure (“right to be forgotten”): Request deletion of your personal data in certain situations'\n- right: Objection\n  text: 'Objection : Object to processing based on legitimate interests or direct marketing (including profiling\n    for advertising).'\n- right: Opt-out of sale/sharing\n  text: 'Right to Opt-Out of Sale/Sharing : Stop the sale or sharing of your personal information for cross-context\n    behavioral advertising.'\nsale_or_sharing:\n  stance: conditional\n  text: Certain sharing of device identifiers qualifies as a “sale” or “sharing” under CCPA/CPRA. See Section 13.2\n    for your opt-out rights.\n"
source_yaml_url: https://artifacts.apis.io/sovrn/privacy/sovrn-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Sovrn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AdTech
- Advertising
- Monetization
- Affiliate Marketing
- Programmatic
- Publishers
- Commerce
- Data
- Reporting
- Product Data
- Agent-Native
---
