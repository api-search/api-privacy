---
api_specs:
- filename: tufin-compliance-api-openapi.yml
  format: yaml
  label: Tufin Compliance API
  slug: tufin-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-compliance-api-openapi.yml
- filename: tufin-devices-api-openapi.yml
  format: yaml
  label: Tufin Devices API
  slug: tufin-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-devices-api-openapi.yml
- filename: tufin-objects-api-openapi.yml
  format: yaml
  label: Tufin Objects API
  slug: tufin-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-objects-api-openapi.yml
- filename: tufin-revisions-api-openapi.yml
  format: yaml
  label: Tufin Revisions API
  slug: tufin-revisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-revisions-api-openapi.yml
- filename: tufin-rules-api-openapi.yml
  format: yaml
  label: Tufin Rules API
  slug: tufin-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-rules-api-openapi.yml
- filename: tufin-tasks-api-openapi.yml
  format: yaml
  label: Tufin Tasks API
  slug: tufin-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-tasks-api-openapi.yml
- filename: tufin-tickets-api-openapi.yml
  format: yaml
  label: Tufin Tickets API
  slug: tufin-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-tickets-api-openapi.yml
- filename: tufin-topology-api-openapi.yml
  format: yaml
  label: Tufin Topology API
  slug: tufin-topology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-topology-api-openapi.yml
- filename: tufin-users-api-openapi.yml
  format: yaml
  label: Tufin Users API
  slug: tufin-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-users-api-openapi.yml
- filename: tufin-workflow-definitions-api-openapi.yml
  format: yaml
  label: Tufin Workflow Definitions API
  slug: tufin-workflow-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-workflow-definitions-api-openapi.yml
- filename: tufin-zones-api-openapi.yml
  format: yaml
  label: Tufin Zones API
  slug: tufin-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tufin/openapi/tufin-zones-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: contact and business details such as name, email, phone number, position, workplace and related business insights
  - category: device
    text: device data (like type, OS, device id, browser version, locale and language settings used)
  - category: location
    text: approximate location based upon such IP addresses
  - category: behavioral
    text: activity logs, session recordings
  - category: communication
    text: call and video recordings, and transcriptions and analyses thereof
  deletion:
    route: email
    text: If you have any questions regarding our data retention practices, please contact us by email at privacy@tufin.com .
  dpa:
    available: true
    text: in accordance with the commercial agreement and data processing addendum with them
    url: null
  purposes:
  - purpose: Provide and operate Services
    text: To facilitate, operate, enhance, and provide our Services.
  - purpose: Marketing and ads
    text: To facilitate and optimize our marketing campaigns, ad management and sales operations
  - purpose: Security and fraud prevention
    text: To support and enhance our data security measures, including for the purposes of preventing and mitigating the risks of fraud, error or any illegal, criminal or prohibited activity.
  residency:
  - region: United States of America, European Union
    text: We and our authorized Service Providers maintain, store and process personal data in the United States of America, European Union, and in other locations as reasonably necessary
  retention:
  - period: null
    scope: Personal data
    text: We retain personal data for as long as we deem it as reasonably necessary in order to maintain and expand our relationship and provide you with our Services and offerings
  rights:
  - right: access
    text: the right to know/request access to (specific pieces of personal data collected; categories of personal data collected
  - right: rectification or erasure
    text: to request rectification or erasure of your personal data held with Tufin
  - right: restrict or object
    text: or to restrict or object to such personal data’s processing
  - right: portability
    text: or to port such personal data
  - right: opt out of sale
    text: including the right to direct us not to sell your personal data to third parties now or in the future
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
  - mechanism: DPF
    text: Tufin Software North America, Inc, complies with the EU-US Data Privacy Framework (EU-US DPF), the UK Extension to the EU-US DPF, and the Swiss-US Data Privacy Framework (Swiss-US DPF)
  - mechanism: adequacy
    text: we rely on the applicable adequacy decision as the legal basis for such transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tufin
provenance_date: '2026-11-10'
provider_name: Tufin
provider_slug: tufin
slug: tufin-privacy-policy
source_date: '2026-11-10'
source_filename: tufin-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tufin.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tufin\naid: tufin\nurl: https://www.tufin.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: contact and business details such as name, email, phone number, position, workplace and related business\n    insights\n- category: device\n  text: device data (like type, OS, device id, browser version, locale and language settings used)\n- category: location\n  text: approximate location based upon such IP addresses\n- category: behavioral\n  text: activity logs, session recordings\n- category: communication\n  text: call and video\
  \ recordings, and transcriptions and analyses thereof\npurposes:\n- purpose: Provide and operate Services\n  text: To facilitate, operate, enhance, and provide our Services.\n- purpose: Marketing and ads\n  text: To facilitate and optimize our marketing campaigns, ad management and sales operations\n- purpose: Security and fraud prevention\n  text: To support and enhance our data security measures, including for the purposes of preventing and mitigating\n    the risks of fraud, error or any illegal, criminal or prohibited activity.\nretention:\n- scope: Personal data\n  period: null\n  text: We retain personal data for as long as we deem it as reasonably necessary in order to maintain and expand\n    our relationship and provide you with our Services and offerings\nresidency:\n- region: United States of America, European Union\n  text: We and our authorized Service Providers maintain, store and process personal data in the United States of\n    America, European Union, and in other locations\
  \ as reasonably necessary\ntransfers:\n- mechanism: DPF\n  text: Tufin Software North America, Inc, complies with the EU-US Data Privacy Framework (EU-US DPF), the UK Extension\n    to the EU-US DPF, and the Swiss-US Data Privacy Framework (Swiss-US DPF)\n- mechanism: adequacy\n  text: we rely on the applicable adequacy decision as the legal basis for such transfer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: in accordance with the commercial agreement and data processing addendum with them\ndeletion:\n  route: email\n  text: If you have any questions regarding our data retention practices, please contact us by email at privacy@tufin.com\n    .\nrights:\n- right: access\n  text: the right to know/request access to (specific pieces of personal data collected; categories of personal\n    data collected\n- right: rectification or erasure\n  text: to request rectification or erasure of your personal data held with Tufin\n- right: restrict or object\n\
  \  text: or to restrict or object to such personal data’s processing\n- right: portability\n  text: or to port such personal data\n- right: opt out of sale\n  text: including the right to direct us not to sell your personal data to third parties now or in the future\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tufin/privacy/tufin-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 19 quoted statements, read from Tufin's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Security
- Compliance
- Firewall Management
- Network Security
- Network Topology
- Policy Orchestration
- Risk Management
- Security Policy Management
- Zero Trust
---
