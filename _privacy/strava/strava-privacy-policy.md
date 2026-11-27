---
api_specs:
- filename: strava-activities-api-openapi.yml
  format: yaml
  label: Strava Activities API
  slug: strava-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-activities-api-openapi.yml
- filename: strava-athletes-api-openapi.yml
  format: yaml
  label: Strava Athletes API
  slug: strava-athletes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-athletes-api-openapi.yml
- filename: strava-clubs-api-openapi.yml
  format: yaml
  label: Strava Clubs API
  slug: strava-clubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-clubs-api-openapi.yml
- filename: strava-gear-api-openapi.yml
  format: yaml
  label: Strava Gear API
  slug: strava-gear-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-gear-api-openapi.yml
- filename: strava-routes-api-openapi.yml
  format: yaml
  label: Strava Routes API
  slug: strava-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-routes-api-openapi.yml
- filename: strava-segment-efforts-api-openapi.yml
  format: yaml
  label: Strava Segment Efforts API
  slug: strava-segment-efforts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-segment-efforts-api-openapi.yml
- filename: strava-segments-api-openapi.yml
  format: yaml
  label: Strava Segments API
  slug: strava-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-segments-api-openapi.yml
- filename: strava-streams-api-openapi.yml
  format: yaml
  label: Strava Streams API
  slug: strava-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-streams-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect account information such as your name, email address, phone number, date of birth, gender, username, and password.
  - category: location
    text: We collect or infer location information when you sign up for and use the Services.
  - category: health
    text: Activity Data can also include health data, such as heart rate, if you choose to provide it.
  - category: financial
    text: we collect information about your purchase, including the final four digits of your credit card number.
  - category: device
    text: We collect technical information from the browser, computer, or mobile device used to access the Services.
  - category: communication
    text: We collect the information you provide in connection with requests for support.
  deletion:
    route: Delete account via account instructions
    text: To delete your account, follow the instructions provided here .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Targeted advertising
    text: 'Targeted Advertising : We advertise our Services through third parties, and may use cookies and other tracking technologies to support targeted advertising and serve relevant ads'
  - purpose: AI development and training
    text: We use information to enhance the quality, reliability, and/or accuracy of our AI Features by creating, developing, training, testing, improving, and maintaining AI and ML models run by Strava or our service providers.
  - purpose: Analytics
    text: 'Analytics : We use information to measure traffic and usage trends, understand how visitors interact with content, and make improvements.'
  residency:
  - region: United States
    text: your information will be transferred, processed, and stored in the United States.
  retention:
  - period: null
    scope: Account information
    text: We generally keep information associated with your account until you delete it or we no longer need the information to provide the Services.
  - period: up to 45 days
    scope: Deleted account data
    text: Following deletion of your account, it may take up to 45 days to delete your personal information and system logs from our systems.
  rights:
  - right: Access and portability
    text: 'Access and Portability : You may have the right to know, and request access to, the personal information we collect, use, share, or otherwise process about you.'
  - right: Rectify or correct
    text: 'Rectify or Correct : You may have the right to correct inaccurate information.'
  - right: Restrict or delete
    text: 'Restrict or Delete : You may have the right to restrict or delete personal information.'
  - right: Revoke consent
    text: 'Revoke Consent : To the extent we rely on your consent to engage in certain processing, you may have the right to withdraw that consent at any time.'
  - right: Opt out of sharing for targeted advertising
    text: You have the right to opt out of sharing your personal information for targeted advertising.
  - right: Appeal
    text: 'Appeal : You may have the right to appeal our decision regarding a request related to your privacy rights.'
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
  - mechanism: SCC
    text: Whenever we transfer personal information internationally, we use legal mechanisms, such as Standard Contractual Clauses, to ensure the protection of your personal information, in accordance with applicable data protection law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Strava
provenance_date: '2026-11-10'
provider_name: Strava
provider_slug: strava
slug: strava-privacy-policy
source_date: '2026-11-10'
source_filename: strava-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.strava.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Strava\naid: strava\nurl: https://www.strava.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect account information such as your name, email address, phone number, date of birth, gender, username,\n    and password.\n- category: location\n  text: We collect or infer location information when you sign up for and use the Services.\n- category: health\n  text: Activity Data can also include health data, such as heart rate, if you choose to provide it.\n- category: financial\n  text: we collect information about your\
  \ purchase, including the final four digits of your credit card number.\n- category: device\n  text: We collect technical information from the browser, computer, or mobile device used to access the Services.\n- category: communication\n  text: We collect the information you provide in connection with requests for support.\npurposes:\n- purpose: Targeted advertising\n  text: 'Targeted Advertising : We advertise our Services through third parties, and may use cookies and other tracking\n    technologies to support targeted advertising and serve relevant ads'\n- purpose: AI development and training\n  text: We use information to enhance the quality, reliability, and/or accuracy of our AI Features by creating,\n    developing, training, testing, improving, and maintaining AI and ML models run by Strava or our service providers.\n- purpose: Analytics\n  text: 'Analytics : We use information to measure traffic and usage trends, understand how visitors interact with\n    content, and make improvements.'\n\
  retention:\n- scope: Account information\n  period: null\n  text: We generally keep information associated with your account until you delete it or we no longer need the\n    information to provide the Services.\n- scope: Deleted account data\n  period: up to 45 days\n  text: Following deletion of your account, it may take up to 45 days to delete your personal information and system\n    logs from our systems.\nresidency:\n- region: United States\n  text: your information will be transferred, processed, and stored in the United States.\ntransfers:\n- mechanism: SCC\n  text: Whenever we transfer personal information internationally, we use legal mechanisms, such as Standard Contractual\n    Clauses, to ensure the protection of your personal information, in accordance with applicable data protection\n    law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account via account instructions\n  text: To delete your account,\
  \ follow the instructions provided here .\nrights:\n- right: Access and portability\n  text: 'Access and Portability : You may have the right to know, and request access to, the personal information\n    we collect, use, share, or otherwise process about you.'\n- right: Rectify or correct\n  text: 'Rectify or Correct : You may have the right to correct inaccurate information.'\n- right: Restrict or delete\n  text: 'Restrict or Delete : You may have the right to restrict or delete personal information.'\n- right: Revoke consent\n  text: 'Revoke Consent : To the extent we rely on your consent to engage in certain processing, you may have the\n    right to withdraw that consent at any time.'\n- right: Opt out of sharing for targeted advertising\n  text: You have the right to opt out of sharing your personal information for targeted advertising.\n- right: Appeal\n  text: 'Appeal : You may have the right to appeal our decision regarding a request related to your privacy rights.'\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/strava/privacy/strava-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Strava's own page on 2026-11-10.
synthetic: false
tags:
- Cycling
- Fitness
- Fitness Tracking
- Running
- Sports
---
