---
api_specs:
- filename: n0t1fy-dev-health-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Health API
  slug: n0t1fy-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-health-api-openapi.yml
- filename: n0t1fy-dev-keys-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Keys API
  slug: n0t1fy-dev-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-keys-api-openapi.yml
- filename: n0t1fy-dev-messages-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Messages API
  slug: n0t1fy-dev-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-messages-api-openapi.yml
- filename: n0t1fy-dev-verifications-api-openapi.yml
  format: yaml
  label: n0t1fy-dev Verifications API
  slug: n0t1fy-dev-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/n0t1fy-dev/openapi/n0t1fy-dev-verifications-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Recipient phone number
  - category: communication
    text: Message text
  - category: identifying
    text: 'Your sign-in identity: the verified email address and the account id that GitHub or Google gives us when you sign in.'
  - category: device
    text: The internet address your requests come from is used only in memory
  deletion:
    route: Write to us from the email address you sign in with
    text: Write to us from the email address you sign in with, so we know the request is yours, and we delete your account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver messages
    text: To deliver the message and answer status questions
  - purpose: verification
    text: To check a code NOTIFY made, and to answer questions about a check
  - purpose: team alerts
    text: To send the alerts the person agreed to receive, and to tell your team apart
  - purpose: support
    text: We use the email address for support and service notices only.
  retention:
  - period: until you delete your account
    scope: recipient phone number
    text: Kept with the message record until you delete your account
  - period: 30 days
    scope: message text
    text: Encrypted at rest and erased after 30 days
  - period: 30 days
    scope: verification record
    text: Deleted after 30 days
  - period: 30 days
    scope: sessions
    text: A session ends when you sign out, or after 30 days.
  - period: 14 days
    scope: database backups
    text: Each copy is encrypted before it leaves our servers and is deleted within 14 days.
  role:
    text: 'Two roles matter here: you are responsible for the recipients you choose to message, and we process those messages on your behalf.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not use your message content for advertising or for training machine-learning models.
  subprocessors:
    text: GoSMS.ge , our Georgian delivery provider, receives the recipient number and the message text, a verification code included, because it delivers the message. Railway runs our servers and our database.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: n0t1fy-dev
provenance_date: '2026-11-10'
provider_name: n0t1fy-dev
provider_slug: n0t1fy-dev
slug: n0t1fy-dev-privacy-policy
source_date: '2026-11-10'
source_filename: n0t1fy-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://n0t1fy.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: n0t1fy-dev\naid: n0t1fy-dev\nurl: https://n0t1fy.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Two roles matter here: you are responsible for the recipients you choose to message, and we process those\n    messages on your behalf.'\ndata_categories:\n- category: contact\n  text: Recipient phone number\n- category: communication\n  text: Message text\n- category: identifying\n  text: 'Your sign-in identity: the verified email address and the account id that GitHub or Google gives us when\n    you sign in.'\n- category: device\n  text: The internet address your requests come from is\
  \ used only in memory\npurposes:\n- purpose: deliver messages\n  text: To deliver the message and answer status questions\n- purpose: verification\n  text: To check a code NOTIFY made, and to answer questions about a check\n- purpose: team alerts\n  text: To send the alerts the person agreed to receive, and to tell your team apart\n- purpose: support\n  text: We use the email address for support and service notices only.\nretention:\n- scope: recipient phone number\n  period: until you delete your account\n  text: Kept with the message record until you delete your account\n- scope: message text\n  period: 30 days\n  text: Encrypted at rest and erased after 30 days\n- scope: verification record\n  period: 30 days\n  text: Deleted after 30 days\n- scope: sessions\n  period: 30 days\n  text: A session ends when you sign out, or after 30 days.\n- scope: database backups\n  period: 14 days\n  text: Each copy is encrypted before it leaves our servers and is deleted within 14 days.\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: GoSMS.ge , our Georgian delivery provider, receives the recipient number and the message text, a verification\n    code included, because it delivers the message. Railway runs our servers and our database.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to us from the email address you sign in with\n  text: Write to us from the email address you sign in with, so we know the request is yours, and we delete your\n    account\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not use your message content for advertising or for training machine-learning\n    models.\n"
source_yaml_url: https://artifacts.apis.io/n0t1fy-dev/privacy/n0t1fy-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 17 quoted statements, read from n0t1fy-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Georgia
- Transactional
---
