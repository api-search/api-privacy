---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Accounts keep a user id and an email.
  - category: contact
    text: Whatever you put in the email, plus the usual headers.
  - category: financial
    text: Pro adds a PayPal subscription id and its status. No card numbers, ever.
  - category: device
    text: API calls, account or not IP address (rate and mint limits), a hashed form of the key, the endpoint called, the query string q , and the timestamp.
  - category: behavioral
    text: No catalog browsing profile — the catalog is a public shelf we crawl and publish.
  deletion:
    route: Email
    text: Write to [email protected] from the Gmail on the account and say which — we will confirm what we hold, correct what is wrong, send you a copy, or close the account and retire its keys.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the API
    text: Quota, cache, rate limits, and abuse prevention.
  - purpose: Run your account
    text: Give you a key after Google sign-in, show quota on /account , and keep anonymous, registered, and Pro apart.
  - purpose: Billing
    text: Take $9 when you ask us to. Match the PayPal subscription to the account so Pro quota lands in the right place.
  - purpose: Answer mail
    text: Reply to what you sent and fix what you report.
  residency:
  - region: United States
    text: We and our providers operate infrastructure in more than one country, including the United States.
  retention:
  - period: While the key is usable, plus as long as needed after that to enforce quota and abuse limits.
    scope: Keys and usage lines
    text: While the key is usable, plus as long as needed after that to enforce quota and abuse limits.
  - period: Suggestions about a day, search results minutes.
    scope: Suggestion and search cache
    text: Suggestions about a day, search results minutes.
  - period: last while the account exists
    scope: Accounts
    text: The user id and email last while the account exists.
  - period: while billing needs them
    scope: Billing records
    text: PayPal subscription ids and status while billing needs them, including disputes, refunds, and tax records we are obliged to keep.
  - period: As long as the thread is live, plus a reasonable tail
    scope: Support mail
    text: As long as the thread is live, plus a reasonable tail for follow-ups and debugging the thing you reported.
  rights:
  - right: access
    text: See, fix, export, or delete.
  - right: correction
    text: correct what is wrong
  - right: portability
    text: send you a copy
  - right: objection or restriction
    text: Object or restrict. If you believe a use described here should not apply to you, say so in the same mail and we will consider it and reply.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell personal information and we do not share it for cross-context behavioral advertising
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: By using www.qequals.com or api.qequals.com you understand that transfer happens, under the protections described on this page and in our providers' own terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Qequals
provenance_date: '2026-11-10'
provider_name: Qequals
provider_slug: qequals
slug: qequals-privacy-policy
source_date: '2026-11-10'
source_filename: qequals-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.qequals.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Qequals\naid: qequals\nurl: https://www.qequals.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Accounts keep a user id and an email.\n- category: contact\n  text: Whatever you put in the email, plus the usual headers.\n- category: financial\n  text: Pro adds a PayPal subscription id and its status. No card numbers, ever.\n- category: device\n  text: API calls, account or not IP address (rate and mint limits), a hashed form of the key, the endpoint called,\n    the query string q , and the timestamp.\n- category: behavioral\n\
  \  text: No catalog browsing profile — the catalog is a public shelf we crawl and publish.\npurposes:\n- purpose: Run the API\n  text: Quota, cache, rate limits, and abuse prevention.\n- purpose: Run your account\n  text: Give you a key after Google sign-in, show quota on /account , and keep anonymous, registered, and Pro apart.\n- purpose: Billing\n  text: Take $9 when you ask us to. Match the PayPal subscription to the account so Pro quota lands in the right\n    place.\n- purpose: Answer mail\n  text: Reply to what you sent and fix what you report.\nretention:\n- scope: Keys and usage lines\n  period: While the key is usable, plus as long as needed after that to enforce quota and abuse limits.\n  text: While the key is usable, plus as long as needed after that to enforce quota and abuse limits.\n- scope: Suggestion and search cache\n  period: Suggestions about a day, search results minutes.\n  text: Suggestions about a day, search results minutes.\n- scope: Accounts\n  period: last\
  \ while the account exists\n  text: The user id and email last while the account exists.\n- scope: Billing records\n  period: while billing needs them\n  text: PayPal subscription ids and status while billing needs them, including disputes, refunds, and tax records\n    we are obliged to keep.\n- scope: Support mail\n  period: As long as the thread is live, plus a reasonable tail\n  text: As long as the thread is live, plus a reasonable tail for follow-ups and debugging the thing you reported.\nresidency:\n- region: United States\n  text: We and our providers operate infrastructure in more than one country, including the United States.\ntransfers:\n- mechanism: other\n  text: By using www.qequals.com or api.qequals.com you understand that transfer happens, under the protections\n    described on this page and in our providers' own terms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email\n  text: Write to [email protected]\
  \ from the Gmail on the account and say which — we will confirm what we hold, correct\n    what is wrong, send you a copy, or close the account and retire its keys.\nrights:\n- right: access\n  text: See, fix, export, or delete.\n- right: correction\n  text: correct what is wrong\n- right: portability\n  text: send you a copy\n- right: objection or restriction\n  text: Object or restrict. If you believe a use described here should not apply to you, say so in the same mail\n    and we will consider it and reply.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell personal information and we do not share it for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/qequals/privacy/qequals-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Qequals's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Autocomplete
- SEO
- Data
- Company
---
