---
api_specs:
- filename: cryptokeyhole-charts-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Charts API
  slug: cryptokeyhole-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-charts-api-openapi.yml
- filename: cryptokeyhole-indices-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Indices API
  slug: cryptokeyhole-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-indices-api-openapi.yml
- filename: cryptokeyhole-markets-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Markets API
  slug: cryptokeyhole-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-markets-api-openapi.yml
- filename: cryptokeyhole-platform-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Platform API
  slug: cryptokeyhole-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-platform-api-openapi.yml
- filename: cryptokeyhole-tools-api-openapi.yml
  format: yaml
  label: CryptoKeyhole Tools API
  slug: cryptokeyhole-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cryptokeyhole/openapi/cryptokeyhole-tools-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username, a salted hash of your password (never the password itself), a hash of your recovery code and the date you joined.
  - category: contact
    text: Email and webhook addresses for alerts, whether they are verified, and delivery records.
  - category: device
    text: IP address, time, the page or API address requested and browser type.
  - category: financial
    text: Stripe collects your card details, email address and, where needed, billing address at checkout. We never see or store your card number.
  - category: communication
    text: Your questions and the answers are kept only in memory while the conversation is open (forgotten after 30 minutes without use)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide account, saved work, alerts, API, AI analyst and plan
    text: 'To provide your account, saved work, alerts, API, AI analyst and plan: this is needed to perform our contract with you.'
  - purpose: Security and fault fixing
    text: 'To keep the service secure, stop abuse and fix faults: our legitimate interest in running a safe, working service.'
  - purpose: Payment and accounting records
    text: 'To keep payment and accounting records: a legal obligation.'
  - purpose: Site usage analytics with consent
    text: 'To understand how the site is used and which pages lead to subscriptions, with Google Analytics: only with your consent, which you can withdraw at any time.'
  residency:
  - region: United Kingdom
    text: The site runs on our own servers in the United Kingdom.
  retention:
  - period: until you delete your account
    scope: Account data and saved work
    text: 'Account data and saved work: until you delete your account.'
  - period: until they expire or you sign out
    scope: Sign-in sessions
    text: 'Sign-in sessions: until they expire or you sign out.'
  - period: normally six years
    scope: Payment records
    text: 'Payment records: kept by Stripe, and by us for as long as tax and accounting law requires, normally six years.'
  - period: 14 months
    scope: Google Analytics data
    text: it keeps this data for 14 months.
  rights:
  - right: Access
    text: You can ask for a copy of your data
  - right: Rectification or erasure
    text: ask us to correct or delete it
  - right: Objection or restriction
    text: object to or restrict how we use it
  - right: Portability
    text: ask for it in a portable form
  - right: Complaint
    text: you can complain to the Information Commissioner’s Office
  role:
    text: CryptoKeyhole is run from the United Kingdom by an individual trading as CryptoKeyhole, who is the controller of your personal data under UK data protection law.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, use it for advertising or send marketing email.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Stripe, Cloudflare, Google and Anthropic may process data outside the UK, with the safeguards UK law requires.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CryptoKeyhole
provenance_date: '2026-11-09'
provider_name: CryptoKeyhole
provider_slug: cryptokeyhole
slug: cryptokeyhole-privacy-policy
source_date: '2026-11-09'
source_filename: cryptokeyhole-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cryptokeyhole.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CryptoKeyhole\naid: cryptokeyhole\nurl: https://cryptokeyhole.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CryptoKeyhole is run from the United Kingdom by an individual trading as CryptoKeyhole, who is the controller\n    of your personal data under UK data protection law.\ndata_categories:\n- category: identifying\n  text: Username, a salted hash of your password (never the password itself), a hash of your recovery code and the\n    date you joined.\n- category: contact\n  text: Email and webhook addresses for alerts, whether they are verified, and delivery records.\n- category:\
  \ device\n  text: IP address, time, the page or API address requested and browser type.\n- category: financial\n  text: Stripe collects your card details, email address and, where needed, billing address at checkout. We never\n    see or store your card number.\n- category: communication\n  text: Your questions and the answers are kept only in memory while the conversation is open (forgotten after 30\n    minutes without use)\npurposes:\n- purpose: Provide account, saved work, alerts, API, AI analyst and plan\n  text: 'To provide your account, saved work, alerts, API, AI analyst and plan: this is needed to perform our contract\n    with you.'\n- purpose: Security and fault fixing\n  text: 'To keep the service secure, stop abuse and fix faults: our legitimate interest in running a safe, working\n    service.'\n- purpose: Payment and accounting records\n  text: 'To keep payment and accounting records: a legal obligation.'\n- purpose: Site usage analytics with consent\n  text: 'To understand\
  \ how the site is used and which pages lead to subscriptions, with Google Analytics: only with\n    your consent, which you can withdraw at any time.'\nretention:\n- scope: Account data and saved work\n  period: until you delete your account\n  text: 'Account data and saved work: until you delete your account.'\n- scope: Sign-in sessions\n  period: until they expire or you sign out\n  text: 'Sign-in sessions: until they expire or you sign out.'\n- scope: Payment records\n  period: normally six years\n  text: 'Payment records: kept by Stripe, and by us for as long as tax and accounting law requires, normally six\n    years.'\n- scope: Google Analytics data\n  period: 14 months\n  text: it keeps this data for 14 months.\nresidency:\n- region: United Kingdom\n  text: The site runs on our own servers in the United Kingdom.\ntransfers:\n- mechanism: other\n  text: Stripe, Cloudflare, Google and Anthropic may process data outside the UK, with the safeguards UK law requires.\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: You can ask for a copy of your data\n- right: Rectification or erasure\n  text: ask us to correct or delete it\n- right: Objection or restriction\n  text: object to or restrict how we use it\n- right: Portability\n  text: ask for it in a portable form\n- right: Complaint\n  text: you can complain to the Information Commissioner’s Office\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, use it for advertising or send marketing email.\n"
source_yaml_url: https://artifacts.apis.io/cryptokeyhole/privacy/cryptokeyhole-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from CryptoKeyhole's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Blockchain
- Analytics
- Data
- Charts
---
