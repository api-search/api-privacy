---
api_specs:
- filename: spruce-health-contact-fields-api-openapi.yml
  format: yaml
  label: Spruce Health Contact Fields API
  slug: spruce-health-contact-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-contact-fields-api-openapi.yml
- filename: spruce-health-contact-tags-api-openapi.yml
  format: yaml
  label: Spruce Health Contact Tags API
  slug: spruce-health-contact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-contact-tags-api-openapi.yml
- filename: spruce-health-contacts-api-openapi.yml
  format: yaml
  label: Spruce Health Contacts API
  slug: spruce-health-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-contacts-api-openapi.yml
- filename: spruce-health-conversation-item-api-openapi.yml
  format: yaml
  label: Spruce Health Conversation Item API
  slug: spruce-health-conversation-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-conversation-item-api-openapi.yml
- filename: spruce-health-conversation-tags-api-openapi.yml
  format: yaml
  label: Spruce Health Conversation Tags API
  slug: spruce-health-conversation-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-conversation-tags-api-openapi.yml
- filename: spruce-health-conversations-api-openapi.yml
  format: yaml
  label: Spruce Health Conversations API
  slug: spruce-health-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-conversations-api-openapi.yml
- filename: spruce-health-internal-endpoints-api-openapi.yml
  format: yaml
  label: Spruce Health Internal Endpoints API
  slug: spruce-health-internal-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-internal-endpoints-api-openapi.yml
- filename: spruce-health-media-api-openapi.yml
  format: yaml
  label: Spruce Health Media API
  slug: spruce-health-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-media-api-openapi.yml
- filename: spruce-health-organization-api-openapi.yml
  format: yaml
  label: Spruce Health Organization API
  slug: spruce-health-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-organization-api-openapi.yml
- filename: spruce-health-phone-lines-api-openapi.yml
  format: yaml
  label: Spruce Health Phone Lines API
  slug: spruce-health-phone-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-phone-lines-api-openapi.yml
- filename: spruce-health-saved-messages-api-openapi.yml
  format: yaml
  label: Spruce Health Saved Messages API
  slug: spruce-health-saved-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-saved-messages-api-openapi.yml
- filename: spruce-health-scheduled-messages-api-openapi.yml
  format: yaml
  label: Spruce Health Scheduled Messages API
  slug: spruce-health-scheduled-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-scheduled-messages-api-openapi.yml
- filename: spruce-health-teams-api-openapi.yml
  format: yaml
  label: Spruce Health Teams API
  slug: spruce-health-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-teams-api-openapi.yml
- filename: spruce-health-transcription-api-openapi.yml
  format: yaml
  label: Spruce Health Transcription API
  slug: spruce-health-transcription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-transcription-api-openapi.yml
- filename: spruce-health-webhooks-api-openapi.yml
  format: yaml
  label: Spruce Health Webhooks API
  slug: spruce-health-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-webhooks-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information by which you may be personally identified, such as name, mailing address, email address, telephone number and account information
  - category: health
    text: Clinical or patient information or data, including PHI or other health-related information.
  - category: financial
    text: payment card information
  - category: location
    text: Details of your visits to our Platform, including traffic data, location data, logs
  - category: device
    text: Information about your computer and Internet connection, including your IP address, operating system, host domain, and browser type.
  - category: behavioral
    text: Your search queries on the Platform.
  deletion:
    route: Notify Spruce of deletion preference
    text: You may choose to have such data deleted by notifying us of this preference.
  dpa:
    available: true
    text: we process PHI in accordance with business associate agreements that we enter into with Providers
    url: null
  purposes:
  - purpose: Payment processing and transactions
    text: To complete any registration or other transactions or actions you request online, such as payment processing
  - purpose: Treatment, payment, or health care operations
    text: For treatment, payment, or health care operations purposes.
  - purpose: De-identified statistics
    text: To create de-identified information that cannot be used to personally identify you, such as aggregate statistics relating to the use of our service.
  - purpose: Advertising effectiveness
    text: To measure or understand the effectiveness of communications (including advertising) that we send to you and others
  retention:
  - period: indefinitely
    scope: Account information
    text: Some data is kept indefinitely, such as account information.
  - period: null
    scope: Connection data in server logs
    text: Some data is deleted or anonymized automatically after a set period of time, such as connection data in server logs.
  rights:
  - right: Information
    text: You may have the right to obtain information about how we collect, use, and share your personal information.
  - right: Access, correction, and deletion
    text: You may also have the right to request access to your personal information, to correct personal information that is out of date or inaccurate, or to delete personal information that is no longer needed for a permitted purpose.
  role:
    text: we collect, use and disclose Patient information only in accordance with our agreements with Providers as a service provider to such Providers
    value: processor
  sale_or_sharing:
    stance: conditional
    text: We share information with advertising networks and analytics partners to support our interest-based advertising, which may qualify as a sale or sharing of personal information, or targeted advertising, under applicable law.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Spruce Health
