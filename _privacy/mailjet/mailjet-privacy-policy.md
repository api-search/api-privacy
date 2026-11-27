---
api_specs:
- filename: mailjet-campaigns-api-openapi.yml
  format: yaml
  label: Mailjet Campaigns API
  slug: mailjet-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-campaigns-api-openapi.yml
- filename: mailjet-contact-lists-api-openapi.yml
  format: yaml
  label: Mailjet Contact Lists API
  slug: mailjet-contact-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-contact-lists-api-openapi.yml
- filename: mailjet-contacts-api-openapi.yml
  format: yaml
  label: Mailjet Contacts API
  slug: mailjet-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-contacts-api-openapi.yml
- filename: mailjet-event-api-openapi.yml
  format: yaml
  label: Mailjet Event API
  slug: mailjet-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-event-api-openapi.yml
- filename: mailjet-send-api-openapi.yml
  format: yaml
  label: Mailjet Send API
  slug: mailjet-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-send-api-openapi.yml
- filename: mailjet-senders-api-openapi.yml
  format: yaml
  label: Mailjet Senders API
  slug: mailjet-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-senders-api-openapi.yml
- filename: mailjet-statistics-api-openapi.yml
  format: yaml
  label: Mailjet Statistics API
  slug: mailjet-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-statistics-api-openapi.yml
- filename: mailjet-templates-api-openapi.yml
  format: yaml
  label: Mailjet Templates API
  slug: mailjet-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailjet/openapi/mailjet-templates-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: This includes the information you provide us when registering to use the platform (i.e. your name, company name, email address, postal address, other contact information you share with us, associated domain name and credit card information).
  - category: financial
    text: 'Payment details: method of payment for Sinch Email services and associated data such as billing address.'
  - category: communication
    text: we have access to the information contained in the subject and content of the emails that you send out
  - category: device
    text: 'Technical data: computer settings when stored, log information on use of portal/forum, IP-address.'
  - category: location
    text: Technical data; terminal equipment data, location data, page views and sessions
  deletion:
    route: Request erasure via the Data Protection Officer
    text: 'Right to Erasure (Right to Be Forgotten): You can request that we delete your personal data under certain circumstances'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Administering the customer relationship and billing
    text: To enable Sinch Email to administer, foster and develop its Customer relationship
  - purpose: Marketing
    text: Sending newsletters, information and invites for seminars or webinars
  - purpose: Analytics and product development
    text: Gathering insights related to the use of services, platforms and websites for the purpose of improving functionalities and the overall customer experience.
  - purpose: Information security
    text: including detecting, investigating and preventing threats and fraud and to find vulnerabilities.
  residency:
  - region: United States or Europe
    text: Your platform will be hosted from their data centers throughout the United States or Europe, based on where you have selected to deploy our services
  retention:
  - period: For the duration of the business relationship between Sinch Email and the customer
    scope: Customer contact and billing data
    text: For the duration of the business relationship between Sinch Email and the customer
  - period: 30 days
    scope: Email address validation data
    text: Email addresses in one-way encrypted (irreversible) form, event timestamps and event counts 30 days
  rights:
  - right: Access
    text: 'Right to Access: You can request access to your personal data stored or processed by us.'
  - right: Portability
    text: 'Right to Data Portability: If you request access to personal data about you that you yourself have provided'
  - right: Rectification
    text: 'Right to Rectification: You have the right to correct inaccurate or incomplete personal data.'
  - right: Erasure
    text: 'Right to Erasure (Right to Be Forgotten): You can request that we delete your personal data under certain circumstances'
  - right: Restriction
    text: 'Right to Restriction of Processing: You can request the temporary suspension of processing of your data'
  - right: Object
    text: You can object to the processing of your personal data for specific purposes
  - right: Withdraw consent
    text: you have the right to withdraw your consent at any time
  - right: Complain to supervisory authority
    text: You have the right to lodge a complaint with a supervisory authority if you believe your data rights have been violated.
  role:
    text: Please note that for most our services, we acts as a processor.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Sinch does not sell personal data
  subprocessors:
    text: We host the website and operate the platform using third parties, including Google Cloud Platform, AWS®, MacStadium and Rackspace®.
    url: null
  transfers:
  - mechanism: SCC
    text: Sinch ensures that the European Standard Contractual Clauses cover the transfers
  - mechanism: DPF
    text: Mailgun Technologies, Inc., a US based Sinch company, complies with the EU-U.S Data Privacy Framework
  - mechanism: BCR
    text: Binding Corporate Rules of the third parties importing the personal data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mailjet
