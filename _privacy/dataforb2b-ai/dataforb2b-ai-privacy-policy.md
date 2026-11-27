---
api_specs:
- filename: dataforb2b-ai-dataforb2b-api-api-openapi.yml
  format: yaml
  label: dataforb2b-ai DataForB2B API
  slug: dataforb2b-ai-dataforb2b-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-dataforb2b-api-api-openapi.yml
- filename: dataforb2b-ai-health-api-openapi.yml
  format: yaml
  label: dataforb2b-ai Health API
  slug: dataforb2b-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-health-api-openapi.yml
- filename: dataforb2b-ai-search-api-openapi.yml
  format: yaml
  label: dataforb2b-ai Search API
  slug: dataforb2b-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-search-api-openapi.yml
- filename: dataforb2b-ai-stats-api-openapi.yml
  format: yaml
  label: dataforb2b-ai Stats API
  slug: dataforb2b-ai-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dataforb2b-ai/openapi/dataforb2b-ai-stats-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, company name, job title, phone number, billing information'
  - category: professional
    text: professional information (job title, employer, work history, education, skills)
  - category: behavioral
    text: 'Usage Data: API calls, features used, pages viewed, time spent, and interaction patterns'
  - category: device
    text: 'Device Information: IP address, browser type, operating system, device identifiers'
  - category: location
    text: Geolocation data (approximate location based on IP)
  - category: communication
    text: 'Communications: Information you provide when you contact our support team or participate in surveys'
  deletion:
    route: Privacy Rights Center, Remove My Data / Do Not Sell page, or email
    text: You may request deletion of your personal information, subject to certain exceptions for legal compliance, fraud prevention, and legitimate business purposes.
  dpa:
    available: true
    text: For more information, please see our Data Processing Agreement .
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Deliver API responses and data enrichment services
  - purpose: Sales prospecting, recruiting and investment research
    text: to give our business customers data for sales prospecting, recruiting and investment research
  - purpose: AI and machine learning
    text: 'We use AI and machine learning technologies to enhance our Services, including: Data enrichment and validation'
  - purpose: Marketing
    text: Send you service updates, newsletters, and promotional materials (with consent)
  residency:
  - region: European Union
    text: Our Services are hosted and operated in the European Union.
  retention:
  - period: null
    scope: Personal information
    text: 'We retain personal information for as long as necessary to: Provide our Services and fulfill our contractual obligations'
  rights:
  - right: Access
    text: 'Right of Access: Request a copy of your personal data'
  - right: Correction
    text: 'Right to Rectification: Correct inaccurate personal data'
  - right: Erasure
    text: 'Right to Erasure: Request deletion of your personal data'
  - right: Portability
    text: 'Right to Data Portability: Receive your data in a portable format'
  - right: Object
    text: 'Right to Object: Object to processing based on legitimate interests'
  - right: Opt-out of sale or sharing
    text: You have the right to opt out of the sale or sharing of your personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: This may be a "sale" under the CCPA, which you can opt out of.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission
  - mechanism: adequacy
    text: Adequacy decisions by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: dataforb2b-ai
provenance_date: '2026-11-09'
provider_name: dataforb2b-ai
provider_slug: dataforb2b-ai
slug: dataforb2b-ai-privacy-policy
source_date: '2026-11-09'
source_filename: dataforb2b-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dataforb2b.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: dataforb2b-ai\naid: dataforb2b-ai\nurl: https://dataforb2b.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, company name, job title, phone number, billing information'\n- category: professional\n  text: professional information (job title, employer, work history, education, skills)\n- category: behavioral\n  text: 'Usage Data: API calls, features used, pages viewed, time spent, and interaction patterns'\n- category: device\n  text: 'Device Information: IP address, browser type, operating\
  \ system, device identifiers'\n- category: location\n  text: Geolocation data (approximate location based on IP)\n- category: communication\n  text: 'Communications: Information you provide when you contact our support team or participate in surveys'\npurposes:\n- purpose: Provide and improve services\n  text: Deliver API responses and data enrichment services\n- purpose: Sales prospecting, recruiting and investment research\n  text: to give our business customers data for sales prospecting, recruiting and investment research\n- purpose: AI and machine learning\n  text: 'We use AI and machine learning technologies to enhance our Services, including: Data enrichment and validation'\n- purpose: Marketing\n  text: Send you service updates, newsletters, and promotional materials (with consent)\nretention:\n- scope: Personal information\n  period: null\n  text: 'We retain personal information for as long as necessary to: Provide our Services and fulfill our contractual\n    obligations'\nresidency:\n\
  - region: European Union\n  text: Our Services are hosted and operated in the European Union.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission\n- mechanism: adequacy\n  text: Adequacy decisions by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: For more information, please see our Data Processing Agreement .\ndeletion:\n  route: Privacy Rights Center, Remove My Data / Do Not Sell page, or email\n  text: You may request deletion of your personal information, subject to certain exceptions for legal compliance,\n    fraud prevention, and legitimate business purposes.\nrights:\n- right: Access\n  text: 'Right of Access: Request a copy of your personal data'\n- right: Correction\n  text: 'Right to Rectification: Correct inaccurate personal data'\n- right: Erasure\n  text: 'Right to Erasure: Request deletion of your personal data'\n- right: Portability\n  text: 'Right to Data\
  \ Portability: Receive your data in a portable format'\n- right: Object\n  text: 'Right to Object: Object to processing based on legitimate interests'\n- right: Opt-out of sale or sharing\n  text: You have the right to opt out of the sale or sharing of your personal information.\nsale_or_sharing:\n  stance: conditional\n  text: This may be a \"sale\" under the CCPA, which you can opt out of.\n"
source_yaml_url: https://artifacts.apis.io/dataforb2b-ai/privacy/dataforb2b-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from dataforb2b-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- B2B
- Artificial Intelligence
- Analytics
---
