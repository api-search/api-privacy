---
api_specs:
- filename: einride-bookingservice-api-openapi.yml
  format: yaml
  label: Einride BookingService API
  slug: einride-bookingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/einride/openapi/einride-bookingservice-api-openapi.yml
- filename: einride-shipmentservice-api-openapi.yml
  format: yaml
  label: Einride ShipmentService API
  slug: einride-shipmentservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/einride/openapi/einride-shipmentservice-api-openapi.yml
- filename: einride-authentication-service-api-openapi.yml
  format: yaml
  label: Einride Authentication Service API
  slug: einride-authentication-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/einride/openapi/einride-authentication-service-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, job title, employer, work e-mail address, work phone number and what we have discussed with you.
  - category: location
    text: Device information, Online identifier, Location data, IP address, User activity
  - category: demographic
    text: Name, Date of birth, Employer, Email address
  - category: biometric
    text: 'From cameras at offices that have them: images of you; not every office has cameras.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website operation and analytics
    text: Run and improve the website, understand how it is used, and measure and target marketing campaigns, using cookies and similar technologies that you accept in the cookie banner.
  - purpose: Marketing to business contacts
    text: Promote products and communicate business activities through various marketing channels.
  - purpose: Office security
    text: Track and manage visitor entries for security purposes.
  - purpose: Camera surveillance
    text: Utilize camera surveillance for office security and personal safety.
  retention:
  - period: 1 year
    scope: Website analytics data
    text: Deleted 1 year after your visit to the website
  - period: 2 years
    scope: Marketing contact data
    text: Deleted 2 years after the last communication was sent by us
  - period: 60 days
    scope: Visitor registration
    text: Deleted 60 days after your visit
  - period: 30 days
    scope: Camera footage
    text: Deleted 30 days after recording
  - period: 10 years
    scope: Contract records
    text: Deleted 10 years after the contractual relationship has ended
  rights:
  - right: Access
    text: Access to your personal data, and a copy of it.
  - right: Correction
    text: Correction of data that is wrong or incomplete.
  - right: Erasure or restriction
    text: Erasure, or restriction of our use, in the cases the law allows.
  - right: Objection
    text: Objection to processing based on our legitimate interest.
  - right: Portability
    text: Data portability for data you gave us and that we process by contract or consent.
  - right: Withdraw consent
    text: Withdrawal of consent at any time where we rely on it, without affecting what happened before.
  - right: Object to direct marketing
    text: Objection to direct marketing at any time (see chapter B).
  role:
    text: Einride AB, reg. no. 559074-8926, Stadsgården 6, Stockholm, operates einride.tech and is the controller for the website and cookies.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Service providers that work on our behalf (processors) are not named here.
    url: null
  transfers:
  - mechanism: SCC
    text: Providers outside the EU/EEA are used only with standard contractual clauses or when they are certified under the EU–US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Einride
provenance_date: '2026-11-09'
provider_name: Einride
provider_slug: einride
slug: einride-privacy-policy
source_date: '2026-11-09'
source_filename: einride-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.einride.tech/privacy/general-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Einride\naid: einride\nurl: https://www.einride.tech/privacy/general-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Einride AB, reg. no. 559074-8926, Stadsgården 6, Stockholm, operates einride.tech and is the controller\n    for the website and cookies.\ndata_categories:\n- category: identifying\n  text: Name, job title, employer, work e-mail address, work phone number and what we have discussed with you.\n- category: location\n  text: Device information, Online identifier, Location data, IP address, User activity\n- category: demographic\n  text: Name, Date of birth, Employer, Email\
  \ address\n- category: biometric\n  text: 'From cameras at offices that have them: images of you; not every office has cameras.'\npurposes:\n- purpose: Website operation and analytics\n  text: Run and improve the website, understand how it is used, and measure and target marketing campaigns, using\n    cookies and similar technologies that you accept in the cookie banner.\n- purpose: Marketing to business contacts\n  text: Promote products and communicate business activities through various marketing channels.\n- purpose: Office security\n  text: Track and manage visitor entries for security purposes.\n- purpose: Camera surveillance\n  text: Utilize camera surveillance for office security and personal safety.\nretention:\n- scope: Website analytics data\n  period: 1 year\n  text: Deleted 1 year after your visit to the website\n- scope: Marketing contact data\n  period: 2 years\n  text: Deleted 2 years after the last communication was sent by us\n- scope: Visitor registration\n  period:\
  \ 60 days\n  text: Deleted 60 days after your visit\n- scope: Camera footage\n  period: 30 days\n  text: Deleted 30 days after recording\n- scope: Contract records\n  period: 10 years\n  text: Deleted 10 years after the contractual relationship has ended\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Providers outside the EU/EEA are used only with standard contractual clauses or when they are certified\n    under the EU–US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: Service providers that work on our behalf (processors) are not named here.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Access to your personal data, and a copy of it.\n- right: Correction\n  text: Correction of data that is wrong or incomplete.\n- right: Erasure or restriction\n  text: Erasure, or restriction of our use, in the cases the law allows.\n- right: Objection\n  text: Objection to processing based on our legitimate\
  \ interest.\n- right: Portability\n  text: Data portability for data you gave us and that we process by contract or consent.\n- right: Withdraw consent\n  text: Withdrawal of consent at any time where we rely on it, without affecting what happened before.\n- right: Object to direct marketing\n  text: Objection to direct marketing at any time (see chapter B).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/einride/privacy/einride-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- rights
summary_line: 23 quoted statements, read from Einride's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sustainable Transport
- Freight
- Logistics
- Autonomous Vehicles
- Electric Vehicles
- Shipping
- gRPC
- Sweden
---
