---
api_specs:
- filename: shotkit-net-openapi-generated.yml
  format: yaml
  label: shotkit-net API
  slug: shotkit-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shotkit-net/openapi/_ae-authored/shotkit-net-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'When you sign up: your name, email address and a hash of your password (we never store the password itself).'
  - category: device
    text: we store a session with your IP address and browser user agent
  - category: financial
    text: We store your Stripe customer ID and your subscription's plan and status.
  - category: behavioral
    text: For each API request we record the workspace, the time, the source (the URL you rendered, or just "html" or "markdown" for raw content), the format, the status, the duration, the size and whether it was a cache hit.
  - category: communication
    text: If you message us through the chat widget or by email, we keep the conversation to help you.
  deletion:
    route: Ask us to delete your account
    text: When you ask us to delete your account, we delete your personal data except what we must keep by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: your account, rendering, file delivery, usage limits and billing (performing our contract with you).'
  - purpose: Account emails
    text: 'To send account emails: email verification, password resets, and messages about your subscription.'
  - purpose: Onboarding emails
    text: To send a short series of onboarding emails after you verify your email, chosen by whether you've taken a screenshot and your plan (legitimate interest).
  - purpose: Abuse prevention and security
    text: To prevent abuse and keep the service secure, for example bot checks at sign-up and rate limits (our legitimate interest).
  - purpose: Aggregate site analytics
    text: To understand how the site is used, in aggregate (legitimate interest).
  residency:
  - region: United States
    text: Some of these providers process data outside your country, including in the United States, under their own safeguards such as standard contractual clauses.
  retention:
  - period: 4 hours by default
    scope: Rendered files
    text: 'deleted automatically when they expire: after 4 hours by default, or after the cache_ttl you set (at most 30 days)'
  - period: 30 days
    scope: Rendered files maximum
    text: after the cache_ttl you set (at most 30 days)
  - period: null
    scope: Sessions
    text: Sessions expire after inactivity.
  - period: null
    scope: Account, workspace and usage data
    text: Account, workspace and usage data are kept while your account exists.
  - period: null
    scope: Billing records
    text: Billing records may be kept longer where tax law requires it.
  rights:
  - right: Access, correction, export, deletion
    text: You can ask us to access, correct, export or delete your personal data
  - right: Object
    text: or object to how we use it, by emailing hello@shotkit.net
  - right: Complaint to authority
    text: you can also complain to your local data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data and we don't use it for advertising.
  subprocessors:
    text: 'We use these kinds of providers to run shotkit. Each one only gets the data it needs:'
    url: null
  transfers:
  - mechanism: SCC
    text: under their own safeguards such as standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: shotkit-net
provenance_date: '2026-11-10'
provider_name: shotkit-net
provider_slug: shotkit-net
slug: shotkit-net-privacy-policy
source_date: '2026-11-10'
source_filename: shotkit-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shotkit.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: shotkit-net\naid: shotkit-net\nurl: https://shotkit.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'When you sign up: your name, email address and a hash of your password (we never store the password itself).'\n- category: device\n  text: we store a session with your IP address and browser user agent\n- category: financial\n  text: We store your Stripe customer ID and your subscription's plan and status.\n- category: behavioral\n  text: For each API request we record the workspace, the time, the source (the URL you rendered,\
  \ or just \"html\"\n    or \"markdown\" for raw content), the format, the status, the duration, the size and whether it was a cache hit.\n- category: communication\n  text: If you message us through the chat widget or by email, we keep the conversation to help you.\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: your account, rendering, file delivery, usage limits and billing (performing our\n    contract with you).'\n- purpose: Account emails\n  text: 'To send account emails: email verification, password resets, and messages about your subscription.'\n- purpose: Onboarding emails\n  text: To send a short series of onboarding emails after you verify your email, chosen by whether you've taken\n    a screenshot and your plan (legitimate interest).\n- purpose: Abuse prevention and security\n  text: To prevent abuse and keep the service secure, for example bot checks at sign-up and rate limits (our legitimate\n    interest).\n- purpose: Aggregate site analytics\n\
  \  text: To understand how the site is used, in aggregate (legitimate interest).\nretention:\n- scope: Rendered files\n  period: 4 hours by default\n  text: 'deleted automatically when they expire: after 4 hours by default, or after the cache_ttl you set (at most\n    30 days)'\n- scope: Rendered files maximum\n  period: 30 days\n  text: after the cache_ttl you set (at most 30 days)\n- scope: Sessions\n  period: null\n  text: Sessions expire after inactivity.\n- scope: Account, workspace and usage data\n  period: null\n  text: Account, workspace and usage data are kept while your account exists.\n- scope: Billing records\n  period: null\n  text: Billing records may be kept longer where tax law requires it.\nresidency:\n- region: United States\n  text: Some of these providers process data outside your country, including in the United States, under their own\n    safeguards such as standard contractual clauses.\ntransfers:\n- mechanism: SCC\n  text: under their own safeguards such as standard\
  \ contractual clauses\nsubprocessors:\n  url: null\n  text: 'We use these kinds of providers to run shotkit. Each one only gets the data it needs:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask us to delete your account\n  text: When you ask us to delete your account, we delete your personal data except what we must keep by law.\nrights:\n- right: Access, correction, export, deletion\n  text: You can ask us to access, correct, export or delete your personal data\n- right: Object\n  text: or object to how we use it, by emailing hello@shotkit.net\n- right: Complaint to authority\n  text: you can also complain to your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data and we don't use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/shotkit-net/privacy/shotkit-net-privacy-policy.yml
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
summary_line: 23 quoted statements, read from shotkit-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screenshots
- Web
- Automation
---
