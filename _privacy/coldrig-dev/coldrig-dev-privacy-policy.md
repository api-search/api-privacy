---
api_specs:
- filename: coldrig-dev-account-api-openapi.yml
  format: yaml
  label: Coldrig Account API
  slug: coldrig-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-account-api-openapi.yml
- filename: coldrig-dev-bootstrap-api-openapi.yml
  format: yaml
  label: Coldrig Bootstrap API
  slug: coldrig-dev-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-bootstrap-api-openapi.yml
- filename: coldrig-dev-byo-domains-api-openapi.yml
  format: yaml
  label: Coldrig Byo Domains API
  slug: coldrig-dev-byo-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-byo-domains-api-openapi.yml
- filename: coldrig-dev-campaigns-api-openapi.yml
  format: yaml
  label: Coldrig Campaigns API
  slug: coldrig-dev-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-campaigns-api-openapi.yml
- filename: coldrig-dev-compliance-api-openapi.yml
  format: yaml
  label: Coldrig Compliance API
  slug: coldrig-dev-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-compliance-api-openapi.yml
- filename: coldrig-dev-dashboard-api-openapi.yml
  format: yaml
  label: Coldrig Dashboard API
  slug: coldrig-dev-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-dashboard-api-openapi.yml
- filename: coldrig-dev-inbox-api-openapi.yml
  format: yaml
  label: Coldrig Inbox API
  slug: coldrig-dev-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-inbox-api-openapi.yml
- filename: coldrig-dev-infrastructure-api-openapi.yml
  format: yaml
  label: Coldrig Infrastructure API
  slug: coldrig-dev-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-infrastructure-api-openapi.yml
- filename: coldrig-dev-leads-api-openapi.yml
  format: yaml
  label: Coldrig Leads API
  slug: coldrig-dev-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-leads-api-openapi.yml
- filename: coldrig-dev-messages-api-openapi.yml
  format: yaml
  label: Coldrig Messages API
  slug: coldrig-dev-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-messages-api-openapi.yml
- filename: coldrig-dev-sandbox-api-openapi.yml
  format: yaml
  label: Coldrig Sandbox API
  slug: coldrig-dev-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-sandbox-api-openapi.yml
