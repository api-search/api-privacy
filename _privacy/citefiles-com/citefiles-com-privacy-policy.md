---
api_specs:
- filename: citefiles-com-openapi-generated.yml
  format: yaml
  label: Cite Files API
  slug: citefiles-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citefiles-com/openapi/_ae-authored/citefiles-com-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: We store your email address, your name if you gave one
  - category: device
    text: your IP address
  - category: device
    text: We also set one cookie holding a random identifier.
  - category: other
    text: Page titles, meta descriptions, headings, word counts, structured-data types, HTTP status codes, response headers relevant to crawling, and a text excerpt from each page we read.
  deletion:
    route: account page
    text: You can delete your own account, immediately, from your account page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Rate limiting
    text: The IP is used for rate limiting
  - purpose: Account matters
    text: 'Your email is used for account matters only: confirming the address, resetting the password, and telling you if someone tries to register with it.'
  - purpose: Generate llms.txt and answerability test
    text: The excerpt is what lets us generate your llms.txt and run the answerability test.
  retention:
  - period: 90 days
    scope: Scans not attached to an account
    text: Scans not attached to an account are deleted after 90 days.
  - period: until you delete them or close the account
    scope: Scans in an account
    text: Scans in an account stay until you delete them or close the account.
  - period: two days
    scope: Free tool rate-limit counter for IP
    text: The rate-limit counter a free tool keeps for your IP address is deleted within two days
  - period: thirty minutes
    scope: Staging site passwords
    text: It exists in the memory of the process running your scan, for thirty minutes, and then it is gone.
  rights:
  - right: Access
    text: You can also ask for a copy of what we hold about you
  - right: Correction
    text: ask us to correct it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell anything to anybody
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cite Files
provenance_date: '2026-11-09'
provider_name: Cite Files
provider_slug: citefiles-com
slug: citefiles-com-privacy-policy
source_date: '2026-11-09'
source_filename: citefiles-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://citefiles.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cite Files\naid: citefiles-com\nurl: https://citefiles.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We store your email address, your name if you gave one\n- category: device\n  text: your IP address\n- category: device\n  text: We also set one cookie holding a random identifier.\n- category: other\n  text: Page titles, meta descriptions, headings, word counts, structured-data types, HTTP status codes, response\n    headers relevant to crawling, and a text excerpt from each page we read.\npurposes:\n- purpose: Rate limiting\n\
  \  text: The IP is used for rate limiting\n- purpose: Account matters\n  text: 'Your email is used for account matters only: confirming the address, resetting the password, and telling\n    you if someone tries to register with it.'\n- purpose: Generate llms.txt and answerability test\n  text: The excerpt is what lets us generate your llms.txt and run the answerability test.\nretention:\n- scope: Scans not attached to an account\n  period: 90 days\n  text: Scans not attached to an account are deleted after 90 days.\n- scope: Scans in an account\n  period: until you delete them or close the account\n  text: Scans in an account stay until you delete them or close the account.\n- scope: Free tool rate-limit counter for IP\n  period: two days\n  text: The rate-limit counter a free tool keeps for your IP address is deleted within two days\n- scope: Staging site passwords\n  period: thirty minutes\n  text: It exists in the memory of the process running your scan, for thirty minutes, and then\
  \ it is gone.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account page\n  text: You can delete your own account, immediately, from your account page\nrights:\n- right: Access\n  text: You can also ask for a copy of what we hold about you\n- right: Correction\n  text: ask us to correct it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell anything to anybody\n"
source_yaml_url: https://artifacts.apis.io/citefiles-com/privacy/citefiles-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Cite Files's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Crawling
- Accessibility
- Open Source
---
