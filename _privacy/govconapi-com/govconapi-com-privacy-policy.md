---
api_specs:
- filename: govconapi-com-openapi-generated.yml
  format: yaml
  label: govconapi-com API
  slug: govconapi-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/govconapi-com/openapi/_ae-authored/govconapi-com-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: The email address you give when you request a key or subscribe.
  - category: identifying
    text: an internal ID for the key (not the key itself)
  - category: device
    text: the IP address the request came from, and the user agent
  - category: behavioral
    text: a log of your API requests
  - category: financial
    text: Stripe processes paid plans and collects and stores your payment details.
  - category: location
    text: an approximate location derived from your IP address
  - category: communication
    text: it stores any conversation you start so we can reply and follow up
  deletion:
    route: email to privacy contact
    text: 'delete your account: we deactivate your keys, delete your account record, and delete or anonymize your request-log entries.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver keys, billing, abuse prevention, support, API usage
    text: We use it to deliver keys, run billing, prevent abuse, answer support requests and understand how the API is used.
  residency:
  - region: EU
    text: Our application and database are hosted in the EU.
  retention:
  - period: while your account exists
    scope: account records
    text: 'Account records: while your account exists.'
  - period: not deleted on a schedule
    scope: API request logs
    text: 'API request logs: not deleted on a schedule.'
  - period: a rolling schedule of a few months
    scope: backups
    text: 'Backups: encrypted, and kept on a rolling schedule of a few months.'
  rights:
  - right: access
    text: show you the information we hold about you
  - right: correction
    text: correct anything that is wrong
  - right: export
    text: export your account record and the request-log entries tied to it
  - right: deletion
    text: delete your account
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information to these providers or to anyone else.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: govconapi-com
provenance_date: '2026-11-09'
provider_name: govconapi-com
provider_slug: govconapi-com
slug: govconapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: govconapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://govconapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: govconapi-com\naid: govconapi-com\nurl: https://govconapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: The email address you give when you request a key or subscribe.\n- category: identifying\n  text: an internal ID for the key (not the key itself)\n- category: device\n  text: the IP address the request came from, and the user agent\n- category: behavioral\n  text: a log of your API requests\n- category: financial\n  text: Stripe processes paid plans and collects and stores your payment details.\n- category: location\n  text:\
  \ an approximate location derived from your IP address\n- category: communication\n  text: it stores any conversation you start so we can reply and follow up\npurposes:\n- purpose: deliver keys, billing, abuse prevention, support, API usage\n  text: We use it to deliver keys, run billing, prevent abuse, answer support requests and understand how the API\n    is used.\nretention:\n- scope: account records\n  period: while your account exists\n  text: 'Account records: while your account exists.'\n- scope: API request logs\n  period: not deleted on a schedule\n  text: 'API request logs: not deleted on a schedule.'\n- scope: backups\n  period: a rolling schedule of a few months\n  text: 'Backups: encrypted, and kept on a rolling schedule of a few months.'\nresidency:\n- region: EU\n  text: Our application and database are hosted in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to privacy contact\n\
  \  text: 'delete your account: we deactivate your keys, delete your account record, and delete or anonymize your\n    request-log entries.'\nrights:\n- right: access\n  text: show you the information we hold about you\n- right: correction\n  text: correct anything that is wrong\n- right: export\n  text: export your account record and the request-log entries tied to it\n- right: deletion\n  text: delete your account\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information to these providers or to anyone else.\n"
source_yaml_url: https://artifacts.apis.io/govconapi-com/privacy/govconapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from govconapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Federal
- Procurement
- Data
---
