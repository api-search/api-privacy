---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: the email address you signed up with, the people you add to the console (email address and role)
  - category: communication
    text: 'For every message received: the sender, recipients, subject, the text and HTML body, threading headers'
  - category: identifying
    text: API tokens, OAuth tokens, sign-in codes, sign-in links and session cookies are stored only as one-way (SHA-256) hashes
  - category: device
    text: For each sign-in link we keep the IP address and browser user agent of the browser that requested it
  - category: location
    text: 'Rate limits : to limit sign-in attempts we count requests per IP address.'
  - category: financial
    text: we store the amount, Stripe's session and payment references, and the status of each top-up
  - category: communication
    text: every text it receives and sends (the other party's mobile phone number, the text, the time and its delivery status)
  deletion:
    route: Write to ben@hapi.vc or support@aimailmcp.com; Data deletion page
    text: Write to ben@hapi.vc or support@aimailmcp.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service and answer requests
    text: People who run AI Mail access stored mail only to keep the service running, to answer your request, or when the law requires it.
  - purpose: AI classification of incoming mail
    text: 'AI Mail''s automatic classification labels incoming mail: the account sees prompt-injection flags, a category, and whether a message needs a reply.'
  residency:
  - region: United States
    text: Railway (United States) hosts the AI Mail server and its Postgres database
  retention:
  - period: until it is deleted
    scope: Mail
    text: Mail is kept until it is deleted. There is no automatic expiry.
  - period: 10 minutes
    scope: Sign-in codes
    text: Sign-in codes expire after 10 minutes, sign-in links after 15 minutes, console sessions after 30 days
  - period: at least 2 days
    scope: Rate limit counters
    text: These counters, with the IP address, are kept for at least 2 days, then removed by a periodic clean-up.
  - period: 180 days
    scope: OAuth connections
    text: These records are deleted after 180 days.
  - period: null
    scope: Audit log, delivery and usage records
    text: The audit log, delivery records and usage records are kept after a mailbox or domain is removed, and are deleted with your account.
  - period: null
    scope: Texts and opt-in records
    text: Texts and opt-in records are kept until the account deletes the number or the account, like mail
  rights:
  - right: access, correction, export, deletion
    text: You can ask to see, correct, export or delete the data we hold about you, and we answer within 30 days.
  - right: complain to data protection authority
    text: including the right to complain to a data protection authority.
  role:
    text: AI Mail MCP is a product of Hapi.vc, LLC (United States), which is responsible for the data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data or use it for advertising.
  subprocessors:
    text: Cloudflare (United States). Email Routing receives mail sent to AI Mail addresses
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Mail MCP
provenance_date: '2026-11-09'
provider_name: AI Mail MCP
provider_slug: aimailmcp-com
slug: aimailmcp-com-privacy-policy
source_date: '2026-11-09'
source_filename: aimailmcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aimailmcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Mail MCP\naid: aimailmcp-com\nurl: https://aimailmcp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AI Mail MCP is a product of Hapi.vc, LLC (United States), which is responsible for the data described here.\ndata_categories:\n- category: contact\n  text: the email address you signed up with, the people you add to the console (email address and role)\n- category: communication\n  text: 'For every message received: the sender, recipients, subject, the text and HTML body, threading headers'\n- category: identifying\n  text: API tokens, OAuth tokens, sign-in codes, sign-in links\
  \ and session cookies are stored only as one-way (SHA-256)\n    hashes\n- category: device\n  text: For each sign-in link we keep the IP address and browser user agent of the browser that requested it\n- category: location\n  text: 'Rate limits : to limit sign-in attempts we count requests per IP address.'\n- category: financial\n  text: we store the amount, Stripe's session and payment references, and the status of each top-up\n- category: communication\n  text: every text it receives and sends (the other party's mobile phone number, the text, the time and its delivery\n    status)\npurposes:\n- purpose: operate the service and answer requests\n  text: People who run AI Mail access stored mail only to keep the service running, to answer your request, or when\n    the law requires it.\n- purpose: AI classification of incoming mail\n  text: 'AI Mail''s automatic classification labels incoming mail: the account sees prompt-injection flags, a category,\n    and whether a message needs a reply.'\n\
  retention:\n- scope: Mail\n  period: until it is deleted\n  text: Mail is kept until it is deleted. There is no automatic expiry.\n- scope: Sign-in codes\n  period: 10 minutes\n  text: Sign-in codes expire after 10 minutes, sign-in links after 15 minutes, console sessions after 30 days\n- scope: Rate limit counters\n  period: at least 2 days\n  text: These counters, with the IP address, are kept for at least 2 days, then removed by a periodic clean-up.\n- scope: OAuth connections\n  period: 180 days\n  text: These records are deleted after 180 days.\n- scope: Audit log, delivery and usage records\n  period: null\n  text: The audit log, delivery records and usage records are kept after a mailbox or domain is removed, and are\n    deleted with your account.\n- scope: Texts and opt-in records\n  period: null\n  text: Texts and opt-in records are kept until the account deletes the number or the account, like mail\nresidency:\n- region: United States\n  text: Railway (United States) hosts the\
  \ AI Mail server and its Postgres database\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare (United States). Email Routing receives mail sent to AI Mail addresses\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to ben@hapi.vc or support@aimailmcp.com; Data deletion page\n  text: Write to ben@hapi.vc or support@aimailmcp.com .\nrights:\n- right: access, correction, export, deletion\n  text: You can ask to see, correct, export or delete the data we hold about you, and we answer within 30 days.\n- right: complain to data protection authority\n  text: including the right to complain to a data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/aimailmcp-com/privacy/aimailmcp-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from AI Mail MCP's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Artificial Intelligence
- MCP
- Software-as-a-Service
- Inbox
---
