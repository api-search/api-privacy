---
api_specs:
- filename: grabmail-io-account-api-openapi.yml
  format: yaml
  label: grabmail-io Account API
  slug: grabmail-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabmail-io/openapi/grabmail-io-account-api-openapi.yml
- filename: grabmail-io-mailbox-api-openapi.yml
  format: yaml
  label: grabmail-io Mailbox API
  slug: grabmail-io-mailbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabmail-io/openapi/grabmail-io-mailbox-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, a hash of your password, your sessions and API keys and, unless you turn it off, the list of inboxes you open while signed in
  - category: communication
    text: The whole message, including headers and attachments, for 5 days. Then it is deleted.
  - category: device
    text: Kept with the message, because it is part of the message and because abuse reports are unanswerable without it.
  deletion:
    route: Delete the message from the inbox or through the API
    text: Delete the message, from the inbox or through the API. It is gone, and it was going anyway within 5 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: keeping the service running and handling abuse
    text: They are used for keeping the service running and for handling abuse, and for nothing else.
  retention:
  - period: 5 days
    scope: messages sent to address
    text: The whole message, including headers and attachments, for 5 days. Then it is deleted.
  - period: null
    scope: server logs
    text: Logs are short-lived and rotated.
  - period: for as long as the subscription lasts
    scope: custom domain records
    text: The domain, its key and its billing record, for as long as the subscription lasts.
  rights:
  - right: access
    text: Open the mailbox. Everything we hold about a public address is on that page
  - right: erasure
    text: Delete the message, from the inbox or through the API.
  - right: correction
    text: 'Not applicable to received mail: we would be altering a message someone else sent you.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: no data sold or shared with a broker
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: grabmail-io
provenance_date: '2026-11-09'
provider_name: grabmail-io
provider_slug: grabmail-io
slug: grabmail-io-privacy-policy
source_date: '2026-11-09'
source_filename: grabmail-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://grabmail.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: grabmail-io\naid: grabmail-io\nurl: https://grabmail.io/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address, a hash of your password, your sessions and API keys and, unless you turn it off, the\n    list of inboxes you open while signed in\n- category: communication\n  text: The whole message, including headers and attachments, for 5 days. Then it is deleted.\n- category: device\n  text: Kept with the message, because it is part of the message and because abuse reports are unanswerable without\n    it.\npurposes:\n\
  - purpose: keeping the service running and handling abuse\n  text: They are used for keeping the service running and for handling abuse, and for nothing else.\nretention:\n- scope: messages sent to address\n  period: 5 days\n  text: The whole message, including headers and attachments, for 5 days. Then it is deleted.\n- scope: server logs\n  period: null\n  text: Logs are short-lived and rotated.\n- scope: custom domain records\n  period: for as long as the subscription lasts\n  text: The domain, its key and its billing record, for as long as the subscription lasts.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the message from the inbox or through the API\n  text: Delete the message, from the inbox or through the API. It is gone, and it was going anyway within 5 days.\nrights:\n- right: access\n  text: Open the mailbox. Everything we hold about a public address is on that page\n\
  - right: erasure\n  text: Delete the message, from the inbox or through the API.\n- right: correction\n  text: 'Not applicable to received mail: we would be altering a message someone else sent you.'\nsale_or_sharing:\n  stance: prohibited\n  text: no data sold or shared with a broker\n"
source_yaml_url: https://artifacts.apis.io/grabmail-io/privacy/grabmail-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from grabmail-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Developer Tools
---
