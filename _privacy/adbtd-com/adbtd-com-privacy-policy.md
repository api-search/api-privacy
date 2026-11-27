---
api_specs:
- filename: adbtd-com-openapi-generated.yml
  format: yaml
  label: adbtd API
  slug: adbtd-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adbtd-com/openapi/_ae-authored/adbtd-com-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: the email address and the password (in hashed form) used for authentication purposes
  - category: financial
    text: We retain only the customer identifier, the subscription identifier, and the metadata associated with each invoice
  - category: communication
    text: Such mailboxes contain whatever data the customer chooses to send and receive, including sender/recipient headers, subject lines, message bodies, and attachments.
  - category: device
    text: the browser user-agent string
  deletion:
    route: erasure request to koren@pukogames.com
    text: any request for erasure may be addressed in writing to koren@pukogames.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: performance of a contract
    text: the processing of account, billing, and email data is necessary for the operation of the mailboxes and dedicated IP addresses ordered by the customer
  - purpose: legal obligation
    text: the retention of invoices for the period prescribed by tax law
  - purpose: legitimate interests
    text: the prevention of fraud, the handling of abuse, and the protection of deliverability
  residency:
  - region: European Union
    text: All servers operated by us are located within the European Union, and more specifically within the territory of the French Republic.
  retention:
  - period: ninety (90) days
    scope: SMTP and IMAP transaction logs
    text: SMTP and IMAP transaction logs are retained for a period of ninety (90) days and are subsequently deleted.
  - period: thirty (30) days
    scope: Server access logs
    text: for a period of thirty (30) days
  - period: for as long as the customer continues to operate the corresponding workspace
    scope: Account data and mailbox content
    text: Account data and the content of mailboxes are retained for as long as the customer continues to operate the corresponding workspace.
  - period: ten (10) years
    scope: Invoices
    text: Invoices are retained for the period prescribed by French tax law, currently set at ten (10) years.
  rights:
  - right: access
    text: the right of access, that is, the right to obtain a copy of the personal data held concerning the data subject
  - right: rectification
    text: the right of rectification of any inaccurate or incomplete data
  - right: erasure
    text: the right of erasure of the account and of the personal data associated with it
  - right: portability
    text: the right to data portability, that is, the right to receive account data and mailbox content in a structured, commonly used, and machine-readable format
  - right: restriction or objection
    text: the right to restrict, or to object to, specific processing operations
  role:
    text: who acts as data controller within the meaning of Regulation (EU) 2016/679 (General Data Protection Regulation)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not share it with advertisers.
  subprocessors:
    text: Should the addition of any new processor become necessary, the present policy shall be updated accordingly, and account holders shall be notified by electronic mail prior to the entry into force of such addition.
    url: null
  transfers:
  - mechanism: other
    text: Stripe operates on a global basis and may transfer personal data outside the European Union in accordance with the transfer mechanisms it has published.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: adbtd
provenance_date: '2026-11-09'
provider_name: adbtd
provider_slug: adbtd-com
slug: adbtd-com-privacy-policy
source_date: '2026-11-09'
source_filename: adbtd-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adbtd.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: adbtd\naid: adbtd-com\nurl: https://adbtd.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: who acts as data controller within the meaning of Regulation (EU) 2016/679 (General Data Protection Regulation)\ndata_categories:\n- category: contact\n  text: the email address and the password (in hashed form) used for authentication purposes\n- category: financial\n  text: We retain only the customer identifier, the subscription identifier, and the metadata associated with each\n    invoice\n- category: communication\n  text: Such mailboxes contain whatever data the customer chooses to send\
  \ and receive, including sender/recipient\n    headers, subject lines, message bodies, and attachments.\n- category: device\n  text: the browser user-agent string\npurposes:\n- purpose: performance of a contract\n  text: the processing of account, billing, and email data is necessary for the operation of the mailboxes and dedicated\n    IP addresses ordered by the customer\n- purpose: legal obligation\n  text: the retention of invoices for the period prescribed by tax law\n- purpose: legitimate interests\n  text: the prevention of fraud, the handling of abuse, and the protection of deliverability\nretention:\n- scope: SMTP and IMAP transaction logs\n  period: ninety (90) days\n  text: SMTP and IMAP transaction logs are retained for a period of ninety (90) days and are subsequently deleted.\n- scope: Server access logs\n  period: thirty (30) days\n  text: for a period of thirty (30) days\n- scope: Account data and mailbox content\n  period: for as long as the customer continues to operate\
  \ the corresponding workspace\n  text: Account data and the content of mailboxes are retained for as long as the customer continues to operate\n    the corresponding workspace.\n- scope: Invoices\n  period: ten (10) years\n  text: Invoices are retained for the period prescribed by French tax law, currently set at ten (10) years.\nresidency:\n- region: European Union\n  text: All servers operated by us are located within the European Union, and more specifically within the territory\n    of the French Republic.\ntransfers:\n- mechanism: other\n  text: Stripe operates on a global basis and may transfer personal data outside the European Union in accordance\n    with the transfer mechanisms it has published.\nsubprocessors:\n  url: null\n  text: Should the addition of any new processor become necessary, the present policy shall be updated accordingly,\n    and account holders shall be notified by electronic mail prior to the entry into force of such addition.\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: erasure request to koren@pukogames.com\n  text: any request for erasure may be addressed in writing to koren@pukogames.com\nrights:\n- right: access\n  text: the right of access, that is, the right to obtain a copy of the personal data held concerning the data subject\n- right: rectification\n  text: the right of rectification of any inaccurate or incomplete data\n- right: erasure\n  text: the right of erasure of the account and of the personal data associated with it\n- right: portability\n  text: the right to data portability, that is, the right to receive account data and mailbox content in a structured,\n    commonly used, and machine-readable format\n- right: restriction or objection\n  text: the right to restrict, or to object to, specific processing operations\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/adbtd-com/privacy/adbtd-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from adbtd's own page on 2026-11-09.
synthetic: false
tags:
- Email Infrastructure
- SMTP
- IMAP
- Dedicated IP
- Deliverability
- Webhook
- MCP
---
