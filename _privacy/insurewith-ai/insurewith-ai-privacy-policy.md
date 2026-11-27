---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Privacy-respecting analytics for site usage (page views, general geography).
  - category: communication
    text: AI chat messages are processed to generate responses but are not permanently stored.
  - category: other
    text: Uploaded PDFs are analyzed in real time and are not retained by InsureWith
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: site analytics
    text: Privacy-respecting analytics for site usage
  - purpose: generate chat responses
    text: AI chat messages are processed to generate responses
  - purpose: SBC document extraction
    text: The document's text is sent to OpenAI's API for the extraction step
  retention:
  - period: null
    scope: uploaded PDFs
    text: are not retained by InsureWith
  - period: null
    scope: AI chat messages
    text: are not permanently stored
  - period: limited-duration
    scope: OpenAI API inputs
    text: may be subject to OpenAI's limited-duration abuse-monitoring retention
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No data sold to third parties
  subprocessors:
    text: We use Cloudflare for hosting and content delivery, Google Fonts for typography, and OpenAI's API as the processing provider for SBC document extraction and AI chat responses
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: insurewith-ai
provenance_date: '2026-11-09'
provider_name: insurewith-ai
provider_slug: insurewith-ai
slug: insurewith-ai-privacy-policy
source_date: '2026-11-09'
source_filename: insurewith-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://insurewith.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: insurewith-ai\naid: insurewith-ai\nurl: https://insurewith.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Privacy-respecting analytics for site usage (page views, general geography).\n- category: communication\n  text: AI chat messages are processed to generate responses but are not permanently stored.\n- category: other\n  text: Uploaded PDFs are analyzed in real time and are not retained by InsureWith\npurposes:\n- purpose: site analytics\n  text: Privacy-respecting analytics for site usage\n- purpose: generate chat responses\n\
  \  text: AI chat messages are processed to generate responses\n- purpose: SBC document extraction\n  text: The document's text is sent to OpenAI's API for the extraction step\nretention:\n- scope: uploaded PDFs\n  period: null\n  text: are not retained by InsureWith\n- scope: AI chat messages\n  period: null\n  text: are not permanently stored\n- scope: OpenAI API inputs\n  period: limited-duration\n  text: may be subject to OpenAI's limited-duration abuse-monitoring retention\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use Cloudflare for hosting and content delivery, Google Fonts for typography, and OpenAI's API as the\n    processing provider for SBC document extraction and AI chat responses\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No data sold to third parties\n"
source_yaml_url: https://artifacts.apis.io/insurewith-ai/privacy/insurewith-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- sale_or_sharing
summary_line: 11 quoted statements, read from insurewith-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Insurance
- Pharmacy
- Data
- Artificial Intelligence
---
