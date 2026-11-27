---
api_specs:
- filename: refract-social-openapi-generated.yml
  format: yaml
  label: Refract API
  slug: refract-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/refract-social/openapi/_ae-authored/refract-social-openapi-generated.yml
claim_count: 35
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address and, if you add one, a profile picture.
  - category: contact
    text: Your questions, Help's answers, what Help checked in your workspace to answer
  - category: financial
    text: Stripe collects your card or other payment method, billing address and tax ID on its own pages; we never see your full card number.
  - category: location
    text: IP address, browser user agent and last activity time
  - category: behavioral
    text: what the page shows and how you move, click, scroll and type on it
  - category: device
    text: your browser, system and screen size
  - category: communication
    text: Email with us. If you write to us, we keep the conversation to help you.
  - category: professional
    text: Organization name, plan, billing interval, credits and their history, and team members' roles and workspace access.
  deletion:
    route: Profile and security, Delete account; or email privacy@refract.social
    text: 'Delete your account: Profile and security, Delete account.'
  dpa:
    available: true
    text: 'Anpsthemes LLC itself is in the US: our access to the data is covered by the same safeguards in our Data processing agreement .'
    url: null
  purposes:
  - purpose: Running your account, workspaces and team
    text: Running your account, workspaces and team
  - purpose: Publishing, scheduling and analytics on connected networks and WordPress sites
    text: Publishing, scheduling and analytics on the networks and WordPress sites you connect
  - purpose: Billing, credits and invoices
    text: Billing, credits and invoices (through Stripe)
  - purpose: Finding and fixing faults
    text: Finding and fixing faults
  - purpose: Understanding how Refract is used, to improve it
    text: Understanding how Refract is used, to improve it
  residency:
  - region: Finland
    text: The database and app run on servers at Hetzner in Helsinki, Finland.
  - region: Netherlands (EU)
    text: Media files and database backups are stored with Backblaze in its EU Central region (Amsterdam, Netherlands), in private storage.
  retention:
  - period: Until you delete it.
    scope: Account
    text: Until you delete it. Deleting it removes your sign-in methods, memberships, API tokens, notifications and sessions at once
  - period: 2 hours
    scope: Sessions
    text: Expire after 2 hours without activity, or up to 400 days with the "remember me" cookie
  - period: 10 minutes
    scope: Sign-in codes
    text: Usable for 10 minutes; kept only as a hash, and deleted a day after they expire.
  - period: 7 days
    scope: Webhook delivery logs
    text: Webhook delivery logs 7 days.
  - period: About 30 days
    scope: Backups
    text: Backups are kept for about 30 days.
  - period: 90 days at most
    scope: Error reports
    text: Deleted by Sentry after 90 days at most.
  - period: 7 years
    scope: Pageviews and usage events
    text: Pageviews and usage events Deleted by PostHog after 7 years.
  - period: 30 days
    scope: Recordings of visits to public pages
    text: Recordings of visits to the public pages Deleted by PostHog after 30 days.
  rights:
  - right: Access and portability
    text: see the personal data we hold about you and get a copy, in a portable format
  - right: Correction
    text: correct it (most of it you can edit yourself in Refract)
  - right: Deletion
    text: have it deleted
  - right: Restrict or object
    text: restrict or object to our use of it, including objecting to product news emails at any time
  - right: Withdraw consent
    text: withdraw consent where we rely on it
  role:
    text: We are the controller of the personal data described here, except as the next paragraph says.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your personal data, and we don't share it for cross-context behavioural advertising.
  subprocessors:
    text: Provider What for Where Hetzner Online Servers and database Helsinki, Finland
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (and the UK addendum) in our agreements with those providers
  - mechanism: DPF
    text: or on the provider's certification under the EU–US Data Privacy Framework where it has one.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Refract
