---
api_specs:
- filename: rows-data-api-openapi.yml
  format: yaml
  label: Rows Data API
  slug: rows-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-data-api-openapi.yml
- filename: rows-folders-api-openapi.yml
  format: yaml
  label: Rows Folders API
  slug: rows-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-folders-api-openapi.yml
- filename: rows-spreadsheets-api-openapi.yml
  format: yaml
  label: Rows Spreadsheets API
  slug: rows-spreadsheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-spreadsheets-api-openapi.yml
- filename: rows-vision-api-openapi.yml
  format: yaml
  label: Rows Vision API
  slug: rows-vision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-vision-api-openapi.yml
- filename: rows-workspaces-api-openapi.yml
  format: yaml
  label: Rows Workspaces API
  slug: rows-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-workspaces-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Customer Account Data: information (First name, Last name, Email address, ....), you input at our request to set up and manage your account.'
  - category: device
    text: Browser type and version used Operating system of your device Your internet service provider Your IP address and country
  - category: financial
    text: Credit card number Credit card validity period Card validation code (CVC) IP address of the user's device
  - category: behavioral
    text: Entered search queries Frequency of page views Use of website functionalities
  deletion:
    route: Email privacy@rows.com
    text: You can send an informal email to privacy@rows.com to have the stored data changed or your account deleted at any time.
  dpa:
    available: true
    text: If you need a Data Processing Agreement with us, please find the already signed version here .
    url: null
  purposes:
  - purpose: Delivery and security of website
    text: We also use it to optimize the website and to ensure the security of our IT systems.
  - purpose: Payment processing
    text: The transmission of payment data to payment service providers serves to process payments, e.g. if you purchase a product and/or use a service.
  - purpose: AI data analysis
    text: The purpose of the data processing is to help you analyze your data and build your spreadsheets with higher productivity.
  residency:
  - region: European Union or EEA
    text: The server of the website is geographically located in the European Union (EU) or the European Economic Area (EEA).
  retention:
  - period: seven days
    scope: IP address in log files
    text: If we store your IP address in log files, this is the case after seven days at the latest.
  - period: 10 years
    scope: Payment data
    text: Your personal data will be deleted at the end of the statutory retention period, i.e. after 10 years at the latest.
  - period: 6 months
    scope: Email contact data
    text: For personal data sent by email, this is the case 6 months after the respective conversation with the user has ended.
  - period: six months
    scope: Job application data
    text: After completion of the application procedure, we will store the data for up to six months.
  - period: up to 30 days
    scope: OpenAI AI Analyst data
    text: OpenAI may store the data for up to 30 days. Groq does not retain your data after processing.
  rights:
  - right: Information
    text: You may request us, the data controller, to confirm whether your personal data is processed by us.
  - right: Rectification
    text: You have a right to rectification and/or modification of your personal data we process if it is incorrect or incomplete.
  - right: Erasure
    text: If you request us to delete your personal data without undue delay, we are required to do so immediately if one of the following applies
  - right: Restriction of processing
    text: You may request the restriction of the processing of your personal data under the following conditions
  - right: Data portability
    text: You have the right to receive your personal data given to us, the data controller, in a structured and machine-readable format.
  - right: Object
    text: you have, at any time, the right to object to the processing of your personal data pursuant to Art. 6 (1) (1) (e) or 6 (1) (1) (f) GDPR
  - right: Withdraw consent
    text: You have the right to withdraw your consent at any time.
  - right: Complain to supervisory authority
    text: you shall have the right to complain to a supervisory authority
  role:
    text: 'The responsible data controller in accordance with the purposes of the General Data Protection Regulation (GDPR) of the European Union and other data protection regulations is: Rows GmbH'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Hotjar is contractually forbidden to sell any of the data collected on our behalf.
  subprocessors:
    text: Our service provider is Google Cloud Platform.
    url: null
  transfers:
  - mechanism: SCC
    text: Part of the data processing agreement with Peaberry are so-called standard data protection clauses (Art. 46 (2) (c) GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rows
provenance_date: '2026-11-10'
provider_name: Rows
provider_slug: rows
slug: rows-privacy-policy
source_date: '2026-11-10'
source_filename: rows-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rows.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rows\naid: rows\nurl: https://rows.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The responsible data controller in accordance with the purposes of the General Data Protection Regulation\n    (GDPR) of the European Union and other data protection regulations is: Rows GmbH'\ndata_categories:\n- category: identifying\n  text: 'Customer Account Data: information (First name, Last name, Email address, ....), you input at our request\n    to set up and manage your account.'\n- category: device\n  text: Browser type and version used Operating system of your device Your internet service\
  \ provider Your IP address\n    and country\n- category: financial\n  text: Credit card number Credit card validity period Card validation code (CVC) IP address of the user's device\n- category: behavioral\n  text: Entered search queries Frequency of page views Use of website functionalities\npurposes:\n- purpose: Delivery and security of website\n  text: We also use it to optimize the website and to ensure the security of our IT systems.\n- purpose: Payment processing\n  text: The transmission of payment data to payment service providers serves to process payments, e.g. if you purchase\n    a product and/or use a service.\n- purpose: AI data analysis\n  text: The purpose of the data processing is to help you analyze your data and build your spreadsheets with higher\n    productivity.\nretention:\n- scope: IP address in log files\n  period: seven days\n  text: If we store your IP address in log files, this is the case after seven days at the latest.\n- scope: Payment data\n  period: 10\
  \ years\n  text: Your personal data will be deleted at the end of the statutory retention period, i.e. after 10 years at\n    the latest.\n- scope: Email contact data\n  period: 6 months\n  text: For personal data sent by email, this is the case 6 months after the respective conversation with the user\n    has ended.\n- scope: Job application data\n  period: six months\n  text: After completion of the application procedure, we will store the data for up to six months.\n- scope: OpenAI AI Analyst data\n  period: up to 30 days\n  text: OpenAI may store the data for up to 30 days. Groq does not retain your data after processing.\nresidency:\n- region: European Union or EEA\n  text: The server of the website is geographically located in the European Union (EU) or the European Economic\n    Area (EEA).\ntransfers:\n- mechanism: SCC\n  text: Part of the data processing agreement with Peaberry are so-called standard data protection clauses (Art.\n    46 (2) (c) GDPR).\nsubprocessors:\n  url:\
  \ null\n  text: Our service provider is Google Cloud Platform.\ndpa:\n  available: true\n  url: null\n  text: If you need a Data Processing Agreement with us, please find the already signed version here .\ndeletion:\n  route: Email privacy@rows.com\n  text: You can send an informal email to privacy@rows.com to have the stored data changed or your account deleted\n    at any time.\nrights:\n- right: Information\n  text: You may request us, the data controller, to confirm whether your personal data is processed by us.\n- right: Rectification\n  text: You have a right to rectification and/or modification of your personal data we process if it is incorrect\n    or incomplete.\n- right: Erasure\n  text: If you request us to delete your personal data without undue delay, we are required to do so immediately\n    if one of the following applies\n- right: Restriction of processing\n  text: You may request the restriction of the processing of your personal data under the following conditions\n\
  - right: Data portability\n  text: You have the right to receive your personal data given to us, the data controller, in a structured and machine-readable\n    format.\n- right: Object\n  text: you have, at any time, the right to object to the processing of your personal data pursuant to Art. 6 (1)\n    (1) (e) or 6 (1) (1) (f) GDPR\n- right: Withdraw consent\n  text: You have the right to withdraw your consent at any time.\n- right: Complain to supervisory authority\n  text: you shall have the right to complain to a supervisory authority\nsale_or_sharing:\n  stance: conditional\n  text: Hotjar is contractually forbidden to sell any of the data collected on our behalf.\n"
source_yaml_url: https://artifacts.apis.io/rows/privacy/rows-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Rows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Spreadsheets
- Data
- No-Code
- Automation
- Artificial Intelligence
- Analytics
- Business Intelligence
---
