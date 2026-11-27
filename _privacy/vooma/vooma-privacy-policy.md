---
api_specs:
- filename: vooma-carriers-api-openapi.yml
  format: yaml
  label: Vooma Carriers API
  slug: vooma-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-carriers-api-openapi.yml
- filename: vooma-contacts-api-openapi.yml
  format: yaml
  label: Vooma Contacts API
  slug: vooma-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-contacts-api-openapi.yml
- filename: vooma-customers-api-openapi.yml
  format: yaml
  label: Vooma Customers API
  slug: vooma-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-customers-api-openapi.yml
- filename: vooma-locations-api-openapi.yml
  format: yaml
  label: Vooma Locations API
  slug: vooma-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-locations-api-openapi.yml
- filename: vooma-movements-api-openapi.yml
  format: yaml
  label: Vooma Movements API
  slug: vooma-movements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-movements-api-openapi.yml
- filename: vooma-quotes-api-openapi.yml
  format: yaml
  label: Vooma Quotes API
  slug: vooma-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-quotes-api-openapi.yml
- filename: vooma-shipments-api-openapi.yml
  format: yaml
  label: Vooma Shipments API
  slug: vooma-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-shipments-api-openapi.yml
- filename: vooma-tracking-status-api-openapi.yml
  format: yaml
  label: Vooma Tracking Status API
  slug: vooma-tracking-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-tracking-status-api-openapi.yml
- filename: vooma-webhooks-api-openapi.yml
  format: yaml
  label: Vooma Webhooks API
  slug: vooma-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-webhooks-api-openapi.yml
