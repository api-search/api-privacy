---
api_specs:
- filename: moxiedocs-com-check-drift-api-openapi.yml
  format: yaml
  label: moxiedocs-com Check Drift API
  slug: moxiedocs-com-check-drift-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxiedocs-com/openapi/moxiedocs-com-check-drift-api-openapi.yml
- filename: moxiedocs-com-docs-api-openapi.yml
  format: yaml
  label: moxiedocs-com Docs API
  slug: moxiedocs-com-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moxiedocs-com/openapi/moxiedocs-com-docs-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and workspace details such as name, email, company, role, and connected repositories.
  - category: financial
    text: Billing and subscription status from Stripe. We do not store full payment card numbers.
  - category: communication
    text: If you connect Slack, the workspace and channel identifiers plus an encrypted bot token and incoming-webhook URL needed to post notifications to the channel you choose.
  - category: behavioral
    text: Contact requests, optional analytics events, logs, and security events needed to operate and improve the service.
  - category: professional
    text: GitHub App installation data, repository metadata, source files, existing documentation, tests, package manifests, and pull request events needed to index and maintain docs.
  deletion:
    route: Email contact@moxiedocs.com or delete from product settings
    text: You can request deletion or export help by contacting contact@moxiedocs.com.
  dpa:
    available: null
    text: Enterprise agreements may include additional security terms, data processing terms, and retention commitments.
    url: null
  purposes:
  - purpose: Authentication and service delivery
    text: To authenticate users, connect GitHub repositories, index codebases, generate searchable documentation, and produce AI-ready context.
  - purpose: Friday Recaps and documentation updates
    text: To create Friday Recaps, suggest documentation updates, and open Cleanup PRs only when authorized by workspace settings.
  - purpose: Support, security and billing
    text: To provide support, answer security questions, prevent abuse, debug service issues, and manage billing.
  - purpose: Product improvement
    text: To improve product quality, reliability, onboarding, and documentation workflows.
  retention:
  - period: null
    scope: Repository indexes, generated docs, logs, and backups
    text: Repository indexes, generated docs, logs, and backups are retained only as long as needed for the product, support, legal, security, or billing purposes.
  - period: null
    scope: Slack credentials
    text: the stored Slack credentials (bot token and webhook URL) are revoked and deleted when you disconnect the integration in Moxie Docs or uninstall the app from your Slack workspace.
  rights:
  - right: access, correct, export, delete, restrict, object
    text: Depending on where you live, you may have rights to access, correct, export, delete, restrict, or object to the processing of your personal data, and to withdraw consent.
  - right: complaint to data protection authority
    text: If you are in the EU, EEA, UK, or Switzerland, you may also lodge a complaint with your local data protection authority.
  role:
    text: we act as a processor handling that data on your behalf and under your instructions
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data or share it for cross-context behavioral advertising
  subprocessors:
    text: The current list, with the purpose and data each one handles, is published on the subprocessors page.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as Standard Contractual Clauses or equivalent mechanisms to protect transferred data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: moxiedocs-com
provenance_date: '2026-11-10'
provider_name: moxiedocs-com
provider_slug: moxiedocs-com
slug: moxiedocs-com-privacy-policy
source_date: '2026-11-10'
source_filename: moxiedocs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://moxiedocs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: moxiedocs-com\naid: moxiedocs-com\nurl: https://moxiedocs.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a processor handling that data on your behalf and under your instructions\ndata_categories:\n- category: identifying\n  text: Account and workspace details such as name, email, company, role, and connected repositories.\n- category: financial\n  text: Billing and subscription status from Stripe. We do not store full payment card numbers.\n- category: communication\n  text: If you connect Slack, the workspace and channel identifiers plus an encrypted bot token and incoming-webhook\n\
  \    URL needed to post notifications to the channel you choose.\n- category: behavioral\n  text: Contact requests, optional analytics events, logs, and security events needed to operate and improve the\n    service.\n- category: professional\n  text: GitHub App installation data, repository metadata, source files, existing documentation, tests, package\n    manifests, and pull request events needed to index and maintain docs.\npurposes:\n- purpose: Authentication and service delivery\n  text: To authenticate users, connect GitHub repositories, index codebases, generate searchable documentation,\n    and produce AI-ready context.\n- purpose: Friday Recaps and documentation updates\n  text: To create Friday Recaps, suggest documentation updates, and open Cleanup PRs only when authorized by workspace\n    settings.\n- purpose: Support, security and billing\n  text: To provide support, answer security questions, prevent abuse, debug service issues, and manage billing.\n- purpose: Product\
  \ improvement\n  text: To improve product quality, reliability, onboarding, and documentation workflows.\nretention:\n- scope: Repository indexes, generated docs, logs, and backups\n  period: null\n  text: Repository indexes, generated docs, logs, and backups are retained only as long as needed for the product,\n    support, legal, security, or billing purposes.\n- scope: Slack credentials\n  period: null\n  text: the stored Slack credentials (bot token and webhook URL) are revoked and deleted when you disconnect the\n    integration in Moxie Docs or uninstall the app from your Slack workspace.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as Standard Contractual Clauses or equivalent mechanisms\n    to protect transferred data.\nsubprocessors:\n  url: null\n  text: The current list, with the purpose and data each one handles, is published on the subprocessors page.\ndpa:\n  available: null\n  url: null\n  text: Enterprise\
  \ agreements may include additional security terms, data processing terms, and retention commitments.\ndeletion:\n  route: Email contact@moxiedocs.com or delete from product settings\n  text: You can request deletion or export help by contacting contact@moxiedocs.com.\nrights:\n- right: access, correct, export, delete, restrict, object\n  text: Depending on where you live, you may have rights to access, correct, export, delete, restrict, or object\n    to the processing of your personal data, and to withdraw consent.\n- right: complaint to data protection authority\n  text: If you are in the EU, EEA, UK, or Switzerland, you may also lodge a complaint with your local data protection\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data or share it for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/moxiedocs-com/privacy/moxiedocs-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from moxiedocs-com's own page on 2026-11-10.
synthetic: false
tags:
- Documentation
- Artificial Intelligence
- GitHub
- Automation
- Developer Tools
---
