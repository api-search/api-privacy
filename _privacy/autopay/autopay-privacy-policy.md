---
api_specs:
- filename: autopay-accounting-api-openapi.yml
  format: yaml
  label: Autopay Accounting API
  slug: autopay-accounting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-accounting-api-openapi.yml
- filename: autopay-booking-api-openapi.yml
  format: yaml
  label: Autopay Booking API
  slug: autopay-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-booking-api-openapi.yml
- filename: autopay-customer-club-api-openapi.yml
  format: yaml
  label: Autopay Customer Club API
  slug: autopay-customer-club-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-customer-club-api-openapi.yml
- filename: autopay-fleet-api-openapi.yml
  format: yaml
  label: Autopay Fleet API
  slug: autopay-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-fleet-api-openapi.yml
- filename: autopay-parking-api-openapi.yml
  format: yaml
  label: Autopay Parking API
  slug: autopay-parking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-parking-api-openapi.yml
- filename: autopay-payment-api-openapi.yml
  format: yaml
  label: Autopay Payment API
  slug: autopay-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-payment-api-openapi.yml
- filename: autopay-permit-api-openapi.yml
  format: yaml
  label: Autopay Permit API
  slug: autopay-permit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-permit-api-openapi.yml
- filename: autopay-statistics-api-openapi.yml
  format: yaml
  label: Autopay Statistics API
  slug: autopay-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-statistics-api-openapi.yml
- filename: autopay-status-api-openapi.yml
  format: yaml
  label: Autopay Status API
  slug: autopay-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-status-api-openapi.yml
- filename: autopay-vehicle-api-openapi.yml
  format: yaml
  label: Autopay Vehicle API
  slug: autopay-vehicle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autopay/openapi/autopay-vehicle-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Email address
  - category: identifying
    text: Vehicle registration numbers
  - category: financial
    text: 'Optional: phone number and payment card details'
  - category: location
    text: Location data (for misuse detection in the Autopay App)
  - category: device
    text: IP addresses and technical logs for fraud prevention and system security
  - category: behavioral
    text: Parking and EV-charging session history
  - category: other
    text: ANPR (Automatic Number Plate Recognition) images and plate numbers
  deletion:
    route: Delete Autopay profile or request deletion by email
    text: You request deletion of your personal data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and operating the service
    text: Providing and operating the Autopay service
  - purpose: Account security and fraud prevention
    text: Ensuring account security and fraud prevention
  - purpose: Customer support
    text: Delivering customer support
  - purpose: Service notifications
    text: Sending important service-related notifications
  - purpose: Legal compliance
    text: Complying with legal obligations and requests from public authorities
  retention:
  - period: null
    scope: Personal data
    text: 'Typically, data is stored until: You delete your Autopay profile, or You request deletion of your personal data'
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction or deletion
    text: Request correction or deletion
  - right: Restriction
    text: Request restriction of processing
  - right: Objection
    text: Object to processing
  - right: Portability
    text: Request data portability
  - right: Withdraw consent
    text: Withdraw consent at any time (where consent is the legal basis)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where transfers occur outside the EU/EEA, we use Standard Contractual Clauses or ensure the destination country is approved by the EU Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Autopay
provenance_date: '2026-11-09'
provider_name: Autopay
provider_slug: autopay
slug: autopay-privacy-policy
source_date: '2026-11-09'
source_filename: autopay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://solutions.autopay.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Autopay\naid: autopay\nurl: https://solutions.autopay.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Email address\n- category: identifying\n  text: Vehicle registration numbers\n- category: financial\n  text: 'Optional: phone number and payment card details'\n- category: location\n  text: Location data (for misuse detection in the Autopay App)\n- category: device\n  text: IP addresses and technical logs for fraud prevention and system security\n- category: behavioral\n  text: Parking\
  \ and EV-charging session history\n- category: other\n  text: ANPR (Automatic Number Plate Recognition) images and plate numbers\npurposes:\n- purpose: Providing and operating the service\n  text: Providing and operating the Autopay service\n- purpose: Account security and fraud prevention\n  text: Ensuring account security and fraud prevention\n- purpose: Customer support\n  text: Delivering customer support\n- purpose: Service notifications\n  text: Sending important service-related notifications\n- purpose: Legal compliance\n  text: Complying with legal obligations and requests from public authorities\nretention:\n- scope: Personal data\n  period: null\n  text: 'Typically, data is stored until: You delete your Autopay profile, or You request deletion of your personal\n    data'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where transfers occur outside the EU/EEA, we use Standard Contractual Clauses or ensure the destination\n    country is approved by the EU Commission.\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete Autopay profile or request deletion by email\n  text: You request deletion of your personal data\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correction or deletion\n  text: Request correction or deletion\n- right: Restriction\n  text: Request restriction of processing\n- right: Objection\n  text: Object to processing\n- right: Portability\n  text: Request data portability\n- right: Withdraw consent\n  text: Withdraw consent at any time (where consent is the legal basis)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/autopay/privacy/autopay-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Autopay's own page on 2026-11-09.
synthetic: false
tags:
- Parking
- Parking Payments
- Fleet Management
- Permits
- Parking Operators
- Norway
---
