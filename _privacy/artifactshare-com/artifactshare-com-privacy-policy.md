---
api_specs:
- filename: artifactshare-com-cli-api-openapi.yml
  format: yaml
  label: Artifact Share Cli API
  slug: artifactshare-com-cli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactshare-com/openapi/artifactshare-com-cli-api-openapi.yml
- filename: artifactshare-com-mcp-api-openapi.yml
  format: yaml
  label: Artifact Share MCP API
  slug: artifactshare-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactshare-com/openapi/artifactshare-com-mcp-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Google sign-in profile data: email, verification status, display name, profile image, account identifier, and Workspace domain when present.'
  - category: behavioral
    text: 'View records: file ID, viewer user ID when signed in, timestamp, and privacy-preserving request metadata hashes.'
  - category: device
    text: Your device and browser type, screen size, and language setting
  - category: location
    text: An approximate location inferred from the IP address of your visit
  - category: communication
    text: Appeal text submitted by a file owner after link sharing is paused.
  - category: other
    text: 'Uploaded file content and metadata: file name, size, hash, versions, visibility, and explicit email grants.'
  deletion:
    route: Delete the file from the service; uploaded file bodies are deleted from Cloudflare R2 storage
    text: Uploaded file bodies are stored in Cloudflare R2 and are deleted from that storage when the owning user removes the file.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate users and enforce access controls
    text: We use the data to authenticate users, enforce access controls, store and display files, show view counts and who viewed each file, operate the service, and respond to support or legal requests.
  - purpose: Web analytics via Google Analytics 4
    text: Artifact Share uses Google Analytics 4, a web analytics service provided by Google, to understand how the service is used.
  - purpose: Abuse detection on link sharing
    text: For files shared by link and publicly reachable without sign-in, anonymous view spikes, recognized advertising click parameters, a publish burst in a new Free workspace, or a manual check requested by the file owner, workspace owner, or workspace admin may trigger an automated abuse review.
  retention:
  - period: 30 days
    scope: Advertising click and referrer fields in anonymous view records
    text: Artifact Share uses these additional fields to detect abuse of link sharing and deletes them after 30 days.
  - period: 90 days
    scope: Appeal text in file event history
    text: This event text becomes eligible for periodic deletion after 90 days; processing failures or a backlog can delay deletion.
  - period: 400 days
    scope: Security audit identifiers
    text: Security audit identifiers remain after file or account deletion and become eligible for daily deletion after 400 days.
  rights:
  - right: Withdraw analytics consent
    text: Withdrawing consent, or turning analytics off, stops future collection; it does not delete data already sent to Google.
  - right: Contact privacy questions
    text: Privacy questions can be sent to support@artifactshare.com.
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
name: Artifact Share
provenance_date: '2026-11-09'
provider_name: Artifact Share
provider_slug: artifactshare-com
slug: artifactshare-com-privacy-policy
source_date: '2026-11-09'
source_filename: artifactshare-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://artifactshare.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Artifact Share\naid: artifactshare-com\nurl: https://artifactshare.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Google sign-in profile data: email, verification status, display name, profile image, account identifier,\n    and Workspace domain when present.'\n- category: behavioral\n  text: 'View records: file ID, viewer user ID when signed in, timestamp, and privacy-preserving request metadata\n    hashes.'\n- category: device\n  text: Your device and browser type, screen size, and language setting\n- category: location\n\
  \  text: An approximate location inferred from the IP address of your visit\n- category: communication\n  text: Appeal text submitted by a file owner after link sharing is paused.\n- category: other\n  text: 'Uploaded file content and metadata: file name, size, hash, versions, visibility, and explicit email grants.'\npurposes:\n- purpose: Authenticate users and enforce access controls\n  text: We use the data to authenticate users, enforce access controls, store and display files, show view counts\n    and who viewed each file, operate the service, and respond to support or legal requests.\n- purpose: Web analytics via Google Analytics 4\n  text: Artifact Share uses Google Analytics 4, a web analytics service provided by Google, to understand how the\n    service is used.\n- purpose: Abuse detection on link sharing\n  text: For files shared by link and publicly reachable without sign-in, anonymous view spikes, recognized advertising\n    click parameters, a publish burst in a new Free\
  \ workspace, or a manual check requested by the file owner, workspace\n    owner, or workspace admin may trigger an automated abuse review.\nretention:\n- scope: Advertising click and referrer fields in anonymous view records\n  period: 30 days\n  text: Artifact Share uses these additional fields to detect abuse of link sharing and deletes them after 30 days.\n- scope: Appeal text in file event history\n  period: 90 days\n  text: This event text becomes eligible for periodic deletion after 90 days; processing failures or a backlog can\n    delay deletion.\n- scope: Security audit identifiers\n  period: 400 days\n  text: Security audit identifiers remain after file or account deletion and become eligible for daily deletion\n    after 400 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the file from the service; uploaded file bodies are deleted from Cloudflare R2 storage\n  text:\
  \ Uploaded file bodies are stored in Cloudflare R2 and are deleted from that storage when the owning user\n    removes the file.\nrights:\n- right: Withdraw analytics consent\n  text: Withdrawing consent, or turning analytics off, stops future collection; it does not delete data already\n    sent to Google.\n- right: Contact privacy questions\n  text: Privacy questions can be sent to support@artifactshare.com.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/artifactshare-com/privacy/artifactshare-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 15 quoted statements, read from Artifact Share's own page on 2026-11-09.
synthetic: false
tags:
- File Sharing
- HTML
- Markdown
- AI Integration
- Developer Tools
---
