---
api_specs:
- filename: priorlabs-prediction-api-openapi.yml
  format: yaml
  label: Prior Labs Prediction API
  slug: priorlabs-prediction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/priorlabs/openapi/priorlabs-prediction-api-openapi.yml
- filename: priorlabs-training-api-openapi.yml
  format: yaml
  label: Prior Labs Training API
  slug: priorlabs-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/priorlabs/openapi/priorlabs-training-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: First and last name
  - category: contact
    text: E-mail address
  - category: device
    text: Browser type and version. The specific type and model of Internet browser you are using
  - category: location
    text: IP address of the requesting computer.
  - category: communication
    text: Transcripts and summaries of the communication content
  - category: professional
    text: Employer and company role, where voluntarily provided by the user
  deletion:
    route: Email to dataprotection@priorlabs.ai
    text: You can delete your user account at any time by sending an e-mail with your request to dataprotection@priorlabs.ai.
  dpa:
    available: true
    text: We have concluded a data processing agreement according to Art. 28 GDPR or EU standard contractual clauses of the EU Commission pursuant to Art. 46 para. 2 lit. c GDPR with each service provider
    url: null
  purposes:
  - purpose: Website operation and security
    text: to be able to provide you with technically functional, attractive and user-friendly Website as well as to ensure the security of our systems
  - purpose: User account creation
    text: We process the aforementioned information to create your user account
  - purpose: Service operation and error detection
    text: for the operation of our Services, including general service operation purposes as well as the detection, analysis and resolution of errors and performance issues
  - purpose: Newsletter
    text: to send you a newsletter via e-mail that contains information about our products and services
  residency:
  - region: Germany and EEA
    text: Your personal data is generally processed in Germany and other countries within the European Economic Area (EEA).
  retention:
  - period: 14 calendar days
    scope: Log files
    text: For personal data stored in log files, this is the case after 14 calendar days at the latest.
  - period: 90 calendar days
    scope: Usage data
    text: Usage data processed is regularly deleted after 90 calendar days, at the latest.
  - period: 3 years
    scope: User accounts
    text: In any event, we will delete your user account when it has been inactive for 3 years.
  - period: null
    scope: Call audio
    text: The audio is deleted as soon as the transcript is created.
  rights:
  - right: Access
    text: Under the conditions of Art. 15 GDPR you have the right to request confirmation from us at any time as to whether we are processing personal data relating to you.
  - right: Rectification
    text: Under the conditions of Art. 16 GDPR you have the right to request us to correct the personal data stored about you if it is inaccurate or incomplete.
  - right: Erasure
    text: You have the right, under the conditions of Art. 17 GDPR, to demand that we delete the personal data concerning you without delay.
  - right: Restriction
    text: You have the right to request that we restrict the processing of your personal data under the conditions of Art. 18 GDPR.
  - right: Portability
    text: You have the right, under the conditions of Art. 20 GDPR, to request that we hand over, in a structured, common and machine-readable format
  - right: Object
    text: You have the right to object to the processing of your personal data under the conditions of Art. 21 GDPR.
  - right: Withdraw consent
    text: You may revoke your consent to the processing of your personal data at any time pursuant to Art. 7 para. 3 GDPR.
  - right: Complain to supervisory authority
    text: you have the right to file a complaint with a competent supervisory authority.
  role:
    text: Prior Labs acts as a controller within the meaning of the GDPR in relation to your personal data processed in connection with the use of our Website, Service or a contact made to or by Prior Labs.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: If possible, we conclude the currently applicable EU standard contractual clauses of the EU Commission pursuant to Art. 46 para. 2 lit. c GDPR with all processors located outside the EEA.
  - mechanism: adequacy
    text: we ensure that a transfer only takes place if an adequacy decision exists with the respective third country and the recipient is certified under this, if necessary.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Prior Labs
