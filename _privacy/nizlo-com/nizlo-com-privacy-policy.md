---
api_specs:
- filename: nizlo-com-nizlo-rmm-api-openapi.yml
  format: yaml
  label: Nizlo RMM API
  slug: nizlo-rmm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nizlo-com/openapi/nizlo-com-nizlo-rmm-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: technician names, business contact details, authentication events, tenant roles, and service preferences
  - category: device
    text: device identity, hardware and software inventory, health measurements, network addresses, logged-in username, alerts
  - category: communication
    text: conversation content, attachments, any name or email address the visitor supplies in chat
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide monitoring and support
    text: Provide monitoring, inventory, alerting, remote administration, automation, reporting, and support.
  - purpose: Authentication and security
    text: Authenticate users and devices, enforce tenant isolation and permissions, and investigate abuse or security events.
  - purpose: Advertising measurement
    text: we use Google Ads across the public Nizlo journey and the authenticated console solely to measure which ads lead to trial creation and which trials connect a first endpoint.
  retention:
  - period: six months
    scope: Measurement preference cookie
    text: We remember that choice in a first-party cookie for up to six months across nizlo.com and app.nizlo.com.
  - period: 30 days
    scope: Advertising attribution cookie
    text: a separate first-party cookie keeps advertising click identifiers and campaign codes for up to 30 days after the latest consented visit
  - period: 24 hours
    scope: Email campaign retry identifiers
    text: Retry identifiers expire after 24 hours; daily aggregate counters expire 30 days after their last update.
  rights:
  - right: access, correction, export, deletion
    text: To request access, correction, export, or deletion, use the authenticated Nizlo service desk.
  - right: withdraw advertising consent
    text: You can decline or withdraw consent through Cookie preferences in the footer.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nizlo
provenance_date: '2026-11-10'
provider_name: Nizlo
provider_slug: nizlo-com
slug: nizlo-com-privacy-policy
source_date: '2026-11-10'
source_filename: nizlo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nizlo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nizlo\naid: nizlo-com\nurl: https://nizlo.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: technician names, business contact details, authentication events, tenant roles, and service preferences\n- category: device\n  text: device identity, hardware and software inventory, health measurements, network addresses, logged-in username,\n    alerts\n- category: communication\n  text: conversation content, attachments, any name or email address the visitor supplies in chat\npurposes:\n- purpose: Provide monitoring and support\n  text:\
  \ Provide monitoring, inventory, alerting, remote administration, automation, reporting, and support.\n- purpose: Authentication and security\n  text: Authenticate users and devices, enforce tenant isolation and permissions, and investigate abuse or security\n    events.\n- purpose: Advertising measurement\n  text: we use Google Ads across the public Nizlo journey and the authenticated console solely to measure which\n    ads lead to trial creation and which trials connect a first endpoint.\nretention:\n- scope: Measurement preference cookie\n  period: six months\n  text: We remember that choice in a first-party cookie for up to six months across nizlo.com and app.nizlo.com.\n- scope: Advertising attribution cookie\n  period: 30 days\n  text: a separate first-party cookie keeps advertising click identifiers and campaign codes for up to 30 days after\n    the latest consented visit\n- scope: Email campaign retry identifiers\n  period: 24 hours\n  text: Retry identifiers expire after 24\
  \ hours; daily aggregate counters expire 30 days after their last update.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correction, export, deletion\n  text: To request access, correction, export, or deletion, use the authenticated Nizlo service desk.\n- right: withdraw advertising consent\n  text: You can decline or withdraw consent through Cookie preferences in the footer.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nizlo-com/privacy/nizlo-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 11 quoted statements, read from Nizlo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- RMM
- Remote Monitoring
- MSP
- Windows
---
