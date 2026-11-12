---
api_specs:
- filename: clousd-com-account-api-openapi.yml
  format: yaml
  label: Clousd Account API
  slug: clousd-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-account-api-openapi.yml
- filename: clousd-com-adb-api-openapi.yml
  format: yaml
  label: Clousd ADB API
  slug: clousd-com-adb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-adb-api-openapi.yml
- filename: clousd-com-ai-agents-api-openapi.yml
  format: yaml
  label: Clousd AI agents API
  slug: clousd-com-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-ai-agents-api-openapi.yml
- filename: clousd-com-apps-api-openapi.yml
  format: yaml
  label: Clousd Apps API
  slug: clousd-com-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-apps-api-openapi.yml
- filename: clousd-com-devices-api-openapi.yml
  format: yaml
  label: Clousd Devices API
  slug: clousd-com-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-devices-api-openapi.yml
- filename: clousd-com-files-and-media-api-openapi.yml
  format: yaml
  label: Clousd Files and media API
  slug: clousd-com-files-and-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-files-and-media-api-openapi.yml
- filename: clousd-com-network-api-openapi.yml
  format: yaml
  label: Clousd Network API
  slug: clousd-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-network-api-openapi.yml
- filename: clousd-com-screen-and-input-api-openapi.yml
  format: yaml
  label: Clousd Screen and input API
  slug: clousd-com-screen-and-input-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-screen-and-input-api-openapi.yml
- filename: clousd-com-tasks-api-openapi.yml
  format: yaml
  label: Clousd Tasks API
  slug: clousd-com-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-tasks-api-openapi.yml
- filename: clousd-com-webhooks-api-openapi.yml
  format: yaml
  label: Clousd Webhooks API
  slug: clousd-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address, password (stored only as a hash), a name if you give one
  - category: financial
    text: balance, every charge, payment and refund, your plan and renewal dates
  - category: location
    text: the country, city and internet provider we look up for it
  - category: device
    text: the Android system log of the device (the same log a developer sees with ADB)
  - category: behavioral
    text: which buttons and links are pressed on our pages
  - category: communication
    text: emails you send to support@ or receive from us (stored with attachments)
  deletion:
    route: Account → Delete account
    text: delete devices, stored credentials, media and the whole account yourself (Account → Delete account)
  dpa:
    available: true
    text: business customers are covered by our Data Processing Addendum , which includes the EU standard contractual clauses
    url: null
  purposes:
  - purpose: Running account, devices and features
    text: Running your account, devices and the features you use; sending service emails
  - purpose: Security and abuse prevention
    text: 'Security: protecting accounts, preventing attacks, investigating abuse and incidents'
  - purpose: Free-trial limiting and fraud prevention
    text: Limiting the free trial to one per person and preventing payment fraud
  - purpose: Billing
    text: Billing, payments, refunds, tax and accounting records
  residency:
  - region: European Union
    text: Our website, databases and device servers are located in the European Union (Germany, Finland and the Netherlands, see section 6)
  retention:
  - period: 30 days
    scope: Account data
    text: While the account exists, then deleted within 30 days
  - period: 7 years
    scope: Payments and billing ledger
    text: Payments, invoices and the billing ledger 7 years after the transaction (tax and accounting law)
  - period: 90 days
    scope: Clousd-hosted model request logs
    text: Clousd-hosted model request logs (no content) 90 days
  - period: 3 years
    scope: Support conversations
    text: Support conversations, emails and attachments 3 years after the last message
  - period: 30 days
    scope: Website server logs
    text: Website server logs 30 days
  rights:
  - right: access
    text: ask us for a copy of the personal data we hold about you
  - right: correction
    text: to correct it, to delete it, to restrict or object to its use
  - right: portability
    text: export your content from devices at any time (ADB, API, media library) and your account data on request
  - right: appeal
    text: If you disagree with our answer, you may appeal by writing to legal@clousd.com
  role:
    text: For your account, billing, security and the way you use the service, Clousd is the controller . For the content you put on your devices and the personal data of other people that you or your AI agents process through the service, you are the controller and Clousd is your processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it for advertising.
  subprocessors:
    text: We list recipients by category. The names of the individual providers in each category are available on request at legal@clousd.com
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission’s standard contractual clauses (Decision 2021/914)
  - mechanism: DPF
    text: or on the provider’s certification under the EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clousd
provenance_date: '2026-11-09'
provider_name: Clousd
provider_slug: clousd-com
slug: clousd-com-privacy-policy
source_date: '2026-11-09'
source_filename: clousd-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clousd.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clousd\naid: clousd-com\nurl: https://clousd.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your account, billing, security and the way you use the service, Clousd is the controller . For the\n    content you put on your devices and the personal data of other people that you or your AI agents process through\n    the service, you are the controller and Clousd is your processor\ndata_categories:\n- category: identifying\n  text: email address, password (stored only as a hash), a name if you give one\n- category: financial\n  text: balance, every charge, payment and refund, your plan\
  \ and renewal dates\n- category: location\n  text: the country, city and internet provider we look up for it\n- category: device\n  text: the Android system log of the device (the same log a developer sees with ADB)\n- category: behavioral\n  text: which buttons and links are pressed on our pages\n- category: communication\n  text: emails you send to support@ or receive from us (stored with attachments)\npurposes:\n- purpose: Running account, devices and features\n  text: Running your account, devices and the features you use; sending service emails\n- purpose: Security and abuse prevention\n  text: 'Security: protecting accounts, preventing attacks, investigating abuse and incidents'\n- purpose: Free-trial limiting and fraud prevention\n  text: Limiting the free trial to one per person and preventing payment fraud\n- purpose: Billing\n  text: Billing, payments, refunds, tax and accounting records\nretention:\n- scope: Account data\n  period: 30 days\n  text: While the account exists,\
  \ then deleted within 30 days\n- scope: Payments and billing ledger\n  period: 7 years\n  text: Payments, invoices and the billing ledger 7 years after the transaction (tax and accounting law)\n- scope: Clousd-hosted model request logs\n  period: 90 days\n  text: Clousd-hosted model request logs (no content) 90 days\n- scope: Support conversations\n  period: 3 years\n  text: Support conversations, emails and attachments 3 years after the last message\n- scope: Website server logs\n  period: 30 days\n  text: Website server logs 30 days\nresidency:\n- region: European Union\n  text: Our website, databases and device servers are located in the European Union (Germany, Finland and the Netherlands,\n    see section 6)\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission’s standard contractual clauses (Decision 2021/914)\n- mechanism: DPF\n  text: or on the provider’s certification under the EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: We list recipients\
  \ by category. The names of the individual providers in each category are available on\n    request at legal@clousd.com\ndpa:\n  available: true\n  url: null\n  text: business customers are covered by our Data Processing Addendum , which includes the EU standard contractual\n    clauses\ndeletion:\n  route: Account → Delete account\n  text: delete devices, stored credentials, media and the whole account yourself (Account → Delete account)\nrights:\n- right: access\n  text: ask us for a copy of the personal data we hold about you\n- right: correction\n  text: to correct it, to delete it, to restrict or object to its use\n- right: portability\n  text: export your content from devices at any time (ADB, API, media library) and your account data on request\n- right: appeal\n  text: If you disagree with our answer, you may appeal by writing to legal@clousd.com\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/clousd-com/privacy/clousd-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Clousd's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Android
- Cloud Phones
- AI Agents
- MCP
- Mobile Testing
- QA
- Emulators
---
