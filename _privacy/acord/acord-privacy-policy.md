---
api_specs:
- filename: acord-claims-api-openapi.yml
  format: yaml
  label: ACORD Claims API
  slug: acord-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-claims-api-openapi.yml
- filename: acord-party-api-openapi.yml
  format: yaml
  label: ACORD Party API
  slug: acord-party-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-party-api-openapi.yml
- filename: acord-policy-api-openapi.yml
  format: yaml
  label: ACORD Policy API
  slug: acord-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-policy-api-openapi.yml
- filename: acord-underwriting-api-openapi.yml
  format: yaml
  label: ACORD Underwriting API
  slug: acord-underwriting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acord/openapi/acord-underwriting-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, role at work, work address, work contact details, business address and banking details
  - category: device
    text: your computer/device’s access date and time, browser, connection speed, internet protocol address, internet service provider, language, location, manufacturer, visit details, and operating system
  - category: behavioral
    text: search engine terms inputted by you
  - category: demographic
    text: date of birth, gender, current salary, compensation history
  - category: health
    text: information relating to your religion or health status
  deletion:
    route: contact legalwork@acord.org
    text: Request erasure of your Personal Information. This right enables you to ask us to delete or remove Personal Information where there is no good reason for us continuing to process such Personal Information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services and administrative tasks
    text: To provide our services (including technical support) and to carry out administrative tasks related to those services
  - purpose: marketing and communications
    text: to send you communications about our services (including marketing)
  - purpose: improve the Site
    text: To improve the Site and make the Site more useful to you and other users.
  - purpose: recruitment
    text: To assess your candidacy as a potential employee or contractor of ACORD.
  residency:
  - region: United States, England, Ireland, Italy
    text: servers located at off-site data centers located in the United States, England, Ireland and Italy
  retention:
  - period: null
    scope: personal information generally
    text: ACORD will retain Personal Information only as reasonably necessary for the purposes for which the Personal Information were collected.
  - period: null
    scope: client documentation
    text: ACORD generally retains client documentation for as long as there is an ongoing client relationship and an appropriate period thereafter
  rights:
  - right: access
    text: Request access to your Personal Information.
  - right: correction
    text: Request correction of the Personal Information that we hold about you.
  - right: erasure
    text: Request erasure of your Personal Information.
  - right: objection
    text: Object to processing of your Personal Information.
  - right: restriction
    text: Request the restriction of processing of your Personal Information.
  - right: portability
    text: Request the transfer of your Personal Information to another party.
  - right: opt out of sale or sharing
    text: The right to request that we not sell your Personal Information;
  - right: opt out of targeted advertising
    text: The right to opt out of targeted advertising;
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We may “sell” or “share” your information when we disclose certain information to our advertising partners, such as search history, cookie identifiers or IP addresses.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: 'European Commission: Standard Contractual Clauses for international transfers'
  - mechanism: DPF
    text: the EU-US Data Privacy Framework and the UK Data Bridge
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ACORD
provenance_date: '2026-11-09'
provider_name: ACORD
provider_slug: acord
slug: acord-privacy-policy
source_date: '2026-11-09'
source_filename: acord-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.acord.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ACORD\naid: acord\nurl: https://www.acord.org/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, role at work, work address, work contact details, business address and banking details\n- category: device\n  text: your computer/device’s access date and time, browser, connection speed, internet protocol address, internet\n    service provider, language, location, manufacturer, visit details, and operating system\n- category: behavioral\n  text: search engine terms inputted by you\n- category: demographic\n  text: date\
  \ of birth, gender, current salary, compensation history\n- category: health\n  text: information relating to your religion or health status\npurposes:\n- purpose: provide services and administrative tasks\n  text: To provide our services (including technical support) and to carry out administrative tasks related to those\n    services\n- purpose: marketing and communications\n  text: to send you communications about our services (including marketing)\n- purpose: improve the Site\n  text: To improve the Site and make the Site more useful to you and other users.\n- purpose: recruitment\n  text: To assess your candidacy as a potential employee or contractor of ACORD.\nretention:\n- scope: personal information generally\n  period: null\n  text: ACORD will retain Personal Information only as reasonably necessary for the purposes for which the Personal\n    Information were collected.\n- scope: client documentation\n  period: null\n  text: ACORD generally retains client documentation for as\
  \ long as there is an ongoing client relationship and\n    an appropriate period thereafter\nresidency:\n- region: United States, England, Ireland, Italy\n  text: servers located at off-site data centers located in the United States, England, Ireland and Italy\ntransfers:\n- mechanism: SCC\n  text: 'European Commission: Standard Contractual Clauses for international transfers'\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework and the UK Data Bridge\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact legalwork@acord.org\n  text: Request erasure of your Personal Information. This right enables you to ask us to delete or remove Personal\n    Information where there is no good reason for us continuing to process such Personal Information.\nrights:\n- right: access\n  text: Request access to your Personal Information.\n- right: correction\n  text: Request correction of the Personal Information that we hold about\
  \ you.\n- right: erasure\n  text: Request erasure of your Personal Information.\n- right: objection\n  text: Object to processing of your Personal Information.\n- right: restriction\n  text: Request the restriction of processing of your Personal Information.\n- right: portability\n  text: Request the transfer of your Personal Information to another party.\n- right: opt out of sale or sharing\n  text: The right to request that we not sell your Personal Information;\n- right: opt out of targeted advertising\n  text: The right to opt out of targeted advertising;\nsale_or_sharing:\n  stance: conditional\n  text: We may “sell” or “share” your information when we disclose certain information to our advertising partners,\n    such as search history, cookie identifiers or IP addresses.\n"
source_yaml_url: https://artifacts.apis.io/acord/privacy/acord-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ACORD's own page on 2026-11-09.
synthetic: false
tags:
- Claims
- Data Standards
- Insurance
- Policy
- Property and Casualty
- Reinsurance
- Standards
- Underwriting
- XML
---
