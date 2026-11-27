---
api_specs:
- filename: anon-li-openapi-generated.yml
  format: yaml
  label: anon.li API
  slug: anon-li-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anon-li/openapi/_ae-authored/anon-li-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Email Address : Required for authentication, sending system notifications (e.g., verification, password reset, and magic links), and as the destination for forwarded emails.'
  - category: financial
    text: We do not store full credit card numbers on our servers.
  - category: identifying
    text: If you sign in with Google or GitHub, we receive your email address and basic profile (name and avatar) from that provider.
  - category: device
    text: 'Session Metadata : Active login sessions include device metadata such as user agent so you can review and manage signed-in devices from your dashboard.'
  - category: behavioral
    text: 'Analytics & product monitoring : We use PostHog (EU region) to understand aggregate usage and improve the product.'
  - category: communication
    text: 'Metadata Logging : We temporarily log minimal metadata (sender address, recipient alias, timestamp) for a maximum of 7 days .'
  deletion:
    route: Delete account in account settings or dashboard
    text: When you delete your account, your personal aliases, recipients, domains, Drops, Forms and their submissions, files, API keys, sessions, credentials, vault materials, and the account record are removed from live systems immediately
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service : Create aliases, forward emails, facilitate encrypted file sharing and form collection, run teams, and manage your account.'
  - purpose: Process payments
    text: 'Process Payments : Handle subscriptions and billing through Stripe and, for cryptocurrency payments, NOWPayments.'
  - purpose: Ensure security
    text: 'Ensure Security : Monitor for abuse, prevent spam, enforce rate limits, and protect our infrastructure.'
  residency:
  - region: United States and European Union
    text: Your information may be processed in countries other than your own, primarily the United States and the European Union.
  retention:
  - period: 7 days
    scope: Metadata logs
    text: 'Metadata Logs : Automatically deleted after 7 days.'
  - period: 30 days on Free, 90 days on Plus, 365 days on Pro and Business
    scope: Form submissions
    text: 'Form Submissions : Deleted automatically once they are older than your plan''s retention window (30 days on Free, 90 days on Plus, 365 days on Pro and Business)'
  - period: up to 30 days
    scope: Backups
    text: 'Backups : Rolling backups are retained for up to 30 days for disaster recovery purposes.'
  rights:
  - right: Access
    text: 'Access : Request a copy of your personal data.'
  - right: Portability
    text: 'Portability : Export your data in a machine-readable format.'
  - right: Correction
    text: 'Correction : Update inaccurate information via your dashboard.'
  - right: Deletion
    text: 'Deletion : Delete your account and all associated data at any time.'
  - right: Restriction
    text: 'Restriction : Request limitation of processing in certain circumstances.'
  - right: Objection
    text: 'Objection : Object to processing based on legitimate interests.'
  - right: Withdrawal
    text: 'Withdrawal : Withdraw consent at any time where processing is based on consent.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not use your information for advertising, sell it, or share it with third parties for their own purposes.
  subprocessors:
    text: The same list is maintained at anon.li/sub-processors .
    url: anon.li/sub-processors
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission
  - mechanism: adequacy
    text: Adequacy decisions where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: anon.li
provenance_date: '2026-11-09'
provider_name: anon.li
provider_slug: anon-li
slug: anon-li-privacy-policy
source_date: '2026-11-09'
source_filename: anon-li-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anon.li/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: anon.li\naid: anon-li\nurl: https://anon.li/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Email Address : Required for authentication, sending system notifications (e.g., verification, password\n    reset, and magic links), and as the destination for forwarded emails.'\n- category: financial\n  text: We do not store full credit card numbers on our servers.\n- category: identifying\n  text: If you sign in with Google or GitHub, we receive your email address and basic profile (name and avatar)\n    from that provider.\n- category:\
  \ device\n  text: 'Session Metadata : Active login sessions include device metadata such as user agent so you can review and\n    manage signed-in devices from your dashboard.'\n- category: behavioral\n  text: 'Analytics & product monitoring : We use PostHog (EU region) to understand aggregate usage and improve the\n    product.'\n- category: communication\n  text: 'Metadata Logging : We temporarily log minimal metadata (sender address, recipient alias, timestamp) for\n    a maximum of 7 days .'\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service : Create aliases, forward emails, facilitate encrypted file sharing and form collection,\n    run teams, and manage your account.'\n- purpose: Process payments\n  text: 'Process Payments : Handle subscriptions and billing through Stripe and, for cryptocurrency payments, NOWPayments.'\n- purpose: Ensure security\n  text: 'Ensure Security : Monitor for abuse, prevent spam, enforce rate limits, and protect our infrastructure.'\n\
  retention:\n- scope: Metadata logs\n  period: 7 days\n  text: 'Metadata Logs : Automatically deleted after 7 days.'\n- scope: Form submissions\n  period: 30 days on Free, 90 days on Plus, 365 days on Pro and Business\n  text: 'Form Submissions : Deleted automatically once they are older than your plan''s retention window (30 days\n    on Free, 90 days on Plus, 365 days on Pro and Business)'\n- scope: Backups\n  period: up to 30 days\n  text: 'Backups : Rolling backups are retained for up to 30 days for disaster recovery purposes.'\nresidency:\n- region: United States and European Union\n  text: Your information may be processed in countries other than your own, primarily the United States and the\n    European Union.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission\n- mechanism: adequacy\n  text: Adequacy decisions where applicable\nsubprocessors:\n  url: anon.li/sub-processors\n  text: The same list is maintained at anon.li/sub-processors\
  \ .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in account settings or dashboard\n  text: When you delete your account, your personal aliases, recipients, domains, Drops, Forms and their submissions,\n    files, API keys, sessions, credentials, vault materials, and the account record are removed from live systems\n    immediately\nrights:\n- right: Access\n  text: 'Access : Request a copy of your personal data.'\n- right: Portability\n  text: 'Portability : Export your data in a machine-readable format.'\n- right: Correction\n  text: 'Correction : Update inaccurate information via your dashboard.'\n- right: Deletion\n  text: 'Deletion : Delete your account and all associated data at any time.'\n- right: Restriction\n  text: 'Restriction : Request limitation of processing in certain circumstances.'\n- right: Objection\n  text: 'Objection : Object to processing based on legitimate interests.'\n- right: Withdrawal\n  text: 'Withdrawal : Withdraw\
  \ consent at any time where processing is based on consent.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use your information for advertising, sell it, or share it with third parties for their own purposes.\n"
source_yaml_url: https://artifacts.apis.io/anon-li/privacy/anon-li-privacy-policy.yml
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
summary_line: 25 quoted statements, read from anon.li's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Email
- Encryption
- File Sharing
- Forms
---
