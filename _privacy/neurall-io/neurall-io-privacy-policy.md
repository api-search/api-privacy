---
api_specs:
- filename: neurall-io-files-api-openapi.yml
  format: yaml
  label: neurall-io Files API
  slug: neurall-io-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurall-io/openapi/neurall-io-files-api-openapi.yml
- filename: neurall-io-generations-api-openapi.yml
  format: yaml
  label: neurall-io Generations API
  slug: neurall-io-generations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurall-io/openapi/neurall-io-generations-api-openapi.yml
- filename: neurall-io-mcp-api-openapi.yml
  format: yaml
  label: neurall-io MCP API
  slug: neurall-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurall-io/openapi/neurall-io-mcp-api-openapi.yml
- filename: neurall-io-pricing-api-openapi.yml
  format: yaml
  label: neurall-io Pricing API
  slug: neurall-io-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurall-io/openapi/neurall-io-pricing-api-openapi.yml
- filename: neurall-io-templates-api-openapi.yml
  format: yaml
  label: neurall-io Templates API
  slug: neurall-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurall-io/openapi/neurall-io-templates-api-openapi.yml
- filename: neurall-io-voices-api-openapi.yml
  format: yaml
  label: neurall-io Voices API
  slug: neurall-io-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neurall-io/openapi/neurall-io-voices-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: the email address you sign up with, and the name you choose to add.'
  - category: financial
    text: 'Billing details: the amount, the currency, the date and a reference to the payment.'
  - category: communication
    text: Support messages, and whatever you put in them.
  - category: device
    text: 'Technical logs: IP address, user agent, API key id and timestamps, kept to keep the service up and to catch abuse.'
  - category: behavioral
    text: 'Attribution: how you reached us, and which page you bought from.'
  - category: biometric
    text: 'What you send to a generation: prompts, and any reference files, which for several features are photographs of a person.'
  deletion:
    route: Delete an item in the app, or close the account
    text: Closing the account deletes the account data, subject to the ledger above.
  dpa:
    available: null
    text: we will name a specific provider on request from a business customer under a confidentiality agreement, which is also how a data processing agreement gets signed.
    url: null
  purposes:
  - purpose: Run requested generation
    text: Generating, storing the result briefly and returning it to you.
  - purpose: Billing
    text: Charging balance, refunding failures, keeping the ledger.
  - purpose: Service security and abuse prevention
    text: Logs, rate limits, fraud and abuse detection, security investigation.
  - purpose: Legal compliance
    text: Records we are required to keep, and responses to lawful requests.
  - purpose: Product improvement
    text: Aggregate counts of what runs and what fails.
  - purpose: Advertising measurement
    text: Seeing which ad and which page led to a signup or a purchase, by reporting those moments to Meta.
  - purpose: Service email
    text: Receipts, security notices and material changes to these documents.
  residency:
  - region: United States
    text: We are a United States company and our infrastructure runs in the United States.
  retention:
  - period: 24 hours
    scope: Uploads through the API
    text: A reference file is deleted 24 hours after it lands, whether or not a generation used it.
  - period: 24 hours
    scope: API outputs
    text: A generation made through the API expires 24 hours after the request.
  - period: null
    scope: Work made in the app
    text: Your library is a place to keep things, so app work persists.
  - period: null
    scope: Voice clones
    text: A voice you create is a resource you reuse, so it is not on the 24 hour clock.
  - period: null
    scope: Generation records
    text: What ran, when and what it cost is the billing ledger, and tax law requires us to keep it.
  - period: null
    scope: Technical logs
    text: Then deleted or aggregated beyond identification.
  rights:
  - right: access and copy
    text: you can ask us for a copy of your data, a correction, deletion, a restriction on how we use it, or a machine-readable export.
  - right: correction
    text: you can ask us for a copy of your data, a correction, deletion, a restriction on how we use it, or a machine-readable export.
  - right: deletion
    text: you can ask us for a copy of your data, a correction, deletion, a restriction on how we use it, or a machine-readable export.
  - right: objection
    text: You can object to processing we do on the basis of legitimate interest.
  - right: withdraw consent
    text: You can withdraw consent to marketing at any time, and every marketing email carries the link.
  - right: complain to authority
    text: you can complain to your data protection authority
  role:
    text: 'Neurall, Inc. , 1007 N Orange St, 4th Floor Suite #1382, Wilmington, DE 19801, United States , is the controller of the personal data described here.'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We never sell your data.
  subprocessors:
    text: We use a small number of processors, each bound by a contract that permits them to act only on our instructions.
    url: null
  transfers:
  - mechanism: SCC
    text: Where we rely on it, that transfer is covered by the European Commission’s Standard Contractual Clauses with the receiving party, plus the UK Addendum where relevant.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: neurall-io
