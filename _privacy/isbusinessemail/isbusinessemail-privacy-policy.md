---
api_specs:
- filename: isbusinessemail-check-api-openapi.yml
  format: yaml
  label: isBusinessEmail Check API
  slug: isbusinessemail-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-check-api-openapi.yml
- filename: isbusinessemail-feedback-api-openapi.yml
  format: yaml
  label: isBusinessEmail Feedback API
  slug: isbusinessemail-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-feedback-api-openapi.yml
- filename: isbusinessemail-health-api-openapi.yml
  format: yaml
  label: isBusinessEmail Health API
  slug: isbusinessemail-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-health-api-openapi.yml
- filename: isbusinessemail-usage-api-openapi.yml
  format: yaml
  label: isBusinessEmail Usage API
  slug: isbusinessemail-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-usage-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, name, sign-in provider and identifiers (Google or Microsoft account IDs, Microsoft tenant ID)
  - category: financial
    text: Stripe collects your billing name and address, VAT ID and card; we never see or store card details
  - category: device
    text: 'Session data: hashed session tokens, device and approximate location for sign-in alerts'
  - category: behavioral
    text: 'Usage: checks per day and category, latency, the last 1,000 requests (domain only)'
  deletion:
    route: Dashboard export and delete (Profile)
    text: Account holders can export and delete their data from the dashboard (Profile).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Create and run account
    text: Create and run your account, sign you in
  - purpose: Billing
    text: Take payment, charge usage, issue invoices, handle VAT
  - purpose: Abuse prevention
    text: Protect it from bots and abuse, rate-limit the public checker
  - purpose: Analytics
    text: Understand how the site is used
  residency:
  - region: EU
    text: Our database is in the EU.
  retention:
  - period: deleted within 30 days of account deletion
    scope: Account data
    text: While your account exists; deleted within 30 days of account deletion
  - period: 90 days
    scope: API request analytics
    text: API request analytics (no email addresses) 90 days
  - period: up to 10 years
    scope: Billing records
    text: As long as accounting and tax law requires (in Lithuania, generally up to 10 years), also after the account is deleted
  - period: 14 months
    scope: Google Analytics data
    text: Google Analytics data 14 months (Google Analytics setting)
  rights:
  - right: access
    text: access your personal data and get a copy
  - right: rectify
    text: rectify inaccurate data
  - right: erase
    text: erase your data
  - right: restrict processing
    text: restrict processing
  - right: portability
    text: data portability , for data you gave us under contract or consent
  - right: object
    text: object to processing based on legitimate interests, including the blocklist, at any time
  - right: withdraw consent
    text: withdraw consent at any time (marketing emails, analytics)
  role:
    text: The controller is Tilfortis MB , a small partnership ( mažoji bendrija ) registered in Lithuania.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal data.
  subprocessors:
    text: The current list of processors is on our Subprocessors page.
    url: null
  transfers:
  - mechanism: adequacy
    text: transfers rely on an adequacy decision (including the EU–US Data Privacy Framework for certified recipients)
  - mechanism: SCC
    text: or on the European Commission’s Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: isBusinessEmail
provenance_date: '2026-11-09'
provider_name: isBusinessEmail
provider_slug: isbusinessemail
slug: isbusinessemail-privacy-policy
source_date: '2026-11-09'
source_filename: isbusinessemail-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://isbusinessemail.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: isBusinessEmail\naid: isbusinessemail\nurl: https://isbusinessemail.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is Tilfortis MB , a small partnership ( mažoji bendrija ) registered in Lithuania.\ndata_categories:\n- category: contact\n  text: Email address, name, sign-in provider and identifiers (Google or Microsoft account IDs, Microsoft tenant\n    ID)\n- category: financial\n  text: Stripe collects your billing name and address, VAT ID and card; we never see or store card details\n- category: device\n  text: 'Session data: hashed session tokens, device and\
  \ approximate location for sign-in alerts'\n- category: behavioral\n  text: 'Usage: checks per day and category, latency, the last 1,000 requests (domain only)'\npurposes:\n- purpose: Create and run account\n  text: Create and run your account, sign you in\n- purpose: Billing\n  text: Take payment, charge usage, issue invoices, handle VAT\n- purpose: Abuse prevention\n  text: Protect it from bots and abuse, rate-limit the public checker\n- purpose: Analytics\n  text: Understand how the site is used\nretention:\n- scope: Account data\n  period: deleted within 30 days of account deletion\n  text: While your account exists; deleted within 30 days of account deletion\n- scope: API request analytics\n  period: 90 days\n  text: API request analytics (no email addresses) 90 days\n- scope: Billing records\n  period: up to 10 years\n  text: As long as accounting and tax law requires (in Lithuania, generally up to 10 years), also after the account\n    is deleted\n- scope: Google Analytics data\n\
  \  period: 14 months\n  text: Google Analytics data 14 months (Google Analytics setting)\nresidency:\n- region: EU\n  text: Our database is in the EU.\ntransfers:\n- mechanism: adequacy\n  text: transfers rely on an adequacy decision (including the EU–US Data Privacy Framework for certified recipients)\n- mechanism: SCC\n  text: or on the European Commission’s Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: The current list of processors is on our Subprocessors page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard export and delete (Profile)\n  text: Account holders can export and delete their data from the dashboard (Profile).\nrights:\n- right: access\n  text: access your personal data and get a copy\n- right: rectify\n  text: rectify inaccurate data\n- right: erase\n  text: erase your data\n- right: restrict processing\n  text: restrict processing\n- right: portability\n  text: data portability , for data you gave us under contract\
  \ or consent\n- right: object\n  text: object to processing based on legitimate interests, including the blocklist, at any time\n- right: withdraw consent\n  text: withdraw consent at any time (marketing emails, analytics)\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/isbusinessemail/privacy/isbusinessemail-privacy-policy.yml
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
summary_line: 26 quoted statements, read from isBusinessEmail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- BusinessTools
- EU-hosted
---
