---
api_specs:
- filename: mullvad-openapi-generated.yml
  format: yaml
  label: Mullvad VPN API
  slug: mullvad-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mullvad/openapi/_ae-authored/mullvad-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: financial
    text: 'Bank wire: sender name, address, bank account number'
  - category: identifying
    text: 'PayPal: transaction-ID, sender name, origin country and e-mail address'
  - category: contact
    text: 'Support by e-mail: your e-mail address and other information which you have written in the e-mail.'
  - category: device
    text: 'Problem reported by the app: Redacted program logs, app version and operating system are sent.'
  deletion:
    route: contact support email
    text: If you would like to exercise your rights, please contact support@mullvadvpn.net for more information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide service and process payments
    text: Payment information are processed for the purpose of providing you with the service we offer, to pay out refunds and for accounting purposes.
  - purpose: support and problem resolution
    text: Processing of e-mails and problem reports via our app/client are made for the purpose of answering questions, resolve problems, and provide general support to customers.
  residency:
  - region: EU/EEA
    text: We only store and process your personal data within the EU/EEA.
  retention:
  - period: 20 days
    scope: transaction ID
    text: Transaction_id is permanently deleted after 20 days.
  - period: seven years
    scope: accounting payment data
    text: some information must be stored for seven years from the end of the fiscal year
  - period: 70 days
    scope: support emails and problem reports
    text: After 70 days, all emails/problem reports sent to our support address are automatically, permanently erased
  rights:
  - right: correction or deletion
    text: You have the right, in certain situations, to request us to correct or delete personal data regarding you and/or restrict the processing as well as a right to data portability (if applicable).
  - right: object
    text: Where the legal basis for the processing is based on a weighing of interests you are as a data subject entitled to object at any time to the processing of your data.
  - right: complaint to authority
    text: You have the right to make a complaint to the Swedish Authority for Privacy Protection (Integritetsskyddsmyndigheten, “IMY”, www.imy.se).
  role:
    text: Data controller contact information Mullvad VPN AB Reg. no. 559238-4001 Box 53049 400 14 Gothenburg Sweden
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mullvad VPN
provenance_date: '2026-11-10'
provider_name: Mullvad VPN
provider_slug: mullvad
slug: mullvad-privacy-policy
source_date: '2026-11-10'
source_filename: mullvad-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mullvad.net/en/help/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mullvad VPN\naid: mullvad\nurl: https://mullvad.net/en/help/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller contact information Mullvad VPN AB Reg. no. 559238-4001 Box 53049 400 14 Gothenburg Sweden\ndata_categories:\n- category: financial\n  text: 'Bank wire: sender name, address, bank account number'\n- category: identifying\n  text: 'PayPal: transaction-ID, sender name, origin country and e-mail address'\n- category: contact\n  text: 'Support by e-mail: your e-mail address and other information which you have written in the e-mail.'\n- category: device\n  text:\
  \ 'Problem reported by the app: Redacted program logs, app version and operating system are sent.'\npurposes:\n- purpose: provide service and process payments\n  text: Payment information are processed for the purpose of providing you with the service we offer, to pay out\n    refunds and for accounting purposes.\n- purpose: support and problem resolution\n  text: Processing of e-mails and problem reports via our app/client are made for the purpose of answering questions,\n    resolve problems, and provide general support to customers.\nretention:\n- scope: transaction ID\n  period: 20 days\n  text: Transaction_id is permanently deleted after 20 days.\n- scope: accounting payment data\n  period: seven years\n  text: some information must be stored for seven years from the end of the fiscal year\n- scope: support emails and problem reports\n  period: 70 days\n  text: After 70 days, all emails/problem reports sent to our support address are automatically, permanently erased\nresidency:\n\
  - region: EU/EEA\n  text: We only store and process your personal data within the EU/EEA.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support email\n  text: If you would like to exercise your rights, please contact support@mullvadvpn.net for more information.\nrights:\n- right: correction or deletion\n  text: You have the right, in certain situations, to request us to correct or delete personal data regarding you\n    and/or restrict the processing as well as a right to data portability (if applicable).\n- right: object\n  text: Where the legal basis for the processing is based on a weighing of interests you are as a data subject entitled\n    to object at any time to the processing of your data.\n- right: complaint to authority\n  text: You have the right to make a complaint to the Swedish Authority for Privacy Protection (Integritetsskyddsmyndigheten,\n    “IMY”, www.imy.se).\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mullvad/privacy/mullvad-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 15 quoted statements, read from Mullvad VPN's own page on 2026-11-10.
synthetic: false
tags:
- Company
- VPN
- Privacy
- Open Source
- Security
---
