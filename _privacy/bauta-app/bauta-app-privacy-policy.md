---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'When you sign in (via WorkOS AuthKit, e.g. with Google): a user ID, your email address, and your name.'
  - category: behavioral
    text: Aggregate, cookieless view counts via Cloudflare Analytics Engine.
  deletion:
    route: Artifact owners self-serve via export_artifact and delete_artifact tools; account-level erasure by email to privacy@bauta.app
    text: 'Account-level erasure and all other requests: email privacy@bauta.app'
  dpa:
    available: true
    text: Each processor's Data Processing Addendum applies to its processing of personal data on our behalf
    url: null
  purposes:
  - purpose: hosting and serving artifacts
    text: We do not read or use your artifact content for anything other than hosting it, serving it to the people you share it with, and abuse prevention
  - purpose: security and abuse defense
    text: 'Legal basis: our legitimate interest (GDPR art. 6(1)(f)) in security, abuse defense, and the accountability of a hosting service.'
  residency:
  - region: EU
    text: Artifact content is stored in a Cloudflare R2 bucket created with the EU jurisdiction restriction
  - region: global
    text: Serving pointers and token storage (Cloudflare Workers KV) are globally replicated by design and cannot be restricted to a single region
  retention:
  - period: removed immediately
    scope: Artifacts you delete
    text: 'Artifacts you delete are removed immediately: metadata is deleted and content is removed once no other artifact references the same content.'
  - period: within at most 2 hours of expiry
    scope: One-time codes and rate-limit counters
    text: within at most 2 hours of expiry, most within 30 minutes
  - period: retained after artifact or account deletion
    scope: Audit log
    text: Audit log entries are append-only and are retained after artifact or account deletion
  - period: 30 days
    scope: Infrastructure point-in-time recovery copies held by Cloudflare
    text: Infrastructure-level point-in-time recovery copies held by Cloudflare age out within 30 days
  rights:
  - right: access, rectify, export, delete, object, restrict
    text: you have the right to access, rectify, export, and delete your personal data, and to object to or restrict processing
  - right: lodge complaint
    text: You may also lodge a complaint with your local supervisory authority (in Norway, Datatilsynet).
  role:
    text: 'Controller: Laien AS (org.nr. NO 916 557 221 MVA), Buen 25, 1528 Moss, Norway.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or share it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where any data is processed on Cloudflare infrastructure outside the EU/EEA, Cloudflare's Data Processing Addendum and its standard contractual clauses govern the transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bauta
provenance_date: '2026-11-09'
provider_name: Bauta
provider_slug: bauta-app
slug: bauta-app-privacy-policy
source_date: '2026-11-09'
source_filename: bauta-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bauta.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bauta\naid: bauta-app\nurl: https://bauta.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Laien AS (org.nr. NO 916 557 221 MVA), Buen 25, 1528 Moss, Norway.'\ndata_categories:\n- category: identifying\n  text: 'When you sign in (via WorkOS AuthKit, e.g. with Google): a user ID, your email address, and your name.'\n- category: behavioral\n  text: Aggregate, cookieless view counts via Cloudflare Analytics Engine.\npurposes:\n- purpose: hosting and serving artifacts\n  text: We do not read or use your artifact content for anything other than hosting it, serving it to the\
  \ people\n    you share it with, and abuse prevention\n- purpose: security and abuse defense\n  text: 'Legal basis: our legitimate interest (GDPR art. 6(1)(f)) in security, abuse defense, and the accountability\n    of a hosting service.'\nretention:\n- scope: Artifacts you delete\n  period: removed immediately\n  text: 'Artifacts you delete are removed immediately: metadata is deleted and content is removed once no other\n    artifact references the same content.'\n- scope: One-time codes and rate-limit counters\n  period: within at most 2 hours of expiry\n  text: within at most 2 hours of expiry, most within 30 minutes\n- scope: Audit log\n  period: retained after artifact or account deletion\n  text: Audit log entries are append-only and are retained after artifact or account deletion\n- scope: Infrastructure point-in-time recovery copies held by Cloudflare\n  period: 30 days\n  text: Infrastructure-level point-in-time recovery copies held by Cloudflare age out within 30 days\nresidency:\n\
  - region: EU\n  text: Artifact content is stored in a Cloudflare R2 bucket created with the EU jurisdiction restriction\n- region: global\n  text: Serving pointers and token storage (Cloudflare Workers KV) are globally replicated by design and cannot\n    be restricted to a single region\ntransfers:\n- mechanism: SCC\n  text: Where any data is processed on Cloudflare infrastructure outside the EU/EEA, Cloudflare's Data Processing\n    Addendum and its standard contractual clauses govern the transfer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Each processor's Data Processing Addendum applies to its processing of personal data on our behalf\ndeletion:\n  route: Artifact owners self-serve via export_artifact and delete_artifact tools; account-level erasure by email\n    to privacy@bauta.app\n  text: 'Account-level erasure and all other requests: email privacy@bauta.app'\nrights:\n- right: access, rectify, export, delete, object, restrict\n \
  \ text: you have the right to access, rectify, export, and delete your personal data, and to object to or restrict\n    processing\n- right: lodge complaint\n  text: You may also lodge a complaint with your local supervisory authority (in Norway, Datatilsynet).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/bauta-app/privacy/bauta-app-privacy-policy.yml
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
summary_line: 17 quoted statements, read from Bauta's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sharing
- NoLogin
- Web Links
- Productivity
---
