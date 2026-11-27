---
api_specs:
- filename: caltech-dataselect-api-openapi.yml
  format: yaml
  label: California Institute of Technology Data Select API
  slug: caltech-dataselect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caltech/openapi/caltech-dataselect-api-openapi.yml
- filename: caltech-event-api-openapi.yml
  format: yaml
  label: California Institute of Technology Event API
  slug: caltech-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caltech/openapi/caltech-event-api-openapi.yml
- filename: caltech-records-api-openapi.yml
  format: yaml
  label: California Institute of Technology Records API
  slug: caltech-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caltech/openapi/caltech-records-api-openapi.yml
- filename: caltech-station-api-openapi.yml
  format: yaml
  label: California Institute of Technology Station API
  slug: caltech-station-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caltech/openapi/caltech-station-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact and account information, such as full name, mailing address, email address, phone number, identification number
  - category: financial
    text: Commercial and financial information, such as donation or transaction information.
  - category: professional
    text: Professional or employment information, such as employer name, your title, work contact information
  - category: location
    text: Geolocation information, which may be general location derived from your IP address or more precise GPS location information
  - category: behavioral
    text: Records of your interactions with Caltech systems and Services, including account activity, Wi-Fi usage, event participation, transactions, inquiries, or other interactions
  - category: device
    text: device identifiers such as MAC address and UUID, carrier and country location, hardware and processor information
  deletion:
    route: Email privacy contact
    text: If you believe we have collected personal information online from a child under 13, please contact us so that we can delete it in accordance with applicable legal requirements.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Maintain and improve services
    text: To maintain, provide, operate, support, and improve the Services and offerings
  - purpose: Advertising
    text: This may include working with our partners to serve you and similar audiences relevant advertisements across other websites
  - purpose: Security and fraud
    text: To secure the sites and detect fraud and illegal activity, including cyberattacks or attempts to commit identity theft
  residency:
  - region: United States
    text: Caltech is located in the United States and recipients of the data disclosures described in this Notice may be located in the United States or elsewhere in the world
  retention:
  - period: null
    scope: General personal information
    text: We will retain your information until after we determine that we no longer need it to fulfill the purposes outlined in this Notice, unless the law or Caltech policy requires us to keep it for a longer period of time.
  - period: null
    scope: Backups
    text: we make backups of certain data, which we may retain for longer than the original data
  rights:
  - right: Right to request deletion
    text: The right to request the deletion of your personal data
  - right: Right to object
    text: The right to object to the processing of your personal data
  - right: Right to access copy
    text: The right to transfer or obtain a copy of your personal data in an easily accessible format
  - right: Right to complain
    text: The right to complain to a supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: California Institute of Technology
provenance_date: '2026-11-09'
provider_name: California Institute of Technology
provider_slug: caltech
slug: caltech-privacy-policy
source_date: '2026-11-09'
source_filename: caltech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.caltech.edu/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: California Institute of Technology\naid: caltech\nurl: https://www.caltech.edu/privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Contact and account information, such as full name, mailing address, email address, phone number, identification\n    number\n- category: financial\n  text: Commercial and financial information, such as donation or transaction information.\n- category: professional\n  text: Professional or employment information, such as employer name, your title, work contact information\n- category: location\n \
  \ text: Geolocation information, which may be general location derived from your IP address or more precise GPS\n    location information\n- category: behavioral\n  text: Records of your interactions with Caltech systems and Services, including account activity, Wi-Fi usage,\n    event participation, transactions, inquiries, or other interactions\n- category: device\n  text: device identifiers such as MAC address and UUID, carrier and country location, hardware and processor information\npurposes:\n- purpose: Maintain and improve services\n  text: To maintain, provide, operate, support, and improve the Services and offerings\n- purpose: Advertising\n  text: This may include working with our partners to serve you and similar audiences relevant advertisements across\n    other websites\n- purpose: Security and fraud\n  text: To secure the sites and detect fraud and illegal activity, including cyberattacks or attempts to commit\n    identity theft\nretention:\n- scope: General personal information\n\
  \  period: null\n  text: We will retain your information until after we determine that we no longer need it to fulfill the purposes\n    outlined in this Notice, unless the law or Caltech policy requires us to keep it for a longer period of time.\n- scope: Backups\n  period: null\n  text: we make backups of certain data, which we may retain for longer than the original data\nresidency:\n- region: United States\n  text: Caltech is located in the United States and recipients of the data disclosures described in this Notice\n    may be located in the United States or elsewhere in the world\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy contact\n  text: If you believe we have collected personal information online from a child under 13, please contact us so\n    that we can delete it in accordance with applicable legal requirements.\nrights:\n- right: Right to request deletion\n  text: The right\
  \ to request the deletion of your personal data\n- right: Right to object\n  text: The right to object to the processing of your personal data\n- right: Right to access copy\n  text: The right to transfer or obtain a copy of your personal data in an easily accessible format\n- right: Right to complain\n  text: The right to complain to a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caltech/privacy/caltech-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 17 quoted statements, read from California Institute of Technology's own page on 2026-11-09.
synthetic: false
tags:
- University
- Higher Education
- Education
- Private Research University
- Institute of Technology
- United States
- California
- Research Data
- Open Data
- Research Repository
- Identity Federation
- Astronomy
- Seismology
- Research Computing
- OAI-PMH
---
