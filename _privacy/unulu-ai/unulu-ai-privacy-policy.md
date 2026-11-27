---
api_specs:
- filename: unulu-ai-claims-api-openapi.yml
  format: yaml
  label: unulu-ai Claims API
  slug: unulu-ai-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unulu-ai/openapi/unulu-ai-claims-api-openapi.yml
- filename: unulu-ai-feature-votes-api-openapi.yml
  format: yaml
  label: unulu-ai Feature Votes API
  slug: unulu-ai-feature-votes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unulu-ai/openapi/unulu-ai-feature-votes-api-openapi.yml
- filename: unulu-ai-sites-api-openapi.yml
  format: yaml
  label: unulu-ai Sites API
  slug: unulu-ai-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unulu-ai/openapi/unulu-ai-sites-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you claim a site we additionally collect your email address and chosen handle.
  - category: contact
    text: When you claim a site we additionally collect your email address and chosen handle.
  - category: behavioral
    text: We also collect technical data such as IP addresses (for rate limiting) and error and usage logs.
  - category: other
    text: 'When you create a bio site we store the content you provide: display name, bio text, links, and theme preference.'
  deletion:
    route: contact us by email
    text: Subject to applicable law, you may request access to, correction of, or deletion of your personal data by contacting us at reveal address .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: host and serve bio sites
    text: We use your data to create, host, and serve your bio sites
  - purpose: claims and verification
    text: to process claims and send verification emails
  - purpose: rate limiting and abuse prevention
    text: to enforce rate limits and prevent abuse
  - purpose: error monitoring and service improvement
    text: to monitor errors and improve the service
  retention:
  - period: default 1 hour
    scope: unclaimed sites
    text: Unclaimed sites expire automatically after a short period (default 1 hour).
  - period: until you delete them
    scope: claimed sites
    text: Claimed sites persist until you delete them.
  - period: null
    scope: email addresses
    text: Email addresses are retained only for claimed sites.
  - period: a limited period
    scope: security, access, and error logs
    text: We retain security, access, and error logs for a limited period as necessary to operate the service, prevent abuse, and debug issues.
  rights:
  - right: access
    text: you may request access to, correction of, or deletion of your personal data by contacting us
  - right: correction
    text: you may request access to, correction of, or deletion of your personal data by contacting us
  - right: deletion
    text: you may request access to, correction of, or deletion of your personal data by contacting us
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We currently use Cloudflare (hosting & CDN), AWS (database storage), Postmark (transactional email), Sentry (error tracking), and Axiom (logging).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: unulu-ai
provenance_date: '2026-11-10'
provider_name: unulu-ai
provider_slug: unulu-ai
slug: unulu-ai-privacy-policy
source_date: '2026-11-10'
source_filename: unulu-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://unulu.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: unulu-ai\naid: unulu-ai\nurl: https://unulu.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you claim a site we additionally collect your email address and chosen handle.\n- category: contact\n  text: When you claim a site we additionally collect your email address and chosen handle.\n- category: behavioral\n  text: We also collect technical data such as IP addresses (for rate limiting) and error and usage logs.\n- category: other\n  text: 'When you create a bio site we store the content you provide: display name, bio text,\
  \ links, and theme preference.'\npurposes:\n- purpose: host and serve bio sites\n  text: We use your data to create, host, and serve your bio sites\n- purpose: claims and verification\n  text: to process claims and send verification emails\n- purpose: rate limiting and abuse prevention\n  text: to enforce rate limits and prevent abuse\n- purpose: error monitoring and service improvement\n  text: to monitor errors and improve the service\nretention:\n- scope: unclaimed sites\n  period: default 1 hour\n  text: Unclaimed sites expire automatically after a short period (default 1 hour).\n- scope: claimed sites\n  period: until you delete them\n  text: Claimed sites persist until you delete them.\n- scope: email addresses\n  period: null\n  text: Email addresses are retained only for claimed sites.\n- scope: security, access, and error logs\n  period: a limited period\n  text: We retain security, access, and error logs for a limited period as necessary to operate the service, prevent\n    abuse,\
  \ and debug issues.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We currently use Cloudflare (hosting & CDN), AWS (database storage), Postmark (transactional email), Sentry\n    (error tracking), and Axiom (logging).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us by email\n  text: Subject to applicable law, you may request access to, correction of, or deletion of your personal data by\n    contacting us at reveal address .\nrights:\n- right: access\n  text: you may request access to, correction of, or deletion of your personal data by contacting us\n- right: correction\n  text: you may request access to, correction of, or deletion of your personal data by contacting us\n- right: deletion\n  text: you may request access to, correction of, or deletion of your personal data by contacting us\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unulu-ai/privacy/unulu-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from unulu-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Link-in-bio
- MCP
---
