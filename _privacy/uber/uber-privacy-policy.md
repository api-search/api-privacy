---
api_specs:
- filename: uber-codes-api-openapi.yml
  format: yaml
  label: Uber Codes API
  slug: uber-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-codes-api-openapi.yml
- filename: uber-deliveries-api-openapi.yml
  format: yaml
  label: Uber Deliveries API
  slug: uber-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-deliveries-api-openapi.yml
- filename: uber-estimates-api-openapi.yml
  format: yaml
  label: Uber Estimates API
  slug: uber-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-estimates-api-openapi.yml
- filename: uber-locations-api-openapi.yml
  format: yaml
  label: Uber Locations API
  slug: uber-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-locations-api-openapi.yml
- filename: uber-menus-api-openapi.yml
  format: yaml
  label: Uber Menus API
  slug: uber-menus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-menus-api-openapi.yml
- filename: uber-orders-api-openapi.yml
  format: yaml
  label: Uber Orders API
  slug: uber-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-orders-api-openapi.yml
- filename: uber-organizations-api-openapi.yml
  format: yaml
  label: Uber Organizations API
  slug: uber-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-organizations-api-openapi.yml
- filename: uber-partners-api-openapi.yml
  format: yaml
  label: Uber Partners API
  slug: uber-partners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-partners-api-openapi.yml
- filename: uber-places-api-openapi.yml
  format: yaml
  label: Uber Places API
  slug: uber-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-places-api-openapi.yml
- filename: uber-products-api-openapi.yml
  format: yaml
  label: Uber Products API
  slug: uber-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-products-api-openapi.yml
- filename: uber-programs-api-openapi.yml
  format: yaml
  label: Uber Programs API
  slug: uber-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-programs-api-openapi.yml
- filename: uber-redemption-api-openapi.yml
  format: yaml
  label: Uber Redemption API
  slug: uber-redemption-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-redemption-api-openapi.yml
- filename: uber-refunds-api-openapi.yml
  format: yaml
  label: Uber Refunds API
  slug: uber-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-refunds-api-openapi.yml
- filename: uber-reporting-api-openapi.yml
  format: yaml
  label: Uber Reporting API
  slug: uber-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-reporting-api-openapi.yml
- filename: uber-requests-api-openapi.yml
  format: yaml
  label: Uber Requests API
  slug: uber-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-requests-api-openapi.yml
- filename: uber-riders-api-openapi.yml
  format: yaml
  label: Uber Riders API
  slug: uber-riders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-riders-api-openapi.yml
- filename: uber-stores-api-openapi.yml
  format: yaml
  label: Uber Stores API
  slug: uber-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-stores-api-openapi.yml
- filename: uber-templates-api-openapi.yml
  format: yaml
  label: Uber Templates API
  slug: uber-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-templates-api-openapi.yml
