---
api_specs:
- filename: lawvu-contracts-api-openapi.yml
  format: yaml
  label: LawVu Contracts API
  slug: lawvu-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-contracts-api-openapi.yml
- filename: lawvu-fields-api-openapi.yml
  format: yaml
  label: LawVu Fields API
  slug: lawvu-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-fields-api-openapi.yml
- filename: lawvu-files-api-openapi.yml
  format: yaml
  label: LawVu Files API
  slug: lawvu-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-files-api-openapi.yml
- filename: lawvu-invoices-api-openapi.yml
  format: yaml
  label: LawVu Invoices API
  slug: lawvu-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-invoices-api-openapi.yml
- filename: lawvu-matters-api-openapi.yml
  format: yaml
  label: LawVu Matters API
  slug: lawvu-matters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-matters-api-openapi.yml
- filename: lawvu-teams-api-openapi.yml
  format: yaml
  label: LawVu Teams API
  slug: lawvu-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-teams-api-openapi.yml
- filename: lawvu-users-api-openapi.yml
  format: yaml
  label: LawVu Users API
  slug: lawvu-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawvu/openapi/lawvu-users-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers , such as names, phone numbers, email addresses, location information, IP addresses and/or other device identifying data.
  - category: professional
    text: Professional Information , such as current employer, occupation, industries, professional licenses, work experience and employment histories, and other qualifications.
  - category: financial
    text: Financial information , such as payment information you provide when making a purchase through our Website.
  - category: behavioral
    text: Internet or other electronic network activity information , such as the website domain visited; which activities and offerings are used, how, and for how long
  - category: location
    text: Geolocation information , such as country codes, IP addresses, and language preferences.
  - category: device
    text: Electronic information , such as information about operating systems, device types, information about browsers
  - category: communication
    text: Audio, electronic and visual informatio n, such as, signatures, records of our interactions, information contained in your correspondence with us
  - category: demographic
    text: Education Information , such as your educational background.
  deletion:
    route: email privacy@lawvu.com
    text: you can do this by emailing our Privacy Officer or Data Protection Officer at privacy@lawvu.com
  dpa:
    available: null
    text: subject to any applicable restrictions contained in our data processing addendum with the relevant customer
    url: null
  purposes:
  - purpose: security and fraud prevention
    text: for security purposes in order to identify activity that is suspicious or potentially fraudulent
  - purpose: billing
    text: to bill you (or the customer on whose behalf you are acting) and to collect money that is owed
  - purpose: marketing with consent
    text: to send you marketing and promotional messages and other information that may be of interest to you where you have consented to receiving such material.
  - purpose: usage analysis and improvement
    text: to analyse and report on usage of the Website and Service, so we can improve the Website and Service
  retention:
  - period: null
    scope: personal information generally
    text: until we no longer have a valid reason for keeping it; until you request us to stop using it; or for as long as required by law
  - period: 7 years
    scope: invoice information
    text: we keep invoice information for 7 years to fulfill our tax obligations
  - period: up to 12 months
    scope: backups and logs
    text: we do keep backups and logs for up to 12 months before they are automatically deleted
  rights:
  - right: access
    text: You have the right to access your readily retrievable Personal Information that we hold about you
  - right: correction
    text: to ask for it to be corrected if you think it is wrong or to be deleted
  - right: erasure
    text: in certain circumstances, have your Personal Information erased
  - right: restriction
    text: restrict the processing of your Personal Information
  - right: portability
    text: move, copy or transfer your Personal Information easily for your own purposes across different services
  - right: objection
    text: object to processing where we rely on our legitimate interests as the lawful basis for processing
  - right: withdraw consent
    text: withdraw your consent at any time, where our processing of your Personal Information is based on consent
  - right: complaint
    text: lodge a complaint with an appropriate supervisory authority
  role:
    text: We process this User Information as an agent for our customers (under the New Zealand Privacy Act 2020 ( NZPA )) and, if applicable, as a data processor (under the General Data Protection Regulation (EU) 2016/679 ( GDPR )) or as service provider
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required by law, we have put in place measures (such as standard contractual clauses) to adequately protect personal information that we transfer across borders.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LawVu
provenance_date: '2026-11-09'
provider_name: LawVu
provider_slug: lawvu
slug: lawvu-privacy-policy
source_date: '2026-11-09'
source_filename: lawvu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lawvu.com/trust-center/privacy/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LawVu\naid: lawvu\nurl: https://lawvu.com/trust-center/privacy/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We process this User Information as an agent for our customers (under the New Zealand Privacy Act 2020 (\n    NZPA )) and, if applicable, as a data processor (under the General Data Protection Regulation (EU) 2016/679\n    ( GDPR )) or as service provider\ndata_categories:\n- category: identifying\n  text: Identifiers , such as names, phone numbers, email addresses, location information, IP addresses and/or other\n    device identifying data.\n- category: professional\n \
  \ text: Professional Information , such as current employer, occupation, industries, professional licenses, work\n    experience and employment histories, and other qualifications.\n- category: financial\n  text: Financial information , such as payment information you provide when making a purchase through our Website.\n- category: behavioral\n  text: Internet or other electronic network activity information , such as the website domain visited; which activities\n    and offerings are used, how, and for how long\n- category: location\n  text: Geolocation information , such as country codes, IP addresses, and language preferences.\n- category: device\n  text: Electronic information , such as information about operating systems, device types, information about browsers\n- category: communication\n  text: Audio, electronic and visual informatio n, such as, signatures, records of our interactions, information\n    contained in your correspondence with us\n- category: demographic\n  text: Education\
  \ Information , such as your educational background.\npurposes:\n- purpose: security and fraud prevention\n  text: for security purposes in order to identify activity that is suspicious or potentially fraudulent\n- purpose: billing\n  text: to bill you (or the customer on whose behalf you are acting) and to collect money that is owed\n- purpose: marketing with consent\n  text: to send you marketing and promotional messages and other information that may be of interest to you where\n    you have consented to receiving such material.\n- purpose: usage analysis and improvement\n  text: to analyse and report on usage of the Website and Service, so we can improve the Website and Service\nretention:\n- scope: personal information generally\n  period: null\n  text: until we no longer have a valid reason for keeping it; until you request us to stop using it; or for as\n    long as required by law\n- scope: invoice information\n  period: 7 years\n  text: we keep invoice information for 7 years\
  \ to fulfill our tax obligations\n- scope: backups and logs\n  period: up to 12 months\n  text: we do keep backups and logs for up to 12 months before they are automatically deleted\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required by law, we have put in place measures (such as standard contractual clauses) to adequately\n    protect personal information that we transfer across borders.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: subject to any applicable restrictions contained in our data processing addendum with the relevant customer\ndeletion:\n  route: email privacy@lawvu.com\n  text: you can do this by emailing our Privacy Officer or Data Protection Officer at privacy@lawvu.com\nrights:\n- right: access\n  text: You have the right to access your readily retrievable Personal Information that we hold about you\n- right: correction\n  text: to ask for it to be corrected if you think it is wrong or to be deleted\n- right:\
  \ erasure\n  text: in certain circumstances, have your Personal Information erased\n- right: restriction\n  text: restrict the processing of your Personal Information\n- right: portability\n  text: move, copy or transfer your Personal Information easily for your own purposes across different services\n- right: objection\n  text: object to processing where we rely on our legitimate interests as the lawful basis for processing\n- right: withdraw consent\n  text: withdraw your consent at any time, where our processing of your Personal Information is based on consent\n- right: complaint\n  text: lodge a complaint with an appropriate supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lawvu/privacy/lawvu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from LawVu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Legal Operations
- Contract Lifecycle Management
- Matter Management
- Document Management
- Spend Management
- Software-as-a-Service
- Workflows
---
