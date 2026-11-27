---
api_specs:
- filename: openapi.json
  format: json
  label: BreakerDesk API
  slug: breakerdesk-api
  spec_type: OpenAPI
  url: https://breakerdesk.com/openapi.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: your name, your email address, your message
  - category: identifying
    text: your name, your email address, your message
  - category: financial
    text: Payment is taken by Stripe, who receive your card details directly; card numbers never reach BreakerDesk.
  deletion:
    route: email hello@breakerdesk.com
    text: 'ask for deletion at any time: hello@breakerdesk.com'
  dpa:
    available: true
    text: Where you store your own customers' details in BreakerDesk we act as your processor under UK GDPR Article 28 and as a service provider under the CCPA, on the written terms published on this site
    url: null
  purposes:
  - purpose: enquiry handling
    text: We collect what you type into an enquiry form
  - purpose: email updates
    text: We email you only about what that sentence names.
  retention:
  - period: 24 months
    scope: enquiry records
    text: Enquiry records are kept for 24 months from when they are sent, then deleted
  - period: 30 days
    scope: unconfirmed email sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: indefinitely
    scope: aggregate statistics
    text: Aggregate statistics that identify nobody are kept indefinitely.
  rights:
  - right: access
    text: You can ask what we hold about you, ask for a copy
  - right: deletion
    text: or ask for deletion at any time
  - right: complain to regulator
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your details and we do not pass them to contractors, lead buyers or advertising networks.
  subprocessors:
    text: we hold a current list of the sub-processors involved
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: breakerdesk-com
provenance_date: '2026-11-09'
provider_name: breakerdesk-com
provider_slug: breakerdesk-com
slug: breakerdesk-com-privacy-policy
source_date: '2026-11-09'
source_filename: breakerdesk-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://breakerdesk.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: breakerdesk-com\naid: breakerdesk-com\nurl: https://breakerdesk.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The controller of the personal data on this site is Ellul Solutions Ltd\ndata_categories:\n- category: contact\n  text: your name, your email address, your message\n- category: identifying\n  text: your name, your email address, your message\n- category: financial\n  text: Payment is taken by Stripe, who receive your card details directly; card numbers never reach BreakerDesk.\npurposes:\n- purpose: enquiry handling\n  text: We collect what you type into an enquiry form\n-\
  \ purpose: email updates\n  text: We email you only about what that sentence names.\nretention:\n- scope: enquiry records\n  period: 24 months\n  text: Enquiry records are kept for 24 months from when they are sent, then deleted\n- scope: unconfirmed email sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: aggregate statistics\n  period: indefinitely\n  text: Aggregate statistics that identify nobody are kept indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: we hold a current list of the sub-processors involved\ndpa:\n  available: true\n  url: null\n  text: Where you store your own customers' details in BreakerDesk we act as your processor under UK GDPR Article\n    28 and as a service provider under the CCPA, on the written terms published on this site\ndeletion:\n  route: email hello@breakerdesk.com\n  text: 'ask for deletion at any time: hello@breakerdesk.com'\nrights:\n- right: access\n  text: You can ask\
  \ what we hold about you, ask for a copy\n- right: deletion\n  text: or ask for deletion at any time\n- right: complain to regulator\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your details and we do not pass them to contractors, lead buyers or advertising networks.\n"
source_yaml_url: https://artifacts.apis.io/breakerdesk-com/privacy/breakerdesk-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from breakerdesk-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electrician
- Software
- Tools
- Contractor
---
