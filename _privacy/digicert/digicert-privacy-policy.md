---
api_specs:
- filename: digicert-account-api-openapi.yml
  format: yaml
  label: Digicert Account API
  slug: digicert-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digicert/openapi/digicert-account-api-openapi.yml
- filename: digicert-domain-api-openapi.yml
  format: yaml
  label: Digicert Domain API
  slug: digicert-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digicert/openapi/digicert-domain-api-openapi.yml
- filename: digicert-order-api-openapi.yml
  format: yaml
  label: Digicert Order API
  slug: digicert-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digicert/openapi/digicert-order-api-openapi.yml
- filename: digicert-organization-api-openapi.yml
  format: yaml
  label: Digicert Organization API
  slug: digicert-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digicert/openapi/digicert-organization-api-openapi.yml
- filename: digicert-user-api-openapi.yml
  format: yaml
  label: Digicert User API
  slug: digicert-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digicert/openapi/digicert-user-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: First and last name, email address, postal address, telephone and fax number(s), IP address, usernames and related account information, job title, employer, and certain payment details.
  - category: device
    text: we may collect device information, including your IP address and other unique identifiers, device name, type of operating system, mobile network information
  - category: behavioral
    text: we may also collect your web traffic information to track sales, demographics, product usage and related analytics
  deletion:
    route: Privacy Request Portal or privacy@digicert.com
    text: Privacy Request Portal. You may submit a request to access, delete, opt out of promotional communications, or request to correct/update your personal information by selecting "Make a Privacy Request"
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing products and services and sales/support
    text: We may use your information to provide our products and services, send order confirmations, respond to customer service requests
  - purpose: Marketing
    text: We may use your information to send promotional emails.
  - purpose: Validation services
    text: As part of issuing certificates, DigiCert uses personal information to perform validation services
  - purpose: Technical usage and analytics
    text: We only collect this information to ensure the proper functioning of our website, to personalize your experience on our website
  retention:
  - period: 7 years
    scope: Account and validation information
    text: industry standards require us to maintain such information for a period of 7 years after your account is terminated, cancelled, or the certificate expires
  - period: up to 7 years
    scope: OCSP data
    text: OCSP data is retained by DigiCert for up to 7 years
  - period: 10 days
    scope: OCSP data in CDN
    text: OCSP data processed by our content delivery network is deleted after 10 days.
  - period: up to 30 days
    scope: Phone call recordings
    text: For most phone calls, we retain records for up to 30 days
  rights:
  - right: access
    text: You may submit a request to access your information, request portability, request deletion, restrict processing of your personal information, request correction
  - right: portability
    text: request portability
  - right: deletion
    text: request deletion
  - right: objection
    text: in certain cases, you may object to us processing your personal information
  - right: withdraw consent
    text: submit a request to withdraw your consent to processing
  - right: opt out of marketing
    text: You have the right to ask us not to process your personal information for direct marketing purposes.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties
  subprocessors:
    text: You may view our list of sub-processors at https://www.digicert.com/content/dam/digicert/pdfs/legal/sub-processor-list.pdf.
    url: https://www.digicert.com/content/dam/digicert/pdfs/legal/sub-processor-list.pdf
  transfers:
  - mechanism: DPF
    text: for personal information originating in the EU/EEA, UK, or Switzerland and that is transferred to the United States, DigiCert is also certified under the Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Digicert
provenance_date: '2026-11-09'
provider_name: Digicert
provider_slug: digicert
slug: digicert-privacy-policy
source_date: '2026-11-09'
source_filename: digicert-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://privacy.digicert.com/policies/en/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Digicert\naid: digicert\nurl: https://privacy.digicert.com/policies/en/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: First and last name, email address, postal address, telephone and fax number(s), IP address, usernames and\n    related account information, job title, employer, and certain payment details.\n- category: device\n  text: we may collect device information, including your IP address and other unique identifiers, device name,\n    type of operating system, mobile network information\n- category: behavioral\n  text: we may also\
  \ collect your web traffic information to track sales, demographics, product usage and related\n    analytics\npurposes:\n- purpose: Providing products and services and sales/support\n  text: We may use your information to provide our products and services, send order confirmations, respond to customer\n    service requests\n- purpose: Marketing\n  text: We may use your information to send promotional emails.\n- purpose: Validation services\n  text: As part of issuing certificates, DigiCert uses personal information to perform validation services\n- purpose: Technical usage and analytics\n  text: We only collect this information to ensure the proper functioning of our website, to personalize your experience\n    on our website\nretention:\n- scope: Account and validation information\n  period: 7 years\n  text: industry standards require us to maintain such information for a period of 7 years after your account is\n    terminated, cancelled, or the certificate expires\n- scope: OCSP data\n\
  \  period: up to 7 years\n  text: OCSP data is retained by DigiCert for up to 7 years\n- scope: OCSP data in CDN\n  period: 10 days\n  text: OCSP data processed by our content delivery network is deleted after 10 days.\n- scope: Phone call recordings\n  period: up to 30 days\n  text: For most phone calls, we retain records for up to 30 days\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: for personal information originating in the EU/EEA, UK, or Switzerland and that is transferred to the United\n    States, DigiCert is also certified under the Data Privacy Framework.\nsubprocessors:\n  url: https://www.digicert.com/content/dam/digicert/pdfs/legal/sub-processor-list.pdf\n  text: You may view our list of sub-processors at https://www.digicert.com/content/dam/digicert/pdfs/legal/sub-processor-list.pdf.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy Request Portal or privacy@digicert.com\n  text: Privacy Request Portal. You may submit a request to access,\
  \ delete, opt out of promotional communications,\n    or request to correct/update your personal information by selecting \"Make a Privacy Request\"\nrights:\n- right: access\n  text: You may submit a request to access your information, request portability, request deletion, restrict processing\n    of your personal information, request correction\n- right: portability\n  text: request portability\n- right: deletion\n  text: request deletion\n- right: objection\n  text: in certain cases, you may object to us processing your personal information\n- right: withdraw consent\n  text: submit a request to withdraw your consent to processing\n- right: opt out of marketing\n  text: You have the right to ask us not to process your personal information for direct marketing purposes.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties\n"
source_yaml_url: https://artifacts.apis.io/digicert/privacy/digicert-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Digicert's own page on 2026-11-09.
synthetic: false
tags:
- Certificates
- Encryption
- PKI
- SSL
- TLS
---
