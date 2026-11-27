---
api_specs:
- filename: datto-v2-account-api-openapi.yml
  format: yaml
  label: Datto /v2/account API
  slug: datto-v2-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-account-api-openapi.yml
- filename: datto-v2-activity-logs-api-openapi.yml
  format: yaml
  label: Datto /v2/activity-logs API
  slug: datto-v2-activity-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-activity-logs-api-openapi.yml
- filename: datto-v2-alert-api-openapi.yml
  format: yaml
  label: Datto /v2/alert API
  slug: datto-v2-alert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-alert-api-openapi.yml
- filename: datto-v2-audit-api-openapi.yml
  format: yaml
  label: Datto /v2/audit API
  slug: datto-v2-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-audit-api-openapi.yml
- filename: datto-v2-device-api-openapi.yml
  format: yaml
  label: Datto /v2/device API
  slug: datto-v2-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-device-api-openapi.yml
- filename: datto-v2-filter-api-openapi.yml
  format: yaml
  label: Datto /v2/filter API
  slug: datto-v2-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-filter-api-openapi.yml
- filename: datto-v2-job-api-openapi.yml
  format: yaml
  label: Datto /v2/job API
  slug: datto-v2-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-job-api-openapi.yml
- filename: datto-v2-site-api-openapi.yml
  format: yaml
  label: Datto /v2/site API
  slug: datto-v2-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-site-api-openapi.yml
- filename: datto-v2-system-api-openapi.yml
  format: yaml
  label: Datto /v2/system API
  slug: datto-v2-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-system-api-openapi.yml
- filename: datto-v2-user-api-openapi.yml
  format: yaml
  label: Datto /v2/user API
  slug: datto-v2-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datto/openapi/datto-v2-user-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as name, address, email address, phone number, device identifiers
  - category: financial
    text: This may include billing and other transaction information, credit card numbers, or other financial information
  - category: location
    text: real-time GPS location tracking and mapping, including analysis of location data and history
  - category: biometric
    text: Biometric information , such as facial images.
  - category: device
    text: 'Automatically-Collected Information: As is true of most websites and SaaS platforms, we gather certain information automatically and store it in log files.'
  - category: communication
    text: we may collect Personal Data, such as through digital text and audio information collected in email, chat, and video telephone and collaboration technologies
  - category: behavioral
    text: usage patterns, travel patterns, web site page views and traffic patterns
  deletion:
    route: Online portal request or contacting the customer for Backedup Content
    text: If your data is contained in Backedup Content and you no longer wish to have your data processed by Kaseya, please contact directly the customer (or client) that you interact with for removal of your information from Backedup Content.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and enhance products
    text: We generally use the information we collect to provide and enhance Kaseya Products and to operate our business.
  - purpose: Marketing
    text: We also use marketing data to send marketing material about our products and services.
  - purpose: Identity verification
    text: Identity verification. We use Stripe for identity document verification and fraud detection.
  - purpose: AI and automated processing
    text: Our processing of Personal Data for the purposes described in this Privacy Statement also includes the use of automated methods of processing, including sentiment analysis, machine learning, artificial intelligence, and generative intelligence capabilities
  retention:
  - period: null
    scope: Account information
    text: We will retain your information for as long as your account is active, as needed to provide you the Kaseya Product, and/or as provided by law.
  - period: null
    scope: Backedup Content
    text: We will retain Backedup Content for such periods as described in the applicable Kaseya Product Specifications.
  rights:
  - right: Access and correction
    text: you may have the right to access and correct such data, to object to the processing of data, and to request that any information we have about you be erased
  role:
    text: We are the controller of marketing data that we collect.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell our marketing data to third parties and we only share marketing data with third -party service providers that help us in our marketing efforts.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Kaseya Holdings Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework
  - mechanism: SCC
    text: Kaseya may also rely on approved Standard Contractual Clauses for cross-border data transfers from the EU, UK, or Switzerland.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Datto
provenance_date: '2026-11-09'
provider_name: Datto
provider_slug: datto
slug: datto-privacy-policy
source_date: '2026-11-09'
source_filename: datto-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.kaseya.com/legal/kaseya-privacy-statement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Datto\naid: datto\nurl: https://www.kaseya.com/legal/kaseya-privacy-statement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of marketing data that we collect.\ndata_categories:\n- category: identifying\n  text: such as name, address, email address, phone number, device identifiers\n- category: financial\n  text: This may include billing and other transaction information, credit card numbers, or other financial information\n- category: location\n  text: real-time GPS location tracking and mapping, including analysis of location data and history\n- category: biometric\n\
  \  text: Biometric information , such as facial images.\n- category: device\n  text: 'Automatically-Collected Information: As is true of most websites and SaaS platforms, we gather certain\n    information automatically and store it in log files.'\n- category: communication\n  text: we may collect Personal Data, such as through digital text and audio information collected in email, chat,\n    and video telephone and collaboration technologies\n- category: behavioral\n  text: usage patterns, travel patterns, web site page views and traffic patterns\npurposes:\n- purpose: Provide and enhance products\n  text: We generally use the information we collect to provide and enhance Kaseya Products and to operate our business.\n- purpose: Marketing\n  text: We also use marketing data to send marketing material about our products and services.\n- purpose: Identity verification\n  text: Identity verification. We use Stripe for identity document verification and fraud detection.\n- purpose: AI and\
  \ automated processing\n  text: Our processing of Personal Data for the purposes described in this Privacy Statement also includes the use\n    of automated methods of processing, including sentiment analysis, machine learning, artificial intelligence,\n    and generative intelligence capabilities\nretention:\n- scope: Account information\n  period: null\n  text: We will retain your information for as long as your account is active, as needed to provide you the Kaseya\n    Product, and/or as provided by law.\n- scope: Backedup Content\n  period: null\n  text: We will retain Backedup Content for such periods as described in the applicable Kaseya Product Specifications.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Kaseya Holdings Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension\n    to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework\n- mechanism: SCC\n  text: Kaseya may also rely on approved Standard Contractual Clauses for cross-border\
  \ data transfers from the EU,\n    UK, or Switzerland.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Online portal request or contacting the customer for Backedup Content\n  text: If your data is contained in Backedup Content and you no longer wish to have your data processed by Kaseya,\n    please contact directly the customer (or client) that you interact with for removal of your information from\n    Backedup Content.\nrights:\n- right: Access and correction\n  text: you may have the right to access and correct such data, to object to the processing of data, and to request\n    that any information we have about you be erased\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell our marketing data to third parties and we only share marketing data with third -party service\n    providers that help us in our marketing efforts.\n"
source_yaml_url: https://artifacts.apis.io/datto/privacy/datto-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Datto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Protection
- Backup
- Disaster Recovery
- Managed Service Providers
- RMM
- Endpoint Management
- Cybersecurity
- IT Operations
- SaaS Protection
---
