---
api_specs:
- filename: appsamurai-campaign-spend-api-openapi.yml
  format: yaml
  label: Appsamurai Campaign Spend API
  slug: appsamurai-campaign-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-campaign-spend-api-openapi.yml
- filename: appsamurai-app-api-openapi.yml
  format: yaml
  label: Appsamurai App API
  slug: appsamurai-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-app-api-openapi.yml
- filename: appsamurai-audience-api-openapi.yml
  format: yaml
  label: Appsamurai Audience API
  slug: appsamurai-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-audience-api-openapi.yml
- filename: appsamurai-instance-api-openapi.yml
  format: yaml
  label: Appsamurai Instance API
  slug: appsamurai-instance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-instance-api-openapi.yml
- filename: appsamurai-segment-api-openapi.yml
  format: yaml
  label: Appsamurai Segment API
  slug: appsamurai-segment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-segment-api-openapi.yml
- filename: appsamurai-story-api-openapi.yml
  format: yaml
  label: Appsamurai Story API
  slug: appsamurai-story-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-story-api-openapi.yml
- filename: appsamurai-story-group-api-openapi.yml
  format: yaml
  label: Appsamurai Story Group API
  slug: appsamurai-story-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsamurai/openapi/appsamurai-story-group-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may collect data which you may be personally identified such as your name, postal address, email address, phone number
  - category: device
    text: IP address, operating system and browser type
  - category: behavioral
    text: Information regarding which advertisements You have seen or clicked on
  - category: financial
    text: If you want to work with App Samurai, you may submit your credit card information.
  - category: location
    text: traffic data, geo information and locale, logs and communication data
  deletion:
    route: request by email to privacy@appsamurai.com
    text: Unless it is prohibited by law, upon your request, we will remove any of your Personal Information from our servers.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: improve website and services
    text: Improve the website by monitoring how you use it and to recognize you when you return to our website.
  - purpose: mobile marketing and advertising services
    text: We use the aforementioned data for providing marketing and advertising services to our Customers
  - purpose: legal obligations and contract enforcement
    text: To carry out our obligations and enforce our rights arising from any contracts entered into between you and us, including for billing and collection.
  residency:
  - region: Europe
    text: Our servers are located in Europe, so your information may be transferred to, stored, or processed in Europe.
  retention:
  - period: null
    scope: website personal information
    text: We will retain your information for as long as your account is active or as long as needed to provide you with our services.
  - period: null
    scope: end-user data
    text: The personal data is anonymised as soon as collected and We store only such anonymized data as long as our Customers are using our technology
  rights:
  - right: access
    text: the right of access (Art 15 GDPR)
  - right: rectification
    text: the right to rectification (Art 16 GDPR)
  - right: erasure
    text: the right to erasure of your personal data (Art 17 GDPR)
  - right: portability
    text: the right to data portability (Art 20 GDPR)
  - right: opt-out of sale (CCPA)
    text: the right to opt-out of the sale of data about you
  role:
    text: We process data as a data controller (as such terms are defined in the GDPR).
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Appsamurai
provenance_date: '2026-11-09'
provider_name: Appsamurai
provider_slug: appsamurai
slug: appsamurai-privacy-policy
source_date: '2026-11-09'
source_filename: appsamurai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://appsamurai.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Appsamurai\naid: appsamurai\nurl: https://appsamurai.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We process data as a data controller (as such terms are defined in the GDPR).\ndata_categories:\n- category: identifying\n  text: we may collect data which you may be personally identified such as your name, postal address, email address,\n    phone number\n- category: device\n  text: IP address, operating system and browser type\n- category: behavioral\n  text: Information regarding which advertisements You have seen or clicked on\n- category: financial\n  text: If you want to\
  \ work with App Samurai, you may submit your credit card information.\n- category: location\n  text: traffic data, geo information and locale, logs and communication data\npurposes:\n- purpose: improve website and services\n  text: Improve the website by monitoring how you use it and to recognize you when you return to our website.\n- purpose: mobile marketing and advertising services\n  text: We use the aforementioned data for providing marketing and advertising services to our Customers\n- purpose: legal obligations and contract enforcement\n  text: To carry out our obligations and enforce our rights arising from any contracts entered into between you\n    and us, including for billing and collection.\nretention:\n- scope: website personal information\n  period: null\n  text: We will retain your information for as long as your account is active or as long as needed to provide you\n    with our services.\n- scope: end-user data\n  period: null\n  text: The personal data is anonymised\
  \ as soon as collected and We store only such anonymized data as long as our\n    Customers are using our technology\nresidency:\n- region: Europe\n  text: Our servers are located in Europe, so your information may be transferred to, stored, or processed in Europe.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request by email to privacy@appsamurai.com\n  text: Unless it is prohibited by law, upon your request, we will remove any of your Personal Information from\n    our servers.\nrights:\n- right: access\n  text: the right of access (Art 15 GDPR)\n- right: rectification\n  text: the right to rectification (Art 16 GDPR)\n- right: erasure\n  text: the right to erasure of your personal data (Art 17 GDPR)\n- right: portability\n  text: the right to data portability (Art 20 GDPR)\n- right: opt-out of sale (CCPA)\n  text: the right to opt-out of the sale of data about you\nsale_or_sharing:\n  stance: unstated\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/appsamurai/privacy/appsamurai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 18 quoted statements, read from Appsamurai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobile
- Advertising
- User Acquisition
- Marketing
- App Growth
- Attribution
- Analytics
- Mobile Marketing
- SDK
- Storyly
- Content Experience
- In-App Stories
- MCP
- Mobile Commerce
---
