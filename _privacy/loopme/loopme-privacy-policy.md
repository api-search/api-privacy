---
api_specs:
- filename: loopme-ad-serving-api-openapi.yml
  format: yaml
  label: LoopMe S2S Ad Serving API
  slug: loopme-ad-serving-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopme/openapi/loopme-ad-serving-api-openapi.yml
- filename: loopme-advertiser-reporting-api-openapi.yml
  format: yaml
  label: LoopMe Advertiser Reporting API
  slug: loopme-advertiser-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopme/openapi/loopme-advertiser-reporting-api-openapi.yml
- filename: loopme-publisher-reporting-api-openapi.yml
  format: yaml
  label: LoopMe Publisher Reporting API
  slug: loopme-publisher-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopme/openapi/loopme-publisher-reporting-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: LoopMe online identifiers (this is the numerical sequence of letters and numbers which LoopMe assign to each User which is unique to LoopMe)
  - category: contact
    text: If you contact our customer support team, we will collect your name and email address in order to respond to your request.
  - category: location
    text: 'Location data: On mobile apps, we may collect your location on the publisher''s app (latitude / longitude) (subject to your consent where required).'
  - category: device
    text: Operating system of your device version, language, date and time, screen size, audio setting, storage space, battery status
  - category: behavioral
    text: User Interactions (e.g., UUID 123 interacts with mainly content related to travel).
  - category: health
    text: Where you chose to provide it, this may include sensitive personal information such as information about any health conditions you suffer from.
  deletion:
    route: Email privacy@loopme.com
    text: If you have any questions or would like to exercise any of these rights by contacting us at privacy@loopme.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Use limited data to select advertising
    text: Advertising presented to you can be based on limited data, such as the website or app you are using, your non-precise geolocation, your device type or which content you are (or have been) interacting with
  - purpose: Create personalised advertising profile
    text: This is then used to build or improve a profile about you (that might include possible interests and personal aspects).
  - purpose: Measure ad performance
    text: Information regarding which advertising is presented to you and how you interact with it can be used to determine how well an ad has worked for you or other users
  - purpose: Ensure security, prevent and detect fraud
    text: Your data is used to monitor for and prevent unusual and possibly fraudulent activity
  - purpose: Provide consumer intelligence to clients
    text: We may share data about you, such as advertising identifiers, audience segment data, survey responses, and campaign performance data, with our advertiser and media company clients
  residency:
  - region: Netherlands
    text: our primary servers are located in the Netherlands, Europe
  retention:
  - period: 13 months
    scope: Event level data
    text: LoopMe deletes all event level data (ad views, clicks etc.) after 13 months.
  - period: 13 months
    scope: Dormant user profiles
    text: Dormant profiles are deleted where there has been no activity on the profile for a period of 13 months.
  - period: 365 days
    scope: Chartboost user data
    text: Chartboost retains personal data in relation to Users for a maximum of 365 days, after which it is either anonymised or destroyed.
  rights:
  - right: Access
    text: the right to request access to, correction of, updates to, or deletion of your personal information
  - right: Objection and restriction
    text: the right to object to processing of your personal information, ask us to restrict processing of your personal information or request portability of your information
  - right: Withdraw consent
    text: where we process your personal information on the basis of consent, the right to withdraw your consent at any time
  - right: Complain to authority
    text: the right to complain to a data protection authority if believed that the processing of your personal data is in violation of the legislation.
  - right: Deletion (US states)
    text: Deletion. You may ask us to delete the personal information that we have collected about you.
  role:
    text: This Privacy Notice applies to the processing of User personal data carried out by LoopMe Ltd (company number 07979184), a company registered in England and its affiliated subsidiaries, including Chartboost LLC
    value: both
  sale_or_sharing:
    stance: conditional
    text: We may also provide personal information to our third-party partners for such purposes. These activities may constitute "selling," "sharing," processing personal information for targeted advertising purposes
  subprocessors:
    text: A list detailing some of these providers is provided here .
    url: null
  transfers:
  - mechanism: SCC
    text: These include implementing the European Commission's Standard Contractual Clauses (and UK equivalent) for transfers of personal information between our group companies
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LoopMe
provenance_date: '2026-11-09'
provider_name: LoopMe
provider_slug: loopme
slug: loopme-privacy-policy
source_date: '2026-11-09'
source_filename: loopme-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://legal.loopme.com/privacy-center
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LoopMe\naid: loopme\nurl: https://legal.loopme.com/privacy-center\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This Privacy Notice applies to the processing of User personal data carried out by LoopMe Ltd (company number\n    07979184), a company registered in England and its affiliated subsidiaries, including Chartboost LLC\ndata_categories:\n- category: identifying\n  text: LoopMe online identifiers (this is the numerical sequence of letters and numbers which LoopMe assign to\n    each User which is unique to LoopMe)\n- category: contact\n  text: If you contact our customer support team, we\
  \ will collect your name and email address in order to respond\n    to your request.\n- category: location\n  text: 'Location data: On mobile apps, we may collect your location on the publisher''s app (latitude / longitude)\n    (subject to your consent where required).'\n- category: device\n  text: Operating system of your device version, language, date and time, screen size, audio setting, storage space,\n    battery status\n- category: behavioral\n  text: User Interactions (e.g., UUID 123 interacts with mainly content related to travel).\n- category: health\n  text: Where you chose to provide it, this may include sensitive personal information such as information about\n    any health conditions you suffer from.\npurposes:\n- purpose: Use limited data to select advertising\n  text: Advertising presented to you can be based on limited data, such as the website or app you are using, your\n    non-precise geolocation, your device type or which content you are (or have been) interacting\
  \ with\n- purpose: Create personalised advertising profile\n  text: This is then used to build or improve a profile about you (that might include possible interests and personal\n    aspects).\n- purpose: Measure ad performance\n  text: Information regarding which advertising is presented to you and how you interact with it can be used to\n    determine how well an ad has worked for you or other users\n- purpose: Ensure security, prevent and detect fraud\n  text: Your data is used to monitor for and prevent unusual and possibly fraudulent activity\n- purpose: Provide consumer intelligence to clients\n  text: We may share data about you, such as advertising identifiers, audience segment data, survey responses, and\n    campaign performance data, with our advertiser and media company clients\nretention:\n- scope: Event level data\n  period: 13 months\n  text: LoopMe deletes all event level data (ad views, clicks etc.) after 13 months.\n- scope: Dormant user profiles\n  period: 13 months\n\
  \  text: Dormant profiles are deleted where there has been no activity on the profile for a period of 13 months.\n- scope: Chartboost user data\n  period: 365 days\n  text: Chartboost retains personal data in relation to Users for a maximum of 365 days, after which it is either\n    anonymised or destroyed.\nresidency:\n- region: Netherlands\n  text: our primary servers are located in the Netherlands, Europe\ntransfers:\n- mechanism: SCC\n  text: These include implementing the European Commission's Standard Contractual Clauses (and UK equivalent) for\n    transfers of personal information between our group companies\nsubprocessors:\n  url: null\n  text: A list detailing some of these providers is provided here .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@loopme.com\n  text: If you have any questions or would like to exercise any of these rights by contacting us at privacy@loopme.com\nrights:\n- right: Access\n  text: the right to request access\
  \ to, correction of, updates to, or deletion of your personal information\n- right: Objection and restriction\n  text: the right to object to processing of your personal information, ask us to restrict processing of your personal\n    information or request portability of your information\n- right: Withdraw consent\n  text: where we process your personal information on the basis of consent, the right to withdraw your consent at\n    any time\n- right: Complain to authority\n  text: the right to complain to a data protection authority if believed that the processing of your personal data\n    is in violation of the legislation.\n- right: Deletion (US states)\n  text: Deletion. You may ask us to delete the personal information that we have collected about you.\nsale_or_sharing:\n  stance: conditional\n  text: We may also provide personal information to our third-party partners for such purposes. These activities\n    may constitute \"selling,\" \"sharing,\" processing personal information\
  \ for targeted advertising purposes\n"
source_yaml_url: https://artifacts.apis.io/loopme/privacy/loopme-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from LoopMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- AdTech
- Mobile Advertising
- CTV
- Reporting
- Programmatic
- Ai Enterprise Software
- SDK
---
