---
api_specs:
- filename: dnsdoctor-dev-domains-api-openapi.yml
  format: yaml
  label: DNS Doctor Domains API
  slug: dnsdoctor-dev-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dnsdoctor-dev/openapi/dnsdoctor-dev-domains-api-openapi.yml
- filename: dnsdoctor-dev-monitoring-api-openapi.yml
  format: yaml
  label: DNS Doctor Monitoring API
  slug: dnsdoctor-dev-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dnsdoctor-dev/openapi/dnsdoctor-dev-monitoring-api-openapi.yml
- filename: dnsdoctor-dev-scan-api-openapi.yml
  format: yaml
  label: DNS Doctor Scan API
  slug: dnsdoctor-dev-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dnsdoctor-dev/openapi/dnsdoctor-dev-scan-api-openapi.yml
- filename: dnsdoctor-dev-tools-api-openapi.yml
  format: yaml
  label: DNS Doctor Tools API
  slug: dnsdoctor-dev-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dnsdoctor-dev/openapi/dnsdoctor-dev-tools-api-openapi.yml
- filename: dnsdoctor-dev-watch-api-openapi.yml
  format: yaml
  label: DNS Doctor Watch API
  slug: dnsdoctor-dev-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dnsdoctor-dev/openapi/dnsdoctor-dev-watch-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: For Monitor, we store your email address, the domains you choose to monitor, and the DMARC reports mailbox providers send about your domains.
  - category: behavioral
    text: privacy-respecting usage analytics, with IP addresses truncated so they can't identify you
  - category: communication
    text: we keep only the verdicts and selected header details of the one message you send (never its body or attachments)
  - category: device
    text: It runs without a visible challenge and processes limited device and network signals to tell humans from automated traffic
  deletion:
    route: close your account
    text: If you close your account we delete your personal data, including its email test results, keeping only what law or tax rules require.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the diagnosis and send sign-in and alert emails
    text: To run the diagnosis, send you magic-link sign-in emails and the alerts you ask for, and to understand which pages are useful.
  - purpose: count ChatGPT conversation steps and users
    text: so we can count how many steps a conversation takes
  retention:
  - period: 12 months
    scope: Monitor reports
    text: Monitor keeps your reports for 12 months.
  - period: 30 days
    scope: ChatGPT conversation code
    text: We clear that code after 30 days.
  - period: 24 hours
    scope: Email test results
    text: Email test results stop being readable 24 hours after the test started
  - period: 14 days
    scope: Encrypted nightly backups
    text: Our encrypted nightly backups roll over after 14 days.
  rights:
  - right: access, correct, export, delete, object
    text: Under the GDPR and similar laws you can access, correct, export, or delete your personal data, and object to processing.
  - right: complain to data-protection authority
    text: You may also complain to your local data-protection authority.
  role:
    text: We're the data controller for dnsdoctor.dev
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We collect as little as we can and never sell your data.
  subprocessors:
    text: 'A short list of processors that make the service work:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DNS Doctor
provenance_date: '2026-11-09'
provider_name: DNS Doctor
provider_slug: dnsdoctor-dev
slug: dnsdoctor-dev-privacy-policy
source_date: '2026-11-09'
source_filename: dnsdoctor-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dnsdoctor.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DNS Doctor\naid: dnsdoctor-dev\nurl: https://dnsdoctor.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We're the data controller for dnsdoctor.dev\ndata_categories:\n- category: contact\n  text: For Monitor, we store your email address, the domains you choose to monitor, and the DMARC reports mailbox\n    providers send about your domains.\n- category: behavioral\n  text: privacy-respecting usage analytics, with IP addresses truncated so they can't identify you\n- category: communication\n  text: we keep only the verdicts and selected header details of the one message you send (never\
  \ its body or attachments)\n- category: device\n  text: It runs without a visible challenge and processes limited device and network signals to tell humans from\n    automated traffic\npurposes:\n- purpose: run the diagnosis and send sign-in and alert emails\n  text: To run the diagnosis, send you magic-link sign-in emails and the alerts you ask for, and to understand which\n    pages are useful.\n- purpose: count ChatGPT conversation steps and users\n  text: so we can count how many steps a conversation takes\nretention:\n- scope: Monitor reports\n  period: 12 months\n  text: Monitor keeps your reports for 12 months.\n- scope: ChatGPT conversation code\n  period: 30 days\n  text: We clear that code after 30 days.\n- scope: Email test results\n  period: 24 hours\n  text: Email test results stop being readable 24 hours after the test started\n- scope: Encrypted nightly backups\n  period: 14 days\n  text: Our encrypted nightly backups roll over after 14 days.\nresidency: []\ntransfers: []\n\
  subprocessors:\n  url: null\n  text: 'A short list of processors that make the service work:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: close your account\n  text: If you close your account we delete your personal data, including its email test results, keeping only what\n    law or tax rules require.\nrights:\n- right: access, correct, export, delete, object\n  text: Under the GDPR and similar laws you can access, correct, export, or delete your personal data, and object\n    to processing.\n- right: complain to data-protection authority\n  text: You may also complain to your local data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We collect as little as we can and never sell your data.\n"
source_yaml_url: https://artifacts.apis.io/dnsdoctor-dev/privacy/dnsdoctor-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from DNS Doctor's own page on 2026-11-09.
synthetic: false
tags:
- DNS
- DNS Tools
- Email Authentication
- Web Application
---
