---
api_specs:
- filename: humana-clinical-api-openapi.yml
  format: yaml
  label: Humana Clinical API
  slug: humana-clinical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humana/openapi/humana-clinical-api-openapi.yml
- filename: humana-coverage-api-openapi.yml
  format: yaml
  label: Humana Coverage API
  slug: humana-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humana/openapi/humana-coverage-api-openapi.yml
- filename: humana-demographic-api-openapi.yml
  format: yaml
  label: Humana Demographic API
  slug: humana-demographic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humana/openapi/humana-demographic-api-openapi.yml
- filename: humana-medications-api-openapi.yml
  format: yaml
  label: Humana Medications API
  slug: humana-medications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humana/openapi/humana-medications-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Direct and personal identifiers: This information includes your name, email, any username and password that you may provide, your address, your tax identification number or social security number, unique identifiers (such as a mobile device ID)'
  - category: demographic
    text: 'Demographic information: Under certain circumstances, we may collect Personal Information regarding your gender, race, or other protected classification data.'
  - category: financial
    text: 'Payment or banking information: Credit card number, name on credit card, expiration date, security code, and billing address.'
  - category: device
    text: 'Electronic network activity: We collect information regarding your use of our websites and mobile applications.'
  - category: location
    text: 'Geolocation information: We may collect information about the location from which you are accessing our mobile applications.'
  - category: behavioral
    text: 'Inferences: We may develop inferences about you using the data set forth above.'
  - category: health
    text: health data in your myHumana.com member portal, may also qualify as sensitive Personal Information.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing services
    text: To provide you the services, including health insurance products, wellness products or providers, or healthcare
  - purpose: Marketing
    text: To send marketing and promotional materials, including information relating to our products, services, sales, or promotions or those of a third party
  - purpose: Analytics and improvement
    text: To administer, maintain, evaluate, and improve our websites, mobile applications, and services, and to develop new products and services
  - purpose: Legal obligations
    text: We use Personal Information to comply with our legal or regulatory obligations, to establish or exercise our rights, and to defend against a legal claim.
  - purpose: Security and fraud prevention
    text: We use Personal Information to detect, investigate, prevent, or take action regarding possible malicious, deceptive, fraudulent, or illegal activity
  rights:
  - right: Access
    text: 'Right to access: You may have the right to obtain from us confirmation as to whether or not Personal Information concerning you is being processed'
  - right: Correction
    text: 'Right to correction: You may have the right to request that we correct any Personal Information about you that is inaccurate.'
  - right: Deletion
    text: 'Right to deletion: You may have the right to request that we erase your Personal Information, under certain conditions.'
  - right: Restrict processing
    text: 'Right to restrict processing: You may have the right to request that we restrict the processing of your Personal Information, under certain conditions.'
  - right: Data portability
    text: 'Right to data portability: You may have the right to request that we transfer the Personal Information we have collected about you to another organization, or directly to you'
  role:
    text: Humana is a controller (i.e., responsible party) of your Personal Information including when we, or service providers acting on our behalf, administer the services.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share Personal Information, except to the extent cookies or other tracking technologies constitute sharing.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Humana
provenance_date: '2026-11-09'
provider_name: Humana
provider_slug: humana
slug: humana-privacy-policy
source_date: '2026-11-09'
source_filename: humana-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.humana.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Humana\naid: humana\nurl: https://www.humana.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Humana is a controller (i.e., responsible party) of your Personal Information including when we, or service\n    providers acting on our behalf, administer the services.\ndata_categories:\n- category: identifying\n  text: 'Direct and personal identifiers: This information includes your name, email, any username and password\n    that you may provide, your address, your tax identification number or social security number, unique identifiers\n    (such as a mobile device ID)'\n\
  - category: demographic\n  text: 'Demographic information: Under certain circumstances, we may collect Personal Information regarding your\n    gender, race, or other protected classification data.'\n- category: financial\n  text: 'Payment or banking information: Credit card number, name on credit card, expiration date, security code,\n    and billing address.'\n- category: device\n  text: 'Electronic network activity: We collect information regarding your use of our websites and mobile applications.'\n- category: location\n  text: 'Geolocation information: We may collect information about the location from which you are accessing our\n    mobile applications.'\n- category: behavioral\n  text: 'Inferences: We may develop inferences about you using the data set forth above.'\n- category: health\n  text: health data in your myHumana.com member portal, may also qualify as sensitive Personal Information.\npurposes:\n- purpose: Providing services\n  text: To provide you the services, including\
  \ health insurance products, wellness products or providers, or healthcare\n- purpose: Marketing\n  text: To send marketing and promotional materials, including information relating to our products, services, sales,\n    or promotions or those of a third party\n- purpose: Analytics and improvement\n  text: To administer, maintain, evaluate, and improve our websites, mobile applications, and services, and to develop\n    new products and services\n- purpose: Legal obligations\n  text: We use Personal Information to comply with our legal or regulatory obligations, to establish or exercise\n    our rights, and to defend against a legal claim.\n- purpose: Security and fraud prevention\n  text: We use Personal Information to detect, investigate, prevent, or take action regarding possible malicious,\n    deceptive, fraudulent, or illegal activity\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: null\n  text: null\nrights:\n- right: Access\n  text: 'Right to access: You may have the right to obtain from us confirmation as to whether or not Personal Information\n    concerning you is being processed'\n- right: Correction\n  text: 'Right to correction: You may have the right to request that we correct any Personal Information about you\n    that is inaccurate.'\n- right: Deletion\n  text: 'Right to deletion: You may have the right to request that we erase your Personal Information, under certain\n    conditions.'\n- right: Restrict processing\n  text: 'Right to restrict processing: You may have the right to request that we restrict the processing of your\n    Personal Information, under certain conditions.'\n- right: Data portability\n  text: 'Right to data portability: You may have the right to request that we transfer the Personal Information\n    we have collected about you to another organization, or directly to you'\nsale_or_sharing:\n  stance: prohibited\n  text:\
  \ We do not sell or share Personal Information, except to the extent cookies or other tracking technologies\n    constitute sharing.\n"
source_yaml_url: https://artifacts.apis.io/humana/privacy/humana-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Humana's own page on 2026-11-09.
synthetic: false
tags:
- FHIR
- Health Insurance
- Healthcare
- Interoperability
- Medicare
- Fortune 100
---
