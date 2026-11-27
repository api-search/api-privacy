---
api_specs:
- filename: bangermail-com-forms-api-openapi.yml
  format: yaml
  label: BangerMail Inc. Forms API
  slug: bangermail-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bangermail-com/openapi/bangermail-com-forms-api-openapi.yml
- filename: bangermail-com-workspaces-api-openapi.yml
  format: yaml
  label: BangerMail Inc. Workspaces API
  slug: bangermail-com-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bangermail-com/openapi/bangermail-com-workspaces-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, sign-in and session information, workspace membership, roles and permissions
  - category: contact
    text: Contacts, lists, segments, and custom fields that you or your agents add or import
  - category: communication
    text: For mailboxes hosted by Banger and mailboxes you connect, this includes message content, attachments, sender and recipient information, subjects, timestamps, headers, thread information, labels, drafts, and delivery status.
  - category: financial
    text: Stripe processes payment-card and billing information needed to charge for the Service.
  - category: behavioral
    text: Limited product and website analytics such as pages visited, referral source, browser and device type, feature usage, and conversion events.
  - category: device
    text: OAuth tokens, API keys, session records, audit events, abuse signals, IP addresses, browser information, and infrastructure logs
  - category: location
    text: IP addresses
  deletion:
    route: Delete your account or contact hello@team.bangermail.com
    text: You may request account or data deletion by contacting hello@team.bangermail.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: 'We use information to: create and manage accounts, workspaces, products, domains, mailboxes, and permissions'
  - purpose: Deliver email and run campaigns
    text: receive, store, search, display, and deliver email, and run Broadcasts, Journeys, and signup forms
  - purpose: Security and abuse prevention
    text: detect, prevent, and respond to spam, fraud, abuse, and security incidents
  - purpose: Analytics and advertising
    text: Analytics and advertising are enabled by default. You can turn them off on the Privacy page.
  residency:
  - region: United States
    text: PlanetScale hosts the primary database, running on AWS in the United States.
  - region: European Union (Frankfurt)
    text: Amazon Web Services sends email through Amazon SES and stores secrets, in the EU (Frankfurt).
  retention:
  - period: null
    scope: Account, workspace, mail, and contact data
    text: Account, workspace, mail, and contact data are generally kept while the account and workspace remain active.
  - period: seven-day window
    scope: Deleted workspace data
    text: Deleting your Banger account starts a seven-day window during which you can cancel.
  - period: one hour
    scope: AI mail assistant run history
    text: AI mail assistant run history is kept for one hour.
  - period: null
    scope: Suppression records
    text: Suppression records, such as unsubscribes, bounces, and complaints, are kept while the workspace exists so that people who opted out are not emailed again.
  - period: up to 90 days
    scope: Ad click identifiers
    text: Ad click identifiers (gclid, gbraid, wbraid, fbclid) and campaign tags stay in the page address and are kept in your browser for up to 90 days
  rights:
  - right: access
    text: access Personal Data about you
  - right: correct
    text: correct inaccurate Personal Data
  - right: deletion
    text: request deletion
  - right: portability
    text: receive a portable copy of certain data
  - right: object or restrict
    text: object to or restrict certain processing
  - right: withdraw consent
    text: withdraw consent
  role:
    text: For account administration, billing, security, and our public website, Banger generally acts as a controller of Personal Data. When Banger processes mail, contacts, and other workspace content on behalf of a customer, the customer is generally the controller and Banger acts as its processor or service provider.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not upload customer lists, mail or contacts.
  subprocessors:
    text: 'Our current subprocessors are: Cloudflare hosts the application, queues, and logs.'
    url: https://bangermail.com/privacy/
  transfers:
  - mechanism: SCC
    text: we use a legally recognized safeguard, such as the European Commission’s Standard Contractual Clauses or applicable UK, Swiss, or Brazilian mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BangerMail Inc.
