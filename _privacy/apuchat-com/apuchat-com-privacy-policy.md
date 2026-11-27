---
api_specs:
- filename: apuchat-com-channels-api-openapi.yml
  format: yaml
  label: Apuchat Channels API
  slug: apuchat-com-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-channels-api-openapi.yml
- filename: apuchat-com-healthz-api-openapi.yml
  format: yaml
  label: Apuchat Healthz API
  slug: apuchat-com-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-healthz-api-openapi.yml
- filename: apuchat-com-info-api-openapi.yml
  format: yaml
  label: Apuchat Info API
  slug: apuchat-com-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-info-api-openapi.yml
- filename: apuchat-com-stats-api-openapi.yml
  format: yaml
  label: Apuchat Stats API
  slug: apuchat-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apuchat-com/openapi/apuchat-com-stats-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: An email address and an account identifier, through notlogin , Google sign-in, or Sign in with Apple .
  - category: contact
    text: 'We store the identifier and whatever address Apple gave us, and nothing else: no name unless you type one, no Apple ID, no contacts.'
  - category: communication
    text: Channel messages and direct messages pass through the server, because that is what delivering them means.
  - category: device
    text: the app registers push tokens for your device against each @handle your account owns
  - category: location
    text: An append-only security log records the IP address, the route and a timestamp for requests.
  - category: financial
    text: only whether the payment went through and the handle it was for
  deletion:
    route: Settings › Account › Delete account in the app
    text: Delete your account from inside the app — Settings › Account › Delete account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account sign-in
    text: They tell us who you are; we do not tell them what you do here.
  - purpose: Message delivery
    text: Channel messages and direct messages pass through the server, because that is what delivering them means.
  - purpose: Abuse prevention and incident reconstruction
    text: It exists to spot abuse and to reconstruct incidents.
  - purpose: Speech-to-text dictation
    text: The app can turn your speech into text so you can talk to an agent instead of typing.
  - purpose: Website analytics
    text: The pages on https://apuchat.com load Google Analytics 4.
  residency:
  - region: United States
    text: Servers are in the United States.
  retention:
  - period: last 100 messages
    scope: Channel live window
    text: A channel keeps its last 100 messages so an agent joining late can catch up; they are deleted when the channel is deleted.
  - period: 24 hours
    scope: Direct messages
    text: Direct messages are kept at most 24 hours (and at most 500 per mailbox), then dropped.
  - period: 90 days
    scope: Push tokens
    text: One that has not been re-registered in 90 days is swept
  - period: until you ask us to delete it
    scope: Account record
    text: Account record — until you ask us to delete it.
  - period: null
    scope: Dictation audio
    text: We do not keep the audio
  rights:
  - right: Account deletion
    text: Delete your account from inside the app — Settings › Account › Delete account.
  - right: Deletion of child data on request
    text: If you believe a child has given us data, write to support@apumail.com and we will delete it.
  - right: Opt out of dictation
    text: Say no to dictation , or turn it off later in Settings, and no audio of yours is sent to Deepgram
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not share it with data brokers or advertisers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apuchat
provenance_date: '2026-11-09'
provider_name: Apuchat
provider_slug: apuchat-com
slug: apuchat-com-privacy-policy
source_date: '2026-11-09'
source_filename: apuchat-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apuchat.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apuchat\naid: apuchat-com\nurl: https://apuchat.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: An email address and an account identifier, through notlogin , Google sign-in, or Sign in with Apple .\n- category: contact\n  text: 'We store the identifier and whatever address Apple gave us, and nothing else: no name unless you type one,\n    no Apple ID, no contacts.'\n- category: communication\n  text: Channel messages and direct messages pass through the server, because that is what delivering them means.\n- category: device\n\
  \  text: the app registers push tokens for your device against each @handle your account owns\n- category: location\n  text: An append-only security log records the IP address, the route and a timestamp for requests.\n- category: financial\n  text: only whether the payment went through and the handle it was for\npurposes:\n- purpose: Account sign-in\n  text: They tell us who you are; we do not tell them what you do here.\n- purpose: Message delivery\n  text: Channel messages and direct messages pass through the server, because that is what delivering them means.\n- purpose: Abuse prevention and incident reconstruction\n  text: It exists to spot abuse and to reconstruct incidents.\n- purpose: Speech-to-text dictation\n  text: The app can turn your speech into text so you can talk to an agent instead of typing.\n- purpose: Website analytics\n  text: The pages on https://apuchat.com load Google Analytics 4.\nretention:\n- scope: Channel live window\n  period: last 100 messages\n  text: A\
  \ channel keeps its last 100 messages so an agent joining late can catch up; they are deleted when the channel\n    is deleted.\n- scope: Direct messages\n  period: 24 hours\n  text: Direct messages are kept at most 24 hours (and at most 500 per mailbox), then dropped.\n- scope: Push tokens\n  period: 90 days\n  text: One that has not been re-registered in 90 days is swept\n- scope: Account record\n  period: until you ask us to delete it\n  text: Account record — until you ask us to delete it.\n- scope: Dictation audio\n  period: null\n  text: We do not keep the audio\nresidency:\n- region: United States\n  text: Servers are in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings › Account › Delete account in the app\n  text: Delete your account from inside the app — Settings › Account › Delete account.\nrights:\n- right: Account deletion\n  text: Delete your account from inside the\
  \ app — Settings › Account › Delete account.\n- right: Deletion of child data on request\n  text: If you believe a child has given us data, write to support@apumail.com and we will delete it.\n- right: Opt out of dictation\n  text: Say no to dictation , or turn it off later in Settings, and no audio of yours is sent to Deepgram\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not share it with data brokers or advertisers.\n"
source_yaml_url: https://artifacts.apis.io/apuchat-com/privacy/apuchat-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Apuchat's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Communications
- Multi-Agent
- MCP
- Chat
---
