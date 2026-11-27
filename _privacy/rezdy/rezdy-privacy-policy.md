---
api_specs:
- filename: rezdy-availability-api-openapi.yml
  format: yaml
  label: Rezdy Availability API
  slug: rezdy-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-availability-api-openapi.yml
- filename: rezdy-bookings-api-openapi.yml
  format: yaml
  label: Rezdy Bookings API
  slug: rezdy-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-bookings-api-openapi.yml
- filename: rezdy-categories-api-openapi.yml
  format: yaml
  label: Rezdy Categories API
  slug: rezdy-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-categories-api-openapi.yml
- filename: rezdy-companies-api-openapi.yml
  format: yaml
  label: Rezdy Companies API
  slug: rezdy-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-companies-api-openapi.yml
- filename: rezdy-manifest-api-openapi.yml
  format: yaml
  label: Rezdy Manifest API
  slug: rezdy-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-manifest-api-openapi.yml
- filename: rezdy-products-api-openapi.yml
  format: yaml
  label: Rezdy Products API
  slug: rezdy-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-products-api-openapi.yml
- filename: rezdy-resources-api-openapi.yml
  format: yaml
  label: Rezdy Resources API
  slug: rezdy-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-resources-api-openapi.yml
- filename: rezdy-vouchers-api-openapi.yml
  format: yaml
  label: Rezdy Vouchers API
  slug: rezdy-vouchers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rezdy/openapi/rezdy-vouchers-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: data that allows someone to identify or contact you, including, for example, your name
  - category: contact
    text: email address
  - category: financial
    text: we collect your credit card information for billing purposes
  - category: behavioral
    text: we automatically track certain information about you based upon your behaviour on our Site
  - category: device
    text: the device from which you connected to the Services
  - category: location
    text: We collect geolocation data
  - category: communication
    text: If you provide us feedback or contact us via email, we may collect your name
  deletion:
    route: contact us, or delete your in-app account
    text: You may request that we delete (and direct our service providers to delete) your Personal Information, subject to certain exceptions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services
    text: resolve service and billing disputes
  - purpose: billing
    text: bill any amounts due from you
  - purpose: fraud and security
    text: detect and protect us against error, fraud and other criminal activity
  - purpose: marketing
    text: deliver information to you that, in some cases, is relevant to your interests, such as product news
  retention:
  - period: as long as your account is active
    scope: general account data
    text: We will retain your information for as long as your account is active or as needed to provide you services.
  - period: up to seven years after your last interaction with the Services
    scope: California identifiers and customer records
    text: for a period of up to seven years after your last interaction with the Services
  rights:
  - right: Right to know
    text: You have the right to request disclosure about our Personal Information collection practices during the prior 12 months
  - right: Right to delete
    text: You may request that we delete (and direct our service providers to delete) your Personal Information, subject to certain exceptions.
  - right: Right to correct
    text: If applicable, you have the right to request us to correct inaccurate Personal Information about you
  - right: Opt out of sale or sharing
    text: You have the right to opt out of having your Personal Information, including Sensitive Personal Information, sold or shared for cross-context behavioral advertising.
  - right: Objection to processing
    text: You may object to our use or disclosure of your Personal Information by contacting us
  - right: Revoke consent
    text: If you revoke your consent for the processing of Personal Information, then we may no longer be able to provide you with Services.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Subject to the exceptions below, we do not sell, rent, lease, retain, disclose or otherwise transfer any information collected either automatically or through your voluntary action to any third party.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we require them to enter into the Standard Contractual Clauses to ensure your Personal Data is protected
  - mechanism: other
    text: We take reasonable steps to ensure your Personal Data is protected in those countries by requiring entities in those countries to comply with contractual obligations
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rezdy
provenance_date: '2026-11-10'
provider_name: Rezdy
provider_slug: rezdy
slug: rezdy-privacy-policy
source_date: '2026-11-10'
source_filename: rezdy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rezdy.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rezdy\naid: rezdy\nurl: https://rezdy.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: data that allows someone to identify or contact you, including, for example, your name\n- category: contact\n  text: email address\n- category: financial\n  text: we collect your credit card information for billing purposes\n- category: behavioral\n  text: we automatically track certain information about you based upon your behaviour on our Site\n- category: device\n  text: the device from which you connected to the\
  \ Services\n- category: location\n  text: We collect geolocation data\n- category: communication\n  text: If you provide us feedback or contact us via email, we may collect your name\npurposes:\n- purpose: provide services\n  text: resolve service and billing disputes\n- purpose: billing\n  text: bill any amounts due from you\n- purpose: fraud and security\n  text: detect and protect us against error, fraud and other criminal activity\n- purpose: marketing\n  text: deliver information to you that, in some cases, is relevant to your interests, such as product news\nretention:\n- scope: general account data\n  period: as long as your account is active\n  text: We will retain your information for as long as your account is active or as needed to provide you services.\n- scope: California identifiers and customer records\n  period: up to seven years after your last interaction with the Services\n  text: for a period of up to seven years after your last interaction with the Services\nresidency:\
  \ []\ntransfers:\n- mechanism: SCC\n  text: we require them to enter into the Standard Contractual Clauses to ensure your Personal Data is protected\n- mechanism: other\n  text: We take reasonable steps to ensure your Personal Data is protected in those countries by requiring entities\n    in those countries to comply with contractual obligations\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us, or delete your in-app account\n  text: You may request that we delete (and direct our service providers to delete) your Personal Information, subject\n    to certain exceptions.\nrights:\n- right: Right to know\n  text: You have the right to request disclosure about our Personal Information collection practices during the\n    prior 12 months\n- right: Right to delete\n  text: You may request that we delete (and direct our service providers to delete) your Personal Information, subject\n    to certain exceptions.\n- right:\
  \ Right to correct\n  text: If applicable, you have the right to request us to correct inaccurate Personal Information about you\n- right: Opt out of sale or sharing\n  text: You have the right to opt out of having your Personal Information, including Sensitive Personal Information,\n    sold or shared for cross-context behavioral advertising.\n- right: Objection to processing\n  text: You may object to our use or disclosure of your Personal Information by contacting us\n- right: Revoke consent\n  text: If you revoke your consent for the processing of Personal Information, then we may no longer be able to\n    provide you with Services.\nsale_or_sharing:\n  stance: conditional\n  text: Subject to the exceptions below, we do not sell, rent, lease, retain, disclose or otherwise transfer any\n    information collected either automatically or through your voluntary action to any third party.\n"
source_yaml_url: https://artifacts.apis.io/rezdy/privacy/rezdy-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Rezdy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Booking
- Software-as-a-Service
- Tourism
---
