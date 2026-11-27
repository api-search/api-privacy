---
api_specs:
- filename: oag-alerts-api-openapi.yml
  format: yaml
  label: OAG Alerts API
  slug: oag-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-alerts-api-openapi.yml
- filename: oag-flight-connections-api-openapi.yml
  format: yaml
  label: OAG Flight Connections API
  slug: oag-flight-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-flight-connections-api-openapi.yml
- filename: oag-flight-info-alerts-api-openapi.yml
  format: yaml
  label: OAG Flight Info Alerts API
  slug: oag-flight-info-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-flight-info-alerts-api-openapi.yml
- filename: oag-flight-instances-api-openapi.yml
  format: yaml
  label: OAG Flight Instances API
  slug: oag-flight-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-flight-instances-api-openapi.yml
- filename: oag-flights-api-openapi.yml
  format: yaml
  label: OAG Flights API
  slug: oag-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-flights-api-openapi.yml
- filename: oag-locations-api-openapi.yml
  format: yaml
  label: OAG Locations API
  slug: oag-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-locations-api-openapi.yml
- filename: oag-oag-api-api-openapi.yml
  format: yaml
  label: OAG OAG API
  slug: oag-oag-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-oag-api-api-openapi.yml
- filename: oag-profile-api-openapi.yml
  format: yaml
  label: OAG Profile API
  slug: oag-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-profile-api-openapi.yml
- filename: oag-status-api-openapi.yml
  format: yaml
  label: OAG Status API
  slug: oag-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oag/openapi/oag-status-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, username, user ID
  - category: contact
    text: Email, phone, company, job title
  - category: financial
    text: Account details, data products/services purchased, payment method type, billing address, transaction history
  - category: device
    text: IP address, device, browser, login data, session data, time zone, general location, cookies / tracking identifiers
  - category: behavioral
    text: How you use our websites, data products, applications, feature usage, clicks, navigation paths
  - category: communication
    text: Emails, messages, call recordings, transcripts, meeting metadata
  deletion:
    route: Privacy rights request form or privacy@oag.com
    text: To submit a data rights request, please use our online privacy rights form
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Legitimate interests
    text: Legitimate interests – to improve and develop our data products, analyse usage, personalise your experience, conduct research, communicate with you, maintain security and network and platform integrity.
  - purpose: Consent
    text: Consent – for analytics, marketing, improving customer interactions, and user surveys.
  retention:
  - period: up to 6 years after the end of our engagement with your organisation (plus until 30 January of the following year)
    scope: Core account and subscription data
    text: Core account and subscription data is retained for up to 6 years after the end of our engagement with your organisation (plus until 30 January of the following year), unless a longer period is required by applicable law.
  - period: 2 years of inactivity
    scope: Direct marketing
    text: Deleted after 2 years of inactivity or on consent withdrawal (core opt-out details retained)
  - period: 1 year after the event if no further activity occurs
    scope: Events and webinars
    text: Deleted 1 year after the event if no further activity occurs
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you
  - right: Erasure
    text: Ask us to delete your personal data in certain circumstances
  - right: Objection
    text: Object to processing based on legitimate interests or for direct marketing
  - right: Portability
    text: Receive your data in a structured, machine-readable format and transfer it to another provider (where applicable)
  role:
    text: OAG Aviation Worldwide Limited is the data controller for personal data collected through our websites.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: EU Standard Contractual Clauses (SCCs) or the UK International Data Transfer Agreement (IDTA)
  - mechanism: adequacy
    text: we rely on applicable adequacy decisions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OAG
provenance_date: '2026-11-10'
provider_name: OAG
provider_slug: oag
slug: oag-privacy-policy
source_date: '2026-11-10'
source_filename: oag-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.oag.com/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OAG\naid: oag\nurl: https://www.oag.com/privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: OAG Aviation Worldwide Limited is the data controller for personal data collected through our websites.\ndata_categories:\n- category: identifying\n  text: Name, username, user ID\n- category: contact\n  text: Email, phone, company, job title\n- category: financial\n  text: Account details, data products/services purchased, payment method type, billing address, transaction history\n- category: device\n  text: IP address, device, browser, login data, session data, time zone, general location,\
  \ cookies / tracking identifiers\n- category: behavioral\n  text: How you use our websites, data products, applications, feature usage, clicks, navigation paths\n- category: communication\n  text: Emails, messages, call recordings, transcripts, meeting metadata\npurposes:\n- purpose: Legitimate interests\n  text: Legitimate interests – to improve and develop our data products, analyse usage, personalise your experience,\n    conduct research, communicate with you, maintain security and network and platform integrity.\n- purpose: Consent\n  text: Consent – for analytics, marketing, improving customer interactions, and user surveys.\nretention:\n- scope: Core account and subscription data\n  period: up to 6 years after the end of our engagement with your organisation (plus until 30 January of the following\n    year)\n  text: Core account and subscription data is retained for up to 6 years after the end of our engagement with your\n    organisation (plus until 30 January of the following\
  \ year), unless a longer period is required by applicable\n    law.\n- scope: Direct marketing\n  period: 2 years of inactivity\n  text: Deleted after 2 years of inactivity or on consent withdrawal (core opt-out details retained)\n- scope: Events and webinars\n  period: 1 year after the event if no further activity occurs\n  text: Deleted 1 year after the event if no further activity occurs\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: EU Standard Contractual Clauses (SCCs) or the UK International Data Transfer Agreement (IDTA)\n- mechanism: adequacy\n  text: we rely on applicable adequacy decisions\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy rights request form or privacy@oag.com\n  text: To submit a data rights request, please use our online privacy rights form\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you\n- right: Erasure\n  text: Ask us to delete your\
  \ personal data in certain circumstances\n- right: Objection\n  text: Object to processing based on legitimate interests or for direct marketing\n- right: Portability\n  text: Receive your data in a structured, machine-readable format and transfer it to another provider (where applicable)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oag/privacy/oag-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 19 quoted statements, read from OAG's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Aviation
- Data
- Analytics
- Travel
---
