---
api_specs:
- filename: paidsync-ai-billing-api-openapi.yml
  format: yaml
  label: paidsync-ai Billing API
  slug: paidsync-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-billing-api-openapi.yml
- filename: paidsync-ai-mcp-api-openapi.yml
  format: yaml
  label: paidsync-ai MCP API
  slug: paidsync-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-mcp-api-openapi.yml
- filename: paidsync-ai-paidsync-api-api-openapi.yml
  format: yaml
  label: paidsync-ai PaidSync API
  slug: paidsync-ai-paidsync-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-paidsync-api-api-openapi.yml
- filename: paidsync-ai-payment-api-openapi.yml
  format: yaml
  label: paidsync-ai Payment API
  slug: paidsync-ai-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-payment-api-openapi.yml
- filename: paidsync-ai-subscribe-api-openapi.yml
  format: yaml
  label: paidsync-ai Subscribe API
  slug: paidsync-ai-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidsync-ai/openapi/paidsync-ai-subscribe-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your name, email address, and profile information provided by Google Authentication.
  - category: behavioral
    text: We also collect usage data such as pages visited and features used.
  - category: device
    text: We may collect device information, browser type, and IP address for security and analytics purposes.
  - category: financial
    text: billing records
  deletion:
    route: Settings > Security > Delete account, or email support@paidsync.ai
    text: You can delete your account directly from Settings > Security > Delete account. Type DELETE to confirm.
  dpa:
    available: true
    text: Our Data Processing Agreement governs that relationship and includes the European Commission’s Standard Contractual Clauses
    url: null
  purposes:
  - purpose: provide and maintain service
    text: We use your information to provide and maintain the PaidSync.ai service, process your transactions, send you service-related communications, and improve the platform.
  - purpose: advertising
    text: Additionally, we use this information for site optimization, fraud and security purposes, and advertising.
  residency:
  - region: United States
    text: Our database, its scheduled backups and uploaded files are in the United States, in Google Cloud region us-central1 in Iowa
  retention:
  - period: null
    scope: deleted account data
    text: after a 30-day recovery window (see “Your Rights” below), your profile, the brands you created with each brand’s profile
  - period: 30 days
    scope: application logs
    text: Application logs are kept for 30 days in Google Cloud Logging
  - period: 7 years
    scope: tool call records
    text: Records of the individual tool calls made on your account are kept for 7 years
  - period: 30 days
    scope: Microsoft Clarity recordings
    text: Microsoft keeps recordings for up to 30 days
  rights:
  - right: access, correct, or delete
    text: You have the right to access, correct, or delete your personal data at any time.
  - right: data portability
    text: If you are located in the EU, you have additional rights under GDPR, including the right to data portability
  - right: object
    text: You can also object, under Article 21 GDPR, to processing based on our legitimate interests by emailing support@paidsync.ai .
  - right: lodge complaint
    text: the right to lodge a complaint with a supervisory authority
  role:
    text: We are the data controller of the personal data we decide the purposes for.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: transfers from the EEA and the UK are covered by the Standard Contractual Clauses incorporated in the Data Processing Agreement
  - mechanism: other
    text: We are not certified under the EU-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: paidsync-ai
provenance_date: '2026-11-10'
provider_name: paidsync-ai
provider_slug: paidsync-ai
slug: paidsync-ai-privacy-policy
source_date: '2026-11-10'
source_filename: paidsync-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://paidsync.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: paidsync-ai\naid: paidsync-ai\nurl: https://paidsync.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the data controller of the personal data we decide the purposes for.\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your name, email address, and profile information provided by Google\n    Authentication.\n- category: behavioral\n  text: We also collect usage data such as pages visited and features used.\n- category: device\n  text: We may collect device information, browser type, and IP address for security and analytics purposes.\n-\
  \ category: financial\n  text: billing records\npurposes:\n- purpose: provide and maintain service\n  text: We use your information to provide and maintain the PaidSync.ai service, process your transactions, send\n    you service-related communications, and improve the platform.\n- purpose: advertising\n  text: Additionally, we use this information for site optimization, fraud and security purposes, and advertising.\nretention:\n- scope: deleted account data\n  period: null\n  text: after a 30-day recovery window (see “Your Rights” below), your profile, the brands you created with each\n    brand’s profile\n- scope: application logs\n  period: 30 days\n  text: Application logs are kept for 30 days in Google Cloud Logging\n- scope: tool call records\n  period: 7 years\n  text: Records of the individual tool calls made on your account are kept for 7 years\n- scope: Microsoft Clarity recordings\n  period: 30 days\n  text: Microsoft keeps recordings for up to 30 days\nresidency:\n- region:\
  \ United States\n  text: Our database, its scheduled backups and uploaded files are in the United States, in Google Cloud region\n    us-central1 in Iowa\ntransfers:\n- mechanism: SCC\n  text: transfers from the EEA and the UK are covered by the Standard Contractual Clauses incorporated in the Data\n    Processing Agreement\n- mechanism: other\n  text: We are not certified under the EU-US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing Agreement governs that relationship and includes the European Commission’s Standard\n    Contractual Clauses\ndeletion:\n  route: Settings > Security > Delete account, or email support@paidsync.ai\n  text: You can delete your account directly from Settings > Security > Delete account. Type DELETE to confirm.\nrights:\n- right: access, correct, or delete\n  text: You have the right to access, correct, or delete your personal data at any time.\n- right: data portability\n\
  \  text: If you are located in the EU, you have additional rights under GDPR, including the right to data portability\n- right: object\n  text: You can also object, under Article 21 GDPR, to processing based on our legitimate interests by emailing\n    support@paidsync.ai .\n- right: lodge complaint\n  text: the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/paidsync-ai/privacy/paidsync-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from paidsync-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Advertising
- Automation
- Marketing
---
