---
api_specs:
- filename: viewmax-studio-account-api-openapi.yml
  format: yaml
  label: ViewMax Studio Account API
  slug: viewmax-studio-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewmax-studio/openapi/viewmax-studio-account-api-openapi.yml
- filename: viewmax-studio-advanced-api-openapi.yml
  format: yaml
  label: ViewMax Studio Advanced API
  slug: viewmax-studio-advanced-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewmax-studio/openapi/viewmax-studio-advanced-api-openapi.yml
- filename: viewmax-studio-catalog-api-openapi.yml
  format: yaml
  label: ViewMax Studio Catalog API
  slug: viewmax-studio-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewmax-studio/openapi/viewmax-studio-catalog-api-openapi.yml
- filename: viewmax-studio-generation-api-openapi.yml
  format: yaml
  label: ViewMax Studio Generation API
  slug: viewmax-studio-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewmax-studio/openapi/viewmax-studio-generation-api-openapi.yml
- filename: viewmax-studio-tasks-api-openapi.yml
  format: yaml
  label: ViewMax Studio Tasks API
  slug: viewmax-studio-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewmax-studio/openapi/viewmax-studio-tasks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: This includes your name, email address, and any other information you provide when creating an account.
  - category: behavioral
    text: Information about how you use Viewmax Studio, including your interactions, features accessed, videos generated, and usage frequency.
  - category: device
    text: Data regarding the devices you use to access Viewmax Studio, such as device type, operating system, and browser type.
  - category: financial
    text: Information regarding your payment methods, such as credit card number, billing address, and any details required for transaction processing.
  - category: other
    text: Images and prompts you upload or input for video generation.
  deletion:
    route: Account controls or support request
    text: Task records are retained as part of your account history until deleted through available account controls or a support request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Manage account and customer support
    text: To manage your account and provide customer support.
  - purpose: Analyze engagement and improve services
    text: To analyze user engagement and improve our services.
  - purpose: Generate videos
    text: To generate videos based on your requests.
  - purpose: Billing and payment processing
    text: To facilitate billing and payment processing for our services.
  - purpose: Advertising measurement and audiences
    text: We may share limited account information (such as your email address) with these platforms to show you relevant ads, measure conversions, and build advertising audiences
  retention:
  - period: null
    scope: Task records
    text: Task records are retained as part of your account history until deleted through available account controls or a support request, subject to backups and records retained for security, billing and legal obligations.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your data
  - right: Export
    text: Export your data
  - right: Opt out of marketing communications
    text: Opt out of marketing communications
  - right: Opt out of sharing with advertising partners
    text: Opt out of the sharing of your information with advertising partners
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 'We do not sell, trade, or otherwise transfer your personal information to outside parties, except in the following circumstances:'
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ViewMax Studio
provenance_date: '2026-11-10'
provider_name: ViewMax Studio
provider_slug: viewmax-studio
slug: viewmax-studio-privacy-policy
source_date: '2026-11-10'
source_filename: viewmax-studio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://viewmax.studio/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ViewMax Studio\naid: viewmax-studio\nurl: https://viewmax.studio/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: This includes your name, email address, and any other information you provide when creating an account.\n- category: behavioral\n  text: Information about how you use Viewmax Studio, including your interactions, features accessed, videos generated,\n    and usage frequency.\n- category: device\n  text: Data regarding the devices you use to access Viewmax Studio, such as device type, operating system, and\n    browser\
  \ type.\n- category: financial\n  text: Information regarding your payment methods, such as credit card number, billing address, and any details\n    required for transaction processing.\n- category: other\n  text: Images and prompts you upload or input for video generation.\npurposes:\n- purpose: Manage account and customer support\n  text: To manage your account and provide customer support.\n- purpose: Analyze engagement and improve services\n  text: To analyze user engagement and improve our services.\n- purpose: Generate videos\n  text: To generate videos based on your requests.\n- purpose: Billing and payment processing\n  text: To facilitate billing and payment processing for our services.\n- purpose: Advertising measurement and audiences\n  text: We may share limited account information (such as your email address) with these platforms to show you relevant\n    ads, measure conversions, and build advertising audiences\nretention:\n- scope: Task records\n  period: null\n  text:\
  \ Task records are retained as part of your account history until deleted through available account controls\n    or a support request, subject to backups and records retained for security, billing and legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account controls or support request\n  text: Task records are retained as part of your account history until deleted through available account controls\n    or a support request\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your data\n- right: Export\n  text: Export your data\n- right: Opt out of marketing communications\n  text: Opt out of marketing communications\n- right: Opt out of sharing with advertising partners\n  text: Opt out of the sharing of your information with advertising partners\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: 'We do not sell, trade, or otherwise transfer your personal information to outside parties, except in the\n    following circumstances:'\n"
source_yaml_url: https://artifacts.apis.io/viewmax-studio/privacy/viewmax-studio-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from ViewMax Studio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Generation
- Marketing
---
