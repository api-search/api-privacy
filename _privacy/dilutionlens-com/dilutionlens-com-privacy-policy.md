---
api_specs:
- filename: dilutionlens-com-company-api-openapi.yml
  format: yaml
  label: DilutionLens Company API
  slug: dilutionlens-com-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dilutionlens-com/openapi/dilutionlens-com-company-api-openapi.yml
- filename: dilutionlens-com-screen-api-openapi.yml
  format: yaml
  label: DilutionLens Screen API
  slug: dilutionlens-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dilutionlens-com/openapi/dilutionlens-com-screen-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: You give us an email address, we email a link that works once and expires after 60 minutes
  - category: identifying
    text: Held as the account itself, with the date you first signed in, the date you last signed in, how many times you have signed in
  - category: device
    text: the IP address it was requested from
  - category: behavioral
    text: We record which companies you unlocked, when, and which sections of the page you opened.
  - category: communication
    text: If you email corrections, a waitlist request, an alert request or a privacy enquiry, we hold that email
  - category: financial
    text: Stripe tells us only that a payment succeeded or failed.
  deletion:
    route: Email privacy@dilutionlens.com from the address you signed up with and ask us to delete it.
    text: Closing your account. Email privacy@dilutionlens.com from the address you signed up with and ask us to delete it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Keep user signed in
    text: It exists to keep you signed in — it is not an analytics or advertising cookie.
  - purpose: Count monthly unlock allowance
    text: That record is how the monthly allowance is counted and how we learn which parts of the product people actually come for.
  - purpose: Usage analytics
    text: We use an analytics service to count page views and a small set of named events
  - purpose: Subscription status
    text: This record is how the site knows to show you the paid tier
  residency:
  - region: United States and Europe
    text: Some of them store or process data outside Australia, mainly in the United States and Europe.
  - region: United States
    text: The analytics service receives your IP address and browser details as part of the request; it is based in the United States.
  retention:
  - period: null
    scope: Sign-in links
    text: These records are deleted once they have expired.
  - period: up to 90 days
    scope: Sign-in cookie
    text: One cookie, dl_session , set when you sign in and lasting up to 90 days.
  - period: null
    scope: Emails sent to us
    text: We keep emails sent to us for as long as we need them to deal with the matter and to show what we did about it.
  rights:
  - right: Access
    text: You can also ask for a copy of what we hold; the same address handles that.
  - right: Correction
    text: You can ask what personal information we hold about you and ask us to correct it.
  - right: Object / removal of directors' names
    text: If you are named and want something changed or removed , email privacy@dilutionlens.com with the company and the entry.
  - right: Complaint
    text: you can complain to the Office of the Australian Information Commissioner at oaic.gov.au.
  role:
    text: “We” is Assemblance Technologies LLC (Delaware, USA) , which operates DilutionLens.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, we do not run advertising, and we do not share analytics data with data brokers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DilutionLens
provenance_date: '2026-11-09'
provider_name: DilutionLens
provider_slug: dilutionlens-com
slug: dilutionlens-com-privacy-policy
source_date: '2026-11-09'
source_filename: dilutionlens-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dilutionlens.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DilutionLens\naid: dilutionlens-com\nurl: https://dilutionlens.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: “We” is Assemblance Technologies LLC (Delaware, USA) , which operates DilutionLens.\ndata_categories:\n- category: contact\n  text: You give us an email address, we email a link that works once and expires after 60 minutes\n- category: identifying\n  text: Held as the account itself, with the date you first signed in, the date you last signed in, how many times\n    you have signed in\n- category: device\n  text: the IP address it was requested from\n- category: behavioral\n\
  \  text: We record which companies you unlocked, when, and which sections of the page you opened.\n- category: communication\n  text: If you email corrections, a waitlist request, an alert request or a privacy enquiry, we hold that email\n- category: financial\n  text: Stripe tells us only that a payment succeeded or failed.\npurposes:\n- purpose: Keep user signed in\n  text: It exists to keep you signed in — it is not an analytics or advertising cookie.\n- purpose: Count monthly unlock allowance\n  text: That record is how the monthly allowance is counted and how we learn which parts of the product people actually\n    come for.\n- purpose: Usage analytics\n  text: We use an analytics service to count page views and a small set of named events\n- purpose: Subscription status\n  text: This record is how the site knows to show you the paid tier\nretention:\n- scope: Sign-in links\n  period: null\n  text: These records are deleted once they have expired.\n- scope: Sign-in cookie\n  period:\
  \ up to 90 days\n  text: One cookie, dl_session , set when you sign in and lasting up to 90 days.\n- scope: Emails sent to us\n  period: null\n  text: We keep emails sent to us for as long as we need them to deal with the matter and to show what we did about\n    it.\nresidency:\n- region: United States and Europe\n  text: Some of them store or process data outside Australia, mainly in the United States and Europe.\n- region: United States\n  text: The analytics service receives your IP address and browser details as part of the request; it is based in\n    the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@dilutionlens.com from the address you signed up with and ask us to delete it.\n  text: Closing your account. Email privacy@dilutionlens.com from the address you signed up with and ask us to delete\n    it.\nrights:\n- right: Access\n  text: You can also ask for a copy of\
  \ what we hold; the same address handles that.\n- right: Correction\n  text: You can ask what personal information we hold about you and ask us to correct it.\n- right: Object / removal of directors' names\n  text: If you are named and want something changed or removed , email privacy@dilutionlens.com with the company\n    and the entry.\n- right: Complaint\n  text: you can complain to the Office of the Australian Information Commissioner at oaic.gov.au.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, we do not run advertising, and we do not share analytics data with\n    data brokers.\n"
source_yaml_url: https://artifacts.apis.io/dilutionlens-com/privacy/dilutionlens-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from DilutionLens's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Capital Markets
- ASX
- Equity Dilution
- Market Data
- MCP
- Investing
---
