---
api_specs:
- filename: simon-data-contacts-api-openapi.yml
  format: yaml
  label: Simon Data Contacts API
  slug: simon-data-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simon-data/openapi/simon-data-contacts-api-openapi.yml
- filename: simon-data-events-api-openapi.yml
  format: yaml
  label: Simon Data Events API
  slug: simon-data-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simon-data/openapi/simon-data-events-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: The types of information we may collect directly from you include your name, username, email address, postal address, phone number, employer’s name, job title
  - category: financial
    text: transactional information (including services purchased or subscribed to and billing address)
  - category: device
    text: device ID or unique identifier, device type
  - category: location
    text: geolocation information
  - category: behavioral
    text: statistics on page views, traffic to and from the sites, referral URL, ad data
  deletion:
    route: Email PRIVACY@SIMON.AI to request erasure
    text: 'Erasure: You can request that we erase some or all of your Personal Data from our systems.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate and improve the platform
    text: Provide, operate, maintain and improve the Simon AI Platform.
  - purpose: Advertising
    text: Showing you advertisements, including interest-based, or online behavioral or targeted advertising.
  - purpose: Marketing and selling the platform
    text: Marketing and selling the Simon AI Platform.
  residency:
  - region: United States
    text: We, and third-party service providers on our behalf, store and process your Personal Data in the United States and elsewhere in the world.
  retention:
  - period: as long as you have an open account
    scope: Personal Data
    text: We retain Personal Data about you for as long as you have an open account with us or as otherwise necessary to provide you Services
  rights:
  - right: Access
    text: 'Access: You can request more information about the Personal Data we hold about you and request a copy of such Personal Data.'
  - right: Rectification
    text: 'Rectification: If you believe that any Personal Data we are holding about you is incorrect or incomplete, you can request that we correct or supplement such data.'
  - right: Erasure
    text: 'Erasure: You can request that we erase some or all of your Personal Data from our systems.'
  - right: Portability
    text: 'Portability: You can ask for a copy of your Personal Data in a machine-readable format.'
  - right: Objection
    text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal Data for certain purposes, such as for direct marketing purposes.'
  - right: Restriction of Processing
    text: 'Restriction of Processing: You can ask us to restrict further processing of your Personal Data.'
  role:
    text: Simon will be the controller of your Personal Data processed in connection with the Services.
    value: both
  sale_or_sharing:
    stance: unstated
    text: Please note that we do not currently sell your Personal Data as sales are defined in Nevada Revised Statutes Chapter 603A.
  subprocessors:
    text: Simon AI’s current list of subprocessors can be found here
    url: null
  transfers:
  - mechanism: DPF
    text: Simon AI complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Simon Data
provenance_date: '2026-11-10'
provider_name: Simon Data
provider_slug: simon-data
slug: simon-data-privacy-policy
source_date: '2026-11-10'
source_filename: simon-data-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.simon.ai/terms/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Simon Data\naid: simon-data\nurl: https://www.simon.ai/terms/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Simon will be the controller of your Personal Data processed in connection with the Services.\ndata_categories:\n- category: contact\n  text: The types of information we may collect directly from you include your name, username, email address, postal\n    address, phone number, employer’s name, job title\n- category: financial\n  text: transactional information (including services purchased or subscribed to and billing address)\n- category: device\n  text: device ID or unique\
  \ identifier, device type\n- category: location\n  text: geolocation information\n- category: behavioral\n  text: statistics on page views, traffic to and from the sites, referral URL, ad data\npurposes:\n- purpose: Provide, operate and improve the platform\n  text: Provide, operate, maintain and improve the Simon AI Platform.\n- purpose: Advertising\n  text: Showing you advertisements, including interest-based, or online behavioral or targeted advertising.\n- purpose: Marketing and selling the platform\n  text: Marketing and selling the Simon AI Platform.\nretention:\n- scope: Personal Data\n  period: as long as you have an open account\n  text: We retain Personal Data about you for as long as you have an open account with us or as otherwise necessary\n    to provide you Services\nresidency:\n- region: United States\n  text: We, and third-party service providers on our behalf, store and process your Personal Data in the United\n    States and elsewhere in the world.\ntransfers:\n- mechanism:\
  \ DPF\n  text: Simon AI complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\nsubprocessors:\n  url: null\n  text: Simon AI’s current list of subprocessors can be found here\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email PRIVACY@SIMON.AI to request erasure\n  text: 'Erasure: You can request that we erase some or all of your Personal Data from our systems.'\nrights:\n- right: Access\n  text: 'Access: You can request more information about the Personal Data we hold about you and request a copy of\n    such Personal Data.'\n- right: Rectification\n  text: 'Rectification: If you believe that any Personal Data we are holding about you is incorrect or incomplete,\n    you can request that we correct or supplement such data.'\n- right: Erasure\n  text: 'Erasure: You can request that we erase some or all\
  \ of your Personal Data from our systems.'\n- right: Portability\n  text: 'Portability: You can ask for a copy of your Personal Data in a machine-readable format.'\n- right: Objection\n  text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal\n    Data for certain purposes, such as for direct marketing purposes.'\n- right: Restriction of Processing\n  text: 'Restriction of Processing: You can ask us to restrict further processing of your Personal Data.'\nsale_or_sharing:\n  stance: unstated\n  text: Please note that we do not currently sell your Personal Data as sales are defined in Nevada Revised Statutes\n    Chapter 603A.\n"
source_yaml_url: https://artifacts.apis.io/simon-data/privacy/simon-data-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Simon Data's own page on 2026-11-10.
synthetic: false
tags:
- Customer Data Platform
- CDP
- Marketing Automation
- Audience Segmentation
- Event Tracking
- Data Ingestion
- Personalization
- Marketing Technology
- Identity Resolution
- Customer Profiles
- Journey Orchestration
- Snowflake
---
