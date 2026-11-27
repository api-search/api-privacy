---
api_specs:
- filename: amazon-scraper-api-amazon-api-openapi.yml
  format: yaml
  label: Amazon Scraper API Amazon API
  slug: amazon-scraper-api-amazon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-scraper-api/openapi/amazon-scraper-api-amazon-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address (used for authentication, billing receipts, and service announcements).
  - category: identifying
    text: Google account ID and email when you sign in with Google OAuth.
  - category: other
    text: 'API request metadata: timestamp, endpoint, HTTP status, latency, credits charged, originating IP, and the API key prefix (not the full key).'
  - category: behavioral
    text: Dashboard activity (pages viewed, actions taken) when you are signed in.
  - category: financial
    text: Payment-method identifiers handled by our payment processor (Stripe).
  - category: financial
    text: Billing address when you supply one for invoicing.
  deletion:
    route: email request
    text: Email [email protected] to exercise any of these rights.
  dpa:
    available: true
    text: Each has a signed DPA on file
    url: null
  purposes:
  - purpose: Contract performance
    text: 'Contract performance (GDPR Art 6(1)(b)): authenticating you, metering credits, processing payments, delivering the service you signed up for.'
  - purpose: Legitimate interest
    text: 'Legitimate interest (Art 6(1)(f)): preventing abuse, enforcing rate limits, detecting fraud, debugging production issues via request logs.'
  - purpose: Legal obligation
    text: 'Legal obligation (Art 6(1)(c)): keeping tax-relevant invoices for 7 years under EU bookkeeping rules.'
  - purpose: Consent
    text: 'Consent (Art 6(1)(a)): marketing emails you opt into.'
  residency:
  - region: EU and US
    text: Servers are located in the EU and US.
  retention:
  - period: 30 days after deletion
    scope: Account data
    text: 'Account data: kept while your account is active, plus 30 days after deletion for restoration, then purged.'
  - period: 90 days
    scope: API request logs
    text: 'API request logs: 90 days for debugging + fraud detection, then aggregated-only.'
  - period: 7 years
    scope: Billing records
    text: 'Billing records (invoices, tax-relevant data): 7 years per EU accounting rules.'
  - period: 12 months
    scope: Email event logs
    text: 'Email event logs (sent / opened / clicked): 12 months, then purged.'
  rights:
  - right: Access
    text: Access your personal data - we'll send you an export in machine-readable form within 30 days.
  - right: Rectify
    text: Rectify inaccurate data - edit in-dashboard or email us.
  - right: Erase
    text: Erase your account and associated data - with the retention exceptions above
  - right: Port
    text: Port your data to another provider in a standard format.
  - right: Object
    text: Object to processing based on legitimate interest.
  - right: Withdraw consent
    text: Withdraw consent at any time for opt-in marketing.
  - right: Complain
    text: Lodge a complaint with your national data-protection authority.
  role:
    text: 'The data controller for the purposes of GDPR is: Chocodata OU Tallinn, Estonia'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data.
  subprocessors:
    text: We share the minimum necessary data with the following processors.
    url: null
  transfers:
  - mechanism: DPF
    text: we rely on the EU-US Data Privacy Framework and Standard Contractual Clauses (SCCs) to safeguard it.
  - mechanism: SCC
    text: Copies of the SCC texts are available on request.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Amazon Scraper API
provenance_date: '2026-11-09'
provider_name: Amazon Scraper API
provider_slug: amazon-scraper-api
slug: amazon-scraper-api-privacy-policy
source_date: '2026-11-09'
source_filename: amazon-scraper-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amazonscraperapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Amazon Scraper API\naid: amazon-scraper-api\nurl: https://amazonscraperapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller for the purposes of GDPR is: Chocodata OU Tallinn, Estonia'\ndata_categories:\n- category: contact\n  text: Email address (used for authentication, billing receipts, and service announcements).\n- category: identifying\n  text: Google account ID and email when you sign in with Google OAuth.\n- category: other\n  text: 'API request metadata: timestamp, endpoint, HTTP status, latency, credits charged, originating IP, and the\n    API key prefix\
  \ (not the full key).'\n- category: behavioral\n  text: Dashboard activity (pages viewed, actions taken) when you are signed in.\n- category: financial\n  text: Payment-method identifiers handled by our payment processor (Stripe).\n- category: financial\n  text: Billing address when you supply one for invoicing.\npurposes:\n- purpose: Contract performance\n  text: 'Contract performance (GDPR Art 6(1)(b)): authenticating you, metering credits, processing payments, delivering\n    the service you signed up for.'\n- purpose: Legitimate interest\n  text: 'Legitimate interest (Art 6(1)(f)): preventing abuse, enforcing rate limits, detecting fraud, debugging\n    production issues via request logs.'\n- purpose: Legal obligation\n  text: 'Legal obligation (Art 6(1)(c)): keeping tax-relevant invoices for 7 years under EU bookkeeping rules.'\n- purpose: Consent\n  text: 'Consent (Art 6(1)(a)): marketing emails you opt into.'\nretention:\n- scope: Account data\n  period: 30 days after deletion\n\
  \  text: 'Account data: kept while your account is active, plus 30 days after deletion for restoration, then purged.'\n- scope: API request logs\n  period: 90 days\n  text: 'API request logs: 90 days for debugging + fraud detection, then aggregated-only.'\n- scope: Billing records\n  period: 7 years\n  text: 'Billing records (invoices, tax-relevant data): 7 years per EU accounting rules.'\n- scope: Email event logs\n  period: 12 months\n  text: 'Email event logs (sent / opened / clicked): 12 months, then purged.'\nresidency:\n- region: EU and US\n  text: Servers are located in the EU and US.\ntransfers:\n- mechanism: DPF\n  text: we rely on the EU-US Data Privacy Framework and Standard Contractual Clauses (SCCs) to safeguard it.\n- mechanism: SCC\n  text: Copies of the SCC texts are available on request.\nsubprocessors:\n  url: null\n  text: We share the minimum necessary data with the following processors.\ndpa:\n  available: true\n  url: null\n  text: Each has a signed DPA on file\n\
  deletion:\n  route: email request\n  text: Email [email protected] to exercise any of these rights.\nrights:\n- right: Access\n  text: Access your personal data - we'll send you an export in machine-readable form within 30 days.\n- right: Rectify\n  text: Rectify inaccurate data - edit in-dashboard or email us.\n- right: Erase\n  text: Erase your account and associated data - with the retention exceptions above\n- right: Port\n  text: Port your data to another provider in a standard format.\n- right: Object\n  text: Object to processing based on legitimate interest.\n- right: Withdraw consent\n  text: Withdraw consent at any time for opt-in marketing.\n- right: Complain\n  text: Lodge a complaint with your national data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data.\n"
source_yaml_url: https://artifacts.apis.io/amazon-scraper-api/privacy/amazon-scraper-api-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Amazon Scraper API's own page on 2026-11-09.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- E-Commerce Data
- Amazon
- marketplace data
- Product Intelligence
- Price Monitoring
- Competitor Research
- MCP
- Agent Tooling
---
