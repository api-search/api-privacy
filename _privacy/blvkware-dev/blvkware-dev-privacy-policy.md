---
api_specs:
- filename: blvkware-dev-check-api-openapi.yml
  format: yaml
  label: BlvkWare Check API
  slug: blvkware-dev-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvkware-dev/openapi/blvkware-dev-check-api-openapi.yml
- filename: blvkware-dev-corpus-api-openapi.yml
  format: yaml
  label: BlvkWare Corpus API
  slug: blvkware-dev-corpus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvkware-dev/openapi/blvkware-dev-corpus-api-openapi.yml
- filename: blvkware-dev-meta-api-openapi.yml
  format: yaml
  label: BlvkWare Meta API
  slug: blvkware-dev-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvkware-dev/openapi/blvkware-dev-meta-api-openapi.yml
- filename: blvkware-dev-watch-api-openapi.yml
  format: yaml
  label: BlvkWare Watch API
  slug: blvkware-dev-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blvkware-dev/openapi/blvkware-dev-watch-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: device
    text: GitHub records standard request data (your IP address, browser user agent, and which files were requested) for delivery and abuse prevention.
  - category: financial
    text: BlvkWare never sees your card details.
  - category: behavioral
    text: 'the design you make to BlvkWare''s kit service: the role, the systems, channels and capabilities you picked, the autonomy level, and your answers about your business, including any rules you write.'
  - category: identifying
    text: one-way fingerprint of the key, which cannot be turned back into the key, with the role it unlocked, the kit size, the times of its first and latest download, and a download count.
  deletion:
    route: Email russ@blvkware.dev
    text: Ask and it will be deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Hosting delivery and abuse prevention
    text: GitHub records standard request data (your IP address, browser user agent, and which files were requested) for delivery and abuse prevention.
  - purpose: Generating kit files
    text: The service uses it to list the files in your kit and, when you download, to generate the kit.
  - purpose: Licence key verification
    text: When you download, the kit service checks your licence key with Gumroad.
  - purpose: Answering correspondence and handling purchases or refunds
    text: That is used only for your purchase, to answer you or to handle a refund, and is never added to a marketing list.
  retention:
  - period: null
    scope: Kit design
    text: The design is not stored. Once the response is sent it is gone, and BlvkWare keeps no copy of it or of your kit.
  - period: null
    scope: Email correspondence
    text: Your address and the content of your message are kept so the conversation can continue.
  - period: null
    scope: Licence key records
    text: 'It keeps one record per key: a one-way fingerprint of the key, which cannot be turned back into the key'
  rights:
  - right: Access, correction, deletion, objection
    text: you may ask for a copy, a correction, or its deletion, and you may object to its use. Write to russ@blvkware.dev and it will be handled within 30 days at no cost.
  - right: Statutory rights
    text: Depending on where you live, these rights may be guaranteed to you by law, including the UK and EU GDPR and the California Consumer Privacy Act.
  role:
    text: BlvkWare is a sole operation run by William Russell Wheeler, based in Mississippi, United States, and selling to businesses nationwide.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: BlvkWare does not sell personal information, under any definition, to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BlvkWare
provenance_date: '2026-11-09'
provider_name: BlvkWare
provider_slug: blvkware-dev
slug: blvkware-dev-privacy-policy
source_date: '2026-11-09'
source_filename: blvkware-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blvkware.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BlvkWare\naid: blvkware-dev\nurl: https://blvkware.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BlvkWare is a sole operation run by William Russell Wheeler, based in Mississippi, United States, and selling\n    to businesses nationwide.\ndata_categories:\n- category: device\n  text: GitHub records standard request data (your IP address, browser user agent, and which files were requested)\n    for delivery and abuse prevention.\n- category: financial\n  text: BlvkWare never sees your card details.\n- category: behavioral\n  text: 'the design you make to BlvkWare''s kit service:\
  \ the role, the systems, channels and capabilities you picked,\n    the autonomy level, and your answers about your business, including any rules you write.'\n- category: identifying\n  text: one-way fingerprint of the key, which cannot be turned back into the key, with the role it unlocked, the\n    kit size, the times of its first and latest download, and a download count.\npurposes:\n- purpose: Hosting delivery and abuse prevention\n  text: GitHub records standard request data (your IP address, browser user agent, and which files were requested)\n    for delivery and abuse prevention.\n- purpose: Generating kit files\n  text: The service uses it to list the files in your kit and, when you download, to generate the kit.\n- purpose: Licence key verification\n  text: When you download, the kit service checks your licence key with Gumroad.\n- purpose: Answering correspondence and handling purchases or refunds\n  text: That is used only for your purchase, to answer you or to handle a refund,\
  \ and is never added to a marketing\n    list.\nretention:\n- scope: Kit design\n  period: null\n  text: The design is not stored. Once the response is sent it is gone, and BlvkWare keeps no copy of it or of your\n    kit.\n- scope: Email correspondence\n  period: null\n  text: Your address and the content of your message are kept so the conversation can continue.\n- scope: Licence key records\n  period: null\n  text: 'It keeps one record per key: a one-way fingerprint of the key, which cannot be turned back into the key'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email russ@blvkware.dev\n  text: Ask and it will be deleted.\nrights:\n- right: Access, correction, deletion, objection\n  text: you may ask for a copy, a correction, or its deletion, and you may object to its use. Write to russ@blvkware.dev\n    and it will be handled within 30 days at no cost.\n- right: Statutory rights\n\
  \  text: Depending on where you live, these rights may be guaranteed to you by law, including the UK and EU GDPR\n    and the California Consumer Privacy Act.\nsale_or_sharing:\n  stance: prohibited\n  text: BlvkWare does not sell personal information, under any definition, to anyone.\n"
source_yaml_url: https://artifacts.apis.io/blvkware-dev/privacy/blvkware-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from BlvkWare's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Kit
- Automation
- Marketplace
- Company
---
