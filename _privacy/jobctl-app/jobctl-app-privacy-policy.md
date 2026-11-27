---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account: your email address (used for magic-link sign-in only).'
  - category: professional
    text: 'Application data you provide: companies, roles, statuses, salaries, notes, interview details, attached CV/cover-letter files, company analyses, and match assessments'
  - category: device
    text: 'Technical: standard server logs (IP address, timestamps, request paths) for security and abuse prevention, retained for up to 30 days.'
  deletion:
    route: 'Settings: delete account'
    text: 'Delete: deleting your account (Settings) permanently and irreversibly removes all your data — applications, files, analyses, events, tokens — in line with GDPR Art. 17.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: store and display your job-application pipeline.'
  - purpose: Authentication
    text: To authenticate you (magic-link emails, session cookies, API tokens, OAuth tokens).
  - purpose: Protect the service
    text: To protect the service (rate limiting, abuse detection via server logs).
  residency:
  - region: Germany (eu-central-1, Frankfurt)
    text: Data is stored in a PostgreSQL database hosted on Amazon Web Services in eu-central-1 (Frankfurt, Germany)
  retention:
  - period: null
    scope: Account data
    text: Your data is kept for as long as your account exists.
  - period: 30 days
    scope: Server logs
    text: Server logs rotate within 30 days.
  rights:
  - right: access, rectify, export, erase
    text: You have the right to access, rectify, export, and erase your personal data, and to object to or restrict processing.
  role:
    text: 'Data controller: Dmytro Rybka, Germany. Email: dmytro@rybka.me'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No profiling, no advertising, no sale of personal data, and no use of your data to train machine-learning models.
  subprocessors:
    text: 4. Third parties Amazon Web Services — hosting and database (EU region). Resend — delivers magic-link sign-in emails (your email address only). GitHub Pages — serves this static website (jobctl.app); no account data touches it.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: jobctl-app
provenance_date: '2026-11-09'
provider_name: jobctl-app
provider_slug: jobctl-app
slug: jobctl-app-privacy-policy
source_date: '2026-11-09'
source_filename: jobctl-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jobctl.app/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: jobctl-app\naid: jobctl-app\nurl: https://jobctl.app/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data controller: Dmytro Rybka, Germany. Email: dmytro@rybka.me'\ndata_categories:\n- category: contact\n  text: 'Account: your email address (used for magic-link sign-in only).'\n- category: professional\n  text: 'Application data you provide: companies, roles, statuses, salaries, notes, interview details, attached\n    CV/cover-letter files, company analyses, and match assessments'\n- category: device\n  text: 'Technical: standard server logs (IP address, timestamps, request paths)\
  \ for security and abuse prevention,\n    retained for up to 30 days.'\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: store and display your job-application pipeline.'\n- purpose: Authentication\n  text: To authenticate you (magic-link emails, session cookies, API tokens, OAuth tokens).\n- purpose: Protect the service\n  text: To protect the service (rate limiting, abuse detection via server logs).\nretention:\n- scope: Account data\n  period: null\n  text: Your data is kept for as long as your account exists.\n- scope: Server logs\n  period: 30 days\n  text: Server logs rotate within 30 days.\nresidency:\n- region: Germany (eu-central-1, Frankfurt)\n  text: Data is stored in a PostgreSQL database hosted on Amazon Web Services in eu-central-1 (Frankfurt, Germany)\ntransfers: []\nsubprocessors:\n  url: null\n  text: 4. Third parties Amazon Web Services — hosting and database (EU region). Resend — delivers magic-link sign-in\n    emails (your email address only).\
  \ GitHub Pages — serves this static website (jobctl.app); no account data touches\n    it.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Settings: delete account'\n  text: 'Delete: deleting your account (Settings) permanently and irreversibly removes all your data — applications,\n    files, analyses, events, tokens — in line with GDPR Art. 17.'\nrights:\n- right: access, rectify, export, erase\n  text: You have the right to access, rectify, export, and erase your personal data, and to object to or restrict\n    processing.\nsale_or_sharing:\n  stance: prohibited\n  text: No profiling, no advertising, no sale of personal data, and no use of your data to train machine-learning\n    models.\n"
source_yaml_url: https://artifacts.apis.io/jobctl-app/privacy/jobctl-app-privacy-policy.yml
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
summary_line: 14 quoted statements, read from jobctl-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job-Tracking
- Developer Tools
- Artificial Intelligence
- MCP
- Productivity
---
