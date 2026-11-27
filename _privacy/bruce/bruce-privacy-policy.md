---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name, email address, and phone number
  - category: contact
    text: Mailing or property address
  - category: professional
    text: Professional role, specialization, and service areas
  - category: biometric
    text: Voice recordings processed by Bruce may constitute biometric identifiers under applicable state laws
  - category: communication
    text: Messages Bruce sends to your clients in your name, by SMS and email, and their responses
  - category: device
    text: Device information, browser type, and IP address
  - category: behavioral
    text: Pages visited, features used, and interaction timestamps
  deletion:
    route: Email support@bruce.bot or delete your account
    text: If you submit a deletion request, Bruce will immediately delete your data from its own systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Client outreach on your behalf
    text: Use the client contacts you upload to send useful, local heads-up and review invitations by SMS and email in your name
  - purpose: Reviews
    text: Invite your clients to leave a review, capture reviews, and connect to your Google Business Profile
  - purpose: AI model improvement
    text: Use anonymized and aggregated data to improve our outreach, voice processing, and platform features
  - purpose: License verification
    text: Validate your professional credentials against public regulatory databases (NMLS, NIPR, DRE, and state-specific licensing authorities)
  retention:
  - period: null
    scope: Account, profile, client and referral partner data
    text: We retain your account, profile, uploaded client data, and referral partner data for as long as your account is active
  - period: null
    scope: Voice recordings
    text: Voice recordings are retained for profile and voice generation unless you request deletion.
  - period: null
    scope: Connected mailbox data
    text: Connected mailbox data is retained for the life of the connection and no longer.
  - period: null
    scope: Mailbox message bodies
    text: 'Message bodies are never retained at all: they are read once during a scan and discarded.'
  rights:
  - right: Edit profile
    text: You may update your professional information, specializations, and preferences at any time through your dashboard or through a voice conversation with Bruce.
  - right: Request data copy
    text: You may request a complete copy of the personal data we hold about you, including the client contacts you uploaded, in a machine-readable format.
  - right: Delete account
    text: You may request account deletion.
  - right: Opt out of communications
    text: You may opt out of non-essential communications (promotional messages) at any time.
  - right: Correct data (California)
    text: 'Right to Correct: You may request correction of inaccurate personal information.'
  - right: Delete data (California)
    text: 'Right to Delete: You may request deletion of your personal information, subject to certain exceptions'
  role:
    text: Bruce is the data controller; each provider acts as a data processor under applicable law
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, lease, or license your personal data to third parties. We do not share your data with advertisers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bruce
provenance_date: '2026-11-09'
provider_name: Bruce
provider_slug: bruce
slug: bruce-privacy-policy
source_date: '2026-11-09'
source_filename: bruce-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bruce.bot/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bruce\naid: bruce\nurl: https://bruce.bot/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Bruce is the data controller; each provider acts as a data processor under applicable law\ndata_categories:\n- category: identifying\n  text: Full name, email address, and phone number\n- category: contact\n  text: Mailing or property address\n- category: professional\n  text: Professional role, specialization, and service areas\n- category: biometric\n  text: Voice recordings processed by Bruce may constitute biometric identifiers under applicable state laws\n- category: communication\n  text:\
  \ Messages Bruce sends to your clients in your name, by SMS and email, and their responses\n- category: device\n  text: Device information, browser type, and IP address\n- category: behavioral\n  text: Pages visited, features used, and interaction timestamps\npurposes:\n- purpose: Client outreach on your behalf\n  text: Use the client contacts you upload to send useful, local heads-up and review invitations by SMS and email\n    in your name\n- purpose: Reviews\n  text: Invite your clients to leave a review, capture reviews, and connect to your Google Business Profile\n- purpose: AI model improvement\n  text: Use anonymized and aggregated data to improve our outreach, voice processing, and platform features\n- purpose: License verification\n  text: Validate your professional credentials against public regulatory databases (NMLS, NIPR, DRE, and state-specific\n    licensing authorities)\nretention:\n- scope: Account, profile, client and referral partner data\n  period: null\n  text: We\
  \ retain your account, profile, uploaded client data, and referral partner data for as long as your account\n    is active\n- scope: Voice recordings\n  period: null\n  text: Voice recordings are retained for profile and voice generation unless you request deletion.\n- scope: Connected mailbox data\n  period: null\n  text: Connected mailbox data is retained for the life of the connection and no longer.\n- scope: Mailbox message bodies\n  period: null\n  text: 'Message bodies are never retained at all: they are read once during a scan and discarded.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@bruce.bot or delete your account\n  text: If you submit a deletion request, Bruce will immediately delete your data from its own systems.\nrights:\n- right: Edit profile\n  text: You may update your professional information, specializations, and preferences at any time through your\n\
  \    dashboard or through a voice conversation with Bruce.\n- right: Request data copy\n  text: You may request a complete copy of the personal data we hold about you, including the client contacts you\n    uploaded, in a machine-readable format.\n- right: Delete account\n  text: You may request account deletion.\n- right: Opt out of communications\n  text: You may opt out of non-essential communications (promotional messages) at any time.\n- right: Correct data (California)\n  text: 'Right to Correct: You may request correction of inaccurate personal information.'\n- right: Delete data (California)\n  text: 'Right to Delete: You may request deletion of your personal information, subject to certain exceptions'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, lease, or license your personal data to third parties. We do not share your data with\n    advertisers.\n"
source_yaml_url: https://artifacts.apis.io/bruce/privacy/bruce-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Bruce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Real Estate
- Mortgage
- Insurance
- Title and Escrow
- Reputation
- Professional Network
- Artificial Intelligence
---
