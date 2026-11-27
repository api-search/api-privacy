---
api_specs:
- filename: emailoctopus-automation-api-openapi.yml
  format: yaml
  label: EmailOctopus Automation API
  slug: emailoctopus-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-automation-api-openapi.yml
- filename: emailoctopus-campaign-api-openapi.yml
  format: yaml
  label: EmailOctopus Campaign API
  slug: emailoctopus-campaign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-campaign-api-openapi.yml
- filename: emailoctopus-contact-api-openapi.yml
  format: yaml
  label: EmailOctopus Contact API
  slug: emailoctopus-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-contact-api-openapi.yml
- filename: emailoctopus-field-api-openapi.yml
  format: yaml
  label: EmailOctopus Field API
  slug: emailoctopus-field-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-field-api-openapi.yml
- filename: emailoctopus-list-api-openapi.yml
  format: yaml
  label: EmailOctopus List API
  slug: emailoctopus-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-list-api-openapi.yml
- filename: emailoctopus-tag-api-openapi.yml
  format: yaml
  label: EmailOctopus Tag API
  slug: emailoctopus-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emailoctopus/openapi/emailoctopus-tag-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your first and last name, email address, password (stored in hashed form), business or organisation name, industry, billing address and country
  - category: financial
    text: Your billing name, address and country, IP address, the date and amount of your last payment and a payment card token.
  - category: location
    text: your IP address (which we use for fraud and abuse detection and to suggest a billing currency)
  - category: device
    text: device, browser and operating system information
  - category: behavioral
    text: Your activities on, and use of, the Services which reveal your preferences, interests or manner of use of the Services and the times of use
  - category: communication
    text: The content of your correspondence with our support team, including any attachments
  deletion:
    route: Delete your account and data through your dashboard, or email privacy@emailoctopus.com
    text: You can delete your account and your data at any time through your dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Create and manage your account
    text: To perform our contract with you or to take steps at your request before entering into a contract
  - purpose: Marketing our Services
    text: Where you have given consent, or for our legitimate interests in promoting our Services to people who have signed up for an account with us
  - purpose: Statistical analysis
    text: Statistical analysis to help us manage our business
  - purpose: AI content moderation
    text: Screening content for phishing, fraud, spam and other abuse, including using automated and AI tools
  residency:
  - region: United States
    text: AI content moderation may run in other AWS regions, including the United States
  retention:
  - period: up to 25 months after your last sign-in or use of the Services
    scope: Account data
    text: for as long as your account is open, and for up to 25 months after your last sign-in or use of the Services
  - period: up to 90 days
    scope: Backups
    text: copies of your data may remain in backup storage for up to 90 days after deletion, after which they are overwritten
  - period: 6 years from the closure of your account
    scope: Invoices and accounting records
    text: 6 years from the closure of your account, to comply with our accounting and tax obligations
  - period: up to 5 years after a conversation is closed
    scope: Support correspondence
    text: up to 5 years after a conversation is closed
  rights:
  - right: Access
    text: Access to a copy of your personal data
  - right: Correction
    text: Correction (also known as rectification)
  - right: Erasure
    text: Erasure (also known as the right to be forgotten)
  - right: Restriction of use
    text: Restriction of use
  - right: Data portability
    text: Data portability
  - right: Withdraw consent
    text: Withdraw consent
  - right: Object
    text: To object to use
  role:
    text: We are the controller of personal data about our customers and our website visitors obtained via the Services
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will always treat your personal data with the utmost respect and never sell it.
  subprocessors:
    text: The providers who process our customers’ contact lists and content on our behalf (our sub-processors) are listed at https://emailoctopus.com/legal/subprocessors .
    url: https://emailoctopus.com/legal/subprocessors
  transfers:
  - mechanism: adequacy
    text: Transfers to the European Economic Area — UK adequacy regulations for the EEA.
  - mechanism: DPF
    text: for providers certified under the EU-US Data Privacy Framework and its UK Extension (the UK-US Data Bridge), the UK adequacy regulations for the United States
  - mechanism: SCC
    text: Otherwise, the International Data Transfer Agreement issued by the Information Commissioner, or the International Data Transfer Addendum to the European Commission’s Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EmailOctopus
