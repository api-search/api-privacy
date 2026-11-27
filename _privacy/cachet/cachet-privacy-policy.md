---
api_specs:
- filename: cachet-connect-api-openapi.yml
  format: yaml
  label: Cachet Connect API
  slug: cachet-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-connect-api-openapi.yml
- filename: cachet-gig-events-api-openapi.yml
  format: yaml
  label: Cachet Gig-Events API
  slug: cachet-gig-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-gig-events-api-openapi.yml
- filename: cachet-user-api-openapi.yml
  format: yaml
  label: Cachet User API
  slug: cachet-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-user-api-openapi.yml
- filename: cachet-vehicle-events-api-openapi.yml
  format: yaml
  label: Cachet Vehicle events API
  slug: cachet-vehicle-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cachet/openapi/cachet-vehicle-events-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: telephone number, e-mail address and country of residence
  - category: identifying
    text: User identification data, name, surname, personal identification number
  - category: financial
    text: The bank account number, payment data, invoice or payment notification data and other payment data
  - category: location
    text: location with city accuracy
  - category: behavioral
    text: Vehicle registration number and activity data (start and end of the trip, length of the trip, location with city accuracy)
  deletion:
    route: request to support@cachet.me
    text: require the deletion of personal data (not applicable to insurance contracts and policies as they are subject to a statutory retention period)
  dpa:
    available: true
    text: DPA provided by the insurance intermediary
    url: null
  purposes:
  - purpose: account management
    text: Cachet processes personal data necessary for the management of the accounts of the Users of the Platform
  - purpose: insurance intermediation
    text: Providing data for the insurance intermediaries
  - purpose: marketing
    text: Newsletters Name, e-mail address Marketing Consent
  residency:
  - region: EU/EEA
    text: Cachet Broker processes personal data in the European Union (EU) and within the European Economic Area (EEA).
  retention:
  - period: 24 months
    scope: account without purchases
    text: If no purchases are made by the User, the account will be deleted after 24 months since the sign-up
  - period: Seven years
    scope: payment data
    text: Payment data Accounting Seven years since the payment is made
  - period: Three years
    scope: insurance events
    text: Insurance events Providing information to the insurance intermediaries Three years since the information was provided to insurance intermediaries
  rights:
  - right: access
    text: access to personal data (accessed via the Platform)
  - right: correction
    text: correction of inaccurate personal data
  - right: deletion
    text: require the deletion of personal data
  - right: restriction
    text: restriction of processing of personal data
  - right: portability
    text: transfer personal data to the controller designated by the User
  - right: withdraw consent
    text: withdrawal of data-processing consent
  - right: complaint
    text: The User has the right to lodge a complaint against the processing of personal data with the supervisory authority
  role:
    text: Cachet is the controller of the data processing necessary for the management of the accounts of the Users of the Platform
    value: both
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
name: Cachet
provenance_date: '2026-11-09'
provider_name: Cachet
provider_slug: cachet
slug: cachet-privacy-policy
source_date: '2026-11-09'
source_filename: cachet-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cachet.me/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cachet\naid: cachet\nurl: https://cachet.me/en/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Cachet is the controller of the data processing necessary for the management of the accounts of the Users\n    of the Platform\ndata_categories:\n- category: contact\n  text: telephone number, e-mail address and country of residence\n- category: identifying\n  text: User identification data, name, surname, personal identification number\n- category: financial\n  text: The bank account number, payment data, invoice or payment notification data and other payment data\n- category: location\n\
  \  text: location with city accuracy\n- category: behavioral\n  text: Vehicle registration number and activity data (start and end of the trip, length of the trip, location with\n    city accuracy)\npurposes:\n- purpose: account management\n  text: Cachet processes personal data necessary for the management of the accounts of the Users of the Platform\n- purpose: insurance intermediation\n  text: Providing data for the insurance intermediaries\n- purpose: marketing\n  text: Newsletters Name, e-mail address Marketing Consent\nretention:\n- scope: account without purchases\n  period: 24 months\n  text: If no purchases are made by the User, the account will be deleted after 24 months since the sign-up\n- scope: payment data\n  period: Seven years\n  text: Payment data Accounting Seven years since the payment is made\n- scope: insurance events\n  period: Three years\n  text: Insurance events Providing information to the insurance intermediaries Three years since the information\n    was provided\
  \ to insurance intermediaries\nresidency:\n- region: EU/EEA\n  text: Cachet Broker processes personal data in the European Union (EU) and within the European Economic Area (EEA).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: DPA provided by the insurance intermediary\ndeletion:\n  route: request to support@cachet.me\n  text: require the deletion of personal data (not applicable to insurance contracts and policies as they are subject\n    to a statutory retention period)\nrights:\n- right: access\n  text: access to personal data (accessed via the Platform)\n- right: correction\n  text: correction of inaccurate personal data\n- right: deletion\n  text: require the deletion of personal data\n- right: restriction\n  text: restriction of processing of personal data\n- right: portability\n  text: transfer personal data to the controller designated by the User\n- right: withdraw consent\n  text: withdrawal of data-processing consent\n\
  - right: complaint\n  text: The User has the right to lodge a complaint against the processing of personal data with the supervisory\n    authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cachet/privacy/cachet-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
summary_line: 22 quoted statements, read from Cachet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Mobility
- Gig Economy
- Car Sharing
- Embedded Insurance
- Event
---
