---
api_specs:
- filename: aignostics-public-api-openapi.yml
  format: yaml
  label: Aignostics Public API
  slug: aignostics-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aignostics/openapi/aignostics-public-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may collect or ask you to provide us with information that can be used to identify you personally, such as your name or email
  - category: device
    text: your device functionality (e.g., browser, operating system, hardware, mobile network information)
  - category: location
    text: 'Location data (via GeoIP): city, country, continent, postal code, approximate latitude/longitude, time zone, and region/state.'
  - category: behavioral
    text: 'Navigation data: full URLs visited within PathoSearch, referrer/referring domain, pages visited, session duration, and bounce status.'
  deletion:
    route: contact support channels or datenschutz@aignostics.com
    text: If you would like this data deleted, you can request this at any time by contacting us through our support channels, and we will delete it promptly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: newsletter delivery
    text: For the delivery of our newsletter, we collect personal data that is transmitted to us via an input form.
  - purpose: service provision and account management
    text: to process your registration with the Portal platform, including verifying your information is active and valid
  - purpose: service monitoring and improvement
    text: We use Sentry and PostHog to monitor performance, troubleshoot issues, and understand usage.
  retention:
  - period: null
    scope: Portal platform usage information
    text: Portal platform usage information will be deleted as soon as it is no longer necessary for the purpose of its collection.
  - period: 30 days
    scope: Logs active storage
    text: 'Active Storage: All logs remain readily accessible for a minimum of 30 days'
  - period: 2 years
    scope: Logs archival storage
    text: 'Archival Storage: All logs are securely archived for a minimum of 2 years'
  - period: 90 days
    scope: Sentry logs
    text: Sentry's and PostHog's retention policies (90 days and 2 years, respectively)
  - period: null
    scope: Newsletter data
    text: The data will only be processed in this context for as long as the corresponding consent is given. After that, it will be deleted.
  rights:
  - right: access
    text: Information about your stored data and itsprocessing (Article 15 GDPR)
  - right: correction
    text: Correction of incorrect personal data (Article 16GDPR)
  - right: deletion
    text: Deletion of your data stored by us (Article 17 GDPR)
  - right: restriction
    text: Restriction of data processing if we are not yet allowed to delete your data due to legal obligations (Article 18 GDPR)
  - right: objection
    text: Objection to the processing of your data by us (Article 21 GDPR)
  - right: portability
    text: Data transferability if you have consented to data processing or have concluded a contract with us (Art. 20 GDPR)
  - right: withdraw consent
    text: If you have given us your consent, you can revoke this at any time with effect for the future.
  - right: complain to supervisory authority
    text: You can contact a supervisory authority at any time with a complaint
  role:
    text: 'The person responsible within the meaning of the data protection laws, in particular the EU General Data Protection Regulation (GDPR), is: Aignostics GmbH'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aignostics
provenance_date: '2026-11-09'
provider_name: Aignostics
provider_slug: aignostics
slug: aignostics-privacy-policy
source_date: '2026-11-09'
source_filename: aignostics-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aignostics.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aignostics\naid: aignostics\nurl: https://www.aignostics.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The person responsible within the meaning of the data protection laws, in particular the EU General Data\n    Protection Regulation (GDPR), is: Aignostics GmbH'\ndata_categories:\n- category: identifying\n  text: we may collect or ask you to provide us with information that can be used to identify you personally, such\n    as your name or email\n- category: device\n  text: your device functionality (e.g., browser, operating system, hardware, mobile network information)\n\
  - category: location\n  text: 'Location data (via GeoIP): city, country, continent, postal code, approximate latitude/longitude, time\n    zone, and region/state.'\n- category: behavioral\n  text: 'Navigation data: full URLs visited within PathoSearch, referrer/referring domain, pages visited, session\n    duration, and bounce status.'\npurposes:\n- purpose: newsletter delivery\n  text: For the delivery of our newsletter, we collect personal data that is transmitted to us via an input form.\n- purpose: service provision and account management\n  text: to process your registration with the Portal platform, including verifying your information is active and\n    valid\n- purpose: service monitoring and improvement\n  text: We use Sentry and PostHog to monitor performance, troubleshoot issues, and understand usage.\nretention:\n- scope: Portal platform usage information\n  period: null\n  text: Portal platform usage information will be deleted as soon as it is no longer necessary for the\
  \ purpose of\n    its collection.\n- scope: Logs active storage\n  period: 30 days\n  text: 'Active Storage: All logs remain readily accessible for a minimum of 30 days'\n- scope: Logs archival storage\n  period: 2 years\n  text: 'Archival Storage: All logs are securely archived for a minimum of 2 years'\n- scope: Sentry logs\n  period: 90 days\n  text: Sentry's and PostHog's retention policies (90 days and 2 years, respectively)\n- scope: Newsletter data\n  period: null\n  text: The data will only be processed in this context for as long as the corresponding consent is given. After\n    that, it will be deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support channels or datenschutz@aignostics.com\n  text: If you would like this data deleted, you can request this at any time by contacting us through our support\n    channels, and we will delete it promptly.\nrights:\n- right:\
  \ access\n  text: Information about your stored data and itsprocessing (Article 15 GDPR)\n- right: correction\n  text: Correction of incorrect personal data (Article 16GDPR)\n- right: deletion\n  text: Deletion of your data stored by us (Article 17 GDPR)\n- right: restriction\n  text: Restriction of data processing if we are not yet allowed to delete your data due to legal obligations (Article\n    18 GDPR)\n- right: objection\n  text: Objection to the processing of your data by us (Article 21 GDPR)\n- right: portability\n  text: Data transferability if you have consented to data processing or have concluded a contract with us (Art.\n    20 GDPR)\n- right: withdraw consent\n  text: If you have given us your consent, you can revoke this at any time with effect for the future.\n- right: complain to supervisory authority\n  text: You can contact a supervisory authority at any time with a complaint\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aignostics/privacy/aignostics-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 22 quoted statements, read from Aignostics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Health
- Healthcare
- Life Sciences
- Pathology
- Medical Imaging
- Digital Pathology
- Oncology
- Biotechnology
- Research
- Germany
---
