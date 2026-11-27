---
api_specs:
- filename: telegram-bot-info-api-openapi.yml
  format: yaml
  label: Telegram Bot Info API
  slug: telegram-bot-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-bot-info-api-openapi.yml
- filename: telegram-chat-management-api-openapi.yml
  format: yaml
  label: Telegram Chat Management API
  slug: telegram-chat-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-chat-management-api-openapi.yml
- filename: telegram-getting-updates-api-openapi.yml
  format: yaml
  label: Telegram Getting Updates API
  slug: telegram-getting-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-getting-updates-api-openapi.yml
- filename: telegram-invites-api-openapi.yml
  format: yaml
  label: Telegram Invites API
  slug: telegram-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-invites-api-openapi.yml
- filename: telegram-member-management-api-openapi.yml
  format: yaml
  label: Telegram Member Management API
  slug: telegram-member-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-member-management-api-openapi.yml
- filename: telegram-message-editing-api-openapi.yml
  format: yaml
  label: Telegram Message Editing API
  slug: telegram-message-editing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-message-editing-api-openapi.yml
- filename: telegram-messaging-api-openapi.yml
  format: yaml
  label: Telegram Messaging API
  slug: telegram-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-messaging-api-openapi.yml
- filename: telegram-payments-api-openapi.yml
  format: yaml
  label: Telegram Payments API
  slug: telegram-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-payments-api-openapi.yml
- filename: telegram-stickers-api-openapi.yml
  format: yaml
  label: Telegram Stickers API
  slug: telegram-stickers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/telegram/openapi/telegram-stickers-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: You provide your mobile number and basic account data (which may include profile name, profile picture and about information) to create a Telegram account.
  - category: identifying
    text: the screen name you choose, your profile pictures, and your username (should you choose to set one) on Telegram are always public
  - category: contact
    text: We only need the number and name (first and last) for this to work and store no other data about your contacts.
  - category: location
    text: If you share your Live Location in any chat or turn on ’Make Myself Visible’ in People Nearby , Telegram will use your data to display your location to those users with whom you are sharing it
  - category: device
    text: we may collect metadata such as your IP address, devices and Telegram apps you've used, history of username changes, etc.
  - category: behavioral
    text: we calculate a rating that shows which people you message frequently
  - category: financial
    text: Telegram does not process payments from users and instead relies on different payment providers around the world.
  deletion:
    route: Deactivation page or Settings > Privacy & Security > Data Settings
    text: If you would like to delete your account, you can do this on the deactivation page .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide cloud messaging services
    text: We will process your data to deliver your cloud chat history, including messages, media and files, to any devices of your choosing
  - purpose: Security and spam prevention
    text: To improve the security of your account, as well as to prevent spam , abuse, and other violations of our Terms of Service, we may collect metadata
  - purpose: Advertising
    text: By default, these sponsored messages are based solely on the topic of the public channels or search terms in which they are shown.
  residency:
  - region: Netherlands
    text: If you signed up for Telegram from the UK or the EEA, your data is stored in data centers in the Netherlands.
  retention:
  - period: 12 months maximum
    scope: Security metadata
    text: If collected, this metadata can be kept for 12 months maximum.
  - period: at least 18 months
    scope: Inactive accounts
    text: By default, if you stop using Telegram and do not come online for at least 18 months, your account will be deleted
  - period: 48 hours after deletion
    scope: Deleted messages in supergroups
    text: deleted messages and original versions of edited messages from supergroups are stored for 48 hours after deletion
  rights:
  - right: Access copy
    text: request a copy of all your personal data that we store and to transmit that copy to another data controller
  - right: Delete or amend
    text: delete (see section 10 below) or amend your personal data
  - right: Restrict or object
    text: restrict, or object to, the processing of your personal data
  - right: Correct
    text: correct any inaccurate or incomplete personal data we hold on you
  - right: Complain
    text: lodge a complaint with national data protection authorities regarding our processing of your personal data
  role:
    text: the data controller responsible for your personal data when you use our Services
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: This will take the form of standard contract clauses approved by the European Commission in an agreement between us and our relevant group companies.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Telegram
provenance_date: '2026-11-10'
provider_name: Telegram
provider_slug: telegram
slug: telegram-privacy-policy
source_date: '2026-11-10'
source_filename: telegram-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://telegram.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Telegram\naid: telegram\nurl: https://telegram.org/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the data controller responsible for your personal data when you use our Services\ndata_categories:\n- category: contact\n  text: You provide your mobile number and basic account data (which may include profile name, profile picture and\n    about information) to create a Telegram account.\n- category: identifying\n  text: the screen name you choose, your profile pictures, and your username (should you choose to set one) on Telegram\n    are always public\n- category: contact\n  text: We\
  \ only need the number and name (first and last) for this to work and store no other data about your contacts.\n- category: location\n  text: If you share your Live Location in any chat or turn on ’Make Myself Visible’ in People Nearby , Telegram\n    will use your data to display your location to those users with whom you are sharing it\n- category: device\n  text: we may collect metadata such as your IP address, devices and Telegram apps you've used, history of username\n    changes, etc.\n- category: behavioral\n  text: we calculate a rating that shows which people you message frequently\n- category: financial\n  text: Telegram does not process payments from users and instead relies on different payment providers around the\n    world.\npurposes:\n- purpose: Provide cloud messaging services\n  text: We will process your data to deliver your cloud chat history, including messages, media and files, to any\n    devices of your choosing\n- purpose: Security and spam prevention\n  text:\
  \ To improve the security of your account, as well as to prevent spam , abuse, and other violations of our\n    Terms of Service, we may collect metadata\n- purpose: Advertising\n  text: By default, these sponsored messages are based solely on the topic of the public channels or search terms\n    in which they are shown.\nretention:\n- scope: Security metadata\n  period: 12 months maximum\n  text: If collected, this metadata can be kept for 12 months maximum.\n- scope: Inactive accounts\n  period: at least 18 months\n  text: By default, if you stop using Telegram and do not come online for at least 18 months, your account will\n    be deleted\n- scope: Deleted messages in supergroups\n  period: 48 hours after deletion\n  text: deleted messages and original versions of edited messages from supergroups are stored for 48 hours after\n    deletion\nresidency:\n- region: Netherlands\n  text: If you signed up for Telegram from the UK or the EEA, your data is stored in data centers in the Netherlands.\n\
  transfers:\n- mechanism: SCC\n  text: This will take the form of standard contract clauses approved by the European Commission in an agreement\n    between us and our relevant group companies.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deactivation page or Settings > Privacy & Security > Data Settings\n  text: If you would like to delete your account, you can do this on the deactivation page .\nrights:\n- right: Access copy\n  text: request a copy of all your personal data that we store and to transmit that copy to another data controller\n- right: Delete or amend\n  text: delete (see section 10 below) or amend your personal data\n- right: Restrict or object\n  text: restrict, or object to, the processing of your personal data\n- right: Correct\n  text: correct any inaccurate or incomplete personal data we hold on you\n- right: Complain\n  text: lodge a complaint with national data protection authorities regarding\
  \ our processing of your personal data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/telegram/privacy/telegram-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from Telegram's own page on 2026-11-10.
synthetic: false
tags:
- Bots
- Chat
- Messaging
- Notification
- Payments
- Telegram
- Social
- Public APIs
- Chatbots
- Webhook
- Mini Apps
---
