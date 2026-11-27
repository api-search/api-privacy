---
api_specs:
- filename: e2a-dev-api-openapi.yml
  format: yaml
  label: e2a API API
  slug: e2a-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2a-dev/openapi/_original/e2a-dev-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and your name, as provided by the sign-in provider you use (Google, or a Token Canopy account), plus the date you signed up.
  - category: communication
    text: 'The full content of mail your agents send and receive: envelope and header addresses (from, to, cc, bcc), subject, plain-text and HTML bodies, attachments, and the threading identifiers'
  - category: device
    text: Request logs (method, status, latency, source IP — never the URL path, which can embed addresses) for operating and securing the service.
  - category: behavioral
    text: 'Website analytics: anonymous public-page records remain in our self-hosted analytics database until we delete them.'
  - category: financial
    text: 'Billing records: retained as long as tax and accounting obligations require, independently of account deletion.'
  deletion:
    route: DELETE /v1/account?confirm=DELETE, or DELETE with permanent=true; or email
    text: Export and deletion are self-serve API calls, not a support ticket
  dpa:
    available: true
    text: Business customers who need a signed Data Processing Agreement can request one at the contact below.
    url: https://e2a.dev/privacy
  purposes:
  - purpose: Storing and serving mail
    text: We store the email your agents send and receive — headers, bodies, and attachments — because storing and serving it back to you is the product.
  - purpose: Abuse prevention
    text: Abuse prevention, including the automated scoring described under Abuse detection , inbound screening, security logging, measuring aggregate public-site traffic, and keeping the service running
  - purpose: Billing and quotas
    text: Per-message usage counters, used to enforce plan quotas and to bill paid plans.
  residency:
  - region: United States
    text: The application and its database run on Google Cloud infrastructure in the United States ( us-central1 )
  retention:
  - period: null
    scope: Messages
    text: 'Messages: retained for as long as your account exists, so your agents can read their own history.'
  - period: 30 days
    scope: Trash
    text: 'Trash: deleting an agent or a message moves it to the trash, where it stays restorable for 30 days before it is purged permanently.'
  - period: about 30 days
    scope: Request and application logs
    text: 'Request and application logs: about 30 days.'
  - period: 30 days
    scope: Database backups
    text: 'Database backups: daily backups retained for 30 days, with point-in-time recovery for the most recent 7 days.'
  - period: 90 days
    scope: Abuse signals
    text: Signals are kept for 90 days, scores for one year, and a confirmed determination of abuse — never message content — for two years
  rights:
  - right: access
    text: You may exercise the rights of access, rectification, erasure, restriction, portability, and objection
  - right: erasure
    text: erasure through the deletion endpoint — immediately with permanent=true , otherwise when the 30-day trash window ends.
  - right: portability
    text: Export. GET /v1/account/export returns a single machine-readable JSON document
  - right: objection
    text: contact us below to object or ask about deletion
  role:
    text: Mnexa, Inc. is the data controller for your e2a account.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not run advertising.
  subprocessors:
    text: Sub-processors These are the third parties that process data on our behalf
    url: https://e2a.dev/privacy
  transfers:
  - mechanism: DPF
    text: the transfer relies on the EU-U.S. / UK Data Privacy Framework certifications of our sub-processors and/or the European Commission's Standard Contractual Clauses.
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: e2a-dev
provenance_date: '2026-11-09'
provider_name: e2a-dev
provider_slug: e2a-dev
slug: e2a-dev-privacy-policy
source_date: '2026-11-09'
source_filename: e2a-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://e2a.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: e2a-dev\naid: e2a-dev\nurl: https://e2a.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Mnexa, Inc. is the data controller for your e2a account.\ndata_categories:\n- category: identifying\n  text: Your email address and your name, as provided by the sign-in provider you use (Google, or a Token Canopy\n    account), plus the date you signed up.\n- category: communication\n  text: 'The full content of mail your agents send and receive: envelope and header addresses (from, to, cc, bcc),\n    subject, plain-text and HTML bodies, attachments, and the threading identifiers'\n- category:\
  \ device\n  text: Request logs (method, status, latency, source IP — never the URL path, which can embed addresses) for operating\n    and securing the service.\n- category: behavioral\n  text: 'Website analytics: anonymous public-page records remain in our self-hosted analytics database until we\n    delete them.'\n- category: financial\n  text: 'Billing records: retained as long as tax and accounting obligations require, independently of account deletion.'\npurposes:\n- purpose: Storing and serving mail\n  text: We store the email your agents send and receive — headers, bodies, and attachments — because storing and\n    serving it back to you is the product.\n- purpose: Abuse prevention\n  text: Abuse prevention, including the automated scoring described under Abuse detection , inbound screening, security\n    logging, measuring aggregate public-site traffic, and keeping the service running\n- purpose: Billing and quotas\n  text: Per-message usage counters, used to enforce plan quotas\
  \ and to bill paid plans.\nretention:\n- scope: Messages\n  period: null\n  text: 'Messages: retained for as long as your account exists, so your agents can read their own history.'\n- scope: Trash\n  period: 30 days\n  text: 'Trash: deleting an agent or a message moves it to the trash, where it stays restorable for 30 days before\n    it is purged permanently.'\n- scope: Request and application logs\n  period: about 30 days\n  text: 'Request and application logs: about 30 days.'\n- scope: Database backups\n  period: 30 days\n  text: 'Database backups: daily backups retained for 30 days, with point-in-time recovery for the most recent 7\n    days.'\n- scope: Abuse signals\n  period: 90 days\n  text: Signals are kept for 90 days, scores for one year, and a confirmed determination of abuse — never message\n    content — for two years\nresidency:\n- region: United States\n  text: The application and its database run on Google Cloud infrastructure in the United States ( us-central1 )\ntransfers:\n\
  - mechanism: DPF\n  text: the transfer relies on the EU-U.S. / UK Data Privacy Framework certifications of our sub-processors and/or\n    the European Commission's Standard Contractual Clauses.\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses.\nsubprocessors:\n  url: https://e2a.dev/privacy\n  text: Sub-processors These are the third parties that process data on our behalf\ndpa:\n  available: true\n  url: https://e2a.dev/privacy\n  text: Business customers who need a signed Data Processing Agreement can request one at the contact below.\ndeletion:\n  route: DELETE /v1/account?confirm=DELETE, or DELETE with permanent=true; or email\n  text: Export and deletion are self-serve API calls, not a support ticket\nrights:\n- right: access\n  text: You may exercise the rights of access, rectification, erasure, restriction, portability, and objection\n- right: erasure\n  text: erasure through the deletion endpoint — immediately with permanent=true , otherwise when\
  \ the 30-day trash\n    window ends.\n- right: portability\n  text: Export. GET /v1/account/export returns a single machine-readable JSON document\n- right: objection\n  text: contact us below to object or ask about deletion\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not run advertising.\n"
source_yaml_url: https://artifacts.apis.io/e2a-dev/privacy/e2a-dev-privacy-policy.yml
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
summary_line: 25 quoted statements, read from e2a-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Open Source
- Artificial Intelligence
---
