---
api_specs:
- filename: intelycare-check-in-check-out-api-openapi.yml
  format: yaml
  label: IntelyCare Check In / Check Out API
  slug: intelycare-check-in-check-out-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-check-in-check-out-api-openapi.yml
- filename: intelycare-shift-api-openapi.yml
  format: yaml
  label: IntelyCare Shift API
  slug: intelycare-shift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-shift-api-openapi.yml
- filename: intelycare-webhook-events-api-openapi.yml
  format: yaml
  label: IntelyCare Webhook Events API
  slug: intelycare-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-webhook-events-api-openapi.yml
- filename: intelycare-time-card-api-openapi.yml
  format: yaml
  label: IntelyCare Time Card API
  slug: intelycare-time-card-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelycare/openapi/intelycare-time-card-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information, such as your name, address, phone number, and email address.
  - category: identifying
    text: Account information , such as username, password, security questions that you select and the answers you provide
  - category: financial
    text: Payment and billing information , such as bank account, credit or debit card information, and billing address
  - category: professional
    text: Professional and employment-related information , such as your previous or current employer name, job title, job description, and job history.
  - category: device
    text: Device information , such as device type, operating system, unique device identifier, and internet protocol (IP) address.
  - category: location
    text: Precise geolocation data . If you are a healthcare provider, we collect your precise location through your device’s GPS feature
  - category: behavioral
    text: Other information regarding your interaction with the Services , such as browser type, log data, date and time stamps, clickstream data
  - category: health
    text: Personal information concerning an individual’s health*, such as health information submitted in connection with healthcare professional registration and credentialing
  deletion:
    route: email privacy@intelycare.com or call 1-844-683-5922
    text: To make a request described in this section, please email us at privacy@intelycare.com or call us at 1-844-683-5922 .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve the Services
    text: 'we may use this information to: provide and improve the Services, including by monitoring usage and trends'
  - purpose: marketing, advertising and analytics
    text: We disclose, and have disclosed in the preceding 12 months, the following categories of personal information for marketing, advertising, and analytics purposes
  - purpose: verify work hours
    text: We use this information to ensure that (i) healthcare providers arrive at their shifts at client facilities on time and stay for the entire time reported
  residency:
  - region: United States
    text: Please note that the Services are designed for users in the United States only and are not intended for users located outside the United States.
  retention:
  - period: null
    scope: personal information
    text: We retain your information for as long as is reasonably necessary for the purposes specified in this Privacy Notice.
  rights:
  - right: Access / Know
    text: You may have the right to request access to the personal information we hold about you
  - right: Deletion
    text: You may have the right to request that we delete personal information we hold about you.
  - right: Correction
    text: You may have the right to request that we correct inaccurate personal information we hold about you.
  - right: Portability
    text: You may have the right to receive a copy of the personal information we hold about you in a portable and, to the extent technically feasible, readily usable format.
  - right: Opt-out of sale or sharing / targeted advertising
    text: You may have a right to direct us not to sell your personal information, or share or process your personal information for targeted advertising.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: allowed
    text: We disclose, and have disclosed in the preceding 12 months, the following categories of personal information for marketing, advertising, and analytics purposes, in a manner that may be considered “selling” or “sharing”
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: the information we collect from you may be transferred to, stored, and processed in the United States or other countries outside your country of residence.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IntelyCare
provenance_date: '2026-11-09'
provider_name: IntelyCare
provider_slug: intelycare
slug: intelycare-privacy-policy
source_date: '2026-11-09'
source_filename: intelycare-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.intelycare.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IntelyCare\naid: intelycare\nurl: https://www.intelycare.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact information, such as your name, address, phone number, and email address.\n- category: identifying\n  text: Account information , such as username, password, security questions that you select and the answers you\n    provide\n- category: financial\n  text: Payment and billing information , such as bank account, credit or debit card information, and billing address\n- category: professional\n  text: Professional\
  \ and employment-related information , such as your previous or current employer name, job title,\n    job description, and job history.\n- category: device\n  text: Device information , such as device type, operating system, unique device identifier, and internet protocol\n    (IP) address.\n- category: location\n  text: Precise geolocation data . If you are a healthcare provider, we collect your precise location through your\n    device’s GPS feature\n- category: behavioral\n  text: Other information regarding your interaction with the Services , such as browser type, log data, date and\n    time stamps, clickstream data\n- category: health\n  text: Personal information concerning an individual’s health*, such as health information submitted in connection\n    with healthcare professional registration and credentialing\npurposes:\n- purpose: provide and improve the Services\n  text: 'we may use this information to: provide and improve the Services, including by monitoring usage and trends'\n\
  - purpose: marketing, advertising and analytics\n  text: We disclose, and have disclosed in the preceding 12 months, the following categories of personal information\n    for marketing, advertising, and analytics purposes\n- purpose: verify work hours\n  text: We use this information to ensure that (i) healthcare providers arrive at their shifts at client facilities\n    on time and stay for the entire time reported\nretention:\n- scope: personal information\n  period: null\n  text: We retain your information for as long as is reasonably necessary for the purposes specified in this Privacy\n    Notice.\nresidency:\n- region: United States\n  text: Please note that the Services are designed for users in the United States only and are not intended for\n    users located outside the United States.\ntransfers:\n- mechanism: other\n  text: the information we collect from you may be transferred to, stored, and processed in the United States or\n    other countries outside your country of residence.\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@intelycare.com or call 1-844-683-5922\n  text: To make a request described in this section, please email us at privacy@intelycare.com or call us at 1-844-683-5922\n    .\nrights:\n- right: Access / Know\n  text: You may have the right to request access to the personal information we hold about you\n- right: Deletion\n  text: You may have the right to request that we delete personal information we hold about you.\n- right: Correction\n  text: You may have the right to request that we correct inaccurate personal information we hold about you.\n- right: Portability\n  text: You may have the right to receive a copy of the personal information we hold about you in a portable and,\n    to the extent technically feasible, readily usable format.\n- right: Opt-out of sale or sharing / targeted advertising\n  text: You may have a right to direct us not to sell your personal\
  \ information, or share or process your personal\n    information for targeted advertising.\nsale_or_sharing:\n  stance: allowed\n  text: We disclose, and have disclosed in the preceding 12 months, the following categories of personal information\n    for marketing, advertising, and analytics purposes, in a manner that may be considered “selling” or “sharing”\n"
source_yaml_url: https://artifacts.apis.io/intelycare/privacy/intelycare-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from IntelyCare's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Healthcare Staffing
- Nursing
- Workforce Management
- Scheduling
- Shift Management
- Timekeeping
- Marketplace
- Webhook
- Per Diem
- Credentialing
- Post-Acute Care
---
