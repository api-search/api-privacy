---
api_specs:
- filename: averray-com-accounts-api-openapi.yml
  format: yaml
  label: Averray Accounts API
  slug: averray-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-accounts-api-openapi.yml
- filename: averray-com-auth-api-openapi.yml
  format: yaml
  label: Averray Auth API
  slug: averray-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-auth-api-openapi.yml
- filename: averray-com-discovery-api-openapi.yml
  format: yaml
  label: Averray Discovery API
  slug: averray-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-discovery-api-openapi.yml
- filename: averray-com-health-api-openapi.yml
  format: yaml
  label: Averray Health API
  slug: averray-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-health-api-openapi.yml
- filename: averray-com-jobs-api-openapi.yml
  format: yaml
  label: Averray Jobs API
  slug: averray-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-jobs-api-openapi.yml
- filename: averray-com-pool-api-openapi.yml
  format: yaml
  label: Averray Pool API
  slug: averray-com-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-pool-api-openapi.yml
- filename: averray-com-receipts-api-openapi.yml
  format: yaml
  label: Averray Receipts API
  slug: averray-com-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-receipts-api-openapi.yml
- filename: averray-com-schemas-api-openapi.yml
  format: yaml
  label: Averray Schemas API
  slug: averray-com-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-schemas-api-openapi.yml
- filename: averray-com-sessions-api-openapi.yml
  format: yaml
  label: Averray Sessions API
  slug: averray-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-sessions-api-openapi.yml
- filename: averray-com-verify-api-openapi.yml
  format: yaml
  label: Averray Verify API
  slug: averray-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/averray-com/openapi/averray-com-verify-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Wallet addresses, claims, submissions, receipts, badges, and reputation are the product's public record
  - category: device
    text: Our servers record IP addresses and user agents in technical logs for security and abuse prevention
  - category: financial
    text: Payment data The Base wallet address that signs the payment.
  - category: communication
    text: Email. Only if you write to us, or where the platform sends a transactional message
  deletion:
    route: Write to pkuriger@averray.com
    text: Off-chain data we control (logs, database records that are not part of the public record) is deletable on request where the law requires it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating the service securely and preventing abuse
    text: Our servers record IP addresses and user agents in technical logs for security and abuse prevention (rate limiting, incident response).
  - purpose: Performance of the service requested by signing in
    text: 'Legal basis: performance of the service you request by signing in.'
  - purpose: Performance of paid verification runs and billing verifiability
    text: Legal basis Performance of the run you request and pay for, and our legitimate interest in keeping billing and receipts verifiable.
  residency:
  - region: France (EU)
    text: Hosting is with OVH in Lille, France (EU).
  - region: Switzerland (Zurich) and Ireland (eu-west-1) for signing keys
    text: Signing infrastructure uses AWS KMS in eu-central-2 (Zurich) with eu-west-1 replication.
  retention:
  - period: indefinitely
    scope: Run records and receipts
    text: Run records and receipts are kept indefinitely in our live database, so that receipts stay verifiable.
  - period: 10 years
    scope: Payment records
    text: Payment records for 10 years, the Swiss retention period for business records.
  - period: null
    scope: Server logs
    text: Logs are size-capped per service and the oldest entries are deleted automatically when the cap is reached
  rights:
  - right: access
    text: you can request access to, rectification of, or deletion of personal data we control
  - right: rectification
    text: you can request access to, rectification of, or deletion of personal data we control
  - right: deletion
    text: you can request access to, rectification of, or deletion of personal data we control
  - right: complain to data protection authority
    text: you can complain to your data protection authority (the Swiss Federal Data Protection and Information Commissioner (FDPIC) or, for EU residents, your national data protection authority)
  role:
    text: Controller Pascal Kuriger Hauptstrasse 51, 8162 Steinmaur, Switzerland
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Sub-processors: OVH (servers), Amazon Web Services (key management), Resend (transactional email), GitHub (public repository content), Slack (internal operational alerts), Base (Coinbase) (Base RPC for payment reads and transaction broadcast).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Averray
provenance_date: '2026-11-09'
provider_name: Averray
provider_slug: averray-com
slug: averray-com-privacy-policy
source_date: '2026-11-09'
source_filename: averray-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://averray.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Averray\naid: averray-com\nurl: https://averray.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller Pascal Kuriger Hauptstrasse 51, 8162 Steinmaur, Switzerland\ndata_categories:\n- category: identifying\n  text: Wallet addresses, claims, submissions, receipts, badges, and reputation are the product's public record\n- category: device\n  text: Our servers record IP addresses and user agents in technical logs for security and abuse prevention\n- category: financial\n  text: Payment data The Base wallet address that signs the payment.\n- category: communication\n  text: Email.\
  \ Only if you write to us, or where the platform sends a transactional message\npurposes:\n- purpose: Operating the service securely and preventing abuse\n  text: Our servers record IP addresses and user agents in technical logs for security and abuse prevention (rate\n    limiting, incident response).\n- purpose: Performance of the service requested by signing in\n  text: 'Legal basis: performance of the service you request by signing in.'\n- purpose: Performance of paid verification runs and billing verifiability\n  text: Legal basis Performance of the run you request and pay for, and our legitimate interest in keeping billing\n    and receipts verifiable.\nretention:\n- scope: Run records and receipts\n  period: indefinitely\n  text: Run records and receipts are kept indefinitely in our live database, so that receipts stay verifiable.\n- scope: Payment records\n  period: 10 years\n  text: Payment records for 10 years, the Swiss retention period for business records.\n- scope: Server\
  \ logs\n  period: null\n  text: Logs are size-capped per service and the oldest entries are deleted automatically when the cap is reached\nresidency:\n- region: France (EU)\n  text: Hosting is with OVH in Lille, France (EU).\n- region: Switzerland (Zurich) and Ireland (eu-west-1) for signing keys\n  text: Signing infrastructure uses AWS KMS in eu-central-2 (Zurich) with eu-west-1 replication.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Sub-processors: OVH (servers), Amazon Web Services (key management), Resend (transactional email), GitHub\n    (public repository content), Slack (internal operational alerts), Base (Coinbase) (Base RPC for payment reads\n    and transaction broadcast).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to pkuriger@averray.com\n  text: Off-chain data we control (logs, database records that are not part of the public record) is deletable on\n    request where the law requires it.\nrights:\n- right: access\n  text: you\
  \ can request access to, rectification of, or deletion of personal data we control\n- right: rectification\n  text: you can request access to, rectification of, or deletion of personal data we control\n- right: deletion\n  text: you can request access to, rectification of, or deletion of personal data we control\n- right: complain to data protection authority\n  text: you can complain to your data protection authority (the Swiss Federal Data Protection and Information Commissioner\n    (FDPIC) or, for EU residents, your national data protection authority)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/averray-com/privacy/averray-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 19 quoted statements, read from Averray's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Blockchain
- Verification
- Agents
- USDC
---
