---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name and work email, from the invitation your admin sends (sign-in runs through Clerk)
  - category: professional
    text: Your role (admin or member) and whether you are active or paused
  - category: communication
    text: Email and calendar (Gmail and Google Calendar), checked about every hour
  - category: behavioral
    text: Agent conversations with the agents you connect, learned as each turn happens
  - category: contact
    text: What you send us when you ask for an invitation or email us, such as your name, email and company
  - category: device
    text: Standard log data, such as IP address and browser information
  deletion:
    route: Private brain erased on leaving; work facts shared stay with company
    text: 'When someone leaves: the work facts they shared stay with the company. Their private brain is erased right away, with no waiting period.'
  dpa:
    available: true
    text: A data processing agreement is available on request.
    url: null
  purposes:
  - purpose: Build and keep each person's brain and the company brain
    text: To build and keep current each person's brain and the company brain
  - purpose: Run, secure, back up, upgrade and support the install
    text: To run, secure, back up, upgrade and support the install
  - purpose: Detect and prevent fraud or abuse
    text: To detect and prevent fraud or abuse
  - purpose: Comply with legal obligations
    text: To comply with legal obligations
  residency:
  - region: Company's own cloud or Team0 AWS cloud
    text: installed in your company's own cloud (AWS or Google Cloud), or hosted by Team0 on a server of its own
  retention:
  - period: until removed or the person leaves
    scope: Facts
    text: 'Facts: kept with their history, never silently overwritten, until removed or the person leaves'
  - period: 24 hours
    scope: Full read results
    text: 'Full read results: 24 hours'
  - period: 7 days
    scope: Agent conversation words
    text: 'Agent conversation words: 7 days; what was learned stays'
  - period: 30 days
    scope: Other agent and API input
    text: 'Other agent and API input: 30 days, encrypted'
  - period: last 7 are kept
    scope: Backups
    text: 'Backups: one each night; the last 7 are kept'
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification: Correct inaccurate or incomplete data'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal data'
  - right: Portability
    text: 'Portability: Export your data in a machine-readable format'
  - right: Object
    text: 'Object: Opt-out of certain data processing activities'
  - right: Restrict
    text: 'Restrict: Limit how we process your data'
  - right: Withdraw consent
    text: 'Withdraw consent: Turn off sharing or coworker lookups, withdraw what you shared, or disconnect a source at any time'
  role:
    text: Your company is the controller of the data in its install.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal information to third parties or use it for advertising.
  subprocessors:
    text: Service Providers the Install Uses
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: team0-ai
provenance_date: '2026-11-10'
provider_name: team0-ai
provider_slug: team0-ai
slug: team0-ai-privacy-policy
source_date: '2026-11-10'
source_filename: team0-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://team0.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: team0-ai\naid: team0-ai\nurl: https://team0.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Your company is the controller of the data in its install.\ndata_categories:\n- category: identifying\n  text: Your name and work email, from the invitation your admin sends (sign-in runs through Clerk)\n- category: professional\n  text: Your role (admin or member) and whether you are active or paused\n- category: communication\n  text: Email and calendar (Gmail and Google Calendar), checked about every hour\n- category: behavioral\n  text: Agent conversations with the agents you connect, learned\
  \ as each turn happens\n- category: contact\n  text: What you send us when you ask for an invitation or email us, such as your name, email and company\n- category: device\n  text: Standard log data, such as IP address and browser information\npurposes:\n- purpose: Build and keep each person's brain and the company brain\n  text: To build and keep current each person's brain and the company brain\n- purpose: Run, secure, back up, upgrade and support the install\n  text: To run, secure, back up, upgrade and support the install\n- purpose: Detect and prevent fraud or abuse\n  text: To detect and prevent fraud or abuse\n- purpose: Comply with legal obligations\n  text: To comply with legal obligations\nretention:\n- scope: Facts\n  period: until removed or the person leaves\n  text: 'Facts: kept with their history, never silently overwritten, until removed or the person leaves'\n- scope: Full read results\n  period: 24 hours\n  text: 'Full read results: 24 hours'\n- scope: Agent conversation\
  \ words\n  period: 7 days\n  text: 'Agent conversation words: 7 days; what was learned stays'\n- scope: Other agent and API input\n  period: 30 days\n  text: 'Other agent and API input: 30 days, encrypted'\n- scope: Backups\n  period: last 7 are kept\n  text: 'Backups: one each night; the last 7 are kept'\nresidency:\n- region: Company's own cloud or Team0 AWS cloud\n  text: installed in your company's own cloud (AWS or Google Cloud), or hosted by Team0 on a server of its own\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service Providers the Install Uses\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement is available on request.\ndeletion:\n  route: Private brain erased on leaving; work facts shared stay with company\n  text: 'When someone leaves: the work facts they shared stay with the company. Their private brain is erased right\n    away, with no waiting period.'\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right:\
  \ Rectification\n  text: 'Rectification: Correct inaccurate or incomplete data'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal data'\n- right: Portability\n  text: 'Portability: Export your data in a machine-readable format'\n- right: Object\n  text: 'Object: Opt-out of certain data processing activities'\n- right: Restrict\n  text: 'Restrict: Limit how we process your data'\n- right: Withdraw consent\n  text: 'Withdraw consent: Turn off sharing or coworker lookups, withdraw what you shared, or disconnect a source\n    at any time'\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal information to third parties or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/team0-ai/privacy/team0-ai-privacy-policy.yml
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
summary_line: 28 quoted statements, read from team0-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Knowledge Management
- Automation
---
