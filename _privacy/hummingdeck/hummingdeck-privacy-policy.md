---
api_specs:
- filename: hummingdeck-companies-api-openapi.yml
  format: yaml
  label: HummingDeck Companies API
  slug: hummingdeck-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-companies-api-openapi.yml
- filename: hummingdeck-contacts-api-openapi.yml
  format: yaml
  label: HummingDeck Contacts API
  slug: hummingdeck-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-contacts-api-openapi.yml
- filename: hummingdeck-decisions-api-openapi.yml
  format: yaml
  label: HummingDeck Decisions API
  slug: hummingdeck-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-decisions-api-openapi.yml
- filename: hummingdeck-decks-api-openapi.yml
  format: yaml
  label: HummingDeck Decks API
  slug: hummingdeck-decks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-decks-api-openapi.yml
- filename: hummingdeck-emails-api-openapi.yml
  format: yaml
  label: HummingDeck Emails API
  slug: hummingdeck-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-emails-api-openapi.yml
- filename: hummingdeck-hooks-api-openapi.yml
  format: yaml
  label: HummingDeck Hooks API
  slug: hummingdeck-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-hooks-api-openapi.yml
- filename: hummingdeck-me-api-openapi.yml
  format: yaml
  label: HummingDeck Me API
  slug: hummingdeck-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-me-api-openapi.yml
- filename: hummingdeck-room-labels-api-openapi.yml
  format: yaml
  label: HummingDeck Room Labels API
  slug: hummingdeck-room-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-room-labels-api-openapi.yml
- filename: hummingdeck-room-views-api-openapi.yml
  format: yaml
  label: HummingDeck Room Views API
  slug: hummingdeck-room-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-room-views-api-openapi.yml
- filename: hummingdeck-rooms-api-openapi.yml
  format: yaml
  label: HummingDeck Rooms API
  slug: hummingdeck-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-rooms-api-openapi.yml
- filename: hummingdeck-shares-api-openapi.yml
  format: yaml
  label: HummingDeck Shares API
  slug: hummingdeck-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-shares-api-openapi.yml
- filename: hummingdeck-views-api-openapi.yml
  format: yaml
  label: HummingDeck Views API
  slug: hummingdeck-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hummingdeck/openapi/hummingdeck-views-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — email address, name, and profile photo
  - category: contact
    text: CRM data — contact names, email addresses, and company information you add to organize your sharing activity
  - category: device
    text: Device and browser information — browser type, operating system, and device category
  - category: location
    text: Network information — IP address and approximate geographic location (city/country level, derived from IP)
  - category: behavioral
    text: Engagement data — which pages were viewed, time spent on each page, total viewing duration, and completion rate
  - category: communication
    text: Recipient email address — the extension reads the first email address from the To field of your compose window to create a personal tracked link.
  deletion:
    route: Delete within the app or email hello@hummingdeck.com
    text: To delete your entire account and all associated data, contact us at hello@hummingdeck.com .
  dpa:
    available: true
    text: Our processing of this data on the customer's behalf is governed by our Data Processing Agreement .
    url: null
  purposes:
  - purpose: Provide the service
    text: Provide the service — host your uploaded documents, generate share links, and deliver engagement analytics
  - purpose: Document engagement analytics
    text: Provide document engagement analytics — show registered users how recipients interact with their shared documents
  - purpose: Improve the product
    text: Improve the product — understand usage patterns to fix issues and develop new features
  - purpose: Security
    text: Ensure security — detect and prevent fraud, abuse, and unauthorized access
  residency:
  - region: United States
    text: We process data on Google Cloud infrastructure located in the United States.
  retention:
  - period: 30 days
    scope: Account data
    text: When you delete your account, we delete your personal data within 30 days, except where we are required to retain it by law.
  - period: 12 months
    scope: Document Viewer data
    text: 'Document Viewer data : retained in identifiable form to provide engagement analytics to the sender, then anonymized after 12 months.'
  rights:
  - right: Access
    text: 'Access : request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction : request correction of inaccurate data'
  - right: Deletion
    text: 'Deletion : request deletion of your personal data'
  - right: Portability
    text: 'Portability : request a machine-readable copy of your data'
  - right: Objection
    text: 'Objection : object to processing based on legitimate interest'
  - right: Restriction
    text: 'Restriction : request that we restrict processing of your data'
  - right: Withdraw consent
    text: 'Withdraw consent : where processing is based on consent, you can withdraw it at any time without affecting processing already carried out'
  role:
    text: As a processor — when we collect engagement data from Document Viewers and deliver analytics to the customer who shared the document, we act on that customer's instructions.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: The full, current list of sub-processors that process customer data on our behalf is published at hummingdeck.com/sub-processors .
    url: hummingdeck.com/sub-processors
  transfers:
  - mechanism: SCC
    text: When data is transferred outside of the European Economic Area, we rely on Standard Contractual Clauses or other approved transfer mechanisms.
  - mechanism: DPF
    text: LinkedIn states that it participates in the EU-US Data Privacy Framework and uses controller-to-controller Standard Contractual Clauses where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HummingDeck
