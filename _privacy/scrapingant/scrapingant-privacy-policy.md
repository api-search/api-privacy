---
api_specs:
- filename: scrapingant-scraping-api-openapi.yml
  format: yaml
  label: ScrapingAnt Scraping API
  slug: scrapingant-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingant/openapi/scrapingant-scraping-api-openapi.yml
- filename: scrapingant-usage-api-openapi.yml
  format: yaml
  label: ScrapingAnt Usage API
  slug: scrapingant-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingant/openapi/scrapingant-usage-api-openapi.yml
- filename: scrapingant-general-api-openapi.yml
  format: yaml
  label: ScrapingAnt General API
  slug: scrapingant-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrapingant/openapi/scrapingant-general-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: we require your username (name) and your email address.
  - category: identifying
    text: We collect your IP address in order to remember your user settings as part of our legitimate interest.
  - category: behavioral
    text: We also use cookies and other tracking technologies on our Site.
  - category: financial
    text: we need the transactions data to provide our services and for accounting purposes.
  - category: professional
    text: we may ask you to provide us with your name, your email address and information on your workplace.
  deletion:
    route: contact us
    text: If one of the aforementioned reasons applies and you wish to request the erasure of personal data stored by us, you may contact us at any time.
  dpa:
    available: true
    text: we sign data processing agreements (DPAs) with our clients.
    url: null
  purposes:
  - purpose: contacting users
    text: In order to have the ability of contacting you when needed or at your request;
  - purpose: analytics and browsing experience
    text: For analytics and browsing experience, in order to identify your country and your language
  - purpose: authentication
    text: For authorization and authentication, so only you have the access to your account;
  - purpose: marketing with consent
    text: For the marketing purposes and special offers
  - purpose: invoicing and payments
    text: For invoicing and processing of payments.
  - purpose: legal compliance
    text: For complying with applicable laws and regulations of countries where services of ScrapingAnt are available.
  residency:
  - region: USA
    text: All the data collected is located on the servers of Amazon in the USA.
  retention:
  - period: 12 months
    scope: data collected while using the Site
    text: All the data you provide us with and we automatically collect as a data controller while you are using our Site is stored for 12 months.
  - period: null
    scope: accounts
    text: as long as you keep the account active and 12 months after you delete it.
  - period: 24 months
    scope: how you found us record
    text: is kept for no longer than 24 months from the date you created your account
  rights:
  - right: confirmation
    text: You have a right to obtain confirmation from the controller as to whether or not your personal data is being processed.
  - right: access
    text: 'You have a right to obtain at any time information from the controller about:'
  - right: rectification
    text: You have the right to obtain the rectification of inaccurate personal data concerning you from the controller without undue delay.
  - right: erasure
    text: You have the right to have your personal data deleted from the controller’s records and access without undue delay
  - right: restriction of processing
    text: 'You have the right to obtain restriction of processing from the controller where one of the following applies:'
  - right: data portability
    text: You have the right to receive your personal data, which was provided to a controller, in a structured, commonly used and machine-readable format.
  - right: object
    text: You have the right to object, on grounds relating to your particular situation, at any time
  - right: withdraw consent
    text: You have the right to withdraw your consent to processing of your personal data at any time.
  role:
    text: We are the controller in relation to your personal data collected for the purposes herein.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Using the API with Sendgrid (a service of Twilio, Ireland), we send you our newsletter and special purposes.
    url: null
  transfers:
  - mechanism: other
    text: We may transfer your personal data to countries outside the EU and EEA (e.g. Ukraine, the USA etc.)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ScrapingAnt
provenance_date: '2026-11-10'
provider_name: ScrapingAnt
provider_slug: scrapingant
slug: scrapingant-privacy-policy
source_date: '2026-11-10'
source_filename: scrapingant-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scrapingant.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ScrapingAnt\naid: scrapingant\nurl: https://scrapingant.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller in relation to your personal data collected for the purposes herein.\ndata_categories:\n- category: contact\n  text: we require your username (name) and your email address.\n- category: identifying\n  text: We collect your IP address in order to remember your user settings as part of our legitimate interest.\n- category: behavioral\n  text: We also use cookies and other tracking technologies on our Site.\n- category: financial\n  text: we need the\
  \ transactions data to provide our services and for accounting purposes.\n- category: professional\n  text: we may ask you to provide us with your name, your email address and information on your workplace.\npurposes:\n- purpose: contacting users\n  text: In order to have the ability of contacting you when needed or at your request;\n- purpose: analytics and browsing experience\n  text: For analytics and browsing experience, in order to identify your country and your language\n- purpose: authentication\n  text: For authorization and authentication, so only you have the access to your account;\n- purpose: marketing with consent\n  text: For the marketing purposes and special offers\n- purpose: invoicing and payments\n  text: For invoicing and processing of payments.\n- purpose: legal compliance\n  text: For complying with applicable laws and regulations of countries where services of ScrapingAnt are available.\nretention:\n- scope: data collected while using the Site\n  period: 12 months\n\
  \  text: All the data you provide us with and we automatically collect as a data controller while you are using our\n    Site is stored for 12 months.\n- scope: accounts\n  period: null\n  text: as long as you keep the account active and 12 months after you delete it.\n- scope: how you found us record\n  period: 24 months\n  text: is kept for no longer than 24 months from the date you created your account\nresidency:\n- region: USA\n  text: All the data collected is located on the servers of Amazon in the USA.\ntransfers:\n- mechanism: other\n  text: We may transfer your personal data to countries outside the EU and EEA (e.g. Ukraine, the USA etc.)\nsubprocessors:\n  url: null\n  text: Using the API with Sendgrid (a service of Twilio, Ireland), we send you our newsletter and special purposes.\ndpa:\n  available: true\n  url: null\n  text: we sign data processing agreements (DPAs) with our clients.\ndeletion:\n  route: contact us\n  text: If one of the aforementioned reasons applies and\
  \ you wish to request the erasure of personal data stored\n    by us, you may contact us at any time.\nrights:\n- right: confirmation\n  text: You have a right to obtain confirmation from the controller as to whether or not your personal data is being\n    processed.\n- right: access\n  text: 'You have a right to obtain at any time information from the controller about:'\n- right: rectification\n  text: You have the right to obtain the rectification of inaccurate personal data concerning you from the controller\n    without undue delay.\n- right: erasure\n  text: You have the right to have your personal data deleted from the controller’s records and access without undue\n    delay\n- right: restriction of processing\n  text: 'You have the right to obtain restriction of processing from the controller where one of the following applies:'\n- right: data portability\n  text: You have the right to receive your personal data, which was provided to a controller, in a structured, commonly\n  \
  \  used and machine-readable format.\n- right: object\n  text: You have the right to object, on grounds relating to your particular situation, at any time\n- right: withdraw consent\n  text: You have the right to withdraw your consent to processing of your personal data at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scrapingant/privacy/scrapingant-privacy-policy.yml
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
summary_line: 28 quoted statements, read from ScrapingAnt's own page on 2026-11-10.
synthetic: false
tags:
- Data Extraction
- Proxies
- Web Scraping
- Browser Automation
- AI Agents
- MCP
- LLM
- Data Collection
- Web Data
---
