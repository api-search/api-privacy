---
api_specs:
- filename: adsagent-md-openapi-generated.yml
  format: yaml
  label: adsagent-md API
  slug: adsagent-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsagent-md/openapi/_ae-authored/adsagent-md-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: AdsAgent may collect public profile details such as name, profile picture, and email address.
  - category: contact
    text: with the OpenID Connect scopes, AdsAgent receives your email address, basic profile, and the OpenID subject identifier to establish your account.
  - category: financial
    text: 'Billing setup status: whether a connected account has billing configured.'
  - category: behavioral
    text: 'Daily spend metrics: recent spend and related reporting metrics for connected accounts.'
  - category: device
    text: 'Operational logs: minimal request metadata (for example tool name, request identifiers, and error classifications) used for security, abuse prevention, and support — not full chat transcripts.'
  deletion:
    route: Email support@adsagent.md to request deletion; platform revocation steps in Section 4
    text: Email support@adsagent.md to request full deletion from AdsAgent systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Dashboard visualization
    text: 'Dashboard visualization: display ad account, page, and performance information inside AdsAgent.'
  - purpose: Ad management and automation
    text: 'Ad management and automation: AdsAgent supports authorized operations on platforms where the relevant features are enabled.'
  - purpose: Cross-platform reporting
    text: 'Cross-platform reporting: combine authorized data sources into one operating view.'
  - purpose: AI assistant workflows
    text: 'AI assistant workflows: when you connect ChatGPT Apps, Claude, or another MCP client, return bounded tool responses so you can inspect and manage authorized advertising data inside that client.'
  residency:
  - region: United States or other jurisdictions
    text: may process personal data on infrastructure located in the United States or other jurisdictions.
  retention:
  - period: 30 days
    scope: Google data
    text: are retained while the connection is active and for up to 30 days after you revoke access or request deletion
  - period: thirty (30) days
    scope: TikTok data
    text: are deleted or anonymized after verified revocation or deletion requests, typically within thirty (30) days .
  - period: null
    scope: Tool-call audit logs
    text: 'Tool-call audit logs (tool name, status, request/response size, hashed identifiers — not full chat transcripts): retained for thirty (30) days , then automatically deleted.'
  - period: fifteen (15) days
    scope: Datadog application logs
    text: The same request metadata in application logs is processed by our logging provider (Datadog) and retained for fifteen (15) days .
  - period: null
    scope: Error diagnostics
    text: retained for fourteen (14) days by default, up to thirty (30) days when needed for abuse or reliability investigation, then automatically deleted.
  - period: null
    scope: Support error reports
    text: 'Support error reports (bounded diagnostics you explicitly submit or approve for troubleshooting): retained for ninety (90) days , then automatically deleted.'
  rights:
  - right: Access
    text: Right of access — request a copy of the personal data we hold about you.
  - right: Erasure
    text: Right to erasure ("right to be forgotten") — request deletion of personal data we hold, subject to legal retention obligations.
  - right: Portability
    text: Right to data portability — receive your personal data in a structured, machine-readable format and transmit it to another controller.
  - right: Object
    text: Right to object — object to processing where it is based on legitimate interests or used for direct marketing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: AdsAgent does not sell, trade, or otherwise transfer personally identifiable information, Meta Ads data, Google Ads data, or TikTok Ads data to outside parties for unrelated commercial use.
  subprocessors:
    text: We use infrastructure providers such as Supabase, Cloudflare, Hetzner and DigitalOcean to host the service, and Datadog for operational logs and monitoring.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses or other lawful transfer mechanisms recognized by the relevant supervisory authority.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: adsagent-md
