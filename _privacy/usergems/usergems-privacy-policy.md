---
api_specs:
- filename: usergems-accounts-api-openapi.yml
  format: yaml
  label: UserGems Accounts API
  slug: usergems-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usergems/openapi/usergems-accounts-api-openapi.yml
- filename: usergems-contacts-api-openapi.yml
  format: yaml
  label: UserGems Contacts API
  slug: usergems-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usergems/openapi/usergems-contacts-api-openapi.yml
- filename: usergems-privacy-api-openapi.yml
  format: yaml
  label: UserGems Privacy API
  slug: usergems-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usergems/openapi/usergems-privacy-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and profile information: email address, name and company name when you register.'
  - category: contact
    text: Name, business title, employer, work email address, phone number and LinkedIn profile URL
  - category: financial
    text: We receive only the last 4 digits of the card number and transaction details.
  - category: location
    text: 'Location data: approximate location estimated from your IP address.'
  - category: behavioral
    text: 'Analytics data: your path to, through and out of the Website or Services, UTM source, time zone, first and last active times, and usage history.'
  - category: device
    text: 'Log data: IP address, operating system, browser details, unique identifiers, device type and version, referring URL, date and time of use, time spent, and errors.'
  - category: professional
    text: 'Public professional profiles, such as LinkedIn: full name, business title, department, current and past employers, and employment start and end dates for up to the last seven years, and the profile URL.'
  - category: communication
    text: 'Communications: name, email address, type of inquiry and anything else you choose to share when you contact us, including support and demo requests.'
  deletion:
    route: usergems.com/privacy-request, privacy@usergems.com, or phone 415 917 7944
    text: 'Online: usergems.com/privacy-request Email: privacy@usergems.com, subject line "Privacy Request" Phone: 415 917 7944'
  dpa:
    available: true
    text: Content customers put into the Services, including our AI features, is processed on their behalf under our customer agreements and data processing agreement.
    url: null
  purposes:
  - purpose: Provide the Services
    text: To provide the Services, including researching, verifying and monitoring the contacts customers ask about and reporting employment changes and related signals to them
  - purpose: Marketing
    text: To market our Services, including contacting and advertising to professionals at companies we want to reach and, for US prospects, prioritizing them based on interest signals.
  - purpose: Security and legal
    text: To prevent, investigate or report fraud or unlawful activity.
  residency:
  - region: United States
    text: We are based in the United States, and personal data is processed there.
  retention:
  - period: Duration of the contract, plus the applicable statute of limitations or legal retention period
    scope: Account, contract and payment data
    text: Duration of the contract, plus the applicable statute of limitations or legal retention period
  - period: Until 24 months after we last verified both that the information is up to date and that we still have a reason to market to you
    scope: Marketing data
    text: Until you unsubscribe, object or withdraw consent. Otherwise, until 24 months after we last verified both that the information is up to date and that we still have a reason to market to you
  - period: Up to 3 years
    scope: Log and analytics data
    text: Log and analytics data Up to 3 years
  - period: Up to 3 years after the last interaction
    scope: Communications and support
    text: Up to 3 years after the last interaction
  rights:
  - right: Access
    text: You can also ask to access, correct or receive a copy of your personal information using the same routes.
  - right: Delete
    text: Delete personal information we hold about you.
  - right: Correct
    text: Correct inaccurate personal information.
  - right: Portability
    text: Receive a portable copy of your personal information.
  - right: Opt out of sharing
    text: Opt out of sharing for cross-context behavioral advertising, and of any future sale of your personal information.
  - right: Object
    text: You can object at any time to processing based on our legitimate interests, including our own marketing and advertising.
  role:
    text: UserGems is the data controller for personal information we collect for our own purposes
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information, and we have not sold personal information in the last 12 months.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers from the EEA we rely on the European Commission's Standard Contractual Clauses.
  - mechanism: other
    text: For the UK we rely on the UK International Data Transfer Addendum, and for Switzerland on the Standard Contractual Clauses as recognized by the Swiss Federal Data Protection and Information Commissioner.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UserGems
