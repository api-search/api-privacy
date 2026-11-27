---
api_specs:
- filename: unplain-io-discovery-api-openapi.yml
  format: yaml
  label: unplain-io Discovery API
  slug: unplain-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unplain-io/openapi/unplain-io-discovery-api-openapi.yml
- filename: unplain-io-feature-requests-api-openapi.yml
  format: yaml
  label: unplain-io Feature requests API
  slug: unplain-io-feature-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unplain-io/openapi/unplain-io-feature-requests-api-openapi.yml
- filename: unplain-io-mcp-api-openapi.yml
  format: yaml
  label: unplain-io MCP API
  slug: unplain-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unplain-io/openapi/unplain-io-mcp-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: your name (if you provide one) and the details needed to create and secure your account.'
  - category: contact
    text: 'Email address: used to sign you in, send important service messages, and respond to support requests.'
  - category: financial
    text: 'Payment information: handled by Stripe. We receive limited billing details (such as your plan and payment status)'
  - category: behavioral
    text: 'Analytics and usage data: basic information about how the service is used (for example, pages visited and features used'
  - category: communication
    text: 'Documents: the files you upload, the text you paste, or the content an AI assistant sends on your behalf through the Unplain MCP'
  deletion:
    route: Email info@unplain.io to request account deletion
    text: you can ask us to delete your account and associated data at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: Provide the service and generate your ebooks and PDFs.
  - purpose: Process payments
    text: Process payments and manage your plan or Creator Pack.
  - purpose: Improve Unplain
    text: Improve Unplain, fix bugs, and understand which features help.
  - purpose: Communicate updates
    text: Communicate important updates, such as security or billing notices.
  retention:
  - period: null
    scope: Account data
    text: We keep your information for as long as your account is active or as needed to provide the service.
  - period: null
    scope: Leads
    text: Leads and their reading activity are kept for as long as the agency keeps the guide and its account.
  rights:
  - right: Access and copy
    text: You can also contact us to request a copy of your data
  - right: Correction
    text: to correct it
  - right: Deletion
    text: or to delete your account and the data associated with it
  role:
    text: 'Unplain is the processor: we store and handle that data for the agency, on its instructions. Unplain is the controller for abuse reports (see Reporting a page ) and for Unplain account data, as described in the rest of this policy.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we don't use the contents of your uploaded documents to train AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: unplain-io
provenance_date: '2026-11-10'
provider_name: unplain-io
provider_slug: unplain-io
slug: unplain-io-privacy-policy
source_date: '2026-11-10'
source_filename: unplain-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://unplain.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: unplain-io\naid: unplain-io\nurl: https://unplain.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Unplain is the processor: we store and handle that data for the agency, on its instructions. Unplain is\n    the controller for abuse reports (see Reporting a page ) and for Unplain account data, as described in the rest\n    of this policy.'\ndata_categories:\n- category: identifying\n  text: 'Account information: your name (if you provide one) and the details needed to create and secure your account.'\n- category: contact\n  text: 'Email address: used to sign you in, send important service\
  \ messages, and respond to support requests.'\n- category: financial\n  text: 'Payment information: handled by Stripe. We receive limited billing details (such as your plan and payment\n    status)'\n- category: behavioral\n  text: 'Analytics and usage data: basic information about how the service is used (for example, pages visited and\n    features used'\n- category: communication\n  text: 'Documents: the files you upload, the text you paste, or the content an AI assistant sends on your behalf\n    through the Unplain MCP'\npurposes:\n- purpose: Provide the service\n  text: Provide the service and generate your ebooks and PDFs.\n- purpose: Process payments\n  text: Process payments and manage your plan or Creator Pack.\n- purpose: Improve Unplain\n  text: Improve Unplain, fix bugs, and understand which features help.\n- purpose: Communicate updates\n  text: Communicate important updates, such as security or billing notices.\nretention:\n- scope: Account data\n  period: null\n  text:\
  \ We keep your information for as long as your account is active or as needed to provide the service.\n- scope: Leads\n  period: null\n  text: Leads and their reading activity are kept for as long as the agency keeps the guide and its account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email info@unplain.io to request account deletion\n  text: you can ask us to delete your account and associated data at any time\nrights:\n- right: Access and copy\n  text: You can also contact us to request a copy of your data\n- right: Correction\n  text: to correct it\n- right: Deletion\n  text: or to delete your account and the data associated with it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we don't use the contents of your uploaded documents to train\n    AI models.\n"
source_yaml_url: https://artifacts.apis.io/unplain-io/privacy/unplain-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from unplain-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Artificial Intelligence
- Marketing
- Software-as-a-Service
---
