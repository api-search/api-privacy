---
api_specs:
- filename: arroway-app-mcp.json
  format: json
  label: Arroway MCP API
  slug: arroway-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arroway-app/openapi/arroway-app-mcp.json
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: name, e-mail address and profile picture, from the identity provider when you sign in with an existing account, or just the e-mail when you sign in with a link.'
  - category: contact
    text: 'Your account: name, e-mail address and profile picture, from the identity provider when you sign in with an existing account, or just the e-mail when you sign in with a link.'
  - category: communication
    text: When your AI logs what it did or proposes a memory, the text it writes is stored — that is the product's function, and it is what you read and approve in the panel.
  - category: behavioral
    text: 'We also record every tool call and every curation action: who, through which connection, in which project, which tool and when.'
  - category: device
    text: An origin cookie, introduced on 2026-08-24 and written only when you ask to install something of ours — the connector or a starter pack — having arrived from one of our public pages.
  - category: behavioral
    text: An acquisition cookie, introduced on 2026-08-26 and written when you reach any of our public pages from outside — a link we published, a search, another site.
  deletion:
    route: Delete your account from the menu under your photo, or request a copy or correction by e-mail to hello@arroway.app.
    text: You can DELETE your account yourself, from the menu under your photo.
  dpa:
    available: true
    text: The current named list is public, in Annex A of the Data Processing Agreement .
    url: null
  purposes:
  - purpose: sign-in and keeping the user signed in
    text: Your session cookie, which is what keeps you signed in. The panel does not work without it.
  - purpose: audit trail of AI actions
    text: 'We also record every tool call and every curation action: who, through which connection, in which project, which tool and when. That is what the audit screen rests on'
  - purpose: measuring which channels bring product users
    text: It exists so we can tell which channel brings people who actually go on to use the product.
  - purpose: audience measurement on public pages
    text: We measure traffic on the public pages with Google Analytics, since 2026-09-18.
  - purpose: e-mail summaries of project contents
    text: besides the sign-in link, you receive a summary of what is in your projects.
  residency:
  - region: United States
    text: Data is kept in a managed PostgreSQL database and the application runs on a cloud hosting platform, both with servers in the United States.
  retention:
  - period: As long as your account exists
    scope: account and content
    text: As long as your account exists. Arroway does not delete as a side effect
  - period: 14 days
    scope: daily-log entries sent to AIs
    text: Daily-log entries older than 14 days stop being sent to AIs, but stay visible to you in the panel.
  - period: 30 days
    scope: acquisition cookie
    text: It is erased on your first signed-in visit, and expires on its own after 30 days if that visit never comes.
  - period: after a short time
    scope: cockpit messages
    text: Only you see that text, and it is erased after a short time or when you turn the cockpit off.
  rights:
  - right: access and copy of data
    text: To get a copy of your data, or to correct something you cannot correct in the panel, write to hello@arroway.app.
  - right: correction
    text: correct or archive any memory, and close a project.
  - right: account deletion
    text: You can DELETE your account yourself, from the menu under your photo.
  - right: revoke AI connection
    text: revoke an AI connection under Connections (access dies immediately)
  - right: LGPD rights (Brazil)
    text: If you are in Brazil, these are your rights under the LGPD (Law 13.709/2018).
  - right: GDPR rights (EU)
    text: In the European Union, under the GDPR.
  role:
    text: Arroway is operated by Alexandre Viola. For anything in this policy — a question, a correction, a copy of your data, or deletion — write to hello@arroway.app.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent or share your content with third parties.
  subprocessors:
    text: 'Categories of providers that process data so Arroway can work: managed database, application hosting, identity provider (when you choose to sign in with an existing account), e-mail delivery, error monitoring, payment processing (when a team subscribes), and audience measurement on the public pages.'
    url: null
  transfers:
  - mechanism: other
    text: This means your data is transferred internationally.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Arroway
