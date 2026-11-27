---
api_specs:
- filename: localytics-audiences-api-openapi.yml
  format: yaml
  label: Localytics Audiences API
  slug: localytics-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-audiences-api-openapi.yml
- filename: localytics-campaigns-api-openapi.yml
  format: yaml
  label: Localytics Campaigns API
  slug: localytics-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-campaigns-api-openapi.yml
- filename: localytics-push-campaigns-api-openapi.yml
  format: yaml
  label: Localytics Push Campaigns API
  slug: localytics-push-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-push-campaigns-api-openapi.yml
- filename: localytics-meta-api-openapi.yml
  format: yaml
  label: Localytics Meta API
  slug: localytics-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-meta-api-openapi.yml
- filename: localytics-push-api-openapi.yml
  format: yaml
  label: Localytics Push API
  slug: localytics-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localytics/openapi/localytics-push-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, job title
  - category: contact
    text: Email, phone number
  - category: behavioral
    text: Event participation
  - category: device
    text: IP address
  - category: device
    text: Device and browser information
  - category: behavioral
    text: Usage and log data
  - category: professional
    text: Company name
  deletion:
    route: null
    text: When personal data is no longer required, it is securely deleted or anonymized.
  dpa:
    available: true
    text: That processing is governed by our Data Processing Addendum (DPA) and customer agreements
    url: null
  purposes:
  - purpose: Provide and operate services
    text: Provide and operate the Services
  - purpose: Support requests
    text: Respond to requests and provide support
  - purpose: Security and fraud prevention
    text: Ensure security and prevent fraud
  - purpose: Marketing communications
    text: Send marketing and product communications
  - purpose: Legal compliance
    text: Comply with legal obligations
  retention:
  - period: null
    scope: personal data
    text: We retain personal data only as long as necessary to fulfill the purposes described in this Policy, including to meet legal, accounting, or reporting requirements.
  rights:
  - right: Access
    text: Access your data
  - right: Correct
    text: Correct inaccuracies
  - right: Deletion
    text: Request deletion
  - right: Restrict or object
    text: Restrict or object to processing
  - right: Portability
    text: Request data portability
  - right: Opt out of sale/sharing (California)
    text: Right to opt out of sale/sharing
  role:
    text: This Privacy Policy applies when Localytics acts as a data controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we implement appropriate safeguards (e.g., Standard Contractual Clauses).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Localytics
provenance_date: '2026-11-09'
provider_name: Localytics
provider_slug: localytics
slug: localytics-privacy-policy
source_date: '2026-11-09'
source_filename: localytics-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.localytics.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Localytics\naid: localytics\nurl: https://www.localytics.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: This Privacy Policy applies when Localytics acts as a data controller\ndata_categories:\n- category: contact\n  text: Name, job title\n- category: contact\n  text: Email, phone number\n- category: behavioral\n  text: Event participation\n- category: device\n  text: IP address\n- category: device\n  text: Device and browser information\n- category: behavioral\n  text: Usage and log data\n- category: professional\n  text: Company name\npurposes:\n- purpose: Provide and operate services\n\
  \  text: Provide and operate the Services\n- purpose: Support requests\n  text: Respond to requests and provide support\n- purpose: Security and fraud prevention\n  text: Ensure security and prevent fraud\n- purpose: Marketing communications\n  text: Send marketing and product communications\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: personal data\n  period: null\n  text: We retain personal data only as long as necessary to fulfill the purposes described in this Policy, including\n    to meet legal, accounting, or reporting requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we implement appropriate safeguards (e.g., Standard Contractual Clauses).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: That processing is governed by our Data Processing Addendum (DPA) and customer agreements\ndeletion:\n  route: null\n  text: When personal data is no longer required, it is securely\
  \ deleted or anonymized.\nrights:\n- right: Access\n  text: Access your data\n- right: Correct\n  text: Correct inaccuracies\n- right: Deletion\n  text: Request deletion\n- right: Restrict or object\n  text: Restrict or object to processing\n- right: Portability\n  text: Request data portability\n- right: Opt out of sale/sharing (California)\n  text: Right to opt out of sale/sharing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/localytics/privacy/localytics-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Localytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MarTech
- Mobile Analytics
- Push Notifications
- Customer Engagement
- Marketing Automation
- Mobile
- Segmentation
- Audiences
- Event Ingestion
- gRPC
---
