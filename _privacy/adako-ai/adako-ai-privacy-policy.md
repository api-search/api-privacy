---
api_specs:
- filename: adako-ai-adako-api-openapi.yml
  format: yaml
  label: Adako Adako API
  slug: adako-ai-adako-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-adako-api-openapi.yml
- filename: adako-ai-chatgpt-ads-api-openapi.yml
  format: yaml
  label: Adako ChatGPT Ads API
  slug: adako-ai-chatgpt-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-chatgpt-ads-api-openapi.yml
- filename: adako-ai-discovery-api-openapi.yml
  format: yaml
  label: Adako Discovery API
  slug: adako-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-discovery-api-openapi.yml
- filename: adako-ai-google-ads-api-openapi.yml
  format: yaml
  label: Adako Google Ads API
  slug: adako-ai-google-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-google-ads-api-openapi.yml
- filename: adako-ai-linkedin-ads-api-openapi.yml
  format: yaml
  label: Adako LinkedIn Ads API
  slug: adako-ai-linkedin-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-linkedin-ads-api-openapi.yml
- filename: adako-ai-meta-ads-api-openapi.yml
  format: yaml
  label: Adako Meta Ads API
  slug: adako-ai-meta-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-meta-ads-api-openapi.yml
- filename: adako-ai-tiktok-ads-api-openapi.yml
  format: yaml
  label: Adako TikTok Ads API
  slug: adako-ai-tiktok-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adako-ai/openapi/adako-ai-tiktok-ads-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address and password.
  - category: contact
    text: Name, email address and password.
  - category: financial
    text: Your plan, subscription status and billing period, the Creem customer and subscription IDs, and task counts for each period.
  - category: location
    text: Google works out an approximate location (country and city) from your IP address and does not store the address.
  - category: device
    text: Session records with the IP address and browser user agent of each sign-in, and when the session expires.
  - category: communication
    text: Messages you send us, and our replies.
  deletion:
    route: Settings → Delete account, or email support@adako.ai
    text: When you delete your account in Settings, we delete your personal data at once; when you ask by email, within 30 days.
  dpa:
    available: true
    text: Write to support@adako.ai for a data processing agreement.
    url: null
  purposes:
  - purpose: Account and sign-in
    text: Create your account, sign you in and keep sessions secure
  - purpose: Running connected tools
    text: Connect ad accounts and run the tools you and your AI assistant call
  - purpose: Website analytics
    text: 'Measure how the website is used with Google Analytics: visits, pages read and where visitors come from'
  residency:
  - region: United States (Virginia)
    text: Adako’s servers and database are in the United States (Virginia)
  retention:
  - period: While your account is open
    scope: Account and connection data
    text: While your account is open
  - period: 90 days rolling
    scope: Synced daily metrics
    text: Synced daily metrics 90 days rolling; older days are deleted every day, whether or not the account syncs
  - period: Up to 14 months
    scope: Google Analytics event data
    text: Google Analytics event data Up to 14 months, then deleted by Google
  - period: null
    scope: Lead form submissions
    text: 'Adako does not store submissions: they are not kept in tool-call records, caches or the synced history.'
  rights:
  - right: access/portability
    text: give you a copy of your personal data in a portable format
  - right: correction
    text: correct data that is wrong
  - right: deletion
    text: delete your data (see Deleting your data )
  - right: objection
    text: stop processing it for a purpose you object to
  role:
    text: We are the controller of the personal data described in this policy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information, and have not done so in the past 12 months.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: the EU–US Data Privacy Framework for certified recipients
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses and the UK Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Adako
provenance_date: '2026-11-09'
provider_name: Adako
provider_slug: adako-ai
slug: adako-ai-privacy-policy
source_date: '2026-11-09'
source_filename: adako-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adako.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Adako\naid: adako-ai\nurl: https://adako.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal data described in this policy\ndata_categories:\n- category: identifying\n  text: Name, email address and password.\n- category: contact\n  text: Name, email address and password.\n- category: financial\n  text: Your plan, subscription status and billing period, the Creem customer and subscription IDs, and task counts\n    for each period.\n- category: location\n  text: Google works out an approximate location (country and city) from your IP address and does\
  \ not store the\n    address.\n- category: device\n  text: Session records with the IP address and browser user agent of each sign-in, and when the session expires.\n- category: communication\n  text: Messages you send us, and our replies.\npurposes:\n- purpose: Account and sign-in\n  text: Create your account, sign you in and keep sessions secure\n- purpose: Running connected tools\n  text: Connect ad accounts and run the tools you and your AI assistant call\n- purpose: Website analytics\n  text: 'Measure how the website is used with Google Analytics: visits, pages read and where visitors come from'\nretention:\n- scope: Account and connection data\n  period: While your account is open\n  text: While your account is open\n- scope: Synced daily metrics\n  period: 90 days rolling\n  text: Synced daily metrics 90 days rolling; older days are deleted every day, whether or not the account syncs\n- scope: Google Analytics event data\n  period: Up to 14 months\n  text: Google Analytics event\
  \ data Up to 14 months, then deleted by Google\n- scope: Lead form submissions\n  period: null\n  text: 'Adako does not store submissions: they are not kept in tool-call records, caches or the synced history.'\nresidency:\n- region: United States (Virginia)\n  text: Adako’s servers and database are in the United States (Virginia)\ntransfers:\n- mechanism: DPF\n  text: the EU–US Data Privacy Framework for certified recipients\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses and the UK Addendum\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Write to support@adako.ai for a data processing agreement.\ndeletion:\n  route: Settings → Delete account, or email support@adako.ai\n  text: When you delete your account in Settings, we delete your personal data at once; when you ask by email, within\n    30 days.\nrights:\n- right: access/portability\n  text: give you a copy of your personal data in a portable format\n- right:\
  \ correction\n  text: correct data that is wrong\n- right: deletion\n  text: delete your data (see Deleting your data )\n- right: objection\n  text: stop processing it for a purpose you object to\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information, and have not done so in the past 12 months.\n"
source_yaml_url: https://artifacts.apis.io/adako-ai/privacy/adako-ai-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Adako's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Marketing
- MCP
- Automation
---
