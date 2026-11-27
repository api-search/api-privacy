---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data (email, name, organization), inbound and outbound message content, customer-supplied contact-form data, and standard server logs (IP, user agent, timestamp).
  - category: device
    text: When a device is registered for push notifications, we also keep a push token and a short label for each device
  - category: device
    text: an identifier that the device gives only to apps from us (on Android, the ANDROID_ID; on iPhone, Apple's identifier for vendor)
  - category: communication
    text: inbound and outbound message content
  deletion:
    route: Delete your account from settings
    text: You can export your data on request and delete your account from settings at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and run the service
    text: We share data only with service providers that help us run AcornReply
  - purpose: Identify and provision accounts via sign-in
    text: We request the minimum profile scopes ( openid , email , and profile ) to identify you and provision your account.
  - purpose: Push notifications
    text: A notification carries a short summary, such as the customer's name and the message subject, and is delivered through the push service of Apple, Google, or your browser's maker.
  - purpose: AI drafting of replies
    text: Anthropic / OpenAI (AI drafting)
  residency:
  - region: United States
    text: AcornReply runs on infrastructure in the United States.
  retention:
  - period: as long as your account is active
    scope: Conversation data
    text: Conversation data is retained for as long as your account is active.
  - period: 30 days
    scope: Deleted accounts and conversation history
    text: Deleted accounts and their conversation history are purged within 30 days.
  - period: rolling 30-day cycle
    scope: Backups
    text: backups are overwritten on a rolling 30-day cycle
  - period: 7 days
    scope: Session cookie
    text: Your browser keeps it for 7 days.
  rights:
  - right: Export data
    text: You can export your data on request
  - right: Delete account
    text: delete your account from settings at any time
  - right: Opt out of product updates
    text: You can opt out of product updates at any time using the unsubscribe link in any email or from your account settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data.
  subprocessors:
    text: 'We share data only with service providers that help us run AcornReply: Postmark (email delivery), Cloudflare Turnstile (bot protection on public contact forms), Neon (database hosting), Railway (application hosting), Cloudflare R2 (storage for attachments and images), Sentry (error monitoring for our servers and web app), Anthropic / OpenAI (AI drafting), Apple (Sign in with Apple and push notification delivery), and Google (Google sign-in, and push notification delivery to the Android app through Firebase Cloud Messaging).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AcornReply
provenance_date: '2026-11-09'
provider_name: AcornReply
provider_slug: acornreply-com
slug: acornreply-com-privacy-policy
source_date: '2026-11-09'
source_filename: acornreply-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://acornreply.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AcornReply\naid: acornreply-com\nurl: https://acornreply.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data (email, name, organization), inbound and outbound message content, customer-supplied contact-form\n    data, and standard server logs (IP, user agent, timestamp).\n- category: device\n  text: When a device is registered for push notifications, we also keep a push token and a short label for each\n    device\n- category: device\n  text: an identifier that the device gives only to apps from us (on Android, the\
  \ ANDROID_ID; on iPhone, Apple's\n    identifier for vendor)\n- category: communication\n  text: inbound and outbound message content\npurposes:\n- purpose: Provide and run the service\n  text: We share data only with service providers that help us run AcornReply\n- purpose: Identify and provision accounts via sign-in\n  text: We request the minimum profile scopes ( openid , email , and profile ) to identify you and provision your\n    account.\n- purpose: Push notifications\n  text: A notification carries a short summary, such as the customer's name and the message subject, and is delivered\n    through the push service of Apple, Google, or your browser's maker.\n- purpose: AI drafting of replies\n  text: Anthropic / OpenAI (AI drafting)\nretention:\n- scope: Conversation data\n  period: as long as your account is active\n  text: Conversation data is retained for as long as your account is active.\n- scope: Deleted accounts and conversation history\n  period: 30 days\n  text: Deleted\
  \ accounts and their conversation history are purged within 30 days.\n- scope: Backups\n  period: rolling 30-day cycle\n  text: backups are overwritten on a rolling 30-day cycle\n- scope: Session cookie\n  period: 7 days\n  text: Your browser keeps it for 7 days.\nresidency:\n- region: United States\n  text: AcornReply runs on infrastructure in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data only with service providers that help us run AcornReply: Postmark (email delivery), Cloudflare\n    Turnstile (bot protection on public contact forms), Neon (database hosting), Railway (application hosting),\n    Cloudflare R2 (storage for attachments and images), Sentry (error monitoring for our servers and web app), Anthropic\n    / OpenAI (AI drafting), Apple (Sign in with Apple and push notification delivery), and Google (Google sign-in,\n    and push notification delivery to the Android app through Firebase Cloud Messaging).'\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: Delete your account from settings\n  text: You can export your data on request and delete your account from settings at any time.\nrights:\n- right: Export data\n  text: You can export your data on request\n- right: Delete account\n  text: delete your account from settings at any time\n- right: Opt out of product updates\n  text: You can opt out of product updates at any time using the unsubscribe link in any email or from your account\n    settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your data.\n"
source_yaml_url: https://artifacts.apis.io/acornreply-com/privacy/acornreply-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AcornReply's own page on 2026-11-09.
synthetic: false
tags:
- Support
- Software-as-a-Service
- Small Teams
- Artificial Intelligence
- Customer Service
---
