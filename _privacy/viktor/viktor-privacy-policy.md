---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Slack workspace identifiers (e.g., workspace/team ID) and limited workspace metadata needed to operate the integration.
  - category: contact
    text: Administrator information for the person who installs Viktor (name and email address as provided by Slack).
  - category: communication
    text: Conversation threads and messages between users and Viktor, including agent outputs and tool calls.
  - category: location
    text: Approximate location inferred from your IP address when you create an account and when you use the Service while signed in
  - category: behavioral
    text: Cookie, pixel, and similar online identifiers used for analytics, advertising measurement, and referral attribution.
  - category: device
    text: Device and browser metadata, IP address, pages viewed, and interaction events.
  - category: financial
    text: Billing contact info, transaction metadata (payment details handled by Stripe)
  deletion:
    route: Deletion request to Viktor (support@viktor.com or account deletion); workspace-level requests may need to come from a workspace administrator or account owner.
    text: You may request deletion of your personal data (including workspace files, conversation threads, and related records).
  dpa:
    available: true
    text: under our Data Processing Addendum available at viktor.com/legal/dpa (the "DPA")
    url: viktor.com/legal/dpa
  purposes:
  - purpose: Provide and operate the Service
    text: Authenticate users and workspaces. Maintain Slack and other integrations you enable.
  - purpose: AI processing to generate outputs
    text: Relevant portions of Customer Data may be processed by AI systems to produce responses, reports, and other outputs at your direction.
  - purpose: Security, safety and integrity
    text: Detect and prevent fraud, abuse, and unauthorized access.
  - purpose: Analytics, advertising and attribution
    text: Measure product and website usage, campaign performance, and conversion events.
  - purpose: Service improvement
    text: We may use aggregated or de-identified data (that cannot reasonably identify you) to understand usage patterns and improve reliability and product experience.
  residency:
  - region: United States
    text: Data center location United States.
  retention:
  - period: ~30 days
    scope: Active production systems
    text: When an account is closed or we receive a validated deletion request, we delete Customer Data from active production systems typically within ~30 days.
  - period: ~35 days
    scope: Backups
    text: Remaining copies are removed as encrypted backups age out on their normal rotation (currently ~35 days)
  - period: up to approximately 90 days
    scope: Slack message history
    text: When Viktor joins a channel, it may retrieve up to approximately 90 days of that channel's prior history to establish context.
  rights:
  - right: Access and correction
    text: You can request access to personal data we hold about you and request correction of inaccurate or incomplete data.
  - right: Deletion
    text: You may request deletion of your personal data (including workspace files, conversation threads, and related records).
  - right: Data portability
    text: Where required by law (e.g., GDPR), you may request a copy of your data in a machine-readable format.
  - right: Opt out of sale, sharing or targeted advertising
    text: You can opt out of "sale," "sharing," or targeted advertising at any time by contacting us at support@viktor.com
  - right: Withdraw consent
    text: You can withdraw your consent at any time via the unsubscribe link or by contacting us
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal data for monetary consideration. We may share certain identifiers and usage data with analytics, advertising measurement, and attribution partners to operate and improve the Service.
  subprocessors:
    text: 'Current subprocessors: Subprocessor Service / Purpose Data Potentially Processed Slack Core platform integration (OAuth, messaging, app functionality)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Viktor
provenance_date: '2026-11-10'
provider_name: Viktor
provider_slug: viktor
slug: viktor-privacy-policy
source_date: '2026-11-10'
source_filename: viktor-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.viktor.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Viktor\naid: viktor\nurl: https://app.viktor.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Slack workspace identifiers (e.g., workspace/team ID) and limited workspace metadata needed to operate the\n    integration.\n- category: contact\n  text: Administrator information for the person who installs Viktor (name and email address as provided by Slack).\n- category: communication\n  text: Conversation threads and messages between users and Viktor, including agent outputs and tool calls.\n- category: location\n  text: Approximate\
  \ location inferred from your IP address when you create an account and when you use the Service\n    while signed in\n- category: behavioral\n  text: Cookie, pixel, and similar online identifiers used for analytics, advertising measurement, and referral\n    attribution.\n- category: device\n  text: Device and browser metadata, IP address, pages viewed, and interaction events.\n- category: financial\n  text: Billing contact info, transaction metadata (payment details handled by Stripe)\npurposes:\n- purpose: Provide and operate the Service\n  text: Authenticate users and workspaces. Maintain Slack and other integrations you enable.\n- purpose: AI processing to generate outputs\n  text: Relevant portions of Customer Data may be processed by AI systems to produce responses, reports, and other\n    outputs at your direction.\n- purpose: Security, safety and integrity\n  text: Detect and prevent fraud, abuse, and unauthorized access.\n- purpose: Analytics, advertising and attribution\n  text:\
  \ Measure product and website usage, campaign performance, and conversion events.\n- purpose: Service improvement\n  text: We may use aggregated or de-identified data (that cannot reasonably identify you) to understand usage patterns\n    and improve reliability and product experience.\nretention:\n- scope: Active production systems\n  period: ~30 days\n  text: When an account is closed or we receive a validated deletion request, we delete Customer Data from active\n    production systems typically within ~30 days.\n- scope: Backups\n  period: ~35 days\n  text: Remaining copies are removed as encrypted backups age out on their normal rotation (currently ~35 days)\n- scope: Slack message history\n  period: up to approximately 90 days\n  text: When Viktor joins a channel, it may retrieve up to approximately 90 days of that channel's prior history\n    to establish context.\nresidency:\n- region: United States\n  text: Data center location United States.\ntransfers: []\nsubprocessors:\n \
  \ url: null\n  text: 'Current subprocessors: Subprocessor Service / Purpose Data Potentially Processed Slack Core platform integration\n    (OAuth, messaging, app functionality)'\ndpa:\n  available: true\n  url: viktor.com/legal/dpa\n  text: under our Data Processing Addendum available at viktor.com/legal/dpa (the \"DPA\")\ndeletion:\n  route: Deletion request to Viktor (support@viktor.com or account deletion); workspace-level requests may need\n    to come from a workspace administrator or account owner.\n  text: You may request deletion of your personal data (including workspace files, conversation threads, and related\n    records).\nrights:\n- right: Access and correction\n  text: You can request access to personal data we hold about you and request correction of inaccurate or incomplete\n    data.\n- right: Deletion\n  text: You may request deletion of your personal data (including workspace files, conversation threads, and related\n    records).\n- right: Data portability\n  text:\
  \ Where required by law (e.g., GDPR), you may request a copy of your data in a machine-readable format.\n- right: Opt out of sale, sharing or targeted advertising\n  text: You can opt out of \"sale,\" \"sharing,\" or targeted advertising at any time by contacting us at support@viktor.com\n- right: Withdraw consent\n  text: You can withdraw your consent at any time via the unsubscribe link or by contacting us\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal data for monetary consideration. We may share certain identifiers and usage\n    data with analytics, advertising measurement, and attribution partners to operate and improve the Service.\n"
source_yaml_url: https://artifacts.apis.io/viktor/privacy/viktor-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Viktor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Artificial Intelligence
- AI Agents
- Automation
- Slack
- Microsoft Teams
- Productivity
- Workflows
---
