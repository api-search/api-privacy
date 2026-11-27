---
api_specs:
- filename: easee-account-api-openapi.yml
  format: yaml
  label: Easee Account API
  slug: easee-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-account-api-openapi.yml
- filename: easee-authorizecharging-api-openapi.yml
  format: yaml
  label: Easee Authorize Charging API
  slug: easee-authorizecharging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-authorizecharging-api-openapi.yml
- filename: easee-charge-session-api-openapi.yml
  format: yaml
  label: Easee Charge Session API
  slug: easee-charge-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-charge-session-api-openapi.yml
- filename: easee-charger-api-openapi.yml
  format: yaml
  label: Easee Charger API
  slug: easee-charger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-charger-api-openapi.yml
- filename: easee-cloud-ocpp-api-openapi.yml
  format: yaml
  label: Easee Cloud OCPP API
  slug: easee-cloud-ocpp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-cloud-ocpp-api-openapi.yml
- filename: easee-daily-schedule-api-openapi.yml
  format: yaml
  label: Easee Daily schedule API
  slug: easee-daily-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-daily-schedule-api-openapi.yml
- filename: easee-delayed-schedule-api-openapi.yml
  format: yaml
  label: Easee Delayed schedule API
  slug: easee-delayed-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-delayed-schedule-api-openapi.yml
- filename: easee-direct-ocpp-for-operators-api-openapi.yml
  format: yaml
  label: Easee Direct OCPP - For Operators API
  slug: easee-direct-ocpp-for-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-direct-ocpp-for-operators-api-openapi.yml
- filename: easee-direct-ocpp-for-users-api-openapi.yml
  format: yaml
  label: Easee Direct OCPP - For Users API
  slug: easee-direct-ocpp-for-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-direct-ocpp-for-users-api-openapi.yml
- filename: easee-easeekeys-api-openapi.yml
  format: yaml
  label: Easee Easee Keys API
  slug: easee-easeekeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-easeekeys-api-openapi.yml
- filename: easee-energy-reporting-api-openapi.yml
  format: yaml
  label: Easee Energy Reporting API
  slug: easee-energy-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-energy-reporting-api-openapi.yml
- filename: easee-equalizer-api-openapi.yml
  format: yaml
  label: Easee Equalizer API
  slug: easee-equalizer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-equalizer-api-openapi.yml
- filename: easee-observations-api-openapi.yml
  format: yaml
  label: Easee Observations API
  slug: easee-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-observations-api-openapi.yml
- filename: easee-resources-api-openapi.yml
  format: yaml
  label: Easee Resources API
  slug: easee-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-resources-api-openapi.yml
- filename: easee-site-api-openapi.yml
  format: yaml
  label: Easee Site API
  slug: easee-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-site-api-openapi.yml
- filename: easee-site-charge-session-api-openapi.yml
  format: yaml
  label: Easee Site Charge Session API
  slug: easee-site-charge-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-site-charge-session-api-openapi.yml
- filename: easee-state-api-openapi.yml
  format: yaml
  label: Easee State API
  slug: easee-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-state-api-openapi.yml
- filename: easee-weekly-schedule-api-openapi.yml
  format: yaml
  label: Easee Weekly schedule API
  slug: easee-weekly-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/easee/openapi/easee-weekly-schedule-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account ID (email address, and/or phone number), serial number, user credential, first and last name, RFID tags, country, or connected devices.
  - category: contact
    text: 'Contact Information: such as name, email address, phone number, postal address (invoicing or delivery), employer or organization details, and other contact information.'
  - category: financial
    text: 'Payment data : such as bank account details, transaction data, credit card or other bank card number.'
  - category: location
    text: 'Technical Data: data about the interaction of your browsers, apps and devices with our services and websites, including IP addresses, browser type and version, time zone and location'
  - category: behavioral
    text: 'Usage data: such as information about how you use our websites, products or services, including aggregated usage patterns.'
  - category: device
    text: 'Charger Activity Data : such as Energy consumption, Charging session information, Temperature readings, Charger status updates, Connection status (online/offline), Firmware version and update history'
  - category: communication
    text: 'Communications data : Your communications or inquires with us, including interactions with customer support, sales team or our social media channels.'
  - category: professional
    text: 'Recruitment data : such as CV, application, references, interview notes, background checks and other information.'
  deletion:
    route: Contact Easee using the contact details in section 1 (dpo@easee.com) to exercise data subject rights
    text: We will also delete most of the personal data we have about you upon your request.
  dpa:
    available: null
    text: The relationship to such suppliers is governed by a data processor agreement, which among other things ensures confidentiality and information security for your personal data.
    url: null
  purposes:
  - purpose: Provide access to charging robots and remote troubleshooting
    text: To provide access to Easee Charging Robots (including without an Easee account); to remotely troubleshoot and fix technical issues; perform firmware and maintenance update
  - purpose: Marketing communication
    text: For marketing communication (including newsletter subscriptions) and social media purposes
  - purpose: Improve products and services
    text: To improve Easee products and services
  - purpose: Statistical and analytical use
    text: To pseudonymize and aggregate data, so that we use them for statistical, research and analytical purposes.
  residency:
  - region: Group companies
    text: Currently, all Easee Group Companies and Subsidiaries are located within the EU/EEA and UK.
  retention:
  - period: four years
    scope: Most personal data
    text: As a main rule, Easee will delete most of your personal data four years after you stop using our products and services or four years after the termination of our contract with you.
  - period: permanently stored
    scope: Charger Activity Data
    text: Charger Activity Data are permanently stored, but these are not associated with any personal data once the relevant user account or Charger Setting and Site Data is deleted.
  - period: unlimited period
    scope: Anonymized information
    text: Easee may keep Anonymized information for unlimited period.
  rights:
  - right: Access
    text: The right to request information from us as to whether and what data we process from you;
  - right: Rectification
    text: The right to have us correct data if it is inaccurate;
  - right: Erasure or restriction
    text: The right to request erasure of data or restrict the processing of your personal data;
  - right: Portability
    text: The right to request that we provide certain personal data in a commonly used electronic format or transfer it to another controller;
  - right: Withdraw consent
    text: The right to withdraw consent, where our processing is based on your consent;
  - right: Complaint
    text: You are also entitled to lodge a complaint with the relevant supervisory authority if you believe that Easee’s processing of your personal data is contrary to applicable data protection laws.
  role:
    text: Easee AS, located at Vassbotnen 23, 4033 Stavanger, Norway is the “data controller” when we collect and process your personal data according to these notice.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: using only companies self-certified under the EU-U.S Data Privacy Framework
  - mechanism: SCC
    text: entering EU Standard Contractual Clauses with the recipients of the data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Easee
