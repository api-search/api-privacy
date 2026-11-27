---
api_specs:
- filename: tps-engage-play-api-openapi.yml
  format: yaml
  label: TPS Engage Play API
  slug: tps-engage-play-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tps-engage/openapi/tps-engage-play-api-openapi.yml
- filename: tps-engage-prefetch-api-openapi.yml
  format: yaml
  label: TPS Engage Prefetch API
  slug: tps-engage-prefetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tps-engage/openapi/tps-engage-prefetch-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, business name, job title, email, phone, country, postal/billing address
  - category: financial
    text: Billing details, transaction history, wallet/Credit balances, invoices, tax IDs (no full card numbers)
  - category: device
    text: IP address, device/browser type, OS, identifiers, referring/exit URLs, clickstream, logs, timestamps, error data
  - category: location
    text: Approximate location from IP; precise location only where you enable it
  - category: behavioral
    text: Aggregated/estimated audience and mobility data and attribution signals (generally not used to identify you)
  - category: communication
    text: Support tickets, emails, chat, call notes, surveys, feedback
  deletion:
    route: Email dpo@seeblindspot.com
    text: We keep personal data only as long as necessary for the purposes in this Policy, then delete or anonymize it.
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide, operate, and secure the Platform and website
    text: Provide, operate, and secure the Platform and website; authenticate users
  - purpose: Process payments and maintain financial records
    text: Process payments, funding, refunds, and chargebacks; maintain financial records
  - purpose: Deliver, verify, and report on campaigns
    text: Deliver, verify, and report on campaigns (including Proof of Play)
  - purpose: Improve products
    text: Improve and develop products, including aggregated analytics
  - purpose: Marketing
    text: Send marketing (where permitted) and personalize it
  residency:
  - region: United States, EU/EEA, United Kingdom
    text: We operate globally and may transfer personal data to countries other than your own, including the United States , the EU/EEA (including Romania), and the United Kingdom
  retention:
  - period: Duration of the account, then up to 12 months after closure
    scope: Account data
    text: Duration of the account, then up to 12 months after closure (subject to legal holds)
  - period: typically 7 years
    scope: Billing, tax, and transaction records
    text: As required by tax/accounting law, typically 7 years
  - period: At least 24 months after closure
    scope: Support and dispute records
    text: At least 24 months after closure, longer where a dispute or legal hold applies
  - period: Until you unsubscribe or object, then suppression-list retention only
    scope: Marketing data
    text: Until you unsubscribe or object, then suppression-list retention only
  rights:
  - right: Access
    text: Access a copy of your personal data;
  - right: Rectify
    text: Rectify inaccurate or incomplete data;
  - right: Erase
    text: Erase data in certain circumstances;
  - right: Object / restrict
    text: Restrict or object to certain processing (including direct marketing, which you can stop at any time);
  - right: Port
    text: Port data you provided to us, in a structured, machine-readable format, in certain cases;
  - right: Withdraw consent
    text: Withdraw consent where we rely on it;
  - right: Opt out of sale/sharing and targeted advertising
    text: Right to opt out of "sale" or "sharing" of personal information and of certain targeted advertising.
  role:
    text: 'We act as a controller for: our website and marketing; account registration and administration; billing and fraud/sanctions screening; our own analytics and service improvement; and our business contacts.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: A current list of our key subprocessors is maintained in our Data Processing Addendum and available on request at dpo@seeblindspot.com .
    url: null
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards, principally the European Commission's Standard Contractual Clauses (and the UK International Data Transfer Addendum for UK transfers)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TPS Engage
provenance_date: '2026-11-10'
provider_name: TPS Engage
provider_slug: tps-engage
slug: tps-engage-privacy-policy
source_date: '2026-11-10'
source_filename: tps-engage-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://seeblindspot.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TPS Engage\naid: tps-engage\nurl: https://seeblindspot.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We act as a controller for: our website and marketing; account registration and administration; billing\n    and fraud/sanctions screening; our own analytics and service improvement; and our business contacts.'\ndata_categories:\n- category: identifying\n  text: Name, business name, job title, email, phone, country, postal/billing address\n- category: financial\n  text: Billing details, transaction history, wallet/Credit balances, invoices, tax IDs (no full card numbers)\n-\
  \ category: device\n  text: IP address, device/browser type, OS, identifiers, referring/exit URLs, clickstream, logs, timestamps, error\n    data\n- category: location\n  text: Approximate location from IP; precise location only where you enable it\n- category: behavioral\n  text: Aggregated/estimated audience and mobility data and attribution signals (generally not used to identify\n    you)\n- category: communication\n  text: Support tickets, emails, chat, call notes, surveys, feedback\npurposes:\n- purpose: Provide, operate, and secure the Platform and website\n  text: Provide, operate, and secure the Platform and website; authenticate users\n- purpose: Process payments and maintain financial records\n  text: Process payments, funding, refunds, and chargebacks; maintain financial records\n- purpose: Deliver, verify, and report on campaigns\n  text: Deliver, verify, and report on campaigns (including Proof of Play)\n- purpose: Improve products\n  text: Improve and develop products, including\
  \ aggregated analytics\n- purpose: Marketing\n  text: Send marketing (where permitted) and personalize it\nretention:\n- scope: Account data\n  period: Duration of the account, then up to 12 months after closure\n  text: Duration of the account, then up to 12 months after closure (subject to legal holds)\n- scope: Billing, tax, and transaction records\n  period: typically 7 years\n  text: As required by tax/accounting law, typically 7 years\n- scope: Support and dispute records\n  period: At least 24 months after closure\n  text: At least 24 months after closure, longer where a dispute or legal hold applies\n- scope: Marketing data\n  period: Until you unsubscribe or object, then suppression-list retention only\n  text: Until you unsubscribe or object, then suppression-list retention only\nresidency:\n- region: United States, EU/EEA, United Kingdom\n  text: We operate globally and may transfer personal data to countries other than your own, including the United\n    States , the EU/EEA\
  \ (including Romania), and the United Kingdom\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards, principally the European Commission's Standard Contractual Clauses (and the\n    UK International Data Transfer Addendum for UK transfers)\nsubprocessors:\n  url: null\n  text: A current list of our key subprocessors is maintained in our Data Processing Addendum and available on request\n    at dpo@seeblindspot.com .\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: Email dpo@seeblindspot.com\n  text: We keep personal data only as long as necessary for the purposes in this Policy, then delete or anonymize\n    it.\nrights:\n- right: Access\n  text: Access a copy of your personal data;\n- right: Rectify\n  text: Rectify inaccurate or incomplete data;\n- right: Erase\n  text: Erase data in certain circumstances;\n- right: Object / restrict\n  text: Restrict or object to certain processing (including direct marketing, which you can\
  \ stop at any time);\n- right: Port\n  text: Port data you provided to us, in a structured, machine-readable format, in certain cases;\n- right: Withdraw consent\n  text: Withdraw consent where we rely on it;\n- right: Opt out of sale/sharing and targeted advertising\n  text: Right to opt out of \"sale\" or \"sharing\" of personal information and of certain targeted advertising.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/tps-engage/privacy/tps-engage-privacy-policy.yml
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
- sale_or_sharing
summary_line: 29 quoted statements, read from TPS Engage's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Digital Out Of Home
- Digital Billboards
- Programmatic Advertising
- Media Buying
- Out-of-Home
---
