---
api_specs:
- filename: turbodocx-deliverable-api-openapi.yml
  format: yaml
  label: TurboDocx Deliverable API
  slug: turbodocx-deliverable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/turbodocx/openapi/turbodocx-deliverable-api-openapi.yml
- filename: turbodocx-tag-api-openapi.yml
  format: yaml
  label: TurboDocx Tag API
  slug: turbodocx-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/turbodocx/openapi/turbodocx-tag-api-openapi.yml
- filename: turbodocx-template-api-openapi.yml
  format: yaml
  label: TurboDocx Template API
  slug: turbodocx-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/turbodocx/openapi/turbodocx-template-api-openapi.yml
- filename: turbodocx-webhooks-api-openapi.yml
  format: yaml
  label: TurboDocx Webhooks API
  slug: turbodocx-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/turbodocx/openapi/turbodocx-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your personal details: Your full name, phone number, and email.'
  - category: contact
    text: 'Your personal details: Your full name, phone number, and email.'
  - category: financial
    text: We don't collect your payment card details.
  - category: location
    text: 'Category G: Geolocation data. Examples: Approximate physical location. Collected: Yes.'
  - category: behavioral
    text: 'Information about your Activities: We may also collect information about how you use our services, such as the content you engage with, templates that you use, or the frequency and duration of your activities.'
  - category: device
    text: operating system, make & ID, IP address, device ID and type, settings and characteristics, Site crashes, identifiers associated with cookies
  - category: communication
    text: 'Messages: Team messages, notes and other collaboration records.'
  deletion:
    route: Email request to team@turbodocx.com
    text: You can request us to delete your information by writing to us at team@turbodocx.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Process payments
    text: To process your payments;
  - purpose: Marketing communications
    text: We use your information to send you marketing communications, newsletter, communicate with you about our services
  - purpose: Fraud and security
    text: This includes detecting, preventing, and responding to fraud, abuse, security risks, and technical issues
  residency:
  - region: United States
    text: Your primary data is stored in Amazon Web Services (AWS) data storage, databases and servers located in the United States.
  retention:
  - period: null
    scope: Personal information
    text: Personal information that we collect, access or process will be retained only so long as necessary for the fulfillment of the purposes for which it was collected, as necessary for our legitimate business purposes, or as required or authorized by law.
  - period: a reasonable period of time
    scope: Deleted account information
    text: we may also retain some of the information so deleted for a reasonable period of time in order to comply with legal requests.
  rights:
  - right: Right to obtain information
    text: 'Right to obtain information: You may have a right to obtain information about how and on what basis your personal information is processed and to obtain a copy.'
  - right: Right to rectification
    text: 'Right to rectification: You may have the right to have any incomplete or inaccurate information we hold about you rectified and corrected.'
  - right: Right of erasure
    text: 'Right of Erasure: You may have the right to erase your personal information in limited circumstances'
  - right: Right of restriction
    text: 'Right of restriction: You may have the right to restrict processing of your personal information where:'
  - right: Right to object
    text: 'Right to object: You may have the right to object to decisions which are based solely on automated processing or profiling.'
  - right: Right to withdraw consent
    text: Right to withdraw your consent. You may have the right to withdraw your consent on using your personal data.
  - right: Data portability
    text: Request the transfer of your Personal Data.
  role:
    text: the Data Controller for the data that you submit to us is TURBODOCX, INC.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: As previously mentioned in this Policy, we do not "sell" (as such term is defined in the CCPA) personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: You hereby consent to any such cross-border transfer of your personal information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TurboDocx
provenance_date: '2026-11-10'
provider_name: TurboDocx
provider_slug: turbodocx
slug: turbodocx-privacy-policy
source_date: '2026-11-10'
source_filename: turbodocx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.turbodocx.com/termsofservice/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TurboDocx\naid: turbodocx\nurl: https://www.turbodocx.com/termsofservice/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the Data Controller for the data that you submit to us is TURBODOCX, INC.\ndata_categories:\n- category: identifying\n  text: 'Your personal details: Your full name, phone number, and email.'\n- category: contact\n  text: 'Your personal details: Your full name, phone number, and email.'\n- category: financial\n  text: We don't collect your payment card details.\n- category: location\n  text: 'Category G: Geolocation data. Examples: Approximate physical location.\
  \ Collected: Yes.'\n- category: behavioral\n  text: 'Information about your Activities: We may also collect information about how you use our services, such\n    as the content you engage with, templates that you use, or the frequency and duration of your activities.'\n- category: device\n  text: operating system, make & ID, IP address, device ID and type, settings and characteristics, Site crashes,\n    identifiers associated with cookies\n- category: communication\n  text: 'Messages: Team messages, notes and other collaboration records.'\npurposes:\n- purpose: Process payments\n  text: To process your payments;\n- purpose: Marketing communications\n  text: We use your information to send you marketing communications, newsletter, communicate with you about our\n    services\n- purpose: Fraud and security\n  text: This includes detecting, preventing, and responding to fraud, abuse, security risks, and technical issues\nretention:\n- scope: Personal information\n  period: null\n  text:\
  \ Personal information that we collect, access or process will be retained only so long as necessary for the\n    fulfillment of the purposes for which it was collected, as necessary for our legitimate business purposes, or\n    as required or authorized by law.\n- scope: Deleted account information\n  period: a reasonable period of time\n  text: we may also retain some of the information so deleted for a reasonable period of time in order to comply\n    with legal requests.\nresidency:\n- region: United States\n  text: Your primary data is stored in Amazon Web Services (AWS) data storage, databases and servers located in\n    the United States.\ntransfers:\n- mechanism: other\n  text: You hereby consent to any such cross-border transfer of your personal information.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to team@turbodocx.com\n  text: You can request us to delete your information by writing to us\
  \ at team@turbodocx.com .\nrights:\n- right: Right to obtain information\n  text: 'Right to obtain information: You may have a right to obtain information about how and on what basis your\n    personal information is processed and to obtain a copy.'\n- right: Right to rectification\n  text: 'Right to rectification: You may have the right to have any incomplete or inaccurate information we hold\n    about you rectified and corrected.'\n- right: Right of erasure\n  text: 'Right of Erasure: You may have the right to erase your personal information in limited circumstances'\n- right: Right of restriction\n  text: 'Right of restriction: You may have the right to restrict processing of your personal information where:'\n- right: Right to object\n  text: 'Right to object: You may have the right to object to decisions which are based solely on automated processing\n    or profiling.'\n- right: Right to withdraw consent\n  text: Right to withdraw your consent. You may have the right to withdraw\
  \ your consent on using your personal data.\n- right: Data portability\n  text: Request the transfer of your Personal Data.\nsale_or_sharing:\n  stance: prohibited\n  text: As previously mentioned in this Policy, we do not \"sell\" (as such term is defined in the CCPA) personal\n    information.\n"
source_yaml_url: https://artifacts.apis.io/turbodocx/privacy/turbodocx-privacy-policy.yml
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
summary_line: 24 quoted statements, read from TurboDocx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Document Automation
- E-Signature
- Artificial Intelligence
- Integration
- Software-as-a-Service
---
