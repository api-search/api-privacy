---
api_specs:
- filename: joinsandwich-com-auth-api-openapi.yml
  format: yaml
  label: joinsandwich-com Auth API
  slug: joinsandwich-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-auth-api-openapi.yml
- filename: joinsandwich-com-community-api-openapi.yml
  format: yaml
  label: joinsandwich-com Community API
  slug: joinsandwich-com-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-community-api-openapi.yml
- filename: joinsandwich-com-content-api-openapi.yml
  format: yaml
  label: joinsandwich-com Content API
  slug: joinsandwich-com-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-content-api-openapi.yml
- filename: joinsandwich-com-discovery-api-openapi.yml
  format: yaml
  label: joinsandwich-com Discovery API
  slug: joinsandwich-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-discovery-api-openapi.yml
- filename: joinsandwich-com-mcp-api-openapi.yml
  format: yaml
  label: joinsandwich-com MCP API
  slug: joinsandwich-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-mcp-api-openapi.yml
- filename: joinsandwich-com-newsletter-api-openapi.yml
  format: yaml
  label: joinsandwich-com Newsletter API
  slug: joinsandwich-com-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/joinsandwich-com/openapi/joinsandwich-com-newsletter-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we may collect your name, email address, and a password.
  - category: device
    text: pages visited, channels browsed, search queries, device type, browser type, IP address, and referring URL
  - category: behavioral
    text: We automatically collect information about how you interact with the Service
  - category: communication
    text: Any posts, comments, or other content you submit to Sandwich channels is stored on our servers and may be visible to other users.
  deletion:
    route: Account deletion or contact via email
    text: If you delete your account, we will remove your personal data within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Personalization
    text: Personalize your experience and deliver relevant content
  - purpose: Analytics and improvement
    text: Analyze usage to improve features and performance
  - purpose: Fraud and abuse prevention
    text: Detect, prevent, and address fraud, abuse, or technical issues
  residency:
  - region: United States
    text: Your data is stored using Google Cloud Platform (Firebase / Firestore) infrastructure located in the United States.
  retention:
  - period: 30 days
    scope: Account deletion
    text: If you delete your account, we will remove your personal data within 30 days, except where retention is required by law or for legitimate business purposes
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Objection or restriction
    text: Object to or restrict certain processing activities
  - right: Portability
    text: Request data portability
  - right: Withdraw consent
    text: Withdraw consent at any time
  role:
    text: Sandwich ("Sandwich," "we," "us," or "our") is operated by Terahertz Inc., a company registered in the United States.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: joinsandwich-com
provenance_date: '2026-11-09'
provider_name: joinsandwich-com
provider_slug: joinsandwich-com
slug: joinsandwich-com-privacy-policy
source_date: '2026-11-09'
source_filename: joinsandwich-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.joinsandwich.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: joinsandwich-com\naid: joinsandwich-com\nurl: https://www.joinsandwich.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Sandwich (\"Sandwich,\" \"we,\" \"us,\" or \"our\") is operated by Terahertz Inc., a company registered in the United\n    States.\ndata_categories:\n- category: identifying\n  text: When you create an account, we may collect your name, email address, and a password.\n- category: device\n  text: pages visited, channels browsed, search queries, device type, browser type, IP address, and referring URL\n- category: behavioral\n  text: We automatically collect information\
  \ about how you interact with the Service\n- category: communication\n  text: Any posts, comments, or other content you submit to Sandwich channels is stored on our servers and may be\n    visible to other users.\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service\n- purpose: Personalization\n  text: Personalize your experience and deliver relevant content\n- purpose: Analytics and improvement\n  text: Analyze usage to improve features and performance\n- purpose: Fraud and abuse prevention\n  text: Detect, prevent, and address fraud, abuse, or technical issues\nretention:\n- scope: Account deletion\n  period: 30 days\n  text: If you delete your account, we will remove your personal data within 30 days, except where retention is\n    required by law or for legitimate business purposes\nresidency:\n- region: United States\n  text: Your data is stored using Google Cloud Platform (Firebase / Firestore) infrastructure located in the United\n\
  \    States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or contact via email\n  text: If you delete your account, we will remove your personal data within 30 days\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Objection or restriction\n  text: Object to or restrict certain processing activities\n- right: Portability\n  text: Request data portability\n- right: Withdraw consent\n  text: Withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/joinsandwich-com/privacy/joinsandwich-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from joinsandwich-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Directory
- Caregiving
- Technology
---
