---
api_specs:
- filename: aidesignblueprint-com-openapi-generated.yml
  format: yaml
  label: AI Design Blueprint API
  slug: aidesignblueprint-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aidesignblueprint-com/openapi/_ae-authored/aidesignblueprint-com-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may process account identifiers, sign-in provider data, profile information, communication preferences
  - category: contact
    text: agency, SME and partner enquiries (including a WhatsApp number when you give one)
  - category: device
    text: the network address it came from, your browser's user-agent string and the page you were on
  - category: behavioral
    text: learning progress, validation runs
  deletion:
    route: Privacy & data management section
    text: When signed in, you can use the Privacy & data management section to review optional consents, inspect a data inventory, generate a portable export of account-linked data, and request account deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and workspace operation
    text: We use this information to authenticate members, create and maintain workspaces, preserve course access, track progress
  - purpose: prioritize support and product demand
    text: These summaries are used to prioritize support, understand product demand, and identify friction in the platform.
  residency:
  - region: United States (AI processors)
    text: Within your plan's included allowance, AIDB Studio conversations go to OpenAI (US)
  retention:
  - period: 30 days
    scope: Google Cloud request logs
    text: That log is kept for 30 days.
  - period: 400 days
    scope: Video analytics daily totals
    text: They are kept as daily totals for 400 days
  - period: 12 months
    scope: Operational security logs identifying fields
    text: the fields that identify you (user ID, email, Firebase account ID, conversation turn ID, and the network-address digest) are removed after 12 months
  - period: 2 days
    scope: Rate-limit ledger rows
    text: each row is deleted after 2 days
  rights:
  - right: data export
    text: generate a portable export of account-linked data
  - right: withdraw optional consent
    text: You can grant or withdraw those optional consents through the cookie banner
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: They are not sold to third parties.
  subprocessors:
    text: Authentication currently relies on Firebase Authentication
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Design Blueprint
provenance_date: '2026-11-09'
provider_name: AI Design Blueprint
provider_slug: aidesignblueprint-com
slug: aidesignblueprint-com-privacy-policy
source_date: '2026-11-09'
source_filename: aidesignblueprint-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aidesignblueprint.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Design Blueprint\naid: aidesignblueprint-com\nurl: https://aidesignblueprint.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we may process account identifiers, sign-in provider data, profile information, communication preferences\n- category: contact\n  text: agency, SME and partner enquiries (including a WhatsApp number when you give one)\n- category: device\n  text: the network address it came from, your browser's user-agent string and the page you were on\n- category: behavioral\n  text: learning progress, validation\
  \ runs\npurposes:\n- purpose: account and workspace operation\n  text: We use this information to authenticate members, create and maintain workspaces, preserve course access,\n    track progress\n- purpose: prioritize support and product demand\n  text: These summaries are used to prioritize support, understand product demand, and identify friction in the\n    platform.\nretention:\n- scope: Google Cloud request logs\n  period: 30 days\n  text: That log is kept for 30 days.\n- scope: Video analytics daily totals\n  period: 400 days\n  text: They are kept as daily totals for 400 days\n- scope: Operational security logs identifying fields\n  period: 12 months\n  text: the fields that identify you (user ID, email, Firebase account ID, conversation turn ID, and the network-address\n    digest) are removed after 12 months\n- scope: Rate-limit ledger rows\n  period: 2 days\n  text: each row is deleted after 2 days\nresidency:\n- region: United States (AI processors)\n  text: Within your plan's\
  \ included allowance, AIDB Studio conversations go to OpenAI (US)\ntransfers: []\nsubprocessors:\n  url: null\n  text: Authentication currently relies on Firebase Authentication\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy & data management section\n  text: When signed in, you can use the Privacy & data management section to review optional consents, inspect a\n    data inventory, generate a portable export of account-linked data, and request account deletion.\nrights:\n- right: data export\n  text: generate a portable export of account-linked data\n- right: withdraw optional consent\n  text: You can grant or withdraw those optional consents through the cookie banner\nsale_or_sharing:\n  stance: prohibited\n  text: They are not sold to third parties.\n"
source_yaml_url: https://artifacts.apis.io/aidesignblueprint-com/privacy/aidesignblueprint-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from AI Design Blueprint's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- AI Agents
- Design
- Platform
- Blueprints
---
