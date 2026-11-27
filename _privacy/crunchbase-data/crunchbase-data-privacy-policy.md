---
api_specs:
- filename: crunchbase-data-autocomplete-api-openapi.yml
  format: yaml
  label: Crunchbase Autocomplete API
  slug: crunchbase-data-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-autocomplete-api-openapi.yml
- filename: crunchbase-data-deleted-entities-api-openapi.yml
  format: yaml
  label: Crunchbase Deleted Entities API
  slug: crunchbase-data-deleted-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-deleted-entities-api-openapi.yml
- filename: crunchbase-data-entity-api-openapi.yml
  format: yaml
  label: Crunchbase Entity API
  slug: crunchbase-data-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-entity-api-openapi.yml
- filename: crunchbase-data-metadata-api-openapi.yml
  format: yaml
  label: Crunchbase Metadata API
  slug: crunchbase-data-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-metadata-api-openapi.yml
- filename: crunchbase-data-search-api-openapi.yml
  format: yaml
  label: Crunchbase Search API
  slug: crunchbase-data-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crunchbase-data/openapi/crunchbase-data-search-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, address, phone number, IP address, username/password*, social media profile IDs/links, personal website URL
  - category: financial
    text: Name, phone number, employment history, credit card type, credit card number, credit card expiration month/year, CVC code
  - category: demographic
    text: Optional Profile data, such as gender, race*, ethnicity*, sexual orientation*
  - category: behavioral
    text: Website & application usage, interaction w/ advertisement, browser/platform/device used, search history, tokenized information (to the extent it constitutes Personal Data), paywall hashes (to the extent it constitutes Personal Data)
  - category: location
    text: Approximate location derived from IP address, location data (city, country, state)
  - category: professional
    text: Employment history, use cases about you, role, current & past companies, current & past job titles, biography description, press references, professional investments, education, events, board and advisor roles
  deletion:
    route: Request via privacy@crunchbase.com or https://preferences.crunchbase.com/privacy
    text: You have the right to request that we delete the Personal Data that we have collected from you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate, improve, personalize Service
    text: We process Personal Data to operate, improve, understand and personalize our Service.
  - purpose: Communications and marketing
    text: To communicate with you about the Service, including Service announcements, updates or offers.
  - purpose: Fraud and security
    text: To protect against or deter fraudulent, illegal or harmful actions and maintain the safety, security and integrity of our Service.
  - purpose: Legal compliance
    text: To comply with our legal or contractual obligations, resolve disputes, and enforce our Terms of Service.
  retention:
  - period: null
    scope: Personal Data generally
    text: We retain Personal Data about you for as long as you have an open account with us or as otherwise necessary to provide the Service.
  rights:
  - right: Access
    text: You have a right to request the following information about our collection, use and disclosure of your Personal Data
  - right: Deletion
    text: You have the right to request that we delete the Personal Data that we have collected from you.
  - right: Correction
    text: You have a right to request that we correct inaccurate Personal Data we maintain about you.
  - right: Opt-out of sale or sharing
    text: You have the right to opt-out of the sale or sharing (as both terms are defined under the CCPA) of your Personal Data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: allowed
    text: we do sell, and, in the preceding 12 months, we have sold your Profile data to our customers and data partners
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Crunchbase
provenance_date: '2026-11-09'
provider_name: Crunchbase
provider_slug: crunchbase-data
slug: crunchbase-data-privacy-policy
source_date: '2026-11-09'
source_filename: crunchbase-data-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://about.crunchbase.com/terms-of-service/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Crunchbase\naid: crunchbase-data\nurl: https://about.crunchbase.com/terms-of-service/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, address, phone number, IP address, username/password*, social media profile IDs/links,\n    personal website URL\n- category: financial\n  text: Name, phone number, employment history, credit card type, credit card number, credit card expiration month/year,\n    CVC code\n- category: demographic\n  text: Optional Profile data, such as gender, race*, ethnicity*, sexual orientation*\n\
  - category: behavioral\n  text: Website & application usage, interaction w/ advertisement, browser/platform/device used, search history,\n    tokenized information (to the extent it constitutes Personal Data), paywall hashes (to the extent it constitutes\n    Personal Data)\n- category: location\n  text: Approximate location derived from IP address, location data (city, country, state)\n- category: professional\n  text: Employment history, use cases about you, role, current & past companies, current & past job titles, biography\n    description, press references, professional investments, education, events, board and advisor roles\npurposes:\n- purpose: Operate, improve, personalize Service\n  text: We process Personal Data to operate, improve, understand and personalize our Service.\n- purpose: Communications and marketing\n  text: To communicate with you about the Service, including Service announcements, updates or offers.\n- purpose: Fraud and security\n  text: To protect against or\
  \ deter fraudulent, illegal or harmful actions and maintain the safety, security and\n    integrity of our Service.\n- purpose: Legal compliance\n  text: To comply with our legal or contractual obligations, resolve disputes, and enforce our Terms of Service.\nretention:\n- scope: Personal Data generally\n  period: null\n  text: We retain Personal Data about you for as long as you have an open account with us or as otherwise necessary\n    to provide the Service.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via privacy@crunchbase.com or https://preferences.crunchbase.com/privacy\n  text: You have the right to request that we delete the Personal Data that we have collected from you.\nrights:\n- right: Access\n  text: You have a right to request the following information about our collection, use and disclosure of your Personal\n    Data\n- right: Deletion\n  text: You have the right\
  \ to request that we delete the Personal Data that we have collected from you.\n- right: Correction\n  text: You have a right to request that we correct inaccurate Personal Data we maintain about you.\n- right: Opt-out of sale or sharing\n  text: You have the right to opt-out of the sale or sharing (as both terms are defined under the CCPA) of your\n    Personal Data.\nsale_or_sharing:\n  stance: allowed\n  text: we do sell, and, in the preceding 12 months, we have sold your Profile data to our customers and data partners\n"
source_yaml_url: https://artifacts.apis.io/crunchbase-data/privacy/crunchbase-data-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Crunchbase's own page on 2026-11-09.
synthetic: false
tags:
- Company Data
- Web Intelligence
- Funding Data
- Firmographics
- B2B Data
- investor-data
- Reference Data
- Private Markets
- Predictions
- Market Insights
- MCP
- Fortune 1000
- Startups
---
