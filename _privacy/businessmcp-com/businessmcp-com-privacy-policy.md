---
api_specs:
- filename: businessmcp-com-account-api-openapi.yml
  format: yaml
  label: BusinessMCP Account API
  slug: businessmcp-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-account-api-openapi.yml
- filename: businessmcp-com-assistant-api-openapi.yml
  format: yaml
  label: BusinessMCP Assistant API
  slug: businessmcp-com-assistant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-assistant-api-openapi.yml
- filename: businessmcp-com-companies-api-openapi.yml
  format: yaml
  label: BusinessMCP Companies API
  slug: businessmcp-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-companies-api-openapi.yml
- filename: businessmcp-com-email-api-openapi.yml
  format: yaml
  label: BusinessMCP Email API
  slug: businessmcp-com-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-email-api-openapi.yml
- filename: businessmcp-com-events-api-api-openapi.yml
  format: yaml
  label: BusinessMCP Events API
  slug: businessmcp-com-events-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-events-api-api-openapi.yml
- filename: businessmcp-com-export-api-openapi.yml
  format: yaml
  label: BusinessMCP Export API
  slug: businessmcp-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-export-api-openapi.yml
- filename: businessmcp-com-free-api-openapi.yml
  format: yaml
  label: BusinessMCP Free API
  slug: businessmcp-com-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-free-api-openapi.yml
- filename: businessmcp-com-ip-api-openapi.yml
  format: yaml
  label: BusinessMCP Ip API
  slug: businessmcp-com-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-ip-api-openapi.yml
- filename: businessmcp-com-meta-api-openapi.yml
  format: yaml
  label: BusinessMCP Meta API
  slug: businessmcp-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-meta-api-openapi.yml
- filename: businessmcp-com-people-api-openapi.yml
  format: yaml
  label: BusinessMCP People API
  slug: businessmcp-com-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-people-api-openapi.yml
- filename: businessmcp-com-read-api-api-openapi.yml
  format: yaml
  label: BusinessMCP Read API
  slug: businessmcp-com-read-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-read-api-api-openapi.yml
- filename: businessmcp-com-signup-api-openapi.yml
  format: yaml
  label: BusinessMCP Signup API
  slug: businessmcp-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-signup-api-openapi.yml
- filename: businessmcp-com-sites-api-openapi.yml
  format: yaml
  label: BusinessMCP Sites API
  slug: businessmcp-com-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-sites-api-openapi.yml
- filename: businessmcp-com-technology-api-openapi.yml
  format: yaml
  label: BusinessMCP Technology API
  slug: businessmcp-com-technology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-technology-api-openapi.yml
- filename: businessmcp-com-tools-api-openapi.yml
  format: yaml
  label: BusinessMCP Tools API
  slug: businessmcp-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-tools-api-openapi.yml
- filename: businessmcp-com-traffic-api-openapi.yml
  format: yaml
  label: BusinessMCP Traffic API
  slug: businessmcp-com-traffic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-traffic-api-openapi.yml
- filename: businessmcp-com-trust-api-openapi.yml
  format: yaml
  label: BusinessMCP Trust API
  slug: businessmcp-com-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-trust-api-openapi.yml
- filename: businessmcp-com-usage-api-openapi.yml
  format: yaml
  label: BusinessMCP Usage API
  slug: businessmcp-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-usage-api-openapi.yml
