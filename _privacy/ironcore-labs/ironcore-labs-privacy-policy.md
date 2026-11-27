---
api_specs:
- filename: ironcore-labs-configuration-assignment-api-openapi.yml
  format: yaml
  label: IronCore Labs Configuration Assignment API
  slug: ironcore-labs-configuration-assignment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironcore-labs/openapi/ironcore-labs-configuration-assignment-api-openapi.yml
- filename: ironcore-labs-kms-configuration-api-openapi.yml
  format: yaml
  label: IronCore Labs KMS Configuration API
  slug: ironcore-labs-kms-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironcore-labs/openapi/ironcore-labs-kms-configuration-api-openapi.yml
- filename: ironcore-labs-tag-api-openapi.yml
  format: yaml
  label: IronCore Labs Tag API
  slug: ironcore-labs-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironcore-labs/openapi/ironcore-labs-tag-api-openapi.yml
- filename: ironcore-labs-tenant-api-openapi.yml
  format: yaml
  label: IronCore Labs Tenant API
  slug: ironcore-labs-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironcore-labs/openapi/ironcore-labs-tenant-api-openapi.yml
- filename: ironcore-labs-tenant-secret-api-openapi.yml
  format: yaml
  label: IronCore Labs Tenant Secret API
  slug: ironcore-labs-tenant-secret-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ironcore-labs/openapi/ironcore-labs-tenant-secret-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect data from you when you set up an account with IronCore, like your name, email address, and billing information.
  - category: behavioral
    text: We use cookies to collect data automatically about your use of our website or for advertising.
  - category: device
    text: we collect your IP addresses to track and analyze information about the devices that are connecting to our systems
  - category: communication
    text: we keep records of the queries and our responses indefinitely until we receive a request at privacy@ironcorelabs.com to delete those conversations.
  deletion:
    route: email privacy@ironcorelabs.com
    text: If you want to ask how to delete or access your data, email privacy@ironcorelabs.com .
  dpa:
    available: true
    text: We offer data processing and security terms for our products to help customers meet GDPR.
    url: null
  purposes:
  - purpose: provide services and billing
    text: We use that data to do things like communicate with you about your account and bill you for using our products and services.
  - purpose: fraud and security
    text: to watch out for fraud, and to improve our products and services.
  - purpose: advertising
    text: We do not use customer data or derive information from it for advertising.
  residency:
  - region: United States
    text: Your data is transferred to the U.S.
  retention:
  - period: indefinitely
    scope: direct customer information
    text: Our direct customer information is maintained indefinitely, even after a customer is no longer doing business with IronCore Labs
  - period: 30 days
    scope: website logs
    text: All website logs older than 30 days are purged daily.
  - period: up to a year
    scope: job applications
    text: Those resumés and applications are kept for up to a year after a position is filled
  - period: 30 days, one year, or unlimited
    scope: audit trail logs
    text: Audit trail logs of customer users and files are stored for a length of time which is under customer control, either 30 days, one year, or unlimited, depending on customer tier.
  rights:
  - right: erasure
    text: we always provide ways for users to opt-out of emails or to request that their data be removed from our systems.
  - right: access
    text: Our customers can view their own information via the console.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not use customer data or derive information from it for advertising.
  subprocessors:
    text: We do engage some third-party vendors to assist in supporting our services, particularly in support of our sales, customer support, and billing needs.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IronCore Labs
provenance_date: '2026-11-09'
provider_name: IronCore Labs
provider_slug: ironcore-labs
slug: ironcore-labs-privacy-policy
source_date: '2026-11-09'
source_filename: ironcore-labs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ironcorelabs.com/trust-center/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IronCore Labs\naid: ironcore-labs\nurl: https://ironcorelabs.com/trust-center/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We collect data from you when you set up an account with IronCore, like your name, email address, and billing\n    information.\n- category: behavioral\n  text: We use cookies to collect data automatically about your use of our website or for advertising.\n- category: device\n  text: we collect your IP addresses to track and analyze information about the devices that are connecting to our\n    systems\n- category:\
  \ communication\n  text: we keep records of the queries and our responses indefinitely until we receive a request at privacy@ironcorelabs.com\n    to delete those conversations.\npurposes:\n- purpose: provide services and billing\n  text: We use that data to do things like communicate with you about your account and bill you for using our products\n    and services.\n- purpose: fraud and security\n  text: to watch out for fraud, and to improve our products and services.\n- purpose: advertising\n  text: We do not use customer data or derive information from it for advertising.\nretention:\n- scope: direct customer information\n  period: indefinitely\n  text: Our direct customer information is maintained indefinitely, even after a customer is no longer doing business\n    with IronCore Labs\n- scope: website logs\n  period: 30 days\n  text: All website logs older than 30 days are purged daily.\n- scope: job applications\n  period: up to a year\n  text: Those resumés and applications are\
  \ kept for up to a year after a position is filled\n- scope: audit trail logs\n  period: 30 days, one year, or unlimited\n  text: Audit trail logs of customer users and files are stored for a length of time which is under customer control,\n    either 30 days, one year, or unlimited, depending on customer tier.\nresidency:\n- region: United States\n  text: Your data is transferred to the U.S.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We do engage some third-party vendors to assist in supporting our services, particularly in support of our\n    sales, customer support, and billing needs.\ndpa:\n  available: true\n  url: null\n  text: We offer data processing and security terms for our products to help customers meet GDPR.\ndeletion:\n  route: email privacy@ironcorelabs.com\n  text: If you want to ask how to delete or access your data, email privacy@ironcorelabs.com .\nrights:\n- right: erasure\n  text: we always provide ways for users to opt-out of emails or to request that their\
  \ data be removed from our\n    systems.\n- right: access\n  text: Our customers can view their own information via the console.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use customer data or derive information from it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/ironcore-labs/privacy/ironcore-labs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from IronCore Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Encryption
- Privacy
- Security
- Application-Layer Encryption
- Key Management
- Cryptography
- Artificial Intelligence
- Software-as-a-Service
---
