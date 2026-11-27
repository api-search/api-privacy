---
api_specs:
- filename: varonis-alerts-api-openapi.yml
  format: yaml
  label: Varonis Alerts API
  slug: varonis-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/varonis/openapi/varonis-alerts-api-openapi.yml
- filename: varonis-events-api-openapi.yml
  format: yaml
  label: Varonis Events API
  slug: varonis-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/varonis/openapi/varonis-events-api-openapi.yml
- filename: varonis-threat-models-api-openapi.yml
  format: yaml
  label: Varonis Threat Models API
  slug: varonis-threat-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/varonis/openapi/varonis-threat-models-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Customer metadata refers to information that describes or contextualizes that content (such as user identities, file/folder/path names, email addresses/subjects/senders/recipients, domains, and IP addresses, timestamps, or communication attributes).
  - category: communication
    text: Customer data refers to the actual content stored within files or communications (such as document text or email bodies)
  deletion:
    route: 'Request to cease processing or delete PII: dl-privacy-requests@varonis.com'
    text: 'Request to cease processing or delete PII: dl-privacy-requests@varonis.com'
  dpa:
    available: true
    text: Any transfer of personal information will be subject to a data processing agreement (DPA)
    url: null
  purposes:
  - purpose: threat detection and response, data security, compliance and remediation
    text: Varonis technology crawls data sources for the purpose of threat detection and response, data security, compliance and remediation.
  - purpose: spam and malicious email detection
    text: Varonis Email Interceptor monitors email communications of organizational employees and detects spam emails and malicious patterns
  residency:
  - region: Customer-chosen geography
    text: Upon onboarding, Varonis' Data Security Platform can be set to operate from the geography of the customer’s choice.
  retention:
  - period: 180 days
    scope: Subscriber Data on Varonis SaaS platforms
    text: Our default retention policy for the Subscriber Data on the Varonis SaaS platforms, is a sliding window of 180 days during the subscription term
  - period: null
    scope: Email content analyzed by Email Interceptor
    text: Varonis does not retain the content of the emails, unless it is detected to be a malicious email.
  - period: 30 days
    scope: Email samples in false positive/negative investigations
    text: Email samples submitted as part of false positive/false negative investigations of Varonis Interceptor are deleted 30 days after case is closed.
  - period: 30 days
    scope: Subscriber Data after subscription termination
    text: Upon the end/termination of the subscription term, Subscriber Data which is held by Varonis at such time shall be deleted within up to 30 days after termination of the subscription.
  rights:
  - right: exercise data subject rights
    text: We have implemented the necessary mechanisms to enable users to exercise such rights.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The full list of Varonis sub-processors and their locations of processing can be found in our Sub-Processors list .
    url: https://www.varonis.com/trust/privacy
  transfers:
  - mechanism: SCC
    text: When required by law, Varonis also incorporates the GDPR's Standard Contractual Clauses (SCCs), or their UK and Swiss counterpart, or the EU-US Data Privacy Framework (DPF)
  - mechanism: DPF
    text: or the EU-US Data Privacy Framework (DPF), including the UK and Swiss extensions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Varonis
provenance_date: '2026-11-10'
provider_name: Varonis
provider_slug: varonis
slug: varonis-privacy-policy
source_date: '2026-11-10'
source_filename: varonis-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.varonis.com/trust/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Varonis\naid: varonis\nurl: https://www.varonis.com/trust/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Customer metadata refers to information that describes or contextualizes that content (such as user identities,\n    file/folder/path names, email addresses/subjects/senders/recipients, domains, and IP addresses, timestamps,\n    or communication attributes).\n- category: communication\n  text: Customer data refers to the actual content stored within files or communications (such as document text\n    or email bodies)\npurposes:\n\
  - purpose: threat detection and response, data security, compliance and remediation\n  text: Varonis technology crawls data sources for the purpose of threat detection and response, data security,\n    compliance and remediation.\n- purpose: spam and malicious email detection\n  text: Varonis Email Interceptor monitors email communications of organizational employees and detects spam emails\n    and malicious patterns\nretention:\n- scope: Subscriber Data on Varonis SaaS platforms\n  period: 180 days\n  text: Our default retention policy for the Subscriber Data on the Varonis SaaS platforms, is a sliding window\n    of 180 days during the subscription term\n- scope: Email content analyzed by Email Interceptor\n  period: null\n  text: Varonis does not retain the content of the emails, unless it is detected to be a malicious email.\n- scope: Email samples in false positive/negative investigations\n  period: 30 days\n  text: Email samples submitted as part of false positive/false negative\
  \ investigations of Varonis Interceptor are\n    deleted 30 days after case is closed.\n- scope: Subscriber Data after subscription termination\n  period: 30 days\n  text: Upon the end/termination of the subscription term, Subscriber Data which is held by Varonis at such time\n    shall be deleted within up to 30 days after termination of the subscription.\nresidency:\n- region: Customer-chosen geography\n  text: Upon onboarding, Varonis' Data Security Platform can be set to operate from the geography of the customer’s\n    choice.\ntransfers:\n- mechanism: SCC\n  text: When required by law, Varonis also incorporates the GDPR's Standard Contractual Clauses (SCCs), or their\n    UK and Swiss counterpart, or the EU-US Data Privacy Framework (DPF)\n- mechanism: DPF\n  text: or the EU-US Data Privacy Framework (DPF), including the UK and Swiss extensions\nsubprocessors:\n  url: https://www.varonis.com/trust/privacy\n  text: The full list of Varonis sub-processors and their locations of processing\
  \ can be found in our Sub-Processors\n    list .\ndpa:\n  available: true\n  url: null\n  text: Any transfer of personal information will be subject to a data processing agreement (DPA)\ndeletion:\n  route: 'Request to cease processing or delete PII: dl-privacy-requests@varonis.com'\n  text: 'Request to cease processing or delete PII: dl-privacy-requests@varonis.com'\nrights:\n- right: exercise data subject rights\n  text: We have implemented the necessary mechanisms to enable users to exercise such rights.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/varonis/privacy/varonis-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 15 quoted statements, read from Varonis's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Security
- Compliance
- Data Analytics
- Data Governance
- Data Security
- Threat Detection
---
