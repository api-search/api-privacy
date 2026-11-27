---
api_specs:
- filename: clevertap-campaigns-api-openapi.yml
  format: yaml
  label: CleverTap Campaigns API
  slug: clevertap-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-campaigns-api-openapi.yml
- filename: clevertap-events-api-openapi.yml
  format: yaml
  label: CleverTap Events API
  slug: clevertap-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-events-api-openapi.yml
- filename: clevertap-profiles-api-openapi.yml
  format: yaml
  label: CleverTap Profiles API
  slug: clevertap-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-profiles-api-openapi.yml
- filename: clevertap-reports-api-openapi.yml
  format: yaml
  label: CleverTap Reports API
  slug: clevertap-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevertap/openapi/clevertap-reports-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name Company name Work email address Telephone number Country Other information voluntarily provided in communications
  - category: device
    text: Internet Protocol (IP) address Browser type Browser language Device characteristics Referring URLs Pages viewed Links clicked Timestamps Similar interaction data
  - category: behavioral
    text: Behavioural event data
  - category: location
    text: Geolocation data where enabled by the Customer.
  - category: professional
    text: Job title Related contact details
  deletion:
    route: Upon termination or expiration of a Customer contract, Customer End User data is deleted from active production systems
    text: Upon termination or expiration of a Customer contract, Customer End User data is deleted from active production systems within the timeframe specified in the applicable agreement.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service operation and communications
    text: Respond to inquiries; provide product demonstrations; Deliver customer support; Administer contracts; Manage billing and financial transactions; Communicate regarding service-related matters.
  - purpose: Security and fraud prevention
    text: CleverTap processes personal data to maintain the security, integrity, and availability of its systems and Services.
  residency:
  - region: Customer End User data
    text: such data is hosted in the production region selected by the Customer at the time of account configuration.
  retention:
  - period: sixty (60) days
    scope: Customer End User data after contract termination
    text: Where no specific contractual retention period is defined, deletion is performed through automated system processes within a maximum period of sixty (60) days following termination of the Service.
  - period: null
    scope: Controller personal data
    text: Personal data is retained only for as long as necessary to fulfil the purposes described in this Privacy Policy, unless a longer retention period is required or permitted by applicable law.
  rights:
  - right: Access
    text: Right of Access You may request confirmation of whether we process personal data about you and access to that data
  - right: Rectification
    text: Right to Rectification You may request the correction of inaccurate personal data
  - right: Erasure
    text: Right to Erasure You may request deletion of personal data where permitted by law.
  - right: Portability
    text: Right to Data Portability Where applicable, you may request the receipt of your personal data in a structured, commonly used, and machine-readable format
  - right: Object
    text: Right to Object You may object to processing based on legitimate interests, including processing for direct marketing purposes.
  role:
    text: CleverTap acts as a data controller when we determine the purposes and means of processing personal data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: CleverTap does not sell personal data for monetary consideration.
  subprocessors:
    text: A current list of sub-processors engaged in connection with the Service is available through our Trust Portal .
    url: https://trust.clevertap.com/
  transfers:
  - mechanism: DPF
    text: Certification under the EU–U.S. Data Privacy Framework (EU–U.S. DPF)
  - mechanism: SCC
    text: The 2021 European Commission Standard Contractual Clauses, where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CleverTap
provenance_date: '2026-11-09'
provider_name: CleverTap
provider_slug: clevertap
slug: clevertap-privacy-policy
source_date: '2026-11-09'
source_filename: clevertap-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clevertap.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CleverTap\naid: clevertap\nurl: https://clevertap.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: CleverTap acts as a data controller when we determine the purposes and means of processing personal data.\ndata_categories:\n- category: identifying\n  text: Name Company name Work email address Telephone number Country Other information voluntarily provided in\n    communications\n- category: device\n  text: Internet Protocol (IP) address Browser type Browser language Device characteristics Referring URLs Pages\n    viewed Links clicked Timestamps Similar interaction data\n- category:\
  \ behavioral\n  text: Behavioural event data\n- category: location\n  text: Geolocation data where enabled by the Customer.\n- category: professional\n  text: Job title Related contact details\npurposes:\n- purpose: Service operation and communications\n  text: Respond to inquiries; provide product demonstrations; Deliver customer support; Administer contracts; Manage\n    billing and financial transactions; Communicate regarding service-related matters.\n- purpose: Security and fraud prevention\n  text: CleverTap processes personal data to maintain the security, integrity, and availability of its systems and\n    Services.\nretention:\n- scope: Customer End User data after contract termination\n  period: sixty (60) days\n  text: Where no specific contractual retention period is defined, deletion is performed through automated system\n    processes within a maximum period of sixty (60) days following termination of the Service.\n- scope: Controller personal data\n  period: null\n  text:\
  \ Personal data is retained only for as long as necessary to fulfil the purposes described in this Privacy\n    Policy, unless a longer retention period is required or permitted by applicable law.\nresidency:\n- region: Customer End User data\n  text: such data is hosted in the production region selected by the Customer at the time of account configuration.\ntransfers:\n- mechanism: DPF\n  text: Certification under the EU–U.S. Data Privacy Framework (EU–U.S. DPF)\n- mechanism: SCC\n  text: The 2021 European Commission Standard Contractual Clauses, where applicable\nsubprocessors:\n  url: https://trust.clevertap.com/\n  text: A current list of sub-processors engaged in connection with the Service is available through our Trust Portal\n    .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Upon termination or expiration of a Customer contract, Customer End User data is deleted from active production\n    systems\n  text: Upon termination or expiration of a Customer\
  \ contract, Customer End User data is deleted from active production\n    systems within the timeframe specified in the applicable agreement.\nrights:\n- right: Access\n  text: Right of Access You may request confirmation of whether we process personal data about you and access to\n    that data\n- right: Rectification\n  text: Right to Rectification You may request the correction of inaccurate personal data\n- right: Erasure\n  text: Right to Erasure You may request deletion of personal data where permitted by law.\n- right: Portability\n  text: Right to Data Portability Where applicable, you may request the receipt of your personal data in a structured,\n    commonly used, and machine-readable format\n- right: Object\n  text: Right to Object You may object to processing based on legitimate interests, including processing for direct\n    marketing purposes.\nsale_or_sharing:\n  stance: prohibited\n  text: CleverTap does not sell personal data for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/clevertap/privacy/clevertap-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from CleverTap's own page on 2026-11-09.
synthetic: false
tags:
- Audiences
- Customer Engagement
- Customer Retention
- Marketing Automation
- Mobile Engagement
- Push Notifications
- User Behavior
---
