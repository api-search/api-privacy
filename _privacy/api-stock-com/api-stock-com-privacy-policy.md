---
api_specs:
- filename: api-stock-com-account-management-api-openapi.yml
  format: yaml
  label: API Stock Account Management API
  slug: api-stock-com-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-account-management-api-openapi.yml
- filename: api-stock-com-agent-api-openapi.yml
  format: yaml
  label: API Stock Agent API
  slug: api-stock-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-agent-api-openapi.yml
- filename: api-stock-com-catalog-api-openapi.yml
  format: yaml
  label: API Stock Catalog API
  slug: api-stock-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-catalog-api-openapi.yml
- filename: api-stock-com-costs-api-openapi.yml
  format: yaml
  label: API Stock Costs API
  slug: api-stock-com-costs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-costs-api-openapi.yml
- filename: api-stock-com-generations-api-openapi.yml
  format: yaml
  label: API Stock Generations API
  slug: api-stock-com-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-generations-api-openapi.yml
- filename: api-stock-com-llm-api-openapi.yml
  format: yaml
  label: API Stock LLM API
  slug: api-stock-com-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-llm-api-openapi.yml
- filename: api-stock-com-task-management-api-openapi.yml
  format: yaml
  label: API Stock Task Management API
  slug: api-stock-com-task-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api-stock-com/openapi/api-stock-com-task-management-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: Account data — your email address, and the name and avatar your sign-in provider gives us if you sign in with Google or GitHub.
  - category: identifying
    text: API keys — the keys issued to your account, their settings, and when each was last used.
  - category: behavioral
    text: 'Generation data — for each request: the model, the parameters you sent (including your prompt and any media URLs you referenced), the status, timings, the price charged, and any error message returned.'
  - category: financial
    text: Payment data — the amount, currency, method, status and the acquirer's transaction reference.
  - category: device
    text: Device data — when you visit the website we ask our identity service for a device identifier derived from your browser and device.
  - category: behavioral
    text: Analytics data — page URLs, traffic sources, campaign parameters, referrers, device and browser information, Google Analytics client and session identifiers, and selected product-funnel events.
  - category: location
    text: Technical data — IP address and derived country, used for security, abuse prevention and routing.
  deletion:
    route: delete your account from the dashboard or by request
    text: Account and session data is deleted when you delete your account, except for what we must retain by law or to defend a legal claim.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: To provide the Service — running generations, delivering results, and firing the webhooks you configure.
  - purpose: Pricing, billing and refunds
    text: To price, charge and refund correctly, and to keep the usage history you see in the dashboard.
  - purpose: Authentication and account security
    text: To authenticate you and keep accounts secure.
  - purpose: Fraud and abuse prevention
    text: To detect, investigate and prevent fraud, abuse and breaches of our acceptable-use rules.
  - purpose: Reliability and improvement
    text: To operate and improve reliability — monitoring, error diagnosis, capacity planning.
  - purpose: Analytics measurement
    text: To measure campaign, page and signup performance using Google Analytics.
  retention:
  - period: retention period shown in your usage log
    scope: Generated media
    text: Generated media is kept for the retention period shown in your usage log and is then deleted from our storage.
  - period: typically several years
    scope: Payment and accounting records
    text: Payment and accounting records are kept for as long as tax and accounting law requires, typically several years, even after an account is closed.
  - period: null
    scope: Account and session data
    text: Account and session data is deleted when you delete your account, except for what we must retain by law or to defend a legal claim.
  - period: up to 400 days
    scope: Google Analytics identity links
    text: Google Analytics identity links are kept for up to 400 days after the browser was last seen
  - period: 14-month retention
    scope: Google Analytics event data
    text: Google Analytics event data is configured for 14-month retention.
  - period: 30 days
    scope: Successfully delivered server-event records
    text: successfully delivered server-event records are normally removed after 30 days.
  rights:
  - right: access
    text: access the personal data we hold about you, and receive a copy of it in a portable format
  - right: correction
    text: have inaccurate data corrected
  - right: deletion
    text: have your data deleted, subject to the retention we are legally required to apply
  - right: restriction or objection
    text: restrict or object to processing we carry out on the basis of legitimate interests
  - right: withdraw consent
    text: withdraw consent where processing is based on consent, without affecting processing already carried out
  - right: complaint
    text: lodge a complaint with your local data protection authority
  role:
    text: API Stock is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not use your prompts, media or outputs to train models, and we do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where personal data is transferred from the EEA or the UK, we rely on an adequacy decision where one exists, and otherwise on Standard Contractual Clauses with appropriate additional safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: API Stock
