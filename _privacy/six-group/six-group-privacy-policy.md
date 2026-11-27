---
api_specs:
- filename: downloads
  format: yaml
  label: SIX bLink API
  slug: blink-api
  spec_type: Postman
  url: https://docs.blink.six-group.com/docs/downloads
- filename: six-group-card-management-api-openapi.yml
  format: yaml
  label: SIX Debi X API
  slug: debix-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-card-management-api-openapi.yml
- filename: six-group-3ds-authentication-api-openapi.yml
  format: yaml
  label: SIX debiX Auth Provider API
  slug: debix-auth-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-3ds-authentication-api-openapi.yml
- filename: six-group-iban-api-openapi.yml
  format: yaml
  label: Swiss Bank Master API
  slug: swiss-bank-master-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-iban-api-openapi.yml
- filename: six-group-status-api-openapi.yml
  format: yaml
  label: SIC Service Status API
  slug: sic-service-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-status-api-openapi.yml
- filename: six-group-calendar-api-openapi.yml
  format: yaml
  label: SIC Clearing Day Calendar API
  slug: sic-clearing-day-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-calendar-api-openapi.yml
- filename: six-group-detailedsettlementinformation-api-openapi.yml
  format: yaml
  label: Settlement Info Reporting API
  slug: settlement-info-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-detailedsettlementinformation-api-openapi.yml
- filename: six-group-3-ds-api-openapi.yml
  format: yaml
  label: SIX 3 DS API
  slug: six-group-3-ds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-3-ds-api-openapi.yml
- filename: six-group-bank-master-api-openapi.yml
  format: yaml
  label: SIX Bank Master API
  slug: six-group-bank-master-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/six-group/openapi/six-group-bank-master-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: SIX processes in general the personal data such as name, gender, address, e-mail address, telephone that the user expressly and actively makes available to us.
  - category: device
    text: The web server of SIX – and in the case of www.six-structured-products.com the web server of Ariva.de AG – automatically records details of the user's visit such as IP address, browser type and version, operating system used, originating website, pages accessed, date, length of visit.
  - category: other
    text: In the case of registration, attendance and realization of events, SIX may incidentally process the image and/or voice that appears in the photographs and videos taken during the corresponding event.
  deletion:
    route: Request deletion via data subject rights; contact Data Protection Officer
    text: to request the deletion of personal data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Technical management and research of websites
    text: Technical management as well as research and further development of websites
  - purpose: User administration, marketing and market research
    text: User administration, marketing, and market research, including to send communications, newsletters and information on SIX campaigns products and services
  - purpose: Selecting competition winners and awarding prizes
    text: Selecting competition winners and awarding prizes, to manage registration, attendance and realization of corporate actions offered and organized by SIX or its partners.
  - purpose: Management of data subject right requests
    text: Management of data subject right requests.
  retention:
  - period: null
    scope: Personal data generally
    text: SIX will only retain your personal data for as long as necessary to fulfill the purpose for which they were collected or to comply with legal or regulatory requirements.
  rights:
  - right: Access
    text: to receive information on whether SIX may save Personal Data and what form this Personal Data may take
  - right: Rectification
    text: to request the rectification of personal data if it is incorrect
  - right: Deletion
    text: to request the deletion of personal data
  - right: Restriction
    text: to request restrictions on processing personal data
  - right: Portability
    text: to receive personal data in a structured, accessible and machine-readable format (if available)
  - right: Objection
    text: or to submit an objection to processing, especially for the purpose of direct advertising
  role:
    text: The legal entities listed below are controller of your personal data and responsible for processing your data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When Personal Data of the User are transferred to other countries, SIX will ensure data protection by granting the protection level required by the applicable law, e.g. by adopting EU Standard Contractual Clauses (SCC) or other legally recognized mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SIX
provenance_date: '2026-11-10'
provider_name: SIX
provider_slug: six-group
slug: six-group-privacy-policy
source_date: '2026-11-10'
source_filename: six-group-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.six-group.com/en/services/legal/privacy/privacy-statement.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SIX\naid: six-group\nurl: https://www.six-group.com/en/services/legal/privacy/privacy-statement.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The legal entities listed below are controller of your personal data and responsible for processing your\n    data.\ndata_categories:\n- category: identifying\n  text: SIX processes in general the personal data such as name, gender, address, e-mail address, telephone that\n    the user expressly and actively makes available to us.\n- category: device\n  text: The web server of SIX – and in the case of www.six-structured-products.com the web server\
  \ of Ariva.de AG\n    – automatically records details of the user's visit such as IP address, browser type and version, operating\n    system used, originating website, pages accessed, date, length of visit.\n- category: other\n  text: In the case of registration, attendance and realization of events, SIX may incidentally process the image\n    and/or voice that appears in the photographs and videos taken during the corresponding event.\npurposes:\n- purpose: Technical management and research of websites\n  text: Technical management as well as research and further development of websites\n- purpose: User administration, marketing and market research\n  text: User administration, marketing, and market research, including to send communications, newsletters and information\n    on SIX campaigns products and services\n- purpose: Selecting competition winners and awarding prizes\n  text: Selecting competition winners and awarding prizes, to manage registration, attendance and realization\
  \ of\n    corporate actions offered and organized by SIX or its partners.\n- purpose: Management of data subject right requests\n  text: Management of data subject right requests.\nretention:\n- scope: Personal data generally\n  period: null\n  text: SIX will only retain your personal data for as long as necessary to fulfill the purpose for which they were\n    collected or to comply with legal or regulatory requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: When Personal Data of the User are transferred to other countries, SIX will ensure data protection by granting\n    the protection level required by the applicable law, e.g. by adopting EU Standard Contractual Clauses (SCC)\n    or other legally recognized mechanism.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via data subject rights; contact Data Protection Officer\n  text: to request the deletion of personal data\nrights:\n-\
  \ right: Access\n  text: to receive information on whether SIX may save Personal Data and what form this Personal Data may take\n- right: Rectification\n  text: to request the rectification of personal data if it is incorrect\n- right: Deletion\n  text: to request the deletion of personal data\n- right: Restriction\n  text: to request restrictions on processing personal data\n- right: Portability\n  text: to receive personal data in a structured, accessible and machine-readable format (if available)\n- right: Objection\n  text: or to submit an objection to processing, especially for the purpose of direct advertising\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/six-group/privacy/six-group-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from SIX's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Reference Data
- Corporate Actions
- Real-Time
- Exchange
- Open Banking
- Payments
- Switzerland
---
