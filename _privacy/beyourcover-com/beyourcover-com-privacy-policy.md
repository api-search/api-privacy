---
api_specs:
- filename: beyourcover-com-account-api-openapi.yml
  format: yaml
  label: BeYourCover Account API
  slug: beyourcover-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-account-api-openapi.yml
- filename: beyourcover-com-books-api-openapi.yml
  format: yaml
  label: BeYourCover Books API
  slug: beyourcover-com-books-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-books-api-openapi.yml
- filename: beyourcover-com-clients-api-openapi.yml
  format: yaml
  label: BeYourCover Clients API
  slug: beyourcover-com-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-clients-api-openapi.yml
- filename: beyourcover-com-covers-api-openapi.yml
  format: yaml
  label: BeYourCover Covers API
  slug: beyourcover-com-covers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-covers-api-openapi.yml
- filename: beyourcover-com-jobs-api-openapi.yml
  format: yaml
  label: BeYourCover Jobs API
  slug: beyourcover-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-jobs-api-openapi.yml
- filename: beyourcover-com-service-api-openapi.yml
  format: yaml
  label: BeYourCover Service API
  slug: beyourcover-com-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-service-api-openapi.yml
- filename: beyourcover-com-templates-api-openapi.yml
  format: yaml
  label: BeYourCover Templates API
  slug: beyourcover-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-templates-api-openapi.yml
- filename: beyourcover-com-wraps-api-openapi.yml
  format: yaml
  label: BeYourCover Wraps API
  slug: beyourcover-com-wraps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-wraps-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile data, such as your name, email address, authentication identifiers, OAuth or magic-link login metadata, and account preferences.
  - category: financial
    text: Billing and subscription information, such as plan selection, transaction identifiers, purchase records, credit balances, subscription status, and limited payment metadata provided by Stripe.
  - category: behavioral
    text: Prompt and generation data, including raw prompts, adapted prompts, prompt history, model selections, job parameters, and generation logs.
  - category: communication
    text: Communications and support data, such as support messages, contact-form submissions, and marketing-consent or unsubscribe records.
  - category: device
    text: Technical and usage data, such as IP address, browser type, device information, cookies, analytics identifiers, affiliate or referral identifiers, error logs, and feature-usage events.
  deletion:
    route: Deletion request via support contact
    text: If you request deletion, we may retain limited records where necessary for security, fraud prevention, tax, accounting, legal compliance, or backup restoration purposes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: We use personal information to provide, operate, secure, and improve the service.
  - purpose: Process payments
    text: processing payments, enforcing limits and credits, providing support, sending service emails
  - purpose: AI processing
    text: Your prompts, book details, uploaded images, and related content may be sent to AI and storage providers to generate, edit, upscale, analyze, store, cache, and deliver outputs.
  - purpose: Aggregated statistics
    text: We may also create aggregated, de-identified statistics from book details and usage
  retention:
  - period: null
    scope: General account and service data
    text: We retain information for as long as needed to provide the service, maintain your account, operate paid features, resolve disputes, enforce our agreements, and comply with legal obligations.
  rights:
  - right: Access, correction, deletion
    text: Request access to, correction of, or deletion of certain personal data we hold about you.
  - right: Object or restrict
    text: Object to or request restriction of certain processing where applicable law provides that right.
  - right: Portability
    text: Request a copy of certain personal data in a portable format where applicable law provides that right.
  - right: Complaint
    text: Lodge a complaint with a competent data protection authority if you believe your rights have been violated.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We share information with service providers and subprocessors only as reasonably necessary to operate the platform, process payments, authenticate users, deliver emails, store assets, monitor performance, and run AI workflows.
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use appropriate safeguards for international transfers, such as contractual protections, provider commitments, or other lawful transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BeYourCover
provenance_date: '2026-11-09'
provider_name: BeYourCover
provider_slug: beyourcover-com
slug: beyourcover-com-privacy-policy
source_date: '2026-11-09'
source_filename: beyourcover-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://beyourcover.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BeYourCover\naid: beyourcover-com\nurl: https://beyourcover.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and profile data, such as your name, email address, authentication identifiers, OAuth or magic-link\n    login metadata, and account preferences.\n- category: financial\n  text: Billing and subscription information, such as plan selection, transaction identifiers, purchase records,\n    credit balances, subscription status, and limited payment metadata provided by Stripe.\n- category: behavioral\n  text:\
  \ Prompt and generation data, including raw prompts, adapted prompts, prompt history, model selections, job\n    parameters, and generation logs.\n- category: communication\n  text: Communications and support data, such as support messages, contact-form submissions, and marketing-consent\n    or unsubscribe records.\n- category: device\n  text: Technical and usage data, such as IP address, browser type, device information, cookies, analytics identifiers,\n    affiliate or referral identifiers, error logs, and feature-usage events.\npurposes:\n- purpose: Provide and operate the service\n  text: We use personal information to provide, operate, secure, and improve the service.\n- purpose: Process payments\n  text: processing payments, enforcing limits and credits, providing support, sending service emails\n- purpose: AI processing\n  text: Your prompts, book details, uploaded images, and related content may be sent to AI and storage providers\n    to generate, edit, upscale, analyze, store,\
  \ cache, and deliver outputs.\n- purpose: Aggregated statistics\n  text: We may also create aggregated, de-identified statistics from book details and usage\nretention:\n- scope: General account and service data\n  period: null\n  text: We retain information for as long as needed to provide the service, maintain your account, operate paid\n    features, resolve disputes, enforce our agreements, and comply with legal obligations.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required, we use appropriate safeguards for international transfers, such as contractual protections,\n    provider commitments, or other lawful transfer mechanisms.\nsubprocessors:\n  url: null\n  text: We share information with service providers and subprocessors only as reasonably necessary to operate the\n    platform, process payments, authenticate users, deliver emails, store assets, monitor performance, and run AI\n    workflows.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: Deletion request via support contact\n  text: If you request deletion, we may retain limited records where necessary for security, fraud prevention, tax,\n    accounting, legal compliance, or backup restoration purposes.\nrights:\n- right: Access, correction, deletion\n  text: Request access to, correction of, or deletion of certain personal data we hold about you.\n- right: Object or restrict\n  text: Object to or request restriction of certain processing where applicable law provides that right.\n- right: Portability\n  text: Request a copy of certain personal data in a portable format where applicable law provides that right.\n- right: Complaint\n  text: Lodge a complaint with a competent data protection authority if you believe your rights have been violated.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beyourcover-com/privacy/beyourcover-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from BeYourCover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- BookCover
- Design
- Publishing
---
