---
api_specs:
- filename: openrelay-account-api-openapi.yml
  format: yaml
  label: OpenRelay Account API
  slug: openrelay-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-account-api-openapi.yml
- filename: openrelay-api-keys-api-openapi.yml
  format: yaml
  label: OpenRelay API Keys API
  slug: openrelay-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-api-keys-api-openapi.yml
- filename: openrelay-batches-api-openapi.yml
  format: yaml
  label: OpenRelay Batches API
  slug: openrelay-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-batches-api-openapi.yml
- filename: openrelay-billing-api-openapi.yml
  format: yaml
  label: OpenRelay Billing API
  slug: openrelay-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-billing-api-openapi.yml
- filename: openrelay-catalog-api-openapi.yml
  format: yaml
  label: OpenRelay Catalog API
  slug: openrelay-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-catalog-api-openapi.yml
- filename: openrelay-clusters-api-openapi.yml
  format: yaml
  label: OpenRelay Clusters API
  slug: openrelay-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-clusters-api-openapi.yml
- filename: openrelay-files-api-openapi.yml
  format: yaml
  label: OpenRelay Files API
  slug: openrelay-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-files-api-openapi.yml
- filename: openrelay-internal-api-openapi.yml
  format: yaml
  label: OpenRelay Internal API
  slug: openrelay-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-internal-api-openapi.yml
- filename: openrelay-organizations-api-openapi.yml
  format: yaml
  label: OpenRelay Organizations API
  slug: openrelay-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-organizations-api-openapi.yml
- filename: openrelay-provider-api-openapi.yml
  format: yaml
  label: OpenRelay Provider API
  slug: openrelay-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-provider-api-openapi.yml
- filename: openrelay-registry-credentials-api-openapi.yml
  format: yaml
  label: OpenRelay Registry Credentials API
  slug: openrelay-registry-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-registry-credentials-api-openapi.yml
- filename: openrelay-runners-api-openapi.yml
  format: yaml
  label: OpenRelay Runners API
  slug: openrelay-runners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-runners-api-openapi.yml
- filename: openrelay-snapshots-api-openapi.yml
  format: yaml
  label: OpenRelay Snapshots API
  slug: openrelay-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-snapshots-api-openapi.yml
- filename: openrelay-ssh-keys-api-openapi.yml
  format: yaml
  label: OpenRelay SSH Keys API
  slug: openrelay-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-ssh-keys-api-openapi.yml
- filename: openrelay-transfers-api-openapi.yml
  format: yaml
  label: OpenRelay Transfers API
  slug: openrelay-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-transfers-api-openapi.yml
- filename: openrelay-usage-api-openapi.yml
  format: yaml
  label: OpenRelay Usage API
  slug: openrelay-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-usage-api-openapi.yml
- filename: openrelay-webhooks-api-openapi.yml
  format: yaml
  label: OpenRelay Webhooks API
  slug: openrelay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-webhooks-api-openapi.yml
- filename: openrelay-vms-api-openapi.yml
  format: yaml
  label: OpenRelay V Ms API
  slug: openrelay-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrelay/openapi/openrelay-vms-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (email address, name, password)
  - category: financial
    text: Payment information (processed securely by our payment providers)
  - category: location
    text: approximate location derived from IP address
  - category: behavioral
    text: Cookies and similar tracking technologies
  - category: device
    text: Device information (browser type, operating system, IP address)
  - category: communication
    text: Communication data (support tickets, emails, feedback)
  - category: other
    text: Inputs and outputs (the content of your inference API requests and the responses returned, together with related usage metadata)
  deletion:
    route: email privacy@openrelay.inc
    text: To request access to or deletion of your analytics data, or to ask us to exclude your account from session recording, email privacy@openrelay.inc
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve our services
  - purpose: Process transactions
    text: Process transactions and send related information
  - purpose: Fraud prevention
    text: Detect, investigate, and prevent fraudulent or unauthorized activity
  residency:
  - region: United States
    text: PostHog processes this data on our behalf on servers in the United States.
  - region: United States
    text: Fingerprint processes this data on our behalf in the United States.
  retention:
  - period: null
    scope: Personal information
    text: We retain your information for as long as your account is active or as needed to provide you services.
  - period: 30 days
    scope: Fingerprint identification events
    text: Fingerprint retains the underlying identification events for 30 days.
  - period: one year afterward
    scope: Verified device identifier and fraud verdict
    text: We keep the verified device identifier and its fraud verdict for as long as your account is active, and for one year afterward.
  rights:
  - right: Access
    text: Access and receive a copy of your data
  - right: Rectification
    text: Rectify inaccurate or incomplete information
  - right: Deletion
    text: Request deletion of your personal data
  - right: Object or restrict
    text: Object to or restrict processing of your data
  - right: Portability
    text: Data portability
  - right: Withdraw consent
    text: Withdraw consent at any time
  - right: Opt out of website-visitor identification
    text: Opt out of third-party website-visitor identification by visiting app.retention.com/optout
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information that identifies you.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OpenRelay
provenance_date: '2026-11-10'
provider_name: OpenRelay
provider_slug: openrelay
slug: openrelay-privacy-policy
source_date: '2026-11-10'
source_filename: openrelay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openrelay.inc/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OpenRelay\naid: openrelay\nurl: https://openrelay.inc/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (email address, name, password)\n- category: financial\n  text: Payment information (processed securely by our payment providers)\n- category: location\n  text: approximate location derived from IP address\n- category: behavioral\n  text: Cookies and similar tracking technologies\n- category: device\n  text: Device information (browser type, operating system, IP address)\n- category: communication\n  text: Communication\
  \ data (support tickets, emails, feedback)\n- category: other\n  text: Inputs and outputs (the content of your inference API requests and the responses returned, together with\n    related usage metadata)\npurposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve our services\n- purpose: Process transactions\n  text: Process transactions and send related information\n- purpose: Fraud prevention\n  text: Detect, investigate, and prevent fraudulent or unauthorized activity\nretention:\n- scope: Personal information\n  period: null\n  text: We retain your information for as long as your account is active or as needed to provide you services.\n- scope: Fingerprint identification events\n  period: 30 days\n  text: Fingerprint retains the underlying identification events for 30 days.\n- scope: Verified device identifier and fraud verdict\n  period: one year afterward\n  text: We keep the verified device identifier and its fraud verdict for as long as your account\
  \ is active, and\n    for one year afterward.\nresidency:\n- region: United States\n  text: PostHog processes this data on our behalf on servers in the United States.\n- region: United States\n  text: Fingerprint processes this data on our behalf in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@openrelay.inc\n  text: To request access to or deletion of your analytics data, or to ask us to exclude your account from session\n    recording, email privacy@openrelay.inc\nrights:\n- right: Access\n  text: Access and receive a copy of your data\n- right: Rectification\n  text: Rectify inaccurate or incomplete information\n- right: Deletion\n  text: Request deletion of your personal data\n- right: Object or restrict\n  text: Object to or restrict processing of your data\n- right: Portability\n  text: Data portability\n- right: Withdraw consent\n  text: Withdraw consent at any time\n\
  - right: Opt out of website-visitor identification\n  text: Opt out of third-party website-visitor identification by visiting app.retention.com/optout\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information that identifies you.\n"
source_yaml_url: https://artifacts.apis.io/openrelay/privacy/openrelay-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from OpenRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- GPU
- Inference
- Artificial Intelligence
- Machine Learning
- Cloud Compute
- Infrastructure
- OpenAI-Compatible
- GPU Cloud
- LLM
---
