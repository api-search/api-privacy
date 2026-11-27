---
api_specs:
- filename: aptean-consumers-api-openapi.yml
  format: yaml
  label: Aptean Consumers API
  slug: aptean-consumers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-consumers-api-openapi.yml
- filename: aptean-events-api-openapi.yml
  format: yaml
  label: Aptean Events API
  slug: aptean-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-events-api-openapi.yml
- filename: aptean-producers-api-openapi.yml
  format: yaml
  label: Aptean Producers API
  slug: aptean-producers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-producers-api-openapi.yml
- filename: aptean-event-definitions-api-openapi.yml
  format: yaml
  label: Aptean Event Definitions API
  slug: aptean-event-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-event-definitions-api-openapi.yml
- filename: aptean-public-keys-api-openapi.yml
  format: yaml
  label: Aptean Public Keys API
  slug: aptean-public-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aptean/openapi/aptean-public-keys-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data - includes first name, last name, username or similar identifier, title, department and reporting relationship.
  - category: contact
    text: Contact Data - includes billing address, delivery address, email address and telephone numbers.
  - category: financial
    text: Transaction Data - includes details of products and services you have purchased from us.
  - category: location
    text: Technical Data - includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location
  - category: behavioral
    text: Usage Data - includes information about how you use our websites, products and services.
  - category: device
    text: Technical Data - includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location, browser plug-in types and versions, operating system and platform
  - category: professional
    text: Job Recruitment Data - includes contact data, cv and resume data, details about your qualifications, skills, experience, employment history
  - category: health
    text: whether or not you have a disability
  deletion:
    route: Request erasure by contacting the DPO or Email
    text: Request erasure of your personal data. This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.
  dpa:
    available: true
    text: Data Processor for content you or your users upload, processed on your behalf under the applicable Data Processing Agreement.
    url: null
  purposes:
  - purpose: Responding to inquiries and requests
    text: To respond to your inquiries or to process your requests (such as to receive promotional materials)
  - purpose: Marketing
    text: 'Marketing: To deliver marketing communications to you and measure or understand the effectiveness of these we serve to you'
  - purpose: Analytics
    text: 'Analytics: To use data analytics to improve our website, products/services, marketing, customer relationships and experiences'
  - purpose: Contract administration
    text: 'Contract Requirements: To administer all parts of our contract with you including without limitation processing and delivering your order, managing payments'
  - purpose: Job applications
    text: 'Job Application: To process and manage your job application, including assessing your qualifications'
  residency:
  - region: United States
    text: Aptean primarily stores the personal data we collect in the United States.
  retention:
  - period: six years
    scope: Basic customer information
    text: By law we have to keep basic information about our customers (including Contact, Identity, Financial and Transaction Data) for six years after they cease being customers.
  - period: 10 years
    scope: Cookies
    text: Except for essential cookies, all cookies will expire after 10 years
  rights:
  - right: access
    text: Request access to your personal data (commonly known as a "data subject access request").
  - right: correction
    text: Request correction of the personal data that we hold about you.
  - right: erasure
    text: Request erasure of your personal data.
  - right: objection
    text: Object to processing of your personal data where we are relying on a legitimate interest
  - right: restriction
    text: Request restriction of processing of your personal data.
  - right: portability
    text: Request the transfer of your personal data to you or to a third party.
  - right: withdraw consent
    text: Withdraw consent at any time where we are relying on consent to process your personal data.
  role:
    text: as a data controller whether received from our websites or collected by other means
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold any categories of personal data, including children's personal data, in the past 12 months.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Aptean, Inc. complies with the EU-U.S. Data Privacy Framework Program (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)
  - mechanism: SCC
    text: We may use specific contracts approved by the European Commission which give personal data the same protection it has in Europe
  - mechanism: adequacy
    text: We will only transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aptean
