---
api_specs:
- filename: fetchlayer-openapi-generated.yml
  format: yaml
  label: FetchLayer API
  slug: fetchlayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/_ae-authored/fetchlayer-openapi-generated.yml
- filename: fetchlayer-airbnb-api-openapi.yml
  format: yaml
  label: HootCodes Airbnb API
  slug: fetchlayer-airbnb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-airbnb-api-openapi.yml
- filename: fetchlayer-bing-api-openapi.yml
  format: yaml
  label: HootCodes Bing API
  slug: fetchlayer-bing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-bing-api-openapi.yml
- filename: fetchlayer-douyin-api-openapi.yml
  format: yaml
  label: HootCodes Douyin API
  slug: fetchlayer-douyin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-douyin-api-openapi.yml
- filename: fetchlayer-duckduckgo-api-openapi.yml
  format: yaml
  label: HootCodes Duckduckgo API
  slug: fetchlayer-duckduckgo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-duckduckgo-api-openapi.yml
- filename: fetchlayer-ebay-api-openapi.yml
  format: yaml
  label: HootCodes eBay API
  slug: fetchlayer-ebay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-ebay-api-openapi.yml
- filename: fetchlayer-temu-api-openapi.yml
  format: yaml
  label: HootCodes Temu API
  slug: fetchlayer-temu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-temu-api-openapi.yml
- filename: fetchlayer-weibo-api-openapi.yml
  format: yaml
  label: HootCodes Weibo API
  slug: fetchlayer-weibo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fetchlayer/openapi/fetchlayer-weibo-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address; name or display name, if provided
  - category: contact
    text: email address; name or display name, if provided
  - category: financial
    text: subscription or plan information; billing status, invoices, transaction references, and payment-related metadata from our payment provider
  - category: device
    text: IP address, device/browser metadata, timestamps, and request logs
  - category: behavioral
    text: API key metadata and usage metrics such as endpoint, request time, and status code
  deletion:
    route: contact privacy@hoot.codes
    text: To exercise a privacy right, contact privacy@hoot.codes .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: create and secure accounts
    text: to create and secure accounts
  - purpose: deliver API responses and features
    text: to deliver API responses, dashboards, and related features
  - purpose: measure usage and prevent abuse
    text: to measure usage, apply quotas, detect abuse, and enforce rate limits
  - purpose: process payments
    text: to process payments, invoices, and plan changes
  - purpose: security and reliability
    text: to maintain service security, reliability, and incident response
  retention:
  - period: null
    scope: account and billing records
    text: account and billing records are retained while your account is active and for a reasonable period afterward as needed for legal, accounting, and dispute purposes
  - period: up to 90 days
    scope: sign-up IP and browser hashes
    text: we keep one-way, keyed hashes of the sign-up IP address, network and browser for up to 90 days, solely to stop repeated use of free trials and promotional credits
  - period: null
    scope: third-party content
    text: We do not store, cache, index, or archive Reddit posts, comments, user profiles, or any other third-party content.
  - period: null
    scope: failed request parameters
    text: Those entries live in rolling diagnostic logs that we do not archive or back up, and they are destroyed outright whenever the service is next deployed
  rights:
  - right: access, correct, delete, restrict, object, port
    text: you may have rights to access, correct, delete, restrict, object to, or port your personal data
  - right: withdraw consent
    text: and to withdraw consent where processing is based on consent
  - right: object (GDPR Article 21)
    text: Where we process your personal data based on legitimate interests, you have the right to object at any time.
  - right: CCPA know, delete, opt out
    text: the right to know what personal information we collect, the right to delete, and the right to opt out of the sale or sharing of personal information
  role:
    text: For account administration, security, billing, and core service operations, we act as a data controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information. We do not share your personal information for cross-context behavioral advertising.
  subprocessors:
    text: Based on the current implementation, these may include providers such as Postmark for transactional email and Polar for billing.
    url: null
  transfers:
  - mechanism: other
    text: Where required, we seek to use appropriate transfer mechanisms and contractual safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HootCodes
provenance_date: '2026-11-09'
provider_name: HootCodes
provider_slug: fetchlayer
slug: fetchlayer-privacy-policy
source_date: '2026-11-09'
source_filename: fetchlayer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fetchlayer.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HootCodes\naid: fetchlayer\nurl: https://fetchlayer.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For account administration, security, billing, and core service operations, we act as a data controller.\ndata_categories:\n- category: identifying\n  text: email address; name or display name, if provided\n- category: contact\n  text: email address; name or display name, if provided\n- category: financial\n  text: subscription or plan information; billing status, invoices, transaction references, and payment-related\n    metadata from our payment provider\n- category: device\n  text:\
  \ IP address, device/browser metadata, timestamps, and request logs\n- category: behavioral\n  text: API key metadata and usage metrics such as endpoint, request time, and status code\npurposes:\n- purpose: create and secure accounts\n  text: to create and secure accounts\n- purpose: deliver API responses and features\n  text: to deliver API responses, dashboards, and related features\n- purpose: measure usage and prevent abuse\n  text: to measure usage, apply quotas, detect abuse, and enforce rate limits\n- purpose: process payments\n  text: to process payments, invoices, and plan changes\n- purpose: security and reliability\n  text: to maintain service security, reliability, and incident response\nretention:\n- scope: account and billing records\n  period: null\n  text: account and billing records are retained while your account is active and for a reasonable period afterward\n    as needed for legal, accounting, and dispute purposes\n- scope: sign-up IP and browser hashes\n  period:\
  \ up to 90 days\n  text: we keep one-way, keyed hashes of the sign-up IP address, network and browser for up to 90 days, solely to\n    stop repeated use of free trials and promotional credits\n- scope: third-party content\n  period: null\n  text: We do not store, cache, index, or archive Reddit posts, comments, user profiles, or any other third-party\n    content.\n- scope: failed request parameters\n  period: null\n  text: Those entries live in rolling diagnostic logs that we do not archive or back up, and they are destroyed\n    outright whenever the service is next deployed\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required, we seek to use appropriate transfer mechanisms and contractual safeguards.\nsubprocessors:\n  url: null\n  text: Based on the current implementation, these may include providers such as Postmark for transactional email\n    and Polar for billing.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacy@hoot.codes\n\
  \  text: To exercise a privacy right, contact privacy@hoot.codes .\nrights:\n- right: access, correct, delete, restrict, object, port\n  text: you may have rights to access, correct, delete, restrict, object to, or port your personal data\n- right: withdraw consent\n  text: and to withdraw consent where processing is based on consent\n- right: object (GDPR Article 21)\n  text: Where we process your personal data based on legitimate interests, you have the right to object at any time.\n- right: CCPA know, delete, opt out\n  text: the right to know what personal information we collect, the right to delete, and the right to opt out of\n    the sale or sharing of personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information. We do not share your personal information for cross-context behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/fetchlayer/privacy/fetchlayer-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from HootCodes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Data Extraction
- Software-as-a-Service
---
