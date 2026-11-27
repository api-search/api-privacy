---
api_specs:
- filename: discountedtokens-api-messages-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Messages API
  slug: discountedtokens-api-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-messages-api-openapi.yml
- filename: discountedtokens-api-models-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Models API
  slug: discountedtokens-api-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-models-api-openapi.yml
- filename: discountedtokens-api-responses-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Responses API
  slug: discountedtokens-api-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-responses-api-openapi.yml
- filename: discountedtokens-api-chat-completions-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Chat Completions API
  slug: discountedtokens-api-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-chat-completions-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: email address, password hash, account identifier, session token, account creation time, credit balance, and API-key metadata.'
  - category: financial
    text: 'Guest checkout: receipt email, IP address, order identifier, amount, currency, payment method, status, payment reference, and timestamps.'
  - category: behavioral
    text: Purchase-funnel events include page paths without query strings, purchase-button clicks, checkout submissions, bounded error categories, campaign tags and a coarse mobile/tablet/desktop class.
  - category: communication
    text: 'Support: messages and attachments you send to the site-owned support email.'
  - category: device
    text: a salted one-way signup fingerprint derived from IP address and user agent
  deletion:
    route: Contact support to request deletion of stored data.
    text: Contact support to request deletion of stored data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: create and secure accounts, deliver and meter API access
    text: Information is used to create and secure accounts, deliver and meter API access, process payments, issue receipts, prevent fraud and abuse, answer support requests, maintain service reliability, meet tax/accounting obligations
  - purpose: aggregate site traffic analytics
    text: with consent where required, understand aggregate site traffic
  retention:
  - period: seven days
    scope: Login sessions
    text: Login sessions expire after seven days.
  - period: up to seven years
    scope: Purchase and payment records
    text: Purchase and payment records may be retained for up to seven years where needed for tax, accounting, fraud, and legal obligations.
  - period: up to thirteen months
    scope: First-party analytics records
    text: First-party analytics records are intended for trend reporting and may be retained for up to thirteen months.
  - period: 90 days
    scope: Purchase-funnel events
    text: Events are retained for 90 days.
  - period: 30 days
    scope: Browser attribution
    text: Browser attribution expires after 30 days
  rights:
  - right: access, correction, deletion, restriction, objection, portability, withdrawal of consent
    text: Subject to applicable law, you may request access, correction, deletion, restriction, objection, portability, or withdrawal of consent.
  - right: complain to local privacy regulator
    text: You may also complain to your local privacy regulator.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use it for cross-context behavioral advertising.
  subprocessors:
    text: Cloudflare (hosting, security, and network logs), Stripe (card checkout), Coinbase or the displayed crypto-payment provider (crypto settlement), Resend (transactional email), and third-party upstream model/API providers needed to fulfill API calls.
    url: null
  transfers:
  - mechanism: other
    text: These providers may process data outside your country under their own terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DiscountedTokens API
provenance_date: '2026-11-09'
provider_name: DiscountedTokens API
provider_slug: discountedtokens-api
slug: discountedtokens-api-privacy-policy
source_date: '2026-11-09'
source_filename: discountedtokens-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://discountedtokens.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DiscountedTokens API\naid: discountedtokens-api\nurl: https://discountedtokens.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: email address, password hash, account identifier, session token, account creation\n    time, credit balance, and API-key metadata.'\n- category: financial\n  text: 'Guest checkout: receipt email, IP address, order identifier, amount, currency, payment method, status,\n    payment reference, and timestamps.'\n- category: behavioral\n  text: Purchase-funnel events include page paths\
  \ without query strings, purchase-button clicks, checkout submissions,\n    bounded error categories, campaign tags and a coarse mobile/tablet/desktop class.\n- category: communication\n  text: 'Support: messages and attachments you send to the site-owned support email.'\n- category: device\n  text: a salted one-way signup fingerprint derived from IP address and user agent\npurposes:\n- purpose: create and secure accounts, deliver and meter API access\n  text: Information is used to create and secure accounts, deliver and meter API access, process payments, issue\n    receipts, prevent fraud and abuse, answer support requests, maintain service reliability, meet tax/accounting\n    obligations\n- purpose: aggregate site traffic analytics\n  text: with consent where required, understand aggregate site traffic\nretention:\n- scope: Login sessions\n  period: seven days\n  text: Login sessions expire after seven days.\n- scope: Purchase and payment records\n  period: up to seven years\n  text:\
  \ Purchase and payment records may be retained for up to seven years where needed for tax, accounting, fraud,\n    and legal obligations.\n- scope: First-party analytics records\n  period: up to thirteen months\n  text: First-party analytics records are intended for trend reporting and may be retained for up to thirteen months.\n- scope: Purchase-funnel events\n  period: 90 days\n  text: Events are retained for 90 days.\n- scope: Browser attribution\n  period: 30 days\n  text: Browser attribution expires after 30 days\nresidency: []\ntransfers:\n- mechanism: other\n  text: These providers may process data outside your country under their own terms.\nsubprocessors:\n  url: null\n  text: Cloudflare (hosting, security, and network logs), Stripe (card checkout), Coinbase or the displayed crypto-payment\n    provider (crypto settlement), Resend (transactional email), and third-party upstream model/API providers needed\n    to fulfill API calls.\ndpa:\n  available: null\n  url: null\n  text:\
  \ null\ndeletion:\n  route: Contact support to request deletion of stored data.\n  text: Contact support to request deletion of stored data.\nrights:\n- right: access, correction, deletion, restriction, objection, portability, withdrawal of consent\n  text: Subject to applicable law, you may request access, correction, deletion, restriction, objection, portability,\n    or withdrawal of consent.\n- right: complain to local privacy regulator\n  text: You may also complain to your local privacy regulator.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/discountedtokens-api/privacy/discountedtokens-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from DiscountedTokens API's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Generative AI Inference
- OpenAI-Compatible
- Anthropic Compatible
- API Reseller
- Aggregator
- Prepaid
- Usage-Based
- Developer Tools
- AI Infrastructure
---
