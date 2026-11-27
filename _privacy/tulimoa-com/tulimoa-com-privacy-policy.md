---
api_specs:
- filename: tulimoa-com-openapi-generated.yml
  format: yaml
  label: tulimoa-com API
  slug: tulimoa-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tulimoa-com/openapi/_ae-authored/tulimoa-com-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your email address (used for magic-link login), your name, your display name and your language preference
  - category: contact
    text: Transmitted are your email address and the content of the respective email.
  - category: financial
    text: For each payment we store the wallet address, the amount, the transaction reference and the network.
  - category: device
    text: the browser's User-Agent, and your IP address
  - category: behavioral
    text: the HTTP referrer, and a salted SHA-256 hash of your IP address
  - category: communication
    text: the content that you and your agents write to it (experiences, notes, goals, checkpoints, open tasks and imported documents)
  deletion:
    route: email to accounts@tulimoa.com
    text: To have your account deleted, write to accounts@tulimoa.com from the email address of your account.
  dpa:
    available: true
    text: Data-processing agreements under Art. 28 GDPR are in place with our processors
    url: null
  purposes:
  - purpose: operating the website and security
    text: (1) correctly deliver the contents of our website, (2) optimise the content of our website and the advertising for it, (3) ensure the lasting functionality of our information-technology systems
  - purpose: providing the memory service and billing its use
    text: 'Purpose: providing the memory service and billing its use.'
  - purpose: listing owner analytics
    text: 'Purpose: enable listing owners to see how often their own listing receives outbound clicks.'
  residency:
  - region: EU (Frankfurt)
    text: The Supabase project with your data is hosted in the EU (eu-central-1, Frankfurt).
  - region: EU (Ireland)
    text: Sending takes place from our EU region (eu-west-1, Ireland).
  retention:
  - period: null
    scope: account data
    text: These data are stored for the duration of your account.
  - period: 30 days
    scope: Google sign-in data
    text: all linked Google sign-in data is removed from our systems within 30 days
  - period: 30 days
    scope: memory experiences sent through /ingest
    text: experiences sent through /ingest that are not marked as durable are deleted after 30 days
  - period: null
    scope: outbound click events
    text: click events are kept indefinitely for statistical purposes
  rights:
  - right: access
    text: Every data subject affected by the processing of personal data has the right, granted by the European legislator, to obtain at any time from the controller free information about the personal data stored about them and a copy of that information.
  - right: erasure
    text: the erasure of personal data concerning them without undue delay
  - right: portability
    text: Signed-in users can download their personal data as a JSON file at any time themselves.
  - right: object
    text: to object, on grounds relating to their particular situation, at any time to the processing of personal data concerning them which is based on Art. 6 (1) (e) or (f) GDPR
  - right: complaint
    text: you have the right to lodge a complaint with a data-protection supervisory authority
  role:
    text: Tulimoa, as the controller, has implemented numerous technical and organisational measures
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Stored data is held by us and our commissioned processors, currently: Supabase, Inc. (USA, data region EU eu-central-1 Frankfurt): database and authentication, including the Tulimoa Memory database'
    url: null
  transfers:
  - mechanism: DPF
    text: Data transfers to the USA are based on the EU-US Data Privacy Framework and, additionally, on EU Standard Contractual Clauses.
  - mechanism: SCC
    text: for that transfer we and Polar rely on the EU Standard Contractual Clauses adopted by the European Commission as the appropriate safeguard.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tulimoa-com
provenance_date: '2026-11-10'
provider_name: tulimoa-com
provider_slug: tulimoa-com
slug: tulimoa-com-privacy-policy
source_date: '2026-11-10'
source_filename: tulimoa-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tulimoa.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tulimoa-com\naid: tulimoa-com\nurl: https://tulimoa.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Tulimoa, as the controller, has implemented numerous technical and organisational measures\ndata_categories:\n- category: identifying\n  text: we store your email address (used for magic-link login), your name, your display name and your language\n    preference\n- category: contact\n  text: Transmitted are your email address and the content of the respective email.\n- category: financial\n  text: For each payment we store the wallet address, the amount, the transaction reference\
  \ and the network.\n- category: device\n  text: the browser's User-Agent, and your IP address\n- category: behavioral\n  text: the HTTP referrer, and a salted SHA-256 hash of your IP address\n- category: communication\n  text: the content that you and your agents write to it (experiences, notes, goals, checkpoints, open tasks and\n    imported documents)\npurposes:\n- purpose: operating the website and security\n  text: (1) correctly deliver the contents of our website, (2) optimise the content of our website and the advertising\n    for it, (3) ensure the lasting functionality of our information-technology systems\n- purpose: providing the memory service and billing its use\n  text: 'Purpose: providing the memory service and billing its use.'\n- purpose: listing owner analytics\n  text: 'Purpose: enable listing owners to see how often their own listing receives outbound clicks.'\nretention:\n- scope: account data\n  period: null\n  text: These data are stored for the duration of your\
  \ account.\n- scope: Google sign-in data\n  period: 30 days\n  text: all linked Google sign-in data is removed from our systems within 30 days\n- scope: memory experiences sent through /ingest\n  period: 30 days\n  text: experiences sent through /ingest that are not marked as durable are deleted after 30 days\n- scope: outbound click events\n  period: null\n  text: click events are kept indefinitely for statistical purposes\nresidency:\n- region: EU (Frankfurt)\n  text: The Supabase project with your data is hosted in the EU (eu-central-1, Frankfurt).\n- region: EU (Ireland)\n  text: Sending takes place from our EU region (eu-west-1, Ireland).\ntransfers:\n- mechanism: DPF\n  text: Data transfers to the USA are based on the EU-US Data Privacy Framework and, additionally, on EU Standard\n    Contractual Clauses.\n- mechanism: SCC\n  text: for that transfer we and Polar rely on the EU Standard Contractual Clauses adopted by the European Commission\n    as the appropriate safeguard.\nsubprocessors:\n\
  \  url: null\n  text: 'Stored data is held by us and our commissioned processors, currently: Supabase, Inc. (USA, data region\n    EU eu-central-1 Frankfurt): database and authentication, including the Tulimoa Memory database'\ndpa:\n  available: true\n  url: null\n  text: Data-processing agreements under Art. 28 GDPR are in place with our processors\ndeletion:\n  route: email to accounts@tulimoa.com\n  text: To have your account deleted, write to accounts@tulimoa.com from the email address of your account.\nrights:\n- right: access\n  text: Every data subject affected by the processing of personal data has the right, granted by the European legislator,\n    to obtain at any time from the controller free information about the personal data stored about them and a copy\n    of that information.\n- right: erasure\n  text: the erasure of personal data concerning them without undue delay\n- right: portability\n  text: Signed-in users can download their personal data as a JSON file at any time\
  \ themselves.\n- right: object\n  text: to object, on grounds relating to their particular situation, at any time to the processing of personal\n    data concerning them which is based on Art. 6 (1) (e) or (f) GDPR\n- right: complaint\n  text: you have the right to lodge a complaint with a data-protection supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tulimoa-com/privacy/tulimoa-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from tulimoa-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Directory
- Artificial Intelligence
- MCP
- Reviews
---
