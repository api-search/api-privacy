---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Login email : used for magic-link sign-in, account recovery and service notices.'
  - category: contact
    text: Self-declared name, organization, role, and a verifiable link (LinkedIn / GitHub / homepage)
  - category: financial
    text: We keep a projection of subscription state (tier, period, status) and billing event receipts for entitlement computation and reconciliation.
  - category: location
    text: 'Anti-abuse metadata : IP reputation, submission frequency, honeypot signals.'
  - category: behavioral
    text: 'We count "encounter" signals on card pages: visits, intent views, conversations started, submissions, and conversations started but abandoned without submitting.'
  - category: device
    text: 'Passkey credentials : we store only the public key and credential metadata.'
  - category: communication
    text: Once your request is accepted, the messages you exchange with the receiver in the in-site conversation (stored encrypted, visible only to the two of you)
  deletion:
    route: Data & Revocation page account deletion, 7-day cooling-off then cryptographic erasure
    text: 'Deletion : start account deletion from the "Data & Revocation" page. The process: a 7-day cooling-off period , cancelable at any time; then cryptographic erasure'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the core service
    text: 'Providing the core service: account, card page, gateway filtering, Assistant Inbox, subscriptions'
  - purpose: Payment processing and tax
    text: Payment processing, invoicing and tax retention
  - purpose: Anti-abuse and security
    text: Anti-abuse, security, account protection
  - purpose: Service notices
    text: Service notices (release notice with conversation entry link, daily digest, security alerts)
  residency:
  - region: Hong Kong / global edge
    text: The operating entity is in Hong Kong, with the Hong Kong Personal Data (Privacy) Ordinance (PDPO) as our compliance baseline. The service runs on Cloudflare's global edge network, so your data may be processed outside your jurisdiction.
  retention:
  - period: Life of the account
    scope: Account and card page data
    text: Account and card page data Life of the account
  - period: Free tier 90 days; paid tiers 180 days
    scope: Requester submissions
    text: Requester submissions (incl. attachments, raw logs) Free tier 90 days; paid tiers 180 days (the receiver may shorten this)
  - period: No more than 30 days
    scope: Visitor conversation transcripts
    text: Visitor conversation transcripts No more than 30 days, hard-deleted (scheduled sweep; readable only by the anti-abuse audit process, never by the owner)
  - period: At least 7 years
    scope: Billing and invoice data
    text: Billing and invoice data Kept at least 7 years as required by law and not erased on account deletion (statutory tax obligation)
  rights:
  - right: Access and rectification
    text: 'Access and rectification : view and edit your profile, contracts and relationship records in-product at any time.'
  - right: Export
    text: 'Export : start a full export from the "Data & Revocation" page.'
  - right: Deletion
    text: 'Deletion : start account deletion from the "Data & Revocation" page.'
  - right: Consent withdrawal
    text: 'Consent withdrawal : agent authority (ConsentGrant) can be revoked instantly; any single relationship record can be deleted.'
  - right: Unsubscribe
    text: 'Unsubscribe : all notification emails carry RFC 8058 one-click unsubscribe'
  - right: Complaints to regulator
    text: You may also complain to the Hong Kong Privacy Commissioner for Personal Data (PCPD)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, run ads, or use third-party cross-site tracking.
  subprocessors:
    text: 'We use only the following third parties to process your data, each under data-processing terms: Processor Purpose Cloudflare Application hosting, storage, transactional email, AI triage inference Stripe Payments and subscription billing (card data handled by Stripe only) Independent object-storage provider Daily encrypted snapshot cold backup (ciphertext only)'
    url: null
  transfers:
  - mechanism: SCC
    text: For EU/UK users we honor the GDPR's extraterritorial provisions (Art. 3(2)), using Standard Contractual Clauses (SCCs) or equivalent safeguards for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: alink
