---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: email address, and - if you signed in with Google or GitHub - the identifier and display name that provider returns.'
  - category: health
    text: If you pass them to an AI plan, also allergies, injuries, pregnancy, medications and medical conditions.
  - category: other
    text: 'Your log: workouts and sets, meals and water, cardio, body metrics, supplements, goals, notes, recipes and check-ins.'
  - category: device
    text: 'Your sessions: sign-in times with the IP address and user-agent, so you and we can spot a session that is not yours.'
  - category: device
    text: We do log the request itself - the endpoint, the HTTP method and status, a timestamp, your IP address, your user-agent string and a request id
  - category: financial
    text: Billing details, if you ever pay for something
  deletion:
    route: delete entries or whole account in app; ladder applies
    text: Delete individual entries or the whole account. The ladder above applies.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery
    text: 'Your account and your log: to give you the service you asked for - GDPR Article 6(1)(b).'
  - purpose: rate limiting and abuse detection
    text: because that is what rate limiting, abuse detection and debugging run on.
  - purpose: AI analysis
    text: Routes it to the AI model that reads it
  residency:
  - region: EU
    text: Servers are in the EU (Hetzner, Falkenstein, Germany), with Cloudflare in front of them.
  - region: US
    text: Some of that processing is in the US, under Standard Contractual Clauses
  retention:
  - period: null
    scope: deleted records in backup
    text: After that it moves to a backup we hold for 30 more days , so we can still get it back if you write in.
  - period: 90 days
    scope: request logs
    text: Request logs (endpoint, status, IP, user-agent) 90 days
  - period: 24 hours
    scope: repeat-request cache
    text: Repeat-request cache ( Idempotency-Key ) 24 hours
  - period: 60 days
    scope: anonymous keys with no activity
    text: An anonymous record with no activity for 60 days may be deleted along with everything in it.
  rights:
  - right: access and export
    text: Export your whole log yourself, in a machine-readable format, from the app or the API.
  - right: rectification
    text: Edit any entry, any time.
  - right: object, restrict or complain
    text: Object, restrict, or complain. Email us.
  - right: restore deleted data
    text: Get something back that you deleted within the last 60 days - email us.
  role:
    text: For the data you log here we are the data controller under the GDPR.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not use your log to train AI models.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Some of that processing is in the US, under Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anatome
provenance_date: '2026-11-09'
provider_name: Anatome
provider_slug: anatome-dev
slug: anatome-dev-privacy-policy
source_date: '2026-11-09'
source_filename: anatome-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anatome.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anatome\naid: anatome-dev\nurl: https://anatome.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the data you log here we are the data controller under the GDPR.\ndata_categories:\n- category: identifying\n  text: 'Your account: email address, and - if you signed in with Google or GitHub - the identifier and display\n    name that provider returns.'\n- category: health\n  text: If you pass them to an AI plan, also allergies, injuries, pregnancy, medications and medical conditions.\n- category: other\n  text: 'Your log: workouts and sets, meals and water, cardio, body metrics,\
  \ supplements, goals, notes, recipes\n    and check-ins.'\n- category: device\n  text: 'Your sessions: sign-in times with the IP address and user-agent, so you and we can spot a session that\n    is not yours.'\n- category: device\n  text: We do log the request itself - the endpoint, the HTTP method and status, a timestamp, your IP address, your\n    user-agent string and a request id\n- category: financial\n  text: Billing details, if you ever pay for something\npurposes:\n- purpose: service delivery\n  text: 'Your account and your log: to give you the service you asked for - GDPR Article 6(1)(b).'\n- purpose: rate limiting and abuse detection\n  text: because that is what rate limiting, abuse detection and debugging run on.\n- purpose: AI analysis\n  text: Routes it to the AI model that reads it\nretention:\n- scope: deleted records in backup\n  period: null\n  text: After that it moves to a backup we hold for 30 more days , so we can still get it back if you write in.\n- scope: request\
  \ logs\n  period: 90 days\n  text: Request logs (endpoint, status, IP, user-agent) 90 days\n- scope: repeat-request cache\n  period: 24 hours\n  text: Repeat-request cache ( Idempotency-Key ) 24 hours\n- scope: anonymous keys with no activity\n  period: 60 days\n  text: An anonymous record with no activity for 60 days may be deleted along with everything in it.\nresidency:\n- region: EU\n  text: Servers are in the EU (Hetzner, Falkenstein, Germany), with Cloudflare in front of them.\n- region: US\n  text: Some of that processing is in the US, under Standard Contractual Clauses\ntransfers:\n- mechanism: SCC\n  text: Some of that processing is in the US, under Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete entries or whole account in app; ladder applies\n  text: Delete individual entries or the whole account. The ladder above applies.\nrights:\n- right: access and export\n  text: Export\
  \ your whole log yourself, in a machine-readable format, from the app or the API.\n- right: rectification\n  text: Edit any entry, any time.\n- right: object, restrict or complain\n  text: Object, restrict, or complain. Email us.\n- right: restore deleted data\n  text: Get something back that you deleted within the last 60 days - email us.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not use your log to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/anatome-dev/privacy/anatome-dev-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Anatome's own page on 2026-11-09.
synthetic: false
tags:
- Fitness
- Nutrition
- Artificial Intelligence
- Health
- Workout Tracking
---
