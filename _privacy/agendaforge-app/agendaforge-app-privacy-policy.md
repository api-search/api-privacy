---
api_specs:
- filename: agendaforge-app-connection-api-openapi.yml
  format: yaml
  label: agendaforge-app Connection API
  slug: agendaforge-app-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-connection-api-openapi.yml
- filename: agendaforge-app-jobs-api-openapi.yml
  format: yaml
  label: agendaforge-app Jobs API
  slug: agendaforge-app-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-jobs-api-openapi.yml
- filename: agendaforge-app-records-api-openapi.yml
  format: yaml
  label: agendaforge-app Records API
  slug: agendaforge-app-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-records-api-openapi.yml
- filename: agendaforge-app-webhooks-api-openapi.yml
  format: yaml
  label: agendaforge-app Webhooks API
  slug: agendaforge-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agendaforge-app/openapi/agendaforge-app-webhooks-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email address, organization name, and authentication identifiers managed through our identity provider.'
  - category: contact
    text: 'Demo form responses: when you submit a demo form on our website (on the forms page and the form template pages), we collect what you enter, including your name and email address'
  - category: financial
    text: 'Payment information: billing details processed by our payment processor (Stripe). We do not store full card numbers on our servers.'
  - category: device
    text: 'Device and log data: IP address, browser type, device type, and timestamps.'
  - category: behavioral
    text: 'Usage data: pages viewed, features used, and actions taken within the Service.'
  - category: communication
    text: 'Communications: messages you send to us for support, sales, or feedback.'
  deletion:
    route: Request deletion by contacting us
    text: We will delete or anonymize your information upon request or when it is no longer required, unless we are legally obligated to retain it.
  dpa:
    available: null
    text: Our GDPR page describes the data processing agreement, the sub-processor list, and the EU data residency option.
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, maintain, and improve the Service.
  - purpose: Authenticate and secure accounts
    text: Authenticate users and secure accounts.
  - purpose: Process transactions
    text: Process transactions and send related billing information.
  - purpose: Power AI features on event content
    text: Power AI features that operate on your event content to assist your workflows.
  - purpose: Support and communication
    text: Respond to support requests and communicate with you about the Service.
  - purpose: Security and abuse monitoring
    text: Monitor usage, detect abuse, and protect the integrity and security of the Service.
  residency:
  - region: United States
    text: By default, event records, sign-in data, and AI processing are in the United States
  - region: European Union
    text: website analytics are in the European Union.
  - region: Singapore
    text: email is sent through Amazon Web Services in Singapore
  retention:
  - period: null
    scope: Account and event information
    text: We retain your information for as long as your account is active or as needed to provide the Service.
  - period: null
    scope: Google OAuth tokens
    text: We retain tokens only while the integration is connected.
  rights:
  - right: Access, update, correct account information
    text: Access, update, or correct your account information within the app.
  - right: Deletion, correction, access on request
    text: Request access to, correction of, or deletion of your personal data by contacting us.
  - right: GDPR rights
    text: access, rectification, erasure, restriction, portability, and objection, and the right to complain to your supervisory authority.
  - right: Opt out of non-essential communications
    text: Opt out of non-essential communications.
  - right: CCPA rights
    text: If you are in California, the CCPA gives you comparable rights.
  role:
    text: Where an event organizer is the controller of your data, we forward the request to them and help them respond.
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Our GDPR page describes the data processing agreement, the sub-processor list, and the EU data residency option.
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers out of the EU, the UK and Switzerland rest on standard contractual clauses or, where the provider holds it, the EU-US Data Privacy Framework certification.
  - mechanism: DPF
    text: or, where the provider holds it, the EU-US Data Privacy Framework certification.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agendaforge-app
provenance_date: '2026-11-09'
provider_name: agendaforge-app
provider_slug: agendaforge-app
slug: agendaforge-app-privacy-policy
source_date: '2026-11-09'
source_filename: agendaforge-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agendaforge.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agendaforge-app\naid: agendaforge-app\nurl: https://agendaforge.app/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: Where an event organizer is the controller of your data, we forward the request to them and help them respond.\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email address, organization name, and authentication identifiers managed through\n    our identity provider.'\n- category: contact\n  text: 'Demo form responses: when you submit a demo form on our website (on the forms page and the form template\n    pages), we collect what you\
  \ enter, including your name and email address'\n- category: financial\n  text: 'Payment information: billing details processed by our payment processor (Stripe). We do not store full\n    card numbers on our servers.'\n- category: device\n  text: 'Device and log data: IP address, browser type, device type, and timestamps.'\n- category: behavioral\n  text: 'Usage data: pages viewed, features used, and actions taken within the Service.'\n- category: communication\n  text: 'Communications: messages you send to us for support, sales, or feedback.'\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, maintain, and improve the Service.\n- purpose: Authenticate and secure accounts\n  text: Authenticate users and secure accounts.\n- purpose: Process transactions\n  text: Process transactions and send related billing information.\n- purpose: Power AI features on event content\n  text: Power AI features that operate on your event content to assist your workflows.\n\
  - purpose: Support and communication\n  text: Respond to support requests and communicate with you about the Service.\n- purpose: Security and abuse monitoring\n  text: Monitor usage, detect abuse, and protect the integrity and security of the Service.\nretention:\n- scope: Account and event information\n  period: null\n  text: We retain your information for as long as your account is active or as needed to provide the Service.\n- scope: Google OAuth tokens\n  period: null\n  text: We retain tokens only while the integration is connected.\nresidency:\n- region: United States\n  text: By default, event records, sign-in data, and AI processing are in the United States\n- region: European Union\n  text: website analytics are in the European Union.\n- region: Singapore\n  text: email is sent through Amazon Web Services in Singapore\ntransfers:\n- mechanism: SCC\n  text: Transfers out of the EU, the UK and Switzerland rest on standard contractual clauses or, where the provider\n    holds it,\
  \ the EU-US Data Privacy Framework certification.\n- mechanism: DPF\n  text: or, where the provider holds it, the EU-US Data Privacy Framework certification.\nsubprocessors:\n  url: null\n  text: Our GDPR page describes the data processing agreement, the sub-processor list, and the EU data residency\n    option.\ndpa:\n  available: null\n  url: null\n  text: Our GDPR page describes the data processing agreement, the sub-processor list, and the EU data residency\n    option.\ndeletion:\n  route: Request deletion by contacting us\n  text: We will delete or anonymize your information upon request or when it is no longer required, unless we are\n    legally obligated to retain it.\nrights:\n- right: Access, update, correct account information\n  text: Access, update, or correct your account information within the app.\n- right: Deletion, correction, access on request\n  text: Request access to, correction of, or deletion of your personal data by contacting us.\n- right: GDPR rights\n  text:\
  \ access, rectification, erasure, restriction, portability, and objection, and the right to complain to your\n    supervisory authority.\n- right: Opt out of non-essential communications\n  text: Opt out of non-essential communications.\n- right: CCPA rights\n  text: If you are in California, the CCPA gives you comparable rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/agendaforge-app/privacy/agendaforge-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from agendaforge-app's own page on 2026-11-09.
synthetic: false
tags:
- Event Management
- Software-as-a-Service
- AI-native
- Conferences
- Software
---
