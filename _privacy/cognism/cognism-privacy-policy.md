---
api_specs:
- filename: cognism-compliance-api-openapi.yml
  format: yaml
  label: Cognism Compliance API
  slug: cognism-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-compliance-api-openapi.yml
- filename: cognism-enrich-api-openapi.yml
  format: yaml
  label: Cognism Enrich API
  slug: cognism-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-enrich-api-openapi.yml
- filename: cognism-entitlement-api-openapi.yml
  format: yaml
  label: Cognism Entitlement API
  slug: cognism-entitlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-entitlement-api-openapi.yml
- filename: cognism-filter-api-openapi.yml
  format: yaml
  label: Cognism Filter API
  slug: cognism-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-filter-api-openapi.yml
- filename: cognism-redeem-api-openapi.yml
  format: yaml
  label: Cognism Redeem API
  slug: cognism-redeem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-redeem-api-openapi.yml
- filename: cognism-search-api-openapi.yml
  format: yaml
  label: Cognism Search API
  slug: cognism-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cognism/openapi/cognism-search-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Full name, Location and contact details (such as email address)
  - category: professional
    text: Professional contact information (telephone number, email)
  - category: device
    text: Other technical information relating to end user device, such as browser type, IP address or browser plug-in
  - category: behavioral
    text: Page interaction information, such as scrolling, clicks and browsing methods
  deletion:
    route: Cognism Privacy Centre form or privacy@cognism.com
    text: 'If you want to permanently erase your data from the Cognism Platform, please: complete the form at the Cognism Privacy Centre (recommended); or contact us at privacy@cognism.com .'
  dpa:
    available: true
    text: Where Cognism is acting as a processor a Data Processing Agreement with customers is in place
    url: null
  purposes:
  - purpose: Providing our Services
    text: Providing our Services to administer our Website and deliver our Services to our Customers or their customers under the agreed terms of service, including support
  - purpose: Direct marketing
    text: Direct marketing communications and advertising to send postal, phone, electronic or email communications to our Customers and prospective Customers
  - purpose: Security
    text: Ensuring the security of our Services to monitor our Website and Services in order to prevent and detect security risks
  residency:
  - region: European Union
    text: Cognism stores personal data inside the European Union.
  retention:
  - period: five (5) years
    scope: Business contact data within the Cognism Platform
    text: For business contact data within our platform, we aim to remove data after five (5) years from the date of collection.
  rights:
  - right: Access
    text: 'Right to access You have the right to request: the confirmation on whether Cognism processes your personal data or not'
  - right: Rectification
    text: Right to rectification You have the right to request the rectification of your personal data
  - right: Erasure
    text: Right to delete You have the right to request the deletion of your personal data (or right to be forgotten)
  - right: Restriction
    text: Right to restriction of processing You have the right to request the restriction of the processing
  - right: Portability
    text: Right to data portability You have the right to request a copy of your personal data in a structured, commonly used and machine-readable format
  - right: Objection
    text: Right to object You have the right to object to our processing of your personal data at any time if the processing is based on our legitimate interest.
  - right: Withdraw consent
    text: Right to withdraw your consent when it has been obtained
  role:
    text: Cognism may either be controller or processor.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cognism Platform is hosted by Amazon Web Services (in Ireland).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cognism
provenance_date: '2026-11-09'
provider_name: Cognism
provider_slug: cognism
slug: cognism-privacy-policy
source_date: '2026-11-09'
source_filename: cognism-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cognism.com/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cognism\naid: cognism\nurl: https://www.cognism.com/en/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Cognism may either be controller or processor.\ndata_categories:\n- category: contact\n  text: Full name, Location and contact details (such as email address)\n- category: professional\n  text: Professional contact information (telephone number, email)\n- category: device\n  text: Other technical information relating to end user device, such as browser type, IP address or browser plug-in\n- category: behavioral\n  text: Page interaction information, such as scrolling, clicks and browsing\
  \ methods\npurposes:\n- purpose: Providing our Services\n  text: Providing our Services to administer our Website and deliver our Services to our Customers or their customers\n    under the agreed terms of service, including support\n- purpose: Direct marketing\n  text: Direct marketing communications and advertising to send postal, phone, electronic or email communications\n    to our Customers and prospective Customers\n- purpose: Security\n  text: Ensuring the security of our Services to monitor our Website and Services in order to prevent and detect\n    security risks\nretention:\n- scope: Business contact data within the Cognism Platform\n  period: five (5) years\n  text: For business contact data within our platform, we aim to remove data after five (5) years from the date\n    of collection.\nresidency:\n- region: European Union\n  text: Cognism stores personal data inside the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cognism Platform is hosted by Amazon\
  \ Web Services (in Ireland).\ndpa:\n  available: true\n  url: null\n  text: Where Cognism is acting as a processor a Data Processing Agreement with customers is in place\ndeletion:\n  route: Cognism Privacy Centre form or privacy@cognism.com\n  text: 'If you want to permanently erase your data from the Cognism Platform, please: complete the form at the\n    Cognism Privacy Centre (recommended); or contact us at privacy@cognism.com .'\nrights:\n- right: Access\n  text: 'Right to access You have the right to request: the confirmation on whether Cognism processes your personal\n    data or not'\n- right: Rectification\n  text: Right to rectification You have the right to request the rectification of your personal data\n- right: Erasure\n  text: Right to delete You have the right to request the deletion of your personal data (or right to be forgotten)\n- right: Restriction\n  text: Right to restriction of processing You have the right to request the restriction of the processing\n- right:\
  \ Portability\n  text: Right to data portability You have the right to request a copy of your personal data in a structured, commonly\n    used and machine-readable format\n- right: Objection\n  text: Right to object You have the right to object to our processing of your personal data at any time if the\n    processing is based on our legitimate interest.\n- right: Withdraw consent\n  text: Right to withdraw your consent when it has been obtained\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cognism/privacy/cognism-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 20 quoted statements, read from Cognism's own page on 2026-11-09.
synthetic: false
tags:
- Sales Intelligence
- B2B
- Data Enrichment
- Contact Data
- GDPR
- Intent Data
- Lead Generation
- Firmographics
- Technographics
- Company Data
- Prospecting
- Data as a Service
---
