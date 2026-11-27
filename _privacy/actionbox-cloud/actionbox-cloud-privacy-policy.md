---
api_specs:
- filename: actionbox-cloud-account-api-openapi.yml
  format: yaml
  label: actionbox-cloud Account API
  slug: actionbox-cloud-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-account-api-openapi.yml
- filename: actionbox-cloud-actions-api-openapi.yml
  format: yaml
  label: actionbox-cloud Actions API
  slug: actionbox-cloud-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-actions-api-openapi.yml
- filename: actionbox-cloud-analytics-api-openapi.yml
  format: yaml
  label: actionbox-cloud Analytics API
  slug: actionbox-cloud-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-analytics-api-openapi.yml
- filename: actionbox-cloud-auth-api-openapi.yml
  format: yaml
  label: actionbox-cloud Auth API
  slug: actionbox-cloud-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-auth-api-openapi.yml
- filename: actionbox-cloud-billing-api-openapi.yml
  format: yaml
  label: actionbox-cloud Billing API
  slug: actionbox-cloud-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-billing-api-openapi.yml
- filename: actionbox-cloud-dashboard-api-openapi.yml
  format: yaml
  label: actionbox-cloud Dashboard API
  slug: actionbox-cloud-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-dashboard-api-openapi.yml
- filename: actionbox-cloud-devices-api-openapi.yml
  format: yaml
  label: actionbox-cloud Devices API
  slug: actionbox-cloud-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-devices-api-openapi.yml
- filename: actionbox-cloud-documentation-api-openapi.yml
  format: yaml
  label: actionbox-cloud Documentation API
  slug: actionbox-cloud-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-documentation-api-openapi.yml
- filename: actionbox-cloud-feedback-api-openapi.yml
  format: yaml
  label: actionbox-cloud Feedback API
  slug: actionbox-cloud-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-feedback-api-openapi.yml
- filename: actionbox-cloud-notifications-api-openapi.yml
  format: yaml
  label: actionbox-cloud Notifications API
  slug: actionbox-cloud-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-notifications-api-openapi.yml
- filename: actionbox-cloud-runs-api-openapi.yml
  format: yaml
  label: actionbox-cloud Runs API
  slug: actionbox-cloud-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-runs-api-openapi.yml
- filename: actionbox-cloud-slack-api-openapi.yml
  format: yaml
  label: actionbox-cloud Slack API
  slug: actionbox-cloud-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-slack-api-openapi.yml
- filename: actionbox-cloud-sources-api-openapi.yml
  format: yaml
  label: actionbox-cloud Sources API
  slug: actionbox-cloud-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-sources-api-openapi.yml
- filename: actionbox-cloud-system-api-openapi.yml
  format: yaml
  label: actionbox-cloud System API
  slug: actionbox-cloud-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-system-api-openapi.yml
- filename: actionbox-cloud-watches-api-openapi.yml
  format: yaml
  label: actionbox-cloud Watches API
  slug: actionbox-cloud-watches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-watches-api-openapi.yml
- filename: actionbox-cloud-webhooks-api-openapi.yml
  format: yaml
  label: actionbox-cloud Webhooks API
  slug: actionbox-cloud-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-webhooks-api-openapi.yml
