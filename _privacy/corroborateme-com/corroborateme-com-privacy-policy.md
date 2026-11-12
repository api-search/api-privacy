---
api_specs:
- filename: corroborateme-com-agents-api-openapi.yml
  format: yaml
  label: CorroborateMe Agents API
  slug: corroborateme-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-agents-api-openapi.yml
- filename: corroborateme-com-billing-api-openapi.yml
  format: yaml
  label: CorroborateMe Billing API
  slug: corroborateme-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-billing-api-openapi.yml
- filename: corroborateme-com-companies-api-openapi.yml
  format: yaml
  label: CorroborateMe Companies API
  slug: corroborateme-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-companies-api-openapi.yml
- filename: corroborateme-com-console-auth-api-openapi.yml
  format: yaml
  label: CorroborateMe Console auth API
  slug: corroborateme-com-console-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-console-auth-api-openapi.yml
- filename: corroborateme-com-discovery-api-openapi.yml
  format: yaml
  label: CorroborateMe Discovery API
  slug: corroborateme-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-discovery-api-openapi.yml
- filename: corroborateme-com-integrations-api-openapi.yml
  format: yaml
  label: CorroborateMe Integrations API
  slug: corroborateme-com-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-integrations-api-openapi.yml
- filename: corroborateme-com-login-link-idp-api-openapi.yml
  format: yaml
  label: CorroborateMe Login-link IdP API
  slug: corroborateme-com-login-link-idp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-login-link-idp-api-openapi.yml
- filename: corroborateme-com-login-links-api-openapi.yml
  format: yaml
  label: CorroborateMe Login links API
  slug: corroborateme-com-login-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-login-links-api-openapi.yml
- filename: corroborateme-com-mcp-api-openapi.yml
  format: yaml
  label: CorroborateMe MCP API
  slug: corroborateme-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-mcp-api-openapi.yml
- filename: corroborateme-com-oidc-api-openapi.yml
  format: yaml
  label: CorroborateMe OIDC API
  slug: corroborateme-com-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corroborateme-com/openapi/corroborateme-com-oidc-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Console accounts: email and authentication artifacts (session tokens, optional OAuth / passkey credentials).'
  - category: contact
    text: 'Login-link end users: email, password hashes, OTPs (short-lived), passkeys, login session metadata, and delivery outcomes (redirect, webhook, etc.).'
  - category: device
    text: 'Technical: IP and request metadata needed for security, rate limiting, Turnstile bot checks, and operations.'
  - category: financial
    text: 'Companies: company name/slug, memberships, plan and billing references, API key hashes (not raw keys after mint), integration secrets (encrypted at rest), webhook allowlists, and audit/usage records.'
  deletion:
    route: Company owners can soft-delete a company (grace period, then hard wipe) and erase individual login-link end users.
    text: Contact support@corroborateme.com for access or deletion requests we cannot complete in-product.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and operations
    text: We use personal data to authenticate users, operate companies and APIs, meter usage, bill paid plans, prevent abuse, comply with law, and improve reliability.
  retention:
  - period: null
    scope: Active accounts and companies
    text: We retain data while accounts and companies are active and as needed for security, billing, and legal obligations.
  - period: until object lifecycle expiry
    scope: Archived audit batches
    text: Archived audit batches may retain limited identifiers until object lifecycle expiry.
  rights:
  - right: Access or deletion requests
    text: Contact support@corroborateme.com for access or deletion requests we cannot complete in-product.
  role:
    text: Where a company customer uses our login-link or OIDC features for their end users, that company is typically the controller of end-user identity data for their app; we process it to provide the Service on their instructions.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Infrastructure runs on Cloudflare (Workers, D1, KV, R2, Email Routing / sending as configured, Turnstile). Payments go through Stripe.
    url: null
  transfers:
  - mechanism: other
    text: Processing may occur in the regions where Cloudflare and our processors operate. By using the Service you acknowledge that transfers may be necessary to provide it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CorroborateMe
provenance_date: '2026-11-09'
provider_name: CorroborateMe
provider_slug: corroborateme-com
slug: corroborateme-com-privacy-policy
source_date: '2026-11-09'
source_filename: corroborateme-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corroborateme.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CorroborateMe\naid: corroborateme-com\nurl: https://corroborateme.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where a company customer uses our login-link or OIDC features for their end users, that company is typically\n    the controller of end-user identity data for their app; we process it to provide the Service on their instructions.\ndata_categories:\n- category: identifying\n  text: 'Console accounts: email and authentication artifacts (session tokens, optional OAuth / passkey credentials).'\n- category: contact\n  text: 'Login-link end users: email, password hashes, OTPs (short-lived),\
  \ passkeys, login session metadata, and\n    delivery outcomes (redirect, webhook, etc.).'\n- category: device\n  text: 'Technical: IP and request metadata needed for security, rate limiting, Turnstile bot checks, and operations.'\n- category: financial\n  text: 'Companies: company name/slug, memberships, plan and billing references, API key hashes (not raw keys after\n    mint), integration secrets (encrypted at rest), webhook allowlists, and audit/usage records.'\npurposes:\n- purpose: Authentication and operations\n  text: We use personal data to authenticate users, operate companies and APIs, meter usage, bill paid plans, prevent\n    abuse, comply with law, and improve reliability.\nretention:\n- scope: Active accounts and companies\n  period: null\n  text: We retain data while accounts and companies are active and as needed for security, billing, and legal obligations.\n- scope: Archived audit batches\n  period: until object lifecycle expiry\n  text: Archived audit batches may retain\
  \ limited identifiers until object lifecycle expiry.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Processing may occur in the regions where Cloudflare and our processors operate. By using the Service you\n    acknowledge that transfers may be necessary to provide it.\nsubprocessors:\n  url: null\n  text: Infrastructure runs on Cloudflare (Workers, D1, KV, R2, Email Routing / sending as configured, Turnstile).\n    Payments go through Stripe.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Company owners can soft-delete a company (grace period, then hard wipe) and erase individual login-link\n    end users.\n  text: Contact support@corroborateme.com for access or deletion requests we cannot complete in-product.\nrights:\n- right: Access or deletion requests\n  text: Contact support@corroborateme.com for access or deletion requests we cannot complete in-product.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/corroborateme-com/privacy/corroborateme-com-privacy-policy.yml
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
summary_line: 13 quoted statements, read from CorroborateMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Authentication
- Identity
- Sign-In
- Passkeys
- OIDC
- Single Sign-On
- AI Agents
- MCP
---
