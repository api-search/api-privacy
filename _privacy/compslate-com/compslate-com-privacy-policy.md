---
claim_count: 37
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: names, work email addresses, roles and reporting lines of the people a workspace admin adds.'
  - category: financial
    text: 'Billing data: invoices and payment records. If you pay by card, Stripe handles the card; we never see or store card numbers.'
  - category: communication
    text: 'Built-in chat: the messages people type in the built-in chat and its replies, stored with the workspace so a conversation can be picked up again.'
  - category: device
    text: 'Technical data: IP addresses for rate limiting and security, and a sign-in cookie.'
  - category: behavioral
    text: 'Activity log: which person made which change, when, and whether it came from the web app, the built-in chat or an AI assistant.'
  - category: identifying
    source: https://compslate.com/dpa
    text: names, work email addresses, job titles, roles and reporting lines
  - category: financial
    source: https://compslate.com/dpa
    text: compensation terms (plans, OTE, base, quota and pay components); deals and bookings; calculated payouts and payments
  - category: communication
    source: https://compslate.com/dpa
    text: messages typed in the built-in chat
  - category: behavioral
    source: https://compslate.com/dpa
    text: the activity log of who changed what, when and how
  deletion:
    route: email legal@compslate.com or admin self-service
    text: Admins can export everything (CSV or Excel) and delete people, plans and deals at any time. To delete a whole workspace, or to access, correct or delete personal data about you, email legal@compslate.com .
  dpa:
    available: true
    text: Data processing addendum
    url: https://compslate.com/dpa
  purposes:
  - purpose: run the service
    text: 'Only to run the service for your workspace: calculating pay, showing comp cards and team views, sending sign-in links and notices an admin asks for, billing, security, and support.'
  - purpose: providing, securing and supporting the Service
    source: https://compslate.com/dpa
    text: 'Purpose: providing, securing and supporting the Service for Customer, as described in the Terms'
  - purpose: Hosting, database, backups and email
    source: https://compslate.com/subprocessors
    text: Hosting, database and backups, and sending email (sign-in links and notices)
  - purpose: Built-in chat AI model
    source: https://compslate.com/subprocessors
    text: 'The AI model behind the built-in chat: what people type in it and the workspace data the chat reads to answer.'
  - purpose: Card payment processing
    source: https://compslate.com/subprocessors
    text: Card payment processing, for customers who pay by card
  - purpose: DNS and email forwarding
    source: https://compslate.com/subprocessors
    text: DNS for our domain, and forwarding of email sent to our addresses
  - purpose: Web fonts
    source: https://compslate.com/subprocessors
    text: Web fonts on our pages; sees visitors' IP addresses
  - purpose: Support mailbox
    source: https://compslate.com/subprocessors
    text: 'Our support mailbox: email you send to our addresses'
  residency:
  - region: United States (us-east-1)
    text: In Amazon Web Services in the United States (us-east-1), encrypted at rest and in transit.
  - region: United States
    source: https://compslate.com/dpa
    text: CompSlate stores Customer Data in the United States, in Amazon Web Services' us-east-1 (N. Virginia) region.
  - region: United States
    source: https://compslate.com/subprocessors
    text: United States (us-east-1, N. Virginia)
  retention:
  - period: for as long as the workspace exists
    scope: workspace data
    text: 'Workspace data: for as long as the workspace exists.'
  - period: 30 days
    scope: after deletion
    text: 'After deletion: removed within 30 days; database backups roll off within 35 days.'
  - period: 90 days
    scope: server logs
    text: 'Server logs: 90 days.'
  - period: 30 days
    scope: sessions
    text: 'Sessions: 30 days.'
  - period: null
    scope: personal data after Terms end
    source: https://compslate.com/dpa
    text: When the Terms end, Customer has 30 days to export its data or ask CompSlate for an export; after that, CompSlate deletes Customer's personal data from the Service
  - period: a further 35 days
    scope: database backups
    source: https://compslate.com/dpa
    text: copies in database backups roll off within a further 35 days
  rights:
  - right: know and access
    text: 'Know and access: what personal information we have about you, where it came from, why we use it and who we share it with, and a copy of it.'
  - right: delete
    text: 'Delete: ask us to delete personal information about you, subject to exceptions the law allows (for example, records we must keep).'
  - right: correct
    text: 'Correct: ask us to fix inaccurate personal information.'
  - right: appeal
    text: Appeals. If we decline your request, you can appeal by replying to our decision.
  - right: access, correction, export, deletion via admins
    source: https://compslate.com/dpa
    text: Admins can view, correct, export and delete most personal data themselves in the Service.
  - right: reasonable help with data subject requests
    source: https://compslate.com/dpa
    text: CompSlate will provide reasonable help for Customer to respond to requests to exercise rights under Data Protection Laws.
  role:
    text: For that data ("customer data"), the company is in charge and CompSlate acts as its service provider (a "processor" in some laws)
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information or share it for cross-context behavioral advertising, and we haven't in the past 12 months, so there is nothing to opt out of.
  subprocessors:
    text: The current list, with locations, is on our Subprocessors page.
    url: https://compslate.com/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CompSlate
