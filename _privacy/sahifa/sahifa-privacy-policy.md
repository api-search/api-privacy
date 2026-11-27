---
api_specs:
- filename: sahifa-pdf-api-openapi.yml
  format: yaml
  label: Sahifa PDF API
  slug: sahifa-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sahifa/openapi/sahifa-pdf-api-openapi.yml
- filename: sahifa-screenshots-api-openapi.yml
  format: yaml
  label: Sahifa Screenshots API
  slug: sahifa-screenshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sahifa/openapi/sahifa-screenshots-api-openapi.yml
- filename: sahifa-status-api-openapi.yml
  format: yaml
  label: Sahifa Status API
  slug: sahifa-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sahifa/openapi/sahifa-status-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, and if you give them, your company name and the language of our emails.
  - category: financial
    text: company or personal name, VAT or tax number, country, billing address, contact person, email address and optional phone number.
  - category: device
    text: the IP address of each demo request is held in the server's memory for up to one hour, then discarded.
  - category: communication
    text: Messages you send us, and our replies.
  - category: other
    text: The HTML, web addresses and settings in a request are processed in memory on our server in Jeddah, only to produce the PDF or image you asked for.
  deletion:
    route: Account page, or email support@sahifa.dev
    text: you can do that at any time from the account page, and your email address and company name are removed at once, and from the encrypted backups within 35 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Perform the requested service
    text: Content is processed to perform the service you request.
  - purpose: Subscription and invoicing
    text: Account and billing details are used to provide the subscription and to invoice it
  - purpose: Account contact and sign-in
    text: The email address is used to send sign-in links, which work once and expire after 15 minutes, and to contact you about your account.
  residency:
  - region: Saudi Arabia (Jeddah)
    text: The API and this website run on Oracle Cloud in the Jeddah region of Saudi Arabia. Content sent to the API does not leave Saudi Arabia.
  - region: Hungary (EU)
    text: Sign-in emails and email correspondence pass through our email provider, Rackhost, in Hungary (European Union).
  retention:
  - period: not kept
    scope: Content sent to the API
    text: 'Content sent to the API: not kept.'
  - period: until you delete it
    scope: Account
    text: Your account is kept until you delete it
  - period: 12 months
    scope: Enquiries not leading to a subscription
    text: Enquiries that do not lead to a subscription are deleted within 12 months.
  - period: 90 days
    scope: Survey answers
    text: are deleted after 90 days, or earlier if you ask
  - period: null
    scope: Technical logs
    text: The log has a fixed maximum size and overwrites its oldest entries.
  rights:
  - right: Access
    text: You can ask what is held about you
  - right: Correction
    text: ask for it to be corrected or deleted
  - right: Restriction
    text: ask for processing to be restricted
  - right: Objection
    text: or object to it.
  - right: Complain to authority
    text: you may complain to the competent authority
  role:
    text: Who is responsible Yimello LLC, Sharjah Media City (Shams), Al Messaned, Al Bataeh, Sharjah, United Arab Emirates, Trade License 2430802.01.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: it is never sold or used for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: A question about Sahifa is sent, together with matching excerpts of our documentation and your last few questions in the same window, to Anthropic in the United States, which writes the answer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sahifa
provenance_date: '2026-11-10'
provider_name: Sahifa
provider_slug: sahifa
slug: sahifa-privacy-policy
source_date: '2026-11-10'
source_filename: sahifa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sahifa.dev/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sahifa\naid: sahifa\nurl: https://sahifa.dev/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Who is responsible Yimello LLC, Sharjah Media City (Shams), Al Messaned, Al Bataeh, Sharjah, United Arab\n    Emirates, Trade License 2430802.01.\ndata_categories:\n- category: identifying\n  text: Your email address, and if you give them, your company name and the language of our emails.\n- category: financial\n  text: company or personal name, VAT or tax number, country, billing address, contact person, email address and\n    optional phone number.\n- category: device\n  text: the IP address\
  \ of each demo request is held in the server's memory for up to one hour, then discarded.\n- category: communication\n  text: Messages you send us, and our replies.\n- category: other\n  text: The HTML, web addresses and settings in a request are processed in memory on our server in Jeddah, only\n    to produce the PDF or image you asked for.\npurposes:\n- purpose: Perform the requested service\n  text: Content is processed to perform the service you request.\n- purpose: Subscription and invoicing\n  text: Account and billing details are used to provide the subscription and to invoice it\n- purpose: Account contact and sign-in\n  text: The email address is used to send sign-in links, which work once and expire after 15 minutes, and to contact\n    you about your account.\nretention:\n- scope: Content sent to the API\n  period: not kept\n  text: 'Content sent to the API: not kept.'\n- scope: Account\n  period: until you delete it\n  text: Your account is kept until you delete it\n- scope:\
  \ Enquiries not leading to a subscription\n  period: 12 months\n  text: Enquiries that do not lead to a subscription are deleted within 12 months.\n- scope: Survey answers\n  period: 90 days\n  text: are deleted after 90 days, or earlier if you ask\n- scope: Technical logs\n  period: null\n  text: The log has a fixed maximum size and overwrites its oldest entries.\nresidency:\n- region: Saudi Arabia (Jeddah)\n  text: The API and this website run on Oracle Cloud in the Jeddah region of Saudi Arabia. Content sent to the API\n    does not leave Saudi Arabia.\n- region: Hungary (EU)\n  text: Sign-in emails and email correspondence pass through our email provider, Rackhost, in Hungary (European\n    Union).\ntransfers:\n- mechanism: other\n  text: A question about Sahifa is sent, together with matching excerpts of our documentation and your last few\n    questions in the same window, to Anthropic in the United States, which writes the answer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page, or email support@sahifa.dev\n  text: you can do that at any time from the account page, and your email address and company name are removed at\n    once, and from the encrypted backups within 35 days.\nrights:\n- right: Access\n  text: You can ask what is held about you\n- right: Correction\n  text: ask for it to be corrected or deleted\n- right: Restriction\n  text: ask for processing to be restricted\n- right: Objection\n  text: or object to it.\n- right: Complain to authority\n  text: you may complain to the competent authority\nsale_or_sharing:\n  stance: prohibited\n  text: it is never sold or used for advertising.\n"
source_yaml_url: https://artifacts.apis.io/sahifa/privacy/sahifa-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Sahifa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Screenshots
- Saudi Arabia
- Cloud
---
