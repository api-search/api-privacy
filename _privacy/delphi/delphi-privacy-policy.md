---
api_specs:
- filename: delphi-audience-api-openapi.yml
  format: yaml
  label: Delphi Audience API
  slug: delphi-audience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-audience-api-openapi.yml
- filename: delphi-clone-api-openapi.yml
  format: yaml
  label: Delphi Clone API
  slug: delphi-clone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-clone-api-openapi.yml
- filename: delphi-conversations-api-openapi.yml
  format: yaml
  label: Delphi Conversations API
  slug: delphi-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-conversations-api-openapi.yml
- filename: delphi-questions-api-openapi.yml
  format: yaml
  label: Delphi Questions API
  slug: delphi-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-questions-api-openapi.yml
- filename: delphi-search-api-openapi.yml
  format: yaml
  label: Delphi Search API
  slug: delphi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-search-api-openapi.yml
- filename: delphi-tags-api-openapi.yml
  format: yaml
  label: Delphi Tags API
  slug: delphi-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-tags-api-openapi.yml
- filename: delphi-usage-api-openapi.yml
  format: yaml
  label: Delphi Usage API
  slug: delphi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-usage-api-openapi.yml
- filename: delphi-voice-api-openapi.yml
  format: yaml
  label: Delphi Voice API
  slug: delphi-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delphi/openapi/delphi-voice-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Profile or Contact Data such as first and last name, email, username, and phone number.
  - category: financial
    text: Payment Data such as payment card type, last 4 digits of payment card, billing address, billing phone number and billing email.
  - category: device
    text: Device/IP Data such as IP address, device ID, domain server and type of device/operating system/browser used to access the Services.
  - category: behavioral
    text: Web Analytics such as web page interactions and referring webpage/source through which you accessed the Services.
  - category: location
    text: Geolocation Data such as IP-address-based location information.
  - category: biometric
    text: Biometric Data such as faceprints and voiceprints (only of Creators).
  - category: communication
    text: Sensory Data such as photos, videos, or recordings of you and/or your environment.
  - category: health
    text: Other Identifying Information that You Voluntarily Provide in communications with Creator's Digital Mind, which could include health data (e.g., medical conditions, mental health information) and other information about yourself.
  deletion:
    route: Email support@delphi.ai
    text: You can request that we erase some or all of your Personal Data from our systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing, customizing and improving the Services
    text: Providing, Customizing and Improving the Services
  - purpose: Marketing
    text: Showing you advertisements, including interest-based, online behavioral or targeted advertising.
  - purpose: Corresponding with you
    text: Responding to correspondence that we receive from you, contacting you when necessary or requested, and sending you information about Delphi AI or the Services.
  - purpose: Legal compliance and enforcement
    text: fulfilling our legal obligations under applicable law, regulation, court order or other legal process
  residency:
  - region: United States
    text: The Services are hosted and operated in the United States ("U.S.")
  retention:
  - period: as long as you have an account
    scope: Account profile information and credentials
    text: We retain your profile information and credentials for as long as you have an account with us.
  - period: as long as we need to process your purchase or subscription
    scope: Payment data
    text: We retain your payment data for as long as we need to process your purchase or subscription.
  - period: three years following the Creator's last interaction with Delphi
    scope: Biometric information
    text: three years following the Creator's last interaction with Delphi.
  rights:
  - right: Access
    text: 'Access: You may have the right to request confirmation of or access to the Personal Information that we process about you.'
  - right: Deletion
    text: 'Deletion: You may have the right to request that we delete the Personal Information that we have collected about you.'
  - right: Correction
    text: 'Correction: You may have the right to request that we correct any inaccurate Personal Information we have collected about you.'
  - right: Portability
    text: 'Portability: You may have the right to request a copy of your Personal Information in a machine-readable format, to the extent technically feasible.'
  - right: Objection
    text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal Data for certain purposes, such as for direct marketing purposes.'
  role:
    text: Delphi AI will be the controller of your Personal Data processed in connection with the Services.
    value: both
  sale_or_sharing:
    stance: allowed
    text: We sell and/or share your Personal Data, subject to your right to opt-out as described in this section.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: In some circumstances, your Personal Data may be transferred to the U.S. pursuant to a data processing agreement incorporating standard data protection clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Delphi
