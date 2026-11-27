---
api_specs:
- filename: nursa-clinicians-api-openapi.yml
  format: yaml
  label: Nursa Clinicians API
  slug: nursa-clinicians-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-clinicians-api-openapi.yml
- filename: nursa-downloads-api-openapi.yml
  format: yaml
  label: Nursa Downloads API
  slug: nursa-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-downloads-api-openapi.yml
- filename: nursa-facilities-api-openapi.yml
  format: yaml
  label: Nursa Facilities API
  slug: nursa-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-facilities-api-openapi.yml
- filename: nursa-facilities-webhooks-api-openapi.yml
  format: yaml
  label: Nursa Facilities webhooks API
  slug: nursa-facilities-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-facilities-webhooks-api-openapi.yml
- filename: nursa-licenses-api-openapi.yml
  format: yaml
  label: Nursa Licenses API
  slug: nursa-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-licenses-api-openapi.yml
- filename: nursa-marketplace-api-openapi.yml
  format: yaml
  label: Nursa Marketplace API
  slug: nursa-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-marketplace-api-openapi.yml
- filename: nursa-scheduled-shifts-api-openapi.yml
  format: yaml
  label: Nursa Scheduled shifts API
  slug: nursa-scheduled-shifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-scheduled-shifts-api-openapi.yml
- filename: nursa-shift-reports-api-openapi.yml
  format: yaml
  label: Nursa Shift reports API
  slug: nursa-shift-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-shift-reports-api-openapi.yml
- filename: nursa-shift-requests-api-openapi.yml
  format: yaml
  label: Nursa Shift requests API
  slug: nursa-shift-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-shift-requests-api-openapi.yml
- filename: nursa-shifts-api-openapi.yml
  format: yaml
  label: Nursa Shifts API
  slug: nursa-shifts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-shifts-api-openapi.yml
- filename: nursa-support-api-openapi.yml
  format: yaml
  label: Nursa Support API
  slug: nursa-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-support-api-openapi.yml
- filename: nursa-user-webhooks-api-openapi.yml
  format: yaml
  label: Nursa User webhooks API
  slug: nursa-user-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-user-webhooks-api-openapi.yml
- filename: nursa-webhook-logs-api-openapi.yml
  format: yaml
  label: Nursa Webhook logs API
  slug: nursa-webhook-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nursa/openapi/nursa-webhook-logs-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nursa collects data, such as, but not limited to, name, address, e-mail address, nursing license information, fax and telephone numbers, employer and credit card information, etc.
  - category: health
    text: You may choose to upload professional credentials or health information, such as vaccination records and test results, to the Platform.
  - category: location
    text: Nursa collects location data before, during, and after your scheduled shift.
  - category: device
    text: Nursa may collect information about your device and browsing preferences, including, but not limited to your IP address, operating system, browser, mobile hardware provider, etc.
  - category: communication
    text: Nursa may keep a record of any correspondence with you.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: direct marketing
    text: For direct marketing campaigns, as permitted by law
  - purpose: display shifts near location
    text: To display available shifts close to your location
  - purpose: credential verification
    text: To use uploaded images or PDFs to verify your credentials and to surface them to authorized facility users.
  - purpose: AI processing
    text: Nursa may use artificial intelligence (AI) technologies to process your personal information for purposes such as improving our services, automating routine tasks, enhancing customer support, analyzing user interactions, providing personalized recommendations, detecting fraud, or enhancing security.
  retention:
  - period: null
    scope: information provided through the Platform
    text: Nursa may retain copies of all information that you provide through the Platform, both during your use of the Platform and any services available through the Platform and after termination or expiration of such use.
  rights:
  - right: data access request
    text: Nursa shall use commercially reasonable efforts to respond to your data access request within 30 days of receiving your request.
  - right: unsubscribe from mailing lists
    text: Should you choose to unsubscribe from any mailing lists for which you registered, you may do so by following the instructions on how to unsubscribe provided in all Nursa communications.
  role:
    text: null
    value: unstated
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
name: Nursa
provenance_date: '2026-11-10'
provider_name: Nursa
provider_slug: nursa
slug: nursa-privacy-policy
source_date: '2026-11-10'
source_filename: nursa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nursa.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nursa\naid: nursa\nurl: https://nursa.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Nursa collects data, such as, but not limited to, name, address, e-mail address, nursing license information,\n    fax and telephone numbers, employer and credit card information, etc.\n- category: health\n  text: You may choose to upload professional credentials or health information, such as vaccination records and\n    test results, to the Platform.\n- category: location\n  text: Nursa collects location data before, during, and after\
  \ your scheduled shift.\n- category: device\n  text: Nursa may collect information about your device and browsing preferences, including, but not limited to\n    your IP address, operating system, browser, mobile hardware provider, etc.\n- category: communication\n  text: Nursa may keep a record of any correspondence with you.\npurposes:\n- purpose: direct marketing\n  text: For direct marketing campaigns, as permitted by law\n- purpose: display shifts near location\n  text: To display available shifts close to your location\n- purpose: credential verification\n  text: To use uploaded images or PDFs to verify your credentials and to surface them to authorized facility users.\n- purpose: AI processing\n  text: Nursa may use artificial intelligence (AI) technologies to process your personal information for purposes\n    such as improving our services, automating routine tasks, enhancing customer support, analyzing user interactions,\n    providing personalized recommendations, detecting\
  \ fraud, or enhancing security.\nretention:\n- scope: information provided through the Platform\n  period: null\n  text: Nursa may retain copies of all information that you provide through the Platform, both during your use of\n    the Platform and any services available through the Platform and after termination or expiration of such use.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: data access request\n  text: Nursa shall use commercially reasonable efforts to respond to your data access request within 30 days of\n    receiving your request.\n- right: unsubscribe from mailing lists\n  text: Should you choose to unsubscribe from any mailing lists for which you registered, you may do so by following\n    the instructions on how to unsubscribe provided in all Nursa communications.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nursa/privacy/nursa-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 12 quoted statements, read from Nursa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Staffing
- Nursing
- Marketplace
- Workforce Management
- Scheduling
- Human Resources
- Per Diem
- Shifts
- Webhook
---