provenance_date: '2026-11-09'
provider_name: HummingDeck
provider_slug: hummingdeck
slug: hummingdeck-privacy-policy
source_date: '2026-11-09'
source_filename: hummingdeck-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hummingdeck.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HummingDeck\naid: hummingdeck\nurl: https://hummingdeck.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As a processor — when we collect engagement data from Document Viewers and deliver analytics to the customer\n    who shared the document, we act on that customer's instructions.\ndata_categories:\n- category: identifying\n  text: Account information — email address, name, and profile photo\n- category: contact\n  text: CRM data — contact names, email addresses, and company information you add to organize your sharing activity\n- category: device\n  text: Device and browser information\
  \ — browser type, operating system, and device category\n- category: location\n  text: Network information — IP address and approximate geographic location (city/country level, derived from IP)\n- category: behavioral\n  text: Engagement data — which pages were viewed, time spent on each page, total viewing duration, and completion\n    rate\n- category: communication\n  text: Recipient email address — the extension reads the first email address from the To field of your compose\n    window to create a personal tracked link.\npurposes:\n- purpose: Provide the service\n  text: Provide the service — host your uploaded documents, generate share links, and deliver engagement analytics\n- purpose: Document engagement analytics\n  text: Provide document engagement analytics — show registered users how recipients interact with their shared\n    documents\n- purpose: Improve the product\n  text: Improve the product — understand usage patterns to fix issues and develop new features\n- purpose:\
  \ Security\n  text: Ensure security — detect and prevent fraud, abuse, and unauthorized access\nretention:\n- scope: Account data\n  period: 30 days\n  text: When you delete your account, we delete your personal data within 30 days, except where we are required\n    to retain it by law.\n- scope: Document Viewer data\n  period: 12 months\n  text: 'Document Viewer data : retained in identifiable form to provide engagement analytics to the sender, then\n    anonymized after 12 months.'\nresidency:\n- region: United States\n  text: We process data on Google Cloud infrastructure located in the United States.\ntransfers:\n- mechanism: SCC\n  text: When data is transferred outside of the European Economic Area, we rely on Standard Contractual Clauses\n    or other approved transfer mechanisms.\n- mechanism: DPF\n  text: LinkedIn states that it participates in the EU-US Data Privacy Framework and uses controller-to-controller\n    Standard Contractual Clauses where applicable.\nsubprocessors:\n\
  \  url: hummingdeck.com/sub-processors\n  text: The full, current list of sub-processors that process customer data on our behalf is published at hummingdeck.com/sub-processors\n    .\ndpa:\n  available: true\n  url: null\n  text: Our processing of this data on the customer's behalf is governed by our Data Processing Agreement .\ndeletion:\n  route: Delete within the app or email hello@hummingdeck.com\n  text: To delete your entire account and all associated data, contact us at hello@hummingdeck.com .\nrights:\n- right: Access\n  text: 'Access : request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction : request correction of inaccurate data'\n- right: Deletion\n  text: 'Deletion : request deletion of your personal data'\n- right: Portability\n  text: 'Portability : request a machine-readable copy of your data'\n- right: Objection\n  text: 'Objection : object to processing based on legitimate interest'\n- right: Restriction\n  text: 'Restriction :\
  \ request that we restrict processing of your data'\n- right: Withdraw consent\n  text: 'Withdraw consent : where processing is based on consent, you can withdraw it at any time without affecting\n    processing already carried out'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/hummingdeck/privacy/hummingdeck-privacy-policy.yml
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
summary_line: 27 quoted statements, read from HummingDeck's own page on 2026-11-09.
synthetic: false
tags:
- Document Sharing
- Engagement Analytics
- Digital Sales Rooms
- Data Rooms
- Client Portals
- Integration
- Secure Sharing
---
