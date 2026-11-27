---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: When you create your account, we collect your name, email address, password (stored as a cryptographic hash), preferred language and, where applicable, your company name.
  - category: financial
    text: We only retain a Stripe customer identifier, card type (e.g., Visa, Mastercard), the last four digits of the card, invoice history and subscription status.
  - category: behavioral
    text: we collect your text prompts, generated responses, tools executed by agents, tokens consumed and associated costs.
  - category: device
    text: IP address, browser type and version, pages viewed, date and time of access, referral URL and operating system.
  - category: other
    text: server resources consumed (CPU, memory, storage, bandwidth), domain names registered or configured, website configurations, hosted files, databases, backups and control panel activity logs.
  deletion:
    route: contact privacy officer
    text: Right to erasure — You may request the deletion of your personal information, subject to our legal retention obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service provision
    text: create and manage your account, provision and maintain your hosting services, process your support requests.
  - purpose: Billing
    text: process payments, issue invoices, manage subscriptions and usage-based billing for AI tokens.
  - purpose: Analytics
    text: understand the usage of our services in order to improve them, produce aggregated and anonymized statistics.
  - purpose: Artificial intelligence processing
    text: execute your requests to AI models, display results and track token consumption.
  - purpose: Communications
    text: send you account-related notices, service updates, security alerts and, with your consent, promotional communications.
  residency:
  - region: Canada
    text: Your hosting data (files, databases, backups, logs) is stored exclusively in Canada, in our data center located in Montreal, Quebec.
  - region: United States
    text: or in the United States when we use additional GPU capacity at RunPod.
  retention:
  - period: duration of the contractual relationship + 30 days after account deletion
    scope: Account data
    text: 'In active systems: duration of the contractual relationship + 30 days after account deletion'
  - period: 7 years
    scope: Billing data
    text: Billing data 7 years (in accordance with Canadian and Quebec tax obligations)
  - period: 90 days
    scope: Server logs
    text: Server logs 90 days
  - period: Not retained (processed in memory only)
    scope: Inference API requests (content)
    text: Inference API requests (content) Not retained (processed in memory only)
  rights:
  - right: Access
    text: Right of access — You may request a copy of the personal information we hold about you.
  - right: Rectification
    text: Right of rectification — You may request the correction of inaccurate or incomplete information.
  - right: Erasure
    text: Right to erasure — You may request the deletion of your personal information, subject to our legal retention obligations.
  - right: Portability
    text: Right to portability — You may request to receive your personal information in a structured and commonly used format.
  - right: Withdraw consent
    text: Right to withdraw consent — You may withdraw your consent at any time for processing based on consent, without affecting the lawfulness of prior processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal information.
  subprocessors:
    text: 'Here is the list of our sub-processors:'
    url: null
  transfers:
  - mechanism: other
    text: We have implemented appropriate contractual measures with each of our sub-processors, including confidentiality clauses, security obligations and restrictions on the use of transmitted data.
  - mechanism: other
    text: For China-based providers, explicit and separate consent is required before any data transmission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BorealHost.ai
provenance_date: '2026-11-09'
provider_name: BorealHost.ai
provider_slug: borealhost-ai
slug: borealhost-ai-privacy-policy
source_date: '2026-11-09'
source_filename: borealhost-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://borealhost.ai/en/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BorealHost.ai\naid: borealhost-ai\nurl: https://borealhost.ai/en/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you create your account, we collect your name, email address, password (stored as a cryptographic hash),\n    preferred language and, where applicable, your company name.\n- category: financial\n  text: We only retain a Stripe customer identifier, card type (e.g., Visa, Mastercard), the last four digits of\n    the card, invoice history and subscription status.\n- category: behavioral\n  text: we collect\
  \ your text prompts, generated responses, tools executed by agents, tokens consumed and associated\n    costs.\n- category: device\n  text: IP address, browser type and version, pages viewed, date and time of access, referral URL and operating\n    system.\n- category: other\n  text: server resources consumed (CPU, memory, storage, bandwidth), domain names registered or configured, website\n    configurations, hosted files, databases, backups and control panel activity logs.\npurposes:\n- purpose: Service provision\n  text: create and manage your account, provision and maintain your hosting services, process your support requests.\n- purpose: Billing\n  text: process payments, issue invoices, manage subscriptions and usage-based billing for AI tokens.\n- purpose: Analytics\n  text: understand the usage of our services in order to improve them, produce aggregated and anonymized statistics.\n- purpose: Artificial intelligence processing\n  text: execute your requests to AI models, display\
  \ results and track token consumption.\n- purpose: Communications\n  text: send you account-related notices, service updates, security alerts and, with your consent, promotional communications.\nretention:\n- scope: Account data\n  period: duration of the contractual relationship + 30 days after account deletion\n  text: 'In active systems: duration of the contractual relationship + 30 days after account deletion'\n- scope: Billing data\n  period: 7 years\n  text: Billing data 7 years (in accordance with Canadian and Quebec tax obligations)\n- scope: Server logs\n  period: 90 days\n  text: Server logs 90 days\n- scope: Inference API requests (content)\n  period: Not retained (processed in memory only)\n  text: Inference API requests (content) Not retained (processed in memory only)\nresidency:\n- region: Canada\n  text: Your hosting data (files, databases, backups, logs) is stored exclusively in Canada, in our data center\n    located in Montreal, Quebec.\n- region: United States\n  text:\
  \ or in the United States when we use additional GPU capacity at RunPod.\ntransfers:\n- mechanism: other\n  text: We have implemented appropriate contractual measures with each of our sub-processors, including confidentiality\n    clauses, security obligations and restrictions on the use of transmitted data.\n- mechanism: other\n  text: For China-based providers, explicit and separate consent is required before any data transmission\nsubprocessors:\n  url: null\n  text: 'Here is the list of our sub-processors:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacy officer\n  text: Right to erasure — You may request the deletion of your personal information, subject to our legal retention\n    obligations.\nrights:\n- right: Access\n  text: Right of access — You may request a copy of the personal information we hold about you.\n- right: Rectification\n  text: Right of rectification — You may request the correction of inaccurate or incomplete information.\n\
  - right: Erasure\n  text: Right to erasure — You may request the deletion of your personal information, subject to our legal retention\n    obligations.\n- right: Portability\n  text: Right to portability — You may request to receive your personal information in a structured and commonly\n    used format.\n- right: Withdraw consent\n  text: Right to withdraw consent — You may withdraw your consent at any time for processing based on consent, without\n    affecting the lawfulness of prior processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/borealhost-ai/privacy/borealhost-ai-privacy-policy.yml
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
summary_line: 26 quoted statements, read from BorealHost.ai's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- WordPress
- Quebec
- Cloud
---
