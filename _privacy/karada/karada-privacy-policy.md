---
api_specs:
- filename: karada-admin-api-openapi.yml
  format: yaml
  label: Karada AI Admin API
  slug: karada-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-admin-api-openapi.yml
- filename: karada-auth-api-openapi.yml
  format: yaml
  label: Karada AI Auth API
  slug: karada-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-auth-api-openapi.yml
- filename: karada-billing-api-openapi.yml
  format: yaml
  label: Karada AI Billing API
  slug: karada-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-billing-api-openapi.yml
- filename: karada-deployments-api-openapi.yml
  format: yaml
  label: Karada AI Deployments API
  slug: karada-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-deployments-api-openapi.yml
- filename: karada-feedback-api-openapi.yml
  format: yaml
  label: Karada AI Feedback API
  slug: karada-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-feedback-api-openapi.yml
- filename: karada-gateway-api-openapi.yml
  format: yaml
  label: Karada AI Gateway API
  slug: karada-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-gateway-api-openapi.yml
- filename: karada-marketplace-api-openapi.yml
  format: yaml
  label: Karada AI Marketplace API
  slug: karada-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-marketplace-api-openapi.yml
- filename: karada-mcp-api-openapi.yml
  format: yaml
  label: Karada AI MCP API
  slug: karada-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-mcp-api-openapi.yml
- filename: karada-newsletter-api-openapi.yml
  format: yaml
  label: Karada AI Newsletter API
  slug: karada-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-newsletter-api-openapi.yml
- filename: karada-pricing-api-openapi.yml
  format: yaml
  label: Karada AI Pricing API
  slug: karada-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-pricing-api-openapi.yml
- filename: karada-projects-api-openapi.yml
  format: yaml
  label: Karada AI Projects API
  slug: karada-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-projects-api-openapi.yml
- filename: karada-registry-api-openapi.yml
  format: yaml
  label: Karada AI Registry API
  slug: karada-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-registry-api-openapi.yml
- filename: karada-system-api-openapi.yml
  format: yaml
  label: Karada AI System API
  slug: karada-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-system-api-openapi.yml
- filename: karada-teams-api-openapi.yml
  format: yaml
  label: Karada AI Teams API
  slug: karada-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-teams-api-openapi.yml
