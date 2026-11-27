---
api_specs:
- filename: eliza-openapi.yaml
  format: yaml
  label: Eliza AI Framework API
  slug: eliza-ai-framework-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/symbaiex-com/openapi/eliza-openapi.yaml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account setup uses a public handle, password or Google sign-in, and an optional contact email.
  - category: contact
    text: WorkOS receives your account ID and contact email to complete sign-in and manage application consent and tokens.
  - category: communication
    text: These records can include private message bodies, profile fields, or moderation content.
  - category: device
    text: Agent identity records include a stable identifier, owner, granted scopes, status, and security audit records.
  deletion:
    route: email austin@symbaiex.com
    text: To request access, correction, account closure, or deletion of data that can legally and operationally be removed, email austin@symbaiex.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond, deliver, honor preferences, investigate abuse
    text: Contact messages and newsletter details are stored long enough to respond, deliver, honor preferences, investigate abuse, and maintain required delivery records.
  - purpose: enforce access and support disconnection
    text: to enforce access and support disconnection
  retention:
  - period: 24 hours
    scope: review proposals approval eligibility
    text: Review proposals remain eligible for owner approval for 24 hours; expiry does not delete the stored proposal or command record.
  - period: after completion, expiry, rejection, or disconnection
    scope: delegated command records
    text: These records remain stored after completion, expiry, rejection, or disconnection.
  rights:
  - right: access, correction, account closure, deletion
    text: To request access, correction, account closure, or deletion of data that can legally and operationally be removed, email austin@symbaiex.com.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: The site does not sell access to private user data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: symbaiex-com
provenance_date: '2026-11-10'
provider_name: symbaiex-com
provider_slug: symbaiex-com
slug: symbaiex-com-privacy-policy
source_date: '2026-11-10'
source_filename: symbaiex-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.symbaiex.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: symbaiex-com\naid: symbaiex-com\nurl: https://www.symbaiex.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account setup uses a public handle, password or Google sign-in, and an optional contact email.\n- category: contact\n  text: WorkOS receives your account ID and contact email to complete sign-in and manage application consent and\n    tokens.\n- category: communication\n  text: These records can include private message bodies, profile fields, or moderation content.\n- category: device\n  text: Agent identity records include\
  \ a stable identifier, owner, granted scopes, status, and security audit records.\npurposes:\n- purpose: respond, deliver, honor preferences, investigate abuse\n  text: Contact messages and newsletter details are stored long enough to respond, deliver, honor preferences, investigate\n    abuse, and maintain required delivery records.\n- purpose: enforce access and support disconnection\n  text: to enforce access and support disconnection\nretention:\n- scope: review proposals approval eligibility\n  period: 24 hours\n  text: Review proposals remain eligible for owner approval for 24 hours; expiry does not delete the stored proposal\n    or command record.\n- scope: delegated command records\n  period: after completion, expiry, rejection, or disconnection\n  text: These records remain stored after completion, expiry, rejection, or disconnection.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ email austin@symbaiex.com\n  text: To request access, correction, account closure, or deletion of data that can legally and operationally be\n    removed, email austin@symbaiex.com.\nrights:\n- right: access, correction, account closure, deletion\n  text: To request access, correction, account closure, or deletion of data that can legally and operationally be\n    removed, email austin@symbaiex.com.\nsale_or_sharing:\n  stance: prohibited\n  text: The site does not sell access to private user data.\n"
source_yaml_url: https://artifacts.apis.io/symbaiex-com/privacy/symbaiex-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from symbaiex-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Research
- OpenAPI
- Public Data
---