provenance_date: '2026-11-09'
provider_name: Aptean
provider_slug: aptean
slug: aptean-privacy-policy
source_date: '2026-11-09'
source_filename: aptean-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aptean.com/en-US/privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aptean\naid: aptean\nurl: https://www.aptean.com/en-US/privacy-statement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: as a data controller whether received from our websites or collected by other means\ndata_categories:\n- category: identifying\n  text: Identity Data - includes first name, last name, username or similar identifier, title, department and reporting\n    relationship.\n- category: contact\n  text: Contact Data - includes billing address, delivery address, email address and telephone numbers.\n- category: financial\n  text: Transaction Data - includes details of products and\
  \ services you have purchased from us.\n- category: location\n  text: Technical Data - includes internet protocol (IP) address, your login data, browser type and version, time\n    zone setting and location\n- category: behavioral\n  text: Usage Data - includes information about how you use our websites, products and services.\n- category: device\n  text: Technical Data - includes internet protocol (IP) address, your login data, browser type and version, time\n    zone setting and location, browser plug-in types and versions, operating system and platform\n- category: professional\n  text: Job Recruitment Data - includes contact data, cv and resume data, details about your qualifications, skills,\n    experience, employment history\n- category: health\n  text: whether or not you have a disability\npurposes:\n- purpose: Responding to inquiries and requests\n  text: To respond to your inquiries or to process your requests (such as to receive promotional materials)\n- purpose: Marketing\n\
  \  text: 'Marketing: To deliver marketing communications to you and measure or understand the effectiveness of these\n    we serve to you'\n- purpose: Analytics\n  text: 'Analytics: To use data analytics to improve our website, products/services, marketing, customer relationships\n    and experiences'\n- purpose: Contract administration\n  text: 'Contract Requirements: To administer all parts of our contract with you including without limitation processing\n    and delivering your order, managing payments'\n- purpose: Job applications\n  text: 'Job Application: To process and manage your job application, including assessing your qualifications'\nretention:\n- scope: Basic customer information\n  period: six years\n  text: By law we have to keep basic information about our customers (including Contact, Identity, Financial and\n    Transaction Data) for six years after they cease being customers.\n- scope: Cookies\n  period: 10 years\n  text: Except for essential cookies, all cookies will\
  \ expire after 10 years\nresidency:\n- region: United States\n  text: Aptean primarily stores the personal data we collect in the United States.\ntransfers:\n- mechanism: DPF\n  text: Aptean, Inc. complies with the EU-U.S. Data Privacy Framework Program (EU-U.S. DPF), the UK Extension to\n    the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)\n- mechanism: SCC\n  text: We may use specific contracts approved by the European Commission which give personal data the same protection\n    it has in Europe\n- mechanism: adequacy\n  text: We will only transfer your personal data to countries that have been deemed to provide an adequate level\n    of protection for personal data by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data Processor for content you or your users upload, processed on your behalf under the applicable Data\n    Processing Agreement.\ndeletion:\n  route: Request erasure by contacting\
  \ the DPO or Email\n  text: Request erasure of your personal data. This enables you to ask us to delete or remove personal data where\n    there is no good reason for us continuing to process it.\nrights:\n- right: access\n  text: Request access to your personal data (commonly known as a \"data subject access request\").\n- right: correction\n  text: Request correction of the personal data that we hold about you.\n- right: erasure\n  text: Request erasure of your personal data.\n- right: objection\n  text: Object to processing of your personal data where we are relying on a legitimate interest\n- right: restriction\n  text: Request restriction of processing of your personal data.\n- right: portability\n  text: Request the transfer of your personal data to you or to a third party.\n- right: withdraw consent\n  text: Withdraw consent at any time where we are relying on consent to process your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: We have not sold any categories of\
  \ personal data, including children's personal data, in the past 12 months.\n"
source_yaml_url: https://artifacts.apis.io/aptean/privacy/aptean-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Aptean's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- ERP
- Supply Chain
- Integration
- Event-Driven
- Webhook
- Enterprise Software
---
