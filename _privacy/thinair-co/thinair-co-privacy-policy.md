---
api_specs:
- filename: thinair-co-account-api-openapi.yml
  format: yaml
  label: thinair-co Account API
  slug: thinair-co-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-account-api-openapi.yml
- filename: thinair-co-billing-api-openapi.yml
  format: yaml
  label: thinair-co Billing API
  slug: thinair-co-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-billing-api-openapi.yml
- filename: thinair-co-conditions-api-openapi.yml
  format: yaml
  label: thinair-co Conditions API
  slug: thinair-co-conditions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-conditions-api-openapi.yml
- filename: thinair-co-connections-api-openapi.yml
  format: yaml
  label: thinair-co Connections API
  slug: thinair-co-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-connections-api-openapi.yml
- filename: thinair-co-geocoding-api-openapi.yml
  format: yaml
  label: thinair-co Geocoding API
  slug: thinair-co-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-geocoding-api-openapi.yml
- filename: thinair-co-geofences-api-openapi.yml
  format: yaml
  label: thinair-co Geofences API
  slug: thinair-co-geofences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-geofences-api-openapi.yml
- filename: thinair-co-intersections-api-openapi.yml
  format: yaml
  label: thinair-co Intersections API
  slug: thinair-co-intersections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-intersections-api-openapi.yml
- filename: thinair-co-learning-api-openapi.yml
  format: yaml
  label: thinair-co Learning API
  slug: thinair-co-learning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-learning-api-openapi.yml
- filename: thinair-co-migrations-api-openapi.yml
  format: yaml
  label: thinair-co Migrations API
  slug: thinair-co-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-migrations-api-openapi.yml
- filename: thinair-co-places-api-openapi.yml
  format: yaml
  label: thinair-co Places API
  slug: thinair-co-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-places-api-openapi.yml
- filename: thinair-co-query-api-openapi.yml
  format: yaml
  label: thinair-co Query API
  slug: thinair-co-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-query-api-openapi.yml
- filename: thinair-co-routing-api-openapi.yml
  format: yaml
  label: thinair-co Routing API
  slug: thinair-co-routing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-routing-api-openapi.yml
- filename: thinair-co-tables-api-openapi.yml
  format: yaml
  label: thinair-co Tables API
  slug: thinair-co-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thinair-co/openapi/thinair-co-tables-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact, demo, and price-check forms: name, work email, phone, company, fleet size, industry, product interest, your message'
  - category: financial
    text: Card details are entered into Stripe's checkout and are not stored on our systems; we receive order totals, payment status, and Stripe reference IDs (customer, payment, and subscription IDs).
  - category: location
    text: Approximate location (country). Our hosting provider infers your country from your IP address
  - category: behavioral
    text: collects information about how you use the Site, such as the pages you view and the actions you take
  - category: communication
    text: 'Support: what you tell our chat assistant or support team, including a summary of the conversation, contact details, USDOT number, and the page you were on, if a support ticket is created.'
  - category: device
    text: Our security provider and the spam-protection check on our forms collect device, browser, and network information (including IP address) to tell people from automated traffic.
  - category: other
    text: database connection details you give ThinAir Data include account log-in credentials (such as a database password)
  deletion:
    route: Contact ThinAir
    text: There is no self-service account deletion yet; to ask for deletion, contact us (section 13).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: inquiries and quotes
    text: To respond to inquiries, prepare quotes, and schedule demos.
  - purpose: orders, payments and support
    text: To process orders and payments, fulfill and ship devices, set up and activate ELD accounts, provide support, send service and billing notices, and handle returns and refunds.
  - purpose: legal compliance
    text: To comply with legal obligations and to establish, exercise, or defend legal claims.
  residency:
  - region: United States
    text: ThinAir is based in the United States, and our providers process information in the United States and elsewhere.
  retention:
  - period: No automatic deletion
    scope: Contact, demo, and quote requests
    text: Kept as long as needed to respond and for our business records. No automatic deletion.
  - period: 7 days for each entry
    scope: ThinAir Data query history
    text: 'The last 100 queries for your account: full query text, connection, tables, timing, row count, and a redacted error message, encrypted with AES-256-GCM 7 days for each entry'
  - period: 14 months
    scope: Google Analytics event data
    text: We set event-data retention in our Google Analytics property to 14 months.
  rights:
  - right: Know/access
    text: 'Know/access: the categories and specific pieces of personal information we hold about you'
  - right: Delete
    text: Delete the personal information we collected from you, subject to exceptions
  - right: Correct
    text: Correct inaccurate personal information.
  role:
    text: ThinAir Telematics, LLC is the controller of the personal information described in this policy, except where section 10.1 or section 9 says another party is the controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: We use these providers to run the Services and our business.
    url: null
  transfers:
  - mechanism: SCC
    text: for example, our chat assistant provider's data processing terms include standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: thinair-co