provenance_date: '2026-11-10'
provider_name: UserGems
provider_slug: usergems
slug: usergems-privacy-policy
source_date: '2026-11-10'
source_filename: usergems-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.usergems.com/legal-security/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UserGems\naid: usergems\nurl: https://www.usergems.com/legal-security/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: UserGems is the data controller for personal information we collect for our own purposes\ndata_categories:\n- category: identifying\n  text: 'Account and profile information: email address, name and company name when you register.'\n- category: contact\n  text: Name, business title, employer, work email address, phone number and LinkedIn profile URL\n- category: financial\n  text: We receive only the last 4 digits of the card number and transaction details.\n- category:\
  \ location\n  text: 'Location data: approximate location estimated from your IP address.'\n- category: behavioral\n  text: 'Analytics data: your path to, through and out of the Website or Services, UTM source, time zone, first\n    and last active times, and usage history.'\n- category: device\n  text: 'Log data: IP address, operating system, browser details, unique identifiers, device type and version, referring\n    URL, date and time of use, time spent, and errors.'\n- category: professional\n  text: 'Public professional profiles, such as LinkedIn: full name, business title, department, current and past\n    employers, and employment start and end dates for up to the last seven years, and the profile URL.'\n- category: communication\n  text: 'Communications: name, email address, type of inquiry and anything else you choose to share when you contact\n    us, including support and demo requests.'\npurposes:\n- purpose: Provide the Services\n  text: To provide the Services, including researching,\
  \ verifying and monitoring the contacts customers ask about\n    and reporting employment changes and related signals to them\n- purpose: Marketing\n  text: To market our Services, including contacting and advertising to professionals at companies we want to reach\n    and, for US prospects, prioritizing them based on interest signals.\n- purpose: Security and legal\n  text: To prevent, investigate or report fraud or unlawful activity.\nretention:\n- scope: Account, contract and payment data\n  period: Duration of the contract, plus the applicable statute of limitations or legal retention period\n  text: Duration of the contract, plus the applicable statute of limitations or legal retention period\n- scope: Marketing data\n  period: Until 24 months after we last verified both that the information is up to date and that we still have\n    a reason to market to you\n  text: Until you unsubscribe, object or withdraw consent. Otherwise, until 24 months after we last verified both\n    that\
  \ the information is up to date and that we still have a reason to market to you\n- scope: Log and analytics data\n  period: Up to 3 years\n  text: Log and analytics data Up to 3 years\n- scope: Communications and support\n  period: Up to 3 years after the last interaction\n  text: Up to 3 years after the last interaction\nresidency:\n- region: United States\n  text: We are based in the United States, and personal data is processed there.\ntransfers:\n- mechanism: SCC\n  text: For transfers from the EEA we rely on the European Commission's Standard Contractual Clauses.\n- mechanism: other\n  text: For the UK we rely on the UK International Data Transfer Addendum, and for Switzerland on the Standard Contractual\n    Clauses as recognized by the Swiss Federal Data Protection and Information Commissioner.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Content customers put into the Services, including our AI features, is processed on their behalf\
  \ under our\n    customer agreements and data processing agreement.\ndeletion:\n  route: usergems.com/privacy-request, privacy@usergems.com, or phone 415 917 7944\n  text: 'Online: usergems.com/privacy-request Email: privacy@usergems.com, subject line \"Privacy Request\" Phone:\n    415 917 7944'\nrights:\n- right: Access\n  text: You can also ask to access, correct or receive a copy of your personal information using the same routes.\n- right: Delete\n  text: Delete personal information we hold about you.\n- right: Correct\n  text: Correct inaccurate personal information.\n- right: Portability\n  text: Receive a portable copy of your personal information.\n- right: Opt out of sharing\n  text: Opt out of sharing for cross-context behavioral advertising, and of any future sale of your personal information.\n- right: Object\n  text: You can object at any time to processing based on our legitimate interests, including our own marketing\n    and advertising.\nsale_or_sharing:\n  stance: conditional\n\
  \  text: We do not sell personal information, and we have not sold personal information in the last 12 months.\n"
source_yaml_url: https://artifacts.apis.io/usergems/privacy/usergems-privacy-policy.yml
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
- sale_or_sharing
summary_line: 28 quoted statements, read from UserGems's own page on 2026-11-10.
synthetic: false
tags:
- Sales Intelligence
- Outbound
- Account Based Marketing
- Champion Tracking
- Job Changes
- Buying Signals
- AI Scoring
- Sales Engagement
- CRM
- Revenue Operations
- Go-To-Market
- MCP
- AI Agents
---
