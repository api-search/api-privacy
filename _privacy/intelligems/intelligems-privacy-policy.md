---
api_specs:
- filename: intelligems-create-custom-event-api-openapi.yml
  format: yaml
  label: Intelligems Create Custom Event API
  slug: intelligems-create-custom-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-create-custom-event-api-openapi.yml
- filename: intelligems-create-experience-api-openapi.yml
  format: yaml
  label: Intelligems Create Experience API
  slug: intelligems-create-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-create-experience-api-openapi.yml
- filename: intelligems-fetch-experience-data-api-openapi.yml
  format: yaml
  label: Intelligems Fetch Experience Data API
  slug: intelligems-fetch-experience-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-fetch-experience-data-api-openapi.yml
- filename: intelligems-fetch-experience-list-api-openapi.yml
  format: yaml
  label: Intelligems Fetch Experience List API
  slug: intelligems-fetch-experience-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-fetch-experience-list-api-openapi.yml
- filename: intelligems-fetch-sitewide-analytics-api-openapi.yml
  format: yaml
  label: Intelligems Fetch Sitewide Analytics API
  slug: intelligems-fetch-sitewide-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-fetch-sitewide-analytics-api-openapi.yml
- filename: intelligems-get-experience-export-api-openapi.yml
  format: yaml
  label: Intelligems Get Experience Export API
  slug: intelligems-get-experience-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-get-experience-export-api-openapi.yml
- filename: intelligems-get-holiday-benchmark-data-api-openapi.yml
  format: yaml
  label: Intelligems Get Holiday Benchmark Data API
  slug: intelligems-get-holiday-benchmark-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-get-holiday-benchmark-data-api-openapi.yml
- filename: intelligems-perform-experience-action-api-openapi.yml
  format: yaml
  label: Intelligems Perform Experience Action API
  slug: intelligems-perform-experience-action-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-perform-experience-action-api-openapi.yml
- filename: intelligems-update-experience-api-openapi.yml
  format: yaml
  label: Intelligems Update Experience API
  slug: intelligems-update-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-update-experience-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address, and phone number
  - category: contact
    text: Store Details (Name, Email, Address, Phone, and other inputted contact information)
  - category: device
    text: IP addresses, web browser details, operating system details, time zone, currency, page views, referring/exit pages, and information about the cookies installed on the particular device
  - category: behavioral
    text: Orders, Cart, and Checkout Events, and associated analytics
  - category: financial
    text: Discount information
  deletion:
    route: Data Deletion page at https://www.intelligems.io/data-deletion
    text: For instructions on requesting deletion, see our Data Deletion page at https://www.intelligems.io/data-deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service and operate the App
    text: We use the personal information we collect from you and your customers in order to provide the Service and to operate the App.
  - purpose: communicate, improve, benchmarks, marketing
    text: Communicate with you; Optimize or improve the App; create aggregated data benchmarks; and provide you with information or advertising relating to our products or services.
  retention:
  - period: 30 days
    scope: Shopify API data
    text: We delete personal information retrieved through Shopify APIs within 30 days after revocation of access or termination or expiration of the applicable agreement
  - period: generally within 30 days
    scope: Meta Platform Data
    text: we will delete or irreversibly de-identify the applicable Meta Platform Data as soon as reasonably practicable, generally within 30 days
  rights:
  - right: access, correction, update, deletion (European residents)
    text: If you are a European resident, you have the right to access personal information we hold about you and to ask that your personal information be corrected, updated, or deleted.
  role:
    text: Intelligems, Inc. (“Intelligems,” “we,” “us,” or “our”) provides the Intelligems application
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your customers’ personal information or disclose it to third parties for their own independent purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: your information will be transferred outside of Europe, including to Canada and the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Intelligems
provenance_date: '2026-11-09'
provider_name: Intelligems
provider_slug: intelligems
slug: intelligems-privacy-policy
source_date: '2026-11-09'
source_filename: intelligems-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.intelligems.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Intelligems\naid: intelligems\nurl: https://www.intelligems.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Intelligems, Inc. (“Intelligems,” “we,” “us,” or “our”) provides the Intelligems application\ndata_categories:\n- category: identifying\n  text: name, email address, and phone number\n- category: contact\n  text: Store Details (Name, Email, Address, Phone, and other inputted contact information)\n- category: device\n  text: IP addresses, web browser details, operating system details, time zone, currency, page views, referring/exit\n    pages, and information about the\
  \ cookies installed on the particular device\n- category: behavioral\n  text: Orders, Cart, and Checkout Events, and associated analytics\n- category: financial\n  text: Discount information\npurposes:\n- purpose: provide the Service and operate the App\n  text: We use the personal information we collect from you and your customers in order to provide the Service and\n    to operate the App.\n- purpose: communicate, improve, benchmarks, marketing\n  text: Communicate with you; Optimize or improve the App; create aggregated data benchmarks; and provide you with\n    information or advertising relating to our products or services.\nretention:\n- scope: Shopify API data\n  period: 30 days\n  text: We delete personal information retrieved through Shopify APIs within 30 days after revocation of access\n    or termination or expiration of the applicable agreement\n- scope: Meta Platform Data\n  period: generally within 30 days\n  text: we will delete or irreversibly de-identify the applicable\
  \ Meta Platform Data as soon as reasonably practicable,\n    generally within 30 days\nresidency: []\ntransfers:\n- mechanism: other\n  text: your information will be transferred outside of Europe, including to Canada and the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data Deletion page at https://www.intelligems.io/data-deletion\n  text: For instructions on requesting deletion, see our Data Deletion page at https://www.intelligems.io/data-deletion.\nrights:\n- right: access, correction, update, deletion (European residents)\n  text: If you are a European resident, you have the right to access personal information we hold about you and\n    to ask that your personal information be corrected, updated, or deleted.\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your customers’ personal information or disclose it to third parties for their own independent\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/intelligems/privacy/intelligems-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Intelligems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- A/B Testing
- E-Commerce
- Pricing
- Personalization
- Conversion Rate Optimization
- Shopify
- Analytics
- Experimentation
- MCP
- Webhook
- Profit Optimization
---