- filename: vooma-api-api-openapi.yml
  format: yaml
  label: Vooma API
  slug: vooma-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vooma/openapi/vooma-api-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: This includes information about you as a person (such as name, address, and date of birth)
  - category: device
    text: Device Type Operating Systems Unique device identifiers Device Settings Geo-location data
  - category: contact
    text: Name Email Phone/mobile number
  - category: financial
    text: Customer records, such as billing and shipping address, and credit or debit card data.
  - category: behavioral
    text: the pages you visit, the time and date of your visit, the time spent on each page
  - category: location
    text: Geolocation data.
  deletion:
    route: contact us using the details provided in this privacy policy
    text: If you terminate or delete your account, we will delete your personal information within 30 days of the deletion of your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide core features and services
    text: to provide you with our platform's core features and services
  - purpose: analytics and market research
    text: for analytics, market research, and business development
  - purpose: advertising and marketing
    text: for advertising and marketing, including to send you promotional information about our products and services
  - purpose: security and fraud prevention
    text: for security and fraud prevention
  - purpose: legal compliance
    text: to comply with our legal obligations and resolve any disputes that we may have
  residency:
  - region: United States
    text: The personal information we collect is stored and/or processed in United States, or where we or our partners, affiliates, and third-party providers maintain facilities.
  retention:
  - period: the duration your account exists on our system
    scope: account data
    text: we may retain this information for the duration your account exists on our system
  - period: 30 days
    scope: deleted account data
    text: If you terminate or delete your account, we will delete your personal information within 30 days of the deletion of your account.
  rights:
  - right: access
    text: 'Access: You may request details of the personal information that we hold about you.'
  - right: correction
    text: 'Correction: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant, or misleading'
  - right: restrict
    text: 'Restrict: You have the right to request that we restrict the processing of your personal information'
  - right: objection
    text: 'Objecting to processing: You have the right to object to processing of your personal information that is based on our legitimate interests or public interest.'
  - right: portability
    text: 'Data portability: You may have the right to request a copy of the personal information we hold about you.'
  - right: deletion
    text: 'Deletion: You may have a right to request that we delete the personal information we hold about you at any time'
  - right: unsubscribe
    text: 'Unsubscribe: To unsubscribe from our email database or opt-out of communications'
  - right: complaint
    text: 'Complaints: If you believe that we have breached a relevant data protection law and wish to make a complaint'
  role:
    text: We, Vooma, located at the address provided in our Contact Us section, are a Data Controller and/or Processor with respect to the personal information you provide to us.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Third parties we currently use include: Google Analytics MailChimp Stripe'
    url: null
  transfers:
  - mechanism: SCC
    text: standard data protection clauses approved by the European Commission
  - mechanism: BCR
    text: the use of binding corporate rules or other legally accepted means
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vooma
provenance_date: '2026-11-10'
provider_name: Vooma
provider_slug: vooma
slug: vooma-privacy-policy
source_date: '2026-11-10'
source_filename: vooma-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.vooma.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vooma\naid: vooma\nurl: https://www.vooma.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We, Vooma, located at the address provided in our Contact Us section, are a Data Controller and/or Processor\n    with respect to the personal information you provide to us.\ndata_categories:\n- category: identifying\n  text: This includes information about you as a person (such as name, address, and date of birth)\n- category: device\n  text: Device Type Operating Systems Unique device identifiers Device Settings Geo-location data\n- category: contact\n  text: Name Email Phone/mobile number\n\
  - category: financial\n  text: Customer records, such as billing and shipping address, and credit or debit card data.\n- category: behavioral\n  text: the pages you visit, the time and date of your visit, the time spent on each page\n- category: location\n  text: Geolocation data.\npurposes:\n- purpose: provide core features and services\n  text: to provide you with our platform's core features and services\n- purpose: analytics and market research\n  text: for analytics, market research, and business development\n- purpose: advertising and marketing\n  text: for advertising and marketing, including to send you promotional information about our products and services\n- purpose: security and fraud prevention\n  text: for security and fraud prevention\n- purpose: legal compliance\n  text: to comply with our legal obligations and resolve any disputes that we may have\nretention:\n- scope: account data\n  period: the duration your account exists on our system\n  text: we may retain this information\
  \ for the duration your account exists on our system\n- scope: deleted account data\n  period: 30 days\n  text: If you terminate or delete your account, we will delete your personal information within 30 days of the\n    deletion of your account.\nresidency:\n- region: United States\n  text: The personal information we collect is stored and/or processed in United States, or where we or our partners,\n    affiliates, and third-party providers maintain facilities.\ntransfers:\n- mechanism: SCC\n  text: standard data protection clauses approved by the European Commission\n- mechanism: BCR\n  text: the use of binding corporate rules or other legally accepted means\nsubprocessors:\n  url: null\n  text: 'Third parties we currently use include: Google Analytics MailChimp Stripe'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us using the details provided in this privacy policy\n  text: If you terminate or delete your account, we will delete your personal information\
  \ within 30 days of the\n    deletion of your account.\nrights:\n- right: access\n  text: 'Access: You may request details of the personal information that we hold about you.'\n- right: correction\n  text: 'Correction: If you believe that any information we hold about you is inaccurate, out of date, incomplete,\n    irrelevant, or misleading'\n- right: restrict\n  text: 'Restrict: You have the right to request that we restrict the processing of your personal information'\n- right: objection\n  text: 'Objecting to processing: You have the right to object to processing of your personal information that is\n    based on our legitimate interests or public interest.'\n- right: portability\n  text: 'Data portability: You may have the right to request a copy of the personal information we hold about you.'\n- right: deletion\n  text: 'Deletion: You may have a right to request that we delete the personal information we hold about you at\n    any time'\n- right: unsubscribe\n  text: 'Unsubscribe:\
  \ To unsubscribe from our email database or opt-out of communications'\n- right: complaint\n  text: 'Complaints: If you believe that we have breached a relevant data protection law and wish to make a complaint'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vooma/privacy/vooma-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 27 quoted statements, read from Vooma's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Freight
- Logistics
- Transportation
- TMS
- Agents
- Freight Brokerage
---
