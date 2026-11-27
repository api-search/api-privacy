---
api_specs:
- filename: koala-io-accounts-api-openapi.yml
  format: yaml
  label: Koala Accounts API
  slug: koala-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-accounts-api-openapi.yml
- filename: koala-io-collection-api-openapi.yml
  format: yaml
  label: Koala Collection API
  slug: koala-io-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-collection-api-openapi.yml
- filename: koala-io-deletion-api-openapi.yml
  format: yaml
  label: Koala Deletion API
  slug: koala-io-deletion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-deletion-api-openapi.yml
- filename: koala-io-sdk-api-openapi.yml
  format: yaml
  label: Koala SDK API
  slug: koala-io-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koala-io/openapi/koala-io-sdk-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: First and last name, Email, Phone number, Avatar/Photo
  - category: location
    text: Location (city, state, and/or country)
  - category: behavioral
    text: Browsing events, Web page interactions, Referring webpage/source through which you accessed the Services
  - category: device
    text: IP address, Type of device/operating system/browser used to access the Services
  - category: professional
    text: Job title, Employer
  - category: other
    text: Social media and similar platform handles, Information about a social media profile, such as number of followers, bio, avatars, etc.
  deletion:
    route: Email request
    text: You have the right to request that we delete the Personal Data that we have collected about you.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing, customizing and improving the Services
    text: Providing, Customizing and Improving the Services
  - purpose: Marketing the Services
    text: Marketing and selling the Services.
  - purpose: Corresponding with you
    text: Corresponding with You
  - purpose: Meeting legal requirements
    text: Meeting Legal Requirements and Enforcing Legal Terms
  residency:
  - region: United States
    text: The Services are hosted and operated in the United States (“U.S.”) through Koala and its service providers
  retention:
  - period: null
    scope: Personal Data with open account
    text: We retain Personal Data about you for as long as you have an open account with us or as otherwise necessary to provide you with our Services.
  rights:
  - right: Access
    text: You have the right to request certain information about our collection and use of your Personal Data over the past 12 months.
  - right: Deletion
    text: You have the right to request that we delete the Personal Data that we have collected about you.
  - right: Rectification
    text: If you believe that any Personal Data we are holding about you is incorrect or incomplete, you can request that we correct or supplement such data.
  - right: Portability
    text: You can ask for a copy of your Personal Data in a machine-readable format.
  - right: Objection
    text: You can contact us to let us know that you object to the further use or disclosure of your Personal Data for certain purposes, such as for direct marketing purposes.
  - right: Restriction of processing
    text: You can ask us to restrict further processing of your Personal Data.
  role:
    text: Koala will be the controller of your Personal Data processed in connection with the Services.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will not sell your Personal Data, and have not done so over the last 12 months.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Koala may transfer, store and process your information to and in the U.S., and possibly other countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Koala
provenance_date: '2026-11-09'
provider_name: Koala
provider_slug: koala-io
slug: koala-io-privacy-policy
source_date: '2026-11-09'
source_filename: koala-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://getkoala.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Koala\naid: koala-io\nurl: https://getkoala.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Koala will be the controller of your Personal Data processed in connection with the Services.\ndata_categories:\n- category: contact\n  text: First and last name, Email, Phone number, Avatar/Photo\n- category: location\n  text: Location (city, state, and/or country)\n- category: behavioral\n  text: Browsing events, Web page interactions, Referring webpage/source through which you accessed the Services\n- category: device\n  text: IP address, Type of device/operating system/browser used to\
  \ access the Services\n- category: professional\n  text: Job title, Employer\n- category: other\n  text: Social media and similar platform handles, Information about a social media profile, such as number of followers,\n    bio, avatars, etc.\npurposes:\n- purpose: Providing, customizing and improving the Services\n  text: Providing, Customizing and Improving the Services\n- purpose: Marketing the Services\n  text: Marketing and selling the Services.\n- purpose: Corresponding with you\n  text: Corresponding with You\n- purpose: Meeting legal requirements\n  text: Meeting Legal Requirements and Enforcing Legal Terms\nretention:\n- scope: Personal Data with open account\n  period: null\n  text: We retain Personal Data about you for as long as you have an open account with us or as otherwise necessary\n    to provide you with our Services.\nresidency:\n- region: United States\n  text: The Services are hosted and operated in the United States (“U.S.”) through Koala and its service providers\n\
  transfers:\n- mechanism: other\n  text: Koala may transfer, store and process your information to and in the U.S., and possibly other countries.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request\n  text: You have the right to request that we delete the Personal Data that we have collected about you.\nrights:\n- right: Access\n  text: You have the right to request certain information about our collection and use of your Personal Data over\n    the past 12 months.\n- right: Deletion\n  text: You have the right to request that we delete the Personal Data that we have collected about you.\n- right: Rectification\n  text: If you believe that any Personal Data we are holding about you is incorrect or incomplete, you can request\n    that we correct or supplement such data.\n- right: Portability\n  text: You can ask for a copy of your Personal Data in a machine-readable format.\n- right: Objection\n  text: You can\
  \ contact us to let us know that you object to the further use or disclosure of your Personal Data\n    for certain purposes, such as for direct marketing purposes.\n- right: Restriction of processing\n  text: You can ask us to restrict further processing of your Personal Data.\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell your Personal Data, and have not done so over the last 12 months.\n"
source_yaml_url: https://artifacts.apis.io/koala-io/privacy/koala-io-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Koala's own page on 2026-11-09.
synthetic: false
tags:
- Buyer Intent
- Visitor Identification
- De-anonymization
- Data Enrichment
- Go-To-Market
- Sales Intelligence
- B2B
- A2A
---