provenance_date: '2026-11-09'
provider_name: CompSlate
provider_slug: compslate-com
slug: compslate-com-privacy-policy
source_date: '2026-11-09'
source_filename: compslate-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://compslate.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CompSlate\naid: compslate-com\nurl: https://compslate.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://compslate.com/dpa\n  - https://compslate.com/privacy\n  - https://compslate.com/subprocessors\nrole:\n  value: both\n  text: For that data (\"customer data\"), the company is in charge and CompSlate acts as its service provider (a\n    \"processor\" in some laws)\ndata_categories:\n- category: identifying\n  text: 'Account data: names, work email addresses, roles and reporting lines of the people a workspace admin adds.'\n- category: financial\n  text: 'Billing data: invoices and payment records.\
  \ If you pay by card, Stripe handles the card; we never see or\n    store card numbers.'\n- category: communication\n  text: 'Built-in chat: the messages people type in the built-in chat and its replies, stored with the workspace\n    so a conversation can be picked up again.'\n- category: device\n  text: 'Technical data: IP addresses for rate limiting and security, and a sign-in cookie.'\n- category: behavioral\n  text: 'Activity log: which person made which change, when, and whether it came from the web app, the built-in\n    chat or an AI assistant.'\n- category: identifying\n  text: names, work email addresses, job titles, roles and reporting lines\n  source: https://compslate.com/dpa\n- category: financial\n  text: compensation terms (plans, OTE, base, quota and pay components); deals and bookings; calculated payouts\n    and payments\n  source: https://compslate.com/dpa\n- category: communication\n  text: messages typed in the built-in chat\n  source: https://compslate.com/dpa\n\
  - category: behavioral\n  text: the activity log of who changed what, when and how\n  source: https://compslate.com/dpa\npurposes:\n- purpose: run the service\n  text: 'Only to run the service for your workspace: calculating pay, showing comp cards and team views, sending\n    sign-in links and notices an admin asks for, billing, security, and support.'\n- purpose: providing, securing and supporting the Service\n  text: 'Purpose: providing, securing and supporting the Service for Customer, as described in the Terms'\n  source: https://compslate.com/dpa\n- purpose: Hosting, database, backups and email\n  text: Hosting, database and backups, and sending email (sign-in links and notices)\n  source: https://compslate.com/subprocessors\n- purpose: Built-in chat AI model\n  text: 'The AI model behind the built-in chat: what people type in it and the workspace data the chat reads to\n    answer.'\n  source: https://compslate.com/subprocessors\n- purpose: Card payment processing\n  text: Card\
  \ payment processing, for customers who pay by card\n  source: https://compslate.com/subprocessors\n- purpose: DNS and email forwarding\n  text: DNS for our domain, and forwarding of email sent to our addresses\n  source: https://compslate.com/subprocessors\n- purpose: Web fonts\n  text: Web fonts on our pages; sees visitors' IP addresses\n  source: https://compslate.com/subprocessors\n- purpose: Support mailbox\n  text: 'Our support mailbox: email you send to our addresses'\n  source: https://compslate.com/subprocessors\nretention:\n- scope: workspace data\n  period: for as long as the workspace exists\n  text: 'Workspace data: for as long as the workspace exists.'\n- scope: after deletion\n  period: 30 days\n  text: 'After deletion: removed within 30 days; database backups roll off within 35 days.'\n- scope: server logs\n  period: 90 days\n  text: 'Server logs: 90 days.'\n- scope: sessions\n  period: 30 days\n  text: 'Sessions: 30 days.'\n- scope: personal data after Terms end\n  period:\
  \ null\n  text: When the Terms end, Customer has 30 days to export its data or ask CompSlate for an export; after that,\n    CompSlate deletes Customer's personal data from the Service\n  source: https://compslate.com/dpa\n- scope: database backups\n  period: a further 35 days\n  text: copies in database backups roll off within a further 35 days\n  source: https://compslate.com/dpa\nresidency:\n- region: United States (us-east-1)\n  text: In Amazon Web Services in the United States (us-east-1), encrypted at rest and in transit.\n- region: United States\n  text: CompSlate stores Customer Data in the United States, in Amazon Web Services' us-east-1 (N. Virginia) region.\n  source: https://compslate.com/dpa\n- region: United States\n  text: United States (us-east-1, N. Virginia)\n  source: https://compslate.com/subprocessors\ntransfers: []\nsubprocessors:\n  url: https://compslate.com/subprocessors\n  text: The current list, with locations, is on our Subprocessors page.\ndpa:\n  available:\
  \ true\n  url: https://compslate.com/dpa\n  text: Data processing addendum\ndeletion:\n  route: email legal@compslate.com or admin self-service\n  text: Admins can export everything (CSV or Excel) and delete people, plans and deals at any time. To delete a\n    whole workspace, or to access, correct or delete personal data about you, email legal@compslate.com .\nrights:\n- right: know and access\n  text: 'Know and access: what personal information we have about you, where it came from, why we use it and who\n    we share it with, and a copy of it.'\n- right: delete\n  text: 'Delete: ask us to delete personal information about you, subject to exceptions the law allows (for example,\n    records we must keep).'\n- right: correct\n  text: 'Correct: ask us to fix inaccurate personal information.'\n- right: appeal\n  text: Appeals. If we decline your request, you can appeal by replying to our decision.\n- right: access, correction, export, deletion via admins\n  text: Admins can view, correct,\
  \ export and delete most personal data themselves in the Service.\n  source: https://compslate.com/dpa\n- right: reasonable help with data subject requests\n  text: CompSlate will provide reasonable help for Customer to respond to requests to exercise rights under Data\n    Protection Laws.\n  source: https://compslate.com/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information or share it for cross-context behavioral advertising, and we haven't\n    in the past 12 months, so there is nothing to opt out of.\n"
source_yaml_url: https://artifacts.apis.io/compslate-com/privacy/compslate-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 37 quoted statements, read from CompSlate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales Compensation
- Sales Commissions
- Revenue Operations
- MCP
- AI Assistants
- SaaS
---
