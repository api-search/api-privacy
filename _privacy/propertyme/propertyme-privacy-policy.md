---
api_specs:
- filename: propertyme-connection-api-openapi.yml
  format: yaml
  label: PropertyMe Connection API
  slug: propertyme-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-connection-api-openapi.yml
- filename: propertyme-scope-activities-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Activities API'
  slug: propertyme-scope-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-activities-api-openapi.yml
- filename: propertyme-scope-bills-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Bills API'
  slug: propertyme-scope-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-bills-api-openapi.yml
- filename: propertyme-scope-contacts-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Contacts API'
  slug: propertyme-scope-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-contacts-api-openapi.yml
- filename: propertyme-scope-messages-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Messages API'
  slug: propertyme-scope-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-messages-api-openapi.yml
- filename: propertyme-scope-properties-api-openapi.yml
  format: yaml
  label: 'PropertyMe Scope: Properties API'
  slug: propertyme-scope-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyme/openapi/propertyme-scope-properties-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, date of birth and contact details
  - category: financial
    text: credit card number, expiry date, bank details and billing address
  - category: location
    text: we may access, collect, monitor and/or remotely store “location data,” which may include GPS coordinates or similar information regarding the location of your mobile device
  - category: device
    text: your IP address, the date and time of your visit, the parts of the Services you access, your actions, and the browser you are using
  - category: professional
    text: professional history, reference and background checks
  - category: communication
    text: communications you make using our Website or Services
  deletion:
    route: delete the record within the Services or contact us
    text: You can permanently delete the data (and personal information) of an individual user (for example an owner or tenant) by deleting the record within the relevant part of the Services. Additionally, you may request the deletion of your data (including personal information) at any time by contacting us using the details listed in section 11(a).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing products or services
    text: This includes for the purpose of providing products or services to you
  - purpose: model training and improvement
    text: including to train, develop and improve models and algorithms used in connection with our Services
  - purpose: marketing
    text: to conduct marketing activities (where you have consented or where otherwise permitted by law) and to conduct market research
  residency:
  - region: Australia and United States of America
    text: At this time, the third parties referred to in paragraph (b) are located in Australia and the United States of America.
  retention:
  - period: indefinitely
    scope: general data
    text: We retain data (including personal information) indefinitely, except credit card data which is deleted when your registration or subscription is cancelled.
  - period: null
    scope: credit card details
    text: We also delete any credit card details you provide to us from our servers once you cancel your registration or subscription.
  rights:
  - right: access
    text: We will, on request, provide you with access to the information we hold about you
  - right: correction
    text: including for the purpose of correcting or updating that information
  - right: complaint to OAIC
    text: you may make a complaint to the Office of the Australian Information Commissioner
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We take all reasonable steps to ensure that the overseas recipient does not breach the Australian Privacy Principles in relation to the personal information we disclose to them.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PropertyMe
provenance_date: '2026-11-10'
provider_name: PropertyMe
provider_slug: propertyme
slug: propertyme-privacy-policy
source_date: '2026-11-10'
source_filename: propertyme-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.propertyme.com.au/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PropertyMe\naid: propertyme\nurl: https://www.propertyme.com.au/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, date of birth and contact details\n- category: financial\n  text: credit card number, expiry date, bank details and billing address\n- category: location\n  text: we may access, collect, monitor and/or remotely store “location data,” which may include GPS coordinates\n    or similar information regarding the location of your mobile device\n- category: device\n  text: your IP address, the date and time of your\
  \ visit, the parts of the Services you access, your actions, and\n    the browser you are using\n- category: professional\n  text: professional history, reference and background checks\n- category: communication\n  text: communications you make using our Website or Services\npurposes:\n- purpose: providing products or services\n  text: This includes for the purpose of providing products or services to you\n- purpose: model training and improvement\n  text: including to train, develop and improve models and algorithms used in connection with our Services\n- purpose: marketing\n  text: to conduct marketing activities (where you have consented or where otherwise permitted by law) and to conduct\n    market research\nretention:\n- scope: general data\n  period: indefinitely\n  text: We retain data (including personal information) indefinitely, except credit card data which is deleted when\n    your registration or subscription is cancelled.\n- scope: credit card details\n  period: null\n \
  \ text: We also delete any credit card details you provide to us from our servers once you cancel your registration\n    or subscription.\nresidency:\n- region: Australia and United States of America\n  text: At this time, the third parties referred to in paragraph (b) are located in Australia and the United States\n    of America.\ntransfers:\n- mechanism: other\n  text: We take all reasonable steps to ensure that the overseas recipient does not breach the Australian Privacy\n    Principles in relation to the personal information we disclose to them.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete the record within the Services or contact us\n  text: You can permanently delete the data (and personal information) of an individual user (for example an owner\n    or tenant) by deleting the record within the relevant part of the Services. Additionally, you may request the\n    deletion of your data (including personal\
  \ information) at any time by contacting us using the details listed\n    in section 11(a).\nrights:\n- right: access\n  text: We will, on request, provide you with access to the information we hold about you\n- right: correction\n  text: including for the purpose of correcting or updating that information\n- right: complaint to OAIC\n  text: you may make a complaint to the Office of the Australian Information Commissioner\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/propertyme/privacy/propertyme-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from PropertyMe's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Australia
- Property Management
- Rentals
- PropTech
- Tenancy
- Trust Accounting
- Inspection
- Maintenance
- Documents
- Payments
- New Zealand
---
