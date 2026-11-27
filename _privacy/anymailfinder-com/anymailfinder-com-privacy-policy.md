---
api_specs:
- filename: anymailfinder-com-account-api-openapi.yml
  format: yaml
  label: Anymail Finder Account API
  slug: anymailfinder-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-account-api-openapi.yml
- filename: anymailfinder-com-bulk-api-openapi.yml
  format: yaml
  label: Anymail Finder Bulk API
  slug: anymailfinder-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-bulk-api-openapi.yml
- filename: anymailfinder-com-domain-api-openapi.yml
  format: yaml
  label: Anymail Finder Domain API
  slug: anymailfinder-com-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-domain-api-openapi.yml
- filename: anymailfinder-com-find-email-api-openapi.yml
  format: yaml
  label: Anymail Finder Find Email API
  slug: anymailfinder-com-find-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-find-email-api-openapi.yml
- filename: anymailfinder-com-geo-lead-api-openapi.yml
  format: yaml
  label: Anymail Finder Geo Lead API
  slug: anymailfinder-com-geo-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-geo-lead-api-openapi.yml
- filename: anymailfinder-com-report-api-openapi.yml
  format: yaml
  label: Anymail Finder Report API
  slug: anymailfinder-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-report-api-openapi.yml
- filename: anymailfinder-com-verify-email-api-openapi.yml
  format: yaml
  label: Anymail Finder Verify Email API
  slug: anymailfinder-com-verify-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anymailfinder-com/openapi/anymailfinder-com-verify-email-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes first name, last name, title.
  - category: contact
    text: Contact Data includes billing address, email address and telephone number.
  - category: financial
    text: Financial Data includes bank account and payment card details when you make a payment for our services.
  - category: professional
    text: 'Business Contact Data: name, business email address, company domain and the email format used at that company.'
  - category: device
    text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location
  deletion:
    route: erasure request via legal@anymailfinder.com
    text: 'Request erasure of your personal data: This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Register users for services
    text: To register you as a User for the provision of our services.
  - purpose: Source personal data for platform
    text: To source personal data for the provision of services so our Users can use the platform.
  - purpose: Data analytics to improve services
    text: To use data analytics to improve our website, products/services, marketing, user relationships and experiences
  residency:
  - region: United States servers
    text: including on servers in the United States.
  retention:
  - period: null
    scope: Business contact database records
    text: records in our shared business contact database do not have a fixed calendar expiry.
  - period: at least once a year
    scope: Business contact retention review
    text: We review continued retention at least once a year, considering the age of the record, its verification history
  rights:
  - right: correction
    text: 'Request correction of your personal data: This enables you to have any incomplete or inaccurate information we hold about you corrected.'
  - right: erasure
    text: 'Request erasure of your personal data: This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.'
  - right: objection
    text: 'Object to processing of your personal data: This is where we are processing your personal data based on a legitimate interest or those of a third party and you may challenge this.'
  - right: restriction
    text: 'Request restriction of processing your personal information: This enables you to ask us to suspend the processing of your personal data in the following scenarios'
  - right: withdraw consent
    text: 'Right to withdraw consent: This is where we are relying on consent to process your personal data.'
  role:
    text: Unless we notify you otherwise, we are the controller of your personal data for the purpose of this website and when we directly engage with you.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: approved standard contractual clauses together with supplementary measures where required.
  - mechanism: adequacy
    text: We will only transfer your personal information to countries that have been deemed to provide an adequate level of protection for personal information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anymail Finder
provenance_date: '2026-11-09'
provider_name: Anymail Finder
provider_slug: anymailfinder-com
slug: anymailfinder-com-privacy-policy
source_date: '2026-11-09'
source_filename: anymailfinder-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anymailfinder.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anymail Finder\naid: anymailfinder-com\nurl: https://anymailfinder.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Unless we notify you otherwise, we are the controller of your personal data for the purpose of this website\n    and when we directly engage with you.\ndata_categories:\n- category: identifying\n  text: Identity Data includes first name, last name, title.\n- category: contact\n  text: Contact Data includes billing address, email address and telephone number.\n- category: financial\n  text: Financial Data includes bank account and payment card details when you\
  \ make a payment for our services.\n- category: professional\n  text: 'Business Contact Data: name, business email address, company domain and the email format used at that company.'\n- category: device\n  text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time\n    zone setting and location\npurposes:\n- purpose: Register users for services\n  text: To register you as a User for the provision of our services.\n- purpose: Source personal data for platform\n  text: To source personal data for the provision of services so our Users can use the platform.\n- purpose: Data analytics to improve services\n  text: To use data analytics to improve our website, products/services, marketing, user relationships and experiences\nretention:\n- scope: Business contact database records\n  period: null\n  text: records in our shared business contact database do not have a fixed calendar expiry.\n- scope: Business contact retention review\n  period:\
  \ at least once a year\n  text: We review continued retention at least once a year, considering the age of the record, its verification\n    history\nresidency:\n- region: United States servers\n  text: including on servers in the United States.\ntransfers:\n- mechanism: SCC\n  text: approved standard contractual clauses together with supplementary measures where required.\n- mechanism: adequacy\n  text: We will only transfer your personal information to countries that have been deemed to provide an adequate\n    level of protection for personal information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: erasure request via legal@anymailfinder.com\n  text: 'Request erasure of your personal data: This enables you to ask us to delete or remove personal data where\n    there is no good reason for us continuing to process it.'\nrights:\n- right: correction\n  text: 'Request correction of your personal data: This enables you\
  \ to have any incomplete or inaccurate information\n    we hold about you corrected.'\n- right: erasure\n  text: 'Request erasure of your personal data: This enables you to ask us to delete or remove personal data where\n    there is no good reason for us continuing to process it.'\n- right: objection\n  text: 'Object to processing of your personal data: This is where we are processing your personal data based on\n    a legitimate interest or those of a third party and you may challenge this.'\n- right: restriction\n  text: 'Request restriction of processing your personal information: This enables you to ask us to suspend the\n    processing of your personal data in the following scenarios'\n- right: withdraw consent\n  text: 'Right to withdraw consent: This is where we are relying on consent to process your personal data.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anymailfinder-com/privacy/anymailfinder-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Anymail Finder's own page on 2026-11-09.
synthetic: false
tags:
- Email Finder
- B2B
- Lead Generation
- Verification
---
