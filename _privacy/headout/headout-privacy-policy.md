---
api_specs:
- filename: headout-booking-api-openapi.yml
  format: yaml
  label: HeadOut Booking API
  slug: headout-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-booking-api-openapi.yml
- filename: headout-categories-api-openapi.yml
  format: yaml
  label: HeadOut Categories API
  slug: headout-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-categories-api-openapi.yml
- filename: headout-collections-api-openapi.yml
  format: yaml
  label: HeadOut Collections API
  slug: headout-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-collections-api-openapi.yml
- filename: headout-inventory-api-openapi.yml
  format: yaml
  label: HeadOut Inventory API
  slug: headout-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-inventory-api-openapi.yml
- filename: headout-products-api-openapi.yml
  format: yaml
  label: HeadOut Products API
  slug: headout-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-products-api-openapi.yml
- filename: headout-subcategories-api-openapi.yml
  format: yaml
  label: HeadOut Subcategories API
  slug: headout-subcategories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/headout/openapi/headout-subcategories-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, social security number, date and place of birth, phone number, address, email ID, payment/card details etc.
  - category: device
    text: Device information such as the browser used for accessing the Headout Platform, the device used for accessing the Headout Platform, operating system, application version number etc.
  - category: location
    text: 'We may collect precise or approximate location data in order to: (a) show You relevant available experiences, services, or events near Your current location'
  - category: behavioral
    text: Behavioural information i.e. how You are accessing Headout Platform, what different sections of the Headout Platform You access, duration of Your access etc.
  - category: communication
    text: Microphone (including audio recording)- Access to the microphone (including audio recording functionality) is required solely to enable interactive audio-guide experiences
  deletion:
    route: email privacy@headout.com
    text: If You have a data privacy request, such as accessing or deleting your data, please reach out to us at privacy@headout.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: booking
    text: 'For booking purposes: We use Your Personal Information, which may include Your and Your fellow travelers'' name, email ID, payment details etc., to ensure that all bookings made on Headout Platform are concluded and enjoyed in satisfactory manner.'
  - purpose: marketing
    text: 'For marketing purposes: We do run marketing and promotional campaigns along with the Service Providers and/or any other third parties'
  - purpose: security
    text: To ensure the security of Our IT systems, for example, to defend against specific attacks on Our systems and to recognize attack patterns
  residency:
  - region: USA or other countries
    text: Your Personal Information is stored in personnel files or within the electronic records (on servers in the USA or other countries) of Headout.
  retention:
  - period: For as long as the User remains a customer
    scope: Booking data, check-in data, special requests data
    text: Booking data, check-in data, special requests data For as long as the User remains a customer
  - period: 10 years or such longer period as may be required
    scope: System logs
    text: System logs 10 years or such longer period as may be required
  - period: Expiry of contract or for a period of 7 years, whichever is later.
    scope: Information pertaining to Supply Partners or any other third party that commercially dealt with Us
    text: Expiry of contract or for a period of 7 years, whichever is later.
  rights:
  - right: Right to Access Information
    text: Right to Access Information- You have the right to request, at any time, a complete summary of the Personal Information we hold about You.
  - right: Right to Erasure
    text: Right to Erasure- You are entitled to ask Us to delete your personal data when it is no longer necessary for its original purpose, has been unlawfully processed, or where an applicable legal requirement for erasure exists.
  - right: Right to Object
    text: Right to Object- You may object, at any time and on grounds specific to Your situation, to the processing of Your personal data.
  - right: Right to Data Portability
    text: Right to Data Portability- You have the right to receive the Personal Information You have provided to Us in a structured, commonly used, machine-readable format
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent this information to anyone nor do We share Your information with any third party, unless otherwise provided under the applicable law and specified in this Privacy Policy
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We share Your information with various third parties, including parties in other countries outside the United States of America
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HeadOut
provenance_date: '2026-11-09'
provider_name: HeadOut
provider_slug: headout
slug: headout-privacy-policy
source_date: '2026-11-09'
source_filename: headout-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.headout.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HeadOut\naid: headout\nurl: https://www.headout.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name, social security number, date and place of birth, phone number, address, email ID, payment/card details\n    etc.\n- category: device\n  text: Device information such as the browser used for accessing the Headout Platform, the device used for accessing\n    the Headout Platform, operating system, application version number etc.\n- category: location\n  text: 'We may collect precise or approximate location data in order\
  \ to: (a) show You relevant available experiences,\n    services, or events near Your current location'\n- category: behavioral\n  text: Behavioural information i.e. how You are accessing Headout Platform, what different sections of the Headout\n    Platform You access, duration of Your access etc.\n- category: communication\n  text: Microphone (including audio recording)- Access to the microphone (including audio recording functionality)\n    is required solely to enable interactive audio-guide experiences\npurposes:\n- purpose: booking\n  text: 'For booking purposes: We use Your Personal Information, which may include Your and Your fellow travelers''\n    name, email ID, payment details etc., to ensure that all bookings made on Headout Platform are concluded and\n    enjoyed in satisfactory manner.'\n- purpose: marketing\n  text: 'For marketing purposes: We do run marketing and promotional campaigns along with the Service Providers\n    and/or any other third parties'\n- purpose: security\n\
  \  text: To ensure the security of Our IT systems, for example, to defend against specific attacks on Our systems\n    and to recognize attack patterns\nretention:\n- scope: Booking data, check-in data, special requests data\n  period: For as long as the User remains a customer\n  text: Booking data, check-in data, special requests data For as long as the User remains a customer\n- scope: System logs\n  period: 10 years or such longer period as may be required\n  text: System logs 10 years or such longer period as may be required\n- scope: Information pertaining to Supply Partners or any other third party that commercially dealt with Us\n  period: Expiry of contract or for a period of 7 years, whichever is later.\n  text: Expiry of contract or for a period of 7 years, whichever is later.\nresidency:\n- region: USA or other countries\n  text: Your Personal Information is stored in personnel files or within the electronic records (on servers in the\n    USA or other countries) of Headout.\n\
  transfers:\n- mechanism: other\n  text: We share Your information with various third parties, including parties in other countries outside the United\n    States of America\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@headout.com\n  text: If You have a data privacy request, such as accessing or deleting your data, please reach out to us at privacy@headout.com.\nrights:\n- right: Right to Access Information\n  text: Right to Access Information- You have the right to request, at any time, a complete summary of the Personal\n    Information we hold about You.\n- right: Right to Erasure\n  text: Right to Erasure- You are entitled to ask Us to delete your personal data when it is no longer necessary\n    for its original purpose, has been unlawfully processed, or where an applicable legal requirement for erasure\n    exists.\n- right: Right to Object\n  text: Right to Object- You may object, at any time and\
  \ on grounds specific to Your situation, to the processing\n    of Your personal data.\n- right: Right to Data Portability\n  text: Right to Data Portability- You have the right to receive the Personal Information You have provided to Us\n    in a structured, commonly used, machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent this information to anyone nor do We share Your information with any third party,\n    unless otherwise provided under the applicable law and specified in this Privacy Policy\n"
source_yaml_url: https://artifacts.apis.io/headout/privacy/headout-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from HeadOut's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Tours and Activities
- Experience
- Attractions
- Ticketing
- Booking
- Marketplace
- Partner API
- Affiliates
- Event
---
