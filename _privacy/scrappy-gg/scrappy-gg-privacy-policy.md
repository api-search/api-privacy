---
api_specs:
- filename: scrappy-gg-openapi-generated.yml
  format: yaml
  label: Scrappy.gg API
  slug: scrappy-gg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scrappy-gg/openapi/_ae-authored/scrappy-gg-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: name, email address, password (stored hashed), profile picture if you sign in with a provider that supplies one'
  - category: contact
    text: 'Leads and profiles a customer collects: typically names, job titles, employers, business email addresses, phone numbers and public social profile links'
  - category: financial
    text: 'Billing: credit balance, usage and purchases. Card details are entered on the hosted checkout of our billing provider and are not seen or stored by us'
  - category: device
    text: 'Sign-in and security records: sign-in times, failed sign-in attempts, IP address and browser user agent'
  - category: behavioral
    text: 'Cloud browser data: the pages visited in a session, files downloaded or uploaded, recordings a customer makes, and saved logins (cookies and site storage) for browser profiles'
  - category: communication
    text: Messages you send us by email or through the chat on our website
  deletion:
    route: Settings > Privacy
    text: delete your account from Settings > Privacy. There is a 30-day grace period during which you can cancel
  dpa:
    available: null
    text: A data processing agreement including transfer terms is being prepared and will be available on request.
    url: null
  purposes:
  - purpose: Providing the service
    text: 'Providing the service you signed up for: your account, running jobs and sessions, billing'
  - purpose: Security
    text: 'Keeping the service secure: sign-in records, rate limiting, lockouts, audit logging'
  - purpose: Diagnostics and reliability
    text: 'Diagnosing faults and improving reliability: logs and performance measurements'
  - purpose: Marketing emails
    text: Marketing emails Your consent, which you can withdraw at any time in Settings
  residency:
  - region: United States
    text: Scrappy is hosted in the United States
  retention:
  - period: While your account is open
    scope: Account data
    text: Account data While your account is open
  - period: 730 days by default
    scope: Leads and profiles
    text: Leads and profiles 730 days by default
  - period: 30 days
    scope: Application logs
    text: Application logs 30 days
  - period: 2 years
    scope: Audit logs
    text: Audit logs 2 years
  rights:
  - right: access
    text: you may have the right to access, correct, delete, export or restrict the use of your personal data
  - right: object
    text: to object to its use, and to withdraw consent
  - right: complain
    text: You also have the right to complain to your local data protection authority.
  role:
    text: For account data, we are the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: The full list, with what each provider receives, is on the subprocessors page
    url: https://scrappy.gg/subprocessors
  transfers:
  - mechanism: other
    text: we do not yet have Standard Contractual Clauses or a Data Privacy Framework certification in place.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Scrappy.gg
provenance_date: '2026-11-10'
provider_name: Scrappy.gg
provider_slug: scrappy-gg
slug: scrappy-gg-privacy-policy
source_date: '2026-11-10'
source_filename: scrappy-gg-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scrappy.gg/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Scrappy.gg\naid: scrappy-gg\nurl: https://scrappy.gg/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account data, we are the controller.\ndata_categories:\n- category: identifying\n  text: 'Account details: name, email address, password (stored hashed), profile picture if you sign in with a provider\n    that supplies one'\n- category: contact\n  text: 'Leads and profiles a customer collects: typically names, job titles, employers, business email addresses,\n    phone numbers and public social profile links'\n- category: financial\n  text: 'Billing: credit balance, usage and purchases.\
  \ Card details are entered on the hosted checkout of our billing\n    provider and are not seen or stored by us'\n- category: device\n  text: 'Sign-in and security records: sign-in times, failed sign-in attempts, IP address and browser user agent'\n- category: behavioral\n  text: 'Cloud browser data: the pages visited in a session, files downloaded or uploaded, recordings a customer\n    makes, and saved logins (cookies and site storage) for browser profiles'\n- category: communication\n  text: Messages you send us by email or through the chat on our website\npurposes:\n- purpose: Providing the service\n  text: 'Providing the service you signed up for: your account, running jobs and sessions, billing'\n- purpose: Security\n  text: 'Keeping the service secure: sign-in records, rate limiting, lockouts, audit logging'\n- purpose: Diagnostics and reliability\n  text: 'Diagnosing faults and improving reliability: logs and performance measurements'\n- purpose: Marketing emails\n  text: Marketing\
  \ emails Your consent, which you can withdraw at any time in Settings\nretention:\n- scope: Account data\n  period: While your account is open\n  text: Account data While your account is open\n- scope: Leads and profiles\n  period: 730 days by default\n  text: Leads and profiles 730 days by default\n- scope: Application logs\n  period: 30 days\n  text: Application logs 30 days\n- scope: Audit logs\n  period: 2 years\n  text: Audit logs 2 years\nresidency:\n- region: United States\n  text: Scrappy is hosted in the United States\ntransfers:\n- mechanism: other\n  text: we do not yet have Standard Contractual Clauses or a Data Privacy Framework certification in place.\nsubprocessors:\n  url: https://scrappy.gg/subprocessors\n  text: The full list, with what each provider receives, is on the subprocessors page\ndpa:\n  available: null\n  url: null\n  text: A data processing agreement including transfer terms is being prepared and will be available on request.\ndeletion:\n  route: Settings\
  \ > Privacy\n  text: delete your account from Settings > Privacy. There is a 30-day grace period during which you can cancel\nrights:\n- right: access\n  text: you may have the right to access, correct, delete, export or restrict the use of your personal data\n- right: object\n  text: to object to its use, and to withdraw consent\n- right: complain\n  text: You also have the right to complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/scrappy-gg/privacy/scrappy-gg-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Scrappy.gg's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Browser
- Automation
- Lead Generation
- AI Agents
- Web Scraping
- Company
---
