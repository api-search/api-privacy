---
api_specs:
- filename: broke2builtai-com-buy-zero-api-openapi.yml
  format: yaml
  label: broke2built Buy Zero API
  slug: broke2builtai-com-buy-zero-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-buy-zero-api-openapi.yml
- filename: broke2builtai-com-contract-audit-api-openapi.yml
  format: yaml
  label: broke2built Contract Audit API
  slug: broke2builtai-com-contract-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-contract-audit-api-openapi.yml
- filename: broke2builtai-com-interface-xray-api-openapi.yml
  format: yaml
  label: broke2built Interface Xray API
  slug: broke2builtai-com-interface-xray-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-interface-xray-api-openapi.yml
- filename: broke2builtai-com-payer-census-api-openapi.yml
  format: yaml
  label: broke2built Payer Census API
  slug: broke2builtai-com-payer-census-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-payer-census-api-openapi.yml
- filename: broke2builtai-com-payout-oracle-api-openapi.yml
  format: yaml
  label: broke2built Payout Oracle API
  slug: broke2builtai-com-payout-oracle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-payout-oracle-api-openapi.yml
- filename: broke2builtai-com-resolver-allowlist-api-openapi.yml
  format: yaml
  label: broke2built Resolver Allowlist API
  slug: broke2builtai-com-resolver-allowlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-resolver-allowlist-api-openapi.yml
- filename: broke2builtai-com-source-verify-api-openapi.yml
  format: yaml
  label: broke2built Source Verify API
  slug: broke2builtai-com-source-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-source-verify-api-openapi.yml
- filename: broke2builtai-com-video-api-openapi.yml
  format: yaml
  label: broke2built Video API
  slug: broke2builtai-com-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-video-api-openapi.yml
- filename: broke2builtai-com-vies-check-api-openapi.yml
  format: yaml
  label: broke2built Vies Check API
  slug: broke2builtai-com-vies-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-vies-check-api-openapi.yml
- filename: broke2builtai-com-wallet-brief-api-openapi.yml
  format: yaml
  label: broke2built Wallet Brief API
  slug: broke2builtai-com-wallet-brief-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-wallet-brief-api-openapi.yml
- filename: broke2builtai-com-watch-api-openapi.yml
  format: yaml
  label: broke2built Watch API
  slug: broke2builtai-com-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/broke2builtai-com/openapi/broke2builtai-com-watch-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: a name (optional) and an email address (optional; if you type one, we keep it whether or not you ask for a reply)
  - category: communication
    text: your message, a name (optional) and an email address (optional
  - category: device
    text: the first 120 characters of your browser's user-agent string (we use it to filter spam)
  - category: location
    text: the country and the referring page
  - category: identifying
    text: a counter keyed on a hash of your IP address that limits abuse
  deletion:
    route: contact page request; flagged then removed by hand
    text: If you ask us through the contact form to delete yours, we flag it and then remove it by hand.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond to messages
    text: We use it only to respond to you.
  - purpose: operate and improve the Site
    text: We use the limited information we collect to operate and improve the Site, respond to your messages, keep the Site secure, and understand in aggregate which content is helpful.
  - purpose: generate tool results
    text: Text you type into our free tools is used only to generate the result you asked for
  retention:
  - period: 400 days
    scope: contact notes
    text: one copy expires after 400 days and the other has no expiry
  - period: no set end date
    scope: notes without set end date
    text: We keep notes so we can reply, with no set end date.
  - period: 400 days
    scope: AI crawler visit logs
    text: kept for 400 days
  - period: 7 days
    scope: Cloudflare request logs
    text: Cloudflare keeps them for up to 7 days
  - period: about a day
    scope: site guide IP counter
    text: expires within about a day
  rights:
  - right: access, correct, delete, restrict, object, portability (GDPR)
    text: you have the right to access, correct, delete, or restrict processing of your personal data, to object to processing, and to data portability.
  - right: know, deletion, opt out of sale or sharing (CCPA/CPRA)
    text: you have the right to know what personal information we collect, to request deletion, and to opt out of the "sale" or "sharing" of personal information.
  role:
    text: Broke to Built ("we," "us," or "our") handles information when you visit broke2builtai.com
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell personal data, use it for ads or train AI on it.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: broke2built
provenance_date: '2026-11-09'
provider_name: broke2built
provider_slug: broke2builtai-com
slug: broke2builtai-com-privacy-policy
source_date: '2026-11-09'
source_filename: broke2builtai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://broke2builtai.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: broke2built\naid: broke2builtai-com\nurl: https://broke2builtai.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Broke to Built (\"we,\" \"us,\" or \"our\") handles information when you visit broke2builtai.com\ndata_categories:\n- category: contact\n  text: a name (optional) and an email address (optional; if you type one, we keep it whether or not you ask for\n    a reply)\n- category: communication\n  text: your message, a name (optional) and an email address (optional\n- category: device\n  text: the first 120 characters of your browser's user-agent string (we use it to filter\
  \ spam)\n- category: location\n  text: the country and the referring page\n- category: identifying\n  text: a counter keyed on a hash of your IP address that limits abuse\npurposes:\n- purpose: respond to messages\n  text: We use it only to respond to you.\n- purpose: operate and improve the Site\n  text: We use the limited information we collect to operate and improve the Site, respond to your messages, keep\n    the Site secure, and understand in aggregate which content is helpful.\n- purpose: generate tool results\n  text: Text you type into our free tools is used only to generate the result you asked for\nretention:\n- scope: contact notes\n  period: 400 days\n  text: one copy expires after 400 days and the other has no expiry\n- scope: notes without set end date\n  period: no set end date\n  text: We keep notes so we can reply, with no set end date.\n- scope: AI crawler visit logs\n  period: 400 days\n  text: kept for 400 days\n- scope: Cloudflare request logs\n  period: 7 days\n\
  \  text: Cloudflare keeps them for up to 7 days\n- scope: site guide IP counter\n  period: about a day\n  text: expires within about a day\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact page request; flagged then removed by hand\n  text: If you ask us through the contact form to delete yours, we flag it and then remove it by hand.\nrights:\n- right: access, correct, delete, restrict, object, portability (GDPR)\n  text: you have the right to access, correct, delete, or restrict processing of your personal data, to object to\n    processing, and to data portability.\n- right: know, deletion, opt out of sale or sharing (CCPA/CPRA)\n  text: you have the right to know what personal information we collect, to request deletion, and to opt out of\n    the \"sale\" or \"sharing\" of personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell personal data, use it for\
  \ ads or train AI on it.\n"
source_yaml_url: https://artifacts.apis.io/broke2builtai-com/privacy/broke2builtai-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from broke2built's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Tools
- Data Intelligence
- Domain Intelligence
- Email Verification
- DNS
- SEO
- Web Audits
- Content Extraction
- Blockchain
- EVM
- Base
- Solana
- x402
- Agentic Payments
- A2A
- MCP
- Autonomous Agents
- Agent Networks
- Video Generation
- Monitoring
---
