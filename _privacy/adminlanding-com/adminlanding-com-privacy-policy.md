---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Display name (for personalization)
  - category: contact
    text: 'For each tenant: name, postal address, phone number, email address, and lease start/end dates'
  - category: financial
    text: 'Lease financials: rent, charges, and deposit amounts'
  - category: device
    text: Device information (browser, OS, screen resolution)
  - category: behavioral
    text: Usage analytics (pages visited, features used, session duration)
  - category: location
    text: Your IP address. It necessarily reaches our servers and our CDN with every request.
  - category: health
    text: They are data concerning health (Art. 9 GDPR)
  deletion:
    route: account deletion
    text: 'Account deletion: if you have an active membership, we first cancel it at Stripe so that nothing more is charged; then, within 24 hours, we delete your account and profile'
  dpa:
    available: true
    text: Professional landlords who require a signed data-processing agreement can request one at privacy@adminlanding.com.
    url: null
  purposes:
  - purpose: User authentication and account management
    text: User authentication and account management
  - purpose: Form autofill and document generation
    text: Form autofill and document generation
  - purpose: Security monitoring and fraud prevention
    text: Security monitoring and fraud prevention
  - purpose: Feature development and optimization
    text: Feature development and optimization
  - purpose: Performance monitoring and error tracking
    text: Performance monitoring and error tracking
  residency:
  - region: EU
    text: The data you entrust to us is stored and processed in the European Union.
  retention:
  - period: Until account deletion
    scope: Active accounts
    text: 'Active accounts: Until account deletion'
  - period: 3 years
    scope: Inactive accounts
    text: 'Inactive accounts: reviewed after 3 years of inactivity and deleted after prior notice by email'
  - period: 24 hours
    scope: Generated documents
    text: ephemeral copies expire 24 hours after they are made and are removed by a sweep that runs every six hours
  - period: 12 months
    scope: Usage logs
    text: your AI-usage log and our legal-explanation log are purged at 12 months
  - period: at most 2 years
    scope: Support tickets
    text: 'Support tickets: at most 2 years, counted from the day the ticket was created'
  - period: 10 years
    scope: Billing and invoice records
    text: The invoices and payments themselves stay in that processor's books and in our accounting records for 10 years
  rights:
  - right: access, rectification, erasure, restriction, objection, portability
    text: You have the rights of access, rectification, erasure, restriction, objection and portability described below.
  - right: complaint to the CNIL
    text: Your rights over these data, including the right to complain to the CNIL, are set out under « Your Privacy Rights » below.
  role:
    text: AdminLanding acts as data controller for your account, billing and analytics data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: your data is processed only to generate the documents relating to your tenancy, is stored in the EU, and is never used for marketing or profiling, nor sold.
  subprocessors:
    text: the sub-processors listed on our Sub-Processors page act under Art. 28 GDPR safeguards in that chain
    url: null
  transfers:
  - mechanism: DPF
    text: Where a transfer to the United States occurs, it is governed by the EU-US Data Privacy Framework and/or the European Commission's Standard Contractual Clauses (SCCs).
  - mechanism: SCC
    text: Where a transfer to the United States occurs, it is governed by the EU-US Data Privacy Framework and/or the European Commission's Standard Contractual Clauses (SCCs).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AdminLanding
provenance_date: '2026-11-09'
provider_name: AdminLanding
provider_slug: adminlanding-com
slug: adminlanding-com-privacy-policy
source_date: '2026-11-09'
source_filename: adminlanding-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.adminlanding.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AdminLanding\naid: adminlanding-com\nurl: https://www.adminlanding.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: AdminLanding acts as data controller for your account, billing and analytics data.\ndata_categories:\n- category: identifying\n  text: Display name (for personalization)\n- category: contact\n  text: 'For each tenant: name, postal address, phone number, email address, and lease start/end dates'\n- category: financial\n  text: 'Lease financials: rent, charges, and deposit amounts'\n- category: device\n  text: Device information (browser, OS, screen resolution)\n\
  - category: behavioral\n  text: Usage analytics (pages visited, features used, session duration)\n- category: location\n  text: Your IP address. It necessarily reaches our servers and our CDN with every request.\n- category: health\n  text: They are data concerning health (Art. 9 GDPR)\npurposes:\n- purpose: User authentication and account management\n  text: User authentication and account management\n- purpose: Form autofill and document generation\n  text: Form autofill and document generation\n- purpose: Security monitoring and fraud prevention\n  text: Security monitoring and fraud prevention\n- purpose: Feature development and optimization\n  text: Feature development and optimization\n- purpose: Performance monitoring and error tracking\n  text: Performance monitoring and error tracking\nretention:\n- scope: Active accounts\n  period: Until account deletion\n  text: 'Active accounts: Until account deletion'\n- scope: Inactive accounts\n  period: 3 years\n  text: 'Inactive accounts:\
  \ reviewed after 3 years of inactivity and deleted after prior notice by email'\n- scope: Generated documents\n  period: 24 hours\n  text: ephemeral copies expire 24 hours after they are made and are removed by a sweep that runs every six hours\n- scope: Usage logs\n  period: 12 months\n  text: your AI-usage log and our legal-explanation log are purged at 12 months\n- scope: Support tickets\n  period: at most 2 years\n  text: 'Support tickets: at most 2 years, counted from the day the ticket was created'\n- scope: Billing and invoice records\n  period: 10 years\n  text: The invoices and payments themselves stay in that processor's books and in our accounting records for 10\n    years\nresidency:\n- region: EU\n  text: The data you entrust to us is stored and processed in the European Union.\ntransfers:\n- mechanism: DPF\n  text: Where a transfer to the United States occurs, it is governed by the EU-US Data Privacy Framework and/or\n    the European Commission's Standard Contractual Clauses\
  \ (SCCs).\n- mechanism: SCC\n  text: Where a transfer to the United States occurs, it is governed by the EU-US Data Privacy Framework and/or\n    the European Commission's Standard Contractual Clauses (SCCs).\nsubprocessors:\n  url: null\n  text: the sub-processors listed on our Sub-Processors page act under Art. 28 GDPR safeguards in that chain\ndpa:\n  available: true\n  url: null\n  text: Professional landlords who require a signed data-processing agreement can request one at privacy@adminlanding.com.\ndeletion:\n  route: account deletion\n  text: 'Account deletion: if you have an active membership, we first cancel it at Stripe so that nothing more is\n    charged; then, within 24 hours, we delete your account and profile'\nrights:\n- right: access, rectification, erasure, restriction, objection, portability\n  text: You have the rights of access, rectification, erasure, restriction, objection and portability described\n    below.\n- right: complaint to the CNIL\n  text: Your rights\
  \ over these data, including the right to complain to the CNIL, are set out under « Your Privacy\n    Rights » below.\nsale_or_sharing:\n  stance: prohibited\n  text: your data is processed only to generate the documents relating to your tenancy, is stored in the EU, and\n    is never used for marketing or profiling, nor sold.\n"
source_yaml_url: https://artifacts.apis.io/adminlanding-com/privacy/adminlanding-com-privacy-policy.yml
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
summary_line: 28 quoted statements, read from AdminLanding's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- French Administration
- Real Estate
- Tax
---
