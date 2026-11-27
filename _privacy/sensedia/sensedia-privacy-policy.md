---
api_specs:
- filename: sensedia-accounts-api-openapi.yml
  format: yaml
  label: Sensedia Accounts API
  slug: sensedia-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensedia/openapi/sensedia-accounts-api-openapi.yml
- filename: sensedia-health-api-openapi.yml
  format: yaml
  label: Sensedia Health API
  slug: sensedia-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensedia/openapi/sensedia-health-api-openapi.yml
- filename: sensedia-sensedia-api-api-openapi.yml
  format: yaml
  label: Sensedia Sensedia API
  slug: sensedia-sensedia-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sensedia/openapi/sensedia-sensedia-api-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Full name Social security Age Gender Marital Status Nationality Social Network Addresses Email Address Phone number Company and job title Voice & Image
  - category: financial
    text: Credit card number and security code Bank account details
  - category: professional
    text: Occupation History of professional experience Educational background Knowledge of languages Gross Salary
  - category: health
    text: Information on workers with disabilities
  - category: location
    text: Geolocation
  - category: device
    text: Source IP Address and Logical Port Device (operating system version)
  - category: behavioral
    text: Your Interests Your Habits and Characteristics Your Hobbies
  deletion:
    route: Contact the privacy channel listed in the policy
    text: We emphasize that, in certain cases, We cannot delete your Personal Data without also deleting your user account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Identify and authenticate and provide services
    text: Identify and authenticate You; Provide services to You, including answering calls, doubts, questions, suggestions and technical help
  - purpose: Recruitment
    text: Recruit employees (if You want to work with us)
  - purpose: Marketing and promotion
    text: For promotional and advertising purposes (institutional videos, whose purpose is to reinforce the brand and events held by Sensedia).
  - purpose: Fraud prevention
    text: Protect You by performing fraud prevention, credit protection and associated risks
  - purpose: Security monitoring
    text: Security monitoring of Our Environments for the sake of yours and our security
  residency:
  - region: Brazil
    text: The collected Data may be stored on our servers located in Brazil
  retention:
  - period: null
    scope: Personal Data
    text: We will use your Personal Data for as long as necessary to satisfy the purposes for which your Personal Data was collected
  - period: short periods
    scope: CCTV recordings
    text: We may also keep records of CCTV recordings for short periods
  rights:
  - right: Confirmation of processing
    text: You have the right to request confirmation of the existence of Personal Data processing, in addition to access or rectification of your Personal Data.
  - right: Limit use or revoke consent
    text: At any time, You may also limit the use and disclosure, or revoke consent to any of our activities for the processing of your Personal Data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We will not license or sell your Personal Data to third parties to use for their own marketing purposes. In cases where this type of sharing occurs, the identity of these third parties will be revealed before obtaining your consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may transfer your Personal Data to other countries, as long as they have laws and regulations compatible with those in force in Brazil.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sensedia
provenance_date: '2026-11-10'
provider_name: Sensedia
provider_slug: sensedia
slug: sensedia-privacy-policy
source_date: '2026-11-10'
source_filename: sensedia-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sensedia.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sensedia\naid: sensedia\nurl: https://www.sensedia.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Full name Social security Age Gender Marital Status Nationality Social Network Addresses Email Address Phone\n    number Company and job title Voice & Image\n- category: financial\n  text: Credit card number and security code Bank account details\n- category: professional\n  text: Occupation History of professional experience Educational background Knowledge of languages Gross Salary\n- category: health\n  text: Information\
  \ on workers with disabilities\n- category: location\n  text: Geolocation\n- category: device\n  text: Source IP Address and Logical Port Device (operating system version)\n- category: behavioral\n  text: Your Interests Your Habits and Characteristics Your Hobbies\npurposes:\n- purpose: Identify and authenticate and provide services\n  text: Identify and authenticate You; Provide services to You, including answering calls, doubts, questions, suggestions\n    and technical help\n- purpose: Recruitment\n  text: Recruit employees (if You want to work with us)\n- purpose: Marketing and promotion\n  text: For promotional and advertising purposes (institutional videos, whose purpose is to reinforce the brand\n    and events held by Sensedia).\n- purpose: Fraud prevention\n  text: Protect You by performing fraud prevention, credit protection and associated risks\n- purpose: Security monitoring\n  text: Security monitoring of Our Environments for the sake of yours and our security\nretention:\n\
  - scope: Personal Data\n  period: null\n  text: We will use your Personal Data for as long as necessary to satisfy the purposes for which your Personal\n    Data was collected\n- scope: CCTV recordings\n  period: short periods\n  text: We may also keep records of CCTV recordings for short periods\nresidency:\n- region: Brazil\n  text: The collected Data may be stored on our servers located in Brazil\ntransfers:\n- mechanism: other\n  text: We may transfer your Personal Data to other countries, as long as they have laws and regulations compatible\n    with those in force in Brazil.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the privacy channel listed in the policy\n  text: We emphasize that, in certain cases, We cannot delete your Personal Data without also deleting your user\n    account.\nrights:\n- right: Confirmation of processing\n  text: You have the right to request confirmation of the existence of Personal\
  \ Data processing, in addition to\n    access or rectification of your Personal Data.\n- right: Limit use or revoke consent\n  text: At any time, You may also limit the use and disclosure, or revoke consent to any of our activities for the\n    processing of your Personal Data\nsale_or_sharing:\n  stance: conditional\n  text: We will not license or sell your Personal Data to third parties to use for their own marketing purposes.\n    In cases where this type of sharing occurs, the identity of these third parties will be revealed before obtaining\n    your consent.\n"
source_yaml_url: https://artifacts.apis.io/sensedia/privacy/sensedia-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Sensedia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Management
- Integration
- Enterprise
- Artificial Intelligence
---
