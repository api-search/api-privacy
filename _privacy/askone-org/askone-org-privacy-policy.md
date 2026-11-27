---
api_specs:
- filename: askone-org-openapi-generated.yml
  format: yaml
  label: AskOne API
  slug: askone-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askone-org/openapi/_ae-authored/askone-org-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: the SHA-256 hash of that number — never the number itself — as the only handle we have on you
  - category: contact
    text: We do not store your email address, any name beyond the display name you choose, your IP address, or any identifier from your device.
  - category: behavioral
    text: The questions you ask , stored exactly as you typed them, and which questions you upvoted .
  - category: communication
    text: A display name , only if you type one.
  - category: device
    text: askone_visitor — the participant cookie described above. It holds a signed random value and nothing else.
  deletion:
    route: Write to us at the address above or at contact@askone.org; we delete on request, promptly.
    text: In the meantime we delete on request, promptly, and you should ask — see below.
  dpa:
    available: true
    text: Each is a processor acting on our instructions under a data processing agreement.
    url: null
  purposes:
  - purpose: running a question queue
    text: our legitimate interest (Art. 6(1)(f) GDPR) in running a question queue that works
  - purpose: AI moderation of questions
    text: we send the question text together with the room’s name and description to OpenRouter , which passes it to TypeSafe for classification.
  - purpose: account authentication
    text: Your account — email address, name, password or social login, and your organization memberships — is held by Clerk , our authentication provider.
  - purpose: product analytics
    text: We use Microsoft Clarity to see how the screens are used — where people hesitate, what they never find.
  retention:
  - period: null
    scope: organization room data
    text: is kept while the room is open and for 30 days after it is closed .
  - period: null
    scope: anonymous Zoom, Meet, Slides and ChatGPT rooms
    text: Its questions, votes, participant hashes and display names are deleted 7 days after it closes .
  - period: 13 months
    scope: API and MCP usage log
    text: API and MCP usage log lines are kept for 13 months, whether or not the workspace they name still exists.
  - period: as long as the workspace exists
    scope: ban and display-name block records
    text: Ban and display-name block records are kept for as long as the workspace exists.
  rights:
  - right: access and copy
    text: tell you what we hold about you, and give you a copy (Art. 15)
  - right: rectification
    text: correct anything inaccurate (Art. 16)
  - right: erasure
    text: delete it (Art. 17)
  - right: restriction
    text: restrict what we do with it (Art. 18)
  - right: portability
    text: hand it over in a portable form (Art. 20)
  - right: objection
    text: object to processing based on legitimate interest, including the analytics above (Art. 21)
  role:
    text: HURYN Sp. z o.o. is the controller for the data described here.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Who else processes it Clerk — accounts, organizations, sign-in, and subscription billing. Supabase — the database holding rooms, questions, votes, survey answers, participant hashes and the API usage log.
    url: null
  transfers:
  - mechanism: SCC
    text: Where any of them processes data outside the European Economic Area, that transfer relies on the European Commission’s Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AskOne
provenance_date: '2026-11-09'
provider_name: AskOne
provider_slug: askone-org
slug: askone-org-privacy-policy
source_date: '2026-11-09'
source_filename: askone-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askone.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AskOne\naid: askone-org\nurl: https://askone.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: HURYN Sp. z o.o. is the controller for the data described here.\ndata_categories:\n- category: identifying\n  text: the SHA-256 hash of that number — never the number itself — as the only handle we have on you\n- category: contact\n  text: We do not store your email address, any name beyond the display name you choose, your IP address, or any\n    identifier from your device.\n- category: behavioral\n  text: The questions you ask , stored exactly as you typed them, and which questions you\
  \ upvoted .\n- category: communication\n  text: A display name , only if you type one.\n- category: device\n  text: askone_visitor — the participant cookie described above. It holds a signed random value and nothing else.\npurposes:\n- purpose: running a question queue\n  text: our legitimate interest (Art. 6(1)(f) GDPR) in running a question queue that works\n- purpose: AI moderation of questions\n  text: we send the question text together with the room’s name and description to OpenRouter , which passes it\n    to TypeSafe for classification.\n- purpose: account authentication\n  text: Your account — email address, name, password or social login, and your organization memberships — is held\n    by Clerk , our authentication provider.\n- purpose: product analytics\n  text: We use Microsoft Clarity to see how the screens are used — where people hesitate, what they never find.\nretention:\n- scope: organization room data\n  period: null\n  text: is kept while the room is open and for 30\
  \ days after it is closed .\n- scope: anonymous Zoom, Meet, Slides and ChatGPT rooms\n  period: null\n  text: Its questions, votes, participant hashes and display names are deleted 7 days after it closes .\n- scope: API and MCP usage log\n  period: 13 months\n  text: API and MCP usage log lines are kept for 13 months, whether or not the workspace they name still exists.\n- scope: ban and display-name block records\n  period: as long as the workspace exists\n  text: Ban and display-name block records are kept for as long as the workspace exists.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where any of them processes data outside the European Economic Area, that transfer relies on the European\n    Commission’s Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: Who else processes it Clerk — accounts, organizations, sign-in, and subscription billing. Supabase — the\n    database holding rooms, questions, votes, survey answers, participant hashes and the API usage\
  \ log.\ndpa:\n  available: true\n  url: null\n  text: Each is a processor acting on our instructions under a data processing agreement.\ndeletion:\n  route: Write to us at the address above or at contact@askone.org; we delete on request, promptly.\n  text: In the meantime we delete on request, promptly, and you should ask — see below.\nrights:\n- right: access and copy\n  text: tell you what we hold about you, and give you a copy (Art. 15)\n- right: rectification\n  text: correct anything inaccurate (Art. 16)\n- right: erasure\n  text: delete it (Art. 17)\n- right: restriction\n  text: restrict what we do with it (Art. 18)\n- right: portability\n  text: hand it over in a portable form (Art. 20)\n- right: objection\n  text: object to processing based on legitimate interest, including the analytics above (Art. 21)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/askone-org/privacy/askone-org-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 24 quoted statements, read from AskOne's own page on 2026-11-09.
synthetic: false
tags:
- Moderation
- LiveQ&A
- Audience Engagement
- WebinarTools
- FreePlatform
---
