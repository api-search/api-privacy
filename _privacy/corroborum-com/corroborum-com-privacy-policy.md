---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: your sign-in identifier from our authentication provider, email address, name if you give one, and the sign-in method you used
  - category: financial
    text: 'Billing: your Stripe customer identifier, plan, subscription status and invoices.'
  - category: behavioral
    text: 'Usage: per-day counts of calls per tool, errors, upstream cost and response time, and which kind of app (such as Claude, ChatGPT or Cursor) the calls came from, linked to your account.'
  - category: device
    text: 'Technical logs: request identifier, your account identifier, tool name, status, response time and a short hash of the query, used to spot repeated requests.'
  - category: other
    text: 'Use case: the optional answer you give about what you will mostly use Corroborum for.'
  deletion:
    route: Delete your account from Settings, or email support@corroborum.com to request deletion
    text: you can see and export your usage (CSV) from your dashboard, delete your account from Settings, and ask us to access, correct or delete your data by emailing support@corroborum.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: To provide the service you signed up for (contract)
  - purpose: billing
    text: to bill you (contract and legal obligation)
  - purpose: abuse prevention and reliability
    text: to prevent abuse and keep the service reliable (legitimate interest)
  residency:
  - region: United States and other countries
    text: Our service providers process data in the United States and other countries.
  retention:
  - period: 24 months
    scope: usage counts
    text: 'Usage counts: deleted after 24 months.'
  - period: 30 minutes
    scope: search results
    text: Search results (the papers found, not your query) are kept for up to 30 minutes so that Claude can fetch the next page
  - period: 10 minutes
    scope: scholarly source responses cache
    text: Responses from the scholarly sources are cached in the server’s memory for up to 10 minutes and never written to disk.
  - period: 12 months
    scope: hashes after account deletion
    text: We keep a keyed one-way hash of your sign-in identifier and of your email address for 12 months after deletion
  rights:
  - right: access
    text: ask us to access, correct or delete your data by emailing support@corroborum.com
  - right: correction
    text: ask us to access, correct or delete your data by emailing support@corroborum.com
  - right: deletion
    text: ask us to access, correct or delete your data by emailing support@corroborum.com
  - right: export usage
    text: You can see and export your usage (CSV) from your dashboard
  - right: complain to authority
    text: You may also complain to your local data protection authority.
  role:
    text: Corroborum is operated by Founderproof, Inc. , a Delaware corporation (“we”, “us”)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it for advertising.
  subprocessors:
    text: 'Service providers We use these processors to run Corroborum: WorkOS: sign-in and account management. Stripe: payments, invoices and tax calculation. Neon: database hosting (accounts, subscriptions, usage counts). Cloudflare: hosting of the search server and this website, DNS, and forwarding of email sent to our support address. Fly.io: standby copy of the search server, used only if we switch back to it. OpenAlex: receives your query text to retrieve papers. Voyage AI: receives your query text and candidate paper text to rank results.'
    url: null
  transfers:
  - mechanism: other
    text: Where required, transfers rely on the providers’ standard contractual safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Corroborum
provenance_date: '2026-11-09'
provider_name: Corroborum
provider_slug: corroborum-com
slug: corroborum-com-privacy-policy
source_date: '2026-11-09'
source_filename: corroborum-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corroborum.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Corroborum\naid: corroborum-com\nurl: https://corroborum.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Corroborum is operated by Founderproof, Inc. , a Delaware corporation (“we”, “us”)\ndata_categories:\n- category: identifying\n  text: your sign-in identifier from our authentication provider, email address, name if you give one, and the sign-in\n    method you used\n- category: financial\n  text: 'Billing: your Stripe customer identifier, plan, subscription status and invoices.'\n- category: behavioral\n  text: 'Usage: per-day counts of calls per tool, errors, upstream cost\
  \ and response time, and which kind of app\n    (such as Claude, ChatGPT or Cursor) the calls came from, linked to your account.'\n- category: device\n  text: 'Technical logs: request identifier, your account identifier, tool name, status, response time and a short\n    hash of the query, used to spot repeated requests.'\n- category: other\n  text: 'Use case: the optional answer you give about what you will mostly use Corroborum for.'\npurposes:\n- purpose: provide the service\n  text: To provide the service you signed up for (contract)\n- purpose: billing\n  text: to bill you (contract and legal obligation)\n- purpose: abuse prevention and reliability\n  text: to prevent abuse and keep the service reliable (legitimate interest)\nretention:\n- scope: usage counts\n  period: 24 months\n  text: 'Usage counts: deleted after 24 months.'\n- scope: search results\n  period: 30 minutes\n  text: Search results (the papers found, not your query) are kept for up to 30 minutes so that Claude can\
  \ fetch\n    the next page\n- scope: scholarly source responses cache\n  period: 10 minutes\n  text: Responses from the scholarly sources are cached in the server’s memory for up to 10 minutes and never written\n    to disk.\n- scope: hashes after account deletion\n  period: 12 months\n  text: We keep a keyed one-way hash of your sign-in identifier and of your email address for 12 months after deletion\nresidency:\n- region: United States and other countries\n  text: Our service providers process data in the United States and other countries.\ntransfers:\n- mechanism: other\n  text: Where required, transfers rely on the providers’ standard contractual safeguards.\nsubprocessors:\n  url: null\n  text: 'Service providers We use these processors to run Corroborum: WorkOS: sign-in and account management. Stripe:\n    payments, invoices and tax calculation. Neon: database hosting (accounts, subscriptions, usage counts). Cloudflare:\n    hosting of the search server and this website, DNS, and\
  \ forwarding of email sent to our support address. Fly.io:\n    standby copy of the search server, used only if we switch back to it. OpenAlex: receives your query text to\n    retrieve papers. Voyage AI: receives your query text and candidate paper text to rank results.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account from Settings, or email support@corroborum.com to request deletion\n  text: you can see and export your usage (CSV) from your dashboard, delete your account from Settings, and ask\n    us to access, correct or delete your data by emailing support@corroborum.com\nrights:\n- right: access\n  text: ask us to access, correct or delete your data by emailing support@corroborum.com\n- right: correction\n  text: ask us to access, correct or delete your data by emailing support@corroborum.com\n- right: deletion\n  text: ask us to access, correct or delete your data by emailing support@corroborum.com\n- right: export usage\n  text: You\
  \ can see and export your usage (CSV) from your dashboard\n- right: complain to authority\n  text: You may also complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/corroborum-com/privacy/corroborum-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Corroborum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Academic Research
- Literature Search
- Scholarly Papers
- MCP
- AI Assistants
- Citations
---
