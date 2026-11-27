---
api_specs:
- filename: food-info-recipesapi-api-openapi.yml
  format: yaml
  label: Food Info Recipes API
  slug: food-info-recipesapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-info/openapi/food-info-recipesapi-api-openapi.yml
- filename: food-info-api-v1-api-openapi.yml
  format: yaml
  label: Food Info api v1 API
  slug: food-info-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-info/openapi/food-info-api-v1-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address , used as your sign-in identifier and for password-reset emails.
  - category: demographic
    text: Date of birth , used to derive your age, which bands the nutrient reference intakes.
  - category: health
    text: Ethnicity is special category data under UK GDPR Art. 9(1), because it is information about racial or ethnic origin.
  - category: location
    text: approximate location (city-level, derived from IP and then discarded)
  - category: behavioral
    text: Your search-click history (which foods you opened) and your UI preferences (theme, default serving unit)
  - category: financial
    text: Stripe receives your email address, payment card details (which we never see ourselves), billing address
  deletion:
    route: Delete my account from the Account page
    text: '"Delete my account" cancels any active subscription and irreversibly clears every satellite record by user id.'
  dpa:
    available: true
    text: We have a written data-processing agreement with each of them and only the data strictly necessary for the relevant service is shared.
    url: null
  purposes:
  - purpose: account creation and authentication
    text: Performance of a contract (UK GDPR Art. 6(1)(b)), for account creation, authentication and the synced features that depend on a signed-in account.
  - purpose: analytics with consent
    text: Consent (Art. 6(1)(a)), for setting analytics cookies (Google Analytics 4).
  - purpose: publishing contributor credit
    text: Performance of a contract again (Art. 6(1)(b)), for publishing the credit you ask us to use alongside a recipe or photograph you have contributed
  residency:
  - region: Europe-West (Neon database)
    text: Configured to run in our Europe-West region; the operator entity is US.
  retention:
  - period: within 30 days of account closure
    scope: Account records
    text: Account records (email, password hash, display name, linked Google identifier) are kept while the account is active and deleted within 30 days of account closure.
  - period: up to 90 days
    scope: Application logs
    text: Application logs are kept for up to 90 days for security and operational diagnostics, then rotated out.
  - period: 6 years after it comes down
    scope: Contributor permissions
    text: Contributor permissions , the message granting us the right to publish your recipe or photograph, are kept while the material is published and for 6 years after it comes down
  - period: 7 years
    scope: Payment records
    text: Stripe retains payment records for 7 years to comply with HMRC record-keeping rules
  rights:
  - right: access
    text: Ask for a copy of the personal data we hold about you (right of access).
  - right: rectification
    text: Have inaccurate data corrected (rectification).
  - right: erasure
    text: Have your data erased, i.e. close your account (erasure / "right to be forgotten").
  - right: restriction or objection
    text: Restrict or object to processing in certain circumstances.
  - right: portability
    text: Receive your data in a portable format.
  - right: withdraw consent
    text: Withdraw consent at any time, where consent is the lawful basis.
  role:
    text: The data controller is DCPNET LTD (Company No. 15734157, VAT 512 3682 13), trading as Food Info
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For Stripe, the Stripe UK Addendum to its EU Standard Contractual Clauses, plus the EU Commission's Data Privacy Framework adequacy decision where applicable.
  - mechanism: DPF
    text: plus the EU Commission's Data Privacy Framework adequacy decision where applicable.
  - mechanism: other
    text: For Fly.io, Neon and Cloudflare, the UK IDTA with the respective Data Processing Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Food Info
provenance_date: '2026-11-09'
provider_name: Food Info
provider_slug: food-info
slug: food-info-privacy-policy
source_date: '2026-11-09'
source_filename: food-info-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://food-info.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Food Info\naid: food-info\nurl: https://food-info.org/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is DCPNET LTD (Company No. 15734157, VAT 512 3682 13), trading as Food Info\ndata_categories:\n- category: identifying\n  text: Email address , used as your sign-in identifier and for password-reset emails.\n- category: demographic\n  text: Date of birth , used to derive your age, which bands the nutrient reference intakes.\n- category: health\n  text: Ethnicity is special category data under UK GDPR Art. 9(1), because it is information about racial or ethnic\n\
  \    origin.\n- category: location\n  text: approximate location (city-level, derived from IP and then discarded)\n- category: behavioral\n  text: Your search-click history (which foods you opened) and your UI preferences (theme, default serving unit)\n- category: financial\n  text: Stripe receives your email address, payment card details (which we never see ourselves), billing address\npurposes:\n- purpose: account creation and authentication\n  text: Performance of a contract (UK GDPR Art. 6(1)(b)), for account creation, authentication and the synced features\n    that depend on a signed-in account.\n- purpose: analytics with consent\n  text: Consent (Art. 6(1)(a)), for setting analytics cookies (Google Analytics 4).\n- purpose: publishing contributor credit\n  text: Performance of a contract again (Art. 6(1)(b)), for publishing the credit you ask us to use alongside a\n    recipe or photograph you have contributed\nretention:\n- scope: Account records\n  period: within 30 days of account\
  \ closure\n  text: Account records (email, password hash, display name, linked Google identifier) are kept while the account\n    is active and deleted within 30 days of account closure.\n- scope: Application logs\n  period: up to 90 days\n  text: Application logs are kept for up to 90 days for security and operational diagnostics, then rotated out.\n- scope: Contributor permissions\n  period: 6 years after it comes down\n  text: Contributor permissions , the message granting us the right to publish your recipe or photograph, are kept\n    while the material is published and for 6 years after it comes down\n- scope: Payment records\n  period: 7 years\n  text: Stripe retains payment records for 7 years to comply with HMRC record-keeping rules\nresidency:\n- region: Europe-West (Neon database)\n  text: Configured to run in our Europe-West region; the operator entity is US.\ntransfers:\n- mechanism: SCC\n  text: For Stripe, the Stripe UK Addendum to its EU Standard Contractual Clauses, plus\
  \ the EU Commission's Data\n    Privacy Framework adequacy decision where applicable.\n- mechanism: DPF\n  text: plus the EU Commission's Data Privacy Framework adequacy decision where applicable.\n- mechanism: other\n  text: For Fly.io, Neon and Cloudflare, the UK IDTA with the respective Data Processing Addendum.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We have a written data-processing agreement with each of them and only the data strictly necessary for the\n    relevant service is shared.\ndeletion:\n  route: Delete my account from the Account page\n  text: '\"Delete my account\" cancels any active subscription and irreversibly clears every satellite record by user\n    id.'\nrights:\n- right: access\n  text: Ask for a copy of the personal data we hold about you (right of access).\n- right: rectification\n  text: Have inaccurate data corrected (rectification).\n- right: erasure\n  text: Have your data erased, i.e. close your account\
  \ (erasure / \"right to be forgotten\").\n- right: restriction or objection\n  text: Restrict or object to processing in certain circumstances.\n- right: portability\n  text: Receive your data in a portable format.\n- right: withdraw consent\n  text: Withdraw consent at any time, where consent is the lawful basis.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/food-info/privacy/food-info-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Food Info's own page on 2026-11-09.
synthetic: false
tags:
- Nutrition
- Food
- food-composition
- Nutrients
- Data
- Open Data
- Dietetics
- Recipes
- Health
- Research
---
