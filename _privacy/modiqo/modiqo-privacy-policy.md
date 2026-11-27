---
api_specs:
- filename: modiqo-sales-api-openapi.yml
  format: yaml
  label: Modiqo Sales API
  slug: modiqo-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modiqo/openapi/modiqo-sales-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your name, email address, and authentication credentials
  - category: financial
    text: payment details are processed by our third-party payment processor (Stripe). We do not store full credit card numbers.
  - category: device
    text: Operating system family, processor architecture, rote CLI version, whether the Service is running in a continuous-integration environment
  - category: behavioral
    text: Pseudonymous usage data tied to your registered account identifier and to a randomly generated installation identifier created on first use.
  - category: location
    text: 'Log Data: Server logs including IP address, browser type, operating system, referring URLs, access timestamps, and pages viewed'
  - category: contact
    text: 'Communications and Sales Inquiries: When you contact us for support, feedback, or a sales inquiry, we collect the information you submit.'
  deletion:
    route: Contact the privacy email address; deletion requests processed within 30 days
    text: We will process deletion requests within 30 days, subject to legal retention requirements.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service operation
    text: Providing, maintaining, and improving the Service
  - purpose: Usage quotas and product analytics
    text: Measuring usage volume on a per-account basis to administer plan limits, fair-use thresholds, and quotas applicable to your subscription tier
  - purpose: Communication
    text: Responding to support requests and inquiries
  - purpose: Safety and compliance
    text: Detecting, preventing, and addressing fraud, abuse, or security incidents
  residency:
  - region: United States
    text: Your information may be transferred to and processed in the United States, where our servers and operations are located.
  retention:
  - period: ninety (90) days
    scope: Raw usage telemetry
    text: Pseudonymous telemetry events tied to your registered account or installation identifier are retained for no more than ninety (90) days
  - period: twelve (12) months
    scope: Log data
    text: Server logs are retained for up to twelve (12) months.
  - period: null
    scope: Account data
    text: Retained while your account is active and for a reasonable period after deletion to comply with legal obligations.
  - period: indefinitely
    scope: Aggregated telemetry metrics
    text: Aggregated and statistical metrics derived from telemetry, which do not identify any individual account, may be retained indefinitely
  rights:
  - right: Access and portability
    text: You may request a copy of the personal information we hold about you by contacting [email protected] .
  - right: Correction
    text: You may update or correct your account information through the Service or by contacting us.
  - right: Deletion
    text: You may request deletion of your account and associated personal data by contacting [email protected] .
  - right: Opt-out of telemetry
    text: You may opt out of telemetry collection and upload at any time through the telemetry-control facilities provided by the Service
  - right: Opt-out of sale (CCPA)
    text: 'Right to Opt-Out of Sale: We do not sell personal information.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'Current and planned service providers include: Cloudflare: Website hosting, content delivery, security, and serverless request processing'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Modiqo
provenance_date: '2026-11-10'
provider_name: Modiqo
provider_slug: modiqo
slug: modiqo-privacy-policy
source_date: '2026-11-10'
source_filename: modiqo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.modiqo.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Modiqo\naid: modiqo\nurl: https://www.modiqo.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your name, email address, and authentication credentials\n- category: financial\n  text: payment details are processed by our third-party payment processor (Stripe). We do not store full credit\n    card numbers.\n- category: device\n  text: Operating system family, processor architecture, rote CLI version, whether the Service is running in a continuous-integration\n    environment\n- category: behavioral\n\
  \  text: Pseudonymous usage data tied to your registered account identifier and to a randomly generated installation\n    identifier created on first use.\n- category: location\n  text: 'Log Data: Server logs including IP address, browser type, operating system, referring URLs, access timestamps,\n    and pages viewed'\n- category: contact\n  text: 'Communications and Sales Inquiries: When you contact us for support, feedback, or a sales inquiry, we collect\n    the information you submit.'\npurposes:\n- purpose: Service operation\n  text: Providing, maintaining, and improving the Service\n- purpose: Usage quotas and product analytics\n  text: Measuring usage volume on a per-account basis to administer plan limits, fair-use thresholds, and quotas\n    applicable to your subscription tier\n- purpose: Communication\n  text: Responding to support requests and inquiries\n- purpose: Safety and compliance\n  text: Detecting, preventing, and addressing fraud, abuse, or security incidents\nretention:\n\
  - scope: Raw usage telemetry\n  period: ninety (90) days\n  text: Pseudonymous telemetry events tied to your registered account or installation identifier are retained for\n    no more than ninety (90) days\n- scope: Log data\n  period: twelve (12) months\n  text: Server logs are retained for up to twelve (12) months.\n- scope: Account data\n  period: null\n  text: Retained while your account is active and for a reasonable period after deletion to comply with legal obligations.\n- scope: Aggregated telemetry metrics\n  period: indefinitely\n  text: Aggregated and statistical metrics derived from telemetry, which do not identify any individual account,\n    may be retained indefinitely\nresidency:\n- region: United States\n  text: Your information may be transferred to and processed in the United States, where our servers and operations\n    are located.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Current and planned service providers include: Cloudflare: Website hosting, content\
  \ delivery, security,\n    and serverless request processing'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the privacy email address; deletion requests processed within 30 days\n  text: We will process deletion requests within 30 days, subject to legal retention requirements.\nrights:\n- right: Access and portability\n  text: You may request a copy of the personal information we hold about you by contacting [email protected] .\n- right: Correction\n  text: You may update or correct your account information through the Service or by contacting us.\n- right: Deletion\n  text: You may request deletion of your account and associated personal data by contacting [email protected] .\n- right: Opt-out of telemetry\n  text: You may opt out of telemetry collection and upload at any time through the telemetry-control facilities\n    provided by the Service\n- right: Opt-out of sale (CCPA)\n  text: 'Right to Opt-Out of Sale: We do not sell personal information.'\n\
  sale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/modiqo/privacy/modiqo-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Modiqo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workflows
- Automation
- Platform
---
