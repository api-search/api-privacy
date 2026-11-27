---
api_specs:
- filename: taxley-tools-api-openapi.yml
  format: yaml
  label: Taxley (UK Corporation Tax API) Tools API
  slug: taxley-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taxley/openapi/taxley-tools-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your name, email address, and a hashed password (or a Google sign-in identifier if you use it).'
  - category: financial
    text: 'Financial: the income, expenses, balance-sheet and computation figures you enter, and the CT600, accounts and computations generated from them.'
  - category: device
    text: 'Website visits: your IP address, approximate location worked out from it, pages viewed, referring site, and browser/device user-agent.'
  - category: communication
    text: 'Questions & enquiries: if you use the "Ask us anything" form or the contact form, the name, email address and message you send us, and the page you were on.'
  deletion:
    route: In-app My data page
    text: You can delete your account at any time on the My data page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service and file returns
    text: To provide the Service and file your Return on your instruction — performance of a contract .
  - purpose: Take payment
    text: To take payment — performance of a contract.
  - purpose: Measure advertising
    text: To understand how the website is used, diagnose abuse and improve customer journeys using cookieless page-view logs — legitimate interests .
  residency:
  - region: United Kingdom
    text: Our server is in the United Kingdom (London).
  retention:
  - period: 30 days
    scope: Website visit logs
    text: the raw IP address on each page view is deleted after 30 days , and page views are deleted after 90 days .
  - period: 14 months
    scope: Google Analytics data
    text: Google Analytics keeps user- and event-level data for 14 months ;
  - period: 24 months
    scope: Email activity log
    text: Email activity log — each record is deleted after 24 months .
  - period: six years
    scope: Filed returns and payment records
    text: A company must keep its accounting records for six years , and we keep the returns we filed and their payment records for that long too.
  rights:
  - right: access
    text: you have the right to access, rectify, erase, restrict, port and object to the processing of your personal data
  - right: withdraw consent
    text: and to withdraw consent where we rely on it.
  - right: complain to regulator
    text: You also have the right to complain to the Information Commission
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data or use it for third-party marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Google LLC is certified under the UK Extension to the EU–US Data Privacy Framework (the UK–US data bridge)
  - mechanism: SCC
    text: Google also uses standard contractual clauses where they are needed.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Taxley (UK Corporation Tax API)
provenance_date: '2026-11-10'
provider_name: Taxley (UK Corporation Tax API)
provider_slug: taxley
slug: taxley-privacy-policy
source_date: '2026-11-10'
source_filename: taxley-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://taxley.co.uk/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Taxley (UK Corporation Tax API)\naid: taxley\nurl: https://taxley.co.uk/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account: your name, email address, and a hashed password (or a Google sign-in identifier if you use it).'\n- category: financial\n  text: 'Financial: the income, expenses, balance-sheet and computation figures you enter, and the CT600, accounts\n    and computations generated from them.'\n- category: device\n  text: 'Website visits: your IP address, approximate location worked out from it, pages viewed,\
  \ referring site,\n    and browser/device user-agent.'\n- category: communication\n  text: 'Questions & enquiries: if you use the \"Ask us anything\" form or the contact form, the name, email address\n    and message you send us, and the page you were on.'\npurposes:\n- purpose: Provide the Service and file returns\n  text: To provide the Service and file your Return on your instruction — performance of a contract .\n- purpose: Take payment\n  text: To take payment — performance of a contract.\n- purpose: Measure advertising\n  text: To understand how the website is used, diagnose abuse and improve customer journeys using cookieless page-view\n    logs — legitimate interests .\nretention:\n- scope: Website visit logs\n  period: 30 days\n  text: the raw IP address on each page view is deleted after 30 days , and page views are deleted after 90 days\n    .\n- scope: Google Analytics data\n  period: 14 months\n  text: Google Analytics keeps user- and event-level data for 14 months ;\n- scope:\
  \ Email activity log\n  period: 24 months\n  text: Email activity log — each record is deleted after 24 months .\n- scope: Filed returns and payment records\n  period: six years\n  text: A company must keep its accounting records for six years , and we keep the returns we filed and their payment\n    records for that long too.\nresidency:\n- region: United Kingdom\n  text: Our server is in the United Kingdom (London).\ntransfers:\n- mechanism: DPF\n  text: Google LLC is certified under the UK Extension to the EU–US Data Privacy Framework (the UK–US data bridge)\n- mechanism: SCC\n  text: Google also uses standard contractual clauses where they are needed.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app My data page\n  text: You can delete your account at any time on the My data page.\nrights:\n- right: access\n  text: you have the right to access, rectify, erase, restrict, port and object to the processing of your\
  \ personal\n    data\n- right: withdraw consent\n  text: and to withdraw consent where we rely on it.\n- right: complain to regulator\n  text: You also have the right to complain to the Information Commission\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data or use it for third-party marketing.\n"
source_yaml_url: https://artifacts.apis.io/taxley/privacy/taxley-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Taxley (UK Corporation Tax API)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- United Kingdom
- Finance
---
