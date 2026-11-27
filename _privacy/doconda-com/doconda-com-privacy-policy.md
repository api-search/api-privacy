---
api_specs:
- filename: doconda-com-dashboard-api-openapi.yml
  format: yaml
  label: doconda-com Dashboard API
  slug: doconda-com-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-dashboard-api-openapi.yml
- filename: doconda-com-documents-api-openapi.yml
  format: yaml
  label: doconda-com Documents API
  slug: doconda-com-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-documents-api-openapi.yml
- filename: doconda-com-editor-api-openapi.yml
  format: yaml
  label: doconda-com Editor API
  slug: doconda-com-editor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-editor-api-openapi.yml
- filename: doconda-com-files-api-openapi.yml
  format: yaml
  label: doconda-com Files API
  slug: doconda-com-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-files-api-openapi.yml
- filename: doconda-com-webhooks-api-openapi.yml
  format: yaml
  label: doconda-com Webhooks API
  slug: doconda-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doconda-com/openapi/doconda-com-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email, name, organization, projects, role, sign-in (also with Google or Microsoft)'
  - category: device
    text: 'Usage: operations, pages, cost, dates, IP and technical logs'
  - category: financial
    text: 'Billing: tax details, payments; of the card only the brand and last 4 digits (Stripe handles the rest)'
  - category: communication
    text: 'Communications: what you write to us'
  - category: behavioral
    text: 'Analytics: pages viewed, clicks, where you came from and, if you accept, a recording of the session (without what you type in forms)'
  deletion:
    route: Email contact@doconda.com to delete account and Google-derived data
    text: write to contact@doconda.com and we will delete your account and this data within 30 days at most.
  dpa:
    available: true
    text: As processor , for the personal data customers include in their documents, files and artifacts. There the customer is in charge, and it is governed by the data processing agreement in the terms of use .
    url: null
  purposes:
  - purpose: Giving access and providing the service
    text: Giving you access and providing the service Contract (art. 6.1.b GDPR)
  - purpose: Billing, security and abuse prevention, service improvement
    text: Billing, showing you your usage, security and abuse prevention, improving the service
  - purpose: Billing and tax obligations
    text: Billing and meeting tax and accounting obligations
  - purpose: Website and dashboard analytics
    text: Understanding how the website and the dashboard are used, and improving them
  residency:
  - region: European Union (Ireland)
    text: Documents and files are stored in the European Union (Ireland), and the AI models also run in the European Union (Amazon Bedrock).
  retention:
  - period: while the account is active
    scope: Account data
    text: 'Account data: while the account is active and, afterwards, for as long as needed to meet legal liabilities.'
  - period: six years
    scope: Invoices and payment data
    text: 'Invoices and payment data: the periods required by law (in general, six years under Spanish commercial law).'
  - period: 30 days by default
    scope: Content of documents and uploaded files
    text: from 15 minutes to 90 days after it finishes (30 days by default), or sooner if they delete it.
  - period: 7 days
    scope: Document events
    text: Each document's events are deleted after 7 days.
  - period: 14 days
    scope: Technical logs
    text: 'Technical logs: 14 days.'
  rights:
  - right: access
    text: You can request access, rectification, erasure, objection, restriction and portability of your data
  - right: withdraw consent
    text: and withdraw consent if you gave it, by writing to contact@doconda.com .
  - right: complain to authority
    text: If you are not satisfied, you can complain to the Spanish Data Protection Agency (aepd.es).
  role:
    text: 'We process personal data in two different roles: As controller , for the data of the people who use Doconda and of visitors to this website'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not use document content to train artificial intelligence models, and we do not sell personal data.
  subprocessors:
    text: With the providers that help us provide the service, as processors and under contract
    url: null
  transfers:
  - mechanism: other
    text: Some providers (for example, the payment provider) may process data outside the European Economic Area; in that case they do so with GDPR safeguards (an adequacy decision, such as the EU-US Data Privacy Framework, or standard contractual clauses).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: doconda-com
provenance_date: '2026-11-09'
provider_name: doconda-com
provider_slug: doconda-com
slug: doconda-com-privacy-policy
source_date: '2026-11-09'
source_filename: doconda-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://doconda.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: doconda-com\naid: doconda-com\nurl: https://doconda.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We process personal data in two different roles: As controller , for the data of the people who use Doconda\n    and of visitors to this website'\ndata_categories:\n- category: identifying\n  text: 'Account: email, name, organization, projects, role, sign-in (also with Google or Microsoft)'\n- category: device\n  text: 'Usage: operations, pages, cost, dates, IP and technical logs'\n- category: financial\n  text: 'Billing: tax details, payments; of the card only the brand and last 4 digits\
  \ (Stripe handles the rest)'\n- category: communication\n  text: 'Communications: what you write to us'\n- category: behavioral\n  text: 'Analytics: pages viewed, clicks, where you came from and, if you accept, a recording of the session (without\n    what you type in forms)'\npurposes:\n- purpose: Giving access and providing the service\n  text: Giving you access and providing the service Contract (art. 6.1.b GDPR)\n- purpose: Billing, security and abuse prevention, service improvement\n  text: Billing, showing you your usage, security and abuse prevention, improving the service\n- purpose: Billing and tax obligations\n  text: Billing and meeting tax and accounting obligations\n- purpose: Website and dashboard analytics\n  text: Understanding how the website and the dashboard are used, and improving them\nretention:\n- scope: Account data\n  period: while the account is active\n  text: 'Account data: while the account is active and, afterwards, for as long as needed to meet legal liabilities.'\n\
  - scope: Invoices and payment data\n  period: six years\n  text: 'Invoices and payment data: the periods required by law (in general, six years under Spanish commercial\n    law).'\n- scope: Content of documents and uploaded files\n  period: 30 days by default\n  text: from 15 minutes to 90 days after it finishes (30 days by default), or sooner if they delete it.\n- scope: Document events\n  period: 7 days\n  text: Each document's events are deleted after 7 days.\n- scope: Technical logs\n  period: 14 days\n  text: 'Technical logs: 14 days.'\nresidency:\n- region: European Union (Ireland)\n  text: Documents and files are stored in the European Union (Ireland), and the AI models also run in the European\n    Union (Amazon Bedrock).\ntransfers:\n- mechanism: other\n  text: Some providers (for example, the payment provider) may process data outside the European Economic Area;\n    in that case they do so with GDPR safeguards (an adequacy decision, such as the EU-US Data Privacy Framework,\n\
  \    or standard contractual clauses).\nsubprocessors:\n  url: null\n  text: With the providers that help us provide the service, as processors and under contract\ndpa:\n  available: true\n  url: null\n  text: As processor , for the personal data customers include in their documents, files and artifacts. There the\n    customer is in charge, and it is governed by the data processing agreement in the terms of use .\ndeletion:\n  route: Email contact@doconda.com to delete account and Google-derived data\n  text: write to contact@doconda.com and we will delete your account and this data within 30 days at most.\nrights:\n- right: access\n  text: You can request access, rectification, erasure, objection, restriction and portability of your data\n- right: withdraw consent\n  text: and withdraw consent if you gave it, by writing to contact@doconda.com .\n- right: complain to authority\n  text: If you are not satisfied, you can complain to the Spanish Data Protection Agency (aepd.es).\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not use document content to train artificial intelligence models, and we do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/doconda-com/privacy/doconda-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from doconda-com's own page on 2026-11-09.
synthetic: false
tags:
- Document Generation
- Conversion
- Automation
- Artificial Intelligence
---
