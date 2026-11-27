---
api_specs:
- filename: toronto-hydro-applicationinformation-api-openapi.yml
  format: yaml
  label: Toronto Hydro Application Information API
  slug: toronto-hydro-applicationinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-applicationinformation-api-openapi.yml
- filename: toronto-hydro-authorization-api-openapi.yml
  format: yaml
  label: Toronto Hydro Authorization API
  slug: toronto-hydro-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-authorization-api-openapi.yml
- filename: toronto-hydro-batch-api-openapi.yml
  format: yaml
  label: Toronto Hydro Batch API
  slug: toronto-hydro-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-batch-api-openapi.yml
- filename: toronto-hydro-usagepoint-api-openapi.yml
  format: yaml
  label: Toronto Hydro Usage Point API
  slug: toronto-hydro-usagepoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toronto-hydro/openapi/toronto-hydro-usagepoint-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information , such as name, address, phone number and email
  - category: identifying
    text: Account information , such as account number, service address, date of birth, government ID number, employer, and login information
  - category: financial
    text: Payment information , such as credit card or other banking information, to bill and collect payment
  - category: location
    text: Geolocation , if an individual uses our app to report an outage
  - category: health
    text: Medical device power requirements , such as type of device, its power needs, and whether it is critical to health.
  - category: behavioral
    text: Customer energy usage and service address , to deliver, monitor and maintain electricity services
  - category: communication
    text: Interactions with us , such as recordings of calls, to keep track of requests, perform quality assurance, resolve disputes and train employees
  - category: device
    text: the internet protocol (IP) address of the computer through which the user is connected to the internet
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate accounts and billing
    text: open and administer accounts (including billing)
  - purpose: Authenticate identity
    text: Authenticate identity
  - purpose: Website analytics
    text: This information is aggregated with that of other visitors to help us understand how the site is being used and how to make it better.
  - purpose: Collect overdue payments
    text: Collect overdue payments
  - purpose: Protect legal interests
    text: Protect us, our employees, our interests, and our property, including in security and legal matters
  retention:
  - period: null
    scope: Personal information
    text: Toronto Hydro will retain personal information only for so long as is reasonably necessary to fulfill the purpose for which it was collected and to meet our legal and contractual obligations.
  rights:
  - right: Access
    text: Individuals can request information regarding the type, use and disclosure of personal information.
  - right: Correction
    text: Individuals can request that their personal information be updated or corrected for purposes of accuracy and completeness.
  - right: Withdraw consent
    text: individuals can refuse or withdraw consent to the collection, use or disclosure of personal information at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Toronto Hydro will not trade, rent or sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We use contractual or other measures to provide a comparable level of protection of this information while the information is being processed by these third parties.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Toronto Hydro
provenance_date: '2026-11-10'
provider_name: Toronto Hydro
provider_slug: toronto-hydro
slug: toronto-hydro-privacy-policy
source_date: '2026-11-10'
source_filename: toronto-hydro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.torontohydro.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Toronto Hydro\naid: toronto-hydro\nurl: https://www.torontohydro.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact information , such as name, address, phone number and email\n- category: identifying\n  text: Account information , such as account number, service address, date of birth, government ID number, employer,\n    and login information\n- category: financial\n  text: Payment information , such as credit card or other banking information, to bill and collect payment\n- category: location\n  text: Geolocation\
  \ , if an individual uses our app to report an outage\n- category: health\n  text: Medical device power requirements , such as type of device, its power needs, and whether it is critical\n    to health.\n- category: behavioral\n  text: Customer energy usage and service address , to deliver, monitor and maintain electricity services\n- category: communication\n  text: Interactions with us , such as recordings of calls, to keep track of requests, perform quality assurance,\n    resolve disputes and train employees\n- category: device\n  text: the internet protocol (IP) address of the computer through which the user is connected to the internet\npurposes:\n- purpose: Operate accounts and billing\n  text: open and administer accounts (including billing)\n- purpose: Authenticate identity\n  text: Authenticate identity\n- purpose: Website analytics\n  text: This information is aggregated with that of other visitors to help us understand how the site is being used\n    and how to make it better.\n\
  - purpose: Collect overdue payments\n  text: Collect overdue payments\n- purpose: Protect legal interests\n  text: Protect us, our employees, our interests, and our property, including in security and legal matters\nretention:\n- scope: Personal information\n  period: null\n  text: Toronto Hydro will retain personal information only for so long as is reasonably necessary to fulfill the\n    purpose for which it was collected and to meet our legal and contractual obligations.\nresidency: []\ntransfers:\n- mechanism: other\n  text: We use contractual or other measures to provide a comparable level of protection of this information while\n    the information is being processed by these third parties.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Individuals can request information regarding the type, use and disclosure of personal information.\n- right: Correction\n\
  \  text: Individuals can request that their personal information be updated or corrected for purposes of accuracy\n    and completeness.\n- right: Withdraw consent\n  text: individuals can refuse or withdraw consent to the collection, use or disclosure of personal information\n    at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: Toronto Hydro will not trade, rent or sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/toronto-hydro/privacy/toronto-hydro-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Toronto Hydro's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Smart Metering
- Green Button
- Grid
- Ontario
- Consumer Data
- Electricity Distribution
---
