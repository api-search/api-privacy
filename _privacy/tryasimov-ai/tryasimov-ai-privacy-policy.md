---
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name or display name, email address, phone number if provided, account status, role, login records, consent status, and account deletion requests.
  - category: location
    text: Self-reported height/body-scale metadata, country/region, languages, experience, environment, useful equipment, and profile completion status.
  - category: behavioral
    text: Event markers such as privacy risk, interruption, bad camera angle, task changed, or important moment.
  - category: device
    text: Device model, OS version, app version, identifierForVendor as a weak local signal, App Attest status, DeviceCheck status, IP-derived server logs, upload timing, file sizes, checksums, retry counts, and suspicious activity flags.
  - category: financial
    text: Stripe Connect onboarding status, connected-account identifiers, payout eligibility, payable balances, payout records, transfer status, bank-payout status when Stripe reports it, failed payout status, and related payment metadata.
  - category: other
    text: First-person RGB video recorded during assigned tasks.
  - category: communication
    text: Microphone narration audio only when an assignment requires narration or when a collector explicitly opts into optional narration for that assignment.
  deletion:
    route: Account deletion in the app; support requests to support@tryasimov.ai
    text: Collectors may request account deletion in the app. Asimov will delete or de-identify eligible information, subject to retention requirements and rights already granted for accepted data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide accounts, assignments, recording, upload, QA, and payout status
    text: Provide collector accounts, assignments, recording, upload, QA, and payout status.
  - purpose: Match collectors to assignments
    text: Match collectors to assignments using self-reported profile metadata.
  - purpose: Build and sell robotics and AI training datasets
    text: Build, annotate, validate, improve, sell, license, sublicense, or share robotics and AI training datasets with customers and service providers, where the collector has provided required consent.
  - purpose: Fraud and security
    text: Detect fraud, duplicate submissions, unsafe behavior, abuse, account compromise, or policy violations.
  retention:
  - period: null
    scope: Account, consent, upload, QA, payout, fraud, and audit records
    text: Asimov retains account, consent, upload, QA, payout, fraud, and audit records as needed to operate the service and meet legal, tax, accounting, fraud-prevention, dispute, safety, and contractual obligations.
  - period: null
    scope: Accepted or licensed data
    text: Account deletion does not automatically recall datasets already accepted, licensed, sold, shared with customers, or retained under prior consent.
  rights:
  - right: Account deletion
    text: Collectors may request account deletion in the app.
  - right: Consent withdrawal
    text: collectors who want to withdraw consent should contact support@tryasimov.ai or use the account deletion flow.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: allowed
    text: Accepted data may be sold, licensed, sublicensed, shared, or otherwise provided to robotics, AI, annotation, QA, processing, storage, infrastructure, and customer organizations for robotics training, evaluation, dataset creation, model development, and related research or commercial uses.
  subprocessors:
    text: Asimov may use processors including AWS for storage, upload processing, logs, and infrastructure; Stripe for Connect onboarding, identity/payment workflows, and payouts
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Asimov
provenance_date: '2026-11-10'
provider_name: Asimov
provider_slug: tryasimov-ai
slug: tryasimov-ai-privacy-policy
source_date: '2026-11-10'
source_filename: tryasimov-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tryasimov.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Asimov\naid: tryasimov-ai\nurl: https://tryasimov.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name or display name, email address, phone number if provided, account status, role, login records, consent\n    status, and account deletion requests.\n- category: location\n  text: Self-reported height/body-scale metadata, country/region, languages, experience, environment, useful equipment,\n    and profile completion status.\n- category: behavioral\n  text: Event markers such as privacy risk, interruption, bad camera angle, task\
  \ changed, or important moment.\n- category: device\n  text: Device model, OS version, app version, identifierForVendor as a weak local signal, App Attest status, DeviceCheck\n    status, IP-derived server logs, upload timing, file sizes, checksums, retry counts, and suspicious activity\n    flags.\n- category: financial\n  text: Stripe Connect onboarding status, connected-account identifiers, payout eligibility, payable balances, payout\n    records, transfer status, bank-payout status when Stripe reports it, failed payout status, and related payment\n    metadata.\n- category: other\n  text: First-person RGB video recorded during assigned tasks.\n- category: communication\n  text: Microphone narration audio only when an assignment requires narration or when a collector explicitly opts\n    into optional narration for that assignment.\npurposes:\n- purpose: Provide accounts, assignments, recording, upload, QA, and payout status\n  text: Provide collector accounts, assignments, recording,\
  \ upload, QA, and payout status.\n- purpose: Match collectors to assignments\n  text: Match collectors to assignments using self-reported profile metadata.\n- purpose: Build and sell robotics and AI training datasets\n  text: Build, annotate, validate, improve, sell, license, sublicense, or share robotics and AI training datasets\n    with customers and service providers, where the collector has provided required consent.\n- purpose: Fraud and security\n  text: Detect fraud, duplicate submissions, unsafe behavior, abuse, account compromise, or policy violations.\nretention:\n- scope: Account, consent, upload, QA, payout, fraud, and audit records\n  period: null\n  text: Asimov retains account, consent, upload, QA, payout, fraud, and audit records as needed to operate the service\n    and meet legal, tax, accounting, fraud-prevention, dispute, safety, and contractual obligations.\n- scope: Accepted or licensed data\n  period: null\n  text: Account deletion does not automatically recall\
  \ datasets already accepted, licensed, sold, shared with customers,\n    or retained under prior consent.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Asimov may use processors including AWS for storage, upload processing, logs, and infrastructure; Stripe\n    for Connect onboarding, identity/payment workflows, and payouts\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in the app; support requests to support@tryasimov.ai\n  text: Collectors may request account deletion in the app. Asimov will delete or de-identify eligible information,\n    subject to retention requirements and rights already granted for accepted data.\nrights:\n- right: Account deletion\n  text: Collectors may request account deletion in the app.\n- right: Consent withdrawal\n  text: collectors who want to withdraw consent should contact support@tryasimov.ai or use the account deletion\n    flow.\nsale_or_sharing:\n  stance: allowed\n  text: Accepted data\
  \ may be sold, licensed, sublicensed, shared, or otherwise provided to robotics, AI, annotation,\n    QA, processing, storage, infrastructure, and customer organizations for robotics training, evaluation, dataset\n    creation, model development, and related research or commercial uses.\n"
source_yaml_url: https://artifacts.apis.io/tryasimov-ai/privacy/tryasimov-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Asimov's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Data
- Artificial Intelligence
- Human Intelligence
---
