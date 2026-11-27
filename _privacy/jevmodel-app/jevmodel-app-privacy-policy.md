---
api_specs:
- filename: jevmodel-app-openapi-generated.yml
  format: yaml
  label: JevModel API
  slug: jevmodel-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jevmodel-app/openapi/_ae-authored/jevmodel-app-openapi-generated.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, the site stores your name, email address, authentication records, and email-verification state.
  - category: behavioral
    text: The workbench stores each successful run's state, question configuration, model answers, usage data, and time under your account.
  - category: device
    text: Session and locale cookies keep you signed in and preserve your language choice.
  deletion:
    route: In the workbench, delete one run or clear all saved runs
    text: You can delete one run or clear all saved runs in the workbench.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account sign-in and security
    text: Session and locale cookies keep you signed in and preserve your language choice.
  - purpose: Enforce site capacity and trial limits
    text: It also keeps daily counters to enforce site capacity and the no-signup trial limit (anonymous visitors are counted by a salted hash of their IP address)
  - purpose: Website usage measurement
    text: When configured, Google Analytics 4 measures site usage, Plausible Community Edition measures page visits, referral sources and aggregate usage, and Microsoft Clarity provides heatmaps and session recordings.
  retention:
  - period: 30 days
    scope: Saved runs
    text: The workbench shows at most your latest 100 successful runs from the previous 30 days.
  - period: null
    scope: Older records
    text: A daily cleanup removes older records.
  - period: null
    scope: Account records
    text: Account records and required security records may remain while your account is active.
  rights:
  - right: Edit account details
    text: You can edit basic account details in settings
  - right: Request help with data
    text: use the account support area to request help with your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: JevModel
provenance_date: '2026-11-09'
provider_name: JevModel
provider_slug: jevmodel-app
slug: jevmodel-app-privacy-policy
source_date: '2026-11-09'
source_filename: jevmodel-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jevmodel.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: JevModel\naid: jevmodel-app\nurl: https://jevmodel.app/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, the site stores your name, email address, authentication records, and email-verification\n    state.\n- category: behavioral\n  text: The workbench stores each successful run's state, question configuration, model answers, usage data, and\n    time under your account.\n- category: device\n  text: Session and locale cookies keep you signed in and preserve your language choice.\npurposes:\n- purpose:\
  \ Account sign-in and security\n  text: Session and locale cookies keep you signed in and preserve your language choice.\n- purpose: Enforce site capacity and trial limits\n  text: It also keeps daily counters to enforce site capacity and the no-signup trial limit (anonymous visitors\n    are counted by a salted hash of their IP address)\n- purpose: Website usage measurement\n  text: When configured, Google Analytics 4 measures site usage, Plausible Community Edition measures page visits,\n    referral sources and aggregate usage, and Microsoft Clarity provides heatmaps and session recordings.\nretention:\n- scope: Saved runs\n  period: 30 days\n  text: The workbench shows at most your latest 100 successful runs from the previous 30 days.\n- scope: Older records\n  period: null\n  text: A daily cleanup removes older records.\n- scope: Account records\n  period: null\n  text: Account records and required security records may remain while your account is active.\nresidency: []\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In the workbench, delete one run or clear all saved runs\n  text: You can delete one run or clear all saved runs in the workbench.\nrights:\n- right: Edit account details\n  text: You can edit basic account details in settings\n- right: Request help with data\n  text: use the account support area to request help with your data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jevmodel-app/privacy/jevmodel-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 12 quoted statements, read from JevModel's own page on 2026-11-09.
synthetic: false
tags:
- Decision API
- Content Moderation
- Spam Filtering
- Support Triage
- Ticket Routing
- Language Detection
- Personal Data Screening
---
