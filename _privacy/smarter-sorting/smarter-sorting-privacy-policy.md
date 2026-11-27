---
api_specs:
- filename: smarter-sorting-api-api-openapi.yml
  format: yaml
  label: Smarter Sorting Api(.*) API
  slug: smarter-sorting-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarter-sorting/openapi/smarter-sorting-api-api-openapi.yml
- filename: smarter-sorting-assets-api-openapi.yml
  format: yaml
  label: Smarter Sorting Assets(.*) API
  slug: smarter-sorting-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarter-sorting/openapi/smarter-sorting-assets-api-openapi.yml
- filename: smarter-sorting-docs-api-openapi.yml
  format: yaml
  label: Smarter Sorting Docs(.*) API
  slug: smarter-sorting-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarter-sorting/openapi/smarter-sorting-docs-api-openapi.yml
- filename: smarter-sorting-products-api-openapi.yml
  format: yaml
  label: Smarter Sorting Products API
  slug: smarter-sorting-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarter-sorting/openapi/smarter-sorting-products-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: device
    text: information from the device (device type, operating system, screen resolution, language, country you are located in, and web browser type)
  - category: identifying
    text: We only capture and store a truncated version of your IP address.
  - category: contact
    text: When visitors leave comments on the site we collect the data shown in the comments form, and the visitor’s IP address and browser user agent string to help spam detection.
  - category: behavioral
    text: the parts of our site you visit, the date and duration of your visit
  - category: biometric
    text: Biometric information , including imagery of the iris, retina, fingerprint, face, hand, palm, vein patterns, or voice recordings and keystroke patterns or rhythms
  - category: financial
    text: Financial Information , including bank account, billing address, and information about your income and account balances.
  deletion:
    route: account or comment deletion by user, or request to erase
    text: All users can see, edit, or delete their personal information at any time (except they cannot change their username).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: facilitate access and recognize misuse
    text: We process this usage data to facilitate your access to our services (e.g. to adjust our services to the device you are using), and to recognize and stop any misuse.
  - purpose: anonymized statistics and site improvement
    text: We also process usage data in an anonymized form for statistical purposes and to improve our site.
  - purpose: analytics and diagnosing technical problems
    text: We use analytics and tracking software to provide our end users with a better experience and service as well as diagnosing technical problems and analyzing user trends.
  - purpose: employment eligibility and hiring
    text: Determining your eligibility for a position with the company
  retention:
  - period: indefinitely
    scope: comments and metadata
    text: If you leave a comment, the comment and its metadata are retained indefinitely.
  - period: one year
    scope: comment cookies
    text: These cookies will last for one year.
  - period: two days
    scope: login cookies
    text: Login cookies last for two days
  rights:
  - right: access (exported file)
    text: you can request to receive an exported file of the personal data we hold about you
  - right: erasure
    text: You can also request that we erase any personal data we hold about you.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your personal data to anyone
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Smarter Sorting
provenance_date: '2026-11-10'
provider_name: Smarter Sorting
provider_slug: smarter-sorting
slug: smarter-sorting-privacy-policy
source_date: '2026-11-10'
source_filename: smarter-sorting-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.smartersorting.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Smarter Sorting\naid: smarter-sorting\nurl: https://www.smartersorting.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: information from the device (device type, operating system, screen resolution, language, country you are\n    located in, and web browser type)\n- category: identifying\n  text: We only capture and store a truncated version of your IP address.\n- category: contact\n  text: When visitors leave comments on the site we collect the data shown in the comments form, and the visitor’s\n    IP address and browser\
  \ user agent string to help spam detection.\n- category: behavioral\n  text: the parts of our site you visit, the date and duration of your visit\n- category: biometric\n  text: Biometric information , including imagery of the iris, retina, fingerprint, face, hand, palm, vein patterns,\n    or voice recordings and keystroke patterns or rhythms\n- category: financial\n  text: Financial Information , including bank account, billing address, and information about your income and account\n    balances.\npurposes:\n- purpose: facilitate access and recognize misuse\n  text: We process this usage data to facilitate your access to our services (e.g. to adjust our services to the\n    device you are using), and to recognize and stop any misuse.\n- purpose: anonymized statistics and site improvement\n  text: We also process usage data in an anonymized form for statistical purposes and to improve our site.\n- purpose: analytics and diagnosing technical problems\n  text: We use analytics and tracking\
  \ software to provide our end users with a better experience and service as\n    well as diagnosing technical problems and analyzing user trends.\n- purpose: employment eligibility and hiring\n  text: Determining your eligibility for a position with the company\nretention:\n- scope: comments and metadata\n  period: indefinitely\n  text: If you leave a comment, the comment and its metadata are retained indefinitely.\n- scope: comment cookies\n  period: one year\n  text: These cookies will last for one year.\n- scope: login cookies\n  period: two days\n  text: Login cookies last for two days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account or comment deletion by user, or request to erase\n  text: All users can see, edit, or delete their personal information at any time (except they cannot change their\n    username).\nrights:\n- right: access (exported file)\n  text: you can request to\
  \ receive an exported file of the personal data we hold about you\n- right: erasure\n  text: You can also request that we erase any personal data we hold about you.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your personal data to anyone\n"
source_yaml_url: https://artifacts.apis.io/smarter-sorting/privacy/smarter-sorting-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Smarter Sorting's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Data
- Regulatory Compliance
- Hazardous Waste
- Retail
- Consumer Goods
- Supply Chain
- Sustainability
- Dangerous Goods
- Product Classification
---