provenance_date: '2026-11-09'
provider_name: EmailOctopus
provider_slug: emailoctopus
slug: emailoctopus-privacy-policy
source_date: '2026-11-09'
source_filename: emailoctopus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://emailoctopus.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EmailOctopus\naid: emailoctopus\nurl: https://emailoctopus.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of personal data about our customers and our website visitors obtained via the Services\ndata_categories:\n- category: identifying\n  text: Your first and last name, email address, password (stored in hashed form), business or organisation name,\n    industry, billing address and country\n- category: financial\n  text: Your billing name, address and country, IP address, the date and amount of your last payment and a payment\n    card token.\n- category:\
  \ location\n  text: your IP address (which we use for fraud and abuse detection and to suggest a billing currency)\n- category: device\n  text: device, browser and operating system information\n- category: behavioral\n  text: Your activities on, and use of, the Services which reveal your preferences, interests or manner of use of\n    the Services and the times of use\n- category: communication\n  text: The content of your correspondence with our support team, including any attachments\npurposes:\n- purpose: Create and manage your account\n  text: To perform our contract with you or to take steps at your request before entering into a contract\n- purpose: Marketing our Services\n  text: Where you have given consent, or for our legitimate interests in promoting our Services to people who have\n    signed up for an account with us\n- purpose: Statistical analysis\n  text: Statistical analysis to help us manage our business\n- purpose: AI content moderation\n  text: Screening content for\
  \ phishing, fraud, spam and other abuse, including using automated and AI tools\nretention:\n- scope: Account data\n  period: up to 25 months after your last sign-in or use of the Services\n  text: for as long as your account is open, and for up to 25 months after your last sign-in or use of the Services\n- scope: Backups\n  period: up to 90 days\n  text: copies of your data may remain in backup storage for up to 90 days after deletion, after which they are\n    overwritten\n- scope: Invoices and accounting records\n  period: 6 years from the closure of your account\n  text: 6 years from the closure of your account, to comply with our accounting and tax obligations\n- scope: Support correspondence\n  period: up to 5 years after a conversation is closed\n  text: up to 5 years after a conversation is closed\nresidency:\n- region: United States\n  text: AI content moderation may run in other AWS regions, including the United States\ntransfers:\n- mechanism: adequacy\n  text: Transfers to\
  \ the European Economic Area — UK adequacy regulations for the EEA.\n- mechanism: DPF\n  text: for providers certified under the EU-US Data Privacy Framework and its UK Extension (the UK-US Data Bridge),\n    the UK adequacy regulations for the United States\n- mechanism: SCC\n  text: Otherwise, the International Data Transfer Agreement issued by the Information Commissioner, or the International\n    Data Transfer Addendum to the European Commission’s Standard Contractual Clauses.\nsubprocessors:\n  url: https://emailoctopus.com/legal/subprocessors\n  text: The providers who process our customers’ contact lists and content on our behalf (our sub-processors) are\n    listed at https://emailoctopus.com/legal/subprocessors .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account and data through your dashboard, or email privacy@emailoctopus.com\n  text: You can delete your account and your data at any time through your dashboard.\nrights:\n- right: Access\n\
  \  text: Access to a copy of your personal data\n- right: Correction\n  text: Correction (also known as rectification)\n- right: Erasure\n  text: Erasure (also known as the right to be forgotten)\n- right: Restriction of use\n  text: Restriction of use\n- right: Data portability\n  text: Data portability\n- right: Withdraw consent\n  text: Withdraw consent\n- right: Object\n  text: To object to use\nsale_or_sharing:\n  stance: prohibited\n  text: We will always treat your personal data with the utmost respect and never sell it.\n"
source_yaml_url: https://artifacts.apis.io/emailoctopus/privacy/emailoctopus-privacy-policy.yml
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
summary_line: 29 quoted statements, read from EmailOctopus's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Email Marketing
- Newsletters
- Campaigns
- Automation
- Contacts
- List
- Marketing
- Webhook
- Transactional Email
- Subscriber Management
- Reporting
---
