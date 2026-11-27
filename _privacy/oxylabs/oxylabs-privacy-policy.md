---
api_specs:
- filename: oxylabs-login-api-openapi.yml
  format: yaml
  label: Oxylabs Login API
  slug: oxylabs-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxylabs/openapi/oxylabs-login-api-openapi.yml
- filename: oxylabs-queries-api-openapi.yml
  format: yaml
  label: Oxylabs Queries API
  slug: oxylabs-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxylabs/openapi/oxylabs-queries-api-openapi.yml
- filename: oxylabs-stats-api-openapi.yml
  format: yaml
  label: Oxylabs Stats API
  slug: oxylabs-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxylabs/openapi/oxylabs-stats-api-openapi.yml
- filename: oxylabs-users-api-openapi.yml
  format: yaml
  label: Oxylabs Users API
  slug: oxylabs-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oxylabs/openapi/oxylabs-users-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, surname, email address, contact details such as your phone number, address, company name, industry
  - category: financial
    text: credit card information (last four digits of your credit card number)
  - category: device
    text: usage data (such as access logs, activity history, preferences)
  - category: communication
    text: audio recordings (voice recordings) of the interview, capturing spoken responses and feedback; video recordings of the person‘s image during the interview
  deletion:
    route: email privacy@oxylabs.io
    text: If you would like to edit your information or delete it, you can email us at privacy@oxylabs.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and self-service access
    text: The personal information collected through registration, self-service functionalities is used exclusively to create the account that gives you access to the Oxylabs.io dashboard and our services
  - purpose: responding to inquiries
    text: If you contact us, we process your personal data for the purposes of responding to your inquiry and administering it.
  - purpose: product information and marketing
    text: Oxylabs.io may use your personal data to inform you about our services.
  - purpose: improving products via client interviews
    text: The data collected from these interviews is used solely for internal business purposes to make informed decisions to improve our products
  retention:
  - period: 5 years
    scope: communication related personal data
    text: Oxylabs.io stores communication related personal data up to 5 years from our last contact with you.
  - period: one (1) year
    scope: interview recordings and associated data
    text: The interview recordings and associated data will be retained for one (1) year from the date of the interview.
  rights:
  - right: access
    text: to get familiar with your personal data and how it is processed
  - right: restriction
    text: to demand restricting the processing of your personal data
  - right: portability
    text: to demand to transfer your personal data to another data controller or provide it directly to you in a convenient format
  - right: objection
    text: to object to processing of your personal data, if it is processed on the basis of a legitimate interest
  - right: withdraw consent
    text: in cases where your personal data is processed on a separate consent basis, you have the right at any time to withdraw your consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Many of those that are incorporated in US are members of EU – US Privacy Framework Program
  - mechanism: SCC
    text: entering into agreements with standard data protection clauses adopted by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Oxylabs
provenance_date: '2026-11-10'
provider_name: Oxylabs
provider_slug: oxylabs
slug: oxylabs-privacy-policy
source_date: '2026-11-10'
source_filename: oxylabs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://oxylabs.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Oxylabs\naid: oxylabs\nurl: https://oxylabs.io/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name, surname, email address, contact details such as your phone number, address, company name, industry\n- category: financial\n  text: credit card information (last four digits of your credit card number)\n- category: device\n  text: usage data (such as access logs, activity history, preferences)\n- category: communication\n  text: audio recordings (voice recordings) of the interview, capturing spoken responses and feedback; video\
  \ recordings\n    of the person‘s image during the interview\npurposes:\n- purpose: account creation and self-service access\n  text: The personal information collected through registration, self-service functionalities is used exclusively\n    to create the account that gives you access to the Oxylabs.io dashboard and our services\n- purpose: responding to inquiries\n  text: If you contact us, we process your personal data for the purposes of responding to your inquiry and administering\n    it.\n- purpose: product information and marketing\n  text: Oxylabs.io may use your personal data to inform you about our services.\n- purpose: improving products via client interviews\n  text: The data collected from these interviews is used solely for internal business purposes to make informed\n    decisions to improve our products\nretention:\n- scope: communication related personal data\n  period: 5 years\n  text: Oxylabs.io stores communication related personal data up to 5 years from our last\
  \ contact with you.\n- scope: interview recordings and associated data\n  period: one (1) year\n  text: The interview recordings and associated data will be retained for one (1) year from the date of the interview.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Many of those that are incorporated in US are members of EU – US Privacy Framework Program\n- mechanism: SCC\n  text: entering into agreements with standard data protection clauses adopted by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@oxylabs.io\n  text: If you would like to edit your information or delete it, you can email us at privacy@oxylabs.io .\nrights:\n- right: access\n  text: to get familiar with your personal data and how it is processed\n- right: restriction\n  text: to demand restricting the processing of your personal data\n- right: portability\n  text: to demand to transfer your personal data to another\
  \ data controller or provide it directly to you in a convenient\n    format\n- right: objection\n  text: to object to processing of your personal data, if it is processed on the basis of a legitimate interest\n- right: withdraw consent\n  text: in cases where your personal data is processed on a separate consent basis, you have the right at any time\n    to withdraw your consent\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oxylabs/privacy/oxylabs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from Oxylabs's own page on 2026-11-10.
synthetic: false
tags:
- AI Web Scraping
- Bot Mitigation Bypass
- CAPTCHA Solving
- Data Extraction
- Datacenter Proxies
- Datasets
- E-Commerce Data
- Browser Automation
- ISP Proxies
- Mobile Proxies
- Proxies
- Residential Proxies
- SERP
- Scraper API
- Web Scraping
- Web Data
- Web Intelligence
- Web Unblocker
---