- filename: actionbox-cloud-workspaces-api-openapi.yml
  format: yaml
  label: actionbox-cloud Workspaces API
  slug: actionbox-cloud-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionbox-cloud/openapi/actionbox-cloud-workspaces-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, display name, Google or Apple account subject identifier, account creation time, and sign-in or account-linking events
  - category: device
    text: device name, platform and operating-system family, app version, an Actionbox-generated device registration identifier
  - category: behavioral
    text: page and route views, referrer host/path, UTM and campaign fields, coarse interaction events
  - category: financial
    text: transaction identifiers, subscription status, billing country or postal code, currency, and invoice history provided by our Merchant of Record
  - category: location
    text: coarse country or region derived by the provider
  - category: communication
    text: When you voluntarily send product feedback from the signed-in dashboard, Actionbox stores the category, message, a generalized page route, limited display context, your account, and workspace
  deletion:
    route: Delete account in the mobile application or dashboard, or DELETE /v1/account with confirmation; or email info@actionbox.cloud with subject 'Account deletion'
    text: They can permanently delete the account and its tenant-scoped records with Delete account in the mobile application or dashboard, or with `DELETE /v1/account` after sending the exact confirmation `DELETE ACTIONBOX ACCOUNT`
  dpa:
    available: null
    text: will provide additional data-processing terms only by written agreement
    url: null
  purposes:
  - purpose: provide, authenticate, maintain and improve the Service
    text: We use information only to provide, authenticate, maintain, secure, and improve the hosted Service
  - purpose: product analytics
    text: measure onboarding, documentation usefulness, product adoption, reliability, and acquisition so we can make product decisions
  - purpose: deliver signed callbacks
    text: deliver and retry signed callbacks and native notification hints
  retention:
  - period: null
    scope: account, Source, Action, event, webhook, device, and security records
    text: We retain account, Source, Action, event, webhook, device, and security records while needed to provide the Service, maintain an audit trail, resolve disputes, prevent abuse, comply with legal obligations, and recover from failures.
  - period: null
    scope: mobile local cache
    text: Signing out or completing account deletion clears the local session, account email, registered device identifier, and cached Action list.
  rights:
  - right: access
    text: you may have rights to request access to, correction of, deletion of, or information about personal data associated with your account
  - right: export
    text: Authenticated account owners can export their current account data from Settings or with `GET /v1/account/export`.
  - right: withdraw analytics consent
    text: use the Privacy choices link to change or withdraw your consent at any time
  role:
    text: Actionbox acts as a Data Controller for account, billing, and direct website visitor data. For Customer Content submitted via the API or dashboard (such as Action titles, descriptions, and callback payloads), the customer acts as the Data Controller and Actionbox acts as a Data Processor under applicable privacy laws.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your personal information or Customer Content
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Actionbox and its providers may process information in countries other than where you live.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: actionbox-cloud
provenance_date: '2026-11-09'
provider_name: actionbox-cloud
provider_slug: actionbox-cloud
slug: actionbox-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: actionbox-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://actionbox.cloud/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: actionbox-cloud\naid: actionbox-cloud\nurl: https://actionbox.cloud/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Actionbox acts as a Data Controller for account, billing, and direct website visitor data. For Customer\n    Content submitted via the API or dashboard (such as Action titles, descriptions, and callback payloads), the\n    customer acts as the Data Controller and Actionbox acts as a Data Processor under applicable privacy laws.\ndata_categories:\n- category: identifying\n  text: your email address, display name, Google or Apple account subject identifier, account creation time,\
  \ and\n    sign-in or account-linking events\n- category: device\n  text: device name, platform and operating-system family, app version, an Actionbox-generated device registration\n    identifier\n- category: behavioral\n  text: page and route views, referrer host/path, UTM and campaign fields, coarse interaction events\n- category: financial\n  text: transaction identifiers, subscription status, billing country or postal code, currency, and invoice history\n    provided by our Merchant of Record\n- category: location\n  text: coarse country or region derived by the provider\n- category: communication\n  text: When you voluntarily send product feedback from the signed-in dashboard, Actionbox stores the category,\n    message, a generalized page route, limited display context, your account, and workspace\npurposes:\n- purpose: provide, authenticate, maintain and improve the Service\n  text: We use information only to provide, authenticate, maintain, secure, and improve the hosted Service\n\
  - purpose: product analytics\n  text: measure onboarding, documentation usefulness, product adoption, reliability, and acquisition so we can make\n    product decisions\n- purpose: deliver signed callbacks\n  text: deliver and retry signed callbacks and native notification hints\nretention:\n- scope: account, Source, Action, event, webhook, device, and security records\n  period: null\n  text: We retain account, Source, Action, event, webhook, device, and security records while needed to provide\n    the Service, maintain an audit trail, resolve disputes, prevent abuse, comply with legal obligations, and recover\n    from failures.\n- scope: mobile local cache\n  period: null\n  text: Signing out or completing account deletion clears the local session, account email, registered device identifier,\n    and cached Action list.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Actionbox and its providers may process information in countries other than where you live.\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: will provide additional data-processing terms only by written agreement\ndeletion:\n  route: Delete account in the mobile application or dashboard, or DELETE /v1/account with confirmation; or email\n    info@actionbox.cloud with subject 'Account deletion'\n  text: They can permanently delete the account and its tenant-scoped records with Delete account in the mobile\n    application or dashboard, or with `DELETE /v1/account` after sending the exact confirmation `DELETE ACTIONBOX\n    ACCOUNT`\nrights:\n- right: access\n  text: you may have rights to request access to, correction of, deletion of, or information about personal data\n    associated with your account\n- right: export\n  text: Authenticated account owners can export their current account data from Settings or with `GET /v1/account/export`.\n- right: withdraw analytics consent\n  text: use the Privacy choices link to change or withdraw your consent at\
  \ any time\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your personal information or Customer Content\n"
source_yaml_url: https://artifacts.apis.io/actionbox-cloud/privacy/actionbox-cloud-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from actionbox-cloud's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Human-in-the-Loop
- Automation
- Approval
- Cloud
---
