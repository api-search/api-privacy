---
api_specs:
- filename: scripthaul-com-openapi.json
  format: json
  label: ScriptHaul API
  slug: scripthaul-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scripthaul-com/openapi/scripthaul-com-openapi.json
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process the YouTube link, or list of links, you submit
  - category: contact
    text: If you email us, we process your email address, message, attachments, and any information you choose to provide.
  - category: device
    text: Cloudflare receives the request needed to connect you to the site. It may process your IP address, browser or user-agent, request URL and headers, referrer, approximate network location, security signals, and request timing
  - category: behavioral
    text: We use Google Analytics 4 to measure how the site is used in aggregate — pages visited, sessions, and rough geography.
  - category: communication
    text: A copyright or takedown notice may include your name, address, telephone number, signature, and statements required to evaluate the notice.
  - category: health
    text: Public captions may incidentally contain names, opinions, health information, political or religious discussion, or other material that could be sensitive in context.
  deletion:
    route: Request deletion of identifiable job metadata via support contact
    text: ask us to delete identifiable job metadata
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Create and complete transcript jobs
    text: validate a submitted link and create, resume, display, and complete transcript jobs
  - purpose: Abuse prevention and rate limits
    text: run Turnstile, enforce request and read limits, prevent duplicate work, and detect abuse
  - purpose: Aggregate site usage measurement
    text: We use Google Analytics 4 to measure how the site is used in aggregate
  - purpose: Respond to rights and support requests
    text: respond to support, privacy, copyright, and other rights requests
  residency:
  - region: United States
    text: the fetch relay is hosted in the United States
  retention:
  - period: indefinitely
    scope: Public caption data and source metadata
    text: Public caption data and related source metadata may be retained indefinitely to make repeat requests faster
  - period: about 90 days
    scope: Completed and failed job records
    text: Completed and failed job records, including their per-video rows, are deleted automatically after about 90 days
  - period: about three days
    scope: Daily quota counters
    text: Daily quota counters are deleted after about three days
  - period: about two days
    scope: Expired source inventories
    text: expired source inventories within about two days of expiring
  rights:
  - right: access
    text: Depending on where you live, you may have rights to request access, correction, deletion, restriction, objection, or portability
  - right: withdraw consent
    text: withdraw consent where processing relies on consent
  - right: appeal
    text: appeal a refusal
  - right: complain to regulator
    text: complain to a privacy regulator
  role:
    text: For personal information whose purposes and means we determine, the ScriptHaul operator acts as the data controller or business.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Transfers are handled as required by applicable law and the relevant provider arrangements.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: scripthaul-com
provenance_date: '2026-11-10'
provider_name: scripthaul-com
provider_slug: scripthaul-com
slug: scripthaul-com-privacy-policy
source_date: '2026-11-10'
source_filename: scripthaul-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scripthaul.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: scripthaul-com\naid: scripthaul-com\nurl: https://scripthaul.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For personal information whose purposes and means we determine, the ScriptHaul operator acts as the data\n    controller or business.\ndata_categories:\n- category: identifying\n  text: We process the YouTube link, or list of links, you submit\n- category: contact\n  text: If you email us, we process your email address, message, attachments, and any information you choose to\n    provide.\n- category: device\n  text: Cloudflare receives the request needed to connect you to\
  \ the site. It may process your IP address, browser\n    or user-agent, request URL and headers, referrer, approximate network location, security signals, and request\n    timing\n- category: behavioral\n  text: We use Google Analytics 4 to measure how the site is used in aggregate — pages visited, sessions, and rough\n    geography.\n- category: communication\n  text: A copyright or takedown notice may include your name, address, telephone number, signature, and statements\n    required to evaluate the notice.\n- category: health\n  text: Public captions may incidentally contain names, opinions, health information, political or religious discussion,\n    or other material that could be sensitive in context.\npurposes:\n- purpose: Create and complete transcript jobs\n  text: validate a submitted link and create, resume, display, and complete transcript jobs\n- purpose: Abuse prevention and rate limits\n  text: run Turnstile, enforce request and read limits, prevent duplicate work, and\
  \ detect abuse\n- purpose: Aggregate site usage measurement\n  text: We use Google Analytics 4 to measure how the site is used in aggregate\n- purpose: Respond to rights and support requests\n  text: respond to support, privacy, copyright, and other rights requests\nretention:\n- scope: Public caption data and source metadata\n  period: indefinitely\n  text: Public caption data and related source metadata may be retained indefinitely to make repeat requests faster\n- scope: Completed and failed job records\n  period: about 90 days\n  text: Completed and failed job records, including their per-video rows, are deleted automatically after about\n    90 days\n- scope: Daily quota counters\n  period: about three days\n  text: Daily quota counters are deleted after about three days\n- scope: Expired source inventories\n  period: about two days\n  text: expired source inventories within about two days of expiring\nresidency:\n- region: United States\n  text: the fetch relay is hosted in the United\
  \ States\ntransfers:\n- mechanism: other\n  text: Transfers are handled as required by applicable law and the relevant provider arrangements.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of identifiable job metadata via support contact\n  text: ask us to delete identifiable job metadata\nrights:\n- right: access\n  text: Depending on where you live, you may have rights to request access, correction, deletion, restriction, objection,\n    or portability\n- right: withdraw consent\n  text: withdraw consent where processing relies on consent\n- right: appeal\n  text: appeal a refusal\n- right: complain to regulator\n  text: complain to a privacy regulator\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal information.\n"
source_yaml_url: https://artifacts.apis.io/scripthaul-com/privacy/scripthaul-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from scripthaul-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- YouTube
- Transcripts
- Free
- Bulk
---
