---
api_specs:
- filename: riot-awareness-api-openapi.yml
  format: yaml
  label: Riot Awareness API
  slug: riot-awareness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-awareness-api-openapi.yml
- filename: riot-breaches-api-openapi.yml
  format: yaml
  label: Riot Breaches API
  slug: riot-breaches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-breaches-api-openapi.yml
- filename: riot-general-api-openapi.yml
  format: yaml
  label: Riot General API
  slug: riot-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-general-api-openapi.yml
- filename: riot-groups-api-openapi.yml
  format: yaml
  label: Riot Groups API
  slug: riot-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-groups-api-openapi.yml
- filename: riot-inbox-api-openapi.yml
  format: yaml
  label: Riot Inbox API
  slug: riot-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-inbox-api-openapi.yml
- filename: riot-scim-api-openapi.yml
  format: yaml
  label: Riot SCIM API
  slug: riot-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-scim-api-openapi.yml
- filename: riot-simulation-api-openapi.yml
  format: yaml
  label: Riot Simulation API
  slug: riot-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-simulation-api-openapi.yml
- filename: riot-slash-api-openapi.yml
  format: yaml
  label: Riot Slash API
  slug: riot-slash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-slash-api-openapi.yml
- filename: riot-sonar-api-openapi.yml
  format: yaml
  label: Riot Sonar API
  slug: riot-sonar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/riot/openapi/riot-sonar-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name, last name, photography
  - category: contact
    text: Email addresses, phone numbers
  - category: professional
    text: Company, position, LinkedIn URL, seniority
  - category: device
    text: Date and time of the connection, IP address, device type, browser type, operating system, location, viewed pages, session records, Solution logs
  - category: behavioral
    text: Email opening (date, time of opening and number of times opened), clicks on a link in the email (date and time of click)
  - category: communication
    text: voice and video recordings and content of your exchanges with the internal services of Riot Security
  deletion:
    route: Email to dpo@tryriot.com or contact employer
    text: you can request the deletion of your personal data (or right to be forgotten)
  dpa:
    available: true
    text: More information about the safeguards that have been implemented to protect transfers of personal data is available in the Data Processing Agreement .
    url: null
  purposes:
  - purpose: Booking demos and processing contact requests
    text: Booking a demo of the Riot Solution
  - purpose: Sales and marketing communications
    text: Sending sales and marketing communications to send you communications about the business activities and services of Riot Security that might interest you
  - purpose: Managing job applications
    text: Managing your job application
  - purpose: Improving the Website and services
    text: Improving the Website, the Cybersecurity Services, as well as your user experience
  - purpose: Provision of Cybersecurity Services as processor
    text: Provision of the Cybersecurity Services subscribed by your employer
  - purpose: Billing and contract management
    text: Billing and contract management
  residency:
  - region: EU/EEA
    text: As far as possible, your personal data is processed within the European Union (EU)/European Economic Area (EEA) .
  retention:
  - period: three (3) year
    scope: Demo data
    text: the data collected in case of a demo of the Riot Solution during three (3) year for directing marketing
  - period: two (2) years
    scope: Job application data
    text: the data collected in the context of your application to a job offer is store during two (2) years as from your last contact with Riot Security
  - period: thirteen (13) months
    scope: Traffic data
    text: your traffic data will be kept for a period up to thirteen (13) months from their collection
  - period: one (1) year
    scope: Riot Solution data as processor
    text: Beyond, and in the absence of shorter or longer periods specifically provided for, this data is stored during one (1) year, deleted upon request or anonymized.
  rights:
  - right: Access
    text: you can request access to your personal data
  - right: Rectification
    text: you can request the rectification of your personal data
  - right: Objection
    text: you can object to the processing of your personal data when the processing is based on legitimate interest.
  - right: Restriction
    text: you can request the restriction of the processing during a limited period of time
  - right: Withdraw consent
    text: you can withdraw your consent when it has been obtained
  - right: Portability
    text: you can ask to receive your personal data in a structured, commonly used and machine-readable format
  - right: Erasure
    text: you can request the deletion of your personal data (or right to be forgotten)
  role:
    text: Riot Security is the data controller of personal data collected and processed for the administrative, operational and commercial management of the Website as publisher.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Riot Security complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework
  - mechanism: SCC
    text: implement all necessary measures through the adoption of appropriate safeguards (such as standard contractual clauses)
  - mechanism: adequacy
    text: Adequacy decision
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Riot
provenance_date: '2026-11-10'
provider_name: Riot
provider_slug: riot
slug: riot-privacy-policy
source_date: '2026-11-10'
source_filename: riot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tryriot.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Riot\naid: riot\nurl: https://tryriot.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Riot Security is the data controller of personal data collected and processed for the administrative, operational\n    and commercial management of the Website as publisher.\ndata_categories:\n- category: identifying\n  text: First name, last name, photography\n- category: contact\n  text: Email addresses, phone numbers\n- category: professional\n  text: Company, position, LinkedIn URL, seniority\n- category: device\n  text: Date and time of the connection, IP address, device type, browser type, operating\
  \ system, location, viewed\n    pages, session records, Solution logs\n- category: behavioral\n  text: Email opening (date, time of opening and number of times opened), clicks on a link in the email (date and\n    time of click)\n- category: communication\n  text: voice and video recordings and content of your exchanges with the internal services of Riot Security\npurposes:\n- purpose: Booking demos and processing contact requests\n  text: Booking a demo of the Riot Solution\n- purpose: Sales and marketing communications\n  text: Sending sales and marketing communications to send you communications about the business activities and\n    services of Riot Security that might interest you\n- purpose: Managing job applications\n  text: Managing your job application\n- purpose: Improving the Website and services\n  text: Improving the Website, the Cybersecurity Services, as well as your user experience\n- purpose: Provision of Cybersecurity Services as processor\n  text: Provision of the Cybersecurity\
  \ Services subscribed by your employer\n- purpose: Billing and contract management\n  text: Billing and contract management\nretention:\n- scope: Demo data\n  period: three (3) year\n  text: the data collected in case of a demo of the Riot Solution during three (3) year for directing marketing\n- scope: Job application data\n  period: two (2) years\n  text: the data collected in the context of your application to a job offer is store during two (2) years as from\n    your last contact with Riot Security\n- scope: Traffic data\n  period: thirteen (13) months\n  text: your traffic data will be kept for a period up to thirteen (13) months from their collection\n- scope: Riot Solution data as processor\n  period: one (1) year\n  text: Beyond, and in the absence of shorter or longer periods specifically provided for, this data is stored during\n    one (1) year, deleted upon request or anonymized.\nresidency:\n- region: EU/EEA\n  text: As far as possible, your personal data is processed within\
  \ the European Union (EU)/European Economic Area\n    (EEA) .\ntransfers:\n- mechanism: DPF\n  text: Riot Security complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the\n    EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework\n- mechanism: SCC\n  text: implement all necessary measures through the adoption of appropriate safeguards (such as standard contractual\n    clauses)\n- mechanism: adequacy\n  text: Adequacy decision\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: More information about the safeguards that have been implemented to protect transfers of personal data is\n    available in the Data Processing Agreement .\ndeletion:\n  route: Email to dpo@tryriot.com or contact employer\n  text: you can request the deletion of your personal data (or right to be forgotten)\nrights:\n- right: Access\n  text: you can request access to your personal data\n- right: Rectification\n  text: you can request the rectification\
  \ of your personal data\n- right: Objection\n  text: you can object to the processing of your personal data when the processing is based on legitimate interest.\n- right: Restriction\n  text: you can request the restriction of the processing during a limited period of time\n- right: Withdraw consent\n  text: you can withdraw your consent when it has been obtained\n- right: Portability\n  text: you can ask to receive your personal data in a structured, commonly used and machine-readable format\n- right: Erasure\n  text: you can request the deletion of your personal data (or right to be forgotten)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/riot/privacy/riot-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Riot's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Security Awareness
- Human Risk Management
- Phishing Simulation
- employee-security
- Security Posture Management
- breach-detection
- Email Security
- SaaS Security
- SCIM
- Webhook
- OCSF
- France
---
