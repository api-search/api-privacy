---
api_specs:
- filename: riverside-exports-api-openapi.yml
  format: yaml
  label: Riverside Exports API
  slug: riverside-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riverside/openapi/riverside-exports-api-openapi.yml
- filename: riverside-productions-api-openapi.yml
  format: yaml
  label: Riverside Productions API
  slug: riverside-productions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riverside/openapi/riverside-productions-api-openapi.yml
- filename: riverside-recordings-api-openapi.yml
  format: yaml
  label: Riverside Recordings API
  slug: riverside-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riverside/openapi/riverside-recordings-api-openapi.yml
- filename: riverside-webinars-api-openapi.yml
  format: yaml
  label: Riverside Webinars API
  slug: riverside-webinars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riverside/openapi/riverside-webinars-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as names, email addresses, phone numbers, login credentials, profile picture, titles, and workplace
  - category: financial
    text: such as your billing address and last four digits of credit card
  - category: location
    text: approximate location based on such IP addresses
  - category: device
    text: device data (like type, OS, device id, browser version, locale and language settings used)
  - category: behavioral
    text: activity logs, session recordings, and the cookies and pixels installed or utilized on their device
  - category: communication
    text: recordings and transcripts of our calls, chats, WhatsApp conversations and emails
  - category: biometric
    text: which is used to create a representation of your unique vocal characteristics and facial geometry
  deletion:
    route: email request to the privacy contact
    text: 'Please contact us by e-mail at: [email protected] if you wish to exercise your privacy rights under any applicable law'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate the Services
    text: To facilitate, operate, enhance, optimize, and provide our Services, including to administer accounts and process transactions
  - purpose: train AI and ML models
    text: to train our AI and ML models and to test, monitor and develop new features based on such data
  - purpose: marketing and advertising
    text: To facilitate and optimize our marketing campaigns, advertising and sales operations, including managing and delivering advertisements for our Services on third-party websites and applications
  retention:
  - period: as long as we have an ongoing legitimate business need
    scope: User and Prospect Data
    text: We retain User and Prospect Data for as long as we have an ongoing legitimate business need to do so
  - period: as long as necessary to complete the requested feature
    scope: Voice Data and Face Data
    text: Riverside retains the Voice Data and Face Data only for as long as necessary to complete the requested feature, after which it is immediately and permanently destroyed.
  rights:
  - right: access
    text: Receive confirmation as to whether or not personal information concerning you is being processed, and access your stored personal information
  - right: rectification
    text: Request rectification of your personal information that is in our control
  - right: erasure
    text: Request erasure of your personal information
  - right: objection
    text: Object to the processing of personal information by us
  - right: portability
    text: Receive a copy of personal information you directly volunteer to us in a structured, commonly used and machine-readable format
  - right: complaint
    text: Lodge a complaint with a supervisory authority
  role:
    text: Riverside is the “data controller” of User and Prospect Data.
    value: both
  sale_or_sharing:
    stance: conditional
    text: You can manage your cookie preferences and opt out of the sale or sharing (for targeted advertising) of your data via our cookie banner.
  subprocessors:
    text: A list of our sub-processors is available here
    url: null
  transfers:
  - mechanism: DPF
    text: Riverside complies with the EU-US Data Privacy Framework (EU-US DPF), the UK Extension to the EU-US DPF, and the Swiss-US Data Privacy Framework (DPF)
  - mechanism: adequacy
    text: We transfer data from the EEA, the UK and Switzerland to Israel on this basis.
  - mechanism: SCC
    text: we and the relevant data exporters and importers have entered into Standard Contractual Clauses as approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Riverside
provenance_date: '2026-11-10'
provider_name: Riverside
provider_slug: riverside
slug: riverside-privacy-policy
source_date: '2026-11-10'
source_filename: riverside-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://riverside.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Riverside\naid: riverside\nurl: https://riverside.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Riverside is the “data controller” of User and Prospect Data.\ndata_categories:\n- category: identifying\n  text: such as names, email addresses, phone numbers, login credentials, profile picture, titles, and workplace\n- category: financial\n  text: such as your billing address and last four digits of credit card\n- category: location\n  text: approximate location based on such IP addresses\n- category: device\n  text: device data (like type, OS, device id, browser\
  \ version, locale and language settings used)\n- category: behavioral\n  text: activity logs, session recordings, and the cookies and pixels installed or utilized on their device\n- category: communication\n  text: recordings and transcripts of our calls, chats, WhatsApp conversations and emails\n- category: biometric\n  text: which is used to create a representation of your unique vocal characteristics and facial geometry\npurposes:\n- purpose: provide and operate the Services\n  text: To facilitate, operate, enhance, optimize, and provide our Services, including to administer accounts and\n    process transactions\n- purpose: train AI and ML models\n  text: to train our AI and ML models and to test, monitor and develop new features based on such data\n- purpose: marketing and advertising\n  text: To facilitate and optimize our marketing campaigns, advertising and sales operations, including managing\n    and delivering advertisements for our Services on third-party websites and applications\n\
  retention:\n- scope: User and Prospect Data\n  period: as long as we have an ongoing legitimate business need\n  text: We retain User and Prospect Data for as long as we have an ongoing legitimate business need to do so\n- scope: Voice Data and Face Data\n  period: as long as necessary to complete the requested feature\n  text: Riverside retains the Voice Data and Face Data only for as long as necessary to complete the requested feature,\n    after which it is immediately and permanently destroyed.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Riverside complies with the EU-US Data Privacy Framework (EU-US DPF), the UK Extension to the EU-US DPF,\n    and the Swiss-US Data Privacy Framework (DPF)\n- mechanism: adequacy\n  text: We transfer data from the EEA, the UK and Switzerland to Israel on this basis.\n- mechanism: SCC\n  text: we and the relevant data exporters and importers have entered into Standard Contractual Clauses as approved\n    by the European Commission\nsubprocessors:\n\
  \  url: null\n  text: A list of our sub-processors is available here\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to the privacy contact\n  text: 'Please contact us by e-mail at: [email protected] if you wish to exercise your privacy rights under any\n    applicable law'\nrights:\n- right: access\n  text: Receive confirmation as to whether or not personal information concerning you is being processed, and access\n    your stored personal information\n- right: rectification\n  text: Request rectification of your personal information that is in our control\n- right: erasure\n  text: Request erasure of your personal information\n- right: objection\n  text: Object to the processing of personal information by us\n- right: portability\n  text: Receive a copy of personal information you directly volunteer to us in a structured, commonly used and machine-readable\n    format\n- right: complaint\n  text: Lodge a complaint with a supervisory authority\n\
  sale_or_sharing:\n  stance: conditional\n  text: You can manage your cookie preferences and opt out of the sale or sharing (for targeted advertising) of\n    your data via our cookie banner.\n"
source_yaml_url: https://artifacts.apis.io/riverside/privacy/riverside-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Riverside's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Video Recording
- Media
- Content Creation
- Audio
---
