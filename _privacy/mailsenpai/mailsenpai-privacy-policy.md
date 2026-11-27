---
api_specs:
- filename: mailsenpai-account-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Account API
  slug: mailsenpai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-account-api-openapi.yml
- filename: mailsenpai-log-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Log API
  slug: mailsenpai-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-log-api-openapi.yml
- filename: mailsenpai-sending-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Sending API
  slug: mailsenpai-sending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-sending-api-openapi.yml
- filename: mailsenpai-suppression-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Suppression API
  slug: mailsenpai-suppression-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-suppression-api-openapi.yml
- filename: mailsenpai-webhooks-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Webhooks API
  slug: mailsenpai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-webhooks-api-openapi.yml
- filename: mailsenpai-website-forms-api-openapi.yml
  format: yaml
  label: SMTP Senpai (MailSenpai) Website forms API
  slug: mailsenpai-website-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailsenpai/openapi/mailsenpai-website-forms-api-openapi.yml
claim_count: 34
description: ''
doc:
  data_categories:
  - category: identifying
    text: an identifier such as a name, an identification number, an online identifier
  - category: contact
    text: your name, telephone number, email address, the company you work for, etc.
  - category: financial
    text: company name, VAT number, tax code, address, email, phone, billing details
  - category: location
    text: approximate location derived from the IP address (country and city, used for clicks and unsubscribes)
  - category: behavioral
    text: 'Opens: individual or anonymous only.'
  - category: device
    text: type of email program, browser and device (user agent)
  - category: professional
    text: professional/employment details (e.g. university attended, knowledge of foreign languages, professional qualifications
  - category: communication
    text: the email address you enter, the domain checked, the IP address and browser of the request
  deletion:
    route: Contact the GDPR Privacy Center (contact form) or use the unsubscribe and tracking preference links
    text: To exercise your rights, contact the sender of the email.
  dpa:
    available: true
    text: under the contract and the data processing agreement ( Annex A )
    url: null
  purposes:
  - purpose: Service Provision
    text: 'to provide the Services, such as: allowing you to register on the Site'
  - purpose: Newsletter
    text: sending you the MailSenpai newsletter, with informational and commercial content about our services, if you have subscribed
  - purpose: Marketing
    text: to send you marketing communications, promotions and advertising, market research and surveys
  - purpose: Profiling
    text: to create a profile of you through the use of profiling cookies, where accepted
  - purpose: Abuse/Fraud
    text: to monitor how the Site is used, prevent or detect any abuse in the use of the Site, or any fraudulent activity
  - purpose: Compliance
    text: to fulfil legal obligations requiring MailSenpai to collect and/or further process certain types of Personal Data
  residency:
  - region: European Union
    text: Platform, relay and CRM data are hosted on servers located in the European Union.
  retention:
  - period: five (5) days
    scope: Browsing data
    text: at present the web contact data are not retained for more than five (5) days
  - period: 90 days
    scope: SMTP relay sending log
    text: The sending log (recipient address, outcome, bounce reason, technical delivery data) is kept for 90 days
  - period: 12 months
    scope: Individual email opens and clicks
    text: 'Individual opens and clicks: 12 months from the date of the event, then deleted.'
  - period: 365 days
    scope: Free website tools data
    text: 'Retention: 365 days from the request'
  - period: 10 years
    scope: Tax and accounting data for orders
    text: tax and accounting data relating to orders are kept for 10 years as required by law
  - period: 30 days
    scope: Visit recordings
    text: Recordings stay on our servers in the European Union and are deleted after 30 days.
  - period: null
    scope: Marketing, Newsletter and Profiling data
    text: Personal Data processed for Marketing, Newsletter and Profiling purposes will be retained by MailSenpai until you withdraw your consent.
  rights:
  - right: access
    text: for access to your Personal Data (or a copy of such Personal Data)
  - right: rectification
    text: for the rectification or updating of your Personal Data processed by MailSenpai
  - right: restriction
    text: for the restriction of the processing of your Personal Data by MailSenpai
  - right: portability
    text: to obtain the Personal Data concerning you in a structured, commonly used and machine-readable format
  - right: objection
    text: object to the processing of your Personal Data by MailSenpai (e.g. Soft Spam)
  - right: withdraw consent
    text: withdraw your consent for the purposes of Marketing, Newsletter and Profiling.
  - right: complaint
    text: you always have the right to lodge a complaint with the competent Supervisory Authority
  role:
    text: The Data Controller with regard to all Personal Data processed through the Site is Octotech Solutions
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission or other safeguards considered adequate
  - mechanism: DPF
    text: Meta and Google may transfer data to the United States under the EU-US Data Privacy Framework and Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SMTP Senpai (MailSenpai)
provenance_date: '2026-11-10'
provider_name: SMTP Senpai (MailSenpai)
provider_slug: mailsenpai
slug: mailsenpai-privacy-policy
source_date: '2026-11-10'
source_filename: mailsenpai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://en.mailsenpai.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SMTP Senpai (MailSenpai)\naid: mailsenpai\nurl: https://en.mailsenpai.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Data Controller with regard to all Personal Data processed through the Site is Octotech Solutions\ndata_categories:\n- category: identifying\n  text: an identifier such as a name, an identification number, an online identifier\n- category: contact\n  text: your name, telephone number, email address, the company you work for, etc.\n- category: financial\n  text: company name, VAT number, tax code, address, email, phone, billing details\n- category: location\n\
  \  text: approximate location derived from the IP address (country and city, used for clicks and unsubscribes)\n- category: behavioral\n  text: 'Opens: individual or anonymous only.'\n- category: device\n  text: type of email program, browser and device (user agent)\n- category: professional\n  text: professional/employment details (e.g. university attended, knowledge of foreign languages, professional\n    qualifications\n- category: communication\n  text: the email address you enter, the domain checked, the IP address and browser of the request\npurposes:\n- purpose: Service Provision\n  text: 'to provide the Services, such as: allowing you to register on the Site'\n- purpose: Newsletter\n  text: sending you the MailSenpai newsletter, with informational and commercial content about our services, if\n    you have subscribed\n- purpose: Marketing\n  text: to send you marketing communications, promotions and advertising, market research and surveys\n- purpose: Profiling\n  text: to create\
  \ a profile of you through the use of profiling cookies, where accepted\n- purpose: Abuse/Fraud\n  text: to monitor how the Site is used, prevent or detect any abuse in the use of the Site, or any fraudulent activity\n- purpose: Compliance\n  text: to fulfil legal obligations requiring MailSenpai to collect and/or further process certain types of Personal\n    Data\nretention:\n- scope: Browsing data\n  period: five (5) days\n  text: at present the web contact data are not retained for more than five (5) days\n- scope: SMTP relay sending log\n  period: 90 days\n  text: The sending log (recipient address, outcome, bounce reason, technical delivery data) is kept for 90 days\n- scope: Individual email opens and clicks\n  period: 12 months\n  text: 'Individual opens and clicks: 12 months from the date of the event, then deleted.'\n- scope: Free website tools data\n  period: 365 days\n  text: 'Retention: 365 days from the request'\n- scope: Tax and accounting data for orders\n  period: 10 years\n\
  \  text: tax and accounting data relating to orders are kept for 10 years as required by law\n- scope: Visit recordings\n  period: 30 days\n  text: Recordings stay on our servers in the European Union and are deleted after 30 days.\n- scope: Marketing, Newsletter and Profiling data\n  period: null\n  text: Personal Data processed for Marketing, Newsletter and Profiling purposes will be retained by MailSenpai\n    until you withdraw your consent.\nresidency:\n- region: European Union\n  text: Platform, relay and CRM data are hosted on servers located in the European Union.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by the European Commission or other safeguards considered adequate\n- mechanism: DPF\n  text: Meta and Google may transfer data to the United States under the EU-US Data Privacy Framework and Standard\n    Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: under the contract and the data\
  \ processing agreement ( Annex A )\ndeletion:\n  route: Contact the GDPR Privacy Center (contact form) or use the unsubscribe and tracking preference links\n  text: To exercise your rights, contact the sender of the email.\nrights:\n- right: access\n  text: for access to your Personal Data (or a copy of such Personal Data)\n- right: rectification\n  text: for the rectification or updating of your Personal Data processed by MailSenpai\n- right: restriction\n  text: for the restriction of the processing of your Personal Data by MailSenpai\n- right: portability\n  text: to obtain the Personal Data concerning you in a structured, commonly used and machine-readable format\n- right: objection\n  text: object to the processing of your Personal Data by MailSenpai (e.g. Soft Spam)\n- right: withdraw consent\n  text: withdraw your consent for the purposes of Marketing, Newsletter and Profiling.\n- right: complaint\n  text: you always have the right to lodge a complaint with the competent Supervisory\
  \ Authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailsenpai/privacy/mailsenpai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 34 quoted statements, read from SMTP Senpai (MailSenpai)'s own page on 2026-11-10.
synthetic: false
tags:
- Email Marketing
- B2B outreach
- SMTP relay
- Artificial Intelligence
- Newsletter platform
---
