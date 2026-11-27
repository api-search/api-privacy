---
api_specs:
- filename: nocthost-openapi-generated.yml
  format: yaml
  label: NoctHost API
  slug: nocthost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nocthost/openapi/_ae-authored/nocthost-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your email address, and a hash of your password (never the password itself).'
  - category: financial
    text: We keep the amount, the coin, the processor's payment reference, and the country your connection resolved to at the moment you created the payment.
  - category: location
    text: the country your connection resolved to at the moment you created the payment
  - category: communication
    text: 'Support: the messages you send us and any images you attach, kept with your account so the conversation has history.'
  - category: behavioral
    text: With it we record the page path, the referring site, campaign parameters if a link had them, and whether you are on desktop or mobile.
  deletion:
    route: Ask us to delete the account
    text: Ask us to delete it and we remove it, except records we are legally required to keep.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service you signed up for, running your account, deploying your servers, billing your balance.
  - purpose: Legal obligations
    text: To meet legal obligations, issuing invoices, keeping accounting records, and complying with sanctions rules.
  - purpose: Legitimate interests
    text: For our legitimate interests, keeping the platform secure, preventing abuse, and answering abuse reports from our upstream providers.
  - purpose: Marketing with consent
    text: 'With your consent: product and marketing emails only.'
  retention:
  - period: while your account exists
    scope: Account data
    text: 'Account data: while your account exists.'
  - period: a short time only
    scope: Request logs including IP addresses
    text: 'Request logs, including IP addresses: a short time only.'
  - period: 2 years
    scope: Account activity connection details and server address history
    text: 'Account activity connection details and the history of server addresses: 2 years from the action, or from the day the address was released, then deleted automatically.'
  - period: null
    scope: Connection details stored with a payment
    text: kept with the payment record without a fixed end date
  - period: 90 days
    scope: Analytics events
    text: 'Analytics events: 90 days, after which they are deleted automatically.'
  - period: 7 days
    scope: Archived server snapshots at zero balance
    text: 'Snapshots of servers archived at a zero balance: 7 days, then removed with the rest of the server.'
  rights:
  - right: Access copy
    text: ask us for a copy of your data
  - right: Correction
    text: ask us to correct it
  - right: Deletion
    text: ask us to delete it
  - right: Restriction or objection
    text: ask us to restrict or stop certain processing
  - right: Portability
    text: ask for it in a portable form
  - right: Withdraw marketing consent
    text: You can withdraw marketing consent at any time without affecting anything else.
  - right: Complain to supervisory authority
    text: you can complain to the Estonian Data Protection Inspectorate (Andmekaitse Inspektsioon)
  role:
    text: Nocthost OÜ (registry code 17569744), registered in Estonia, operates NoctHost and is the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No advertising cookies, no cross-site tracking, no data sold or shared with advertisers or data brokers. Ever.
  subprocessors:
    text: The cloud provider your server runs on, Vultr, DigitalOcean, Hetzner or Linode, depending on what you chose.
    url: null
  transfers:
  - mechanism: other
    text: Because servers and providers are located worldwide, data may be processed outside the European Economic Area.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NoctHost
provenance_date: '2026-11-10'
provider_name: NoctHost
provider_slug: nocthost
slug: nocthost-privacy-policy
source_date: '2026-11-10'
source_filename: nocthost-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nocthost.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NoctHost\naid: nocthost\nurl: https://nocthost.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Nocthost OÜ (registry code 17569744), registered in Estonia, operates NoctHost and is the data controller\n    for the personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Account: your email address, and a hash of your password (never the password itself).'\n- category: financial\n  text: We keep the amount, the coin, the processor's payment reference, and the country your connection resolved\n    to at the moment you created the payment.\n- category: location\n\
  \  text: the country your connection resolved to at the moment you created the payment\n- category: communication\n  text: 'Support: the messages you send us and any images you attach, kept with your account so the conversation\n    has history.'\n- category: behavioral\n  text: With it we record the page path, the referring site, campaign parameters if a link had them, and whether\n    you are on desktop or mobile.\npurposes:\n- purpose: Provide the service\n  text: To provide the service you signed up for, running your account, deploying your servers, billing your balance.\n- purpose: Legal obligations\n  text: To meet legal obligations, issuing invoices, keeping accounting records, and complying with sanctions rules.\n- purpose: Legitimate interests\n  text: For our legitimate interests, keeping the platform secure, preventing abuse, and answering abuse reports\n    from our upstream providers.\n- purpose: Marketing with consent\n  text: 'With your consent: product and marketing emails\
  \ only.'\nretention:\n- scope: Account data\n  period: while your account exists\n  text: 'Account data: while your account exists.'\n- scope: Request logs including IP addresses\n  period: a short time only\n  text: 'Request logs, including IP addresses: a short time only.'\n- scope: Account activity connection details and server address history\n  period: 2 years\n  text: 'Account activity connection details and the history of server addresses: 2 years from the action, or from\n    the day the address was released, then deleted automatically.'\n- scope: Connection details stored with a payment\n  period: null\n  text: kept with the payment record without a fixed end date\n- scope: Analytics events\n  period: 90 days\n  text: 'Analytics events: 90 days, after which they are deleted automatically.'\n- scope: Archived server snapshots at zero balance\n  period: 7 days\n  text: 'Snapshots of servers archived at a zero balance: 7 days, then removed with the rest of the server.'\nresidency:\
  \ []\ntransfers:\n- mechanism: other\n  text: Because servers and providers are located worldwide, data may be processed outside the European Economic\n    Area.\nsubprocessors:\n  url: null\n  text: The cloud provider your server runs on, Vultr, DigitalOcean, Hetzner or Linode, depending on what you chose.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask us to delete the account\n  text: Ask us to delete it and we remove it, except records we are legally required to keep.\nrights:\n- right: Access copy\n  text: ask us for a copy of your data\n- right: Correction\n  text: ask us to correct it\n- right: Deletion\n  text: ask us to delete it\n- right: Restriction or objection\n  text: ask us to restrict or stop certain processing\n- right: Portability\n  text: ask for it in a portable form\n- right: Withdraw marketing consent\n  text: You can withdraw marketing consent at any time without affecting anything else.\n- right: Complain to supervisory authority\n \
  \ text: you can complain to the Estonian Data Protection Inspectorate (Andmekaitse Inspektsioon)\nsale_or_sharing:\n  stance: prohibited\n  text: No advertising cookies, no cross-site tracking, no data sold or shared with advertisers or data brokers.\n    Ever.\n"
source_yaml_url: https://artifacts.apis.io/nocthost/privacy/nocthost-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from NoctHost's own page on 2026-11-10.
synthetic: false
tags:
- Company
- VPS
- Cloud
- Crypto Payments
- GPU
---
