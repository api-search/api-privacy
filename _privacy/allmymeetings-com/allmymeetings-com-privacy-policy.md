---
api_specs:
- filename: allmymeetings-com-openapi.yml
  format: yaml
  label: AllMyMeetings API
  slug: allmymeetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmymeetings-com/openapi/allmymeetings-com-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Request metadata (IP address, user agent, timestamp)
  - category: contact
    text: Email address
  - category: financial
    text: We store your Stripe customer ID and the last four digits and type of your payment method.
  - category: behavioral
    text: Pages visited and features used
  - category: device
    text: Browser type, operating system, and device information
  - category: other
    text: Event title, description, and location
  deletion:
    route: Email the contact address in Section 8
    text: To exercise any of these rights, contact us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: Provide the Service — synchronize calendars, process scheduling bookings, and manage your account.
  - purpose: Advertising
    text: Advertising — measure the effectiveness of our advertising campaigns through Google Ads conversion tracking and serve relevant ads to potential users through remarketing (see Section 5).
  - purpose: Improve the Service
    text: Improve the Service — analyze usage patterns, monitor performance, and develop new features.
  residency:
  - region: United States
    text: Wolfgang Solutions, LLC is based in the United States.
  - region: United States
    text: Laravel Cloud (Laravel Holdings Inc.), on Amazon Web Services (us-east-2, United States)
  retention:
  - period: Until you delete your account, plus 30 days for backup removal
    scope: Account information
    text: Until you delete your account, plus 30 days for backup removal
  - period: 30 days
    scope: Sync logs
    text: 30 days, deleted automatically each day.
  - period: 12 months after the booked event date, or until account deletion
    scope: Scheduling bookings
    text: 12 months after the booked event date, or until account deletion
  - period: typically 7 years
    scope: Payment records
    text: As required by tax and financial regulations (typically 7 years)
  rights:
  - right: Right of access
    text: Right of access — request a copy of the personal data we hold about you.
  - right: Right to rectification
    text: Right to rectification — request correction of inaccurate or incomplete data.
  - right: Right to data portability
    text: Right to data portability — receive your data in a structured, commonly used, machine-readable format.
  - right: Right to object
    text: Right to object — object to processing based on legitimate interests, including profiling.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: The EU-U.S. Data Privacy Framework (where applicable)
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission
  - mechanism: other
    text: Supplementary measures where required by applicable law
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AllMyMeetings
provenance_date: '2026-11-09'
provider_name: AllMyMeetings
provider_slug: allmymeetings-com
slug: allmymeetings-com-privacy-policy
source_date: '2026-11-09'
source_filename: allmymeetings-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://allmymeetings.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AllMyMeetings\naid: allmymeetings-com\nurl: https://allmymeetings.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Request metadata (IP address, user agent, timestamp)\n- category: contact\n  text: Email address\n- category: financial\n  text: We store your Stripe customer ID and the last four digits and type of your payment method.\n- category: behavioral\n  text: Pages visited and features used\n- category: device\n  text: Browser type, operating system, and device information\n- category: other\n  text: Event title, description,\
  \ and location\npurposes:\n- purpose: Provide the Service\n  text: Provide the Service — synchronize calendars, process scheduling bookings, and manage your account.\n- purpose: Advertising\n  text: Advertising — measure the effectiveness of our advertising campaigns through Google Ads conversion tracking\n    and serve relevant ads to potential users through remarketing (see Section 5).\n- purpose: Improve the Service\n  text: Improve the Service — analyze usage patterns, monitor performance, and develop new features.\nretention:\n- scope: Account information\n  period: Until you delete your account, plus 30 days for backup removal\n  text: Until you delete your account, plus 30 days for backup removal\n- scope: Sync logs\n  period: 30 days\n  text: 30 days, deleted automatically each day.\n- scope: Scheduling bookings\n  period: 12 months after the booked event date, or until account deletion\n  text: 12 months after the booked event date, or until account deletion\n- scope: Payment\
  \ records\n  period: typically 7 years\n  text: As required by tax and financial regulations (typically 7 years)\nresidency:\n- region: United States\n  text: Wolfgang Solutions, LLC is based in the United States.\n- region: United States\n  text: Laravel Cloud (Laravel Holdings Inc.), on Amazon Web Services (us-east-2, United States)\ntransfers:\n- mechanism: DPF\n  text: The EU-U.S. Data Privacy Framework (where applicable)\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission\n- mechanism: other\n  text: Supplementary measures where required by applicable law\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the contact address in Section 8\n  text: To exercise any of these rights, contact us at [email protected] .\nrights:\n- right: Right of access\n  text: Right of access — request a copy of the personal data we hold about you.\n- right: Right to rectification\n  text:\
  \ Right to rectification — request correction of inaccurate or incomplete data.\n- right: Right to data portability\n  text: Right to data portability — receive your data in a structured, commonly used, machine-readable format.\n- right: Right to object\n  text: Right to object — object to processing based on legitimate interests, including profiling.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/allmymeetings-com/privacy/allmymeetings-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from AllMyMeetings's own page on 2026-11-09.
synthetic: false
tags:
- Calendar
- Sync
- Artificial Intelligence
- Productivity
- Software-as-a-Service
---
