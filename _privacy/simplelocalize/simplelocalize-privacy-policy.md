---
api_specs:
- filename: simplelocalize-customers-api-openapi.yml
  format: yaml
  label: SimpleLocalize Customers API
  slug: simplelocalize-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-customers-api-openapi.yml
- filename: simplelocalize-export-api-openapi.yml
  format: yaml
  label: SimpleLocalize Export API
  slug: simplelocalize-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-export-api-openapi.yml
- filename: simplelocalize-import-api-openapi.yml
  format: yaml
  label: SimpleLocalize Import API
  slug: simplelocalize-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-import-api-openapi.yml
- filename: simplelocalize-languages-api-openapi.yml
  format: yaml
  label: SimpleLocalize Languages API
  slug: simplelocalize-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-languages-api-openapi.yml
- filename: simplelocalize-projects-api-openapi.yml
  format: yaml
  label: SimpleLocalize Projects API
  slug: simplelocalize-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-projects-api-openapi.yml
- filename: simplelocalize-publication-api-openapi.yml
  format: yaml
  label: SimpleLocalize Publication API
  slug: simplelocalize-publication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-publication-api-openapi.yml
- filename: simplelocalize-translations-api-openapi.yml
  format: yaml
  label: SimpleLocalize Translations API
  slug: simplelocalize-translations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplelocalize/openapi/simplelocalize-translations-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: An email address is required to create an account.
  - category: identifying
    text: An IP address is processed and stored.
  - category: identifying
    text: If you use social login (GitHub, Google Account, Microsoft Account), then we additionally process and store your social login identifier , profile photo , first name , last name
  - category: financial
    text: the billing information and the payment process is handled by Paddle .
  deletion:
    route: Email contact@simplelocalize.io
    text: You have the right to delete or change your account information by e-mailing us at contact@simplelocalize.io .
  dpa:
    available: true
    text: Here you can also find our Data Processing Agreement (DPA) .
    url: https://simplelocalize.io/privacy-policy/
  purposes:
  - purpose: Login
    text: Login SimpleLocalize.io Use SimpleLocalize.io features
  - purpose: Account and service
    text: we can send you invoices, updates or other essential information
  - purpose: Business communications
    text: Informing users about business matters
  residency:
  - region: Ireland (EU)
    text: Your data is stored in a secure Amazon Web Services hosting center (Amazon Data Services Ireland Limited) in the Ireland (EU member)
  retention:
  - period: null
    scope: Records kept for legal obligations
    text: In the event that it is our duty to keep a record of some of your personal information, for example for accounting purposes, this information is retained.
  - period: 30 days
    scope: Other information on deletion request
    text: We will irrevocably remove all other information within 30 days of your request.
  rights:
  - right: Delete or change account data
    text: You have the right to delete or change your account information by e-mailing us
  - right: Withdraw consent
    text: Where we rely on your consent to process your personal data, you have the right to withdraw or decline consent at any time.
  - right: Object
    text: Where we rely on our legitimate interests to process your personal data, you have the right to object.
  - right: Unsubscribe from commercial communications
    text: You may manage your receipt of commercial communications by clicking on the "unsubscribe" link
  role:
    text: SimpleLocalize.io is the data controller for the Personal Data of Customers and Website Visitors, but not for the Personal Data of End Users.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not rent or sell personal information and any other information we store.
  subprocessors:
    text: Sub-processors Amazon Web Services (EU, Amazon Data Services Ireland Limited) - hosting, cloud infrastructure, data storage, Hetzner.com (Germany) - hosting, cloud infrastructure, data storage
    url: https://simplelocalize.io/privacy-policy/
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SimpleLocalize
provenance_date: '2026-11-10'
provider_name: SimpleLocalize
provider_slug: simplelocalize
slug: simplelocalize-privacy-policy
source_date: '2026-11-10'
source_filename: simplelocalize-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://simplelocalize.io/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SimpleLocalize\naid: simplelocalize\nurl: https://simplelocalize.io/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: SimpleLocalize.io is the data controller for the Personal Data of Customers and Website Visitors, but not\n    for the Personal Data of End Users.\ndata_categories:\n- category: contact\n  text: An email address is required to create an account.\n- category: identifying\n  text: An IP address is processed and stored.\n- category: identifying\n  text: If you use social login (GitHub, Google Account, Microsoft Account), then we additionally process and store\n  \
  \  your social login identifier , profile photo , first name , last name\n- category: financial\n  text: the billing information and the payment process is handled by Paddle .\npurposes:\n- purpose: Login\n  text: Login SimpleLocalize.io Use SimpleLocalize.io features\n- purpose: Account and service\n  text: we can send you invoices, updates or other essential information\n- purpose: Business communications\n  text: Informing users about business matters\nretention:\n- scope: Records kept for legal obligations\n  period: null\n  text: In the event that it is our duty to keep a record of some of your personal information, for example for\n    accounting purposes, this information is retained.\n- scope: Other information on deletion request\n  period: 30 days\n  text: We will irrevocably remove all other information within 30 days of your request.\nresidency:\n- region: Ireland (EU)\n  text: Your data is stored in a secure Amazon Web Services hosting center (Amazon Data Services Ireland\
  \ Limited)\n    in the Ireland (EU member)\ntransfers: []\nsubprocessors:\n  url: https://simplelocalize.io/privacy-policy/\n  text: Sub-processors Amazon Web Services (EU, Amazon Data Services Ireland Limited) - hosting, cloud infrastructure,\n    data storage, Hetzner.com (Germany) - hosting, cloud infrastructure, data storage\ndpa:\n  available: true\n  url: https://simplelocalize.io/privacy-policy/\n  text: Here you can also find our Data Processing Agreement (DPA) .\ndeletion:\n  route: Email contact@simplelocalize.io\n  text: You have the right to delete or change your account information by e-mailing us at contact@simplelocalize.io\n    .\nrights:\n- right: Delete or change account data\n  text: You have the right to delete or change your account information by e-mailing us\n- right: Withdraw consent\n  text: Where we rely on your consent to process your personal data, you have the right to withdraw or decline consent\n    at any time.\n- right: Object\n  text: Where we rely on\
  \ our legitimate interests to process your personal data, you have the right to object.\n- right: Unsubscribe from commercial communications\n  text: You may manage your receipt of commercial communications by clicking on the \"unsubscribe\" link\nsale_or_sharing:\n  stance: prohibited\n  text: We do not rent or sell personal information and any other information we store.\n"
source_yaml_url: https://artifacts.apis.io/simplelocalize/privacy/simplelocalize-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from SimpleLocalize's own page on 2026-11-10.
synthetic: false
tags:
- Localization
- Translation
- Internationalization
---
