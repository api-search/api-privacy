---
api_specs:
- filename: citedtravel-com-billing-api-openapi.yml
  format: yaml
  label: CitedTravel Billing API
  slug: citedtravel-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-billing-api-openapi.yml
- filename: citedtravel-com-entry-api-openapi.yml
  format: yaml
  label: CitedTravel Entry API
  slug: citedtravel-com-entry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-entry-api-openapi.yml
- filename: citedtravel-com-facts-api-openapi.yml
  format: yaml
  label: CitedTravel Facts API
  slug: citedtravel-com-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-facts-api-openapi.yml
- filename: citedtravel-com-meta-api-openapi.yml
  format: yaml
  label: CitedTravel Meta API
  slug: citedtravel-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citedtravel-com/openapi/citedtravel-com-meta-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, plan, key creation time, acceptance of the Terms
  - category: financial
    text: Payment details, name and billing address
  - category: identifying
    text: IP address To apply rate limits to requests made without a key (60 per minute)
  - category: communication
    text: Emails you send us (address, name, content) and emails we send you
  - category: device
    text: 'Request logs: time, method, URL including query parameters'
  - category: financial
    text: 'x402 payments: payer wallet address, transaction hash, amount, asset, network, resource requested, time, status and the Terms version that applied'
  deletion:
    route: Email support@citedtravel.com
    text: If you ask us to revoke a key or delete your account, we delete the key record within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Issue and manage API key
    text: 'When you create a free API key: to issue and manage the key, contact you about it, and prevent abuse.'
  - purpose: Operate, secure and debug the Service
    text: To operate, secure and debug the Service.
  - purpose: Newsletter
    text: 'Builder and Pro subscribers: to send the newsletter that comes with the subscription, unless you said no at checkout or unsubscribe.'
  residency:
  - region: United States
    text: We are based in the United States and our providers process data in the United States and other countries, including through Cloudflare's global network.
  retention:
  - period: 3 days
    scope: Request and error logs
    text: Request and error logs (Cloudflare Workers Logs) 3 days.
  - period: 35 days
    scope: Usage counters for a key
    text: counters for a key 35 days after its last use.
  - period: 10 years
    scope: x402 payment ledger
    text: x402 payment ledger (only the fields listed in section 2) 10 years after the payment
  - period: 3 years
    scope: Withdrawal requests
    text: Withdrawal requests 3 years after we receive them, then deleted automatically.
  - period: 5 years after the end of the calendar year in which the sponsorship ended
    scope: Sponsor purchases
    text: Sponsor purchases 5 years after the end of the calendar year in which the sponsorship ended, as business and tax records; then deleted automatically.
  rights:
  - right: access, correction and deletion
    text: You can ask to access, correct or delete your personal information, to restrict or object to its use, and to receive it in a portable format.
  - right: opt out of sale or sharing (California)
    text: and to opt out of its sale or sharing (we do not sell or share it).
  - right: complain to data-protection authority
    text: You can complain to your local data-protection authority (in the UK, the Information Commissioner's Office).
  role:
    text: We are the controller of the personal information described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share it for cross-context behavioural advertising.
  subprocessors:
    text: 'We use these service providers (processors), each under its own data-protection terms: Provider Purpose Data'
    url: null
  transfers:
  - mechanism: DPF
    text: we rely on appropriate safeguards such as our providers' certification under the EU-US Data Privacy Framework (and its UK and Swiss extensions)
  - mechanism: SCC
    text: or the European Commission's standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CitedTravel
provenance_date: '2026-11-09'
provider_name: CitedTravel
provider_slug: citedtravel-com
slug: citedtravel-com-privacy-policy
source_date: '2026-11-09'
source_filename: citedtravel-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://citedtravel.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CitedTravel\naid: citedtravel-com\nurl: https://citedtravel.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal information described here.\ndata_categories:\n- category: contact\n  text: Email address, plan, key creation time, acceptance of the Terms\n- category: financial\n  text: Payment details, name and billing address\n- category: identifying\n  text: IP address To apply rate limits to requests made without a key (60 per minute)\n- category: communication\n  text: Emails you send us (address, name, content) and emails we send you\n- category:\
  \ device\n  text: 'Request logs: time, method, URL including query parameters'\n- category: financial\n  text: 'x402 payments: payer wallet address, transaction hash, amount, asset, network, resource requested, time,\n    status and the Terms version that applied'\npurposes:\n- purpose: Issue and manage API key\n  text: 'When you create a free API key: to issue and manage the key, contact you about it, and prevent abuse.'\n- purpose: Operate, secure and debug the Service\n  text: To operate, secure and debug the Service.\n- purpose: Newsletter\n  text: 'Builder and Pro subscribers: to send the newsletter that comes with the subscription, unless you said no\n    at checkout or unsubscribe.'\nretention:\n- scope: Request and error logs\n  period: 3 days\n  text: Request and error logs (Cloudflare Workers Logs) 3 days.\n- scope: Usage counters for a key\n  period: 35 days\n  text: counters for a key 35 days after its last use.\n- scope: x402 payment ledger\n  period: 10 years\n  text: x402\
  \ payment ledger (only the fields listed in section 2) 10 years after the payment\n- scope: Withdrawal requests\n  period: 3 years\n  text: Withdrawal requests 3 years after we receive them, then deleted automatically.\n- scope: Sponsor purchases\n  period: 5 years after the end of the calendar year in which the sponsorship ended\n  text: Sponsor purchases 5 years after the end of the calendar year in which the sponsorship ended, as business\n    and tax records; then deleted automatically.\nresidency:\n- region: United States\n  text: We are based in the United States and our providers process data in the United States and other countries,\n    including through Cloudflare's global network.\ntransfers:\n- mechanism: DPF\n  text: we rely on appropriate safeguards such as our providers' certification under the EU-US Data Privacy Framework\n    (and its UK and Swiss extensions)\n- mechanism: SCC\n  text: or the European Commission's standard contractual clauses\nsubprocessors:\n  url: null\n\
  \  text: 'We use these service providers (processors), each under its own data-protection terms: Provider Purpose\n    Data'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@citedtravel.com\n  text: If you ask us to revoke a key or delete your account, we delete the key record within 30 days.\nrights:\n- right: access, correction and deletion\n  text: You can ask to access, correct or delete your personal information, to restrict or object to its use, and\n    to receive it in a portable format.\n- right: opt out of sale or sharing (California)\n  text: and to opt out of its sale or sharing (we do not sell or share it).\n- right: complain to data-protection authority\n  text: You can complain to your local data-protection authority (in the UK, the Information Commissioner's Office).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/citedtravel-com/privacy/citedtravel-com-privacy-policy.yml
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
- sale_or_sharing
summary_line: 24 quoted statements, read from CitedTravel's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Data
- TravelFacts
- Open Data
---