provenance_date: '2026-11-10'
provider_name: Refract
provider_slug: refract-social
slug: refract-social-privacy-policy
source_date: '2026-11-10'
source_filename: refract-social-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://refract.social/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Refract\naid: refract-social\nurl: https://refract.social/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of the personal data described here, except as the next paragraph says.\ndata_categories:\n- category: identifying\n  text: Name, email address and, if you add one, a profile picture.\n- category: contact\n  text: Your questions, Help's answers, what Help checked in your workspace to answer\n- category: financial\n  text: Stripe collects your card or other payment method, billing address and tax ID on its own pages; we never\n    see your full card number.\n\
  - category: location\n  text: IP address, browser user agent and last activity time\n- category: behavioral\n  text: what the page shows and how you move, click, scroll and type on it\n- category: device\n  text: your browser, system and screen size\n- category: communication\n  text: Email with us. If you write to us, we keep the conversation to help you.\n- category: professional\n  text: Organization name, plan, billing interval, credits and their history, and team members' roles and workspace\n    access.\npurposes:\n- purpose: Running your account, workspaces and team\n  text: Running your account, workspaces and team\n- purpose: Publishing, scheduling and analytics on connected networks and WordPress sites\n  text: Publishing, scheduling and analytics on the networks and WordPress sites you connect\n- purpose: Billing, credits and invoices\n  text: Billing, credits and invoices (through Stripe)\n- purpose: Finding and fixing faults\n  text: Finding and fixing faults\n- purpose: Understanding\
  \ how Refract is used, to improve it\n  text: Understanding how Refract is used, to improve it\nretention:\n- scope: Account\n  period: Until you delete it.\n  text: Until you delete it. Deleting it removes your sign-in methods, memberships, API tokens, notifications and\n    sessions at once\n- scope: Sessions\n  period: 2 hours\n  text: Expire after 2 hours without activity, or up to 400 days with the \"remember me\" cookie\n- scope: Sign-in codes\n  period: 10 minutes\n  text: Usable for 10 minutes; kept only as a hash, and deleted a day after they expire.\n- scope: Webhook delivery logs\n  period: 7 days\n  text: Webhook delivery logs 7 days.\n- scope: Backups\n  period: About 30 days\n  text: Backups are kept for about 30 days.\n- scope: Error reports\n  period: 90 days at most\n  text: Deleted by Sentry after 90 days at most.\n- scope: Pageviews and usage events\n  period: 7 years\n  text: Pageviews and usage events Deleted by PostHog after 7 years.\n- scope: Recordings of visits\
  \ to public pages\n  period: 30 days\n  text: Recordings of visits to the public pages Deleted by PostHog after 30 days.\nresidency:\n- region: Finland\n  text: The database and app run on servers at Hetzner in Helsinki, Finland.\n- region: Netherlands (EU)\n  text: Media files and database backups are stored with Backblaze in its EU Central region (Amsterdam, Netherlands),\n    in private storage.\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (and the UK addendum) in our agreements\n    with those providers\n- mechanism: DPF\n  text: or on the provider's certification under the EU–US Data Privacy Framework where it has one.\nsubprocessors:\n  url: null\n  text: Provider What for Where Hetzner Online Servers and database Helsinki, Finland\ndpa:\n  available: true\n  url: null\n  text: 'Anpsthemes LLC itself is in the US: our access to the data is covered by the same safeguards in our Data\n    processing agreement .'\ndeletion:\n\
  \  route: Profile and security, Delete account; or email privacy@refract.social\n  text: 'Delete your account: Profile and security, Delete account.'\nrights:\n- right: Access and portability\n  text: see the personal data we hold about you and get a copy, in a portable format\n- right: Correction\n  text: correct it (most of it you can edit yourself in Refract)\n- right: Deletion\n  text: have it deleted\n- right: Restrict or object\n  text: restrict or object to our use of it, including objecting to product news emails at any time\n- right: Withdraw consent\n  text: withdraw consent where we rely on it\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your personal data, and we don't share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/refract-social/privacy/refract-social-privacy-policy.yml
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
summary_line: 35 quoted statements, read from Refract's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Scheduling
- Artificial Intelligence
- Automation
- Company
---
