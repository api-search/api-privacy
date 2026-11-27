---
api_specs:
- filename: clearancesearchengine-com-openapi-generated.yml
  format: yaml
  label: CASE API
  slug: clearancesearchengine-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearancesearchengine-com/openapi/_ae-authored/clearancesearchengine-com-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email and sign-in identity, handled by Clerk.
  - category: contact
    text: Your email address and the message text.
  - category: behavioral
    text: Which pages you open and which features you use, a random visitor id, and your account id when you are signed in.
  - category: device
    text: tied to a random cookie id and to your account when signed in
  - category: other
    text: The SOR PDF you choose to upload (stored on AWS)
  - category: financial
    text: Card numbers never touch our servers; we keep only a payment reference and the amount.
  deletion:
    route: Delete option on results page or account, or automatic retention clock
    text: You can delete any upload immediately from your results page or your account .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Analyze uploaded document
    text: Reads the document text (the AI step)
  - purpose: Measure site use
    text: We measure how the site is used, and which ads bring people here
  - purpose: Ad measurement
    text: Measures which ads bring people to the site
  residency:
  - region: United States
    text: Uploaded documents are stored in a dedicated AWS S3 bucket in the United States (us-east-1)
  retention:
  - period: 14 days
    scope: Uploads not attached to a purchase
    text: Uploads not attached to a purchase are automatically deleted 14 days after upload.
  - period: 30 days
    scope: Uploads attached to a purchased report
    text: Uploads attached to a purchased report are kept 30 days , then deleted.
  - period: 30 days
    scope: OpenAI abuse-monitoring copies
    text: their short-term abuse-monitoring copies are deleted within 30 days
  rights:
  - right: Delete upload
    text: You can delete any upload immediately from your results page or your account .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No selling or renting of your data, ever.
  subprocessors:
    text: Providers CASE relies on, what each receives, and its published security documentation
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CASE
provenance_date: '2026-11-09'
provider_name: CASE
provider_slug: clearancesearchengine-com
slug: clearancesearchengine-com-privacy-policy
source_date: '2026-11-09'
source_filename: clearancesearchengine-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clearancesearchengine.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CASE\naid: clearancesearchengine-com\nurl: https://www.clearancesearchengine.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email and sign-in identity, handled by Clerk.\n- category: contact\n  text: Your email address and the message text.\n- category: behavioral\n  text: Which pages you open and which features you use, a random visitor id, and your account id when you are signed\n    in.\n- category: device\n  text: tied to a random cookie id and to your account when signed in\n- category: other\n  text: The SOR PDF\
  \ you choose to upload (stored on AWS)\n- category: financial\n  text: Card numbers never touch our servers; we keep only a payment reference and the amount.\npurposes:\n- purpose: Analyze uploaded document\n  text: Reads the document text (the AI step)\n- purpose: Measure site use\n  text: We measure how the site is used, and which ads bring people here\n- purpose: Ad measurement\n  text: Measures which ads bring people to the site\nretention:\n- scope: Uploads not attached to a purchase\n  period: 14 days\n  text: Uploads not attached to a purchase are automatically deleted 14 days after upload.\n- scope: Uploads attached to a purchased report\n  period: 30 days\n  text: Uploads attached to a purchased report are kept 30 days , then deleted.\n- scope: OpenAI abuse-monitoring copies\n  period: 30 days\n  text: their short-term abuse-monitoring copies are deleted within 30 days\nresidency:\n- region: United States\n  text: Uploaded documents are stored in a dedicated AWS S3 bucket in the\
  \ United States (us-east-1)\ntransfers: []\nsubprocessors:\n  url: null\n  text: Providers CASE relies on, what each receives, and its published security documentation\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete option on results page or account, or automatic retention clock\n  text: You can delete any upload immediately from your results page or your account .\nrights:\n- right: Delete upload\n  text: You can delete any upload immediately from your results page or your account .\nsale_or_sharing:\n  stance: prohibited\n  text: No selling or renting of your data, ever.\n"
source_yaml_url: https://artifacts.apis.io/clearancesearchengine-com/privacy/clearancesearchengine-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from CASE's own page on 2026-11-09.
synthetic: false
tags:
- Security Clearance
- Legal Research
- Knowledge Base
---
