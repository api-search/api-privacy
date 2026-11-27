---
api_specs:
- filename: affset-com-openapi-generated.yml
  format: yaml
  label: Affset API
  slug: affset-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affset-com/openapi/_ae-authored/affset-com-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: name and email when you submit the contact form or request access to the Service
  - category: device
    text: device type, operating system, and browser (parsed from the user-agent string)
  - category: location
    text: a country derived from the request (via Cloudflare's edge network, which also processes the underlying IP address to route and secure the request)
  - category: behavioral
    text: any click-identifier parameters the tenant's tracking link carries
  - category: other
    text: standard operational data such as API request metadata, used for security, rate limiting, and diagnosing issues
  deletion:
    route: dashboard sign-in or support email
    text: you can access, update, export, or request deletion of your account data by signing in to the dashboard or contacting support@affset.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: ad serving, targeting, tracking, postbacks
    text: To operate ad serving, targeting, tracking, and postback delivery for our tenants
  - purpose: billing and notices
    text: To process billing and send account, security, and service notices
  - purpose: fraud and security
    text: To detect and prevent fraud, abuse, and security incidents
  retention:
  - period: null
    scope: account and billing data
    text: Account and billing data is retained for as long as the Account is active
  - period: null
    scope: ad-serving event data
    text: retention windows are published on our pricing page and vary by plan tier
  rights:
  - right: access, update, export, deletion
    text: you can access, update, export, or request deletion of your account data
  - right: object or restrict processing
    text: including the right to object to or restrict certain processing
  role:
    text: For account, billing, and dashboard data, Affset is the data controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data
  subprocessors:
    text: Cloudflare — hosting, CDN, DNS, and edge network for the entire Service
    url: null
  transfers:
  - mechanism: other
    text: we rely on appropriate safeguards (such as standard contractual clauses) for cross-border transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Affset
provenance_date: '2026-11-09'
provider_name: Affset
provider_slug: affset-com
slug: affset-com-privacy-policy
source_date: '2026-11-09'
source_filename: affset-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://affset.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Affset\naid: affset-com\nurl: https://affset.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account, billing, and dashboard data, Affset is the data controller.\ndata_categories:\n- category: contact\n  text: name and email when you submit the contact form or request access to the Service\n- category: device\n  text: device type, operating system, and browser (parsed from the user-agent string)\n- category: location\n  text: a country derived from the request (via Cloudflare's edge network, which also processes the underlying IP\n    address to route and secure the request)\n- category:\
  \ behavioral\n  text: any click-identifier parameters the tenant's tracking link carries\n- category: other\n  text: standard operational data such as API request metadata, used for security, rate limiting, and diagnosing\n    issues\npurposes:\n- purpose: ad serving, targeting, tracking, postbacks\n  text: To operate ad serving, targeting, tracking, and postback delivery for our tenants\n- purpose: billing and notices\n  text: To process billing and send account, security, and service notices\n- purpose: fraud and security\n  text: To detect and prevent fraud, abuse, and security incidents\nretention:\n- scope: account and billing data\n  period: null\n  text: Account and billing data is retained for as long as the Account is active\n- scope: ad-serving event data\n  period: null\n  text: retention windows are published on our pricing page and vary by plan tier\nresidency: []\ntransfers:\n- mechanism: other\n  text: we rely on appropriate safeguards (such as standard contractual clauses)\
  \ for cross-border transfers\nsubprocessors:\n  url: null\n  text: Cloudflare — hosting, CDN, DNS, and edge network for the entire Service\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard sign-in or support email\n  text: you can access, update, export, or request deletion of your account data by signing in to the dashboard\n    or contacting support@affset.com\nrights:\n- right: access, update, export, deletion\n  text: you can access, update, export, or request deletion of your account data\n- right: object or restrict processing\n  text: including the right to object to or restrict certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/affset-com/privacy/affset-com-privacy-policy.yml
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
summary_line: 17 quoted statements, read from Affset's own page on 2026-11-09.
synthetic: false
tags:
- Affiliate Tracking
- Media Buying
- CPA Networks
- Postback
- White Label
- Pricing
---
