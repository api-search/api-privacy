---
api_specs:
- filename: ringahuman-com-openapi-generated.yml
  format: yaml
  label: ringahuman-com API
  slug: ringahuman-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ringahuman-com/openapi/_ae-authored/ringahuman-com-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Customer account data: email, company name, API keys (stored only as hashes), and OAuth grants when you connect an app such as ChatGPT or Claude.'
  - category: contact
    text: 'Caller data: name, email, mobile number (for task alerts), states covered, and activity such as tasks claimed, dial times and earnings.'
  - category: communication
    text: 'Call outcomes: the disposition, caller notes, and any meeting time the caller records. We do not record calls.'
  - category: location
    text: 'Call task data customers send us: the lead''s phone number, name, business name, state or timezone, the goal and brief for the call, links, and the consent basis the customer asserts.'
  - category: device
    text: 'Operational logs: standard request logs (IP address, user agent, timestamps) for security and debugging.'
  deletion:
    route: Request account data deletion by contacting us
    text: Customers can ask us to delete their account data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Route call tasks
    text: To route call tasks to callers, enforce calling-hour and do-not-call rules, and return outcomes to the customer who created the task.
  - purpose: Audit trail
    text: To keep an audit trail of every task (created, claimed, dialed, completed) for compliance and dispute resolution.
  - purpose: Operate and improve service
    text: To operate, secure and improve the service, and to contact customers and callers about their accounts.
  retention:
  - period: while the customer's account is active and for a reasonable period afterward
    scope: Task records and audit trails
    text: We keep task records and audit trails while the customer's account is active and for a reasonable period afterward for compliance purposes.
  - period: indefinitely
    scope: Do-not-call entries
    text: Do-not-call entries are kept indefinitely so opt-outs keep being honored.
  rights:
  - right: Access, correction, deletion
    text: Customers and callers can request access to, correction of, or deletion of their data by emailing us.
  - right: Additional rights under local laws
    text: Depending on where you live, you may have additional rights under laws such as the CCPA.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information, and we don't use lead data to market to leads ourselves.
  subprocessors:
    text: Service providers that host and run the service (for example Cloudflare for hosting, Neon for our database, and an SMS provider for caller alerts) process data on our behalf.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ringahuman-com
provenance_date: '2026-11-10'
provider_name: ringahuman-com
provider_slug: ringahuman-com
slug: ringahuman-com-privacy-policy
source_date: '2026-11-10'
source_filename: ringahuman-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ringahuman.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ringahuman-com\naid: ringahuman-com\nurl: https://ringahuman.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Customer account data: email, company name, API keys (stored only as hashes), and OAuth grants when you\n    connect an app such as ChatGPT or Claude.'\n- category: contact\n  text: 'Caller data: name, email, mobile number (for task alerts), states covered, and activity such as tasks claimed,\n    dial times and earnings.'\n- category: communication\n  text: 'Call outcomes: the disposition, caller notes, and any meeting\
  \ time the caller records. We do not record\n    calls.'\n- category: location\n  text: 'Call task data customers send us: the lead''s phone number, name, business name, state or timezone, the\n    goal and brief for the call, links, and the consent basis the customer asserts.'\n- category: device\n  text: 'Operational logs: standard request logs (IP address, user agent, timestamps) for security and debugging.'\npurposes:\n- purpose: Route call tasks\n  text: To route call tasks to callers, enforce calling-hour and do-not-call rules, and return outcomes to the customer\n    who created the task.\n- purpose: Audit trail\n  text: To keep an audit trail of every task (created, claimed, dialed, completed) for compliance and dispute resolution.\n- purpose: Operate and improve service\n  text: To operate, secure and improve the service, and to contact customers and callers about their accounts.\nretention:\n- scope: Task records and audit trails\n  period: while the customer's account is active\
  \ and for a reasonable period afterward\n  text: We keep task records and audit trails while the customer's account is active and for a reasonable period\n    afterward for compliance purposes.\n- scope: Do-not-call entries\n  period: indefinitely\n  text: Do-not-call entries are kept indefinitely so opt-outs keep being honored.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers that host and run the service (for example Cloudflare for hosting, Neon for our database,\n    and an SMS provider for caller alerts) process data on our behalf.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account data deletion by contacting us\n  text: Customers can ask us to delete their account data.\nrights:\n- right: Access, correction, deletion\n  text: Customers and callers can request access to, correction of, or deletion of their data by emailing us.\n- right: Additional rights under local laws\n  text: Depending on where you live,\
  \ you may have additional rights under laws such as the CCPA.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information, and we don't use lead data to market to leads ourselves.\n"
source_yaml_url: https://artifacts.apis.io/ringahuman-com/privacy/ringahuman-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from ringahuman-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Telephony
- Lead Generation
- Compliance
---