provenance_date: '2026-11-09'
provider_name: Arroway
provider_slug: arroway-app
slug: arroway-app-privacy-policy
source_date: '2026-11-09'
source_filename: arroway-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.arroway.app/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Arroway\naid: arroway-app\nurl: https://www.arroway.app/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Arroway is operated by Alexandre Viola. For anything in this policy — a question, a correction, a copy of\n    your data, or deletion — write to hello@arroway.app.\ndata_categories:\n- category: identifying\n  text: 'Your account: name, e-mail address and profile picture, from the identity provider when you sign in with\n    an existing account, or just the e-mail when you sign in with a link.'\n- category: contact\n  text: 'Your account: name, e-mail address and profile picture,\
  \ from the identity provider when you sign in with\n    an existing account, or just the e-mail when you sign in with a link.'\n- category: communication\n  text: When your AI logs what it did or proposes a memory, the text it writes is stored — that is the product's\n    function, and it is what you read and approve in the panel.\n- category: behavioral\n  text: 'We also record every tool call and every curation action: who, through which connection, in which project,\n    which tool and when.'\n- category: device\n  text: An origin cookie, introduced on 2026-08-24 and written only when you ask to install something of ours —\n    the connector or a starter pack — having arrived from one of our public pages.\n- category: behavioral\n  text: An acquisition cookie, introduced on 2026-08-26 and written when you reach any of our public pages from\n    outside — a link we published, a search, another site.\npurposes:\n- purpose: sign-in and keeping the user signed in\n  text: Your session cookie,\
  \ which is what keeps you signed in. The panel does not work without it.\n- purpose: audit trail of AI actions\n  text: 'We also record every tool call and every curation action: who, through which connection, in which project,\n    which tool and when. That is what the audit screen rests on'\n- purpose: measuring which channels bring product users\n  text: It exists so we can tell which channel brings people who actually go on to use the product.\n- purpose: audience measurement on public pages\n  text: We measure traffic on the public pages with Google Analytics, since 2026-09-18.\n- purpose: e-mail summaries of project contents\n  text: besides the sign-in link, you receive a summary of what is in your projects.\nretention:\n- scope: account and content\n  period: As long as your account exists\n  text: As long as your account exists. Arroway does not delete as a side effect\n- scope: daily-log entries sent to AIs\n  period: 14 days\n  text: Daily-log entries older than 14 days stop\
  \ being sent to AIs, but stay visible to you in the panel.\n- scope: acquisition cookie\n  period: 30 days\n  text: It is erased on your first signed-in visit, and expires on its own after 30 days if that visit never comes.\n- scope: cockpit messages\n  period: after a short time\n  text: Only you see that text, and it is erased after a short time or when you turn the cockpit off.\nresidency:\n- region: United States\n  text: Data is kept in a managed PostgreSQL database and the application runs on a cloud hosting platform, both\n    with servers in the United States.\ntransfers:\n- mechanism: other\n  text: This means your data is transferred internationally.\nsubprocessors:\n  url: null\n  text: 'Categories of providers that process data so Arroway can work: managed database, application hosting, identity\n    provider (when you choose to sign in with an existing account), e-mail delivery, error monitoring, payment processing\n    (when a team subscribes), and audience measurement on\
  \ the public pages.'\ndpa:\n  available: true\n  url: null\n  text: The current named list is public, in Annex A of the Data Processing Agreement .\ndeletion:\n  route: Delete your account from the menu under your photo, or request a copy or correction by e-mail to hello@arroway.app.\n  text: You can DELETE your account yourself, from the menu under your photo.\nrights:\n- right: access and copy of data\n  text: To get a copy of your data, or to correct something you cannot correct in the panel, write to hello@arroway.app.\n- right: correction\n  text: correct or archive any memory, and close a project.\n- right: account deletion\n  text: You can DELETE your account yourself, from the menu under your photo.\n- right: revoke AI connection\n  text: revoke an AI connection under Connections (access dies immediately)\n- right: LGPD rights (Brazil)\n  text: If you are in Brazil, these are your rights under the LGPD (Law 13.709/2018).\n- right: GDPR rights (EU)\n  text: In the European Union,\
  \ under the GDPR.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent or share your content with third parties.\n"
source_yaml_url: https://artifacts.apis.io/arroway-app/privacy/arroway-app-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Arroway's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Memory
- Teamwork
- Automation
---
