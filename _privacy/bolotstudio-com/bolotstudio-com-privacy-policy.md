---
api_specs:
- filename: bolotstudio-com-authentication-api-openapi.yml
  format: yaml
  label: Bolot Studio Authentication API
  slug: bolotstudio-com-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-authentication-api-openapi.yml
- filename: bolotstudio-com-discovery-api-openapi.yml
  format: yaml
  label: Bolot Studio Discovery API
  slug: bolotstudio-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-discovery-api-openapi.yml
- filename: bolotstudio-com-feeds-api-openapi.yml
  format: yaml
  label: Bolot Studio Feeds API
  slug: bolotstudio-com-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-feeds-api-openapi.yml
- filename: bolotstudio-com-mcp-api-openapi.yml
  format: yaml
  label: Bolot Studio MCP API
  slug: bolotstudio-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-mcp-api-openapi.yml
- filename: bolotstudio-com-products-api-openapi.yml
  format: yaml
  label: Bolot Studio Products API
  slug: bolotstudio-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolotstudio-com/openapi/bolotstudio-com-products-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email address, shipping address, and phone number (optional) to process and deliver your orders.
  - category: financial
    text: Payment details are processed securely through Shopify Payments. We never store your full card details.
  - category: device
    text: IP address, browser type, pages visited, and time spent on our site to improve our services.
  - category: other
    text: Files uploaded for custom prints may be stored in Google Cloud Storage and processed through Google Gemini/Imagen or Anthropic-supported features when those workflows are used.
  - category: behavioral
    text: We analyse browsing patterns (pages visited, time spent, products viewed) to classify your shopping intent into categories (e.g., casual browser, ready-to-buy).
  deletion:
    route: Email support@bolotstudio.com
    text: Email support@bolotstudio.com. We respond without undue delay and within one month after receiving the request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Order processing
    text: To process and fulfill your orders, send confirmations and shipping updates.
  - purpose: Customer support
    text: To respond to your questions, requests, and provide assistance when needed.
  - purpose: Service improvement
    text: To improve our website, products, and overall customer experience.
  - purpose: Marketing
    text: With your consent, to send promotional offers and newsletters.
  - purpose: Marketing personalisation
    text: With your marketing consent, we use your purchase history and browsing behaviour to show you relevant advertisements on third-party platforms (Meta, TikTok, Google).
  residency:
  - region: EU
    text: Upstash Inc. – Cache and session storage (EU-West region)
  - region: Poland/EU
    text: Fakturownia sp. z o.o. – Invoice management (Poland, EU – no transfer outside EEA)
  retention:
  - period: 5 years
    scope: Order and transaction data
    text: Generally 5 years for accounting and tax records, counted under the rule applicable to the relevant year or period
  - period: Until account deletion request or 3 years of inactivity
    scope: Account information
    text: Account Information Until account deletion request or 3 years of inactivity
  - period: Until consent withdrawal, or maximum 3 years from last active engagement
    scope: Marketing preferences
    text: Marketing Preferences Until consent withdrawal, or maximum 3 years from last active engagement
  - period: maximum of 24 hours
    scope: AI shopping assistant chat
    text: We store them on our servers for a maximum of 24 hours, after which they are deleted automatically.
  - period: 3 years from last interaction
    scope: Customer support records
    text: Customer Support Records 3 years from last interaction
  - period: 3 years
    scope: Consent records
    text: Consent Records 3 years (GDPR compliance documentation)
  rights:
  - right: Access
    text: Request a copy of all personal data we hold about you.
  - right: Rectification
    text: Request correction of any inaccurate or incomplete data.
  - right: Erasure
    text: Request deletion of your personal data from our systems.
  - right: Portability
    text: Receive your data in a machine-readable format.
  - right: Object
    text: Object to processing of your data for direct marketing.
  - right: Withdraw consent
    text: Withdraw your consent for data processing at any time.
  role:
    text: Data Controller Legal Entity BOLOT Sp. z o.o.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We do not sell personal data for money.
  subprocessors:
    text: Service providers may receive data where needed.
    url: null
  transfers:
  - mechanism: DPF
    text: Stripe, Inc. USA EU-US Data Privacy Framework & Standard Contractual Clauses (SCCs)
  - mechanism: SCC
    text: Anthropic – AI-powered features (USA, SCCs)
  - mechanism: other
    text: TikTok (ByteDance Ltd.) USA, Singapore, and potentially the People's Republic of China
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bolot Studio
provenance_date: '2026-11-09'
provider_name: Bolot Studio
provider_slug: bolotstudio-com
slug: bolotstudio-com-privacy-policy
source_date: '2026-11-09'
source_filename: bolotstudio-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bolotstudio.com/en/pages/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bolot Studio\naid: bolotstudio-com\nurl: https://bolotstudio.com/en/pages/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data Controller Legal Entity BOLOT Sp. z o.o.\ndata_categories:\n- category: contact\n  text: Name, email address, shipping address, and phone number (optional) to process and deliver your orders.\n- category: financial\n  text: Payment details are processed securely through Shopify Payments. We never store your full card details.\n- category: device\n  text: IP address, browser type, pages visited, and time spent on our site to improve our services.\n- category:\
  \ other\n  text: Files uploaded for custom prints may be stored in Google Cloud Storage and processed through Google Gemini/Imagen\n    or Anthropic-supported features when those workflows are used.\n- category: behavioral\n  text: We analyse browsing patterns (pages visited, time spent, products viewed) to classify your shopping intent\n    into categories (e.g., casual browser, ready-to-buy).\npurposes:\n- purpose: Order processing\n  text: To process and fulfill your orders, send confirmations and shipping updates.\n- purpose: Customer support\n  text: To respond to your questions, requests, and provide assistance when needed.\n- purpose: Service improvement\n  text: To improve our website, products, and overall customer experience.\n- purpose: Marketing\n  text: With your consent, to send promotional offers and newsletters.\n- purpose: Marketing personalisation\n  text: With your marketing consent, we use your purchase history and browsing behaviour to show you relevant advertisements\n\
  \    on third-party platforms (Meta, TikTok, Google).\nretention:\n- scope: Order and transaction data\n  period: 5 years\n  text: Generally 5 years for accounting and tax records, counted under the rule applicable to the relevant year\n    or period\n- scope: Account information\n  period: Until account deletion request or 3 years of inactivity\n  text: Account Information Until account deletion request or 3 years of inactivity\n- scope: Marketing preferences\n  period: Until consent withdrawal, or maximum 3 years from last active engagement\n  text: Marketing Preferences Until consent withdrawal, or maximum 3 years from last active engagement\n- scope: AI shopping assistant chat\n  period: maximum of 24 hours\n  text: We store them on our servers for a maximum of 24 hours, after which they are deleted automatically.\n- scope: Customer support records\n  period: 3 years from last interaction\n  text: Customer Support Records 3 years from last interaction\n- scope: Consent records\n  period:\
  \ 3 years\n  text: Consent Records 3 years (GDPR compliance documentation)\nresidency:\n- region: EU\n  text: Upstash Inc. – Cache and session storage (EU-West region)\n- region: Poland/EU\n  text: Fakturownia sp. z o.o. – Invoice management (Poland, EU – no transfer outside EEA)\ntransfers:\n- mechanism: DPF\n  text: Stripe, Inc. USA EU-US Data Privacy Framework & Standard Contractual Clauses (SCCs)\n- mechanism: SCC\n  text: Anthropic – AI-powered features (USA, SCCs)\n- mechanism: other\n  text: TikTok (ByteDance Ltd.) USA, Singapore, and potentially the People's Republic of China\nsubprocessors:\n  url: null\n  text: Service providers may receive data where needed.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@bolotstudio.com\n  text: Email support@bolotstudio.com. We respond without undue delay and within one month after receiving the request.\nrights:\n- right: Access\n  text: Request a copy of all personal data we hold about you.\n- right:\
  \ Rectification\n  text: Request correction of any inaccurate or incomplete data.\n- right: Erasure\n  text: Request deletion of your personal data from our systems.\n- right: Portability\n  text: Receive your data in a machine-readable format.\n- right: Object\n  text: Object to processing of your data for direct marketing.\n- right: Withdraw consent\n  text: Withdraw your consent for data processing at any time.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell personal data for money.\n"
source_yaml_url: https://artifacts.apis.io/bolotstudio-com/privacy/bolotstudio-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 30 quoted statements, read from Bolot Studio's own page on 2026-11-09.
synthetic: false
tags:
- Print Shop
- CustomPrints
- E-Commerce
- Photography
- Aluminium
---
