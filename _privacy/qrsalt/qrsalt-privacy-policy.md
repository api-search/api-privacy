---
api_specs:
- filename: qrsalt-barcode-api-openapi.yml
  format: yaml
  label: QRSalt Barcode API
  slug: qrsalt-barcode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-barcode-api-openapi.yml
- filename: qrsalt-codes-api-openapi.yml
  format: yaml
  label: QRSalt Codes API
  slug: qrsalt-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-codes-api-openapi.yml
- filename: qrsalt-domains-api-openapi.yml
  format: yaml
  label: QRSalt Domains API
  slug: qrsalt-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-domains-api-openapi.yml
- filename: qrsalt-forms-api-openapi.yml
  format: yaml
  label: QRSalt Forms API
  slug: qrsalt-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-forms-api-openapi.yml
- filename: qrsalt-i-api-openapi.yml
  format: yaml
  label: QRSalt I API
  slug: qrsalt-i-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-i-api-openapi.yml
- filename: qrsalt-qr-api-openapi.yml
  format: yaml
  label: QRSalt Qr API
  slug: qrsalt-qr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-qr-api-openapi.yml
- filename: qrsalt-qrsalt-api-api-openapi.yml
  format: yaml
  label: QRSalt QRSalt API
  slug: qrsalt-qrsalt-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qrsalt/openapi/qrsalt-qrsalt-api-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, and a name if you give one.
  - category: device
    text: the device type, operating system family and browser family
  - category: location
    text: 'an approximate location: country, region, city and a position rounded to about 11 km, as reported by Cloudflare'
  - category: behavioral
    text: the referring site, when there is one
  - category: financial
    text: We receive and keep the plan, price, billing interval, status, dates and Whop's reference numbers
  deletion:
    route: Settings
    text: You can delete your account from Settings.
  dpa:
    available: true
    text: under our data processing agreement
    url: null
  purposes:
  - purpose: Running accounts, serving codes and pages, payment, service email
    text: Running your account, serving your codes and pages, taking payment, service email
  - purpose: Security and abuse prevention
    text: Security, rate limiting, bot checks, destination checks, image moderation, abuse handling, security records, technical logs and backups
  - purpose: Ad measurement and analytics with consent
    text: Ad measurement and analytics cookies, reporting sign-ups and purchases to Google (including the hashed email), and keeping the ad click identifier
  residency:
  - region: United States (New York)
    text: The service runs on a server in New York
  retention:
  - period: 30 days
    scope: Individual scan events
    text: Individual scan events 30 days, after they have been added to daily totals, then deleted
  - period: Two days at most
    scope: Page and menu visitor hashes
    text: Page and menu visitor hashes Two days at most
  - period: Until you delete them or your account
    scope: Account, content and codes
    text: Your account, content, codes and destination history Until you delete them or your account (see section 10)
  rights:
  - right: Access and portability
    text: get a copy of your data, and take it elsewhere in a machine-readable format
  - right: Correction
    text: 'correct it: change it in the dashboard, or email us'
  - right: Deletion
    text: 'delete it: delete individual items, or your whole account from Settings'
  - right: Restriction
    text: restrict our use of it while a complaint is looked into
  - right: Objection
    text: object to anything we do on the basis of legitimate interests
  - right: Withdraw consent
    text: withdraw consent to ad measurement and analytics, as easily as you gave it, in Cookie settings
  role:
    text: we are the controller
    value: controller
  sale_or_sharing:
    stance: conditional
    text: When ad measurement is on, the Google tag (Google Ads and Google Analytics)
  subprocessors:
    text: The full list, with what each handles and where, is on the sub-processor page
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on the European Commission's Standard Contractual Clauses in our contracts with those providers
  - mechanism: DPF
    text: and on the EU–US Data Privacy Framework for providers that are certified under it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: QRSalt
provenance_date: '2026-11-10'
provider_name: QRSalt
provider_slug: qrsalt
slug: qrsalt-privacy-policy
source_date: '2026-11-10'
source_filename: qrsalt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://qrsalt.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: QRSalt\naid: qrsalt\nurl: https://qrsalt.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: we are the controller\ndata_categories:\n- category: identifying\n  text: Your email address, and a name if you give one.\n- category: device\n  text: the device type, operating system family and browser family\n- category: location\n  text: 'an approximate location: country, region, city and a position rounded to about 11 km, as reported by Cloudflare'\n- category: behavioral\n  text: the referring site, when there is one\n- category: financial\n  text: We receive and keep the plan, price,\
  \ billing interval, status, dates and Whop's reference numbers\npurposes:\n- purpose: Running accounts, serving codes and pages, payment, service email\n  text: Running your account, serving your codes and pages, taking payment, service email\n- purpose: Security and abuse prevention\n  text: Security, rate limiting, bot checks, destination checks, image moderation, abuse handling, security records,\n    technical logs and backups\n- purpose: Ad measurement and analytics with consent\n  text: Ad measurement and analytics cookies, reporting sign-ups and purchases to Google (including the hashed email),\n    and keeping the ad click identifier\nretention:\n- scope: Individual scan events\n  period: 30 days\n  text: Individual scan events 30 days, after they have been added to daily totals, then deleted\n- scope: Page and menu visitor hashes\n  period: Two days at most\n  text: Page and menu visitor hashes Two days at most\n- scope: Account, content and codes\n  period: Until you delete them\
  \ or your account\n  text: Your account, content, codes and destination history Until you delete them or your account (see section\n    10)\nresidency:\n- region: United States (New York)\n  text: The service runs on a server in New York\ntransfers:\n- mechanism: SCC\n  text: We rely on the European Commission's Standard Contractual Clauses in our contracts with those providers\n- mechanism: DPF\n  text: and on the EU–US Data Privacy Framework for providers that are certified under it.\nsubprocessors:\n  url: null\n  text: The full list, with what each handles and where, is on the sub-processor page\ndpa:\n  available: true\n  url: null\n  text: under our data processing agreement\ndeletion:\n  route: Settings\n  text: You can delete your account from Settings.\nrights:\n- right: Access and portability\n  text: get a copy of your data, and take it elsewhere in a machine-readable format\n- right: Correction\n  text: 'correct it: change it in the dashboard, or email us'\n- right: Deletion\n\
  \  text: 'delete it: delete individual items, or your whole account from Settings'\n- right: Restriction\n  text: restrict our use of it while a complaint is looked into\n- right: Objection\n  text: object to anything we do on the basis of legitimate interests\n- right: Withdraw consent\n  text: withdraw consent to ad measurement and analytics, as easily as you gave it, in Cookie settings\nsale_or_sharing:\n  stance: conditional\n  text: When ad measurement is on, the Google tag (Google Ads and Google Analytics)\n"
source_yaml_url: https://artifacts.apis.io/qrsalt/privacy/qrsalt-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from QRSalt's own page on 2026-11-10.
synthetic: false
tags:
- QR Codes
- Barcodes
- Analytics
- Dynamic links
---
