---
api_specs:
- filename: temp-md-accounts-api-openapi.yml
  format: yaml
  label: temp.md Accounts API
  slug: temp-md-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-accounts-api-openapi.yml
- filename: temp-md-agents-api-openapi.yml
  format: yaml
  label: temp.md Agents API
  slug: temp-md-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-agents-api-openapi.yml
- filename: temp-md-applications-api-openapi.yml
  format: yaml
  label: temp.md Applications API
  slug: temp-md-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-applications-api-openapi.yml
- filename: temp-md-comments-api-openapi.yml
  format: yaml
  label: temp.md Comments API
  slug: temp-md-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-comments-api-openapi.yml
- filename: temp-md-health-api-openapi.yml
  format: yaml
  label: temp.md Health API
  slug: temp-md-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-health-api-openapi.yml
- filename: temp-md-lifecycle-api-openapi.yml
  format: yaml
  label: temp.md Lifecycle API
  slug: temp-md-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-lifecycle-api-openapi.yml
- filename: temp-md-organizations-api-openapi.yml
  format: yaml
  label: temp.md Organizations API
  slug: temp-md-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-organizations-api-openapi.yml
- filename: temp-md-previews-api-openapi.yml
  format: yaml
  label: temp.md Previews API
  slug: temp-md-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-previews-api-openapi.yml
- filename: temp-md-publish-api-openapi.yml
  format: yaml
  label: temp.md Publish API
  slug: temp-md-publish-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-publish-api-openapi.yml
- filename: temp-md-publish-grants-api-openapi.yml
  format: yaml
  label: temp.md Publish Grants API
  slug: temp-md-publish-grants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-publish-grants-api-openapi.yml
- filename: temp-md-publish-sessions-api-openapi.yml
  format: yaml
  label: temp.md Publish Sessions API
  slug: temp-md-publish-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-publish-sessions-api-openapi.yml
- filename: temp-md-review-requests-api-openapi.yml
  format: yaml
  label: temp.md Review Requests API
  slug: temp-md-review-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-review-requests-api-openapi.yml
- filename: temp-md-safety-api-openapi.yml
  format: yaml
  label: temp.md Safety API
  slug: temp-md-safety-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-safety-api-openapi.yml
- filename: temp-md-usage-api-openapi.yml
  format: yaml
  label: temp.md Usage API
  slug: temp-md-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/temp-md/openapi/temp-md-usage-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: contact
    text: If you create an account to claim a link, we collect your email address and a hashed password.
  - category: identifying
    text: We also store your IP address for abuse prevention.
  - category: other
    text: When you publish a file to temp.md, we store the file content and associated metadata (content type, size, expiry date).
  deletion:
    route: owner deletes file or closes account
    text: Claimed files are retained until the owner deletes them or closes their account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: serve published files
    text: File content is stored solely to serve it at the published URL.
  - purpose: authentication
    text: Email addresses are used only for authentication.
  retention:
  - period: 7 days
    scope: unclaimed files
    text: Unclaimed files are automatically deleted 7 days after the last publish or update, plus a 7-day grace period.
  - period: null
    scope: claimed files
    text: Claimed files are retained until the owner deletes them or closes their account.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your data with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: temp.md
provenance_date: '2026-11-10'
provider_name: temp.md
provider_slug: temp-md
slug: temp-md-privacy-policy
source_date: '2026-11-10'
source_filename: temp-md-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://temp.md/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: temp.md\naid: temp-md\nurl: https://temp.md/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: If you create an account to claim a link, we collect your email address and a hashed password.\n- category: identifying\n  text: We also store your IP address for abuse prevention.\n- category: other\n  text: When you publish a file to temp.md, we store the file content and associated metadata (content type, size,\n    expiry date).\npurposes:\n- purpose: serve published files\n  text: File content is stored solely to serve it at the published\
  \ URL.\n- purpose: authentication\n  text: Email addresses are used only for authentication.\nretention:\n- scope: unclaimed files\n  period: 7 days\n  text: Unclaimed files are automatically deleted 7 days after the last publish or update, plus a 7-day grace period.\n- scope: claimed files\n  period: null\n  text: Claimed files are retained until the owner deletes them or closes their account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: owner deletes file or closes account\n  text: Claimed files are retained until the owner deletes them or closes their account.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/temp-md/privacy/temp-md-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 9 quoted statements, read from temp.md's own page on 2026-11-10.
synthetic: false
tags:
- Web Publishing
- Static Hosting
- AI Agents
- MCP
- A2A
- Developer Tools
- Preview Infrastructure
- File Sharing
- Agent-Native
- Company
---
