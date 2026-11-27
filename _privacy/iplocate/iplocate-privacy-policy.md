---
api_specs:
- filename: iplocate-openapi.yml
  format: yaml
  label: IPLocate API
  slug: iplocate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iplocate/openapi/iplocate-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: This may include your name, e-mail address, your IP address and device/browser information, and any other information you choose to provide us.
  - category: location
    text: we will receive latitude/longitude and an accuracy estimate from your browser or device, together with your IP address and the time of submission.
  - category: device
    text: This may include your Internet Protocol (IP) address, device and browser type, pages viewed, date and time of your visit, referring page, and similar usage data.
  deletion:
    route: null
    text: after which we delete them or further aggregate them.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Manage access and use of services
    text: To manage your access to and use of IPLocate services.
  - purpose: Customer management
    text: To carry out customer management, including contracts, orders, deliveries, invoices, and follow-ups.
  - purpose: Testing and training for geolocation
    text: We use obfuscated location submissions for testing and training purposes related to IPLocate’s geolocation services.
  - purpose: Legal obligations
    text: To respect our legal and regulatory obligations.
  retention:
  - period: 90 days
    scope: Obfuscated location submissions
    text: We retain obfuscated location submissions for up to 90 days for analysis and testing, after which we delete them or further aggregate them.
  - period: null
    scope: Personal Information
    text: We retain Personal Information for as long as necessary to provide the Website and Services and for other legitimate purposes such as security, analytics, and legal compliance.
  rights:
  - right: Withdraw location permission
    text: You may also withdraw permission through your browser or device settings at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A complete list of service providers is available on our List of Service Providers page.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IPLocate (formerly GeoIPs)
provenance_date: '2026-11-09'
provider_name: IPLocate (formerly GeoIPs)
provider_slug: iplocate
slug: iplocate-privacy-policy
source_date: '2026-11-09'
source_filename: iplocate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.iplocate.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IPLocate (formerly GeoIPs)\naid: iplocate\nurl: https://www.iplocate.io/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: This may include your name, e-mail address, your IP address and device/browser information, and any other\n    information you choose to provide us.\n- category: location\n  text: we will receive latitude/longitude and an accuracy estimate from your browser or device, together with your\n    IP address and the time of submission.\n- category: device\n  text: This may include your Internet Protocol (IP) address,\
  \ device and browser type, pages viewed, date and time\n    of your visit, referring page, and similar usage data.\npurposes:\n- purpose: Manage access and use of services\n  text: To manage your access to and use of IPLocate services.\n- purpose: Customer management\n  text: To carry out customer management, including contracts, orders, deliveries, invoices, and follow-ups.\n- purpose: Testing and training for geolocation\n  text: We use obfuscated location submissions for testing and training purposes related to IPLocate’s geolocation\n    services.\n- purpose: Legal obligations\n  text: To respect our legal and regulatory obligations.\nretention:\n- scope: Obfuscated location submissions\n  period: 90 days\n  text: We retain obfuscated location submissions for up to 90 days for analysis and testing, after which we delete\n    them or further aggregate them.\n- scope: Personal Information\n  period: null\n  text: We retain Personal Information for as long as necessary to provide the\
  \ Website and Services and for other\n    legitimate purposes such as security, analytics, and legal compliance.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: A complete list of service providers is available on our List of Service Providers page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: after which we delete them or further aggregate them.\nrights:\n- right: Withdraw location permission\n  text: You may also withdraw permission through your browser or device settings at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iplocate/privacy/iplocate-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 12 quoted statements, read from IPLocate (formerly GeoIPs)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- IP Geolocation
- Threat Detection
- Privacy
- Data
---