provenance_date: '2026-11-09'
provider_name: API Stock
provider_slug: api-stock-com
slug: api-stock-com-privacy-policy
source_date: '2026-11-09'
source_filename: api-stock-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://api-stock.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: API Stock\naid: api-stock-com\nurl: https://api-stock.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: API Stock is the controller of the personal data described here.\ndata_categories:\n- category: contact\n  text: Account data — your email address, and the name and avatar your sign-in provider gives us if you sign in\n    with Google or GitHub.\n- category: identifying\n  text: API keys — the keys issued to your account, their settings, and when each was last used.\n- category: behavioral\n  text: 'Generation data — for each request: the model, the parameters you sent (including\
  \ your prompt and any media\n    URLs you referenced), the status, timings, the price charged, and any error message returned.'\n- category: financial\n  text: Payment data — the amount, currency, method, status and the acquirer's transaction reference.\n- category: device\n  text: Device data — when you visit the website we ask our identity service for a device identifier derived from\n    your browser and device.\n- category: behavioral\n  text: Analytics data — page URLs, traffic sources, campaign parameters, referrers, device and browser information,\n    Google Analytics client and session identifiers, and selected product-funnel events.\n- category: location\n  text: Technical data — IP address and derived country, used for security, abuse prevention and routing.\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service — running generations, delivering results, and firing the webhooks you configure.\n- purpose: Pricing, billing and refunds\n  text: To price, charge\
  \ and refund correctly, and to keep the usage history you see in the dashboard.\n- purpose: Authentication and account security\n  text: To authenticate you and keep accounts secure.\n- purpose: Fraud and abuse prevention\n  text: To detect, investigate and prevent fraud, abuse and breaches of our acceptable-use rules.\n- purpose: Reliability and improvement\n  text: To operate and improve reliability — monitoring, error diagnosis, capacity planning.\n- purpose: Analytics measurement\n  text: To measure campaign, page and signup performance using Google Analytics.\nretention:\n- scope: Generated media\n  period: retention period shown in your usage log\n  text: Generated media is kept for the retention period shown in your usage log and is then deleted from our storage.\n- scope: Payment and accounting records\n  period: typically several years\n  text: Payment and accounting records are kept for as long as tax and accounting law requires, typically several\n    years, even after an account\
  \ is closed.\n- scope: Account and session data\n  period: null\n  text: Account and session data is deleted when you delete your account, except for what we must retain by law\n    or to defend a legal claim.\n- scope: Google Analytics identity links\n  period: up to 400 days\n  text: Google Analytics identity links are kept for up to 400 days after the browser was last seen\n- scope: Google Analytics event data\n  period: 14-month retention\n  text: Google Analytics event data is configured for 14-month retention.\n- scope: Successfully delivered server-event records\n  period: 30 days\n  text: successfully delivered server-event records are normally removed after 30 days.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where personal data is transferred from the EEA or the UK, we rely on an adequacy decision where one exists,\n    and otherwise on Standard Contractual Clauses with appropriate additional safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: delete your account from the dashboard or by request\n  text: Account and session data is deleted when you delete your account, except for what we must retain by law\n    or to defend a legal claim.\nrights:\n- right: access\n  text: access the personal data we hold about you, and receive a copy of it in a portable format\n- right: correction\n  text: have inaccurate data corrected\n- right: deletion\n  text: have your data deleted, subject to the retention we are legally required to apply\n- right: restriction or objection\n  text: restrict or object to processing we carry out on the basis of legitimate interests\n- right: withdraw consent\n  text: withdraw consent where processing is based on consent, without affecting processing already carried out\n- right: complaint\n  text: lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use your prompts, media or outputs\
  \ to train models, and we do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/api-stock-com/privacy/api-stock-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from API Stock's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- LLM
- Platform
---
