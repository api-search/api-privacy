---
api_specs:
- filename: pepbank-io-account-api-openapi.yml
  format: yaml
  label: PepBank Account API
  slug: pepbank-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-account-api-openapi.yml
- filename: pepbank-io-contribute-api-openapi.yml
  format: yaml
  label: PepBank Contribute API
  slug: pepbank-io-contribute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-contribute-api-openapi.yml
- filename: pepbank-io-evidence-api-openapi.yml
  format: yaml
  label: PepBank Evidence API
  slug: pepbank-io-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-evidence-api-openapi.yml
- filename: pepbank-io-exports-api-openapi.yml
  format: yaml
  label: PepBank Exports API
  slug: pepbank-io-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-exports-api-openapi.yml
- filename: pepbank-io-peptides-api-openapi.yml
  format: yaml
  label: PepBank Peptides API
  slug: pepbank-io-peptides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-peptides-api-openapi.yml
- filename: pepbank-io-records-api-openapi.yml
  format: yaml
  label: PepBank Records API
  slug: pepbank-io-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-records-api-openapi.yml
- filename: pepbank-io-sync-api-openapi.yml
  format: yaml
  label: PepBank Sync API
  slug: pepbank-io-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pepbank-io/openapi/pepbank-io-sync-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store your email address, your name, whether your email is confirmed, an optional profile picture and your preferred page view.
  - category: device
    text: Your session stores a session token, dates, your user ID, your browser's user-agent string and, when our host passes it on, your network address.
  - category: behavioral
    text: We store the data searches you run and details of their results.
  - category: communication
    text: We store your questions, the answers, the conversation title, the model you chose and the dates.
  - category: professional
    text: To verify you as a researcher, we store your institutional email, its domain, your institution, your ORCID ID if you add one, the verification status and its dates.
  - category: location
    text: your approximate location (country, region and city), which Google works out from your network address without storing the address
  deletion:
    route: 'Account page: Delete account; chat menu: Delete; contact form for other requests'
    text: Open Account and choose Delete account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sign in and run account
    text: We use them to sign you in and to run your account.
  - purpose: apply usage limits
    text: To apply usage limits, we count requests and keep usage records with the account or a coded network key
  - purpose: measure site use
    text: It uses Google Analytics to measure how people use the site
  retention:
  - period: 30 days
    scope: sessions
    text: Sessions end after 30 days, unless you use the site and renew them.
  - period: 10 minutes
    scope: sign-in codes
    text: Sign-in codes expire after 10 minutes.
  - period: 14 months
    scope: Google Analytics event and user data
    text: Google Analytics keeps event and user data for 14 months.
  - period: null
    scope: chat history
    text: Chat history has no automatic end date.
  - period: null
    scope: account details, chats and saved items
    text: Your account details, chats and saved items stay until you delete them.
  rights:
  - right: deletion
    text: Open Account and choose Delete account.
  - right: data requests
    text: For other data requests, or if you cannot get into your account, use the contact form.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not show ads from other companies, and we do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PepBank
provenance_date: '2026-11-10'
provider_name: PepBank
provider_slug: pepbank-io
slug: pepbank-io-privacy-policy
source_date: '2026-11-10'
source_filename: pepbank-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pepbank.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PepBank\naid: pepbank-io\nurl: https://pepbank.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store your email address, your name, whether your email is confirmed, an optional profile picture and\n    your preferred page view.\n- category: device\n  text: Your session stores a session token, dates, your user ID, your browser's user-agent string and, when our\n    host passes it on, your network address.\n- category: behavioral\n  text: We store the data searches you run and details of their results.\n- category: communication\n\
  \  text: We store your questions, the answers, the conversation title, the model you chose and the dates.\n- category: professional\n  text: To verify you as a researcher, we store your institutional email, its domain, your institution, your ORCID\n    ID if you add one, the verification status and its dates.\n- category: location\n  text: your approximate location (country, region and city), which Google works out from your network address without\n    storing the address\npurposes:\n- purpose: sign in and run account\n  text: We use them to sign you in and to run your account.\n- purpose: apply usage limits\n  text: To apply usage limits, we count requests and keep usage records with the account or a coded network key\n- purpose: measure site use\n  text: It uses Google Analytics to measure how people use the site\nretention:\n- scope: sessions\n  period: 30 days\n  text: Sessions end after 30 days, unless you use the site and renew them.\n- scope: sign-in codes\n  period: 10 minutes\n\
  \  text: Sign-in codes expire after 10 minutes.\n- scope: Google Analytics event and user data\n  period: 14 months\n  text: Google Analytics keeps event and user data for 14 months.\n- scope: chat history\n  period: null\n  text: Chat history has no automatic end date.\n- scope: account details, chats and saved items\n  period: null\n  text: Your account details, chats and saved items stay until you delete them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Account page: Delete account; chat menu: Delete; contact form for other requests'\n  text: Open Account and choose Delete account.\nrights:\n- right: deletion\n  text: Open Account and choose Delete account.\n- right: data requests\n  text: For other data requests, or if you cannot get into your account, use the contact form.\nsale_or_sharing:\n  stance: unstated\n  text: We do not show ads from other companies, and we do not sell personal\
  \ data.\n"
source_yaml_url: https://artifacts.apis.io/pepbank-io/privacy/pepbank-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from PepBank's own page on 2026-11-10.
synthetic: false
tags:
- Peptides
- Research
- Database
- Biotechnology
- Free
---