provenance_date: '2026-11-09'
provider_name: Delphi
provider_slug: delphi
slug: delphi-privacy-policy
source_date: '2026-11-09'
source_filename: delphi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.delphi.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Delphi\naid: delphi\nurl: https://www.delphi.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Delphi AI will be the controller of your Personal Data processed in connection with the Services.\ndata_categories:\n- category: contact\n  text: Profile or Contact Data such as first and last name, email, username, and phone number.\n- category: financial\n  text: Payment Data such as payment card type, last 4 digits of payment card, billing address, billing phone number\n    and billing email.\n- category: device\n  text: Device/IP Data such as IP address, device ID, domain server and type of\
  \ device/operating system/browser\n    used to access the Services.\n- category: behavioral\n  text: Web Analytics such as web page interactions and referring webpage/source through which you accessed the\n    Services.\n- category: location\n  text: Geolocation Data such as IP-address-based location information.\n- category: biometric\n  text: Biometric Data such as faceprints and voiceprints (only of Creators).\n- category: communication\n  text: Sensory Data such as photos, videos, or recordings of you and/or your environment.\n- category: health\n  text: Other Identifying Information that You Voluntarily Provide in communications with Creator's Digital Mind,\n    which could include health data (e.g., medical conditions, mental health information) and other information\n    about yourself.\npurposes:\n- purpose: Providing, customizing and improving the Services\n  text: Providing, Customizing and Improving the Services\n- purpose: Marketing\n  text: Showing you advertisements, including\
  \ interest-based, online behavioral or targeted advertising.\n- purpose: Corresponding with you\n  text: Responding to correspondence that we receive from you, contacting you when necessary or requested, and sending\n    you information about Delphi AI or the Services.\n- purpose: Legal compliance and enforcement\n  text: fulfilling our legal obligations under applicable law, regulation, court order or other legal process\nretention:\n- scope: Account profile information and credentials\n  period: as long as you have an account\n  text: We retain your profile information and credentials for as long as you have an account with us.\n- scope: Payment data\n  period: as long as we need to process your purchase or subscription\n  text: We retain your payment data for as long as we need to process your purchase or subscription.\n- scope: Biometric information\n  period: three years following the Creator's last interaction with Delphi\n  text: three years following the Creator's last interaction\
  \ with Delphi.\nresidency:\n- region: United States\n  text: The Services are hosted and operated in the United States (\"U.S.\")\ntransfers:\n- mechanism: other\n  text: In some circumstances, your Personal Data may be transferred to the U.S. pursuant to a data processing agreement\n    incorporating standard data protection clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@delphi.ai\n  text: You can request that we erase some or all of your Personal Data from our systems.\nrights:\n- right: Access\n  text: 'Access: You may have the right to request confirmation of or access to the Personal Information that we\n    process about you.'\n- right: Deletion\n  text: 'Deletion: You may have the right to request that we delete the Personal Information that we have collected\n    about you.'\n- right: Correction\n  text: 'Correction: You may have the right to request that we correct any inaccurate Personal\
  \ Information we have\n    collected about you.'\n- right: Portability\n  text: 'Portability: You may have the right to request a copy of your Personal Information in a machine-readable\n    format, to the extent technically feasible.'\n- right: Objection\n  text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal\n    Data for certain purposes, such as for direct marketing purposes.'\nsale_or_sharing:\n  stance: allowed\n  text: We sell and/or share your Personal Data, subject to your right to opt-out as described in this section.\n"
source_yaml_url: https://artifacts.apis.io/delphi/privacy/delphi-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Delphi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Clones
- Digital Minds
- Conversational AI
- Voice
- Search
- RAG
- Knowledge Base
- Creator Economy
- Webhook
---
