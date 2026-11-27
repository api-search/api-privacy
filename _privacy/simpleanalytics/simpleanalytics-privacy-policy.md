---
api_specs:
- filename: simpleanalytics-events-api-openapi.yml
  format: yaml
  label: Simple Analytics Events API
  slug: simpleanalytics-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-events-api-openapi.yml
- filename: simpleanalytics-export-api-openapi.yml
  format: yaml
  label: Simple Analytics Export API
  slug: simpleanalytics-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-export-api-openapi.yml
- filename: simpleanalytics-stats-api-openapi.yml
  format: yaml
  label: Simple Analytics Stats API
  slug: simpleanalytics-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-stats-api-openapi.yml
- filename: simpleanalytics-websites-api-openapi.yml
  format: yaml
  label: Simple Analytics Websites API
  slug: simpleanalytics-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-websites-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process the name of your website, email address and credit card or other payment details in order to register you for our services.
  - category: behavioral
    text: The data will mainly include, but not be limited to, the country in which the visitor is located, the pages that are visited, the device and browser with which these pages are visited and how someone arrived at these pages.
  - category: communication
    text: If you want to contact us via the website, we ask for the content of your message.
  deletion:
    route: Delete your account
    text: When you delete your account, we will delete both your and your visitors' data.
  dpa:
    available: null
    text: We conclude processing agreements with these third parties to optimally protect your privacy.
    url: null
  purposes:
  - purpose: Account registration
    text: We process the name of your website, email address and credit card or other payment details in order to register you for our services.
  - purpose: Visitor analytics
    text: We use this information to provide an insight in visits to your website and to keep you satisfied during the term of our agreement.
  - purpose: Direct marketing
    text: We process your email for direct marketing.
  - purpose: Affiliate marketing
    text: We process your name, email address and bank account number for affiliate marketing.
  residency:
  - region: Netherlands
    text: This data will be sent directly to our servers in the Netherlands and will not be processed abroad.
  retention:
  - period: 90 days
    scope: Backup after account deletion
    text: A backup of this data is stored for up to 90 days after the end of our agreement.
  - period: 7 years
    scope: Invoice data
    text: According to a legal obligation of the Dutch Tax and Customs Administration, we are required to store invoice data for 7 years.
  rights:
  - right: Access
    text: You can request to view your data at any time.
  - right: Correction
    text: If you want to have your data adjusted, corrected, supplemented, protected or erased, you can submit a request hereto.
  - right: Objection
    text: You can object to the processing of your data.
  - right: Data transfer
    text: If you want to transfer your data to another provider, we will provide your data in a structured and commonly used form that can be accessed by common digital systems.
  - right: Withdrawal of consent
    text: When we process data based on your explicit consent, you have the right to withdraw your consent.
  role:
    text: We are the controller of your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Simple Analytics
provenance_date: '2026-11-10'
provider_name: Simple Analytics
provider_slug: simpleanalytics
slug: simpleanalytics-privacy-policy
source_date: '2026-11-10'
source_filename: simpleanalytics-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.simpleanalytics.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Simple Analytics\naid: simpleanalytics\nurl: https://www.simpleanalytics.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of your personal data.\ndata_categories:\n- category: identifying\n  text: We process the name of your website, email address and credit card or other payment details in order to\n    register you for our services.\n- category: behavioral\n  text: The data will mainly include, but not be limited to, the country in which the visitor is located, the pages\n    that are visited, the device and browser with which these pages are visited\
  \ and how someone arrived at these\n    pages.\n- category: communication\n  text: If you want to contact us via the website, we ask for the content of your message.\npurposes:\n- purpose: Account registration\n  text: We process the name of your website, email address and credit card or other payment details in order to\n    register you for our services.\n- purpose: Visitor analytics\n  text: We use this information to provide an insight in visits to your website and to keep you satisfied during\n    the term of our agreement.\n- purpose: Direct marketing\n  text: We process your email for direct marketing.\n- purpose: Affiliate marketing\n  text: We process your name, email address and bank account number for affiliate marketing.\nretention:\n- scope: Backup after account deletion\n  period: 90 days\n  text: A backup of this data is stored for up to 90 days after the end of our agreement.\n- scope: Invoice data\n  period: 7 years\n  text: According to a legal obligation of the Dutch\
  \ Tax and Customs Administration, we are required to store invoice\n    data for 7 years.\nresidency:\n- region: Netherlands\n  text: This data will be sent directly to our servers in the Netherlands and will not be processed abroad.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: We conclude processing agreements with these third parties to optimally protect your privacy.\ndeletion:\n  route: Delete your account\n  text: When you delete your account, we will delete both your and your visitors' data.\nrights:\n- right: Access\n  text: You can request to view your data at any time.\n- right: Correction\n  text: If you want to have your data adjusted, corrected, supplemented, protected or erased, you can submit a request\n    hereto.\n- right: Objection\n  text: You can object to the processing of your data.\n- right: Data transfer\n  text: If you want to transfer your data to another provider, we will provide your data in a structured\
  \ and commonly\n    used form that can be accessed by common digital systems.\n- right: Withdrawal of consent\n  text: When we process data based on your explicit consent, you have the right to withdraw your consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/simpleanalytics/privacy/simpleanalytics-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Simple Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Privacy
- Cookieless
- GDPR
- Event
- Data Export
- Europe
---
