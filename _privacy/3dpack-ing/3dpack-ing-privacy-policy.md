---
api_specs:
- filename: 3dpack-ing-packing-api-openapi.yml
  format: yaml
  label: 3dpack-ing Packing API
  slug: 3dpack-ing-packing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3dpack-ing/openapi/3dpack-ing-packing-api-openapi.yml
- filename: 3dpack-ing-typed-api-openapi.yml
  format: yaml
  label: 3dpack-ing Typed API
  slug: 3dpack-ing-typed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/3dpack-ing/openapi/3dpack-ing-typed-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, if you sign in with Google, Microsoft or LinkedIn
  - category: contact
    text: your email address
  - category: financial
    text: We receive a customer reference, the plan you bought and whether the payment succeeded — never your card details.
  - category: device
    text: your IP address and the requests you make
  - category: behavioral
    text: clicks, page visibility and navigation on the site
  - category: communication
    text: the shipment description it writes for each request
  deletion:
    route: Write to contact@3dpack.ing from the address you sign in with, asking for deletion
    text: 'You can ask us for a copy of your data, to correct it, to delete it or your account, to restrict or object to its use, or to receive it in a portable form: write to contact@3dpack.ing from the address you sign in with.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service you asked for: sign you in, compute and store your load plans, count your plan and allowance, and take payment.'
  - purpose: Security and fixing problems
    text: To keep the service secure and working, and to fix problems.
  - purpose: Free allowance abuse prevention
    text: To keep the free allowance to one per person
  - purpose: Product contact with consent
    text: To email or call you about the product, only if you ticked the optional box in the sign-in form.
  - purpose: Site analytics with consent
    text: To understand how the site is used, only if you accepted analytics. (Consent.)
  residency:
  - region: China
    text: DeepSeek processes data in China.
  retention:
  - period: until you ask us to delete it
    scope: Account and settings
    text: 'Your account and its settings: until you ask us to delete it.'
  - period: until you ask us to delete them or your account
    scope: Load plans
    text: 'Your load plans: stored until you ask us to delete them or your account.'
  - period: until they are revoked or your account is deleted
    scope: Access keys
    text: 'Access keys created for connected assistants: until they are revoked or your account is deleted.'
  - period: as long as Norwegian bookkeeping law requires
    scope: Payment and billing records
    text: 'Payment and billing records: as long as Norwegian bookkeeping law requires.'
  - period: 30 days
    scope: Server logs
    text: 'Server logs , including IP addresses: 30 days in our log service.'
  rights:
  - right: access
    text: You can ask us for a copy of your data
  - right: rectification
    text: to correct it
  - right: erasure
    text: to delete it or your account
  - right: restriction and objection
    text: to restrict or object to its use
  - right: portability
    text: to receive it in a portable form
  - right: withdraw consent
    text: You can withdraw any consent at any time, without affecting what was done before.
  - right: complain to authority
    text: you can complain to Datatilsynet, the Norwegian Data Protection Authority.
  role:
    text: operated by Novian Works, an individually owned business (ENK) registered in Norway, which is responsible for the personal data described here
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not pass your email address to anyone for their own use.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 3dpack-ing
provenance_date: '2026-11-09'
provider_name: 3dpack-ing
provider_slug: 3dpack-ing
slug: 3dpack-ing-privacy-policy
source_date: '2026-11-09'
source_filename: 3dpack-ing-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://3dpack.ing/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 3dpack-ing\naid: 3dpack-ing\nurl: https://3dpack.ing/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: operated by Novian Works, an individually owned business (ENK) registered in Norway, which is responsible\n    for the personal data described here\ndata_categories:\n- category: identifying\n  text: your name, if you sign in with Google, Microsoft or LinkedIn\n- category: contact\n  text: your email address\n- category: financial\n  text: We receive a customer reference, the plan you bought and whether the payment succeeded — never your card\n    details.\n- category: device\n\
  \  text: your IP address and the requests you make\n- category: behavioral\n  text: clicks, page visibility and navigation on the site\n- category: communication\n  text: the shipment description it writes for each request\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service you asked for: sign you in, compute and store your load plans, count your plan and\n    allowance, and take payment.'\n- purpose: Security and fixing problems\n  text: To keep the service secure and working, and to fix problems.\n- purpose: Free allowance abuse prevention\n  text: To keep the free allowance to one per person\n- purpose: Product contact with consent\n  text: To email or call you about the product, only if you ticked the optional box in the sign-in form.\n- purpose: Site analytics with consent\n  text: To understand how the site is used, only if you accepted analytics. (Consent.)\nretention:\n- scope: Account and settings\n  period: until you ask us to delete it\n  text: 'Your\
  \ account and its settings: until you ask us to delete it.'\n- scope: Load plans\n  period: until you ask us to delete them or your account\n  text: 'Your load plans: stored until you ask us to delete them or your account.'\n- scope: Access keys\n  period: until they are revoked or your account is deleted\n  text: 'Access keys created for connected assistants: until they are revoked or your account is deleted.'\n- scope: Payment and billing records\n  period: as long as Norwegian bookkeeping law requires\n  text: 'Payment and billing records: as long as Norwegian bookkeeping law requires.'\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs , including IP addresses: 30 days in our log service.'\nresidency:\n- region: China\n  text: DeepSeek processes data in China.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to contact@3dpack.ing from the address you sign in with, asking for deletion\n\
  \  text: 'You can ask us for a copy of your data, to correct it, to delete it or your account, to restrict or object\n    to its use, or to receive it in a portable form: write to contact@3dpack.ing from the address you sign in with.'\nrights:\n- right: access\n  text: You can ask us for a copy of your data\n- right: rectification\n  text: to correct it\n- right: erasure\n  text: to delete it or your account\n- right: restriction and objection\n  text: to restrict or object to its use\n- right: portability\n  text: to receive it in a portable form\n- right: withdraw consent\n  text: You can withdraw any consent at any time, without affecting what was done before.\n- right: complain to authority\n  text: you can complain to Datatilsynet, the Norwegian Data Protection Authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not pass your email address to anyone for their own use.\n"
source_yaml_url: https://artifacts.apis.io/3dpack-ing/privacy/3dpack-ing-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from 3dpack-ing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- 3D
- Software-as-a-Service
---
