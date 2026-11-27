---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account details: your email and a sign-in identity, handled by WorkOS.'
  - category: financial
    text: 'Billing: subscription status and identifiers. Payment details are handled by Polar and never reach QuerySail.'
  - category: device
    text: Our hosting provider (Vercel) records request details such as IP address and user agent in its own infrastructure logs.
  - category: behavioral
    text: 'Website analytics: our public pages (not your account pages) use Google Analytics to count visits and see which sites and campaigns send people here.'
  - category: identifying
    text: 'Google connection: your Google account identifier and email, the Search Console, Google Analytics or Google Ads permission you approved'
  deletion:
    route: Delete your account in Account → Settings.
    text: Delete your account in Account → Settings. Access stops immediately. Your Google credentials are deleted and we ask Google to revoke the token, your connections and other account data are removed promptly and in any case within seven days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the connected reporting service
    text: Data you ask for is returned to the assistant host you connect, which has its own privacy terms.
  - purpose: Enforce fair-use limits
    text: Usage counters per account to enforce fair-use limits.
  - purpose: Website analytics
    text: 'Website analytics: our public pages (not your account pages) use Google Analytics to count visits and see which sites and campaigns send people here.'
  - purpose: Learn which listings bring people
    text: If you create an account, we save these two values on it to learn which listings bring people to QuerySail.
  retention:
  - period: 15 minutes
    scope: Short-lived cache
    text: 'Short-lived cache: 15 minutes.'
  - period: about 30 days
    scope: Operational logs
    text: 'Operational logs: about 30 days.'
  - period: about 3 days
    scope: Usage counters
    text: 'Usage counters: about 3 days.'
  rights:
  - right: Export account metadata
    text: Export your account metadata in Account → Settings.
  - right: Disconnect Google
    text: Disconnect Google in Account → Connections.
  - right: Hide property or ad account
    text: Hide a property or ad account from the assistant in Account → Connections.
  - right: Change cookie choice
    text: Change your choice at any time with "Cookie settings" at the bottom of every public page.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it for advertising.
  subprocessors:
    text: We use WorkOS (sign-in), Google (Search Console, Analytics and Google Ads data, and Google Analytics for our own website), Polar (payments), Vercel (hosting for the website and the MCP endpoints) and Convex (database and backend).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: querysail-com
provenance_date: '2026-11-10'
provider_name: querysail-com
provider_slug: querysail-com
slug: querysail-com-privacy-policy
source_date: '2026-11-10'
source_filename: querysail-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://querysail.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: querysail-com\naid: querysail-com\nurl: https://querysail.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account details: your email and a sign-in identity, handled by WorkOS.'\n- category: financial\n  text: 'Billing: subscription status and identifiers. Payment details are handled by Polar and never reach QuerySail.'\n- category: device\n  text: Our hosting provider (Vercel) records request details such as IP address and user agent in its own infrastructure\n    logs.\n- category: behavioral\n  text: 'Website analytics: our\
  \ public pages (not your account pages) use Google Analytics to count visits and see\n    which sites and campaigns send people here.'\n- category: identifying\n  text: 'Google connection: your Google account identifier and email, the Search Console, Google Analytics or Google\n    Ads permission you approved'\npurposes:\n- purpose: Run the connected reporting service\n  text: Data you ask for is returned to the assistant host you connect, which has its own privacy terms.\n- purpose: Enforce fair-use limits\n  text: Usage counters per account to enforce fair-use limits.\n- purpose: Website analytics\n  text: 'Website analytics: our public pages (not your account pages) use Google Analytics to count visits and see\n    which sites and campaigns send people here.'\n- purpose: Learn which listings bring people\n  text: If you create an account, we save these two values on it to learn which listings bring people to QuerySail.\nretention:\n- scope: Short-lived cache\n  period: 15 minutes\n\
  \  text: 'Short-lived cache: 15 minutes.'\n- scope: Operational logs\n  period: about 30 days\n  text: 'Operational logs: about 30 days.'\n- scope: Usage counters\n  period: about 3 days\n  text: 'Usage counters: about 3 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use WorkOS (sign-in), Google (Search Console, Analytics and Google Ads data, and Google Analytics for\n    our own website), Polar (payments), Vercel (hosting for the website and the MCP endpoints) and Convex (database\n    and backend).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account in Account → Settings.\n  text: Delete your account in Account → Settings. Access stops immediately. Your Google credentials are deleted\n    and we ask Google to revoke the token, your connections and other account data are removed promptly and in any\n    case within seven days\nrights:\n- right: Export account metadata\n  text: Export your account metadata in Account\
  \ → Settings.\n- right: Disconnect Google\n  text: Disconnect Google in Account → Connections.\n- right: Hide property or ad account\n  text: Hide a property or ad account from the assistant in Account → Connections.\n- right: Change cookie choice\n  text: Change your choice at any time with \"Cookie settings\" at the bottom of every public page.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/querysail-com/privacy/querysail-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from querysail-com's own page on 2026-11-10.
synthetic: false
tags:
- MCP
- Google Search Console
- Google Analytics
- AI Assistant
- Software-as-a-Service
---
