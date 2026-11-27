---
api_specs:
- filename: chocodata-amazon-api-openapi.yml
  format: yaml
  label: Chocodata Amazon API
  slug: chocodata-amazon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-amazon-api-openapi.yml
- filename: chocodata-chocodata-api-openapi.yml
  format: yaml
  label: Chocodata Chocodata API
  slug: chocodata-chocodata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-chocodata-api-openapi.yml
- filename: chocodata-reddit-api-openapi.yml
  format: yaml
  label: Chocodata Reddit API
  slug: chocodata-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-reddit-api-openapi.yml
- filename: chocodata-universal-api-openapi.yml
  format: yaml
  label: Chocodata Universal API
  slug: chocodata-universal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-universal-api-openapi.yml
- filename: chocodata-youtube-api-openapi.yml
  format: yaml
  label: Chocodata Youtube API
  slug: chocodata-youtube-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-youtube-api-openapi.yml
- filename: chocodata-app-store-api-openapi.yml
  format: yaml
  label: Chocodata App Store API
  slug: chocodata-app-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-app-store-api-openapi.yml
- filename: chocodata-google-play-api-openapi.yml
  format: yaml
  label: Chocodata Google Play API
  slug: chocodata-google-play-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chocodata/openapi/chocodata-google-play-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (used for authentication, billing receipts, and service announcements).
  - category: identifying
    text: Google account ID and email when you sign in with Google OAuth.
  - category: financial
    text: We store only the Stripe customer ID, subscription ID, and invoice history.
  - category: financial
    text: Billing address when you supply one for invoicing.
  - category: behavioral
    text: Dashboard activity (pages viewed, actions taken) when you are signed in.
  - category: device
    text: 'API request metadata: timestamp, endpoint, HTTP status, latency, credits charged, originating IP, and the API key prefix (not the full key).'
  deletion:
    route: email info@chocodata.com
    text: Erase your account and associated data - with the retention exceptions above (billing records kept for 7 years where required by law).
  dpa:
    available: true
    text: Each has a signed DPA on file
    url: null
  purposes:
  - purpose: authenticating and delivering service
    text: 'Contract performance (GDPR Art 6(1)(b)): authenticating you, metering credits, processing payments, delivering the service you signed up for.'
  - purpose: abuse prevention and debugging
    text: 'Legitimate interest (Art 6(1)(f)): preventing abuse, enforcing rate limits, detecting fraud, debugging production issues via request logs.'
  - purpose: tax record keeping
    text: 'Legal obligation (Art 6(1)(c)): keeping tax-relevant invoices for 7 years under EU bookkeeping rules.'
  - purpose: marketing emails
    text: 'Consent (Art 6(1)(a)): marketing emails you opt into.'
  residency:
  - region: EU and US
    text: Servers are located in the EU and US.
  retention:
  - period: 30 days after deletion
    scope: account data
    text: 'Account data: kept while your account is active, plus 30 days after deletion for restoration, then purged.'
  - period: 90 days
    scope: API request logs
    text: 'API request logs: 90 days for debugging + fraud detection, then aggregated-only.'
  - period: 7 years
    scope: billing records
    text: 'Billing records (invoices, tax-relevant data): 7 years per EU accounting rules.'
  - period: 12 months
    scope: email event logs
    text: 'Email event logs (sent / opened / clicked): 12 months, then purged.'
  rights:
  - right: access
    text: Access your personal data - we'll send you an export in machine-readable form within 30 days.
  - right: rectify
    text: Rectify inaccurate data - edit in-dashboard or email us.
  - right: erase
    text: Erase your account and associated data
  - right: portability
    text: Port your data to another provider in a standard format.
  - right: object
    text: Object to processing based on legitimate interest.
  - right: withdraw consent
    text: Withdraw consent at any time for opt-in marketing.
  - right: complain
    text: Lodge a complaint with your national data-protection authority.
  role:
    text: 'The data controller for the purposes of GDPR is: Chocodata OU Tallinn, Estonia info@chocodata.com'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data.
  subprocessors:
    text: Stripe - payment processing + invoicing. Receives your email, name, billing address, and card details.
    url: null
  transfers:
  - mechanism: DPF
    text: we rely on the EU-US Data Privacy Framework and Standard Contractual Clauses (SCCs) to safeguard it.
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chocodata
provenance_date: '2026-11-09'
provider_name: Chocodata
provider_slug: chocodata
slug: chocodata-privacy-policy
source_date: '2026-11-09'
source_filename: chocodata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chocodata.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chocodata\naid: chocodata\nurl: https://chocodata.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller for the purposes of GDPR is: Chocodata OU Tallinn, Estonia info@chocodata.com'\ndata_categories:\n- category: identifying\n  text: Email address (used for authentication, billing receipts, and service announcements).\n- category: identifying\n  text: Google account ID and email when you sign in with Google OAuth.\n- category: financial\n  text: We store only the Stripe customer ID, subscription ID, and invoice history.\n- category: financial\n  text: Billing address\
  \ when you supply one for invoicing.\n- category: behavioral\n  text: Dashboard activity (pages viewed, actions taken) when you are signed in.\n- category: device\n  text: 'API request metadata: timestamp, endpoint, HTTP status, latency, credits charged, originating IP, and the\n    API key prefix (not the full key).'\npurposes:\n- purpose: authenticating and delivering service\n  text: 'Contract performance (GDPR Art 6(1)(b)): authenticating you, metering credits, processing payments, delivering\n    the service you signed up for.'\n- purpose: abuse prevention and debugging\n  text: 'Legitimate interest (Art 6(1)(f)): preventing abuse, enforcing rate limits, detecting fraud, debugging\n    production issues via request logs.'\n- purpose: tax record keeping\n  text: 'Legal obligation (Art 6(1)(c)): keeping tax-relevant invoices for 7 years under EU bookkeeping rules.'\n- purpose: marketing emails\n  text: 'Consent (Art 6(1)(a)): marketing emails you opt into.'\nretention:\n- scope: account\
  \ data\n  period: 30 days after deletion\n  text: 'Account data: kept while your account is active, plus 30 days after deletion for restoration, then purged.'\n- scope: API request logs\n  period: 90 days\n  text: 'API request logs: 90 days for debugging + fraud detection, then aggregated-only.'\n- scope: billing records\n  period: 7 years\n  text: 'Billing records (invoices, tax-relevant data): 7 years per EU accounting rules.'\n- scope: email event logs\n  period: 12 months\n  text: 'Email event logs (sent / opened / clicked): 12 months, then purged.'\nresidency:\n- region: EU and US\n  text: Servers are located in the EU and US.\ntransfers:\n- mechanism: DPF\n  text: we rely on the EU-US Data Privacy Framework and Standard Contractual Clauses (SCCs) to safeguard it.\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs)\nsubprocessors:\n  url: null\n  text: Stripe - payment processing + invoicing. Receives your email, name, billing address, and card details.\ndpa:\n  available:\
  \ true\n  url: null\n  text: Each has a signed DPA on file\ndeletion:\n  route: email info@chocodata.com\n  text: Erase your account and associated data - with the retention exceptions above (billing records kept for 7\n    years where required by law).\nrights:\n- right: access\n  text: Access your personal data - we'll send you an export in machine-readable form within 30 days.\n- right: rectify\n  text: Rectify inaccurate data - edit in-dashboard or email us.\n- right: erase\n  text: Erase your account and associated data\n- right: portability\n  text: Port your data to another provider in a standard format.\n- right: object\n  text: Object to processing based on legitimate interest.\n- right: withdraw consent\n  text: Withdraw consent at any time for opt-in marketing.\n- right: complain\n  text: Lodge a complaint with your national data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data.\n"
source_yaml_url: https://artifacts.apis.io/chocodata/privacy/chocodata-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Chocodata's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- SERP
- E-Commerce Data
- social-media-data
- Proxy
- MCP
- Agent-Native
- structured-json
---
