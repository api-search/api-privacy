---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address
  - category: contact
    text: Email address
  - category: device
    text: IP address and User-Agent (for rate limiting and security)
  - category: financial
    text: 'We receive from Stripe only: subscription status, plan type, and a customer identifier.'
  deletion:
    route: Contact us to request account deletion
    text: Delete your account — contact us and we will delete your data within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Authenticate identity and authorize API access
    text: Authenticate your identity and authorize API access
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud, abuse, and security incidents
  - purpose: Aggregate analytics
    text: Generate aggregate, anonymized analytics to improve the platform
  residency:
  - region: US-Central1
    text: 'Database: Google Cloud SQL (PostgreSQL 16), encrypted at rest, US-Central1 region'
  retention:
  - period: 30 days
    scope: Account data
    text: Deleted within 30 days of account deletion request.
  - period: 90 days
    scope: API call logs
    text: Retained for 90 days for analytics, then aggregated and anonymized.
  - period: 10 minutes
    scope: OTP codes
    text: Automatically expired and purged after 10 minutes.
  - period: 1 hour
    scope: Password reset tokens
    text: Expired and purged after 1 hour.
  - period: 7-day retention
    scope: Backups
    text: GPG-encrypted daily backups to Google Cloud Storage with 7-day retention
  rights:
  - right: Access
    text: Access your personal data — view your profile and usage history in the dashboard
  - right: Correction
    text: Correct inaccurate data — update your display name and email in settings
  - right: Deletion
    text: Delete your account — contact us and we will delete your data within 30 days
  - right: Export
    text: Export your data — request a copy of your data via our contact form
  - right: Restrict processing
    text: Restrict processing — you may revoke API keys at any time to stop data collection
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: crowvault-ai
provenance_date: '2026-11-09'
provider_name: crowvault-ai
provider_slug: crowvault-ai
slug: crowvault-ai-privacy-policy
source_date: '2026-11-09'
source_filename: crowvault-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crowvault.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: crowvault-ai\naid: crowvault-ai\nurl: https://crowvault.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address\n- category: contact\n  text: Email address\n- category: device\n  text: IP address and User-Agent (for rate limiting and security)\n- category: financial\n  text: 'We receive from Stripe only: subscription status, plan type, and a customer identifier.'\npurposes:\n- purpose: Provide, maintain, and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Authenticate identity and authorize\
  \ API access\n  text: Authenticate your identity and authorize API access\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud, abuse, and security incidents\n- purpose: Aggregate analytics\n  text: Generate aggregate, anonymized analytics to improve the platform\nretention:\n- scope: Account data\n  period: 30 days\n  text: Deleted within 30 days of account deletion request.\n- scope: API call logs\n  period: 90 days\n  text: Retained for 90 days for analytics, then aggregated and anonymized.\n- scope: OTP codes\n  period: 10 minutes\n  text: Automatically expired and purged after 10 minutes.\n- scope: Password reset tokens\n  period: 1 hour\n  text: Expired and purged after 1 hour.\n- scope: Backups\n  period: 7-day retention\n  text: GPG-encrypted daily backups to Google Cloud Storage with 7-day retention\nresidency:\n- region: US-Central1\n  text: 'Database:\
  \ Google Cloud SQL (PostgreSQL 16), encrypted at rest, US-Central1 region'\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us to request account deletion\n  text: Delete your account — contact us and we will delete your data within 30 days\nrights:\n- right: Access\n  text: Access your personal data — view your profile and usage history in the dashboard\n- right: Correction\n  text: Correct inaccurate data — update your display name and email in settings\n- right: Deletion\n  text: Delete your account — contact us and we will delete your data within 30 days\n- right: Export\n  text: Export your data — request a copy of your data via our contact form\n- right: Restrict processing\n  text: Restrict processing — you may revoke API keys at any time to stop data collection\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/crowvault-ai/privacy/crowvault-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from crowvault-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Developer Tools
- Automation
- Cloud
- Platform
---
