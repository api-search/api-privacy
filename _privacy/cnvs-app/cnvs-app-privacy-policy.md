---
api_specs:
- filename: cnvs-app-ai-facing-api-openapi.yml
  format: yaml
  label: cnvs.app AI Facing API
  slug: cnvs-app-ai-facing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnvs-app/openapi/cnvs-app-ai-facing-api-openapi.yml
- filename: cnvs-app-boards-api-openapi.yml
  format: yaml
  label: cnvs.app Boards API
  slug: cnvs-app-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnvs-app/openapi/cnvs-app-boards-api-openapi.yml
- filename: cnvs-app-discovery-api-openapi.yml
  format: yaml
  label: cnvs.app Discovery API
  slug: cnvs-app-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnvs-app/openapi/cnvs-app-discovery-api-openapi.yml
- filename: cnvs-app-items-api-openapi.yml
  format: yaml
  label: cnvs.app Items API
  slug: cnvs-app-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnvs-app/openapi/cnvs-app-items-api-openapi.yml
- filename: cnvs-app-kanban-api-openapi.yml
  format: yaml
  label: cnvs.app Kanban API
  slug: cnvs-app-kanban-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnvs-app/openapi/cnvs-app-kanban-api-openapi.yml
- filename: cnvs-app-reads-api-openapi.yml
  format: yaml
  label: cnvs.app Reads API
  slug: cnvs-app-reads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cnvs-app/openapi/cnvs-app-reads-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Board security data: the board ID, lock mode, and a salted one-way hash of an optional access key.'
  - category: contact
    text: 'Support submissions: information you choose to send through the feedback form or support email.'
  - category: behavioral
    text: Coarse product events cover creating a board, copying a board's share link, opening the todo landing page, switching board mode, and creating a column or creating/moving a task.
  - category: location
    text: approximate location derived from network information
  - category: device
    text: browser, device and operating-system details
  - category: communication
    text: 'Operational connection data: Cloudflare and our service may process IP address, request headers, timing, and security/rate-limit signals needed to deliver and protect the service.'
  - category: other
    text: 'Board content: drawings, text, links, images, diagrams, columns, tasks, coordinates, item IDs, author labels, and timestamps supplied by collaborators or MCP/API clients.'
  deletion:
    route: Holding the delete control removes a board's content from the live service.
    text: Holding the delete control removes a board's content from the live service.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate shared boards and sync collaborators
    text: We use board and connection data to synchronize collaborators, render previews and exports, execute requested MCP/API operations, enforce quotas and access locks, prevent abuse, diagnose failures, and maintain the service.
  - purpose: aggregate feature usage analytics
    text: Aggregate analytics helps us understand basic feature usage.
  - purpose: support assistance
    text: When you ask support for help, connection data from short-lived service logs (kept about 7 days) may be used to help locate your boards.
  retention:
  - period: 30 days
    scope: inactive boards
    text: Boards are retained for up to 30 days of inactivity .
  - period: 30 days
    scope: deleted board ID tombstone
    text: The deleted ID remains tombstoned for 30 days so stale links show an erased state.
  - period: about 7 days
    scope: short-lived service logs
    text: connection data from short-lived service logs (kept about 7 days)
  - period: null
    scope: Cloudflare D1 Time Travel history
    text: currently up to 7 days on Workers Free or 30 days on Workers Paid
  - period: at most 60 seconds
    scope: cnvs_created cookie
    text: sets a first-party cnvs_created cookie for at most 60 seconds
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not use board content to train AI models, sell personal data, build advertising profiles, or run a public board directory.
  subprocessors:
    text: 'Service providers process limited data on our behalf: Cloudflare provides edge delivery, Workers, Durable Objects, D1 storage, security, and rate limiting. Google Analytics provides aggregate page and coarse product-usage measurement. Coder AI feedback service receives support information you intentionally submit.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cnvs.app
provenance_date: '2026-11-09'
provider_name: cnvs.app
provider_slug: cnvs-app
slug: cnvs-app-privacy-policy
source_date: '2026-11-09'
source_filename: cnvs-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cnvs.app/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cnvs.app\naid: cnvs-app\nurl: https://cnvs.app/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Board security data: the board ID, lock mode, and a salted one-way hash of an optional access key.'\n- category: contact\n  text: 'Support submissions: information you choose to send through the feedback form or support email.'\n- category: behavioral\n  text: Coarse product events cover creating a board, copying a board's share link, opening the todo landing page,\n    switching board mode, and creating a column or creating/moving a\
  \ task.\n- category: location\n  text: approximate location derived from network information\n- category: device\n  text: browser, device and operating-system details\n- category: communication\n  text: 'Operational connection data: Cloudflare and our service may process IP address, request headers, timing,\n    and security/rate-limit signals needed to deliver and protect the service.'\n- category: other\n  text: 'Board content: drawings, text, links, images, diagrams, columns, tasks, coordinates, item IDs, author labels,\n    and timestamps supplied by collaborators or MCP/API clients.'\npurposes:\n- purpose: operate shared boards and sync collaborators\n  text: We use board and connection data to synchronize collaborators, render previews and exports, execute requested\n    MCP/API operations, enforce quotas and access locks, prevent abuse, diagnose failures, and maintain the service.\n- purpose: aggregate feature usage analytics\n  text: Aggregate analytics helps us understand basic\
  \ feature usage.\n- purpose: support assistance\n  text: When you ask support for help, connection data from short-lived service logs (kept about 7 days) may be\n    used to help locate your boards.\nretention:\n- scope: inactive boards\n  period: 30 days\n  text: Boards are retained for up to 30 days of inactivity .\n- scope: deleted board ID tombstone\n  period: 30 days\n  text: The deleted ID remains tombstoned for 30 days so stale links show an erased state.\n- scope: short-lived service logs\n  period: about 7 days\n  text: connection data from short-lived service logs (kept about 7 days)\n- scope: Cloudflare D1 Time Travel history\n  period: null\n  text: currently up to 7 days on Workers Free or 30 days on Workers Paid\n- scope: cnvs_created cookie\n  period: at most 60 seconds\n  text: sets a first-party cnvs_created cookie for at most 60 seconds\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers process limited data on our behalf: Cloudflare\
  \ provides edge delivery, Workers, Durable\n    Objects, D1 storage, security, and rate limiting. Google Analytics provides aggregate page and coarse product-usage\n    measurement. Coder AI feedback service receives support information you intentionally submit.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Holding the delete control removes a board's content from the live service.\n  text: Holding the delete control removes a board's content from the live service.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use board content to train AI models, sell personal data, build advertising profiles, or run a\n    public board directory.\n"
source_yaml_url: https://artifacts.apis.io/cnvs-app/privacy/cnvs-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 18 quoted statements, read from cnvs.app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Whiteboard
- Collaboration
- Real-Time
- Kanban
- MCP
- AI Agents
- Diagramming
---