provenance_date: '2026-11-09'
provider_name: BangerMail Inc.
provider_slug: bangermail-com
slug: bangermail-com-privacy-policy
source_date: '2026-11-09'
source_filename: bangermail-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bangermail.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BangerMail Inc.\naid: bangermail-com\nurl: https://bangermail.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account administration, billing, security, and our public website, Banger generally acts as a controller\n    of Personal Data. When Banger processes mail, contacts, and other workspace content on behalf of a customer,\n    the customer is generally the controller and Banger acts as its processor or service provider.\ndata_categories:\n- category: identifying\n  text: Your name, email address, sign-in and session information, workspace membership, roles and permissions\n\
  - category: contact\n  text: Contacts, lists, segments, and custom fields that you or your agents add or import\n- category: communication\n  text: For mailboxes hosted by Banger and mailboxes you connect, this includes message content, attachments, sender\n    and recipient information, subjects, timestamps, headers, thread information, labels, drafts, and delivery status.\n- category: financial\n  text: Stripe processes payment-card and billing information needed to charge for the Service.\n- category: behavioral\n  text: Limited product and website analytics such as pages visited, referral source, browser and device type, feature\n    usage, and conversion events.\n- category: device\n  text: OAuth tokens, API keys, session records, audit events, abuse signals, IP addresses, browser information,\n    and infrastructure logs\n- category: location\n  text: IP addresses\npurposes:\n- purpose: Provide and operate the Service\n  text: 'We use information to: create and manage accounts, workspaces,\
  \ products, domains, mailboxes, and permissions'\n- purpose: Deliver email and run campaigns\n  text: receive, store, search, display, and deliver email, and run Broadcasts, Journeys, and signup forms\n- purpose: Security and abuse prevention\n  text: detect, prevent, and respond to spam, fraud, abuse, and security incidents\n- purpose: Analytics and advertising\n  text: Analytics and advertising are enabled by default. You can turn them off on the Privacy page.\nretention:\n- scope: Account, workspace, mail, and contact data\n  period: null\n  text: Account, workspace, mail, and contact data are generally kept while the account and workspace remain active.\n- scope: Deleted workspace data\n  period: seven-day window\n  text: Deleting your Banger account starts a seven-day window during which you can cancel.\n- scope: AI mail assistant run history\n  period: one hour\n  text: AI mail assistant run history is kept for one hour.\n- scope: Suppression records\n  period: null\n  text: Suppression\
  \ records, such as unsubscribes, bounces, and complaints, are kept while the workspace exists\n    so that people who opted out are not emailed again.\n- scope: Ad click identifiers\n  period: up to 90 days\n  text: Ad click identifiers (gclid, gbraid, wbraid, fbclid) and campaign tags stay in the page address and are\n    kept in your browser for up to 90 days\nresidency:\n- region: United States\n  text: PlanetScale hosts the primary database, running on AWS in the United States.\n- region: European Union (Frankfurt)\n  text: Amazon Web Services sends email through Amazon SES and stores secrets, in the EU (Frankfurt).\ntransfers:\n- mechanism: SCC\n  text: we use a legally recognized safeguard, such as the European Commission’s Standard Contractual Clauses or\n    applicable UK, Swiss, or Brazilian mechanisms.\nsubprocessors:\n  url: https://bangermail.com/privacy/\n  text: 'Our current subprocessors are: Cloudflare hosts the application, queues, and logs.'\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Delete your account or contact hello@team.bangermail.com\n  text: You may request account or data deletion by contacting hello@team.bangermail.com .\nrights:\n- right: access\n  text: access Personal Data about you\n- right: correct\n  text: correct inaccurate Personal Data\n- right: deletion\n  text: request deletion\n- right: portability\n  text: receive a portable copy of certain data\n- right: object or restrict\n  text: object to or restrict certain processing\n- right: withdraw consent\n  text: withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not upload customer lists, mail or contacts.\n"
source_yaml_url: https://artifacts.apis.io/bangermail-com/privacy/bangermail-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from BangerMail Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Artificial Intelligence
- Automation
- Software-as-a-Service
- Marketing
---
