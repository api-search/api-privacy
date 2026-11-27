---
api_specs:
- filename: astra-accounts-api-openapi.yml
  format: yaml
  label: Astra Accounts API
  slug: astra-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-accounts-api-openapi.yml
- filename: astra-authorization-api-openapi.yml
  format: yaml
  label: Astra Authorization API
  slug: astra-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-authorization-api-openapi.yml
- filename: astra-cards-api-openapi.yml
  format: yaml
  label: Astra Cards API
  slug: astra-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-cards-api-openapi.yml
- filename: astra-instant-payment-eligibility-api-openapi.yml
  format: yaml
  label: Astra Instant Payment Eligibility API
  slug: astra-instant-payment-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-instant-payment-eligibility-api-openapi.yml
- filename: astra-payment-instruments-api-openapi.yml
  format: yaml
  label: Astra Payment Instruments API
  slug: astra-payment-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-payment-instruments-api-openapi.yml
- filename: astra-routines-api-openapi.yml
  format: yaml
  label: Astra Routines API
  slug: astra-routines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-routines-api-openapi.yml
- filename: astra-transfers-api-openapi.yml
  format: yaml
  label: Astra Transfers API
  slug: astra-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-transfers-api-openapi.yml
- filename: astra-user-api-openapi.yml
  format: yaml
  label: Astra User API
  slug: astra-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astra/openapi/astra-user-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may ask you to provide us with Personal Information about you, like your name, e-mail address, mobile phone number, or an avatar for your account
  - category: financial
    text: the username or email associated with that institution, the password for your financial account, and other similar information
  - category: biometric
    text: biometric information, and mailing address
  - category: location
    text: We may also derive the approximate location of the device your use to access our Site from your IP address.
  - category: behavioral
    text: We also may collect information about how you use our Site, including what links you may click on or whether you have visited our Site in the past and when.
  - category: device
    text: we may collect technical information from you during your use of the Site. For instance, we may collect information from you about the device you use to access the Site
  deletion:
    route: Email support from the account email with CANCEL in the subject line
    text: You may request your account be deleted by our support department by emailing [email protected] from the email address associated with your account, indicating “CANCEL” in the subject line of the message.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Site and services
    text: Providing the Site and all related services to you;
  - purpose: Improving the Site and developing new services
    text: Improving the Site and all related services, as well as to research and develop new services
  - purpose: Identity verification and fraud prevention
    text: To verify your identity and the identities of other members of your company;
  - purpose: Marketing
    text: To communicate with you about products, services, offers, and events offered or sponsored by Astra
  retention:
  - period: null
    scope: Personal information generally
    text: We will retain information we collect about you for the period necessary to fulfill the purposes outlined in this Privacy Policy, unless a longer retention period is required by applicable law.
  - period: null
    scope: Financial account information used by Plaid
    text: Once the connection is established, we delete the financial account information from our system.
  rights:
  - right: Access
    text: You have the right to request certain information about our collection and use of your Personal Information over the past 12 months.
  - right: Deletion
    text: You have the right to request that we delete the Personal Information that we have collected about you.
  - right: Correction
    text: You have the right to request that we correct inaccurate Personal Information that we have collected about you.
  - right: Opt out of sale or sharing
    text: You have the right to opt out of the sale or sharing of your Personal Information.
  - right: Data portability
    text: request data portability, your requested information will be provided in a readily usable format to allow transmission to other organizations.
  - right: Appeal
    text: If you would like to appeal our actions in response to your verifiable consumer request, please email [email protected] from the email associated with the Astra profile
  role:
    text: Astra, Inc. (“Astra” “we” “us” “our”) is committed to protecting and respecting your privacy.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: While we do not sell Personal Information in the way the term “sell” is commonly used, we do disclose limited cookie data with our business partners in order to provide and maintain our Site. Such a disclosure may constitute a “sale” for purposes of the CCPA.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Astra
provenance_date: '2026-11-09'
provider_name: Astra
provider_slug: astra
slug: astra-privacy-policy
source_date: '2026-11-09'
source_filename: astra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astrafi.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Astra\naid: astra\nurl: https://astrafi.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Astra, Inc. (“Astra” “we” “us” “our”) is committed to protecting and respecting your privacy.\ndata_categories:\n- category: identifying\n  text: we may ask you to provide us with Personal Information about you, like your name, e-mail address, mobile\n    phone number, or an avatar for your account\n- category: financial\n  text: the username or email associated with that institution, the password for your financial account, and other\n    similar information\n- category: biometric\n  text:\
  \ biometric information, and mailing address\n- category: location\n  text: We may also derive the approximate location of the device your use to access our Site from your IP address.\n- category: behavioral\n  text: We also may collect information about how you use our Site, including what links you may click on or whether\n    you have visited our Site in the past and when.\n- category: device\n  text: we may collect technical information from you during your use of the Site. For instance, we may collect\n    information from you about the device you use to access the Site\npurposes:\n- purpose: Providing the Site and services\n  text: Providing the Site and all related services to you;\n- purpose: Improving the Site and developing new services\n  text: Improving the Site and all related services, as well as to research and develop new services\n- purpose: Identity verification and fraud prevention\n  text: To verify your identity and the identities of other members of your company;\n\
  - purpose: Marketing\n  text: To communicate with you about products, services, offers, and events offered or sponsored by Astra\nretention:\n- scope: Personal information generally\n  period: null\n  text: We will retain information we collect about you for the period necessary to fulfill the purposes outlined\n    in this Privacy Policy, unless a longer retention period is required by applicable law.\n- scope: Financial account information used by Plaid\n  period: null\n  text: Once the connection is established, we delete the financial account information from our system.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support from the account email with CANCEL in the subject line\n  text: You may request your account be deleted by our support department by emailing [email protected] from the\n    email address associated with your account, indicating “CANCEL” in the subject line\
  \ of the message.\nrights:\n- right: Access\n  text: You have the right to request certain information about our collection and use of your Personal Information\n    over the past 12 months.\n- right: Deletion\n  text: You have the right to request that we delete the Personal Information that we have collected about you.\n- right: Correction\n  text: You have the right to request that we correct inaccurate Personal Information that we have collected about\n    you.\n- right: Opt out of sale or sharing\n  text: You have the right to opt out of the sale or sharing of your Personal Information.\n- right: Data portability\n  text: request data portability, your requested information will be provided in a readily usable format to allow\n    transmission to other organizations.\n- right: Appeal\n  text: If you would like to appeal our actions in response to your verifiable consumer request, please email [email\n    protected] from the email associated with the Astra profile\nsale_or_sharing:\n\
  \  stance: conditional\n  text: While we do not sell Personal Information in the way the term “sell” is commonly used, we do disclose limited\n    cookie data with our business partners in order to provide and maintain our Site. Such a disclosure may constitute\n    a “sale” for purposes of the CCPA.\n"
source_yaml_url: https://artifacts.apis.io/astra/privacy/astra-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Astra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Money Movement
- ACH
- Instant Payments
- Bank Transfers
- Disbursements
---
