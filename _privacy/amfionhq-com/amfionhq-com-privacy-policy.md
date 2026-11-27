---
api_specs:
- filename: amfionhq-com-fleet-api-openapi.yml
  format: yaml
  label: amfionhq-com Fleet API
  slug: amfionhq-com-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-fleet-api-openapi.yml
- filename: amfionhq-com-tenants-api-openapi.yml
  format: yaml
  label: amfionhq-com Tenants API
  slug: amfionhq-com-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-tenants-api-openapi.yml
- filename: amfionhq-com-tools-api-openapi.yml
  format: yaml
  label: amfionhq-com Tools API
  slug: amfionhq-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-tools-api-openapi.yml
- filename: amfionhq-com-usage-api-openapi.yml
  format: yaml
  label: amfionhq-com Usage API
  slug: amfionhq-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amfionhq-com/openapi/amfionhq-com-usage-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact information: Name, email address, and phone number — the details you give the assistant, and the number you call or text from'
  - category: communication
    text: 'Conversation data: Messages you exchange with the assistant, including booking requests, questions, and responses, and any replies from the business’s staff'
  - category: financial
    text: card details go to Stripe and never to Amfion
  - category: device
    text: 'Technical data: Browser type, session identifiers, and a keyed one-way hash of your IP address.'
  - category: behavioral
    text: measures page views, the steps of signing up, and how quickly our pages load
  - category: location
    text: the two-letter country code our edge network reports for your connection
  deletion:
    route: Tenant admin dashboard or email request
    text: A Tenant’s admin can delete its account data from the dashboard (the account stops at once and is deleted after a 7-day period in which the deletion can be cancelled), or ask us by email, and we act within 30 days of a verified request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Booking and assistant service
    text: Process your messages and calls through our AI assistant to help you book appointments, answer your questions, and pass your requests and messages to the business
  - purpose: Security and fraud prevention
    text: Protect against fraud, abuse, and unauthorized access
  - purpose: Website measurement
    text: We use it for measurement only — Google Signals and ads personalization are switched off in our code.
  residency:
  - region: Germany
    text: Our Supabase database and file storage are located in Germany.
  - region: United States
    text: Amfion is based in the United States, and the platform runs in more than one country
  retention:
  - period: 30, 90, 180 or 365 days
    scope: Conversation history
    text: until the business deletes it or its account data, or, if the business chooses, for 30, 90, 180 or 365 days after a conversation’s last message
  - period: 7 days
    scope: Website previews
    text: 7 days after it was last used and no later than 30 days after it was created
  - period: 90 days
    scope: Setup requests from website
    text: The website or listing, email address, callback number and IP hash are deleted 90 days after the request, or sooner if you ask us.
  - period: up to 12 weeks
    scope: Encrypted backups
    text: Encrypted database backups are kept for up to 12 weeks
  - period: 30 days
    scope: Appointment portal tokens
    text: These tokens expire after 30 days.
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your personal data
  - right: Data portability
    text: Request your data in a structured, machine-readable format
  - right: Withdraw consent
    text: Where processing is based on consent, you may withdraw it at any time
  - right: Non-discrimination (CCPA)
    text: We will not discriminate against you for exercising your privacy rights
  role:
    text: 'As a Data Controller: We act as a Data Controller for information we collect directly'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data. We never have, and we never will.
  subprocessors:
    text: The Subprocessors page lists the providers named here, with what each one receives and where it processes it.
    url: null
  transfers:
  - mechanism: DPF
    text: For these transfers Google relies on the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: amfionhq-com
provenance_date: '2026-11-09'
provider_name: amfionhq-com
provider_slug: amfionhq-com
slug: amfionhq-com-privacy-policy
source_date: '2026-11-09'
source_filename: amfionhq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amfionhq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: amfionhq-com\naid: amfionhq-com\nurl: https://amfionhq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'As a Data Controller: We act as a Data Controller for information we collect directly'\ndata_categories:\n- category: contact\n  text: 'Contact information: Name, email address, and phone number — the details you give the assistant, and the\n    number you call or text from'\n- category: communication\n  text: 'Conversation data: Messages you exchange with the assistant, including booking requests, questions, and\n    responses, and any replies from the business’s staff'\n- category:\
  \ financial\n  text: card details go to Stripe and never to Amfion\n- category: device\n  text: 'Technical data: Browser type, session identifiers, and a keyed one-way hash of your IP address.'\n- category: behavioral\n  text: measures page views, the steps of signing up, and how quickly our pages load\n- category: location\n  text: the two-letter country code our edge network reports for your connection\npurposes:\n- purpose: Booking and assistant service\n  text: Process your messages and calls through our AI assistant to help you book appointments, answer your questions,\n    and pass your requests and messages to the business\n- purpose: Security and fraud prevention\n  text: Protect against fraud, abuse, and unauthorized access\n- purpose: Website measurement\n  text: We use it for measurement only — Google Signals and ads personalization are switched off in our code.\nretention:\n- scope: Conversation history\n  period: 30, 90, 180 or 365 days\n  text: until the business deletes\
  \ it or its account data, or, if the business chooses, for 30, 90, 180 or 365 days\n    after a conversation’s last message\n- scope: Website previews\n  period: 7 days\n  text: 7 days after it was last used and no later than 30 days after it was created\n- scope: Setup requests from website\n  period: 90 days\n  text: The website or listing, email address, callback number and IP hash are deleted 90 days after the request,\n    or sooner if you ask us.\n- scope: Encrypted backups\n  period: up to 12 weeks\n  text: Encrypted database backups are kept for up to 12 weeks\n- scope: Appointment portal tokens\n  period: 30 days\n  text: These tokens expire after 30 days.\nresidency:\n- region: Germany\n  text: Our Supabase database and file storage are located in Germany.\n- region: United States\n  text: Amfion is based in the United States, and the platform runs in more than one country\ntransfers:\n- mechanism: DPF\n  text: For these transfers Google relies on the EU-U.S. Data Privacy Framework\n\
  subprocessors:\n  url: null\n  text: The Subprocessors page lists the providers named here, with what each one receives and where it processes\n    it.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Tenant admin dashboard or email request\n  text: A Tenant’s admin can delete its account data from the dashboard (the account stops at once and is deleted\n    after a 7-day period in which the deletion can be cancelled), or ask us by email, and we act within 30 days\n    of a verified request.\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your personal data\n- right: Data portability\n  text: Request your data in a structured, machine-readable format\n- right: Withdraw consent\n  text: Where processing is based on consent, you may withdraw it at any time\n- right: Non-discrimination (CCPA)\n  text: We will not\
  \ discriminate against you for exercising your privacy rights\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data. We never have, and we never will.\n"
source_yaml_url: https://artifacts.apis.io/amfionhq-com/privacy/amfionhq-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from amfionhq-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Front Desk
- Booking
- Automation
---
