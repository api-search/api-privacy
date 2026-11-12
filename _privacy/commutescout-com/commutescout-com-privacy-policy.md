---
api_specs:
- filename: commutescout-com-tools-api-openapi.yml
  format: yaml
  label: CommuteScout Tools API
  slug: commutescout-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commutescout-com/openapi/commutescout-com-tools-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: if you create an account, we store your email and what you save to it (watch areas, places, reports, plugin choices, API keys)
  - category: location
    text: coordinates rounded to about a kilometer
  - category: behavioral
    text: questions you ask the assistant are logged to improve answers, tied to a salted daily hash instead of your address
  - category: device
    text: the push subscription for each device
  - category: contact
    text: the name, email address, and message you type
  - category: communication
    text: the message is delivered to us as email
  deletion:
    route: Delete my account button on the watch page, or email for other requests
    text: delete the whole account with the "Delete my account" button there - that immediately removes the account record
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service and saved features
    text: because that is what those features are
  - purpose: Improve assistant answers
    text: questions you ask the assistant are logged to improve answers
  - purpose: Answer contact messages
    text: We use them to read and answer you, and for nothing else.
  - purpose: Notify pre-launch waitlist members
    text: We use it once, to tell you when Pro launches.
  residency:
  - region: us-west1 (Google Cloud)
    text: Data lives in Google Cloud's us-west1 region.
  retention:
  - period: null
    scope: Account data
    text: Account data stays until you delete it.
  - period: two days
    scope: Reports
    text: Reports are deleted from storage two days after they are posted
  - period: 180 days
    scope: Shared trips
    text: shared trips after 180 days
  - period: about 30 days
    scope: Anonymized question and request logs
    text: Anonymized question logs and request logs age out with normal log retention (about 30 days).
  rights:
  - right: Review and edit watch areas
    text: Signed-in users can see every watch area on the watch page , edit or delete any of them
  - right: Delete account
    text: delete the whole account with the "Delete my account" button there
  - right: Request removal of waitlist email
    text: Ask us at any time to remove it.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: nothing is sold
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CommuteScout
provenance_date: '2026-11-09'
provider_name: CommuteScout
provider_slug: commutescout-com
slug: commutescout-com-privacy-policy
source_date: '2026-11-09'
source_filename: commutescout-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://commutescout.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CommuteScout\naid: commutescout-com\nurl: https://commutescout.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: if you create an account, we store your email and what you save to it (watch areas, places, reports, plugin\n    choices, API keys)\n- category: location\n  text: coordinates rounded to about a kilometer\n- category: behavioral\n  text: questions you ask the assistant are logged to improve answers, tied to a salted daily hash instead of your\n    address\n- category: device\n  text: the push subscription for each device\n\
  - category: contact\n  text: the name, email address, and message you type\n- category: communication\n  text: the message is delivered to us as email\npurposes:\n- purpose: Run the service and saved features\n  text: because that is what those features are\n- purpose: Improve assistant answers\n  text: questions you ask the assistant are logged to improve answers\n- purpose: Answer contact messages\n  text: We use them to read and answer you, and for nothing else.\n- purpose: Notify pre-launch waitlist members\n  text: We use it once, to tell you when Pro launches.\nretention:\n- scope: Account data\n  period: null\n  text: Account data stays until you delete it.\n- scope: Reports\n  period: two days\n  text: Reports are deleted from storage two days after they are posted\n- scope: Shared trips\n  period: 180 days\n  text: shared trips after 180 days\n- scope: Anonymized question and request logs\n  period: about 30 days\n  text: Anonymized question logs and request logs age out with\
  \ normal log retention (about 30 days).\nresidency:\n- region: us-west1 (Google Cloud)\n  text: Data lives in Google Cloud's us-west1 region.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete my account button on the watch page, or email for other requests\n  text: delete the whole account with the \"Delete my account\" button there - that immediately removes the account\n    record\nrights:\n- right: Review and edit watch areas\n  text: Signed-in users can see every watch area on the watch page , edit or delete any of them\n- right: Delete account\n  text: delete the whole account with the \"Delete my account\" button there\n- right: Request removal of waitlist email\n  text: Ask us at any time to remove it.\nsale_or_sharing:\n  stance: prohibited\n  text: nothing is sold\n"
source_yaml_url: https://artifacts.apis.io/commutescout-com/privacy/commutescout-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from CommuteScout's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Traffic
- Road Conditions
- Transportation
- Navigation
- Route Planning
- Maps
- MCP
- Open Source
---
