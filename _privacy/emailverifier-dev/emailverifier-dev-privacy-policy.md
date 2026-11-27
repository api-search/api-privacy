---
api_specs:
- filename: emailverifier-dev-domains-api-openapi.yml
  format: yaml
  label: emailverifier-dev Domains API
  slug: emailverifier-dev-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailverifier-dev/openapi/emailverifier-dev-domains-api-openapi.yml
- filename: emailverifier-dev-usage-api-openapi.yml
  format: yaml
  label: emailverifier-dev Usage API
  slug: emailverifier-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailverifier-dev/openapi/emailverifier-dev-usage-api-openapi.yml
- filename: emailverifier-dev-verification-api-openapi.yml
  format: yaml
  label: emailverifier-dev Verification API
  slug: emailverifier-dev-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailverifier-dev/openapi/emailverifier-dev-verification-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect account email addresses, password hashes, session records, project details, hashed API keys, usage counts, verification outcomes, timestamps, and technical request data needed to operate and secure the service.
  - category: financial
    text: Stripe processes payment and billing information.
  - category: behavioral
    text: If you allow analytics, Google Analytics measures visits, completed account registrations, and project creation across our website and blog.
  deletion:
    route: dashboard, for finished jobs
    text: you can delete a finished job sooner from the dashboard
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery and security
    text: We use this data to provide verification results, enforce quotas, attribute usage to the correct project, prevent abuse, support customers, improve reliability, and meet legal obligations.
  retention:
  - period: when a job completes or permanently fails
    scope: bulk working records
    text: Bulk working records are removed when a job completes or permanently fails.
  - period: seven days
    scope: completed bulk files
    text: Completed bulk files expire after seven days, and you can delete a finished job sooner from the dashboard.
  - period: up to 24 hours
    scope: Cloudflare edge cache lookups
    text: Cloudflare’s edge cache retains hashed identifiers and lookup metadata for up to 24 hours.
  - period: 90-day lifetime
    scope: Google Analytics cookies
    text: It uses first-party cookies with a 90-day lifetime to recognize a browser.
  rights:
  - right: access, correct, or delete
    text: You may ask to access, correct, or delete personal data, subject to legal and operational retention requirements.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: emailverifier-dev
provenance_date: '2026-11-09'
provider_name: emailverifier-dev
provider_slug: emailverifier-dev
slug: emailverifier-dev-privacy-policy
source_date: '2026-11-09'
source_filename: emailverifier-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://emailverifier.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: emailverifier-dev\naid: emailverifier-dev\nurl: https://emailverifier.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect account email addresses, password hashes, session records, project details, hashed API keys,\n    usage counts, verification outcomes, timestamps, and technical request data needed to operate and secure the\n    service.\n- category: financial\n  text: Stripe processes payment and billing information.\n- category: behavioral\n  text: If you allow analytics, Google Analytics measures visits, completed\
  \ account registrations, and project creation\n    across our website and blog.\npurposes:\n- purpose: service delivery and security\n  text: We use this data to provide verification results, enforce quotas, attribute usage to the correct project,\n    prevent abuse, support customers, improve reliability, and meet legal obligations.\nretention:\n- scope: bulk working records\n  period: when a job completes or permanently fails\n  text: Bulk working records are removed when a job completes or permanently fails.\n- scope: completed bulk files\n  period: seven days\n  text: Completed bulk files expire after seven days, and you can delete a finished job sooner from the dashboard.\n- scope: Cloudflare edge cache lookups\n  period: up to 24 hours\n  text: Cloudflare’s edge cache retains hashed identifiers and lookup metadata for up to 24 hours.\n- scope: Google Analytics cookies\n  period: 90-day lifetime\n  text: It uses first-party cookies with a 90-day lifetime to recognize a browser.\n\
  residency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard, for finished jobs\n  text: you can delete a finished job sooner from the dashboard\nrights:\n- right: access, correct, or delete\n  text: You may ask to access, correct, or delete personal data, subject to legal and operational retention requirements.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/emailverifier-dev/privacy/emailverifier-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 10 quoted statements, read from emailverifier-dev's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Verification
- Software-as-a-Service
- Data Quality
---
