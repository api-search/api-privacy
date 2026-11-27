---
api_specs:
- filename: bool-com-openapi-generated.yml
  format: yaml
  label: Bool API
  slug: bool-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bool-com/openapi/_ae-authored/bool-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — name, email address, and either a password (which we store only as a salted hash)
  - category: contact
    text: email address, a salted password hash (or the identity provider used instead), display name
  - category: financial
    text: Billing information — plan, subscription status, invoices, purchase history, and the identifiers our payment processor returns.
  - category: location
    text: an approximate location (country, region, and city) derived from the network request
  - category: behavioral
    text: the path visited, the referring site, campaign parameters and click identifiers included in a landing-page URL
  - category: device
    text: coarse device, operating-system, and browser categories
  - category: communication
    text: Communications — support requests, feedback, and messages you send us, and our replies.
  - category: other
    text: What you build — the prompts you send, the chat history of a project, files you upload as attachments
  deletion:
    route: Delete project or account from the app, or email hello@bool.com
    text: When you delete a project or your account, we delete or de-identify the associated data, including a published app's account directory and stored data, within a reasonable period
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate Bool and apps
    text: Provide, operate, host, and serve Bool and the apps built on it;
  - purpose: AI output generation
    text: Generate code and other output in response to prompts, which requires sending prompt and project content to the AI providers described in Section 5;
  - purpose: Authentication
    text: Authenticate people, keep sessions active, and enforce access to private projects and apps;
  - purpose: Billing and metering
    text: Meter plans, credits, and usage, process payments, and prevent billing abuse;
  - purpose: Security and abuse prevention
    text: Detect, investigate, and stop fraud, abuse, security incidents, and violations of our Terms; and
  residency:
  - region: United States
    text: Bool is operated from the United States, and our service providers may process and store data in the United States and other countries.
  retention:
  - period: while your account is active
    scope: Account, project, and app data
    text: Account, project, and app data are kept while your account is active.
  - period: a limited operational window
    scope: Traffic measurement and request logs for published apps
    text: Traffic measurement and request logs for published apps are kept for a limited operational window and then deleted or aggregated.
  - period: as long as applicable law requires
    scope: Billing and tax records
    text: Billing and tax records are kept as long as applicable law requires.
  - period: a short period after deletion
    scope: Backups
    text: Backups persist for a short period after deletion before they age out.
  rights:
  - right: access, correct, delete, or receive a copy
    text: the right to access, correct, delete, or receive a copy of your personal information
  - right: object or restrict processing
    text: to object to or restrict certain processing, to withdraw consent
  - right: non-discrimination
    text: not to be discriminated against for exercising these rights
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not use it for third-party advertising or cross-context behavioral advertising.
  subprocessors:
    text: 'Service providers who run parts of Bool on our behalf, under contracts that limit them to that purpose. They currently include: cloud hosting and serverless compute; managed Postgres, authentication, file storage, and realtime messaging; isolated sandbox environments that run and build your app''s code; AI model providers and the model-routing layer in front of them (including Anthropic, OpenAI, and Google); a payment processor (Stripe);'
    url: null
  transfers:
  - mechanism: other
    text: If you use Bool from outside the United States, you understand that your information will be processed there, where privacy laws may differ from those in your country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bool
provenance_date: '2026-11-09'
provider_name: Bool
provider_slug: bool-com
slug: bool-com-privacy-policy
source_date: '2026-11-09'
source_filename: bool-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bool.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bool\naid: bool-com\nurl: https://bool.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information — name, email address, and either a password (which we store only as a salted hash)\n- category: contact\n  text: email address, a salted password hash (or the identity provider used instead), display name\n- category: financial\n  text: Billing information — plan, subscription status, invoices, purchase history, and the identifiers our payment\n    processor returns.\n- category: location\n  text: an approximate location\
  \ (country, region, and city) derived from the network request\n- category: behavioral\n  text: the path visited, the referring site, campaign parameters and click identifiers included in a landing-page\n    URL\n- category: device\n  text: coarse device, operating-system, and browser categories\n- category: communication\n  text: Communications — support requests, feedback, and messages you send us, and our replies.\n- category: other\n  text: What you build — the prompts you send, the chat history of a project, files you upload as attachments\npurposes:\n- purpose: Provide and operate Bool and apps\n  text: Provide, operate, host, and serve Bool and the apps built on it;\n- purpose: AI output generation\n  text: Generate code and other output in response to prompts, which requires sending prompt and project content\n    to the AI providers described in Section 5;\n- purpose: Authentication\n  text: Authenticate people, keep sessions active, and enforce access to private projects and\
  \ apps;\n- purpose: Billing and metering\n  text: Meter plans, credits, and usage, process payments, and prevent billing abuse;\n- purpose: Security and abuse prevention\n  text: Detect, investigate, and stop fraud, abuse, security incidents, and violations of our Terms; and\nretention:\n- scope: Account, project, and app data\n  period: while your account is active\n  text: Account, project, and app data are kept while your account is active.\n- scope: Traffic measurement and request logs for published apps\n  period: a limited operational window\n  text: Traffic measurement and request logs for published apps are kept for a limited operational window and then\n    deleted or aggregated.\n- scope: Billing and tax records\n  period: as long as applicable law requires\n  text: Billing and tax records are kept as long as applicable law requires.\n- scope: Backups\n  period: a short period after deletion\n  text: Backups persist for a short period after deletion before they age out.\nresidency:\n\
  - region: United States\n  text: Bool is operated from the United States, and our service providers may process and store data in the United\n    States and other countries.\ntransfers:\n- mechanism: other\n  text: If you use Bool from outside the United States, you understand that your information will be processed there,\n    where privacy laws may differ from those in your country.\nsubprocessors:\n  url: null\n  text: 'Service providers who run parts of Bool on our behalf, under contracts that limit them to that purpose.\n    They currently include: cloud hosting and serverless compute; managed Postgres, authentication, file storage,\n    and realtime messaging; isolated sandbox environments that run and build your app''s code; AI model providers\n    and the model-routing layer in front of them (including Anthropic, OpenAI, and Google); a payment processor\n    (Stripe);'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete project or account from the app,\
  \ or email hello@bool.com\n  text: When you delete a project or your account, we delete or de-identify the associated data, including a published\n    app's account directory and stored data, within a reasonable period\nrights:\n- right: access, correct, delete, or receive a copy\n  text: the right to access, correct, delete, or receive a copy of your personal information\n- right: object or restrict processing\n  text: to object to or restrict certain processing, to withdraw consent\n- right: non-discrimination\n  text: not to be discriminated against for exercising these rights\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not use it for third-party advertising or cross-context behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/bool-com/privacy/bool-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Bool's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Low-Code
- Platform
- Development
---
