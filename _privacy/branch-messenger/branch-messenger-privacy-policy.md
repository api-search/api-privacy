---
api_specs:
- filename: branch-messenger-analytics-api-openapi.yml
  format: yaml
  label: Branch Analytics API
  slug: branch-messenger-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branch-messenger/openapi/branch-messenger-analytics-api-openapi.yml
- filename: branch-messenger-app-api-openapi.yml
  format: yaml
  label: Branch App API
  slug: branch-messenger-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branch-messenger/openapi/branch-messenger-app-api-openapi.yml
- filename: branch-messenger-branch-api-api-openapi.yml
  format: yaml
  label: Branch Branch API
  slug: branch-messenger-branch-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branch-messenger/openapi/branch-messenger-branch-api-api-openapi.yml
- filename: branch-messenger-event-api-openapi.yml
  format: yaml
  label: Branch Event API
  slug: branch-messenger-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branch-messenger/openapi/branch-messenger-event-api-openapi.yml
- filename: branch-messenger-img1-api-openapi.yml
  format: yaml
  label: Branch Img1 API
  slug: branch-messenger-img1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branch-messenger/openapi/branch-messenger-img1-api-openapi.yml
- filename: branch-messenger-query-api-openapi.yml
  format: yaml
  label: Branch Query API
  slug: branch-messenger-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/branch-messenger/openapi/branch-messenger-query-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Advertising identifier (e.g., GAID, Android ID, IDFA, IDFV, RIDA) Used for device identification and attribution
  - category: contact
    text: Such information we may receive may include contact and professional details about you which you have chosen to share with us including name, email address, phone number, office or other mailing address
  - category: location
    text: IP Address Standard web HTTP request; used for attribution and to understand general location
  - category: behavioral
    text: Engagement Data Information relating to the Client’s ad campaigns and User interactions, such as clicks on Client ads, Client ad impressions viewed
  - category: device
    text: Device model Metadata feature used for device identification and attribution
  - category: professional
    text: professional data including organization you are affiliated with, your job title, and industry
  deletion:
    route: Email to request account deletion or deletion of end-user data via the deletion request control
    text: If you would like to delete your account, please email [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deep linking and attribution
    text: To support Clients in implementing deep linking, which uses Branch’s connection information in real time to improve the User experience.
  - purpose: analytics reporting to Clients
    text: To report individualized and aggregated analytics metrics about the performance of the Client’s product and marketing initiatives to the Client directly.
  - purpose: product improvement and marketing
    text: data that Branch collects through the Services is processed to provide, maintain, optimize, research and improve the Services we provide our Clients, including to support other Branch products and services, to perform anti- fraud protection analysis, develop new products and services, and market products or services
  residency:
  - region: United States
    text: All information collected via the Website and Services is stored on servers located in the United States.
  retention:
  - period: null
    scope: Website and Services information
    text: Branch retains the information we collect through our Website and Services for no more time than is needed to serve the legitimate business purposes for which it was collected, or as necessary to comply with our legal obligations.
  rights:
  - right: access, correct, erase and restrict processing
    text: you may have the right to access, correct, erase and restrict the processing of your personal data.
  - right: object to processing
    text: You may also have the right to object to Branch’s processing of your data
  - right: opt out of promotional emails
    text: You can opt-out of receiving promotional emails from us by following the instructions in those emails
  role:
    text: Branch has no direct relationship with Users. Branch’s Services are provided when Branch Clients install on their platforms “Branch Mechanisms”
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not rent or sell customer end user data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Branch complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-US Data Privacy Framework (Swiss-U.S. DPF)
  - mechanism: SCC
    text: such as Standard Contractual Clauses or the Data Privacy Framework mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Branch
provenance_date: '2026-11-09'
provider_name: Branch
provider_slug: branch-messenger
slug: branch-messenger-privacy-policy
source_date: '2026-11-09'
source_filename: branch-messenger-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://legal.branch.io/saas/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Branch\naid: branch-messenger\nurl: https://legal.branch.io/saas/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Branch has no direct relationship with Users. Branch’s Services are provided when Branch Clients install\n    on their platforms “Branch Mechanisms”\ndata_categories:\n- category: identifying\n  text: Advertising identifier (e.g., GAID, Android ID, IDFA, IDFV, RIDA) Used for device identification and attribution\n- category: contact\n  text: Such information we may receive may include contact and professional details about you which you have chosen\n    to share with us\
  \ including name, email address, phone number, office or other mailing address\n- category: location\n  text: IP Address Standard web HTTP request; used for attribution and to understand general location\n- category: behavioral\n  text: Engagement Data Information relating to the Client’s ad campaigns and User interactions, such as clicks\n    on Client ads, Client ad impressions viewed\n- category: device\n  text: Device model Metadata feature used for device identification and attribution\n- category: professional\n  text: professional data including organization you are affiliated with, your job title, and industry\npurposes:\n- purpose: deep linking and attribution\n  text: To support Clients in implementing deep linking, which uses Branch’s connection information in real time\n    to improve the User experience.\n- purpose: analytics reporting to Clients\n  text: To report individualized and aggregated analytics metrics about the performance of the Client’s product\n    and marketing\
  \ initiatives to the Client directly.\n- purpose: product improvement and marketing\n  text: data that Branch collects through the Services is processed to provide, maintain, optimize, research and\n    improve the Services we provide our Clients, including to support other Branch products and services, to perform\n    anti- fraud protection analysis, develop new products and services, and market products or services\nretention:\n- scope: Website and Services information\n  period: null\n  text: Branch retains the information we collect through our Website and Services for no more time than is needed\n    to serve the legitimate business purposes for which it was collected, or as necessary to comply with our legal\n    obligations.\nresidency:\n- region: United States\n  text: All information collected via the Website and Services is stored on servers located in the United States.\ntransfers:\n- mechanism: DPF\n  text: Branch complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF),\
  \ the UK Extension to the EU-U.S. DPF,\n    and the Swiss-US Data Privacy Framework (Swiss-U.S. DPF)\n- mechanism: SCC\n  text: such as Standard Contractual Clauses or the Data Privacy Framework mechanism\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to request account deletion or deletion of end-user data via the deletion request control\n  text: If you would like to delete your account, please email [email protected] .\nrights:\n- right: access, correct, erase and restrict processing\n  text: you may have the right to access, correct, erase and restrict the processing of your personal data.\n- right: object to processing\n  text: You may also have the right to object to Branch’s processing of your data\n- right: opt out of promotional emails\n  text: You can opt-out of receiving promotional emails from us by following the instructions in those emails\nsale_or_sharing:\n  stance: prohibited\n  text: We do not\
  \ rent or sell customer end user data.\n"
source_yaml_url: https://artifacts.apis.io/branch-messenger/privacy/branch-messenger-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Branch's own page on 2026-11-09.
synthetic: false
tags:
- Mobile
- Deep Linking
- Attribution
- Marketing
- Analytics
---
