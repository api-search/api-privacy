---
api_specs:
- filename: shotkiln-com-billing-api-openapi.yml
  format: yaml
  label: shotkiln-com Billing API
  slug: shotkiln-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-billing-api-openapi.yml
- filename: shotkiln-com-checkout-api-openapi.yml
  format: yaml
  label: shotkiln-com Checkout API
  slug: shotkiln-com-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-checkout-api-openapi.yml
- filename: shotkiln-com-keys-api-openapi.yml
  format: yaml
  label: shotkiln-com Keys API
  slug: shotkiln-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-keys-api-openapi.yml
- filename: shotkiln-com-mcp-api-openapi.yml
  format: yaml
  label: shotkiln-com MCP API
  slug: shotkiln-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-mcp-api-openapi.yml
- filename: shotkiln-com-og-api-openapi.yml
  format: yaml
  label: shotkiln-com Og API
  slug: shotkiln-com-og-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-og-api-openapi.yml
- filename: shotkiln-com-pdf-api-openapi.yml
  format: yaml
  label: shotkiln-com PDF API
  slug: shotkiln-com-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-pdf-api-openapi.yml
- filename: shotkiln-com-screenshot-api-openapi.yml
  format: yaml
  label: shotkiln-com Screenshot API
  slug: shotkiln-com-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-screenshot-api-openapi.yml
- filename: shotkiln-com-usage-api-openapi.yml
  format: yaml
  label: shotkiln-com Usage API
  slug: shotkiln-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkiln-com/openapi/shotkiln-com-usage-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'API keys: a one-way hash of each key, a short prefix, its plan, billing mode and creation and revocation times.'
  - category: contact
    text: when you send a message, we receive the email address you give, the topic, your message and the page you sent it from
  - category: financial
    text: We store the processor's customer and subscription identifiers, your plan and the subscription status.
  - category: device
    text: a salted hash of your IP address (IPv6 grouped by /64) enforces rate limits.
  - category: behavioral
    text: cookieless, aggregate counts of page views and button clicks (path, referring site, country)
  deletion:
    route: Ask us to delete a key and its records via the contact form or support@shotkiln.com
    text: Ask us and we delete a key and its records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate requests
    text: 'Purpose: authenticate your requests (performance of our contract with you).'
  - purpose: provide paid plan and accounting
    text: 'Purpose: provide the paid plan and keep accounting records (contract; legal obligation).'
  - purpose: key recovery and abuse prevention
    text: 'Purpose: give you a new key and prevent abuse (contract; legitimate interests).'
  - purpose: provide rendering service
    text: 'Purpose: provide the service (contract).'
  - purpose: answer contact requests
    text: 'Purpose: answer you (your request; legitimate interests).'
  - purpose: spam protection on contact form
    text: 'Purpose: keep the form usable and stop spam (legitimate interests).'
  retention:
  - period: at most 30 days
    scope: Rendered outputs
    text: 'Rendered outputs: until the cache_ttl you choose ends (default 1 hour, 7 days for OG images, at most 30 days)'
  - period: 15 minutes
    scope: Key shown on payment confirmation page
    text: 'A key shown again on the payment confirmation page: stored encrypted for 15 minutes, then deleted within about an hour.'
  - period: 90 days
    scope: Payment event identifiers
    text: 'Payment event identifiers: 90 days.'
  - period: 24 months
    scope: Revoked keys and checkout records
    text: 'Revoked keys and checkout records: 24 months after revocation or checkout, then deleted.'
  - period: up to 7 days
    scope: Operational logs at hosting provider
    text: 'Operational logs at our hosting provider: up to 7 days.'
  - period: no longer than 24 months after the conversation ends
    scope: Contact-form messages and support emails
    text: 'Contact-form messages and support emails: in our support mailbox for as long as we need them to answer you and handle follow-up, and no longer than 24 months after the conversation ends.'
  rights:
  - right: access, correction, deletion, export
    text: You can ask us to access, correct, delete or export your data
  - right: restriction and objection
    text: to restrict or object to its use
  - right: withdraw consent
    text: to withdraw consent where we rely on it
  - right: complain to authority
    text: You can also complain to your data protection authority.
  role:
    text: SPONE FZCO, United Arab Emirates ("we", "us"), which is the controller of that data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, use it for advertising, or make automated decisions with legal effects about you.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where the law requires it, transfers are covered by appropriate safeguards such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: shotkiln-com
