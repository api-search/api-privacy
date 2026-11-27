---
api_specs:
- filename: casedaleel-com-public-api-openapi.yml
  format: yaml
  label: CaseDaleel Public API
  slug: casedaleel-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casedaleel-com/openapi/casedaleel-com-public-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: the chat asks for your name, your email address, your phone number and a short description of what is happening
  - category: financial
    text: for an order, its amount, status (pending, paid or refunded), the payment provider's reference and the dates it was paid or refunded
  - category: health
    text: Some of this is sensitive personal data under the PDPL — for example information revealing health, family life, religious or political belief, or criminal allegations
  - category: device
    text: Connection details for the chat intake — the browser description your browser sends, and a salted hash of your IP address
  - category: behavioral
    text: Aggregate, cookie-free visit statistics — pages viewed, referrer site, campaign tags in the link, device type
  - category: communication
    text: Messages you send us — when you write to us, by email or through the contact form
  deletion:
    route: Account page for case or account deletion; email contact@casedaleel.com for other requests
    text: You can delete a case, or your whole account, yourself.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running the case Navigator and organising case file
    text: Running the case Navigator and organising your case file
  - purpose: Storing chat intake details and conversation
    text: Storing your chat intake details and the conversation, and contacting you about your matter
  - purpose: Sending service email
    text: Sending service email — verification, password reset, the link to save a guest conversation, and notices about your case
  - purpose: Preparing case pack and taking payment
    text: Preparing a case pack, taking payment for it, and keeping the accounting record
  residency:
  - region: European Union (Amsterdam) for uploaded documents
    text: Documents you upload are stored in a private, encrypted storage bucket in the European Union.
  - region: Outside the UAE for accounts and cases
    text: Accounts, cases and transcripts are held in our hosting provider's database, outside the UAE.
  retention:
  - period: Until you delete the case or your account
    scope: Case content, Navigator messages and uploaded documents
    text: Until you delete the case or your account. If your account has been dormant for 24 months, we delete the case content and tell you at your registered email address before we do
  - period: 12 months
    scope: Guest accounts and unsaved chat intake records
    text: Deleted 12 months after the last activity in the conversation, together with the conversation, unless you save it to an account or ask us to delete it sooner
  - period: Up to 30 days
    scope: Server and security logs
    text: Up to 30 days, then overwritten by our hosting provider
  rights:
  - right: Access
    text: Access — to get confirmation that we hold data about you and a copy of it, along with the purposes, recipients and retention periods.
  - right: Erase
    text: Erase — to have your data deleted.
  - right: Portability
    text: Portability — to receive the data you gave us in a structured, commonly used, machine-readable format
  - right: Object
    text: Object — to object to processing based on our legitimate interests, and to object to the automated processing described in section 6.
  - right: Withdraw consent
    text: Withdraw consent — at any time, and as easily as you gave it.
  role:
    text: We are the controller of the personal data described in this notice
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we run no advertising trackers.
  subprocessors:
    text: Beyond that, your data reaches only the service providers we need to run the platform.
    url: null
  transfers:
  - mechanism: other
    text: Contractual safeguards with each provider, requiring it to protect the data to a standard consistent with the PDPL
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CaseDaleel
provenance_date: '2026-11-09'
provider_name: CaseDaleel
provider_slug: casedaleel-com
slug: casedaleel-com-privacy-policy
source_date: '2026-11-09'
source_filename: casedaleel-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://casedaleel.com/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CaseDaleel\naid: casedaleel-com\nurl: https://casedaleel.com/en/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal data described in this notice\ndata_categories:\n- category: contact\n  text: the chat asks for your name, your email address, your phone number and a short description of what is happening\n- category: financial\n  text: for an order, its amount, status (pending, paid or refunded), the payment provider's reference and the dates\n    it was paid or refunded\n- category: health\n  text: Some of this is sensitive personal data under the\
  \ PDPL — for example information revealing health, family\n    life, religious or political belief, or criminal allegations\n- category: device\n  text: Connection details for the chat intake — the browser description your browser sends, and a salted hash of\n    your IP address\n- category: behavioral\n  text: Aggregate, cookie-free visit statistics — pages viewed, referrer site, campaign tags in the link, device\n    type\n- category: communication\n  text: Messages you send us — when you write to us, by email or through the contact form\npurposes:\n- purpose: Running the case Navigator and organising case file\n  text: Running the case Navigator and organising your case file\n- purpose: Storing chat intake details and conversation\n  text: Storing your chat intake details and the conversation, and contacting you about your matter\n- purpose: Sending service email\n  text: Sending service email — verification, password reset, the link to save a guest conversation, and notices\n    about\
  \ your case\n- purpose: Preparing case pack and taking payment\n  text: Preparing a case pack, taking payment for it, and keeping the accounting record\nretention:\n- scope: Case content, Navigator messages and uploaded documents\n  period: Until you delete the case or your account\n  text: Until you delete the case or your account. If your account has been dormant for 24 months, we delete the\n    case content and tell you at your registered email address before we do\n- scope: Guest accounts and unsaved chat intake records\n  period: 12 months\n  text: Deleted 12 months after the last activity in the conversation, together with the conversation, unless you\n    save it to an account or ask us to delete it sooner\n- scope: Server and security logs\n  period: Up to 30 days\n  text: Up to 30 days, then overwritten by our hosting provider\nresidency:\n- region: European Union (Amsterdam) for uploaded documents\n  text: Documents you upload are stored in a private, encrypted storage bucket\
  \ in the European Union.\n- region: Outside the UAE for accounts and cases\n  text: Accounts, cases and transcripts are held in our hosting provider's database, outside the UAE.\ntransfers:\n- mechanism: other\n  text: Contractual safeguards with each provider, requiring it to protect the data to a standard consistent with\n    the PDPL\nsubprocessors:\n  url: null\n  text: Beyond that, your data reaches only the service providers we need to run the platform.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page for case or account deletion; email contact@casedaleel.com for other requests\n  text: You can delete a case, or your whole account, yourself.\nrights:\n- right: Access\n  text: Access — to get confirmation that we hold data about you and a copy of it, along with the purposes, recipients\n    and retention periods.\n- right: Erase\n  text: Erase — to have your data deleted.\n- right: Portability\n  text: Portability — to receive the data you gave\
  \ us in a structured, commonly used, machine-readable format\n- right: Object\n  text: Object — to object to processing based on our legitimate interests, and to object to the automated processing\n    described in section 6.\n- right: Withdraw consent\n  text: Withdraw consent — at any time, and as easily as you gave it.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we run no advertising trackers.\n"
source_yaml_url: https://artifacts.apis.io/casedaleel-com/privacy/casedaleel-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from CaseDaleel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- United Arab Emirates
- Lawyer Matching
- Artificial Intelligence
- Employment Law
- MCP
---
