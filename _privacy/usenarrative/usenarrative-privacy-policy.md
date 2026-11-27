---
api_specs:
- filename: usenarrative-health-api-openapi.yml
  format: yaml
  label: Narrative Sports Health API
  slug: usenarrative-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usenarrative/openapi/usenarrative-health-api-openapi.yml
- filename: usenarrative-highlight-packages-api-openapi.yml
  format: yaml
  label: Narrative Sports Highlight Packages API
  slug: usenarrative-highlight-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usenarrative/openapi/usenarrative-highlight-packages-api-openapi.yml
- filename: usenarrative-highlights-api-openapi.yml
  format: yaml
  label: Narrative Sports Highlights API
  slug: usenarrative-highlights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usenarrative/openapi/usenarrative-highlights-api-openapi.yml
- filename: usenarrative-projects-api-openapi.yml
  format: yaml
  label: Narrative Sports Projects API
  slug: usenarrative-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usenarrative/openapi/usenarrative-projects-api-openapi.yml
- filename: usenarrative-recaps-api-openapi.yml
  format: yaml
  label: Narrative Sports Recaps API
  slug: usenarrative-recaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usenarrative/openapi/usenarrative-recaps-api-openapi.yml
- filename: usenarrative-tasks-api-openapi.yml
  format: yaml
  label: Narrative Sports Tasks API
  slug: usenarrative-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usenarrative/openapi/usenarrative-tasks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, and a name if you give us one.
  - category: contact
    text: Your email address, and a name if you give us one.
  - category: financial
    text: Billing details . Your plan, invoices and payment status.
  - category: location
    text: approximate location from your IP address
  - category: behavioral
    text: Pages viewed, features used, browser and operating system, approximate location from your IP address, and error reports.
  - category: device
    text: browser and operating system
  - category: communication
    text: The prompts you write, the edits you accept or undo, and the version history of each project.
  - category: other
    text: The video, audio, images and fonts you add to a project, and the renders we produce from them.
  deletion:
    route: Delete projects in the app or ask to close the account
    text: Delete individual projects yourself, or ask us to close your account and remove it all.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide access and billing
    text: We use your account and billing details to give you access and charge for it.
  - purpose: Produce requested edit
    text: We use your footage and prompts to produce the edit you asked for, and to keep it available so you can come back to it.
  - purpose: Bug fixing and product improvement
    text: We use product and device data to find bugs, keep the service up and decide what to build next.
  - purpose: Model training excluded
    text: We do not use your footage, your prompts or your edits to train our own models
  residency:
  - region: United States
    text: We operate in the United States, and your data is stored and processed there and in other countries where our providers run.
  retention:
  - period: until you delete them or close your account
    scope: Projects and footage
    text: Projects, footage and renders stay until you delete them or close your account.
  - period: within 30 days
    scope: Deleted projects
    text: clears it from storage and backups within 30 days
  - period: 30 days
    scope: Agent conversations
    text: Your conversations with the agent, and the record of what it did in them, are kept for 30 days from when they were written and then deleted
  - period: as long as tax and accounting law requires
    scope: Billing records
    text: We keep billing records for as long as tax and accounting law requires
  rights:
  - right: Access
    text: See it . Ask for a copy of what we hold about you.
  - right: Correction
    text: Correct it . Fix anything wrong from your account settings or by writing to us.
  - right: Deletion
    text: Delete it . Delete individual projects yourself, or ask us to close your account and remove it all.
  - right: Portability
    text: Take it elsewhere . Download your footage and renders at any time.
  - right: Objection and withdrawal of consent
    text: Ask us to stop processing where we rely on legitimate interest, or withdraw a consent you gave.
  - right: Complain to authority
    text: you may also complain to your data protection authority.
  role:
    text: We use your account and billing details to give you access and charge for it.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell it.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Narrative Sports
provenance_date: '2026-11-10'
provider_name: Narrative Sports
provider_slug: usenarrative
slug: usenarrative-privacy-policy
source_date: '2026-11-10'
source_filename: usenarrative-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://usenarrative.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Narrative Sports\naid: usenarrative\nurl: https://usenarrative.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We use your account and billing details to give you access and charge for it.\ndata_categories:\n- category: identifying\n  text: Your email address, and a name if you give us one.\n- category: contact\n  text: Your email address, and a name if you give us one.\n- category: financial\n  text: Billing details . Your plan, invoices and payment status.\n- category: location\n  text: approximate location from your IP address\n- category: behavioral\n  text: Pages viewed, features\
  \ used, browser and operating system, approximate location from your IP address, and\n    error reports.\n- category: device\n  text: browser and operating system\n- category: communication\n  text: The prompts you write, the edits you accept or undo, and the version history of each project.\n- category: other\n  text: The video, audio, images and fonts you add to a project, and the renders we produce from them.\npurposes:\n- purpose: Provide access and billing\n  text: We use your account and billing details to give you access and charge for it.\n- purpose: Produce requested edit\n  text: We use your footage and prompts to produce the edit you asked for, and to keep it available so you can come\n    back to it.\n- purpose: Bug fixing and product improvement\n  text: We use product and device data to find bugs, keep the service up and decide what to build next.\n- purpose: Model training excluded\n  text: We do not use your footage, your prompts or your edits to train our own models\n\
  retention:\n- scope: Projects and footage\n  period: until you delete them or close your account\n  text: Projects, footage and renders stay until you delete them or close your account.\n- scope: Deleted projects\n  period: within 30 days\n  text: clears it from storage and backups within 30 days\n- scope: Agent conversations\n  period: 30 days\n  text: Your conversations with the agent, and the record of what it did in them, are kept for 30 days from when\n    they were written and then deleted\n- scope: Billing records\n  period: as long as tax and accounting law requires\n  text: We keep billing records for as long as tax and accounting law requires\nresidency:\n- region: United States\n  text: We operate in the United States, and your data is stored and processed there and in other countries where\n    our providers run.\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's standard contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Delete projects in the app or ask to close the account\n  text: Delete individual projects yourself, or ask us to close your account and remove it all.\nrights:\n- right: Access\n  text: See it . Ask for a copy of what we hold about you.\n- right: Correction\n  text: Correct it . Fix anything wrong from your account settings or by writing to us.\n- right: Deletion\n  text: Delete it . Delete individual projects yourself, or ask us to close your account and remove it all.\n- right: Portability\n  text: Take it elsewhere . Download your footage and renders at any time.\n- right: Objection and withdrawal of consent\n  text: Ask us to stop processing where we rely on legitimate interest, or withdraw a consent you gave.\n- right: Complain to authority\n  text: you may also complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell it.\n"
source_yaml_url: https://artifacts.apis.io/usenarrative/privacy/usenarrative-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Narrative Sports's own page on 2026-11-10.
synthetic: false
tags:
- Sports
- Video
- Artificial Intelligence
- Highlights
- Broadcasting
- Media
- Sports Technology
---
