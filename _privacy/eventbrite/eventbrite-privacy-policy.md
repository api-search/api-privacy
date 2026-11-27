---
api_specs:
- filename: eventbrite-attendees-api-openapi.yml
  format: yaml
  label: Eventbrite Attendees API
  slug: eventbrite-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-attendees-api-openapi.yml
- filename: eventbrite-categories-api-openapi.yml
  format: yaml
  label: Eventbrite Categories API
  slug: eventbrite-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-categories-api-openapi.yml
- filename: eventbrite-events-api-openapi.yml
  format: yaml
  label: Eventbrite Events API
  slug: eventbrite-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-events-api-openapi.yml
- filename: eventbrite-orders-api-openapi.yml
  format: yaml
  label: Eventbrite Orders API
  slug: eventbrite-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-orders-api-openapi.yml
- filename: eventbrite-organizations-api-openapi.yml
  format: yaml
  label: Eventbrite Organizations API
  slug: eventbrite-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-organizations-api-openapi.yml
- filename: eventbrite-ticket-classes-api-openapi.yml
  format: yaml
  label: Eventbrite Ticket Classes API
  slug: eventbrite-ticket-classes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-ticket-classes-api-openapi.yml
- filename: eventbrite-users-api-openapi.yml
  format: yaml
  label: Eventbrite Users API
  slug: eventbrite-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-users-api-openapi.yml
- filename: eventbrite-venues-api-openapi.yml
  format: yaml
  label: Eventbrite Venues API
  slug: eventbrite-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventbrite/openapi/eventbrite-venues-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: The Personal Data we may collect includes without limitation your name, address, email address
  - category: financial
    text: In some cases, we may collect your credit card information (e.g., your credit card number and expiration date, billing address, etc.)
  - category: location
    text: your provided location with other Eventbrite users
  - category: behavioral
    text: This may include information about your browsing behavior, page visits, clicks and cursor movements and searches on our sites.
  - category: device
    text: a unique identifier associated with your access device and/or browser (including, for example, your Internet Protocol (IP) address)
  - category: demographic
    text: We may derive or infer additional Personal Data about you, including demographic characteristics such as age range, gender, and parental status
  - category: communication
    text: If you opt in to marketing text messages from a particular Organizer or otherwise provide your phone number during event registration, we may collect your telephone number
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: You can find Eventbrite's pre-signed Standard Contractual Clauses and additional information in the Organizer Data Processing Agreement (DPA).
    url: null
  purposes:
  - purpose: Respond to inquiries and provide services
    text: we will use the Personal Data you provide to answer your question or resolve your problem
  - purpose: Internal business purposes
    text: We may use your Personal Data for internal business purposes, including without limitation, to help us improve the content and functionality of the Services
  - purpose: Marketing and advertising
    text: We may use your Personal Data for our marketing and advertising purposes, including (without limitation) by email, SMS marketing, display media, and targeting other devices
  - purpose: Interest-based recommendations and targeting
    text: We sometimes make inferences about the type of events or activities you may be interested in based on information you provide in your Eventbrite profile
  residency:
  - region: United States
    text: you are sending information (including Personal Data) to the United States where our servers are located.
  retention:
  - period: ninety (90) days
    scope: Account data after account closure request
    text: we will typically retain your Personal Data for a period of ninety (90) days after you have requested that your account is closed
  - period: seven (7) years
    scope: Inactive accounts
    text: or if it's been inactive for seven (7) years
  - period: null
    scope: Sales customers and prospects
    text: For sales customers and prospects, we retain your data as long as we maintain a relationship with you and for a limited period of thereafter as necessary to meet business and legal requirements.
  rights:
  - right: Access
    text: the right to request a copy of the Personal Data
  - right: Rectify, restrict or delete
    text: request that we rectify, restrict or delete your Personal Data
  - right: Object to profiling
    text: object to profiling and unsubscribe from marketing communications
  - right: Lodge a complaint
    text: You also have the right to lodge a complaint with the competent national data protection authority
  role:
    text: Eventbrite may act as either a data controller or a data processor in respect of your Personal Data, depending on the circumstances.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We are not in the business of selling your Personal Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: This includes the use of Standard Contractual Clauses issued pursuant to Commission Implementing Decision (EU) 2021/914
  - mechanism: DPF
    text: Eventbrite has also certified its compliance with the EU-US Data Privacy Framework, the Swiss-US Data Privacy Framework, and the UK Extension to the EU-US Data Privacy Framework
  - mechanism: other
    text: the UK International Data Transfer Addendum (IDTA)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Eventbrite
