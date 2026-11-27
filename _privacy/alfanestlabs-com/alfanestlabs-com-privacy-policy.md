---
api_specs:
- filename: alfanestlabs-com-openapi-generated.yml
  format: yaml
  label: AlfaNest Labs API
  slug: alfanestlabs-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alfanestlabs-com/openapi/_ae-authored/alfanestlabs-com-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and authentication data (for example email address, name where provided, session identifiers) when you sign in.
  - category: financial
    text: 'Billing data when you subscribe: payment processing is handled by our payment provider; we typically receive limited billing metadata (for example customer id, subscription status, invoice references).'
  - category: device
    text: Technical and security data (for example IP address, user agent, timestamps, logs) to secure services and investigate abuse.
  - category: communication
    text: Communications you send to us (for example support emails).
  - category: behavioral
    text: Product usage data necessary to operate features you use (for example scan inputs you submit, workspace metadata, security analysis outputs).
  deletion:
    route: Delete the account
    text: When you delete the account, we purge Labs rows at once.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'Provide the service (contract / pre-contractual steps): account creation, authentication, delivering product features you request.'
  - purpose: Billing and accounting
    text: 'Billing and accounting (contract / legal obligation): invoices, tax compliance where applicable.'
  - purpose: Security and fraud prevention
    text: 'Security and fraud prevention (legitimate interests): protecting accounts, infrastructure, and users; detecting abuse.'
  - purpose: Product improvement
    text: 'Product improvement (legitimate interests / consent): first-party product analytics'
  - purpose: Audience measurement
    text: we use AlfaNest Pulse, our own audience measurement, hosted on our servers. It needs no cookie and stores nothing on your device
  retention:
  - period: while the account exists
    scope: Account and profile data
    text: Account and profile data stay while the account exists.
  - period: at most 14 days on the host and 3 days on the night disk
    scope: Encrypted backups
    text: Encrypted backups of those rows stay at most 14 days on the host and 3 days on the night disk.
  - period: 90 days
    scope: Security logs
    text: Security logs stay 90 days.
  - period: 10 years
    scope: Billing and invoices
    text: Billing and invoices stay 10 years under the French accounting hold.
  - period: 13 months
    scope: Pulse aggregates
    text: Pulse aggregates stay 13 months.
  - period: 48 hours
    scope: Daily anonymous visit code
    text: The daily anonymous visit code is gone in 48 hours.
  rights:
  - right: access, rectify, erase, restrict, object, portability
    text: you may have rights to access, rectify, erase, restrict processing, object, and data portability
  - right: lodge a complaint
    text: the right to lodge a complaint with a supervisory authority
  role:
    text: Data controller AlfaNest Labs, France.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AlfaNest Labs
provenance_date: '2026-11-09'
provider_name: AlfaNest Labs
provider_slug: alfanestlabs-com
slug: alfanestlabs-com-privacy-policy
source_date: '2026-11-09'
source_filename: alfanestlabs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alfanestlabs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AlfaNest Labs\naid: alfanestlabs-com\nurl: https://alfanestlabs.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller AlfaNest Labs, France.\ndata_categories:\n- category: identifying\n  text: Account and authentication data (for example email address, name where provided, session identifiers) when\n    you sign in.\n- category: financial\n  text: 'Billing data when you subscribe: payment processing is handled by our payment provider; we typically receive\n    limited billing metadata (for example customer id, subscription status, invoice references).'\n- category: device\n\
  \  text: Technical and security data (for example IP address, user agent, timestamps, logs) to secure services and\n    investigate abuse.\n- category: communication\n  text: Communications you send to us (for example support emails).\n- category: behavioral\n  text: Product usage data necessary to operate features you use (for example scan inputs you submit, workspace\n    metadata, security analysis outputs).\npurposes:\n- purpose: Provide the service\n  text: 'Provide the service (contract / pre-contractual steps): account creation, authentication, delivering product\n    features you request.'\n- purpose: Billing and accounting\n  text: 'Billing and accounting (contract / legal obligation): invoices, tax compliance where applicable.'\n- purpose: Security and fraud prevention\n  text: 'Security and fraud prevention (legitimate interests): protecting accounts, infrastructure, and users; detecting\n    abuse.'\n- purpose: Product improvement\n  text: 'Product improvement (legitimate interests\
  \ / consent): first-party product analytics'\n- purpose: Audience measurement\n  text: we use AlfaNest Pulse, our own audience measurement, hosted on our servers. It needs no cookie and stores\n    nothing on your device\nretention:\n- scope: Account and profile data\n  period: while the account exists\n  text: Account and profile data stay while the account exists.\n- scope: Encrypted backups\n  period: at most 14 days on the host and 3 days on the night disk\n  text: Encrypted backups of those rows stay at most 14 days on the host and 3 days on the night disk.\n- scope: Security logs\n  period: 90 days\n  text: Security logs stay 90 days.\n- scope: Billing and invoices\n  period: 10 years\n  text: Billing and invoices stay 10 years under the French accounting hold.\n- scope: Pulse aggregates\n  period: 13 months\n  text: Pulse aggregates stay 13 months.\n- scope: Daily anonymous visit code\n  period: 48 hours\n  text: The daily anonymous visit code is gone in 48 hours.\nresidency: []\n\
  transfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the account\n  text: When you delete the account, we purge Labs rows at once.\nrights:\n- right: access, rectify, erase, restrict, object, portability\n  text: you may have rights to access, rectify, erase, restrict processing, object, and data portability\n- right: lodge a complaint\n  text: the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alfanestlabs-com/privacy/alfanestlabs-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 20 quoted statements, read from AlfaNest Labs's own page on 2026-11-09.
synthetic: false
tags:
- Data Security
- API Risk
- Machine Identity
- Artificial Intelligence
- Privacy
---
