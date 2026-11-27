---
api_specs:
- filename: getdynamiq-api-reference-openapi-generated.yml
  format: yaml
  label: Dynamiq API Reference API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getdynamiq/openapi/_ae-authored/getdynamiq-api-reference-openapi-generated.yml
- filename: getdynamiq-platform-openapi-generated.yml
  format: yaml
  label: Dynamiq Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getdynamiq/openapi/_ae-authored/getdynamiq-platform-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information : When you sign up for an account or subscribe to our Services, we collect information such as your name, email address, billing details, and any other necessary fields.'
  - category: device
    text: This includes IP addresses, browser types, referring pages, and other device identifiers.
  - category: communication
    text: 'Communications : We may collect information when you contact us by email, support tickets, or other channels, including chat logs, feedback, or requests.'
  - category: health
    text: In cases where our Services process PHI on behalf of healthcare providers or other Covered Entities, we adhere to HIPAA requirements
  deletion:
    route: Email legal@getdynamiq.ai to request deletion of Microsoft Teams data
    text: To request deletion of Microsoft Teams data, contact legal@getdynamiq.ai .
  dpa:
    available: true
    text: our data processing is governed by contractual agreements (e.g., Data Processing Addendum, Business Associate Agreement ).
    url: null
  purposes:
  - purpose: Provide, maintain and improve Services
    text: To provide, maintain, troubleshoot, secure, and improve the Services.
  - purpose: Account management and billing
    text: To manage user accounts, process billing, and handle customer support.
  - purpose: Security and fraud prevention
    text: To monitor, detect, and protect against fraudulent or malicious activities.
  - purpose: Aggregated analytics
    text: To analyze trends, usage, and activities in connection with our Services, in an anonymized or aggregated manner.
  retention:
  - period: null
    scope: Personal data
    text: We retain personal data only for as long as necessary to fulfill the purposes for which it was collected or to comply with applicable legal obligations, contractual requirements, or legitimate business interests.
  - period: null
    scope: Google Workspace API data
    text: Google Workspace API data is retained only as long as necessary to provide the Services or to comply with applicable legal obligations.
  - period: one hour
    scope: Microsoft Teams files created by Wilson in channels and group chats
    text: In channels and group chats, these are shared as download links that expire after one hour.
  rights:
  - right: Access
    text: 'Right of Access : The right to request confirmation of whether we process your personal data and a copy of such data.'
  - right: Rectification
    text: 'Right to Rectification : The right to request correction of inaccurate or incomplete data.'
  - right: Erasure
    text: 'Right to Erasure (“Right to be Forgotten”) : The right to request the deletion of your personal data, subject to certain exceptions.'
  - right: Restrict processing
    text: 'Right to Restrict Processing : The right to request the restriction of certain processing activities.'
  - right: Portability
    text: 'Right to Data Portability : The right to receive your personal data in a structured, commonly used, machine-readable format.'
  - right: Object
    text: 'Right to Object : The right to object to processing of your personal data, including for direct marketing.'
  - right: Lodge a complaint
    text: 'Right to Lodge a Complaint : If you are in the EU/EEA, you have the right to lodge a complaint with your local supervisory authority.'
  role:
    text: Where we process personal data on behalf of a customer who is subject to GDPR or HIPAA, we act as a Data Processor or Business Associate (as applicable).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Google Workspace API data is never sold and is never used for advertising, marketing, profiling, or any unrelated secondary purpose.
  subprocessors:
    text: 'Sub-processor List : We maintain a public list of the third-party sub-processors we engage to process personal data on our behalf.'
    url: null
  transfers:
  - mechanism: SCC
    text: If we transfer personal data outside of the European Economic Area (EEA) to countries that may not provide the same level of data protection as your home jurisdiction, we implement appropriate safeguards, such as Standard Contractual Clauses (SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dynamiq
provenance_date: '2026-11-09'
provider_name: Dynamiq
provider_slug: getdynamiq
slug: getdynamiq-privacy-policy
source_date: '2026-11-09'
source_filename: getdynamiq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.getdynamiq.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dynamiq\naid: getdynamiq\nurl: https://www.getdynamiq.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where we process personal data on behalf of a customer who is subject to GDPR or HIPAA, we act as a Data\n    Processor or Business Associate (as applicable).\ndata_categories:\n- category: identifying\n  text: 'Account Information : When you sign up for an account or subscribe to our Services, we collect information\n    such as your name, email address, billing details, and any other necessary fields.'\n- category: device\n  text: This includes IP addresses, browser types, referring\
  \ pages, and other device identifiers.\n- category: communication\n  text: 'Communications : We may collect information when you contact us by email, support tickets, or other channels,\n    including chat logs, feedback, or requests.'\n- category: health\n  text: In cases where our Services process PHI on behalf of healthcare providers or other Covered Entities, we\n    adhere to HIPAA requirements\npurposes:\n- purpose: Provide, maintain and improve Services\n  text: To provide, maintain, troubleshoot, secure, and improve the Services.\n- purpose: Account management and billing\n  text: To manage user accounts, process billing, and handle customer support.\n- purpose: Security and fraud prevention\n  text: To monitor, detect, and protect against fraudulent or malicious activities.\n- purpose: Aggregated analytics\n  text: To analyze trends, usage, and activities in connection with our Services, in an anonymized or aggregated\n    manner.\nretention:\n- scope: Personal data\n  period:\
  \ null\n  text: We retain personal data only for as long as necessary to fulfill the purposes for which it was collected\n    or to comply with applicable legal obligations, contractual requirements, or legitimate business interests.\n- scope: Google Workspace API data\n  period: null\n  text: Google Workspace API data is retained only as long as necessary to provide the Services or to comply with\n    applicable legal obligations.\n- scope: Microsoft Teams files created by Wilson in channels and group chats\n  period: one hour\n  text: In channels and group chats, these are shared as download links that expire after one hour.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: If we transfer personal data outside of the European Economic Area (EEA) to countries that may not provide\n    the same level of data protection as your home jurisdiction, we implement appropriate safeguards, such as Standard\n    Contractual Clauses (SCCs)\nsubprocessors:\n  url: null\n  text: 'Sub-processor\
  \ List : We maintain a public list of the third-party sub-processors we engage to process personal\n    data on our behalf.'\ndpa:\n  available: true\n  url: null\n  text: our data processing is governed by contractual agreements (e.g., Data Processing Addendum, Business Associate\n    Agreement ).\ndeletion:\n  route: Email legal@getdynamiq.ai to request deletion of Microsoft Teams data\n  text: To request deletion of Microsoft Teams data, contact legal@getdynamiq.ai .\nrights:\n- right: Access\n  text: 'Right of Access : The right to request confirmation of whether we process your personal data and a copy\n    of such data.'\n- right: Rectification\n  text: 'Right to Rectification : The right to request correction of inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Right to Erasure (“Right to be Forgotten”) : The right to request the deletion of your personal data, subject\n    to certain exceptions.'\n- right: Restrict processing\n  text: 'Right to Restrict Processing : The\
  \ right to request the restriction of certain processing activities.'\n- right: Portability\n  text: 'Right to Data Portability : The right to receive your personal data in a structured, commonly used, machine-readable\n    format.'\n- right: Object\n  text: 'Right to Object : The right to object to processing of your personal data, including for direct marketing.'\n- right: Lodge a complaint\n  text: 'Right to Lodge a Complaint : If you are in the EU/EEA, you have the right to lodge a complaint with your\n    local supervisory authority.'\nsale_or_sharing:\n  stance: prohibited\n  text: Google Workspace API data is never sold and is never used for advertising, marketing, profiling, or any\n    unrelated secondary purpose.\n"
source_yaml_url: https://artifacts.apis.io/getdynamiq/privacy/getdynamiq-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Dynamiq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Platform
- Agents
---
