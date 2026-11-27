---
api_specs:
- filename: aol-openid-connect-api-openapi.yml
  format: yaml
  label: AOL OpenID Connect API
  slug: aol-openid-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aol/openapi/aol-openid-connect-api-openapi.yml
- filename: aol-oauth2-api-openapi.yml
  format: yaml
  label: AOL O Auth2 API
  slug: aol-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aol/openapi/aol-oauth2-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, phone number, postal address, IDs (“ Identity and Contact Data ”).
  - category: contact
    text: Name, email address, phone number, postal address, IDs (“ Identity and Contact Data ”).
  - category: location
    text: Information about your approximate location (for example, the country or city you are in) (“ Approximate Geolocation Information ”).
  - category: behavioral
    text: Information about your interaction with our Services, such as your browsing history and search history, and information about your interaction with our ads (“ Online activity information ”).
  - category: communication
    text: Information about the emails you send and receive, such as the subject line, the content of incoming and outgoing emails and attachments, and metadata about your emails, such as the times they are sent (“ Email Information ”).
  - category: financial
    text: Details about the payments made and the products and services purchased (“ Transaction data ”).
  - category: demographic
    text: Age, gender, marital status and socioeconomic information (for example, your level of education, employment status and income range) (“ Demographic Data ”)
  - category: device
    text: Technical data such as your IP address, your login data, browser type and version, hardware information, time zone setting and location
  deletion:
    route: Privacy dashboard or Data Protection Officer contact
    text: To contact us and exercise your rights, please visit your privacy dashboard, which you can access here . You may also contact our Data Protection Officer at dpo@teamaol.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To enable you to use our Services (“ Service Delivery ”).
  - purpose: Smart features
    text: To provide you with some specific, smart features, such as the smart email features
  - purpose: Service improvement
    text: To improve and develop our products and services (“ Service Improvement ”).
  - purpose: Tailored content
    text: To provide tailored content to you, including to build a content interest profile (“ Tailored Content ”).
  - purpose: Troubleshooting
    text: To ensure the quality and the proper functioning of the Services, by analyzing, preventing or correcting failures and bugs
  - purpose: Marketing
    text: To carry out marketing activities, and send you information and marketing communications about our products and services
  - purpose: Targeted advertising
    text: To show you personalized advertising, including by installing third party tracking technologies, and to measure the effectiveness of these ads (“ Targeted Advertising ”).
  retention:
  - period: three (3) years
    scope: Service Delivery data
    text: Personal data processed for Service Delivery will be kept for no more than three (3) years from your last interaction with our Services, or from the expiration of your subscription.
  - period: one (1) year
    scope: Troubleshooting data
    text: Personal data processed for the purposes of Troubleshooting will be kept for no more than one (1) year from your last interaction with our Services, or from the expiration of your subscription.
  - period: five (5) years
    scope: Customer Support data
    text: Personal data processed for Customer Support purposes will be kept for no more than five (5) years from the closure of the request.
  - period: ten (10) years
    scope: Defense data
    text: Personal data processed for Defense purposes will be kept for no more than ten (10) years from your last interaction with our Services, or from the expiration of your subscription.
  rights:
  - right: Access
    text: Right of access. You have the right to obtain information about the processing of your personal data and to access it.
  - right: Rectification
    text: Right to rectification. You have the right to ask for the update, rectification or integration of your personal data.
  - right: Erasure
    text: Right to erasure. You have the right to request the deletion of your personal data.
  - right: Restriction
    text: Right to restriction of processing. You have the right to request the restriction of the processing of your personal data.
  - right: Portability
    text: Right to data portability. You have the right to obtain a portable electronic copy of your personal data.
  - right: Object
    text: Right to object. Where we rely on our legitimate interest to process your personal data, you have the right to object to such processing
  - right: Withdraw consent
    text: Right to withdraw your consent. Where we rely on your consent to process your personal data, you have the right to withdraw your consent
  role:
    text: The Data Controller is AOL Media LLC, based in 770 Broadway, New York, NY 10003, United States of America.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Requiring third parties to sign a Data Processing Agreement which incorporates the appropriate Standard Contractual Clauses, or another legally applicable data transfer mechanism
  - mechanism: adequacy
    text: Transferring personal data to third parties residing in countries that have been deemed to provide an adequate level of protection for personal data by the European Commission or UK Information Commissioner’s Office
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AOL
provenance_date: '2026-11-09'
provider_name: AOL
provider_slug: aol
slug: aol-privacy-policy
source_date: '2026-11-09'
source_filename: aol-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://legal.aol.com/privacy/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AOL\naid: aol\nurl: https://legal.aol.com/privacy/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Data Controller is AOL Media LLC, based in 770 Broadway, New York, NY 10003, United States of America.\ndata_categories:\n- category: identifying\n  text: Name, email address, phone number, postal address, IDs (“ Identity and Contact Data ”).\n- category: contact\n  text: Name, email address, phone number, postal address, IDs (“ Identity and Contact Data ”).\n- category: location\n  text: Information about your approximate location (for example, the country or city you are in) (“\
  \ Approximate\n    Geolocation Information ”).\n- category: behavioral\n  text: Information about your interaction with our Services, such as your browsing history and search history,\n    and information about your interaction with our ads (“ Online activity information ”).\n- category: communication\n  text: Information about the emails you send and receive, such as the subject line, the content of incoming and\n    outgoing emails and attachments, and metadata about your emails, such as the times they are sent (“ Email Information\n    ”).\n- category: financial\n  text: Details about the payments made and the products and services purchased (“ Transaction data ”).\n- category: demographic\n  text: Age, gender, marital status and socioeconomic information (for example, your level of education, employment\n    status and income range) (“ Demographic Data ”)\n- category: device\n  text: Technical data such as your IP address, your login data, browser type and version, hardware information,\n\
  \    time zone setting and location\npurposes:\n- purpose: Service delivery\n  text: To enable you to use our Services (“ Service Delivery ”).\n- purpose: Smart features\n  text: To provide you with some specific, smart features, such as the smart email features\n- purpose: Service improvement\n  text: To improve and develop our products and services (“ Service Improvement ”).\n- purpose: Tailored content\n  text: To provide tailored content to you, including to build a content interest profile (“ Tailored Content ”).\n- purpose: Troubleshooting\n  text: To ensure the quality and the proper functioning of the Services, by analyzing, preventing or correcting\n    failures and bugs\n- purpose: Marketing\n  text: To carry out marketing activities, and send you information and marketing communications about our products\n    and services\n- purpose: Targeted advertising\n  text: To show you personalized advertising, including by installing third party tracking technologies, and to\n    measure\
  \ the effectiveness of these ads (“ Targeted Advertising ”).\nretention:\n- scope: Service Delivery data\n  period: three (3) years\n  text: Personal data processed for Service Delivery will be kept for no more than three (3) years from your last\n    interaction with our Services, or from the expiration of your subscription.\n- scope: Troubleshooting data\n  period: one (1) year\n  text: Personal data processed for the purposes of Troubleshooting will be kept for no more than one (1) year from\n    your last interaction with our Services, or from the expiration of your subscription.\n- scope: Customer Support data\n  period: five (5) years\n  text: Personal data processed for Customer Support purposes will be kept for no more than five (5) years from\n    the closure of the request.\n- scope: Defense data\n  period: ten (10) years\n  text: Personal data processed for Defense purposes will be kept for no more than ten (10) years from your last\n    interaction with our Services, or from\
  \ the expiration of your subscription.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Requiring third parties to sign a Data Processing Agreement which incorporates the appropriate Standard\n    Contractual Clauses, or another legally applicable data transfer mechanism\n- mechanism: adequacy\n  text: Transferring personal data to third parties residing in countries that have been deemed to provide an adequate\n    level of protection for personal data by the European Commission or UK Information Commissioner’s Office\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy dashboard or Data Protection Officer contact\n  text: To contact us and exercise your rights, please visit your privacy dashboard, which you can access here .\n    You may also contact our Data Protection Officer at dpo@teamaol.com\nrights:\n- right: Access\n  text: Right of access. You have the right to obtain information about the processing\
  \ of your personal data and\n    to access it.\n- right: Rectification\n  text: Right to rectification. You have the right to ask for the update, rectification or integration of your personal\n    data.\n- right: Erasure\n  text: Right to erasure. You have the right to request the deletion of your personal data.\n- right: Restriction\n  text: Right to restriction of processing. You have the right to request the restriction of the processing of your\n    personal data.\n- right: Portability\n  text: Right to data portability. You have the right to obtain a portable electronic copy of your personal data.\n- right: Object\n  text: Right to object. Where we rely on our legitimate interest to process your personal data, you have the right\n    to object to such processing\n- right: Withdraw consent\n  text: Right to withdraw your consent. Where we rely on your consent to process your personal data, you have the\n    right to withdraw your consent\nsale_or_sharing:\n  stance: unstated\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/aol/privacy/aol-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 30 quoted statements, read from AOL's own page on 2026-11-09.
synthetic: false
tags:
- Digital Media
- News
- Entertainment
- Advertising
- Identity
- OpenID Connect
- Authentication
- Email
- Consumer Internet
- Fortune 1000
---
