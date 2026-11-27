---
api_specs:
- filename: monid-api-keys-api-openapi.yml
  format: yaml
  label: Monid API Keys API
  slug: monid-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-api-keys-api-openapi.yml
- filename: monid-auth-api-openapi.yml
  format: yaml
  label: Monid Auth API
  slug: monid-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-auth-api-openapi.yml
- filename: monid-controls-api-openapi.yml
  format: yaml
  label: Monid Controls API
  slug: monid-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-controls-api-openapi.yml
- filename: monid-discover-api-openapi.yml
  format: yaml
  label: Monid Discover API
  slug: monid-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-discover-api-openapi.yml
- filename: monid-endpoints-api-openapi.yml
  format: yaml
  label: Monid Endpoints API
  slug: monid-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-endpoints-api-openapi.yml
- filename: monid-inspect-api-openapi.yml
  format: yaml
  label: Monid Inspect API
  slug: monid-inspect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-inspect-api-openapi.yml
- filename: monid-public-registry-api-openapi.yml
  format: yaml
  label: Monid Public Registry API
  slug: monid-public-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-public-registry-api-openapi.yml
- filename: monid-resources-api-openapi.yml
  format: yaml
  label: Monid Resources API
  slug: monid-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-resources-api-openapi.yml
- filename: monid-runs-api-openapi.yml
  format: yaml
  label: Monid Runs API
  slug: monid-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-runs-api-openapi.yml
- filename: monid-wallet-api-openapi.yml
  format: yaml
  label: Monid Wallet API
  slug: monid-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-wallet-api-openapi.yml
- filename: monid-identities-api-openapi.yml
  format: yaml
  label: Monid Identities API
  slug: monid-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monid/openapi/monid-identities-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: names phone numbers email addresses usernames billing addresses debit/credit card numbers
  - category: device
    text: We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about your activity in the Services (such as the date/time stamps associated with your usage, pages and files viewed, searches, and other actions you take such as which features you use)
  deletion:
    route: Account settings, contacting us, or data subject access request
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: We may disclose your personal information with our service providers pursuant to a written contract between us and each service provider.
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: Fraud and security protection
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  - purpose: Identify usage trends
    text: To identify usage trends.
  - purpose: Marketing effectiveness
    text: To determine the effectiveness of our marketing and promotional campaigns.
  retention:
  - period: As long as the user has an account with us
    scope: Category A and B personal information
    text: Category A - As long as the user has an account with us Category B - As long as the user has an account with us
  - period: null
    scope: General personal information
    text: When we have no ongoing legitimate business need to process your personal information, we will either delete or anonymize such information
  rights:
  - right: Access and copy
    text: (i) to request access and obtain a copy of your personal information
  - right: Rectification or erasure
    text: (ii) to request rectification or erasure;
  - right: Restriction of processing
    text: (iii) to restrict the processing of your personal information;
  - right: Data portability
    text: (iv) if applicable, to data portability;
  - right: Object to processing
    text: In certain circumstances, you may also have the right to object to the processing of your personal information.
  - right: Withdraw consent
    text: you have the right to withdraw your consent at any time.
  - right: Opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not disclosed, sold, or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Monid
provenance_date: '2026-11-10'
provider_name: Monid
provider_slug: monid
slug: monid-privacy-policy
source_date: '2026-11-10'
source_filename: monid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://monid.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Monid\naid: monid\nurl: https://monid.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: names phone numbers email addresses usernames billing addresses debit/credit card numbers\n- category: device\n  text: We collect device data such as information about your computer, phone, tablet, or other device you use to\n    access the Services.\n- category: location\n  text: We collect location data such as information about your device's location,\
  \ which can be either precise or\n    imprecise.\n- category: behavioral\n  text: information about your activity in the Services (such as the date/time stamps associated with your usage,\n    pages and files viewed, searches, and other actions you take such as which features you use)\npurposes:\n- purpose: Account creation and authentication\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: Fraud and security protection\n  text: To protect our Services. We may process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\n- purpose: Identify usage trends\n  text: To identify usage trends.\n- purpose: Marketing effectiveness\n  text: To determine the effectiveness of our marketing and promotional campaigns.\nretention:\n- scope: Category A and B personal information\n  period: As long as the user has an account with us\n  text: Category A - As long as the user\
  \ has an account with us Category B - As long as the user has an account\n    with us\n- scope: General personal information\n  period: null\n  text: When we have no ongoing legitimate business need to process your personal information, we will either delete\n    or anonymize such information\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: We may disclose your personal information with our service providers pursuant to a written contract between\n    us and each service provider.\ndeletion:\n  route: Account settings, contacting us, or data subject access request\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: Access and copy\n  text: (i) to request access and obtain a copy of your personal information\n- right: Rectification or erasure\n  text: (ii) to request rectification or erasure;\n- right: Restriction\
  \ of processing\n  text: (iii) to restrict the processing of your personal information;\n- right: Data portability\n  text: (iv) if applicable, to data portability;\n- right: Object to processing\n  text: In certain circumstances, you may also have the right to object to the processing of your personal information.\n- right: Withdraw consent\n  text: you have the right to withdraw your consent at any time.\n- right: Opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: unstated\n  text: We have not disclosed, sold, or shared any personal information to third parties for a business or commercial\n    purpose in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/monid/privacy/monid-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
summary_line: 20 quoted statements, read from Monid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agents
- MCP
- Tools
- Data
- API Marketplace
---