- filename: coldrig-dev-webhooks-api-openapi.yml
  format: yaml
  label: Coldrig Webhooks API
  slug: coldrig-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coldrig-dev/openapi/coldrig-dev-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: the email address you submit, and the timestamp/source of submission
  - category: identifying
    text: your name or business name, your email address
  - category: financial
    text: billing information processed by Stripe (we do not store full payment card numbers ourselves)
  - category: location
    text: the physical postal address and sender identity you provide for use in your own outbound email footers
  - category: behavioral
    text: 'Operational data: API usage, tool calls, and platform logs needed to operate, secure, meter, and bill the Service.'
  - category: device
    text: 'Site analytics: we load no third-party analytics or ad trackers on this site as of this writing'
  - category: contact
    source: https://coldrig.dev/dpa
    text: personal data within lead lists and recipient data ("Customer Data")
  deletion:
    route: email privacy@coldrig.dev
    text: You may request deletion — see Contact below.
  dpa:
    available: true
    text: The full Data Processing Addendum (DPA) — roles, subprocessors, security, and what happens to your data on termination — is at coldrig.dev/dpa and applies automatically to every account
    url: coldrig.dev/dpa
  purposes:
  - purpose: operate the Service
    text: 'To operate the Service: setting up domains and mailboxes, sending your campaigns, handling replies, billing, and support.'
  - purpose: abuse monitoring
    text: To monitor for abuse and enforce the Acceptable Use Policy
  - purpose: operate cold-outreach infrastructure
    source: https://coldrig.dev/dpa
    text: hosting and processing of Customer Data to operate cold-outreach infrastructure on your behalf
  - purpose: deliver the Service you configure
    source: https://coldrig.dev/dpa
    text: EpiphanyMade processes Customer Data solely to deliver the Service you configure
  residency:
  - region: US
    source: https://coldrig.dev/dpa
    text: Customer Data is processed and stored in EpiphanyMade's and its subprocessors' US infrastructure.
  retention:
  - period: null
    scope: account and operational data
    text: We retain account and operational data for as long as your account is active plus a reasonable period for legal, tax, and dispute-handling purposes.
  - period: 90 days
    scope: free test-mode account never live
    text: A free test-mode account that has never gone live may be removed once it has gone unused for at least 90 days.
  - period: null
    scope: product-updates signup emails
    text: Product-updates signup emails are retained until you unsubscribe or are converted to a customer or removed.
  - period: indefinitely
    scope: suppression / opt-out list
    source: https://coldrig.dev/dpa
    text: it is retained indefinitely and is never deleted, including after termination
  - period: active account plus a reasonable period for legal, tax, and dispute-handling purposes
    scope: lead lists, campaign content and other Customer Data
    source: https://coldrig.dev/dpa
    text: retained per the standard window in the Privacy Policy §7 (active account plus a reasonable period for legal, tax, and dispute-handling purposes)
  rights:
  - right: access
    text: you may have rights to access, correct, delete, or export your personal information
  - right: opt out
    text: and to opt out of certain processing
  - right: CCPA know/delete/correct
    text: (a) know what personal information we have collected about you and why; (b) delete personal information we hold about you, subject to certain exceptions; (c) correct inaccurate personal information
  - right: access, correction, deletion requests forwarded to customer
    source: https://coldrig.dev/dpa
    text: If EpiphanyMade receives a request from one of your recipients to access, correct, or delete their data, we will forward it to you promptly
  role:
    text: we process that data only to deliver the outreach you configure
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'We share data with the vendors and processors necessary to run the Service: Stripe (billing), our domain registrar and mailbox/warmup vendor(s)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coldrig
provenance_date: '2026-11-09'
provider_name: Coldrig
provider_slug: coldrig-dev
slug: coldrig-dev-privacy-policy
source_date: '2026-11-09'
source_filename: coldrig-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coldrig.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coldrig\naid: coldrig-dev\nurl: https://coldrig.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://coldrig.dev/dpa\n  - https://coldrig.dev/privacy\nrole:\n  value: both\n  text: we process that data only to deliver the outreach you configure\ndata_categories:\n- category: contact\n  text: the email address you submit, and the timestamp/source of submission\n- category: identifying\n  text: your name or business name, your email address\n- category: financial\n  text: billing information processed by Stripe (we do not store full payment card numbers ourselves)\n- category: location\n  text: the\
  \ physical postal address and sender identity you provide for use in your own outbound email footers\n- category: behavioral\n  text: 'Operational data: API usage, tool calls, and platform logs needed to operate, secure, meter, and bill the\n    Service.'\n- category: device\n  text: 'Site analytics: we load no third-party analytics or ad trackers on this site as of this writing'\n- category: contact\n  text: personal data within lead lists and recipient data (\"Customer Data\")\n  source: https://coldrig.dev/dpa\npurposes:\n- purpose: operate the Service\n  text: 'To operate the Service: setting up domains and mailboxes, sending your campaigns, handling replies, billing,\n    and support.'\n- purpose: abuse monitoring\n  text: To monitor for abuse and enforce the Acceptable Use Policy\n- purpose: operate cold-outreach infrastructure\n  text: hosting and processing of Customer Data to operate cold-outreach infrastructure on your behalf\n  source: https://coldrig.dev/dpa\n- purpose: deliver\
  \ the Service you configure\n  text: EpiphanyMade processes Customer Data solely to deliver the Service you configure\n  source: https://coldrig.dev/dpa\nretention:\n- scope: account and operational data\n  period: null\n  text: We retain account and operational data for as long as your account is active plus a reasonable period for\n    legal, tax, and dispute-handling purposes.\n- scope: free test-mode account never live\n  period: 90 days\n  text: A free test-mode account that has never gone live may be removed once it has gone unused for at least 90\n    days.\n- scope: product-updates signup emails\n  period: null\n  text: Product-updates signup emails are retained until you unsubscribe or are converted to a customer or removed.\n- scope: suppression / opt-out list\n  period: indefinitely\n  text: it is retained indefinitely and is never deleted, including after termination\n  source: https://coldrig.dev/dpa\n- scope: lead lists, campaign content and other Customer Data\n  period:\
  \ active account plus a reasonable period for legal, tax, and dispute-handling purposes\n  text: retained per the standard window in the Privacy Policy §7 (active account plus a reasonable period for legal,\n    tax, and dispute-handling purposes)\n  source: https://coldrig.dev/dpa\nresidency:\n- region: US\n  text: Customer Data is processed and stored in EpiphanyMade's and its subprocessors' US infrastructure.\n  source: https://coldrig.dev/dpa\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data with the vendors and processors necessary to run the Service: Stripe (billing), our domain\n    registrar and mailbox/warmup vendor(s)'\ndpa:\n  available: true\n  url: coldrig.dev/dpa\n  text: The full Data Processing Addendum (DPA) — roles, subprocessors, security, and what happens to your data\n    on termination — is at coldrig.dev/dpa and applies automatically to every account\ndeletion:\n  route: email privacy@coldrig.dev\n  text: You may request deletion — see Contact below.\n\
  rights:\n- right: access\n  text: you may have rights to access, correct, delete, or export your personal information\n- right: opt out\n  text: and to opt out of certain processing\n- right: CCPA know/delete/correct\n  text: (a) know what personal information we have collected about you and why; (b) delete personal information\n    we hold about you, subject to certain exceptions; (c) correct inaccurate personal information\n- right: access, correction, deletion requests forwarded to customer\n  text: If EpiphanyMade receives a request from one of your recipients to access, correct, or delete their data,\n    we will forward it to you promptly\n  source: https://coldrig.dev/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/coldrig-dev/privacy/coldrig-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Coldrig's own page on 2026-11-09.
synthetic: false
tags:
- Cold Email
- Outreach
- AI Agents
- Email Infrastructure
---
