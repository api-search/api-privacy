---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address you provide at signup.
  - category: identifying
    text: OAuth identifiers and tokens when you sign in with Google or GitHub.
  - category: contact
    text: Collaborator invites (the email addresses you invite).
  - category: device
    text: Rate-limit counters keyed on a short-lived IP-derived identifier (held in memory, not persisted long-term).
  - category: communication
    text: Saved AI-agent conversations and the messages exchanged with the writing assistant.
  - category: financial
    text: Token-usage rollups used to debug failures, prevent abuse, and bill credits.
  deletion:
    route: 'Account page: delete your account from your account page; hard-delete within 30 days.'
    text: We hard-delete account, books, chapters, agent conversations, audit records, and operational telemetry within 30 days and instruct sub-processors to do the same.
  dpa:
    available: true
    text: We use carefully selected service providers (“sub-processors”) under Article 28 GDPR data-processing agreements.
    url: null
  purposes:
  - purpose: Account creation and contract performance
    text: 'Legal basis: performance of the contract you enter into by creating an account (Art. 6(1)(b) GDPR).'
  - purpose: Operating a secure, reliable service
    text: 'Legal basis: our legitimate interest in operating a secure, reliable service (Art. 6(1)(f) GDPR).'
  - purpose: Counting unique readers and identifying drop-off points
    text: We use this only to count unique readers and identify drop-off points.
  - purpose: Strictly necessary cookies
    text: We use cookies that are strictly necessary to keep you signed in and to protect the Service from CSRF attacks.
  - purpose: Print-on-demand orders
    text: Lulu Press, Inc. (USA) — print-on-demand orders, including your name and shipping address when you order a printed copy.
  residency:
  - region: United States
    text: Most of our sub-processors are based in the United States.
  retention:
  - period: 30 days
    scope: Account data
    text: 'Account data: while your account is active, plus up to 30 days after deletion to allow reversal of a destructive request.'
  - period: null
    scope: Books and chapters
    text: 'Books and chapters: until you delete them, with a 30-day soft-delete window before permanent removal.'
  - period: 90 days
    scope: Operational telemetry
    text: 'Operational telemetry: 90 days, then permanently deleted by a daily cron job.'
  - period: 90 days
    scope: Reader analytics
    text: 'Reader analytics: 90 days for individual events, aggregated indefinitely.'
  - period: 30 days
    scope: Backups
    text: 'Backups: rolling encrypted backups for up to 30 days.'
  rights:
  - right: Access
    text: Access the personal data we hold about you — available from your account page as a JSON export.
  - right: Rectification
    text: Rectify inaccurate data — change your name, email, and content directly from your account.
  - right: Erasure
    text: Erase your data — delete your account from your account page.
  - right: Restriction or objection
    text: Restrict or object to processing based on legitimate interest — email will.schulz@aw3.tech and we will action the request within 30 days.
  - right: Withdraw consent
    text: Withdraw consent at any time without affecting the lawfulness of processing before withdrawal.
  - right: Portability
    text: Data portability — the JSON export above is in a structured, commonly used, machine-readable format.
  - right: Complaint
    text: Lodge a complaint with your local supervisory authority.
  role:
    text: Anthra is the data controller for personal data processed through the Service.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A current, dated sub-processor list is maintained in our public repository and is available on request.
    url: null
  transfers:
  - mechanism: SCC
    text: Where personal data is transferred outside the EEA / UK we rely on the Standard Contractual Clauses (SCCs) approved by the European Commission
  - mechanism: DPF
    text: and, where applicable, the EU–US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anthra
provenance_date: '2026-11-09'
provider_name: Anthra
provider_slug: anthra-com
slug: anthra-com-privacy-policy
source_date: '2026-11-09'
source_filename: anthra-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anthra.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anthra\naid: anthra-com\nurl: https://anthra.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Anthra is the data controller for personal data processed through the Service.\ndata_categories:\n- category: identifying\n  text: Name and email address you provide at signup.\n- category: identifying\n  text: OAuth identifiers and tokens when you sign in with Google or GitHub.\n- category: contact\n  text: Collaborator invites (the email addresses you invite).\n- category: device\n  text: Rate-limit counters keyed on a short-lived IP-derived identifier (held in memory, not persisted long-term).\n\
  - category: communication\n  text: Saved AI-agent conversations and the messages exchanged with the writing assistant.\n- category: financial\n  text: Token-usage rollups used to debug failures, prevent abuse, and bill credits.\npurposes:\n- purpose: Account creation and contract performance\n  text: 'Legal basis: performance of the contract you enter into by creating an account (Art. 6(1)(b) GDPR).'\n- purpose: Operating a secure, reliable service\n  text: 'Legal basis: our legitimate interest in operating a secure, reliable service (Art. 6(1)(f) GDPR).'\n- purpose: Counting unique readers and identifying drop-off points\n  text: We use this only to count unique readers and identify drop-off points.\n- purpose: Strictly necessary cookies\n  text: We use cookies that are strictly necessary to keep you signed in and to protect the Service from CSRF attacks.\n- purpose: Print-on-demand orders\n  text: Lulu Press, Inc. (USA) — print-on-demand orders, including your name and shipping address\
  \ when you order\n    a printed copy.\nretention:\n- scope: Account data\n  period: 30 days\n  text: 'Account data: while your account is active, plus up to 30 days after deletion to allow reversal of a destructive\n    request.'\n- scope: Books and chapters\n  period: null\n  text: 'Books and chapters: until you delete them, with a 30-day soft-delete window before permanent removal.'\n- scope: Operational telemetry\n  period: 90 days\n  text: 'Operational telemetry: 90 days, then permanently deleted by a daily cron job.'\n- scope: Reader analytics\n  period: 90 days\n  text: 'Reader analytics: 90 days for individual events, aggregated indefinitely.'\n- scope: Backups\n  period: 30 days\n  text: 'Backups: rolling encrypted backups for up to 30 days.'\nresidency:\n- region: United States\n  text: Most of our sub-processors are based in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where personal data is transferred outside the EEA / UK we rely on the Standard Contractual Clauses\
  \ (SCCs)\n    approved by the European Commission\n- mechanism: DPF\n  text: and, where applicable, the EU–US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: A current, dated sub-processor list is maintained in our public repository and is available on request.\ndpa:\n  available: true\n  url: null\n  text: We use carefully selected service providers (“sub-processors”) under Article 28 GDPR data-processing agreements.\ndeletion:\n  route: 'Account page: delete your account from your account page; hard-delete within 30 days.'\n  text: We hard-delete account, books, chapters, agent conversations, audit records, and operational telemetry within\n    30 days and instruct sub-processors to do the same.\nrights:\n- right: Access\n  text: Access the personal data we hold about you — available from your account page as a JSON export.\n- right: Rectification\n  text: Rectify inaccurate data — change your name, email, and content directly from your account.\n- right: Erasure\n  text:\
  \ Erase your data — delete your account from your account page.\n- right: Restriction or objection\n  text: Restrict or object to processing based on legitimate interest — email will.schulz@aw3.tech and we will action\n    the request within 30 days.\n- right: Withdraw consent\n  text: Withdraw consent at any time without affecting the lawfulness of processing before withdrawal.\n- right: Portability\n  text: Data portability — the JSON export above is in a structured, commonly used, machine-readable format.\n- right: Complaint\n  text: Lodge a complaint with your local supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anthra-com/privacy/anthra-com-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Anthra's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- BookCreation
- Writing
- Illustration
- Audiobook
---
