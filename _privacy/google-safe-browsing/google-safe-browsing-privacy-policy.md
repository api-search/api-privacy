---
api_specs:
- filename: google-safe-browsing-hashes-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Hashes API
  slug: google-safe-browsing-hashes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-hashes-api-openapi.yml
- filename: google-safe-browsing-hashlist-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Hash List API
  slug: google-safe-browsing-hashlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-hashlist-api-openapi.yml
- filename: google-safe-browsing-hashlists-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Hash Lists API
  slug: google-safe-browsing-hashlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-hashlists-api-openapi.yml
- filename: google-safe-browsing-projects-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Projects API
  slug: google-safe-browsing-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-projects-api-openapi.yml
- filename: google-safe-browsing-threatlists-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Threat Lists API
  slug: google-safe-browsing-threatlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-threatlists-api-openapi.yml
- filename: google-safe-browsing-uris-api-openapi.yml
  format: yaml
  label: Google Safe Browsing Uris API
  slug: google-safe-browsing-uris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-uris-api-openapi.yml
- filename: google-safe-browsing-urls-api-openapi.yml
  format: yaml
  label: Google Safe Browsing URLs API
  slug: google-safe-browsing-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-safe-browsing/openapi/google-safe-browsing-urls-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers and similar information such as your name and password, phone number, and address, as well as unique identifiers tied to the browser, application, or device you’re using.
  - category: location
    text: We collect location information when you use our services
  - category: health
    text: Health information if you choose to provide it, such as your medical history
  - category: biometric
    text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development studies.
  - category: behavioral
    text: Internet, network, and other activity information such as your search terms
  - category: communication
    text: we may collect call and message log information like your phone number
  - category: financial
    text: Commercial information such as your payment information and a history of purchases you make on Google’s services.
  deletion:
    route: Export & delete
    text: You can export a copy of your information or delete it from your Google Account at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide our services
    text: We use your information to deliver our services
  - purpose: Protect Google, our users, and the public
    text: We use information to help improve the safety and reliability of our services.
  - purpose: Advertising
    text: Google processes information to provide advertising, including online identifiers, browsing and search activity, and information about your location and interactions with advertisements.
  - purpose: Research and development
    text: we use publicly available information to help train Google’s AI models
  residency:
  - region: outside the country where you live
    text: We maintain servers around the world and your information may be processed on servers located outside of the country where you live.
  retention:
  - period: null
    scope: advertising data in server logs
    text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in server logs.
  - period: until you delete your Google Account
    scope: information about how often you use our services
    text: We keep some data until you delete your Google Account, such as information about how often you use our services.
  rights:
  - right: access, correction, deletion
    text: And they give you the right to access your information, sometimes in a portable format; correct your information; and to request that Google delete that information.
  - right: opt out of profiling and targeted advertising
    text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We also comply with certain legal frameworks relating to the transfer of data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Google Safe Browsing
provenance_date: '2026-11-09'
provider_name: Google Safe Browsing
provider_slug: google-safe-browsing
slug: google-safe-browsing-privacy-policy
source_date: '2026-11-09'
source_filename: google-safe-browsing-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://policies.google.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Google Safe Browsing\naid: google-safe-browsing\nurl: https://policies.google.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifiers and similar information such as your name and password, phone number, and address, as well as\n    unique identifiers tied to the browser, application, or device you’re using.\n- category: location\n  text: We collect location information when you use our services\n- category: health\n  text: Health information if you choose to provide it, such as your medical history\n\
  - category: biometric\n  text: Biometric information if you choose to provide it, such as fingerprints in Google’s product development\n    studies.\n- category: behavioral\n  text: Internet, network, and other activity information such as your search terms\n- category: communication\n  text: we may collect call and message log information like your phone number\n- category: financial\n  text: Commercial information such as your payment information and a history of purchases you make on Google’s\n    services.\npurposes:\n- purpose: Provide our services\n  text: We use your information to deliver our services\n- purpose: Protect Google, our users, and the public\n  text: We use information to help improve the safety and reliability of our services.\n- purpose: Advertising\n  text: Google processes information to provide advertising, including online identifiers, browsing and search activity,\n    and information about your location and interactions with advertisements.\n- purpose: Research\
  \ and development\n  text: we use publicly available information to help train Google’s AI models\nretention:\n- scope: advertising data in server logs\n  period: null\n  text: Other data is deleted or anonymized automatically after a set period of time, such as advertising data in\n    server logs.\n- scope: information about how often you use our services\n  period: until you delete your Google Account\n  text: We keep some data until you delete your Google Account, such as information about how often you use our\n    services.\nresidency:\n- region: outside the country where you live\n  text: We maintain servers around the world and your information may be processed on servers located outside of\n    the country where you live.\ntransfers:\n- mechanism: other\n  text: We also comply with certain legal frameworks relating to the transfer of data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Export & delete\n  text:\
  \ You can export a copy of your information or delete it from your Google Account at any time\nrights:\n- right: access, correction, deletion\n  text: And they give you the right to access your information, sometimes in a portable format; correct your information;\n    and to request that Google delete that information.\n- right: opt out of profiling and targeted advertising\n  text: Many of these laws also provide the right to opt out of certain forms of profiling and targeted advertising.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-safe-browsing/privacy/google-safe-browsing-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 18 quoted statements, read from Google Safe Browsing's own page on 2026-11-09.
synthetic: false
tags:
- Google
- Malware
- Safe Browsing
- Security
- Threats
- URLs
---
