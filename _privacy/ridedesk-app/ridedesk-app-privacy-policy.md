---
api_specs:
- filename: ridedesk-app-openapi-generated.yml
  format: yaml
  label: ridedesk-app API
  slug: ridedesk-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ridedesk-app/openapi/_ae-authored/ridedesk-app-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, work email address, password hash, organisation name, role and membership.'
  - category: financial
    text: 'Business and billing data: company legal name, address, VAT ID, registration details, subscription and invoice records.'
  - category: location
    text: 'What is sent: latitude and longitude, their accuracy, heading and speed, and the time of the reading.'
  - category: device
    text: 'Technical data: IP address, browser and device type, pages requested, and timestamps'
  deletion:
    route: Staff delete own login in app (menu → Delete account) or at https://ridedesk.app/delete-account; by email to privacy@ridenrank.com for Meta data
    text: Staff can delete their own RideDesk login in the app (menu → Delete account ) or on the web at https://ridedesk.app/delete-account .
  dpa:
    available: true
    text: We process it only on their documented instructions under a written data processing agreement.
    url: null
  purposes:
  - purpose: Provide and operate the RideDesk service
    text: To provide, operate and support the RideDesk service under our contract with the operator
  - purpose: Security and abuse prevention
    text: To keep the service secure, prevent abuse and fraud, and maintain proper business records
  - purpose: Legal obligations
    text: To meet our legal, tax and accounting obligations
  - purpose: Website statistics and advertising measurement
    text: Statistics and advertising measurement on our public website, ridedesk.app — only with your consent
  - purpose: Meta features
    text: We access Meta Platform Data only to provide those features to the operator who granted access.
  residency:
  - region: EU
    text: Our database, file storage and email sending are pinned to EU regions.
  retention:
  - period: for the life of the account
    scope: Operator account and organisation records
    text: 'Operator account and organisation records: for the life of the account, then deleted or anonymised.'
  - period: six years after the end of the relationship
    scope: Invoices and tax records
    text: 'Invoices and tax records: six years after the end of the relationship, as UK accounting and limitation rules require.'
  - period: deleted after 12 hours at the latest
    scope: Driver positions
    text: 'Driver positions: only the latest one, cleared when the shift ends and deleted after 12 hours at the latest.'
  - period: within 30 days at the latest
    scope: YouTube connection data
    text: delete the stored tokens and channel details of one whose access was revoked, within 30 days at the latest.
  rights:
  - right: access, rectify, erase, restrict, object
    text: to access, rectify, erase, restrict or object to it, to receive your data in a portable form, and to withdraw any consent you have given
  role:
    text: We are the controller for the data of the operators who sign up for RideDesk
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The current list is published at https://ridedesk.app/legal/subprocessors .
    url: https://ridedesk.app/legal/subprocessors
  transfers:
  - mechanism: DPF
    text: the EU-US Data Privacy Framework
  - mechanism: SCC
    text: the EU Standard Contractual Clauses
  - mechanism: other
    text: the UK International Data Transfer Agreement or Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ridedesk-app
provenance_date: '2026-11-10'
provider_name: ridedesk-app
provider_slug: ridedesk-app
slug: ridedesk-app-privacy-policy
source_date: '2026-11-10'
source_filename: ridedesk-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ridedesk.app/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ridedesk-app\naid: ridedesk-app\nurl: https://ridedesk.app/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for the data of the operators who sign up for RideDesk\ndata_categories:\n- category: identifying\n  text: 'Account data: name, work email address, password hash, organisation name, role and membership.'\n- category: financial\n  text: 'Business and billing data: company legal name, address, VAT ID, registration details, subscription and\n    invoice records.'\n- category: location\n  text: 'What is sent: latitude and longitude, their accuracy, heading and\
  \ speed, and the time of the reading.'\n- category: device\n  text: 'Technical data: IP address, browser and device type, pages requested, and timestamps'\npurposes:\n- purpose: Provide and operate the RideDesk service\n  text: To provide, operate and support the RideDesk service under our contract with the operator\n- purpose: Security and abuse prevention\n  text: To keep the service secure, prevent abuse and fraud, and maintain proper business records\n- purpose: Legal obligations\n  text: To meet our legal, tax and accounting obligations\n- purpose: Website statistics and advertising measurement\n  text: Statistics and advertising measurement on our public website, ridedesk.app — only with your consent\n- purpose: Meta features\n  text: We access Meta Platform Data only to provide those features to the operator who granted access.\nretention:\n- scope: Operator account and organisation records\n  period: for the life of the account\n  text: 'Operator account and organisation records:\
  \ for the life of the account, then deleted or anonymised.'\n- scope: Invoices and tax records\n  period: six years after the end of the relationship\n  text: 'Invoices and tax records: six years after the end of the relationship, as UK accounting and limitation\n    rules require.'\n- scope: Driver positions\n  period: deleted after 12 hours at the latest\n  text: 'Driver positions: only the latest one, cleared when the shift ends and deleted after 12 hours at the latest.'\n- scope: YouTube connection data\n  period: within 30 days at the latest\n  text: delete the stored tokens and channel details of one whose access was revoked, within 30 days at the latest.\nresidency:\n- region: EU\n  text: Our database, file storage and email sending are pinned to EU regions.\ntransfers:\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses\n- mechanism: other\n  text: the UK International Data Transfer Agreement or Addendum\nsubprocessors:\n\
  \  url: https://ridedesk.app/legal/subprocessors\n  text: The current list is published at https://ridedesk.app/legal/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: We process it only on their documented instructions under a written data processing agreement.\ndeletion:\n  route: Staff delete own login in app (menu → Delete account) or at https://ridedesk.app/delete-account; by email\n    to privacy@ridenrank.com for Meta data\n  text: Staff can delete their own RideDesk login in the app (menu → Delete account ) or on the web at https://ridedesk.app/delete-account\n    .\nrights:\n- right: access, rectify, erase, restrict, object\n  text: to access, rectify, erase, restrict or object to it, to receive your data in a portable form, and to withdraw\n    any consent you have given\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ridedesk-app/privacy/ridedesk-app-privacy-policy.yml
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
summary_line: 22 quoted statements, read from ridedesk-app's own page on 2026-11-10.
synthetic: false
tags:
- Transportation
- Dispatch
- Booking
- Software-as-a-Service
---
