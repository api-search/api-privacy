---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your full name: it is the sender name on every letter.'
  - category: contact
    text: Your e-mail address, if you sign in with one.
  - category: financial
    text: We receive the payment’s ID and status, never your card number.
  - category: location
    text: Your sender addresses (without the name), your preferences (language, e-mails about your letters)
  - category: device
    text: We read the browser and system from your browser’s request at that moment and do not store them.
  - category: communication
    text: Our logs never contain letter text, sign-in codes, e-mail addresses or postal addresses.
  deletion:
    route: Delete your account
    text: When you delete your account, we delete your account data, sessions, addresses and connected apps at once
  dpa:
    available: true
    text: 'These companies process data for us, under data processing agreements:'
    url: null
  purposes:
  - purpose: mail letters
    text: We need it to show you the preview and to mail the letter (Art. 6(1)(b)).
  - purpose: prevent duplicates and abuse
    text: the hashes to prevent duplicates and abuse (Art. 6(1)(f), our legitimate interest in a postal service that cannot be used for harassment)
  - purpose: find and fix errors
    text: 'Purpose: find and fix errors fast (Art. 6(1)(f)).'
  residency:
  - region: EU
    text: Our database, with your account and your letters, is stored in the EU.
  - region: USA
    text: Cloudflare’s network and its other services also process data in the USA
  retention:
  - period: Until the letter reaches a final state.
    scope: Letter text, addresses and enclosures
    text: Until the letter reaches a final state.
  - period: Until you delete your account
    scope: Account data
    text: Until you delete your account
  - period: At most 7 days
    scope: Logs at Cloudflare
    text: At most 7 days
  - period: 30 days
    scope: Error reports at Sentry
    text: Error reports at Sentry 30 days
  - period: 3 years
    scope: Support e-mails in our mailbox
    text: We keep support e-mails for 3 years after the last message of the conversation; then we delete them.
  rights:
  - right: access, correction, deletion
    text: You have the right to access your data, to have it corrected or delete
  - right: object
    text: Stop all cards (your right to object).
  role:
    text: 'The controller under the GDPR is:'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'These companies process data for us, under data processing agreements:'
    url: null
  transfers:
  - mechanism: SCC
    text: For this transfer we rely on the EU standard contractual clauses in PostGrid’s data processing addendum.
  - mechanism: DPF
    text: For other transfers to the USA we rely on the EU–U.S. Data Privacy Framework where the recipient is certified under it
  - mechanism: adequacy
    text: the European Commission decided that Switzerland protects personal data adequately
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Letter Desk
provenance_date: '2026-11-09'
provider_name: Agent Letter Desk
provider_slug: agentletterdesk-com
slug: agentletterdesk-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentletterdesk-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentletterdesk.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Letter Desk\naid: agentletterdesk-com\nurl: https://agentletterdesk.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'The controller under the GDPR is:'\ndata_categories:\n- category: identifying\n  text: 'Your full name: it is the sender name on every letter.'\n- category: contact\n  text: Your e-mail address, if you sign in with one.\n- category: financial\n  text: We receive the payment’s ID and status, never your card number.\n- category: location\n  text: Your sender addresses (without the name), your preferences (language, e-mails about your letters)\n\
  - category: device\n  text: We read the browser and system from your browser’s request at that moment and do not store them.\n- category: communication\n  text: Our logs never contain letter text, sign-in codes, e-mail addresses or postal addresses.\npurposes:\n- purpose: mail letters\n  text: We need it to show you the preview and to mail the letter (Art. 6(1)(b)).\n- purpose: prevent duplicates and abuse\n  text: the hashes to prevent duplicates and abuse (Art. 6(1)(f), our legitimate interest in a postal service that\n    cannot be used for harassment)\n- purpose: find and fix errors\n  text: 'Purpose: find and fix errors fast (Art. 6(1)(f)).'\nretention:\n- scope: Letter text, addresses and enclosures\n  period: Until the letter reaches a final state.\n  text: Until the letter reaches a final state.\n- scope: Account data\n  period: Until you delete your account\n  text: Until you delete your account\n- scope: Logs at Cloudflare\n  period: At most 7 days\n  text: At most 7 days\n-\
  \ scope: Error reports at Sentry\n  period: 30 days\n  text: Error reports at Sentry 30 days\n- scope: Support e-mails in our mailbox\n  period: 3 years\n  text: We keep support e-mails for 3 years after the last message of the conversation; then we delete them.\nresidency:\n- region: EU\n  text: Our database, with your account and your letters, is stored in the EU.\n- region: USA\n  text: Cloudflare’s network and its other services also process data in the USA\ntransfers:\n- mechanism: SCC\n  text: For this transfer we rely on the EU standard contractual clauses in PostGrid’s data processing addendum.\n- mechanism: DPF\n  text: For other transfers to the USA we rely on the EU–U.S. Data Privacy Framework where the recipient is certified\n    under it\n- mechanism: adequacy\n  text: the European Commission decided that Switzerland protects personal data adequately\nsubprocessors:\n  url: null\n  text: 'These companies process data for us, under data processing agreements:'\ndpa:\n  available:\
  \ true\n  url: null\n  text: 'These companies process data for us, under data processing agreements:'\ndeletion:\n  route: Delete your account\n  text: When you delete your account, we delete your account data, sessions, addresses and connected apps at once\nrights:\n- right: access, correction, deletion\n  text: You have the right to access your data, to have it corrected or delete\n- right: object\n  text: Stop all cards (your right to object).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentletterdesk-com/privacy/agentletterdesk-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Agent Letter Desk's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Mail
- Certified Mail
- LetterService
- Automation
- Company
---
