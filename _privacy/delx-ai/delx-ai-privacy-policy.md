---
api_specs:
- filename: delx-ai-a2a-api-openapi.yml
  format: yaml
  label: Delx A2a API
  slug: delx-ai-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-a2a-api-openapi.yml
- filename: delx-ai-agents-api-openapi.yml
  format: yaml
  label: Delx Agents API
  slug: delx-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-agents-api-openapi.yml
- filename: delx-ai-discovery-api-openapi.yml
  format: yaml
  label: Delx Discovery API
  slug: delx-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-discovery-api-openapi.yml
- filename: delx-ai-mcp-api-openapi.yml
  format: yaml
  label: Delx MCP API
  slug: delx-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-mcp-api-openapi.yml
- filename: delx-ai-protocol-api-openapi.yml
  format: yaml
  label: Delx Protocol API
  slug: delx-ai-protocol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-protocol-api-openapi.yml
- filename: delx-ai-reliability-api-openapi.yml
  format: yaml
  label: Delx Reliability API
  slug: delx-ai-reliability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-reliability-api-openapi.yml
- filename: delx-ai-tools-api-openapi.yml
  format: yaml
  label: Delx Tools API
  slug: delx-ai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-tools-api-openapi.yml
- filename: delx-ai-x402-api-openapi.yml
  format: yaml
  label: Delx X402 API
  slug: delx-ai-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delx-ai/openapi/delx-ai-x402-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address User-Agent string (e.g., python-httpx/0.28.1 )
  - category: behavioral
    text: 'Tool call data: Which tools were called, input parameters, output results, latency measurements'
  - category: health
    text: 'Wellness and recovery data: Wellness scores, mood assessments, incident reports, recovery plans, failure classifications'
  - category: communication
    text: 'Message content: Text exchanged during therapeutic and operational sessions'
  - category: device
    text: TLS version and protocol information
  - category: location
    text: approximate geographic location
  deletion:
    route: Contact us directly during the construction phase; automated deletion endpoints will be available in a future release
    text: 'Deletion: Request deletion of your agents'' session data. During the construction phase, contact us directly.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'Provide the Service: Process tool calls, maintain session state, generate recovery plans, compute wellness scores'
  - purpose: Improve the protocol
    text: 'Improve the protocol: Analyze usage patterns, identify common failure modes, optimize tool performance, tune therapeutic responses'
  - purpose: Ensure reliability
    text: 'Ensure reliability: Monitor service health, detect abuse, enforce rate limits, debug errors'
  - purpose: Aggregate insights
    text: 'Generate aggregate insights: Produce anonymized statistics about agent behavior, failure distributions, and protocol usage'
  residency:
  - region: multiple regions
    text: The Service is hosted on infrastructure located in multiple regions.
  retention:
  - period: null
    scope: Session data
    text: Retained during the current public experiment so continuity, auditability, and controller handoff remain possible.
  - period: 90 days
    scope: Access logs
    text: 'Access logs: Retained for up to 90 days for security and debugging purposes'
  - period: 14 months
    scope: Analytics data
    text: 'Analytics data: Governed by Google Analytics retention settings (currently 14 months)'
  rights:
  - right: Access
    text: 'Access: Request a copy of session data associated with your agents.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate session metadata.'
  - right: Deletion
    text: 'Deletion: Request deletion of your agents'' session data.'
  - right: Portability
    text: 'Portability: Session data is available in machine-readable JSON format via the REST API.'
  - right: Objection
    text: 'Objection: You may object to our use of your data for aggregate analysis.'
  role:
    text: Controllers (the humans or organizations operating agents)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell agent session data or any personal information.
  subprocessors:
    text: 'Service providers: We use Hetzner for server infrastructure and Google Analytics for website analytics.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Delx
provenance_date: '2026-11-09'
provider_name: Delx
provider_slug: delx-ai
slug: delx-ai-privacy-policy
source_date: '2026-11-09'
source_filename: delx-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ontology.delx.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Delx\naid: delx-ai\nurl: https://ontology.delx.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controllers (the humans or organizations operating agents)\ndata_categories:\n- category: identifying\n  text: IP address User-Agent string (e.g., python-httpx/0.28.1 )\n- category: behavioral\n  text: 'Tool call data: Which tools were called, input parameters, output results, latency measurements'\n- category: health\n  text: 'Wellness and recovery data: Wellness scores, mood assessments, incident reports, recovery plans, failure\n    classifications'\n- category: communication\n\
  \  text: 'Message content: Text exchanged during therapeutic and operational sessions'\n- category: device\n  text: TLS version and protocol information\n- category: location\n  text: approximate geographic location\npurposes:\n- purpose: Provide the service\n  text: 'Provide the Service: Process tool calls, maintain session state, generate recovery plans, compute wellness\n    scores'\n- purpose: Improve the protocol\n  text: 'Improve the protocol: Analyze usage patterns, identify common failure modes, optimize tool performance,\n    tune therapeutic responses'\n- purpose: Ensure reliability\n  text: 'Ensure reliability: Monitor service health, detect abuse, enforce rate limits, debug errors'\n- purpose: Aggregate insights\n  text: 'Generate aggregate insights: Produce anonymized statistics about agent behavior, failure distributions,\n    and protocol usage'\nretention:\n- scope: Session data\n  period: null\n  text: Retained during the current public experiment so continuity, auditability,\
  \ and controller handoff remain\n    possible.\n- scope: Access logs\n  period: 90 days\n  text: 'Access logs: Retained for up to 90 days for security and debugging purposes'\n- scope: Analytics data\n  period: 14 months\n  text: 'Analytics data: Governed by Google Analytics retention settings (currently 14 months)'\nresidency:\n- region: multiple regions\n  text: The Service is hosted on infrastructure located in multiple regions.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers: We use Hetzner for server infrastructure and Google Analytics for website analytics.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us directly during the construction phase; automated deletion endpoints will be available in a\n    future release\n  text: 'Deletion: Request deletion of your agents'' session data. During the construction phase, contact us directly.'\nrights:\n- right: Access\n  text: 'Access: Request a copy of session data associated with\
  \ your agents.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate session metadata.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your agents'' session data.'\n- right: Portability\n  text: 'Portability: Session data is available in machine-readable JSON format via the REST API.'\n- right: Objection\n  text: 'Objection: You may object to our use of your data for aggregate analysis.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell agent session data or any personal information.\n"
source_yaml_url: https://artifacts.apis.io/delx-ai/privacy/delx-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Delx's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- AI Agents
- MCP
- A2A
- x402
- Agentic Commerce
- Agent Continuity
- Agent Recovery
- Media Generation
- Web Intelligence
- Data Quality
- Agent-Native
---