provenance_date: '2026-11-09'
provider_name: Eventbrite
provider_slug: eventbrite
slug: eventbrite-privacy-policy
source_date: '2026-11-09'
source_filename: eventbrite-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.eventbrite.com/help/en-us/articles/460838/eventbrite-privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Eventbrite\naid: eventbrite\nurl: https://www.eventbrite.com/help/en-us/articles/460838/eventbrite-privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Eventbrite may act as either a data controller or a data processor in respect of your Personal Data, depending\n    on the circumstances.\ndata_categories:\n- category: contact\n  text: The Personal Data we may collect includes without limitation your name, address, email address\n- category: financial\n  text: In some cases, we may collect your credit card information (e.g., your credit card number and expiration\n    date, billing address,\
  \ etc.)\n- category: location\n  text: your provided location with other Eventbrite users\n- category: behavioral\n  text: This may include information about your browsing behavior, page visits, clicks and cursor movements and\n    searches on our sites.\n- category: device\n  text: a unique identifier associated with your access device and/or browser (including, for example, your Internet\n    Protocol (IP) address)\n- category: demographic\n  text: We may derive or infer additional Personal Data about you, including demographic characteristics such as\n    age range, gender, and parental status\n- category: communication\n  text: If you opt in to marketing text messages from a particular Organizer or otherwise provide your phone number\n    during event registration, we may collect your telephone number\npurposes:\n- purpose: Respond to inquiries and provide services\n  text: we will use the Personal Data you provide to answer your question or resolve your problem\n- purpose: Internal\
  \ business purposes\n  text: We may use your Personal Data for internal business purposes, including without limitation, to help us improve\n    the content and functionality of the Services\n- purpose: Marketing and advertising\n  text: We may use your Personal Data for our marketing and advertising purposes, including (without limitation)\n    by email, SMS marketing, display media, and targeting other devices\n- purpose: Interest-based recommendations and targeting\n  text: We sometimes make inferences about the type of events or activities you may be interested in based on information\n    you provide in your Eventbrite profile\nretention:\n- scope: Account data after account closure request\n  period: ninety (90) days\n  text: we will typically retain your Personal Data for a period of ninety (90) days after you have requested that\n    your account is closed\n- scope: Inactive accounts\n  period: seven (7) years\n  text: or if it's been inactive for seven (7) years\n- scope: Sales\
  \ customers and prospects\n  period: null\n  text: For sales customers and prospects, we retain your data as long as we maintain a relationship with you and\n    for a limited period of thereafter as necessary to meet business and legal requirements.\nresidency:\n- region: United States\n  text: you are sending information (including Personal Data) to the United States where our servers are located.\ntransfers:\n- mechanism: SCC\n  text: This includes the use of Standard Contractual Clauses issued pursuant to Commission Implementing Decision\n    (EU) 2021/914\n- mechanism: DPF\n  text: Eventbrite has also certified its compliance with the EU-US Data Privacy Framework, the Swiss-US Data Privacy\n    Framework, and the UK Extension to the EU-US Data Privacy Framework\n- mechanism: other\n  text: the UK International Data Transfer Addendum (IDTA)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: You can find Eventbrite's pre-signed Standard Contractual\
  \ Clauses and additional information in the Organizer\n    Data Processing Agreement (DPA).\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: the right to request a copy of the Personal Data\n- right: Rectify, restrict or delete\n  text: request that we rectify, restrict or delete your Personal Data\n- right: Object to profiling\n  text: object to profiling and unsubscribe from marketing communications\n- right: Lodge a complaint\n  text: You also have the right to lodge a complaint with the competent national data protection authority\nsale_or_sharing:\n  stance: conditional\n  text: We are not in the business of selling your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/eventbrite/privacy/eventbrite-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Eventbrite's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Event Technology
- Ticketing
- Marketplace
---
