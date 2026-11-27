---
api_specs:
- filename: validic-devices-api-openapi.yml
  format: yaml
  label: Validic Devices API
  slug: validic-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-devices-api-openapi.yml
- filename: validic-marketplace-connections-api-openapi.yml
  format: yaml
  label: Validic Marketplace & Connections API
  slug: validic-marketplace-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-marketplace-connections-api-openapi.yml
- filename: validic-observations-data-api-openapi.yml
  format: yaml
  label: Validic Observations & Data API
  slug: validic-observations-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-observations-data-api-openapi.yml
- filename: validic-push-service-api-openapi.yml
  format: yaml
  label: Validic Push Service API
  slug: validic-push-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-push-service-api-openapi.yml
- filename: validic-streaming-api-openapi.yml
  format: yaml
  label: Validic Streaming API
  slug: validic-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-streaming-api-openapi.yml
- filename: validic-users-api-openapi.yml
  format: yaml
  label: Validic Users API
  slug: validic-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-users-api-openapi.yml
- filename: validic-measurements-api-openapi.yml
  format: yaml
  label: Validic Measurements API
  slug: validic-measurements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-measurements-api-openapi.yml
- filename: validic-organizations-api-openapi.yml
  format: yaml
  label: Validic Organizations API
  slug: validic-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-organizations-api-openapi.yml
- filename: validic-streams-api-openapi.yml
  format: yaml
  label: Validic Streams API
  slug: validic-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-streams-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, date of birth, address, e-mail address and/or telephone number
  - category: health
    text: Sensitive Information, which may include personal information related to medical or health conditions.
  - category: behavioral
    text: These services may collect page visits, click patterns, device information, approximate location, referral sources, and behavioral data including session recordings and heat maps.
  - category: location
    text: Validic does not collect precise location data of End Users at any time, either through the Website or the Service.
  - category: device
    text: Site Information . Due to standard internet communications protocols, when End Users visit the Website, Validic automatically receives certain technical information.
  deletion:
    route: Privacy Officer email
    text: To submit a verifiable request for deletion of consumer or marketing information, please contact our Privacy Officer at the email address provided in the Contact Information section.
  dpa:
    available: true
    text: upon request, we will provide Clients with a data processing addendum to govern our compliance therewith.
    url: null
  purposes:
  - purpose: product development and analytics
    text: Validic uses Aggregated User Data for product development, analytics, and to improve products and services.
  - purpose: troubleshooting and service improvement
    text: We collect and process non-identifiable technical log data from our SDKs for troubleshooting, quality assurance, and service improvement.
  - purpose: providing the Service to Clients
    text: We share the Program Data we collect from the Programs only with the respective Client for each End User.
  retention:
  - period: 30 days
    scope: technical diagnostic data
    text: retained for a limited period (typically 30 days)
  - period: typically at least 30 calendar days
    scope: client data after contract termination
    text: We will maintain their data for a retrieval period as specified in our service agreement (typically at least 30 calendar days)
  rights:
  - right: access
    text: Right to access personal data
  - right: correct
    text: Right to correct inaccuracies in personal data
  - right: delete
    text: Right to delete personal data
  - right: opt out of sale
    text: Right to opt out of the sale of personal data
  role:
    text: we are a data processor and not a controller
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: Validic does not sell health data, Program Data, or Client-related information collected through our Services and Applications.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Validic has certified to the U.S. Department of Commerce that it adheres to the EU-U.S. Data Privacy Framework Principles
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Validic
provenance_date: '2026-11-10'
provider_name: Validic
provider_slug: validic
slug: validic-privacy-policy
source_date: '2026-11-10'
source_filename: validic-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://validic.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Validic\naid: validic\nurl: https://validic.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: we are a data processor and not a controller\ndata_categories:\n- category: identifying\n  text: name, date of birth, address, e-mail address and/or telephone number\n- category: health\n  text: Sensitive Information, which may include personal information related to medical or health conditions.\n- category: behavioral\n  text: These services may collect page visits, click patterns, device information, approximate location, referral\n    sources, and behavioral data including session\
  \ recordings and heat maps.\n- category: location\n  text: Validic does not collect precise location data of End Users at any time, either through the Website or the\n    Service.\n- category: device\n  text: Site Information . Due to standard internet communications protocols, when End Users visit the Website,\n    Validic automatically receives certain technical information.\npurposes:\n- purpose: product development and analytics\n  text: Validic uses Aggregated User Data for product development, analytics, and to improve products and services.\n- purpose: troubleshooting and service improvement\n  text: We collect and process non-identifiable technical log data from our SDKs for troubleshooting, quality assurance,\n    and service improvement.\n- purpose: providing the Service to Clients\n  text: We share the Program Data we collect from the Programs only with the respective Client for each End User.\nretention:\n- scope: technical diagnostic data\n  period: 30 days\n  text: retained\
  \ for a limited period (typically 30 days)\n- scope: client data after contract termination\n  period: typically at least 30 calendar days\n  text: We will maintain their data for a retrieval period as specified in our service agreement (typically at least\n    30 calendar days)\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Validic has certified to the U.S. Department of Commerce that it adheres to the EU-U.S. Data Privacy Framework\n    Principles\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: upon request, we will provide Clients with a data processing addendum to govern our compliance therewith.\ndeletion:\n  route: Privacy Officer email\n  text: To submit a verifiable request for deletion of consumer or marketing information, please contact our Privacy\n    Officer at the email address provided in the Contact Information section.\nrights:\n- right: access\n  text: Right to access personal data\n- right: correct\n  text: Right to correct\
  \ inaccuracies in personal data\n- right: delete\n  text: Right to delete personal data\n- right: opt out of sale\n  text: Right to opt out of the sale of personal data\nsale_or_sharing:\n  stance: prohibited\n  text: Validic does not sell health data, Program Data, or Client-related information collected through our Services\n    and Applications.\n"
source_yaml_url: https://artifacts.apis.io/validic/privacy/validic-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Validic's own page on 2026-11-10.
synthetic: false
tags:
- Health Data
- Digital Health
- Wearables
- Remote Patient Monitoring
- Health IoT
- Interoperability
- HIPAA
---
