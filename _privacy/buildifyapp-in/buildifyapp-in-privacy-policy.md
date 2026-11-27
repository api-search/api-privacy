---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, I receive your email address and a user ID (via the authentication provider, Supabase)
  - category: contact
    text: The email address you invited and a one-way hash of the invite link's token, never the token itself.
  - category: behavioral
    text: Anonymous usage analytics (in the extension) To understand where new users get stuck during setup, Coauth records a few anonymous product events
  - category: device
    text: Each event carries a random installation ID generated on your device, the event name, the extension version
  - category: financial
    text: Billing, if you upgrade. Your plan, the subscription's status and renewal date, and the customer ID the payment processor gives you
  - category: communication
    text: 'Coauth sends three kinds of email through Resend: sign-in codes, team invites, and onboarding tips and reminders.'
  - category: other
    text: Passwords (with the notes and password history saved alongside them), passkey private keys, the text of your notes and your authenticator (2FA) secrets are encrypted on your device before they are saved or synced.
  deletion:
    route: Email kalpesh@buildifyapp.in to request deletion of account and vault data
    text: 'Delete your account and data: email me and I will delete your account records and vault data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run password and passkey sync and autofill
    text: 'Coauth is a zero-knowledge password and passkey manager: it saves, autofills, and generates your website logins'
  - purpose: Account creation and sign-in
    text: to create your account and sync your vault
  - purpose: Team sharing
    text: Team names, membership, roles, and an activity log of team actions, needed to make sharing work.
  - purpose: Billing
    text: Dodo tells Coauth whether your subscription is active and when it renews, so Pro can be switched on for your account.
  - purpose: Breach check
    text: For each password, Coauth computes a SHA-1 hash on your device and sends only the first 5 characters of that hash
  - purpose: Fixing onboarding drop-off
    text: I use it only to fix drop-off in onboarding
  residency:
  - region: ap-south-1
    text: Encrypted vault data, team data, and account records are stored with Supabase (Postgres), region ap-south-1.
  retention:
  - period: until you delete your account
    scope: Account and vault data
    text: Your account and vault data are kept until you delete your account.
  - period: removed when the team is deleted
    scope: Team data
    text: Team data is removed when the team is deleted.
  - period: for the life of the team
    scope: Audit-log entries
    text: Audit-log entries are retained for the life of the team.
  - period: 48 hours
    scope: Invites
    text: An invite expires 48 hours after it is sent.
  rights:
  - right: Unsubscribe from tips and reminders
    text: Unsubscribe from tips and reminders with the link in any of those emails.
  - right: Remove passkeys
    text: Remove a personal passkey, or unshare a team passkey, at any time from the popup.
  role:
    text: Coauth is built and run by Kalpesh Mahida under the Buildify name (buildifyapp.in). "I" in this policy means him.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: I do not sell or rent your data to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Buildify
provenance_date: '2026-11-09'
provider_name: Buildify
provider_slug: buildifyapp-in
slug: buildifyapp-in-privacy-policy
source_date: '2026-11-09'
source_filename: buildifyapp-in-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.buildifyapp.in/coauth/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Buildify\naid: buildifyapp-in\nurl: https://www.buildifyapp.in/coauth/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Coauth is built and run by Kalpesh Mahida under the Buildify name (buildifyapp.in). \"I\" in this policy means\n    him.\ndata_categories:\n- category: identifying\n  text: When you create an account, I receive your email address and a user ID (via the authentication provider,\n    Supabase)\n- category: contact\n  text: The email address you invited and a one-way hash of the invite link's token, never the token itself.\n- category: behavioral\n  text: Anonymous usage\
  \ analytics (in the extension) To understand where new users get stuck during setup, Coauth\n    records a few anonymous product events\n- category: device\n  text: Each event carries a random installation ID generated on your device, the event name, the extension version\n- category: financial\n  text: Billing, if you upgrade. Your plan, the subscription's status and renewal date, and the customer ID the\n    payment processor gives you\n- category: communication\n  text: 'Coauth sends three kinds of email through Resend: sign-in codes, team invites, and onboarding tips and\n    reminders.'\n- category: other\n  text: Passwords (with the notes and password history saved alongside them), passkey private keys, the text of\n    your notes and your authenticator (2FA) secrets are encrypted on your device before they are saved or synced.\npurposes:\n- purpose: Run password and passkey sync and autofill\n  text: 'Coauth is a zero-knowledge password and passkey manager: it saves, autofills,\
  \ and generates your website\n    logins'\n- purpose: Account creation and sign-in\n  text: to create your account and sync your vault\n- purpose: Team sharing\n  text: Team names, membership, roles, and an activity log of team actions, needed to make sharing work.\n- purpose: Billing\n  text: Dodo tells Coauth whether your subscription is active and when it renews, so Pro can be switched on for\n    your account.\n- purpose: Breach check\n  text: For each password, Coauth computes a SHA-1 hash on your device and sends only the first 5 characters of\n    that hash\n- purpose: Fixing onboarding drop-off\n  text: I use it only to fix drop-off in onboarding\nretention:\n- scope: Account and vault data\n  period: until you delete your account\n  text: Your account and vault data are kept until you delete your account.\n- scope: Team data\n  period: removed when the team is deleted\n  text: Team data is removed when the team is deleted.\n- scope: Audit-log entries\n  period: for the life of\
  \ the team\n  text: Audit-log entries are retained for the life of the team.\n- scope: Invites\n  period: 48 hours\n  text: An invite expires 48 hours after it is sent.\nresidency:\n- region: ap-south-1\n  text: Encrypted vault data, team data, and account records are stored with Supabase (Postgres), region ap-south-1.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email kalpesh@buildifyapp.in to request deletion of account and vault data\n  text: 'Delete your account and data: email me and I will delete your account records and vault data.'\nrights:\n- right: Unsubscribe from tips and reminders\n  text: Unsubscribe from tips and reminders with the link in any of those emails.\n- right: Remove passkeys\n  text: Remove a personal passkey, or unshare a team passkey, at any time from the popup.\nsale_or_sharing:\n  stance: prohibited\n  text: I do not sell or rent your data to anyone.\n"
source_yaml_url: https://artifacts.apis.io/buildifyapp-in/privacy/buildifyapp-in-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Buildify's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Production
- Regulated
- SoloEngineer
- Cloud
---