- filename: businessmcp-com-visibility-api-openapi.yml
  format: yaml
  label: BusinessMCP Visibility API
  slug: businessmcp-com-visibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/businessmcp-com/openapi/businessmcp-com-visibility-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email, workspace name, team membership, and subscription status
  - category: contact
    text: CRM contacts
  - category: behavioral
    text: page paths
  - category: device
    text: device/browser type
  - category: location
    text: coarse geo (country/region/city derived from IP then discarded)
  - category: communication
    text: the messages you exchange with the AI assistant
  deletion:
    route: CRM self-service or email to privacy@businessmcp.com
    text: Workspace owners can export or delete any contact directly from the CRM without contacting us.
  dpa:
    available: true
    text: Each is bound by a data-protection agreement no less protective than our DPA
    url: null
  purposes:
  - purpose: service delivery
    text: 'Contract: to provide the service you signed up for'
  - purpose: product analytics and security
    text: operating cookieless, pseudonymous product analytics, securing the platform, and preventing abuse
  residency:
  - region: United States
    text: Our main database (Supabase) and our application hosting (Vercel) are in the United States
  - region: United Kingdom
    text: Our raw analytics event store (Tinybird) is in London, United Kingdom
  retention:
  - period: Up to 13 months
    scope: raw analytics events
    text: Up to 13 months
  - period: normally a few hours
    scope: visitor IP for company identification
    text: Until the enrichment job processes it — normally a few hours
  - period: 30 days
    scope: network observations
    text: 30 days after the visitor was last seen on that network
  - period: Until you delete the workspace or account
    scope: account and workspace content
    text: Until you delete the workspace or account
  rights:
  - right: access, rectify, erase, port, restrict, object
    text: to access, rectify, erase, port, restrict, and object to the processing of your personal data
  - right: withdraw consent
    text: to withdraw consent at any time
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with your local supervisory authority.
  role:
    text: we act as your processor
    value: both
  sale_or_sharing:
    stance: conditional
    text: we do not sell personal information
  subprocessors:
    text: Sub-processors
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission’s Standard Contractual Clauses
  - mechanism: DPF
    text: on the EU-U.S. Data Privacy Framework and its UK Extension
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BusinessMCP
provenance_date: '2026-11-09'
provider_name: BusinessMCP
provider_slug: businessmcp-com
slug: businessmcp-com-privacy-policy
source_date: '2026-11-09'
source_filename: businessmcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://businessmcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BusinessMCP\naid: businessmcp-com\nurl: https://businessmcp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as your processor\ndata_categories:\n- category: identifying\n  text: your email, workspace name, team membership, and subscription status\n- category: contact\n  text: CRM contacts\n- category: behavioral\n  text: page paths\n- category: device\n  text: device/browser type\n- category: location\n  text: coarse geo (country/region/city derived from IP then discarded)\n- category: communication\n  text: the messages you exchange with the AI assistant\npurposes:\n- purpose:\
  \ service delivery\n  text: 'Contract: to provide the service you signed up for'\n- purpose: product analytics and security\n  text: operating cookieless, pseudonymous product analytics, securing the platform, and preventing abuse\nretention:\n- scope: raw analytics events\n  period: Up to 13 months\n  text: Up to 13 months\n- scope: visitor IP for company identification\n  period: normally a few hours\n  text: Until the enrichment job processes it — normally a few hours\n- scope: network observations\n  period: 30 days\n  text: 30 days after the visitor was last seen on that network\n- scope: account and workspace content\n  period: Until you delete the workspace or account\n  text: Until you delete the workspace or account\nresidency:\n- region: United States\n  text: Our main database (Supabase) and our application hosting (Vercel) are in the United States\n- region: United Kingdom\n  text: Our raw analytics event store (Tinybird) is in London, United Kingdom\ntransfers:\n- mechanism:\
  \ SCC\n  text: we rely on the European Commission’s Standard Contractual Clauses\n- mechanism: DPF\n  text: on the EU-U.S. Data Privacy Framework and its UK Extension\nsubprocessors:\n  url: null\n  text: Sub-processors\ndpa:\n  available: true\n  url: null\n  text: Each is bound by a data-protection agreement no less protective than our DPA\ndeletion:\n  route: CRM self-service or email to privacy@businessmcp.com\n  text: Workspace owners can export or delete any contact directly from the CRM without contacting us.\nrights:\n- right: access, rectify, erase, port, restrict, object\n  text: to access, rectify, erase, port, restrict, and object to the processing of your personal data\n- right: withdraw consent\n  text: to withdraw consent at any time\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: conditional\n  text: we do not sell personal information\n"
source_yaml_url: https://artifacts.apis.io/businessmcp-com/privacy/businessmcp-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BusinessMCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Marketing
- Sales
- Automation
- Platform
---
