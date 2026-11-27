---
api_specs:
- filename: robase-dev-dashboard-api-openapi.yml
  format: yaml
  label: robase-dev Dashboard API
  slug: robase-dev-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-dashboard-api-openapi.yml
- filename: robase-dev-otp-api-openapi.yml
  format: yaml
  label: robase-dev OTP API
  slug: robase-dev-otp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-otp-api-openapi.yml
- filename: robase-dev-sms-api-openapi.yml
  format: yaml
  label: robase-dev SMS API
  slug: robase-dev-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-sms-api-openapi.yml
- filename: robase-dev-system-api-openapi.yml
  format: yaml
  label: robase-dev System API
  slug: robase-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/robase-dev/openapi/robase-dev-system-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, company name, and password.
  - category: contact
    text: 'Usage Data: We collect API request logs, including sender and recipient phone numbers, message content, timestamps, delivery status, and IP addresses'
  - category: financial
    text: 'We collect payment processing data (handled by our third-party payment processor: we do not store full credit card numbers).'
  - category: device
    text: IP addresses
  - category: communication
    text: message content
  deletion:
    route: contact us
    text: You may request deletion of your data by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate service
    text: To provide, operate, and maintain our SMS OTP API service
  - purpose: billing
    text: To process transactions and send billing notifications
  - purpose: reliability and improvement
    text: To monitor and improve platform reliability and performance
  - purpose: communications and support
    text: To communicate with you about service updates, security alerts, and support
  - purpose: fraud prevention
    text: To detect and prevent fraud, abuse, or unauthorized access
  - purpose: legal compliance
    text: To comply with legal obligations and regulatory requirements
  retention:
  - period: as long as your account is active
    scope: account information
    text: We retain your account information for as long as your account is active.
  - period: up to 12 months
    scope: message logs
    text: Message logs (including phone numbers and delivery data) are retained for up to 12 months for billing, auditing, and dispute resolution purposes.
  rights:
  - right: access
    text: you may have the right to access, correct, delete, or port your personal data.
  - right: withdraw consent
    text: You may also withdraw consent where processing is based on consent.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: robase-dev
provenance_date: '2026-11-10'
provider_name: robase-dev
provider_slug: robase-dev
slug: robase-dev-privacy-policy
source_date: '2026-11-10'
source_filename: robase-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://robase.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: robase-dev\naid: robase-dev\nurl: https://robase.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, company name, and password.\n- category: contact\n  text: 'Usage Data: We collect API request logs, including sender and recipient phone numbers, message content,\n    timestamps, delivery status, and IP addresses'\n- category: financial\n  text: 'We collect payment processing data (handled by our third-party payment processor: we do not store full\n    credit card numbers).'\n- category: device\n\
  \  text: IP addresses\n- category: communication\n  text: message content\npurposes:\n- purpose: provide and operate service\n  text: To provide, operate, and maintain our SMS OTP API service\n- purpose: billing\n  text: To process transactions and send billing notifications\n- purpose: reliability and improvement\n  text: To monitor and improve platform reliability and performance\n- purpose: communications and support\n  text: To communicate with you about service updates, security alerts, and support\n- purpose: fraud prevention\n  text: To detect and prevent fraud, abuse, or unauthorized access\n- purpose: legal compliance\n  text: To comply with legal obligations and regulatory requirements\nretention:\n- scope: account information\n  period: as long as your account is active\n  text: We retain your account information for as long as your account is active.\n- scope: message logs\n  period: up to 12 months\n  text: Message logs (including phone numbers and delivery data) are retained\
  \ for up to 12 months for billing, auditing,\n    and dispute resolution purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us\n  text: You may request deletion of your data by contacting us.\nrights:\n- right: access\n  text: you may have the right to access, correct, delete, or port your personal data.\n- right: withdraw consent\n  text: You may also withdraw consent where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/robase-dev/privacy/robase-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from robase-dev's own page on 2026-11-10.
synthetic: false
tags:
- SMS
- OTP
- Africa
- Messaging
- Communications
---
