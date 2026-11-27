---
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, work email, company, role, and account details
  - category: device
    text: IP address, device, browser, usage, cookie, and security-log information
  - category: financial
    text: subscription, transaction, and billing records
  - category: behavioral
    text: Microsoft Clarity for session and behavioural analytics
  - category: communication
    text: support requests and other communications
  - category: identifying
    source: https://app.customerdashboard.io/legal/dpa/
    text: Identity, contact, account, business, usage, transaction, analytical, and other database information selected by the Customer
  deletion:
    route: post-termination deletion on schedule
    source: https://app.customerdashboard.io/legal/dpa/
    text: normally delete active Customer Personal Data and dashboard configurations within 30 days
  dpa:
    available: true
    text: our Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide the Service
    text: create accounts and provide the Service
  - purpose: Product and website analytics
    text: understand and improve the website and Service
  - purpose: Marketing
    text: send marketing where permitted and manage opt-outs
  - purpose: Legal compliance
    text: comply with legal obligations
  - purpose: service provision
    source: https://app.customerdashboard.io/legal/dpa/
    text: Providing the Service according to the Customer’s configuration and instructions
  residency:
  - region: Europe (Frankfurt)
    text: Our primary AWS infrastructure is located in the Europe (Frankfurt) region.
  - region: Germany
    source: https://app.customerdashboard.io/legal/dpa/
    text: hosting primary application infrastructure in AWS Europe (Frankfurt)
  - region: European Economic Area
    source: https://app.customerdashboard.io/legal/dpa/
    text: CustomerDashboard may process Customer Personal Data in the European Economic Area and in countries where authorised subprocessors operate.
  retention:
  - period: 30 days
    scope: Cached customer data and dashboard configurations
    text: cached customer data and active dashboard configurations are normally deleted within 30 days after termination
  - period: 90 days
    scope: Residual backups
    text: residual backup copies may remain for up to 90 days
  - period: 30 days
    scope: active Customer Personal Data and dashboard configurations
    source: https://app.customerdashboard.io/legal/dpa/
    text: normally delete active Customer Personal Data and dashboard configurations within 30 days
  - period: 90 days
    scope: backups
    source: https://app.customerdashboard.io/legal/dpa/
    text: Residual copies may remain in backups for up to 90 days
  rights:
  - right: access, correct, delete, restrict, obtain a copy
    text: individuals may have rights to access, correct, delete, restrict, or obtain a copy of their personal data
  - right: object
    text: object to certain processing
  - right: withdraw consent
    text: withdraw consent at any time
  - right: complain to authority
    text: They may also complain to a data-protection authority.
  - right: assistance with data-protection rights
    source: https://app.customerdashboard.io/legal/dpa/
    text: CustomerDashboard will provide reasonable assistance to help the Customer respond to requests to exercise data-protection rights.
  role:
    text: Boundlessly Oy is the controller of personal data used to operate its business
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not disclose customer dashboard data for advertising.
  subprocessors:
    text: Amazon Web Services (AWS) for hosting and infrastructure; Auth0/Okta for authentication; Lemon Squeezy for subscriptions and payments
    url: null
  transfers:
  - mechanism: DPF
    text: the EU–US Data Privacy Framework where available
  - mechanism: SCC
    text: European Commission Standard Contractual Clauses
  - mechanism: adequacy
    text: an adequacy decision
  - mechanism: SCC
    source: https://app.customerdashboard.io/legal/dpa/
    text: European Commission Standard Contractual Clauses
  - mechanism: DPF
    source: https://app.customerdashboard.io/legal/dpa/
    text: the EU–US Data Privacy Framework where available
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CustomerDashboard
provenance_date: '2026-11-09'
provider_name: CustomerDashboard
provider_slug: customerdashboard-io
slug: customerdashboard-io-privacy-policy
source_date: '2026-11-09'
source_filename: customerdashboard-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.customerdashboard.io/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CustomerDashboard\naid: customerdashboard-io\nurl: https://app.customerdashboard.io/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://app.customerdashboard.io/legal/dpa/\n  - https://app.customerdashboard.io/legal/privacy/\nrole:\n  value: both\n  text: Boundlessly Oy is the controller of personal data used to operate its business\ndata_categories:\n- category: identifying\n  text: name, work email, company, role, and account details\n- category: device\n  text: IP address, device, browser, usage, cookie, and security-log information\n- category: financial\n  text: subscription, transaction,\
  \ and billing records\n- category: behavioral\n  text: Microsoft Clarity for session and behavioural analytics\n- category: communication\n  text: support requests and other communications\n- category: identifying\n  text: Identity, contact, account, business, usage, transaction, analytical, and other database information selected\n    by the Customer\n  source: https://app.customerdashboard.io/legal/dpa/\npurposes:\n- purpose: Provide the Service\n  text: create accounts and provide the Service\n- purpose: Product and website analytics\n  text: understand and improve the website and Service\n- purpose: Marketing\n  text: send marketing where permitted and manage opt-outs\n- purpose: Legal compliance\n  text: comply with legal obligations\n- purpose: service provision\n  text: Providing the Service according to the Customer’s configuration and instructions\n  source: https://app.customerdashboard.io/legal/dpa/\nretention:\n- scope: Cached customer data and dashboard configurations\n  period:\
  \ 30 days\n  text: cached customer data and active dashboard configurations are normally deleted within 30 days after termination\n- scope: Residual backups\n  period: 90 days\n  text: residual backup copies may remain for up to 90 days\n- scope: active Customer Personal Data and dashboard configurations\n  period: 30 days\n  text: normally delete active Customer Personal Data and dashboard configurations within 30 days\n  source: https://app.customerdashboard.io/legal/dpa/\n- scope: backups\n  period: 90 days\n  text: Residual copies may remain in backups for up to 90 days\n  source: https://app.customerdashboard.io/legal/dpa/\nresidency:\n- region: Europe (Frankfurt)\n  text: Our primary AWS infrastructure is located in the Europe (Frankfurt) region.\n- region: Germany\n  text: hosting primary application infrastructure in AWS Europe (Frankfurt)\n  source: https://app.customerdashboard.io/legal/dpa/\n- region: European Economic Area\n  text: CustomerDashboard may process Customer Personal\
  \ Data in the European Economic Area and in countries where\n    authorised subprocessors operate.\n  source: https://app.customerdashboard.io/legal/dpa/\ntransfers:\n- mechanism: DPF\n  text: the EU–US Data Privacy Framework where available\n- mechanism: SCC\n  text: European Commission Standard Contractual Clauses\n- mechanism: adequacy\n  text: an adequacy decision\n- mechanism: SCC\n  text: European Commission Standard Contractual Clauses\n  source: https://app.customerdashboard.io/legal/dpa/\n- mechanism: DPF\n  text: the EU–US Data Privacy Framework where available\n  source: https://app.customerdashboard.io/legal/dpa/\nsubprocessors:\n  url: null\n  text: Amazon Web Services (AWS) for hosting and infrastructure; Auth0/Okta for authentication; Lemon Squeezy for\n    subscriptions and payments\ndpa:\n  available: true\n  url: null\n  text: our Data Processing Addendum\ndeletion:\n  route: post-termination deletion on schedule\n  text: normally delete active Customer Personal Data\
  \ and dashboard configurations within 30 days\n  source: https://app.customerdashboard.io/legal/dpa/\nrights:\n- right: access, correct, delete, restrict, obtain a copy\n  text: individuals may have rights to access, correct, delete, restrict, or obtain a copy of their personal data\n- right: object\n  text: object to certain processing\n- right: withdraw consent\n  text: withdraw consent at any time\n- right: complain to authority\n  text: They may also complain to a data-protection authority.\n- right: assistance with data-protection rights\n  text: CustomerDashboard will provide reasonable assistance to help the Customer respond to requests to exercise\n    data-protection rights.\n  source: https://app.customerdashboard.io/legal/dpa/\nsale_or_sharing:\n  stance: prohibited\n  text: We do not disclose customer dashboard data for advertising.\n"
source_yaml_url: https://artifacts.apis.io/customerdashboard-io/privacy/customerdashboard-io-privacy-policy.yml
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
summary_line: 33 quoted statements, read from CustomerDashboard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Dashboards
- Customer-Facing Analytics
- Embedded Analytics
- Client Reporting
- White Label
- Multi-Tenant
- MCP
- Software-as-a-Service
---
