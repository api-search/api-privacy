---
api_specs:
- filename: formfeed-account-api-openapi.yml
  format: yaml
  label: Formfeed Account API
  slug: formfeed-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-account-api-openapi.yml
- filename: formfeed-brand-api-openapi.yml
  format: yaml
  label: Formfeed Brand API
  slug: formfeed-brand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-brand-api-openapi.yml
- filename: formfeed-compat-api-openapi.yml
  format: yaml
  label: Formfeed Compat API
  slug: formfeed-compat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-compat-api-openapi.yml
- filename: formfeed-files-api-openapi.yml
  format: yaml
  label: Formfeed Files API
  slug: formfeed-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-files-api-openapi.yml
- filename: formfeed-partials-api-openapi.yml
  format: yaml
  label: Formfeed Partials API
  slug: formfeed-partials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-partials-api-openapi.yml
- filename: formfeed-pdf-tools-api-openapi.yml
  format: yaml
  label: Formfeed PDF tools API
  slug: formfeed-pdf-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-pdf-tools-api-openapi.yml
- filename: formfeed-renders-api-openapi.yml
  format: yaml
  label: Formfeed Renders API
  slug: formfeed-renders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-renders-api-openapi.yml
- filename: formfeed-templates-api-openapi.yml
  format: yaml
  label: Formfeed Templates API
  slug: formfeed-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-templates-api-openapi.yml
- filename: formfeed-webhooks-api-openapi.yml
  format: yaml
  label: Formfeed Webhooks API
  slug: formfeed-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/formfeed/openapi/formfeed-webhooks-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: sends us your email address, your name, the identifier of your account there
  - category: device
    text: it records the page, the referring website, browser, operating system, device type, screen size, language and the country derived from your IP address
  - category: contact
    text: we keep the email address, language, time and the page they came from
  - category: identifying
    source: https://formfeed.dev/legal/dpa
    text: 'Any personal data the customer includes in template data: names, addresses, contract and invoice details, identifiers.'
  - category: other
    source: https://formfeed.dev/legal/dpa
    text: the account data of the customer's users
  - category: financial
    source: https://formfeed.dev/legal/subprocessors
    text: Stripe sees billing contact and payment data, never document data.
  deletion:
    route: email hello@formfeed.dev
    text: to have them removed from an organisation that already exists, write to hello@formfeed.dev.
  dpa:
    available: true
    text: Document data you send to the API is processed on your behalf under our data processing agreement (formfeed.dev/legal/dpa).
    url: https://formfeed.dev/legal/dpa
  purposes:
  - purpose: usage statistics
    text: we use the statistics only to see which pages are read and which lead to sign-ups
  - purpose: error reporting
    text: Errors in the app, the API and the render servers are reported to Sentry
  - purpose: document rendering
    source: https://formfeed.dev/legal/dpa
    text: Rendering PDF and image documents from templates and customer data
  - purpose: service operation
    source: https://formfeed.dev/legal/dpa
    text: operating the service (logs, metering, support)
  - purpose: accounts, templates, render metadata, fonts
    source: https://formfeed.dev/legal/subprocessors
    text: 'Purpose: accounts, templates, render metadata, fonts'
  - purpose: sign-in links, invitations, quota and billing notices
    source: https://formfeed.dev/legal/subprocessors
    text: 'Purpose: sign-in links, invitations, quota and billing notices, and tips and product news for those who subscribed.'
  - purpose: subscriptions, invoices, tax
    source: https://formfeed.dev/legal/subprocessors
    text: 'Purpose: subscriptions, invoices, tax.'
  residency:
  - region: EU
    text: Accounts, templates and rendered documents are stored and rendered in the EU
  - region: EU
    source: https://formfeed.dev/legal/dpa
    text: EU-only processing
  - region: Frankfurt
    source: https://formfeed.dev/legal/subprocessors
    text: the project is hosted in Frankfurt (AWS eu-central-1)
  - region: EU
    source: https://formfeed.dev/legal/subprocessors
    text: Rendered documents and uploaded files are stored in the EU only, unless a workspace configures its own storage destination (bring your own storage)
  retention:
  - period: 30 days after you delete the organisation
    scope: account data of an organisation
    text: Account data, including the campaign values and click id of an organisation, is deleted 30 days after you delete the organisation.
  - period: 14 September 2027
    scope: waitlist entries
    text: delete these entries by 14 September 2027 at the latest, or earlier when you ask us to.
  - period: configured retention period
    scope: rendered documents
    source: https://formfeed.dev/legal/dpa
    text: Rendered documents are deleted at the end of the configured retention period.
  - period: 30 days
    scope: organisation data after deletion
    source: https://formfeed.dev/legal/dpa
    text: When the organisation is deleted, all data is removed within 30 days, backups within a further 30 days.
  - period: null
    scope: render servers (Fly.io)
    source: https://formfeed.dev/legal/subprocessors
    text: no persistent storage of customer data
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: You have the rights of access, rectification, erasure, restriction, portability and objection (Art. 15–21 GDPR)
  - right: complaint to supervisory authority
    text: the right to lodge a complaint with a supervisory authority
  - right: access, export and deletion assistance
    source: https://formfeed.dev/legal/dpa
    text: We forward requests from data subjects to the customer without undue delay and assist with technical means (export, deletion of specific renders or data).
  role:
    text: is the controller for this website and the Formfeed service.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Every service provider involved is listed at formfeed.dev/legal/subprocessors.
    url: https://formfeed.dev/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: The emails are sent through Resend, Inc. (USA, EU standard contractual clauses).
  - mechanism: SCC
    source: https://formfeed.dev/legal/subprocessors
    text: The providers above are engaged under GDPR-compliant agreements with standard contractual clauses where a transfer of account or billing data occurs.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Formfeed
