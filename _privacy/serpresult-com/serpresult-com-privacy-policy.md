---
api_specs:
- filename: serpresult-com-account-api-openapi.yml
  format: yaml
  label: SerpResult Account API
  slug: serpresult-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-account-api-openapi.yml
- filename: serpresult-com-api-keys-api-openapi.yml
  format: yaml
  label: SerpResult API keys API
  slug: serpresult-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-api-keys-api-openapi.yml
- filename: serpresult-com-billing-api-openapi.yml
  format: yaml
  label: SerpResult Billing API
  slug: serpresult-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-billing-api-openapi.yml
- filename: serpresult-com-meta-api-openapi.yml
  format: yaml
  label: SerpResult Meta API
  slug: serpresult-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-meta-api-openapi.yml
- filename: serpresult-com-search-api-openapi.yml
  format: yaml
  label: SerpResult Search API
  slug: serpresult-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-search-api-openapi.yml
- filename: serpresult-com-usage-api-openapi.yml
  format: yaml
  label: SerpResult Usage API
  slug: serpresult-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serpresult-com/openapi/serpresult-com-usage-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, your name if you give one, and the profile details your identity provider returns when you sign in with Google.
  - category: financial
    text: the billing address and tax id you enter at checkout
  - category: device
    text: Your theme preference is stored in your own browser and is never sent to us.
  deletion:
    route: Deleting the account
    text: Deleting your account removes the account row and the keys and logs that hang off it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Answer API calls and show them in the dashboard
    text: To answer your API calls and show them back to you in the dashboard.
  - purpose: Metering and rate limits
    text: To meter credits and enforce rate limits.
  - purpose: Debugging failures
    text: To debug failures, which is why each response carries a request id.
  - purpose: Service email
    text: To send service email you cannot opt out of, such as email verification.
  retention:
  - period: null
    scope: Account data
    text: Account data is kept while the account exists.
  - period: null
    scope: Query logs
    text: Query logs are kept for a bounded retention window and then deleted by a scheduled job.
  - period: null
    scope: Stored results
    text: Stored results expire on their own freshness window.
  rights:
  - right: access, correct, export or delete
    text: you may have the right to access, correct, export or delete the personal data we hold about you, and to object to some processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not use your queries to build a profile of you or your organisation.
  subprocessors:
    text: 'We share data only with the processors needed to run the service: our hosting and edge platform, which runs the API and stores the database; the infrastructure that retrieves results from the target search engine; a transactional email provider, for verification and account email; Polar (Polar Software Inc.), the merchant of record for plans bought from us'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SerpResult
provenance_date: '2026-11-10'
provider_name: SerpResult
provider_slug: serpresult-com
slug: serpresult-com-privacy-policy
source_date: '2026-11-10'
source_filename: serpresult-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.serpresult.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SerpResult\naid: serpresult-com\nurl: https://www.serpresult.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, your name if you give one, and the profile details your identity provider returns when\n    you sign in with Google.\n- category: financial\n  text: the billing address and tax id you enter at checkout\n- category: device\n  text: Your theme preference is stored in your own browser and is never sent to us.\npurposes:\n- purpose: Answer API calls and show them in the dashboard\n  text: To answer\
  \ your API calls and show them back to you in the dashboard.\n- purpose: Metering and rate limits\n  text: To meter credits and enforce rate limits.\n- purpose: Debugging failures\n  text: To debug failures, which is why each response carries a request id.\n- purpose: Service email\n  text: To send service email you cannot opt out of, such as email verification.\nretention:\n- scope: Account data\n  period: null\n  text: Account data is kept while the account exists.\n- scope: Query logs\n  period: null\n  text: Query logs are kept for a bounded retention window and then deleted by a scheduled job.\n- scope: Stored results\n  period: null\n  text: Stored results expire on their own freshness window.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data only with the processors needed to run the service: our hosting and edge platform, which\n    runs the API and stores the database; the infrastructure that retrieves results from the target search engine;\n \
  \   a transactional email provider, for verification and account email; Polar (Polar Software Inc.), the merchant\n    of record for plans bought from us'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deleting the account\n  text: Deleting your account removes the account row and the keys and logs that hang off it.\nrights:\n- right: access, correct, export or delete\n  text: you may have the right to access, correct, export or delete the personal data we hold about you, and to\n    object to some processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not use your queries to build a profile of you or your organisation.\n"
source_yaml_url: https://artifacts.apis.io/serpresult-com/privacy/serpresult-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from SerpResult's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Data
- JSON
- Cloud
---
