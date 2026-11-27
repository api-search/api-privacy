---
api_specs:
- filename: criteo-accounts-api-openapi.yml
  format: yaml
  label: Criteo Accounts API
  slug: criteo-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-accounts-api-openapi.yml
- filename: criteo-advertiser-api-openapi.yml
  format: yaml
  label: Criteo Advertiser API
  slug: criteo-advertiser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-advertiser-api-openapi.yml
- filename: criteo-analytics-api-openapi.yml
  format: yaml
  label: Criteo Analytics API
  slug: criteo-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-analytics-api-openapi.yml
- filename: criteo-audience-api-openapi.yml
  format: yaml
  label: Criteo Audience API
  slug: criteo-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-audience-api-openapi.yml
- filename: criteo-balance-api-openapi.yml
  format: yaml
  label: Criteo Balance API
  slug: criteo-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-balance-api-openapi.yml
- filename: criteo-billing-api-openapi.yml
  format: yaml
  label: Criteo Billing API
  slug: criteo-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-billing-api-openapi.yml
- filename: criteo-campaign-api-openapi.yml
  format: yaml
  label: Criteo Campaign API
  slug: criteo-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-campaign-api-openapi.yml
- filename: criteo-catalog-api-openapi.yml
  format: yaml
  label: Criteo Catalog API
  slug: criteo-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-catalog-api-openapi.yml
- filename: criteo-creative-api-openapi.yml
  format: yaml
  label: Criteo Creative API
  slug: criteo-creative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-creative-api-openapi.yml
- filename: criteo-gateway-api-openapi.yml
  format: yaml
  label: Criteo Gateway API
  slug: criteo-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-gateway-api-openapi.yml
- filename: criteo-reco-api-openapi.yml
  format: yaml
  label: Criteo Reco API
  slug: criteo-reco-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-reco-api-openapi.yml
- filename: criteo-segment-api-openapi.yml
  format: yaml
  label: Criteo Segment API
  slug: criteo-segment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/criteo/openapi/criteo-segment-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Criteo-generated identifier (“UID”) : Identifier assigned to the Criteo cookie set on your web browser'
  - category: device
    text: 'Device identifier : Advertising identifier of your device, including smartphone, tablet, or connected TV'
  - category: behavioral
    text: 'Selected shopping events : Products viewed, put in a shopping cart or purchased on an advertiser’s website or app'
  - category: location
    text: Information about your coarse location (country, region, or city) derived from your IP address.
  - category: device
    text: 'Device-level information : Technical details about your browser, apps, and device'
  deletion:
    route: Data Protection Officer contact or Click here to exercise your rights
    text: Click here to exercise your rights
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Display personalized advertising
    text: Displaying personalized advertising on websites, apps or other platforms, including by relying on real-time bidding.
  - purpose: Display contextual advertising
    text: Displaying relevant advertising based on the content of the web page, app or other platform you visit or use
  - purpose: Attribution & conversion measurement
    text: Matching purchases and app installations with campaign events, like clicks and displays of ads.
  - purpose: Fraud prevention
    text: Detecting activities that do not match human activity.
  - purpose: Data model training & service optimization
    text: Training data models to improve the performance of Criteo's advertising operations.
  retention:
  - period: 13 months
    scope: Ads data
    text: We retain data for 13 months from the date of collection
  rights:
  - right: Right of access
    text: You have the right to confirm with us whether your personal data is processed
  - right: Right to rectification
    text: You have the right to request the rectification of inaccurate or incomplete personal data concerning you.
  - right: Right to erasure
    text: In certain circumstances, you may have the right to ask us to erase your personal data.
  - right: Right to object
    text: Under certain circumstances, you may have the right to object
  - right: Right to data portability
    text: When we process your personal data based on your consent, you have the right to receive personal data
  - right: Right to lodge a complaint
    text: You also have the right to lodge a complaint with the competent data protection supervisory authority.
  role:
    text: Criteo, advertisers, and/or publishers act as joint data controllers (or “businesses”) for the processing activity consisting in storing or reading information
    value: both
  sale_or_sharing:
    stance: conditional
    text: In the past 12 months, we have disclosed or sold these categories of personal information for the commercial purpose of providing cross-context behavioral advertising
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: transfers to other countries such as the USA may be protected under arrangements such as the EU-US Data Protection Framework
  - mechanism: SCC
    text: This will include using appropriate safeguards such as the EU Standard Data Protection Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Criteo
provenance_date: '2026-11-09'
provider_name: Criteo
provider_slug: criteo
slug: criteo-privacy-policy
source_date: '2026-11-09'
source_filename: criteo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.criteo.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Criteo\naid: criteo\nurl: https://www.criteo.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Criteo, advertisers, and/or publishers act as joint data controllers (or “businesses”) for the processing\n    activity consisting in storing or reading information\ndata_categories:\n- category: identifying\n  text: 'Criteo-generated identifier (“UID”) : Identifier assigned to the Criteo cookie set on your web browser'\n- category: device\n  text: 'Device identifier : Advertising identifier of your device, including smartphone, tablet, or connected TV'\n- category: behavioral\n  text: 'Selected\
  \ shopping events : Products viewed, put in a shopping cart or purchased on an advertiser’s website\n    or app'\n- category: location\n  text: Information about your coarse location (country, region, or city) derived from your IP address.\n- category: device\n  text: 'Device-level information : Technical details about your browser, apps, and device'\npurposes:\n- purpose: Display personalized advertising\n  text: Displaying personalized advertising on websites, apps or other platforms, including by relying on real-time\n    bidding.\n- purpose: Display contextual advertising\n  text: Displaying relevant advertising based on the content of the web page, app or other platform you visit or\n    use\n- purpose: Attribution & conversion measurement\n  text: Matching purchases and app installations with campaign events, like clicks and displays of ads.\n- purpose: Fraud prevention\n  text: Detecting activities that do not match human activity.\n- purpose: Data model training & service optimization\n\
  \  text: Training data models to improve the performance of Criteo's advertising operations.\nretention:\n- scope: Ads data\n  period: 13 months\n  text: We retain data for 13 months from the date of collection\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: transfers to other countries such as the USA may be protected under arrangements such as the EU-US Data\n    Protection Framework\n- mechanism: SCC\n  text: This will include using appropriate safeguards such as the EU Standard Data Protection Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data Protection Officer contact or Click here to exercise your rights\n  text: Click here to exercise your rights\nrights:\n- right: Right of access\n  text: You have the right to confirm with us whether your personal data is processed\n- right: Right to rectification\n  text: You have the right to request the rectification of inaccurate or incomplete personal data\
  \ concerning you.\n- right: Right to erasure\n  text: In certain circumstances, you may have the right to ask us to erase your personal data.\n- right: Right to object\n  text: Under certain circumstances, you may have the right to object\n- right: Right to data portability\n  text: When we process your personal data based on your consent, you have the right to receive personal data\n- right: Right to lodge a complaint\n  text: You also have the right to lodge a complaint with the competent data protection supervisory authority.\nsale_or_sharing:\n  stance: conditional\n  text: In the past 12 months, we have disclosed or sold these categories of personal information for the commercial\n    purpose of providing cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/criteo/privacy/criteo-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Criteo's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Agent Skills
- Analytics
- Audiences
- Campaigns
- Catalog
- Commerce
- Commerce Media
- Display Advertising
- Marketing
- MCP
- Media
- OAuth
- OpenAPI
- Reporting
- Retail
- Retail Media
- Sponsored Products
- A2A
- AdTech
- Authentication
---
