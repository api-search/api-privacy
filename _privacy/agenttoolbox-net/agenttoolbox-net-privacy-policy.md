---
api_specs:
- filename: agenttoolbox-net-directory-api-openapi.yml
  format: yaml
  label: Agent Toolbox Directory API
  slug: agenttoolbox-net-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenttoolbox-net/openapi/agenttoolbox-net-directory-api-openapi.yml
- filename: agenttoolbox-net-tools-api-openapi.yml
  format: yaml
  label: Agent Toolbox Tools API
  slug: agenttoolbox-net-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenttoolbox-net/openapi/agenttoolbox-net-tools-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: if you subscribe, we store your email address with our email provider to send the newsletter
  - category: identifying
    text: an account id, your email address (private, never shown publicly), your public handle, an optional bio (160 characters)
  - category: device
    text: our host may collect standard server logs (IP, user agent, pages visited)
  - category: financial
    text: We never see or store your full card details.
  deletion:
    route: /account page 'Delete my account' or email to request removal
    text: on /account, "Delete my account" removes your account record, sessions and email address immediately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: send newsletter
    text: we store your email address with our email provider to send the newsletter
  - purpose: rate limiting
    text: We temporarily use your IP address for rate limiting.
  - purpose: affiliate attribution
    text: We also count clicks on our own /go/ affiliate links; these are aggregate counts only, with no personal data.
  - purpose: spam prevention
    text: plus a one-way hash of your IP address for spam and rate limiting
  retention:
  - period: 30 days
    scope: email and account data
    text: We delete your email address and account data within 30 days after you unsubscribe or delete your account.
  - period: up to 30 days
    scope: sessions
    text: a secure, HttpOnly cookie keeps you signed in for up to 30 days
  - period: 15 minutes
    scope: sign-in links
    text: The link expires after 15 minutes; we store only a hash of it.
  rights:
  - right: access or deletion
    text: you may request access to or deletion of your personal data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Toolbox
provenance_date: '2026-11-09'
provider_name: Agent Toolbox
provider_slug: agenttoolbox-net
slug: agenttoolbox-net-privacy-policy
source_date: '2026-11-09'
source_filename: agenttoolbox-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenttoolbox.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Toolbox\naid: agenttoolbox-net\nurl: https://agenttoolbox.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: if you subscribe, we store your email address with our email provider to send the newsletter\n- category: identifying\n  text: an account id, your email address (private, never shown publicly), your public handle, an optional bio (160\n    characters)\n- category: device\n  text: our host may collect standard server logs (IP, user agent, pages visited)\n- category: financial\n  text: We never see or store your full card\
  \ details.\npurposes:\n- purpose: send newsletter\n  text: we store your email address with our email provider to send the newsletter\n- purpose: rate limiting\n  text: We temporarily use your IP address for rate limiting.\n- purpose: affiliate attribution\n  text: We also count clicks on our own /go/ affiliate links; these are aggregate counts only, with no personal\n    data.\n- purpose: spam prevention\n  text: plus a one-way hash of your IP address for spam and rate limiting\nretention:\n- scope: email and account data\n  period: 30 days\n  text: We delete your email address and account data within 30 days after you unsubscribe or delete your account.\n- scope: sessions\n  period: up to 30 days\n  text: a secure, HttpOnly cookie keeps you signed in for up to 30 days\n- scope: sign-in links\n  period: 15 minutes\n  text: The link expires after 15 minutes; we store only a hash of it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n \
  \ url: null\n  text: null\ndeletion:\n  route: /account page 'Delete my account' or email to request removal\n  text: on /account, \"Delete my account\" removes your account record, sessions and email address immediately.\nrights:\n- right: access or deletion\n  text: you may request access to or deletion of your personal data\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agenttoolbox-net/privacy/agenttoolbox-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from Agent Toolbox's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Tools
- Free
- Browser
- Agents
---
