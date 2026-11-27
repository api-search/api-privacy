---
api_specs:
- filename: algeriacertify-com-certificates-api-openapi.yml
  format: yaml
  label: Algeria Certify Certificates API
  slug: algeriacertify-com-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algeriacertify-com/openapi/algeriacertify-com-certificates-api-openapi.yml
- filename: algeriacertify-com-system-api-openapi.yml
  format: yaml
  label: Algeria Certify System API
  slug: algeriacertify-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algeriacertify-com/openapi/algeriacertify-com-system-api-openapi.yml
- filename: algeriacertify-com-verification-api-openapi.yml
  format: yaml
  label: Algeria Certify Verification API
  slug: algeriacertify-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algeriacertify-com/openapi/algeriacertify-com-verification-api-openapi.yml
- filename: algeriacertify-com-zapier-api-openapi.yml
  format: yaml
  label: Algeria Certify Zapier API
  slug: algeriacertify-com-zapier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algeriacertify-com/openapi/algeriacertify-com-zapier-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity data: Full name, date of birth, and registration or university number.'
  - category: other
    text: 'Academic data: Certificate title, specialization, graduation year, and grades or evaluations (where applicable).'
  - category: device
    text: 'Usage data: IP address, browser type, and verification logs for security and fraud prevention purposes.'
  - category: other
    text: 'Technical digital data: Encrypted unique digital identifier (UUID), verification code hash (QR Hash), and issuance date and time.'
  deletion:
    route: Account deletion; issuing entity revocation
    text: Deleted account data is retained for two (2) years after account deletion then automatically purged.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Real-time verification
    text: Enabling real-time verification of certificate authenticity via direct electronic scanning.
  - purpose: Fraud prevention
    text: Preventing forgery or unauthorized modification of documents.
  - purpose: Institutional record integrity
    text: Protecting the integrity of digital academic records for institutions.
  - purpose: Platform continuity
    text: Ensuring platform continuity and performance at the highest efficiency.
  residency:
  - region: Algeria
    text: Sensitive data and central records are hosted on secure servers within national territory.
  retention:
  - period: permanently
    scope: Issued digital certificates
    text: Issued digital certificates are stored permanently to ensure future verifiability.
  - period: two (2) years
    scope: Deleted account data
    text: Deleted account data is retained for two (2) years after account deletion then automatically purged.
  - period: 5 years
    scope: Verification logs
    text: Verification logs are retained for 5 years for auditing and compliance purposes.
  rights:
  - right: Access
    text: 'Right of access: You may request a copy of the recorded data related to you.'
  - right: Rectification
    text: 'Right of rectification: You may request correction of any material error by coordinating with the issuing academic entity.'
  - right: Revocation and erasure
    text: 'Right of revocation and erasure: The issuing entity has the right to revoke a certificate if entitlement is proven invalid.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: The platform does not sell, lease, or commercially exploit personal data in any form.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Algeria Certify
provenance_date: '2026-11-09'
provider_name: Algeria Certify
provider_slug: algeriacertify-com
slug: algeriacertify-com-privacy-policy
source_date: '2026-11-09'
source_filename: algeriacertify-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://algeriacertify.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Algeria Certify\naid: algeriacertify-com\nurl: https://algeriacertify.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Identity data: Full name, date of birth, and registration or university number.'\n- category: other\n  text: 'Academic data: Certificate title, specialization, graduation year, and grades or evaluations (where applicable).'\n- category: device\n  text: 'Usage data: IP address, browser type, and verification logs for security and fraud prevention purposes.'\n- category: other\n  text: 'Technical digital data:\
  \ Encrypted unique digital identifier (UUID), verification code hash (QR Hash), and\n    issuance date and time.'\npurposes:\n- purpose: Real-time verification\n  text: Enabling real-time verification of certificate authenticity via direct electronic scanning.\n- purpose: Fraud prevention\n  text: Preventing forgery or unauthorized modification of documents.\n- purpose: Institutional record integrity\n  text: Protecting the integrity of digital academic records for institutions.\n- purpose: Platform continuity\n  text: Ensuring platform continuity and performance at the highest efficiency.\nretention:\n- scope: Issued digital certificates\n  period: permanently\n  text: Issued digital certificates are stored permanently to ensure future verifiability.\n- scope: Deleted account data\n  period: two (2) years\n  text: Deleted account data is retained for two (2) years after account deletion then automatically purged.\n- scope: Verification logs\n  period: 5 years\n  text: Verification logs\
  \ are retained for 5 years for auditing and compliance purposes.\nresidency:\n- region: Algeria\n  text: Sensitive data and central records are hosted on secure servers within national territory.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion; issuing entity revocation\n  text: Deleted account data is retained for two (2) years after account deletion then automatically purged.\nrights:\n- right: Access\n  text: 'Right of access: You may request a copy of the recorded data related to you.'\n- right: Rectification\n  text: 'Right of rectification: You may request correction of any material error by coordinating with the issuing\n    academic entity.'\n- right: Revocation and erasure\n  text: 'Right of revocation and erasure: The issuing entity has the right to revoke a certificate if entitlement\n    is proven invalid.'\nsale_or_sharing:\n  stance: prohibited\n  text: The platform does not\
  \ sell, lease, or commercially exploit personal data in any form.\n"
source_yaml_url: https://artifacts.apis.io/algeriacertify-com/privacy/algeriacertify-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Algeria Certify's own page on 2026-11-09.
synthetic: false
tags:
- Certificate Management
- Digital Verification
- Education
- Algeria
- Security
---
