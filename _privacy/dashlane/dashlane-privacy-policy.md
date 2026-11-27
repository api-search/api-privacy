---
api_specs:
- filename: dashlane-teams-api-openapi.yml
  format: yaml
  label: Dashlane Teams API
  slug: dashlane-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dashlane/openapi/dashlane-teams-api-openapi.yml
- filename: dashlane-time-api-openapi.yml
  format: yaml
  label: Dashlane Time API
  slug: dashlane-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dashlane/openapi/dashlane-time-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: financial
    text: We may store partial payment information (such as the expiration date and last four digits of a credit card) for tax compliance and user support purposes.
  - category: location
    text: We collect the originating IP for all Users and what IP addresses the user accesses the Services from.
  - category: device
    text: operating system name and version, device identifier, browser type, and browser or device language.
  - category: communication
    text: We record sales, support, and user research calls, which may be audio only or audio and video, with affirmative consent.
  deletion:
    route: Delete your Account via the Apps; personal data erased automatically
    text: If you delete your Account, all Personal Data will automatically be erased within 30 days of the date of deletion.
  dpa:
    available: true
    text: we have GDPR-compliant Data Processing Addenda in place among our EU and US Affiliates
    url: null
  purposes:
  - purpose: Service delivery and operation
    text: Dashlane uses Personal Data to provide and promote the Services and respond to your requests
  - purpose: Marketing and advertising
    text: We and our third-party advertising partners may collect and use your personal data for marketing and advertising purposes
  - purpose: Compliance and protection
    text: comply with applicable laws, lawful requests, and legal process
  residency:
  - region: United States
    text: Certain Affiliates are in the United States, where privacy and related laws are not deemed adequate by European regulators
  retention:
  - period: 30 days
    scope: Registration Data
    text: We store Registration Data for up to 30 days after Account deletion.
  - period: 45 days
    scope: IP activity logs
    text: We retain 45 days of IP activity for all users in our production logs.
  - period: 13 months
    scope: Secured Data
    text: Secured Data is also deleted as part of the automatic deletion of accounts that have been inactive for more than 13 months.
  rights:
  - right: Withdraw consent
    text: You may withdraw your consent to our processing of your Personal Data, in whole or in part
  - right: Access
    text: You may access the Personal Data we hold about you at any time via your Account or by contacting us directly.
  - right: Modification
    text: You may modify incorrect or outdated Personal Data we hold about you at any time via your Account or by contacting us directly.
  - right: Erasure
    text: you can request that we erase it.
  - right: Portability
    text: You may request a copy of your Personal Data and may always move it to other entities as you choose.
  - right: Opt-out of targeted advertising
    text: You can opt out of the use of your personal information for targeted advertising purposes.
  role:
    text: where we are acting as a controller, the controller is Dashlane SAS of 21 Rue Pierre Picard, 75018 Paris, France.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Dashlane will never sell your Personal Data
  subprocessors:
    text: The Subprocessors List discloses what service providers have access to Personal Data in connection with our delivery of the Services.
    url: null
  transfers:
  - mechanism: other
    text: we have GDPR-compliant Data Processing Addenda in place among our EU and US Affiliates
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dashlane
provenance_date: '2026-11-09'
provider_name: Dashlane
provider_slug: dashlane
slug: dashlane-privacy-policy
source_date: '2026-11-09'
source_filename: dashlane-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.dashlane.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dashlane\naid: dashlane\nurl: https://www.dashlane.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: where we are acting as a controller, the controller is Dashlane SAS of 21 Rue Pierre Picard, 75018 Paris,\n    France.\ndata_categories:\n- category: financial\n  text: We may store partial payment information (such as the expiration date and last four digits of a credit card)\n    for tax compliance and user support purposes.\n- category: location\n  text: We collect the originating IP for all Users and what IP addresses the user accesses the Services from.\n- category: device\n  text:\
  \ operating system name and version, device identifier, browser type, and browser or device language.\n- category: communication\n  text: We record sales, support, and user research calls, which may be audio only or audio and video, with affirmative\n    consent.\npurposes:\n- purpose: Service delivery and operation\n  text: Dashlane uses Personal Data to provide and promote the Services and respond to your requests\n- purpose: Marketing and advertising\n  text: We and our third-party advertising partners may collect and use your personal data for marketing and advertising\n    purposes\n- purpose: Compliance and protection\n  text: comply with applicable laws, lawful requests, and legal process\nretention:\n- scope: Registration Data\n  period: 30 days\n  text: We store Registration Data for up to 30 days after Account deletion.\n- scope: IP activity logs\n  period: 45 days\n  text: We retain 45 days of IP activity for all users in our production logs.\n- scope: Secured Data\n  period:\
  \ 13 months\n  text: Secured Data is also deleted as part of the automatic deletion of accounts that have been inactive for more\n    than 13 months.\nresidency:\n- region: United States\n  text: Certain Affiliates are in the United States, where privacy and related laws are not deemed adequate by European\n    regulators\ntransfers:\n- mechanism: other\n  text: we have GDPR-compliant Data Processing Addenda in place among our EU and US Affiliates\nsubprocessors:\n  url: null\n  text: The Subprocessors List discloses what service providers have access to Personal Data in connection with\n    our delivery of the Services.\ndpa:\n  available: true\n  url: null\n  text: we have GDPR-compliant Data Processing Addenda in place among our EU and US Affiliates\ndeletion:\n  route: Delete your Account via the Apps; personal data erased automatically\n  text: If you delete your Account, all Personal Data will automatically be erased within 30 days of the date of\n    deletion.\nrights:\n- right:\
  \ Withdraw consent\n  text: You may withdraw your consent to our processing of your Personal Data, in whole or in part\n- right: Access\n  text: You may access the Personal Data we hold about you at any time via your Account or by contacting us directly.\n- right: Modification\n  text: You may modify incorrect or outdated Personal Data we hold about you at any time via your Account or by\n    contacting us directly.\n- right: Erasure\n  text: you can request that we erase it.\n- right: Portability\n  text: You may request a copy of your Personal Data and may always move it to other entities as you choose.\n- right: Opt-out of targeted advertising\n  text: You can opt out of the use of your personal information for targeted advertising purposes.\nsale_or_sharing:\n  stance: prohibited\n  text: Dashlane will never sell your Personal Data\n"
source_yaml_url: https://artifacts.apis.io/dashlane/privacy/dashlane-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Dashlane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Password Management
- Identity
- Security
- Credential Monitoring
- Secrets Management
---
