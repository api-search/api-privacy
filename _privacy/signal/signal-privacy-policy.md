---
api_specs:
- filename: signal-accounts-api-openapi.yml
  format: yaml
  label: Signal Accounts API
  slug: signal-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-accounts-api-openapi.yml
- filename: signal-attachments-api-openapi.yml
  format: yaml
  label: Signal Attachments API
  slug: signal-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-attachments-api-openapi.yml
- filename: signal-certificates-api-openapi.yml
  format: yaml
  label: Signal Certificates API
  slug: signal-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-certificates-api-openapi.yml
- filename: signal-devices-api-openapi.yml
  format: yaml
  label: Signal Devices API
  slug: signal-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-devices-api-openapi.yml
- filename: signal-keys-api-openapi.yml
  format: yaml
  label: Signal Keys API
  slug: signal-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-keys-api-openapi.yml
- filename: signal-messages-api-openapi.yml
  format: yaml
  label: Signal Messages API
  slug: signal-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-messages-api-openapi.yml
- filename: signal-profiles-api-openapi.yml
  format: yaml
  label: Signal Profiles API
  slug: signal-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-profiles-api-openapi.yml
- filename: signal-registration-api-openapi.yml
  format: yaml
  label: Signal Registration API
  slug: signal-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-registration-api-openapi.yml
- filename: signal-stickers-api-openapi.yml
  format: yaml
  label: Signal Stickers API
  slug: signal-stickers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signal/openapi/signal-stickers-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: You register a phone number when you create a Signal account.
  - category: identifying
    text: You may optionally add other information to your account, such as a profile name and profile picture.
  - category: communication
    text: Signal queues end-to-end encrypted messages on its servers for delivery to devices that are temporarily offline
  - category: device
    text: Additional technical information is stored on our servers, including randomly generated authentication tokens, keys, push tokens, and other material that is necessary to establish calls and transmit messages.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services
    text: Phone numbers are used to provide our Services to you and other Signal users.
  - purpose: user support
    text: If you contact Signal User Support, any personal data you may share with us is kept only for the purposes of researching the issue and contacting you about your case.
  - purpose: contact discovery
    text: Information from the contacts on your device may be cryptographically hashed and transmitted to the server in order to determine which of your contacts are registered.
  - purpose: legal compliance and security
    text: To detect, prevent, or otherwise address fraud, security, or technical issues.
  retention:
  - period: null
    scope: user support data
    text: any personal data you may share with us is kept only for the purposes of researching the issue and contacting you about your case.
  role:
    text: Signal Messenger, LLC
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Signal does not sell, rent or monetize your personal data or content in any way – ever.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: the transfer of your encrypted information and metadata to the United States and other countries where we have or use facilities, service providers or partners.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Signal
provenance_date: '2026-11-10'
provider_name: Signal
provider_slug: signal
slug: signal-privacy-policy
source_date: '2026-11-10'
source_filename: signal-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://signal.org/legal/#privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Signal\naid: signal\nurl: https://signal.org/legal/#privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Signal Messenger, LLC\ndata_categories:\n- category: contact\n  text: You register a phone number when you create a Signal account.\n- category: identifying\n  text: You may optionally add other information to your account, such as a profile name and profile picture.\n- category: communication\n  text: Signal queues end-to-end encrypted messages on its servers for delivery to devices that are temporarily\n    offline\n- category: device\n  text: Additional technical information\
  \ is stored on our servers, including randomly generated authentication tokens,\n    keys, push tokens, and other material that is necessary to establish calls and transmit messages.\npurposes:\n- purpose: provide services\n  text: Phone numbers are used to provide our Services to you and other Signal users.\n- purpose: user support\n  text: If you contact Signal User Support, any personal data you may share with us is kept only for the purposes\n    of researching the issue and contacting you about your case.\n- purpose: contact discovery\n  text: Information from the contacts on your device may be cryptographically hashed and transmitted to the server\n    in order to determine which of your contacts are registered.\n- purpose: legal compliance and security\n  text: To detect, prevent, or otherwise address fraud, security, or technical issues.\nretention:\n- scope: user support data\n  period: null\n  text: any personal data you may share with us is kept only for the purposes of researching\
  \ the issue and contacting\n    you about your case.\nresidency: []\ntransfers:\n- mechanism: other\n  text: the transfer of your encrypted information and metadata to the United States and other countries where we\n    have or use facilities, service providers or partners.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Signal does not sell, rent or monetize your personal data or content in any way – ever.\n"
source_yaml_url: https://artifacts.apis.io/signal/privacy/signal-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- sale_or_sharing
summary_line: 12 quoted statements, read from Signal's own page on 2026-11-10.
synthetic: false
tags:
- Encryption
- Messaging
- Security
- Cryptography
- Open Source
- Privacy
- Real-Time
---
