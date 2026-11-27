---
api_specs:
- filename: capslane-com-transcript-api-openapi.yml
  format: yaml
  label: capslane-com Transcript API
  slug: capslane-com-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capslane-com/openapi/capslane-com-transcript-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your Webba ID identifier, name and email address.'
  - category: financial
    text: 'Billing data: Stripe customer, subscription and invoice identifiers. Capslane does not store payment card details.'
  - category: device
    text: 'Security data: session identifiers, timestamps, IP-related server logs and events needed to protect accounts and the API.'
  - category: behavioral
    text: 'Site analytics: pages visited, clicks, scrolling, browser and device information, approximate location and masked session recordings used to understand how the public website and dashboard are used.'
  - category: location
    text: approximate location and masked session recordings
  - category: communication
    text: If you use the documentation chat on a public page, your messages and the conversation history needed to answer are sent to Context7.
  deletion:
    route: Email request to luca.deguin@webba-creative.fr
    text: Send requests to luca.deguin@webba-creative.fr .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide account, API, transcripts, support and paid plan
    text: 'Provide the account, API, transcripts, support and paid plan: performance of the contract or steps requested before entering into it.'
  - purpose: Process payments and maintain invoices
    text: 'Process payments and maintain invoices: performance of the contract and compliance with accounting and tax obligations.'
  - purpose: Secure accounts and prevent abuse
    text: 'Secure accounts, prevent abuse, enforce quotas and diagnose incidents: our legitimate interests in operating a safe and reliable service.'
  - purpose: Measure and improve the service
    text: 'Measure and improve Capslane: our legitimate interest in understanding navigation problems and improving the service.'
  residency:
  - region: France
    text: OVH hosts the core service in France.
  retention:
  - period: seven days
    scope: Dashboard sessions
    text: Dashboard sessions expire after seven days and are deleted when you sign out.
  - period: 30 days
    scope: Native transcript cache entries
    text: Native transcript cache entries expire after 30 days.
  - period: ten years
    scope: Invoices and accounting records
    text: Invoices and accounting records are retained for ten years where French law requires it.
  - period: thirty minutes
    scope: Public acquisition context
    text: Public acquisition context expires after thirty minutes.
  rights:
  - right: access
    text: You may request access, correction, deletion, restriction or portability of your personal data.
  - right: objection
    text: You may object to processing based on legitimate interests.
  - right: withdraw consent
    text: When processing relies on consent, you may withdraw it at any time without affecting earlier processing.
  - right: complaint to CNIL
    text: You may also lodge a complaint with the CNIL , the French data protection authority.
  role:
    text: Webba Creative Technologies is the controller for account administration, security, usage and billing data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use it for third-party advertising.
  subprocessors:
    text: 'Access is limited to authorised Webba personnel and the providers needed to run Capslane: Webba ID: identity and sign-in; Stripe: checkout, subscription management, invoices and payments; OVH SAS: infrastructure hosting in France; YouTube and Google services: access to the public video resources requested by the customer. Microsoft Clarity: privacy-preserving site analytics, heatmaps and masked session recordings. Context7, operated by Upstash: the documentation chat on public pages.'
    url: null
  transfers:
  - mechanism: adequacy
    text: Where required, those transfers rely on an adequacy decision, the European Commission's standard contractual clauses or another safeguard recognised by applicable data protection law.
  - mechanism: SCC
    text: the European Commission's standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: capslane-com
provenance_date: '2026-11-09'
provider_name: capslane-com
provider_slug: capslane-com
slug: capslane-com-privacy-policy
source_date: '2026-11-09'
source_filename: capslane-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://capslane.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: capslane-com\naid: capslane-com\nurl: https://capslane.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Webba Creative Technologies is the controller for account administration, security, usage and billing data.\ndata_categories:\n- category: identifying\n  text: 'Account data: your Webba ID identifier, name and email address.'\n- category: financial\n  text: 'Billing data: Stripe customer, subscription and invoice identifiers. Capslane does not store payment card\n    details.'\n- category: device\n  text: 'Security data: session identifiers, timestamps, IP-related server logs and\
  \ events needed to protect accounts\n    and the API.'\n- category: behavioral\n  text: 'Site analytics: pages visited, clicks, scrolling, browser and device information, approximate location\n    and masked session recordings used to understand how the public website and dashboard are used.'\n- category: location\n  text: approximate location and masked session recordings\n- category: communication\n  text: If you use the documentation chat on a public page, your messages and the conversation history needed to\n    answer are sent to Context7.\npurposes:\n- purpose: Provide account, API, transcripts, support and paid plan\n  text: 'Provide the account, API, transcripts, support and paid plan: performance of the contract or steps requested\n    before entering into it.'\n- purpose: Process payments and maintain invoices\n  text: 'Process payments and maintain invoices: performance of the contract and compliance with accounting and\n    tax obligations.'\n- purpose: Secure accounts and\
  \ prevent abuse\n  text: 'Secure accounts, prevent abuse, enforce quotas and diagnose incidents: our legitimate interests in operating\n    a safe and reliable service.'\n- purpose: Measure and improve the service\n  text: 'Measure and improve Capslane: our legitimate interest in understanding navigation problems and improving\n    the service.'\nretention:\n- scope: Dashboard sessions\n  period: seven days\n  text: Dashboard sessions expire after seven days and are deleted when you sign out.\n- scope: Native transcript cache entries\n  period: 30 days\n  text: Native transcript cache entries expire after 30 days.\n- scope: Invoices and accounting records\n  period: ten years\n  text: Invoices and accounting records are retained for ten years where French law requires it.\n- scope: Public acquisition context\n  period: thirty minutes\n  text: Public acquisition context expires after thirty minutes.\nresidency:\n- region: France\n  text: OVH hosts the core service in France.\ntransfers:\n\
  - mechanism: adequacy\n  text: Where required, those transfers rely on an adequacy decision, the European Commission's standard contractual\n    clauses or another safeguard recognised by applicable data protection law.\n- mechanism: SCC\n  text: the European Commission's standard contractual clauses\nsubprocessors:\n  url: null\n  text: 'Access is limited to authorised Webba personnel and the providers needed to run Capslane: Webba ID: identity\n    and sign-in; Stripe: checkout, subscription management, invoices and payments; OVH SAS: infrastructure hosting\n    in France; YouTube and Google services: access to the public video resources requested by the customer. Microsoft\n    Clarity: privacy-preserving site analytics, heatmaps and masked session recordings. Context7, operated by Upstash:\n    the documentation chat on public pages.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to luca.deguin@webba-creative.fr\n  text: Send requests to luca.deguin@webba-creative.fr\
  \ .\nrights:\n- right: access\n  text: You may request access, correction, deletion, restriction or portability of your personal data.\n- right: objection\n  text: You may object to processing based on legitimate interests.\n- right: withdraw consent\n  text: When processing relies on consent, you may withdraw it at any time without affecting earlier processing.\n- right: complaint to CNIL\n  text: You may also lodge a complaint with the CNIL , the French data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not use it for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/capslane-com/privacy/capslane-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from capslane-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- YouTube
- Transcript
- Artificial Intelligence
---
