---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account email address, one-time sign-in codes, session tokens
  - category: contact
    text: Account email address, one-time sign-in codes, session tokens
  - category: financial
    text: Payment records (Stripe checkout session id, status, amount) — only if you request a paid verification level
  - category: device
    text: Server logs (IP address, request path, status, user agent)
  - category: location
    text: Verification and change events (method used, timestamp, the IP address the request came from)
  - category: behavioral
    text: 'Question log: the question text sent to the ask endpoint, the channel (human/agent), an optional agent identifier, timestamp'
  deletion:
    route: Write to hello@intesta.io from the email address on your account
    text: To exercise any right, write to hello@intesta.io from the email address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign-in and managing passports
    text: To let entity owners sign in and manage their passports (legitimate interest / performance of the service)
  - purpose: Registry
    text: The registry itself. Published entities and public facts are visible to anyone
  - purpose: Abuse prevention and passport improvement
    text: Abuse prevention, rate limiting and improving the passports (unanswered questions are shown to the entity owner as a to-do)
  - purpose: Trust level upgrade
    text: To upgrade an entity's trust level after a completed payment
  - purpose: Quota accounting
    text: for quota accounting and then deleted
  residency:
  - region: European Union
    text: 'Servers: hosted in the European Union (OVH, Germany).'
  - region: France
    text: Encrypted backups are stored in France.
  retention:
  - period: until you ask us to delete it
    scope: Account data
    text: 'Account: until you ask us to delete it. Codes and sessions: short-lived, expire automatically'
  - period: Up to 12 months
    scope: Question log
    text: Up to 12 months, then deleted automatically
  - period: Rotated within 30 days
    scope: Server logs
    text: Rotated within 30 days
  - period: up to 13 months
    scope: Usage logs
    text: These records are kept for up to 13 months for quota accounting and then deleted.
  - period: Kept while the entity exists
    scope: Entity data
    text: Kept while the entity exists.
  rights:
  - right: access
    text: you can ask us for access to, correction of, or deletion of your personal data
  - right: correction
    text: you can ask us for access to, correction of, or deletion of your personal data
  - right: deletion
    text: you can ask us for access to, correction of, or deletion of your personal data
  - right: objection
    text: object to processing
  - right: portability
    text: ask for a copy of your data
  - right: complaint
    text: You may also lodge a complaint with the Spanish data protection authority (AEPD) or the supervisory authority in your country.
  role:
    text: DC ESCRYPT SL is the data controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use advertising trackers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: intesta-io
provenance_date: '2026-11-09'
provider_name: intesta-io
provider_slug: intesta-io
slug: intesta-io-privacy-policy
source_date: '2026-11-09'
source_filename: intesta-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://intesta.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: intesta-io\naid: intesta-io\nurl: https://intesta.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: DC ESCRYPT SL is the data controller.\ndata_categories:\n- category: identifying\n  text: Account email address, one-time sign-in codes, session tokens\n- category: contact\n  text: Account email address, one-time sign-in codes, session tokens\n- category: financial\n  text: Payment records (Stripe checkout session id, status, amount) — only if you request a paid verification level\n- category: device\n  text: Server logs (IP address, request path, status, user agent)\n- category: location\n\
  \  text: Verification and change events (method used, timestamp, the IP address the request came from)\n- category: behavioral\n  text: 'Question log: the question text sent to the ask endpoint, the channel (human/agent), an optional agent\n    identifier, timestamp'\npurposes:\n- purpose: Sign-in and managing passports\n  text: To let entity owners sign in and manage their passports (legitimate interest / performance of the service)\n- purpose: Registry\n  text: The registry itself. Published entities and public facts are visible to anyone\n- purpose: Abuse prevention and passport improvement\n  text: Abuse prevention, rate limiting and improving the passports (unanswered questions are shown to the entity\n    owner as a to-do)\n- purpose: Trust level upgrade\n  text: To upgrade an entity's trust level after a completed payment\n- purpose: Quota accounting\n  text: for quota accounting and then deleted\nretention:\n- scope: Account data\n  period: until you ask us to delete it\n  text:\
  \ 'Account: until you ask us to delete it. Codes and sessions: short-lived, expire automatically'\n- scope: Question log\n  period: Up to 12 months\n  text: Up to 12 months, then deleted automatically\n- scope: Server logs\n  period: Rotated within 30 days\n  text: Rotated within 30 days\n- scope: Usage logs\n  period: up to 13 months\n  text: These records are kept for up to 13 months for quota accounting and then deleted.\n- scope: Entity data\n  period: Kept while the entity exists\n  text: Kept while the entity exists.\nresidency:\n- region: European Union\n  text: 'Servers: hosted in the European Union (OVH, Germany).'\n- region: France\n  text: Encrypted backups are stored in France.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@intesta.io from the email address on your account\n  text: To exercise any right, write to hello@intesta.io from the email address on your account.\nrights:\n\
  - right: access\n  text: you can ask us for access to, correction of, or deletion of your personal data\n- right: correction\n  text: you can ask us for access to, correction of, or deletion of your personal data\n- right: deletion\n  text: you can ask us for access to, correction of, or deletion of your personal data\n- right: objection\n  text: object to processing\n- right: portability\n  text: ask for a copy of your data\n- right: complaint\n  text: You may also lodge a complaint with the Spanish data protection authority (AEPD) or the supervisory authority\n    in your country.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not use advertising trackers.\n"
source_yaml_url: https://artifacts.apis.io/intesta-io/privacy/intesta-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from intesta-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
