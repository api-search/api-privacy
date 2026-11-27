---
api_specs:
- filename: deepdna-ai-knowledge-api-openapi.yml
  format: yaml
  label: deepdna-ai Knowledge API
  slug: deepdna-ai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deepdna-ai/openapi/deepdna-ai-knowledge-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address Your registration through the website form; telling you what changed at DeepDNA and answering your replies
  - category: device
    text: Country code Two-letter ISO country code (e.g. "ES", "DE") derived from your connection by Cloudflare.
  - category: communication
    text: What you are building (optional) If you filled it in, what you wrote about your use case and, if you chose one, the monthly volume you expected (up to 500 characters together)
  - category: identifying
    text: IP address Rate limiting of the form only (preventing abuse), while the form existed.
  - category: behavioral
    text: We log aggregated pageview metadata server-side (path, day, anonymised user-agent bucket, referrer host, UTM parameters) under legitimate interest
  deletion:
    route: Email to the privacy contact address
    text: You can request deletion of any data at any time.
  dpa:
    available: true
    text: Cloudflare maintains a GDPR compliance programme and offers a Data Processing Addendum (DPA) that includes Standard Contractual Clauses (SCCs) for international data transfers.
    url: null
  purposes:
  - purpose: Registration and contact about changes
    text: Your registration through the website form; telling you what changed at DeepDNA and answering your replies
  - purpose: Abuse prevention for signup form
    text: Rate limiting of the form only (preventing abuse), while the form existed.
  - purpose: Knowing whether the service is used
    text: 'Legitimate interest (Art. 6(1)(f)): knowing whether the service is used and what to cover next.'
  residency:
  - region: Outside the EEA possible
    text: your data may be replicated across Cloudflare's network of data centres worldwide, including locations outside the European Economic Area (EEA).
  retention:
  - period: until you request deletion
    scope: Email and associated metadata
    text: Until you request deletion
  - period: 3,600 seconds (1 hour)
    scope: IP address (rate limit key)
    text: automatically deleted after 3,600 seconds (1 hour)
  - period: three months
    scope: MCP lookup records
    text: deleted automatically by Cloudflare Workers Analytics Engine three months after they are written
  rights:
  - right: Access
    text: 'Right of access (Art. 15): Request a copy of all personal data we hold about you.'
  - right: Rectification
    text: 'Right to rectification (Art. 16): Request correction of inaccurate personal data'
  - right: Erasure
    text: 'Right to erasure (Art. 17): Request deletion of your personal data.'
  - right: Restriction
    text: 'Right to restriction of processing (Art. 18): Request that we limit how we use your data'
  - right: Portability
    text: 'Right to data portability (Art. 20): Receive your data in a structured, commonly used, machine-readable format (JSON)'
  - right: Object
    text: 'Right to object (Art. 21): Object to processing based on legitimate interest.'
  - right: Withdraw consent
    text: 'Right to withdraw consent : You may withdraw your consent at any time.'
  role:
    text: DeepDNA is the data controller for the personal data described in this policy, as defined under the EU General Data Protection Regulation (GDPR).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, share, or monetise your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) as approved by the European Commission
  - mechanism: other
    text: Cloudflare's Data Processing Addendum (DPA) , which incorporates appropriate safeguards under GDPR Art. 46
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: deepdna-ai
provenance_date: '2026-11-09'
provider_name: deepdna-ai
provider_slug: deepdna-ai
slug: deepdna-ai-privacy-policy
source_date: '2026-11-09'
source_filename: deepdna-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://deepdna.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: deepdna-ai\naid: deepdna-ai\nurl: https://deepdna.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: DeepDNA is the data controller for the personal data described in this policy, as defined under the EU General\n    Data Protection Regulation (GDPR).\ndata_categories:\n- category: contact\n  text: Email address Your registration through the website form; telling you what changed at DeepDNA and answering\n    your replies\n- category: device\n  text: Country code Two-letter ISO country code (e.g. \"ES\", \"DE\") derived from your connection by Cloudflare.\n- category: communication\n\
  \  text: What you are building (optional) If you filled it in, what you wrote about your use case and, if you chose\n    one, the monthly volume you expected (up to 500 characters together)\n- category: identifying\n  text: IP address Rate limiting of the form only (preventing abuse), while the form existed.\n- category: behavioral\n  text: We log aggregated pageview metadata server-side (path, day, anonymised user-agent bucket, referrer host,\n    UTM parameters) under legitimate interest\npurposes:\n- purpose: Registration and contact about changes\n  text: Your registration through the website form; telling you what changed at DeepDNA and answering your replies\n- purpose: Abuse prevention for signup form\n  text: Rate limiting of the form only (preventing abuse), while the form existed.\n- purpose: Knowing whether the service is used\n  text: 'Legitimate interest (Art. 6(1)(f)): knowing whether the service is used and what to cover next.'\nretention:\n- scope: Email and associated\
  \ metadata\n  period: until you request deletion\n  text: Until you request deletion\n- scope: IP address (rate limit key)\n  period: 3,600 seconds (1 hour)\n  text: automatically deleted after 3,600 seconds (1 hour)\n- scope: MCP lookup records\n  period: three months\n  text: deleted automatically by Cloudflare Workers Analytics Engine three months after they are written\nresidency:\n- region: Outside the EEA possible\n  text: your data may be replicated across Cloudflare's network of data centres worldwide, including locations outside\n    the European Economic Area (EEA).\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) as approved by the European Commission\n- mechanism: other\n  text: Cloudflare's Data Processing Addendum (DPA) , which incorporates appropriate safeguards under GDPR Art.\n    46\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Cloudflare maintains a GDPR compliance programme and offers a Data Processing\
  \ Addendum (DPA) that includes\n    Standard Contractual Clauses (SCCs) for international data transfers.\ndeletion:\n  route: Email to the privacy contact address\n  text: You can request deletion of any data at any time.\nrights:\n- right: Access\n  text: 'Right of access (Art. 15): Request a copy of all personal data we hold about you.'\n- right: Rectification\n  text: 'Right to rectification (Art. 16): Request correction of inaccurate personal data'\n- right: Erasure\n  text: 'Right to erasure (Art. 17): Request deletion of your personal data.'\n- right: Restriction\n  text: 'Right to restriction of processing (Art. 18): Request that we limit how we use your data'\n- right: Portability\n  text: 'Right to data portability (Art. 20): Receive your data in a structured, commonly used, machine-readable\n    format (JSON)'\n- right: Object\n  text: 'Right to object (Art. 21): Object to processing based on legitimate interest.'\n- right: Withdraw consent\n  text: 'Right to withdraw consent\
  \ : You may withdraw your consent at any time.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, share, or monetise your data.\n"
source_yaml_url: https://artifacts.apis.io/deepdna-ai/privacy/deepdna-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from deepdna-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacogenomics
- MCP
- AI Agents
- Genomics
- Healthcare
---
