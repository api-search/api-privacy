---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, your organisation's name, and your role and membership status within it
  - category: financial
    text: the identifiers our payment processor issues for your organisation and its subscription, the plan you are on, your billing interval, the current billing period
  - category: device
    text: device and operating-system details (such as model, OS version, and total and available memory)
  - category: communication
    text: the free-text description the Authorised Tester wrote
  - category: behavioral
    text: which of the app's screens you saw, which steps were reached and whether they succeeded
  deletion:
    route: email or delete-account option in settings
    text: To request deletion, email [email protected] or use the delete-account option in your settings, which opens the same request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service
    text: ingesting and storing accepted bug reports and forwarding issues to the Integrations a Customer has configured
  - purpose: operate Customer accounts
    text: 'to operate Customer accounts: authentication, authorisation and support'
  - purpose: security
    text: 'to keep the Service secure: rate limiting, abuse detection, operational logging'
  - purpose: improve the Service
    text: 'to improve the Service: analysing how the Service is used'
  - purpose: advertising measurement
    text: to measure which advertisements lead to sign-ups
  residency:
  - region: United Kingdom (AWS eu-west-2 London)
    text: Data is processed in the AWS eu-west-2 (London) region.
  retention:
  - period: 30 days
    scope: accepted bug reports on Free plan
    text: We make an accepted report's content, summary, and attachments available for 30 days on Free or up to 1 year on paid plans.
  - period: null
    scope: customer account data
    text: Customer account data is retained while the account is active.
  - period: 12 months
    scope: operational and diagnostic logs
    text: Operational and diagnostic logs — the application logs generated when the console and our API handle requests — are retained for 12 months and then deleted automatically.
  - period: up to 3 years
    scope: infrastructure audit logs
    text: Infrastructure audit logs are retained for up to 3 years.
  rights:
  - right: access, correct, delete, port, restrict, object
    text: you may have the right to access, correct, delete, port, or restrict the processing of your personal data, and to object to processing based on legitimate interests
  - right: withdraw consent
    text: You can also withdraw consent at any time without affecting prior processing.
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with a supervisory authority — in the UK, the Information Commissioner's Office ( ico.org.uk ).
  role:
    text: For Customer account data (the records identifying an organisation, its members, and its subscription), we act as a controller . For bug reports submitted through a Customer's SDK, the Customer is the controller of the personal data it contains and we act as a processor on its behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: The definitive list of named sub-processors is published at bugscreen.app/subprocessors
    url: https://www.bugscreen.app/subprocessors
  transfers:
  - mechanism: SCC
    text: the EU Standard Contractual Clauses
  - mechanism: other
    text: the UK International Data Transfer Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BugScreen
provenance_date: '2026-11-09'
provider_name: BugScreen
provider_slug: bugscreen-app
slug: bugscreen-app-privacy-policy
source_date: '2026-11-09'
source_filename: bugscreen-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bugscreen.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BugScreen\naid: bugscreen-app\nurl: https://www.bugscreen.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For Customer account data (the records identifying an organisation, its members, and its subscription),\n    we act as a controller . For bug reports submitted through a Customer's SDK, the Customer is the controller\n    of the personal data it contains and we act as a processor on its behalf.\ndata_categories:\n- category: identifying\n  text: your email address, your organisation's name, and your role and membership status within it\n- category: financial\n  text: the identifiers\
  \ our payment processor issues for your organisation and its subscription, the plan you are\n    on, your billing interval, the current billing period\n- category: device\n  text: device and operating-system details (such as model, OS version, and total and available memory)\n- category: communication\n  text: the free-text description the Authorised Tester wrote\n- category: behavioral\n  text: which of the app's screens you saw, which steps were reached and whether they succeeded\npurposes:\n- purpose: provide the Service\n  text: ingesting and storing accepted bug reports and forwarding issues to the Integrations a Customer has configured\n- purpose: operate Customer accounts\n  text: 'to operate Customer accounts: authentication, authorisation and support'\n- purpose: security\n  text: 'to keep the Service secure: rate limiting, abuse detection, operational logging'\n- purpose: improve the Service\n  text: 'to improve the Service: analysing how the Service is used'\n- purpose: advertising\
  \ measurement\n  text: to measure which advertisements lead to sign-ups\nretention:\n- scope: accepted bug reports on Free plan\n  period: 30 days\n  text: We make an accepted report's content, summary, and attachments available for 30 days on Free or up to 1\n    year on paid plans.\n- scope: customer account data\n  period: null\n  text: Customer account data is retained while the account is active.\n- scope: operational and diagnostic logs\n  period: 12 months\n  text: Operational and diagnostic logs — the application logs generated when the console and our API handle requests\n    — are retained for 12 months and then deleted automatically.\n- scope: infrastructure audit logs\n  period: up to 3 years\n  text: Infrastructure audit logs are retained for up to 3 years.\nresidency:\n- region: United Kingdom (AWS eu-west-2 London)\n  text: Data is processed in the AWS eu-west-2 (London) region.\ntransfers:\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses\n- mechanism: other\n\
  \  text: the UK International Data Transfer Addendum\nsubprocessors:\n  url: https://www.bugscreen.app/subprocessors\n  text: The definitive list of named sub-processors is published at bugscreen.app/subprocessors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email or delete-account option in settings\n  text: To request deletion, email [email protected] or use the delete-account option in your settings, which opens\n    the same request.\nrights:\n- right: access, correct, delete, port, restrict, object\n  text: you may have the right to access, correct, delete, port, or restrict the processing of your personal data,\n    and to object to processing based on legitimate interests\n- right: withdraw consent\n  text: You can also withdraw consent at any time without affecting prior processing.\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with a supervisory authority — in the UK, the Information Commissioner's\n\
  \    Office ( ico.org.uk ).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/bugscreen-app/privacy/bugscreen-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BugScreen's own page on 2026-11-09.
synthetic: false
tags:
- Bug Reporting
- QA
- Mobile
- SDK
- Integration
---
