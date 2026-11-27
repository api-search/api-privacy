---
api_specs:
- filename: thread-page-endpoint-urls-api-openapi.yml
  format: yaml
  label: ThreadPage Endpoint URLs API
  slug: thread-page-endpoint-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-endpoint-urls-api-openapi.yml
- filename: thread-page-events-api-openapi.yml
  format: yaml
  label: ThreadPage Events API
  slug: thread-page-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-events-api-openapi.yml
- filename: thread-page-integration-api-api-openapi.yml
  format: yaml
  label: ThreadPage Integration API
  slug: thread-page-integration-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-integration-api-api-openapi.yml
- filename: thread-page-requests-api-openapi.yml
  format: yaml
  label: ThreadPage Requests API
  slug: thread-page-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thread-page/openapi/thread-page-requests-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: Email, account ID, optional display name, password hash for password login
  - category: location
    text: an approximate location (country, region and city) worked out from your IP address
  deletion:
    route: contact us
    text: Contact us to request deletion; locating a pseudonymous record may require limited additional information.
  dpa:
    available: true
    text: where data-protection law requires a separate written agreement, we sign one with you on our standard terms on request
    url: null
  purposes:
  - purpose: Create an account, provide requested features and answer service questions
    text: Create an account, provide requested features and answer service questions
  - purpose: Send emails about your account and plan
    text: 'Send emails about your account and plan: sign-in codes, a welcome when you create an account, plan confirmations, renewal reminders, notices when Pro is cancelled or ends, and legal notices'
  residency:
  - region: Ukraine
    text: Our operator is registered in and works from Ukraine
  retention:
  - period: up to a year
    scope: analytics identifiers in browser storage and cookie
    text: Analytics keep their identifiers in your browser’s storage and in a cookie of thread.page, kept for up to a year.
  - period: an hour or a day
    scope: rate-limit counters
    text: Rate-limit counters hold a keyed digest of your network address and a keyed fingerprint of the email address, deleted soon after they expire (an hour or a day).
  - period: up to 5 minutes
    scope: Amazon Bedrock request start data
    text: To answer the steps of one edit faster, Amazon Bedrock can keep the start of a request on the server that processed it, for up to 5 minutes after the edit's last request.
  rights:
  - right: object
    text: you can object as described in section 11
  role:
    text: We are the controller of personal data that we process for our own purposes
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, share it for cross-context behavioural advertising
  subprocessors:
    text: Depending on the feature used, these providers receive information
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ThreadPage
provenance_date: '2026-11-10'
provider_name: ThreadPage
provider_slug: thread-page
slug: thread-page-privacy-policy
source_date: '2026-11-10'
source_filename: thread-page-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thread.page/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ThreadPage\naid: thread-page\nurl: https://thread.page/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: We are the controller of personal data that we process for our own purposes\ndata_categories:\n- category: contact\n  text: Email, account ID, optional display name, password hash for password login\n- category: location\n  text: an approximate location (country, region and city) worked out from your IP address\npurposes:\n- purpose: Create an account, provide requested features and answer service questions\n  text: Create an account, provide requested features and answer\
  \ service questions\n- purpose: Send emails about your account and plan\n  text: 'Send emails about your account and plan: sign-in codes, a welcome when you create an account, plan confirmations,\n    renewal reminders, notices when Pro is cancelled or ends, and legal notices'\nretention:\n- scope: analytics identifiers in browser storage and cookie\n  period: up to a year\n  text: Analytics keep their identifiers in your browser’s storage and in a cookie of thread.page, kept for up to\n    a year.\n- scope: rate-limit counters\n  period: an hour or a day\n  text: Rate-limit counters hold a keyed digest of your network address and a keyed fingerprint of the email address,\n    deleted soon after they expire (an hour or a day).\n- scope: Amazon Bedrock request start data\n  period: up to 5 minutes\n  text: To answer the steps of one edit faster, Amazon Bedrock can keep the start of a request on the server that\n    processed it, for up to 5 minutes after the edit's last request.\nresidency:\n\
  - region: Ukraine\n  text: Our operator is registered in and works from Ukraine\ntransfers: []\nsubprocessors:\n  url: null\n  text: Depending on the feature used, these providers receive information\ndpa:\n  available: true\n  url: null\n  text: where data-protection law requires a separate written agreement, we sign one with you on our standard terms\n    on request\ndeletion:\n  route: contact us\n  text: Contact us to request deletion; locating a pseudonymous record may require limited additional information.\nrights:\n- right: object\n  text: you can object as described in section 11\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, share it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/thread-page/privacy/thread-page-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from ThreadPage's own page on 2026-11-10.
synthetic: false
tags:
- Notes
- Collaboration
- Productivity
- Artificial Intelligence
- Web App
---