- filename: uber-trips-api-openapi.yml
  format: yaml
  label: Uber Trips API
  slug: uber-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uber/openapi/uber-trips-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Contact info ( i.e. , email or phone number)
  - category: financial
    text: Payment method (including related payment verification information)
  - category: location
    text: Approximate location Precise location
  - category: behavioral
    text: Uber search history
  - category: device
    text: Device IP address or other unique device identifiers
  - category: demographic
    text: Age or date of birth Gender or inferred gender (using first name)
  - category: health
    text: Processing health data, or other sensitive data, depending on the region you live in
  - category: biometric
    text: This may include biometric data that allows you to be identified based on your physical or biological characteristics.
  - category: communication
    text: Content (including audio recordings, recordings of phone calls, call transcripts, and chat logs)
  deletion:
    route: Privacy menus in the Uber app, or Uber’s website, or Privacy Center
    text: You may request that we delete your account through the Privacy menus in the Uber app, or through Uber’s website
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: Uber uses data to provide, personalize, maintain, and improve our products and services.
  - purpose: Safety and fraud prevention
    text: For safety, security, and fraud prevention and detection.
  - purpose: Marketing and advertising
    text: For marketing and advertising.
  - purpose: Research and development
    text: We use data for analysis, research and product development, including training machine learning models.
  - purpose: Customer support
    text: For customer support.
  - purpose: Legal proceedings
    text: For legal proceedings and requirements.
  residency:
  - region: United States
    text: This includes processing of your data on Uber’s servers in the United States
  retention:
  - period: null
    scope: Account data
    text: for as long as you maintain your Uber account (i.e., the life of your account)
  - period: 7 years
    scope: Tax, insurance, legal or regulatory data
    text: for 7 years from collection (unless you first delete your Uber account)
  - period: 1 year for government IDs
    scope: Identity verification - government IDs
    text: 1 year for government IDs
  - period: 3 years for user-submitted selfies
    scope: Identity verification - selfies
    text: 3 years for user-submitted selfies
  - period: 48 hours
    scope: Age verification ID images for alcohol delivery
    text: we delete such images within 48 hours unless longer retention is required by law
  - period: 90 days
    scope: Account deletion
    text: We generally delete data within 90 days of an account deletion request
  rights:
  - right: Access
    text: You may also request access to or copies of your data, make changes or updates to your account, request account deletion, or request that Uber restrict its processing of your data.
  - right: Portability
    text: Depending on where you are located, you may have the right to access your data and to portability of your data.
  - right: Objection and restriction
    text: You may request that we stop using all or some of your data, or that we limit our use of your data.
  - right: Withdraw consent
    text: Where we rely on consent, you have the right to withdraw your consent at any time
  - right: Complaint
    text: you may have the right to file a complaint relating to Uber’s handling of your data with the data protection authority in your country
  role:
    text: Uber Technologies, Inc. is the sole controller of the data processed by Uber when you use Uber’s services globally, except where it is a joint controller with other Uber affiliates.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: transfer mechanisms such as the Standard Contractual Clauses adopted by the European Commission (and their approved equivalents for the UK and Switzerland)
  - mechanism: DPF
    text: the EU-US Data Privacy Framework (“EU-US DPF”), the UK Extension to the EU-US DPF, and the Swiss-US Data Privacy Framework (“Swiss-US DPF”)
  - mechanism: adequacy
    text: adequacy decisions regarding the country of transfer
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Uber
provenance_date: '2026-11-10'
provider_name: Uber
provider_slug: uber
slug: uber-privacy-policy
source_date: '2026-11-10'
source_filename: uber-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.uber.com/global/en/privacy-notice-riders-order-recipients/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Uber\naid: uber\nurl: https://www.uber.com/global/en/privacy-notice-riders-order-recipients/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Uber Technologies, Inc. is the sole controller of the data processed by Uber when you use Uber’s services\n    globally, except where it is a joint controller with other Uber affiliates.\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Contact info ( i.e. , email or phone number)\n- category: financial\n  text: Payment method (including related payment verification information)\n- category: location\n\
  \  text: Approximate location Precise location\n- category: behavioral\n  text: Uber search history\n- category: device\n  text: Device IP address or other unique device identifiers\n- category: demographic\n  text: Age or date of birth Gender or inferred gender (using first name)\n- category: health\n  text: Processing health data, or other sensitive data, depending on the region you live in\n- category: biometric\n  text: This may include biometric data that allows you to be identified based on your physical or biological characteristics.\n- category: communication\n  text: Content (including audio recordings, recordings of phone calls, call transcripts, and chat logs)\npurposes:\n- purpose: Provide services\n  text: Uber uses data to provide, personalize, maintain, and improve our products and services.\n- purpose: Safety and fraud prevention\n  text: For safety, security, and fraud prevention and detection.\n- purpose: Marketing and advertising\n  text: For marketing and advertising.\n\
  - purpose: Research and development\n  text: We use data for analysis, research and product development, including training machine learning models.\n- purpose: Customer support\n  text: For customer support.\n- purpose: Legal proceedings\n  text: For legal proceedings and requirements.\nretention:\n- scope: Account data\n  period: null\n  text: for as long as you maintain your Uber account (i.e., the life of your account)\n- scope: Tax, insurance, legal or regulatory data\n  period: 7 years\n  text: for 7 years from collection (unless you first delete your Uber account)\n- scope: Identity verification - government IDs\n  period: 1 year for government IDs\n  text: 1 year for government IDs\n- scope: Identity verification - selfies\n  period: 3 years for user-submitted selfies\n  text: 3 years for user-submitted selfies\n- scope: Age verification ID images for alcohol delivery\n  period: 48 hours\n  text: we delete such images within 48 hours unless longer retention is required by law\n\
  - scope: Account deletion\n  period: 90 days\n  text: We generally delete data within 90 days of an account deletion request\nresidency:\n- region: United States\n  text: This includes processing of your data on Uber’s servers in the United States\ntransfers:\n- mechanism: SCC\n  text: transfer mechanisms such as the Standard Contractual Clauses adopted by the European Commission (and their\n    approved equivalents for the UK and Switzerland)\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework (“EU-US DPF”), the UK Extension to the EU-US DPF, and the Swiss-US Data\n    Privacy Framework (“Swiss-US DPF”)\n- mechanism: adequacy\n  text: adequacy decisions regarding the country of transfer\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy menus in the Uber app, or Uber’s website, or Privacy Center\n  text: You may request that we delete your account through the Privacy menus in the Uber app, or through Uber’s\n\
  \    website\nrights:\n- right: Access\n  text: You may also request access to or copies of your data, make changes or updates to your account, request\n    account deletion, or request that Uber restrict its processing of your data.\n- right: Portability\n  text: Depending on where you are located, you may have the right to access your data and to portability of your\n    data.\n- right: Objection and restriction\n  text: You may request that we stop using all or some of your data, or that we limit our use of your data.\n- right: Withdraw consent\n  text: Where we rely on consent, you have the right to withdraw your consent at any time\n- right: Complaint\n  text: you may have the right to file a complaint relating to Uber’s handling of your data with the data protection\n    authority in your country\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uber/privacy/uber-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 33 quoted statements, read from Uber's own page on 2026-11-10.
synthetic: false
tags:
- Ride Hailing
- Taxis
- Transportation
- Food Delivery
- Delivery
- Logistics
- Mobility
---
