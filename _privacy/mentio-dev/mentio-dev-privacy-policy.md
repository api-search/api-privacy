---
api_specs:
- filename: mentio-dev-alerts-api-openapi.yml
  format: yaml
  label: mentio-dev Alerts API
  slug: mentio-dev-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-alerts-api-openapi.yml
- filename: mentio-dev-analytics-api-openapi.yml
  format: yaml
  label: mentio-dev Analytics API
  slug: mentio-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-analytics-api-openapi.yml
- filename: mentio-dev-api-keys-api-openapi.yml
  format: yaml
  label: mentio-dev API keys API
  slug: mentio-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-api-keys-api-openapi.yml
- filename: mentio-dev-attention-api-openapi.yml
  format: yaml
  label: mentio-dev Attention API
  slug: mentio-dev-attention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-attention-api-openapi.yml
- filename: mentio-dev-auth-api-openapi.yml
  format: yaml
  label: mentio-dev Auth API
  slug: mentio-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-auth-api-openapi.yml
- filename: mentio-dev-billing-api-openapi.yml
  format: yaml
  label: mentio-dev Billing API
  slug: mentio-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-billing-api-openapi.yml
- filename: mentio-dev-company-api-openapi.yml
  format: yaml
  label: mentio-dev Company API
  slug: mentio-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-company-api-openapi.yml
- filename: mentio-dev-feeds-api-openapi.yml
  format: yaml
  label: mentio-dev Feeds API
  slug: mentio-dev-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-feeds-api-openapi.yml
- filename: mentio-dev-filters-api-openapi.yml
  format: yaml
  label: mentio-dev Filters API
  slug: mentio-dev-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-filters-api-openapi.yml
- filename: mentio-dev-groups-api-openapi.yml
  format: yaml
  label: mentio-dev Groups API
  slug: mentio-dev-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-groups-api-openapi.yml
- filename: mentio-dev-keywords-api-openapi.yml
  format: yaml
  label: mentio-dev Keywords API
  slug: mentio-dev-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-keywords-api-openapi.yml
- filename: mentio-dev-members-api-openapi.yml
  format: yaml
  label: mentio-dev Members API
  slug: mentio-dev-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-members-api-openapi.yml
- filename: mentio-dev-mentions-api-openapi.yml
  format: yaml
  label: mentio-dev Mentions API
  slug: mentio-dev-mentions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-mentions-api-openapi.yml
- filename: mentio-dev-people-api-openapi.yml
  format: yaml
  label: mentio-dev People API
  slug: mentio-dev-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-people-api-openapi.yml
- filename: mentio-dev-segments-api-openapi.yml
  format: yaml
  label: mentio-dev Segments API
  slug: mentio-dev-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-segments-api-openapi.yml
- filename: mentio-dev-system-api-openapi.yml
  format: yaml
  label: mentio-dev System API
  slug: mentio-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-system-api-openapi.yml
- filename: mentio-dev-usage-api-openapi.yml
  format: yaml
  label: mentio-dev Usage API
  slug: mentio-dev-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-usage-api-openapi.yml
