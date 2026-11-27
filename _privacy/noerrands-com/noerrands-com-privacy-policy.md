---
api_specs:
- filename: noerrands-com-booking-api-openapi.yml
  format: yaml
  label: noerrands-com Booking API
  slug: noerrands-com-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-booking-api-openapi.yml
- filename: noerrands-com-cards-api-openapi.yml
  format: yaml
  label: noerrands-com Cards API
  slug: noerrands-com-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-cards-api-openapi.yml
- filename: noerrands-com-fax-api-openapi.yml
  format: yaml
  label: noerrands-com Fax API
  slug: noerrands-com-fax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-fax-api-openapi.yml
- filename: noerrands-com-mail-api-openapi.yml
  format: yaml
  label: noerrands-com Mail API
  slug: noerrands-com-mail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-mail-api-openapi.yml
- filename: noerrands-com-prints-api-openapi.yml
  format: yaml
  label: noerrands-com Prints API
  slug: noerrands-com-prints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-prints-api-openapi.yml
- filename: noerrands-com-ship-api-openapi.yml
  format: yaml
  label: noerrands-com Ship API
  slug: noerrands-com-ship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-ship-api-openapi.yml
- filename: noerrands-com-sign-api-openapi.yml
  format: yaml
  label: noerrands-com Sign API
  slug: noerrands-com-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-sign-api-openapi.yml
- filename: noerrands-com-tables-api-openapi.yml
  format: yaml
  label: noerrands-com Tables API
  slug: noerrands-com-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/noerrands-com/openapi/noerrands-com-tables-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address You, when you create an API key
  - category: financial
    text: Your credit balance and ledger of charges
  - category: device
    text: 'Basic technical logs: IP address, timestamp, endpoint, status code'
  - category: identifying
    text: A hash of your API key and its first 12 characters
  - category: communication
    text: Content you send through a specific connector is described on that connector's own privacy page
  deletion:
    route: Ask your agent to delete your data and it calls delete_my_data, or email support@noerrands.com
    text: Ask your agent to delete your data and it calls delete_my_data , which works on every connector.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: To run the service
  - purpose: Billing and refunds
    text: Billing and refunds
  - purpose: Security and abuse prevention
    text: Security, abuse prevention, rate limiting, and debugging
  residency:
  - region: Western North America
    text: Our database (Cloudflare D1) is placed in western North America
  - region: Eastern North America
    text: our file storage (Cloudflare R2) in eastern North America
  retention:
  - period: Until you delete your account
    scope: Account email
    text: Until you delete your account. delete_my_data erases it at once; we keep no copy or hash of it
  - period: Until the key is revoked, then 30 days
    scope: API key hashes
    text: Until the key is revoked, then 30 days
  - period: At least 7 years
    scope: Billing ledger and receipts
    text: At least 7 years, because tax rules require it
  - period: Up to 90 days
    scope: Technical logs
    text: Up to 90 days. Rate-limit counters, which hold IP addresses, are deleted within 3 days
  rights:
  - right: Deletion
    text: You can also email support@noerrands.com from the address on your account and ask us to delete it.
  - right: Access copy
    text: You can also ask us for a copy of what we hold about you, or ask us to correct it.
  - right: Correction
    text: or ask us to correct it
  role:
    text: This policy covers No Errands, operated by Maren Technologies LLC, a company organised in Missouri, United States.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and we do not share it for cross-context behavioural advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We have not signed separate transfer agreements, such as Standard Contractual Clauses, with them.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: noerrands-com
provenance_date: '2026-11-10'
provider_name: noerrands-com
provider_slug: noerrands-com
slug: noerrands-com-privacy-policy
source_date: '2026-11-10'
source_filename: noerrands-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://noerrands.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: noerrands-com\naid: noerrands-com\nurl: https://noerrands.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This policy covers No Errands, operated by Maren Technologies LLC, a company organised in Missouri, United\n    States.\ndata_categories:\n- category: contact\n  text: Your email address You, when you create an API key\n- category: financial\n  text: Your credit balance and ledger of charges\n- category: device\n  text: 'Basic technical logs: IP address, timestamp, endpoint, status code'\n- category: identifying\n  text: A hash of your API key and its first 12 characters\n\
  - category: communication\n  text: Content you send through a specific connector is described on that connector's own privacy page\npurposes:\n- purpose: Run the service\n  text: To run the service\n- purpose: Billing and refunds\n  text: Billing and refunds\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention, rate limiting, and debugging\nretention:\n- scope: Account email\n  period: Until you delete your account\n  text: Until you delete your account. delete_my_data erases it at once; we keep no copy or hash of it\n- scope: API key hashes\n  period: Until the key is revoked, then 30 days\n  text: Until the key is revoked, then 30 days\n- scope: Billing ledger and receipts\n  period: At least 7 years\n  text: At least 7 years, because tax rules require it\n- scope: Technical logs\n  period: Up to 90 days\n  text: Up to 90 days. Rate-limit counters, which hold IP addresses, are deleted within 3 days\nresidency:\n- region: Western North America\n  text: Our database\
  \ (Cloudflare D1) is placed in western North America\n- region: Eastern North America\n  text: our file storage (Cloudflare R2) in eastern North America\ntransfers:\n- mechanism: other\n  text: We have not signed separate transfer agreements, such as Standard Contractual Clauses, with them.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask your agent to delete your data and it calls delete_my_data, or email support@noerrands.com\n  text: Ask your agent to delete your data and it calls delete_my_data , which works on every connector.\nrights:\n- right: Deletion\n  text: You can also email support@noerrands.com from the address on your account and ask us to delete it.\n- right: Access copy\n  text: You can also ask us for a copy of what we hold about you, or ask us to correct it.\n- right: Correction\n  text: or ask us to correct it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and\
  \ we do not share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/noerrands-com/privacy/noerrands-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from noerrands-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Productivity
- Messaging
---
