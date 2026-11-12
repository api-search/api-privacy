---
api_specs:
- filename: clstr-news-openapi-generated.yml
  format: yaml
  label: CLSTR API
  slug: clstr-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clstr-news/openapi/_ae-authored/clstr-news-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: we store your email address, display name, and (if provided by Google) profile picture URL
  - category: financial
    text: We store a Stripe customer/subscription identifier and the plan status. We do not see or store card details.
  - category: behavioral
    text: Items you create on the service (followed topics, briefing and monitor preferences) are stored against your account.
  - category: device
    text: we store a cryptographic hash of each key (never the key itself), its label and creation date
  - category: location
    text: 'coarse request context: country, the Cloudflare edge location, the network operator (for example a hosting provider)'
  - category: identifying
    text: Our infrastructure processes standard request data such as IP address and user agent for security, abuse prevention, and rate limiting.
  deletion:
    route: Email support@clstr.news to request account deletion
    text: To request account deletion or to exercise any of these rights, email support@clstr.news and we will action your request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: We process account, subscription, product and API data to provide the service you signed up for.
  - purpose: Running, securing and improving the service
    text: We process usage records, logs and service emails on the basis of our legitimate interest in running, securing and improving the service
  - purpose: Usage statistics
    text: For analytics we use Simple Analytics , which is cookieless and does not profile visitors.
  retention:
  - period: null
    scope: Account and product data
    text: We keep account and product data for as long as your account exists.
  - period: null
    scope: Logs
    text: These logs are short-lived.
  - period: 7 days
    scope: Session cookie
    text: Expires after 7 days of inactivity.
  - period: 90 days
    scope: Referral memory
    text: expires after 90 days
  rights:
  - right: access
    text: you may have the right to access, correct, export, or delete your personal data, and to object to certain processing
  - right: object to processing
    text: you can object to that processing at any time by emailing us
  role:
    text: CLSTR is operated as an independent project based in the EU.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Third parties that receive your data Cloudflare : hosting and web services. Google : sign-in, only when you choose to sign in with Google. Stripe : subscription payments, only for paying users. Simple Analytics : privacy-friendly, cookieless usage statistics. Turso : database hosting; stores account and product data. AI model providers : process news content and search queries.'
    url: null
  transfers:
  - mechanism: other
    text: Some of these providers process data in the United States, under their standard data protection terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CLSTR
provenance_date: '2026-11-09'
provider_name: CLSTR
provider_slug: clstr-news
slug: clstr-news-privacy-policy
source_date: '2026-11-09'
source_filename: clstr-news-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clstr.news/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CLSTR\naid: clstr-news\nurl: https://clstr.news/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CLSTR is operated as an independent project based in the EU.\ndata_categories:\n- category: contact\n  text: we store your email address, display name, and (if provided by Google) profile picture URL\n- category: financial\n  text: We store a Stripe customer/subscription identifier and the plan status. We do not see or store card details.\n- category: behavioral\n  text: Items you create on the service (followed topics, briefing and monitor preferences) are stored against your\n    account.\n\
  - category: device\n  text: we store a cryptographic hash of each key (never the key itself), its label and creation date\n- category: location\n  text: 'coarse request context: country, the Cloudflare edge location, the network operator (for example a hosting\n    provider)'\n- category: identifying\n  text: Our infrastructure processes standard request data such as IP address and user agent for security, abuse\n    prevention, and rate limiting.\npurposes:\n- purpose: Provide the service\n  text: We process account, subscription, product and API data to provide the service you signed up for.\n- purpose: Running, securing and improving the service\n  text: We process usage records, logs and service emails on the basis of our legitimate interest in running, securing\n    and improving the service\n- purpose: Usage statistics\n  text: For analytics we use Simple Analytics , which is cookieless and does not profile visitors.\nretention:\n- scope: Account and product data\n  period: null\n\
  \  text: We keep account and product data for as long as your account exists.\n- scope: Logs\n  period: null\n  text: These logs are short-lived.\n- scope: Session cookie\n  period: 7 days\n  text: Expires after 7 days of inactivity.\n- scope: Referral memory\n  period: 90 days\n  text: expires after 90 days\nresidency: []\ntransfers:\n- mechanism: other\n  text: Some of these providers process data in the United States, under their standard data protection terms.\nsubprocessors:\n  url: null\n  text: 'Third parties that receive your data Cloudflare : hosting and web services. Google : sign-in, only when\n    you choose to sign in with Google. Stripe : subscription payments, only for paying users. Simple Analytics :\n    privacy-friendly, cookieless usage statistics. Turso : database hosting; stores account and product data. AI\n    model providers : process news content and search queries.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@clstr.news\
  \ to request account deletion\n  text: To request account deletion or to exercise any of these rights, email support@clstr.news and we will action\n    your request.\nrights:\n- right: access\n  text: you may have the right to access, correct, export, or delete your personal data, and to object to certain\n    processing\n- right: object to processing\n  text: you can object to that processing at any time by emailing us\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clstr-news/privacy/clstr-news-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 19 quoted statements, read from CLSTR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- News API
- MCP
- AI Agents
- News Clustering
- Media Monitoring
- Summarization
---
