---
api_specs:
- filename: botnotice-app-consent-api-openapi.yml
  format: yaml
  label: BotNotice Consent API
  slug: botnotice-app-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botnotice-app/openapi/botnotice-app-consent-api-openapi.yml
- filename: botnotice-app-content-register-api-openapi.yml
  format: yaml
  label: BotNotice Content register API
  slug: botnotice-app-content-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botnotice-app/openapi/botnotice-app-content-register-api-openapi.yml
- filename: botnotice-app-free-tools-api-openapi.yml
  format: yaml
  label: BotNotice Free tools API
  slug: botnotice-app-free-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botnotice-app/openapi/botnotice-app-free-tools-api-openapi.yml
- filename: botnotice-app-law-dataset-api-openapi.yml
  format: yaml
  label: BotNotice Law dataset API
  slug: botnotice-app-law-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botnotice-app/openapi/botnotice-app-law-dataset-api-openapi.yml
- filename: botnotice-app-voice-api-openapi.yml
  format: yaml
  label: BotNotice Voice API
  slug: botnotice-app-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botnotice-app/openapi/botnotice-app-voice-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, the domains and settings of sites you add, the answers you give in the AI profile, and billing information processed by Stripe (we never see full card numbers).
  - category: device
    text: Our servers derive a short, daily-rotating code from the visitor's IP address and browser, keyed with a secret only we hold, so repeat views can be counted; the IP address and browser string themselves are not stored.
  - category: location
    text: Country and region are recorded when provided by our hosting network.
  - category: communication
    text: The widget does not set cookies, does not track visitors across sites, and does not collect names, messages or chat content.
  deletion:
    route: Email support@botnotice.app to request deletion of account data
    text: You can access, correct, export or delete your account data by emailing support@botnotice.app.
  dpa:
    available: true
    text: we process that data for them, under our Data Processing Agreement .
    url: https://botnotice.app/legal/dpa
  purposes:
  - purpose: Operate the service
    text: To operate the service, produce logs and reports for the account holder, send sign-in links, billing emails, the scan reports people ask for and (on Managed Compliance) weekly law-change digests, and to improve the product.
  - purpose: Scan report follow-up
    text: We use your email to send you the report link and to follow up about it.
  residency:
  - region: United States
    text: Our servers and our providers are in the United States.
  retention:
  - period: 7 years on plans with records
    scope: Disclosure records
    text: Disclosure records are kept for the account's retention period (7 years on plans with records, or a shorter period the account holder chooses) and deleted about 30 days after, together with their off-site copies, unless they are under a legal hold.
  - period: one year
    scope: Free scan reports
    text: Reports and the emails kept with them are deleted one year after the report was made, or sooner if you ask.
  - period: within 30 days of a request
    scope: Account data
    text: Account data is deleted within 30 days of a request.
  rights:
  - right: Access, correction, export, deletion
    text: You can access, correct, export or delete your account data by emailing support@botnotice.app.
  - right: Object or restrict processing
    text: You can ask for access to, correction, deletion or a copy of your data, object to or restrict its processing, and complain to your data protection authority.
  role:
    text: We are the controller for the information about our own account holders and website visitors described here. For the records BotNotice keeps about visitors to our customers' websites, the customer is the controller and we process that data for them, under our Data Processing Agreement .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: 'The full list, with what each one does and where: sub-processors .'
    url: https://botnotice.app/legal/sub-processors
  transfers:
  - mechanism: SCC
    text: Personal data transferred there from the EU, UK or Switzerland is protected by the European Commission's standard contractual clauses, with the UK addendum and Swiss adjustments, as set out in our Data Processing Agreement.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BotNotice
provenance_date: '2026-11-09'
provider_name: BotNotice
provider_slug: botnotice-app
slug: botnotice-app-privacy-policy
source_date: '2026-11-09'
source_filename: botnotice-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://botnotice.app/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BotNotice\naid: botnotice-app\nurl: https://botnotice.app/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller for the information about our own account holders and website visitors described here.\n    For the records BotNotice keeps about visitors to our customers' websites, the customer is the controller and\n    we process that data for them, under our Data Processing Agreement .\ndata_categories:\n- category: identifying\n  text: Your email address, the domains and settings of sites you add, the answers you give in the AI profile, and\n    billing information processed\
  \ by Stripe (we never see full card numbers).\n- category: device\n  text: Our servers derive a short, daily-rotating code from the visitor's IP address and browser, keyed with a\n    secret only we hold, so repeat views can be counted; the IP address and browser string themselves are not stored.\n- category: location\n  text: Country and region are recorded when provided by our hosting network.\n- category: communication\n  text: The widget does not set cookies, does not track visitors across sites, and does not collect names, messages\n    or chat content.\npurposes:\n- purpose: Operate the service\n  text: To operate the service, produce logs and reports for the account holder, send sign-in links, billing emails,\n    the scan reports people ask for and (on Managed Compliance) weekly law-change digests, and to improve the product.\n- purpose: Scan report follow-up\n  text: We use your email to send you the report link and to follow up about it.\nretention:\n- scope: Disclosure records\n\
  \  period: 7 years on plans with records\n  text: Disclosure records are kept for the account's retention period (7 years on plans with records, or a shorter\n    period the account holder chooses) and deleted about 30 days after, together with their off-site copies, unless\n    they are under a legal hold.\n- scope: Free scan reports\n  period: one year\n  text: Reports and the emails kept with them are deleted one year after the report was made, or sooner if you ask.\n- scope: Account data\n  period: within 30 days of a request\n  text: Account data is deleted within 30 days of a request.\nresidency:\n- region: United States\n  text: Our servers and our providers are in the United States.\ntransfers:\n- mechanism: SCC\n  text: Personal data transferred there from the EU, UK or Switzerland is protected by the European Commission's\n    standard contractual clauses, with the UK addendum and Swiss adjustments, as set out in our Data Processing\n    Agreement.\nsubprocessors:\n  url: https://botnotice.app/legal/sub-processors\n\
  \  text: 'The full list, with what each one does and where: sub-processors .'\ndpa:\n  available: true\n  url: https://botnotice.app/legal/dpa\n  text: we process that data for them, under our Data Processing Agreement .\ndeletion:\n  route: Email support@botnotice.app to request deletion of account data\n  text: You can access, correct, export or delete your account data by emailing support@botnotice.app.\nrights:\n- right: Access, correction, export, deletion\n  text: You can access, correct, export or delete your account data by emailing support@botnotice.app.\n- right: Object or restrict processing\n  text: You can ask for access to, correction, deletion or a copy of your data, object to or restrict its processing,\n    and complain to your data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/botnotice-app/privacy/botnotice-app-privacy-policy.yml
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
summary_line: 18 quoted statements, read from BotNotice's own page on 2026-11-09.
synthetic: false
tags:
- AI disclosure
- chatbot compliance
- Recordkeeping
- website widget
- managed compliance
- subscription pricing
---
