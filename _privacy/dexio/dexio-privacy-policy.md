---
api_specs:
- filename: dexio-dexio-api-api-openapi.yml
  format: yaml
  label: Dexio Dexio API
  slug: dexio-dexio-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexio/openapi/dexio-dexio-api-api-openapi.yml
- filename: dexio-install-api-openapi.yml
  format: yaml
  label: Dexio Install API
  slug: dexio-install-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexio/openapi/dexio-install-api-openapi.yml
- filename: dexio-mcp-api-openapi.yml
  format: yaml
  label: Dexio MCP API
  slug: dexio-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexio/openapi/dexio-mcp-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, your first and last name if you give them or they come from Google or GitHub
  - category: identifying
    text: we receive your account id, name and verified email address from them.
  - category: behavioral
    text: Usage and technical data. When an API key or connected app was last used, when you last signed in, and the IP address and browser details that come with each request.
  - category: location
    text: your approximate location from your IP address
  - category: financial
    text: Card details go to Stripe, not to us.
  deletion:
    route: email
    text: You can also ask us to access, correct, export or delete your personal information, or object to how we use it, by emailing us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the Service
    text: 'To run the Service: sign you in, keep workspaces separate, show your wikis to you and to the agents and apps you connect.'
  - purpose: security
    text: 'To keep it secure: rate limits, abuse prevention and investigating problems.'
  - purpose: account contact
    text: To contact you about your account, security, and changes to the Service or these policies.
  - purpose: legal obligations
    text: To meet legal obligations.
  residency:
  - region: United States
    text: Amazon Web Services hosts the Service and stores its data in the United States.
  retention:
  - period: while your account is open
    scope: account and content
    text: We keep your account and content while your account is open.
  - period: within 30 days
    scope: account data after deletion
    text: When you delete your account we delete its data from the live service within 30 days
  - period: up to 400 days
    scope: server logs
    text: Server logs are kept for up to 400 days.
  rights:
  - right: access, correct, export, delete, object
    text: You can also ask us to access, correct, export or delete your personal information, or object to how we use it, by emailing us.
  - right: non-discrimination
    text: We will not treat you differently for using these rights.
  role:
    text: which is responsible for this information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, do not share it for advertising, and do not use your content to train AI models.
  subprocessors:
    text: Stripe processes payments for paid plans.
    url: null
  transfers:
  - mechanism: other
    text: Information may be processed in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dexio
provenance_date: '2026-11-09'
provider_name: Dexio
provider_slug: dexio
slug: dexio-privacy-policy
source_date: '2026-11-09'
source_filename: dexio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dexio.wiki/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dexio\naid: dexio\nurl: https://dexio.wiki/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: which is responsible for this information.\ndata_categories:\n- category: contact\n  text: Your email address, your first and last name if you give them or they come from Google or GitHub\n- category: identifying\n  text: we receive your account id, name and verified email address from them.\n- category: behavioral\n  text: Usage and technical data. When an API key or connected app was last used, when you last signed in, and the\n    IP address and browser details that come with each request.\n\
  - category: location\n  text: your approximate location from your IP address\n- category: financial\n  text: Card details go to Stripe, not to us.\npurposes:\n- purpose: run the Service\n  text: 'To run the Service: sign you in, keep workspaces separate, show your wikis to you and to the agents and\n    apps you connect.'\n- purpose: security\n  text: 'To keep it secure: rate limits, abuse prevention and investigating problems.'\n- purpose: account contact\n  text: To contact you about your account, security, and changes to the Service or these policies.\n- purpose: legal obligations\n  text: To meet legal obligations.\nretention:\n- scope: account and content\n  period: while your account is open\n  text: We keep your account and content while your account is open.\n- scope: account data after deletion\n  period: within 30 days\n  text: When you delete your account we delete its data from the live service within 30 days\n- scope: server logs\n  period: up to 400 days\n  text: Server logs\
  \ are kept for up to 400 days.\nresidency:\n- region: United States\n  text: Amazon Web Services hosts the Service and stores its data in the United States.\ntransfers:\n- mechanism: other\n  text: Information may be processed in the United States.\nsubprocessors:\n  url: null\n  text: Stripe processes payments for paid plans.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: You can also ask us to access, correct, export or delete your personal information, or object to how we\n    use it, by emailing us.\nrights:\n- right: access, correct, export, delete, object\n  text: You can also ask us to access, correct, export or delete your personal information, or object to how we\n    use it, by emailing us.\n- right: non-discrimination\n  text: We will not treat you differently for using these rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, do not share it for advertising, and do not use your content to train\n\
  \    AI models.\n"
source_yaml_url: https://artifacts.apis.io/dexio/privacy/dexio-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Dexio's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Wiki
- Knowledge Management
- Agent Integration
- Open Source
---
