---
api_specs:
- filename: viewsmeet-com-agent-api-openapi.yml
  format: yaml
  label: ViewsMeet Agent API
  slug: viewsmeet-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-agent-api-openapi.yml
- filename: viewsmeet-com-agents-api-openapi.yml
  format: yaml
  label: ViewsMeet Agents API
  slug: viewsmeet-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-agents-api-openapi.yml
- filename: viewsmeet-com-assessments-api-openapi.yml
  format: yaml
  label: ViewsMeet Assessments API
  slug: viewsmeet-com-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-assessments-api-openapi.yml
- filename: viewsmeet-com-connections-api-openapi.yml
  format: yaml
  label: ViewsMeet Connections API
  slug: viewsmeet-com-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-connections-api-openapi.yml
- filename: viewsmeet-com-experiments-api-openapi.yml
  format: yaml
  label: ViewsMeet Experiments API
  slug: viewsmeet-com-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-experiments-api-openapi.yml
- filename: viewsmeet-com-mcp-api-openapi.yml
  format: yaml
  label: ViewsMeet MCP API
  slug: viewsmeet-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-mcp-api-openapi.yml
- filename: viewsmeet-com-personality-api-openapi.yml
  format: yaml
  label: ViewsMeet Personality API
  slug: viewsmeet-com-personality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/viewsmeet-com/openapi/viewsmeet-com-personality-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: behavioral
    text: A submission contains the pack ID, version, digest, five self choices, five panel predictions, and whether public contribution was selected.
  - category: device
    text: Each request can contain the Event ID, a random deduplication ID, the stored X Click ID when available, and the request IP address plus user agent
  - category: location
    text: For the public world view, ViewsMeet retains only the two-letter country code supplied by Cloudflare at the edge.
  - category: contact
    text: Cloudflare Email Routing forwards the sender, recipient, subject, message content, and normal email headers to a verified destination mailbox outside the gameplay database.
  deletion:
    route: creator control
    text: Use the creator control to delete a challenge and every relay into it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: X advertising measurement
    text: X can use the resulting site-visit and landing-page activity for campaign attribution, reporting, optimization, website-activity audiences, retargeting, and related audience modeling under X’s own terms and controls.
  - purpose: Operational security
    text: The Cloudflare edge can process IP address, user agent, route, response status, approximate region, timing, rate-limit, abuse, and security signals needed to deliver and protect the service.
  residency:
  - region: edge country code
    text: For the public world view, ViewsMeet retains only the two-letter country code supplied by Cloudflare at the edge. It does not retain the raw address for the world view
  retention:
  - period: 30 days
    scope: X twclid in local storage
    text: ViewsMeet also keeps a valid twclid with its capture time in local storage for no more than 30 days so a later coarse conversion can be matched.
  - period: seven days
    scope: Unfinished personality snapshot in browser
    text: An unfinished snapshot can keep its shuffled item order and bounded 1–5 responses in this browser’s local storage for up to seven days.
  - period: seven days
    scope: Perception challenges
    text: They expire no later than seven days after creation and are hard-deleted with their responses and safety reports
  rights:
  - right: delete response
    text: Use the local response control to delete your challenge response and invalidate relays made from it.
  - right: clear local storage
    text: Clear local storage to remove tokens from the current device, understanding that this also removes local deletion access.
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
name: ViewsMeet
provenance_date: '2026-11-10'
provider_name: ViewsMeet
provider_slug: viewsmeet-com
slug: viewsmeet-com-privacy-policy
source_date: '2026-11-10'
source_filename: viewsmeet-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://viewsmeet.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ViewsMeet\naid: viewsmeet-com\nurl: https://viewsmeet.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: A submission contains the pack ID, version, digest, five self choices, five panel predictions, and whether\n    public contribution was selected.\n- category: device\n  text: Each request can contain the Event ID, a random deduplication ID, the stored X Click ID when available,\n    and the request IP address plus user agent\n- category: location\n  text: For the public world view, ViewsMeet retains only the two-letter country\
  \ code supplied by Cloudflare at\n    the edge.\n- category: contact\n  text: Cloudflare Email Routing forwards the sender, recipient, subject, message content, and normal email headers\n    to a verified destination mailbox outside the gameplay database.\npurposes:\n- purpose: X advertising measurement\n  text: X can use the resulting site-visit and landing-page activity for campaign attribution, reporting, optimization,\n    website-activity audiences, retargeting, and related audience modeling under X’s own terms and controls.\n- purpose: Operational security\n  text: The Cloudflare edge can process IP address, user agent, route, response status, approximate region, timing,\n    rate-limit, abuse, and security signals needed to deliver and protect the service.\nretention:\n- scope: X twclid in local storage\n  period: 30 days\n  text: ViewsMeet also keeps a valid twclid with its capture time in local storage for no more than 30 days so a\n    later coarse conversion can be matched.\n\
  - scope: Unfinished personality snapshot in browser\n  period: seven days\n  text: An unfinished snapshot can keep its shuffled item order and bounded 1–5 responses in this browser’s local\n    storage for up to seven days.\n- scope: Perception challenges\n  period: seven days\n  text: They expire no later than seven days after creation and are hard-deleted with their responses and safety\n    reports\nresidency:\n- region: edge country code\n  text: For the public world view, ViewsMeet retains only the two-letter country code supplied by Cloudflare at\n    the edge. It does not retain the raw address for the world view\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: creator control\n  text: Use the creator control to delete a challenge and every relay into it.\nrights:\n- right: delete response\n  text: Use the local response control to delete your challenge response and invalidate relays made from it.\n\
  - right: clear local storage\n  text: Clear local storage to remove tokens from the current device, understanding that this also removes local\n    deletion access.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/viewsmeet-com/privacy/viewsmeet-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 13 quoted statements, read from ViewsMeet's own page on 2026-11-10.
synthetic: false
tags:
- Social
- Games
- Personality Assessment
- Surveys & Polls
- Agent-Native
- MCP
- A2A
- Research
- Psychology
- Consumer
- Cloudflare Workers
---
