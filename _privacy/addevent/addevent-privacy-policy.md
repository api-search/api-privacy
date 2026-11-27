---
api_specs:
- filename: addevent-calendar-subscribers-api-openapi.yml
  format: yaml
  label: AddEvent Calendar subscribers API
  slug: addevent-calendar-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-calendar-subscribers-api-openapi.yml
- filename: addevent-calendars-api-openapi.yml
  format: yaml
  label: AddEvent Calendars API
  slug: addevent-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-calendars-api-openapi.yml
- filename: addevent-events-api-openapi.yml
  format: yaml
  label: AddEvent Events API
  slug: addevent-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-events-api-openapi.yml
- filename: addevent-rsvp-attendees-api-openapi.yml
  format: yaml
  label: AddEvent RSVP attendees API
  slug: addevent-rsvp-attendees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-rsvp-attendees-api-openapi.yml
- filename: addevent-templates-api-openapi.yml
  format: yaml
  label: AddEvent Templates API
  slug: addevent-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-templates-api-openapi.yml
- filename: addevent-timezones-api-openapi.yml
  format: yaml
  label: AddEvent Timezones API
  slug: addevent-timezones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/addevent/openapi/addevent-timezones-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, business information, address, email address and other information that enables Users to be personally identified
  - category: financial
    text: Stripe collects and processes your payment information (such as credit card number and billing details) on our behalf.
  - category: device
    text: a unique identifier related to the device/browser you use, statistics on your activities on the Services, information about how you ended up on the Services and data collected through Cookies, Pixel Tags and other similar technologies
  deletion:
    route: Account page or contacting us by email
    text: You can request access to some of your Personal Data being stored by us. You can also ask us to correct, update or delete any inaccurate Personal Data that we process about them.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: specific reason provided
    text: If you provide Personal Data for a certain purpose we may use it for that purpose.
  - purpose: internal business purposes
    text: We may use your Personal Data for internal business purposes, including without limitation, to help us improve the content and functionality of the Services.
  - purpose: marketing communications
    text: We may use your Personal Data to contact you in the future for marketing purposes
  residency:
  - region: Ireland
    text: Be aware that you are sending information (including Personal Data) to Ireland where our primary servers and data storage is located.
  retention:
  - period: 90 days
    scope: active or closed accounts
    text: If you have an account with us, we will typically retain your Personal Data for a period of 90 days after you have requested that your account be closed or if it has been inactive for 5 years.
  - period: 5 years
    scope: inactive accounts
    text: if it has been inactive for 5 years
  rights:
  - right: access
    text: the right to request a copy of the Personal Data
  - right: rectify, restrict or delete
    text: request that we rectify, restrict or delete your Personal Data
  - right: object to profiling
    text: object to profiling and unsubscribe from marketing communications
  role:
    text: AddEvent may act as either a data controller or a data processor in respect of your Personal Data, depending on the circumstances.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We are not in the business of selling your Personal Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Whenever we transfer Personal Data outside of the EEA, Switzerland or the UK, we take legally required steps to make sure that appropriate safeguards are in place to protect your Personal Data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AddEvent
provenance_date: '2026-11-09'
provider_name: AddEvent
provider_slug: addevent
slug: addevent-privacy-policy
source_date: '2026-11-09'
source_filename: addevent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.addevent.com/c/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AddEvent\naid: addevent\nurl: https://www.addevent.com/c/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: AddEvent may act as either a data controller or a data processor in respect of your Personal Data, depending\n    on the circumstances.\ndata_categories:\n- category: identifying\n  text: your name, business information, address, email address and other information that enables Users to be personally\n    identified\n- category: financial\n  text: Stripe collects and processes your payment information (such as credit card number and billing details)\n    on our behalf.\n- category:\
  \ device\n  text: a unique identifier related to the device/browser you use, statistics on your activities on the Services,\n    information about how you ended up on the Services and data collected through Cookies, Pixel Tags and other\n    similar technologies\npurposes:\n- purpose: specific reason provided\n  text: If you provide Personal Data for a certain purpose we may use it for that purpose.\n- purpose: internal business purposes\n  text: We may use your Personal Data for internal business purposes, including without limitation, to help us improve\n    the content and functionality of the Services.\n- purpose: marketing communications\n  text: We may use your Personal Data to contact you in the future for marketing purposes\nretention:\n- scope: active or closed accounts\n  period: 90 days\n  text: If you have an account with us, we will typically retain your Personal Data for a period of 90 days after\n    you have requested that your account be closed or if it has been inactive\
  \ for 5 years.\n- scope: inactive accounts\n  period: 5 years\n  text: if it has been inactive for 5 years\nresidency:\n- region: Ireland\n  text: Be aware that you are sending information (including Personal Data) to Ireland where our primary servers\n    and data storage is located.\ntransfers:\n- mechanism: other\n  text: Whenever we transfer Personal Data outside of the EEA, Switzerland or the UK, we take legally required steps\n    to make sure that appropriate safeguards are in place to protect your Personal Data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page or contacting us by email\n  text: You can request access to some of your Personal Data being stored by us. You can also ask us to correct,\n    update or delete any inaccurate Personal Data that we process about them.\nrights:\n- right: access\n  text: the right to request a copy of the Personal Data\n- right: rectify, restrict or delete\n  text:\
  \ request that we rectify, restrict or delete your Personal Data\n- right: object to profiling\n  text: object to profiling and unsubscribe from marketing communications\nsale_or_sharing:\n  stance: prohibited\n  text: We are not in the business of selling your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/addevent/privacy/addevent-privacy-policy.yml
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
summary_line: 16 quoted statements, read from AddEvent's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Integration
- Marketing
- Software-as-a-Service
- Event
---
