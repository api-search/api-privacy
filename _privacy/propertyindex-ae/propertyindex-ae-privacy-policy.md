---
api_specs:
- filename: propertyindex-ae-account-api-openapi.yml
  format: yaml
  label: PropertyIndex Account API
  slug: propertyindex-ae-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyindex-ae/openapi/propertyindex-ae-account-api-openapi.yml
- filename: propertyindex-ae-locations-api-openapi.yml
  format: yaml
  label: PropertyIndex Locations API
  slug: propertyindex-ae-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyindex-ae/openapi/propertyindex-ae-locations-api-openapi.yml
- filename: propertyindex-ae-market-index-api-openapi.yml
  format: yaml
  label: PropertyIndex Market index API
  slug: propertyindex-ae-market-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyindex-ae/openapi/propertyindex-ae-market-index-api-openapi.yml
- filename: propertyindex-ae-rentals-api-openapi.yml
  format: yaml
  label: PropertyIndex Rentals API
  slug: propertyindex-ae-rentals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyindex-ae/openapi/propertyindex-ae-rentals-api-openapi.yml
- filename: propertyindex-ae-sales-api-openapi.yml
  format: yaml
  label: PropertyIndex Sales API
  slug: propertyindex-ae-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propertyindex-ae/openapi/propertyindex-ae-sales-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Contact Information: Name and email address.'
  - category: identifying
    text: 'Unique Identifiers: Username and password.'
  - category: professional
    text: 'Professional Information: Company name or professional role (if applicable).'
  - category: device
    text: Your device's Internet Protocol (IP) address.
  - category: behavioral
    text: Search queries and filters used within the Service.
  - category: location
    text: collect information about your location and your activities on our website
  - category: financial
    text: Stripe may collect and process payment information in accordance with their Privacy Policy.
  deletion:
    route: Account settings or email request to privacy@propertyindex.ae
    text: If you wish for your personal data to be completely removed from our customer relationship management platform and other third-party services, please send us an explicit request via email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain our Service
  - purpose: Marketing communications
    text: Send you marketing communications (with your consent)
  - purpose: Security and fraud
    text: Detect, prevent, and address technical issues and fraud
  - purpose: Analytics and improvement
    text: Understand and analyze how you use our Service
  retention:
  - period: 30 days
    scope: Deleted account or data
    text: If you delete your data or account, the data will be flagged for removal and will be deleted from our systems within 30 days and from backups within 90 days.
  - period: 90 days
    scope: Backups
    text: will be deleted from our systems within 30 days and from backups within 90 days.
  rights:
  - right: Access
    text: 'Access: Request details of the personal information we hold about you.'
  - right: Correction
    text: 'Correction: Correct any personal information that is inaccurate, out of date, incomplete, or misleading.'
  - right: Erasure
    text: 'Erasure: Request the deletion of your personal information when it is no longer necessary for the purposes for which it was collected.'
  - right: Restriction
    text: 'Restriction: Request that we stop processing your personal information under certain circumstances.'
  - right: Data transfer
    text: 'Data Transfer: Request to receive or transfer your personal information to another party where technically feasible.'
  - right: Withdraw consent
    text: 'Withdraw Consent: Withdraw your consent where you have previously given consent to the processing of your personal information.'
  - right: Lodge complaint
    text: 'Lodge a Complaint: Submit a complaint to the UAE Data Office if you believe your data protection rights have been violated.'
  role:
    text: This Privacy Policy applies to the website propertyindex.ae and all its subdomains (the "Sites"), together with the Property Index web applications and services (the "Services"), owned and operated by GXM Ventures FZE LLC trading as Property Index
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or any data you enter into our Services in any way.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: When we transfer personal data outside the UAE, we ensure that appropriate safeguards are in place in accordance with UAE data protection laws to protect your personal information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PropertyIndex
provenance_date: '2026-11-10'
provider_name: PropertyIndex
provider_slug: propertyindex-ae
slug: propertyindex-ae-privacy-policy
source_date: '2026-11-10'
source_filename: propertyindex-ae-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.propertyindex.ae/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PropertyIndex\naid: propertyindex-ae\nurl: https://www.propertyindex.ae/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy applies to the website propertyindex.ae and all its subdomains (the \"Sites\"), together\n    with the Property Index web applications and services (the \"Services\"), owned and operated by GXM Ventures FZE\n    LLC trading as Property Index\ndata_categories:\n- category: identifying\n  text: 'Contact Information: Name and email address.'\n- category: identifying\n  text: 'Unique Identifiers: Username and password.'\n- category: professional\n\
  \  text: 'Professional Information: Company name or professional role (if applicable).'\n- category: device\n  text: Your device's Internet Protocol (IP) address.\n- category: behavioral\n  text: Search queries and filters used within the Service.\n- category: location\n  text: collect information about your location and your activities on our website\n- category: financial\n  text: Stripe may collect and process payment information in accordance with their Privacy Policy.\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain our Service\n- purpose: Marketing communications\n  text: Send you marketing communications (with your consent)\n- purpose: Security and fraud\n  text: Detect, prevent, and address technical issues and fraud\n- purpose: Analytics and improvement\n  text: Understand and analyze how you use our Service\nretention:\n- scope: Deleted account or data\n  period: 30 days\n  text: If you delete your data or account, the data will be\
  \ flagged for removal and will be deleted from our systems\n    within 30 days and from backups within 90 days.\n- scope: Backups\n  period: 90 days\n  text: will be deleted from our systems within 30 days and from backups within 90 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: When we transfer personal data outside the UAE, we ensure that appropriate safeguards are in place in accordance\n    with UAE data protection laws to protect your personal information.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or email request to privacy@propertyindex.ae\n  text: If you wish for your personal data to be completely removed from our customer relationship management platform\n    and other third-party services, please send us an explicit request via email.\nrights:\n- right: Access\n  text: 'Access: Request details of the personal information we hold about you.'\n- right: Correction\n  text:\
  \ 'Correction: Correct any personal information that is inaccurate, out of date, incomplete, or misleading.'\n- right: Erasure\n  text: 'Erasure: Request the deletion of your personal information when it is no longer necessary for the purposes\n    for which it was collected.'\n- right: Restriction\n  text: 'Restriction: Request that we stop processing your personal information under certain circumstances.'\n- right: Data transfer\n  text: 'Data Transfer: Request to receive or transfer your personal information to another party where technically\n    feasible.'\n- right: Withdraw consent\n  text: 'Withdraw Consent: Withdraw your consent where you have previously given consent to the processing of your\n    personal information.'\n- right: Lodge complaint\n  text: 'Lodge a Complaint: Submit a complaint to the UAE Data Office if you believe your data protection rights\n    have been violated.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or any\
  \ data you enter into our Services in any way.\n"
source_yaml_url: https://artifacts.apis.io/propertyindex-ae/privacy/propertyindex-ae-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from PropertyIndex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Dubai
- Property Data
- Market Intelligence
---
