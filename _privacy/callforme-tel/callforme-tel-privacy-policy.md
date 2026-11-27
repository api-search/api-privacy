---
api_specs:
- filename: callforme-tel-account-api-openapi.yml
  format: yaml
  label: CallForMe Account API
  slug: callforme-tel-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-account-api-openapi.yml
- filename: callforme-tel-batches-api-openapi.yml
  format: yaml
  label: CallForMe Batches API
  slug: callforme-tel-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-batches-api-openapi.yml
- filename: callforme-tel-businesses-api-openapi.yml
  format: yaml
  label: CallForMe Businesses API
  slug: callforme-tel-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-businesses-api-openapi.yml
- filename: callforme-tel-calls-api-openapi.yml
  format: yaml
  label: CallForMe Calls API
  slug: callforme-tel-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-calls-api-openapi.yml
- filename: callforme-tel-pricing-api-openapi.yml
  format: yaml
  label: CallForMe Pricing API
  slug: callforme-tel-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-pricing-api-openapi.yml
- filename: callforme-tel-setups-api-openapi.yml
  format: yaml
  label: CallForMe Setups API
  slug: callforme-tel-setups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/callforme-tel/openapi/callforme-tel-setups-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: an account created when you connect your agent, your email and name if you give them
  - category: financial
    text: balance, and a Stripe customer reference
  - category: behavioral
    text: first-party cookies record how you found the site (the link or site that sent you, and the page you landed on)
  - category: device
    text: basic logs (IP address, agent name from the user-agent)
  - category: location
    text: your IP address, which it uses to estimate your country and region
  - category: communication
    text: the transcript, a link to the audio recording, answers, outcome, and cost
  deletion:
    route: email hello@greatwork.company
    text: Email hello@greatwork.company from your account email to delete your account and calls, including the call recordings held by Retell.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention and debugging
    text: basic logs (IP address, agent name from the user-agent) for abuse prevention and debugging
  - purpose: measure which channels work
    text: so we can tell which channels work
  - purpose: analytics
    text: to count visits and see which pages and sources work
  retention:
  - period: while your account is open
    scope: call records
    text: We keep call records while your account is open so your agent can look them up.
  - period: 2 months
    scope: Google Analytics data
    text: We keep this data in Google Analytics for 2 months.
  - period: 14 days
    scope: deleted data in nightly backups
    text: Deleted data also leaves our nightly backups, which we keep for 14 days.
  - period: 90 days
    scope: cfm_s cookie
    text: 'cfm_s : keeps you signed in on the account page (90 days).'
  rights:
  - right: opt out of calls
    text: If you ask not to be called, on the call, by calling +1 (469) 966-0062, or at callforme.tel/for-businesses , your number goes on an opt-out list that applies to every CallForMe user.
  - right: opt out of Google Analytics
    text: To opt out, use a content blocker or Google's opt-out add-on
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data, don't share it for advertising, and don't use it to train AI models.
  subprocessors:
    text: Retell AI and its telephony, speech and language-model providers place, record and transcribe calls and run the voice assistant.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CallForMe
provenance_date: '2026-11-09'
provider_name: CallForMe
provider_slug: callforme-tel
slug: callforme-tel-privacy-policy
source_date: '2026-11-09'
source_filename: callforme-tel-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://callforme.tel/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CallForMe\naid: callforme-tel\nurl: https://callforme.tel/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: an account created when you connect your agent, your email and name if you give them\n- category: financial\n  text: balance, and a Stripe customer reference\n- category: behavioral\n  text: first-party cookies record how you found the site (the link or site that sent you, and the page you landed\n    on)\n- category: device\n  text: basic logs (IP address, agent name from the user-agent)\n- category: location\n  text: your\
  \ IP address, which it uses to estimate your country and region\n- category: communication\n  text: the transcript, a link to the audio recording, answers, outcome, and cost\npurposes:\n- purpose: abuse prevention and debugging\n  text: basic logs (IP address, agent name from the user-agent) for abuse prevention and debugging\n- purpose: measure which channels work\n  text: so we can tell which channels work\n- purpose: analytics\n  text: to count visits and see which pages and sources work\nretention:\n- scope: call records\n  period: while your account is open\n  text: We keep call records while your account is open so your agent can look them up.\n- scope: Google Analytics data\n  period: 2 months\n  text: We keep this data in Google Analytics for 2 months.\n- scope: deleted data in nightly backups\n  period: 14 days\n  text: Deleted data also leaves our nightly backups, which we keep for 14 days.\n- scope: cfm_s cookie\n  period: 90 days\n  text: 'cfm_s : keeps you signed in on the\
  \ account page (90 days).'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Retell AI and its telephony, speech and language-model providers place, record and transcribe calls and\n    run the voice assistant.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@greatwork.company\n  text: Email hello@greatwork.company from your account email to delete your account and calls, including the call\n    recordings held by Retell.\nrights:\n- right: opt out of calls\n  text: If you ask not to be called, on the call, by calling +1 (469) 966-0062, or at callforme.tel/for-businesses\n    , your number goes on an opt-out list that applies to every CallForMe user.\n- right: opt out of Google Analytics\n  text: To opt out, use a content blocker or Google's opt-out add-on\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data, don't share it for advertising, and don't use it to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/callforme-tel/privacy/callforme-tel-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from CallForMe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Voice
- Phone Calls
- Telephony
- MCP
- REST API
---