provenance_date: '2026-11-10'
provider_name: Spruce Health
provider_slug: spruce-health
slug: spruce-health-privacy-policy
source_date: '2026-11-10'
source_filename: spruce-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sprucehealth.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Spruce Health\naid: spruce-health\nurl: https://sprucehealth.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: we collect, use and disclose Patient information only in accordance with our agreements with Providers as\n    a service provider to such Providers\ndata_categories:\n- category: identifying\n  text: Information by which you may be personally identified, such as name, mailing address, email address, telephone\n    number and account information\n- category: health\n  text: Clinical or patient information or data, including PHI or other health-related information.\n- category:\
  \ financial\n  text: payment card information\n- category: location\n  text: Details of your visits to our Platform, including traffic data, location data, logs\n- category: device\n  text: Information about your computer and Internet connection, including your IP address, operating system, host\n    domain, and browser type.\n- category: behavioral\n  text: Your search queries on the Platform.\npurposes:\n- purpose: Payment processing and transactions\n  text: To complete any registration or other transactions or actions you request online, such as payment processing\n- purpose: Treatment, payment, or health care operations\n  text: For treatment, payment, or health care operations purposes.\n- purpose: De-identified statistics\n  text: To create de-identified information that cannot be used to personally identify you, such as aggregate statistics\n    relating to the use of our service.\n- purpose: Advertising effectiveness\n  text: To measure or understand the effectiveness of communications\
  \ (including advertising) that we send to you\n    and others\nretention:\n- scope: Account information\n  period: indefinitely\n  text: Some data is kept indefinitely, such as account information.\n- scope: Connection data in server logs\n  period: null\n  text: Some data is deleted or anonymized automatically after a set period of time, such as connection data in\n    server logs.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: we process PHI in accordance with business associate agreements that we enter into with Providers\ndeletion:\n  route: Notify Spruce of deletion preference\n  text: You may choose to have such data deleted by notifying us of this preference.\nrights:\n- right: Information\n  text: You may have the right to obtain information about how we collect, use, and share your personal information.\n- right: Access, correction, and deletion\n  text: You may also have the right to request access to your\
  \ personal information, to correct personal information\n    that is out of date or inaccurate, or to delete personal information that is no longer needed for a permitted\n    purpose.\nsale_or_sharing:\n  stance: conditional\n  text: We share information with advertising networks and analytics partners to support our interest-based advertising,\n    which may qualify as a sale or sharing of personal information, or targeted advertising, under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/spruce-health/privacy/spruce-health-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Spruce Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- HIPAA
- Communications
- Secure Messaging
- Telehealth
- Patient Engagement
- Contacts
- Conversations
- Messaging
- SMS
- Voice
- VoIP
- Fax
- Video
- Webhook
- Scheduling
- Transcription
- EHR Integration
- Compliance
---
