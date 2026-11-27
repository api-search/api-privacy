---
api_specs:
- filename: tickerall-com-accounts-api-openapi.yml
  format: yaml
  label: tickerall-com Accounts API
  slug: tickerall-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-accounts-api-openapi.yml
- filename: tickerall-com-bulk-api-openapi.yml
  format: yaml
  label: tickerall-com Bulk API
  slug: tickerall-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-bulk-api-openapi.yml
- filename: tickerall-com-candles-history-api-openapi.yml
  format: yaml
  label: tickerall-com Candles & History API
  slug: tickerall-com-candles-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-candles-history-api-openapi.yml
- filename: tickerall-com-copy-trading-api-openapi.yml
  format: yaml
  label: tickerall-com Copy Trading API
  slug: tickerall-com-copy-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-copy-trading-api-openapi.yml
- filename: tickerall-com-orders-api-openapi.yml
  format: yaml
  label: tickerall-com Orders API
  slug: tickerall-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-orders-api-openapi.yml
- filename: tickerall-com-sessions-api-openapi.yml
  format: yaml
  label: tickerall-com Sessions API
  slug: tickerall-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-sessions-api-openapi.yml
- filename: tickerall-com-symbols-api-openapi.yml
  format: yaml
  label: tickerall-com Symbols API
  slug: tickerall-com-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-symbols-api-openapi.yml
- filename: tickerall-com-trade-history-api-openapi.yml
  format: yaml
  label: tickerall-com Trade History API
  slug: tickerall-com-trade-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerall-com/openapi/tickerall-com-trade-history-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details — your email and authentication
  - category: financial
    text: Billing information — handled by our payment processor (Stripe).
  - category: other
    text: Broker connection credentials — the server name, login, and password you provide to connect a broker account.
  - category: financial
    text: Trading & market data — balances, positions, orders, deal/order history, symbols, and candles
  - category: behavioral
    text: Usage & diagnostics — API request metadata, connection health, and system logs
  deletion:
    route: request
    text: You can ask us to delete your account and associated data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the service
    text: To provide the service (maintain your broker connections and serve your API/MCP requests), process billing, provide support, secure the platform against abuse, and improve the product.
  retention:
  - period: while your account is active
    scope: Account and billing records
    text: We keep account and billing records while your account is active and as needed to meet legal and accounting obligations.
  - period: during a live connection
    scope: Broker passwords
    text: Broker passwords are kept only in memory during a live connection
  - period: null
    scope: Trading and market data
    text: Trading and market data is retained to provide history and analytics features.
  rights:
  - right: Access or deletion
    text: request access to or deletion of your personal data by emailing [email protected]
  - right: Additional local rights
    text: Depending on where you live, you may have additional rights under local data-protection law.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data.
  subprocessors:
    text: Service providers that help us run TickerAll — our payment processor (Stripe), our authentication provider, and our hosting/infrastructure providers
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tickerall-com
provenance_date: '2026-11-10'
provider_name: tickerall-com
provider_slug: tickerall-com
slug: tickerall-com-privacy-policy
source_date: '2026-11-10'
source_filename: tickerall-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tickerall.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tickerall-com\naid: tickerall-com\nurl: https://tickerall.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account details — your email and authentication\n- category: financial\n  text: Billing information — handled by our payment processor (Stripe).\n- category: other\n  text: Broker connection credentials — the server name, login, and password you provide to connect a broker account.\n- category: financial\n  text: Trading & market data — balances, positions, orders, deal/order history, symbols, and candles\n- category: behavioral\n\
  \  text: Usage & diagnostics — API request metadata, connection health, and system logs\npurposes:\n- purpose: Operate the service\n  text: To provide the service (maintain your broker connections and serve your API/MCP requests), process billing,\n    provide support, secure the platform against abuse, and improve the product.\nretention:\n- scope: Account and billing records\n  period: while your account is active\n  text: We keep account and billing records while your account is active and as needed to meet legal and accounting\n    obligations.\n- scope: Broker passwords\n  period: during a live connection\n  text: Broker passwords are kept only in memory during a live connection\n- scope: Trading and market data\n  period: null\n  text: Trading and market data is retained to provide history and analytics features.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers that help us run TickerAll — our payment processor (Stripe), our authentication provider,\n\
  \    and our hosting/infrastructure providers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request\n  text: You can ask us to delete your account and associated data at any time.\nrights:\n- right: Access or deletion\n  text: request access to or deletion of your personal data by emailing [email protected]\n- right: Additional local rights\n  text: Depending on where you live, you may have additional rights under local data-protection law.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data.\n"
source_yaml_url: https://artifacts.apis.io/tickerall-com/privacy/tickerall-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from tickerall-com's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Trading
- Foreign Exchange
- MT5
- MT4
---
