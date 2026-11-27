---
api_specs:
- filename: leafwright-co-openapi-generated.yml
  format: yaml
  label: leafwright-co API
  slug: leafwright-co-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leafwright-co/openapi/_ae-authored/leafwright-co-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and authentication identifiers, handled through Supabase Auth.
  - category: financial
    text: Subscriptions and metered usage are processed by Stripe.
  - category: other
    text: The HTML, templates, and data you send are processed to render your PDFs.
  - category: behavioral
    text: Vercel Analytics (cookieless) measures page traffic and performance on the marketing site.
  - category: device
    text: Render jobs, logs, API request metadata, and usage counters, kept so you can debug renders and we can enforce quotas.
  deletion:
    route: Account deletion or emailed request
    text: Deleting your account removes your data from our systems within 30 days, except records we must keep for tax or legal compliance.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rendering PDFs
    text: The HTML, templates, and data you send are processed to render your PDFs.
  - purpose: debugging and quotas
    text: kept so you can debug renders and we can enforce quotas.
  - purpose: analytics
    text: Vercel Analytics (cookieless) measures page traffic and performance on the marketing site.
  retention:
  - period: while your account is active
    scope: Account and billing records
    text: Account and billing records are kept while your account is active.
  - period: project's retention window
    scope: Captured render source
    text: It is held for your project's retention window — the same window as the document it produced — and then deleted.
  - period: within 30 days
    scope: Account data after deletion
    text: Deleting your account removes your data from our systems within 30 days, except records we must keep for tax or legal compliance.
  rights:
  - right: copy of data or deletion on request
    text: You can request a copy of your data or ask us to delete it at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data, and we don't use your documents or templates to train AI models.
  subprocessors:
    text: Vercel (hosting), Supabase (authentication and database), Stripe (payments), and Google Cloud (rendering infrastructure and optional storage).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: leafwright-co
provenance_date: '2026-11-09'
provider_name: leafwright-co
provider_slug: leafwright-co
slug: leafwright-co-privacy-policy
source_date: '2026-11-09'
source_filename: leafwright-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://leafwright.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: leafwright-co\naid: leafwright-co\nurl: https://leafwright.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address and authentication identifiers, handled through Supabase Auth.\n- category: financial\n  text: Subscriptions and metered usage are processed by Stripe.\n- category: other\n  text: The HTML, templates, and data you send are processed to render your PDFs.\n- category: behavioral\n  text: Vercel Analytics (cookieless) measures page traffic and performance on the marketing site.\n- category: device\n  text:\
  \ Render jobs, logs, API request metadata, and usage counters, kept so you can debug renders and we can enforce\n    quotas.\npurposes:\n- purpose: rendering PDFs\n  text: The HTML, templates, and data you send are processed to render your PDFs.\n- purpose: debugging and quotas\n  text: kept so you can debug renders and we can enforce quotas.\n- purpose: analytics\n  text: Vercel Analytics (cookieless) measures page traffic and performance on the marketing site.\nretention:\n- scope: Account and billing records\n  period: while your account is active\n  text: Account and billing records are kept while your account is active.\n- scope: Captured render source\n  period: project's retention window\n  text: It is held for your project's retention window — the same window as the document it produced — and then\n    deleted.\n- scope: Account data after deletion\n  period: within 30 days\n  text: Deleting your account removes your data from our systems within 30 days, except records we must\
  \ keep for\n    tax or legal compliance.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Vercel (hosting), Supabase (authentication and database), Stripe (payments), and Google Cloud (rendering\n    infrastructure and optional storage).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or emailed request\n  text: Deleting your account removes your data from our systems within 30 days, except records we must keep for\n    tax or legal compliance.\nrights:\n- right: copy of data or deletion on request\n  text: You can request a copy of your data or ask us to delete it at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data, and we don't use your documents or templates to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/leafwright-co/privacy/leafwright-co-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from leafwright-co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- HTML to PDF
- Serverless
- Artificial Intelligence
- PDF
---
