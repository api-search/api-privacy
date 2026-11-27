---
api_specs:
- filename: salsify-digital-assets-api-openapi.yml
  format: yaml
  label: Salsify Digital Assets API
  slug: salsify-digital-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-digital-assets-api-openapi.yml
- filename: salsify-export-runs-api-openapi.yml
  format: yaml
  label: Salsify Export Runs API
  slug: salsify-export-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-export-runs-api-openapi.yml
- filename: salsify-imports-api-openapi.yml
  format: yaml
  label: Salsify Imports API
  slug: salsify-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-imports-api-openapi.yml
- filename: salsify-lists-api-openapi.yml
  format: yaml
  label: Salsify Lists API
  slug: salsify-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-lists-api-openapi.yml
- filename: salsify-org-id-api-openapi.yml
  format: yaml
  label: Salsify <org ID> API
  slug: salsify-org-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-org-id-api-openapi.yml
- filename: salsify-products-api-openapi.yml
  format: yaml
  label: Salsify Products API
  slug: salsify-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-products-api-openapi.yml
- filename: salsify-properties-api-openapi.yml
  format: yaml
  label: Salsify Properties API
  slug: salsify-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-properties-api-openapi.yml
- filename: salsify-record-types-api-openapi.yml
  format: yaml
  label: Salsify Record Types API
  slug: salsify-record-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-record-types-api-openapi.yml
- filename: salsify-records-api-openapi.yml
  format: yaml
  label: Salsify Records API
  slug: salsify-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-records-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Your name; Email address; Address; Company name; Country Job title; Phone
  - category: identifying
    text: Your name; Email address; Address; Company name; Job title; Phone; Communications you send to us
  - category: device
    text: The information inside our log files includes internet protocol (“IP”) addresses, type of browser, Internet Service Provider (ISP), date/time stamp, referring/exit pages, clicked pages
  - category: financial
    text: Billing information (such as billing name, billing address, and credit card number)
  - category: health
    text: Health and safety information (in some instances)
  - category: communication
    text: If you communicate with us via a phone call, your voice and any other Personal Data voluntarily shared
  deletion:
    route: Request via privacy@salsify.com, the request portal or the personal data request form
    text: Upon receiving a verified request to delete personal data, we will do so unless otherwise authorized by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Performance of a contract
    text: We process your Personal Data to perform our contract with you for the provision of our services
  - purpose: Marketing and profiling
    text: Creating a user profile (profiling).
  - purpose: Fraud and security
    text: Detecting and preventing fraud and other harmful activity;
  - purpose: Statutory obligations
    text: We may process your data in order to fulfill our statutory obligations.
  retention:
  - period: null
    scope: Personal Data
    text: 'We reserve the right to retain any Personal Data as long as the Personal Data are needed to: (i) fulfill the purposes that are described in Section 5'
  rights:
  - right: Access
    text: 'Right of access: You may contact us to find out what information we hold about you.'
  - right: Rectification and erasure
    text: 'Right of rectification and erasure: You may correct your data and ask for it to be erased.'
  - right: Restrict processing
    text: Right to restrict processing. You may object to our carrying out of certain processing actions.
  - right: Portability
    text: 'Right of portability: You may ask us to forward items of your personal data in electronic format to you.'
  - right: Object
    text: Right to object to the processing of your personal data carried out on the basis of our legitimate interests.
  - right: Non-discrimination
    text: You have the right not to be discriminated against for the exercise of your California privacy rights described above.
  role:
    text: Alkemics SAS is the controller for your personal data. For all other individuals, Salsify, Inc. is the controller for your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not “sell” or “share” the Personal Data covered by this Policy and have not done so in the twelve months prior to the effective date of this Policy.
  subprocessors:
    text: For a list of our main service providers and the types of services they provide to us, please see this page
    url: https://www.salsify.com/privacy-policy
  transfers:
  - mechanism: SCC
    text: we will enter into “Standard Contractual Clauses” approved by the relevant authority or take other measures to provide an adequate level of data protection under EU, Swiss and UK law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Salsify
provenance_date: '2026-11-10'
provider_name: Salsify
provider_slug: salsify
slug: salsify-privacy-policy
source_date: '2026-11-10'
source_filename: salsify-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.salsify.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Salsify\naid: salsify\nurl: https://www.salsify.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Alkemics SAS is the controller for your personal data. For all other individuals, Salsify, Inc. is the controller\n    for your personal data.\ndata_categories:\n- category: contact\n  text: Your name; Email address; Address; Company name; Country Job title; Phone\n- category: identifying\n  text: Your name; Email address; Address; Company name; Job title; Phone; Communications you send to us\n- category: device\n  text: The information inside our log files includes internet protocol\
  \ (“IP”) addresses, type of browser, Internet\n    Service Provider (ISP), date/time stamp, referring/exit pages, clicked pages\n- category: financial\n  text: Billing information (such as billing name, billing address, and credit card number)\n- category: health\n  text: Health and safety information (in some instances)\n- category: communication\n  text: If you communicate with us via a phone call, your voice and any other Personal Data voluntarily shared\npurposes:\n- purpose: Performance of a contract\n  text: We process your Personal Data to perform our contract with you for the provision of our services\n- purpose: Marketing and profiling\n  text: Creating a user profile (profiling).\n- purpose: Fraud and security\n  text: Detecting and preventing fraud and other harmful activity;\n- purpose: Statutory obligations\n  text: We may process your data in order to fulfill our statutory obligations.\nretention:\n- scope: Personal Data\n  period: null\n  text: 'We reserve the right to retain\
  \ any Personal Data as long as the Personal Data are needed to: (i) fulfill\n    the purposes that are described in Section 5'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we will enter into “Standard Contractual Clauses” approved by the relevant authority or take other measures\n    to provide an adequate level of data protection under EU, Swiss and UK law.\nsubprocessors:\n  url: https://www.salsify.com/privacy-policy\n  text: For a list of our main service providers and the types of services they provide to us, please see this page\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via privacy@salsify.com, the request portal or the personal data request form\n  text: Upon receiving a verified request to delete personal data, we will do so unless otherwise authorized by\n    law.\nrights:\n- right: Access\n  text: 'Right of access: You may contact us to find out what information we hold about you.'\n- right: Rectification and erasure\n  text: 'Right\
  \ of rectification and erasure: You may correct your data and ask for it to be erased.'\n- right: Restrict processing\n  text: Right to restrict processing. You may object to our carrying out of certain processing actions.\n- right: Portability\n  text: 'Right of portability: You may ask us to forward items of your personal data in electronic format to you.'\n- right: Object\n  text: Right to object to the processing of your personal data carried out on the basis of our legitimate interests.\n- right: Non-discrimination\n  text: You have the right not to be discriminated against for the exercise of your California privacy rights described\n    above.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not “sell” or “share” the Personal Data covered by this Policy and have not done so in the twelve\n    months prior to the effective date of this Policy.\n"
source_yaml_url: https://artifacts.apis.io/salsify/privacy/salsify-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Salsify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Experience Management
- Product Information Management
- Digital Asset Management
- Commerce
- Retail
- Syndication
- Data Management
- Software-as-a-Service
---