provenance_date: '2026-11-10'
provider_name: Mailjet
provider_slug: mailjet
slug: mailjet-privacy-policy
source_date: '2026-11-10'
source_filename: mailjet-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mailjet.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mailjet\naid: mailjet\nurl: https://www.mailjet.com/legal/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Please note that for most our services, we acts as a processor.\ndata_categories:\n- category: contact\n  text: This includes the information you provide us when registering to use the platform (i.e. your name, company\n    name, email address, postal address, other contact information you share with us, associated domain name and\n    credit card information).\n- category: financial\n  text: 'Payment details: method of payment for Sinch Email services and associated data such\
  \ as billing address.'\n- category: communication\n  text: we have access to the information contained in the subject and content of the emails that you send out\n- category: device\n  text: 'Technical data: computer settings when stored, log information on use of portal/forum, IP-address.'\n- category: location\n  text: Technical data; terminal equipment data, location data, page views and sessions\npurposes:\n- purpose: Administering the customer relationship and billing\n  text: To enable Sinch Email to administer, foster and develop its Customer relationship\n- purpose: Marketing\n  text: Sending newsletters, information and invites for seminars or webinars\n- purpose: Analytics and product development\n  text: Gathering insights related to the use of services, platforms and websites for the purpose of improving functionalities\n    and the overall customer experience.\n- purpose: Information security\n  text: including detecting, investigating and preventing threats and fraud and\
  \ to find vulnerabilities.\nretention:\n- scope: Customer contact and billing data\n  period: For the duration of the business relationship between Sinch Email and the customer\n  text: For the duration of the business relationship between Sinch Email and the customer\n- scope: Email address validation data\n  period: 30 days\n  text: Email addresses in one-way encrypted (irreversible) form, event timestamps and event counts 30 days\nresidency:\n- region: United States or Europe\n  text: Your platform will be hosted from their data centers throughout the United States or Europe, based on where\n    you have selected to deploy our services\ntransfers:\n- mechanism: SCC\n  text: Sinch ensures that the European Standard Contractual Clauses cover the transfers\n- mechanism: DPF\n  text: Mailgun Technologies, Inc., a US based Sinch company, complies with the EU-U.S Data Privacy Framework\n- mechanism: BCR\n  text: Binding Corporate Rules of the third parties importing the personal data\nsubprocessors:\n\
  \  url: null\n  text: We host the website and operate the platform using third parties, including Google Cloud Platform, AWS®,\n    MacStadium and Rackspace®.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request erasure via the Data Protection Officer\n  text: 'Right to Erasure (Right to Be Forgotten): You can request that we delete your personal data under certain\n    circumstances'\nrights:\n- right: Access\n  text: 'Right to Access: You can request access to your personal data stored or processed by us.'\n- right: Portability\n  text: 'Right to Data Portability: If you request access to personal data about you that you yourself have provided'\n- right: Rectification\n  text: 'Right to Rectification: You have the right to correct inaccurate or incomplete personal data.'\n- right: Erasure\n  text: 'Right to Erasure (Right to Be Forgotten): You can request that we delete your personal data under certain\n    circumstances'\n- right: Restriction\n  text: 'Right\
  \ to Restriction of Processing: You can request the temporary suspension of processing of your data'\n- right: Object\n  text: You can object to the processing of your personal data for specific purposes\n- right: Withdraw consent\n  text: you have the right to withdraw your consent at any time\n- right: Complain to supervisory authority\n  text: You have the right to lodge a complaint with a supervisory authority if you believe your data rights have\n    been violated.\nsale_or_sharing:\n  stance: prohibited\n  text: Sinch does not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/mailjet/privacy/mailjet-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Mailjet's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Email Delivery
- Marketing Email
- SMTP
- Transactional Email
---
