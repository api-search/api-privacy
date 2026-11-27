---
api_specs:
- filename: veritahire-com-account-api-openapi.yml
  format: yaml
  label: veritahire-com Account API
  slug: veritahire-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-account-api-openapi.yml
- filename: veritahire-com-employer-profile-api-openapi.yml
  format: yaml
  label: veritahire-com Employer profile API
  slug: veritahire-com-employer-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-employer-profile-api-openapi.yml
- filename: veritahire-com-free-no-key-api-openapi.yml
  format: yaml
  label: veritahire-com Free, no key API
  slug: veritahire-com-free-no-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-free-no-key-api-openapi.yml
- filename: veritahire-com-hiring-market-php-api-openapi.yml
  format: yaml
  label: veritahire-com Hiring Market.php API
  slug: veritahire-com-hiring-market-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-hiring-market-php-api-openapi.yml
- filename: veritahire-com-hiring-velocity-api-openapi.yml
  format: yaml
  label: veritahire-com Hiring velocity API
  slug: veritahire-com-hiring-velocity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-hiring-velocity-api-openapi.yml
- filename: veritahire-com-postings-api-openapi.yml
  format: yaml
  label: veritahire-com Postings API
  slug: veritahire-com-postings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veritahire-com/openapi/veritahire-com-postings-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, phone number, and ZIP code;
  - category: professional
    text: your résumé and any cover letter
  - category: device
    text: basic technical logs (IP address, browser type, pages requested)
  deletion:
    route: request account deletion by contacting VeritaHire
    text: You can ask us to delete your account and associated data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: job matching
    text: We compare the skills and experience in your profile to live job postings using our own in-house logic.
  - purpose: routing applications
    text: When you submit an application, we transmit it to the employer you chose.
  - purpose: account and service operation
    text: To sign you in, keep the site secure, prevent abuse, and (only if you opt in) email you about jobs you’re a strong fit for.
  retention:
  - period: null
    scope: user profile
    text: We keep your profile while your account is active.
  - period: 12 months
    scope: assistant tool call logs
    text: Kept 12 months.
  - period: 90 days
    scope: assistant job searches
    text: Kept 90 days.
  rights:
  - right: access, correction, deletion
    text: Access, correct, or delete.
  - right: marketing opt-out
    text: Opt out of marketing.
  - right: additional state rights
    text: Depending on where you live (for example, California), you may have additional rights to know, delete, correct, and to not be discriminated against for exercising them.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: We use a small number of service providers to run the site (hosting, and — for account verification — a text-message sender).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: veritahire-com
provenance_date: '2026-11-10'
provider_name: veritahire-com
provider_slug: veritahire-com
slug: veritahire-com-privacy-policy
source_date: '2026-11-10'
source_filename: veritahire-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://veritahire.com/privacy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: veritahire-com\naid: veritahire-com\nurl: https://veritahire.com/privacy.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, email address, phone number, and ZIP code;\n- category: professional\n  text: your résumé and any cover letter\n- category: device\n  text: basic technical logs (IP address, browser type, pages requested)\npurposes:\n- purpose: job matching\n  text: We compare the skills and experience in your profile to live job postings using our own in-house logic.\n- purpose: routing applications\n  text: When you submit\
  \ an application, we transmit it to the employer you chose.\n- purpose: account and service operation\n  text: To sign you in, keep the site secure, prevent abuse, and (only if you opt in) email you about jobs you’re\n    a strong fit for.\nretention:\n- scope: user profile\n  period: null\n  text: We keep your profile while your account is active.\n- scope: assistant tool call logs\n  period: 12 months\n  text: Kept 12 months.\n- scope: assistant job searches\n  period: 90 days\n  text: Kept 90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small number of service providers to run the site (hosting, and — for account verification — a\n    text-message sender).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request account deletion by contacting VeritaHire\n  text: You can ask us to delete your account and associated data at any time.\nrights:\n- right: access, correction, deletion\n  text: Access, correct, or delete.\n- right:\
  \ marketing opt-out\n  text: Opt out of marketing.\n- right: additional state rights\n  text: Depending on where you live (for example, California), you may have additional rights to know, delete, correct,\n    and to not be discriminated against for exercising them.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/veritahire-com/privacy/veritahire-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from veritahire-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job
- Hiring
- Data
---
