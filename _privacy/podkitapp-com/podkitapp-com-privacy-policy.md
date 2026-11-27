---
api_specs:
- filename: podkitapp-com-admin-api-openapi.yml
  format: yaml
  label: podkitapp-com Admin API
  slug: podkitapp-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-admin-api-openapi.yml
- filename: podkitapp-com-episodes-api-openapi.yml
  format: yaml
  label: podkitapp-com Episodes API
  slug: podkitapp-com-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-episodes-api-openapi.yml
- filename: podkitapp-com-podcasts-api-openapi.yml
  format: yaml
  label: podkitapp-com Podcasts API
  slug: podkitapp-com-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-podcasts-api-openapi.yml
- filename: podkitapp-com-search-api-openapi.yml
  format: yaml
  label: podkitapp-com Search API
  slug: podkitapp-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-search-api-openapi.yml
- filename: podkitapp-com-usage-api-openapi.yml
  format: yaml
  label: podkitapp-com Usage API
  slug: podkitapp-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-usage-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, collected when you sign up for a free API key or subscribe to a paid plan.
  - category: device
    text: Basic technical logs (IP address, timestamps, error details) for security, abuse prevention, and troubleshooting
  - category: behavioral
    text: Request/usage counts per API key, used to enforce plan quotas and rate limits
  - category: financial
    text: We receive your email, subscription status, and plan tier from Polar to provision your API key
  deletion:
    route: email support@podkitapp.com
    text: To exercise any of these rights, email us at support@podkitapp.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the API
    text: Provide, operate, and maintain the API (authenticate requests, enforce quotas and rate limits, serve responses).
  - purpose: Billing and subscriptions
    text: Process billing and manage subscriptions, via Polar.
  - purpose: Abuse and security monitoring
    text: Monitor for abuse, security issues, and to keep the Service reliable
  - purpose: Support requests
    text: Respond to support requests you send us.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your account (email, hashed key, plan) for as long as your account is active, and for a reasonable period after cancellation for billing records and support purposes.
  - period: shortly after delivery
    scope: Key delivery records
    text: Temporary records used to deliver a newly issued API key are automatically purged shortly after delivery
  - period: rolling monthly basis
    scope: Usage counters
    text: Usage/request counters are retained on a rolling monthly basis for quota enforcement
  rights:
  - right: Access
    text: You can ask us what personal data we hold about you and request a copy of it.
  - right: Deletion
    text: You can ask us to delete your personal data, subject to legal or contractual retention requirements
  - right: Correction
    text: You can ask us to correct inaccurate or incomplete data.
  - right: Portability
    text: You can ask us for your data in a structured, commonly-used, machine-readable format.
  - right: Objection
    text: You can object to certain uses of your data, including for direct marketing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not use your account data for advertising or share it with data brokers.
  subprocessors:
    text: We use the following third-party service providers to operate PodKit.
    url: null
  transfers:
  - mechanism: other
    text: We are in the process of confirming the specific transfer mechanism used by each subprocessor listed in our Subprocessors table and will update this section with specifics.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: podkitapp-com
provenance_date: '2026-11-10'
provider_name: podkitapp-com
provider_slug: podkitapp-com
slug: podkitapp-com-privacy-policy
source_date: '2026-11-10'
source_filename: podkitapp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://podkitapp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: podkitapp-com\naid: podkitapp-com\nurl: https://podkitapp.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, collected when you sign up for a free API key or subscribe to a paid plan.\n- category: device\n  text: Basic technical logs (IP address, timestamps, error details) for security, abuse prevention, and troubleshooting\n- category: behavioral\n  text: Request/usage counts per API key, used to enforce plan quotas and rate limits\n- category: financial\n  text: We receive your email, subscription status, and plan\
  \ tier from Polar to provision your API key\npurposes:\n- purpose: Provide and operate the API\n  text: Provide, operate, and maintain the API (authenticate requests, enforce quotas and rate limits, serve responses).\n- purpose: Billing and subscriptions\n  text: Process billing and manage subscriptions, via Polar.\n- purpose: Abuse and security monitoring\n  text: Monitor for abuse, security issues, and to keep the Service reliable\n- purpose: Support requests\n  text: Respond to support requests you send us.\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your account (email, hashed key, plan) for as long as your account is active, and for a reasonable\n    period after cancellation for billing records and support purposes.\n- scope: Key delivery records\n  period: shortly after delivery\n  text: Temporary records used to deliver a newly issued API key are automatically purged shortly after delivery\n- scope: Usage counters\n  period:\
  \ rolling monthly basis\n  text: Usage/request counters are retained on a rolling monthly basis for quota enforcement\nresidency: []\ntransfers:\n- mechanism: other\n  text: We are in the process of confirming the specific transfer mechanism used by each subprocessor listed in\n    our Subprocessors table and will update this section with specifics.\nsubprocessors:\n  url: null\n  text: We use the following third-party service providers to operate PodKit.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@podkitapp.com\n  text: To exercise any of these rights, email us at support@podkitapp.com\nrights:\n- right: Access\n  text: You can ask us what personal data we hold about you and request a copy of it.\n- right: Deletion\n  text: You can ask us to delete your personal data, subject to legal or contractual retention requirements\n- right: Correction\n  text: You can ask us to correct inaccurate or incomplete data.\n- right: Portability\n  text: You\
  \ can ask us for your data in a structured, commonly-used, machine-readable format.\n- right: Objection\n  text: You can object to certain uses of your data, including for direct marketing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not use your account data for advertising or share it\n    with data brokers.\n"
source_yaml_url: https://artifacts.apis.io/podkitapp-com/privacy/podkitapp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from podkitapp-com's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Data
- Developers
- Audio
---
