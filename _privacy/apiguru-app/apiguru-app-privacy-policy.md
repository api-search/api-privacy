---
api_specs:
- filename: apiguru-app-amazon-data-api-openapi.yml
  format: yaml
  label: apiguru-app Amazon Data API
  slug: apiguru-app-amazon-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apiguru-app/openapi/apiguru-app-amazon-data-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address
  - category: identifying
    text: if you sign in with Google — your Google account identifier
  - category: device
    text: We record the IP address you registered from, the country derived from it, and where you arrived from (referrer or campaign)
  - category: financial
    text: We keep the Stripe customer and subscription identifiers, your balance, your plan and your usage counts.
  - category: behavioral
    text: Microsoft Clarity — heatmaps and session recordings of how pages are used.
  - category: communication
    text: 'If you email us or use the feedback wall: what you write.'
  deletion:
    route: email request to [email protected]
    text: Write to [email protected] from the address on the account and you can get a copy of what we hold, have it corrected, have the account and its data deleted, or object to the analytics above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing and usage
    text: We need this to bill correctly, to show you your own usage, and to investigate abuse and outages.
  - purpose: abuse prevention
    text: to tell real signups from automated ones.
  - purpose: advertising measurement
    text: so we know which ads bring people who actually use the API
  residency:
  - region: Germany
    text: Our servers are in Germany (Hetzner).
  - region: United States
    text: Some processors above operate in the United States, so data reaches them there.
  retention:
  - period: until you ask us to delete the account
    scope: account records
    text: 'Account records: until you ask us to delete the account.'
  - period: while they are useful for billing disputes, usage reporting and abuse investigation
    scope: API request logs
    text: 'API request logs: kept while they are useful for billing disputes, usage reporting and abuse investigation, then removed.'
  - period: until you ask us to remove them
    scope: feedback wall entries
    text: 'Feedback wall entries: kept until you ask us to remove them.'
  - period: with the campaign record
    scope: email tracking
    text: 'Email tracking: kept with the campaign record.'
  rights:
  - right: access
    text: get a copy of what we hold
  - right: correction
    text: have it corrected
  - right: deletion
    text: have the account and its data deleted
  - right: objection
    text: object to the analytics above
  - right: complain to data protection authority
    text: If you are in the EEA or the UK you also have the right to complain to your data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell personal data to anyone
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: apiguru-app
provenance_date: '2026-11-09'
provider_name: apiguru-app
provider_slug: apiguru-app
slug: apiguru-app-privacy-policy
source_date: '2026-11-09'
source_filename: apiguru-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dash.apiguru.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apiguru-app\naid: apiguru-app\nurl: https://dash.apiguru.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email address\n- category: identifying\n  text: if you sign in with Google — your Google account identifier\n- category: device\n  text: We record the IP address you registered from, the country derived from it, and where you arrived from (referrer\n    or campaign)\n- category: financial\n  text: We keep the Stripe customer and subscription identifiers, your balance, your plan and your usage counts.\n- category: behavioral\n\
  \  text: Microsoft Clarity — heatmaps and session recordings of how pages are used.\n- category: communication\n  text: 'If you email us or use the feedback wall: what you write.'\npurposes:\n- purpose: billing and usage\n  text: We need this to bill correctly, to show you your own usage, and to investigate abuse and outages.\n- purpose: abuse prevention\n  text: to tell real signups from automated ones.\n- purpose: advertising measurement\n  text: so we know which ads bring people who actually use the API\nretention:\n- scope: account records\n  period: until you ask us to delete the account\n  text: 'Account records: until you ask us to delete the account.'\n- scope: API request logs\n  period: while they are useful for billing disputes, usage reporting and abuse investigation\n  text: 'API request logs: kept while they are useful for billing disputes, usage reporting and abuse investigation,\n    then removed.'\n- scope: feedback wall entries\n  period: until you ask us to remove them\n\
  \  text: 'Feedback wall entries: kept until you ask us to remove them.'\n- scope: email tracking\n  period: with the campaign record\n  text: 'Email tracking: kept with the campaign record.'\nresidency:\n- region: Germany\n  text: Our servers are in Germany (Hetzner).\n- region: United States\n  text: Some processors above operate in the United States, so data reaches them there.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to [email protected]\n  text: Write to [email protected] from the address on the account and you can get a copy of what we hold, have\n    it corrected, have the account and its data deleted, or object to the analytics above.\nrights:\n- right: access\n  text: get a copy of what we hold\n- right: correction\n  text: have it corrected\n- right: deletion\n  text: have the account and its data deleted\n- right: objection\n  text: object to the analytics above\n- right: complain\
  \ to data protection authority\n  text: If you are in the EEA or the UK you also have the right to complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell personal data to anyone\n"
source_yaml_url: https://artifacts.apis.io/apiguru-app/privacy/apiguru-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from apiguru-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Amazon
- Real-Time
- Integration
---