provenance_date: '2026-11-09'
provider_name: Formfeed
provider_slug: formfeed
slug: formfeed-privacy-policy
source_date: '2026-11-09'
source_filename: formfeed-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://formfeed.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Formfeed\naid: formfeed\nurl: https://formfeed.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://formfeed.dev/legal/dpa\n  - https://formfeed.dev/legal/privacy\n  - https://formfeed.dev/legal/subprocessors\nrole:\n  value: controller\n  text: is the controller for this website and the Formfeed service.\ndata_categories:\n- category: identifying\n  text: sends us your email address, your name, the identifier of your account there\n- category: device\n  text: it records the page, the referring website, browser, operating system, device type, screen size, language\n    and the country derived\
  \ from your IP address\n- category: contact\n  text: we keep the email address, language, time and the page they came from\n- category: identifying\n  text: 'Any personal data the customer includes in template data: names, addresses, contract and invoice details,\n    identifiers.'\n  source: https://formfeed.dev/legal/dpa\n- category: other\n  text: the account data of the customer's users\n  source: https://formfeed.dev/legal/dpa\n- category: financial\n  text: Stripe sees billing contact and payment data, never document data.\n  source: https://formfeed.dev/legal/subprocessors\npurposes:\n- purpose: usage statistics\n  text: we use the statistics only to see which pages are read and which lead to sign-ups\n- purpose: error reporting\n  text: Errors in the app, the API and the render servers are reported to Sentry\n- purpose: document rendering\n  text: Rendering PDF and image documents from templates and customer data\n  source: https://formfeed.dev/legal/dpa\n- purpose: service operation\n\
  \  text: operating the service (logs, metering, support)\n  source: https://formfeed.dev/legal/dpa\n- purpose: accounts, templates, render metadata, fonts\n  text: 'Purpose: accounts, templates, render metadata, fonts'\n  source: https://formfeed.dev/legal/subprocessors\n- purpose: sign-in links, invitations, quota and billing notices\n  text: 'Purpose: sign-in links, invitations, quota and billing notices, and tips and product news for those who\n    subscribed.'\n  source: https://formfeed.dev/legal/subprocessors\n- purpose: subscriptions, invoices, tax\n  text: 'Purpose: subscriptions, invoices, tax.'\n  source: https://formfeed.dev/legal/subprocessors\nretention:\n- scope: account data of an organisation\n  period: 30 days after you delete the organisation\n  text: Account data, including the campaign values and click id of an organisation, is deleted 30 days after you\n    delete the organisation.\n- scope: waitlist entries\n  period: 14 September 2027\n  text: delete these entries\
  \ by 14 September 2027 at the latest, or earlier when you ask us to.\n- scope: rendered documents\n  period: configured retention period\n  text: Rendered documents are deleted at the end of the configured retention period.\n  source: https://formfeed.dev/legal/dpa\n- scope: organisation data after deletion\n  period: 30 days\n  text: When the organisation is deleted, all data is removed within 30 days, backups within a further 30 days.\n  source: https://formfeed.dev/legal/dpa\n- scope: render servers (Fly.io)\n  period: null\n  text: no persistent storage of customer data\n  source: https://formfeed.dev/legal/subprocessors\nresidency:\n- region: EU\n  text: Accounts, templates and rendered documents are stored and rendered in the EU\n- region: EU\n  text: EU-only processing\n  source: https://formfeed.dev/legal/dpa\n- region: Frankfurt\n  text: the project is hosted in Frankfurt (AWS eu-central-1)\n  source: https://formfeed.dev/legal/subprocessors\n- region: EU\n  text: Rendered documents\
  \ and uploaded files are stored in the EU only, unless a workspace configures its own storage\n    destination (bring your own storage)\n  source: https://formfeed.dev/legal/subprocessors\ntransfers:\n- mechanism: SCC\n  text: The emails are sent through Resend, Inc. (USA, EU standard contractual clauses).\n- mechanism: SCC\n  text: The providers above are engaged under GDPR-compliant agreements with standard contractual clauses where\n    a transfer of account or billing data occurs.\n  source: https://formfeed.dev/legal/subprocessors\nsubprocessors:\n  url: https://formfeed.dev/legal/subprocessors\n  text: Every service provider involved is listed at formfeed.dev/legal/subprocessors.\ndpa:\n  available: true\n  url: https://formfeed.dev/legal/dpa\n  text: Document data you send to the API is processed on your behalf under our data processing agreement (formfeed.dev/legal/dpa).\ndeletion:\n  route: email hello@formfeed.dev\n  text: to have them removed from an organisation that already\
  \ exists, write to hello@formfeed.dev.\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: You have the rights of access, rectification, erasure, restriction, portability and objection (Art. 15–21\n    GDPR)\n- right: complaint to supervisory authority\n  text: the right to lodge a complaint with a supervisory authority\n- right: access, export and deletion assistance\n  text: We forward requests from data subjects to the customer without undue delay and assist with technical means\n    (export, deletion of specific renders or data).\n  source: https://formfeed.dev/legal/dpa\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/formfeed/privacy/formfeed-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Formfeed's own page on 2026-11-09.
synthetic: false
tags:
- PDF
- Image Generation
- Templates
- Developer Tools
- Software-as-a-Service
---
