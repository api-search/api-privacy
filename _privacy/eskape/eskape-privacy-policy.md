---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: company name, country and registration or VAT number, betting licence number (if any)
  - category: contact
    text: email address, password (stored as a hash only)
  - category: device
    text: the time and IP address of registration and the country of that address
  - category: behavioral
    text: the requests made with the key (counts per day and endpoint; where enabled, per hour, status and competition)
  - category: professional
    text: name, role, employer, business email and phone number, LinkedIn profile, country
  deletion:
    route: email request to management@eskape.pro or deleting registration
    text: Deleting your registration ends the Free Plan
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the Free Plan
    text: Registration, the key, the quota, competitions, sign-in and the emails are necessary to perform our agreement with the Subscriber
  - purpose: security and fairness
    text: Limits on failed password attempts, on registrations and on requests from a single IP address
  - purpose: checking active businesses
    text: the checks of the company at registration serve our legitimate interest in providing the Service only to active businesses
  - purpose: business contacts
    text: We contact people whose role at a betting operator, a platform or a data provider is relevant to the Service
  residency:
  - region: European Union
    text: The Service runs on servers in the European Union (currently an OVHcloud data centre in Gravelines, France)
  retention:
  - period: the term of the Free Plan plus five years
    scope: registration and plan records
    text: the term of the Free Plan plus five years (the Accountancy Act), then deleted
  - period: 30 days
    scope: unconfirmed registrations
    text: A registration whose confirmation link was never opened 30 days, then deleted
  - period: 92 days
    scope: detailed statistics
    text: Detailed statistics (hour, status, competition, fixture) 92 days, then deleted automatically
  - period: no more than 60 minutes
    scope: odds submitted
    text: Odds you submit for a fixture in memory only, no more than 60 minutes, never written to disk
  - period: null
    scope: business contacts
    text: Otherwise we delete your data no later than 12 months after the last contact.
  rights:
  - right: access
    text: you have the right to access your data
  - right: correction or erasure
    text: to have it corrected or erased
  - right: restriction
    text: to restrict its processing
  - right: portability
    text: to receive a copy of the data you provided in a machine-readable format
  - right: objection
    text: you may object to processing based on our legitimate interest
  role:
    text: who is the controller of your personal data
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data or use subscriber data for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: the European Commission has recognised Canada as providing an adequate level of protection for organisations subject to PIPEDA
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ESKape Sportsbook Feed
provenance_date: '2026-11-09'
provider_name: ESKape Sportsbook Feed
provider_slug: eskape
slug: eskape-privacy-policy
source_date: '2026-11-09'
source_filename: eskape-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eskape.pro/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ESKape Sportsbook Feed\naid: eskape\nurl: https://eskape.pro/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: who is the controller of your personal data\ndata_categories:\n- category: identifying\n  text: company name, country and registration or VAT number, betting licence number (if any)\n- category: contact\n  text: email address, password (stored as a hash only)\n- category: device\n  text: the time and IP address of registration and the country of that address\n- category: behavioral\n  text: the requests made with the key (counts per day and endpoint; where enabled, per hour,\
  \ status and competition)\n- category: professional\n  text: name, role, employer, business email and phone number, LinkedIn profile, country\npurposes:\n- purpose: operate the Free Plan\n  text: Registration, the key, the quota, competitions, sign-in and the emails are necessary to perform our agreement\n    with the Subscriber\n- purpose: security and fairness\n  text: Limits on failed password attempts, on registrations and on requests from a single IP address\n- purpose: checking active businesses\n  text: the checks of the company at registration serve our legitimate interest in providing the Service only to\n    active businesses\n- purpose: business contacts\n  text: We contact people whose role at a betting operator, a platform or a data provider is relevant to the Service\nretention:\n- scope: registration and plan records\n  period: the term of the Free Plan plus five years\n  text: the term of the Free Plan plus five years (the Accountancy Act), then deleted\n- scope: unconfirmed\
  \ registrations\n  period: 30 days\n  text: A registration whose confirmation link was never opened 30 days, then deleted\n- scope: detailed statistics\n  period: 92 days\n  text: Detailed statistics (hour, status, competition, fixture) 92 days, then deleted automatically\n- scope: odds submitted\n  period: no more than 60 minutes\n  text: Odds you submit for a fixture in memory only, no more than 60 minutes, never written to disk\n- scope: business contacts\n  period: null\n  text: Otherwise we delete your data no later than 12 months after the last contact.\nresidency:\n- region: European Union\n  text: The Service runs on servers in the European Union (currently an OVHcloud data centre in Gravelines, France)\ntransfers:\n- mechanism: adequacy\n  text: the European Commission has recognised Canada as providing an adequate level of protection for organisations\n    subject to PIPEDA\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: email request to management@eskape.pro or deleting registration\n  text: Deleting your registration ends the Free Plan\nrights:\n- right: access\n  text: you have the right to access your data\n- right: correction or erasure\n  text: to have it corrected or erased\n- right: restriction\n  text: to restrict its processing\n- right: portability\n  text: to receive a copy of the data you provided in a machine-readable format\n- right: objection\n  text: you may object to processing based on our legitimate interest\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data or use subscriber data for advertising.\n"
source_yaml_url: https://artifacts.apis.io/eskape/privacy/eskape-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ESKape Sportsbook Feed's own page on 2026-11-09.
synthetic: false
tags:
- Sportsbook
- Odds API
- B2B
- Football
- Betting
---
