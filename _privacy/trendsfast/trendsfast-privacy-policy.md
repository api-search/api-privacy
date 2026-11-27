---
api_specs:
- filename: trendsfast-next-move-api-openapi.yml
  format: yaml
  label: TrendsFast Next Move API
  slug: trendsfast-next-move-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trendsfast/openapi/trendsfast-next-move-api-openapi.yml
- filename: trendsfast-next-moves-api-openapi.yml
  format: yaml
  label: TrendsFast Next Moves API
  slug: trendsfast-next-moves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trendsfast/openapi/trendsfast-next-moves-api-openapi.yml
- filename: trendsfast-projects-api-openapi.yml
  format: yaml
  label: TrendsFast Projects API
  slug: trendsfast-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trendsfast/openapi/trendsfast-projects-api-openapi.yml
- filename: trendsfast-public-api-openapi.yml
  format: yaml
  label: TrendsFast Public API
  slug: trendsfast-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trendsfast/openapi/trendsfast-public-api-openapi.yml
- filename: trendsfast-trends-api-openapi.yml
  format: yaml
  label: TrendsFast Trends API
  slug: trendsfast-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trendsfast/openapi/trendsfast-trends-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Trends Fast stores the corresponding authentication ID, normalized email address, and—when supplied by the identity provider—a bounded display name and HTTPS avatar URL.
  - category: contact
    text: If you explicitly join the historical product-interest form, we also store the normalized email address and consent record needed to contact you about that launch.
  - category: location
    text: an approximate location that Google derives from your IP address
  - category: device
    text: your browser and device type
  - category: behavioral
    text: We store your submitted product URL, proposed website profile, confirmed product context, permitted research excerpts, Daily Trend Briefs, generated drafts, saved edits and feedback.
  deletion:
    route: verified support request
    text: Full account or project deletion requires a verified support request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate account and enforce limits
    text: We also keep the usage, trial, subscription and security records needed to operate your account and enforce its limits.
  - purpose: billing and security
    text: For billing and security we keep a usage record of each call
  retention:
  - period: 30-day
    scope: marketing results
    text: Marketing results have a 30-day retention deadline
  - period: 90-day
    scope: scan and analytics policy
    text: The current scan and analytics policy uses a 90-day retention target.
  - period: 180 days
    scope: historical launch-interest consent
    text: Historical launch-interest consent expires after 180 days unless renewed.
  - period: 30 days
    scope: shared result links
    text: after at most 30 days
  rights:
  - right: access and deletion requests
    text: For privacy, access or deletion requests, contact meestierolff@gmail.com
  - right: export retained marketing data
    text: You can export your retained marketing data from the dashboard.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: data that reaches Google in the United States is covered by Google's certification under the EU–US Data Privacy Framework
  - mechanism: other
    text: Supabase and Cloudflare may process data in other countries under their own applicable terms and transfer safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TrendsFast
provenance_date: '2026-11-10'
provider_name: TrendsFast
provider_slug: trendsfast
slug: trendsfast-privacy-policy
source_date: '2026-11-10'
source_filename: trendsfast-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://trendsfast.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TrendsFast\naid: trendsfast\nurl: https://trendsfast.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Trends Fast stores the corresponding authentication ID, normalized email address, and—when supplied by the\n    identity provider—a bounded display name and HTTPS avatar URL.\n- category: contact\n  text: If you explicitly join the historical product-interest form, we also store the normalized email address\n    and consent record needed to contact you about that launch.\n- category: location\n  text: an approximate location\
  \ that Google derives from your IP address\n- category: device\n  text: your browser and device type\n- category: behavioral\n  text: We store your submitted product URL, proposed website profile, confirmed product context, permitted research\n    excerpts, Daily Trend Briefs, generated drafts, saved edits and feedback.\npurposes:\n- purpose: operate account and enforce limits\n  text: We also keep the usage, trial, subscription and security records needed to operate your account and enforce\n    its limits.\n- purpose: billing and security\n  text: For billing and security we keep a usage record of each call\nretention:\n- scope: marketing results\n  period: 30-day\n  text: Marketing results have a 30-day retention deadline\n- scope: scan and analytics policy\n  period: 90-day\n  text: The current scan and analytics policy uses a 90-day retention target.\n- scope: historical launch-interest consent\n  period: 180 days\n  text: Historical launch-interest consent expires after 180 days\
  \ unless renewed.\n- scope: shared result links\n  period: 30 days\n  text: after at most 30 days\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: data that reaches Google in the United States is covered by Google's certification under the EU–US Data\n    Privacy Framework\n- mechanism: other\n  text: Supabase and Cloudflare may process data in other countries under their own applicable terms and transfer\n    safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: verified support request\n  text: Full account or project deletion requires a verified support request\nrights:\n- right: access and deletion requests\n  text: For privacy, access or deletion requests, contact meestierolff@gmail.com\n- right: export retained marketing data\n  text: You can export your retained marketing data from the dashboard.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trendsfast/privacy/trendsfast-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from TrendsFast's own page on 2026-11-10.
synthetic: false
tags:
- Trends
- Social Media
- Search
- Artificial Intelligence
---
