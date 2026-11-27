---
api_specs:
- filename: debian-bugs-api-openapi.yml
  format: yaml
  label: Debian Bugs API
  slug: debian-bugs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debian/openapi/debian-bugs-api-openapi.yml
- filename: debian-maintainers-api-openapi.yml
  format: yaml
  label: Debian Maintainers API
  slug: debian-maintainers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debian/openapi/debian-maintainers-api-openapi.yml
- filename: debian-reproducibility-api-openapi.yml
  format: yaml
  label: Debian Reproducibility API
  slug: debian-reproducibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/debian/openapi/debian-reproducibility-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: names and email addresses in emails received by the project
  - category: contact
    text: country and address or phone details
  - category: device
    text: the IP address used for access or email headers
  - category: communication
    text: all Debian mailing lists are publicly archived, as are all interactions with the bug tracking system
  deletion:
    route: log in to the db.debian.org web interface or send signed email to the email interface
    text: can always be removed by logging into the db.debian.org web interface or sending signed email to the email interface
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation and reliability
    text: for the purposes of ensuring service availability and reliability, and to enable debugging and diagnosis of issues when they arise
  - purpose: tracking project member activity
    text: Echelon is a system used by the Project to track member activity
  retention:
  - period: 15 days
    scope: web server logs
    text: it is only stored for 15 days in the case of web server logs
  - period: 10 days
    scope: mail logs
    text: 10 days in the case of mail log
  - period: 4 weeks
    scope: authentication/ssh logs
    text: 4 weeks in the case of authentication/ssh logs
  - period: 24 hours
    scope: raw popcon submissions
    text: Raw submissions are stored for 24 hours
  - period: 20 days
    scope: anonymized popcon submissions
    text: Anonymized submissions are kept for at most 20 days
  - period: indefinitely
    scope: git history
    text: We retain it indefinitely so that we can always verify the copyright and other legal status of contributions
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
name: Debian
provenance_date: '2026-11-09'
provider_name: Debian
provider_slug: debian
slug: debian-privacy-policy
source_date: '2026-11-09'
source_filename: debian-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.debian.org/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Debian\naid: debian\nurl: https://www.debian.org/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: names and email addresses in emails received by the project\n- category: contact\n  text: country and address or phone details\n- category: device\n  text: the IP address used for access or email headers\n- category: communication\n  text: all Debian mailing lists are publicly archived, as are all interactions with the bug tracking system\npurposes:\n- purpose: service operation and reliability\n  text: for the purposes of ensuring\
  \ service availability and reliability, and to enable debugging and diagnosis\n    of issues when they arise\n- purpose: tracking project member activity\n  text: Echelon is a system used by the Project to track member activity\nretention:\n- scope: web server logs\n  period: 15 days\n  text: it is only stored for 15 days in the case of web server logs\n- scope: mail logs\n  period: 10 days\n  text: 10 days in the case of mail log\n- scope: authentication/ssh logs\n  period: 4 weeks\n  text: 4 weeks in the case of authentication/ssh logs\n- scope: raw popcon submissions\n  period: 24 hours\n  text: Raw submissions are stored for 24 hours\n- scope: anonymized popcon submissions\n  period: 20 days\n  text: Anonymized submissions are kept for at most 20 days\n- scope: git history\n  period: indefinitely\n  text: We retain it indefinitely so that we can always verify the copyright and other legal status of contributions\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: log in to the db.debian.org web interface or send signed email to the email interface\n  text: can always be removed by logging into the db.debian.org web interface or sending signed email to the email\n    interface\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/debian/privacy/debian-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 13 quoted statements, read from Debian's own page on 2026-11-09.
synthetic: false
tags:
- Bug Tracker
- Debian
- Linux
- Open Source
- Operating System
- Package Management
- Source Code
---