provenance_date: '2026-11-10'
provider_name: neurall-io
provider_slug: neurall-io
slug: neurall-io-privacy-policy
source_date: '2026-11-10'
source_filename: neurall-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://neurall.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: neurall-io\naid: neurall-io\nurl: https://neurall.io/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Neurall, Inc. , 1007 N Orange St, 4th Floor Suite #1382, Wilmington, DE 19801, United States , is the controller\n    of the personal data described here.'\ndata_categories:\n- category: identifying\n  text: 'Account details: the email address you sign up with, and the name you choose to add.'\n- category: financial\n  text: 'Billing details: the amount, the currency, the date and a reference to the payment.'\n- category: communication\n  text: Support messages, and whatever you put\
  \ in them.\n- category: device\n  text: 'Technical logs: IP address, user agent, API key id and timestamps, kept to keep the service up and to catch\n    abuse.'\n- category: behavioral\n  text: 'Attribution: how you reached us, and which page you bought from.'\n- category: biometric\n  text: 'What you send to a generation: prompts, and any reference files, which for several features are photographs\n    of a person.'\npurposes:\n- purpose: Run requested generation\n  text: Generating, storing the result briefly and returning it to you.\n- purpose: Billing\n  text: Charging balance, refunding failures, keeping the ledger.\n- purpose: Service security and abuse prevention\n  text: Logs, rate limits, fraud and abuse detection, security investigation.\n- purpose: Legal compliance\n  text: Records we are required to keep, and responses to lawful requests.\n- purpose: Product improvement\n  text: Aggregate counts of what runs and what fails.\n- purpose: Advertising measurement\n  text: Seeing\
  \ which ad and which page led to a signup or a purchase, by reporting those moments to Meta.\n- purpose: Service email\n  text: Receipts, security notices and material changes to these documents.\nretention:\n- scope: Uploads through the API\n  period: 24 hours\n  text: A reference file is deleted 24 hours after it lands, whether or not a generation used it.\n- scope: API outputs\n  period: 24 hours\n  text: A generation made through the API expires 24 hours after the request.\n- scope: Work made in the app\n  period: null\n  text: Your library is a place to keep things, so app work persists.\n- scope: Voice clones\n  period: null\n  text: A voice you create is a resource you reuse, so it is not on the 24 hour clock.\n- scope: Generation records\n  period: null\n  text: What ran, when and what it cost is the billing ledger, and tax law requires us to keep it.\n- scope: Technical logs\n  period: null\n  text: Then deleted or aggregated beyond identification.\nresidency:\n- region: United\
  \ States\n  text: We are a United States company and our infrastructure runs in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where we rely on it, that transfer is covered by the European Commission’s Standard Contractual Clauses\n    with the receiving party, plus the UK Addendum where relevant.\nsubprocessors:\n  url: null\n  text: We use a small number of processors, each bound by a contract that permits them to act only on our instructions.\ndpa:\n  available: null\n  url: null\n  text: we will name a specific provider on request from a business customer under a confidentiality agreement,\n    which is also how a data processing agreement gets signed.\ndeletion:\n  route: Delete an item in the app, or close the account\n  text: Closing the account deletes the account data, subject to the ledger above.\nrights:\n- right: access and copy\n  text: you can ask us for a copy of your data, a correction, deletion, a restriction on how we use it, or a machine-readable\n    export.\n\
  - right: correction\n  text: you can ask us for a copy of your data, a correction, deletion, a restriction on how we use it, or a machine-readable\n    export.\n- right: deletion\n  text: you can ask us for a copy of your data, a correction, deletion, a restriction on how we use it, or a machine-readable\n    export.\n- right: objection\n  text: You can object to processing we do on the basis of legitimate interest.\n- right: withdraw consent\n  text: You can withdraw consent to marketing at any time, and every marketing email carries the link.\n- right: complain to authority\n  text: you can complain to your data protection authority\nsale_or_sharing:\n  stance: conditional\n  text: We never sell your data.\n"
source_yaml_url: https://artifacts.apis.io/neurall-io/privacy/neurall-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from neurall-io's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Image
- Voice
- Creators
- Developers
---
