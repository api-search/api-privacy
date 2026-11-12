---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address Your display name and profile photo (as provided by the identity provider)
  - category: communication
    text: Email messages (subject, body, headers, attachments metadata)
  - category: device
    text: Device and browser information (user agent, screen size)
  - category: behavioral
    text: Usage analytics (pages visited, features used) via PostHog
  - category: financial
    text: Stripe receives your payment method details, billing address, and transaction information.
  deletion:
    route: Settings → account deletion; or contact privacy@conduitmail.app
    text: You may delete your account at any time in Settings. Deletion is immediate and irreversible
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: Access and display your email (via API or IMAP), sync labels and folders, apply rules, send email (via API or SMTP), and manage your inbox.'
  - purpose: AI features
    text: When you use AI features (summarization, drafting, search, rules), relevant email content is sent to Anthropic's Claude API for processing via our servers.
  - purpose: Product analytics
    text: We use PostHog to understand how the Service is used so we can improve it.
  - purpose: Error tracking
    text: We use Sentry to detect and fix bugs.
  residency:
  - region: United States
    text: Our subprocessors process data primarily in the United States.
  retention:
  - period: null
    scope: Account deletion
    text: all server-side data (account record, rules, settings, writing samples, files staged by connected applications and messages waiting to send, encrypted OAuth tokens, and encrypted IMAP/SMTP credentials) is permanently erased from our live systems when you confirm
  - period: up to 14 weeks
    scope: Encrypted backups
    text: Deleted data can remain in encrypted backups for up to 14 weeks, until those backups expire.
  - period: 6 years after you delete your account
    scope: Acceptance records
    text: We keep these records for 6 years after you delete your account, as proof of what you agreed to, and then erase them.
  - period: within 30 days
    scope: Anthropic AI processing data
    text: Anthropic deletes what we send it from its systems within 30 days, with the exceptions described in Section 7
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Erasure
    text: 'Erasure: Request deletion of your personal data.'
  - right: Data Portability
    text: 'Data Portability: Request a machine-readable export of your data.'
  - right: Rectification
    text: 'Rectification: Request correction of inaccurate personal data.'
  - right: Objection
    text: 'Objection: Object to processing of your personal data for certain purposes.'
  - right: Restriction
    text: 'Restriction: Request that we limit how we use your data.'
  role:
    text: Conduit Mail ("Conduit Mail," "we," "us," or "our") is operated by Conduit Labs LLC
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information. We do not share your personal information for cross-context behavioral advertising.
  subprocessors:
    text: 'We rely on the following third-party services (subprocessors) to provide the Service: Google (Gmail API, Firebase Authentication, Cloud Firestore, Cloud Run)'
    url: null
  transfers:
  - mechanism: other
    text: By using the Service, you consent to the transfer and processing of your data in the United States.
  - mechanism: other
    text: Data transferred from the EEA, United Kingdom, or Switzerland to the United States is transferred on the basis of the derogations in Article 49 GDPR
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Conduit Mail
provenance_date: '2026-11-09'
provider_name: Conduit Mail
provider_slug: conduitmail-app
slug: conduitmail-app-privacy-policy
source_date: '2026-11-09'
source_filename: conduitmail-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://conduitmail.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Conduit Mail\naid: conduitmail-app\nurl: https://conduitmail.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Conduit Mail (\"Conduit Mail,\" \"we,\" \"us,\" or \"our\") is operated by Conduit Labs LLC\ndata_categories:\n- category: identifying\n  text: Your email address Your display name and profile photo (as provided by the identity provider)\n- category: communication\n  text: Email messages (subject, body, headers, attachments metadata)\n- category: device\n  text: Device and browser information (user agent, screen size)\n- category: behavioral\n  text: Usage analytics (pages\
  \ visited, features used) via PostHog\n- category: financial\n  text: Stripe receives your payment method details, billing address, and transaction information.\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: Access and display your email (via API or IMAP), sync labels and folders, apply rules,\n    send email (via API or SMTP), and manage your inbox.'\n- purpose: AI features\n  text: When you use AI features (summarization, drafting, search, rules), relevant email content is sent to Anthropic's\n    Claude API for processing via our servers.\n- purpose: Product analytics\n  text: We use PostHog to understand how the Service is used so we can improve it.\n- purpose: Error tracking\n  text: We use Sentry to detect and fix bugs.\nretention:\n- scope: Account deletion\n  period: null\n  text: all server-side data (account record, rules, settings, writing samples, files staged by connected applications\n    and messages waiting to send, encrypted OAuth tokens, and\
  \ encrypted IMAP/SMTP credentials) is permanently erased\n    from our live systems when you confirm\n- scope: Encrypted backups\n  period: up to 14 weeks\n  text: Deleted data can remain in encrypted backups for up to 14 weeks, until those backups expire.\n- scope: Acceptance records\n  period: 6 years after you delete your account\n  text: We keep these records for 6 years after you delete your account, as proof of what you agreed to, and then\n    erase them.\n- scope: Anthropic AI processing data\n  period: within 30 days\n  text: Anthropic deletes what we send it from its systems within 30 days, with the exceptions described in Section\n    7\nresidency:\n- region: United States\n  text: Our subprocessors process data primarily in the United States.\ntransfers:\n- mechanism: other\n  text: By using the Service, you consent to the transfer and processing of your data in the United States.\n- mechanism: other\n  text: Data transferred from the EEA, United Kingdom, or Switzerland to\
  \ the United States is transferred on the\n    basis of the derogations in Article 49 GDPR\nsubprocessors:\n  url: null\n  text: 'We rely on the following third-party services (subprocessors) to provide the Service: Google (Gmail API,\n    Firebase Authentication, Cloud Firestore, Cloud Run)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → account deletion; or contact privacy@conduitmail.app\n  text: You may delete your account at any time in Settings. Deletion is immediate and irreversible\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you.'\n- right: Erasure\n  text: 'Erasure: Request deletion of your personal data.'\n- right: Data Portability\n  text: 'Data Portability: Request a machine-readable export of your data.'\n- right: Rectification\n  text: 'Rectification: Request correction of inaccurate personal data.'\n- right: Objection\n  text: 'Objection: Object to processing of your personal data for\
  \ certain purposes.'\n- right: Restriction\n  text: 'Restriction: Request that we limit how we use your data.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information. We do not share your personal information for cross-context behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/conduitmail-app/privacy/conduitmail-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Conduit Mail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Email Client
- Artificial Intelligence
- MCP
- AI Agents
- Productivity
- Automation
---
