---
api_specs:
- filename: campfiresms-com-auth-api-openapi.yml
  format: yaml
  label: Campfire SMS Auth API
  slug: campfiresms-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-auth-api-openapi.yml
- filename: campfiresms-com-bridges-api-openapi.yml
  format: yaml
  label: Campfire SMS Bridges API
  slug: campfiresms-com-bridges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-bridges-api-openapi.yml
- filename: campfiresms-com-credential-api-openapi.yml
  format: yaml
  label: Campfire SMS Credential API
  slug: campfiresms-com-credential-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-credential-api-openapi.yml
- filename: campfiresms-com-enrollment-api-openapi.yml
  format: yaml
  label: Campfire SMS Enrollment API
  slug: campfiresms-com-enrollment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-enrollment-api-openapi.yml
- filename: campfiresms-com-health-api-openapi.yml
  format: yaml
  label: Campfire SMS Health API
  slug: campfiresms-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-health-api-openapi.yml
- filename: campfiresms-com-installations-api-openapi.yml
  format: yaml
  label: Campfire SMS Installations API
  slug: campfiresms-com-installations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-installations-api-openapi.yml
- filename: campfiresms-com-join-api-openapi.yml
  format: yaml
  label: Campfire SMS Join API
  slug: campfiresms-com-join-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-join-api-openapi.yml
- filename: campfiresms-com-login-api-openapi.yml
  format: yaml
  label: Campfire SMS Login API
  slug: campfiresms-com-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-login-api-openapi.yml
- filename: campfiresms-com-public-api-openapi.yml
  format: yaml
  label: Campfire SMS Public API
  slug: campfiresms-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-public-api-openapi.yml
- filename: campfiresms-com-setup-api-openapi.yml
  format: yaml
  label: Campfire SMS Setup API
  slug: campfiresms-com-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-setup-api-openapi.yml
- filename: campfiresms-com-webhooks-api-openapi.yml
  format: yaml
  label: Campfire SMS Webhooks API
  slug: campfiresms-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campfiresms-com/openapi/campfiresms-com-webhooks-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: telecommunications providers deliver your originating phone number, message body, message identifier, and related delivery data to Campfire SMS
  - category: contact
    text: If you email us, we receive your email address and the contents of your request.
  - category: identifying
    text: Account information , such as your verified phone number, a salted hash of your PIN, installation records, and message balance, is kept while your account is open.
  - category: financial
    text: Payment records are held by our payment processor, Stripe, and kept as long as tax and accounting law requires.
  - category: communication
    text: 'Your replies: the text of each SMS you send to Campfire SMS, its message ID, and the time it was received.'
  deletion:
    route: email support request
    text: You may request access to, correction of, or deletion of your personal information by emailing us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate messaging service
    text: We use information to operate the messaging service, authenticate and route messages, deliver conversational replies and task notifications, suppress duplicate processing, troubleshoot failures, prevent abuse, comply with law, and respond to support requests.
  - purpose: connected AI service operation
    text: We share information with the AI services you choose to connect, as described under Connected AI services .
  retention:
  - period: seven days
    scope: Incoming SMS awaiting agent
    text: Incoming SMS messages waiting for your agent are deleted automatically seven days after we receive them.
  - period: null
    scope: Account information
    text: Account information , such as your verified phone number, a salted hash of your PIN, installation records, and message balance, is kept while your account is open.
  - period: 30 days
    scope: Account deletion
    text: If you ask us to delete your account, we delete it within 30 days.
  - period: null
    scope: Opt-in and opt-out records
    text: Opt-in and opt-out records (your phone number and its START or STOP status) are kept for as long as we operate the SMS program, including after account deletion, so that an opt-out is always honored.
  rights:
  - right: access
    text: You may request access to, correction of, or deletion of your personal information by emailing us.
  - right: correction
    text: You may request access to, correction of, or deletion of your personal information by emailing us.
  - right: deletion
    text: You may request access to, correction of, or deletion of your personal information by emailing us.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Campfire SMS does not sell or share mobile phone numbers, SMS opt-in data, or text-messaging consent with third parties or affiliates for their marketing or promotional purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Campfire SMS
provenance_date: '2026-11-09'
provider_name: Campfire SMS
provider_slug: campfiresms-com
slug: campfiresms-com-privacy-policy
source_date: '2026-11-09'
source_filename: campfiresms-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://campfiresms.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Campfire SMS\naid: campfiresms-com\nurl: https://campfiresms.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: telecommunications providers deliver your originating phone number, message body, message identifier, and\n    related delivery data to Campfire SMS\n- category: contact\n  text: If you email us, we receive your email address and the contents of your request.\n- category: identifying\n  text: Account information , such as your verified phone number, a salted hash of your PIN, installation records,\n    and message balance,\
  \ is kept while your account is open.\n- category: financial\n  text: Payment records are held by our payment processor, Stripe, and kept as long as tax and accounting law requires.\n- category: communication\n  text: 'Your replies: the text of each SMS you send to Campfire SMS, its message ID, and the time it was received.'\npurposes:\n- purpose: operate messaging service\n  text: We use information to operate the messaging service, authenticate and route messages, deliver conversational\n    replies and task notifications, suppress duplicate processing, troubleshoot failures, prevent abuse, comply\n    with law, and respond to support requests.\n- purpose: connected AI service operation\n  text: We share information with the AI services you choose to connect, as described under Connected AI services\n    .\nretention:\n- scope: Incoming SMS awaiting agent\n  period: seven days\n  text: Incoming SMS messages waiting for your agent are deleted automatically seven days after we receive\
  \ them.\n- scope: Account information\n  period: null\n  text: Account information , such as your verified phone number, a salted hash of your PIN, installation records,\n    and message balance, is kept while your account is open.\n- scope: Account deletion\n  period: 30 days\n  text: If you ask us to delete your account, we delete it within 30 days.\n- scope: Opt-in and opt-out records\n  period: null\n  text: Opt-in and opt-out records (your phone number and its START or STOP status) are kept for as long as we operate\n    the SMS program, including after account deletion, so that an opt-out is always honored.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support request\n  text: You may request access to, correction of, or deletion of your personal information by emailing us.\nrights:\n- right: access\n  text: You may request access to, correction of, or deletion of your personal\
  \ information by emailing us.\n- right: correction\n  text: You may request access to, correction of, or deletion of your personal information by emailing us.\n- right: deletion\n  text: You may request access to, correction of, or deletion of your personal information by emailing us.\nsale_or_sharing:\n  stance: prohibited\n  text: Campfire SMS does not sell or share mobile phone numbers, SMS opt-in data, or text-messaging consent with\n    third parties or affiliates for their marketing or promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/campfiresms-com/privacy/campfiresms-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Campfire SMS's own page on 2026-11-09.
synthetic: false
tags:
- SMS
- Artificial Intelligence
- Automation
- Messaging
- Integration
---
