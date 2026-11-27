---
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data - Name, email address, and profile information provided through Clerk authentication.
  - category: contact
    text: Email address - Used to link your Slack identity to your Atomic Reps account
  - category: behavioral
    text: Daily practice data - Answers to daily questions, streaks, progress tracking, and team-level aggregate statistics.
  - category: device
    text: IP address and request metadata, processed for security and abuse prevention.
  - category: communication
    text: Slack integration data - Workspace ID, bot tokens, user ID mapping, email addresses, and display names
  deletion:
    route: Self-serve erasure from account page or Me tab in the iPhone app; otherwise email privacy@atomicreps.com
    text: Access, export and erasure of your own data are self-serve from your account page on the web, and erasure also from the Me tab in the iPhone app
  dpa:
    available: true
    text: a Data Processing Agreement under GDPR Art 28 is published at /dpa .
    url: /dpa
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: games, daily practice sessions, and leaderboards.'
  - purpose: Security and abuse prevention
    text: 'Beyond providing the Service, we use personal data only for the limited purposes set out in "Lawful basis for processing" above: security and abuse prevention, optional analytics and marketing email (which you can decline or withdraw), and legally required record-keeping.'
  - purpose: Improve platform and question quality
    text: We retain your practice data both for your own visibility (your record, streaks, and certificates) and to improve the platform, for example tuning question difficulty and detecting broken questions.
  residency:
  - region: Ireland (EU)
    text: 'Location: EU West (Ireland).'
  - region: Germany (EU, PostHog)
    text: 'Location: EU (Frankfurt).'
  retention:
  - period: null
    scope: Free tier anonymous aggregates
    text: Anonymous aggregate statistics (response counts, accuracy rates, domain-level metrics) on a 90-day rolling window.
  - period: null
    scope: Team plan attribution layer
    text: The workspace's attribution layer (which member answered, for streaks and participation) runs on a 365-day rolling window
  - period: 15 days
    scope: Slack-specific data after uninstall
    text: is permanently deleted within 15 days (a 14-day retention window plus a daily deletion sweep)
  - period: 365 days
    scope: Workspace audit log
    text: are kept for 365 days from the event, after which a weekly job purges them automatically
  - period: 7 years
    scope: Billing and tax records
    text: Retained for 7 years as required by Swedish Bokföringslagen (1999:1078) and equivalent foreign law.
  rights:
  - right: Access
    text: Access your personal data we hold (Art 15).
  - right: Export
    text: Export (data portability) in a machine-readable format (Art 20).
  - right: Correction
    text: Correct inaccurate or incomplete data (Art 16).
  - right: Erasure
    text: Delete your personal data (Art 17).
  - right: Object
    text: Object (Art 21) to processing of your personal data, including processing under legitimate-interest grounds.
  - right: Restriction
    text: Restriction of processing (Art 18).
  - right: Withdraw consent
    text: Withdraw consent at any time, where processing is based on consent (Art 7(3)).
  role:
    text: Controller Account data, billing data, marketing email, security logs, and product analytics. Processor Workspace member practice data, processed on behalf of your organization
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information and have not done so in the preceding twelve months
  subprocessors:
    text: The same list, as a table, is at /subprocessors .
    url: /subprocessors
  transfers:
  - mechanism: DPF
    text: EU-US Data Privacy Framework - Clerk, Slack (through Salesforce, Inc.), and Stripe (Polar's payment-card processor) are certified under the EU-US Data Privacy Framework
  - mechanism: SCC
    text: 'Convex and Cloudflare operate under the EU SCCs approved by the European Commission: Module 2 (controller-to-processor) where we act as controller, and Module 3 (processor-to-processor) where we act as processor on behalf of your organization.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atomic Reps AB
provenance_date: '2026-11-09'
provider_name: Atomic Reps AB
provider_slug: atomicreps-com
slug: atomicreps-com-privacy-policy
source_date: '2026-11-09'
source_filename: atomicreps-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://atomicreps.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atomic Reps AB\naid: atomicreps-com\nurl: https://atomicreps.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Controller Account data, billing data, marketing email, security logs, and product analytics. Processor\n    Workspace member practice data, processed on behalf of your organization\ndata_categories:\n- category: identifying\n  text: Account data - Name, email address, and profile information provided through Clerk authentication.\n- category: contact\n  text: Email address - Used to link your Slack identity to your Atomic Reps account\n- category: behavioral\n  text: Daily practice\
  \ data - Answers to daily questions, streaks, progress tracking, and team-level aggregate statistics.\n- category: device\n  text: IP address and request metadata, processed for security and abuse prevention.\n- category: communication\n  text: Slack integration data - Workspace ID, bot tokens, user ID mapping, email addresses, and display names\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: games, daily practice sessions, and leaderboards.'\n- purpose: Security and abuse prevention\n  text: 'Beyond providing the Service, we use personal data only for the limited purposes set out in \"Lawful basis\n    for processing\" above: security and abuse prevention, optional analytics and marketing email (which you can\n    decline or withdraw), and legally required record-keeping.'\n- purpose: Improve platform and question quality\n  text: We retain your practice data both for your own visibility (your record, streaks, and certificates) and to\n    improve the platform,\
  \ for example tuning question difficulty and detecting broken questions.\nretention:\n- scope: Free tier anonymous aggregates\n  period: null\n  text: Anonymous aggregate statistics (response counts, accuracy rates, domain-level metrics) on a 90-day rolling\n    window.\n- scope: Team plan attribution layer\n  period: null\n  text: The workspace's attribution layer (which member answered, for streaks and participation) runs on a 365-day\n    rolling window\n- scope: Slack-specific data after uninstall\n  period: 15 days\n  text: is permanently deleted within 15 days (a 14-day retention window plus a daily deletion sweep)\n- scope: Workspace audit log\n  period: 365 days\n  text: are kept for 365 days from the event, after which a weekly job purges them automatically\n- scope: Billing and tax records\n  period: 7 years\n  text: Retained for 7 years as required by Swedish Bokföringslagen (1999:1078) and equivalent foreign law.\nresidency:\n- region: Ireland (EU)\n  text: 'Location: EU West\
  \ (Ireland).'\n- region: Germany (EU, PostHog)\n  text: 'Location: EU (Frankfurt).'\ntransfers:\n- mechanism: DPF\n  text: EU-US Data Privacy Framework - Clerk, Slack (through Salesforce, Inc.), and Stripe (Polar's payment-card\n    processor) are certified under the EU-US Data Privacy Framework\n- mechanism: SCC\n  text: 'Convex and Cloudflare operate under the EU SCCs approved by the European Commission: Module 2 (controller-to-processor)\n    where we act as controller, and Module 3 (processor-to-processor) where we act as processor on behalf of your\n    organization.'\nsubprocessors:\n  url: /subprocessors\n  text: The same list, as a table, is at /subprocessors .\ndpa:\n  available: true\n  url: /dpa\n  text: a Data Processing Agreement under GDPR Art 28 is published at /dpa .\ndeletion:\n  route: Self-serve erasure from account page or Me tab in the iPhone app; otherwise email privacy@atomicreps.com\n  text: Access, export and erasure of your own data are self-serve from your account\
  \ page on the web, and erasure\n    also from the Me tab in the iPhone app\nrights:\n- right: Access\n  text: Access your personal data we hold (Art 15).\n- right: Export\n  text: Export (data portability) in a machine-readable format (Art 20).\n- right: Correction\n  text: Correct inaccurate or incomplete data (Art 16).\n- right: Erasure\n  text: Delete your personal data (Art 17).\n- right: Object\n  text: Object (Art 21) to processing of your personal data, including processing under legitimate-interest grounds.\n- right: Restriction\n  text: Restriction of processing (Art 18).\n- right: Withdraw consent\n  text: Withdraw consent at any time, where processing is based on consent (Art 7(3)).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information and have not done so in the preceding twelve months\n"
source_yaml_url: https://artifacts.apis.io/atomicreps-com/privacy/atomicreps-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Atomic Reps AB's own page on 2026-11-09.
synthetic: false
tags:
- Developer Tools
- Education
- Artificial Intelligence
- Software Engineering
- Sweden
---
