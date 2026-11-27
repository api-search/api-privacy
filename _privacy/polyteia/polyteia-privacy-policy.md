---
api_specs:
- filename: polyteia-organization-api-openapi.yml
  format: yaml
  label: Polyteia Organization API
  slug: polyteia-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polyteia/openapi/polyteia-organization-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name Last name Institution Email address
  - category: contact
    text: Address Phone number Email
  - category: device
    text: identification data of the browser and operating system used
  - category: location
    text: Geographical location
  - category: behavioral
    text: Pages visited
  deletion:
    route: Email request
    text: If you wish to permanently unsubscribe from the protected area, please send us an email to support@polyteia.de .
  dpa:
    available: true
    text: We have concluded a data processing agreement with T-Systems in accordance with Art. 28 GDPR.
    url: null
  purposes:
  - purpose: Respond to inquiries
    text: We use this data on the basis of Art. 6 para. 1 lit. f GDPR to respond to your inquiry.
  - purpose: Newsletter delivery and recipient profiling
    text: we conduct analyses, individual measurements, storage, and evaluation of open rates and click-through rates in recipient profiles.
  - purpose: Website analysis
    text: We use HubSpot to analyze the use of our website.
  - purpose: Server error and abuse analysis
    text: We process this data to analyze server errors and attempted abuses.
  residency:
  - region: Germany
    text: The servers are located in data centers in Germany.
  - region: EU (Datadog)
    text: The data is stored in Datadog's EU region.
  retention:
  - period: 15 days
    scope: Server log files
    text: Log data is regularly deleted promptly, but no later than after 15 days.
  - period: 90 days
    scope: Online application data
    text: If no employment is offered, your personal data or application documents will be deleted 90 days after the end of the application process
  - period: 14-day trial access period
    scope: Trial account data
    text: If no permanent business relationship with Polyteia GmbH has been established after the 14-day trial access period, your data, including all data created by you during the trial access, will be deleted from the Polyteia database.
  rights:
  - right: Access
    text: According to Art. 15 of the EU GDPR, you have the right to request confirmation from us whether personal data concerning you are being processed.
  - right: Rectification
    text: According to Art. 16 of the EU GDPR, you have the right to immediately request the correction of incorrect personal data concerning you.
  - right: Erasure
    text: According to Art. 17 of the EU GDPR, you have the right to demand that personal data concerning you be deleted without delay.
  - right: Restriction of processing
    text: According to Art. 18 of the EU GDPR, you have the right to demand from us the restriction of processing if one of the conditions mentioned in Art. 18 of the EU GDPR applies.
  - right: Portability
    text: According to Art. 20 of the EU GDPR, you have the right to receive the personal data concerning you, which you have provided to us, in a structured, commonly used, and machine-readable format.
  - right: Object
    text: According to Art. 21 of the EU GDPR, you have the right to object at any time to the processing of personal data concerning you
  - right: Withdraw consent
    text: According to Art. 7 para. 3 of the EU GDPR, you have the right to withdraw your consent to the processing at any time.
  - right: Complaint to supervisory authority
    text: According to Art. 77 of the EU GDPR, without prejudice to any other administrative or judicial remedy, you have the right to lodge a complaint with a supervisory authority
  role:
    text: Polyteia GmbH is responsible for the data processing described below in accordance with data protection regulations.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: HubSpot Inc. is certified under the EU-US Data Privacy Framework.
  - mechanism: SCC
    text: which includes the EU Standard Contractual Clauses for any access from third countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Polyteia
provenance_date: '2026-11-10'
provider_name: Polyteia
provider_slug: polyteia
slug: polyteia-privacy-policy
source_date: '2026-11-10'
source_filename: polyteia-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.polyteia.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Polyteia\naid: polyteia\nurl: https://www.polyteia.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Polyteia GmbH is responsible for the data processing described below in accordance with data protection\n    regulations.\ndata_categories:\n- category: identifying\n  text: First name Last name Institution Email address\n- category: contact\n  text: Address Phone number Email\n- category: device\n  text: identification data of the browser and operating system used\n- category: location\n  text: Geographical location\n- category: behavioral\n  text: Pages visited\npurposes:\n\
  - purpose: Respond to inquiries\n  text: We use this data on the basis of Art. 6 para. 1 lit. f GDPR to respond to your inquiry.\n- purpose: Newsletter delivery and recipient profiling\n  text: we conduct analyses, individual measurements, storage, and evaluation of open rates and click-through rates\n    in recipient profiles.\n- purpose: Website analysis\n  text: We use HubSpot to analyze the use of our website.\n- purpose: Server error and abuse analysis\n  text: We process this data to analyze server errors and attempted abuses.\nretention:\n- scope: Server log files\n  period: 15 days\n  text: Log data is regularly deleted promptly, but no later than after 15 days.\n- scope: Online application data\n  period: 90 days\n  text: If no employment is offered, your personal data or application documents will be deleted 90 days after the\n    end of the application process\n- scope: Trial account data\n  period: 14-day trial access period\n  text: If no permanent business relationship with\
  \ Polyteia GmbH has been established after the 14-day trial access\n    period, your data, including all data created by you during the trial access, will be deleted from the Polyteia\n    database.\nresidency:\n- region: Germany\n  text: The servers are located in data centers in Germany.\n- region: EU (Datadog)\n  text: The data is stored in Datadog's EU region.\ntransfers:\n- mechanism: DPF\n  text: HubSpot Inc. is certified under the EU-US Data Privacy Framework.\n- mechanism: SCC\n  text: which includes the EU Standard Contractual Clauses for any access from third countries.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We have concluded a data processing agreement with T-Systems in accordance with Art. 28 GDPR.\ndeletion:\n  route: Email request\n  text: If you wish to permanently unsubscribe from the protected area, please send us an email to support@polyteia.de\n    .\nrights:\n- right: Access\n  text: According to Art. 15 of the EU GDPR,\
  \ you have the right to request confirmation from us whether personal\n    data concerning you are being processed.\n- right: Rectification\n  text: According to Art. 16 of the EU GDPR, you have the right to immediately request the correction of incorrect\n    personal data concerning you.\n- right: Erasure\n  text: According to Art. 17 of the EU GDPR, you have the right to demand that personal data concerning you be deleted\n    without delay.\n- right: Restriction of processing\n  text: According to Art. 18 of the EU GDPR, you have the right to demand from us the restriction of processing\n    if one of the conditions mentioned in Art. 18 of the EU GDPR applies.\n- right: Portability\n  text: According to Art. 20 of the EU GDPR, you have the right to receive the personal data concerning you, which\n    you have provided to us, in a structured, commonly used, and machine-readable format.\n- right: Object\n  text: According to Art. 21 of the EU GDPR, you have the right to object at any\
  \ time to the processing of personal\n    data concerning you\n- right: Withdraw consent\n  text: According to Art. 7 para. 3 of the EU GDPR, you have the right to withdraw your consent to the processing\n    at any time.\n- right: Complaint to supervisory authority\n  text: According to Art. 77 of the EU GDPR, without prejudice to any other administrative or judicial remedy, you\n    have the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/polyteia/privacy/polyteia-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Polyteia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- GovTech
- Public Sector
- Data Platform
- Government
- Data Analytics
- Germany
- Business Intelligence
- No-Code
---
