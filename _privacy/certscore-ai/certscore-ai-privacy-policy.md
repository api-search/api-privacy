---
api_specs:
- filename: certscore-ai-auth-api-openapi.yml
  format: yaml
  label: certscore-ai Auth API
  slug: certscore-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-auth-api-openapi.yml
- filename: certscore-ai-diagnostics-api-openapi.yml
  format: yaml
  label: certscore-ai Diagnostics API
  slug: certscore-ai-diagnostics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-diagnostics-api-openapi.yml
- filename: certscore-ai-domains-api-openapi.yml
  format: yaml
  label: certscore-ai Domains API
  slug: certscore-ai-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-domains-api-openapi.yml
- filename: certscore-ai-findings-api-openapi.yml
  format: yaml
  label: certscore-ai Findings API
  slug: certscore-ai-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-findings-api-openapi.yml
- filename: certscore-ai-pulse-api-openapi.yml
  format: yaml
  label: certscore-ai Pulse API
  slug: certscore-ai-pulse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-pulse-api-openapi.yml
- filename: certscore-ai-runtime-inventory-api-openapi.yml
  format: yaml
  label: certscore-ai Runtime Inventory API
  slug: certscore-ai-runtime-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-runtime-inventory-api-openapi.yml
- filename: certscore-ai-scans-api-openapi.yml
  format: yaml
  label: certscore-ai Scans API
  slug: certscore-ai-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certscore-ai/openapi/certscore-ai-scans-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: We may collect information you provide directly, such as your email address, name, authentication details, submitted domains, scan settings, selected plan, and account preferences.
  - category: device
    text: We may collect technical information needed to operate the service, such as authentication events, usage logs, scan status events, browser metadata, and product interaction data.
  - category: financial
    text: CertScore.ai may retain Stripe customer identifiers, subscription identifiers, plan status, invoice or checkout status, billing event metadata
  deletion:
    route: privacy request form or email
    text: To exercise privacy rights, use the CertScore.ai privacy request form or email [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account administration and authentication
    text: CertScore.ai processes personal data and service data for account administration, authentication, scan and report delivery, monitoring, customer support, billing, security
  retention:
  - period: 90 days
    scope: authenticated application activity records
    text: These activity records are restricted to authorized administrators and retained for up to 90 days, subject to routine deletion processing.
  - period: null
    scope: personal data generally
    text: We retain personal data only for as long as necessary for the purposes described in this policy.
  rights:
  - right: access, correction, deletion, restriction, portability, objection
    text: you may request access, correction, deletion, restriction, portability, or objection in relation to your personal data
  - right: withdraw consent
    text: may have rights to withdraw consent or exercise certain opt-outs
  role:
    text: CertScore.ai is the controller of personal data described in this policy unless this policy states otherwise.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: CertScore.ai does not describe service-provider access alone as a sale of personal information.
  subprocessors:
    text: Current provider examples include AWS for hosting and infrastructure, Stripe for payment and subscription processing, Gmail SMTP where applicable for email delivery, Google Analytics for optional website analytics, and Microsoft Clarity for optional session-insight analysis.
    url: null
  transfers:
  - mechanism: other
    text: International transfers of personal data may occur because CertScore.ai is operated from the United States and uses service providers that may process information in the United States and other countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: certscore-ai
provenance_date: '2026-11-09'
provider_name: certscore-ai
provider_slug: certscore-ai
slug: certscore-ai-privacy-policy
source_date: '2026-11-09'
source_filename: certscore-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://certscore.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: certscore-ai\naid: certscore-ai\nurl: https://certscore.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CertScore.ai is the controller of personal data described in this policy unless this policy states otherwise.\ndata_categories:\n- category: contact\n  text: We may collect information you provide directly, such as your email address, name, authentication details,\n    submitted domains, scan settings, selected plan, and account preferences.\n- category: device\n  text: We may collect technical information needed to operate the service, such as authentication events, usage\n  \
  \  logs, scan status events, browser metadata, and product interaction data.\n- category: financial\n  text: CertScore.ai may retain Stripe customer identifiers, subscription identifiers, plan status, invoice or checkout\n    status, billing event metadata\npurposes:\n- purpose: account administration and authentication\n  text: CertScore.ai processes personal data and service data for account administration, authentication, scan and\n    report delivery, monitoring, customer support, billing, security\nretention:\n- scope: authenticated application activity records\n  period: 90 days\n  text: These activity records are restricted to authorized administrators and retained for up to 90 days, subject\n    to routine deletion processing.\n- scope: personal data generally\n  period: null\n  text: We retain personal data only for as long as necessary for the purposes described in this policy.\nresidency: []\ntransfers:\n- mechanism: other\n  text: International transfers of personal data may\
  \ occur because CertScore.ai is operated from the United States\n    and uses service providers that may process information in the United States and other countries.\nsubprocessors:\n  url: null\n  text: Current provider examples include AWS for hosting and infrastructure, Stripe for payment and subscription\n    processing, Gmail SMTP where applicable for email delivery, Google Analytics for optional website analytics,\n    and Microsoft Clarity for optional session-insight analysis.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy request form or email\n  text: To exercise privacy rights, use the CertScore.ai privacy request form or email [email protected] .\nrights:\n- right: access, correction, deletion, restriction, portability, objection\n  text: you may request access, correction, deletion, restriction, portability, or objection in relation to your\n    personal data\n- right: withdraw consent\n  text: may have rights to withdraw consent or exercise\
  \ certain opt-outs\nsale_or_sharing:\n  stance: unstated\n  text: CertScore.ai does not describe service-provider access alone as a sale of personal information.\n"
source_yaml_url: https://artifacts.apis.io/certscore-ai/privacy/certscore-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 12 quoted statements, read from certscore-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Security
- Scanning
- Compliance
---
