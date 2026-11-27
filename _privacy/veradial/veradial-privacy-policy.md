---
api_specs:
- filename: veradial-hooks-api-openapi.yml
  format: yaml
  label: VeraDial Hooks API
  slug: veradial-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-hooks-api-openapi.yml
- filename: veradial-keys-api-openapi.yml
  format: yaml
  label: VeraDial Keys API
  slug: veradial-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-keys-api-openapi.yml
- filename: veradial-lines-api-openapi.yml
  format: yaml
  label: VeraDial Lines API
  slug: veradial-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-lines-api-openapi.yml
- filename: veradial-me-api-openapi.yml
  format: yaml
  label: VeraDial Me API
  slug: veradial-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-me-api-openapi.yml
- filename: veradial-samples-api-openapi.yml
  format: yaml
  label: VeraDial Samples API
  slug: veradial-samples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veradial/openapi/veradial-samples-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your email address and profile information through Supabase Auth.
  - category: contact
    text: If you add contacts yourself or import them from a CSV file, we store the phone numbers, names, companies and email addresses you provide in your account and show them in your contact list
  - category: location
    text: When you make or receive calls, we may collect your device's GPS coordinates to associate a location with the call record.
  - category: communication
    text: We store message bodies, sender/recipient numbers, timestamps, and delivery status for messages sent and received through the service.
  deletion:
    route: Account deletion
    text: Deleting your account deletes your appointment requests.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide calling, messaging, voicemail, and call screening services
    text: Provide calling, messaging, voicemail, and call screening services
  - purpose: Enforce acceptable use policies and detect abuse
    text: Enforce acceptable use policies and detect abuse
  retention:
  - period: 90 days
    scope: Device call-delivery events
    text: are deleted no later than 90 days after collection
  - period: null
    scope: Appointment requests
    text: Deleting your account deletes your appointment requests.
  role:
    text: VeraDial Inc., the entity responsible for the personal information described below.
    value: controller
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
name: VeraDial
provenance_date: '2026-11-10'
provider_name: VeraDial
provider_slug: veradial
slug: veradial-privacy-policy
source_date: '2026-11-10'
source_filename: veradial-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://veradial.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: VeraDial\naid: veradial\nurl: https://veradial.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: VeraDial Inc., the entity responsible for the personal information described below.\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your email address and profile information through Supabase Auth.\n- category: contact\n  text: If you add contacts yourself or import them from a CSV file, we store the phone numbers, names, companies\n    and email addresses you provide in your account and show them in your contact list\n- category:\
  \ location\n  text: When you make or receive calls, we may collect your device's GPS coordinates to associate a location with\n    the call record.\n- category: communication\n  text: We store message bodies, sender/recipient numbers, timestamps, and delivery status for messages sent and\n    received through the service.\npurposes:\n- purpose: Provide calling, messaging, voicemail, and call screening services\n  text: Provide calling, messaging, voicemail, and call screening services\n- purpose: Enforce acceptable use policies and detect abuse\n  text: Enforce acceptable use policies and detect abuse\nretention:\n- scope: Device call-delivery events\n  period: 90 days\n  text: are deleted no later than 90 days after collection\n- scope: Appointment requests\n  period: null\n  text: Deleting your account deletes your appointment requests.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account\
  \ deletion\n  text: Deleting your account deletes your appointment requests.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/veradial/privacy/veradial-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
summary_line: 10 quoted statements, read from VeraDial's own page on 2026-11-10.
synthetic: false
tags:
- AI Receptionist
- Business Phone
- Telephony
- Voice AI
- SMS
- Webhook
- MCP
- Small Business
---