provenance_date: '2026-11-10'
provider_name: Prior Labs
provider_slug: priorlabs
slug: priorlabs-privacy-policy
source_date: '2026-11-10'
source_filename: priorlabs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://priorlabs.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Prior Labs\naid: priorlabs\nurl: https://priorlabs.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Prior Labs acts as a controller within the meaning of the GDPR in relation to your personal data processed\n    in connection with the use of our Website, Service or a contact made to or by Prior Labs.\ndata_categories:\n- category: identifying\n  text: First and last name\n- category: contact\n  text: E-mail address\n- category: device\n  text: Browser type and version. The specific type and model of Internet browser you are using\n- category: location\n  text: IP address of\
  \ the requesting computer.\n- category: communication\n  text: Transcripts and summaries of the communication content\n- category: professional\n  text: Employer and company role, where voluntarily provided by the user\npurposes:\n- purpose: Website operation and security\n  text: to be able to provide you with technically functional, attractive and user-friendly Website as well as to\n    ensure the security of our systems\n- purpose: User account creation\n  text: We process the aforementioned information to create your user account\n- purpose: Service operation and error detection\n  text: for the operation of our Services, including general service operation purposes as well as the detection,\n    analysis and resolution of errors and performance issues\n- purpose: Newsletter\n  text: to send you a newsletter via e-mail that contains information about our products and services\nretention:\n- scope: Log files\n  period: 14 calendar days\n  text: For personal data stored in log files,\
  \ this is the case after 14 calendar days at the latest.\n- scope: Usage data\n  period: 90 calendar days\n  text: Usage data processed is regularly deleted after 90 calendar days, at the latest.\n- scope: User accounts\n  period: 3 years\n  text: In any event, we will delete your user account when it has been inactive for 3 years.\n- scope: Call audio\n  period: null\n  text: The audio is deleted as soon as the transcript is created.\nresidency:\n- region: Germany and EEA\n  text: Your personal data is generally processed in Germany and other countries within the European Economic Area\n    (EEA).\ntransfers:\n- mechanism: SCC\n  text: If possible, we conclude the currently applicable EU standard contractual clauses of the EU Commission pursuant\n    to Art. 46 para. 2 lit. c GDPR with all processors located outside the EEA.\n- mechanism: adequacy\n  text: we ensure that a transfer only takes place if an adequacy decision exists with the respective third country\n    and the recipient\
  \ is certified under this, if necessary.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We have concluded a data processing agreement according to Art. 28 GDPR or EU standard contractual clauses\n    of the EU Commission pursuant to Art. 46 para. 2 lit. c GDPR with each service provider\ndeletion:\n  route: Email to dataprotection@priorlabs.ai\n  text: You can delete your user account at any time by sending an e-mail with your request to dataprotection@priorlabs.ai.\nrights:\n- right: Access\n  text: Under the conditions of Art. 15 GDPR you have the right to request confirmation from us at any time as to\n    whether we are processing personal data relating to you.\n- right: Rectification\n  text: Under the conditions of Art. 16 GDPR you have the right to request us to correct the personal data stored\n    about you if it is inaccurate or incomplete.\n- right: Erasure\n  text: You have the right, under the conditions of Art. 17 GDPR, to demand\
  \ that we delete the personal data concerning\n    you without delay.\n- right: Restriction\n  text: You have the right to request that we restrict the processing of your personal data under the conditions\n    of Art. 18 GDPR.\n- right: Portability\n  text: You have the right, under the conditions of Art. 20 GDPR, to request that we hand over, in a structured,\n    common and machine-readable format\n- right: Object\n  text: You have the right to object to the processing of your personal data under the conditions of Art. 21 GDPR.\n- right: Withdraw consent\n  text: You may revoke your consent to the processing of your personal data at any time pursuant to Art. 7 para.\n    3 GDPR.\n- right: Complain to supervisory authority\n  text: you have the right to file a complaint with a competent supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/priorlabs/privacy/priorlabs-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 28 quoted statements, read from Prior Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Machine Learning
- Artificial Intelligence
- Tabular Data
- Foundation Models
- Predictions
- Data Science
- MCP
- SDK
---
