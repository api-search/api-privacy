---
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email, name, sign-in ID, when you joined and were last seen'
  - category: contact
    text: their email if they give one
  - category: device
    text: 'device details: device model, OS version, app version, SDK version, language, platform (on the web: browser, OS and site name)'
  - category: communication
    text: their messages, the photos and files they attach, and when each was sent and read
  - category: location
    text: an approximate location that Google derives from your IP address
  - category: financial
    text: Billing details of paying teams (name, email, address, VAT number, payment method)
  deletion:
    route: Dashboard deletion, developer deletes user from app, or request by email
    text: deleting an app in the dashboard removes its users, conversations, messages and files for good.
  dpa:
    available: true
    text: under our Data Processing Agreement
    url: null
  purposes:
  - purpose: Sign in and account management
    text: Sign you in and show your team who you are
  - purpose: Run the chat and push
    text: Run the chat and push in your app
  - purpose: Deliver the chat for developer
    text: 'We use it only to deliver the chat: show messages to the developer, send replies back by push and email, and keep the service secure.'
  - purpose: Website analytics with consent
    text: 'Legal basis: your consent (Art. 6(1)(a) GDPR and § 25(1) TDDDG).'
  residency:
  - region: Germany (Falkenstein)
    text: 'Servers: API, database, dashboard, website, backups'
  - region: USA
    text: Google Cloud us-east1
  retention:
  - period: until the developer deletes it
    scope: App users' data
    text: App users' data stays until the developer deletes it
  - period: 30 days
    scope: Developer account end
    text: When a developer's account ends, we delete their apps' data within 30 days.
  - period: 14 days
    scope: Backups
    text: 'Backups : a nightly database backup kept for 14 days'
  - period: 14 days
    scope: Server logs
    text: Server logs (IP address, time, request) are kept for 14 days.
  - period: 13 months
    scope: Google Analytics cookies
    text: Google Analytics sets two cookies ( _ga and _ga_… , kept for 13 months)
  - period: up to an hour
    scope: Agent sign-in links
    text: the dashboard keeps that link for up to an hour
  rights:
  - right: access
    text: You can ask to see the data we hold about you
  - right: correction
    text: correct it
  - right: deletion
    text: delete it
  - right: portability
    text: get a copy in a common format
  - right: restriction and objection
    text: restrict or object to how we use it
  - right: withdraw consent
    text: withdraw consent you gave
  - right: complaint
    text: You can also complain to a data protection authority
  role:
    text: For people who use the dashboard (developers and their teammates at app.devreply.com ), we decide what we collect and why. We are the controller .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don't use it for ads, don't build profiles across apps, don't track users, and don't sell or share it.
  subprocessors:
    text: These companies help us run DevReply and may handle personal data for it.
    url: https://devreply.com/privacy.html#subprocessors
  transfers:
  - mechanism: DPF
    text: we rely on the EU–US Data Privacy Framework (and its UK extension) for providers certified under it
  - mechanism: SCC
    text: and on the European Commission's Standard Contractual Clauses otherwise
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: devreply-com
provenance_date: '2026-11-09'
provider_name: devreply-com
provider_slug: devreply-com
slug: devreply-com-privacy-policy
source_date: '2026-11-09'
source_filename: devreply-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://devreply.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: devreply-com\naid: devreply-com\nurl: https://devreply.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For people who use the dashboard (developers and their teammates at app.devreply.com ), we decide what we\n    collect and why. We are the controller .\ndata_categories:\n- category: identifying\n  text: 'Account: email, name, sign-in ID, when you joined and were last seen'\n- category: contact\n  text: their email if they give one\n- category: device\n  text: 'device details: device model, OS version, app version, SDK version, language, platform (on the web: browser,\n    OS and\
  \ site name)'\n- category: communication\n  text: their messages, the photos and files they attach, and when each was sent and read\n- category: location\n  text: an approximate location that Google derives from your IP address\n- category: financial\n  text: Billing details of paying teams (name, email, address, VAT number, payment method)\npurposes:\n- purpose: Sign in and account management\n  text: Sign you in and show your team who you are\n- purpose: Run the chat and push\n  text: Run the chat and push in your app\n- purpose: Deliver the chat for developer\n  text: 'We use it only to deliver the chat: show messages to the developer, send replies back by push and email,\n    and keep the service secure.'\n- purpose: Website analytics with consent\n  text: 'Legal basis: your consent (Art. 6(1)(a) GDPR and § 25(1) TDDDG).'\nretention:\n- scope: App users' data\n  period: until the developer deletes it\n  text: App users' data stays until the developer deletes it\n- scope: Developer\
  \ account end\n  period: 30 days\n  text: When a developer's account ends, we delete their apps' data within 30 days.\n- scope: Backups\n  period: 14 days\n  text: 'Backups : a nightly database backup kept for 14 days'\n- scope: Server logs\n  period: 14 days\n  text: Server logs (IP address, time, request) are kept for 14 days.\n- scope: Google Analytics cookies\n  period: 13 months\n  text: Google Analytics sets two cookies ( _ga and _ga_… , kept for 13 months)\n- scope: Agent sign-in links\n  period: up to an hour\n  text: the dashboard keeps that link for up to an hour\nresidency:\n- region: Germany (Falkenstein)\n  text: 'Servers: API, database, dashboard, website, backups'\n- region: USA\n  text: Google Cloud us-east1\ntransfers:\n- mechanism: DPF\n  text: we rely on the EU–US Data Privacy Framework (and its UK extension) for providers certified under it\n- mechanism: SCC\n  text: and on the European Commission's Standard Contractual Clauses otherwise\nsubprocessors:\n  url: https://devreply.com/privacy.html#subprocessors\n\
  \  text: These companies help us run DevReply and may handle personal data for it.\ndpa:\n  available: true\n  url: null\n  text: under our Data Processing Agreement\ndeletion:\n  route: Dashboard deletion, developer deletes user from app, or request by email\n  text: deleting an app in the dashboard removes its users, conversations, messages and files for good.\nrights:\n- right: access\n  text: You can ask to see the data we hold about you\n- right: correction\n  text: correct it\n- right: deletion\n  text: delete it\n- right: portability\n  text: get a copy in a common format\n- right: restriction and objection\n  text: restrict or object to how we use it\n- right: withdraw consent\n  text: withdraw consent you gave\n- right: complaint\n  text: You can also complain to a data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We don't use it for ads, don't build profiles across apps, don't track users, and don't sell or share it.\n"
source_yaml_url: https://artifacts.apis.io/devreply-com/privacy/devreply-com-privacy-policy.yml
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
summary_line: 32 quoted statements, read from devreply-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Chat
- Customer Service
- Mobile
- Web
- Developer Tools
---
