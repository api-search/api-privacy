---
api_specs:
- filename: alpic-analytics-api-openapi.yml
  format: yaml
  label: Alpic Analytics API
  slug: alpic-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-analytics-api-openapi.yml
- filename: alpic-beacon-api-openapi.yml
  format: yaml
  label: Alpic Beacon API
  slug: alpic-beacon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-beacon-api-openapi.yml
- filename: alpic-deployments-api-openapi.yml
  format: yaml
  label: Alpic Deployments API
  slug: alpic-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-deployments-api-openapi.yml
- filename: alpic-distribution-api-openapi.yml
  format: yaml
  label: Alpic Distribution API
  slug: alpic-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-distribution-api-openapi.yml
- filename: alpic-environments-api-openapi.yml
  format: yaml
  label: Alpic Environments API
  slug: alpic-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-environments-api-openapi.yml
- filename: alpic-projects-api-openapi.yml
  format: yaml
  label: Alpic Projects API
  slug: alpic-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-projects-api-openapi.yml
- filename: alpic-teams-api-openapi.yml
  format: yaml
  label: Alpic Teams API
  slug: alpic-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-teams-api-openapi.yml
- filename: alpic-tunnels-api-openapi.yml
  format: yaml
  label: Alpic Tunnels API
  slug: alpic-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-tunnels-api-openapi.yml
- filename: alpic-insights-api-openapi.yml
  format: yaml
  label: Alpic Insights API
  slug: alpic-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-insights-api-openapi.yml
- filename: alpic-submissions-api-openapi.yml
  format: yaml
  label: Alpic Submissions API
  slug: alpic-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-submissions-api-openapi.yml
- filename: alpic-telemetry-api-openapi.yml
  format: yaml
  label: Alpic Telemetry API
  slug: alpic-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alpic/openapi/alpic-telemetry-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: This may include your name, professional email address, company name, job title, business contact details, billing and payment information, account credentials, and text contained in your communications.
  - category: device
    text: IP address, device and browser information, operating system, access timestamps, authentication logs, infrastructure, performance data, and interaction data.
  - category: behavioral
    text: product analytics tools that may collect interaction data including page views, feature usage, clicks, and session recordings of your use of the authenticated platform
  deletion:
    route: Contact privacy@alpic.ai
    text: You may exercise your rights by contacting us at privacy@alpic.ai.
  dpa:
    available: true
    text: These providers process personal data under Data Processing Agreements
    url: null
  purposes:
  - purpose: Provision of Services
    text: To create and manage user accounts, authenticate access, operate and maintain the Services, process payments, and provide customer support.
  - purpose: Security and Operations
    text: To monitor, secure, and maintain our infrastructure; detect, prevent, and investigate fraud, misuse, or security incidents
  - purpose: Marketing (where permitted)
    text: To send information about our Services, events, or updates, where permitted by applicable law and subject to your communication preferences
  residency:
  - region: France
    text: ALPIC is headquartered in France
  retention:
  - period: up to three (3) years
    scope: Prospect and marketing data without relationship
    text: where no relationship is established, for up to three (3) years from the last contact or interaction
  - period: null
    scope: Controller data
    text: personal data is retained only for as long as necessary to fulfill the purposes for which it was collected, including the duration of the contractual relationship, applicable statutory limitation periods
  rights:
  - right: access
    text: The right to access the personal data we hold about you
  - right: erasure
    text: The right to request erasure of your personal data in certain circumstances
  - right: portability
    text: The right to data portability, allowing you to receive certain personal data in a structured, commonly used, and machine-readable format
  - right: objection/restriction
    text: The right to restrict or object to our processing of your personal data
  - right: withdraw consent
    text: The right to withdraw consent at any time where processing is based on consent
  role:
    text: Where ALPIC processes personal data in connection with account management, billing, support, security monitoring, or legal compliance, ALPIC acts as a data controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: A current list of our subprocessors is available upon request.
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): European Commission-approved contractual safeguards entered into with recipients of personal data'
  - mechanism: DPF
    text: 'EU-U.S. Data Privacy Framework (where applicable): Transfers to U.S.-based organizations certified under the EU-U.S. Data Privacy Framework'
  - mechanism: adequacy
    text: 'Adequacy Decisions: Transfers to countries recognized by the European Commission as providing an adequate level of data protection'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alpic
provenance_date: '2026-11-09'
provider_name: Alpic
provider_slug: alpic
slug: alpic-privacy-policy
source_date: '2026-11-09'
source_filename: alpic-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alpic.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alpic\naid: alpic\nurl: https://alpic.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where ALPIC processes personal data in connection with account management, billing, support, security monitoring,\n    or legal compliance, ALPIC acts as a data controller.\ndata_categories:\n- category: identifying\n  text: This may include your name, professional email address, company name, job title, business contact details,\n    billing and payment information, account credentials, and text contained in your communications.\n- category: device\n  text: IP address, device and browser information,\
  \ operating system, access timestamps, authentication logs, infrastructure,\n    performance data, and interaction data.\n- category: behavioral\n  text: product analytics tools that may collect interaction data including page views, feature usage, clicks, and\n    session recordings of your use of the authenticated platform\npurposes:\n- purpose: Provision of Services\n  text: To create and manage user accounts, authenticate access, operate and maintain the Services, process payments,\n    and provide customer support.\n- purpose: Security and Operations\n  text: To monitor, secure, and maintain our infrastructure; detect, prevent, and investigate fraud, misuse, or\n    security incidents\n- purpose: Marketing (where permitted)\n  text: To send information about our Services, events, or updates, where permitted by applicable law and subject\n    to your communication preferences\nretention:\n- scope: Prospect and marketing data without relationship\n  period: up to three (3) years\n \
  \ text: where no relationship is established, for up to three (3) years from the last contact or interaction\n- scope: Controller data\n  period: null\n  text: personal data is retained only for as long as necessary to fulfill the purposes for which it was collected,\n    including the duration of the contractual relationship, applicable statutory limitation periods\nresidency:\n- region: France\n  text: ALPIC is headquartered in France\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): European Commission-approved contractual safeguards entered into with\n    recipients of personal data'\n- mechanism: DPF\n  text: 'EU-U.S. Data Privacy Framework (where applicable): Transfers to U.S.-based organizations certified under\n    the EU-U.S. Data Privacy Framework'\n- mechanism: adequacy\n  text: 'Adequacy Decisions: Transfers to countries recognized by the European Commission as providing an adequate\n    level of data protection'\nsubprocessors:\n  url: null\n  text:\
  \ A current list of our subprocessors is available upon request.\ndpa:\n  available: true\n  url: null\n  text: These providers process personal data under Data Processing Agreements\ndeletion:\n  route: Contact privacy@alpic.ai\n  text: You may exercise your rights by contacting us at privacy@alpic.ai.\nrights:\n- right: access\n  text: The right to access the personal data we hold about you\n- right: erasure\n  text: The right to request erasure of your personal data in certain circumstances\n- right: portability\n  text: The right to data portability, allowing you to receive certain personal data in a structured, commonly used,\n    and machine-readable format\n- right: objection/restriction\n  text: The right to restrict or object to our processing of your personal data\n- right: withdraw consent\n  text: The right to withdraw consent at any time where processing is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/alpic/privacy/alpic-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Alpic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Cloud Platform
- Developer Tools
- Deployment
- ChatGPT Apps
- AI Agents
- Platform-as-a-Service
---
