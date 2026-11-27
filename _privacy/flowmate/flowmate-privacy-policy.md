---
api_specs:
- filename: flowmate-openapi-generated.yml
  format: yaml
  label: FlowMate API
  slug: flowmate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmate/openapi/_ae-authored/flowmate-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect account data such as name, work email, company name, and role
  - category: contact
    text: Telephone +49-221-165343-33
  - category: device
    text: browser type, operating system, and the domain name of your internet service provider
  - category: financial
    text: We do not store full card details ourselves.
  - category: professional
    text: your job title, company, and professional background on your public LinkedIn profile
  - category: communication
    text: the confirmation of your email address
  deletion:
    route: account settings or email privacy@flowmate.io
    text: You can also view, change, or delete your account data yourself at any time from your account settings. To exercise any other right, email privacy@flowmate.io.
  dpa:
    available: true
    text: FlowMate acts as your processor under our Data Processing Agreement
    url: null
  purposes:
  - purpose: account creation and operation
    text: We use it to create and run your account, to send service emails such as the confirmation of your email address, and to provide support (Art. 6(1)(b) GDPR).
  - purpose: payment processing
    text: Paid plans are billed through Stripe (Art. 6(1)(b) GDPR).
  - purpose: marketing product tips
    text: If you tick the checkbox at signup, we also send you product tips and incentives by email, based on your consent
  - purpose: analytics and advertising
    text: Only with your consent, we load Google Tag Manager, which we use for analytics (Google Analytics) and advertising (Google Ads)
  residency:
  - region: Germany (platform hosting)
    text: Google Cloud - hosting of the FlowMate platform in Frankfurt, Germany
  - region: Germany (database)
    text: MongoDB Atlas - database hosting for the FlowMate platform, in Frankfurt, Germany
  retention:
  - period: until you delete your account
    scope: account data
    text: 'Account data: kept until you delete your account.'
  - period: 30 days
    scope: activity logs
    text: 'Activity logs: deleted automatically after 30 days.'
  - period: up to 7 days
    scope: platform backups
    text: 'Backups: platform backups are kept for up to 7 days, so deleted data can remain in a backup for that period.'
  - period: null
    scope: newsletter data
    text: 'Newsletter data: kept until you withdraw your consent.'
  - period: until you ask us to delete it
    scope: CRM, support and email tools
    text: 'Data in our CRM, support, and email tools: kept until you ask us to delete it. We delete it within one month of your request.'
  rights:
  - right: access
    text: Request access to the personal data we hold about you
  - right: correction
    text: Request correction of inaccurate data
  - right: deletion
    text: Request deletion, unless a legal retention obligation applies (in which case we'll block rather than delete)
  - right: objection and restriction
    text: Object to or restrict certain processing
  - right: portability
    text: Receive the data you provided to us in a common, machine-readable format (data portability), where applicable
  - right: withdraw consent
    text: Withdraw consent at any time, without affecting processing carried out before withdrawal
  - right: complaint
    text: Lodge a complaint with a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data, and only disclose it beyond the above where legally required or with your consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the EU Commission's Standard Contractual Clauses, an adequacy decision, or another valid GDPR Chapter V transfer mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FlowMate
provenance_date: '2026-11-09'
provider_name: FlowMate
provider_slug: flowmate
slug: flowmate-privacy-policy
source_date: '2026-11-09'
source_filename: flowmate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.flowmate.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FlowMate\naid: flowmate\nurl: https://www.flowmate.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect account data such as name, work email, company name, and role\n- category: contact\n  text: Telephone +49-221-165343-33\n- category: device\n  text: browser type, operating system, and the domain name of your internet service provider\n- category: financial\n  text: We do not store full card details ourselves.\n- category: professional\n  text: your job title, company, and professional background on your public\
  \ LinkedIn profile\n- category: communication\n  text: the confirmation of your email address\npurposes:\n- purpose: account creation and operation\n  text: We use it to create and run your account, to send service emails such as the confirmation of your email\n    address, and to provide support (Art. 6(1)(b) GDPR).\n- purpose: payment processing\n  text: Paid plans are billed through Stripe (Art. 6(1)(b) GDPR).\n- purpose: marketing product tips\n  text: If you tick the checkbox at signup, we also send you product tips and incentives by email, based on your\n    consent\n- purpose: analytics and advertising\n  text: Only with your consent, we load Google Tag Manager, which we use for analytics (Google Analytics) and advertising\n    (Google Ads)\nretention:\n- scope: account data\n  period: until you delete your account\n  text: 'Account data: kept until you delete your account.'\n- scope: activity logs\n  period: 30 days\n  text: 'Activity logs: deleted automatically after 30 days.'\n\
  - scope: platform backups\n  period: up to 7 days\n  text: 'Backups: platform backups are kept for up to 7 days, so deleted data can remain in a backup for that period.'\n- scope: newsletter data\n  period: null\n  text: 'Newsletter data: kept until you withdraw your consent.'\n- scope: CRM, support and email tools\n  period: until you ask us to delete it\n  text: 'Data in our CRM, support, and email tools: kept until you ask us to delete it. We delete it within one\n    month of your request.'\nresidency:\n- region: Germany (platform hosting)\n  text: Google Cloud - hosting of the FlowMate platform in Frankfurt, Germany\n- region: Germany (database)\n  text: MongoDB Atlas - database hosting for the FlowMate platform, in Frankfurt, Germany\ntransfers:\n- mechanism: SCC\n  text: we rely on the EU Commission's Standard Contractual Clauses, an adequacy decision, or another valid GDPR\n    Chapter V transfer mechanism.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n \
  \ url: null\n  text: FlowMate acts as your processor under our Data Processing Agreement\ndeletion:\n  route: account settings or email privacy@flowmate.io\n  text: You can also view, change, or delete your account data yourself at any time from your account settings.\n    To exercise any other right, email privacy@flowmate.io.\nrights:\n- right: access\n  text: Request access to the personal data we hold about you\n- right: correction\n  text: Request correction of inaccurate data\n- right: deletion\n  text: Request deletion, unless a legal retention obligation applies (in which case we'll block rather than delete)\n- right: objection and restriction\n  text: Object to or restrict certain processing\n- right: portability\n  text: Receive the data you provided to us in a common, machine-readable format (data portability), where applicable\n- right: withdraw consent\n  text: Withdraw consent at any time, without affecting processing carried out before withdrawal\n- right: complaint\n  text:\
  \ Lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data, and only disclose it beyond the above where legally required or with your consent.\n"
source_yaml_url: https://artifacts.apis.io/flowmate/privacy/flowmate-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from FlowMate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- Artificial Intelligence
- Integration
- Workflows
---
