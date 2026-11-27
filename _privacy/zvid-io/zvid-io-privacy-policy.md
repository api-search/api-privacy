---
api_specs:
- filename: zvid-io-api-keys-api-openapi.yml
  format: yaml
  label: zvid-io API Keys API
  slug: zvid-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-api-keys-api-openapi.yml
- filename: zvid-io-authoring-api-openapi.yml
  format: yaml
  label: zvid-io Authoring API
  slug: zvid-io-authoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-authoring-api-openapi.yml
- filename: zvid-io-bulk-render-api-openapi.yml
  format: yaml
  label: zvid-io Bulk Render API
  slug: zvid-io-bulk-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-bulk-render-api-openapi.yml
- filename: zvid-io-credits-api-openapi.yml
  format: yaml
  label: zvid-io Credits API
  slug: zvid-io-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-credits-api-openapi.yml
- filename: zvid-io-library-api-openapi.yml
  format: yaml
  label: zvid-io Library API
  slug: zvid-io-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-library-api-openapi.yml
- filename: zvid-io-projects-api-openapi.yml
  format: yaml
  label: zvid-io Projects API
  slug: zvid-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-projects-api-openapi.yml
- filename: zvid-io-render-api-openapi.yml
  format: yaml
  label: zvid-io Render API
  slug: zvid-io-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-render-api-openapi.yml
- filename: zvid-io-stock-api-openapi.yml
  format: yaml
  label: zvid-io Stock API
  slug: zvid-io-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-stock-api-openapi.yml
- filename: zvid-io-templates-api-openapi.yml
  format: yaml
  label: zvid-io Templates API
  slug: zvid-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-templates-api-openapi.yml
- filename: zvid-io-uploads-api-openapi.yml
  format: yaml
  label: zvid-io Uploads API
  slug: zvid-io-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-uploads-api-openapi.yml
- filename: zvid-io-user-api-openapi.yml
  format: yaml
  label: zvid-io User API
  slug: zvid-io-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-user-api-openapi.yml
- filename: zvid-io-webhooks-api-openapi.yml
  format: yaml
  label: zvid-io Webhooks API
  slug: zvid-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-webhooks-api-openapi.yml
- filename: zvid-io-zvid-api-api-openapi.yml
  format: yaml
  label: zvid-io Zvid API
  slug: zvid-io-zvid-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zvid-io/openapi/zvid-io-zvid-api-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name and last name
  - category: contact
    text: Email address
  - category: identifying
    text: Password (stored in a hashed form)
  - category: device
    text: IP address
  - category: device
    text: Browser type and settings
  - category: other
    text: API keys and associated usage (e.g., number of calls, rate-limit status)
  deletion:
    route: dashboard or API
    text: Delete projects, jobs, or rendered outputs via the dashboard or API (where supported)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: Render videos based on your JSON project payloads
  - purpose: Security and abuse prevention
    text: Detect and prevent fraud, abuse, or security incidents
  - purpose: Marketing
    text: Send product updates or marketing messages
  retention:
  - period: for a limited period
    scope: Logs and API usage
    text: Logs and API usage kept for a limited period for security and diagnostics.
  - period: after the render completes
    scope: Downloaded media used for rendering
    text: Downloaded media used for rendering is removed from our systems after the render completes.
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you.
  - right: Correction
    text: Request correction of inaccurate or incomplete data.
  - right: Deletion
    text: Request deletion of your personal data where legally permitted.
  - right: Restriction / Objection
    text: Object to or request restriction of certain processing.
  - right: Portability
    text: Request a copy of your data in a machine-readable format.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When required, we implement appropriate safeguards (such as standard contractual clauses or equivalent mechanisms) to protect your information during such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: zvid-io
provenance_date: '2026-11-10'
provider_name: zvid-io
provider_slug: zvid-io
slug: zvid-io-privacy-policy
source_date: '2026-11-10'
source_filename: zvid-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zvid.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: zvid-io\naid: zvid-io\nurl: https://zvid.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: First name and last name\n- category: contact\n  text: Email address\n- category: identifying\n  text: Password (stored in a hashed form)\n- category: device\n  text: IP address\n- category: device\n  text: Browser type and settings\n- category: other\n  text: API keys and associated usage (e.g., number of calls, rate-limit status)\npurposes:\n- purpose: Provide the Service\n  text: Render videos based on your JSON project payloads\n- purpose:\
  \ Security and abuse prevention\n  text: Detect and prevent fraud, abuse, or security incidents\n- purpose: Marketing\n  text: Send product updates or marketing messages\nretention:\n- scope: Logs and API usage\n  period: for a limited period\n  text: Logs and API usage kept for a limited period for security and diagnostics.\n- scope: Downloaded media used for rendering\n  period: after the render completes\n  text: Downloaded media used for rendering is removed from our systems after the render completes.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: When required, we implement appropriate safeguards (such as standard contractual clauses or equivalent mechanisms)\n    to protect your information during such transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard or API\n  text: Delete projects, jobs, or rendered outputs via the dashboard or API (where supported)\nrights:\n- right: Access\n  text:\
  \ Request a copy of the personal data we hold about you.\n- right: Correction\n  text: Request correction of inaccurate or incomplete data.\n- right: Deletion\n  text: Request deletion of your personal data where legally permitted.\n- right: Restriction / Objection\n  text: Object to or request restriction of certain processing.\n- right: Portability\n  text: Request a copy of your data in a machine-readable format.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zvid-io/privacy/zvid-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from zvid-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Automation
- Media
---
