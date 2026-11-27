---
api_specs:
- filename: budgeyapp-com-openapi-generated.yml
  format: yaml
  label: Budgey API
  slug: budgeyapp-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/budgeyapp-com/openapi/_ae-authored/budgeyapp-com-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (email address, name)
  - category: financial
    text: Bank and card account and transaction data, when you choose to connect a financial account via Plaid
  - category: communication
    text: Your typed Budgey chat history (your messages and Budgey's replies) and the text of notifications we send you, stored on our servers and tied to your account
  - category: financial
    text: Your budgeting data (budgets, categories, transactions)
  deletion:
    route: request account deletion in app or by contacting support
    text: You can request deletion of your account at any time. On account deletion we revoke any remaining Plaid connections at Plaid and permanently delete your account and its associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide budgeting services
    text: Budgey collects only the information required to provide you with our budgeting services.
  - purpose: AI chat replies
    text: we send your chat messages and the budget context needed to answer (such as your budgets, categories, and transactions) to xAI (Grok) to generate a reply
  - purpose: memory search
    text: the text of your message is also sent to OpenAI to create a search embedding (a numeric representation of the text)
  retention:
  - period: while your account is active
    scope: account and budgeting data
    text: Your account and budgeting data is retained while your account is active
  - period: while your account is active
    scope: chat history, notification text, inbox items
    text: Your typed Budgey chat history, saved notification text, and inbox items are retained while your account is active.
  - period: up to 30 days
    scope: AI providers
    text: both may keep requests for up to 30 days for abuse and safety monitoring, then delete them
  rights:
  - right: access
    text: 'Right to access: Request a copy of your personal data'
  - right: rectification
    text: 'Right to rectification: Correct inaccurate or incomplete data'
  - right: deletion
    text: 'Right to deletion: Request deletion of your personal data'
  - right: portability
    text: 'Right to portability: Receive your data in a portable format'
  - right: withdraw consent
    text: 'Right to withdraw consent: Revoke permissions at any time'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data to third parties
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Budgey
provenance_date: '2026-11-09'
provider_name: Budgey
provider_slug: budgeyapp-com
slug: budgeyapp-com-privacy-policy
source_date: '2026-11-09'
source_filename: budgeyapp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.budgeyapp.com/terms/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Budgey\naid: budgeyapp-com\nurl: https://www.budgeyapp.com/terms/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (email address, name)\n- category: financial\n  text: Bank and card account and transaction data, when you choose to connect a financial account via Plaid\n- category: communication\n  text: Your typed Budgey chat history (your messages and Budgey's replies) and the text of notifications we send\n    you, stored on our servers and tied to your account\n- category: financial\n  text: Your budgeting\
  \ data (budgets, categories, transactions)\npurposes:\n- purpose: provide budgeting services\n  text: Budgey collects only the information required to provide you with our budgeting services.\n- purpose: AI chat replies\n  text: we send your chat messages and the budget context needed to answer (such as your budgets, categories, and\n    transactions) to xAI (Grok) to generate a reply\n- purpose: memory search\n  text: the text of your message is also sent to OpenAI to create a search embedding (a numeric representation of\n    the text)\nretention:\n- scope: account and budgeting data\n  period: while your account is active\n  text: Your account and budgeting data is retained while your account is active\n- scope: chat history, notification text, inbox items\n  period: while your account is active\n  text: Your typed Budgey chat history, saved notification text, and inbox items are retained while your account\n    is active.\n- scope: AI providers\n  period: up to 30 days\n  text: both\
  \ may keep requests for up to 30 days for abuse and safety monitoring, then delete them\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request account deletion in app or by contacting support\n  text: You can request deletion of your account at any time. On account deletion we revoke any remaining Plaid\n    connections at Plaid and permanently delete your account and its associated data\nrights:\n- right: access\n  text: 'Right to access: Request a copy of your personal data'\n- right: rectification\n  text: 'Right to rectification: Correct inaccurate or incomplete data'\n- right: deletion\n  text: 'Right to deletion: Request deletion of your personal data'\n- right: portability\n  text: 'Right to portability: Receive your data in a portable format'\n- right: withdraw consent\n  text: 'Right to withdraw consent: Revoke permissions at any time'\nsale_or_sharing:\n  stance: prohibited\n  text:\
  \ We never sell your data to third parties\n"
source_yaml_url: https://artifacts.apis.io/budgeyapp-com/privacy/budgeyapp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Budgey's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Budgeting
- Finance
- Personal Finance
- AI Agents
---
