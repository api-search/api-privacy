---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: An account identifier, your email address and your name.
  - category: contact
    text: When you sign in, Clerk creates your account and holds your email address and, if you use Google, the name and picture Google returns.
  - category: financial
    text: If you pay, Stripe holds your billing details and gives us a customer identifier, a subscription identifier, your plan and its status, and the start and end of the current period.
  - category: device
    text: Your connection key, hashed. The key you paste into Claude, ChatGPT, Gemini or Perplexity is shown once and stored as a hash, with its first characters and its last four
  - category: behavioral
    text: 'Two counters and a timestamp: calls this period, dossiers this period, when the key was last used, plus a per-minute count'
  - category: behavioral
    text: How the server is used. When you use the AmlakIntel server, we record which tool was called, in which market, whether it answered, declined or failed, and how long it took
  - category: financial
    text: 'For a portfolio, each holding as you describe it: the place and, where you give them, a label, the property type, bedrooms, size, what you paid and in which currency, and when you bought it.'
  deletion:
    route: Write to hello@intelwork4ce.com and name the watchlist, portfolio or view, or ask us to delete your account and everything in it.
    text: Write to hello@intelwork4ce.com and name the watchlist, portfolio or view, or ask us to delete your account and everything in it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Recognise and look after your account
    text: so that we can recognise your account when we look after it
  - purpose: Counting visits to the website
    text: We count visits to this website with PostHog
  - purpose: Saved watchlists, portfolios and views
    text: we keep it so it is there the next time you ask
  residency:
  - region: Belgium (Google Cloud europe-west1)
    text: Account and billing records, and what you save, sit in a PostgreSQL database in Google Cloud's europe-west1 region, in Belgium.
  - region: European Union
    text: The registry data behind the figures sits in BigQuery in the EU.
  - region: Doha (me-central1)
    text: Ingestion jobs that read Gulf government portals run in me-central1 , in Doha, and they read public registers, never anything about you.
  retention:
  - period: null
    scope: Account identifier, email and name
    text: We keep them until your account is deleted.
  - period: null
    scope: Saved items on own account
    text: Until it is deleted. When your account is deleted, everything you saved on your own account and everything you kept private on a Desk is deleted with it.
  - period: null
    scope: Account record, call counts and sent-record history after deletion
    text: We do not set an end date today.
  rights:
  - right: Access, correct, export, restrict or delete
    text: If you are in the EU or the UK you have the right to access, correct, export, restrict or delete your personal data, and to object to our processing of it.
  - right: Object to processing
    text: to object to our processing of it
  - right: Complain to data protection authority
    text: You can also complain to your national data protection authority.
  role:
    text: AmlakIntel is a product of IntelWork4ce and is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, we do not share it for advertising, and we have no affiliate or data partnerships.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AmlakIntel
provenance_date: '2026-11-09'
provider_name: AmlakIntel
provider_slug: amlakintel-com
slug: amlakintel-com-privacy-policy
source_date: '2026-11-09'
source_filename: amlakintel-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amlakintel.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AmlakIntel\naid: amlakintel-com\nurl: https://amlakintel.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AmlakIntel is a product of IntelWork4ce and is the controller of the personal data described here.\ndata_categories:\n- category: identifying\n  text: An account identifier, your email address and your name.\n- category: contact\n  text: When you sign in, Clerk creates your account and holds your email address and, if you use Google, the name\n    and picture Google returns.\n- category: financial\n  text: If you pay, Stripe holds your billing details and gives us a customer\
  \ identifier, a subscription identifier,\n    your plan and its status, and the start and end of the current period.\n- category: device\n  text: Your connection key, hashed. The key you paste into Claude, ChatGPT, Gemini or Perplexity is shown once\n    and stored as a hash, with its first characters and its last four\n- category: behavioral\n  text: 'Two counters and a timestamp: calls this period, dossiers this period, when the key was last used, plus\n    a per-minute count'\n- category: behavioral\n  text: How the server is used. When you use the AmlakIntel server, we record which tool was called, in which market,\n    whether it answered, declined or failed, and how long it took\n- category: financial\n  text: 'For a portfolio, each holding as you describe it: the place and, where you give them, a label, the property\n    type, bedrooms, size, what you paid and in which currency, and when you bought it.'\npurposes:\n- purpose: Recognise and look after your account\n  text: so that\
  \ we can recognise your account when we look after it\n- purpose: Counting visits to the website\n  text: We count visits to this website with PostHog\n- purpose: Saved watchlists, portfolios and views\n  text: we keep it so it is there the next time you ask\nretention:\n- scope: Account identifier, email and name\n  period: null\n  text: We keep them until your account is deleted.\n- scope: Saved items on own account\n  period: null\n  text: Until it is deleted. When your account is deleted, everything you saved on your own account and everything\n    you kept private on a Desk is deleted with it.\n- scope: Account record, call counts and sent-record history after deletion\n  period: null\n  text: We do not set an end date today.\nresidency:\n- region: Belgium (Google Cloud europe-west1)\n  text: Account and billing records, and what you save, sit in a PostgreSQL database in Google Cloud's europe-west1\n    region, in Belgium.\n- region: European Union\n  text: The registry data behind\
  \ the figures sits in BigQuery in the EU.\n- region: Doha (me-central1)\n  text: Ingestion jobs that read Gulf government portals run in me-central1 , in Doha, and they read public registers,\n    never anything about you.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@intelwork4ce.com and name the watchlist, portfolio or view, or ask us to delete your account\n    and everything in it.\n  text: Write to hello@intelwork4ce.com and name the watchlist, portfolio or view, or ask us to delete your account\n    and everything in it.\nrights:\n- right: Access, correct, export, restrict or delete\n  text: If you are in the EU or the UK you have the right to access, correct, export, restrict or delete your personal\n    data, and to object to our processing of it.\n- right: Object to processing\n  text: to object to our processing of it\n- right: Complain to data protection authority\n  text: You\
  \ can also complain to your national data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, we do not share it for advertising, and we have no affiliate or data partnerships.\n"
source_yaml_url: https://artifacts.apis.io/amlakintel-com/privacy/amlakintel-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from AmlakIntel's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Artificial Intelligence
- Property Data
- Gulf
- ChatGPT
---
