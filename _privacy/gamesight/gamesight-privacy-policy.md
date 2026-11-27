---
api_specs:
- filename: gamesight-measurement-api-openapi.yml
  format: yaml
  label: Gamesight Measurement API
  slug: gamesight-measurement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gamesight/openapi/gamesight-measurement-api-openapi.yml
- filename: gamesight-reporting-api-openapi.yml
  format: yaml
  label: Gamesight Reporting API
  slug: gamesight-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gamesight/openapi/gamesight-reporting-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: information that can be used to personally identify Customers; such as email address, first and last name, company name, company’s website
  - category: financial
    text: Customers may also provide their billing details, such as credit card number
  - category: device
    text: The data stored by the API includes information such as hashed IP address, API version, anonymized User ID, timestamp, Developer API Key, OS version, screen resolution, timezone, system language, and in-game events.
  - category: behavioral
    text: including information regarding game purchase activity and in-game events such as DLC purchases
  - category: device
    text: Included in our cookie we collect hashed IP address, User agent string, timestamp, referral url, session_id, and an id for the particular ad seen.
  - category: professional
    text: account email address, which we use to link the creator’s Gamesight profile to their YouTube channel and to contact them
  deletion:
    route: Written request from Customer; or email to privacy@gamesight.io for YouTube data
    text: We will make reasonable commercial efforts to delete any information provided to us by a Customer upon the receipt of a written request by such Customer.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: attribution and analytics for Customers
    text: We use this information to provide attribution for our Customers which includes matching this cookies with devices.
  - purpose: creating aggregate and anonymous data
    text: The use of information collected through our service will be used for creating aggregate data and anonymous data, and for internal use or for improving the services and creating new features
  - purpose: creator discovery and campaign reporting
    text: to provide creator discovery, evaluation, brand-safety review, and campaign performance reporting to our Customers (game publishers and developers)
  - purpose: fraud prevention and diagnostics
    text: help diagnose and prevent fraudulent activity
  retention:
  - period: null
    scope: Personal Information for Customer accounts
    text: We may retain Personal Information for as long as the applicable Customer account is active or as is necessary for us to provide Services
  - period: 30 days
    scope: YouTube data after revocation
    text: When you do, we stop collecting your data and delete the YouTube data collected through that authorization within 30 days.
  - period: 7 days
    scope: YouTube data on deletion request
    text: and we will do so within 7 days
  - period: null
    scope: YouTube channel identity
    text: We retain this information until the creator disconnects the channel or requests its deletion.
  rights:
  - right: access
    text: Upon request, we will provide you with information about whether we hold any of your Personal Information.
  - right: correction and update
    text: If your Personal Information changes, you may correct or update it by making the change on our member information page or by emailing us at privacy@gamesight.io .
  - right: opt-out of tracking
    text: If you are an Player, you can opt-out of Gamesight Analytics tracking by emailing us at privacy@gamesight.io
  role:
    text: We collect information under the direction of our Customers, and have no direct relationship with the individuals whose data we process.
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell it.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Gamesight
provenance_date: '2026-11-09'
provider_name: Gamesight
provider_slug: gamesight
slug: gamesight-privacy-policy
source_date: '2026-11-09'
source_filename: gamesight-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gamesight.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Gamesight\naid: gamesight\nurl: https://gamesight.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We collect information under the direction of our Customers, and have no direct relationship with the individuals\n    whose data we process.\ndata_categories:\n- category: identifying\n  text: information that can be used to personally identify Customers; such as email address, first and last name,\n    company name, company’s website\n- category: financial\n  text: Customers may also provide their billing details, such as credit card number\n- category: device\n  text: The data stored\
  \ by the API includes information such as hashed IP address, API version, anonymized User\n    ID, timestamp, Developer API Key, OS version, screen resolution, timezone, system language, and in-game events.\n- category: behavioral\n  text: including information regarding game purchase activity and in-game events such as DLC purchases\n- category: device\n  text: Included in our cookie we collect hashed IP address, User agent string, timestamp, referral url, session_id,\n    and an id for the particular ad seen.\n- category: professional\n  text: account email address, which we use to link the creator’s Gamesight profile to their YouTube channel and\n    to contact them\npurposes:\n- purpose: attribution and analytics for Customers\n  text: We use this information to provide attribution for our Customers which includes matching this cookies with\n    devices.\n- purpose: creating aggregate and anonymous data\n  text: The use of information collected through our service will be used for\
  \ creating aggregate data and anonymous\n    data, and for internal use or for improving the services and creating new features\n- purpose: creator discovery and campaign reporting\n  text: to provide creator discovery, evaluation, brand-safety review, and campaign performance reporting to our\n    Customers (game publishers and developers)\n- purpose: fraud prevention and diagnostics\n  text: help diagnose and prevent fraudulent activity\nretention:\n- scope: Personal Information for Customer accounts\n  period: null\n  text: We may retain Personal Information for as long as the applicable Customer account is active or as is necessary\n    for us to provide Services\n- scope: YouTube data after revocation\n  period: 30 days\n  text: When you do, we stop collecting your data and delete the YouTube data collected through that authorization\n    within 30 days.\n- scope: YouTube data on deletion request\n  period: 7 days\n  text: and we will do so within 7 days\n- scope: YouTube channel\
  \ identity\n  period: null\n  text: We retain this information until the creator disconnects the channel or requests its deletion.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Written request from Customer; or email to privacy@gamesight.io for YouTube data\n  text: We will make reasonable commercial efforts to delete any information provided to us by a Customer upon the\n    receipt of a written request by such Customer.\nrights:\n- right: access\n  text: Upon request, we will provide you with information about whether we hold any of your Personal Information.\n- right: correction and update\n  text: If your Personal Information changes, you may correct or update it by making the change on our member information\n    page or by emailing us at privacy@gamesight.io .\n- right: opt-out of tracking\n  text: If you are an Player, you can opt-out of Gamesight Analytics tracking by emailing us\
  \ at privacy@gamesight.io\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell it.\n"
source_yaml_url: https://artifacts.apis.io/gamesight/privacy/gamesight-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 19 quoted statements, read from Gamesight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Marketing
- Analytics
- Attribution
- Measurements
- Advertising
- Creators
- Game Development
---
