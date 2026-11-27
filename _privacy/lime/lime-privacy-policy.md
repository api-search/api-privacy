---
api_specs:
- filename: lime-free-bike-status-api-openapi.yml
  format: yaml
  label: Lime Free Bike Status API
  slug: lime-free-bike-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lime/openapi/lime-free-bike-status-api-openapi.yml
- filename: lime-gbfs-json-api-openapi.yml
  format: yaml
  label: Lime Gbfs.json API
  slug: lime-gbfs-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lime/openapi/lime-gbfs-json-api-openapi.yml
- filename: lime-station-information-api-openapi.yml
  format: yaml
  label: Lime Station Information API
  slug: lime-station-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lime/openapi/lime-station-information-api-openapi.yml
- filename: lime-station-status-api-openapi.yml
  format: yaml
  label: Lime Station Status API
  slug: lime-station-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lime/openapi/lime-station-status-api-openapi.yml
- filename: lime-system-information-api-openapi.yml
  format: yaml
  label: Lime System Information API
  slug: lime-system-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lime/openapi/lime-system-information-api-openapi.yml
- filename: lime-vehicle-types-api-openapi.yml
  format: yaml
  label: Lime Vehicle Types API
  slug: lime-vehicle-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lime/openapi/lime-vehicle-types-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information such as your name, ID number, e-mail address, telephone number, date of birth, gender, address details, and payment information such as your credit card details.
  - category: location
    text: Trip and Location data when you sign up and use the Services.
  - category: device
    text: technical information such as your device's IP address and device token
  - category: biometric
    text: by using facial recognition technology
  - category: financial
    text: and your bank account details
  - category: behavioral
    text: to gather analytics information about you
  - category: other
    text: 'User-generated content: we collect information you share on the Services'
  deletion:
    route: Settings screen in the app, or request by email to support@li.me
    text: You can delete your Lime account at any time by selecting “Delete your account” from the Settings screen in the app, by submitting a request to us at support@li.me
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Services
    text: provide the Services to you at your request
  - purpose: process payments
    text: process payments, subscriptions or donations
  - purpose: service improvement and machine learning
    text: optimize, develop and improve our Services, including via the creation and training of machine learning models
  - purpose: personalized advertising
    text: personalize advertisements to you
  - purpose: fraud and policy enforcement
    text: detect, investigate, and prevent activities that may violate Lime's policies or terms or be illegal
  retention:
  - period: for the lifetime of the account
    scope: account information
    text: We retain account information, such as your email address and your date of birth, or a copy of your ID, for the lifetime of the account.
  - period: 7 years
    scope: transaction information
    text: Certain information relating to transactions relating to an account are retained for 7 years
  - period: during the ride
    scope: environmental visual data
    text: We process environmental visual data during the ride
  - period: null
    scope: deleted accounts
    text: We may also retain information from deleted accounts to prevent fraud
  rights:
  - right: access
    text: Right of access - You can access much of your information by logging into your account.
  - right: erasure
    text: Right of erasure - You have the right to request that we delete your information.
  - right: portability
    text: Right to data portability - You may have the right to receive certain of your information in a structured, commonly used and machine-readable format
  - right: object to marketing
    text: Right to object (marketing) - You have the right to object to processing for direct marketing purposes at any time.
  - right: lodge complaint
    text: You also have the right to lodge a complaint with your local supervisory authority for data protection.
  role:
    text: Lime is the controller for this processing
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Except as noted in the Privacy Information for California Residents notice, we do not sell your personal information with third parties for their direct marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Lime also relies on Standard Contractual Clauses approved by the European Commission
  - mechanism: adequacy
    text: Lime may rely on the Commission's adequacy decision, as applicable, to transfer data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Lime
provenance_date: '2026-11-09'
provider_name: Lime
provider_slug: lime
slug: lime-privacy-policy
source_date: '2026-11-09'
source_filename: lime-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.li.me/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Lime\naid: lime\nurl: https://www.li.me/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Lime is the controller for this processing\ndata_categories:\n- category: identifying\n  text: Account information such as your name, ID number, e-mail address, telephone number, date of birth, gender,\n    address details, and payment information such as your credit card details.\n- category: location\n  text: Trip and Location data when you sign up and use the Services.\n- category: device\n  text: technical information such as your device's IP address and device token\n- category:\
  \ biometric\n  text: by using facial recognition technology\n- category: financial\n  text: and your bank account details\n- category: behavioral\n  text: to gather analytics information about you\n- category: other\n  text: 'User-generated content: we collect information you share on the Services'\npurposes:\n- purpose: provide the Services\n  text: provide the Services to you at your request\n- purpose: process payments\n  text: process payments, subscriptions or donations\n- purpose: service improvement and machine learning\n  text: optimize, develop and improve our Services, including via the creation and training of machine learning\n    models\n- purpose: personalized advertising\n  text: personalize advertisements to you\n- purpose: fraud and policy enforcement\n  text: detect, investigate, and prevent activities that may violate Lime's policies or terms or be illegal\nretention:\n- scope: account information\n  period: for the lifetime of the account\n  text: We retain account\
  \ information, such as your email address and your date of birth, or a copy of your ID,\n    for the lifetime of the account.\n- scope: transaction information\n  period: 7 years\n  text: Certain information relating to transactions relating to an account are retained for 7 years\n- scope: environmental visual data\n  period: during the ride\n  text: We process environmental visual data during the ride\n- scope: deleted accounts\n  period: null\n  text: We may also retain information from deleted accounts to prevent fraud\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Lime also relies on Standard Contractual Clauses approved by the European Commission\n- mechanism: adequacy\n  text: Lime may rely on the Commission's adequacy decision, as applicable, to transfer data\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings screen in the app, or request by email to support@li.me\n  text: You can delete your Lime account\
  \ at any time by selecting “Delete your account” from the Settings screen\n    in the app, by submitting a request to us at support@li.me\nrights:\n- right: access\n  text: Right of access - You can access much of your information by logging into your account.\n- right: erasure\n  text: Right of erasure - You have the right to request that we delete your information.\n- right: portability\n  text: Right to data portability - You may have the right to receive certain of your information in a structured,\n    commonly used and machine-readable format\n- right: object to marketing\n  text: Right to object (marketing) - You have the right to object to processing for direct marketing purposes at\n    any time.\n- right: lodge complaint\n  text: You also have the right to lodge a complaint with your local supervisory authority for data protection.\nsale_or_sharing:\n  stance: conditional\n  text: Except as noted in the Privacy Information for California Residents notice, we do not sell your\
  \ personal\n    information with third parties for their direct marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/lime/privacy/lime-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Lime's own page on 2026-11-09.
synthetic: false
tags:
- Shared Mobility
- Micromobility
- Electric Scooters
- Electric Bikes
- E-Bikes
- E-Scooter
- Transportation
- Urban Mobility
- GBFS
- MDS
- Smart Cities
- Transit
- Mobility
---
