---
api_specs:
- filename: aidataparser-com-openapi-generated.yml
  format: yaml
  label: AIDataParser API
  slug: aidataparser-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aidataparser-com/openapi/_ae-authored/aidataparser-com-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: We store your email, a hashed version of your API key (never the raw key), and a credit ledger
  - category: identifying
    text: a hashed version of your API key (never the raw key)
  - category: behavioral
    text: cookieless page views (path, referrer, screen width, a daily-rotating hash — no IP address is stored)
  - category: other
    text: The document's text or image bytes are sent to Anthropic's Claude API to extract structured data
  deletion:
    route: Email hello@aidataparser.com to request deletion of account data
    text: Email hello@aidataparser.com to request a copy of the account data we hold, revoke/delete your API key and account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Document extraction
    text: Anthropic (Claude API) Document extraction Document content, per-request only
  - purpose: Hosting and analytics
    text: Vercel Hosting, analytics Page views, request logs
  - purpose: Account and credit storage
    text: Postgres (Supabase-hosted) Account & credit storage; page-view counts
  retention:
  - period: null
    scope: Document content
    text: 'Document content: not retained — discarded after each request completes.'
  - period: 30 days
    scope: Account data
    text: 'Account data (email, hashed key, credit balance): kept while your account is active; deleted within 30 days of a deletion request.'
  rights:
  - right: access
    text: Email hello@aidataparser.com to request a copy of the account data we hold
  - right: deletion
    text: revoke/delete your API key and account
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell, rent, or share your data with third parties.
  subprocessors:
    text: Third-party services Service Purpose Data Anthropic (Claude API) Document extraction Document content, per-request only Vercel Hosting, analytics Page views, request logs Postgres (Supabase-hosted) Account & credit storage
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIDataParser
provenance_date: '2026-11-09'
provider_name: AIDataParser
provider_slug: aidataparser-com
slug: aidataparser-com-privacy-policy
source_date: '2026-11-09'
source_filename: aidataparser-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aidataparser.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIDataParser\naid: aidataparser-com\nurl: https://aidataparser.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We store your email, a hashed version of your API key (never the raw key), and a credit ledger\n- category: identifying\n  text: a hashed version of your API key (never the raw key)\n- category: behavioral\n  text: cookieless page views (path, referrer, screen width, a daily-rotating hash — no IP address is stored)\n- category: other\n  text: The document's text or image bytes are sent to Anthropic's Claude API to extract\
  \ structured data\npurposes:\n- purpose: Document extraction\n  text: Anthropic (Claude API) Document extraction Document content, per-request only\n- purpose: Hosting and analytics\n  text: Vercel Hosting, analytics Page views, request logs\n- purpose: Account and credit storage\n  text: Postgres (Supabase-hosted) Account & credit storage; page-view counts\nretention:\n- scope: Document content\n  period: null\n  text: 'Document content: not retained — discarded after each request completes.'\n- scope: Account data\n  period: 30 days\n  text: 'Account data (email, hashed key, credit balance): kept while your account is active; deleted within 30\n    days of a deletion request.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Third-party services Service Purpose Data Anthropic (Claude API) Document extraction Document content, per-request\n    only Vercel Hosting, analytics Page views, request logs Postgres (Supabase-hosted) Account & credit storage\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@aidataparser.com to request deletion of account data\n  text: Email hello@aidataparser.com to request a copy of the account data we hold, revoke/delete your API key and\n    account\nrights:\n- right: access\n  text: Email hello@aidataparser.com to request a copy of the account data we hold\n- right: deletion\n  text: revoke/delete your API key and account\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell, rent, or share your data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/aidataparser-com/privacy/aidataparser-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from AIDataParser's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data Extraction
- JSON
- PDF
- Image Processing
---
