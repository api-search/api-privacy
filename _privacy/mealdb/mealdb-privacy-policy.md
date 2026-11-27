---
api_specs:
- filename: mealdb-categories-php-api-openapi.yml
  format: yaml
  label: TheMealDB Categories.php API
  slug: mealdb-categories-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-categories-php-api-openapi.yml
- filename: mealdb-filter-php-api-openapi.yml
  format: yaml
  label: TheMealDB Filter.php API
  slug: mealdb-filter-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-filter-php-api-openapi.yml
- filename: mealdb-list-php-api-openapi.yml
  format: yaml
  label: TheMealDB List.php API
  slug: mealdb-list-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-list-php-api-openapi.yml
- filename: mealdb-lookup-php-api-openapi.yml
  format: yaml
  label: TheMealDB Lookup.php API
  slug: mealdb-lookup-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-lookup-php-api-openapi.yml
- filename: mealdb-premium-api-openapi.yml
  format: yaml
  label: TheMealDB Premium API
  slug: mealdb-premium-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-premium-api-openapi.yml
- filename: mealdb-random-php-api-openapi.yml
  format: yaml
  label: TheMealDB Random.php API
  slug: mealdb-random-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-random-php-api-openapi.yml
- filename: mealdb-search-php-api-openapi.yml
  format: yaml
  label: TheMealDB Search.php API
  slug: mealdb-search-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-search-php-api-openapi.yml
- filename: mealdb-discovery-api-openapi.yml
  format: yaml
  label: TheMealDB Discovery API
  slug: mealdb-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-discovery-api-openapi.yml
- filename: mealdb-filter-api-openapi.yml
  format: yaml
  label: TheMealDB Filter API
  slug: mealdb-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-filter-api-openapi.yml
- filename: mealdb-lists-api-openapi.yml
  format: yaml
  label: TheMealDB Lists API
  slug: mealdb-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-lists-api-openapi.yml
- filename: mealdb-lookup-api-openapi.yml
  format: yaml
  label: TheMealDB Lookup API
  slug: mealdb-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-lookup-api-openapi.yml
- filename: mealdb-search-api-openapi.yml
  format: yaml
  label: TheMealDB Search API
  slug: mealdb-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-search-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Email Address: For account creation, authentication, and communication.'
  - category: behavioral
    text: 'Usage Information: Collected through cloudflare for analytics, feature adoption tracking, user journey analysis, error tracking, and session replays.'
  - category: financial
    text: 'Payment Information: Processed by Paddle to handle orders and payments.'
  deletion:
    route: Delete your account
    text: Once you delete your account, all associated personal data is permanently removed from our systems, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: 'Email Address: For account creation, authentication, and communication.'
  - purpose: Payment processing
    text: 'Payment Information: Processed by Paddle to handle orders and payments.'
  - purpose: Technical monitoring and bug fixing
    text: 'Legitimate Interest: For technical functionality monitoring including app monitoring, error tracking, analytics, and session replays via cloudflare.'
  retention:
  - period: null
    scope: Account-related data
    text: Account-related data, such as your email address and authentication details, is retained for the duration of your account’s existence.
  - period: six to ten years
    scope: Payment-related data
    text: This includes data related to invoices and transaction records, which are typically retained for six to ten years, depending on the applicable laws.
  rights:
  - right: Access
    text: 'Right to Access: Request copies of your data.'
  - right: Rectification
    text: 'Right to Rectification: Correct inaccurate or incomplete data.'
  - right: Erasure
    text: 'Right to Erasure: Delete your account and associated data.'
  - right: Restrict processing
    text: 'Right to Restrict Processing: Limit how your data is used.'
  - right: Object
    text: 'Right to Object: Object to data processing under specific circumstances.'
  - right: Data portability
    text: 'Right to Data Portability: Request your data in a portable format.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers comply with GDPR standards through the use of Standard Contractual Clauses (SCCs) and other safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TheMealDB
provenance_date: '2026-11-10'
provider_name: TheMealDB
provider_slug: mealdb
slug: mealdb-privacy-policy
source_date: '2026-11-10'
source_filename: mealdb-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.themealdb.com/privacy_policy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TheMealDB\naid: mealdb\nurl: https://www.themealdb.com/privacy_policy.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Email Address: For account creation, authentication, and communication.'\n- category: behavioral\n  text: 'Usage Information: Collected through cloudflare for analytics, feature adoption tracking, user journey\n    analysis, error tracking, and session replays.'\n- category: financial\n  text: 'Payment Information: Processed by Paddle to handle orders and payments.'\npurposes:\n- purpose: Account creation and authentication\n\
  \  text: 'Email Address: For account creation, authentication, and communication.'\n- purpose: Payment processing\n  text: 'Payment Information: Processed by Paddle to handle orders and payments.'\n- purpose: Technical monitoring and bug fixing\n  text: 'Legitimate Interest: For technical functionality monitoring including app monitoring, error tracking, analytics,\n    and session replays via cloudflare.'\nretention:\n- scope: Account-related data\n  period: null\n  text: Account-related data, such as your email address and authentication details, is retained for the duration\n    of your account’s existence.\n- scope: Payment-related data\n  period: six to ten years\n  text: This includes data related to invoices and transaction records, which are typically retained for six to\n    ten years, depending on the applicable laws.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: These transfers comply with GDPR standards through the use of Standard Contractual Clauses (SCCs) and other\n\
  \    safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account\n  text: Once you delete your account, all associated personal data is permanently removed from our systems, except\n    where retention is required by law.\nrights:\n- right: Access\n  text: 'Right to Access: Request copies of your data.'\n- right: Rectification\n  text: 'Right to Rectification: Correct inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Right to Erasure: Delete your account and associated data.'\n- right: Restrict processing\n  text: 'Right to Restrict Processing: Limit how your data is used.'\n- right: Object\n  text: 'Right to Object: Object to data processing under specific circumstances.'\n- right: Data portability\n  text: 'Right to Data Portability: Request your data in a portable format.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mealdb/privacy/mealdb-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from TheMealDB's own page on 2026-11-10.
synthetic: false
tags:
- Food
- Recipes
- Meals
- Cooking
- Ingredients
- Cuisine
- Open Data
---
