---
api_specs:
- filename: agentrenderapi-com-corpus-api-openapi.yml
  format: yaml
  label: AgentRender Corpus API
  slug: agentrenderapi-com-corpus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrenderapi-com/openapi/agentrenderapi-com-corpus-api-openapi.yml
- filename: agentrenderapi-com-deployment-api-openapi.yml
  format: yaml
  label: AgentRender Deployment API
  slug: agentrenderapi-com-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrenderapi-com/openapi/agentrenderapi-com-deployment-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: when you connect AgentRender through ChatGPT or another OAuth client, our sign-in provider Auth0 (and Google, if you choose Google) shares your email address, whether it is verified, and an account identifier with us.
  - category: financial
    text: payment fulfillment identifiers from Stripe
  - category: location
    text: your IP address, user agent
  - category: device
    text: the MCP client name and version
  - category: behavioral
    text: the page URL and options you submit (viewport, format, full page, and similar).
  - category: communication
    text: Support emails and Stripe payment confirmations (Stripe handles card details; we never see full card numbers).
  deletion:
    route: email hello@agentrenderapi.com
    text: Email hello@agentrenderapi.com to access or delete your account, sign-in record, usage counters, or the request-log entries tied to your account or IP address; we'll verify the request and reply within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run renders and sign-in
    text: To run renders, sign you in, enforce plan limits and rate limits, prevent abuse and SSRF attacks, keep the service secure, fix problems, handle billing and support, and measure overall usage.
  - purpose: no sale or advertising
    text: We do not sell personal data or use it for advertising.
  retention:
  - period: 60 minutes
    scope: screenshot and PDF files
    text: download links expire 60 minutes after the render, and the files are deleted automatically shortly after (normally within about 70 minutes).
  - period: null
    scope: extract results
    text: 'Extract results: not stored.'
  - period: 90 days
    scope: request log
    text: 'Request log (including IP addresses): 90 days, then deleted automatically.'
  - period: null
    scope: usage counters
    text: 'Usage counters: kept while your account is active.'
  - period: null
    scope: account and key records
    text: 'Account, sign-in and key records: until you ask us to delete your account or we close it.'
  - period: null
    scope: billing records
    text: 'Billing records: kept as required for tax and accounting.'
  - period: null
    scope: waitlist data
    text: 'Waitlist data: until you ask us to delete it.'
  rights:
  - right: access and deletion
    text: Email hello@agentrenderapi.com to access or delete your account, sign-in record, usage counters, or the request-log entries tied to your account or IP address
  - right: disconnect
    text: Disconnect AgentRender in ChatGPT at any time.
  role:
    text: 'Publisher / controller: Corbin Vachal (Individual), doing business as AgentRender.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it for advertising.
  subprocessors:
    text: Who receives it (subprocessors) Fly.io — API hosting and rendering. Auth0 by Okta — sign-in. Google — only if you sign in with Google. Stripe — payments and subscriptions. Resend — email sending and our support inbox. Cloudflare — website hosting and DNS. Formspree — waitlist form, if used.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentRender
provenance_date: '2026-11-09'
provider_name: AgentRender
provider_slug: agentrenderapi-com
slug: agentrenderapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentrenderapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentrenderapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentRender\naid: agentrenderapi-com\nurl: https://agentrenderapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Publisher / controller: Corbin Vachal (Individual), doing business as AgentRender.'\ndata_categories:\n- category: identifying\n  text: when you connect AgentRender through ChatGPT or another OAuth client, our sign-in provider Auth0 (and Google,\n    if you choose Google) shares your email address, whether it is verified, and an account identifier with us.\n- category: financial\n  text: payment fulfillment identifiers from Stripe\n- category: location\n  text: your\
  \ IP address, user agent\n- category: device\n  text: the MCP client name and version\n- category: behavioral\n  text: the page URL and options you submit (viewport, format, full page, and similar).\n- category: communication\n  text: Support emails and Stripe payment confirmations (Stripe handles card details; we never see full card numbers).\npurposes:\n- purpose: run renders and sign-in\n  text: To run renders, sign you in, enforce plan limits and rate limits, prevent abuse and SSRF attacks, keep the\n    service secure, fix problems, handle billing and support, and measure overall usage.\n- purpose: no sale or advertising\n  text: We do not sell personal data or use it for advertising.\nretention:\n- scope: screenshot and PDF files\n  period: 60 minutes\n  text: download links expire 60 minutes after the render, and the files are deleted automatically shortly after\n    (normally within about 70 minutes).\n- scope: extract results\n  period: null\n  text: 'Extract results: not stored.'\n\
  - scope: request log\n  period: 90 days\n  text: 'Request log (including IP addresses): 90 days, then deleted automatically.'\n- scope: usage counters\n  period: null\n  text: 'Usage counters: kept while your account is active.'\n- scope: account and key records\n  period: null\n  text: 'Account, sign-in and key records: until you ask us to delete your account or we close it.'\n- scope: billing records\n  period: null\n  text: 'Billing records: kept as required for tax and accounting.'\n- scope: waitlist data\n  period: null\n  text: 'Waitlist data: until you ask us to delete it.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who receives it (subprocessors) Fly.io — API hosting and rendering. Auth0 by Okta — sign-in. Google — only\n    if you sign in with Google. Stripe — payments and subscriptions. Resend — email sending and our support inbox.\n    Cloudflare — website hosting and DNS. Formspree — waitlist form, if used.\ndpa:\n  available: null\n  url: null\n  text:\
  \ null\ndeletion:\n  route: email hello@agentrenderapi.com\n  text: Email hello@agentrenderapi.com to access or delete your account, sign-in record, usage counters, or the\n    request-log entries tied to your account or IP address; we'll verify the request and reply within 30 days.\nrights:\n- right: access and deletion\n  text: Email hello@agentrenderapi.com to access or delete your account, sign-in record, usage counters, or the\n    request-log entries tied to your account or IP address\n- right: disconnect\n  text: Disconnect AgentRender in ChatGPT at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/agentrenderapi-com/privacy/agentrenderapi-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from AgentRender's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Screenshots
- PDF
- Data Extraction
- ChatGPT
---
