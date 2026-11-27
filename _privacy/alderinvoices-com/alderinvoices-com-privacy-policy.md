---
api_specs:
- filename: alderinvoices-com-drafts-api-openapi.yml
  format: yaml
  label: Alder Drafts API
  slug: alderinvoices-com-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-drafts-api-openapi.yml
- filename: alderinvoices-com-pdf-api-openapi.yml
  format: yaml
  label: Alder PDF API
  slug: alderinvoices-com-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-pdf-api-openapi.yml
- filename: alderinvoices-com-template-drafts-api-openapi.yml
  format: yaml
  label: Alder Template Drafts API
  slug: alderinvoices-com-template-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-template-drafts-api-openapi.yml
- filename: alderinvoices-com-templates-api-openapi.yml
  format: yaml
  label: Alder Templates API
  slug: alderinvoices-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-templates-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: the email and business name you enter
  - category: identifying
    text: The Stripe account ID, business name, email, country and website.
  - category: financial
    text: It also includes its payment history (amounts, dates, refunds and disputes).
  - category: behavioral
    text: We count page views, builder opens and PDF downloads as daily totals only.
  deletion:
    route: email founders@meetalder.com from your Stripe account's email address
    text: To delete everything, email founders@meetalder.com from your Stripe account's email address.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the Service
    text: 'To run the Service: sign-in, pay links, balances, overdue status, and the API and MCP server.'
  - purpose: understand users
    text: To understand who uses the tool.
  - purpose: prevent abuse and legal obligations
    text: To prevent abuse, and to meet legal obligations.
  residency:
  - region: United States
    text: 'Supabase: the database, in the United States.'
  retention:
  - period: null
    scope: signup email
    text: We keep a signup email until you ask us to remove it or opt out.
  - period: 30 days
    scope: profile and invoices
    text: We'll remove your profile and invoices within 30 days, except records we must keep by law.
  rights:
  - right: access, correct, export or delete
    text: you may have the right to access, correct, export or delete your personal data, and to object to marketing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data, and we don't contact your customers.
  subprocessors:
    text: 'Stripe: payments and account connection. Vercel: hosting. Request logs, including IP addresses, are kept for a short time. Supabase: the database, in the United States. Slack: internal notifications to the Alder team when a business connects, leaves its email or asks for help. Attio: Alder''s CRM, where we keep the businesses that connect or leave their email.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alder
provenance_date: '2026-11-09'
provider_name: Alder
provider_slug: alderinvoices-com
slug: alderinvoices-com-privacy-policy
source_date: '2026-11-09'
source_filename: alderinvoices-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alderinvoices.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alder\naid: alderinvoices-com\nurl: https://alderinvoices.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: the email and business name you enter\n- category: identifying\n  text: The Stripe account ID, business name, email, country and website.\n- category: financial\n  text: It also includes its payment history (amounts, dates, refunds and disputes).\n- category: behavioral\n  text: We count page views, builder opens and PDF downloads as daily totals only.\npurposes:\n- purpose: run the Service\n  text: 'To run the Service: sign-in,\
  \ pay links, balances, overdue status, and the API and MCP server.'\n- purpose: understand users\n  text: To understand who uses the tool.\n- purpose: prevent abuse and legal obligations\n  text: To prevent abuse, and to meet legal obligations.\nretention:\n- scope: signup email\n  period: null\n  text: We keep a signup email until you ask us to remove it or opt out.\n- scope: profile and invoices\n  period: 30 days\n  text: We'll remove your profile and invoices within 30 days, except records we must keep by law.\nresidency:\n- region: United States\n  text: 'Supabase: the database, in the United States.'\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Stripe: payments and account connection. Vercel: hosting. Request logs, including IP addresses, are kept\n    for a short time. Supabase: the database, in the United States. Slack: internal notifications to the Alder team\n    when a business connects, leaves its email or asks for help. Attio: Alder''s CRM, where we keep the businesses\n\
  \    that connect or leave their email.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email founders@meetalder.com from your Stripe account's email address\n  text: To delete everything, email founders@meetalder.com from your Stripe account's email address.\nrights:\n- right: access, correct, export or delete\n  text: you may have the right to access, correct, export or delete your personal data, and to object to marketing.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data, and we don't contact your customers.\n"
source_yaml_url: https://artifacts.apis.io/alderinvoices-com/privacy/alderinvoices-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Alder's own page on 2026-11-09.
synthetic: false
tags:
- Invoices
- Finance
- PDF
- Free
- MCP
---