provenance_date: '2026-11-09'
provider_name: Easee
provider_slug: easee
slug: easee-privacy-policy
source_date: '2026-11-09'
source_filename: easee-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://easee.com/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Easee\naid: easee\nurl: https://easee.com/en/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Easee AS, located at Vassbotnen 23, 4033 Stavanger, Norway is the “data controller” when we collect and\n    process your personal data according to these notice.\ndata_categories:\n- category: identifying\n  text: Account ID (email address, and/or phone number), serial number, user credential, first and last name, RFID\n    tags, country, or connected devices.\n- category: contact\n  text: 'Contact Information: such as name, email address, phone number, postal address (invoicing or delivery),\n\
  \    employer or organization details, and other contact information.'\n- category: financial\n  text: 'Payment data : such as bank account details, transaction data, credit card or other bank card number.'\n- category: location\n  text: 'Technical Data: data about the interaction of your browsers, apps and devices with our services and websites,\n    including IP addresses, browser type and version, time zone and location'\n- category: behavioral\n  text: 'Usage data: such as information about how you use our websites, products or services, including aggregated\n    usage patterns.'\n- category: device\n  text: 'Charger Activity Data : such as Energy consumption, Charging session information, Temperature readings,\n    Charger status updates, Connection status (online/offline), Firmware version and update history'\n- category: communication\n  text: 'Communications data : Your communications or inquires with us, including interactions with customer support,\n    sales team or our social\
  \ media channels.'\n- category: professional\n  text: 'Recruitment data : such as CV, application, references, interview notes, background checks and other information.'\npurposes:\n- purpose: Provide access to charging robots and remote troubleshooting\n  text: To provide access to Easee Charging Robots (including without an Easee account); to remotely troubleshoot\n    and fix technical issues; perform firmware and maintenance update\n- purpose: Marketing communication\n  text: For marketing communication (including newsletter subscriptions) and social media purposes\n- purpose: Improve products and services\n  text: To improve Easee products and services\n- purpose: Statistical and analytical use\n  text: To pseudonymize and aggregate data, so that we use them for statistical, research and analytical purposes.\nretention:\n- scope: Most personal data\n  period: four years\n  text: As a main rule, Easee will delete most of your personal data four years after you stop using our products\n\
  \    and services or four years after the termination of our contract with you.\n- scope: Charger Activity Data\n  period: permanently stored\n  text: Charger Activity Data are permanently stored, but these are not associated with any personal data once the\n    relevant user account or Charger Setting and Site Data is deleted.\n- scope: Anonymized information\n  period: unlimited period\n  text: Easee may keep Anonymized information for unlimited period.\nresidency:\n- region: Group companies\n  text: Currently, all Easee Group Companies and Subsidiaries are located within the EU/EEA and UK.\ntransfers:\n- mechanism: DPF\n  text: using only companies self-certified under the EU-U.S Data Privacy Framework\n- mechanism: SCC\n  text: entering EU Standard Contractual Clauses with the recipients of the data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: The relationship to such suppliers is governed by a data processor agreement, which among other\
  \ things ensures\n    confidentiality and information security for your personal data.\ndeletion:\n  route: Contact Easee using the contact details in section 1 (dpo@easee.com) to exercise data subject rights\n  text: We will also delete most of the personal data we have about you upon your request.\nrights:\n- right: Access\n  text: The right to request information from us as to whether and what data we process from you;\n- right: Rectification\n  text: The right to have us correct data if it is inaccurate;\n- right: Erasure or restriction\n  text: The right to request erasure of data or restrict the processing of your personal data;\n- right: Portability\n  text: The right to request that we provide certain personal data in a commonly used electronic format or transfer\n    it to another controller;\n- right: Withdraw consent\n  text: The right to withdraw consent, where our processing is based on your consent;\n- right: Complaint\n  text: You are also entitled to lodge a complaint with\
  \ the relevant supervisory authority if you believe that Easee’s\n    processing of your personal data is contrary to applicable data protection laws.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/easee/privacy/easee-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from Easee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Smart Home
- IoT
- Energy
---
