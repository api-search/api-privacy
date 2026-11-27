---
api_specs:
- filename: atlasemoji-com-openapi-generated.yml
  format: yaml
  label: Atlasemoji API
  slug: atlasemoji-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlasemoji-com/openapi/_ae-authored/atlasemoji-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account identifier (e.g., user ID)
  - category: contact
    text: Basic profile info from your sign-in provider (typically name and email)
  - category: location
    text: Location data you choose to attach (map point/area)
  - category: location
    text: phone location pings from phones that accepted the session
  - category: device
    text: Device/app information (browser type, OS, app version)
  - category: communication
    text: Approximate network data (IP address) used for security and abuse prevention
  - category: financial
    text: Fixed geofence trial location data
  deletion:
    route: in-app account or content deletion, or request via in-app feedback channel
    text: 'Account + private content : retained until you delete it or delete your account'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide core features
    text: Provide core features (maps, posts, routes, datasets, sharing)
  - purpose: Authenticate and secure account
    text: Authenticate you and keep your account secure
  - purpose: Prevent abuse
    text: Prevent abuse (spam, harassment, illegal content)
  - purpose: Geofence sessions
    text: Operate consented geofence sessions, display participating phones, evaluate boundary crossings, and generate session event records.
  retention:
  - period: null
    scope: Account and private content
    text: 'Account + private content : retained until you delete it or delete your account (subject to backups and legal obligations).'
  - period: null
    scope: Logs
    text: 'Logs : retained for a limited period for security and reliability, then deleted or aggregated.'
  - period: null
    scope: Fixed geofence trial records
    text: 'Fixed geofence trial records : Saved manifests, geofence records, CRM/base-user records, consent logs, and event records may remain available so the creator can access the test data.'
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete data
  - right: Object or restrict
    text: Object to or restrict certain processing
  - right: Portability
    text: Data portability (where applicable)
  - right: Withdraw consent
    text: Withdraw consent (where we rely on consent)
  role:
    text: Atlasemoji is the data controller for personal data we process in the app.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No selling your personal data.
  subprocessors:
    text: 'Atlasemoji relies on infrastructure providers to operate. For example: Google Firebase (hosting, authentication, storage, database, and related services).'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, transfers are protected using lawful mechanisms such as Standard Contractual Clauses (SCCs) and other safeguards under GDPR Chapter V.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atlasemoji
provenance_date: '2026-11-09'
provider_name: Atlasemoji
provider_slug: atlasemoji-com
slug: atlasemoji-com-privacy-policy
source_date: '2026-11-09'
source_filename: atlasemoji-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://atlasemoji.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atlasemoji\naid: atlasemoji-com\nurl: https://atlasemoji.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Atlasemoji is the data controller for personal data we process in the app.\ndata_categories:\n- category: identifying\n  text: Account identifier (e.g., user ID)\n- category: contact\n  text: Basic profile info from your sign-in provider (typically name and email)\n- category: location\n  text: Location data you choose to attach (map point/area)\n- category: location\n  text: phone location pings from phones that accepted the session\n- category: device\n  text: Device/app information\
  \ (browser type, OS, app version)\n- category: communication\n  text: Approximate network data (IP address) used for security and abuse prevention\n- category: financial\n  text: Fixed geofence trial location data\npurposes:\n- purpose: Provide core features\n  text: Provide core features (maps, posts, routes, datasets, sharing)\n- purpose: Authenticate and secure account\n  text: Authenticate you and keep your account secure\n- purpose: Prevent abuse\n  text: Prevent abuse (spam, harassment, illegal content)\n- purpose: Geofence sessions\n  text: Operate consented geofence sessions, display participating phones, evaluate boundary crossings, and generate\n    session event records.\nretention:\n- scope: Account and private content\n  period: null\n  text: 'Account + private content : retained until you delete it or delete your account (subject to backups and\n    legal obligations).'\n- scope: Logs\n  period: null\n  text: 'Logs : retained for a limited period for security and reliability,\
  \ then deleted or aggregated.'\n- scope: Fixed geofence trial records\n  period: null\n  text: 'Fixed geofence trial records : Saved manifests, geofence records, CRM/base-user records, consent logs,\n    and event records may remain available so the creator can access the test data.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, transfers are protected using lawful mechanisms such as Standard Contractual Clauses (SCCs)\n    and other safeguards under GDPR Chapter V.\nsubprocessors:\n  url: null\n  text: 'Atlasemoji relies on infrastructure providers to operate. For example: Google Firebase (hosting, authentication,\n    storage, database, and related services).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app account or content deletion, or request via in-app feedback channel\n  text: 'Account + private content : retained until you delete it or delete your account'\nrights:\n- right: Access\n  text: Access your personal data\n- right:\
  \ Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete data\n- right: Object or restrict\n  text: Object to or restrict certain processing\n- right: Portability\n  text: Data portability (where applicable)\n- right: Withdraw consent\n  text: Withdraw consent (where we rely on consent)\nsale_or_sharing:\n  stance: prohibited\n  text: No selling your personal data.\n"
source_yaml_url: https://artifacts.apis.io/atlasemoji-com/privacy/atlasemoji-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Atlasemoji's own page on 2026-11-09.
synthetic: false
tags:
- GIS
- Platform
- Artificial Intelligence
- UAV
- Location Intelligence
---