provenance_date: '2026-11-10'
provider_name: shotkiln-com
provider_slug: shotkiln-com
slug: shotkiln-com-privacy-policy
source_date: '2026-11-10'
source_filename: shotkiln-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shotkiln.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: shotkiln-com\naid: shotkiln-com\nurl: https://shotkiln.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: SPONE FZCO, United Arab Emirates (\"we\", \"us\"), which is the controller of that data.\ndata_categories:\n- category: identifying\n  text: 'API keys: a one-way hash of each key, a short prefix, its plan, billing mode and creation and revocation\n    times.'\n- category: contact\n  text: when you send a message, we receive the email address you give, the topic, your message and the page you\n    sent it from\n- category: financial\n  text: We store the processor's customer and\
  \ subscription identifiers, your plan and the subscription status.\n- category: device\n  text: a salted hash of your IP address (IPv6 grouped by /64) enforces rate limits.\n- category: behavioral\n  text: cookieless, aggregate counts of page views and button clicks (path, referring site, country)\npurposes:\n- purpose: authenticate requests\n  text: 'Purpose: authenticate your requests (performance of our contract with you).'\n- purpose: provide paid plan and accounting\n  text: 'Purpose: provide the paid plan and keep accounting records (contract; legal obligation).'\n- purpose: key recovery and abuse prevention\n  text: 'Purpose: give you a new key and prevent abuse (contract; legitimate interests).'\n- purpose: provide rendering service\n  text: 'Purpose: provide the service (contract).'\n- purpose: answer contact requests\n  text: 'Purpose: answer you (your request; legitimate interests).'\n- purpose: spam protection on contact form\n  text: 'Purpose: keep the form usable and stop\
  \ spam (legitimate interests).'\nretention:\n- scope: Rendered outputs\n  period: at most 30 days\n  text: 'Rendered outputs: until the cache_ttl you choose ends (default 1 hour, 7 days for OG images, at most 30\n    days)'\n- scope: Key shown on payment confirmation page\n  period: 15 minutes\n  text: 'A key shown again on the payment confirmation page: stored encrypted for 15 minutes, then deleted within\n    about an hour.'\n- scope: Payment event identifiers\n  period: 90 days\n  text: 'Payment event identifiers: 90 days.'\n- scope: Revoked keys and checkout records\n  period: 24 months\n  text: 'Revoked keys and checkout records: 24 months after revocation or checkout, then deleted.'\n- scope: Operational logs at hosting provider\n  period: up to 7 days\n  text: 'Operational logs at our hosting provider: up to 7 days.'\n- scope: Contact-form messages and support emails\n  period: no longer than 24 months after the conversation ends\n  text: 'Contact-form messages and support emails:\
  \ in our support mailbox for as long as we need them to answer\n    you and handle follow-up, and no longer than 24 months after the conversation ends.'\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where the law requires it, transfers are covered by appropriate safeguards such as standard contractual\n    clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask us to delete a key and its records via the contact form or support@shotkiln.com\n  text: Ask us and we delete a key and its records.\nrights:\n- right: access, correction, deletion, export\n  text: You can ask us to access, correct, delete or export your data\n- right: restriction and objection\n  text: to restrict or object to its use\n- right: withdraw consent\n  text: to withdraw consent where we rely on it\n- right: complain to authority\n  text: You can also complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell personal data, use it for advertising, or make automated decisions with legal effects about\n    you.\n"
source_yaml_url: https://artifacts.apis.io/shotkiln-com/privacy/shotkiln-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from shotkiln-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screenshots
- Web
- Automation
---
