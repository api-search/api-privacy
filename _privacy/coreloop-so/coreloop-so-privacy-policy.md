---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity, from our authentication provider: email address, first and last name, and profile image.'
  - category: contact
    text: Either way we receive your name and message, and — if you provide them — your email address, phone number and a subject line.
  - category: behavioral
    text: We measure which pages are visited and which features are opened.
  - category: device
    text: a value derived from the network address and browser details your browser already sends
  - category: communication
    text: Anything you write into your profile, upload as a document or image, or type into a cancellation survey.
  deletion:
    route: Self-service in account settings, or request via support@coreloop.so
    text: Delete your account. Delete your company, if you own it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account, publish profile, serve page and agent endpoints
    text: Run your account, publish your profile, serve your page and agent endpoints, and support you
  - purpose: Payment and subscription management
    text: Take payment, manage your subscription, and handle cancellations
  - purpose: Newsletter
    text: 'Consent is reserved for the one thing that is genuinely optional: the newsletter.'
  residency:
  - region: Ireland
    text: Our database, our file storage and the application servers that run CoreLoop are all located in Ireland.
  - region: EU (email)
    text: Email is sent and received through our provider's EU region.
  - region: Germany
    text: Error monitoring runs in Germany.
  retention:
  - period: 90 days
    scope: Individual agent and page interaction records
    text: Raw records are deleted after 90 days, leaving only daily counts.
  - period: seven days
    scope: Deleted company data
    text: The data is kept for seven days .
  - period: thirty days
    scope: Backup copies of uploaded files
    text: Every backup copy is deleted thirty days after it was taken
  - period: 180 days
    scope: Resolved or spam support tickets
    text: Resolved or spam support tickets, their messages and their attachments 180 days
  rights:
  - right: Access
    text: Access — a copy of the personal data we hold about you, and an explanation of what we do with it.
  - right: Rectification
    text: Rectification — correction of anything inaccurate, and completion of anything incomplete.
  - right: Erasure
    text: Erasure — deletion, where we have no overriding reason to keep it.
  - right: Restriction
    text: Restriction — a pause on our use of it while a dispute about it is resolved.
  - right: Portability
    text: Portability — the data you gave us, in a structured, machine-readable form, where we process it by consent or under our contract with you.
  - right: Objection
    text: Objection — to any processing we base on legitimate interests, including our security and telemetry processing.
  role:
    text: We are the controller of the personal data we hold for our own purposes
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Who else processes data for us
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CoreLoop
provenance_date: '2026-11-09'
provider_name: CoreLoop
provider_slug: coreloop-so
slug: coreloop-so-privacy-policy
source_date: '2026-11-09'
source_filename: coreloop-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coreloop.so/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CoreLoop\naid: coreloop-so\nurl: https://coreloop.so/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of the personal data we hold for our own purposes\ndata_categories:\n- category: identifying\n  text: 'Identity, from our authentication provider: email address, first and last name, and profile image.'\n- category: contact\n  text: Either way we receive your name and message, and — if you provide them — your email address, phone number\n    and a subject line.\n- category: behavioral\n  text: We measure which pages are visited and which features are opened.\n- category:\
  \ device\n  text: a value derived from the network address and browser details your browser already sends\n- category: communication\n  text: Anything you write into your profile, upload as a document or image, or type into a cancellation survey.\npurposes:\n- purpose: Run account, publish profile, serve page and agent endpoints\n  text: Run your account, publish your profile, serve your page and agent endpoints, and support you\n- purpose: Payment and subscription management\n  text: Take payment, manage your subscription, and handle cancellations\n- purpose: Newsletter\n  text: 'Consent is reserved for the one thing that is genuinely optional: the newsletter.'\nretention:\n- scope: Individual agent and page interaction records\n  period: 90 days\n  text: Raw records are deleted after 90 days, leaving only daily counts.\n- scope: Deleted company data\n  period: seven days\n  text: The data is kept for seven days .\n- scope: Backup copies of uploaded files\n  period: thirty days\n  text:\
  \ Every backup copy is deleted thirty days after it was taken\n- scope: Resolved or spam support tickets\n  period: 180 days\n  text: Resolved or spam support tickets, their messages and their attachments 180 days\nresidency:\n- region: Ireland\n  text: Our database, our file storage and the application servers that run CoreLoop are all located in Ireland.\n- region: EU (email)\n  text: Email is sent and received through our provider's EU region.\n- region: Germany\n  text: Error monitoring runs in Germany.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who else processes data for us\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service in account settings, or request via support@coreloop.so\n  text: Delete your account. Delete your company, if you own it.\nrights:\n- right: Access\n  text: Access — a copy of the personal data we hold about you, and an explanation of what we do with it.\n- right: Rectification\n  text: Rectification — correction of\
  \ anything inaccurate, and completion of anything incomplete.\n- right: Erasure\n  text: Erasure — deletion, where we have no overriding reason to keep it.\n- right: Restriction\n  text: Restriction — a pause on our use of it while a dispute about it is resolved.\n- right: Portability\n  text: Portability — the data you gave us, in a structured, machine-readable form, where we process it by consent\n    or under our contract with you.\n- right: Objection\n  text: Objection — to any processing we base on legitimate interests, including our security and telemetry processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/coreloop-so/privacy/coreloop-so-privacy-policy.yml
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
summary_line: 25 quoted statements, read from CoreLoop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- A2A
- llms.txt
- Business Directory
- Agent Discoverability
---
