---
api_specs:
- filename: loa-healthcare-pricing-api-entities-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Entities API
  slug: loa-healthcare-pricing-api-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-entities-api-openapi.yml
- filename: loa-healthcare-pricing-api-entity-analytics-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Entity Analytics API
  slug: loa-healthcare-pricing-api-entity-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-entity-analytics-api-openapi.yml
- filename: loa-healthcare-pricing-api-entity-updates-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Entity Updates API
  slug: loa-healthcare-pricing-api-entity-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-entity-updates-api-openapi.yml
- filename: loa-healthcare-pricing-api-prices-api-openapi.yml
  format: yaml
  label: Loa Healthcare Pricing API Prices API
  slug: loa-healthcare-pricing-api-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loa-healthcare-pricing-api/openapi/loa-healthcare-pricing-api-prices-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, postal address, e-mail, phone, account credentials
  - category: health
    text: Insurance & Health-Related Data (may be PHI) Plan name, member ID, deductible status, clinician choices, claim documents, communications with providers
  - category: financial
    text: Payment-card token, subscription tier, billing address
  - category: device
    text: IP address, device ID, browser type, session logs, cookies, pixels
  - category: communication
    text: Messages you send to Loa Care or that we send on your behalf to providers
  deletion:
    route: Email request to privacy contact
    text: Request account closure through the same contact process.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Services
    text: Provide the Services (e.g., authenticate you, fetch insurance benefits, generate pricing e-mails, prepare claim forms).
  - purpose: Analytics and model training
    text: Analyze and improve our Site, train models, and develop new features (using aggregated or de-identified data where feasible).
  - purpose: Comply with law
    text: Comply with law (HIPAA, state privacy laws, consumer-protection statutes, accounting rules, law-enforcement requests).
  residency:
  - region: United States
    text: Loa Care is based in the United States and uses service providers with international infrastructure and operations.
  retention:
  - period: life of your account plus 7 years
    scope: Account Data & PHI
    text: 'Account Data & PHI: kept for the life of your account plus 7 years (standard healthcare claims retention) unless a longer period is required by law or requested by you.'
  - period: at least 7 years
    scope: Payment records
    text: 'Payment records: kept for at least 7 years under tax law.'
  - period: 24 months
    scope: Logs & device data
    text: 'Logs & device data: kept for 24 months then aggregated or deleted.'
  - period: 5 years
    scope: Practice outreach records
    text: 'Practice outreach records (each e-mail sent, where the address came from, and any claim or reply): kept for 5 years.'
  rights:
  - right: access
    text: access or port your personal information
  - right: correction
    text: correct inaccuracies
  - right: deletion
    text: delete certain data
  - right: opt-out of targeted advertising, data sales, or certain profiling
    text: opt-out of targeted advertising, data sales, or certain profiling
  - right: appeal
    text: appeal denials of requests
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your PHI or other sensitive data.
  subprocessors:
    text: Service providers. Vercel and Cloudflare provide hosting, request delivery, and related infrastructure; Supabase provides database and authentication services; Mixpanel processes operational analytics.
    url: null
  transfers:
  - mechanism: other
    text: Information may be processed or accessed in the United States and other countries where those providers operate, including for network delivery, security, and support.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Loa Healthcare Pricing API
provenance_date: '2026-11-09'
provider_name: Loa Healthcare Pricing API
provider_slug: loa-healthcare-pricing-api
slug: loa-healthcare-pricing-api-privacy-policy
source_date: '2026-11-09'
source_filename: loa-healthcare-pricing-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.loacare.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Loa Healthcare Pricing API\naid: loa-healthcare-pricing-api\nurl: https://www.loacare.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, postal address, e-mail, phone, account credentials\n- category: health\n  text: Insurance & Health-Related Data (may be PHI) Plan name, member ID, deductible status, clinician choices,\n    claim documents, communications with providers\n- category: financial\n  text: Payment-card token, subscription tier, billing address\n- category: device\n  text: IP address, device ID, browser type,\
  \ session logs, cookies, pixels\n- category: communication\n  text: Messages you send to Loa Care or that we send on your behalf to providers\npurposes:\n- purpose: Provide the Services\n  text: Provide the Services (e.g., authenticate you, fetch insurance benefits, generate pricing e-mails, prepare\n    claim forms).\n- purpose: Analytics and model training\n  text: Analyze and improve our Site, train models, and develop new features (using aggregated or de-identified\n    data where feasible).\n- purpose: Comply with law\n  text: Comply with law (HIPAA, state privacy laws, consumer-protection statutes, accounting rules, law-enforcement\n    requests).\nretention:\n- scope: Account Data & PHI\n  period: life of your account plus 7 years\n  text: 'Account Data & PHI: kept for the life of your account plus 7 years (standard healthcare claims retention)\n    unless a longer period is required by law or requested by you.'\n- scope: Payment records\n  period: at least 7 years\n  text: 'Payment\
  \ records: kept for at least 7 years under tax law.'\n- scope: Logs & device data\n  period: 24 months\n  text: 'Logs & device data: kept for 24 months then aggregated or deleted.'\n- scope: Practice outreach records\n  period: 5 years\n  text: 'Practice outreach records (each e-mail sent, where the address came from, and any claim or reply): kept\n    for 5 years.'\nresidency:\n- region: United States\n  text: Loa Care is based in the United States and uses service providers with international infrastructure and\n    operations.\ntransfers:\n- mechanism: other\n  text: Information may be processed or accessed in the United States and other countries where those providers\n    operate, including for network delivery, security, and support.\nsubprocessors:\n  url: null\n  text: Service providers. Vercel and Cloudflare provide hosting, request delivery, and related infrastructure;\n    Supabase provides database and authentication services; Mixpanel processes operational analytics.\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to privacy contact\n  text: Request account closure through the same contact process.\nrights:\n- right: access\n  text: access or port your personal information\n- right: correction\n  text: correct inaccuracies\n- right: deletion\n  text: delete certain data\n- right: opt-out of targeted advertising, data sales, or certain profiling\n  text: opt-out of targeted advertising, data sales, or certain profiling\n- right: appeal\n  text: appeal denials of requests\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your PHI or other sensitive data.\n"
source_yaml_url: https://artifacts.apis.io/loa-healthcare-pricing-api/privacy/loa-healthcare-pricing-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Loa Healthcare Pricing API's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Price Transparency
- medical pricing
- Hospitals
- Providers
- Provider Directory
- hospital prices
- CPT
- HCPCS
- MCP
- Agent-Native
- OpenAPI
- Llms.txt
---