- filename: karada-user-api-openapi.yml
  format: yaml
  label: Karada AI User API
  slug: karada-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/karada/openapi/karada-user-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address, name, organization name, and authentication tokens provided via OAuth providers (such as GitHub or Google)
  - category: financial
    text: transactions are processed directly by authorized PCI-DSS compliant payment providers (such as Stripe or Paddle)
  - category: device
    text: our platform records infrastructure telemetry, including request timestamps, execution duration (latency in milliseconds), HTTP status codes, and container memory consumption
  deletion:
    route: Request by emailing privacy@karada.ai; account deletion from dashboard
    text: You can request the permanent deletion of your account and all associated MCP deployments by emailing privacy@karada.ai .
  dpa:
    available: null
    text: Each vendor undergoes security assessment and is bound by Data Processing Addenda (DPAs)
    url: null
  purposes:
  - purpose: Provide, maintain and protect the Service
    text: We collect only the minimum personal and technical information necessary to provide, maintain, and protect the Service
  - purpose: Product analytics
    text: PostHog Product analytics and feature usage (anonymized)
  - purpose: No AI model training
    text: We NEVER train AI models on your code, OpenAPI specs, API secrets, or MCP runtime payloads.
  residency:
  - region: United States and other global regions
    text: Karada utilizes cloud infrastructure hosted in the United States and other globally distributed regions.
  retention:
  - period: within thirty (30) days
    scope: 'Account deletion: deployments, secrets, configurations'
    text: Upon account deletion, all active serverless container instances, secret vault entries, and server configurations are immediately de-provisioned and permanently purged from production databases within thirty (30) days.
  - period: sixty (60) day backup rotation
    scope: Ephemeral server logs and backups
    text: Ephemeral server logs and backups are cycled and overwritten within our standard sixty (60) day backup rotation.
  rights:
  - right: Access and portability
    text: You can export your team definitions, OpenAPI configurations, and generated Go MCP server projects at any time from the dashboard.
  - right: Rectification
    text: You can update your name, email, and team information directly in your account profile settings.
  - right: Erasure
    text: You can request the permanent deletion of your account and all associated MCP deployments by emailing privacy@karada.ai .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell, rent, or monetize your personal data, API specifications, or telemetry to third-party data brokers or advertising networks.
  subprocessors:
    text: Each vendor undergoes security assessment and is bound by Data Processing Addenda (DPAs)
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on European Commission approved Standard Contractual Clauses (SCCs) and equivalent UK data transfer mechanisms to protect your information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Karada AI
provenance_date: '2026-11-09'
provider_name: Karada AI
provider_slug: karada
slug: karada-privacy-policy
source_date: '2026-11-09'
source_filename: karada-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://karada.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Karada AI\naid: karada\nurl: https://karada.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your email address, name, organization name, and authentication tokens provided via OAuth providers\n    (such as GitHub or Google)\n- category: financial\n  text: transactions are processed directly by authorized PCI-DSS compliant payment providers (such as Stripe or\n    Paddle)\n- category: device\n  text: our platform records infrastructure telemetry, including request timestamps, execution duration (latency\n    in milliseconds),\
  \ HTTP status codes, and container memory consumption\npurposes:\n- purpose: Provide, maintain and protect the Service\n  text: We collect only the minimum personal and technical information necessary to provide, maintain, and protect\n    the Service\n- purpose: Product analytics\n  text: PostHog Product analytics and feature usage (anonymized)\n- purpose: No AI model training\n  text: We NEVER train AI models on your code, OpenAPI specs, API secrets, or MCP runtime payloads.\nretention:\n- scope: 'Account deletion: deployments, secrets, configurations'\n  period: within thirty (30) days\n  text: Upon account deletion, all active serverless container instances, secret vault entries, and server configurations\n    are immediately de-provisioned and permanently purged from production databases within thirty (30) days.\n- scope: Ephemeral server logs and backups\n  period: sixty (60) day backup rotation\n  text: Ephemeral server logs and backups are cycled and overwritten within our standard\
  \ sixty (60) day backup rotation.\nresidency:\n- region: United States and other global regions\n  text: Karada utilizes cloud infrastructure hosted in the United States and other globally distributed regions.\ntransfers:\n- mechanism: SCC\n  text: we rely on European Commission approved Standard Contractual Clauses (SCCs) and equivalent UK data transfer\n    mechanisms to protect your information\nsubprocessors:\n  url: null\n  text: Each vendor undergoes security assessment and is bound by Data Processing Addenda (DPAs)\ndpa:\n  available: null\n  url: null\n  text: Each vendor undergoes security assessment and is bound by Data Processing Addenda (DPAs)\ndeletion:\n  route: Request by emailing privacy@karada.ai; account deletion from dashboard\n  text: You can request the permanent deletion of your account and all associated MCP deployments by emailing privacy@karada.ai\n    .\nrights:\n- right: Access and portability\n  text: You can export your team definitions, OpenAPI configurations,\
  \ and generated Go MCP server projects at any\n    time from the dashboard.\n- right: Rectification\n  text: You can update your name, email, and team information directly in your account profile settings.\n- right: Erasure\n  text: You can request the permanent deletion of your account and all associated MCP deployments by emailing privacy@karada.ai\n    .\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell, rent, or monetize your personal data, API specifications, or telemetry to third-party\n    data brokers or advertising networks.\n"
source_yaml_url: https://artifacts.apis.io/karada/privacy/karada-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Karada AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- MCP
- Automation
---
