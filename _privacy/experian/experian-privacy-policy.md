---
api_specs:
- filename: experian-address-validation-api-openapi.yml
  format: yaml
  label: Experian Address Validation API
  slug: experian-address-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-address-validation-api-openapi.yml
- filename: experian-bulk-address-api-openapi.yml
  format: yaml
  label: Experian Bulk Address API
  slug: experian-bulk-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-bulk-address-api-openapi.yml
- filename: experian-bulk-email-api-openapi.yml
  format: yaml
  label: Experian Bulk Email API
  slug: experian-bulk-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-bulk-email-api-openapi.yml
- filename: experian-bulk-phone-api-openapi.yml
  format: yaml
  label: Experian Bulk Phone API
  slug: experian-bulk-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-bulk-phone-api-openapi.yml
- filename: experian-email-validation-api-openapi.yml
  format: yaml
  label: Experian Email Validation API
  slug: experian-email-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-email-validation-api-openapi.yml
- filename: experian-enrichment-api-openapi.yml
  format: yaml
  label: Experian Enrichment API
  slug: experian-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-enrichment-api-openapi.yml
- filename: experian-identity-append-usa-only-api-openapi.yml
  format: yaml
  label: Experian Identity Append (USA only) API
  slug: experian-identity-append-usa-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-identity-append-usa-only-api-openapi.yml
- filename: experian-phone-validation-api-openapi.yml
  format: yaml
  label: Experian Phone Validation API
  slug: experian-phone-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-phone-validation-api-openapi.yml
- filename: experian-reverse-phone-append-usa-only-api-openapi.yml
  format: yaml
  label: Experian Reverse Phone Append (USA only) API
  slug: experian-reverse-phone-append-usa-only-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/experian/openapi/experian-reverse-phone-append-usa-only-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Company name · Name · Title · Address · Phone · Email Address
  - category: device
    text: How you connect to the internet (including IP address), how you engage with our site, screen resolution, browser data stored on your device
  - category: location
    text: location data (city, region of the IP address you used when accessing our services)
  - category: communication
    text: we will also collect your marketing preferences so that we know whether or not you want to hear from us for marketing purposes
  deletion:
    route: Contact the Data Protection Officer
    text: information which is no longer required for any purposes will be deleted/disposed of securely.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Customer support
    text: To provide and improve customer support we will use your information
  - purpose: Marketing and market research
    text: If you have given us your consent to contact you we will use the information you have submitted through our website for marketing and market research
  - purpose: Reporting and analytics
    text: We will use your information for reporting and analytical purposes
  - purpose: Complaint and dispute resolution
    text: we will use the information we have about you to help us manage your complaint and to bring it to a close
  - purpose: Legal compliance
    text: To comply with the law Like any other business, we are required to comply with many laws and regulations.
  residency:
  - region: United States
    text: when you submit your identifiable data via the Global Developer Portal, we will store your data in the US.
  - region: United Kingdom
    text: Experian is based in the UK, which is where our main databases are.
  retention:
  - period: 12 months
    scope: Contact information
    text: For the contact information you provide, we will keep your data for 12 months after your last engagement with us.
  - period: null
    scope: Event registration data
    text: This data will only be retained for as long as necessary to administer the event.
  rights:
  - right: Access
    text: You can also ask for access to the personal information we hold about you
  - right: Correction
    text: request that we correct any mistakes
  - right: Erasure or restriction
    text: restrict or stop processing or delete it
  - right: Withdraw consent
    text: you have the right to withdraw that consent at any time on our website
  - right: Portability
    text: you can require that we provide the information we hold about you either to you or a third party in a commonly used format.
  role:
    text: Experian is responsible for processing the personal information you provide to us on this website developer.experian.com
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your data remains protected under contractual provisions defined for that purpose.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Experian
provenance_date: '2026-11-09'
provider_name: Experian
provider_slug: experian
slug: experian-privacy-policy
source_date: '2026-11-09'
source_filename: experian-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://developer.experian.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Experian\naid: experian\nurl: https://developer.experian.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Experian is responsible for processing the personal information you provide to us on this website developer.experian.com\ndata_categories:\n- category: identifying\n  text: Company name · Name · Title · Address · Phone · Email Address\n- category: device\n  text: How you connect to the internet (including IP address), how you engage with our site, screen resolution,\n    browser data stored on your device\n- category: location\n  text: location data (city, region of the\
  \ IP address you used when accessing our services)\n- category: communication\n  text: we will also collect your marketing preferences so that we know whether or not you want to hear from us\n    for marketing purposes\npurposes:\n- purpose: Customer support\n  text: To provide and improve customer support we will use your information\n- purpose: Marketing and market research\n  text: If you have given us your consent to contact you we will use the information you have submitted through\n    our website for marketing and market research\n- purpose: Reporting and analytics\n  text: We will use your information for reporting and analytical purposes\n- purpose: Complaint and dispute resolution\n  text: we will use the information we have about you to help us manage your complaint and to bring it to a close\n- purpose: Legal compliance\n  text: To comply with the law Like any other business, we are required to comply with many laws and regulations.\nretention:\n- scope: Contact information\n\
  \  period: 12 months\n  text: For the contact information you provide, we will keep your data for 12 months after your last engagement\n    with us.\n- scope: Event registration data\n  period: null\n  text: This data will only be retained for as long as necessary to administer the event.\nresidency:\n- region: United States\n  text: when you submit your identifiable data via the Global Developer Portal, we will store your data in the US.\n- region: United Kingdom\n  text: Experian is based in the UK, which is where our main databases are.\ntransfers:\n- mechanism: other\n  text: Your data remains protected under contractual provisions defined for that purpose.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the Data Protection Officer\n  text: information which is no longer required for any purposes will be deleted/disposed of securely.\nrights:\n- right: Access\n  text: You can also ask for access to the personal\
  \ information we hold about you\n- right: Correction\n  text: request that we correct any mistakes\n- right: Erasure or restriction\n  text: restrict or stop processing or delete it\n- right: Withdraw consent\n  text: you have the right to withdraw that consent at any time on our website\n- right: Portability\n  text: you can require that we provide the information we hold about you either to you or a third party in a commonly\n    used format.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/experian/privacy/experian-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from Experian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit Bureau
- Credit Reporting
- Identity Verification
- Fraud Prevention
- Data Quality
- Address Validation
- Email Verification
- Phone Validation
- Data Enrichment
- Financial Services
- Risk Management
---
