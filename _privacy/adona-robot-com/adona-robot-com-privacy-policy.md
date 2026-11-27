---
api_specs:
- filename: adona-robot-com-openapi-generated.yml
  format: yaml
  label: adona-robot-com API
  slug: adona-robot-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adona-robot-com/openapi/_ae-authored/adona-robot-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: The account's email address, the company name given at sign-up, and the sites you declare for your key.
  - category: device
    text: the IP address and the browser, at sign-up, at each sign-in
  - category: location
    text: At sign-up the country of the IP address is looked up
  - category: behavioral
    text: The measure of your usage (slices, simultaneous connections, symbols followed live), which sets your plan and your invoice.
  - category: financial
    text: On a paid plan, your payment details are entered at Stripe and kept by Stripe. We never see your card number.
  - category: communication
    text: your name, your work email, your company, its website if you give it, the use, the size of the audience and the symbols you chose, your message
  deletion:
    route: Delete the account or write to privacy@adona-robot.com
    text: When the account is deleted, the address, the company name and the declared sites are erased from the account, the sessions removed, and the IP address and the browser cleared from the sign-in records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and bill the service
    text: To provide the service you signed up for and to bill it; to keep accounting records as the law requires
  - purpose: Protect the service
    text: to protect the service and its customers, which is what the sign-in records and the trial's fingerprint are for (one trial per company and per network)
  - purpose: Answer requests
    text: to answer a request you sent with the redistribution form
  residency:
  - region: Switzerland
    text: Our servers are in Switzerland, at Infomaniak in Geneva.
  retention:
  - period: 12 months
    scope: Trial fingerprint
    text: The trial's fingerprint is kept 12 months, then deleted.
  - period: as long as the account exists
    scope: Account data
    text: The address, the company name, the declared sites and your sessions are kept as long as the account exists.
  - period: 10 years
    scope: Invoices
    text: Invoices, with the address and the company name they carry, are kept 10 years, as Swiss accounting law requires
  - period: 14 days
    scope: Web server log
    text: The web server also logs each request with its IP address; that log is kept 14 days, then deleted.
  - period: 13 months
    scope: Audience statistics
    text: These statistics identify nobody; they are kept 13 months, then deleted.
  - period: 12 months
    scope: Redistribution form requests
    text: A request sent with the redistribution form is kept 12 months in our database, then deleted.
  rights:
  - right: access
    text: You can ask what we keep about you
  - right: rectification
    text: have it corrected or deleted
  - right: portability
    text: or receive it in a common format
  - right: complaint
    text: you can also turn to the Federal Data Protection and Information Commissioner (FDPIC)
  role:
    text: run by Adona Robot Sàrl, Chemin des Semailles 42, 1212 Grand-Lancy, Switzerland (CHE-205.255.519), which decides what is kept and why.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nothing is sold or used for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on the safeguards those providers offer for such transfers, such as standard contractual clauses or their certification under the Swiss-US Data Privacy Framework.
  - mechanism: DPF
    text: or their certification under the Swiss-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: adona-robot-com
provenance_date: '2026-11-09'
provider_name: adona-robot-com
provider_slug: adona-robot-com
slug: adona-robot-com-privacy-policy
source_date: '2026-11-09'
source_filename: adona-robot-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adona-robot.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: adona-robot-com\naid: adona-robot-com\nurl: https://adona-robot.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: run by Adona Robot Sàrl, Chemin des Semailles 42, 1212 Grand-Lancy, Switzerland (CHE-205.255.519), which\n    decides what is kept and why.\ndata_categories:\n- category: contact\n  text: The account's email address, the company name given at sign-up, and the sites you declare for your key.\n- category: device\n  text: the IP address and the browser, at sign-up, at each sign-in\n- category: location\n  text: At sign-up the country of the IP address is looked up\n- category:\
  \ behavioral\n  text: The measure of your usage (slices, simultaneous connections, symbols followed live), which sets your plan\n    and your invoice.\n- category: financial\n  text: On a paid plan, your payment details are entered at Stripe and kept by Stripe. We never see your card number.\n- category: communication\n  text: your name, your work email, your company, its website if you give it, the use, the size of the audience\n    and the symbols you chose, your message\npurposes:\n- purpose: Provide and bill the service\n  text: To provide the service you signed up for and to bill it; to keep accounting records as the law requires\n- purpose: Protect the service\n  text: to protect the service and its customers, which is what the sign-in records and the trial's fingerprint\n    are for (one trial per company and per network)\n- purpose: Answer requests\n  text: to answer a request you sent with the redistribution form\nretention:\n- scope: Trial fingerprint\n  period: 12 months\n \
  \ text: The trial's fingerprint is kept 12 months, then deleted.\n- scope: Account data\n  period: as long as the account exists\n  text: The address, the company name, the declared sites and your sessions are kept as long as the account exists.\n- scope: Invoices\n  period: 10 years\n  text: Invoices, with the address and the company name they carry, are kept 10 years, as Swiss accounting law requires\n- scope: Web server log\n  period: 14 days\n  text: The web server also logs each request with its IP address; that log is kept 14 days, then deleted.\n- scope: Audience statistics\n  period: 13 months\n  text: These statistics identify nobody; they are kept 13 months, then deleted.\n- scope: Redistribution form requests\n  period: 12 months\n  text: A request sent with the redistribution form is kept 12 months in our database, then deleted.\nresidency:\n- region: Switzerland\n  text: Our servers are in Switzerland, at Infomaniak in Geneva.\ntransfers:\n- mechanism: SCC\n  text: We rely\
  \ on the safeguards those providers offer for such transfers, such as standard contractual clauses\n    or their certification under the Swiss-US Data Privacy Framework.\n- mechanism: DPF\n  text: or their certification under the Swiss-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete the account or write to privacy@adona-robot.com\n  text: When the account is deleted, the address, the company name and the declared sites are erased from the account,\n    the sessions removed, and the IP address and the browser cleared from the sign-in records.\nrights:\n- right: access\n  text: You can ask what we keep about you\n- right: rectification\n  text: have it corrected or deleted\n- right: portability\n  text: or receive it in a common format\n- right: complaint\n  text: you can also turn to the Federal Data Protection and Information Commissioner (FDPIC)\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: Nothing is sold or used for advertising.\n"
source_yaml_url: https://artifacts.apis.io/adona-robot-com/privacy/adona-robot-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from adona-robot-com's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Foreign Exchange
- Metals
- Swiss
---
