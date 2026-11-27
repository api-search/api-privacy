---
api_specs:
- filename: mailboxlayer-bulk-check-api-openapi.yml
  format: yaml
  label: Mailboxlayer Bulk Check API
  slug: mailboxlayer-bulk-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailboxlayer/openapi/mailboxlayer-bulk-check-api-openapi.yml
- filename: mailboxlayer-check-api-openapi.yml
  format: yaml
  label: Mailboxlayer Check API
  slug: mailboxlayer-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailboxlayer/openapi/mailboxlayer-check-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'personal information: full name; email address; address, zip code, city, region, country'
  - category: financial
    text: 'payment information: credit card type, last four digits, expiration date; date of payment, invoice ID, currency, amount; monthly or annual payment'
  - category: device
    text: IP-address; date and time stamp, time difference to GMT; requested site, site from which the request was sent, transmitted data volume; access status/HTTP status code; browser, operating system, interface, language and version of the browser software
  - category: professional
    text: 'company information (optional): company name, website, tax ID'
  deletion:
    route: request by e-mail to the E-Mail Address or by mail to the postal address
    text: Should you decide that you do not want us to process your data any further, please send a request via e-mail to the E-Mail Address or via mail to the postal address depicted in Section 1.4.
  dpa:
    available: true
    text: In these cases, we will provide you with separate data processing agreements.
    url: null
  purposes:
  - purpose: provide and improve the Services
    text: provide and improve the Services
  - purpose: customer relations management, including newsletters
    text: customer relations management, including newsletters
  - purpose: security and stability of the Services
    text: security and stability of the Services
  retention:
  - period: null
    scope: registered users
    text: We store your Data as long as you are a registered user of the Product.
  rights:
  - right: access
    text: You have the right to obtain (i) confirmation as to whether or not your Data is being processed by us
  - right: rectification
    text: You have the right to obtain from us the rectification of inaccurate Data concerning you.
  - right: erasure
    text: We will erase your Data immediately and inform you of this process.
  - right: restriction of processing
    text: You have the right to obtain from us a restriction of processing of your Data in the following cases
  - right: portability
    text: You have the right to (i) receive your Data in a structured, commonly used and machine-readable format
  - right: object
    text: You have the right to object at any time to the processing of Data.
  - right: lodge a complaint
    text: You have the right to lodge a complaint with a supervisory authority
  role:
    text: The controller for the processing of your personal data within the meaning of the GDPR is the Company.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: we use third party providers to process data for us, such as PayLane Sp. z o.o.; International Business Machines Corporation (IBM BlueMix); Zendesk, Inc.; or The Rocket Science Group LLC d/b/a MailChimp.
    url: null
  transfers:
  - mechanism: DPF
    text: Google is certified via EU-US privacy shield.
  - mechanism: other
    text: All service providers are part of the EU-US Privacy Shield or otherwise adhere to sufficient data protection standards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mailboxlayer
provenance_date: '2026-11-10'
provider_name: Mailboxlayer
provider_slug: mailboxlayer
slug: mailboxlayer-privacy-policy
source_date: '2026-11-10'
source_filename: mailboxlayer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mailboxlayer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mailboxlayer\naid: mailboxlayer\nurl: https://mailboxlayer.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The controller for the processing of your personal data within the meaning of the GDPR is the Company.\ndata_categories:\n- category: identifying\n  text: 'personal information: full name; email address; address, zip code, city, region, country'\n- category: financial\n  text: 'payment information: credit card type, last four digits, expiration date; date of payment, invoice ID,\n    currency, amount; monthly or annual payment'\n- category: device\n  text: IP-address; date and time\
  \ stamp, time difference to GMT; requested site, site from which the request was\n    sent, transmitted data volume; access status/HTTP status code; browser, operating system, interface, language\n    and version of the browser software\n- category: professional\n  text: 'company information (optional): company name, website, tax ID'\npurposes:\n- purpose: provide and improve the Services\n  text: provide and improve the Services\n- purpose: customer relations management, including newsletters\n  text: customer relations management, including newsletters\n- purpose: security and stability of the Services\n  text: security and stability of the Services\nretention:\n- scope: registered users\n  period: null\n  text: We store your Data as long as you are a registered user of the Product.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Google is certified via EU-US privacy shield.\n- mechanism: other\n  text: All service providers are part of the EU-US Privacy Shield or otherwise adhere\
  \ to sufficient data protection\n    standards.\nsubprocessors:\n  url: null\n  text: we use third party providers to process data for us, such as PayLane Sp. z o.o.; International Business\n    Machines Corporation (IBM BlueMix); Zendesk, Inc.; or The Rocket Science Group LLC d/b/a MailChimp.\ndpa:\n  available: true\n  url: null\n  text: In these cases, we will provide you with separate data processing agreements.\ndeletion:\n  route: request by e-mail to the E-Mail Address or by mail to the postal address\n  text: Should you decide that you do not want us to process your data any further, please send a request via e-mail\n    to the E-Mail Address or via mail to the postal address depicted in Section 1.4.\nrights:\n- right: access\n  text: You have the right to obtain (i) confirmation as to whether or not your Data is being processed by us\n- right: rectification\n  text: You have the right to obtain from us the rectification of inaccurate Data concerning you.\n- right: erasure\n  text:\
  \ We will erase your Data immediately and inform you of this process.\n- right: restriction of processing\n  text: You have the right to obtain from us a restriction of processing of your Data in the following cases\n- right: portability\n  text: You have the right to (i) receive your Data in a structured, commonly used and machine-readable format\n- right: object\n  text: You have the right to object at any time to the processing of Data.\n- right: lodge a complaint\n  text: You have the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailboxlayer/privacy/mailboxlayer-privacy-policy.yml
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
summary_line: 21 quoted statements, read from Mailboxlayer's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Email Verification
- SMTP
- MX Records
- Catch-All Detection
- Disposable Email
- Free Email Provider
- Role Address
- Quality Score
- APILayer
- Public APIs
- Data Quality
- Fraud Prevention
- Deliverability
- Communications
- Developer Tools
- Security
---
