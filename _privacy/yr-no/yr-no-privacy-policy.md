---
api_specs:
- filename: yr-no-alerts-api-openapi.yml
  format: yaml
  label: Yr Alerts API
  slug: yr-no-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yr-no/openapi/yr-no-alerts-api-openapi.yml
- filename: yr-no-data-api-openapi.yml
  format: yaml
  label: Yr Data API
  slug: yr-no-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yr-no/openapi/yr-no-data-api-openapi.yml
- filename: yr-no-metadata-api-openapi.yml
  format: yaml
  label: Yr Metadata API
  slug: yr-no-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yr-no/openapi/yr-no-metadata-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: This may include your name and contact details, but also other information that can indirectly be associated with you.
  - category: identifying
    text: Here, names, personal identification numbers/D-numbers, phone numbers, and email addresses are registered.
  - category: device
    text: MET logs the use of these services, including the user’s IP address.
  - category: health
    text: Case documents may also contain sensitive personal data, such as health information.
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: A data processing agreement between MET and Enonic regulates what information the provider has access to and how it should be processed.
    url: null
  purposes:
  - purpose: Better accommodate users and partners
    text: The primary purpose of MET's processing of personal data is to better accommodate our users and partners' experiences when contacting the institute or using our digital services.
  - purpose: Detect unwanted activities and troubleshoot
    text: The purpose of logging usage is to detect unwanted activities, troubleshoot, and prepare statistics that we use to improve and further develop the services.
  - purpose: Protect assets
    text: The purpose of visitor registration is to protect MET's assets.
  residency:
  - region: Europe
    text: The information is stored on servers in Europe.
  retention:
  - period: 6 months
    scope: Course registration data not covered by accounting obligations
    text: Data not covered by accounting obligations are deleted after 6 months.
  - period: 90 days
    scope: Website IP addresses on public data sites
    text: For such websites, IP addresses are stored for up to 90 days.
  - period: 120 days
    scope: Job applications
    text: Applications are deleted after 120 days.
  - period: 7 days
    scope: Video surveillance recordings
    text: Recordings are stored on servers operated by MET and are deleted after 7 days.
  - period: annually
    scope: Visitor register
    text: The electronic visitor register, Visitor, deletes data annually.
  rights:
  - right: Access own information
    text: If you are registered as a user in one of our services, you have the right to access your own information.
  - right: Correct and delete
    text: You have the right to correct and delete personal data.
  - right: Withdraw consent
    text: Even if you have previously consented to the storage of personal data, you have the right to change your mind.
  - right: Complain to authority
    text: You have the right to complain to the Data Protection Authority if you believe the processing is in violation of the regulations.
  role:
    text: The CEO of the Norwegian Meteorological Institute (MET) has the overall responsibility for MET's processing of personal data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Transfer to third countries is managed through an agreement on the transfer of information to third countries (MCC) with Google.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yr
provenance_date: '2026-11-10'
provider_name: Yr
provider_slug: yr-no
slug: yr-no-privacy-policy
source_date: '2026-11-10'
source_filename: yr-no-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.met.no/en/About-us/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yr\naid: yr-no\nurl: https://www.met.no/en/About-us/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The CEO of the Norwegian Meteorological Institute (MET) has the overall responsibility for MET's processing\n    of personal data.\ndata_categories:\n- category: contact\n  text: This may include your name and contact details, but also other information that can indirectly be associated\n    with you.\n- category: identifying\n  text: Here, names, personal identification numbers/D-numbers, phone numbers, and email addresses are registered.\n- category: device\n  text: MET logs the use\
  \ of these services, including the user’s IP address.\n- category: health\n  text: Case documents may also contain sensitive personal data, such as health information.\npurposes:\n- purpose: Better accommodate users and partners\n  text: The primary purpose of MET's processing of personal data is to better accommodate our users and partners'\n    experiences when contacting the institute or using our digital services.\n- purpose: Detect unwanted activities and troubleshoot\n  text: The purpose of logging usage is to detect unwanted activities, troubleshoot, and prepare statistics that\n    we use to improve and further develop the services.\n- purpose: Protect assets\n  text: The purpose of visitor registration is to protect MET's assets.\nretention:\n- scope: Course registration data not covered by accounting obligations\n  period: 6 months\n  text: Data not covered by accounting obligations are deleted after 6 months.\n- scope: Website IP addresses on public data sites\n  period: 90\
  \ days\n  text: For such websites, IP addresses are stored for up to 90 days.\n- scope: Job applications\n  period: 120 days\n  text: Applications are deleted after 120 days.\n- scope: Video surveillance recordings\n  period: 7 days\n  text: Recordings are stored on servers operated by MET and are deleted after 7 days.\n- scope: Visitor register\n  period: annually\n  text: The electronic visitor register, Visitor, deletes data annually.\nresidency:\n- region: Europe\n  text: The information is stored on servers in Europe.\ntransfers:\n- mechanism: other\n  text: Transfer to third countries is managed through an agreement on the transfer of information to third countries\n    (MCC) with Google.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement between MET and Enonic regulates what information the provider has access to\n    and how it should be processed.\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\
  \ own information\n  text: If you are registered as a user in one of our services, you have the right to access your own information.\n- right: Correct and delete\n  text: You have the right to correct and delete personal data.\n- right: Withdraw consent\n  text: Even if you have previously consented to the storage of personal data, you have the right to change your\n    mind.\n- right: Complain to authority\n  text: You have the right to complain to the Data Protection Authority if you believe the processing is in violation\n    of the regulations.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yr-no/privacy/yr-no-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
summary_line: 20 quoted statements, read from Yr's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Forecast
- Meteorology
- Climate
- Norway
- Nordic
- Open Data
- Aviation Weather
- Marine Weather
- Alerts
---
