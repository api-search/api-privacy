---
api_specs:
- filename: allfly-connect-api-openapi.yml
  format: yaml
  label: AllFly Connect API
  slug: allfly-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allfly/openapi/allfly-connect-api-openapi.yml
- filename: allfly-events-api-openapi.yml
  format: yaml
  label: AllFly Events API
  slug: allfly-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allfly/openapi/allfly-events-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Personal Identifiers: Name, email address, phone number, date of birth'
  - category: financial
    text: 'Payment Information: Credit card details, billing address, corporate payment account information'
  - category: location
    text: 'Location Information: Approximate location based on IP address, GPS data (with your permission)'
  - category: behavioral
    text: 'Usage Data: Pages viewed, features used, click patterns, search queries, booking patterns'
  - category: device
    text: 'Device Information: IP address, browser type, operating system, device identifiers'
  - category: professional
    text: 'Professional Information: Company name, job title, employee ID, department'
  deletion:
    route: request via contacting AllFly
    text: You may request that we delete your personal information, subject to certain exceptions such as legal obligations or ongoing services.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Process travel bookings and reservations
    text: Process travel bookings and reservations
  - purpose: Marketing communications
    text: Send marketing communications (with your consent)
  - purpose: Fraud prevention and security
    text: Monitor for security threats and fraudulent activity
  - purpose: Analytics
    text: Analyze usage trends and platform performance
  residency:
  - region: United States
    text: AllFly is based in the United States.
  retention:
  - period: seven years
    scope: Travel booking information
    text: Generally, we retain travel booking information for seven years after the completion of travel, unless a longer retention period is required by law or your employer's policies.
  rights:
  - right: Access and portability
    text: You have the right to request access to the personal information we hold about you and receive a copy in a portable format.
  - right: Correction
    text: You can update or correct your personal information through your account settings or by contacting us.
  - right: Deletion
    text: You may request that we delete your personal information, subject to certain exceptions such as legal obligations or ongoing services.
  - right: Opt-out of marketing
    text: You can unsubscribe from marketing communications by clicking the "unsubscribe" link in our emails or updating your preferences in your account settings.
  - right: Opt-out of sale (California)
    text: The right to opt-out of the sale of personal information (we do not sell personal information)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: The right to opt-out of the sale of personal information (we do not sell personal information)
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We implement appropriate safeguards for international data transfers as required by applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AllFly
provenance_date: '2026-11-09'
provider_name: AllFly
provider_slug: allfly
slug: allfly-privacy-policy
source_date: '2026-11-09'
source_filename: allfly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://allfly.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AllFly\naid: allfly\nurl: https://allfly.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Personal Identifiers: Name, email address, phone number, date of birth'\n- category: financial\n  text: 'Payment Information: Credit card details, billing address, corporate payment account information'\n- category: location\n  text: 'Location Information: Approximate location based on IP address, GPS data (with your permission)'\n- category: behavioral\n  text: 'Usage Data: Pages viewed, features used, click patterns, search queries,\
  \ booking patterns'\n- category: device\n  text: 'Device Information: IP address, browser type, operating system, device identifiers'\n- category: professional\n  text: 'Professional Information: Company name, job title, employee ID, department'\npurposes:\n- purpose: Process travel bookings and reservations\n  text: Process travel bookings and reservations\n- purpose: Marketing communications\n  text: Send marketing communications (with your consent)\n- purpose: Fraud prevention and security\n  text: Monitor for security threats and fraudulent activity\n- purpose: Analytics\n  text: Analyze usage trends and platform performance\nretention:\n- scope: Travel booking information\n  period: seven years\n  text: Generally, we retain travel booking information for seven years after the completion of travel, unless a\n    longer retention period is required by law or your employer's policies.\nresidency:\n- region: United States\n  text: AllFly is based in the United States.\ntransfers:\n- mechanism:\
  \ other\n  text: We implement appropriate safeguards for international data transfers as required by applicable law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request via contacting AllFly\n  text: You may request that we delete your personal information, subject to certain exceptions such as legal obligations\n    or ongoing services.\nrights:\n- right: Access and portability\n  text: You have the right to request access to the personal information we hold about you and receive a copy in\n    a portable format.\n- right: Correction\n  text: You can update or correct your personal information through your account settings or by contacting us.\n- right: Deletion\n  text: You may request that we delete your personal information, subject to certain exceptions such as legal obligations\n    or ongoing services.\n- right: Opt-out of marketing\n  text: You can unsubscribe from marketing communications by clicking the \"\
  unsubscribe\" link in our emails or updating\n    your preferences in your account settings.\n- right: Opt-out of sale (California)\n  text: The right to opt-out of the sale of personal information (we do not sell personal information)\nsale_or_sharing:\n  stance: prohibited\n  text: The right to opt-out of the sale of personal information (we do not sell personal information)\n"
source_yaml_url: https://artifacts.apis.io/allfly/privacy/allfly-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from AllFly's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Corporate Travel
- Marketplace
- Booking
- Software-as-a-Service
---
