---
api_specs:
- filename: polygonscan-polygonscan-api-api-openapi.yml
  format: yaml
  label: PolygonScan PolygonScan API
  slug: polygonscan-polygonscan-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygonscan/openapi/polygonscan-polygonscan-api-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: personal information that links back to an individual, e.g., name, gender, date of birth, and other personal identification numbers
  - category: contact
    text: contact information, e.g., address, phone number and email address
  - category: device
    text: technical information, e.g., IP address for API services, browser type, device type, operating system, log data, API access logs
  - category: behavioral
    text: usage and behavioural data, e.g. browsing activity on our platform, search queries, access times, referral sources
  deletion:
    route: request or no longer required
    text: PolygonScan shall take all reasonable steps to ensure that all Personal Data is destroyed or permanently deleted when either requested or no longer required for the Purpose
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and perform services
    text: to enable us to provide and perform our services to you
  - purpose: business development and marketing analysis
    text: for business development purposes such as statistical and marketing analysis, systems testing, maintenance and development
  - purpose: marketing communications
    text: to communicate offers, product, services and information on products and activities
  - purpose: legal compliance
    text: to comply with any legal or regulatory requirements
  retention:
  - period: 5 days
    scope: raw web server site visit logs
    text: all raw web server site visit logs are retained for a minimum of 5 days only and then purged on an automated scheduled basis
  - period: 24-month period
    scope: inactive data
    text: prepare a disposal schedule for inactive data to be automatically purged within a 24-month period
  - period: at least 2 years
    scope: data breach records
    text: We will maintain a record of all data breaches for at least 2 years from the date of notification
  rights:
  - right: access
    text: request access to and to request correction of your Personal Data
  - right: withdraw consent
    text: to revoke or withdraw your consent to the processing of your Personal Data
  - right: restrict processing
    text: to restrict or limit the processing of your Personal Data
  - right: erasure
    text: to erase your Personal Data from all of our databases
  - right: portability
    text: to request a copy of your Personal Data in a structured, commonly used, and machine-readable format
  - right: opt-out of marketing
    text: to opt-out of receiving direct marketing materials at any time
  role:
    text: PolygonScan acting as a data controller and data processor
    value: both
  sale_or_sharing:
    stance: conditional
    text: We will not trade or sell your Personal Data to third parties without your consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we will implement organisational and technical measures by only transferring to Third Party Sites where the target location is compliant with data protection legislation or have the same or comparable data protection laws
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PolygonScan
provenance_date: '2026-11-10'
provider_name: PolygonScan
provider_slug: polygonscan
slug: polygonscan-privacy-policy
source_date: '2026-11-10'
source_filename: polygonscan-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://polygonscan.com/privacypolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PolygonScan\naid: polygonscan\nurl: https://polygonscan.com/privacypolicy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: PolygonScan acting as a data controller and data processor\ndata_categories:\n- category: identifying\n  text: personal information that links back to an individual, e.g., name, gender, date of birth, and other personal\n    identification numbers\n- category: contact\n  text: contact information, e.g., address, phone number and email address\n- category: device\n  text: technical information, e.g., IP address for API services, browser type, device type, operating system, log\n\
  \    data, API access logs\n- category: behavioral\n  text: usage and behavioural data, e.g. browsing activity on our platform, search queries, access times, referral\n    sources\npurposes:\n- purpose: provide and perform services\n  text: to enable us to provide and perform our services to you\n- purpose: business development and marketing analysis\n  text: for business development purposes such as statistical and marketing analysis, systems testing, maintenance\n    and development\n- purpose: marketing communications\n  text: to communicate offers, product, services and information on products and activities\n- purpose: legal compliance\n  text: to comply with any legal or regulatory requirements\nretention:\n- scope: raw web server site visit logs\n  period: 5 days\n  text: all raw web server site visit logs are retained for a minimum of 5 days only and then purged on an automated\n    scheduled basis\n- scope: inactive data\n  period: 24-month period\n  text: prepare a disposal schedule\
  \ for inactive data to be automatically purged within a 24-month period\n- scope: data breach records\n  period: at least 2 years\n  text: We will maintain a record of all data breaches for at least 2 years from the date of notification\nresidency: []\ntransfers:\n- mechanism: other\n  text: we will implement organisational and technical measures by only transferring to Third Party Sites where\n    the target location is compliant with data protection legislation or have the same or comparable data protection\n    laws\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request or no longer required\n  text: PolygonScan shall take all reasonable steps to ensure that all Personal Data is destroyed or permanently\n    deleted when either requested or no longer required for the Purpose\nrights:\n- right: access\n  text: request access to and to request correction of your Personal Data\n- right: withdraw consent\n  text: to revoke\
  \ or withdraw your consent to the processing of your Personal Data\n- right: restrict processing\n  text: to restrict or limit the processing of your Personal Data\n- right: erasure\n  text: to erase your Personal Data from all of our databases\n- right: portability\n  text: to request a copy of your Personal Data in a structured, commonly used, and machine-readable format\n- right: opt-out of marketing\n  text: to opt-out of receiving direct marketing materials at any time\nsale_or_sharing:\n  stance: conditional\n  text: We will not trade or sell your Personal Data to third parties without your consent.\n"
source_yaml_url: https://artifacts.apis.io/polygonscan/privacy/polygonscan-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from PolygonScan's own page on 2026-11-10.
synthetic: false
tags:
- Blockchain
- Polygon
- Explorer
- Web3
- EVM
- Smart Contracts
- DeFi
- Cryptocurrency
---
