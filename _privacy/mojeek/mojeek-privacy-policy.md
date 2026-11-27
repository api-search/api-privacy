---
api_specs:
- filename: mojeek-openapi-generated.yml
  format: yaml
  label: Mojeek API
  slug: mojeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mojeek/openapi/_ae-authored/mojeek-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address and company details
  - category: device
    text: Our standard server logs contain the time of the visit, the page requested and possibly referral data. Browser information is kept in a separate log.
  - category: behavioral
    text: The page requested includes the search terms.
  - category: financial
    text: billing information
  - category: communication
    text: support correspondence
  deletion:
    route: Contact privacy@mojeek.com to request deletion
    text: To use any of these rights, contact us at privacy@mojeek.com.
  dpa:
    available: true
    text: Search queries sent through the API. We process these on behalf of our customer, as their processor, under our Data Processing Agreement .
    url: null
  purposes:
  - purpose: run the account and provide the service
    text: 'run the account and provide the service (lawful basis: contract)'
  - purpose: invoicing and tax records
    text: 'invoice and keep tax records (lawful basis: legal obligation)'
  - purpose: improve search results
    text: We use these aggregate statistics to improve our results, including to test and train our search systems.
  - purpose: return API search results
    text: We use them only to return results and, unless the customer has chosen zero data retention, keep them for up to 90 days solely to fix faults.
  - purpose: ads selection
    text: To select a relevant ad, our servers send adMarketplace your search terms and a two-letter country code only.
  residency:
  - region: UK
    text: Search requests are handled only on our own servers in the UK.
  retention:
  - period: 90 days
    scope: Website logs
    text: Logs are deleted after 90 days.
  - period: 2 years after the last message
    scope: Contact and support emails
    text: Contact and support emails 2 years after the last message, unless you ask us to delete them sooner
  - period: For the life of the account, plus 12 months after it closes
    scope: API account data
    text: API account data For the life of the account, plus 12 months after it closes
  - period: 6 years
    scope: Invoices and tax records
    text: Invoices and tax records 6 years, as UK law requires
  - period: Up to 90 days
    scope: API search queries
    text: API search queries Up to 90 days, or not at all under zero data retention (see above)
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: correction or deletion
    text: have it corrected or deleted
  - right: objection or restriction
    text: object to or restrict its use
  - right: portability
    text: receive a copy in a portable form
  - right: complain
    text: You also have the right to complain to the Information Commissioner's Office .
  role:
    text: Mojeek Limited is the controller of the personal data described in this policy, except where we say otherwise.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: we never sell or distribute this data to any third party.
  subprocessors:
    text: 'We use a small number of providers for business functions: Fastmail for support and general email; Mailgun for account and sign-up emails; Stripe for payments (as an independent controller; see above); and adMarketplace for some ads (search terms only; see Advertising).'
    url: null
  transfers:
  - mechanism: adequacy
    text: Where they do, we rely on UK adequacy regulations (including the UK–US data bridge for certified US companies)
  - mechanism: other
    text: or the UK International Data Transfer Agreement or Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mojeek
provenance_date: '2026-11-10'
provider_name: Mojeek
provider_slug: mojeek
slug: mojeek-privacy-policy
source_date: '2026-11-10'
source_filename: mojeek-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mojeek.com/about/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mojeek\naid: mojeek\nurl: https://www.mojeek.com/about/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Mojeek Limited is the controller of the personal data described in this policy, except where we say otherwise.\ndata_categories:\n- category: identifying\n  text: name, email address and company details\n- category: device\n  text: Our standard server logs contain the time of the visit, the page requested and possibly referral data. Browser\n    information is kept in a separate log.\n- category: behavioral\n  text: The page requested includes the search terms.\n- category: financial\n\
  \  text: billing information\n- category: communication\n  text: support correspondence\npurposes:\n- purpose: run the account and provide the service\n  text: 'run the account and provide the service (lawful basis: contract)'\n- purpose: invoicing and tax records\n  text: 'invoice and keep tax records (lawful basis: legal obligation)'\n- purpose: improve search results\n  text: We use these aggregate statistics to improve our results, including to test and train our search systems.\n- purpose: return API search results\n  text: We use them only to return results and, unless the customer has chosen zero data retention, keep them for\n    up to 90 days solely to fix faults.\n- purpose: ads selection\n  text: To select a relevant ad, our servers send adMarketplace your search terms and a two-letter country code\n    only.\nretention:\n- scope: Website logs\n  period: 90 days\n  text: Logs are deleted after 90 days.\n- scope: Contact and support emails\n  period: 2 years after the last message\n\
  \  text: Contact and support emails 2 years after the last message, unless you ask us to delete them sooner\n- scope: API account data\n  period: For the life of the account, plus 12 months after it closes\n  text: API account data For the life of the account, plus 12 months after it closes\n- scope: Invoices and tax records\n  period: 6 years\n  text: Invoices and tax records 6 years, as UK law requires\n- scope: API search queries\n  period: Up to 90 days\n  text: API search queries Up to 90 days, or not at all under zero data retention (see above)\nresidency:\n- region: UK\n  text: Search requests are handled only on our own servers in the UK.\ntransfers:\n- mechanism: adequacy\n  text: Where they do, we rely on UK adequacy regulations (including the UK–US data bridge for certified US companies)\n- mechanism: other\n  text: or the UK International Data Transfer Agreement or Addendum.\nsubprocessors:\n  url: null\n  text: 'We use a small number of providers for business functions: Fastmail\
  \ for support and general email; Mailgun\n    for account and sign-up emails; Stripe for payments (as an independent controller; see above); and adMarketplace\n    for some ads (search terms only; see Advertising).'\ndpa:\n  available: true\n  url: null\n  text: Search queries sent through the API. We process these on behalf of our customer, as their processor, under\n    our Data Processing Agreement .\ndeletion:\n  route: Contact privacy@mojeek.com to request deletion\n  text: To use any of these rights, contact us at privacy@mojeek.com.\nrights:\n- right: access\n  text: access the personal data we hold about you\n- right: correction or deletion\n  text: have it corrected or deleted\n- right: objection or restriction\n  text: object to or restrict its use\n- right: portability\n  text: receive a copy in a portable form\n- right: complain\n  text: You also have the right to complain to the Information Commissioner's Office .\nsale_or_sharing:\n  stance: prohibited\n  text: we never sell\
  \ or distribute this data to any third party.\n"
source_yaml_url: https://artifacts.apis.io/mojeek/privacy/mojeek-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Mojeek's own page on 2026-11-10.
synthetic: false
tags:
- Search
- Privacy
- Open Source
- Community
---
