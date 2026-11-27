---
claim_count: 31
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: identifying
    text: Display name
  - category: demographic
    text: Date of birth (we derive your age from it)
  - category: health
    text: 'Per-day: body weight, body-fat percentage, cardio minutes, sleep duration, mood, and free-text daily notes'
  - category: biometric
    text: Optional biometric unlock is handled on your device and is not sent to us.
  - category: financial
    text: 'A masked card summary only: card brand, last four digits, and expiry'
  - category: behavioral
    text: lifecycle and behavioural events such as signed up, email verified, trial started, trial cancelled, MCP connected, program created, program scheduled, log added, workout logged, and account deleted
  - category: device
    text: device and OS information, app version, IP address, and interactions with the Service
  deletion:
    route: in-app account-deletion option or support@evertrain.app
    text: delete your Account using the in-app account-deletion option . Otherwise, contact support@evertrain.app .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and workout service
    text: Create and manage your Account; provide free-tier features; deliver workouts, logging, and tracking
  - purpose: Billing
    text: Provide the paid tier, the AI Connection, and billing
  - purpose: Security
    text: Keep the Service secure; prevent fraud and abuse; error/crash reporting
  - purpose: Product analytics
    text: Product analytics — non-sensitive lifecycle/behavioural events (no health values) via PostHog
  - purpose: Session replay
    text: Session replay (masked) via PostHog — can capture on-screen health data
  residency:
  - region: United States
    text: Region is the United States (chosen for latency) — see clause 10
  retention:
  - period: For the life of your Account
    scope: Account data
    text: For the life of your Account; deleted (or anonymised) on Account deletion, subject to the wind-down below
  - period: typically up to 7 years in Australia
    scope: Billing records
    text: Retained as required by tax/accounting law (typically up to 7 years in Australia) even after Account deletion
  - period: 'target: up to 12 months'
    scope: Analytics events (PostHog)
    text: 'Retained for a limited analytics window (target: up to 12 months) then aggregated/deleted'
  - period: 'target: up to 30 days'
    scope: Session-replay recordings
    text: 'Short retention (target: up to 30 days) then deleted; not retained if you did not consent'
  rights:
  - right: access
    text: to access your data
  - right: correct
    text: to correct inaccurate data
  - right: delete
    text: to delete it
  - right: restrict or object
    text: to restrict or object to processing
  - right: portability
    text: to data portability
  - right: withdraw consent
    text: to withdraw consent
  role:
    text: The data controller is Gymismo Holdings Pty Ltd (ABN 38 644 206 717) of U603, 3 Henry Street, Turrella NSW, Australia , trading as Evertrain.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not "sell" your personal information, and we do not "share" it for cross-context behavioural advertising
  subprocessors:
    text: We share data with a defined set of sub-processors (infrastructure, billing, video, error reporting, email)
    url: null
  transfers:
  - mechanism: DPF
    text: Google Cloud is certified under the EU–US Data Privacy Framework (and its UK extension)
  - mechanism: SCC
    text: we additionally rely on the European Commission's Standard Contractual Clauses and the UK International Data Transfer Addendum
  - mechanism: other
    text: Your AI vendor — transfer on your explicit consent (Art. 49(1)(a))
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Evertrain
provenance_date: '2026-11-09'
provider_name: Evertrain
provider_slug: evertrain-app
slug: evertrain-app-privacy-policy
source_date: '2026-11-09'
source_filename: evertrain-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://evertrain.app/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Evertrain\naid: evertrain-app\nurl: https://evertrain.app/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Gymismo Holdings Pty Ltd (ABN 38 644 206 717) of U603, 3 Henry Street, Turrella NSW,\n    Australia , trading as Evertrain.\ndata_categories:\n- category: contact\n  text: Email address\n- category: identifying\n  text: Display name\n- category: demographic\n  text: Date of birth (we derive your age from it)\n- category: health\n  text: 'Per-day: body weight, body-fat percentage, cardio minutes, sleep duration, mood, and free-text daily notes'\n- category:\
  \ biometric\n  text: Optional biometric unlock is handled on your device and is not sent to us.\n- category: financial\n  text: 'A masked card summary only: card brand, last four digits, and expiry'\n- category: behavioral\n  text: lifecycle and behavioural events such as signed up, email verified, trial started, trial cancelled, MCP\n    connected, program created, program scheduled, log added, workout logged, and account deleted\n- category: device\n  text: device and OS information, app version, IP address, and interactions with the Service\npurposes:\n- purpose: Account and workout service\n  text: Create and manage your Account; provide free-tier features; deliver workouts, logging, and tracking\n- purpose: Billing\n  text: Provide the paid tier, the AI Connection, and billing\n- purpose: Security\n  text: Keep the Service secure; prevent fraud and abuse; error/crash reporting\n- purpose: Product analytics\n  text: Product analytics — non-sensitive lifecycle/behavioural events (no\
  \ health values) via PostHog\n- purpose: Session replay\n  text: Session replay (masked) via PostHog — can capture on-screen health data\nretention:\n- scope: Account data\n  period: For the life of your Account\n  text: For the life of your Account; deleted (or anonymised) on Account deletion, subject to the wind-down below\n- scope: Billing records\n  period: typically up to 7 years in Australia\n  text: Retained as required by tax/accounting law (typically up to 7 years in Australia) even after Account deletion\n- scope: Analytics events (PostHog)\n  period: 'target: up to 12 months'\n  text: 'Retained for a limited analytics window (target: up to 12 months) then aggregated/deleted'\n- scope: Session-replay recordings\n  period: 'target: up to 30 days'\n  text: 'Short retention (target: up to 30 days) then deleted; not retained if you did not consent'\nresidency:\n- region: United States\n  text: Region is the United States (chosen for latency) — see clause 10\ntransfers:\n- mechanism:\
  \ DPF\n  text: Google Cloud is certified under the EU–US Data Privacy Framework (and its UK extension)\n- mechanism: SCC\n  text: we additionally rely on the European Commission's Standard Contractual Clauses and the UK International\n    Data Transfer Addendum\n- mechanism: other\n  text: Your AI vendor — transfer on your explicit consent (Art. 49(1)(a))\nsubprocessors:\n  url: null\n  text: We share data with a defined set of sub-processors (infrastructure, billing, video, error reporting, email)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app account-deletion option or support@evertrain.app\n  text: delete your Account using the in-app account-deletion option . Otherwise, contact support@evertrain.app\n    .\nrights:\n- right: access\n  text: to access your data\n- right: correct\n  text: to correct inaccurate data\n- right: delete\n  text: to delete it\n- right: restrict or object\n  text: to restrict or object to processing\n- right: portability\n \
  \ text: to data portability\n- right: withdraw consent\n  text: to withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not \"sell\" your personal information, and we do not \"share\" it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/evertrain-app/privacy/evertrain-app-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Evertrain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fitness
- Health
- Training
---
