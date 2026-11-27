---
api_specs:
- filename: agentic-endpoints-com-compress-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Compress API
  slug: agentic-endpoints-com-compress-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-compress-api-openapi.yml
- filename: agentic-endpoints-com-credits-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Credits API
  slug: agentic-endpoints-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-credits-api-openapi.yml
- filename: agentic-endpoints-com-meetings-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Meetings API
  slug: agentic-endpoints-com-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-meetings-api-openapi.yml
- filename: agentic-endpoints-com-once-key-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Once Key API
  slug: agentic-endpoints-com-once-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-once-key-api-openapi.yml
- filename: agentic-endpoints-com-pdf-parse-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Pdf Parse API
  slug: agentic-endpoints-com-pdf-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-pdf-parse-api-openapi.yml
- filename: agentic-endpoints-com-reach-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Reach API
  slug: agentic-endpoints-com-reach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-reach-api-openapi.yml
- filename: agentic-endpoints-com-scrape-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Scrape API
  slug: agentic-endpoints-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-scrape-api-openapi.yml
- filename: agentic-endpoints-com-vault-api-openapi.yml
  format: yaml
  label: Agentic Endpoints Vault API
  slug: agentic-endpoints-com-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-vault-api-openapi.yml
- filename: agentic-endpoints-com-x402-api-openapi.yml
  format: yaml
  label: Agentic Endpoints X402 API
  slug: agentic-endpoints-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentic-endpoints-com/openapi/agentic-endpoints-com-x402-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: The address itself is never written to storage, and the stored value cannot be reversed back to it.
  - category: device
    text: a User-Agent string truncated to 120 characters
  - category: location
    text: a two-letter country and the name of the network the call came from (for example a cloud provider)
  - category: financial
    text: Credit balances store a hash of the token and the amounts.
  - category: communication
    text: If you give a monitoring webhook URL, the watched URLs and each change in their result are sent to that URL
  deletion:
    route: DELETE endpoint for meeting transcripts; deletion of data under namespace or token you control via documented endpoints; write to support@agentic-endpoints.com
    text: Data you stored under a namespace or token you control can be deleted by you at any time using the documented endpoints.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: perform the service you asked and paid for
    text: Data is processed to perform the service you asked and paid for (contract)
  - purpose: security, abuse prevention and payment reconciliation
    text: to keep the service secure, prevent abuse, enforce free limits and reconcile payments (legitimate interests)
  - purpose: sanctions screening and tax/accounting records
    text: to screen payments against sanctions lists and keep tax and accounting records (legal obligation)
  - purpose: AI summarization of meeting transcripts
    text: /meetings/summarize sends the relevant transcript excerpts to an AI model hosted by Cloudflare Workers AI, and its answer is labelled ai_generated.
  residency:
  - region: Canada
    text: The operator is in Canada, and the processors above may process data in Canada, the United States and elsewhere.
  - region: United States
    text: Cloudflare processes traffic and stores the data described above on our behalf, and may do so outside Canada, including in the United States.
  retention:
  - period: one hour
    scope: free scan IP hash
    text: only a hash of your IP address is counted for one hour to enforce the free limit
  - period: 90 days
    scope: reach report URLs and results
    text: /reach/report keeps the URLs you submit and their scan results for 90 days, readable by anyone holding the report's link, then deletes them.
  - period: 24 hours by default
    scope: once-key stores
    text: Once-key stores an action key, a hash of your payload and any result you record, until its time to live expires (24 hours by default)
  - period: null
    scope: monitoring data
    text: deletes them 30 days after it ends
  - period: 90 days
    scope: demand counters
    text: Demand counters are kept for 90 days.
  - period: indefinitely
    scope: x402 endpoint history
    text: This history is kept indefinitely and is not linked to whoever asked.
  - period: up to 24 hours
    scope: unpaid card orders
    text: An order placed by card is held unpaid for up to 24 hours awaiting Stripe's confirmation
  rights:
  - right: access
    text: You may ask for access to, correction of, or deletion of personal data held about you
  - right: correction
    text: You may ask for access to, correction of, or deletion of personal data held about you
  - right: deletion
    text: You may ask for access to, correction of, or deletion of personal data held about you
  - right: object
    text: you may object to processing based on legitimate interests
  - right: complain
    text: or complain to your data protection authority
  role:
    text: The controller is an independent sole trader, trading as Agentic Endpoints, British Columbia, Canada.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The service runs on Cloudflare Workers, Durable Objects and Workers AI; Cloudflare processes traffic and stores the data described above on our behalf
    url: null
  transfers:
  - mechanism: SCC
    text: Where the law of your country requires a safeguard for such a transfer, the processors' standard contractual commitments are relied on.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentic Endpoints
