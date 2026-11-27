---
api_specs:
- filename: autohost-accounts-api-openapi.yml
  format: yaml
  label: Autohost Accounts API
  slug: autohost-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-accounts-api-openapi.yml
- filename: autohost-background-check-api-openapi.yml
  format: yaml
  label: Autohost Background Check API
  slug: autohost-background-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-background-check-api-openapi.yml
- filename: autohost-fraud-api-openapi.yml
  format: yaml
  label: Autohost Fraud API
  slug: autohost-fraud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-fraud-api-openapi.yml
- filename: autohost-idcheck-api-openapi.yml
  format: yaml
  label: Autohost Idcheck API
  slug: autohost-idcheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-idcheck-api-openapi.yml
- filename: autohost-listings-api-openapi.yml
  format: yaml
  label: Autohost Listings API
  slug: autohost-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-listings-api-openapi.yml
- filename: autohost-lookup-api-openapi.yml
  format: yaml
  label: Autohost Lookup API
  slug: autohost-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-lookup-api-openapi.yml
- filename: autohost-reservations-api-openapi.yml
  format: yaml
  label: Autohost Reservations API
  slug: autohost-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-reservations-api-openapi.yml
- filename: autohost-validate-api-openapi.yml
  format: yaml
  label: Autohost Validate API
  slug: autohost-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autohost/openapi/autohost-validate-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your full name, used to verify your identity;
  - category: contact
    text: Your email address and phone number, so we can communicate with you and verify your information;
  - category: financial
    text: Payment and banking information, including limited credit card metadata or other forms of payment, for payment verification purposes;
  - category: location
    text: Approximate location information, used to tailor the information in our reports to the client;
  - category: behavioral
    text: IP address, your device ID, information about how you use our site and platforms, such as pages visited, links clicked, text entered, and referring URL, browser, operating system and Internet Service Provider.
  - category: identifying
    text: Photo of the user and their identification or travel document that you upload, used to validate the user's identity.
  deletion:
    route: Email privacy@autohost.ai
    text: Lodge a complaint with your local data protection authorities if you are not satisfied with our response.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website analytics
    text: Analyze the accuracy and effectiveness of the platform;
  residency:
  - region: United States
    text: We store personal data on servers provided by Amazon Web Services, located in the United States.
  retention:
  - period: null
    scope: Personal data generally
    text: we will only retain your personal data for as long as necessary to fulfill the purposes for which it was collected
  rights:
  - right: Access
    text: Access the personal data that we collected about you; we will respond to such request within 30 days
  - right: Correction
    text: Have your personal data corrected if it is inaccurate;
  - right: Challenge practices
    text: Challenge our privacy practices if you have concerns;
  - right: Object
    text: Object when we will seek your consent, if required under applicable legislation
  role:
    text: When we collect and use your personal data, we do so on behalf of our clients and under contractual agreements with and written instructions from our clients.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: 'We do not sell, rent or disclose the personal data that we collect with third parties except in the following circumstances:'
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may transfer your personal data to a third-party service provider operating outside of your jurisdiction of residence.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Autohost
provenance_date: '2026-11-09'
provider_name: Autohost
provider_slug: autohost
slug: autohost-privacy-policy
source_date: '2026-11-09'
source_filename: autohost-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.autohost.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Autohost\naid: autohost\nurl: https://www.autohost.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: When we collect and use your personal data, we do so on behalf of our clients and under contractual agreements\n    with and written instructions from our clients.\ndata_categories:\n- category: identifying\n  text: Your full name, used to verify your identity;\n- category: contact\n  text: Your email address and phone number, so we can communicate with you and verify your information;\n- category: financial\n  text: Payment and banking information, including limited credit card metadata\
  \ or other forms of payment, for payment\n    verification purposes;\n- category: location\n  text: Approximate location information, used to tailor the information in our reports to the client;\n- category: behavioral\n  text: IP address, your device ID, information about how you use our site and platforms, such as pages visited,\n    links clicked, text entered, and referring URL, browser, operating system and Internet Service Provider.\n- category: identifying\n  text: Photo of the user and their identification or travel document that you upload, used to validate the user's\n    identity.\npurposes:\n- purpose: Website analytics\n  text: Analyze the accuracy and effectiveness of the platform;\nretention:\n- scope: Personal data generally\n  period: null\n  text: we will only retain your personal data for as long as necessary to fulfill the purposes for which it was\n    collected\nresidency:\n- region: United States\n  text: We store personal data on servers provided by Amazon Web Services,\
  \ located in the United States.\ntransfers:\n- mechanism: other\n  text: We may transfer your personal data to a third-party service provider operating outside of your jurisdiction\n    of residence.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@autohost.ai\n  text: Lodge a complaint with your local data protection authorities if you are not satisfied with our response.\nrights:\n- right: Access\n  text: Access the personal data that we collected about you; we will respond to such request within 30 days\n- right: Correction\n  text: Have your personal data corrected if it is inaccurate;\n- right: Challenge practices\n  text: Challenge our privacy practices if you have concerns;\n- right: Object\n  text: Object when we will seek your consent, if required under applicable legislation\nsale_or_sharing:\n  stance: prohibited\n  text: 'We do not sell, rent or disclose the personal data that we collect with third\
  \ parties except in the following\n    circumstances:'\n"
source_yaml_url: https://artifacts.apis.io/autohost/privacy/autohost-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Autohost's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity Verification
- Background Checks
- Fraud Prevention
- Hospitality
- Real Estate
---
