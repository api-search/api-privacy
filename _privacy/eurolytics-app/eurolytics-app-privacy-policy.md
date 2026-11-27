---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: location
    text: country & region Derived from IP geolocation, then the IP is discarded (see below)
  - category: device
    text: device type Desktop, mobile, or tablet — parsed from the User-Agent header
  - category: identifying
    text: email Your email address, used for login, verification, and service communications
  - category: contact
    text: name Your display name (optional)
  - category: behavioral
    text: engagement Time on page and scroll depth (sent when the visitor leaves the page)
  deletion:
    route: Contact hello@eurolytics.app to delete your account
    text: 'Account deletion: Contact us at hello@eurolytics.app to delete your account and all associated data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Produce analytics
    text: collects the minimum data needed to produce useful analytics
  - purpose: Account security
    text: IP address Stored for your login sessions only, for security purposes (detecting unauthorized access)
  - purpose: Transactional and notification emails
    text: We send transactional emails (verification codes, password resets, welcome messages) and optional notification emails (weekly reports, traffic alerts) via Brevo.
  residency:
  - region: European Union
    text: All Eurolytics infrastructure is hosted in the European Union with Hetzner, a German cloud provider.
  retention:
  - period: null
    scope: Visitor IP address
    text: The IP is truncated (IPv4 to /24, IPv6 to /48) before any processing, then discarded entirely. Never written to disk.
  - period: 7-day expiry
    scope: Session token
    text: A hashed JWT token stored in an httpOnly cookie (7-day expiry)
  rights:
  - right: Data export
    text: 'Data export: You can export all your analytics data as JSON from the dashboard at any time.'
  - right: Data correction
    text: 'Data correction: You can update your name and email from your account settings, or contact us for assistance.'
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
name: Eurolytics
provenance_date: '2026-11-09'
provider_name: Eurolytics
provider_slug: eurolytics-app
slug: eurolytics-app-privacy-policy
source_date: '2026-11-09'
source_filename: eurolytics-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eurolytics.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Eurolytics\naid: eurolytics-app\nurl: https://eurolytics.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: location\n  text: country & region Derived from IP geolocation, then the IP is discarded (see below)\n- category: device\n  text: device type Desktop, mobile, or tablet — parsed from the User-Agent header\n- category: identifying\n  text: email Your email address, used for login, verification, and service communications\n- category: contact\n  text: name Your display name (optional)\n- category: behavioral\n  text: engagement Time on page and\
  \ scroll depth (sent when the visitor leaves the page)\npurposes:\n- purpose: Produce analytics\n  text: collects the minimum data needed to produce useful analytics\n- purpose: Account security\n  text: IP address Stored for your login sessions only, for security purposes (detecting unauthorized access)\n- purpose: Transactional and notification emails\n  text: We send transactional emails (verification codes, password resets, welcome messages) and optional notification\n    emails (weekly reports, traffic alerts) via Brevo.\nretention:\n- scope: Visitor IP address\n  period: null\n  text: The IP is truncated (IPv4 to /24, IPv6 to /48) before any processing, then discarded entirely. Never written\n    to disk.\n- scope: Session token\n  period: 7-day expiry\n  text: A hashed JWT token stored in an httpOnly cookie (7-day expiry)\nresidency:\n- region: European Union\n  text: All Eurolytics infrastructure is hosted in the European Union with Hetzner, a German cloud provider.\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact hello@eurolytics.app to delete your account\n  text: 'Account deletion: Contact us at hello@eurolytics.app to delete your account and all associated data.'\nrights:\n- right: Data export\n  text: 'Data export: You can export all your analytics data as JSON from the dashboard at any time.'\n- right: Data correction\n  text: 'Data correction: You can update your name and email from your account settings, or contact us for assistance.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eurolytics-app/privacy/eurolytics-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 14 quoted statements, read from Eurolytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Privacy
- GDPR
- Web Analytics
- EU-hosted
---