provenance_date: '2026-11-09'
provider_name: Agentic Endpoints
provider_slug: agentic-endpoints-com
slug: agentic-endpoints-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentic-endpoints-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentic-endpoints.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentic Endpoints\naid: agentic-endpoints-com\nurl: https://agentic-endpoints.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is an independent sole trader, trading as Agentic Endpoints, British Columbia, Canada.\ndata_categories:\n- category: identifying\n  text: The address itself is never written to storage, and the stored value cannot be reversed back to it.\n- category: device\n  text: a User-Agent string truncated to 120 characters\n- category: location\n  text: a two-letter country and the name of the network the call came from (for example a cloud provider)\n\
  - category: financial\n  text: Credit balances store a hash of the token and the amounts.\n- category: communication\n  text: If you give a monitoring webhook URL, the watched URLs and each change in their result are sent to that\n    URL\npurposes:\n- purpose: perform the service you asked and paid for\n  text: Data is processed to perform the service you asked and paid for (contract)\n- purpose: security, abuse prevention and payment reconciliation\n  text: to keep the service secure, prevent abuse, enforce free limits and reconcile payments (legitimate interests)\n- purpose: sanctions screening and tax/accounting records\n  text: to screen payments against sanctions lists and keep tax and accounting records (legal obligation)\n- purpose: AI summarization of meeting transcripts\n  text: /meetings/summarize sends the relevant transcript excerpts to an AI model hosted by Cloudflare Workers AI,\n    and its answer is labelled ai_generated.\nretention:\n- scope: free scan IP hash\n  period:\
  \ one hour\n  text: only a hash of your IP address is counted for one hour to enforce the free limit\n- scope: reach report URLs and results\n  period: 90 days\n  text: /reach/report keeps the URLs you submit and their scan results for 90 days, readable by anyone holding the\n    report's link, then deletes them.\n- scope: once-key stores\n  period: 24 hours by default\n  text: Once-key stores an action key, a hash of your payload and any result you record, until its time to live\n    expires (24 hours by default)\n- scope: monitoring data\n  period: null\n  text: deletes them 30 days after it ends\n- scope: demand counters\n  period: 90 days\n  text: Demand counters are kept for 90 days.\n- scope: x402 endpoint history\n  period: indefinitely\n  text: This history is kept indefinitely and is not linked to whoever asked.\n- scope: unpaid card orders\n  period: up to 24 hours\n  text: An order placed by card is held unpaid for up to 24 hours awaiting Stripe's confirmation\nresidency:\n\
  - region: Canada\n  text: The operator is in Canada, and the processors above may process data in Canada, the United States and elsewhere.\n- region: United States\n  text: Cloudflare processes traffic and stores the data described above on our behalf, and may do so outside Canada,\n    including in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where the law of your country requires a safeguard for such a transfer, the processors' standard contractual\n    commitments are relied on.\nsubprocessors:\n  url: null\n  text: The service runs on Cloudflare Workers, Durable Objects and Workers AI; Cloudflare processes traffic and\n    stores the data described above on our behalf\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DELETE endpoint for meeting transcripts; deletion of data under namespace or token you control via documented\n    endpoints; write to support@agentic-endpoints.com\n  text: Data you stored under a namespace or token you control can\
  \ be deleted by you at any time using the documented\n    endpoints.\nrights:\n- right: access\n  text: You may ask for access to, correction of, or deletion of personal data held about you\n- right: correction\n  text: You may ask for access to, correction of, or deletion of personal data held about you\n- right: deletion\n  text: You may ask for access to, correction of, or deletion of personal data held about you\n- right: object\n  text: you may object to processing based on legitimate interests\n- right: complain\n  text: or complain to your data protection authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentic-endpoints-com/privacy/agentic-endpoints-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Agentic Endpoints's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Payments
- Micro-utilities
- Base
---