- filename: mentio-dev-views-api-openapi.yml
  format: yaml
  label: mentio-dev Views API
  slug: mentio-dev-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mentio-dev/openapi/mentio-dev-views-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, and a password (stored only as a salted hash) when you sign up
  - category: financial
    text: Keyword-days and matched mention counts, which determine the daily deductions from your prepaid balance, and the ledger of top-ups and deductions behind it.
  - category: other
    text: Standard operational logs (timestamps, request metadata, errors)
  - category: device
    text: PostHog, our product analytics provider, stores an identifier in a cookie and in your browser's local storage
  - category: identifying
    text: the author's public name, handle, avatar, and follower, following and post counts as the platform shows them
  - category: contact
    text: an email address only where the author published it on their public profile
  - category: behavioral
    text: the engagement counts (likes, reposts, replies) the platform reported when we read the post
  - category: other
    text: 'a classification our AI derives from the post: how relevant it is to the customer, its sentiment, and topic tags such as a question or a bug report'
  deletion:
    route: removal page or email to support@mentio.dev
    text: You can object to this processing and ask us to erase your data at any time through our removal page or by writing to support@mentio.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision and billing
    text: To provide and improve the service, deliver the notifications you configure, bill usage, secure the platform, and communicate with you about your account.
  - purpose: monitoring public conversations
    text: ours and our customers' interest in monitoring public conversations about their products, brands and markets
  - purpose: ad attribution measurement
    text: We use it to measure which ads lead to customers
  retention:
  - period: 30 days
    scope: unmatched stored posts
    text: A stored post that no customer keyword matches any more is deleted after 30 days
  - period: 90 days
    scope: alert records
    text: records of alerts delivered about a post after 90 days
  - period: within 30 days
    scope: YouTube API Services data
    text: refresh or delete that data within 30 days of retrieving it
  - period: as long as law requires
    scope: billing records
    text: Billing records are kept as long as law requires.
  rights:
  - right: access, correction, deletion, portability, restriction, objection
    text: you can request access, correction, deletion, portability, or restriction of your personal data, and object to processing, by emailing support@mentio.dev
  - right: lodge complaint
    text: You can also lodge a complaint with your local supervisory authority.
  role:
    text: For that data the customer is the controller and Mentio processes it on their behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not run ads.
  subprocessors:
    text: 'Cloudflare : hosting, storage, and AI inference for the entire service.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mentio-dev
provenance_date: '2026-11-10'
provider_name: mentio-dev
provider_slug: mentio-dev
slug: mentio-dev-privacy-policy
source_date: '2026-11-10'
source_filename: mentio-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mentio.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mentio-dev\naid: mentio-dev\nurl: https://mentio.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For that data the customer is the controller and Mentio processes it on their behalf.\ndata_categories:\n- category: identifying\n  text: Your name, email address, and a password (stored only as a salted hash) when you sign up\n- category: financial\n  text: Keyword-days and matched mention counts, which determine the daily deductions from your prepaid balance,\n    and the ledger of top-ups and deductions behind it.\n- category: other\n  text: Standard operational logs (timestamps, request\
  \ metadata, errors)\n- category: device\n  text: PostHog, our product analytics provider, stores an identifier in a cookie and in your browser's local storage\n- category: identifying\n  text: the author's public name, handle, avatar, and follower, following and post counts as the platform shows\n    them\n- category: contact\n  text: an email address only where the author published it on their public profile\n- category: behavioral\n  text: the engagement counts (likes, reposts, replies) the platform reported when we read the post\n- category: other\n  text: 'a classification our AI derives from the post: how relevant it is to the customer, its sentiment, and topic\n    tags such as a question or a bug report'\npurposes:\n- purpose: service provision and billing\n  text: To provide and improve the service, deliver the notifications you configure, bill usage, secure the platform,\n    and communicate with you about your account.\n- purpose: monitoring public conversations\n  text: ours\
  \ and our customers' interest in monitoring public conversations about their products, brands and markets\n- purpose: ad attribution measurement\n  text: We use it to measure which ads lead to customers\nretention:\n- scope: unmatched stored posts\n  period: 30 days\n  text: A stored post that no customer keyword matches any more is deleted after 30 days\n- scope: alert records\n  period: 90 days\n  text: records of alerts delivered about a post after 90 days\n- scope: YouTube API Services data\n  period: within 30 days\n  text: refresh or delete that data within 30 days of retrieving it\n- scope: billing records\n  period: as long as law requires\n  text: Billing records are kept as long as law requires.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Cloudflare : hosting, storage, and AI inference for the entire service.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: removal page or email to support@mentio.dev\n  text: You can object to\
  \ this processing and ask us to erase your data at any time through our removal page or\n    by writing to support@mentio.dev .\nrights:\n- right: access, correction, deletion, portability, restriction, objection\n  text: you can request access, correction, deletion, portability, or restriction of your personal data, and object\n    to processing, by emailing support@mentio.dev\n- right: lodge complaint\n  text: You can also lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not run ads.\n"
source_yaml_url: https://artifacts.apis.io/mentio-dev/privacy/mentio-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from mentio-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Listening
- AI Integration
- SDK
- Real-Time Monitoring
---