provenance_date: '2026-11-09'
provider_name: alink
provider_slug: al-ink
slug: al-ink-privacy-policy
source_date: '2026-11-09'
source_filename: al-ink-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://al.ink/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: alink\naid: al-ink\nurl: https://al.ink/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Login email : used for magic-link sign-in, account recovery and service notices.'\n- category: contact\n  text: Self-declared name, organization, role, and a verifiable link (LinkedIn / GitHub / homepage)\n- category: financial\n  text: We keep a projection of subscription state (tier, period, status) and billing event receipts for entitlement\n    computation and reconciliation.\n- category: location\n  text: 'Anti-abuse metadata : IP reputation,\
  \ submission frequency, honeypot signals.'\n- category: behavioral\n  text: 'We count \"encounter\" signals on card pages: visits, intent views, conversations started, submissions, and\n    conversations started but abandoned without submitting.'\n- category: device\n  text: 'Passkey credentials : we store only the public key and credential metadata.'\n- category: communication\n  text: Once your request is accepted, the messages you exchange with the receiver in the in-site conversation (stored\n    encrypted, visible only to the two of you)\npurposes:\n- purpose: Providing the core service\n  text: 'Providing the core service: account, card page, gateway filtering, Assistant Inbox, subscriptions'\n- purpose: Payment processing and tax\n  text: Payment processing, invoicing and tax retention\n- purpose: Anti-abuse and security\n  text: Anti-abuse, security, account protection\n- purpose: Service notices\n  text: Service notices (release notice with conversation entry link, daily digest,\
  \ security alerts)\nretention:\n- scope: Account and card page data\n  period: Life of the account\n  text: Account and card page data Life of the account\n- scope: Requester submissions\n  period: Free tier 90 days; paid tiers 180 days\n  text: Requester submissions (incl. attachments, raw logs) Free tier 90 days; paid tiers 180 days (the receiver\n    may shorten this)\n- scope: Visitor conversation transcripts\n  period: No more than 30 days\n  text: Visitor conversation transcripts No more than 30 days, hard-deleted (scheduled sweep; readable only by the\n    anti-abuse audit process, never by the owner)\n- scope: Billing and invoice data\n  period: At least 7 years\n  text: Billing and invoice data Kept at least 7 years as required by law and not erased on account deletion (statutory\n    tax obligation)\nresidency:\n- region: Hong Kong / global edge\n  text: The operating entity is in Hong Kong, with the Hong Kong Personal Data (Privacy) Ordinance (PDPO) as our\n    compliance baseline.\
  \ The service runs on Cloudflare's global edge network, so your data may be processed outside\n    your jurisdiction.\ntransfers:\n- mechanism: SCC\n  text: For EU/UK users we honor the GDPR's extraterritorial provisions (Art. 3(2)), using Standard Contractual\n    Clauses (SCCs) or equivalent safeguards for cross-border transfers.\nsubprocessors:\n  url: null\n  text: 'We use only the following third parties to process your data, each under data-processing terms: Processor\n    Purpose Cloudflare Application hosting, storage, transactional email, AI triage inference Stripe Payments and\n    subscription billing (card data handled by Stripe only) Independent object-storage provider Daily encrypted\n    snapshot cold backup (ciphertext only)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data & Revocation page account deletion, 7-day cooling-off then cryptographic erasure\n  text: 'Deletion : start account deletion from the \"Data & Revocation\" page. The process:\
  \ a 7-day cooling-off period\n    , cancelable at any time; then cryptographic erasure'\nrights:\n- right: Access and rectification\n  text: 'Access and rectification : view and edit your profile, contracts and relationship records in-product at\n    any time.'\n- right: Export\n  text: 'Export : start a full export from the \"Data & Revocation\" page.'\n- right: Deletion\n  text: 'Deletion : start account deletion from the \"Data & Revocation\" page.'\n- right: Consent withdrawal\n  text: 'Consent withdrawal : agent authority (ConsentGrant) can be revoked instantly; any single relationship record\n    can be deleted.'\n- right: Unsubscribe\n  text: 'Unsubscribe : all notification emails carry RFC 8058 one-click unsubscribe'\n- right: Complaints to regulator\n  text: You may also complain to the Hong Kong Privacy Commissioner for Personal Data (PCPD)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, run ads, or use third-party cross-site tracking.\n"
source_yaml_url: https://artifacts.apis.io/al-ink/privacy/al-ink-privacy-policy.yml
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
summary_line: 26 quoted statements, read from alink's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Public-Page
- Link-Service
---
