---
api_specs:
- filename: moltlinestudio-com-agent-check-api-openapi.yml
  format: yaml
  label: moltlinestudio-com Agent Check API
  slug: moltlinestudio-com-agent-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moltlinestudio-com/openapi/moltlinestudio-com-agent-check-api-openapi.yml
- filename: moltlinestudio-com-auth-md-api-openapi.yml
  format: yaml
  label: moltlinestudio-com Auth.md API
  slug: moltlinestudio-com-auth-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moltlinestudio-com/openapi/moltlinestudio-com-auth-md-api-openapi.yml
- filename: moltlinestudio-com-badge-api-openapi.yml
  format: yaml
  label: moltlinestudio-com Badge API
  slug: moltlinestudio-com-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moltlinestudio-com/openapi/moltlinestudio-com-badge-api-openapi.yml
- filename: moltlinestudio-com-premium-api-openapi.yml
  format: yaml
  label: moltlinestudio-com Premium API
  slug: moltlinestudio-com-premium-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moltlinestudio-com/openapi/moltlinestudio-com-premium-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Email address: only when you buy an All-Access license, so we can send your key and handle support.'
  - category: financial
    text: 'Payment data: cryptocurrency payments are processed by NOWPayments . We receive a payment confirmation and amount; we never see or store card numbers, wallet keys, or bank details.'
  - category: device
    text: your IP address, the country it resolves to, your client's user-agent string
  - category: behavioral
    text: 'Google signals and ads personalisation are switched on: Google may link these visits to the Google accounts of signed-in users who allow it'
  deletion:
    route: email support@moltlinestudio.com
    text: You can ask us to access or delete the email and order record we hold for you by writing to support@moltlinestudio.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver license key and support
    text: 'We use the limited data above only to: deliver your license key; validate and support your license; process and confirm payment; prevent fraud, key resale, and abuse'
  - purpose: measure website and ads performance
    text: measure how the website and our own Google ads perform, and show ads on blog articles
  retention:
  - period: null
    scope: order records
    text: Order records are pruned automatically once they are no longer needed for fulfillment and support (records older than the active support window are removed).
  - period: null
    scope: operational request logs
    text: Operational request logs are rotated regularly and retained no longer than needed to enforce anti-sharing limits and investigate abuse, then deleted.
  - period: 14 months
    scope: Google Analytics data
    text: Google Analytics data is deleted automatically after 14 months.
  rights:
  - right: access and deletion
    text: You can ask us to access or delete the email and order record we hold for you by writing to support@moltlinestudio.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data, and we share it with no one else except where required by law.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: moltlinestudio-com
provenance_date: '2026-11-10'
provider_name: moltlinestudio-com
provider_slug: moltlinestudio-com
slug: moltlinestudio-com-privacy-policy
source_date: '2026-11-10'
source_filename: moltlinestudio-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://moltlinestudio.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: moltlinestudio-com\naid: moltlinestudio-com\nurl: https://moltlinestudio.com/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Email address: only when you buy an All-Access license, so we can send your key and handle support.'\n- category: financial\n  text: 'Payment data: cryptocurrency payments are processed by NOWPayments . We receive a payment confirmation\n    and amount; we never see or store card numbers, wallet keys, or bank details.'\n- category: device\n  text: your IP address, the country it resolves to, your client's\
  \ user-agent string\n- category: behavioral\n  text: 'Google signals and ads personalisation are switched on: Google may link these visits to the Google accounts\n    of signed-in users who allow it'\npurposes:\n- purpose: deliver license key and support\n  text: 'We use the limited data above only to: deliver your license key; validate and support your license; process\n    and confirm payment; prevent fraud, key resale, and abuse'\n- purpose: measure website and ads performance\n  text: measure how the website and our own Google ads perform, and show ads on blog articles\nretention:\n- scope: order records\n  period: null\n  text: Order records are pruned automatically once they are no longer needed for fulfillment and support (records\n    older than the active support window are removed).\n- scope: operational request logs\n  period: null\n  text: Operational request logs are rotated regularly and retained no longer than needed to enforce anti-sharing\n    limits and investigate abuse,\
  \ then deleted.\n- scope: Google Analytics data\n  period: 14 months\n  text: Google Analytics data is deleted automatically after 14 months.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@moltlinestudio.com\n  text: You can ask us to access or delete the email and order record we hold for you by writing to support@moltlinestudio.com\n    .\nrights:\n- right: access and deletion\n  text: You can ask us to access or delete the email and order record we hold for you by writing to support@moltlinestudio.com\n    .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data, and we share it with no one else except where required by law.\n"
source_yaml_url: https://artifacts.apis.io/moltlinestudio-com/privacy/moltlinestudio-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from moltlinestudio-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Agent Skills
- Platform
- Tools
---