provenance_date: '2026-11-09'
provider_name: adsagent-md
provider_slug: adsagent-md
slug: adsagent-md-privacy-policy
source_date: '2026-11-09'
source_filename: adsagent-md-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adsagent.md/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: adsagent-md\naid: adsagent-md\nurl: https://adsagent.md/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: AdsAgent may collect public profile details such as name, profile picture, and email address.\n- category: contact\n  text: with the OpenID Connect scopes, AdsAgent receives your email address, basic profile, and the OpenID subject\n    identifier to establish your account.\n- category: financial\n  text: 'Billing setup status: whether a connected account has billing configured.'\n- category: behavioral\n  text: 'Daily spend metrics:\
  \ recent spend and related reporting metrics for connected accounts.'\n- category: device\n  text: 'Operational logs: minimal request metadata (for example tool name, request identifiers, and error classifications)\n    used for security, abuse prevention, and support — not full chat transcripts.'\npurposes:\n- purpose: Dashboard visualization\n  text: 'Dashboard visualization: display ad account, page, and performance information inside AdsAgent.'\n- purpose: Ad management and automation\n  text: 'Ad management and automation: AdsAgent supports authorized operations on platforms where the relevant features\n    are enabled.'\n- purpose: Cross-platform reporting\n  text: 'Cross-platform reporting: combine authorized data sources into one operating view.'\n- purpose: AI assistant workflows\n  text: 'AI assistant workflows: when you connect ChatGPT Apps, Claude, or another MCP client, return bounded tool\n    responses so you can inspect and manage authorized advertising data inside that\
  \ client.'\nretention:\n- scope: Google data\n  period: 30 days\n  text: are retained while the connection is active and for up to 30 days after you revoke access or request deletion\n- scope: TikTok data\n  period: thirty (30) days\n  text: are deleted or anonymized after verified revocation or deletion requests, typically within thirty (30) days\n    .\n- scope: Tool-call audit logs\n  period: null\n  text: 'Tool-call audit logs (tool name, status, request/response size, hashed identifiers — not full chat transcripts):\n    retained for thirty (30) days , then automatically deleted.'\n- scope: Datadog application logs\n  period: fifteen (15) days\n  text: The same request metadata in application logs is processed by our logging provider (Datadog) and retained\n    for fifteen (15) days .\n- scope: Error diagnostics\n  period: null\n  text: retained for fourteen (14) days by default, up to thirty (30) days when needed for abuse or reliability\n    investigation, then automatically deleted.\n\
  - scope: Support error reports\n  period: null\n  text: 'Support error reports (bounded diagnostics you explicitly submit or approve for troubleshooting): retained\n    for ninety (90) days , then automatically deleted.'\nresidency:\n- region: United States or other jurisdictions\n  text: may process personal data on infrastructure located in the United States or other jurisdictions.\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses or other lawful transfer mechanisms recognized by the relevant supervisory\n    authority.\nsubprocessors:\n  url: null\n  text: We use infrastructure providers such as Supabase, Cloudflare, Hetzner and DigitalOcean to host the service,\n    and Datadog for operational logs and monitoring.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@adsagent.md to request deletion; platform revocation steps in Section 4\n  text: Email support@adsagent.md to request full deletion from AdsAgent systems.\n\
  rights:\n- right: Access\n  text: Right of access — request a copy of the personal data we hold about you.\n- right: Erasure\n  text: Right to erasure (\"right to be forgotten\") — request deletion of personal data we hold, subject to legal\n    retention obligations.\n- right: Portability\n  text: Right to data portability — receive your personal data in a structured, machine-readable format and transmit\n    it to another controller.\n- right: Object\n  text: Right to object — object to processing where it is based on legitimate interests or used for direct marketing.\nsale_or_sharing:\n  stance: prohibited\n  text: AdsAgent does not sell, trade, or otherwise transfer personally identifiable information, Meta Ads data,\n    Google Ads data, or TikTok Ads data to outside parties for unrelated commercial use.\n"
source_yaml_url: https://artifacts.apis.io/adsagent-md/privacy/adsagent-md-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from adsagent-md's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AdTech
- Marketing Automation
- Artificial Intelligence
- MCP
---
