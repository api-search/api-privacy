---
api_specs:
- filename: sudomock-com-account-api-openapi.yml
  format: yaml
  label: sudomock-com Account API
  slug: sudomock-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-account-api-openapi.yml
- filename: sudomock-com-background-removal-api-openapi.yml
  format: yaml
  label: sudomock-com Background removal API
  slug: sudomock-com-background-removal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-background-removal-api-openapi.yml
- filename: sudomock-com-fonts-api-openapi.yml
  format: yaml
  label: sudomock-com Fonts API
  slug: sudomock-com-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-fonts-api-openapi.yml
- filename: sudomock-com-jobs-api-openapi.yml
  format: yaml
  label: sudomock-com Jobs API
  slug: sudomock-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-jobs-api-openapi.yml
- filename: sudomock-com-photo-mockups-api-openapi.yml
  format: yaml
  label: sudomock-com Photo mockups API
  slug: sudomock-com-photo-mockups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-photo-mockups-api-openapi.yml
- filename: sudomock-com-psd-mockups-api-openapi.yml
  format: yaml
  label: sudomock-com PSD mockups API
  slug: sudomock-com-psd-mockups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-psd-mockups-api-openapi.yml
- filename: sudomock-com-studio-api-openapi.yml
  format: yaml
  label: sudomock-com Studio API
  slug: sudomock-com-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-studio-api-openapi.yml
- filename: sudomock-com-video-mockups-api-openapi.yml
  format: yaml
  label: sudomock-com Video mockups API
  slug: sudomock-com-video-mockups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-video-mockups-api-openapi.yml
- filename: sudomock-com-webhook-deliveries-api-openapi.yml
  format: yaml
  label: sudomock-com Webhook deliveries API
  slug: sudomock-com-webhook-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-webhook-deliveries-api-openapi.yml
- filename: sudomock-com-webhook-endpoints-api-openapi.yml
  format: yaml
  label: sudomock-com Webhook endpoints API
  slug: sudomock-com-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sudomock-com/openapi/sudomock-com-webhook-endpoints-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Account information (email address)
  - category: identifying
    text: If you sign in with Apple, Google or GitHub, we receive your name and email address from that provider
  - category: financial
    text: Payment information (processed securely through Stripe - we never store card details)
  - category: device
    text: Device information and IP addresses (for security and fraud prevention)
  - category: behavioral
    text: Usage analytics and performance metrics
  - category: communication
    text: Communication data when you contact support
  deletion:
    route: Request deletion
    text: You can ask us to delete any uploaded file at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve rendering service
    text: Provide, maintain, and improve our rendering service
  - purpose: Process transactions
    text: Process transactions and manage subscriptions
  - purpose: Fraud and technical issues
    text: Detect, prevent, and address technical issues and fraud
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: United States
    text: Our servers are located in the United States.
  - region: EU (Frankfurt, Germany)
    text: Event data is stored in the EU (Frankfurt, Germany)
  retention:
  - period: 7 days
    scope: Image renders
    text: Image renders are deleted 7 days after they are produced.
  - period: null
    scope: Account data
    text: Kept for as long as your account exists.
  - period: 30 days
    scope: Usage logs
    text: Request logs are kept for 30 days.
  - period: at least 7 years
    scope: Billing records
    text: Kept for at least 7 years, as tax and accounting law requires
  - period: null
    scope: Video outputs
    text: Not deleted on a schedule, and no automatic time limit applies.
  rights:
  - right: Access
    text: 'Access : Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification : Request correction of inaccurate data'
  - right: Erasure
    text: 'Erasure : Request deletion of your personal data'
  - right: Portability
    text: 'Portability : Request transfer of your data in a structured format'
  - right: Objection
    text: 'Objection : Object to processing of your data'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use the following third-party services that may process your information:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: sudomock-com
provenance_date: '2026-11-10'
provider_name: sudomock-com
provider_slug: sudomock-com
slug: sudomock-com-privacy-policy
source_date: '2026-11-10'
source_filename: sudomock-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sudomock.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sudomock-com\naid: sudomock-com\nurl: https://sudomock.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Account information (email address)\n- category: identifying\n  text: If you sign in with Apple, Google or GitHub, we receive your name and email address from that provider\n- category: financial\n  text: Payment information (processed securely through Stripe - we never store card details)\n- category: device\n  text: Device information and IP addresses (for security and fraud prevention)\n- category: behavioral\n  text:\
  \ Usage analytics and performance metrics\n- category: communication\n  text: Communication data when you contact support\npurposes:\n- purpose: Provide and improve rendering service\n  text: Provide, maintain, and improve our rendering service\n- purpose: Process transactions\n  text: Process transactions and manage subscriptions\n- purpose: Fraud and technical issues\n  text: Detect, prevent, and address technical issues and fraud\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Image renders\n  period: 7 days\n  text: Image renders are deleted 7 days after they are produced.\n- scope: Account data\n  period: null\n  text: Kept for as long as your account exists.\n- scope: Usage logs\n  period: 30 days\n  text: Request logs are kept for 30 days.\n- scope: Billing records\n  period: at least 7 years\n  text: Kept for at least 7 years, as tax and accounting law requires\n- scope: Video outputs\n  period: null\n  text: Not deleted on a schedule,\
  \ and no automatic time limit applies.\nresidency:\n- region: United States\n  text: Our servers are located in the United States.\n- region: EU (Frankfurt, Germany)\n  text: Event data is stored in the EU (Frankfurt, Germany)\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use the following third-party services that may process your information:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion\n  text: You can ask us to delete any uploaded file at any time.\nrights:\n- right: Access\n  text: 'Access : Request a copy of your personal data'\n- right: Rectification\n  text: 'Rectification : Request correction of inaccurate data'\n- right: Erasure\n  text: 'Erasure : Request deletion of your personal data'\n- right: Portability\n  text: 'Portability : Request transfer of your data in a structured format'\n- right: Objection\n  text: 'Objection : Object to processing of your data'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sudomock-com/privacy/sudomock-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 24 quoted statements, read from sudomock-com's own page on 2026-11-10.
synthetic: false
tags:
- Mockup
- PSD
- E-Commerce
- Automation
---
