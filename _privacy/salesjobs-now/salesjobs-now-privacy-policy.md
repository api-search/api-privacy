---
api_specs:
- filename: salesjobs-now-jobs-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Jobs API
  slug: salesjobs-now-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-jobs-api-openapi.yml
- filename: salesjobs-now-pay-csv-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Pay.csv API
  slug: salesjobs-now-pay-csv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-pay-csv-api-openapi.yml
- filename: salesjobs-now-pay-json-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Pay.json API
  slug: salesjobs-now-pay-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-pay-json-api-openapi.yml
- filename: salesjobs-now-roles-json-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Roles.json API
  slug: salesjobs-now-roles-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-roles-json-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'What you type in or upload yourself: the email address you sign up or subscribe with, your name, your LinkedIn link or CV, answers you give in forms, your forum posts, and messages to us or to the assistant in your account.'
  - category: location
    text: a rough location worked out from your connection
  - category: behavioral
    text: pages viewed, buttons pressed (an Apply click, for example)
  - category: device
    text: the browser and device you use
  - category: professional
    text: your work history with its dates, education, certifications, languages and skills
  - category: communication
    text: Conversations with the assistant in your account are stored with the account, so it can pick up where you left off.
  deletion:
    route: account deletion steps
    text: To close your account and see exactly what goes with it, read the account deletion steps.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the board
    text: 'To run the board: show open sales roles, keep your account, send the alerts and emails you asked for, and pass you to an employer''s own application page when you press Apply.'
  - purpose: match you
    text: 'To match you: rank openings against your profile and say how well a given role fits.'
  - purpose: improve features
    text: To learn which pages and features help people land sales jobs, so we can improve them.
  retention:
  - period: null
    scope: general
    text: Data stays only as long as the purpose it was collected for, plus any longer period the law sets or allows
  rights:
  - right: access
    text: See whether we process your data, and get a copy of it.
  - right: erase
    text: Erase it, in the cases the law allows.
  - right: object
    text: Object to processing, including any based on legitimate interests and any for direct marketing.
  role:
    text: O-mega Enterprise, Inc., the operator of SalesJobs.Now, decides why and how your personal data is processed, which makes it the "controller" under data protection law.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data.
  subprocessors:
    text: 'Companies that run parts of the Service for us: hosting and database, email delivery, the AI models that read profiles and searches, our profile data provider and our voice provider.'
    url: null
  transfers:
  - mechanism: SCC
    text: such as the European Commission's standard contractual clauses
  - mechanism: adequacy
    text: an adequacy decision
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SalesJobs.Now
provenance_date: '2026-11-10'
provider_name: SalesJobs.Now
provider_slug: salesjobs-now
slug: salesjobs-now-privacy-policy
source_date: '2026-11-10'
source_filename: salesjobs-now-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://salesjobs.now/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SalesJobs.Now\naid: salesjobs-now\nurl: https://salesjobs.now/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: O-mega Enterprise, Inc., the operator of SalesJobs.Now, decides why and how your personal data is processed,\n    which makes it the \"controller\" under data protection law.\ndata_categories:\n- category: identifying\n  text: 'What you type in or upload yourself: the email address you sign up or subscribe with, your name, your LinkedIn\n    link or CV, answers you give in forms, your forum posts, and messages to us or to the assistant in your account.'\n- category: location\n\
  \  text: a rough location worked out from your connection\n- category: behavioral\n  text: pages viewed, buttons pressed (an Apply click, for example)\n- category: device\n  text: the browser and device you use\n- category: professional\n  text: your work history with its dates, education, certifications, languages and skills\n- category: communication\n  text: Conversations with the assistant in your account are stored with the account, so it can pick up where you\n    left off.\npurposes:\n- purpose: run the board\n  text: 'To run the board: show open sales roles, keep your account, send the alerts and emails you asked for, and\n    pass you to an employer''s own application page when you press Apply.'\n- purpose: match you\n  text: 'To match you: rank openings against your profile and say how well a given role fits.'\n- purpose: improve features\n  text: To learn which pages and features help people land sales jobs, so we can improve them.\nretention:\n- scope: general\n  period: null\n\
  \  text: Data stays only as long as the purpose it was collected for, plus any longer period the law sets or allows\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: such as the European Commission's standard contractual clauses\n- mechanism: adequacy\n  text: an adequacy decision\nsubprocessors:\n  url: null\n  text: 'Companies that run parts of the Service for us: hosting and database, email delivery, the AI models that\n    read profiles and searches, our profile data provider and our voice provider.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion steps\n  text: To close your account and see exactly what goes with it, read the account deletion steps.\nrights:\n- right: access\n  text: See whether we process your data, and get a copy of it.\n- right: erase\n  text: Erase it, in the cases the law allows.\n- right: object\n  text: Object to processing, including any based on legitimate interests and any for direct marketing.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We never sell your data.\n"
source_yaml_url: https://artifacts.apis.io/salesjobs-now/privacy/salesjobs-now-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from SalesJobs.Now's own page on 2026-11-10.
synthetic: false
tags:
- Sales
- Job
- Recruiting
- Data
---
