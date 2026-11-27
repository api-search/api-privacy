---
api_specs:
- filename: ugcagent-messages-api-openapi.yml
  format: yaml
  label: UGC Agent Messages API
  slug: ugcagent-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ugcagent/openapi/ugcagent-messages-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process information such as your name, email address, Firebase user identifier, authentication status, organization or team membership, invitations, preferences, and communications with support.
  - category: financial
    text: We receive limited billing records such as Stripe customer and subscription identifiers, plan, billing period, subscription status, renewal or cancellation status, and transaction metadata.
  - category: behavioral
    text: Product analytics may include the text of a submitted creator-search goal, limited to 1,000 characters, so we can investigate result quality.
  - category: device
    text: We and our providers may process IP address, browser and device details, approximate location derived from IP, pages viewed, referring URL, timestamps, feature interactions, errors, subscription events, run status and counts, and session or console diagnostics.
  - category: professional
    text: public business emails, portfolio links, follower and engagement information, public posts or videos, content metrics, brand references
  deletion:
    route: Email hello@ugcagent.app with the subject “Privacy request.”
    text: Email hello@ugcagent.app with the subject “Privacy request.” Describe the right you want to exercise and the account, email, or public profile involved.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: authenticate users, run searches, enrich and score creator profiles, store conversations and lists, operate automations and MCP access, generate exports, and provide support.'
  - purpose: Process subscriptions
    text: 'Process subscriptions: initiate checkout, maintain plan entitlements, apply usage limits, handle team access, and connect users with Stripe’s billing portal.'
  - purpose: Improve and troubleshoot
    text: 'Improve and troubleshoot: measure feature performance, understand failed or difficult searches, replay technical sessions, diagnose errors, and develop safer or more accurate workflows.'
  residency:
  - region: United States, European Economic Area, and other countries
    text: UGC Agent and its providers may process information in the United States, European Economic Area, and other countries where they operate.
  retention:
  - period: null
    scope: Account and product information
    text: We retain account and product information while an account is active and afterward only as long as reasonably needed to provide requested access, resolve disputes, enforce agreements, maintain security and deduplication records, comply with law, or complete a verified deletion request.
  - period: null
    scope: Public creator information
    text: Public creator information is retained in user conversations, lists, exports, and operational deduplication records until deleted, suppressed, refreshed, or no longer needed for the requested business workflow.
  rights:
  - right: access
    text: you may have rights to know or access personal information, correct it, request deletion, restrict processing, receive portable data, object to certain processing, withdraw consent, opt out of marketing, and lodge a complaint with a data-protection authority.
  - right: correction or deletion of creator data
    text: A creator may request correction, suppression, or deletion as described below.
  role:
    text: Autopilot, operating UGC Agent, is the controller of personal information described in this policy unless a different party is identified at collection.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell customer account information or customer content for money, and we do not share them for cross-context behavioral advertising.
  subprocessors:
    text: Providers may change as the Service evolves.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on adequacy decisions, contractual safeguards such as standard contractual clauses, or another lawful transfer mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UGC Agent
provenance_date: '2026-11-10'
provider_name: UGC Agent
provider_slug: ugcagent
slug: ugcagent-privacy-policy
source_date: '2026-11-10'
source_filename: ugcagent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ugcagent.app/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UGC Agent\naid: ugcagent\nurl: https://ugcagent.app/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Autopilot, operating UGC Agent, is the controller of personal information described in this policy unless\n    a different party is identified at collection.\ndata_categories:\n- category: identifying\n  text: We process information such as your name, email address, Firebase user identifier, authentication status,\n    organization or team membership, invitations, preferences, and communications with support.\n- category: financial\n  text: We receive limited billing records such as\
  \ Stripe customer and subscription identifiers, plan, billing period,\n    subscription status, renewal or cancellation status, and transaction metadata.\n- category: behavioral\n  text: Product analytics may include the text of a submitted creator-search goal, limited to 1,000 characters,\n    so we can investigate result quality.\n- category: device\n  text: We and our providers may process IP address, browser and device details, approximate location derived from\n    IP, pages viewed, referring URL, timestamps, feature interactions, errors, subscription events, run status and\n    counts, and session or console diagnostics.\n- category: professional\n  text: public business emails, portfolio links, follower and engagement information, public posts or videos, content\n    metrics, brand references\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: authenticate users, run searches, enrich and score creator profiles, store conversations\n    and lists, operate automations\
  \ and MCP access, generate exports, and provide support.'\n- purpose: Process subscriptions\n  text: 'Process subscriptions: initiate checkout, maintain plan entitlements, apply usage limits, handle team access,\n    and connect users with Stripe’s billing portal.'\n- purpose: Improve and troubleshoot\n  text: 'Improve and troubleshoot: measure feature performance, understand failed or difficult searches, replay\n    technical sessions, diagnose errors, and develop safer or more accurate workflows.'\nretention:\n- scope: Account and product information\n  period: null\n  text: We retain account and product information while an account is active and afterward only as long as reasonably\n    needed to provide requested access, resolve disputes, enforce agreements, maintain security and deduplication\n    records, comply with law, or complete a verified deletion request.\n- scope: Public creator information\n  period: null\n  text: Public creator information is retained in user conversations,\
  \ lists, exports, and operational deduplication\n    records until deleted, suppressed, refreshed, or no longer needed for the requested business workflow.\nresidency:\n- region: United States, European Economic Area, and other countries\n  text: UGC Agent and its providers may process information in the United States, European Economic Area, and other\n    countries where they operate.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on adequacy decisions, contractual safeguards such as standard contractual clauses,\n    or another lawful transfer mechanism.\nsubprocessors:\n  url: null\n  text: Providers may change as the Service evolves.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@ugcagent.app with the subject “Privacy request.”\n  text: Email hello@ugcagent.app with the subject “Privacy request.” Describe the right you want to exercise and\n    the account, email, or public profile involved.\nrights:\n- right: access\n  text: you\
  \ may have rights to know or access personal information, correct it, request deletion, restrict processing,\n    receive portable data, object to certain processing, withdraw consent, opt out of marketing, and lodge a complaint\n    with a data-protection authority.\n- right: correction or deletion of creator data\n  text: A creator may request correction, suppression, or deletion as described below.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell customer account information or customer content for money, and we do not share them for\n    cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/ugcagent/privacy/ugcagent-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from UGC Agent's own page on 2026-11-10.
synthetic: false
tags:
- Company
- UGC
- Marketing
- Data
- Creators
---
