---
api_specs:
- filename: coldstate-ai-auth-api-openapi.yml
  format: yaml
  label: ColdState Auth API
  slug: coldstate-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-auth-api-openapi.yml
- filename: coldstate-ai-billing-api-openapi.yml
  format: yaml
  label: ColdState Billing API
  slug: coldstate-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-billing-api-openapi.yml
- filename: coldstate-ai-indexes-api-openapi.yml
  format: yaml
  label: ColdState Indexes API
  slug: coldstate-ai-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-indexes-api-openapi.yml
- filename: coldstate-ai-knowledge-api-openapi.yml
  format: yaml
  label: ColdState Knowledge API
  slug: coldstate-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-knowledge-api-openapi.yml
- filename: coldstate-ai-mcp-api-openapi.yml
  format: yaml
  label: ColdState MCP API
  slug: coldstate-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-mcp-api-openapi.yml
- filename: coldstate-ai-meta-api-openapi.yml
  format: yaml
  label: ColdState Meta API
  slug: coldstate-ai-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-meta-api-openapi.yml
- filename: coldstate-ai-search-api-openapi.yml
  format: yaml
  label: ColdState Search API
  slug: coldstate-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-search-api-openapi.yml
- filename: coldstate-ai-usage-api-openapi.yml
  format: yaml
  label: ColdState Usage API
  slug: coldstate-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldstate-ai/openapi/coldstate-ai-usage-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address
  - category: contact
    text: Company name
  - category: financial
    text: We do not store credit card numbers, CVVs, or full card details on our servers.
  - category: device
    text: IP addresses (for rate limiting and abuse prevention only)
  - category: behavioral
    text: API query counts, timestamps, and associated index identifiers
  - category: other
    text: Documents you send to a custom index are tokenized in memory while the index is built and are not stored.
  deletion:
    route: Delete your account, or email daniel@coldstate.ai to exercise deletion rights
    text: Delete your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management
    text: To create and manage your account
  - purpose: Authentication
    text: To authenticate API requests
  - purpose: Payments
    text: To process payments and manage subscriptions
  - purpose: Rate limiting
    text: To enforce rate limits and usage quotas per your plan tier
  - purpose: Abuse prevention
    text: To detect and prevent abuse or unauthorized access
  - purpose: Service notifications
    text: To send critical service notifications (outages, security alerts, billing issues)
  residency:
  - region: United States
    text: ColdState is based in Ohio, United States. If you access the service from the European Union, United Kingdom, or other jurisdictions with data protection laws, your data will be transferred to and processed in the United States.
  retention:
  - period: 30 days after deletion
    scope: Account data
    text: Account data is retained while your account is active and for 30 days after deletion.
  - period: 12 months
    scope: Usage logs
    text: Usage logs are retained for 12 months for billing reconciliation, then aggregated and anonymized.
  - period: within 24 hours of account deletion
    scope: Index data
    text: Index data (reference ids and derived scoring data — your document text is never stored) is deleted immediately when you delete an index, and within 24 hours of account deletion.
  - period: 24 hours
    scope: IaaS downloads
    text: IaaS downloads expire and are purged after 24 hours.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Correct inaccurate data
  - right: Deletion
    text: Delete your account and associated data
  - right: Portability
    text: Export your data in a portable format
  - right: Objection
    text: Object to processing of your data
  role:
    text: ColdState Inc. ("ColdState," "we," "us," or "our") is an Ohio corporation that operates the ColdState Services search API platform
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your personal information with third parties for marketing purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ColdState
provenance_date: '2026-11-09'
provider_name: ColdState
provider_slug: coldstate-ai
slug: coldstate-ai-privacy-policy
source_date: '2026-11-09'
source_filename: coldstate-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://services.coldstate.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ColdState\naid: coldstate-ai\nurl: https://services.coldstate.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ColdState Inc. (\"ColdState,\" \"we,\" \"us,\" or \"our\") is an Ohio corporation that operates the ColdState Services\n    search API platform\ndata_categories:\n- category: identifying\n  text: Email address\n- category: contact\n  text: Company name\n- category: financial\n  text: We do not store credit card numbers, CVVs, or full card details on our servers.\n- category: device\n  text: IP addresses (for rate limiting and abuse prevention only)\n- category: behavioral\n\
  \  text: API query counts, timestamps, and associated index identifiers\n- category: other\n  text: Documents you send to a custom index are tokenized in memory while the index is built and are not stored.\npurposes:\n- purpose: Account management\n  text: To create and manage your account\n- purpose: Authentication\n  text: To authenticate API requests\n- purpose: Payments\n  text: To process payments and manage subscriptions\n- purpose: Rate limiting\n  text: To enforce rate limits and usage quotas per your plan tier\n- purpose: Abuse prevention\n  text: To detect and prevent abuse or unauthorized access\n- purpose: Service notifications\n  text: To send critical service notifications (outages, security alerts, billing issues)\nretention:\n- scope: Account data\n  period: 30 days after deletion\n  text: Account data is retained while your account is active and for 30 days after deletion.\n- scope: Usage logs\n  period: 12 months\n  text: Usage logs are retained for 12 months for billing\
  \ reconciliation, then aggregated and anonymized.\n- scope: Index data\n  period: within 24 hours of account deletion\n  text: Index data (reference ids and derived scoring data — your document text is never stored) is deleted immediately\n    when you delete an index, and within 24 hours of account deletion.\n- scope: IaaS downloads\n  period: 24 hours\n  text: IaaS downloads expire and are purged after 24 hours.\nresidency:\n- region: United States\n  text: ColdState is based in Ohio, United States. If you access the service from the European Union, United Kingdom,\n    or other jurisdictions with data protection laws, your data will be transferred to and processed in the United\n    States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account, or email daniel@coldstate.ai to exercise deletion rights\n  text: Delete your account and associated data\nrights:\n- right: Access\n  text: Access\
  \ your personal data\n- right: Correction\n  text: Correct inaccurate data\n- right: Deletion\n  text: Delete your account and associated data\n- right: Portability\n  text: Export your data in a portable format\n- right: Objection\n  text: Object to processing of your data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your personal information with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/coldstate-ai/privacy/coldstate-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from ColdState's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Knowledge Base
- Search
- Deterministic Retrieval
- MCP
- AI Agents
- Citations
---
