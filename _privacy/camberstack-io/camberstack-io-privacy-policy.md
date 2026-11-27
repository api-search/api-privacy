---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your Google account email and a stable Google account ID (the openid and email scopes)
  - category: behavioral
    text: 'Your Google Ads data, optional (the https://www.googleapis.com/auth/adwords scope): account and campaign structure, performance metrics, search terms, keywords and conversion settings'
  - category: behavioral
    text: Your Search Console data and sitemaps, optional
  - category: behavioral
    text: Your Google Analytics data and setup, optional
  - category: financial
    text: Your Google Merchant Center data and products, optional (the https://www.googleapis.com/auth/content scope)
  deletion:
    route: Email adam@camberstack.io from your Google account's address
    text: 'When you ask us to delete your data: email adam@camberstack.io from your Google account''s address and within 30 days we delete your Google token, account, proposals, Merchant Center product changes, usage log and feedback.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Answer AI assistant requests
    text: To answer the requests your AI assistant makes on your behalf (reports and read-only queries).
  - purpose: Apply approved changes
    text: To apply changes to your Google Ads account, your Search Console sitemaps and properties, your Google Analytics setup or your Merchant Center products, only when you approve a specific proposal, and to reverse them if you ask.
  residency:
  - region: United States
    text: Camberstack runs on infrastructure we operate in the United States, with the off-site backup copy on Cloudflare R2.
  retention:
  - period: You ask us to delete it, or two years without use (not while on a paid plan)
    scope: Google email and account ID
    text: You ask us to delete it, or two years without use (not while on a paid plan)
  - period: six months without use
    scope: Google refresh token, encrypted
    text: You disconnect or revoke access, or six months without use
  - period: up to 90 days
    scope: Web server and application logs
    text: Web server and application logs (IP address, time, path, errors) are kept for up to 90 days for security and then deleted.
  - period: null
    scope: Reports and query results
    text: Reports, search-term lists, query results, Google Analytics reports and Merchant Center product statuses and reports are computed on request and returned to your AI assistant. We do not store them.
  - period: 35 days at most
    scope: Backups
    text: They are used only to recover from a failure and expire after 35 days at most
  rights:
  - right: Unsubscribe from emails
    text: Every email has an unsubscribe link, and replies reach a person.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, use it for advertising, share it with data brokers, or use it to train AI or machine-learning models.
  subprocessors:
    text: Service providers. Resend delivers our emails, so it receives your email address. Stripe handles payments if you upgrade, so it receives your email address and keeps payment records under its own policy. Cloudflare R2 stores an encrypted-at-rest copy of our backups.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: camberstack-io
provenance_date: '2026-11-09'
provider_name: camberstack-io
provider_slug: camberstack-io
slug: camberstack-io-privacy-policy
source_date: '2026-11-09'
source_filename: camberstack-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://camberstack.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: camberstack-io\naid: camberstack-io\nurl: https://camberstack.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your Google account email and a stable Google account ID (the openid and email scopes)\n- category: behavioral\n  text: 'Your Google Ads data, optional (the https://www.googleapis.com/auth/adwords scope): account and campaign\n    structure, performance metrics, search terms, keywords and conversion settings'\n- category: behavioral\n  text: Your Search Console data and sitemaps, optional\n- category: behavioral\n  text:\
  \ Your Google Analytics data and setup, optional\n- category: financial\n  text: Your Google Merchant Center data and products, optional (the https://www.googleapis.com/auth/content scope)\npurposes:\n- purpose: Answer AI assistant requests\n  text: To answer the requests your AI assistant makes on your behalf (reports and read-only queries).\n- purpose: Apply approved changes\n  text: To apply changes to your Google Ads account, your Search Console sitemaps and properties, your Google Analytics\n    setup or your Merchant Center products, only when you approve a specific proposal, and to reverse them if you\n    ask.\nretention:\n- scope: Google email and account ID\n  period: You ask us to delete it, or two years without use (not while on a paid plan)\n  text: You ask us to delete it, or two years without use (not while on a paid plan)\n- scope: Google refresh token, encrypted\n  period: six months without use\n  text: You disconnect or revoke access, or six months without use\n- scope:\
  \ Web server and application logs\n  period: up to 90 days\n  text: Web server and application logs (IP address, time, path, errors) are kept for up to 90 days for security\n    and then deleted.\n- scope: Reports and query results\n  period: null\n  text: Reports, search-term lists, query results, Google Analytics reports and Merchant Center product statuses\n    and reports are computed on request and returned to your AI assistant. We do not store them.\n- scope: Backups\n  period: 35 days at most\n  text: They are used only to recover from a failure and expire after 35 days at most\nresidency:\n- region: United States\n  text: Camberstack runs on infrastructure we operate in the United States, with the off-site backup copy on Cloudflare\n    R2.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers. Resend delivers our emails, so it receives your email address. Stripe handles payments\n    if you upgrade, so it receives your email address and keeps payment records under\
  \ its own policy. Cloudflare\n    R2 stores an encrypted-at-rest copy of our backups.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email adam@camberstack.io from your Google account's address\n  text: 'When you ask us to delete your data: email adam@camberstack.io from your Google account''s address and\n    within 30 days we delete your Google token, account, proposals, Merchant Center product changes, usage log and\n    feedback.'\nrights:\n- right: Unsubscribe from emails\n  text: Every email has an unsubscribe link, and replies reach a person.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, use it for advertising, share it with data brokers, or use it to train AI or machine-learning\n    models.\n"
source_yaml_url: https://artifacts.apis.io/camberstack-io/privacy/camberstack-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from camberstack-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
