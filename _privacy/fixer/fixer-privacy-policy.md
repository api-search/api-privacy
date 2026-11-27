---
api_specs:
- filename: fixer-conversion-api-openapi.yml
  format: yaml
  label: Fixer Conversion API
  slug: fixer-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixer/openapi/fixer-conversion-api-openapi.yml
- filename: fixer-fluctuation-api-openapi.yml
  format: yaml
  label: Fixer Fluctuation API
  slug: fixer-fluctuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixer/openapi/fixer-fluctuation-api-openapi.yml
- filename: fixer-rates-api-openapi.yml
  format: yaml
  label: Fixer Rates API
  slug: fixer-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixer/openapi/fixer-rates-api-openapi.yml
- filename: fixer-symbols-api-openapi.yml
  format: yaml
  label: Fixer Symbols API
  slug: fixer-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixer/openapi/fixer-symbols-api-openapi.yml
- filename: fixer-time-series-api-openapi.yml
  format: yaml
  label: Fixer Time Series API
  slug: fixer-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fixer/openapi/fixer-time-series-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal information means any information that may be used to identify you, such as, your name, title, phone number, email address, or mailing address.
  - category: financial
    text: billing name and address, credit card number (“Billing Information”)
  - category: device
    text: machine information, IP address, license key, information about the operation system and/or user environment where the product is installed
  - category: location
    text: your location, your browser type, your Internet service provider and/or mobile carrier
  - category: behavioral
    text: the pages and files you viewed, your searches, your operating system and system configuration information, and date/time stamps associated with your usage
  deletion:
    route: Request to delete certain information in your account
    text: When you decide to delete certain information in your account, we will fulfill your request and update this information on our platform.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing websites and services
    text: The Company uses Data about the Company’s customers to perform the Services requested and fulfill its obligations under applicable terms of use/service
  - purpose: Displaying personalized advertisements
    text: We process your Data to conduct marketing research, advertise to you, provide personalized information about us on and off our websites
  - purpose: Sending marketing communications
    text: We will process your Data to send you marketing information, product recommendations and other non-transactional communications
  retention:
  - period: null
    scope: Personal information
    text: we may retain your information during the time in which you have an account to use our Website or Services and for a reasonable period of time afterward.
  rights:
  - right: Right of access, objection, restriction of processing, erasure, and portability
    text: Right of access, objection, restriction of processing, erasure, and portability.
  - right: Right to withdraw consent
    text: You also have the right to withdraw your consent at any time when we process your personal data based on your consent.
  - right: Right to opt-out of direct marketing
    text: You have the right to opt-out at any time to receiving marketing materials from us
  - right: Right to lodge a complaint with a supervisory authority
    text: you have the right to lodge a complaint with a supervisory authority
  role:
    text: apilayer Data Products GmbH (the “Company”), is committed to respecting and protecting the privacy of our customers, partners, webinars attendees and website visitors.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: we do not sell, rent or trade email lists with other companies for marketing purposes.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we will ensure that the recipient of your Data offers an adequate level of protection, for instance by entering into standard contractual clauses for the transfer of data as approved by the European Commission (Art. 46 GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fixer
provenance_date: '2026-11-09'
provider_name: Fixer
provider_slug: fixer
slug: fixer-privacy-policy
source_date: '2026-11-09'
source_filename: fixer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fixer.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fixer\naid: fixer\nurl: https://fixer.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: apilayer Data Products GmbH (the “Company”), is committed to respecting and protecting the privacy of our\n    customers, partners, webinars attendees and website visitors.\ndata_categories:\n- category: identifying\n  text: Personal information means any information that may be used to identify you, such as, your name, title,\n    phone number, email address, or mailing address.\n- category: financial\n  text: billing name and address, credit card number (“Billing Information”)\n- category: device\n\
  \  text: machine information, IP address, license key, information about the operation system and/or user environment\n    where the product is installed\n- category: location\n  text: your location, your browser type, your Internet service provider and/or mobile carrier\n- category: behavioral\n  text: the pages and files you viewed, your searches, your operating system and system configuration information,\n    and date/time stamps associated with your usage\npurposes:\n- purpose: Providing websites and services\n  text: The Company uses Data about the Company’s customers to perform the Services requested and fulfill its obligations\n    under applicable terms of use/service\n- purpose: Displaying personalized advertisements\n  text: We process your Data to conduct marketing research, advertise to you, provide personalized information about\n    us on and off our websites\n- purpose: Sending marketing communications\n  text: We will process your Data to send you marketing information,\
  \ product recommendations and other non-transactional\n    communications\nretention:\n- scope: Personal information\n  period: null\n  text: we may retain your information during the time in which you have an account to use our Website or Services\n    and for a reasonable period of time afterward.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we will ensure that the recipient of your Data offers an adequate level of protection, for instance by entering\n    into standard contractual clauses for the transfer of data as approved by the European Commission (Art. 46 GDPR).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to delete certain information in your account\n  text: When you decide to delete certain information in your account, we will fulfill your request and update this\n    information on our platform.\nrights:\n- right: Right of access, objection, restriction of processing, erasure, and portability\n\
  \  text: Right of access, objection, restriction of processing, erasure, and portability.\n- right: Right to withdraw consent\n  text: You also have the right to withdraw your consent at any time when we process your personal data based on\n    your consent.\n- right: Right to opt-out of direct marketing\n  text: You have the right to opt-out at any time to receiving marketing materials from us\n- right: Right to lodge a complaint with a supervisory authority\n  text: you have the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: conditional\n  text: we do not sell, rent or trade email lists with other companies for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/fixer/privacy/fixer-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Fixer's own page on 2026-11-09.
synthetic: false
tags:
- Foreign Exchange
- ECB
- Conversion
- Historical Rates
- Time Series
- Fluctuation
- APILayer
- Public APIs
---
