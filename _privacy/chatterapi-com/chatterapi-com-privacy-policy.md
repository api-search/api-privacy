---
api_specs:
- filename: chatterapi-com-account-api-openapi.yml
  format: yaml
  label: chatterapi-com Account API
  slug: chatterapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-account-api-openapi.yml
- filename: chatterapi-com-everywhere-api-openapi.yml
  format: yaml
  label: chatterapi-com Everywhere API
  slug: chatterapi-com-everywhere-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-everywhere-api-openapi.yml
- filename: chatterapi-com-reddit-api-openapi.yml
  format: yaml
  label: chatterapi-com Reddit API
  slug: chatterapi-com-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-reddit-api-openapi.yml
- filename: chatterapi-com-x-api-openapi.yml
  format: yaml
  label: chatterapi-com X API
  slug: chatterapi-com-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterapi-com/openapi/chatterapi-com-x-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: your email address, your name if your sign-in provider shares it, and which provider you signed in with.'
  - category: financial
    text: 'Billing: Lemon Squeezy handles payments as the merchant of record. We never see your full card number.'
  - category: behavioral
    text: 'Usage records for each call: the tool, the time, the credits charged, the status, how long it took, which data provider served it and the request id.'
  - category: communication
    text: 'Request content: the queries, handles and URLs you send.'
  - category: device
    text: 'Free tools: a hashed IP address and the tool used, so we can apply daily limits.'
  deletion:
    route: account settings or email to privacy contact
    text: To delete your account, use your settings, or email piyushh@amplifyxlabs.com from your account address and we'll do it for you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide service and bill
    text: We use your data to provide the service, bill you, prevent abuse and answer support requests.
  - purpose: advertising attribution
    text: If you sign up, we save it to your account once so we can see which pages bring people in.
  residency:
  - region: India
    text: Your data is stored in India (Supabase, Mumbai region)
  retention:
  - period: 13 months
    scope: Usage records
    text: 'Usage records: 13 months.'
  - period: 30 days
    scope: Free tool run records
    text: 'Free tool run records: 30 days.'
  - period: minutes to hours
    scope: Cached responses
    text: 'Cached responses: minutes to hours.'
  - period: until you delete your account
    scope: Account data
    text: 'Account data: until you delete your account.'
  - period: as long as the law requires
    scope: Billing records
    text: 'Billing records: as long as the law requires, held by Lemon Squeezy.'
  rights:
  - right: access
    text: You can ask to see, correct or delete your data.
  - right: correction
    text: You can ask to see, correct or delete your data.
  - right: deletion
    text: You can ask to see, correct or delete your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, and we do not use your queries to train models.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: processed by providers based in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: chatterapi-com
provenance_date: '2026-11-09'
provider_name: chatterapi-com
provider_slug: chatterapi-com
slug: chatterapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: chatterapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chatterapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: chatterapi-com\naid: chatterapi-com\nurl: https://chatterapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account details: your email address, your name if your sign-in provider shares it, and which provider you\n    signed in with.'\n- category: financial\n  text: 'Billing: Lemon Squeezy handles payments as the merchant of record. We never see your full card number.'\n- category: behavioral\n  text: 'Usage records for each call: the tool, the time, the credits charged, the status, how long it took, which\n    data provider\
  \ served it and the request id.'\n- category: communication\n  text: 'Request content: the queries, handles and URLs you send.'\n- category: device\n  text: 'Free tools: a hashed IP address and the tool used, so we can apply daily limits.'\npurposes:\n- purpose: provide service and bill\n  text: We use your data to provide the service, bill you, prevent abuse and answer support requests.\n- purpose: advertising attribution\n  text: If you sign up, we save it to your account once so we can see which pages bring people in.\nretention:\n- scope: Usage records\n  period: 13 months\n  text: 'Usage records: 13 months.'\n- scope: Free tool run records\n  period: 30 days\n  text: 'Free tool run records: 30 days.'\n- scope: Cached responses\n  period: minutes to hours\n  text: 'Cached responses: minutes to hours.'\n- scope: Account data\n  period: until you delete your account\n  text: 'Account data: until you delete your account.'\n- scope: Billing records\n  period: as long as the law requires\n\
  \  text: 'Billing records: as long as the law requires, held by Lemon Squeezy.'\nresidency:\n- region: India\n  text: Your data is stored in India (Supabase, Mumbai region)\ntransfers:\n- mechanism: other\n  text: processed by providers based in the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings or email to privacy contact\n  text: To delete your account, use your settings, or email piyushh@amplifyxlabs.com from your account address and\n    we'll do it for you.\nrights:\n- right: access\n  text: You can ask to see, correct or delete your data.\n- right: correction\n  text: You can ask to see, correct or delete your data.\n- right: deletion\n  text: You can ask to see, correct or delete your data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, and we do not use your queries to train models.\n"
source_yaml_url: https://artifacts.apis.io/chatterapi-com/privacy/chatterapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from chatterapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Reddit
- X
- Data
- MCP
---