provenance_date: '2026-11-10'
provider_name: thinair-co
provider_slug: thinair-co
slug: thinair-co-privacy-policy
source_date: '2026-11-10'
source_filename: thinair-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.thinair.co/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: thinair-co\naid: thinair-co\nurl: https://www.thinair.co/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: ThinAir Telematics, LLC is the controller of the personal information described in this policy, except where\n    section 10.1 or section 9 says another party is the controller.\ndata_categories:\n- category: contact\n  text: 'Contact, demo, and price-check forms: name, work email, phone, company, fleet size, industry, product interest,\n    your message'\n- category: financial\n  text: Card details are entered into Stripe's checkout and are not stored on\
  \ our systems; we receive order totals,\n    payment status, and Stripe reference IDs (customer, payment, and subscription IDs).\n- category: location\n  text: Approximate location (country). Our hosting provider infers your country from your IP address\n- category: behavioral\n  text: collects information about how you use the Site, such as the pages you view and the actions you take\n- category: communication\n  text: 'Support: what you tell our chat assistant or support team, including a summary of the conversation, contact\n    details, USDOT number, and the page you were on, if a support ticket is created.'\n- category: device\n  text: Our security provider and the spam-protection check on our forms collect device, browser, and network information\n    (including IP address) to tell people from automated traffic.\n- category: other\n  text: database connection details you give ThinAir Data include account log-in credentials (such as a database\n    password)\npurposes:\n- purpose:\
  \ inquiries and quotes\n  text: To respond to inquiries, prepare quotes, and schedule demos.\n- purpose: orders, payments and support\n  text: To process orders and payments, fulfill and ship devices, set up and activate ELD accounts, provide support,\n    send service and billing notices, and handle returns and refunds.\n- purpose: legal compliance\n  text: To comply with legal obligations and to establish, exercise, or defend legal claims.\nretention:\n- scope: Contact, demo, and quote requests\n  period: No automatic deletion\n  text: Kept as long as needed to respond and for our business records. No automatic deletion.\n- scope: ThinAir Data query history\n  period: 7 days for each entry\n  text: 'The last 100 queries for your account: full query text, connection, tables, timing, row count, and a redacted\n    error message, encrypted with AES-256-GCM 7 days for each entry'\n- scope: Google Analytics event data\n  period: 14 months\n  text: We set event-data retention in our Google\
  \ Analytics property to 14 months.\nresidency:\n- region: United States\n  text: ThinAir is based in the United States, and our providers process information in the United States and elsewhere.\ntransfers:\n- mechanism: SCC\n  text: for example, our chat assistant provider's data processing terms include standard contractual clauses.\nsubprocessors:\n  url: null\n  text: We use these providers to run the Services and our business.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact ThinAir\n  text: There is no self-service account deletion yet; to ask for deletion, contact us (section 13).\nrights:\n- right: Know/access\n  text: 'Know/access: the categories and specific pieces of personal information we hold about you'\n- right: Delete\n  text: Delete the personal information we collected from you, subject to exceptions\n- right: Correct\n  text: Correct inaccurate personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal\
  \ information, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/thinair-co/privacy/thinair-co-privacy-policy.yml
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
summary_line: 22 quoted statements, read from thinair-co's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fleet Management
- Telematics
- Logistics
- Compliance
---
